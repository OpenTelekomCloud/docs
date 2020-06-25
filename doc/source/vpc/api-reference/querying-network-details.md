# Querying Network Details<a name="vpc_network_0002"></a>

## Function<a name="section58515065204939"></a>

This API is used to query details about a network.

## URI<a name="section43354202204939"></a>

GET /v2.0/networks/\{network\_id\}

[Table 1](#table1710134691014)  describes the parameters.

**Table  1**  Parameter description

<a name="table1710134691014"></a>
<table><thead align="left"><tr id="row1775694617109"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p775644621011"><a name="p775644621011"></a><a name="p775644621011"></a><strong id="b78438591578"><a name="b78438591578"></a><a name="b78438591578"></a>Name</strong></p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p575674618101"><a name="p575674618101"></a><a name="p575674618101"></a><strong id="b75895085819"><a name="b75895085819"></a><a name="b75895085819"></a>Mandatory</strong></p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p17568468102"><a name="p17568468102"></a><a name="p17568468102"></a><strong id="b154271011583"><a name="b154271011583"></a><a name="b154271011583"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row875634651011"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p8756154610104"><a name="p8756154610104"></a><a name="p8756154610104"></a>network_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p37561846191013"><a name="p37561846191013"></a><a name="p37561846191013"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p1375624661014"><a name="p1375624661014"></a><a name="p1375624661014"></a>Specifies the network ID.</p>
</td>
</tr>
</tbody>
</table>

## Request Message<a name="section29238419204939"></a>

None

## Response Message<a name="section41298168204939"></a>

**Table  2**  Response parameter

<a name="table56817282204939"></a>
<table><thead align="left"><tr id="row35431593204939"><th class="cellrowborder" valign="top" width="21.59%" id="mcps1.2.4.1.1"><p id="p51386807204939"><a name="p51386807204939"></a><a name="p51386807204939"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="13.63%" id="mcps1.2.4.1.2"><p id="p1581813204939"><a name="p1581813204939"></a><a name="p1581813204939"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="64.78%" id="mcps1.2.4.1.3"><p id="p43510562204939"><a name="p43510562204939"></a><a name="p43510562204939"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row34694625204939"><td class="cellrowborder" valign="top" width="21.59%" headers="mcps1.2.4.1.1 "><p id="p58801265204939"><a name="p58801265204939"></a><a name="p58801265204939"></a>network</p>
</td>
<td class="cellrowborder" valign="top" width="13.63%" headers="mcps1.2.4.1.2 "><p id="p65282042204939"><a name="p65282042204939"></a><a name="p65282042204939"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="64.78%" headers="mcps1.2.4.1.3 "><p id="p26708244204939"><a name="p26708244204939"></a><a name="p26708244204939"></a>Specifies the network list. For details, see <a href="#table49902238182444">Table 3</a>.</p>
</td>
</tr>
</tbody>
</table>

**Table  3** **network**  objects

<a name="table49902238182444"></a>
<table><thead align="left"><tr id="row27727643182444"><th class="cellrowborder" valign="top" width="26.22737726227377%" id="mcps1.2.4.1.1"><p id="p31346634182444"><a name="p31346634182444"></a><a name="p31346634182444"></a><strong id="b0359166576"><a name="b0359166576"></a><a name="b0359166576"></a>Attribute</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22.957704229577043%" id="mcps1.2.4.1.2"><p id="p56049421182444"><a name="p56049421182444"></a><a name="p56049421182444"></a><strong id="b16423162918571"><a name="b16423162918571"></a><a name="b16423162918571"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50.81491850814919%" id="mcps1.2.4.1.3"><p id="p32650631182444"><a name="p32650631182444"></a><a name="p32650631182444"></a><strong id="b15221930145714"><a name="b15221930145714"></a><a name="b15221930145714"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row27455432182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p9297551182444"><a name="p9297551182444"></a><a name="p9297551182444"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p14904129182444"><a name="p14904129182444"></a><a name="p14904129182444"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p19312361182444"><a name="p19312361182444"></a><a name="p19312361182444"></a>Specifies the network status. The value can be <strong id="b7735193355712"><a name="b7735193355712"></a><a name="b7735193355712"></a>ACTIVE</strong>, <strong id="b17362033175715"><a name="b17362033175715"></a><a name="b17362033175715"></a>BUILD</strong>, <strong id="b57371133115719"><a name="b57371133115719"></a><a name="b57371133115719"></a>DOWN</strong>, or <strong id="b273819338575"><a name="b273819338575"></a><a name="b273819338575"></a>ERROR</strong>.</p>
</td>
</tr>
<tr id="row39593523182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p52958822182444"><a name="p52958822182444"></a><a name="p52958822182444"></a>subnets</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p13041033737"><a name="p13041033737"></a><a name="p13041033737"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p61280841182444"><a name="p61280841182444"></a><a name="p61280841182444"></a>Specifies IDs of the subnets associated with this network. The IDs are in a list.</p>
<p id="p14656663182444"><a name="p14656663182444"></a><a name="p14656663182444"></a>Only one subnet can be associated with each network.</p>
</td>
</tr>
<tr id="row64801111182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p14398613182444"><a name="p14398613182444"></a><a name="p14398613182444"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p25436971182444"><a name="p25436971182444"></a><a name="p25436971182444"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p59079578182444"><a name="p59079578182444"></a><a name="p59079578182444"></a>Specifies the network name.</p>
<p id="p61954155182444"><a name="p61954155182444"></a><a name="p61954155182444"></a>The name cannot be <strong id="b3786442185710"><a name="b3786442185710"></a><a name="b3786442185710"></a>admin_external_net</strong>.</p>
</td>
</tr>
<tr id="row20716483182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p313524182444"><a name="p313524182444"></a><a name="p313524182444"></a>router:external</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p25395478182444"><a name="p25395478182444"></a><a name="p25395478182444"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p17174434182444"><a name="p17174434182444"></a><a name="p17174434182444"></a>Specifies whether the network is an external network. This is an extended attribute.</p>
</td>
</tr>
<tr id="row48951951182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p5685084182444"><a name="p5685084182444"></a><a name="p5685084182444"></a>admin_state_up</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p57838641182444"><a name="p57838641182444"></a><a name="p57838641182444"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p52254844182444"><a name="p52254844182444"></a><a name="p52254844182444"></a>Specifies the administrative status.</p>
<p id="p531550182444"><a name="p531550182444"></a><a name="p531550182444"></a>The value can only be <strong id="b1569671019587"><a name="b1569671019587"></a><a name="b1569671019587"></a>true</strong>.</p>
</td>
</tr>
<tr id="row4783956182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p51956132182444"><a name="p51956132182444"></a><a name="p51956132182444"></a>tenant_id</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p47697173182444"><a name="p47697173182444"></a><a name="p47697173182444"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p10487112"><a name="p10487112"></a><a name="p10487112"></a>Specifies the project ID. </p>
</td>
</tr>
<tr id="row42537647182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p22997365182444"><a name="p22997365182444"></a><a name="p22997365182444"></a>shared</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p50847313182444"><a name="p50847313182444"></a><a name="p50847313182444"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p8672810182444"><a name="p8672810182444"></a><a name="p8672810182444"></a>Specifies whether the firewall rule can be shared by different tenants.</p>
</td>
</tr>
<tr id="row31409028182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p61103330182444"><a name="p61103330182444"></a><a name="p61103330182444"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p50422701182444"><a name="p50422701182444"></a><a name="p50422701182444"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p31263412182444"><a name="p31263412182444"></a><a name="p31263412182444"></a>Specifies the network ID.</p>
<p id="p311313148445"><a name="p311313148445"></a><a name="p311313148445"></a>This parameter is not mandatory when you query networks.</p>
</td>
</tr>
<tr id="row62882662182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p60330876182444"><a name="p60330876182444"></a><a name="p60330876182444"></a>provider:network_type</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p54962794182444"><a name="p54962794182444"></a><a name="p54962794182444"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p3680057182444"><a name="p3680057182444"></a><a name="p3680057182444"></a>Specifies the network type. Only the VXLAN and GENEVE networks are supported. This is an extended attribute.</p>
<p id="p33120518182444"><a name="p33120518182444"></a><a name="p33120518182444"></a>Tenants can create only networks whose type is <strong id="b1779434145815"><a name="b1779434145815"></a><a name="b1779434145815"></a>geneve</strong>.</p>
</td>
</tr>
<tr id="row8468164182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p14832653182444"><a name="p14832653182444"></a><a name="p14832653182444"></a>availability_zone_hints</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p60594206182444"><a name="p60594206182444"></a><a name="p60594206182444"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p8008921182444"><a name="p8008921182444"></a><a name="p8008921182444"></a>Specifies the availability zones available to this network. The current version does not support cross-availability-zone network scheduling.</p>
</td>
</tr>
<tr id="row44742828182444"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p290489182444"><a name="p290489182444"></a><a name="p290489182444"></a>availability_zones</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p64601459312"><a name="p64601459312"></a><a name="p64601459312"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p24927678182444"><a name="p24927678182444"></a><a name="p24927678182444"></a>Specifies the availability zone of this network.</p>
</td>
</tr>
<tr id="row25641034212156"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p53737204212156"><a name="p53737204212156"></a><a name="p53737204212156"></a>port_security_enabled</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p31320715212156"><a name="p31320715212156"></a><a name="p31320715212156"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p34506445212156"><a name="p34506445212156"></a><a name="p34506445212156"></a>Specifies whether the security option is enabled for the port. If the option is not enabled, the security group and DHCP snooping settings of all VMs in the network do not take effect.</p>
</td>
</tr>
<tr id="row421706155213"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p14217767523"><a name="p14217767523"></a><a name="p14217767523"></a>dns_domain</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p22172685219"><a name="p22172685219"></a><a name="p22172685219"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p021812614525"><a name="p021812614525"></a><a name="p021812614525"></a>Specifies the default private network DNS domain address. The system automatically sets this parameter, and you are not allowed to configure or change the parameter value.</p>
</td>
</tr>
<tr id="row1312882941114"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p870051413911"><a name="p870051413911"></a><a name="p870051413911"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p15700614790"><a name="p15700614790"></a><a name="p15700614790"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p1628911198243"><a name="p1628911198243"></a><a name="p1628911198243"></a>Specifies the project ID. </p>
</td>
</tr>
<tr id="row9120034101119"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p1953114119914"><a name="p1953114119914"></a><a name="p1953114119914"></a>created_at</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p595318416919"><a name="p595318416919"></a><a name="p595318416919"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p1395374115919"><a name="p1395374115919"></a><a name="p1395374115919"></a>Specifies the time (UTC) when the network is created.</p>
<p id="p65980291419"><a name="p65980291419"></a><a name="p65980291419"></a>Format: <em id="i201321387595"><a name="i201321387595"></a><a name="i201321387595"></a>yyyy-MM-ddTHH:mm:ss</em></p>
</td>
</tr>
<tr id="row1542863714112"><td class="cellrowborder" valign="top" width="26.22737726227377%" headers="mcps1.2.4.1.1 "><p id="p139719548912"><a name="p139719548912"></a><a name="p139719548912"></a>updated_at</p>
</td>
<td class="cellrowborder" valign="top" width="22.957704229577043%" headers="mcps1.2.4.1.2 "><p id="p53971154594"><a name="p53971154594"></a><a name="p53971154594"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50.81491850814919%" headers="mcps1.2.4.1.3 "><p id="p1339713549918"><a name="p1339713549918"></a><a name="p1339713549918"></a>Specifies the time (UTC) when the network is updated.</p>
<p id="p16955446144511"><a name="p16955446144511"></a><a name="p16955446144511"></a>Format: <em id="i94181115205916"><a name="i94181115205916"></a><a name="i94181115205916"></a>yyyy-MM-ddTHH:mm:ss</em></p>
</td>
</tr>
</tbody>
</table>

## Example:<a name="section39047607204939"></a>

Example request

```
GET https://{Endpoint}/v2.0/networks/0133cd73-34d4-4d4c-bf1f-e65b24603206
```

Example response

```
{
    "network": {
        "id": "0133cd73-34d4-4d4c-bf1f-e65b24603206",
        "name": "3804f26c-7862-43b6-ad3c-48445f42de89",
        "status": "ACTIVE",
        "shared": false,
        "subnets": [
            "423796f5-e02f-476f-bf02-2b88c8ddac8b"
        ],
        "availability_zone_hints": [],
        "availability_zones": [
            "az2.dc2",
            "az5.dc5"
        ],
        "admin_state_up": true,
        "tenant_id": "bbfe8c41dd034a07bebd592bf03b4b0c",
        "project_id": "bbfe8c41dd034a07bebd592bf03b4b0c",
        "provider:network_type": "vxlan",
        "router:external": false,
        "port_security_enabled": true,
        "created_at": "2018-03-23T03:51:58",
        "updated_at": "2018-03-23T03:51:58"
    }
}
```

## Status Code<a name="section10470352390"></a>

See  [Status Codes](status-codes.md).

## Error Code<a name="section85821649202813"></a>

See  [Error Codes](error-codes.md).

