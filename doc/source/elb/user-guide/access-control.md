# Access Control<a name="EN-US_TOPIC_0094005094"></a>

Access control allows you to add a whitelist to specify IP addresses that can access a listener.

>![](/images/icon-notice.gif) **NOTICE:**   
>-   You can add whitelists only to listeners of enhanced load balancers. Adding whitelists may cause service risks. Once a whitelist is added, only IP addresses in the whitelist can access the listener.  
>-   If access control is enabled but no whitelist is added, the listener cannot be accessed.  
>-   Access control does not conflict with inbound security group rules. Whitelists define the IP addresses or CIDR blocks from which the load balancer receives traffic, whereas inbound security group rules specify the protocol, ports, and IP addresses that allow traffic to backend servers.  

## Add a Whitelist<a name="section9017688174523"></a>

1.  Log in to the management console.
2.  In the upper left corner of the page, click  ![](figures/icon-region.png)  and select the desired region and project.
3.  Click  **Service List**. Under  **Network**, click  **Elastic Load Balancing**.

1.  Locate the target load balancer and click its name.
2.  Click  **Listeners**, locate the target listener, and click its name. In the  **Basic Information**  area, click  **Configure**  beside  **Access Control**.

    **Table  1**  Parameter description

    <a name="table3263104318541"></a>
    <table><thead align="left"><tr id="row6556870018541"><th class="cellrowborder" valign="top" width="21.000000000000004%" id="mcps1.2.4.1.1"><p id="p60775331862"><a name="p60775331862"></a><a name="p60775331862"></a><strong id="b842352706114331"><a name="b842352706114331"></a><a name="b842352706114331"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="58.00000000000001%" id="mcps1.2.4.1.2"><p id="p5449227018541"><a name="p5449227018541"></a><a name="p5449227018541"></a><strong id="b8423527061772"><a name="b8423527061772"></a><a name="b8423527061772"></a>Description</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="21.000000000000004%" id="mcps1.2.4.1.3"><p id="p5179777918541"><a name="p5179777918541"></a><a name="p5179777918541"></a><strong id="b842352706194150"><a name="b842352706194150"></a><a name="b842352706194150"></a>Example Value</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row6352683318541"><td class="cellrowborder" valign="top" width="21.000000000000004%" headers="mcps1.2.4.1.1 "><p id="p4539988218541"><a name="p4539988218541"></a><a name="p4539988218541"></a>Access Control</p>
    </td>
    <td class="cellrowborder" valign="top" width="58.00000000000001%" headers="mcps1.2.4.1.2 "><p id="p2634610118936"><a name="p2634610118936"></a><a name="p2634610118936"></a>Enabled</p>
    <a name="ul2943297718957"></a><a name="ul2943297718957"></a><ul id="ul2943297718957"><li>If access control is enabled and no whitelist is set, no IP address can access the listener.</li><li>If access control function is enabled and a whitelist is set, only IP addresses in the whitelist can access the listener.</li></ul>
    <p id="p5351183118541"><a name="p5351183118541"></a><a name="p5351183118541"></a>Disabled</p>
    <a name="ul42097092181052"></a><a name="ul42097092181052"></a><ul id="ul42097092181052"><li>If access control is disabled, load listener can be accessed from any IP address.</li></ul>
    </td>
    <td class="cellrowborder" valign="top" width="21.000000000000004%" headers="mcps1.2.4.1.3 "><p id="p3949107318541"><a name="p3949107318541"></a><a name="p3949107318541"></a>N/A</p>
    </td>
    </tr>
    <tr id="row1987534018541"><td class="cellrowborder" valign="top" width="21.000000000000004%" headers="mcps1.2.4.1.1 "><p id="p6639869918541"><a name="p6639869918541"></a><a name="p6639869918541"></a>Whitelist</p>
    </td>
    <td class="cellrowborder" valign="top" width="58.00000000000001%" headers="mcps1.2.4.1.2 "><p id="p39771091184017"><a name="p39771091184017"></a><a name="p39771091184017"></a>Lists the IP addresses or CIDR blocks that can access the listener.</p>
    <div class="note" id="note1238160118401"><a name="note1238160118401"></a><a name="note1238160118401"></a><span class="notetitle"> NOTE: </span><div class="notebody"><p id="p58558164184037"><a name="p58558164184037"></a><a name="p58558164184037"></a>A maximum of 300 IP addresses or CIDR blocks are supported. A comma (,) is used to separate every two entries.</p>
    </div></div>
    </td>
    <td class="cellrowborder" valign="top" width="21.000000000000004%" headers="mcps1.2.4.1.3 "><p id="p3823315618541"><a name="p3823315618541"></a><a name="p3823315618541"></a>10.168.2.24,10.168.16.0/24</p>
    </td>
    </tr>
    </tbody>
    </table>

3.  Click  **OK**.

