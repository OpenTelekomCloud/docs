# Adding a Security Group Rule<a name="en-us_topic_0030969470"></a>

## Scenarios<a name="s480ea51d8f2542828c323c6c8eb50861"></a>

After a security group is created, you can add rules to the security group. A rule applies either to inbound traffic \(ingress\) or outbound traffic \(egress\). After ECSs are added to the security group, they are protected by the rules of that group.

-   Inbound rules control incoming traffic to ECSs associated with the security group.
-   Outbound rules control outgoing traffic from ECSs associated with the security group.

For details about the default security group rules, see  [Default Security Groups and Security Group Rules](default-security-groups-and-security-group-rules.md). For details about security group rule configuration examples, see  [Security Group Configuration Examples](security-group-configuration-examples.md).

## Procedure<a name="section2999103814551"></a>

1.  Log in to the management console.
2.  Click  ![](figures/icon-region.png)  in the upper left corner and select the desired region and project.
3.  On the console homepage, under  **Network**, click  **Virtual Private Cloud**.
4.  In the navigation pane on the left, choose  **Access Control**  \>  **Security Groups**.
5.  On the  **Security Groups**  page, locate the target security group and click  **Manage Rule**  in the  **Operation**  column to switch to the page for managing inbound and outbound rules.
6.  On the inbound rule tab, click  **Add Rule**. In the displayed dialog box, set required parameters to add an inbound rule.

    You can click  **+**  to add more inbound rules.

    **Figure  1**  Add Inbound Rule<a name="fig3472133015819"></a>  
    ![](figures/add-inbound-rule.png "add-inbound-rule")

    **Table  1**  Inbound rule parameter description

    <a name="table111445216564"></a>
    <table><thead align="left"><tr id="row1811565205613"><th class="cellrowborder" valign="top" width="12.55%" id="mcps1.2.4.1.1"><p id="p51151452125620"><a name="p51151452125620"></a><a name="p51151452125620"></a><strong id="b2131889160"><a name="b2131889160"></a><a name="b2131889160"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="69.45%" id="mcps1.2.4.1.2"><p id="p5115552175613"><a name="p5115552175613"></a><a name="p5115552175613"></a><strong id="b2109380569"><a name="b2109380569"></a><a name="b2109380569"></a>Description</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18%" id="mcps1.2.4.1.3"><p id="p711565219563"><a name="p711565219563"></a><a name="p711565219563"></a><strong id="b984193573219"><a name="b984193573219"></a><a name="b984193573219"></a>Example Value</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row9115105219562"><td class="cellrowborder" rowspan="2" valign="top" width="12.55%" headers="mcps1.2.4.1.1 "><p id="p151157525565"><a name="p151157525565"></a><a name="p151157525565"></a>Protocol &amp; Port</p>
    <p id="p3510193211510"><a name="p3510193211510"></a><a name="p3510193211510"></a></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.45%" headers="mcps1.2.4.1.2 "><p id="p1711515526562"><a name="p1711515526562"></a><a name="p1711515526562"></a>Specifies the network protocol. Currently, the value can be <strong id="b63642068"><a name="b63642068"></a><a name="b63642068"></a>All</strong>, <strong id="b1275884042"><a name="b1275884042"></a><a name="b1275884042"></a>TCP</strong>, <strong id="b873919964"><a name="b873919964"></a><a name="b873919964"></a>UDP</strong>, <strong id="b1624173192"><a name="b1624173192"></a><a name="b1624173192"></a>ICMP</strong>, <strong id="b104287139"><a name="b104287139"></a><a name="b104287139"></a>GRE</strong>, or others.</p>
    </td>
    <td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.4.1.3 "><p id="p193908441914"><a name="p193908441914"></a><a name="p193908441914"></a>Custom TCP</p>
    </td>
    </tr>
    <tr id="row6510532121511"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p4115175245613"><a name="p4115175245613"></a><a name="p4115175245613"></a><strong id="b840131483114"><a name="b840131483114"></a><a name="b840131483114"></a>Port</strong>: specifies the port or port range over which the traffic can reach your ECS. Ports 1 to 65535 are all allowed. </p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p1551023251511"><a name="p1551023251511"></a><a name="p1551023251511"></a>22, or 22-30</p>
    </td>
    </tr>
    <tr id="row511615528561"><td class="cellrowborder" valign="top" width="12.55%" headers="mcps1.2.4.1.1 "><p id="p86899991813"><a name="p86899991813"></a><a name="p86899991813"></a>Source</p>
    </td>
    <td class="cellrowborder" valign="top" width="69.45%" headers="mcps1.2.4.1.2 "><p id="p18116175212564"><a name="p18116175212564"></a><a name="p18116175212564"></a><strong id="b18923132315592"><a name="b18923132315592"></a><a name="b18923132315592"></a>Source</strong>: specifies the source of the security group rule. The value can be another security group or a single IP address. For example:</p>
    <a name="ul12116352195619"></a><a name="ul12116352195619"></a><ul id="ul12116352195619"><li>xxx.xxx.xxx.xxx/32 (IPv4 address)</li><li>xxx.xxx.xxx.0/24 (subnet CIDR block)</li><li>0.0.0.0/0 (any IP address)</li></ul>
    </td>
    <td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.4.1.3 "><p id="p611613524569"><a name="p611613524569"></a><a name="p611613524569"></a>0.0.0.0/0</p>
    </td>
    </tr>
    <tr id="row111615525565"><td class="cellrowborder" valign="top" width="12.55%" headers="mcps1.2.4.1.1 "><p id="p1711655217565"><a name="p1711655217565"></a><a name="p1711655217565"></a>Description</p>
    </td>
    <td class="cellrowborder" valign="top" width="69.45%" headers="mcps1.2.4.1.2 "><p id="p1211611525564"><a name="p1211611525564"></a><a name="p1211611525564"></a>Provides supplementary information about the security group rule. This parameter is optional.</p>
    <p id="p6116175225613"><a name="p6116175225613"></a><a name="p6116175225613"></a>The security group rule description can contain a maximum of 255 characters and cannot contain angle brackets (&lt; or &gt;).</p>
    </td>
    <td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.4.1.3 "><p id="p3116115216568"><a name="p3116115216568"></a><a name="p3116115216568"></a>N/A</p>
    </td>
    </tr>
    </tbody>
    </table>

