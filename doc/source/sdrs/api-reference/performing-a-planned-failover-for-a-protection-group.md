# Performing a Planned Failover for a Protection Group<a name="sdrs_05_0409"></a>

## Function<a name="en-us_topic_0079693002_section34649765"></a>

When you perform a planned failover for a protection group, the current production site of the protection group is switched to the DR site specified when the protection group is created, or reverse. After the planned failover is performed, data synchronization between the production site and DR site continues, but the direction is reverse.

## Constraints and Limitations<a name="section1066141012331"></a>

-   The protection group must have replication pairs.
-   **status**  of the protection group must be  **protected**  or  **error-reversing**.
-   All servers at the current production site of the protection group are stopped. During a planned failover, do not start servers at the production site and DR site. Otherwise, the planned failover may fail.
-   If the production site server or DR site server of a protected instance is deleted using the native interface, the planned failover or planned failback will fail, and the protected instance as well as the protection group will become unavailable.

## Restrictions on Logging In to a Server After You Perform a Planned Failover for the First Time<a name="section330514140125"></a>

-   If the production site server \(when the protected instance is created\) runs Windows and has Cloudbase-Init installed, pay attention to the following restrictions after you perform a planned failover for the first time:

    -   If you choose to use a password for the server login, you can use the password of the production site server 3 to 5 minutes after the DR site server starts and before Cloudbase-Init starts. It takes 1 to 2 minutes for the server to display the login UI. 

        After Cloudbase-Init starts, manually reset the password on the DR site server.

        After you perform a planned failback, use the configured password to log in to the production site server.

    -   If you choose to use a key for the server login, you can use the password obtained from the production site server 3 to 5 minutes after the DR site server starts and before Cloudbase-Init starts. It takes 1 to 2 minutes for the server to display the login UI.  

        After Cloudbase-Init starts, use the password obtained from the DR site server for the login.

        After you perform a planned failback, use the obtained password to log in to the production site server.

    >![](/images/icon-note.gif) **NOTE:**   
    >If you change the login password of the DR site server after you perform a planned failover for the first time, log in to the DR site server using the new password. After you perform a planned failback again, use the new password to log in to the production site server.  

-   If the production site server \(when the protected instance is created\) runs Windows and has no Cloudbase-Init installed, pay attention to the following restrictions after you perform a planned failover or failover for the first time:
    -   If you choose to use a password for the server login, use the password of the production site server to log in to the production site or DR site server.
    -   If you choose to use a key for the server login, use the password obtained from the production site server to log in to the production site or DR site server.

-   If the production site server \(when the protected instance is created\) runs Linux, pay attention to the following restrictions after you perform a planned failover or failover for the first time:
    -   If you choose to use a password for the server login, use the password of the production site server to log in to the production site or DR site server.

        >![](/images/icon-note.gif) **NOTE:**   
        >For servers running CoreOS, if you change the login password of the production site server after you perform a planned failover for the first time, log in to the DR site server using the new password. After you perform a planned failback again, use the initial password to log in to the production site server.  

    -   If you choose to use a key for the server login, use the password obtained from the production site server to log in to the production site or DR site server.


## URI<a name="en-us_topic_0079693002_section39390935"></a>

-   URI format

    POST /v1/\{project\_id\}/server-groups/\{server\_group\_id\}/action

-   Parameter description

    <a name="en-us_topic_0079693002_table63321005"></a>
    <table><thead align="left"><tr id="en-us_topic_0079693002_row37593218"><th class="cellrowborder" valign="top" width="19.801980198019802%" id="mcps1.1.5.1.1"><p id="p106701181136"><a name="p106701181136"></a><a name="p106701181136"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="14.85148514851485%" id="mcps1.1.5.1.2"><p id="p12670121816135"><a name="p12670121816135"></a><a name="p12670121816135"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="15.841584158415841%" id="mcps1.1.5.1.3"><p id="p1767021881316"><a name="p1767021881316"></a><a name="p1767021881316"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="49.504950495049506%" id="mcps1.1.5.1.4"><p id="p86711818141312"><a name="p86711818141312"></a><a name="p86711818141312"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="en-us_topic_0079693002_row29123463"><td class="cellrowborder" valign="top" width="19.801980198019802%" headers="mcps1.1.5.1.1 "><p id="p1667113180131"><a name="p1667113180131"></a><a name="p1667113180131"></a>project_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.85148514851485%" headers="mcps1.1.5.1.2 "><p id="p967118180137"><a name="p967118180137"></a><a name="p967118180137"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="15.841584158415841%" headers="mcps1.1.5.1.3 "><p id="p1267171815136"><a name="p1267171815136"></a><a name="p1267171815136"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="49.504950495049506%" headers="mcps1.1.5.1.4 "><p id="p16711118121320"><a name="p16711118121320"></a><a name="p16711118121320"></a>Specifies the project ID.</p>
    </td>
    </tr>
    <tr id="row697122711274"><td class="cellrowborder" valign="top" width="19.801980198019802%" headers="mcps1.1.5.1.1 "><p id="p7671118201311"><a name="p7671118201311"></a><a name="p7671118201311"></a>server_group_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.85148514851485%" headers="mcps1.1.5.1.2 "><p id="p14671181831320"><a name="p14671181831320"></a><a name="p14671181831320"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="15.841584158415841%" headers="mcps1.1.5.1.3 "><p id="p767171820138"><a name="p767171820138"></a><a name="p767171820138"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="49.504950495049506%" headers="mcps1.1.5.1.4 "><p id="p1067110182135"><a name="p1067110182135"></a><a name="p1067110182135"></a>Specifies the ID of a protection group.</p>
    <p id="p1541334120514"><a name="p1541334120514"></a><a name="p1541334120514"></a>For details, see <a href="querying-protection-groups.md">Querying Protection Groups</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>


