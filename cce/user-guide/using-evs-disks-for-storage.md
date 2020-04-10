# Using EVS Disks for Storage<a name="cce_01_0044"></a>

To meet data  persistency  requirements,  CCE  allows  EVS  disks to be mounted to  containers. By using EVS disks, you can mount the remote file directory of storage system into a container so that data in the data volume is permanently preserved. Even if the container is deleted, only the attached data volume is deleted. Data in the data volume is still stored in the storage system.

## Application Scenarios<a name="section361117426610"></a>

Currently, EVS disks of three specifications are supported: common I/O, high I/O, and ultra-high I/O.

-   Common I/O: The backend storage is provided by the  SATA  storage media. Common I/O is applicable to scenarios where large capacity and low read/write rate are required, and the volume of transactions is low. Examples include development testing and enterprise office applications.
-   High I/O: The backend storage is provided by the  SAS  storage media. High I/O is applicable to scenarios where relatively high performance, high read/write rate, and real-time data storage are required. Examples include creating file systems and sharing distributed files.
-   Ultra-high I/O: The backend storage is provided by the  SSD  storage media. Super-high I/O is applicable to scenarios where high performance, high read/write rate, and data-intensive applications are required. Examples include  NoSQL, relational database, and  data warehouse  \(such as  Oracle RAC  and  SAP HANA\).

## Constraints<a name="section1274816104391"></a>

-   Shared disks cannot be used to share data among nodes in CCE clusters. As a result, when an EVS disk is used by multiple nodes, data may fail to be processed due to issues such as read/write conflicts and caching conflicts. Therefore, ensure that the EVS disk is used by a single pod when creating a Deployment.
-   Container storage in CCE clusters of Kubernetes 1.13 or later version supports encryption. Currently, E2E encryption is supported only in certain regions.

## Creating an EVS Disk<a name="section46651332174515"></a>

