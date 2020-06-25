# Querying a Firewall Rule<a name="vpc_firewall_0002"></a>

## Function<a name="section65879037122957"></a>

This API is used to query details about a specific firewall rule.

## URI<a name="section46813763122957"></a>

GET /v2.0/fwaas/firewall\_rules/\{firewall\_rule\_id\}

[Table 1](#table18880184689)  describes the parameters.

**Table  1**  Parameter description

<a name="table18880184689"></a>
<table><thead align="left"><tr id="row13968641385"><th class="cellrowborder" valign="top" width="22.222222222222225%" id="mcps1.2.5.1.1"><p id="p209684410817"><a name="p209684410817"></a><a name="p209684410817"></a><strong id="b842352706195711"><a name="b842352706195711"></a><a name="b842352706195711"></a>Name</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.14141414141414%" id="mcps1.2.5.1.2"><p id="p69681441386"><a name="p69681441386"></a><a name="p69681441386"></a><strong id="b84235270615219"><a name="b84235270615219"></a><a name="b84235270615219"></a>Mandatory</strong></p>
</th>
<th class="cellrowborder" valign="top" width="27.27272727272727%" id="mcps1.2.5.1.3"><p id="p1096813412811"><a name="p1096813412811"></a><a name="p1096813412811"></a><strong id="b842352706145623"><a name="b842352706145623"></a><a name="b842352706145623"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="36.36363636363636%" id="mcps1.2.5.1.4"><p id="p139686416813"><a name="p139686416813"></a><a name="p139686416813"></a><strong id="b8423527061645"><a name="b8423527061645"></a><a name="b8423527061645"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row19681041189"><td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.2.5.1.1 "><p id="p1682422682817"><a name="p1682422682817"></a><a name="p1682422682817"></a>firewall_rule_id</p>
</td>
<td class="cellrowborder" valign="top" width="14.14141414141414%" headers="mcps1.2.5.1.2 "><p id="p1797015416817"><a name="p1797015416817"></a><a name="p1797015416817"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="27.27272727272727%" headers="mcps1.2.5.1.3 "><p id="p19701411813"><a name="p19701411813"></a><a name="p19701411813"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="36.36363636363636%" headers="mcps1.2.5.1.4 "><p id="p158091718125714"><a name="p158091718125714"></a><a name="p158091718125714"></a>Specifies the firewall rule ID, which uniquely identifies the firewall rule. The <strong id="b7553152154311"><a name="b7553152154311"></a><a name="b7553152154311"></a>firewall_rule_id</strong> value is used as the filter.</p>
</td>
</tr>
</tbody>
</table>

## Request Message<a name="section25083919122957"></a>

None

## Response Message<a name="section24140738122957"></a>

**Table  2**  Response parameter

<a name="table22071969122957"></a>
<table><thead align="left"><tr id="row27211568122957"><th class="cellrowborder" valign="top" width="21.349999999999998%" id="mcps1.2.4.1.1"><p id="p41925459122957"><a name="p41925459122957"></a><a name="p41925459122957"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="19.11%" id="mcps1.2.4.1.2"><p id="p18784029122957"><a name="p18784029122957"></a><a name="p18784029122957"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="59.540000000000006%" id="mcps1.2.4.1.3"><p id="p64308775122957"><a name="p64308775122957"></a><a name="p64308775122957"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row14692262122957"><td class="cellrowborder" valign="top" width="21.349999999999998%" headers="mcps1.2.4.1.1 "><p id="p36226380122957"><a name="p36226380122957"></a><a name="p36226380122957"></a>firewall_rule</p>
</td>
<td class="cellrowborder" valign="top" width="19.11%" headers="mcps1.2.4.1.2 "><p id="p60366906122957"><a name="p60366906122957"></a><a name="p60366906122957"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="59.540000000000006%" headers="mcps1.2.4.1.3 "><p id="p61314665122957"><a name="p61314665122957"></a><a name="p61314665122957"></a>Specifies the firewall rule objects. For details, see <a href="#table38646929121127">Table 3</a>.</p>
</td>
</tr>
</tbody>
</table>

**Table  3** **Firewall Rule**  objects

<a name="table38646929121127"></a>
<table><thead align="left"><tr id="row18263398121127"><th class="cellrowborder" valign="top" width="32.76%" id="mcps1.2.4.1.1"><p id="p2027461121127"><a name="p2027461121127"></a><a name="p2027461121127"></a><strong id="b131671821192220"><a name="b131671821192220"></a><a name="b131671821192220"></a>Attribute</strong></p>
</th>
<th class="cellrowborder" valign="top" width="20.69%" id="mcps1.2.4.1.2"><p id="p51747644121127"><a name="p51747644121127"></a><a name="p51747644121127"></a><strong id="b7134162222211"><a name="b7134162222211"></a><a name="b7134162222211"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="46.550000000000004%" id="mcps1.2.4.1.3"><p id="p12805757121127"><a name="p12805757121127"></a><a name="p12805757121127"></a><strong id="b685572315226"><a name="b685572315226"></a><a name="b685572315226"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row39528007121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p7362024121127"><a name="p7362024121127"></a><a name="p7362024121127"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p53278848121127"><a name="p53278848121127"></a><a name="p53278848121127"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p13095685121127"><a name="p13095685121127"></a><a name="p13095685121127"></a>Specifies the UUID of the firewall rule.</p>
</td>
</tr>
<tr id="row3417421121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p16296528121127"><a name="p16296528121127"></a><a name="p16296528121127"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p52887833121127"><a name="p52887833121127"></a><a name="p52887833121127"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p29399172121127"><a name="p29399172121127"></a><a name="p29399172121127"></a>Specifies the firewall rule name.</p>
</td>
</tr>
<tr id="row33772147121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p62102623121127"><a name="p62102623121127"></a><a name="p62102623121127"></a>description</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p30062050121127"><a name="p30062050121127"></a><a name="p30062050121127"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p64485971121127"><a name="p64485971121127"></a><a name="p64485971121127"></a>Provides supplementary information about the firewall rule.</p>
</td>
</tr>
<tr id="row39157453121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p40485546121127"><a name="p40485546121127"></a><a name="p40485546121127"></a>tenant_id</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p20366062121127"><a name="p20366062121127"></a><a name="p20366062121127"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p10487112"><a name="p10487112"></a><a name="p10487112"></a>Specifies the project ID.</p>
</td>
</tr>
<tr id="row13612334121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p3945861121127"><a name="p3945861121127"></a><a name="p3945861121127"></a>public</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p53059091121127"><a name="p53059091121127"></a><a name="p53059091121127"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p46007536121127"><a name="p46007536121127"></a><a name="p46007536121127"></a>Specifies whether the firewall rule can be shared by different tenants.</p>
</td>
</tr>
<tr id="row66347377121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p7361769121127"><a name="p7361769121127"></a><a name="p7361769121127"></a>protocol</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p50019959121127"><a name="p50019959121127"></a><a name="p50019959121127"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p36897817121127"><a name="p36897817121127"></a><a name="p36897817121127"></a>Specifies the IP protocol.</p>
</td>
</tr>
<tr id="row8703753121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p5943474121127"><a name="p5943474121127"></a><a name="p5943474121127"></a>source_port</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p59206978121127"><a name="p59206978121127"></a><a name="p59206978121127"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p62826249121127"><a name="p62826249121127"></a><a name="p62826249121127"></a>Specifies the source port number or port number range.</p>
</td>
</tr>
<tr id="row52935496121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p12876203121127"><a name="p12876203121127"></a><a name="p12876203121127"></a>destination_port</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p66631365121127"><a name="p66631365121127"></a><a name="p66631365121127"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p66851026121127"><a name="p66851026121127"></a><a name="p66851026121127"></a>Specifies the destination port number or port number range.</p>
</td>
</tr>
<tr id="row37973187121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p18090983121127"><a name="p18090983121127"></a><a name="p18090983121127"></a>ip_version</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p15064211121127"><a name="p15064211121127"></a><a name="p15064211121127"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p10402054121127"><a name="p10402054121127"></a><a name="p10402054121127"></a>Specifies the IP protocol version.</p>
</td>
</tr>
<tr id="row34581454121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p61377852121127"><a name="p61377852121127"></a><a name="p61377852121127"></a>source_ip_address</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p36483585121127"><a name="p36483585121127"></a><a name="p36483585121127"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p31475962121127"><a name="p31475962121127"></a><a name="p31475962121127"></a>Specifies the source IP address or CIDR block.</p>
</td>
</tr>
<tr id="row13949121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p43901244121127"><a name="p43901244121127"></a><a name="p43901244121127"></a>destination_ip_address</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p14651426121127"><a name="p14651426121127"></a><a name="p14651426121127"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p53743554121127"><a name="p53743554121127"></a><a name="p53743554121127"></a>Specifies the destination IP address or CIDR block.</p>
</td>
</tr>
<tr id="row33223843121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p40131900121127"><a name="p40131900121127"></a><a name="p40131900121127"></a>action</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p952780121127"><a name="p952780121127"></a><a name="p952780121127"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p16135729121127"><a name="p16135729121127"></a><a name="p16135729121127"></a>Specifies action performed on traffic passing through the firewall.</p>
</td>
</tr>
<tr id="row11398101121127"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p50347088121127"><a name="p50347088121127"></a><a name="p50347088121127"></a>enabled</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p46161809121127"><a name="p46161809121127"></a><a name="p46161809121127"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p57324252121127"><a name="p57324252121127"></a><a name="p57324252121127"></a>Specifies whether the firewall rule is enabled.</p>
</td>
</tr>
<tr id="row1574912215580"><td class="cellrowborder" valign="top" width="32.76%" headers="mcps1.2.4.1.1 "><p id="p1312116475819"><a name="p1312116475819"></a><a name="p1312116475819"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="20.69%" headers="mcps1.2.4.1.2 "><p id="p5125543583"><a name="p5125543583"></a><a name="p5125543583"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46.550000000000004%" headers="mcps1.2.4.1.3 "><p id="p47094254282"><a name="p47094254282"></a><a name="p47094254282"></a>Specifies the project ID. </p>
</td>
</tr>
</tbody>
</table>

## Example:<a name="section16344236122957"></a>

Example request

```
GET https://{Endpoint}/v2.0/fwaas/firewall_rules/514e6776-162a-4b5d-ab8b-aa36b86655ef
```

Example response

```
{
    "firewall_rule": {
        "protocol": "tcp", 
        "name": "bobby_rule", 
        "mode": "normal", 
        "tenant_id": "4490a89232ce46d4ae4bfb227ef1a40a", 
        "rule_profile": "", 
        "enabled": true, 
        "source_port": null, 
        "source_ip_address": null, 
        "destination_ip_address": null, 
        "firewall_policy_id": null, 
        "action": "allow", 
        "position": null, 
        "ip_version": 4, 
        "shared": false, 
        "destination_port": null, 
        "id": "514e6776-162a-4b5d-ab8b-aa36b86655ef", 
        "description": "",
        "project_id": "4490a89232ce46d4ae4bfb227ef1a40a"
    }
}
```

## Status Code<a name="section10470352390"></a>

See  [Status Codes](status-codes.md).

## Error Code<a name="section85821649202813"></a>

See  [Error Codes](error-codes.md).

