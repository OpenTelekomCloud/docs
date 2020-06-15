# Deleting a Security Group<a name="EN-US_TOPIC_0067161717"></a>

## Function<a name="en-us_topic_0057973179_section16588975"></a>

This API is used to delete a security group for an ECS.

## URI<a name="en-us_topic_0057973179_section15083054"></a>

POST /v2/\{project\_id\}/servers/\{server\_id\}/action

POST /v2.1/\{project\_id\}/servers/\{server\_id\}/action

[Table 1](#table55945983)  describes the parameters in the URI.

**Table  1**  Parameter description

<a name="table55945983"></a>
<table><thead align="left"><tr id="row11302482"><th class="cellrowborder" valign="top" width="16.46%" id="mcps1.2.4.1.1"><p id="p5187119"><a name="p5187119"></a><a name="p5187119"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="17.150000000000002%" id="mcps1.2.4.1.2"><p id="p17503500"><a name="p17503500"></a><a name="p17503500"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="66.39%" id="mcps1.2.4.1.3"><p id="p8497414"><a name="p8497414"></a><a name="p8497414"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row49888896"><td class="cellrowborder" valign="top" width="16.46%" headers="mcps1.2.4.1.1 "><p id="p14468758"><a name="p14468758"></a><a name="p14468758"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="17.150000000000002%" headers="mcps1.2.4.1.2 "><p id="p31118786"><a name="p31118786"></a><a name="p31118786"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="66.39%" headers="mcps1.2.4.1.3 "><p id="p19718121214"><a name="p19718121214"></a><a name="p19718121214"></a>Specifies the project ID.</p>
</td>
</tr>
<tr id="row613736410235"><td class="cellrowborder" valign="top" width="16.46%" headers="mcps1.2.4.1.1 "><p id="p2736446410235"><a name="p2736446410235"></a><a name="p2736446410235"></a>server_id</p>
</td>
<td class="cellrowborder" valign="top" width="17.150000000000002%" headers="mcps1.2.4.1.2 "><p id="p192907210235"><a name="p192907210235"></a><a name="p192907210235"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="66.39%" headers="mcps1.2.4.1.3 "><p id="p2203711610235"><a name="p2203711610235"></a><a name="p2203711610235"></a>Specifies the ECS ID.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="en-us_topic_0057973179_section56802184"></a>

[Table 2](#en-us_topic_0058745339_table44724688204850)  describes the request parameters.

**Table  2**  Request parameter

<a name="en-us_topic_0058745339_table44724688204850"></a>
<table><thead align="left"><tr id="en-us_topic_0058745339_row1798761204850"><th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.1"><p id="en-us_topic_0058745339_p39560242204918"><a name="en-us_topic_0058745339_p39560242204918"></a><a name="en-us_topic_0058745339_p39560242204918"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.2"><p id="p1744285513269"><a name="p1744285513269"></a><a name="p1744285513269"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="15%" id="mcps1.2.5.1.3"><p id="en-us_topic_0058745339_p50263001204918"><a name="en-us_topic_0058745339_p50263001204918"></a><a name="en-us_topic_0058745339_p50263001204918"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="51%" id="mcps1.2.5.1.4"><p id="en-us_topic_0058745339_p2596798204918"><a name="en-us_topic_0058745339_p2596798204918"></a><a name="en-us_topic_0058745339_p2596798204918"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0058745339_row5848663204850"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0058745339_p22382703204933"><a name="en-us_topic_0058745339_p22382703204933"></a><a name="en-us_topic_0058745339_p22382703204933"></a>removeSecurityGroup</p>
</td>
<td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.2 "><p id="p1544245582616"><a name="p1544245582616"></a><a name="p1544245582616"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="15%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0058745339_p1059631204933"><a name="en-us_topic_0058745339_p1059631204933"></a><a name="en-us_topic_0058745339_p1059631204933"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0058745339_p40030009204933"><a name="en-us_topic_0058745339_p40030009204933"></a><a name="en-us_topic_0058745339_p40030009204933"></a>Deletes a security group for an ECS.</p>
</td>
</tr>
</tbody>
</table>

**Table  3** **removeSecurityGroup**  parameter description

<a name="en-us_topic_0058745339_table59377750205027"></a>
<table><thead align="left"><tr id="en-us_topic_0058745339_row1841518205027"><th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.1"><p id="p022464114103"><a name="p022464114103"></a><a name="p022464114103"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.2"><p id="p1281195882614"><a name="p1281195882614"></a><a name="p1281195882614"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="15%" id="mcps1.2.5.1.3"><p id="p522412415109"><a name="p522412415109"></a><a name="p522412415109"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="51%" id="mcps1.2.5.1.4"><p id="p1222404112106"><a name="p1222404112106"></a><a name="p1222404112106"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0058745339_row20042728205027"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0058745339_p29571470205128"><a name="en-us_topic_0058745339_p29571470205128"></a><a name="en-us_topic_0058745339_p29571470205128"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.2 "><p id="p11811558182613"><a name="p11811558182613"></a><a name="p11811558182613"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="15%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0058745339_p46478847205128"><a name="en-us_topic_0058745339_p46478847205128"></a><a name="en-us_topic_0058745339_p46478847205128"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="51%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0058745339_p5042904205128"><a name="en-us_topic_0058745339_p5042904205128"></a><a name="en-us_topic_0058745339_p5042904205128"></a>Specifies the UUID or the name of the security group from which the ECS is removed. The name takes effect for the NICs on the ECS.</p>
</td>
</tr>
</tbody>
</table>

## Response<a name="en-us_topic_0057973179_section41457614"></a>

None

## Example Request<a name="section158377710302"></a>

```
POST https://{endpoint}/v2.1/{project_id}/servers/{server_id}/action
```

```
{ 
    "removeSecurityGroup": { 
        "name": "sg-test"
    }
}
```

## Example Response<a name="section595062522516"></a>

None

## Returned Values<a name="section657556601763"></a>

See  [Returned Values for General Requests](returned-values-for-general-requests.md).

