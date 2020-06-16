# Querying a Certificate<a name="EN-US_TOPIC_0193631147"></a>

## Function Description<a name="section11738841"></a>

This API is used to query information about a certificate.

## URI<a name="section38540707"></a>

-   URI format

    GET  /v1/\{project\_id\}/waf/certificate/\{certificate\_id\}

-   Parameter description

    **Table  1**  Path parameters

    <a name="table34855425"></a>
    <table><thead align="left"><tr id="row42314802"><th class="cellrowborder" valign="top" width="30.930000000000003%" id="mcps1.2.5.1.1"><p id="p4946898"><a name="p4946898"></a><a name="p4946898"></a><strong id="b0544174617356"><a name="b0544174617356"></a><a name="b0544174617356"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="20.62%" id="mcps1.2.5.1.2"><p id="p65154430"><a name="p65154430"></a><a name="p65154430"></a><strong id="b1544047153515"><a name="b1544047153515"></a><a name="b1544047153515"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="14.430000000000001%" id="mcps1.2.5.1.3"><p id="p43017503"><a name="p43017503"></a><a name="p43017503"></a><strong id="b10497124853519"><a name="b10497124853519"></a><a name="b10497124853519"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="34.02%" id="mcps1.2.5.1.4"><p id="p61865757"><a name="p61865757"></a><a name="p61865757"></a><strong id="b637254917355"><a name="b637254917355"></a><a name="b637254917355"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row45070431"><td class="cellrowborder" valign="top" width="30.930000000000003%" headers="mcps1.2.5.1.1 "><p id="p26826318"><a name="p26826318"></a><a name="p26826318"></a>project_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="20.62%" headers="mcps1.2.5.1.2 "><p id="p25448145"><a name="p25448145"></a><a name="p25448145"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.430000000000001%" headers="mcps1.2.5.1.3 "><p id="p48033873"><a name="p48033873"></a><a name="p48033873"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="34.02%" headers="mcps1.2.5.1.4 "><p id="p65538485"><a name="p65538485"></a><a name="p65538485"></a>Specifies the project ID.</p>
    </td>
    </tr>
    <tr id="row52975456"><td class="cellrowborder" valign="top" width="30.930000000000003%" headers="mcps1.2.5.1.1 "><p id="p63153558"><a name="p63153558"></a><a name="p63153558"></a>certificate_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="20.62%" headers="mcps1.2.5.1.2 "><p id="p15164580"><a name="p15164580"></a><a name="p15164580"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="14.430000000000001%" headers="mcps1.2.5.1.3 "><p id="p20371507"><a name="p20371507"></a><a name="p20371507"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="34.02%" headers="mcps1.2.5.1.4 "><p id="p39479403"><a name="p39479403"></a><a name="p39479403"></a>Specifies the certificate ID.</p>
    </td>
    </tr>
    </tbody>
    </table>


## Request<a name="section11322047"></a>

Request parameters

None

## Response<a name="section34789567"></a>

Response parameters

**Table  2**  Parameter description