1.  Log in to the CCE console. In the navigation pane, choose  **Resource Management \> Storage**. Click  **Create EVS Disk**.
2.  Configure basic disk information, as shown in  [Table 1](#table20328123218464).

    **Table  1**  Basic disk information

    <a name="table20328123218464"></a>
    <table><thead align="left"><tr id="row533073264618"><th class="cellrowborder" valign="top" width="26%" id="mcps1.2.3.1.1"><p id="p12330932164617"><a name="p12330932164617"></a><a name="p12330932164617"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="74%" id="mcps1.2.3.1.2"><p id="p133306326467"><a name="p133306326467"></a><a name="p133306326467"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row0330113224615"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.3.1.1 "><p id="p18330232154618"><a name="p18330232154618"></a><a name="p18330232154618"></a>* PVC Name</p>
    </td>
    <td class="cellrowborder" valign="top" width="74%" headers="mcps1.2.3.1.2 "><p id="p929111285472"><a name="p929111285472"></a><a name="p929111285472"></a>Name of the PVC. A storage volume is automatically created when a PVC is created. One PVC corresponds to one storage volume. The name of a storage volume is automatically generated when a PVC is created.</p>
    </td>
    </tr>
    <tr id="row20242958195514"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.3.1.1 "><p id="p1243195835517"><a name="p1243195835517"></a><a name="p1243195835517"></a>Cluster Name</p>
    </td>
    <td class="cellrowborder" valign="top" width="74%" headers="mcps1.2.3.1.2 "><p id="p4243258145517"><a name="p4243258145517"></a><a name="p4243258145517"></a>Cluster where the new EVS disk is deployed.</p>
    </td>
    </tr>
    <tr id="row198351838762"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.3.1.1 "><p id="p4837143820613"><a name="p4837143820613"></a><a name="p4837143820613"></a>Namespace</p>
    </td>
    <td class="cellrowborder" valign="top" width="74%" headers="mcps1.2.3.1.2 "><p id="p7837143816615"><a name="p7837143816615"></a><a name="p7837143816615"></a>Select the namespace to be deployed for the EVS disk. If you do not need to select the namespace, retain the default value.</p>
    </td>
    </tr>
    <tr id="row17020817474"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.3.1.1 "><p id="p421381478"><a name="p421381478"></a><a name="p421381478"></a>Volume Capacity</p>
    </td>
    <td class="cellrowborder" valign="top" width="74%" headers="mcps1.2.3.1.2 "><p id="p4766420114910"><a name="p4766420114910"></a><a name="p4766420114910"></a>Capacity of the new EVS disk.</p>
    </td>
    </tr>
    <tr id="row423313555917"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.3.1.1 "><p id="p112371055298"><a name="p112371055298"></a><a name="p112371055298"></a>Access Mode</p>
    </td>
    <td class="cellrowborder" valign="top" width="74%" headers="mcps1.2.3.1.2 "><p id="p1823911552915"><a name="p1823911552915"></a><a name="p1823911552915"></a>Access mode. If this parameter is set to <strong id="b52121853105113"><a name="b52121853105113"></a><a name="b52121853105113"></a>ReadWriteMany</strong>, the volume can be mounted as read-write by multiple nodes.</p>
    </td>
    </tr>
    <tr id="row12462640575"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.3.1.1 "><p id="p1246210401871"><a name="p1246210401871"></a><a name="p1246210401871"></a>AZ</p>
    </td>
    <td class="cellrowborder" valign="top" width="74%" headers="mcps1.2.3.1.2 "><p id="p34621840572"><a name="p34621840572"></a><a name="p34621840572"></a>AZ to which the volume belongs.</p>
    </td>
    </tr>
    <tr id="row894716592271"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.3.1.1 "><p id="p12949559152717"><a name="p12949559152717"></a><a name="p12949559152717"></a>Type</p>
    </td>
    <td class="cellrowborder" valign="top" width="74%" headers="mcps1.2.3.1.2 "><p id="p13949659132716"><a name="p13949659132716"></a><a name="p13949659132716"></a>Type of the new EVS disk.</p>
    </td>
    </tr>
    <tr id="row4690726114316"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.3.1.1 "><p id="p136915265434"><a name="p136915265434"></a><a name="p136915265434"></a>Encryption</p>
    </td>
    <td class="cellrowborder" valign="top" width="74%" headers="mcps1.2.3.1.2 "><div class="p" id="p1433714742818"><a name="p1433714742818"></a><a name="p1433714742818"></a><span class="uicontrol" id="uicontrol1951612227355"><a name="uicontrol1951612227355"></a><a name="uicontrol1951612227355"></a><b>KMS Encryption</b></span> is deselected by default. If <span class="uicontrol" id="uicontrol168318320369"><a name="uicontrol168318320369"></a><a name="uicontrol168318320369"></a><b>KMS Encryption</b></span> is selected, set the following parameters:<a name="ul32358634612"></a><a name="ul32358634612"></a><ul id="ul32358634612"><li><strong id="b197291123125918"><a name="b197291123125918"></a><a name="b197291123125918"></a>Agency Name</strong>: Agencies can be used to assign permissions to trusted accounts or cloud services for a specific period of time. If no agency is created, click <span class="uicontrol" id="uicontrol1314249548"><a name="uicontrol1314249548"></a><a name="uicontrol1314249548"></a><b>Create Agency</b></span>. The agency name <strong id="b325318181392"><a name="b325318181392"></a><a name="b325318181392"></a>EVSAccessKMS</strong> indicates that EVS is granted the permission to access KMS. After EVS is authorized successfully, it can obtain KMS keys to encrypt and decrypt EVS systems.</li><li><strong id="b35963176410"><a name="b35963176410"></a><a name="b35963176410"></a>Key Name</strong>: A secret is a type of resource that holds sensitive data, such as authentication and key information. All content in secrets is user-defined. Secrets can be loaded into containerized applications. For details on how to create a secret, see <a href="https://docs.otc.t-systems.com/en-us/usermanual/ecs/en-us_topic_0014250631.html" target="_blank" rel="noopener noreferrer">Creating a Key Pair</a>.</li><li><strong id="b95534651410"><a name="b95534651410"></a><a name="b95534651410"></a>Key ID</strong>: generated by default.</li></ul>
    </div>
    </td>
    </tr>
    </tbody>
    </table>

3.  Click  **Next**. Review order details, click  **Submit**, and wait until the creation is successful.

    The EVS disk is displayed in the disk list. When its status becomes  **Normal**, the EVS disk is created successfully.

4.  Click the PVC name to view detailed information about the EVS disk.

## Using an EVS Disk<a name="section359413445405"></a>

1.  Create a workload by referring to  [Creating a Deployment](creating-a-deployment.md)  or  [Creating a StatefulSet](creating-a-statefulset.md). After you add a container, expand  **Data Storage**. On the  **Cloud Volume**  tab page, click  **Add Cloud Storage**.
2.  Set the storage type to  **EVS**.

    **Table  2**  Parameters required for mounting EVS disks

    <a name="table9241341114317"></a>
    <table><thead align="left"><tr id="row132473414435"><th class="cellrowborder" valign="top" width="21%" id="mcps1.2.3.1.1"><p id="p1324910414436"><a name="p1324910414436"></a><a name="p1324910414436"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="79%" id="mcps1.2.3.1.2"><p id="p6252164111435"><a name="p6252164111435"></a><a name="p6252164111435"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1425217417438"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.3.1.1 "><p id="p18255194124313"><a name="p18255194124313"></a><a name="p18255194124313"></a>Type</p>
    </td>
    <td class="cellrowborder" valign="top" width="79%" headers="mcps1.2.3.1.2 "><p id="p9499194511284"><a name="p9499194511284"></a><a name="p9499194511284"></a>EVS: The method of using an EVS disk is the same as that of a traditional disk. EVS disks have higher data reliability and I/O throughput and are more user-friendly than traditional hard disks. EVS disks are available for file systems, databases, and system software or workloads that require block storage devices.</p>
    <div class="caution" id="note1965204943010"><a name="note1965204943010"></a><a name="note1965204943010"></a><span class="cautiontitle"> CAUTION: </span><div class="cautionbody"><a name="ul644483475219"></a><a name="ul644483475219"></a><ul id="ul644483475219"><li><strong id="b744433417526"><a name="b744433417526"></a><a name="b744433417526"></a>An EVS disk can be attached to only one pod.</strong></li><li>When you create a StatefulSet and add cloud storage, existing volumes cannot be added to EVS disks.</li><li>EVS disks cannot be mounted across AZs and cannot be used by multiple workloads, multiple pods of the same workload, or multiple tasks.</li></ul>
    </div></div>
    </td>
    </tr>
    <tr id="row226284114432"><td class="cellrowborder" colspan="2" valign="top" headers="mcps1.2.3.1.1 mcps1.2.3.1.2 "><p id="p1126514412436"><a name="p1126514412436"></a><a name="p1126514412436"></a>Allocation Mode</p>
    </td>
    </tr>
    <tr id="row126744194311"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.3.1.1 "><p id="p62691741164312"><a name="p62691741164312"></a><a name="p62691741164312"></a>Manual</p>
    </td>
    <td class="cellrowborder" valign="top" width="79%" headers="mcps1.2.3.1.2 "><p id="p726915413433"><a name="p726915413433"></a><a name="p726915413433"></a>Select a created storage. If no storage is available, follow the prompts to create one.</p>
    </td>
    </tr>
    <tr id="row9299164154310"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.3.1.1 "><p id="p830134116436"><a name="p830134116436"></a><a name="p830134116436"></a>Automatic</p>
    </td>
    <td class="cellrowborder" valign="top" width="79%" headers="mcps1.2.3.1.2 "><p id="p13303124114313"><a name="p13303124114313"></a><a name="p13303124114313"></a>An EVS disk is created automatically. You need to enter the storage capacity.</p>
    <a name="ol1930612417437"></a><a name="ol1930612417437"></a><ol id="ol1930612417437"><li>If you have selected EVS disk as the storage type, select an AZ for creating the EVS disk first.</li><li>Select a storage subtype.<a name="ul14313174113435"></a><a name="ul14313174113435"></a><ul id="ul14313174113435"><li>High I/O: EVS disks that use Serial Attached SCSI (SAS)</li><li>Common I/O: EVS disks that use Serial Advanced Technology Attachment (SATA)</li><li>Ultra-high I/O: EVS disks that use Solid-State Drive (SSD)</li></ul>
    </li><li>Enter the storage capacity in the unit of GB. Ensure that the storage capacity quota is not exceeded; otherwise, EVS creation will fail.</li><li>Set the encryption mode. Select <span class="uicontrol" id="uicontrol1299064913571"><a name="uicontrol1299064913571"></a><a name="uicontrol1299064913571"></a><b>KMS Encryption</b></span> and set the following parameters:<a name="ul194004160312"></a><a name="ul194004160312"></a><ul id="ul194004160312"><li><strong id="b85701017122114"><a name="b85701017122114"></a><a name="b85701017122114"></a>Agency Name</strong>: Agencies can be used to assign permissions to trusted accounts or cloud services for a specific period of time. The agency name <strong id="b5410192014417"><a name="b5410192014417"></a><a name="b5410192014417"></a>EVSAccessKMS</strong> indicates that EVS is granted the permission to access KMS. After EVS is authorized successfully, it can obtain KMS keys to encrypt and decrypt EVS systems.</li><li><strong id="b1368152973"><a name="b1368152973"></a><a name="b1368152973"></a>Key Name</strong>: A secret is a type of resource that holds sensitive data, such as authentication and key information. All content in secrets is user-defined. Secrets can be loaded into containerized applications. For details on how to create a secret, see <a href="https://docs.otc.t-systems.com/en-us/usermanual/ecs/en-us_topic_0014250631.html" target="_blank" rel="noopener noreferrer">Creating a Key Pair</a>.</li><li><strong id="b502222245"><a name="b502222245"></a><a name="b502222245"></a>Key ID</strong>: generated by default.</li></ul>
    </li></ol>
    </td>
    </tr>
    <tr id="row13325134164316"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.3.1.1 "><p id="p1327194134311"><a name="p1327194134311"></a><a name="p1327194134311"></a>Add Container Path</p>
    </td>
    <td class="cellrowborder" valign="top" width="79%" headers="mcps1.2.3.1.2 "><a name="ol153291941194312"></a><a name="ol153291941194312"></a><ol id="ol153291941194312"><li>Click <span class="uicontrol" id="uicontrol62341328144117"><a name="uicontrol62341328144117"></a><a name="uicontrol62341328144117"></a><b>Add Container Path</b></span>.</li><li><strong id="b117998406416"><a name="b117998406416"></a><a name="b117998406416"></a>Container Path</strong>: Enter the container path to which the data volume is mounted.<div class="notice" id="note3336941124310"><a name="note3336941124310"></a><a name="note3336941124310"></a><span class="noticetitle"> NOTICE: </span><div class="noticebody"><a name="ul434084115433"></a><a name="ul434084115433"></a><ul id="ul434084115433"><li>Do not mount a data volume to a system directory such as <strong id="b1521214371291"><a name="b1521214371291"></a><a name="b1521214371291"></a>/</strong> or <strong id="b1521215376295"><a name="b1521215376295"></a><a name="b1521215376295"></a>/var/run</strong>; this action may cause a container error to occur. You are advised to mount the container to an empty directory. If the directory is not empty, ensure that there are no files affecting container startup in the directory. Otherwise, such files will be replaced, resulting in failures to start the container and create the workload.</li><li>When the data volume is mounted to a high-risk directory, you are advised to use a low-permission account to start the container; otherwise, high-risk files on the host machine may be damaged.</li></ul>
    </div></div>
    </li><li>Set permissions.<a name="ul193486419432"></a><a name="ul193486419432"></a><ul id="ul193486419432"><li><strong id="b88323487419"><a name="b88323487419"></a><a name="b88323487419"></a>Read-only</strong>: allows you only to read data volumes in the container path.</li><li><strong id="b1658115115411"><a name="b1658115115411"></a><a name="b1658115115411"></a>Read/Write</strong>: allows you to modify the data volumes in the container path. To prevent data loss, newly written data will not be migrated during container migration.</li></ul>
    </li></ol>
    </td>
    </tr>
    </tbody>
    </table>

3.  Click  **OK**.

## Importing EVS Disks<a name="section18528593167"></a>

CCE allows you to import existing EVS disks.

>![](public_sys-resources/icon-note.gif) **NOTE:**   
>An EVS disk can be imported to only one namespace. If an EVS disk has been imported into a namespace, it is invisible in other namespaces and cannot be imported again.  **If you want to import an EVS disk that has file system \(ext4\) formatted, ensure that no partition has been created for the disk. Otherwise, data may be lost.**  

1.  Log in to the CCE console. In the navigation pane, choose  **Resource** **Management**  \>  **Storage**. On the  **EVS**  tab page, click  **Import**.
2.  Select one or more EVS disks that you want to attach and mount. Then, click  **OK**.

## Unbinding an EVS Disk<a name="section72768527568"></a>

After an EVS disk is successfully created or attached, the EVS disk is automatically bound to the current cluster and cannot be used by other clusters. After the EVS disk is unbound from the cluster, it can be attached and used by other clusters.

If the EVS disk has been mounted to a workload, the EVS disk cannot be unbound from the cluster.

1.  Log in to the CCE console. In the navigation pane, choose  **Resource Management**  \>  **Storage**. In the EVS disk list, click  **Unbind**  next to the target EVS disk.
2.  Confirm the unbinding, and click  **OK**.

## Using kubectl to Create an EVS Disk<a name="section198505107598"></a>

CCE supports the creation of EVS disks in the form of PersistentVolumeClaim \(PVC\).

1.  Configure kubectl. For details, see  [Connecting to a Kubernetes Cluster Using kubectl](connecting-to-a-kubernetes-cluster-using-kubectl.md).
2.  Run the following commands to configure the  **pvc-evs-auto-example.yaml**  file, which is used to create a PVC.

    **touch pvc-evs-auto-example.yaml**

    **vi pvc-evs-auto-example.yaml**

    The following shows an example of creating an EVS disk.

    ```
    apiVersion: v1
    kind: PersistentVolumeClaim
    metadata:
      name: pvc-evs-auto-example
      namespace: default
      annotations:
        volume.beta.kubernetes.io/storage-class: sata
      labels:
        failure-domain.beta.kubernetes.io/region: eu-de
        failure-domain.beta.kubernetes.io/zone: eu-de-01
    spec:
      accessModes:
      - ReadWriteMany
      resources:
        requests:
          storage: 10Gi
    ```

    In this example:

    -   **volume.beta.kubernetes.io/storage-class**: EVS disk type, high I/O \(SAS\), ultra-high I/O \(SSD\), or common I/O \(SATA\).
    -   **failure-domain.beta.kubernetes.io/region**: region where the cluster is located.
    -   **failure-domain.beta.kubernetes.io/zone**: AZ where the EVS volume is created. It must be the same as the AZ planned for the workload.
    -   **storage**: storage capacity in Gi.

3.  Run the following command to create a PVC:

    **kubectl create -f pvc-evs-auto-example.yaml**

    After the command is executed, an EVS disk is created in the partition where the cluster is located. Choose  **Storage**  \>  **EVS**  to view the EVS disk. Alternatively, you can view the EVS disk based on the volume name on the EVS console.


## Using an Existing EVS to Create a PVC<a name="section122885710205"></a>

CCE allows you to use an existing EVS disk to create a PersistentVolume. After a PersistentVolume is created, you can create a PersistentVolumeClaim and bind it to the current PersistentVolume.

1.  Log in to the EVS console, create an EVS disk, and record the VolumeID, capacity, and disk type of the EVS disk.
2.  Configure kubectl. For details, see  [Connecting to a Kubernetes Cluster Using kubectl](connecting-to-a-kubernetes-cluster-using-kubectl.md).
3.  Create a YAML file for creating the PersistentVolume. Assume that the file name is  **pv-evs-example.yaml**.

    **touch pv-evs-example.yaml**

    **vi pv-evs-example.yaml**

    -   Example YAML file for clusters of version 1.9:

        ```
        apiVersion: v1 
        kind: PersistentVolume 
        metadata: 
          labels: 
            failure-domain.beta.kubernetes.io/region: eu-de
            failure-domain.beta.kubernetes.io/zone:  eu-de-01
          name: pv-evs-example 
          namespace: default 
        spec: 
          accessModes: 
          - ReadWriteMany 
          capacity: 
            storage: 10Gi 
          flexVolume: 
            driver: huawei.com/fuxivol 
            fsType: ext4 
            options: 
              fsType: ext4 
              kubernetes.io/namespace: default 
              volumeID: 0992dbda-6340-470e-a74e-4f0db288ed82 
          persistentVolumeReclaimPolicy: Delete 
          storageClassName: sata
        ```

    -   Example YAML file for clusters of version 1.11:

        ```
        apiVersion: v1 
        kind: PersistentVolume 
        metadata: 
          labels: 
            failure-domain.beta.kubernetes.io/region: eu-de
            failure-domain.beta.kubernetes.io/zone:  eu-de-01
          name: pv-evs-example 
        spec: 
          accessModes: 
          - ReadWriteMany 
          capacity: 
            storage: 10Gi 
          flexVolume: 
            driver: huawei.com/fuxivol 
            fsType: ext4 
            options:
              fsType: ext4 
              volumeID: 0992dbda-6340-470e-a74e-4f0db288ed82 
          persistentVolumeReclaimPolicy: Delete 
          storageClassName: sata
        ```

    -   Example YAML file for clusters of version 1.11.7 or later and version 1.13:

        ```
        apiVersion: v1 
        kind: PersistentVolume 
        metadata: 
          labels: 
            failure-domain.beta.kubernetes.io/region: eu-de
            failure-domain.beta.kubernetes.io/zone:  eu-de-01
          name: pv-evs-example 
        spec: 
          accessModes: 
          - ReadWriteMany 
          capacity: 
            storage: 10Gi 
          flexVolume: 
            driver: huawei.com/fuxivol 
            fsType: ext4 
            options:
              disk-mode: SCSI
              fsType: ext4 
              volumeID: 0992dbda-6340-470e-a74e-4f0db288ed82 
          persistentVolumeReclaimPolicy: Delete 
          storageClassName: sata
        ```

    In this example:

    -   **failure-domain.beta.kubernetes.io/region**: region where the EVS disk resides.
    -   **failure-domain.beta.kubernetes.io/zone**: AZ where the EVS volume is created. It must be the same as the AZ planned for the workload.
    -   **driver**: storage driver used to mount the volume. Set the driver to  **huawei.com/fuxivol**  for the EVS volume.
    -   **volumeID**: volume ID of an EVS volume.
    -   **disk-mode**: EVS disk mode. The value is VBD or SCSI. For CCE clusters earlier than v1.11.7, this field is left blank. The default value is VBD. This field is mandatory for virtual clusters of v1.11.7+ and v1.13 that use Linux x86. As the EVS volumes dynamically provisioned for a PVC are SCSI EVS volumes, the disk mode  **SCSI**  is recommended for static PVs. Volumes in the VBD mode can still be used after cluster upgrade.
    -   **storage**: EVS volume capacity in the unit of Gi.
    -   **storageClassName**: EVS disk type. Currently, high I/O \(SAS\), ultra-high I/O \(SSD\), and common I/O \(SATA\) are supported.

4.  Create a PV.

    **kubectl create -f pv-evs-example.yaml**

5.  Create a YAML file for creating the PVC. Assume that the file name is  **pvc-evs-example.yaml**.

    **touch pvc-evs-example.yaml**

    **vi pvc-evs-example.yaml**

    -   The following is a YAML file example for clusters of version 1.9:

        ```
        apiVersion: v1  
        kind: PersistentVolumeClaim  
        metadata:  
          annotations:  
            volume.beta.kubernetes.io/storage-class: sata
            volume.beta.kubernetes.io/storage-provisioner: flexvolume-huawei.com/fuxivol 
          labels: 
            failure-domain.beta.kubernetes.io/region: eu-de
            failure-domain.beta.kubernetes.io/zone: eu-de-01
          name: pvc-evs-example 
          namespace: default  
        spec:  
          accessModes:  
          - ReadWriteMany  
          resources:  
            requests:  
              storage: 10Gi
          volumeName: pv-evs-example
          volumeNamespace: default
        ```

    -   The following is a YAML file example for clusters of 1.11 or later version:

        ```
        apiVersion: v1  
        kind: PersistentVolumeClaim  
        metadata:  
          annotations:  
            volume.beta.kubernetes.io/storage-class: sata
            volume.beta.kubernetes.io/storage-provisioner: flexvolume-huawei.com/fuxivol 
          labels: 
            failure-domain.beta.kubernetes.io/region: eu-de
            failure-domain.beta.kubernetes.io/zone: eu-de-01
          name: pvc-evs-example 
          namespace: default  
        spec:  
          accessModes:  
          - ReadWriteMany  
          resources:  
            requests:  
              storage: 10Gi
          volumeName: pv-evs-example
        ```

    In this example:

    -   **volume.beta.kubernetes.io/storage-class**: Storage type. The value can be  **sas**,  **ssd**, or  **sata**. The value must be the same as the existing PV.
    -   **volume.beta.kubernetes.io/storage-provisioner**: must be set to  **flexvolume-huawei.com/fuxivol**.
    -   **failure-domain.beta.kubernetes.io/region**: region where the cluster is located.
    -   **failure-domain.beta.kubernetes.io/zone**: AZ where the EVS volume is created. It must be the same as the AZ planned for the workload.
    -   **storage**: requested capacity of the PVC, which must be the same as the storage size of the existing PV.
    -   **volumeName**: name of a PV.

6.  Create a PVC.

    **kubectl create -f pvc-evs-example.yaml**

    After the operation is successful, choose  **Resource Management**  \>  **Storage**  to view the created PVC. You can also view the EVS disk by name on the EVS page.


## Using kubectl to Mount an EVS Disk<a name="section1996254515127"></a>

After an EVS disk is created or imported to the CCE console, you can mount it in a workload.

>![](public_sys-resources/icon-notice.gif) **NOTICE:**   
>EVS disks cannot be mounted across AZs. Before mounting, you can run the  **kubectl get pvc**  command to query the available PVCs in the partition where the current cluster is located.  

1.  Run the following commands to configure the  **evs-pod-example.yaml**  file, which is used to create a pod.

    **touch evs-pod-example.yaml**

    **vi evs-pod-example.yaml**

    Example of mounting an EVS disk to a Deployment \(PVC sharing\):

    ```
    apiVersion: extensions/v1beta1 
    kind: Deployment 
    metadata: 
      name: evs-pod-example 
      namespace: default 
    spec: 
      replicas: 1 
      selector: 
        matchLabels: 
          app: evs-pod-example 
      template: 
        metadata: 
          labels: 
            app: evs-pod-example 
        spec: 
          containers: 
          - image: nginx
            name: container-0 
            volumeMounts: 
            - mountPath: /tmp 
              name: pvc-evs-example 
          restartPolicy: Always 
          volumes: 
          - name: pvc-evs-example 
            persistentVolumeClaim: 
              claimName: pvc-evs-auto-example
    ```

    In this example:

    -   **name**: name of the Deployment.
    -   **app**: name of the pod workload.
    -   **mountPath**: mount path of the container. In this example, the EVS disk is mounted to the  **/tmp**  directory.
    -   **claimName**: name of an existing PVC.
    -   **spec.template.spec.containers.volumeMounts.name**  and  **spec.template.spec.volumes.name**  must be consistent because they have a mapping relationship.

    Example of mounting an EVS disk to a StatefulSet \(PVCTemplate inclusive\):

    ```
    apiVersion: apps/v1
    kind: StatefulSet
    metadata:
      name: deploy-evs-sata-in
      namespace: default
      generation: 1
      labels:
        appgroup: ''
      annotations:
        container.io/container-0: ***/swr/dockerimage/nginx.png
        description: ''
    spec:
      replicas: 1
      selector:
        matchLabels:
          app: deploy-evs-sata-in
          failure-domain.beta.kubernetes.io/region: eu-de
          failure-domain.beta.kubernetes.io/zone: eu-de-02
      template:
        metadata:
          labels:
            app: deploy-evs-sata-in
            failure-domain.beta.kubernetes.io/region: eu-de
            failure-domain.beta.kubernetes.io/zone: eu-de-02
          annotations:
            metrics.alpha.kubernetes.io/custom-endpoints: '[{"api":"","path":"","port":"","names":""}]'
            pod.alpha.kubernetes.io/initialized: 'true'
        spec:
          containers:
            - name: container-0
              image: 'nginx:1.12-alpine-perl'
              env:
                - name: PAAS_APP_NAME
                  value: deploy-evs-sata-in
                - name: PAAS_NAMESPACE
                  value: default
                - name: PAAS_PROJECT_ID
                  value: a2cd8e998dca42e98a41f596c636dbda
              resources: {}
              volumeMounts:
                - name: bs-sata-mountoptionpvc
                  mountPath: /tmp
              terminationMessagePath: /dev/termination-log
              terminationMessagePolicy: File
              imagePullPolicy: IfNotPresent
          restartPolicy: Always
          terminationGracePeriodSeconds: 30
          dnsPolicy: ClusterFirst
          securityContext: {}
          imagePullSecrets:
            - name: default-secret
          affinity: {}
          schedulerName: default-scheduler
      volumeClaimTemplates:
        - metadata:
            name: bs-sata-mountoptionpvc
            annotations:
              volume.beta.kubernetes.io/storage-class: sata
              volume.beta.kubernetes.io/storage-provisioner: flexvolume-huawei.com/fuxivol
    
          spec:
            accessModes:
              - ReadWriteMany
            resources:
              requests:
                storage: 10Gi
      serviceName: wwww
      podManagementPolicy: OrderedReady
      updateStrategy:
        type: RollingUpdate
      revisionHistoryLimit: 10
    ```

    In this example:

    -   **name**: name of the created workload.
    -   **image**: image of the workload.
    -   **mountPath**: mount path of the container. In this example, the EVS disk is mounted to the  **/tmp**  directory.
    -   **serviceName**: service corresponding to the workload. For details about how to create a service, see  [Creating a StatefulSet](creating-a-statefulset.md).
    -   **spec.template.spec.containers.volumeMounts.name**  and  **spec.volumeClaimTemplates.metadata.name**  must be consistent because they have a mapping relationship.

2.  Run the following command to create a pod:

    **kubectl create -f evs-pod-example.yaml**

    After the creation is complete, log in to the CCE console. In the navigation pane, choose  **Storage**  \>  **EVS**. Then, click the PVC name. On the PVC details page, you can view the binding relationship between the EVS disk and the PVC.


## Related Operations<a name="section1683811402220"></a>

After the EVS disk is created, you can perform operations described in  [Table 3](#table1619535674020).

**Table  3**  Other operations

<a name="table1619535674020"></a>
<table><thead align="left"><tr id="row17103718171311"><th class="cellrowborder" valign="top" width="32%" id="mcps1.2.3.1.1"><p id="p110320185130"><a name="p110320185130"></a><a name="p110320185130"></a>Operation</p>
</th>
<th class="cellrowborder" valign="top" width="68%" id="mcps1.2.3.1.2"><p id="p51031018141311"><a name="p51031018141311"></a><a name="p51031018141311"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row13103191815135"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="p17103171811319"><a name="p17103171811319"></a><a name="p17103171811319"></a>Deleting an EVS disk</p>
</td>
<td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><a name="ol1810311811318"></a><a name="ol1810311811318"></a><ol id="ol1810311811318"><li>Select the EVS disk to be deleted and click <strong id="b8423527069265"><a name="b8423527069265"></a><a name="b8423527069265"></a>Delete</strong> in the <strong id="b8423527069268"><a name="b8423527069268"></a><a name="b8423527069268"></a>Operation</strong> column.</li><li>Follow the prompts to delete the EVS disk.</li></ol>
</td>
</tr>
</tbody>
</table>