7.  On the outbound rule tab, click  **Add Rule**. In the displayed dialog box, set required parameters to add an outbound rule.

    You can click  **+**  to add more outbound rules.

    **Figure  2**  Add Outbound Rule<a name="fig172021330144714"></a>  
    ![](figures/add-outbound-rule.png "add-outbound-rule")

    **Table  2**  Outbound rule parameter description

    <a name="table0614192319232"></a>
    <table><thead align="left"><tr id="row19614623202312"><th class="cellrowborder" valign="top" width="12.55%" id="mcps1.2.4.1.1"><p id="p361592319230"><a name="p361592319230"></a><a name="p361592319230"></a><strong id="b1246024759"><a name="b1246024759"></a><a name="b1246024759"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="69.45%" id="mcps1.2.4.1.2"><p id="p1961514231232"><a name="p1961514231232"></a><a name="p1961514231232"></a><strong id="b392753994"><a name="b392753994"></a><a name="b392753994"></a>Description</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18%" id="mcps1.2.4.1.3"><p id="p1061552372311"><a name="p1061552372311"></a><a name="p1061552372311"></a><strong id="b78071625745"><a name="b78071625745"></a><a name="b78071625745"></a>Example Value</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row76161523132311"><td class="cellrowborder" rowspan="2" valign="top" width="12.55%" headers="mcps1.2.4.1.1 "><p id="p1761652313238"><a name="p1761652313238"></a><a name="p1761652313238"></a>Protocol &amp; Port</p>
    <p id="p4616323182310"><a name="p4616323182310"></a><a name="p4616323182310"></a></p>
    </td>
    <td class="cellrowborder" valign="top" width="69.45%" headers="mcps1.2.4.1.2 "><p id="p1461632352313"><a name="p1461632352313"></a><a name="p1461632352313"></a>Specifies the network protocol. Currently, the value can be <strong id="b202822549"><a name="b202822549"></a><a name="b202822549"></a>All</strong>, <strong id="b2060632122"><a name="b2060632122"></a><a name="b2060632122"></a>TCP</strong>, <strong id="b1478300017"><a name="b1478300017"></a><a name="b1478300017"></a>UDP</strong>, <strong id="b1962364235"><a name="b1962364235"></a><a name="b1962364235"></a>ICMP</strong>, <strong id="b722142174"><a name="b722142174"></a><a name="b722142174"></a>GRE</strong>, or others.</p>
    </td>
    <td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.4.1.3 "><p id="p157082238193"><a name="p157082238193"></a><a name="p157082238193"></a>Custom TCP</p>
    </td>
    </tr>
    <tr id="row5616723112313"><td class="cellrowborder" valign="top" headers="mcps1.2.4.1.1 "><p id="p761613239235"><a name="p761613239235"></a><a name="p761613239235"></a><strong id="b1962587115"><a name="b1962587115"></a><a name="b1962587115"></a>Port</strong>: specifies the port or port range over which the traffic can leave your ECS. The value ranges from 1 to 65535. </p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.4.1.2 "><p id="p12616182311235"><a name="p12616182311235"></a><a name="p12616182311235"></a>22, or 22-30</p>
    </td>
    </tr>
    <tr id="row2617112315232"><td class="cellrowborder" valign="top" width="12.55%" headers="mcps1.2.4.1.1 "><p id="p15617623172315"><a name="p15617623172315"></a><a name="p15617623172315"></a>Source</p>
    </td>
    <td class="cellrowborder" valign="top" width="69.45%" headers="mcps1.2.4.1.2 "><p id="p196171823152315"><a name="p196171823152315"></a><a name="p196171823152315"></a><strong id="b4110206531"><a name="b4110206531"></a><a name="b4110206531"></a>Source</strong>: specifies the source of the security group rule. The value can be another security group or a single IP address. For example:</p>
    <a name="ul16177237233"></a><a name="ul16177237233"></a><ul id="ul16177237233"><li>xxx.xxx.xxx.xxx/32 (IPv4 address)</li><li>xxx.xxx.xxx.0/24 (subnet CIDR block)</li><li>0.0.0.0/0 (any IP address)</li></ul>
    </td>
    <td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.4.1.3 "><p id="p4617102352310"><a name="p4617102352310"></a><a name="p4617102352310"></a>0.0.0.0/0</p>
    </td>
    </tr>
    <tr id="row196181723162317"><td class="cellrowborder" valign="top" width="12.55%" headers="mcps1.2.4.1.1 "><p id="p2061811237237"><a name="p2061811237237"></a><a name="p2061811237237"></a>Description</p>
    </td>
    <td class="cellrowborder" valign="top" width="69.45%" headers="mcps1.2.4.1.2 "><p id="p0618182392312"><a name="p0618182392312"></a><a name="p0618182392312"></a>Provides supplementary information about the security group rule. This parameter is optional.</p>
    <p id="p16618823192317"><a name="p16618823192317"></a><a name="p16618823192317"></a>The security group rule description can contain a maximum of 255 characters and cannot contain angle brackets (&lt; or &gt;).</p>
    </td>
    <td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.4.1.3 "><p id="p20618623202311"><a name="p20618623202311"></a><a name="p20618623202311"></a>N/A</p>
    </td>
    </tr>
    </tbody>
    </table>

8.  Click  **OK**.