<a name="table58327572"></a>
<table><thead align="left"><tr id="row12075850"><th class="cellrowborder" valign="top" width="42.85571442855714%" id="mcps1.2.4.1.1"><p id="p38619773"><a name="p38619773"></a><a name="p38619773"></a><strong id="b17606141233620"><a name="b17606141233620"></a><a name="b17606141233620"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="17.348265173482652%" id="mcps1.2.4.1.2"><p id="p41193880"><a name="p41193880"></a><a name="p41193880"></a><strong id="b11138813143619"><a name="b11138813143619"></a><a name="b11138813143619"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="39.796020397960206%" id="mcps1.2.4.1.3"><p id="p48369988"><a name="p48369988"></a><a name="p48369988"></a><strong id="b866919138360"><a name="b866919138360"></a><a name="b866919138360"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row32676712"><td class="cellrowborder" valign="top" width="42.85571442855714%" headers="mcps1.2.4.1.1 "><p id="p29567983"><a name="p29567983"></a><a name="p29567983"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="17.348265173482652%" headers="mcps1.2.4.1.2 "><p id="p46196443"><a name="p46196443"></a><a name="p46196443"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39.796020397960206%" headers="mcps1.2.4.1.3 "><p id="p50924436"><a name="p50924436"></a><a name="p50924436"></a>Specifies the certificate ID.</p>
</td>
</tr>
<tr id="row55666745"><td class="cellrowborder" valign="top" width="42.85571442855714%" headers="mcps1.2.4.1.1 "><p id="p12712463"><a name="p12712463"></a><a name="p12712463"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="17.348265173482652%" headers="mcps1.2.4.1.2 "><p id="p23076582"><a name="p23076582"></a><a name="p23076582"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39.796020397960206%" headers="mcps1.2.4.1.3 "><p id="p57263845"><a name="p57263845"></a><a name="p57263845"></a>Specifies the certificate name.</p>
</td>
</tr>
<tr id="row1916146135417"><td class="cellrowborder" valign="top" width="42.85571442855714%" headers="mcps1.2.4.1.1 "><p id="p466545510448"><a name="p466545510448"></a><a name="p466545510448"></a>expireTime</p>
</td>
<td class="cellrowborder" valign="top" width="17.348265173482652%" headers="mcps1.2.4.1.2 "><p id="p11665125516444"><a name="p11665125516444"></a><a name="p11665125516444"></a>Long</p>
</td>
<td class="cellrowborder" valign="top" width="39.796020397960206%" headers="mcps1.2.4.1.3 "><p id="p17665655174419"><a name="p17665655174419"></a><a name="p17665655174419"></a>Specifies the time when the certificate expires.</p>
</td>
</tr>
<tr id="row5804171043619"><td class="cellrowborder" valign="top" width="42.85571442855714%" headers="mcps1.2.4.1.1 "><p id="p10804161063616"><a name="p10804161063616"></a><a name="p10804161063616"></a>timestamp</p>
</td>
<td class="cellrowborder" valign="top" width="17.348265173482652%" headers="mcps1.2.4.1.2 "><p id="p1880417108362"><a name="p1880417108362"></a><a name="p1880417108362"></a>Long</p>
</td>
<td class="cellrowborder" valign="top" width="39.796020397960206%" headers="mcps1.2.4.1.3 "><p id="p6804121083614"><a name="p6804121083614"></a><a name="p6804121083614"></a>Specifies the time when the certificate is uploaded.</p>
</td>
</tr>
</tbody>
</table>

## Example<a name="section10441101211352"></a>

A certificate named  **cert\_b**  is used as an example.

Response example

```
{
    "id": "388a7789d55b41d1918b3088a8f1e7f3",
    "name": "cert_b",
    "timestamp": 1545467166765,
    "expireTime": 1555467166765
}
```

## Status Code<a name="section44670651"></a>

[Table 3](#en-us_topic_0193631139_t82c3440f3efb42a38b9d4dc4011a33d0)  describes the normal status code returned by the API.

**Table  3**  Status code

<a name="en-us_topic_0193631139_t82c3440f3efb42a38b9d4dc4011a33d0"></a>
<table><thead align="left"><tr id="en-us_topic_0193631139_r3d6e2f205c444705bdbb9daaac74e575"><th class="cellrowborder" valign="top" width="22%" id="mcps1.2.4.1.1"><p id="en-us_topic_0193631139_af3c4073076f24eca88d94e3fa1effdc6"><a name="en-us_topic_0193631139_af3c4073076f24eca88d94e3fa1effdc6"></a><a name="en-us_topic_0193631139_af3c4073076f24eca88d94e3fa1effdc6"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="19.41%" id="mcps1.2.4.1.2"><p id="en-us_topic_0193631139_en-us_topic_0144911667_p4531342288"><a name="en-us_topic_0193631139_en-us_topic_0144911667_p4531342288"></a><a name="en-us_topic_0193631139_en-us_topic_0144911667_p4531342288"></a>Description</p>
</th>
<th class="cellrowborder" valign="top" width="58.589999999999996%" id="mcps1.2.4.1.3"><p id="en-us_topic_0193631139_ada185614bba24140995b8123b3e9faa8"><a name="en-us_topic_0193631139_ada185614bba24140995b8123b3e9faa8"></a><a name="en-us_topic_0193631139_ada185614bba24140995b8123b3e9faa8"></a>Meaning</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0193631139_rc7b2adc390904a1ba79e303017797786"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0193631139_a93f3895d44bb4226934cc626ac50e37b"><a name="en-us_topic_0193631139_a93f3895d44bb4226934cc626ac50e37b"></a><a name="en-us_topic_0193631139_a93f3895d44bb4226934cc626ac50e37b"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="19.41%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0193631139_en-us_topic_0144911667_p7538425819"><a name="en-us_topic_0193631139_en-us_topic_0144911667_p7538425819"></a><a name="en-us_topic_0193631139_en-us_topic_0144911667_p7538425819"></a>OK</p>
</td>
<td class="cellrowborder" valign="top" width="58.589999999999996%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0193631139_en-us_topic_0144911667_p369874114414"><a name="en-us_topic_0193631139_en-us_topic_0144911667_p369874114414"></a><a name="en-us_topic_0193631139_en-us_topic_0144911667_p369874114414"></a>The request has succeeded.</p>
</td>
</tr>
</tbody>
</table>

For details about error status codes, see  [Status Codes](status-codes.md).

