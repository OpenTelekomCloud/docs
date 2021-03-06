# Step 1: Create a VPC Endpoint Service<a name="vpcep_02_02022"></a>

## Scenarios<a name="section9264105115117"></a>

This section describes how to create a VPC endpoint service by selecting an enhanced load balancer as an example backend service.

## Procedure<a name="section1071282101213"></a>

1.  Log in to the management console.
2.  Click  ![](/vpcep/user-guide/figures/icon-region.png)  in the upper left corner and select the desired region and project.
3.  Click  **Service List**  and choose  **VPC Endpoint**  under  **Network**.

1.  In the navigation pane on the left, choose  **VPC Endpoint**  \>  **VPC Endpoint Services**  and click  **Create VPC Endpoint Service**.

    The  **Create VPC Endpoint Service**  page is displayed.

    **Figure  1**  Create VPC Endpoint Service<a name="fig24549994419"></a>  
    ![](/vpcep/user-guide/figures/create-vpc-endpoint-service.png "create-vpc-endpoint-service")

2.  Configure parameters by referring to  [Table 1](#table20351132821713).

    **Table  1**  Required parameters

    <a name="table20351132821713"></a>
    <table><thead align="left"><tr id="row1835272821716"><th class="cellrowborder" valign="top" width="20.52%" id="mcps1.2.3.1.1"><p id="p235242816174"><a name="p235242816174"></a><a name="p235242816174"></a><strong id="b1498238145814"><a name="b1498238145814"></a><a name="b1498238145814"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="79.47999999999999%" id="mcps1.2.3.1.2"><p id="p143525281174"><a name="p143525281174"></a><a name="p143525281174"></a><strong id="b1519012108589"><a name="b1519012108589"></a><a name="b1519012108589"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row1354172831717"><td class="cellrowborder" valign="top" width="20.52%" headers="mcps1.2.3.1.1 "><p id="p203553284171"><a name="p203553284171"></a><a name="p203553284171"></a>Region</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.47999999999999%" headers="mcps1.2.3.1.2 "><p id="p19598107162718"><a name="p19598107162718"></a><a name="p19598107162718"></a>Specifies the region where the VPC endpoint service is located.</p>
    <p id="p481613202717"><a name="p481613202717"></a><a name="p481613202717"></a>Resources in different regions cannot communicate with each other over internal networks. For lower network latency and faster access to resources, select the nearest region.</p>
    </td>
    </tr>
    <tr id="row1350113217192"><td class="cellrowborder" valign="top" width="20.52%" headers="mcps1.2.3.1.1 "><p id="p850232111910"><a name="p850232111910"></a><a name="p850232111910"></a>Name</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.47999999999999%" headers="mcps1.2.3.1.2 "><p id="p272814376379"><a name="p272814376379"></a><a name="p272814376379"></a>This parameter is optional.</p>
    <p id="p5469827172719"><a name="p5469827172719"></a><a name="p5469827172719"></a>Specifies the name of the VPC endpoint service.</p>
    <p id="p113205101911"><a name="p113205101911"></a><a name="p113205101911"></a>The value contains a maximum of 16 characters, including letters, digits, underscores (_), and hyphens (-).</p>
    <a name="ul23391435674"></a><a name="ul23391435674"></a><ul id="ul23391435674"><li>If you do not configure this parameter, the VPC endpoint service name generated by the system is in the <em id="i16117531549"><a name="i16117531549"></a><a name="i16117531549"></a>region</em>.<em id="i10215355417"><a name="i10215355417"></a><a name="i10215355417"></a>service_id</em> format, for example, <strong id="b172954153817"><a name="b172954153817"></a><a name="b172954153817"></a>eu-de.69e93219-e3ad-43b9-8416-9d788319ac9f</strong>.</li><li>If you configure this parameter, the VPC endpoint service name generated by the system is in the <em id="i47071615152914"><a name="i47071615152914"></a><a name="i47071615152914"></a>region</em>.<em id="i3657121162919"><a name="i3657121162919"></a><a name="i3657121162919"></a>Name</em>.<em id="i8261122717297"><a name="i8261122717297"></a><a name="i8261122717297"></a>service_id</em> format, for example, <strong id="b4982692290"><a name="b4982692290"></a><a name="b4982692290"></a>eu-de.test.e9c186ca-99e4-4a88-9011-8898f1d680c0</strong>.</li></ul>
    </td>
    </tr>
    <tr id="row15357142816176"><td class="cellrowborder" valign="top" width="20.52%" headers="mcps1.2.3.1.1 "><p id="p33591328191713"><a name="p33591328191713"></a><a name="p33591328191713"></a>VPC</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.47999999999999%" headers="mcps1.2.3.1.2 "><p id="p113592289171"><a name="p113592289171"></a><a name="p113592289171"></a>Specifies the VPC where the VPC endpoint service is located.</p>
    </td>
    </tr>
    <tr id="row1036162871712"><td class="cellrowborder" valign="top" width="20.52%" headers="mcps1.2.3.1.1 "><p id="p4362142871712"><a name="p4362142871712"></a><a name="p4362142871712"></a>Service Type</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.47999999999999%" headers="mcps1.2.3.1.2 "><p id="p133632028151718"><a name="p133632028151718"></a><a name="p133632028151718"></a>Specifies the type of the VPC endpoint service. The value can only be <strong id="b94541042624"><a name="b94541042624"></a><a name="b94541042624"></a>Interface</strong>.</p>
    </td>
    </tr>
    <tr id="row13365028121710"><td class="cellrowborder" valign="top" width="20.52%" headers="mcps1.2.3.1.1 "><p id="p1736582818172"><a name="p1736582818172"></a><a name="p1736582818172"></a>Connection Approval</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.47999999999999%" headers="mcps1.2.3.1.2 "><p id="p53561208446"><a name="p53561208446"></a><a name="p53561208446"></a>Specifies whether the connection between a VPC endpoint and a VPC endpoint service requires approval from the owner of the VPC endpoint service.</p>
    <p id="p6183220134612"><a name="p6183220134612"></a><a name="p6183220134612"></a>You can determine whether to enable or disable the connection approval.</p>
    <p id="p59981552161415"><a name="p59981552161415"></a><a name="p59981552161415"></a>If connection approval is enabled, any VPC endpoint for connecting to the VPC endpoint service needs to be approved. For details, see step <a href="step-2-create-a-vpc-endpoint.md#li1979812511478">5</a>.</p>
    </td>
    </tr>
    <tr id="row8367128141713"><td class="cellrowborder" valign="top" width="20.52%" headers="mcps1.2.3.1.1 "><p id="p173671128151715"><a name="p173671128151715"></a><a name="p173671128151715"></a>Port Mapping</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.47999999999999%" headers="mcps1.2.3.1.2 "><p id="p15223957526"><a name="p15223957526"></a><a name="p15223957526"></a>Specifies the protocol and ports used for communication between the VPC endpoint service and VPC endpoint. The protocol is TCP or UDP.</p>
    <p id="p118118017204"><a name="p118118017204"></a><a name="p118118017204"></a><strong id="b1031318110435"><a name="b1031318110435"></a><a name="b1031318110435"></a>Service Port</strong>: A service port is provided by the backend service bound to the VPC endpoint service.</p>
    <p id="p3530125116191"><a name="p3530125116191"></a><a name="p3530125116191"></a><strong id="b176844547430"><a name="b176844547430"></a><a name="b176844547430"></a>Terminal Port</strong>: A terminal port is provided by the VPC endpoint, allowing you to access the VPC endpoint service.</p>
    <p id="p836817285177"><a name="p836817285177"></a><a name="p836817285177"></a>The service and terminal port numbers range from <strong id="b19811842103913"><a name="b19811842103913"></a><a name="b19811842103913"></a>1</strong> to <strong id="b17958164913917"><a name="b17958164913917"></a><a name="b17958164913917"></a>65535</strong>. A maximum of 50 port mappings can be added at a time.</p>
    <div class="note" id="note1952119430426"><a name="note1952119430426"></a><a name="note1952119430426"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p10522124314426"><a name="p10522124314426"></a><a name="p10522124314426"></a>Accessing a VPC endpoint service from a VPC endpoint is to access the service port from the associated terminal port.</p>
    </div></div>
    </td>
    </tr>
    <tr id="row93701328131717"><td class="cellrowborder" valign="top" width="20.52%" headers="mcps1.2.3.1.1 "><p id="p9370142851715"><a name="p9370142851715"></a><a name="p9370142851715"></a>Backend Resource Type</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.47999999999999%" headers="mcps1.2.3.1.2 "><p id="p1612011320271"><a name="p1612011320271"></a><a name="p1612011320271"></a>Specifies the type of the backend resource that provides services to be accessed.</p>
    <p id="p1732173704013"><a name="p1732173704013"></a><a name="p1732173704013"></a>This parameter can be set to <strong id="b8374208155912"><a name="b8374208155912"></a><a name="b8374208155912"></a>Enhanced load balancer</strong> or <strong id="b13719184313465"><a name="b13719184313465"></a><a name="b13719184313465"></a>ECS</strong>.</p>
    <a name="ul184514375313"></a><a name="ul184514375313"></a><ul id="ul184514375313"><li><strong id="b1801112154514"><a name="b1801112154514"></a><a name="b1801112154514"></a>Enhanced load balancer</strong>: Select this value if the backend resource is an enhanced load balancer. Backend resources of this type suit services that receive high access traffic and demand high reliability and disaster recovery (DR) performance.</li><li><strong id="b7999183618478"><a name="b7999183618478"></a><a name="b7999183618478"></a>ECS</strong>: Select this value if the backend resource is an Elastic Cloud Server (ECS). Backend resources of this type serve as servers.</li></ul>
    <div class="p" id="p19531163061313"><a name="p19531163061313"></a><a name="p19531163061313"></a>Select <strong id="b1837202019301"><a name="b1837202019301"></a><a name="b1837202019301"></a>Enhanced load balancer</strong>.<div class="note" id="note16693628171311"><a name="note16693628171311"></a><a name="note16693628171311"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p14875607183"><a name="p14875607183"></a><a name="p14875607183"></a>Security groups use the whitelist mechanism. For the security group of the backend resource configured for the VPC endpoint service, you need to add an inbound rule for the whitelist, where the source IP address is 198.19.128.0/20. For details, see <a href="https://docs.otc.t-systems.com/en-us/usermanual/vpc/en-us_topic_0030969470.html" target="_blank" rel="noopener noreferrer">Adding a Security Group Rule</a> in the <em id="i1085572210494"><a name="i1085572210494"></a><a name="i1085572210494"></a>Virtual Private Cloud User Guide</em>.</p>
    </div></div>
    </div>
    </td>
    </tr>
    <tr id="row564795616561"><td class="cellrowborder" valign="top" width="20.52%" headers="mcps1.2.3.1.1 "><p id="p1648956105615"><a name="p1648956105615"></a><a name="p1648956105615"></a>Load Balancer</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.47999999999999%" headers="mcps1.2.3.1.2 "><p id="p154192112610"><a name="p154192112610"></a><a name="p154192112610"></a>When <strong id="b124713319294"><a name="b124713319294"></a><a name="b124713319294"></a>Backend Resource Type</strong> is set to <strong id="b7879155918304"><a name="b7879155918304"></a><a name="b7879155918304"></a>Enhanced load balancer</strong>, select the load balancer that provides services from the drop-down list. Only enhanced load balancers are supported.</p>
    </td>
    </tr>
    <tr id="row213195211588"><td class="cellrowborder" valign="top" width="20.52%" headers="mcps1.2.3.1.1 "><p id="p622112531583"><a name="p622112531583"></a><a name="p622112531583"></a>Tag</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.47999999999999%" headers="mcps1.2.3.1.2 "><p id="p2088141885612"><a name="p2088141885612"></a><a name="p2088141885612"></a>This parameter is optional.</p>
    <p id="p1322113536585"><a name="p1322113536585"></a><a name="p1322113536585"></a>Specifies the VPC endpoint service tag, which consists of a key and a value. You can add a maximum of 10 tags to each VPC endpoint service.</p>
    <p id="p1222115316582"><a name="p1222115316582"></a><a name="p1222115316582"></a>Tag keys and values must meet requirements listed in <a href="#table539113432713">Table 2</a>.</p>
    <div class="note" id="note153500541565"><a name="note153500541565"></a><a name="note153500541565"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="en-us_topic_0131645182_p1697925218"><a name="en-us_topic_0131645182_p1697925218"></a><a name="en-us_topic_0131645182_p1697925218"></a>If a predefined tag has been created on TMS, you can directly select the corresponding tag key and value.</p>
    <p id="en-us_topic_0131645182_p6121182813506"><a name="en-us_topic_0131645182_p6121182813506"></a><a name="en-us_topic_0131645182_p6121182813506"></a>For details about predefined tags, see <a href="https://docs.otc.t-systems.com/usermanual/tms/en-us_topic_0056266269.html" target="_blank" rel="noopener noreferrer">Predefined Tag Overview</a>.</p>
    </div></div>
    </td>
    </tr>
    </tbody>
    </table>

    **Table  2**  Tag requirements for VPC endpoint services

    <a name="table539113432713"></a>
    <table><thead align="left"><tr id="en-us_topic_0162785419_row1975492119112"><th class="cellrowborder" valign="top" width="20.119999999999997%" id="mcps1.2.3.1.1"><p id="en-us_topic_0162785419_p127543216114"><a name="en-us_topic_0162785419_p127543216114"></a><a name="en-us_topic_0162785419_p127543216114"></a><strong id="b7396194010470"><a name="b7396194010470"></a><a name="b7396194010470"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="79.88%" id="mcps1.2.3.1.2"><p id="en-us_topic_0162785419_p187541211118"><a name="en-us_topic_0162785419_p187541211118"></a><a name="en-us_topic_0162785419_p187541211118"></a><strong id="b43235416476"><a name="b43235416476"></a><a name="b43235416476"></a>Requirement</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="en-us_topic_0162785419_row1375419211915"><td class="cellrowborder" valign="top" width="20.119999999999997%" headers="mcps1.2.3.1.1 "><p id="en-us_topic_0162785419_p15754421417"><a name="en-us_topic_0162785419_p15754421417"></a><a name="en-us_topic_0162785419_p15754421417"></a>Tag key</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.88%" headers="mcps1.2.3.1.2 "><a name="en-us_topic_0162785419_ul182248574315"></a><a name="en-us_topic_0162785419_ul182248574315"></a><ul id="en-us_topic_0162785419_ul182248574315"><li>Cannot be left blank.</li><li>Must be unique for the same VPC endpoint service.</li><li>Contains a maximum of 36 characters and only allows the following characters:<a name="en-us_topic_0162785419_ul15224957937"></a><a name="en-us_topic_0162785419_ul15224957937"></a><ul id="en-us_topic_0162785419_ul15224957937"><li>Uppercase letters</li><li>Lowercase letters</li><li>Digits</li><li>Special characters, including hyphens (-) and underscores (_)</li></ul>
    </li></ul>
    </td>
    </tr>
    <tr id="en-us_topic_0162785419_row97543211410"><td class="cellrowborder" valign="top" width="20.119999999999997%" headers="mcps1.2.3.1.1 "><p id="en-us_topic_0162785419_p97549211414"><a name="en-us_topic_0162785419_p97549211414"></a><a name="en-us_topic_0162785419_p97549211414"></a>Tag value</p>
    </td>
    <td class="cellrowborder" valign="top" width="79.88%" headers="mcps1.2.3.1.2 "><div class="p" id="en-us_topic_0162785419_p20581523133713"><a name="en-us_topic_0162785419_p20581523133713"></a><a name="en-us_topic_0162785419_p20581523133713"></a>Contains a maximum of 43 characters and only allows the following characters:<a name="en-us_topic_0162785419_ul19120173116418"></a><a name="en-us_topic_0162785419_ul19120173116418"></a><ul id="en-us_topic_0162785419_ul19120173116418"><li>Uppercase letters</li><li>Lowercase letters</li><li>Digits</li><li>Special characters, including hyphens (-) and underscores (_)</li></ul>
    </div>
    </td>
    </tr>
    </tbody>
    </table>

3.  Click  **Create Now**.
4.  On the displayed page, click  **Back to VPC Endpoint Service List**  to view the newly-created VPC endpoint service.
5.  In the VPC endpoint service list, locate the target VPC endpoint service and click its name to view the details.

    **Figure  2**  Summary of the VPC endpoint service<a name="fig14511321114513"></a>  
    ![](/vpcep/user-guide/figures/summary-of-the-vpc-endpoint-service.jpg "summary-of-the-vpc-endpoint-service")


