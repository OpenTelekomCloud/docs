# Querying BMS Metadata \(Native OpenStack API\)<a name="EN-US_TOPIC_0060402469"></a>

## Function<a name="section61558535185333"></a>

The BMS metadata includes BMS basic information on the cloud platform, such as the BMS ID, hostname, and network information. This API is used to query the BMS metadata.

## Constraints<a name="section57278039123222"></a>

Pagination query is not supported.

## URI<a name="section47451206185333"></a>

GET /v2.1/\{project\_id\}/servers/\{server\_id\}/metadata

[Table 1](#table3831319143216)  lists the parameters.

**Table  1**  Parameter description

<a name="table3831319143216"></a>
<table><thead align="left"><tr id="row38322019153219"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p49662088185333"><a name="p49662088185333"></a><a name="p49662088185333"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p63206191185333"><a name="p63206191185333"></a><a name="p63206191185333"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p19427838185333"><a name="p19427838185333"></a><a name="p19427838185333"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15832181913211"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p26317623185333"><a name="p26317623185333"></a><a name="p26317623185333"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p51352688185333"><a name="p51352688185333"></a><a name="p51352688185333"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p65927025185333"><a name="p65927025185333"></a><a name="p65927025185333"></a>Specifies the project ID.</p>
<p id="p9141450142010"><a name="p9141450142010"></a><a name="p9141450142010"></a>For how to obtain the project ID, see <a href="https://docs.otc.t-systems.com/en-us/api/apiug/apig-en-api-180328009.html" target="_blank" rel="noopener noreferrer">Obtaining Required Information</a>.</p>
</td>
</tr>
<tr id="row78321619103218"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p10854909185333"><a name="p10854909185333"></a><a name="p10854909185333"></a>server_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p6832475185333"><a name="p6832475185333"></a><a name="p6832475185333"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p16559613185333"><a name="p16559613185333"></a><a name="p16559613185333"></a>Specifies the <span id="text956081517186"><a name="text956081517186"></a><a name="text956081517186"></a>BMS</span><span id="text11560151581814"><a name="text11560151581814"></a><a name="text11560151581814"></a></span> ID.</p>
<p id="p29791113277"><a name="p29791113277"></a><a name="p29791113277"></a>You can obtain the BMS ID from the <span id="en-us_topic_0113746489_text013014803615"><a name="en-us_topic_0113746489_text013014803615"></a><a name="en-us_topic_0113746489_text013014803615"></a>BMS</span><span id="en-us_topic_0113746489_text10131448133612"><a name="en-us_topic_0113746489_text10131448133612"></a><a name="en-us_topic_0113746489_text10131448133612"></a></span> console or using the <a href="querying-bmss-(native-openstack-api).md">Querying BMSs (Native OpenStack API)</a> API.</p>
</td>
</tr>
</tbody>
</table>

## Request Message<a name="section14818796185333"></a>

-   Request parameters

    None

-   Example request

    ```
    GET https://{ECS Endpoint}/v2.1/c685484a8cc2416b97260938705deb65/servers/95bf2490-5428-432c-ad9b-5e3406f869dd/metadata
    ```


## Response Message<a name="section22254218185333"></a>

-   Response parameters

    <a name="table48150236185333"></a>
    <table><thead align="left"><tr id="row64499137185333"><th class="cellrowborder" valign="top" width="22.259999999999998%" id="mcps1.1.4.1.1"><p id="p59978491115233"><a name="p59978491115233"></a><a name="p59978491115233"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="22.24%" id="mcps1.1.4.1.2"><p id="p26419641115233"><a name="p26419641115233"></a><a name="p26419641115233"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="55.50000000000001%" id="mcps1.1.4.1.3"><p id="p64181866115233"><a name="p64181866115233"></a><a name="p64181866115233"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row51055328185333"><td class="cellrowborder" valign="top" width="22.259999999999998%" headers="mcps1.1.4.1.1 "><p id="p41840919185333"><a name="p41840919185333"></a><a name="p41840919185333"></a>metadata</p>
    </td>
    <td class="cellrowborder" valign="top" width="22.24%" headers="mcps1.1.4.1.2 "><p id="p33671307185333"><a name="p33671307185333"></a><a name="p33671307185333"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="55.50000000000001%" headers="mcps1.1.4.1.3 "><p id="p51647808185333"><a name="p51647808185333"></a><a name="p51647808185333"></a>Specifies the user-defined metadata key and value pair. For details, see <a href="#table22722954185333">Table 2</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

    **Table  2** **metadata**  field data structure description

    <a name="table22722954185333"></a>
    <table><thead align="left"><tr id="row5305371185333"><th class="cellrowborder" valign="top" width="22.957704229577043%" id="mcps1.2.4.1.1"><p id="p1640481205915"><a name="p1640481205915"></a><a name="p1640481205915"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="21.467853214678534%" id="mcps1.2.4.1.2"><p id="p1440581220594"><a name="p1440581220594"></a><a name="p1440581220594"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="55.57444255574442%" id="mcps1.2.4.1.3"><p id="p1340841217596"><a name="p1340841217596"></a><a name="p1340841217596"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row2696702185333"><td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.1 "><p id="p17106284185333"><a name="p17106284185333"></a><a name="p17106284185333"></a>User-defined field key and value pair</p>
    </td>
    <td class="cellrowborder" valign="top" width="21.467853214678534%" headers="mcps1.2.4.1.2 "><p id="p43431730185333"><a name="p43431730185333"></a><a name="p43431730185333"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="55.57444255574442%" headers="mcps1.2.4.1.3 "><p id="p5719410617654"><a name="p5719410617654"></a><a name="p5719410617654"></a>Specifies the key and value pair of the metadata.</p>
    <p id="p4498490617654"><a name="p4498490617654"></a><a name="p4498490617654"></a>The maximum size for each metadata key and value pair is 255 bytes.</p>
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

