# Querying the Details of an Organization<a name="EN-US_TOPIC_0198655133"></a>

## Function<a name="section14905762191056"></a>

Query the details of an organization.

## URI<a name="section10482810165331"></a>

GET /v2/manage/namespaces/\{_namespace_\}

For details about parameters, see  [Table 1](#table05962819187).

**Table  1**  Parameter description

<a name="table05962819187"></a>
<table><thead align="left"><tr id="row18599289181"><th class="cellrowborder" valign="top" width="21.272127212721273%" id="mcps1.2.5.1.1"><p id="p145942820183"><a name="p145942820183"></a><a name="p145942820183"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="19.351935193519353%" id="mcps1.2.5.1.2"><p id="p14796031194218"><a name="p14796031194218"></a><a name="p14796031194218"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="19.08190819081908%" id="mcps1.2.5.1.3"><p id="p1311119571031"><a name="p1311119571031"></a><a name="p1311119571031"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="40.29402940294029%" id="mcps1.2.5.1.4"><p id="p205910283185"><a name="p205910283185"></a><a name="p205910283185"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row146018284188"><td class="cellrowborder" valign="top" width="21.272127212721273%" headers="mcps1.2.5.1.1 "><p id="p0601928131816"><a name="p0601928131816"></a><a name="p0601928131816"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="19.351935193519353%" headers="mcps1.2.5.1.2 "><p id="p48011931194218"><a name="p48011931194218"></a><a name="p48011931194218"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="19.08190819081908%" headers="mcps1.2.5.1.3 "><p id="p1611814571310"><a name="p1611814571310"></a><a name="p1611814571310"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="40.29402940294029%" headers="mcps1.2.5.1.4 "><p id="p16705925111218"><a name="p16705925111218"></a><a name="p16705925111218"></a>Organization name.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="section3270966102931"></a>

N/A

## Response<a name="section46271297104114"></a>

**Response parameters**

**Table  2**  Response body parameter description

<a name="table1787854911167"></a>
<table><thead align="left"><tr id="row1588184916165"><th class="cellrowborder" valign="top" width="21%" id="mcps1.2.4.1.1"><p id="p158847496166"><a name="p158847496166"></a><a name="p158847496166"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.4.1.2"><p id="p2088624911169"><a name="p2088624911169"></a><a name="p2088624911169"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="59%" id="mcps1.2.4.1.3"><p id="p128875496169"><a name="p128875496169"></a><a name="p128875496169"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row888994917169"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.4.1.1 "><p id="p1889144915167"><a name="p1889144915167"></a><a name="p1889144915167"></a>id</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p149251254972"><a name="p149251254972"></a><a name="p149251254972"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.4.1.3 "><p id="p14894149141612"><a name="p14894149141612"></a><a name="p14894149141612"></a>ID</p>
</td>
</tr>
<tr id="row19895649171616"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.4.1.1 "><p id="p589616491166"><a name="p589616491166"></a><a name="p589616491166"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p792511543713"><a name="p792511543713"></a><a name="p792511543713"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.4.1.3 "><p id="p2904184981613"><a name="p2904184981613"></a><a name="p2904184981613"></a>Organization name</p>
</td>
</tr>
<tr id="row1576047252"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.4.1.1 "><p id="p3578164162517"><a name="p3578164162517"></a><a name="p3578164162517"></a>creator_name</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p8578134122515"><a name="p8578134122515"></a><a name="p8578134122515"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.4.1.3 "><p id="p1557814492513"><a name="p1557814492513"></a><a name="p1557814492513"></a>Username</p>
</td>
</tr>
<tr id="row670815227263"><td class="cellrowborder" valign="top" width="21%" headers="mcps1.2.4.1.1 "><p id="p270822232620"><a name="p270822232620"></a><a name="p270822232620"></a>auth</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.4.1.2 "><p id="p11708622162613"><a name="p11708622162613"></a><a name="p11708622162613"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="59%" headers="mcps1.2.4.1.3 "><p id="p3709822102615"><a name="p3709822102615"></a><a name="p3709822102615"></a>User permission. The value can be 1, 3, or 7. <strong id="b7199814115011"><a name="b7199814115011"></a><a name="b7199814115011"></a>7</strong>: manage <strong id="b7696624104213"><a name="b7696624104213"></a><a name="b7696624104213"></a>3</strong>: write <strong id="b126501438134218"><a name="b126501438134218"></a><a name="b126501438134218"></a>1</strong>: read</p>
</td>
</tr>
</tbody>
</table>

**Response example**

```
{
    "id": 1422,
    "name": "otc",
    "creator_name": "username",
    "auth": 7
}
```

## Status Code<a name="section5365169104253"></a>

For details about status code, see  [Table 3](#t33d02fa79e8443868a71c99f411610a5).

**Table  3**  Status code

<a name="t33d02fa79e8443868a71c99f411610a5"></a>
<table><thead align="left"><tr id="r9eb80d64e8f34d0db940daa95fc929dd"><th class="cellrowborder" valign="top" width="16.439999999999998%" id="mcps1.2.3.1.1"><p id="a7e51ed73a71e4dc29d0dd4aae3016632"><a name="a7e51ed73a71e4dc29d0dd4aae3016632"></a><a name="a7e51ed73a71e4dc29d0dd4aae3016632"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="83.56%" id="mcps1.2.3.1.2"><p id="aa802d02e21c944f1863435a0d11c7ec1"><a name="aa802d02e21c944f1863435a0d11c7ec1"></a><a name="aa802d02e21c944f1863435a0d11c7ec1"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r1cc0192c651444db882dde750b14be23"><td class="cellrowborder" valign="top" width="16.439999999999998%" headers="mcps1.2.3.1.1 "><p id="a6a3639a3cb154e17b95c5076c8036471"><a name="a6a3639a3cb154e17b95c5076c8036471"></a><a name="a6a3639a3cb154e17b95c5076c8036471"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="83.56%" headers="mcps1.2.3.1.2 "><p id="ad54ae639e7f94380a87bfc10cc91a4f0"><a name="ad54ae639e7f94380a87bfc10cc91a4f0"></a><a name="ad54ae639e7f94380a87bfc10cc91a4f0"></a>Operation successful.</p>
</td>
</tr>
<tr id="r0bd68000afe546dd9c7a8d3a05991a04"><td class="cellrowborder" valign="top" width="16.439999999999998%" headers="mcps1.2.3.1.1 "><p id="ad46ccdc6b7e04df3b6b5679f7606f434"><a name="ad46ccdc6b7e04df3b6b5679f7606f434"></a><a name="ad46ccdc6b7e04df3b6b5679f7606f434"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="83.56%" headers="mcps1.2.3.1.2 "><p id="a1f2e8d58145d461781428d28f07a5351"><a name="a1f2e8d58145d461781428d28f07a5351"></a><a name="a1f2e8d58145d461781428d28f07a5351"></a>Request error.</p>
</td>
</tr>
<tr id="row059261364320"><td class="cellrowborder" valign="top" width="16.439999999999998%" headers="mcps1.2.3.1.1 "><p id="p059261310438"><a name="p059261310438"></a><a name="p059261310438"></a>401</p>
</td>
<td class="cellrowborder" valign="top" width="83.56%" headers="mcps1.2.3.1.2 "><p id="p759261314433"><a name="p759261314433"></a><a name="p759261314433"></a>Authentication failed.</p>
</td>
</tr>
<tr id="row9547111612437"><td class="cellrowborder" valign="top" width="16.439999999999998%" headers="mcps1.2.3.1.1 "><p id="p19547131615432"><a name="p19547131615432"></a><a name="p19547131615432"></a>404</p>
</td>
<td class="cellrowborder" valign="top" width="83.56%" headers="mcps1.2.3.1.2 "><p id="p16547416114315"><a name="p16547416114315"></a><a name="p16547416114315"></a>The organization does not exist.</p>
</td>
</tr>
<tr id="r19bdef782c164c93917f897241e521f8"><td class="cellrowborder" valign="top" width="16.439999999999998%" headers="mcps1.2.3.1.1 "><p id="a7da68e311c0f4267bacf3cbdb71d1ead"><a name="a7da68e311c0f4267bacf3cbdb71d1ead"></a><a name="a7da68e311c0f4267bacf3cbdb71d1ead"></a>500</p>
</td>
<td class="cellrowborder" valign="top" width="83.56%" headers="mcps1.2.3.1.2 "><p id="aa6fd12cedd8841e29eeeca27c1bdea1a"><a name="aa6fd12cedd8841e29eeeca27c1bdea1a"></a><a name="aa6fd12cedd8841e29eeeca27c1bdea1a"></a>Internal error.</p>
</td>
</tr>
</tbody>
</table>

