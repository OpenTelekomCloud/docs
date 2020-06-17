# Updating BMS Metadata \(Native OpenStack API\)<a name="EN-US_TOPIC_0053158712"></a>

## Function<a name="section61558535185333"></a>

This API is used to update BMS metadata.

-   If the metadata does not contain the target field, the field is automatically added to the field.
-   If the metadata contains the target field, the field value is automatically updated.

## Constraints<a name="section57278039123222"></a>

The BMS  **OS-EXT-STS:vm\_state**  attribute \(BMS status\) must be  **active**,  **stopped**,  **paused**, or  **suspended**.

## URI<a name="section47451206185333"></a>

POST /v2.1/\{project\_id\}/servers/\{server\_id\}/metadata

[Table 1](#table560512381338)  lists the parameters.

**Table  1**  Parameter description

<a name="table560512381338"></a>
<table><thead align="left"><tr id="row960883873311"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p55073076202321"><a name="p55073076202321"></a><a name="p55073076202321"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p4027920716375"><a name="p4027920716375"></a><a name="p4027920716375"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p19427838185333"><a name="p19427838185333"></a><a name="p19427838185333"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row96081838143310"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p26317623185333"><a name="p26317623185333"></a><a name="p26317623185333"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p51352688185333"><a name="p51352688185333"></a><a name="p51352688185333"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p65927025185333"><a name="p65927025185333"></a><a name="p65927025185333"></a>Specifies the project ID.</p>
<p id="p9141450142010"><a name="p9141450142010"></a><a name="p9141450142010"></a>For how to obtain the project ID, see <a href="https://docs.otc.t-systems.com/en-us/api/apiug/apig-en-api-180328009.html" target="_blank" rel="noopener noreferrer">Obtaining Required Information</a>.</p>
</td>
</tr>
<tr id="row86081438153310"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p10854909185333"><a name="p10854909185333"></a><a name="p10854909185333"></a>server_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p6832475185333"><a name="p6832475185333"></a><a name="p6832475185333"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p16559613185333"><a name="p16559613185333"></a><a name="p16559613185333"></a>Specifies the <span id="text574164961818"><a name="text574164961818"></a><a name="text574164961818"></a>BMS</span><span id="text1374134981810"><a name="text1374134981810"></a><a name="text1374134981810"></a></span> ID.</p>
<p id="p29791113277"><a name="p29791113277"></a><a name="p29791113277"></a>You can obtain the BMS ID from the <span id="en-us_topic_0113746489_text013014803615"><a name="en-us_topic_0113746489_text013014803615"></a><a name="en-us_topic_0113746489_text013014803615"></a>BMS</span><span id="en-us_topic_0113746489_text10131448133612"><a name="en-us_topic_0113746489_text10131448133612"></a><a name="en-us_topic_0113746489_text10131448133612"></a></span> console or using the <a href="querying-bmss-(native-openstack-api).md">Querying BMSs (Native OpenStack API)</a> API.</p>
</td>
</tr>
</tbody>
</table>

## Request Message<a name="section14818796185333"></a>

-   Request parameters

    <a name="table52485804185333"></a>
    <table><thead align="left"><tr id="row22430249185333"><th class="cellrowborder" valign="top" width="17.2%" id="mcps1.1.5.1.1"><p id="p59978491115233"><a name="p59978491115233"></a><a name="p59978491115233"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="17.95%" id="mcps1.1.5.1.2"><p id="p101184475910"><a name="p101184475910"></a><a name="p101184475910"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="23.59%" id="mcps1.1.5.1.3"><p id="p26419641115233"><a name="p26419641115233"></a><a name="p26419641115233"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="41.260000000000005%" id="mcps1.1.5.1.4"><p id="p64181866115233"><a name="p64181866115233"></a><a name="p64181866115233"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row27794510185333"><td class="cellrowborder" valign="top" width="17.2%" headers="mcps1.1.5.1.1 "><p id="p36762838185333"><a name="p36762838185333"></a><a name="p36762838185333"></a>metadata</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.95%" headers="mcps1.1.5.1.2 "><p id="p59522419181648"><a name="p59522419181648"></a><a name="p59522419181648"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="23.59%" headers="mcps1.1.5.1.3 "><p id="p11727220185333"><a name="p11727220185333"></a><a name="p11727220185333"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.260000000000005%" headers="mcps1.1.5.1.4 "><p id="p26317995185333"><a name="p26317995185333"></a><a name="p26317995185333"></a>Specifies the user-defined metadata key and value pair. For details, see <a href="#table59792218185333">Table 2</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

    **Table  2** **metadata**  field data structure description

    <a name="table59792218185333"></a>
    <table><thead align="left"><tr id="row39910345185333"><th class="cellrowborder" valign="top" width="17.531753175317533%" id="mcps1.2.5.1.1"><p id="p0999194316596"><a name="p0999194316596"></a><a name="p0999194316596"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="17.341734173417343%" id="mcps1.2.5.1.2"><p id="p1320161017416"><a name="p1320161017416"></a><a name="p1320161017416"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="23.912391239123913%" id="mcps1.2.5.1.3"><p id="p150244165912"><a name="p150244165912"></a><a name="p150244165912"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="41.21412141214121%" id="mcps1.2.5.1.4"><p id="p17344419599"><a name="p17344419599"></a><a name="p17344419599"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row17903267185333"><td class="cellrowborder" valign="top" width="17.531753175317533%" headers="mcps1.2.5.1.1 "><p id="p40878540185333"><a name="p40878540185333"></a><a name="p40878540185333"></a>User-defined field key and value pair</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.341734173417343%" headers="mcps1.2.5.1.2 "><p id="p4201410446"><a name="p4201410446"></a><a name="p4201410446"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="23.912391239123913%" headers="mcps1.2.5.1.3 "><p id="p37081126185333"><a name="p37081126185333"></a><a name="p37081126185333"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="41.21412141214121%" headers="mcps1.2.5.1.4 "><p id="p54377834185333"><a name="p54377834185333"></a><a name="p54377834185333"></a>Specifies the user-defined metadata key and value pair.</p>
    <a name="ul12187816141520"></a><a name="ul12187816141520"></a><ul id="ul12187816141520"><li>The maximum size for each metadata key and value pair is 255 bytes.</li><li>The key does not support the following special characters:<p id="p104281244172319"><a name="p104281244172319"></a><a name="p104281244172319"></a>:`~!@#$%^&amp;*()=+&lt;,&gt;?/'";{[]}|\</p>
    </li><li>The value does not support the following special characters:<p id="p15830162842312"><a name="p15830162842312"></a><a name="p15830162842312"></a>\"</p>
    </li></ul>
    </td>
    </tr>
    </tbody>
    </table>


-   Example request

    ```
    POST https://{ECS Endpoint}/v2.1/c685484a8cc2416b97260938705deb65/servers/95bf2490-5428-432c-ad9b-5e3406f869dd/metadata
    ```

    ```
    {
        "metadata": {
            "key": "value"
        }
        }
    ```


## Response Message<a name="section22254218185333"></a>

-   Response parameters

    <a name="table48150236185333"></a>
    <table><thead align="left"><tr id="row64499137185333"><th class="cellrowborder" valign="top" width="23.82238223822382%" id="mcps1.1.4.1.1"><p id="p1697956135910"><a name="p1697956135910"></a><a name="p1697956135910"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="24.562456245624563%" id="mcps1.1.4.1.2"><p id="p598956135910"><a name="p598956135910"></a><a name="p598956135910"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="51.615161516151616%" id="mcps1.1.4.1.3"><p id="p1610045625911"><a name="p1610045625911"></a><a name="p1610045625911"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row51055328185333"><td class="cellrowborder" valign="top" width="23.82238223822382%" headers="mcps1.1.4.1.1 "><p id="p41840919185333"><a name="p41840919185333"></a><a name="p41840919185333"></a>metadata</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.562456245624563%" headers="mcps1.1.4.1.2 "><p id="p33671307185333"><a name="p33671307185333"></a><a name="p33671307185333"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.615161516151616%" headers="mcps1.1.4.1.3 "><p id="p51647808185333"><a name="p51647808185333"></a><a name="p51647808185333"></a>Specifies the user-defined metadata key and value pair. For details, see <a href="#table22722954185333">Table 3</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

    **Table  3** **metadata**  field data structure description

    <a name="table22722954185333"></a>
    <table><thead align="left"><tr id="row5305371185333"><th class="cellrowborder" valign="top" width="23.82%" id="mcps1.2.4.1.1"><p id="p893525865912"><a name="p893525865912"></a><a name="p893525865912"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="24.43%" id="mcps1.2.4.1.2"><p id="p99361858125912"><a name="p99361858125912"></a><a name="p99361858125912"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="51.74999999999999%" id="mcps1.2.4.1.3"><p id="p693905855910"><a name="p693905855910"></a><a name="p693905855910"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row2696702185333"><td class="cellrowborder" valign="top" width="23.82%" headers="mcps1.2.4.1.1 "><p id="p17106284185333"><a name="p17106284185333"></a><a name="p17106284185333"></a>User-defined field key and value pair</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.43%" headers="mcps1.2.4.1.2 "><p id="p43431730185333"><a name="p43431730185333"></a><a name="p43431730185333"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.74999999999999%" headers="mcps1.2.4.1.3 "><p id="p5719410617654"><a name="p5719410617654"></a><a name="p5719410617654"></a>Specifies the key and value pair of the metadata.</p>
    <a name="ul1049861817191"></a><a name="ul1049861817191"></a><ul id="ul1049861817191"><li>The maximum size for each metadata key and value pair is 255 bytes.</li><li>The value does not support the following special characters:<p id="p1821315403243"><a name="p1821315403243"></a><a name="p1821315403243"></a>\"</p>
    </li></ul>
    </td>
    </tr>
    </tbody>
    </table>

-   Example response

    ```
    {
        "metadata": {
            "key": "value"
        }
        }
    ```


## Returned Values<a name="section7610951"></a>

Normal values

<a name="en-us_topic_0106040941_table753804619176"></a>
<table><thead align="left"><tr id="en-us_topic_0106040941_row10735134615172"><th class="cellrowborder" valign="top" width="42.42%" id="mcps1.1.3.1.1"><p id="en-us_topic_0106040941_p19735204616177"><a name="en-us_topic_0106040941_p19735204616177"></a><a name="en-us_topic_0106040941_p19735204616177"></a>Returned Values</p>
</th>
<th class="cellrowborder" valign="top" width="57.58%" id="mcps1.1.3.1.2"><p id="en-us_topic_0106040941_p207355465176"><a name="en-us_topic_0106040941_p207355465176"></a><a name="en-us_topic_0106040941_p207355465176"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0106040941_row1473514621713"><td class="cellrowborder" valign="top" width="42.42%" headers="mcps1.1.3.1.1 "><p id="en-us_topic_0106040941_p13735144611178"><a name="en-us_topic_0106040941_p13735144611178"></a><a name="en-us_topic_0106040941_p13735144611178"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="57.58%" headers="mcps1.1.3.1.2 "><p id="en-us_topic_0106040941_p207351246161711"><a name="en-us_topic_0106040941_p207351246161711"></a><a name="en-us_topic_0106040941_p207351246161711"></a>The server has successfully processed the request.</p>
</td>
</tr>
</tbody>
</table>

For details about other returned values, see  [Status Codes](status-codes.md).

## Error Codes<a name="section14752650154917"></a>

See  [Error Codes](error-codes.md).

