# Using Job Browser on the Hue WebUI<a name="EN-US_TOPIC_0125375816"></a>

## Scenario<a name="sb4316978814b4f86ae12ef9fe7686f60"></a>

After Kerberos authentication is enabled for an MRS cluster, users can use the Hue WebUI to query all jobs in the cluster.

## Accessing  **Job Browser**<a name="section349132517406"></a>

1.  Access the Hue WebUI and click  **Job Browser**.
2.  View the jobs in the cluster.

    >![](/images/icon-note.gif) **NOTE:**   
    >The number on  **Job Browser**  indicates the total number of jobs in the cluster.  

    **Job Browser**  displays the following job information.

    **Table  1**  MRS job attributes

    <a name="table6543827417408"></a>
    <table><thead align="left"><tr id="row2576147717408"><th class="cellrowborder" valign="top" width="30.64%" id="mcps1.2.3.1.1"><p id="p5084955417408"><a name="p5084955417408"></a><a name="p5084955417408"></a>Attribute</p>
    </th>
    <th class="cellrowborder" valign="top" width="69.36%" id="mcps1.2.3.1.2"><p id="p2517317717408"><a name="p2517317717408"></a><a name="p2517317717408"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1800768317408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p5674433917408"><a name="p5674433917408"></a><a name="p5674433917408"></a><span class="parmname" id="parmname630492617408"><a name="parmname630492617408"></a><a name="parmname630492617408"></a><b>Logs</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p2756296517408"><a name="p2756296517408"></a><a name="p2756296517408"></a>Log information. If a job has logs, <a name="image3288871317408"></a><a name="image3288871317408"></a><span><img id="image3288871317408" src="figures/icon_mrs_mma.jpg"></span> is displayed.</p>
    </td>
    </tr>
    <tr id="row2890271317408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p4933622217408"><a name="p4933622217408"></a><a name="p4933622217408"></a><span class="parmname" id="parmname2785142317408"><a name="parmname2785142317408"></a><a name="parmname2785142317408"></a><b>ID</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p3681102117408"><a name="p3681102117408"></a><a name="p3681102117408"></a>Job ID, which is generated by the system automatically</p>
    </td>
    </tr>
    <tr id="row858155817408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p5941837717408"><a name="p5941837717408"></a><a name="p5941837717408"></a><span class="parmname" id="parmname5879782517408"><a name="parmname5879782517408"></a><a name="parmname5879782517408"></a><b>Name</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p4815920517408"><a name="p4815920517408"></a><a name="p4815920517408"></a>Job name</p>
    </td>
    </tr>
    <tr id="row580227217408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p2401763617408"><a name="p2401763617408"></a><a name="p2401763617408"></a><span class="parmname" id="parmname1012516617408"><a name="parmname1012516617408"></a><a name="parmname1012516617408"></a><b>Application Type</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p6055246117408"><a name="p6055246117408"></a><a name="p6055246117408"></a><span id="ph6638037417408"><a name="ph6638037417408"></a><a name="ph6638037417408"></a>Job type information</span></p>
    </td>
    </tr>
    <tr id="row2687781117408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p22206117408"><a name="p22206117408"></a><a name="p22206117408"></a><span class="parmname" id="parmname5222045617408"><a name="parmname5222045617408"></a><a name="parmname5222045617408"></a><b>Status</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p3512901317408"><a name="p3512901317408"></a><a name="p3512901317408"></a>Job status. Possible values are <span class="parmvalue" id="parmvalue1798697017408"><a name="parmvalue1798697017408"></a><a name="parmvalue1798697017408"></a><b>RUNNING</b></span>,&nbsp;<span class="parmname" id="parmname2766500417408"><a name="parmname2766500417408"></a><a name="parmname2766500417408"></a><b>SUCCEEDED</b></span>,&nbsp;<span class="parmname" id="parmname4765844717408"><a name="parmname4765844717408"></a><a name="parmname4765844717408"></a><b>FAILED</b></span>, and&nbsp;<span class="parmname" id="parmname2627284517408"><a name="parmname2627284517408"></a><a name="parmname2627284517408"></a><b>KILLED</b></span>.</p>
    </td>
    </tr>
    <tr id="row5090401817408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p2961912217408"><a name="p2961912217408"></a><a name="p2961912217408"></a><span class="parmname" id="parmname4057371517408"><a name="parmname4057371517408"></a><a name="parmname4057371517408"></a><b>User</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p5033871417408"><a name="p5033871417408"></a><a name="p5033871417408"></a>User who starts the job</p>
    </td>
    </tr>
    <tr id="row2684529217408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p2958477017408"><a name="p2958477017408"></a><a name="p2958477017408"></a><span class="parmname" id="parmname5548297917408"><a name="parmname5548297917408"></a><a name="parmname5548297917408"></a><b>Maps</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p4755617917408"><a name="p4755617917408"></a><a name="p4755617917408"></a>Map progress</p>
    </td>
    </tr>
    <tr id="row1591897217408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p2698507817408"><a name="p2698507817408"></a><a name="p2698507817408"></a><span class="parmname" id="parmname4028104417408"><a name="parmname4028104417408"></a><a name="parmname4028104417408"></a><b>Reduces</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p3830773717408"><a name="p3830773717408"></a><a name="p3830773717408"></a>Reduce progress</p>
    </td>
    </tr>
    <tr id="row4975199117408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p1436832717408"><a name="p1436832717408"></a><a name="p1436832717408"></a><span class="parmname" id="parmname905302117408"><a name="parmname905302117408"></a><a name="parmname905302117408"></a><b>Queue</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p2298384317408"><a name="p2298384317408"></a><a name="p2298384317408"></a>Yarn queue used for job running</p>
    </td>
    </tr>
    <tr id="row2697941617408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p337950017408"><a name="p337950017408"></a><a name="p337950017408"></a><span class="parmname" id="parmname4511474217408"><a name="parmname4511474217408"></a><a name="parmname4511474217408"></a><b>Priority</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p530410617408"><a name="p530410617408"></a><a name="p530410617408"></a>Job running priority</p>
    </td>
    </tr>
    <tr id="row2484968417408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p3784905417408"><a name="p3784905417408"></a><a name="p3784905417408"></a><span class="parmname" id="parmname4148815217408"><a name="parmname4148815217408"></a><a name="parmname4148815217408"></a><b>Duration</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p4587453317408"><a name="p4587453317408"></a><a name="p4587453317408"></a>Job running duration</p>
    </td>
    </tr>
    <tr id="row5642807017408"><td class="cellrowborder" valign="top" width="30.64%" headers="mcps1.2.3.1.1 "><p id="p6666741217408"><a name="p6666741217408"></a><a name="p6666741217408"></a><span class="parmname" id="parmname2232057117408"><a name="parmname2232057117408"></a><a name="parmname2232057117408"></a><b>Submitted</b></span></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.36%" headers="mcps1.2.3.1.2 "><p id="p3135130917408"><a name="p3135130917408"></a><a name="p3135130917408"></a>Time when the job is submitted to the MRS cluster</p>
    </td>
    </tr>
    </tbody>
    </table>

    >![](/images/icon-note.gif) **NOTE:**   
    >If the MRS cluster has Spark, the  **Spark-JDBCServer**  job is started by default to execute tasks.  


## Searching for  Jobs<a name="section9175833174017"></a>

1.  Enter keywords in  **Username** or **Text** on **Job Browser**  to search for the desired jobs.
2.  Clear the search criteria. The system displays all jobs.

## Querying  Job Details<a name="section24125061174023"></a>

1.  In the job list on  **Job Browser**, click the row that contains the desired job to view details.
2.  On the  **Metadata**  tab page, you can view the metadata of the job.

    >![](/images/icon-note.gif) **NOTE:**   
    >You can click  ![](figures/icon_mrs_dbjoblog.jpg)  to open job running logs.  