## Request<a name="en-us_topic_0079693002_section18974100"></a>

-   Parameter description

    <a name="en-us_topic_0079693002_table54932709"></a>
    <table><thead align="left"><tr id="en-us_topic_0079693002_row41882373"><th class="cellrowborder" valign="top" width="25%" id="mcps1.1.5.1.1"><p id="p6331239161316"><a name="p6331239161316"></a><a name="p6331239161316"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.1.5.1.2"><p id="p43311939181317"><a name="p43311939181317"></a><a name="p43311939181317"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="15%" id="mcps1.1.5.1.3"><p id="p933123981319"><a name="p933123981319"></a><a name="p933123981319"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="46%" id="mcps1.1.5.1.4"><p id="p33311839101314"><a name="p33311839101314"></a><a name="p33311839101314"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="en-us_topic_0079693002_row27990155"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.1.5.1.1 "><p id="p1333173961315"><a name="p1333173961315"></a><a name="p1333173961315"></a>reverse-server-group</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.1.5.1.2 "><p id="p13311939141313"><a name="p13311939141313"></a><a name="p13311939141313"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.1.5.1.3 "><p id="p933133951316"><a name="p933133951316"></a><a name="p933133951316"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="46%" headers="mcps1.1.5.1.4 "><p id="p143318392139"><a name="p143318392139"></a><a name="p143318392139"></a>Performs a planned failover for a protection group.</p>
    <p id="p202261126183516"><a name="p202261126183516"></a><a name="p202261126183516"></a>For details, see <a href="#table104985554308">Table 1</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

    **Table  1** **reverse-server-group**  field description

    <a name="table104985554308"></a>
    <table><thead align="left"><tr id="row1750025520308"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="p1050265514309"><a name="p1050265514309"></a><a name="p1050265514309"></a><strong id="b842352706151210"><a name="b842352706151210"></a><a name="b842352706151210"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.2.5.1.2"><p id="p450305515302"><a name="p450305515302"></a><a name="p450305515302"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="15%" id="mcps1.2.5.1.3"><p id="p3504205511308"><a name="p3504205511308"></a><a name="p3504205511308"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="46%" id="mcps1.2.5.1.4"><p id="p850513557302"><a name="p850513557302"></a><a name="p850513557302"></a><strong id="b84235270615457"><a name="b84235270615457"></a><a name="b84235270615457"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row17514655163017"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p20514195510306"><a name="p20514195510306"></a><a name="p20514195510306"></a>priority_station</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.5.1.2 "><p id="p651513554309"><a name="p651513554309"></a><a name="p651513554309"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.2.5.1.3 "><p id="p195161055133013"><a name="p195161055133013"></a><a name="p195161055133013"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="46%" headers="mcps1.2.5.1.4 "><p id="p2051875519301"><a name="p2051875519301"></a><a name="p2051875519301"></a>Specifies the direction of the planned failover.</p>
    <a name="ul105186557308"></a><a name="ul105186557308"></a><ul id="ul105186557308"><li><strong id="b20571954773"><a name="b20571954773"></a><a name="b20571954773"></a>target</strong>: indicates to fail services from the production site specified when the protection group is created to the DR site specified when a protection group is created.</li><li><strong id="b1071915815816"><a name="b1071915815816"></a><a name="b1071915815816"></a>source</strong>: indicates to fail services from the DR site specified when the protection group is created to the production site specified when a protection group is created.</li></ul>
    </td>
    </tr>
    </tbody>
    </table>


-   Example request

    POST https://\{Endpoint\}/v1/\{project\_id\}/server-groups/40df180b-9fe2-471a-8c64-1b758dc84189/action

    ```
    {
      "reverse-server-group": {
        "priority_station": "source"
      }
    } 
    ```


