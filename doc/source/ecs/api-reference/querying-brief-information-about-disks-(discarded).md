# Querying Brief Information About Disks \(Discarded\)<a name="EN-US_TOPIC_0065817709"></a>

## Function<a name="en-us_topic_0057973209_section52409933"></a>

This API is used to query brief information about disks.

## Constraints<a name="en-us_topic_0057973209_section53828184"></a>

-   This API will be discarded. You are advised to use the EVS API "Querying EVS Disks \(Native OpenStack API V2\)".

## URI<a name="en-us_topic_0057973209_section1927356"></a>

GET /v2/\{project\_id\}/os-volumes

GET /v2.1/\{project\_id\}/os-volumes

[Table 1](#en-us_topic_0057973209_table2814978410562)  describes the parameters in the URI.

**Table  1**  Parameter description

<a name="en-us_topic_0057973209_table2814978410562"></a>
<table><thead align="left"><tr id="en-us_topic_0057973209_row4149654710562"><th class="cellrowborder" valign="top" width="33%" id="mcps1.2.4.1.1"><p id="p5187119"><a name="p5187119"></a><a name="p5187119"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="23%" id="mcps1.2.4.1.2"><p id="p17503500"><a name="p17503500"></a><a name="p17503500"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="44%" id="mcps1.2.4.1.3"><p id="p8497414"><a name="p8497414"></a><a name="p8497414"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0057973209_row3491217610562"><td class="cellrowborder" valign="top" width="33%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p931403110562"><a name="en-us_topic_0057973209_p931403110562"></a><a name="en-us_topic_0057973209_p931403110562"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p1623904210562"><a name="en-us_topic_0057973209_p1623904210562"></a><a name="en-us_topic_0057973209_p1623904210562"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.4.1.3 "><p id="p37593705"><a name="p37593705"></a><a name="p37593705"></a>Specifies the project ID.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="en-us_topic_0057973209_section62865382"></a>

N/A

## Response<a name="en-us_topic_0057973209_section28917527"></a>

[Table 2](#en-us_topic_0057973209_table26952071)  describes the response parameters.

**Table  2**  Response parameters

<a name="en-us_topic_0057973209_table26952071"></a>
<table><thead align="left"><tr id="en-us_topic_0057973209_row27956541"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p62404314"><a name="p62404314"></a><a name="p62404314"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p3528183"><a name="p3528183"></a><a name="p3528183"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p17347392"><a name="p17347392"></a><a name="p17347392"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0057973209_row31251660"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p48356531"><a name="en-us_topic_0057973209_p48356531"></a><a name="en-us_topic_0057973209_p48356531"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p24564930"><a name="en-us_topic_0057973209_p24564930"></a><a name="en-us_topic_0057973209_p24564930"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p42128507"><a name="en-us_topic_0057973209_p42128507"></a><a name="en-us_topic_0057973209_p42128507"></a>Specifies the disk ID in UUID format.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row43612244"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p42930836"><a name="en-us_topic_0057973209_p42930836"></a><a name="en-us_topic_0057973209_p42930836"></a>displayName</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p54845664"><a name="en-us_topic_0057973209_p54845664"></a><a name="en-us_topic_0057973209_p54845664"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p4678079"><a name="en-us_topic_0057973209_p4678079"></a><a name="en-us_topic_0057973209_p4678079"></a>Specifies the disk name.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row42102716"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p54876848"><a name="en-us_topic_0057973209_p54876848"></a><a name="en-us_topic_0057973209_p54876848"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p15839667"><a name="en-us_topic_0057973209_p15839667"></a><a name="en-us_topic_0057973209_p15839667"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p39539981"><a name="en-us_topic_0057973209_p39539981"></a><a name="en-us_topic_0057973209_p39539981"></a>Specifies the disk status.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row20315511"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p34943688"><a name="en-us_topic_0057973209_p34943688"></a><a name="en-us_topic_0057973209_p34943688"></a>attachments</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p11866445"><a name="en-us_topic_0057973209_p11866445"></a><a name="en-us_topic_0057973209_p11866445"></a>Array of objects</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p9464853"><a name="en-us_topic_0057973209_p9464853"></a><a name="en-us_topic_0057973209_p9464853"></a>Specifies the attachment information about a disk.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row18074813"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p54773733"><a name="en-us_topic_0057973209_p54773733"></a><a name="en-us_topic_0057973209_p54773733"></a>availabilityZone</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p7487365"><a name="en-us_topic_0057973209_p7487365"></a><a name="en-us_topic_0057973209_p7487365"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p917327"><a name="en-us_topic_0057973209_p917327"></a><a name="en-us_topic_0057973209_p917327"></a>Specifies the AZ to which the disk belongs.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row8255951"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p64752280"><a name="en-us_topic_0057973209_p64752280"></a><a name="en-us_topic_0057973209_p64752280"></a>createdAt</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p10443326"><a name="en-us_topic_0057973209_p10443326"></a><a name="en-us_topic_0057973209_p10443326"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p512574"><a name="en-us_topic_0057973209_p512574"></a><a name="en-us_topic_0057973209_p512574"></a>Specifies the time when the disk was created.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row4613174"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p38122810"><a name="en-us_topic_0057973209_p38122810"></a><a name="en-us_topic_0057973209_p38122810"></a>displayDescription</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p939935"><a name="en-us_topic_0057973209_p939935"></a><a name="en-us_topic_0057973209_p939935"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p60011947"><a name="en-us_topic_0057973209_p60011947"></a><a name="en-us_topic_0057973209_p60011947"></a>Specifies the disk description.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row3236611"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p60838957"><a name="en-us_topic_0057973209_p60838957"></a><a name="en-us_topic_0057973209_p60838957"></a>volumeType</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p29008475"><a name="en-us_topic_0057973209_p29008475"></a><a name="en-us_topic_0057973209_p29008475"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p3869669"><a name="en-us_topic_0057973209_p3869669"></a><a name="en-us_topic_0057973209_p3869669"></a>Specifies the disk type.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row34827024"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p2416665"><a name="en-us_topic_0057973209_p2416665"></a><a name="en-us_topic_0057973209_p2416665"></a>snapshotId</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p61532138"><a name="en-us_topic_0057973209_p61532138"></a><a name="en-us_topic_0057973209_p61532138"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p52543238"><a name="en-us_topic_0057973209_p52543238"></a><a name="en-us_topic_0057973209_p52543238"></a>Specifies the snapshot ID.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row3127100"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p51968558"><a name="en-us_topic_0057973209_p51968558"></a><a name="en-us_topic_0057973209_p51968558"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p48703693"><a name="en-us_topic_0057973209_p48703693"></a><a name="en-us_topic_0057973209_p48703693"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p39631152"><a name="en-us_topic_0057973209_p39631152"></a><a name="en-us_topic_0057973209_p39631152"></a>Specifies the disk metadata.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row21136050"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p34298471"><a name="en-us_topic_0057973209_p34298471"></a><a name="en-us_topic_0057973209_p34298471"></a>size</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p26712781"><a name="en-us_topic_0057973209_p26712781"></a><a name="en-us_topic_0057973209_p26712781"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p41316042"><a name="en-us_topic_0057973209_p41316042"></a><a name="en-us_topic_0057973209_p41316042"></a>Specifies the disk size.</p>
</td>
</tr>
</tbody>
</table>

**Table  3** **attachments**  field description

<a name="en-us_topic_0057973209_table10694153118228"></a>
<table><thead align="left"><tr id="en-us_topic_0057973209_row1770213111229"><th class="cellrowborder" valign="top" width="26.502650265026507%" id="mcps1.2.4.1.1"><p id="p74471434194813"><a name="p74471434194813"></a><a name="p74471434194813"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="24.81248124812481%" id="mcps1.2.4.1.2"><p id="p7463193414486"><a name="p7463193414486"></a><a name="p7463193414486"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="48.684868486848686%" id="mcps1.2.4.1.3"><p id="p746323444816"><a name="p746323444816"></a><a name="p746323444816"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0057973209_row17709183112211"><td class="cellrowborder" valign="top" width="26.502650265026507%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p5711203142219"><a name="en-us_topic_0057973209_p5711203142219"></a><a name="en-us_topic_0057973209_p5711203142219"></a>device</p>
</td>
<td class="cellrowborder" valign="top" width="24.81248124812481%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p371215313222"><a name="en-us_topic_0057973209_p371215313222"></a><a name="en-us_topic_0057973209_p371215313222"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48.684868486848686%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p87146313224"><a name="en-us_topic_0057973209_p87146313224"></a><a name="en-us_topic_0057973209_p87146313224"></a>Specifies the directory to which the disk is mounted.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row11715153182215"><td class="cellrowborder" valign="top" width="26.502650265026507%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p197177319224"><a name="en-us_topic_0057973209_p197177319224"></a><a name="en-us_topic_0057973209_p197177319224"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="24.81248124812481%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p1719183182216"><a name="en-us_topic_0057973209_p1719183182216"></a><a name="en-us_topic_0057973209_p1719183182216"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48.684868486848686%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p97211331142215"><a name="en-us_topic_0057973209_p97211331142215"></a><a name="en-us_topic_0057973209_p97211331142215"></a>Specifies the ID of the attached resource.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row117221431132216"><td class="cellrowborder" valign="top" width="26.502650265026507%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p37244312222"><a name="en-us_topic_0057973209_p37244312222"></a><a name="en-us_topic_0057973209_p37244312222"></a>serverId</p>
</td>
<td class="cellrowborder" valign="top" width="24.81248124812481%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p11726103113222"><a name="en-us_topic_0057973209_p11726103113222"></a><a name="en-us_topic_0057973209_p11726103113222"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48.684868486848686%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p18728731122219"><a name="en-us_topic_0057973209_p18728731122219"></a><a name="en-us_topic_0057973209_p18728731122219"></a>Specifies the ECS ID.</p>
</td>
</tr>
<tr id="en-us_topic_0057973209_row1729193182219"><td class="cellrowborder" valign="top" width="26.502650265026507%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0057973209_p673013122218"><a name="en-us_topic_0057973209_p673013122218"></a><a name="en-us_topic_0057973209_p673013122218"></a>volumeId</p>
</td>
<td class="cellrowborder" valign="top" width="24.81248124812481%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0057973209_p1573210319222"><a name="en-us_topic_0057973209_p1573210319222"></a><a name="en-us_topic_0057973209_p1573210319222"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="48.684868486848686%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0057973209_p97342312223"><a name="en-us_topic_0057973209_p97342312223"></a><a name="en-us_topic_0057973209_p97342312223"></a>Specifies the ID of the attached disk.</p>
</td>
</tr>
</tbody>
</table>

## Example Request<a name="en-us_topic_0057973209_section58931151"></a>

```
GET https://{endpoint}/v2/b84c367e4d1047fc9b54f28b400ddbc2/os-volumes
GET https://{endpoint}/v2.1/b84c367e4d1047fc9b54f28b400ddbc2/os-volumes
```

## Example Response<a name="section11315915113914"></a>

```
{
    "volumes": [
        {
        "status": " available",
        "attachments": [{}],
        "availabilityZone": "nova",
        "createdAt": "2016-05-20T07:57:56.299000",
        "displayDescription": null,
        "volumeType": null,
        "dispalyName": "test",
        "snapshotId": null,
        "metadata": {},
        "id": "70b14513-faad-4646-b7ab-a065cef282b4",
        "size": 1    
        }
    ]
}
```

## Returned Values<a name="en-us_topic_0057973209_en-us_topic_0020212692_section22960139"></a>

See  [Returned Values for General Requests](returned-values-for-general-requests.md).