## Response<a name="en-us_topic_0079693002_section36549175"></a>

-   Parameter description

    <a name="table155991608555"></a>
    <table><thead align="left"><tr id="row460510055518"><th class="cellrowborder" valign="top" width="29.07%" id="mcps1.1.4.1.1"><p id="p125611510173"><a name="p125611510173"></a><a name="p125611510173"></a><strong id="b842352706151210_1"><a name="b842352706151210_1"></a><a name="b842352706151210_1"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="17.44%" id="mcps1.1.4.1.2"><p id="p1456195171718"><a name="p1456195171718"></a><a name="p1456195171718"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="53.49%" id="mcps1.1.4.1.3"><p id="p12561651177"><a name="p12561651177"></a><a name="p12561651177"></a><strong id="b84235270615457_1"><a name="b84235270615457_1"></a><a name="b84235270615457_1"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row86164025512"><td class="cellrowborder" valign="top" width="29.07%" headers="mcps1.1.4.1.1 "><p id="p4561551711"><a name="p4561551711"></a><a name="p4561551711"></a>job_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.44%" headers="mcps1.1.4.1.2 "><p id="p35635121719"><a name="p35635121719"></a><a name="p35635121719"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="53.49%" headers="mcps1.1.4.1.3 "><p id="p15561951175"><a name="p15561951175"></a><a name="p15561951175"></a>Specifies the returned parameter when the asynchronous API command is issued successfully. For details about the task execution result, see the description in <a href="querying-the-job-status.md">Querying the Job Status</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Example response

    ```
    { 
       "job_id": "0000000062db92d70162db9d200f002d" 
     }
    ```

    Or

    ```
    { 
         "error": { 
             "message": "XXXX",  
             "code": "XXX" 
         } 
     }
    ```

    In this example,  **error**  represents a general error, including  **badrequest**  \(shown below\) and  **itemNotFound**.

    ```
    { 
         "badrequest": { 
             "message": "XXXX",  
             "code": "XXX" 
         } 
     }
    ```


## Returned Values<a name="en-us_topic_0079693002_section60507121"></a>

-   Normal

    <a name="sdrs_05_0101_table4315991194956"></a>
    <table><thead align="left"><tr id="sdrs_05_0101_row2336641294956"><th class="cellrowborder" valign="top" width="42.59%" id="mcps1.1.3.1.1"><p id="sdrs_05_0101_p1363125894956"><a name="sdrs_05_0101_p1363125894956"></a><a name="sdrs_05_0101_p1363125894956"></a>Returned Value</p>
    </th>
    <th class="cellrowborder" valign="top" width="57.410000000000004%" id="mcps1.1.3.1.2"><p id="sdrs_05_0101_p3039012494956"><a name="sdrs_05_0101_p3039012494956"></a><a name="sdrs_05_0101_p3039012494956"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="sdrs_05_0101_row507566794956"><td class="cellrowborder" valign="top" width="42.59%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p847584694956"><a name="sdrs_05_0101_p847584694956"></a><a name="sdrs_05_0101_p847584694956"></a>200</p>
    </td>
    <td class="cellrowborder" valign="top" width="57.410000000000004%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p1545496394956"><a name="sdrs_05_0101_p1545496394956"></a><a name="sdrs_05_0101_p1545496394956"></a>The server has accepted the request.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Abnormal

    <a name="sdrs_05_0101_table22458872203835"></a>
    <table><thead align="left"><tr id="sdrs_05_0101_row35704554203835"><th class="cellrowborder" valign="top" width="43.419999999999995%" id="mcps1.1.3.1.1"><p id="sdrs_05_0101_p6387753203835"><a name="sdrs_05_0101_p6387753203835"></a><a name="sdrs_05_0101_p6387753203835"></a>Returned Value</p>
    </th>
    <th class="cellrowborder" valign="top" width="56.58%" id="mcps1.1.3.1.2"><p id="sdrs_05_0101_p47646009203835"><a name="sdrs_05_0101_p47646009203835"></a><a name="sdrs_05_0101_p47646009203835"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="sdrs_05_0101_row34121538203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p12381163203835"><a name="sdrs_05_0101_p12381163203835"></a><a name="sdrs_05_0101_p12381163203835"></a>400 Bad Request</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p63350108203835"><a name="sdrs_05_0101_p63350108203835"></a><a name="sdrs_05_0101_p63350108203835"></a>The server failed to process the request.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row33280063203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p11330608203835"><a name="sdrs_05_0101_p11330608203835"></a><a name="sdrs_05_0101_p11330608203835"></a>401 Unauthorized</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p45364094203835"><a name="sdrs_05_0101_p45364094203835"></a><a name="sdrs_05_0101_p45364094203835"></a>You must enter a username and the password to access the requested page.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row5623667203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p52863895203835"><a name="sdrs_05_0101_p52863895203835"></a><a name="sdrs_05_0101_p52863895203835"></a>403 Forbidden</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p54117066203835"><a name="sdrs_05_0101_p54117066203835"></a><a name="sdrs_05_0101_p54117066203835"></a>You are forbidden to access the requested page.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row17291554203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p58438642203835"><a name="sdrs_05_0101_p58438642203835"></a><a name="sdrs_05_0101_p58438642203835"></a>404 Not Found</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p35909542203835"><a name="sdrs_05_0101_p35909542203835"></a><a name="sdrs_05_0101_p35909542203835"></a>The server could not find the requested page.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row54750425203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p5599455203835"><a name="sdrs_05_0101_p5599455203835"></a><a name="sdrs_05_0101_p5599455203835"></a>405 Method Not Allowed</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p50902717203835"><a name="sdrs_05_0101_p50902717203835"></a><a name="sdrs_05_0101_p50902717203835"></a>You are not allowed to use the method specified in the request.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row55471277203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p63988484203835"><a name="sdrs_05_0101_p63988484203835"></a><a name="sdrs_05_0101_p63988484203835"></a>406 Not Acceptable</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p15684678203835"><a name="sdrs_05_0101_p15684678203835"></a><a name="sdrs_05_0101_p15684678203835"></a>The response generated by the server could not be accepted by the client.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row6944380203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p25623884203835"><a name="sdrs_05_0101_p25623884203835"></a><a name="sdrs_05_0101_p25623884203835"></a>407 Proxy Authentication Required</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p62268733203835"><a name="sdrs_05_0101_p62268733203835"></a><a name="sdrs_05_0101_p62268733203835"></a>You must use the proxy server for authentication so that the request can be processed.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row23547689203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p28314670203835"><a name="sdrs_05_0101_p28314670203835"></a><a name="sdrs_05_0101_p28314670203835"></a>408 Request Timeout</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p11786919203835"><a name="sdrs_05_0101_p11786919203835"></a><a name="sdrs_05_0101_p11786919203835"></a>The request timed out.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row38973411203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p2729702203835"><a name="sdrs_05_0101_p2729702203835"></a><a name="sdrs_05_0101_p2729702203835"></a>409 Conflict</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p19779281203835"><a name="sdrs_05_0101_p19779281203835"></a><a name="sdrs_05_0101_p19779281203835"></a>The request could not be processed due to a conflict.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row43795805203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p57799353203835"><a name="sdrs_05_0101_p57799353203835"></a><a name="sdrs_05_0101_p57799353203835"></a>500 Internal Server Error</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p51235984203835"><a name="sdrs_05_0101_p51235984203835"></a><a name="sdrs_05_0101_p51235984203835"></a>Failed to complete the request because of a service error.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row58470678203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p38504500203835"><a name="sdrs_05_0101_p38504500203835"></a><a name="sdrs_05_0101_p38504500203835"></a>501 Not Implemented</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p31856770203835"><a name="sdrs_05_0101_p31856770203835"></a><a name="sdrs_05_0101_p31856770203835"></a>Failed to complete the request because the server does not support the requested function.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row18275474203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p3918444203835"><a name="sdrs_05_0101_p3918444203835"></a><a name="sdrs_05_0101_p3918444203835"></a>502 Bad Gateway</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p48958538203835"><a name="sdrs_05_0101_p48958538203835"></a><a name="sdrs_05_0101_p48958538203835"></a>Failed to complete the request because the server receives an invalid response from an upstream server.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row37973662203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p55967806203835"><a name="sdrs_05_0101_p55967806203835"></a><a name="sdrs_05_0101_p55967806203835"></a>503 Service Unavailable</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p37098455203835"><a name="sdrs_05_0101_p37098455203835"></a><a name="sdrs_05_0101_p37098455203835"></a>Failed to complete the request because the system is unavailable.</p>
    </td>
    </tr>
    <tr id="sdrs_05_0101_row65450640203835"><td class="cellrowborder" valign="top" width="43.419999999999995%" headers="mcps1.1.3.1.1 "><p id="sdrs_05_0101_p67010448203835"><a name="sdrs_05_0101_p67010448203835"></a><a name="sdrs_05_0101_p67010448203835"></a>504 Gateway Timeout</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.58%" headers="mcps1.1.3.1.2 "><p id="sdrs_05_0101_p59137180203835"><a name="sdrs_05_0101_p59137180203835"></a><a name="sdrs_05_0101_p59137180203835"></a>A gateway timeout error occurred.</p>
    </td>
    </tr>
    </tbody>
    </table>


