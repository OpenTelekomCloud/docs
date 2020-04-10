# Data Structure of Response Parameters<a name="cce_02_0014"></a>

**Table  1**  Response parameters of v1.ReplicationController

<a name="en-us_topic_0079614930_table30479638"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row17250336"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p55099937"><a name="en-us_topic_0079614930_p55099937"></a><a name="en-us_topic_0079614930_p55099937"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.2.4.1.2"><p id="p2081516115913"><a name="p2081516115913"></a><a name="p2081516115913"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="p6941625918"><a name="p6941625918"></a><a name="p6941625918"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row17017832"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p36267164"><a name="en-us_topic_0079614930_p36267164"></a><a name="en-us_topic_0079614930_p36267164"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p51959135"><a name="en-us_topic_0079614930_p51959135"></a><a name="en-us_topic_0079614930_p51959135"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p47940444"><a name="en-us_topic_0079614930_p47940444"></a><a name="en-us_topic_0079614930_p47940444"></a>A string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row28810815"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p51974659"><a name="en-us_topic_0079614930_p51974659"></a><a name="en-us_topic_0079614930_p51974659"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p49197844"><a name="en-us_topic_0079614930_p49197844"></a><a name="en-us_topic_0079614930_p49197844"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p25602393"><a name="en-us_topic_0079614930_p25602393"></a><a name="en-us_topic_0079614930_p25602393"></a>Versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row29094946"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p7880465"><a name="en-us_topic_0079614930_p7880465"></a><a name="en-us_topic_0079614930_p7880465"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="ad4828131a16d41e69a201fb59acb84b1"><a name="ad4828131a16d41e69a201fb59acb84b1"></a><a name="ad4828131a16d41e69a201fb59acb84b1"></a><a href="#en-us_topic_0079614930_table33054158">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p29911441"><a name="en-us_topic_0079614930_p29911441"></a><a name="en-us_topic_0079614930_p29911441"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row767514"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p62168702"><a name="en-us_topic_0079614930_p62168702"></a><a name="en-us_topic_0079614930_p62168702"></a>spec</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="a852b4cee31114f1d866358bf2b02f4ce"><a name="a852b4cee31114f1d866358bf2b02f4ce"></a><a name="a852b4cee31114f1d866358bf2b02f4ce"></a><a href="#en-us_topic_0079614930_table29051967">spec</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p1181723"><a name="en-us_topic_0079614930_p1181723"></a><a name="en-us_topic_0079614930_p1181723"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row10635509"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p56169928"><a name="en-us_topic_0079614930_p56169928"></a><a name="en-us_topic_0079614930_p56169928"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="a2acd19948102428eb77c860c56acaaa2"><a name="a2acd19948102428eb77c860c56acaaa2"></a><a name="a2acd19948102428eb77c860c56acaaa2"></a><a href="#en-us_topic_0079614930_table60141117">status</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p36126934"><a name="en-us_topic_0079614930_p36126934"></a><a name="en-us_topic_0079614930_p36126934"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  2**  Response parameters of v1.ReplicationControllerList

<a name="en-us_topic_0079614930_table5881294"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row24610089"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p47260226"><a name="en-us_topic_0079614930_p47260226"></a><a name="en-us_topic_0079614930_p47260226"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p151861612595"><a name="p151861612595"></a><a name="p151861612595"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p21951613594"><a name="p21951613594"></a><a name="p21951613594"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row59951591"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24240706"><a name="en-us_topic_0079614930_p24240706"></a><a name="en-us_topic_0079614930_p24240706"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p17340145"><a name="en-us_topic_0079614930_p17340145"></a><a name="en-us_topic_0079614930_p17340145"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p62374493"><a name="en-us_topic_0079614930_p62374493"></a><a name="en-us_topic_0079614930_p62374493"></a>A string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row24499525"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p38304470"><a name="en-us_topic_0079614930_p38304470"></a><a name="en-us_topic_0079614930_p38304470"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p15654360"><a name="en-us_topic_0079614930_p15654360"></a><a name="en-us_topic_0079614930_p15654360"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p60043634"><a name="en-us_topic_0079614930_p60043634"></a><a name="en-us_topic_0079614930_p60043634"></a>Versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row3521800"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p16830394"><a name="en-us_topic_0079614930_p16830394"></a><a name="en-us_topic_0079614930_p16830394"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="ae27c756c3e8c4d7b8b72cbd440b20c9e"><a name="ae27c756c3e8c4d7b8b72cbd440b20c9e"></a><a name="ae27c756c3e8c4d7b8b72cbd440b20c9e"></a><a href="#en-us_topic_0079614930_table66688435">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p30138892"><a name="en-us_topic_0079614930_p30138892"></a><a name="en-us_topic_0079614930_p30138892"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row2814577"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p26654174"><a name="en-us_topic_0079614930_p26654174"></a><a name="en-us_topic_0079614930_p26654174"></a>items</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a65502d1935b94750b218e45e0b2d6903"><a name="a65502d1935b94750b218e45e0b2d6903"></a><a name="a65502d1935b94750b218e45e0b2d6903"></a><a href="#en-us_topic_0079614930_table63325007">items</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p59446649"><a name="en-us_topic_0079614930_p59446649"></a><a name="en-us_topic_0079614930_p59446649"></a>List of replication controllers.</p>
</td>
</tr>
</tbody>
</table>

**Table  3**  Response parameters of v1.Pod

<a name="en-us_topic_0079614930_table52931650"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row16588560"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p1496135"><a name="en-us_topic_0079614930_p1496135"></a><a name="en-us_topic_0079614930_p1496135"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1227141610599"><a name="p1227141610599"></a><a name="p1227141610599"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1627171645913"><a name="p1627171645913"></a><a name="p1627171645913"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row2109304"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p36635921"><a name="en-us_topic_0079614930_p36635921"></a><a name="en-us_topic_0079614930_p36635921"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p14719623"><a name="en-us_topic_0079614930_p14719623"></a><a name="en-us_topic_0079614930_p14719623"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p51438785"><a name="en-us_topic_0079614930_p51438785"></a><a name="en-us_topic_0079614930_p51438785"></a>A string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row60295883"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p52128359"><a name="en-us_topic_0079614930_p52128359"></a><a name="en-us_topic_0079614930_p52128359"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p61647547"><a name="en-us_topic_0079614930_p61647547"></a><a name="en-us_topic_0079614930_p61647547"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p27395440"><a name="en-us_topic_0079614930_p27395440"></a><a name="en-us_topic_0079614930_p27395440"></a>Versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row45232374"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p39943711"><a name="en-us_topic_0079614930_p39943711"></a><a name="en-us_topic_0079614930_p39943711"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p14215164"><a name="en-us_topic_0079614930_p14215164"></a><a name="en-us_topic_0079614930_p14215164"></a><a href="#en-us_topic_0079614930_table33054158">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p10577654"><a name="en-us_topic_0079614930_p10577654"></a><a name="en-us_topic_0079614930_p10577654"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row28090025"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p60699544"><a name="en-us_topic_0079614930_p60699544"></a><a name="en-us_topic_0079614930_p60699544"></a>spec</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p17716056"><a name="en-us_topic_0079614930_p17716056"></a><a name="en-us_topic_0079614930_p17716056"></a><a href="#en-us_topic_0079614930_table39592297">spec</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p25714449"><a name="en-us_topic_0079614930_p25714449"></a><a name="en-us_topic_0079614930_p25714449"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row30103450"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p22460346"><a name="en-us_topic_0079614930_p22460346"></a><a name="en-us_topic_0079614930_p22460346"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p7348710"><a name="en-us_topic_0079614930_p7348710"></a><a name="en-us_topic_0079614930_p7348710"></a><a href="#en-us_topic_0079614930_table32774565">status</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p58374663"><a name="en-us_topic_0079614930_p58374663"></a><a name="en-us_topic_0079614930_p58374663"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  4**  Response parameters of v1.PodList

<a name="en-us_topic_0079614930_table6622802"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row61186665"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p57172870"><a name="en-us_topic_0079614930_p57172870"></a><a name="en-us_topic_0079614930_p57172870"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p939116105910"><a name="p939116105910"></a><a name="p939116105910"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p12391716185918"><a name="p12391716185918"></a><a name="p12391716185918"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row66568510"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p23340236"><a name="en-us_topic_0079614930_p23340236"></a><a name="en-us_topic_0079614930_p23340236"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p11511003"><a name="en-us_topic_0079614930_p11511003"></a><a name="en-us_topic_0079614930_p11511003"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p59976083"><a name="en-us_topic_0079614930_p59976083"></a><a name="en-us_topic_0079614930_p59976083"></a>A string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row2913837"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p34694260"><a name="en-us_topic_0079614930_p34694260"></a><a name="en-us_topic_0079614930_p34694260"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p58771704"><a name="en-us_topic_0079614930_p58771704"></a><a name="en-us_topic_0079614930_p58771704"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p62887584"><a name="en-us_topic_0079614930_p62887584"></a><a name="en-us_topic_0079614930_p62887584"></a>Versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row29117349"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p9695103"><a name="en-us_topic_0079614930_p9695103"></a><a name="en-us_topic_0079614930_p9695103"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p47105906"><a name="en-us_topic_0079614930_p47105906"></a><a name="en-us_topic_0079614930_p47105906"></a><a href="#en-us_topic_0079614930_table66688435">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p57482021"><a name="en-us_topic_0079614930_p57482021"></a><a name="en-us_topic_0079614930_p57482021"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row47576142"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p28462276"><a name="en-us_topic_0079614930_p28462276"></a><a name="en-us_topic_0079614930_p28462276"></a>items</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p23743056"><a name="en-us_topic_0079614930_p23743056"></a><a name="en-us_topic_0079614930_p23743056"></a><a href="#en-us_topic_0079614930_table63293941">items</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p44139351"><a name="en-us_topic_0079614930_p44139351"></a><a name="en-us_topic_0079614930_p44139351"></a>List of pods.</p>
</td>
</tr>
</tbody>
</table>

**Table  5**  Response parameters of v1.PodTemplate

<a name="en-us_topic_0079614930_table59605225"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row46940727"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p44102542"><a name="en-us_topic_0079614930_p44102542"></a><a name="en-us_topic_0079614930_p44102542"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p949121613595"><a name="p949121613595"></a><a name="p949121613595"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p649171613597"><a name="p649171613597"></a><a name="p649171613597"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row61370790"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p4978063"><a name="en-us_topic_0079614930_p4978063"></a><a name="en-us_topic_0079614930_p4978063"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p569920"><a name="en-us_topic_0079614930_p569920"></a><a name="en-us_topic_0079614930_p569920"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p46163554"><a name="en-us_topic_0079614930_p46163554"></a><a name="en-us_topic_0079614930_p46163554"></a>A string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row12818804"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p31690242"><a name="en-us_topic_0079614930_p31690242"></a><a name="en-us_topic_0079614930_p31690242"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p16772820"><a name="en-us_topic_0079614930_p16772820"></a><a name="en-us_topic_0079614930_p16772820"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p16421203"><a name="en-us_topic_0079614930_p16421203"></a><a name="en-us_topic_0079614930_p16421203"></a>Versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row13573102"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p25679515"><a name="en-us_topic_0079614930_p25679515"></a><a name="en-us_topic_0079614930_p25679515"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p66774824"><a name="en-us_topic_0079614930_p66774824"></a><a name="en-us_topic_0079614930_p66774824"></a><a href="#en-us_topic_0079614930_table33054158">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p40051645"><a name="en-us_topic_0079614930_p40051645"></a><a name="en-us_topic_0079614930_p40051645"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row24920491"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p5293856"><a name="en-us_topic_0079614930_p5293856"></a><a name="en-us_topic_0079614930_p5293856"></a>template</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p26149169"><a name="en-us_topic_0079614930_p26149169"></a><a name="en-us_topic_0079614930_p26149169"></a><a href="#en-us_topic_0079614930_table4399144">template</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p37707976"><a name="en-us_topic_0079614930_p37707976"></a><a name="en-us_topic_0079614930_p37707976"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  6**  Response parameters of v1.PodTemplateList

<a name="en-us_topic_0079614930_table66684983"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row1786593"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p10496346"><a name="en-us_topic_0079614930_p10496346"></a><a name="en-us_topic_0079614930_p10496346"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1558816185913"><a name="p1558816185913"></a><a name="p1558816185913"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p85891613594"><a name="p85891613594"></a><a name="p85891613594"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row33221002"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p6546613"><a name="en-us_topic_0079614930_p6546613"></a><a name="en-us_topic_0079614930_p6546613"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p60513649"><a name="en-us_topic_0079614930_p60513649"></a><a name="en-us_topic_0079614930_p60513649"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p2658533"><a name="en-us_topic_0079614930_p2658533"></a><a name="en-us_topic_0079614930_p2658533"></a>A string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row23926804"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p59022992"><a name="en-us_topic_0079614930_p59022992"></a><a name="en-us_topic_0079614930_p59022992"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p16133081"><a name="en-us_topic_0079614930_p16133081"></a><a name="en-us_topic_0079614930_p16133081"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p31711190"><a name="en-us_topic_0079614930_p31711190"></a><a name="en-us_topic_0079614930_p31711190"></a>Versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row16965260"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p32008819"><a name="en-us_topic_0079614930_p32008819"></a><a name="en-us_topic_0079614930_p32008819"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a7e9559988fa2455498f6a2b034afc28c"><a name="a7e9559988fa2455498f6a2b034afc28c"></a><a name="a7e9559988fa2455498f6a2b034afc28c"></a><a href="#tf50171b557ef4ebdafb2cc0bcb724d1b">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p26228578"><a name="en-us_topic_0079614930_p26228578"></a><a name="en-us_topic_0079614930_p26228578"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row34730616"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p61716500"><a name="en-us_topic_0079614930_p61716500"></a><a name="en-us_topic_0079614930_p61716500"></a>items</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p710201617910"><a name="en-us_topic_0079614930_p710201617910"></a><a name="en-us_topic_0079614930_p710201617910"></a><a href="data-structure-of-request-parameters.md#en-us_topic_0079614925_table58905579">v1.PodTemplate</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p54180000"><a name="en-us_topic_0079614930_p54180000"></a><a name="en-us_topic_0079614930_p54180000"></a>List of pod templates.</p>
</td>
</tr>
</tbody>
</table>

**Table  7**  Data structure of the items field

<a name="en-us_topic_0079614930_table63293941"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row50435184"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p58718067"><a name="en-us_topic_0079614930_p58718067"></a><a name="en-us_topic_0079614930_p58718067"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p176614166590"><a name="p176614166590"></a><a name="p176614166590"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1067131615599"><a name="p1067131615599"></a><a name="p1067131615599"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row36754162"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24297160"><a name="en-us_topic_0079614930_p24297160"></a><a name="en-us_topic_0079614930_p24297160"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p21912950"><a name="en-us_topic_0079614930_p21912950"></a><a name="en-us_topic_0079614930_p21912950"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p30118565"><a name="en-us_topic_0079614930_p30118565"></a><a name="en-us_topic_0079614930_p30118565"></a>A string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row2631637"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p11836007"><a name="en-us_topic_0079614930_p11836007"></a><a name="en-us_topic_0079614930_p11836007"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p19192526"><a name="en-us_topic_0079614930_p19192526"></a><a name="en-us_topic_0079614930_p19192526"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p11090802"><a name="en-us_topic_0079614930_p11090802"></a><a name="en-us_topic_0079614930_p11090802"></a>Versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row32708358"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p32131343"><a name="en-us_topic_0079614930_p32131343"></a><a name="en-us_topic_0079614930_p32131343"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a4226ab677eb747ffa5ace85c49d91070"><a name="a4226ab677eb747ffa5ace85c49d91070"></a><a name="a4226ab677eb747ffa5ace85c49d91070"></a><a href="#en-us_topic_0079614930_table33054158">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p24805660"><a name="en-us_topic_0079614930_p24805660"></a><a name="en-us_topic_0079614930_p24805660"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row21924350"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p31041896"><a name="en-us_topic_0079614930_p31041896"></a><a name="en-us_topic_0079614930_p31041896"></a>spec</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a5863cdcb478146f1b9cd48aa51d01491"><a name="a5863cdcb478146f1b9cd48aa51d01491"></a><a name="a5863cdcb478146f1b9cd48aa51d01491"></a><a href="#en-us_topic_0079614930_table39592297">spec</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p57588138"><a name="en-us_topic_0079614930_p57588138"></a><a name="en-us_topic_0079614930_p57588138"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row48531194"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p38712671"><a name="en-us_topic_0079614930_p38712671"></a><a name="en-us_topic_0079614930_p38712671"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p48718669"><a name="en-us_topic_0079614930_p48718669"></a><a name="en-us_topic_0079614930_p48718669"></a><a href="#en-us_topic_0079614930_table32774565">status</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p53898091"><a name="en-us_topic_0079614930_p53898091"></a><a name="en-us_topic_0079614930_p53898091"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  8**  Data structure of the status field

<a name="en-us_topic_0079614930_table32774565"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row36210358"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p47357861"><a name="en-us_topic_0079614930_p47357861"></a><a name="en-us_topic_0079614930_p47357861"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1678191695910"><a name="p1678191695910"></a><a name="p1678191695910"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p207915169592"><a name="p207915169592"></a><a name="p207915169592"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row4816637"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p54603342"><a name="en-us_topic_0079614930_p54603342"></a><a name="en-us_topic_0079614930_p54603342"></a>phase</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p60794620"><a name="en-us_topic_0079614930_p60794620"></a><a name="en-us_topic_0079614930_p60794620"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p25417198"><a name="en-us_topic_0079614930_p25417198"></a><a name="en-us_topic_0079614930_p25417198"></a>Current condition of the pod.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row27428197"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p7091448"><a name="en-us_topic_0079614930_p7091448"></a><a name="en-us_topic_0079614930_p7091448"></a>conditions</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p37536453"><a name="en-us_topic_0079614930_p37536453"></a><a name="en-us_topic_0079614930_p37536453"></a><a href="#en-us_topic_0079614930_table26535630">conditions</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p20553842"><a name="en-us_topic_0079614930_p20553842"></a><a name="en-us_topic_0079614930_p20553842"></a>Current service state of the pod.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row50766852"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p18474341"><a name="en-us_topic_0079614930_p18474341"></a><a name="en-us_topic_0079614930_p18474341"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p20026618"><a name="en-us_topic_0079614930_p20026618"></a><a name="en-us_topic_0079614930_p20026618"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p11543339"><a name="en-us_topic_0079614930_p11543339"></a><a name="en-us_topic_0079614930_p11543339"></a>A human readable message indicating details about why the pod is in this condition.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row36781194"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p26486770"><a name="en-us_topic_0079614930_p26486770"></a><a name="en-us_topic_0079614930_p26486770"></a>reason</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p65053610"><a name="en-us_topic_0079614930_p65053610"></a><a name="en-us_topic_0079614930_p65053610"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p34851034"><a name="en-us_topic_0079614930_p34851034"></a><a name="en-us_topic_0079614930_p34851034"></a>A brief CamelCase message indicating details about why the pod is in this state. e.g. 'OutOfDisk'</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row45223855"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p39253639"><a name="en-us_topic_0079614930_p39253639"></a><a name="en-us_topic_0079614930_p39253639"></a>hostIP</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p25428204"><a name="en-us_topic_0079614930_p25428204"></a><a name="en-us_topic_0079614930_p25428204"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p46418629"><a name="en-us_topic_0079614930_p46418629"></a><a name="en-us_topic_0079614930_p46418629"></a>IP address of the host to which the pod is assigned. Empty if not yet scheduled.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row15114481"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p16313428"><a name="en-us_topic_0079614930_p16313428"></a><a name="en-us_topic_0079614930_p16313428"></a>podIP</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p46319263"><a name="en-us_topic_0079614930_p46319263"></a><a name="en-us_topic_0079614930_p46319263"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p60872827"><a name="en-us_topic_0079614930_p60872827"></a><a name="en-us_topic_0079614930_p60872827"></a>IP address allocated to the pod. Routable at least within the cluster. Empty if not yet allocated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row10984535"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p17332110"><a name="en-us_topic_0079614930_p17332110"></a><a name="en-us_topic_0079614930_p17332110"></a>startTime</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p61723690"><a name="en-us_topic_0079614930_p61723690"></a><a name="en-us_topic_0079614930_p61723690"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p33563027"><a name="en-us_topic_0079614930_p33563027"></a><a name="en-us_topic_0079614930_p33563027"></a>RFC 3339 date and time at which the object was acknowledged by the Kubelet. This is before the Kubelet pulled the container image(s) for the pod.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row33631792"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p39820598"><a name="en-us_topic_0079614930_p39820598"></a><a name="en-us_topic_0079614930_p39820598"></a>containerStatuses</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p4243005"><a name="en-us_topic_0079614930_p4243005"></a><a name="en-us_topic_0079614930_p4243005"></a><a href="#en-us_topic_0079614930_table37494083">containerStatuses</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p8139116"><a name="en-us_topic_0079614930_p8139116"></a><a name="en-us_topic_0079614930_p8139116"></a>The list has one entry per container in the manifest. Each entry is currently the output of docker inspect.</p>
</td>
</tr>
</tbody>
</table>

**Table  9**  Data structure of the conditions field

<a name="en-us_topic_0079614930_table26535630"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row29527278"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p42899290"><a name="en-us_topic_0079614930_p42899290"></a><a name="en-us_topic_0079614930_p42899290"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p194131615593"><a name="p194131615593"></a><a name="p194131615593"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p129521655912"><a name="p129521655912"></a><a name="p129521655912"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row17405051"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p523050"><a name="en-us_topic_0079614930_p523050"></a><a name="en-us_topic_0079614930_p523050"></a>type</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p42367085"><a name="en-us_topic_0079614930_p42367085"></a><a name="en-us_topic_0079614930_p42367085"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p9181869"><a name="en-us_topic_0079614930_p9181869"></a><a name="en-us_topic_0079614930_p9181869"></a>Type of the condition. Currently only Ready.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row15527959"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p49805148"><a name="en-us_topic_0079614930_p49805148"></a><a name="en-us_topic_0079614930_p49805148"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p7685202"><a name="en-us_topic_0079614930_p7685202"></a><a name="en-us_topic_0079614930_p7685202"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p18521632"><a name="en-us_topic_0079614930_p18521632"></a><a name="en-us_topic_0079614930_p18521632"></a>Status of the condition. Can be True, False, or Unknown.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row32476968"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p13388783"><a name="en-us_topic_0079614930_p13388783"></a><a name="en-us_topic_0079614930_p13388783"></a>lastProbeTime</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p10749601"><a name="en-us_topic_0079614930_p10749601"></a><a name="en-us_topic_0079614930_p10749601"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p65411368"><a name="en-us_topic_0079614930_p65411368"></a><a name="en-us_topic_0079614930_p65411368"></a>Last time we probed the condition.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row51831407"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p37594448"><a name="en-us_topic_0079614930_p37594448"></a><a name="en-us_topic_0079614930_p37594448"></a>lastTransitionTime</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p25251449"><a name="en-us_topic_0079614930_p25251449"></a><a name="en-us_topic_0079614930_p25251449"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p32101523"><a name="en-us_topic_0079614930_p32101523"></a><a name="en-us_topic_0079614930_p32101523"></a>Last time the condition transitioned from one status to another.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row20478258"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p48126200"><a name="en-us_topic_0079614930_p48126200"></a><a name="en-us_topic_0079614930_p48126200"></a>reason</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p5908098"><a name="en-us_topic_0079614930_p5908098"></a><a name="en-us_topic_0079614930_p5908098"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p8793912"><a name="en-us_topic_0079614930_p8793912"></a><a name="en-us_topic_0079614930_p8793912"></a>Unique, one-word, CamelCase reason for the condition's last transition.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row12036352"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p35420452"><a name="en-us_topic_0079614930_p35420452"></a><a name="en-us_topic_0079614930_p35420452"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p50484393"><a name="en-us_topic_0079614930_p50484393"></a><a name="en-us_topic_0079614930_p50484393"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p62704055"><a name="en-us_topic_0079614930_p62704055"></a><a name="en-us_topic_0079614930_p62704055"></a>Human-readable message indicating details about last transition.</p>
</td>
</tr>
</tbody>
</table>

**Table  10**  Data structure of the containerStatuses field

<a name="en-us_topic_0079614930_table37494083"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row25588789"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p59426032"><a name="en-us_topic_0079614930_p59426032"></a><a name="en-us_topic_0079614930_p59426032"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p181066169591"><a name="p181066169591"></a><a name="p181066169591"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1110712164591"><a name="p1110712164591"></a><a name="p1110712164591"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row65683259"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p18743735"><a name="en-us_topic_0079614930_p18743735"></a><a name="en-us_topic_0079614930_p18743735"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p41847592"><a name="en-us_topic_0079614930_p41847592"></a><a name="en-us_topic_0079614930_p41847592"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p34211830"><a name="en-us_topic_0079614930_p34211830"></a><a name="en-us_topic_0079614930_p34211830"></a>This must be a DNS_LABEL. Each container in a pod must have a unique name. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row39471019"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p43035983"><a name="en-us_topic_0079614930_p43035983"></a><a name="en-us_topic_0079614930_p43035983"></a>state</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p910905917164"><a name="en-us_topic_0079614930_p910905917164"></a><a name="en-us_topic_0079614930_p910905917164"></a><a href="#en-us_topic_0079614930_table1902427">state/lastState</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p32093935"><a name="en-us_topic_0079614930_p32093935"></a><a name="en-us_topic_0079614930_p32093935"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row20409962"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p42594206"><a name="en-us_topic_0079614930_p42594206"></a><a name="en-us_topic_0079614930_p42594206"></a>lastState</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a90fea3daa0204637bf02cafb037ef070"><a name="a90fea3daa0204637bf02cafb037ef070"></a><a name="a90fea3daa0204637bf02cafb037ef070"></a><a href="#en-us_topic_0079614930_table1902427">state/lastState</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p19278548"><a name="en-us_topic_0079614930_p19278548"></a><a name="en-us_topic_0079614930_p19278548"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row39289205"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p28309076"><a name="en-us_topic_0079614930_p28309076"></a><a name="en-us_topic_0079614930_p28309076"></a>ready</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p11333852"><a name="en-us_topic_0079614930_p11333852"></a><a name="en-us_topic_0079614930_p11333852"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p45626804"><a name="en-us_topic_0079614930_p45626804"></a><a name="en-us_topic_0079614930_p45626804"></a>A flag indicating whether the container has passed its readiness probe.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row7988053"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p43052585"><a name="en-us_topic_0079614930_p43052585"></a><a name="en-us_topic_0079614930_p43052585"></a>restartCount</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p64707361"><a name="en-us_topic_0079614930_p64707361"></a><a name="en-us_topic_0079614930_p64707361"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p6804902"><a name="en-us_topic_0079614930_p6804902"></a><a name="en-us_topic_0079614930_p6804902"></a>The number of times the container has been restarted, currently based on the number of dead containers that have not yet been removed. Note that this is calculated from dead containers. However, those containers are subject to garbage collection. This value will get capped at 5 by GC.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row61244120"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p61826715"><a name="en-us_topic_0079614930_p61826715"></a><a name="en-us_topic_0079614930_p61826715"></a>image</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p41907998"><a name="en-us_topic_0079614930_p41907998"></a><a name="en-us_topic_0079614930_p41907998"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p39104649"><a name="en-us_topic_0079614930_p39104649"></a><a name="en-us_topic_0079614930_p39104649"></a>Image that the container is running.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row16397525"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p53131185"><a name="en-us_topic_0079614930_p53131185"></a><a name="en-us_topic_0079614930_p53131185"></a>imageID</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p8658696"><a name="en-us_topic_0079614930_p8658696"></a><a name="en-us_topic_0079614930_p8658696"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p30265796"><a name="en-us_topic_0079614930_p30265796"></a><a name="en-us_topic_0079614930_p30265796"></a>ID of the container's image.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row3956716"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p52058554"><a name="en-us_topic_0079614930_p52058554"></a><a name="en-us_topic_0079614930_p52058554"></a>containerID</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p55993312"><a name="en-us_topic_0079614930_p55993312"></a><a name="en-us_topic_0079614930_p55993312"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p39164423"><a name="en-us_topic_0079614930_p39164423"></a><a name="en-us_topic_0079614930_p39164423"></a>Container's ID in the format 'docker://'.</p>
</td>
</tr>
</tbody>
</table>

**Table  11**  Data structure of the state/lastState field

<a name="en-us_topic_0079614930_table1902427"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row42946824"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p56140680"><a name="en-us_topic_0079614930_p56140680"></a><a name="en-us_topic_0079614930_p56140680"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p12704101615915"><a name="p12704101615915"></a><a name="p12704101615915"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p10704201613599"><a name="p10704201613599"></a><a name="p10704201613599"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row66229107"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p62957461"><a name="en-us_topic_0079614930_p62957461"></a><a name="en-us_topic_0079614930_p62957461"></a>waiting</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="ab8a27bafd3da491abba1c04a4ac635d4"><a name="ab8a27bafd3da491abba1c04a4ac635d4"></a><a name="ab8a27bafd3da491abba1c04a4ac635d4"></a><a href="#en-us_topic_0079614930_table17121849">waiting</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p8848839"><a name="en-us_topic_0079614930_p8848839"></a><a name="en-us_topic_0079614930_p8848839"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row12530692"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p8353121"><a name="en-us_topic_0079614930_p8353121"></a><a name="en-us_topic_0079614930_p8353121"></a>running</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a36791fc9bcc846948f4225d13fcc62b7"><a name="a36791fc9bcc846948f4225d13fcc62b7"></a><a name="a36791fc9bcc846948f4225d13fcc62b7"></a><a href="#en-us_topic_0079614930_table19878917">running</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p43995612"><a name="en-us_topic_0079614930_p43995612"></a><a name="en-us_topic_0079614930_p43995612"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row60416193"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p61873442"><a name="en-us_topic_0079614930_p61873442"></a><a name="en-us_topic_0079614930_p61873442"></a>terminated</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a253c54cf0edc4b4f995ae4c85795b4b6"><a name="a253c54cf0edc4b4f995ae4c85795b4b6"></a><a name="a253c54cf0edc4b4f995ae4c85795b4b6"></a><a href="#en-us_topic_0079614930_table44692528">terminated</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p10140379"><a name="en-us_topic_0079614930_p10140379"></a><a name="en-us_topic_0079614930_p10140379"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  12**  Data structure of the waiting field

<a name="en-us_topic_0079614930_table17121849"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row2186211"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p42865437"><a name="en-us_topic_0079614930_p42865437"></a><a name="en-us_topic_0079614930_p42865437"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p57052016195910"><a name="p57052016195910"></a><a name="p57052016195910"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1870516163596"><a name="p1870516163596"></a><a name="p1870516163596"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row11716734"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p9531402"><a name="en-us_topic_0079614930_p9531402"></a><a name="en-us_topic_0079614930_p9531402"></a>reason</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p33846094"><a name="en-us_topic_0079614930_p33846094"></a><a name="en-us_topic_0079614930_p33846094"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p57179123"><a name="en-us_topic_0079614930_p57179123"></a><a name="en-us_topic_0079614930_p57179123"></a>(brief) reason the container is not yet running.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row44850065"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p8976682"><a name="en-us_topic_0079614930_p8976682"></a><a name="en-us_topic_0079614930_p8976682"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p56022647"><a name="en-us_topic_0079614930_p56022647"></a><a name="en-us_topic_0079614930_p56022647"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p41540577"><a name="en-us_topic_0079614930_p41540577"></a><a name="en-us_topic_0079614930_p41540577"></a>Message regarding why the container is not yet running.</p>
</td>
</tr>
</tbody>
</table>

**Table  13**  Data structure of the running field

<a name="en-us_topic_0079614930_table19878917"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row26348324"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p53839469"><a name="en-us_topic_0079614930_p53839469"></a><a name="en-us_topic_0079614930_p53839469"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1370711163599"><a name="p1370711163599"></a><a name="p1370711163599"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p6707151675914"><a name="p6707151675914"></a><a name="p6707151675914"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row33107994"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p64501877"><a name="en-us_topic_0079614930_p64501877"></a><a name="en-us_topic_0079614930_p64501877"></a>startedAt</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p57269561"><a name="en-us_topic_0079614930_p57269561"></a><a name="en-us_topic_0079614930_p57269561"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p8322828"><a name="en-us_topic_0079614930_p8322828"></a><a name="en-us_topic_0079614930_p8322828"></a>Time at which the container was last (re-)started.</p>
</td>
</tr>
</tbody>
</table>

**Table  14**  Data structure of the terminated field

<a name="en-us_topic_0079614930_table44692528"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row62719193"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p47089838"><a name="en-us_topic_0079614930_p47089838"></a><a name="en-us_topic_0079614930_p47089838"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1707111635910"><a name="p1707111635910"></a><a name="p1707111635910"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1670751617594"><a name="p1670751617594"></a><a name="p1670751617594"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row38457336"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p28036527"><a name="en-us_topic_0079614930_p28036527"></a><a name="en-us_topic_0079614930_p28036527"></a>startedAt</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p56366243"><a name="en-us_topic_0079614930_p56366243"></a><a name="en-us_topic_0079614930_p56366243"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p2262971"><a name="en-us_topic_0079614930_p2262971"></a><a name="en-us_topic_0079614930_p2262971"></a>Exit status from the last termination of the container.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row20366744"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p39093602"><a name="en-us_topic_0079614930_p39093602"></a><a name="en-us_topic_0079614930_p39093602"></a>signal</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p12465221"><a name="en-us_topic_0079614930_p12465221"></a><a name="en-us_topic_0079614930_p12465221"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p3049960"><a name="en-us_topic_0079614930_p3049960"></a><a name="en-us_topic_0079614930_p3049960"></a>Signal from the last termination of the container.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row27449641"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p8828431"><a name="en-us_topic_0079614930_p8828431"></a><a name="en-us_topic_0079614930_p8828431"></a>reason</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p44014347"><a name="en-us_topic_0079614930_p44014347"></a><a name="en-us_topic_0079614930_p44014347"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p8392322"><a name="en-us_topic_0079614930_p8392322"></a><a name="en-us_topic_0079614930_p8392322"></a>(brief) reason from the last termination of the container.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row8422040"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p11096662"><a name="en-us_topic_0079614930_p11096662"></a><a name="en-us_topic_0079614930_p11096662"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p26414404"><a name="en-us_topic_0079614930_p26414404"></a><a name="en-us_topic_0079614930_p26414404"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p59191946"><a name="en-us_topic_0079614930_p59191946"></a><a name="en-us_topic_0079614930_p59191946"></a>Message regarding the last termination of the container.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row62965470"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p67038300"><a name="en-us_topic_0079614930_p67038300"></a><a name="en-us_topic_0079614930_p67038300"></a>startedAt</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p61393223"><a name="en-us_topic_0079614930_p61393223"></a><a name="en-us_topic_0079614930_p61393223"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p6795142"><a name="en-us_topic_0079614930_p6795142"></a><a name="en-us_topic_0079614930_p6795142"></a>Time at which previous execution of the container started.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row61156281"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p54711698"><a name="en-us_topic_0079614930_p54711698"></a><a name="en-us_topic_0079614930_p54711698"></a>finishedAt</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p2462515"><a name="en-us_topic_0079614930_p2462515"></a><a name="en-us_topic_0079614930_p2462515"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p65246021"><a name="en-us_topic_0079614930_p65246021"></a><a name="en-us_topic_0079614930_p65246021"></a>Time at which the container last terminated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row50343279"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p51273837"><a name="en-us_topic_0079614930_p51273837"></a><a name="en-us_topic_0079614930_p51273837"></a>containerID</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p59540143"><a name="en-us_topic_0079614930_p59540143"></a><a name="en-us_topic_0079614930_p59540143"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p58022302"><a name="en-us_topic_0079614930_p58022302"></a><a name="en-us_topic_0079614930_p58022302"></a>Container's ID in the format 'docker://'.</p>
</td>
</tr>
</tbody>
</table>

**Table  15**  Data structure of the metadata field

<a name="en-us_topic_0079614930_table66688435"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row31807536"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p26273638"><a name="en-us_topic_0079614930_p26273638"></a><a name="en-us_topic_0079614930_p26273638"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p18710161615598"><a name="p18710161615598"></a><a name="p18710161615598"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p147101169591"><a name="p147101169591"></a><a name="p147101169591"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row17190203"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p50229187"><a name="en-us_topic_0079614930_p50229187"></a><a name="en-us_topic_0079614930_p50229187"></a>selfLink</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p42032323"><a name="en-us_topic_0079614930_p42032323"></a><a name="en-us_topic_0079614930_p42032323"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p49175012"><a name="en-us_topic_0079614930_p49175012"></a><a name="en-us_topic_0079614930_p49175012"></a>SelfLink is a URL representing this object. Populated by the system. Read-only.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row39921928"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p12450749"><a name="en-us_topic_0079614930_p12450749"></a><a name="en-us_topic_0079614930_p12450749"></a>resourceVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p1877734"><a name="en-us_topic_0079614930_p1877734"></a><a name="en-us_topic_0079614930_p1877734"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p17878764"><a name="en-us_topic_0079614930_p17878764"></a><a name="en-us_topic_0079614930_p17878764"></a>String that identifies the server's internal version of this object that can be used by clients to determine when objects have changed. Value must be treated as opaque by clients and passed unmodified back to the server. Populated by the system. Read-only.</p>
</td>
</tr>
</tbody>
</table>

**Table  16**  Data structure of the items field

<a name="en-us_topic_0079614930_table63325007"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row37516664"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p18950973"><a name="en-us_topic_0079614930_p18950973"></a><a name="en-us_topic_0079614930_p18950973"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p20711161675916"><a name="p20711161675916"></a><a name="p20711161675916"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p167111216205914"><a name="p167111216205914"></a><a name="p167111216205914"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row28794079"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p50619062"><a name="en-us_topic_0079614930_p50619062"></a><a name="en-us_topic_0079614930_p50619062"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p6503349"><a name="en-us_topic_0079614930_p6503349"></a><a name="en-us_topic_0079614930_p6503349"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p57009285"><a name="en-us_topic_0079614930_p57009285"></a><a name="en-us_topic_0079614930_p57009285"></a>Kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row43321523"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p19382463"><a name="en-us_topic_0079614930_p19382463"></a><a name="en-us_topic_0079614930_p19382463"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p26475631"><a name="en-us_topic_0079614930_p26475631"></a><a name="en-us_topic_0079614930_p26475631"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p64151339"><a name="en-us_topic_0079614930_p64151339"></a><a name="en-us_topic_0079614930_p64151339"></a>APIVersion defines the versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row40491146"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p58557380"><a name="en-us_topic_0079614930_p58557380"></a><a name="en-us_topic_0079614930_p58557380"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a4249446039654944804f5e455b53dacf"><a name="a4249446039654944804f5e455b53dacf"></a><a name="a4249446039654944804f5e455b53dacf"></a><a href="#en-us_topic_0079614930_table33054158">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p63837475"><a name="en-us_topic_0079614930_p63837475"></a><a name="en-us_topic_0079614930_p63837475"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row37666363"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p31076558"><a name="en-us_topic_0079614930_p31076558"></a><a name="en-us_topic_0079614930_p31076558"></a>spec</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a875ecde10b8f42a4a98e06cb10a0f192"><a name="a875ecde10b8f42a4a98e06cb10a0f192"></a><a name="a875ecde10b8f42a4a98e06cb10a0f192"></a><a href="#en-us_topic_0079614930_table29051967">spec</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p16572114"><a name="en-us_topic_0079614930_p16572114"></a><a name="en-us_topic_0079614930_p16572114"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row14931301"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p1475883"><a name="en-us_topic_0079614930_p1475883"></a><a name="en-us_topic_0079614930_p1475883"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a8b7892f94c4a427bbf2291985cce3ed0"><a name="a8b7892f94c4a427bbf2291985cce3ed0"></a><a name="a8b7892f94c4a427bbf2291985cce3ed0"></a><a href="#en-us_topic_0079614930_table60141117">status</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p19595752"><a name="en-us_topic_0079614930_p19595752"></a><a name="en-us_topic_0079614930_p19595752"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  17**  Data structure of the metadata field

<a name="en-us_topic_0079614930_table33054158"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row28541725"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p30178389"><a name="en-us_topic_0079614930_p30178389"></a><a name="en-us_topic_0079614930_p30178389"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.2.4.1.2"><p id="p19713201620592"><a name="p19713201620592"></a><a name="p19713201620592"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="p97135167593"><a name="p97135167593"></a><a name="p97135167593"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row21715305"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p14109251"><a name="en-us_topic_0079614930_p14109251"></a><a name="en-us_topic_0079614930_p14109251"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p1998665"><a name="en-us_topic_0079614930_p1998665"></a><a name="en-us_topic_0079614930_p1998665"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p27674213"><a name="en-us_topic_0079614930_p27674213"></a><a name="en-us_topic_0079614930_p27674213"></a>Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated.</p>
</td>
</tr>
<tr id="rfdf1995300c04b3e8a2546569a0c6e55"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="aa02c17ca37ef453d889ec86891ca430a"><a name="aa02c17ca37ef453d889ec86891ca430a"></a><a name="aa02c17ca37ef453d889ec86891ca430a"></a>clusterName</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="acf63832363bf4b829b3652a43062c021"><a name="acf63832363bf4b829b3652a43062c021"></a><a name="acf63832363bf4b829b3652a43062c021"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p766718575305"><a name="en-us_topic_0079614930_p766718575305"></a><a name="en-us_topic_0079614930_p766718575305"></a>The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request.</p>
</td>
</tr>
<tr id="r43674f133d104fde9b689a2dbb32bebd"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="a9958228064a141b78314fc31dc2cfef4"><a name="a9958228064a141b78314fc31dc2cfef4"></a><a name="a9958228064a141b78314fc31dc2cfef4"></a>initializers</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="a8c2743b129b9487486acb0543860c87b"><a name="a8c2743b129b9487486acb0543860c87b"></a><a name="a8c2743b129b9487486acb0543860c87b"></a><a href="#t050e77dc2b1644c895d89f389e46d859">initializers</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a1b8a98e9639f4021bf8970f7d4893fe4"><a name="a1b8a98e9639f4021bf8970f7d4893fe4"></a><a name="a1b8a98e9639f4021bf8970f7d4893fe4"></a>An initializer is a controller which enforces some system invariant at object creation time. This field is a list of initializers that have not yet acted on this object. If nil or empty, this object has been completely initialized. Otherwise, the object is considered uninitialized and is hidden (in list/watch and get calls) from clients that haven't explicitly asked to observe uninitialized objects. When an object is created, the system will populate this list with the current set of initializers. Only privileged users may set or modify this list. Once it is empty, it may not be modified further by any user.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row47741325"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p41842146"><a name="en-us_topic_0079614930_p41842146"></a><a name="en-us_topic_0079614930_p41842146"></a>generateName</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p33770688"><a name="en-us_topic_0079614930_p33770688"></a><a name="en-us_topic_0079614930_p33770688"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p51071182"><a name="en-us_topic_0079614930_p51071182"></a><a name="en-us_topic_0079614930_p51071182"></a>GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.</p>
<p id="en-us_topic_0079614930_p56987454"><a name="en-us_topic_0079614930_p56987454"></a><a name="en-us_topic_0079614930_p56987454"></a>If this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).</p>
<p id="en-us_topic_0079614930_p43125044"><a name="en-us_topic_0079614930_p43125044"></a><a name="en-us_topic_0079614930_p43125044"></a>Applied only if Name is not specified.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row52581080"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p31209078"><a name="en-us_topic_0079614930_p31209078"></a><a name="en-us_topic_0079614930_p31209078"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p44907393"><a name="en-us_topic_0079614930_p44907393"></a><a name="en-us_topic_0079614930_p44907393"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p13620192"><a name="en-us_topic_0079614930_p13620192"></a><a name="en-us_topic_0079614930_p13620192"></a>Namespace defines the space within each name must be unique. An empty namespace is equivalent to the "default" namespace, but "default" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty. Must be a DNS_LABEL. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row55472867"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p64117212"><a name="en-us_topic_0079614930_p64117212"></a><a name="en-us_topic_0079614930_p64117212"></a>selfLink</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p26111645"><a name="en-us_topic_0079614930_p26111645"></a><a name="en-us_topic_0079614930_p26111645"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p34668495"><a name="en-us_topic_0079614930_p34668495"></a><a name="en-us_topic_0079614930_p34668495"></a>SelfLink is a URL representing this object. Populated by the system. Read-only.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row43581001"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p40400231"><a name="en-us_topic_0079614930_p40400231"></a><a name="en-us_topic_0079614930_p40400231"></a>uid</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p51193289"><a name="en-us_topic_0079614930_p51193289"></a><a name="en-us_topic_0079614930_p51193289"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p53015768"><a name="en-us_topic_0079614930_p53015768"></a><a name="en-us_topic_0079614930_p53015768"></a>UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations. Populated by the system. Read-only.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row7379867"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p60898392"><a name="en-us_topic_0079614930_p60898392"></a><a name="en-us_topic_0079614930_p60898392"></a>resourceVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p33822709"><a name="en-us_topic_0079614930_p33822709"></a><a name="en-us_topic_0079614930_p33822709"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p55284890"><a name="en-us_topic_0079614930_p55284890"></a><a name="en-us_topic_0079614930_p55284890"></a>An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources. Populated by the system. Read-only. Value must be treated as opaque by clients.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row27801968"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p37366901"><a name="en-us_topic_0079614930_p37366901"></a><a name="en-us_topic_0079614930_p37366901"></a>generation</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p6820118"><a name="en-us_topic_0079614930_p6820118"></a><a name="en-us_topic_0079614930_p6820118"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p15558717"><a name="en-us_topic_0079614930_p15558717"></a><a name="en-us_topic_0079614930_p15558717"></a>A sequence number representing a specific generation of the desired state. Currently only implemented by replication controllers. Populated by the system. Read-only.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row5810725"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p906701"><a name="en-us_topic_0079614930_p906701"></a><a name="en-us_topic_0079614930_p906701"></a>creationTimestamp</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p6333933"><a name="en-us_topic_0079614930_p6333933"></a><a name="en-us_topic_0079614930_p6333933"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p43286574"><a name="en-us_topic_0079614930_p43286574"></a><a name="en-us_topic_0079614930_p43286574"></a>CreationTimestamp is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row54034850"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p14746743"><a name="en-us_topic_0079614930_p14746743"></a><a name="en-us_topic_0079614930_p14746743"></a>deletionTimestamp</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p53635520"><a name="en-us_topic_0079614930_p53635520"></a><a name="en-us_topic_0079614930_p53635520"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p49509862"><a name="en-us_topic_0079614930_p49509862"></a><a name="en-us_topic_0079614930_p49509862"></a>DeletionTimestamp is RFC 3339 date and time at which this resource will be deleted. This field is set by the server when a graceful deletion is requested by the user, and is not directly settable by a client. The resource will be deleted (no longer visible from resource lists, and not reachable by name) after the time in this field. Once set, this value may not be unset or be set further into the future, although it may be shortened or the resource may be deleted prior to this time. For example, a user may request that a pod is deleted in 30 seconds. The Kubelet will react by sending a graceful termination signal to the containers in the pod. Once the resource is deleted in the API, the Kubelet will send a hard termination signal to the container. If not set, graceful deletion of the object has not been requested. Populated by the system when a graceful deletion is requested. Read-only.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row42935575"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p55229522"><a name="en-us_topic_0079614930_p55229522"></a><a name="en-us_topic_0079614930_p55229522"></a>deletionGracePeriodSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p44406302"><a name="en-us_topic_0079614930_p44406302"></a><a name="en-us_topic_0079614930_p44406302"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p40140706"><a name="en-us_topic_0079614930_p40140706"></a><a name="en-us_topic_0079614930_p40140706"></a>Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row25722041"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p3110597"><a name="en-us_topic_0079614930_p3110597"></a><a name="en-us_topic_0079614930_p3110597"></a>labels</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p50631838"><a name="en-us_topic_0079614930_p50631838"></a><a name="en-us_topic_0079614930_p50631838"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p7538219"><a name="en-us_topic_0079614930_p7538219"></a><a name="en-us_topic_0079614930_p7538219"></a>Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row735113"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p59544192"><a name="en-us_topic_0079614930_p59544192"></a><a name="en-us_topic_0079614930_p59544192"></a>annotations</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p58350239"><a name="en-us_topic_0079614930_p58350239"></a><a name="en-us_topic_0079614930_p58350239"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p28748943"><a name="en-us_topic_0079614930_p28748943"></a><a name="en-us_topic_0079614930_p28748943"></a>Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects.</p>
</td>
</tr>
<tr id="rb1bb50c174b447a79ee9854c6e6739c1"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="a599fe60be01c4d7a9a745d7925bc7e09"><a name="a599fe60be01c4d7a9a745d7925bc7e09"></a><a name="a599fe60be01c4d7a9a745d7925bc7e09"></a>ownerReferences</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="ab6b5169a4eb04f2688ef7ff4cc4f207d"><a name="ab6b5169a4eb04f2688ef7ff4cc4f207d"></a><a name="ab6b5169a4eb04f2688ef7ff4cc4f207d"></a><a href="#t9b2c5d4719b24ea6a40f0f5e7bd366b8">ownerReferences</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a2209e70c347a48a281b58a635d1535a6"><a name="a2209e70c347a48a281b58a635d1535a6"></a><a name="a2209e70c347a48a281b58a635d1535a6"></a>List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller.</p>
</td>
</tr>
<tr id="re355b861e0b74409818a58c0cec9de58"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="ac01d3911fc8144ffb8ef3efa4200fae7"><a name="ac01d3911fc8144ffb8ef3efa4200fae7"></a><a name="ac01d3911fc8144ffb8ef3efa4200fae7"></a>finalizers</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="a132247f6ab2649d59fb9d148c31edf3a"><a name="a132247f6ab2649d59fb9d148c31edf3a"></a><a name="a132247f6ab2649d59fb9d148c31edf3a"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a1c16b21e4de14db08f58d9aa22ba6ba0"><a name="a1c16b21e4de14db08f58d9aa22ba6ba0"></a><a name="a1c16b21e4de14db08f58d9aa22ba6ba0"></a>Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed.</p>
</td>
</tr>
</tbody>
</table>

**Table  18**  Data structure of the spec field

<a name="en-us_topic_0079614930_table29051967"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row49494501"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p49631670"><a name="en-us_topic_0079614930_p49631670"></a><a name="en-us_topic_0079614930_p49631670"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.2.4.1.2"><p id="p1171841665912"><a name="p1171841665912"></a><a name="p1171841665912"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="p5719316175912"><a name="p5719316175912"></a><a name="p5719316175912"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row38272373"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p13054504"><a name="en-us_topic_0079614930_p13054504"></a><a name="en-us_topic_0079614930_p13054504"></a>replicas</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p50781912"><a name="en-us_topic_0079614930_p50781912"></a><a name="en-us_topic_0079614930_p50781912"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p19694188"><a name="en-us_topic_0079614930_p19694188"></a><a name="en-us_topic_0079614930_p19694188"></a>Replicas is the number of desired replicas. This is a pointer to distinguish between explicit zero and unspecified. Defaults to 1.</p>
</td>
</tr>
<tr id="r4aec73aaa8d6473ea8553e565be9a633"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p693133016417"><a name="en-us_topic_0079614930_p693133016417"></a><a name="en-us_topic_0079614930_p693133016417"></a>selector</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p69415301342"><a name="en-us_topic_0079614930_p69415301342"></a><a name="en-us_topic_0079614930_p69415301342"></a>object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p1794330544"><a name="en-us_topic_0079614930_p1794330544"></a><a name="en-us_topic_0079614930_p1794330544"></a>Selector is a label query over pods that should match the Replicas count. If Selector is empty, it is defaulted to the labels present on the Pod template. Label keys and values that must match in order to be controlled by this replication controller, if empty defaulted to labels on Pod template.</p>
</td>
</tr>
<tr id="r1e83899972b94fd49f78a557cc349b2d"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="a19493a6b39aa42f7ab07295fe7fd9318"><a name="a19493a6b39aa42f7ab07295fe7fd9318"></a><a name="a19493a6b39aa42f7ab07295fe7fd9318"></a>minReadySeconds</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="a95a3972c36bb41d2997bee190c6723b2"><a name="a95a3972c36bb41d2997bee190c6723b2"></a><a name="a95a3972c36bb41d2997bee190c6723b2"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="ad8ba1b5881c445cc8b14610cdc3db96e"><a name="ad8ba1b5881c445cc8b14610cdc3db96e"></a><a name="ad8ba1b5881c445cc8b14610cdc3db96e"></a>Minimum number of seconds for which a newly created pod should be ready without any of its container crashing, for it to be considered available. Defaults to 0 (pod will be considered available as soon as it is ready)</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row43029967"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p62875317"><a name="en-us_topic_0079614930_p62875317"></a><a name="en-us_topic_0079614930_p62875317"></a>template</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="a21262b64622d4d629c9a43cf4b4f27a6"><a name="a21262b64622d4d629c9a43cf4b4f27a6"></a><a name="a21262b64622d4d629c9a43cf4b4f27a6"></a><a href="#en-us_topic_0079614930_table4399144">template</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p6771634"><a name="en-us_topic_0079614930_p6771634"></a><a name="en-us_topic_0079614930_p6771634"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  19**  Data structure of the status field

<a name="en-us_topic_0079614930_table60141117"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row37173655"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p58276079"><a name="en-us_topic_0079614930_p58276079"></a><a name="en-us_topic_0079614930_p58276079"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p87204167595"><a name="p87204167595"></a><a name="p87204167595"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p57201016205918"><a name="p57201016205918"></a><a name="p57201016205918"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row27075683"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p45646685"><a name="en-us_topic_0079614930_p45646685"></a><a name="en-us_topic_0079614930_p45646685"></a>replicas</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p6393987"><a name="en-us_topic_0079614930_p6393987"></a><a name="en-us_topic_0079614930_p6393987"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p48150975"><a name="en-us_topic_0079614930_p48150975"></a><a name="en-us_topic_0079614930_p48150975"></a>Replicas is the most recently observed number of replicas.</p>
</td>
</tr>
<tr id="raad3d8f9b4734b459d386d7a662d5336"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p132411251334"><a name="en-us_topic_0079614930_p132411251334"></a><a name="en-us_topic_0079614930_p132411251334"></a>availableReplicas</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p12412253310"><a name="en-us_topic_0079614930_p12412253310"></a><a name="en-us_topic_0079614930_p12412253310"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="a33bcfbba2dec440d9c5d0bdd95533be8"><a name="a33bcfbba2dec440d9c5d0bdd95533be8"></a><a name="a33bcfbba2dec440d9c5d0bdd95533be8"></a>The number of available replicas (ready for at least minReadySeconds) for this replication controller.</p>
</td>
</tr>
<tr id="rda64f15068f34cb688bd84e57d658eba"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p959944214581"><a name="en-us_topic_0079614930_p959944214581"></a><a name="en-us_topic_0079614930_p959944214581"></a>readyReplicas</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="adea9796cb55b4ed18ac59d0512a35e02"><a name="adea9796cb55b4ed18ac59d0512a35e02"></a><a name="adea9796cb55b4ed18ac59d0512a35e02"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="a4cbbe9469da4461bbd7addfee4f9d504"><a name="a4cbbe9469da4461bbd7addfee4f9d504"></a><a name="a4cbbe9469da4461bbd7addfee4f9d504"></a>The number of ready replicas for this replication controller.</p>
</td>
</tr>
<tr id="r22885a4a882343a4bea312ea5ab2276c"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p164135016593"><a name="en-us_topic_0079614930_p164135016593"></a><a name="en-us_topic_0079614930_p164135016593"></a>fullyLabeledReplicas</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a573c3f48a0654270975a065bededdfea"><a name="a573c3f48a0654270975a065bededdfea"></a><a name="a573c3f48a0654270975a065bededdfea"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p241390115918"><a name="en-us_topic_0079614930_p241390115918"></a><a name="en-us_topic_0079614930_p241390115918"></a>The number of pods that have labels matching the labels of the pod template of the replication controller.</p>
</td>
</tr>
<tr id="ra1e039c700dd45c0887b851b6801c63e"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="a2f587920564648798b485678b3e2dfae"><a name="a2f587920564648798b485678b3e2dfae"></a><a name="a2f587920564648798b485678b3e2dfae"></a>conditions</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a38471d8e5bc24c77b622a2e440320a5d"><a name="a38471d8e5bc24c77b622a2e440320a5d"></a><a name="a38471d8e5bc24c77b622a2e440320a5d"></a><a href="#t0136d24c39ae4df89959d36b2119f260">ReplicationControllerCondition</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="afa4284a82e8544c782344bb59345468a"><a name="afa4284a82e8544c782344bb59345468a"></a><a name="afa4284a82e8544c782344bb59345468a"></a>Represents the latest available observations of a replication controller's current state.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row30705591"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p4124972"><a name="en-us_topic_0079614930_p4124972"></a><a name="en-us_topic_0079614930_p4124972"></a>observedGeneration</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p65687338"><a name="en-us_topic_0079614930_p65687338"></a><a name="en-us_topic_0079614930_p65687338"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p19074136"><a name="en-us_topic_0079614930_p19074136"></a><a name="en-us_topic_0079614930_p19074136"></a>ObservedGeneration reflects the generation of the most recently observed replication controller.</p>
</td>
</tr>
</tbody>
</table>

**Table  20**  Data structure of the initializers field

<a name="t050e77dc2b1644c895d89f389e46d859"></a>
<table><thead align="left"><tr id="r39b5f5cdeea442f09d57a73438a3cbdd"><th class="cellrowborder" valign="top" width="26%" id="mcps1.2.4.1.1"><p id="a8a1d268a8df74d4db1422b3adb240425"><a name="a8a1d268a8df74d4db1422b3adb240425"></a><a name="a8a1d268a8df74d4db1422b3adb240425"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.2.4.1.2"><p id="a07f341acaa7849438020dfbacc8283e2"><a name="a07f341acaa7849438020dfbacc8283e2"></a><a name="a07f341acaa7849438020dfbacc8283e2"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44%" id="mcps1.2.4.1.3"><p id="en-us_topic_0079614930_p12832140407"><a name="en-us_topic_0079614930_p12832140407"></a><a name="en-us_topic_0079614930_p12832140407"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r232080d946b142898970428e54b64066"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p128321049407"><a name="en-us_topic_0079614930_p128321049407"></a><a name="en-us_topic_0079614930_p128321049407"></a>pending</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p683244194010"><a name="en-us_topic_0079614930_p683244194010"></a><a name="en-us_topic_0079614930_p683244194010"></a><a href="#t692762a9bbc843b5896568bfd21b9648">pending</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p783254124017"><a name="en-us_topic_0079614930_p783254124017"></a><a name="en-us_topic_0079614930_p783254124017"></a>Pending is a list of initializers that must execute in order before this object is visible. When the last pending initializer is removed, and no failing result is set, the initializers struct will be set to nil and the object is considered as initialized and visible to all clients.</p>
</td>
</tr>
<tr id="r80ee49e795914b3682ccb2c3036316df"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="a0b303b01e17f4f90b3301f27cff4d110"><a name="a0b303b01e17f4f90b3301f27cff4d110"></a><a name="a0b303b01e17f4f90b3301f27cff4d110"></a>result</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="aab398b49ed3b474f9f5d27b8b4e601ca"><a name="aab398b49ed3b474f9f5d27b8b4e601ca"></a><a name="aab398b49ed3b474f9f5d27b8b4e601ca"></a><a href="#t6c6ba0cfa7084a419291c2d12d305875">result</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44%" headers="mcps1.2.4.1.3 "><p id="ae5bef952a21c49b38dde750f6f144520"><a name="ae5bef952a21c49b38dde750f6f144520"></a><a name="ae5bef952a21c49b38dde750f6f144520"></a>If result is set with the Failure field, the object will be persisted to storage and then deleted, ensuring that other clients can observe the deletion.</p>
</td>
</tr>
</tbody>
</table>

**Table  21**  Data structure of the pending field

<a name="t692762a9bbc843b5896568bfd21b9648"></a>
<table><thead align="left"><tr id="r18c9e95961b54866b7b590339b3ed99d"><th class="cellrowborder" valign="top" width="25.742574257425744%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p284419416407"><a name="en-us_topic_0079614930_p284419416407"></a><a name="en-us_topic_0079614930_p284419416407"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="29.7029702970297%" id="mcps1.2.4.1.2"><p id="ac7a11661036d4bf18bbe2c8e319cd85e"><a name="ac7a11661036d4bf18bbe2c8e319cd85e"></a><a name="ac7a11661036d4bf18bbe2c8e319cd85e"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.554455445544555%" id="mcps1.2.4.1.3"><p id="en-us_topic_0079614930_p148446494015"><a name="en-us_topic_0079614930_p148446494015"></a><a name="en-us_topic_0079614930_p148446494015"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r86efd501d40e4300a1d414f0d07d16cc"><td class="cellrowborder" valign="top" width="25.742574257425744%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p88441484015"><a name="en-us_topic_0079614930_p88441484015"></a><a name="en-us_topic_0079614930_p88441484015"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="29.7029702970297%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p584414124010"><a name="en-us_topic_0079614930_p584414124010"></a><a name="en-us_topic_0079614930_p584414124010"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.554455445544555%" headers="mcps1.2.4.1.3 "><p id="ab74127e3bb24471389d398b83e1879db"><a name="ab74127e3bb24471389d398b83e1879db"></a><a name="ab74127e3bb24471389d398b83e1879db"></a>name of the process that is responsible for initializing this object.</p>
</td>
</tr>
</tbody>
</table>

**Table  22**  Data structure of the result field

<a name="t6c6ba0cfa7084a419291c2d12d305875"></a>
<table><thead align="left"><tr id="rdf2ec7121be34ff282d0b8aa63a8386d"><th class="cellrowborder" valign="top" width="26%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p2856044409"><a name="en-us_topic_0079614930_p2856044409"></a><a name="en-us_topic_0079614930_p2856044409"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="28.999999999999996%" id="mcps1.2.4.1.2"><p id="en-us_topic_0079614930_p168561148407"><a name="en-us_topic_0079614930_p168561148407"></a><a name="en-us_topic_0079614930_p168561148407"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="en-us_topic_0079614930_p38561644407"><a name="en-us_topic_0079614930_p38561644407"></a><a name="en-us_topic_0079614930_p38561644407"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r5767ecbc13c64b7495eec05eb4e3ce7c"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p48562041405"><a name="en-us_topic_0079614930_p48562041405"></a><a name="en-us_topic_0079614930_p48562041405"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p7857943407"><a name="en-us_topic_0079614930_p7857943407"></a><a name="en-us_topic_0079614930_p7857943407"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p108571048404"><a name="en-us_topic_0079614930_p108571048404"></a><a name="en-us_topic_0079614930_p108571048404"></a>APIVersion defines the versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
</td>
</tr>
<tr id="r83622f935d634259912e5784dd8d2899"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p178576411405"><a name="en-us_topic_0079614930_p178576411405"></a><a name="en-us_topic_0079614930_p178576411405"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p78574411409"><a name="en-us_topic_0079614930_p78574411409"></a><a name="en-us_topic_0079614930_p78574411409"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p785764154017"><a name="en-us_topic_0079614930_p785764154017"></a><a name="en-us_topic_0079614930_p785764154017"></a>Suggested HTTP return code for this status, 0 if not set.</p>
</td>
</tr>
<tr id="r3f56a6a641324124af9617a10a798517"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="a4a94c6b95e754a27ad1996ce074f9d7e"><a name="a4a94c6b95e754a27ad1996ce074f9d7e"></a><a name="a4a94c6b95e754a27ad1996ce074f9d7e"></a>details</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p198578414402"><a name="en-us_topic_0079614930_p198578414402"></a><a name="en-us_topic_0079614930_p198578414402"></a><a href="#t8621cc18eac440e38feedc125a229d1d">details</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="aa6e300126b5744178a6332bcd99051fe"><a name="aa6e300126b5744178a6332bcd99051fe"></a><a name="aa6e300126b5744178a6332bcd99051fe"></a>Extended data associated with the reason. Each reason may define its own extended details. This field is optional and the data returned is not guaranteed to conform to any schema except that defined by the reason type.</p>
</td>
</tr>
<tr id="re4d71d5cf45d40d6b4af806e039c9b96"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="a703e388ca3da4d2a8fbbdac14c345502"><a name="a703e388ca3da4d2a8fbbdac14c345502"></a><a name="a703e388ca3da4d2a8fbbdac14c345502"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p785715484014"><a name="en-us_topic_0079614930_p785715484014"></a><a name="en-us_topic_0079614930_p785715484014"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p885812494014"><a name="en-us_topic_0079614930_p885812494014"></a><a name="en-us_topic_0079614930_p885812494014"></a>Kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated.</p>
</td>
</tr>
<tr id="r1bd8ad14d231412e8163aae4245a6092"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p148582412401"><a name="en-us_topic_0079614930_p148582412401"></a><a name="en-us_topic_0079614930_p148582412401"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p58585464014"><a name="en-us_topic_0079614930_p58585464014"></a><a name="en-us_topic_0079614930_p58585464014"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p168588444017"><a name="en-us_topic_0079614930_p168588444017"></a><a name="en-us_topic_0079614930_p168588444017"></a>A human-readable description of the status of this operation.</p>
</td>
</tr>
<tr id="rf95715f7e760438589d074b2536084fd"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p185817444010"><a name="en-us_topic_0079614930_p185817444010"></a><a name="en-us_topic_0079614930_p185817444010"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="a51f9cce578f647eda2dd697fca2de741"><a name="a51f9cce578f647eda2dd697fca2de741"></a><a name="a51f9cce578f647eda2dd697fca2de741"></a><a href="#te555e6efe7cd4ab8809d83b30977a22a">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a462a88bd344a40cbad92920a471cf610"><a name="a462a88bd344a40cbad92920a471cf610"></a><a name="a462a88bd344a40cbad92920a471cf610"></a>Standard list metadata.</p>
</td>
</tr>
<tr id="r5a2003f28f834829b7e4ed8c4c121449"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p78591046404"><a name="en-us_topic_0079614930_p78591046404"></a><a name="en-us_topic_0079614930_p78591046404"></a>reason</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p685918454011"><a name="en-us_topic_0079614930_p685918454011"></a><a name="en-us_topic_0079614930_p685918454011"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="ab1144d0c74d843ef88df2ca4aca93559"><a name="ab1144d0c74d843ef88df2ca4aca93559"></a><a name="ab1144d0c74d843ef88df2ca4aca93559"></a>A machine-readable description of why this operation is in the "Failure" status. If this value is empty there is no information available. A Reason clarifies an HTTP status code but does not override it.</p>
</td>
</tr>
<tr id="rb66bfa79993b449c8da76a10c0748d45"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="a7b4b0e5fda6f4831803727f84e7fd765"><a name="a7b4b0e5fda6f4831803727f84e7fd765"></a><a name="a7b4b0e5fda6f4831803727f84e7fd765"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p208597414019"><a name="en-us_topic_0079614930_p208597414019"></a><a name="en-us_topic_0079614930_p208597414019"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p78609417401"><a name="en-us_topic_0079614930_p78609417401"></a><a name="en-us_topic_0079614930_p78609417401"></a>Status of the operation. One of: "Success" or "Failure".</p>
</td>
</tr>
</tbody>
</table>

**Table  23**  Data structure of the details field

<a name="t8621cc18eac440e38feedc125a229d1d"></a>
<table><thead align="left"><tr id="rdfcdd7483a2f4f95a2e24a83d7f02b9f"><th class="cellrowborder" valign="top" width="26%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p68711346409"><a name="en-us_topic_0079614930_p68711346409"></a><a name="en-us_topic_0079614930_p68711346409"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="28.999999999999996%" id="mcps1.2.4.1.2"><p id="en-us_topic_0079614930_p198712040408"><a name="en-us_topic_0079614930_p198712040408"></a><a name="en-us_topic_0079614930_p198712040408"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="abe53a8baf4284ddd9386b32fa5ee045f"><a name="abe53a8baf4284ddd9386b32fa5ee045f"></a><a name="abe53a8baf4284ddd9386b32fa5ee045f"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r56ace96e6e5245819c1d1eeb08255212"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="ac0a6b02cc2644d5b9f1f7d28f9f65332"><a name="ac0a6b02cc2644d5b9f1f7d28f9f65332"></a><a name="ac0a6b02cc2644d5b9f1f7d28f9f65332"></a>causes</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p487284194011"><a name="en-us_topic_0079614930_p487284194011"></a><a name="en-us_topic_0079614930_p487284194011"></a><a href="#t1193c22aa5984fd0b43bfc8f02276db7">causes</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p15872147403"><a name="en-us_topic_0079614930_p15872147403"></a><a name="en-us_topic_0079614930_p15872147403"></a>The Causes array includes more details associated with the StatusReason failure. Not all StatusReasons may provide detailed causes.</p>
</td>
</tr>
<tr id="r6f25067706ef4f8082705eeb792fe209"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p148727474016"><a name="en-us_topic_0079614930_p148727474016"></a><a name="en-us_topic_0079614930_p148727474016"></a>group</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p188721443409"><a name="en-us_topic_0079614930_p188721443409"></a><a name="en-us_topic_0079614930_p188721443409"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p118721445409"><a name="en-us_topic_0079614930_p118721445409"></a><a name="en-us_topic_0079614930_p118721445409"></a>The group attribute of the resource associated with the status StatusReason.</p>
</td>
</tr>
<tr id="r3337d00864604383acf105269d55e74c"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="a672a4cbd52374453a2b3247fec15ccb7"><a name="a672a4cbd52374453a2b3247fec15ccb7"></a><a name="a672a4cbd52374453a2b3247fec15ccb7"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="a0c76b84dbb3f4b14bea48ad432bbd16b"><a name="a0c76b84dbb3f4b14bea48ad432bbd16b"></a><a name="a0c76b84dbb3f4b14bea48ad432bbd16b"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="aecf134c53d144b7496c244fa4766778a"><a name="aecf134c53d144b7496c244fa4766778a"></a><a name="aecf134c53d144b7496c244fa4766778a"></a>The kind attribute of the resource associated with the status StatusReason. On some operations may differ from the requested resource Kind.</p>
</td>
</tr>
<tr id="r09445815aea049058020e3078e2d7f13"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="aeb54deb421ad47bf9d001d07f63beab9"><a name="aeb54deb421ad47bf9d001d07f63beab9"></a><a name="aeb54deb421ad47bf9d001d07f63beab9"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="a47e695bb5cbc4a45a23bd8c4380275dd"><a name="a47e695bb5cbc4a45a23bd8c4380275dd"></a><a name="a47e695bb5cbc4a45a23bd8c4380275dd"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="ad641265e64c54acbb47a9403cc4250a5"><a name="ad641265e64c54acbb47a9403cc4250a5"></a><a name="ad641265e64c54acbb47a9403cc4250a5"></a>The name attribute of the resource associated with the status StatusReason (when there is a single name which can be described).</p>
</td>
</tr>
<tr id="r470ef158a33640098d5cd828f3c74770"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p98731449407"><a name="en-us_topic_0079614930_p98731449407"></a><a name="en-us_topic_0079614930_p98731449407"></a>retryAfterSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p198739413408"><a name="en-us_topic_0079614930_p198739413408"></a><a name="en-us_topic_0079614930_p198739413408"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p178732434018"><a name="en-us_topic_0079614930_p178732434018"></a><a name="en-us_topic_0079614930_p178732434018"></a>If specified, the time in seconds before the operation should be retried.</p>
</td>
</tr>
<tr id="r2be4bfe1f2b7405e86df43bd0d33f31b"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p148731248406"><a name="en-us_topic_0079614930_p148731248406"></a><a name="en-us_topic_0079614930_p148731248406"></a>uid</p>
</td>
<td class="cellrowborder" valign="top" width="28.999999999999996%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p78737484019"><a name="en-us_topic_0079614930_p78737484019"></a><a name="en-us_topic_0079614930_p78737484019"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p198739412409"><a name="en-us_topic_0079614930_p198739412409"></a><a name="en-us_topic_0079614930_p198739412409"></a>UID of the resource. (when there is a single resource which can be described).</p>
</td>
</tr>
</tbody>
</table>

**Table  24**  Data structure of the metadata field

<a name="te555e6efe7cd4ab8809d83b30977a22a"></a>
<table><thead align="left"><tr id="re7eb25a1f0214f5abef00c68a99a4f94"><th class="cellrowborder" valign="top" width="27%" id="mcps1.2.4.1.1"><p id="af2c106ca72684cb5b4f7eaaac59f15e6"><a name="af2c106ca72684cb5b4f7eaaac59f15e6"></a><a name="af2c106ca72684cb5b4f7eaaac59f15e6"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="28.000000000000004%" id="mcps1.2.4.1.2"><p id="ac3e6fe9bbe0146e6a82e1af48b844f31"><a name="ac3e6fe9bbe0146e6a82e1af48b844f31"></a><a name="ac3e6fe9bbe0146e6a82e1af48b844f31"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="en-us_topic_0079614930_p158866484011"><a name="en-us_topic_0079614930_p158866484011"></a><a name="en-us_topic_0079614930_p158866484011"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="rbdbc2524f4ad4223936ffd49f1a6c2b1"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p788604174011"><a name="en-us_topic_0079614930_p788604174011"></a><a name="en-us_topic_0079614930_p788604174011"></a>resourceVersion</p>
</td>
<td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p9886241400"><a name="en-us_topic_0079614930_p9886241400"></a><a name="en-us_topic_0079614930_p9886241400"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p118863464016"><a name="en-us_topic_0079614930_p118863464016"></a><a name="en-us_topic_0079614930_p118863464016"></a>String that identifies the server's internal version of this object that can be used by clients to determine when objects have changed. Value must be treated as opaque by clients and passed unmodified back to the server. Populated by the system. Read-only.</p>
</td>
</tr>
<tr id="r2fd7a272928841c48d3c794f2e28b49e"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="abc54d0565e6c459d9ab7773ef026a2fd"><a name="abc54d0565e6c459d9ab7773ef026a2fd"></a><a name="abc54d0565e6c459d9ab7773ef026a2fd"></a>selfLink</p>
</td>
<td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p288684144015"><a name="en-us_topic_0079614930_p288684144015"></a><a name="en-us_topic_0079614930_p288684144015"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p88861043401"><a name="en-us_topic_0079614930_p88861043401"></a><a name="en-us_topic_0079614930_p88861043401"></a>SelfLink is a URL representing this object. Populated by the system. Read-only.</p>
</td>
</tr>
</tbody>
</table>

**Table  25**  Data structure of the causes field

<a name="t1193c22aa5984fd0b43bfc8f02276db7"></a>
<table><thead align="left"><tr id="r4ac138286cf641609437f2ade7ace6d1"><th class="cellrowborder" valign="top" width="27%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p188975454017"><a name="en-us_topic_0079614930_p188975454017"></a><a name="en-us_topic_0079614930_p188975454017"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="27%" id="mcps1.2.4.1.2"><p id="en-us_topic_0079614930_p3898547403"><a name="en-us_topic_0079614930_p3898547403"></a><a name="en-us_topic_0079614930_p3898547403"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="46%" id="mcps1.2.4.1.3"><p id="a2f671e3aaa5342078731c1b4ebb3c19d"><a name="a2f671e3aaa5342078731c1b4ebb3c19d"></a><a name="a2f671e3aaa5342078731c1b4ebb3c19d"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r1e39c0b1d98946c5892a58a7acde7ce2"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p589819494014"><a name="en-us_topic_0079614930_p589819494014"></a><a name="en-us_topic_0079614930_p589819494014"></a>field</p>
</td>
<td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p16898242401"><a name="en-us_topic_0079614930_p16898242401"></a><a name="en-us_topic_0079614930_p16898242401"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46%" headers="mcps1.2.4.1.3 "><p id="ad3e401bec85f4764b8e7f54ed1318646"><a name="ad3e401bec85f4764b8e7f54ed1318646"></a><a name="ad3e401bec85f4764b8e7f54ed1318646"></a>The field of the resource that has caused this error, as named by its JSON serialization. May include dot and postfix notation for nested attributes. Arrays are zero-indexed. Fields may appear more than once in an array of causes due to fields having multiple errors. Optional. Examples: "name" - the field "name" on the current resource "items[0].name" - the field "name" on the first array entry in "items"</p>
</td>
</tr>
<tr id="r139cf020bd6e463a9e7fb1153dcd4c26"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p108989484017"><a name="en-us_topic_0079614930_p108989484017"></a><a name="en-us_topic_0079614930_p108989484017"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p0898647409"><a name="en-us_topic_0079614930_p0898647409"></a><a name="en-us_topic_0079614930_p0898647409"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46%" headers="mcps1.2.4.1.3 "><p id="a207be7161dde4f41a191b965c99f48d8"><a name="a207be7161dde4f41a191b965c99f48d8"></a><a name="a207be7161dde4f41a191b965c99f48d8"></a>A human-readable description of the cause of the error. This field may be presented as-is to a reader.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row5898247409"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p138981344407"><a name="en-us_topic_0079614930_p138981344407"></a><a name="en-us_topic_0079614930_p138981344407"></a>reason</p>
</td>
<td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p188987417406"><a name="en-us_topic_0079614930_p188987417406"></a><a name="en-us_topic_0079614930_p188987417406"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="46%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p089916464019"><a name="en-us_topic_0079614930_p089916464019"></a><a name="en-us_topic_0079614930_p089916464019"></a>A machine-readable description of the cause of the error. If this value is empty there is no information available.</p>
</td>
</tr>
</tbody>
</table>

**Table  26**  Data structure of the ownerReferences field

<a name="t9b2c5d4719b24ea6a40f0f5e7bd366b8"></a>
<table><thead align="left"><tr id="r3a26942761ab4b7d92867b3a8805dcee"><th class="cellrowborder" valign="top" width="27%" id="mcps1.2.4.1.1"><p id="a995203116d034393912ffdae279c4b79"><a name="a995203116d034393912ffdae279c4b79"></a><a name="a995203116d034393912ffdae279c4b79"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="28.000000000000004%" id="mcps1.2.4.1.2"><p id="p873531665917"><a name="p873531665917"></a><a name="p873531665917"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="p10735816125919"><a name="p10735816125919"></a><a name="p10735816125919"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r1a8b239f51da4dceae42456a93544db2"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="a44a242c839ef4b24800dc0f7bc93a66e"><a name="a44a242c839ef4b24800dc0f7bc93a66e"></a><a name="a44a242c839ef4b24800dc0f7bc93a66e"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.2.4.1.2 "><p id="acb8e910f46684c8db48930642fd088e2"><a name="acb8e910f46684c8db48930642fd088e2"></a><a name="acb8e910f46684c8db48930642fd088e2"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a85cbb86313294a4e8ee15e1d5762b3bc"><a name="a85cbb86313294a4e8ee15e1d5762b3bc"></a><a name="a85cbb86313294a4e8ee15e1d5762b3bc"></a>API version of the referent.</p>
</td>
</tr>
<tr id="r9448286cd2084b2aac7b92a09c6b7a2a"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="a3fd6b15a3f0548599ee2f25244878c12"><a name="a3fd6b15a3f0548599ee2f25244878c12"></a><a name="a3fd6b15a3f0548599ee2f25244878c12"></a>blockOwnerDeletion</p>
</td>
<td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p686552923317"><a name="en-us_topic_0079614930_p686552923317"></a><a name="en-us_topic_0079614930_p686552923317"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a8e45550fc29f4b248bfe0222ed5979ba"><a name="a8e45550fc29f4b248bfe0222ed5979ba"></a><a name="a8e45550fc29f4b248bfe0222ed5979ba"></a>If true, AND if the owner has the "foregroundDeletion" finalizer, then the owner cannot be deleted from the key-value store until this reference is removed. Defaults to false. To set this field, a user needs "delete" permission of the owner, otherwise 422 (Unprocessable Entity) will be returned.</p>
</td>
</tr>
<tr id="r2122474b79994b8ab649ae21e2ad14e4"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="a79406e46e80a4784bdf0cf5a334bc7a9"><a name="a79406e46e80a4784bdf0cf5a334bc7a9"></a><a name="a79406e46e80a4784bdf0cf5a334bc7a9"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.2.4.1.2 "><p id="adc55f19b96554b7f97ba3484f1eedabe"><a name="adc55f19b96554b7f97ba3484f1eedabe"></a><a name="adc55f19b96554b7f97ba3484f1eedabe"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a427d108ac8614fc49a408f89d41bcfbe"><a name="a427d108ac8614fc49a408f89d41bcfbe"></a><a name="a427d108ac8614fc49a408f89d41bcfbe"></a>Kind of the referent.</p>
</td>
</tr>
<tr id="rea463ff566b4492d9207a46c05c2669a"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="a30c27f0b447e4cd781122ce4c4fd99f0"><a name="a30c27f0b447e4cd781122ce4c4fd99f0"></a><a name="a30c27f0b447e4cd781122ce4c4fd99f0"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.2.4.1.2 "><p id="ac0e9f31f73c54e3fa7073671d1170589"><a name="ac0e9f31f73c54e3fa7073671d1170589"></a><a name="ac0e9f31f73c54e3fa7073671d1170589"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a06e799f5e44c456dacbf4bf50d2fd506"><a name="a06e799f5e44c456dacbf4bf50d2fd506"></a><a name="a06e799f5e44c456dacbf4bf50d2fd506"></a>Name of the referent.</p>
</td>
</tr>
<tr id="r6027962dc03944498bc15c09001ee4e0"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="a1920898a5bb24b219fa649bff32ae744"><a name="a1920898a5bb24b219fa649bff32ae744"></a><a name="a1920898a5bb24b219fa649bff32ae744"></a>uid</p>
</td>
<td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.2.4.1.2 "><p id="a3ef8333f47284017af6e5ab4aa485109"><a name="a3ef8333f47284017af6e5ab4aa485109"></a><a name="a3ef8333f47284017af6e5ab4aa485109"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a2951e72e0c2c4af082ba801befefb50d"><a name="a2951e72e0c2c4af082ba801befefb50d"></a><a name="a2951e72e0c2c4af082ba801befefb50d"></a>UID of the referent.</p>
</td>
</tr>
<tr id="ra8871fdbe3cd4e3281288e9c423825b7"><td class="cellrowborder" valign="top" width="27%" headers="mcps1.2.4.1.1 "><p id="ab2fa7b22fe1f4085b07690fdd8b7ac0c"><a name="ab2fa7b22fe1f4085b07690fdd8b7ac0c"></a><a name="ab2fa7b22fe1f4085b07690fdd8b7ac0c"></a>controller</p>
</td>
<td class="cellrowborder" valign="top" width="28.000000000000004%" headers="mcps1.2.4.1.2 "><p id="a1cb9a0c8a0934ceda4dd7c57401c5140"><a name="a1cb9a0c8a0934ceda4dd7c57401c5140"></a><a name="a1cb9a0c8a0934ceda4dd7c57401c5140"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a5665913c90e7404794a2c4dfb3fd84a1"><a name="a5665913c90e7404794a2c4dfb3fd84a1"></a><a name="a5665913c90e7404794a2c4dfb3fd84a1"></a>If true, this reference points to the managing controller.</p>
</td>
</tr>
</tbody>
</table>

**Table  27**  Data structure of the template field

<a name="en-us_topic_0079614930_table4399144"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row57734587"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p45989946"><a name="en-us_topic_0079614930_p45989946"></a><a name="en-us_topic_0079614930_p45989946"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1473771605912"><a name="p1473771605912"></a><a name="p1473771605912"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p4737121611594"><a name="p4737121611594"></a><a name="p4737121611594"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row29024834"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p2201379"><a name="en-us_topic_0079614930_p2201379"></a><a name="en-us_topic_0079614930_p2201379"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a7f488c22b0f74226b008d9081296131a"><a name="a7f488c22b0f74226b008d9081296131a"></a><a name="a7f488c22b0f74226b008d9081296131a"></a><a href="#en-us_topic_0079614930_table33054158">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p14848227"><a name="en-us_topic_0079614930_p14848227"></a><a name="en-us_topic_0079614930_p14848227"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row66525186"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p19830949"><a name="en-us_topic_0079614930_p19830949"></a><a name="en-us_topic_0079614930_p19830949"></a>spec</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a18a6615544394fb1bae1b58bc214799c"><a name="a18a6615544394fb1bae1b58bc214799c"></a><a name="a18a6615544394fb1bae1b58bc214799c"></a><a href="#en-us_topic_0079614930_table39592297">spec</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p53884223"><a name="en-us_topic_0079614930_p53884223"></a><a name="en-us_topic_0079614930_p53884223"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  28**  Data structure of the spec field

<a name="en-us_topic_0079614930_table39592297"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row10450704"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p41200727"><a name="en-us_topic_0079614930_p41200727"></a><a name="en-us_topic_0079614930_p41200727"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p973815166591"><a name="p973815166591"></a><a name="p973815166591"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p173861695912"><a name="p173861695912"></a><a name="p173861695912"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row12300244"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p56795708"><a name="en-us_topic_0079614930_p56795708"></a><a name="en-us_topic_0079614930_p56795708"></a>volumes</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a201dcc7da19f48c49414ba66af6910bd"><a name="a201dcc7da19f48c49414ba66af6910bd"></a><a name="a201dcc7da19f48c49414ba66af6910bd"></a><a href="#en-us_topic_0079614930_table20786353">volumes</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p48231578"><a name="en-us_topic_0079614930_p48231578"></a><a name="en-us_topic_0079614930_p48231578"></a>List of volumes that can be mounted by containers belonging to the pod.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row31431022"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p62884833"><a name="en-us_topic_0079614930_p62884833"></a><a name="en-us_topic_0079614930_p62884833"></a>containers</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a1cca5a822e3b42cda35a6851fde6e5e2"><a name="a1cca5a822e3b42cda35a6851fde6e5e2"></a><a name="a1cca5a822e3b42cda35a6851fde6e5e2"></a><a href="#en-us_topic_0079614930_table21660524">containers</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p2094376"><a name="en-us_topic_0079614930_p2094376"></a><a name="en-us_topic_0079614930_p2094376"></a>List of containers belonging to the pod. Containers cannot currently be added or removed. There must be at least one container in a Pod. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row18849388"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p50405427"><a name="en-us_topic_0079614930_p50405427"></a><a name="en-us_topic_0079614930_p50405427"></a>restartPolicy</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p56307807"><a name="en-us_topic_0079614930_p56307807"></a><a name="en-us_topic_0079614930_p56307807"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p64638552"><a name="en-us_topic_0079614930_p64638552"></a><a name="en-us_topic_0079614930_p64638552"></a>Restart policy for all containers within the pod. One of Always, OnFailure, Never. Default to Always.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row44876061"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p11082291"><a name="en-us_topic_0079614930_p11082291"></a><a name="en-us_topic_0079614930_p11082291"></a>terminationGracePeriodSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p25250378"><a name="en-us_topic_0079614930_p25250378"></a><a name="en-us_topic_0079614930_p25250378"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p32014729"><a name="en-us_topic_0079614930_p32014729"></a><a name="en-us_topic_0079614930_p32014729"></a>Optional duration in seconds the pod needs to terminate gracefully. May be decreased in delete request. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period will be used instead. The grace period is the duration in seconds after the processes running in the pod are sent a termination signal and the time when the processes are forcibly halted with a kill signal. Set this value longer than the expected cleanup time for your process. Defaults to 30 seconds.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row19697112"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p51962215"><a name="en-us_topic_0079614930_p51962215"></a><a name="en-us_topic_0079614930_p51962215"></a>activeDeadlineSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p48189875"><a name="en-us_topic_0079614930_p48189875"></a><a name="en-us_topic_0079614930_p48189875"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p11065763"><a name="en-us_topic_0079614930_p11065763"></a><a name="en-us_topic_0079614930_p11065763"></a>Optional duration in seconds the pod may be active on the node relative to StartTime before the system will actively try to mark it failed and kill associated containers. Value must be a positive integer.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row32483004"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p13877662"><a name="en-us_topic_0079614930_p13877662"></a><a name="en-us_topic_0079614930_p13877662"></a>dnsPolicy</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p50348824"><a name="en-us_topic_0079614930_p50348824"></a><a name="en-us_topic_0079614930_p50348824"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p51722963"><a name="en-us_topic_0079614930_p51722963"></a><a name="en-us_topic_0079614930_p51722963"></a>Set DNS policy for containers within the pod. One of 'ClusterFirst' or 'Default'. Defaults to "ClusterFirst".</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row62853488"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p57967791"><a name="en-us_topic_0079614930_p57967791"></a><a name="en-us_topic_0079614930_p57967791"></a>serviceAccountName</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p64879490"><a name="en-us_topic_0079614930_p64879490"></a><a name="en-us_topic_0079614930_p64879490"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p20747346"><a name="en-us_topic_0079614930_p20747346"></a><a name="en-us_topic_0079614930_p20747346"></a>ServiceAccountName is the name of the ServiceAccount to use to run this pod.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row52508388"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p25321017"><a name="en-us_topic_0079614930_p25321017"></a><a name="en-us_topic_0079614930_p25321017"></a>serviceAccount</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p37736511"><a name="en-us_topic_0079614930_p37736511"></a><a name="en-us_topic_0079614930_p37736511"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p36758557"><a name="en-us_topic_0079614930_p36758557"></a><a name="en-us_topic_0079614930_p36758557"></a>DeprecatedServiceAccount is a depreciated alias for ServiceAccountName. Deprecated: Use serviceAccountName instead.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row62391565"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p20552036"><a name="en-us_topic_0079614930_p20552036"></a><a name="en-us_topic_0079614930_p20552036"></a>nodeName</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p54102182"><a name="en-us_topic_0079614930_p54102182"></a><a name="en-us_topic_0079614930_p54102182"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p20200637"><a name="en-us_topic_0079614930_p20200637"></a><a name="en-us_topic_0079614930_p20200637"></a>NodeName is a request to schedule this pod onto a specific node. If it is non-empty, the scheduler simply schedules this pod onto that node, assuming that it fits resource requirements.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row47588012"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p29423773"><a name="en-us_topic_0079614930_p29423773"></a><a name="en-us_topic_0079614930_p29423773"></a>hostNetwork</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p34515414"><a name="en-us_topic_0079614930_p34515414"></a><a name="en-us_topic_0079614930_p34515414"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p44285184"><a name="en-us_topic_0079614930_p44285184"></a><a name="en-us_topic_0079614930_p44285184"></a>Host networking requested for this pod. Use the host's network namespace. If this option is set, the ports that will be used must be specified. Default to false.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row63022343"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p4536157"><a name="en-us_topic_0079614930_p4536157"></a><a name="en-us_topic_0079614930_p4536157"></a>hostPID</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p31884407"><a name="en-us_topic_0079614930_p31884407"></a><a name="en-us_topic_0079614930_p31884407"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p32500157"><a name="en-us_topic_0079614930_p32500157"></a><a name="en-us_topic_0079614930_p32500157"></a>Use the host's pid namespace. Optional: Default to false.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row24065965"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p3186145"><a name="en-us_topic_0079614930_p3186145"></a><a name="en-us_topic_0079614930_p3186145"></a>hostIPC</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p56751222"><a name="en-us_topic_0079614930_p56751222"></a><a name="en-us_topic_0079614930_p56751222"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p33446292"><a name="en-us_topic_0079614930_p33446292"></a><a name="en-us_topic_0079614930_p33446292"></a>Use the host's ipc namespace. Optional: Default to false.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row32581173"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p21829362"><a name="en-us_topic_0079614930_p21829362"></a><a name="en-us_topic_0079614930_p21829362"></a>securityContext</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p23347916"><a name="en-us_topic_0079614930_p23347916"></a><a name="en-us_topic_0079614930_p23347916"></a><a href="#en-us_topic_0079614930_ref458875925">securityContext</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p42088446"><a name="en-us_topic_0079614930_p42088446"></a><a name="en-us_topic_0079614930_p42088446"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row43251701"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p13726868"><a name="en-us_topic_0079614930_p13726868"></a><a name="en-us_topic_0079614930_p13726868"></a>imagePullSecrets</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p38134512"><a name="en-us_topic_0079614930_p38134512"></a><a name="en-us_topic_0079614930_p38134512"></a><a href="#en-us_topic_0079614930_ref458875945">imagePullSecrets</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p16989553"><a name="en-us_topic_0079614930_p16989553"></a><a name="en-us_topic_0079614930_p16989553"></a>ImagePullSecrets is an optional list of references to secrets in the same namespace to use for pulling any of the images used by this PodSpec. If specified, these secrets will be passed to individual puller implementations for them to use. For example, in the case of docker, only DockerConfig type secrets are honored.</p>
</td>
</tr>
</tbody>
</table>

**Table  29**  Data structure of the volumes field

<a name="en-us_topic_0079614930_table20786353"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row61654013"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p27919180"><a name="en-us_topic_0079614930_p27919180"></a><a name="en-us_topic_0079614930_p27919180"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1774481605919"><a name="p1774481605919"></a><a name="p1774481605919"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p37446168597"><a name="p37446168597"></a><a name="p37446168597"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row29994707"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p13652196"><a name="en-us_topic_0079614930_p13652196"></a><a name="en-us_topic_0079614930_p13652196"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p32086057"><a name="en-us_topic_0079614930_p32086057"></a><a name="en-us_topic_0079614930_p32086057"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p48833802"><a name="en-us_topic_0079614930_p48833802"></a><a name="en-us_topic_0079614930_p48833802"></a>Volume's name. Must be a DNS_LABEL and unique within the pod.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row36851041"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p32144377"><a name="en-us_topic_0079614930_p32144377"></a><a name="en-us_topic_0079614930_p32144377"></a>hostPath</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p53557729"><a name="en-us_topic_0079614930_p53557729"></a><a name="en-us_topic_0079614930_p53557729"></a><a href="#en-us_topic_0079614930_ref458875954">hostPath</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p53334606"><a name="en-us_topic_0079614930_p53334606"></a><a name="en-us_topic_0079614930_p53334606"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row10249410"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24895883"><a name="en-us_topic_0079614930_p24895883"></a><a name="en-us_topic_0079614930_p24895883"></a>emptyDir</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p3300677"><a name="en-us_topic_0079614930_p3300677"></a><a name="en-us_topic_0079614930_p3300677"></a><a href="#en-us_topic_0079614930_ref458875962">emptyDir</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p57383898"><a name="en-us_topic_0079614930_p57383898"></a><a name="en-us_topic_0079614930_p57383898"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row42109460"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p55423091"><a name="en-us_topic_0079614930_p55423091"></a><a name="en-us_topic_0079614930_p55423091"></a>gitRepo</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p60085411"><a name="en-us_topic_0079614930_p60085411"></a><a name="en-us_topic_0079614930_p60085411"></a><a href="#en-us_topic_0079614930_ref458875979">gitRepo</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p47285805"><a name="en-us_topic_0079614930_p47285805"></a><a name="en-us_topic_0079614930_p47285805"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row22919061"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p44504614"><a name="en-us_topic_0079614930_p44504614"></a><a name="en-us_topic_0079614930_p44504614"></a>secret</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p48103976"><a name="en-us_topic_0079614930_p48103976"></a><a name="en-us_topic_0079614930_p48103976"></a><a href="#en-us_topic_0079614930_ref458875984">secret</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p36971736"><a name="en-us_topic_0079614930_p36971736"></a><a name="en-us_topic_0079614930_p36971736"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row64310173"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p41741537"><a name="en-us_topic_0079614930_p41741537"></a><a name="en-us_topic_0079614930_p41741537"></a>nfs</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p25621300"><a name="en-us_topic_0079614930_p25621300"></a><a name="en-us_topic_0079614930_p25621300"></a><a href="#en-us_topic_0079614930_ref458875989">nfs</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p21664204"><a name="en-us_topic_0079614930_p21664204"></a><a name="en-us_topic_0079614930_p21664204"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row60760110"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p22621859"><a name="en-us_topic_0079614930_p22621859"></a><a name="en-us_topic_0079614930_p22621859"></a>iscsi</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p20431305"><a name="en-us_topic_0079614930_p20431305"></a><a name="en-us_topic_0079614930_p20431305"></a><a href="#en-us_topic_0079614930_ref458875996">iscsi</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p63362823"><a name="en-us_topic_0079614930_p63362823"></a><a name="en-us_topic_0079614930_p63362823"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row33394502"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p20600174"><a name="en-us_topic_0079614930_p20600174"></a><a name="en-us_topic_0079614930_p20600174"></a>glusterfs</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p58001382"><a name="en-us_topic_0079614930_p58001382"></a><a name="en-us_topic_0079614930_p58001382"></a><a href="#en-us_topic_0079614930_ref458876000">glusterfs</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p4423307"><a name="en-us_topic_0079614930_p4423307"></a><a name="en-us_topic_0079614930_p4423307"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row39809767"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p3365696"><a name="en-us_topic_0079614930_p3365696"></a><a name="en-us_topic_0079614930_p3365696"></a>persistentVolumeClaim</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p4185994"><a name="en-us_topic_0079614930_p4185994"></a><a name="en-us_topic_0079614930_p4185994"></a><a href="#en-us_topic_0079614930_ref458876006">persistentVolumeClaim</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p31691351"><a name="en-us_topic_0079614930_p31691351"></a><a name="en-us_topic_0079614930_p31691351"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row16786704"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p17545755"><a name="en-us_topic_0079614930_p17545755"></a><a name="en-us_topic_0079614930_p17545755"></a>rbd</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p11920055"><a name="en-us_topic_0079614930_p11920055"></a><a name="en-us_topic_0079614930_p11920055"></a><a href="#en-us_topic_0079614930_ref458876012">rbd</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p32676970"><a name="en-us_topic_0079614930_p32676970"></a><a name="en-us_topic_0079614930_p32676970"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row25657280"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p64973822"><a name="en-us_topic_0079614930_p64973822"></a><a name="en-us_topic_0079614930_p64973822"></a>cinder</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p28388204"><a name="en-us_topic_0079614930_p28388204"></a><a name="en-us_topic_0079614930_p28388204"></a><a href="#en-us_topic_0079614930_ref458876023">cinder</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p25470662"><a name="en-us_topic_0079614930_p25470662"></a><a name="en-us_topic_0079614930_p25470662"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row27909369"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p46066408"><a name="en-us_topic_0079614930_p46066408"></a><a name="en-us_topic_0079614930_p46066408"></a>cephfs</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p40391592"><a name="en-us_topic_0079614930_p40391592"></a><a name="en-us_topic_0079614930_p40391592"></a><a href="#en-us_topic_0079614930_ref458876031">cephfs</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p51788650"><a name="en-us_topic_0079614930_p51788650"></a><a name="en-us_topic_0079614930_p51788650"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row63444666"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p38744283"><a name="en-us_topic_0079614930_p38744283"></a><a name="en-us_topic_0079614930_p38744283"></a>flocker</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p51279213"><a name="en-us_topic_0079614930_p51279213"></a><a name="en-us_topic_0079614930_p51279213"></a><a href="#en-us_topic_0079614930_ref458876036">flocker</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p2909269"><a name="en-us_topic_0079614930_p2909269"></a><a name="en-us_topic_0079614930_p2909269"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row26183426"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p40482774"><a name="en-us_topic_0079614930_p40482774"></a><a name="en-us_topic_0079614930_p40482774"></a>downwardAPI</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p57879225"><a name="en-us_topic_0079614930_p57879225"></a><a name="en-us_topic_0079614930_p57879225"></a><a href="#en-us_topic_0079614930_ref458876042">downwardAPI</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p49589129"><a name="en-us_topic_0079614930_p49589129"></a><a name="en-us_topic_0079614930_p49589129"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row43648979"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p45906392"><a name="en-us_topic_0079614930_p45906392"></a><a name="en-us_topic_0079614930_p45906392"></a>fc</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p27430286"><a name="en-us_topic_0079614930_p27430286"></a><a name="en-us_topic_0079614930_p27430286"></a><a href="#en-us_topic_0079614930_table52859449">fc</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p65346308"><a name="en-us_topic_0079614930_p65346308"></a><a name="en-us_topic_0079614930_p65346308"></a>-</p>
</td>
</tr>
<tr id="rcdc2238bd4d6408b80dcf2ece4ccae16"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="a7d4aa9a9869142898cbf03193822f2bf"><a name="a7d4aa9a9869142898cbf03193822f2bf"></a><a name="a7d4aa9a9869142898cbf03193822f2bf"></a>vsphereVolume</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="aa4121f4490534d5ab579729acb3360e6"><a name="aa4121f4490534d5ab579729acb3360e6"></a><a name="aa4121f4490534d5ab579729acb3360e6"></a><a href="#t330ab365df1742b78ea0ac6a440a6ee0">vsphereVolume</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="a756f6d368e224e669a54dd7fd4ad21b6"><a name="a756f6d368e224e669a54dd7fd4ad21b6"></a><a name="a756f6d368e224e669a54dd7fd4ad21b6"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  30**  Data structure of the containers field

<a name="en-us_topic_0079614930_table21660524"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row36090219"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p37626636"><a name="en-us_topic_0079614930_p37626636"></a><a name="en-us_topic_0079614930_p37626636"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.330000000000002%" id="mcps1.2.4.1.2"><p id="p13750161618599"><a name="p13750161618599"></a><a name="p13750161618599"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.61%" id="mcps1.2.4.1.3"><p id="p57509168598"><a name="p57509168598"></a><a name="p57509168598"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row43349186"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p21623157"><a name="en-us_topic_0079614930_p21623157"></a><a name="en-us_topic_0079614930_p21623157"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p6645264"><a name="en-us_topic_0079614930_p6645264"></a><a name="en-us_topic_0079614930_p6645264"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p1395516"><a name="en-us_topic_0079614930_p1395516"></a><a name="en-us_topic_0079614930_p1395516"></a>Name of the container specified as a DNS_LABEL. Each container in a pod must have a unique name (DNS_LABEL). Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row12559648"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p10698535"><a name="en-us_topic_0079614930_p10698535"></a><a name="en-us_topic_0079614930_p10698535"></a>image</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p61275027"><a name="en-us_topic_0079614930_p61275027"></a><a name="en-us_topic_0079614930_p61275027"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p64330188"><a name="en-us_topic_0079614930_p64330188"></a><a name="en-us_topic_0079614930_p64330188"></a>Docker image name.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row42100785"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p54720391"><a name="en-us_topic_0079614930_p54720391"></a><a name="en-us_topic_0079614930_p54720391"></a>command</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p3166686"><a name="en-us_topic_0079614930_p3166686"></a><a name="en-us_topic_0079614930_p3166686"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p55175005"><a name="en-us_topic_0079614930_p55175005"></a><a name="en-us_topic_0079614930_p55175005"></a>Entrypoint array. Not executed within a shell. The docker image's entrypoint is used if this is not provided. Variable references $(VAR_NAME) are expanded using the container's environment. If a variable cannot be resolved, the reference in the input string will be unchanged. The $(VAR_NAME) syntax can be escaped with a double $$, for example, $$(VAR_NAME). Escaped references will never be expanded, regardless of whether the variable exists or not. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row26813004"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24369691"><a name="en-us_topic_0079614930_p24369691"></a><a name="en-us_topic_0079614930_p24369691"></a>args</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p27787943"><a name="en-us_topic_0079614930_p27787943"></a><a name="en-us_topic_0079614930_p27787943"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p36230871"><a name="en-us_topic_0079614930_p36230871"></a><a name="en-us_topic_0079614930_p36230871"></a>Arguments to the entrypoint. The docker image's cmd is used if this is not provided. Variable references $(VAR_NAME) are expanded using the container's environment. If a variable cannot be resolved, the reference in the input string will be unchanged. The $(VAR_NAME) syntax can be escaped with a double $$, for example, $$(VAR_NAME). Escaped references will never be expanded, regardless of whether the variable exists or not. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row57642384"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p38521522"><a name="en-us_topic_0079614930_p38521522"></a><a name="en-us_topic_0079614930_p38521522"></a>workingDir</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p33235564"><a name="en-us_topic_0079614930_p33235564"></a><a name="en-us_topic_0079614930_p33235564"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p7726183"><a name="en-us_topic_0079614930_p7726183"></a><a name="en-us_topic_0079614930_p7726183"></a>Container's working directory. Defaults to Docker's default. Defaults to image's default. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row2426788"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p62352163"><a name="en-us_topic_0079614930_p62352163"></a><a name="en-us_topic_0079614930_p62352163"></a>ports</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p17360438"><a name="en-us_topic_0079614930_p17360438"></a><a name="en-us_topic_0079614930_p17360438"></a><a href="#en-us_topic_0079614930_table5972994">ports</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p39293304"><a name="en-us_topic_0079614930_p39293304"></a><a name="en-us_topic_0079614930_p39293304"></a>List of ports to expose from the container. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row18095418"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p56442747"><a name="en-us_topic_0079614930_p56442747"></a><a name="en-us_topic_0079614930_p56442747"></a>env</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p8459760"><a name="en-us_topic_0079614930_p8459760"></a><a name="en-us_topic_0079614930_p8459760"></a><a href="#en-us_topic_0079614930_table53756949">env</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p60258576"><a name="en-us_topic_0079614930_p60258576"></a><a name="en-us_topic_0079614930_p60258576"></a>List of environment variables to set in the container. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row5456280"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p39305498"><a name="en-us_topic_0079614930_p39305498"></a><a name="en-us_topic_0079614930_p39305498"></a>resources</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p29628785"><a name="en-us_topic_0079614930_p29628785"></a><a name="en-us_topic_0079614930_p29628785"></a><a href="#t5532c616d0de49d2aabe5e4cad89e370">resources</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p51121413"><a name="en-us_topic_0079614930_p51121413"></a><a name="en-us_topic_0079614930_p51121413"></a>Resources represents the minimum resources the volume should have.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row57439537"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p22090922"><a name="en-us_topic_0079614930_p22090922"></a><a name="en-us_topic_0079614930_p22090922"></a>volumeMounts</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p44534292"><a name="en-us_topic_0079614930_p44534292"></a><a name="en-us_topic_0079614930_p44534292"></a><a href="#en-us_topic_0079614930_table14050500">volumeMounts</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p51918161"><a name="en-us_topic_0079614930_p51918161"></a><a name="en-us_topic_0079614930_p51918161"></a>Pod volumes to mount into the container's file system. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row64610266"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p66049029"><a name="en-us_topic_0079614930_p66049029"></a><a name="en-us_topic_0079614930_p66049029"></a>livenessProbe</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p48371137"><a name="en-us_topic_0079614930_p48371137"></a><a name="en-us_topic_0079614930_p48371137"></a><a href="#en-us_topic_0079614930_table59345638">livenessProbe</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p30405604"><a name="en-us_topic_0079614930_p30405604"></a><a name="en-us_topic_0079614930_p30405604"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row5214986"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p19760744"><a name="en-us_topic_0079614930_p19760744"></a><a name="en-us_topic_0079614930_p19760744"></a>readinessProbe</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p57116406"><a name="en-us_topic_0079614930_p57116406"></a><a name="en-us_topic_0079614930_p57116406"></a><a href="#en-us_topic_0079614930_table59345638">readinessProbe</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p30364352"><a name="en-us_topic_0079614930_p30364352"></a><a name="en-us_topic_0079614930_p30364352"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row4843715"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p56796626"><a name="en-us_topic_0079614930_p56796626"></a><a name="en-us_topic_0079614930_p56796626"></a>lifecycle</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p37124018"><a name="en-us_topic_0079614930_p37124018"></a><a name="en-us_topic_0079614930_p37124018"></a><a href="#en-us_topic_0079614930_table64348702">lifecycle</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p18537444"><a name="en-us_topic_0079614930_p18537444"></a><a name="en-us_topic_0079614930_p18537444"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row32619268"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24915013"><a name="en-us_topic_0079614930_p24915013"></a><a name="en-us_topic_0079614930_p24915013"></a>terminationMessagePath</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p4850167"><a name="en-us_topic_0079614930_p4850167"></a><a name="en-us_topic_0079614930_p4850167"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p57319233"><a name="en-us_topic_0079614930_p57319233"></a><a name="en-us_topic_0079614930_p57319233"></a>Path at which the file to which the container's termination message will be written is mounted into the container's file system. Message written is intended to be brief final status, such as an assertion failure message. Defaults to /dev/termination-log. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row46111055"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p44007985"><a name="en-us_topic_0079614930_p44007985"></a><a name="en-us_topic_0079614930_p44007985"></a>imagePullPolicy</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p7877056"><a name="en-us_topic_0079614930_p7877056"></a><a name="en-us_topic_0079614930_p7877056"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p34061795"><a name="en-us_topic_0079614930_p34061795"></a><a name="en-us_topic_0079614930_p34061795"></a>Image pull policy. One of Always, Never, IfNotPresent. Defaults to Always if the latest tag is specified, or IfNotPresent otherwise. Cannot be updated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row38120704"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p769309"><a name="en-us_topic_0079614930_p769309"></a><a name="en-us_topic_0079614930_p769309"></a>securityContext</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p62314050"><a name="en-us_topic_0079614930_p62314050"></a><a name="en-us_topic_0079614930_p62314050"></a><a href="#en-us_topic_0079614930_table42267412">securityContext</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p14273304"><a name="en-us_topic_0079614930_p14273304"></a><a name="en-us_topic_0079614930_p14273304"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row61350877"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p3365118"><a name="en-us_topic_0079614930_p3365118"></a><a name="en-us_topic_0079614930_p3365118"></a>stdin</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p4139173"><a name="en-us_topic_0079614930_p4139173"></a><a name="en-us_topic_0079614930_p4139173"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p66837559"><a name="en-us_topic_0079614930_p66837559"></a><a name="en-us_topic_0079614930_p66837559"></a>Whether this container should allocate a buffer for stdin in the container runtime. If this is not set, reads from stdin in the container will always result in EOF. Default is false.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row64667125"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p3545749"><a name="en-us_topic_0079614930_p3545749"></a><a name="en-us_topic_0079614930_p3545749"></a>stdinOnce</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p18770262"><a name="en-us_topic_0079614930_p18770262"></a><a name="en-us_topic_0079614930_p18770262"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p43996255"><a name="en-us_topic_0079614930_p43996255"></a><a name="en-us_topic_0079614930_p43996255"></a>Whether the container runtime should close the stdin channel after it has been opened by a single attach. When stdin is true, the stdin stream will remain open across multiple attach sessions. If stdinOnce is set to true, stdin is opened on container start, is empty until the first client attaches to stdin, and then remains open and accepts data until the client disconnects, at which time stdin is closed and remains closed until the container is restarted. If this flag is false, a container process that reads from stdin will never receive an EOF. Default is false.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row60421983"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p62342440"><a name="en-us_topic_0079614930_p62342440"></a><a name="en-us_topic_0079614930_p62342440"></a>tty</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p16572878"><a name="en-us_topic_0079614930_p16572878"></a><a name="en-us_topic_0079614930_p16572878"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p225848"><a name="en-us_topic_0079614930_p225848"></a><a name="en-us_topic_0079614930_p225848"></a>Whether this container should allocate a TTY for itself, also requires 'stdin' to be true. Default is false.</p>
</td>
</tr>
</tbody>
</table>

**Table  31**  Data structure of the securityContext field

<a name="en-us_topic_0079614930_ref458875925"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row41062319"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p37713565"><a name="en-us_topic_0079614930_p37713565"></a><a name="en-us_topic_0079614930_p37713565"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1575514162591"><a name="p1575514162591"></a><a name="p1575514162591"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p17755191614592"><a name="p17755191614592"></a><a name="p17755191614592"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row2793896"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24979015"><a name="en-us_topic_0079614930_p24979015"></a><a name="en-us_topic_0079614930_p24979015"></a>seLinuxOptions</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p10034359"><a name="en-us_topic_0079614930_p10034359"></a><a name="en-us_topic_0079614930_p10034359"></a><a href="#en-us_topic_0079614930_table44862393">seLinuxOptions</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p7476768"><a name="en-us_topic_0079614930_p7476768"></a><a name="en-us_topic_0079614930_p7476768"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row182049"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p14745969"><a name="en-us_topic_0079614930_p14745969"></a><a name="en-us_topic_0079614930_p14745969"></a>runAsUser</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p53572813"><a name="en-us_topic_0079614930_p53572813"></a><a name="en-us_topic_0079614930_p53572813"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p44430622"><a name="en-us_topic_0079614930_p44430622"></a><a name="en-us_topic_0079614930_p44430622"></a>The UID to run the entrypoint of the container process. Defaults to user specified in image metadata if unspecified. May also be set in SecurityContext. If set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence for that container.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row64331286"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p43451697"><a name="en-us_topic_0079614930_p43451697"></a><a name="en-us_topic_0079614930_p43451697"></a>runAsNonRoot</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p29926581"><a name="en-us_topic_0079614930_p29926581"></a><a name="en-us_topic_0079614930_p29926581"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p8133960"><a name="en-us_topic_0079614930_p8133960"></a><a name="en-us_topic_0079614930_p8133960"></a>Indicates that the container must run as a non-root user. If true, the Kubelet will validate the image at runtime to ensure that it does not run as UID 0 (root) and fail to start the container if it does. If unset or false, no such validation will be performed. May also be set in SecurityContext. If set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row6096784"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24077504"><a name="en-us_topic_0079614930_p24077504"></a><a name="en-us_topic_0079614930_p24077504"></a>supplementalGroups</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p4120788"><a name="en-us_topic_0079614930_p4120788"></a><a name="en-us_topic_0079614930_p4120788"></a>Array of integers</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p65348405"><a name="en-us_topic_0079614930_p65348405"></a><a name="en-us_topic_0079614930_p65348405"></a>A list of groups applied to the first process run in each container, in addition to the container's primary GID. If unspecified, no groups will be added to any container.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row51264733"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p58802715"><a name="en-us_topic_0079614930_p58802715"></a><a name="en-us_topic_0079614930_p58802715"></a>fsGroup</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p65399514"><a name="en-us_topic_0079614930_p65399514"></a><a name="en-us_topic_0079614930_p65399514"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p62869314"><a name="en-us_topic_0079614930_p62869314"></a><a name="en-us_topic_0079614930_p62869314"></a>A special supplemental group that applies to all containers in a pod. Some volume types allow the Kubelet to change the ownership of that volume to be owned by the pod:</p>
<p id="en-us_topic_0079614930_p28952916"><a name="en-us_topic_0079614930_p28952916"></a><a name="en-us_topic_0079614930_p28952916"></a>The owning GID will be the FSGroup 2. The setgid bit is set (new files created in the volume will be owned by FSGroup) 3. The permission bits are OR'd with rw-rw.</p>
</td>
</tr>
</tbody>
</table>

**Table  32**  Data structure of the imagePullSecrets field

<a name="en-us_topic_0079614930_ref458875945"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row17290772"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p58375326"><a name="en-us_topic_0079614930_p58375326"></a><a name="en-us_topic_0079614930_p58375326"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1975791611590"><a name="p1975791611590"></a><a name="p1975791611590"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p19757121614599"><a name="p19757121614599"></a><a name="p19757121614599"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row23524847"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p26464459"><a name="en-us_topic_0079614930_p26464459"></a><a name="en-us_topic_0079614930_p26464459"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p63246431"><a name="en-us_topic_0079614930_p63246431"></a><a name="en-us_topic_0079614930_p63246431"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p22687316"><a name="en-us_topic_0079614930_p22687316"></a><a name="en-us_topic_0079614930_p22687316"></a>Name of the referent.</p>
</td>
</tr>
</tbody>
</table>

**Table  33**  Data structure of the hostPath field

<a name="en-us_topic_0079614930_ref458875954"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row48514746"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p37380344"><a name="en-us_topic_0079614930_p37380344"></a><a name="en-us_topic_0079614930_p37380344"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p975881618599"><a name="p975881618599"></a><a name="p975881618599"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p18758916115913"><a name="p18758916115913"></a><a name="p18758916115913"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row15975518"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p18948542"><a name="en-us_topic_0079614930_p18948542"></a><a name="en-us_topic_0079614930_p18948542"></a>path</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p58436906"><a name="en-us_topic_0079614930_p58436906"></a><a name="en-us_topic_0079614930_p58436906"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p35768971"><a name="en-us_topic_0079614930_p35768971"></a><a name="en-us_topic_0079614930_p35768971"></a>Path of the directory on the host.</p>
</td>
</tr>
</tbody>
</table>

**Table  34**  Data structure of the emptyDir field

<a name="en-us_topic_0079614930_ref458875962"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row49142989"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p21159210"><a name="en-us_topic_0079614930_p21159210"></a><a name="en-us_topic_0079614930_p21159210"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1875914162594"><a name="p1875914162594"></a><a name="p1875914162594"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1175917167592"><a name="p1175917167592"></a><a name="p1175917167592"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row43552930"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p38126448"><a name="en-us_topic_0079614930_p38126448"></a><a name="en-us_topic_0079614930_p38126448"></a>medium</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p1234623"><a name="en-us_topic_0079614930_p1234623"></a><a name="en-us_topic_0079614930_p1234623"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p32895671"><a name="en-us_topic_0079614930_p32895671"></a><a name="en-us_topic_0079614930_p32895671"></a>What type of storage medium should back this directory. The default is "" which means to use the node's default medium. Must be an empty string (default) or Memory.</p>
</td>
</tr>
</tbody>
</table>

**Table  35**  Data structure of the gitRepo field

<a name="en-us_topic_0079614930_ref458875979"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row6915674"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p23298740"><a name="en-us_topic_0079614930_p23298740"></a><a name="en-us_topic_0079614930_p23298740"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.330000000000002%" id="mcps1.2.4.1.2"><p id="p7763131617596"><a name="p7763131617596"></a><a name="p7763131617596"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.61%" id="mcps1.2.4.1.3"><p id="p376381655912"><a name="p376381655912"></a><a name="p376381655912"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row52041212"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p54588632"><a name="en-us_topic_0079614930_p54588632"></a><a name="en-us_topic_0079614930_p54588632"></a>repository</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p59603032"><a name="en-us_topic_0079614930_p59603032"></a><a name="en-us_topic_0079614930_p59603032"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p63116260"><a name="en-us_topic_0079614930_p63116260"></a><a name="en-us_topic_0079614930_p63116260"></a>Repository URL</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row31175435"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p42182293"><a name="en-us_topic_0079614930_p42182293"></a><a name="en-us_topic_0079614930_p42182293"></a>revision</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p61322592"><a name="en-us_topic_0079614930_p61322592"></a><a name="en-us_topic_0079614930_p61322592"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p1074068"><a name="en-us_topic_0079614930_p1074068"></a><a name="en-us_topic_0079614930_p1074068"></a>Commit hash for the specified revision.</p>
</td>
</tr>
</tbody>
</table>

**Table  36**  Data structure of the secret field

<a name="en-us_topic_0079614930_ref458875984"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row50642235"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p8380364"><a name="en-us_topic_0079614930_p8380364"></a><a name="en-us_topic_0079614930_p8380364"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p17764116185919"><a name="p17764116185919"></a><a name="p17764116185919"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p9764181612592"><a name="p9764181612592"></a><a name="p9764181612592"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row56408281"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p5668011"><a name="en-us_topic_0079614930_p5668011"></a><a name="en-us_topic_0079614930_p5668011"></a>secretName</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p56455762"><a name="en-us_topic_0079614930_p56455762"></a><a name="en-us_topic_0079614930_p56455762"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p9514038"><a name="en-us_topic_0079614930_p9514038"></a><a name="en-us_topic_0079614930_p9514038"></a>SecretName is the name of a secret in the pod's namespace.</p>
</td>
</tr>
</tbody>
</table>

**Table  37**  Data structure of the nfs field

<a name="en-us_topic_0079614930_ref458875989"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row38500800"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p31557075"><a name="en-us_topic_0079614930_p31557075"></a><a name="en-us_topic_0079614930_p31557075"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p17651716185915"><a name="p17651716185915"></a><a name="p17651716185915"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p676581645917"><a name="p676581645917"></a><a name="p676581645917"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row17130654"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p45405763"><a name="en-us_topic_0079614930_p45405763"></a><a name="en-us_topic_0079614930_p45405763"></a>server</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p53988209"><a name="en-us_topic_0079614930_p53988209"></a><a name="en-us_topic_0079614930_p53988209"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p10968783"><a name="en-us_topic_0079614930_p10968783"></a><a name="en-us_topic_0079614930_p10968783"></a>Server is the hostname or IP address of the NFS server.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row31610183"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p10288049"><a name="en-us_topic_0079614930_p10288049"></a><a name="en-us_topic_0079614930_p10288049"></a>path</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p28025631"><a name="en-us_topic_0079614930_p28025631"></a><a name="en-us_topic_0079614930_p28025631"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p55483642"><a name="en-us_topic_0079614930_p55483642"></a><a name="en-us_topic_0079614930_p55483642"></a>Path that is exported by the NFS server.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row29590731"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p48039028"><a name="en-us_topic_0079614930_p48039028"></a><a name="en-us_topic_0079614930_p48039028"></a>readOnly</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p65956029"><a name="en-us_topic_0079614930_p65956029"></a><a name="en-us_topic_0079614930_p65956029"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p40838094"><a name="en-us_topic_0079614930_p40838094"></a><a name="en-us_topic_0079614930_p40838094"></a>ReadOnly here will force the NFS export to be mounted with read-only permissions. Defaults to false.</p>
</td>
</tr>
</tbody>
</table>

**Table  38**  Data structure of the iscsi field

<a name="en-us_topic_0079614930_ref458875996"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row11654386"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p4481233"><a name="en-us_topic_0079614930_p4481233"></a><a name="en-us_topic_0079614930_p4481233"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p17661116165920"><a name="p17661116165920"></a><a name="p17661116165920"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p076621612591"><a name="p076621612591"></a><a name="p076621612591"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row18923528"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p56410793"><a name="en-us_topic_0079614930_p56410793"></a><a name="en-us_topic_0079614930_p56410793"></a>targetPortal</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p5871486"><a name="en-us_topic_0079614930_p5871486"></a><a name="en-us_topic_0079614930_p5871486"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p5828335"><a name="en-us_topic_0079614930_p5828335"></a><a name="en-us_topic_0079614930_p5828335"></a>iSCSI target portal. The portal is either an IP or ip_addr:port if the port is other than default (typically TCP ports 860 and 3260).</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row52455022"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p20998422"><a name="en-us_topic_0079614930_p20998422"></a><a name="en-us_topic_0079614930_p20998422"></a>iqn</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p23150606"><a name="en-us_topic_0079614930_p23150606"></a><a name="en-us_topic_0079614930_p23150606"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p63259774"><a name="en-us_topic_0079614930_p63259774"></a><a name="en-us_topic_0079614930_p63259774"></a>Target iSCSI Qualified Name.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row32467059"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p12586123"><a name="en-us_topic_0079614930_p12586123"></a><a name="en-us_topic_0079614930_p12586123"></a>lun</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p12843056"><a name="en-us_topic_0079614930_p12843056"></a><a name="en-us_topic_0079614930_p12843056"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p33654601"><a name="en-us_topic_0079614930_p33654601"></a><a name="en-us_topic_0079614930_p33654601"></a>iSCSI target lun number.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row34455957"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p39469112"><a name="en-us_topic_0079614930_p39469112"></a><a name="en-us_topic_0079614930_p39469112"></a>fsType</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p42881475"><a name="en-us_topic_0079614930_p42881475"></a><a name="en-us_topic_0079614930_p42881475"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p50847455"><a name="en-us_topic_0079614930_p50847455"></a><a name="en-us_topic_0079614930_p50847455"></a>Filesystem type of the volume that you want to mount. Tip: Ensure that the filesystem type is supported by the host operating system. Examples: "ext4", "xfs", "ntfs".</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row54973915"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p23702098"><a name="en-us_topic_0079614930_p23702098"></a><a name="en-us_topic_0079614930_p23702098"></a>readOnly</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p40821806"><a name="en-us_topic_0079614930_p40821806"></a><a name="en-us_topic_0079614930_p40821806"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p18232023"><a name="en-us_topic_0079614930_p18232023"></a><a name="en-us_topic_0079614930_p18232023"></a>ReadOnly here will force the ReadOnly setting in VolumeMounts. Defaults to false.</p>
</td>
</tr>
</tbody>
</table>

**Table  39**  Data structure of the glusterfs field

<a name="en-us_topic_0079614930_ref458876000"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row66586256"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p24777680"><a name="en-us_topic_0079614930_p24777680"></a><a name="en-us_topic_0079614930_p24777680"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p676811655912"><a name="p676811655912"></a><a name="p676811655912"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p176811618599"><a name="p176811618599"></a><a name="p176811618599"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row42552963"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24237973"><a name="en-us_topic_0079614930_p24237973"></a><a name="en-us_topic_0079614930_p24237973"></a>endpoints</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p17118783"><a name="en-us_topic_0079614930_p17118783"></a><a name="en-us_topic_0079614930_p17118783"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p44444202"><a name="en-us_topic_0079614930_p44444202"></a><a name="en-us_topic_0079614930_p44444202"></a>EndpointsName is the endpoint name that details Glusterfs topology.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row64453503"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p53351278"><a name="en-us_topic_0079614930_p53351278"></a><a name="en-us_topic_0079614930_p53351278"></a>path</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p26486257"><a name="en-us_topic_0079614930_p26486257"></a><a name="en-us_topic_0079614930_p26486257"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p65012081"><a name="en-us_topic_0079614930_p65012081"></a><a name="en-us_topic_0079614930_p65012081"></a>Path is the Glusterfs volume path.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row48237819"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p14949248"><a name="en-us_topic_0079614930_p14949248"></a><a name="en-us_topic_0079614930_p14949248"></a>readOnly</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p2929590"><a name="en-us_topic_0079614930_p2929590"></a><a name="en-us_topic_0079614930_p2929590"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p35970244"><a name="en-us_topic_0079614930_p35970244"></a><a name="en-us_topic_0079614930_p35970244"></a>ReadOnly here will force the Glusterfs volume to be mounted with read-only permissions. Defaults to false.</p>
</td>
</tr>
</tbody>
</table>

**Table  40**  Data structure of the persistentVolumeClaim field

<a name="en-us_topic_0079614930_ref458876006"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row55083180"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p32552624"><a name="en-us_topic_0079614930_p32552624"></a><a name="en-us_topic_0079614930_p32552624"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1376916169595"><a name="p1376916169595"></a><a name="p1376916169595"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p276911685914"><a name="p276911685914"></a><a name="p276911685914"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row6593974"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p64349884"><a name="en-us_topic_0079614930_p64349884"></a><a name="en-us_topic_0079614930_p64349884"></a>claimName</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p44958086"><a name="en-us_topic_0079614930_p44958086"></a><a name="en-us_topic_0079614930_p44958086"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p17726332"><a name="en-us_topic_0079614930_p17726332"></a><a name="en-us_topic_0079614930_p17726332"></a>ClaimName is the name of a PersistentVolumeClaim in the same namespace as the pod using this volume.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row25319268"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p37594824"><a name="en-us_topic_0079614930_p37594824"></a><a name="en-us_topic_0079614930_p37594824"></a>readOnly</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p25281933"><a name="en-us_topic_0079614930_p25281933"></a><a name="en-us_topic_0079614930_p25281933"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p34570715"><a name="en-us_topic_0079614930_p34570715"></a><a name="en-us_topic_0079614930_p34570715"></a>Will force the ReadOnly setting in VolumeMounts. Default false.</p>
</td>
</tr>
</tbody>
</table>

**Table  41**  Data structure of the rbd field

<a name="en-us_topic_0079614930_ref458876012"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row55232825"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p44673844"><a name="en-us_topic_0079614930_p44673844"></a><a name="en-us_topic_0079614930_p44673844"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p87701016115915"><a name="p87701016115915"></a><a name="p87701016115915"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1770416165915"><a name="p1770416165915"></a><a name="p1770416165915"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row6959423"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p26842363"><a name="en-us_topic_0079614930_p26842363"></a><a name="en-us_topic_0079614930_p26842363"></a>monitors</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p26747820"><a name="en-us_topic_0079614930_p26747820"></a><a name="en-us_topic_0079614930_p26747820"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p19089850"><a name="en-us_topic_0079614930_p19089850"></a><a name="en-us_topic_0079614930_p19089850"></a>A collection of Ceph monitors.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row37590927"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24966259"><a name="en-us_topic_0079614930_p24966259"></a><a name="en-us_topic_0079614930_p24966259"></a>image</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p9001062"><a name="en-us_topic_0079614930_p9001062"></a><a name="en-us_topic_0079614930_p9001062"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p57997459"><a name="en-us_topic_0079614930_p57997459"></a><a name="en-us_topic_0079614930_p57997459"></a>The rados image name.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row52215086"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p1563554"><a name="en-us_topic_0079614930_p1563554"></a><a name="en-us_topic_0079614930_p1563554"></a>fsType</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p59539043"><a name="en-us_topic_0079614930_p59539043"></a><a name="en-us_topic_0079614930_p59539043"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p57933144"><a name="en-us_topic_0079614930_p57933144"></a><a name="en-us_topic_0079614930_p57933144"></a>Filesystem type of the volume that you want to mount. Tip: Ensure that the filesystem type is supported by the host operating system. Examples: "ext4", "xfs", "ntfs".</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row51636249"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p21786680"><a name="en-us_topic_0079614930_p21786680"></a><a name="en-us_topic_0079614930_p21786680"></a>pool</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p19890688"><a name="en-us_topic_0079614930_p19890688"></a><a name="en-us_topic_0079614930_p19890688"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p533016"><a name="en-us_topic_0079614930_p533016"></a><a name="en-us_topic_0079614930_p533016"></a>The rados pool name. Default is rbd.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row4797145"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p53024493"><a name="en-us_topic_0079614930_p53024493"></a><a name="en-us_topic_0079614930_p53024493"></a>user</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p16677"><a name="en-us_topic_0079614930_p16677"></a><a name="en-us_topic_0079614930_p16677"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p1350890"><a name="en-us_topic_0079614930_p1350890"></a><a name="en-us_topic_0079614930_p1350890"></a>The rados user name. Default is admin.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row12158012"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p45274943"><a name="en-us_topic_0079614930_p45274943"></a><a name="en-us_topic_0079614930_p45274943"></a>keyring</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p43391746"><a name="en-us_topic_0079614930_p43391746"></a><a name="en-us_topic_0079614930_p43391746"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p25070509"><a name="en-us_topic_0079614930_p25070509"></a><a name="en-us_topic_0079614930_p25070509"></a>Keyring is the path to key ring for RBDUser. Default is /etc/ceph/keyring.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row24307993"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p22790453"><a name="en-us_topic_0079614930_p22790453"></a><a name="en-us_topic_0079614930_p22790453"></a>secretRef</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p34087372"><a name="en-us_topic_0079614930_p34087372"></a><a name="en-us_topic_0079614930_p34087372"></a><a href="#en-us_topic_0079614930_ref458875945">imagePullSecrets</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p9613768"><a name="en-us_topic_0079614930_p9613768"></a><a name="en-us_topic_0079614930_p9613768"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row19415056"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p29115678"><a name="en-us_topic_0079614930_p29115678"></a><a name="en-us_topic_0079614930_p29115678"></a>readOnly</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p9559684"><a name="en-us_topic_0079614930_p9559684"></a><a name="en-us_topic_0079614930_p9559684"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p36136939"><a name="en-us_topic_0079614930_p36136939"></a><a name="en-us_topic_0079614930_p36136939"></a>ReadOnly here will force the ReadOnly setting in VolumeMounts. Defaults to false.</p>
</td>
</tr>
</tbody>
</table>

**Table  42**  Data structure of the cinder field

<a name="en-us_topic_0079614930_ref458876023"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row28847564"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p54951308"><a name="en-us_topic_0079614930_p54951308"></a><a name="en-us_topic_0079614930_p54951308"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p107733164599"><a name="p107733164599"></a><a name="p107733164599"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p19773151615910"><a name="p19773151615910"></a><a name="p19773151615910"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row16465207"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p58613401"><a name="en-us_topic_0079614930_p58613401"></a><a name="en-us_topic_0079614930_p58613401"></a>volumeID</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p50065064"><a name="en-us_topic_0079614930_p50065064"></a><a name="en-us_topic_0079614930_p50065064"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p28738379"><a name="en-us_topic_0079614930_p28738379"></a><a name="en-us_topic_0079614930_p28738379"></a>volume id used to identify the volume in cinder</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row57318824"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p12313157"><a name="en-us_topic_0079614930_p12313157"></a><a name="en-us_topic_0079614930_p12313157"></a>fsType</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p57841642"><a name="en-us_topic_0079614930_p57841642"></a><a name="en-us_topic_0079614930_p57841642"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p54661440"><a name="en-us_topic_0079614930_p54661440"></a><a name="en-us_topic_0079614930_p54661440"></a>Required: Filesystem type to mount. Must be a filesystem type supported by the host operating system. Only ext3 and ext4 are allowed.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row22190917"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p52633830"><a name="en-us_topic_0079614930_p52633830"></a><a name="en-us_topic_0079614930_p52633830"></a>readOnly</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p35481869"><a name="en-us_topic_0079614930_p35481869"></a><a name="en-us_topic_0079614930_p35481869"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p55459103"><a name="en-us_topic_0079614930_p55459103"></a><a name="en-us_topic_0079614930_p55459103"></a>Optional: Defaults to false (read/write). ReadOnly here will force the ReadOnly setting in VolumeMounts.</p>
</td>
</tr>
</tbody>
</table>

**Table  43**  Data structure of the cephfs field

<a name="en-us_topic_0079614930_ref458876031"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row47356423"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p10665089"><a name="en-us_topic_0079614930_p10665089"></a><a name="en-us_topic_0079614930_p10665089"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p077411167599"><a name="p077411167599"></a><a name="p077411167599"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p13775141613590"><a name="p13775141613590"></a><a name="p13775141613590"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row52677538"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p39022190"><a name="en-us_topic_0079614930_p39022190"></a><a name="en-us_topic_0079614930_p39022190"></a>monitors</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p6680818"><a name="en-us_topic_0079614930_p6680818"></a><a name="en-us_topic_0079614930_p6680818"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p4275415"><a name="en-us_topic_0079614930_p4275415"></a><a name="en-us_topic_0079614930_p4275415"></a>Required: Monitors is a collection of Ceph monitors</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row38478741"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p29770350"><a name="en-us_topic_0079614930_p29770350"></a><a name="en-us_topic_0079614930_p29770350"></a>user</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p62588155"><a name="en-us_topic_0079614930_p62588155"></a><a name="en-us_topic_0079614930_p62588155"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p36475813"><a name="en-us_topic_0079614930_p36475813"></a><a name="en-us_topic_0079614930_p36475813"></a>Optional: User is the rados user name, default is admin</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row59846864"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p15757807"><a name="en-us_topic_0079614930_p15757807"></a><a name="en-us_topic_0079614930_p15757807"></a>secretFile</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p1314015"><a name="en-us_topic_0079614930_p1314015"></a><a name="en-us_topic_0079614930_p1314015"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p39326408"><a name="en-us_topic_0079614930_p39326408"></a><a name="en-us_topic_0079614930_p39326408"></a>SecretFile is the path to key ring for User, default is /etc/ceph/user.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row18393353"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p13466585"><a name="en-us_topic_0079614930_p13466585"></a><a name="en-us_topic_0079614930_p13466585"></a>secretRef</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p17051573"><a name="en-us_topic_0079614930_p17051573"></a><a name="en-us_topic_0079614930_p17051573"></a><a href="#en-us_topic_0079614930_ref458875945">imagePullSecrets</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p39000198"><a name="en-us_topic_0079614930_p39000198"></a><a name="en-us_topic_0079614930_p39000198"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row15457470"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p44095577"><a name="en-us_topic_0079614930_p44095577"></a><a name="en-us_topic_0079614930_p44095577"></a>readOnly</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p14971997"><a name="en-us_topic_0079614930_p14971997"></a><a name="en-us_topic_0079614930_p14971997"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p4772208"><a name="en-us_topic_0079614930_p4772208"></a><a name="en-us_topic_0079614930_p4772208"></a>Optional: Defaults to false (read/write). ReadOnly here will force the ReadOnly setting in VolumeMounts.</p>
</td>
</tr>
</tbody>
</table>

**Table  44**  Data structure of the flocker field

<a name="en-us_topic_0079614930_ref458876036"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row59343389"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p42085170"><a name="en-us_topic_0079614930_p42085170"></a><a name="en-us_topic_0079614930_p42085170"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1577712166598"><a name="p1577712166598"></a><a name="p1577712166598"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p2777201611597"><a name="p2777201611597"></a><a name="p2777201611597"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row11188796"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p33877299"><a name="en-us_topic_0079614930_p33877299"></a><a name="en-us_topic_0079614930_p33877299"></a>datasetName</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p59706727"><a name="en-us_topic_0079614930_p59706727"></a><a name="en-us_topic_0079614930_p59706727"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p4406719"><a name="en-us_topic_0079614930_p4406719"></a><a name="en-us_topic_0079614930_p4406719"></a>Required: the volume name. This is going to be store on metadata -&gt; name on the payload for Flocker.</p>
</td>
</tr>
</tbody>
</table>

**Table  45**  Data structure of the downwardAPI field

<a name="en-us_topic_0079614930_ref458876042"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row54164940"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p25283991"><a name="en-us_topic_0079614930_p25283991"></a><a name="en-us_topic_0079614930_p25283991"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p6778191615590"><a name="p6778191615590"></a><a name="p6778191615590"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p5778131610593"><a name="p5778131610593"></a><a name="p5778131610593"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row10349436"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p32998010"><a name="en-us_topic_0079614930_p32998010"></a><a name="en-us_topic_0079614930_p32998010"></a>items</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p55593128"><a name="en-us_topic_0079614930_p55593128"></a><a name="en-us_topic_0079614930_p55593128"></a><a href="#en-us_topic_0079614930_table1108358">items</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p6749486"><a name="en-us_topic_0079614930_p6749486"></a><a name="en-us_topic_0079614930_p6749486"></a>Items is a list of downward API volume file.</p>
</td>
</tr>
</tbody>
</table>

**Table  46**  Data structure of the fc field

<a name="en-us_topic_0079614930_table52859449"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row66929418"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p52573766"><a name="en-us_topic_0079614930_p52573766"></a><a name="en-us_topic_0079614930_p52573766"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1779191615914"><a name="p1779191615914"></a><a name="p1779191615914"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p12779121615912"><a name="p12779121615912"></a><a name="p12779121615912"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row18775539"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p44423729"><a name="en-us_topic_0079614930_p44423729"></a><a name="en-us_topic_0079614930_p44423729"></a>targetWWNs</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p41552307"><a name="en-us_topic_0079614930_p41552307"></a><a name="en-us_topic_0079614930_p41552307"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p10293730"><a name="en-us_topic_0079614930_p10293730"></a><a name="en-us_topic_0079614930_p10293730"></a>Required: FC target world wide names (WWNs)</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row25534709"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p55045586"><a name="en-us_topic_0079614930_p55045586"></a><a name="en-us_topic_0079614930_p55045586"></a>lun</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p29507471"><a name="en-us_topic_0079614930_p29507471"></a><a name="en-us_topic_0079614930_p29507471"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p41294932"><a name="en-us_topic_0079614930_p41294932"></a><a name="en-us_topic_0079614930_p41294932"></a>Required: FC target lun number</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row36110074"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p39234847"><a name="en-us_topic_0079614930_p39234847"></a><a name="en-us_topic_0079614930_p39234847"></a>fsType</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p23906016"><a name="en-us_topic_0079614930_p23906016"></a><a name="en-us_topic_0079614930_p23906016"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p57339175"><a name="en-us_topic_0079614930_p57339175"></a><a name="en-us_topic_0079614930_p57339175"></a>Required: Filesystem type to mount. Must be a filesystem type supported by the host operating system. Ex. "ext4", "xfs", "ntfs"</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row46290527"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p58545191"><a name="en-us_topic_0079614930_p58545191"></a><a name="en-us_topic_0079614930_p58545191"></a>readOnly</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p44540007"><a name="en-us_topic_0079614930_p44540007"></a><a name="en-us_topic_0079614930_p44540007"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p50970824"><a name="en-us_topic_0079614930_p50970824"></a><a name="en-us_topic_0079614930_p50970824"></a>Optional: Defaults to false (read/write). ReadOnly here will force the ReadOnly setting in VolumeMounts.</p>
</td>
</tr>
</tbody>
</table>

**Table  47**  Data structure of the vsphereVolume field

<a name="t330ab365df1742b78ea0ac6a440a6ee0"></a>
<table><thead align="left"><tr id="r97bab52536bb4b5a899ed56cbeaa9400"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.4.1.1"><p id="ab8ecb8993cfc4dd7a4f8642d98e352f3"><a name="ab8ecb8993cfc4dd7a4f8642d98e352f3"></a><a name="ab8ecb8993cfc4dd7a4f8642d98e352f3"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.2.4.1.2"><p id="p27801516115918"><a name="p27801516115918"></a><a name="p27801516115918"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="p37811616125911"><a name="p37811616125911"></a><a name="p37811616125911"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r771452d75e6345709ee15c8004730125"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="adc236b2019f648e5b7b676f467aea8a7"><a name="adc236b2019f648e5b7b676f467aea8a7"></a><a name="adc236b2019f648e5b7b676f467aea8a7"></a>volumePath</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p184647203226"><a name="en-us_topic_0079614930_p184647203226"></a><a name="en-us_topic_0079614930_p184647203226"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p54646204220"><a name="en-us_topic_0079614930_p54646204220"></a><a name="en-us_topic_0079614930_p54646204220"></a>Path that identifies vSphere volume vmdk.</p>
</td>
</tr>
<tr id="r1b7a9170060646cf92c9841cd0a6baba"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="a159be5c095994b4497afd72267d987a8"><a name="a159be5c095994b4497afd72267d987a8"></a><a name="a159be5c095994b4497afd72267d987a8"></a>fsType</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="ae7c6868abac84a85853a4e7ebcca400e"><a name="ae7c6868abac84a85853a4e7ebcca400e"></a><a name="ae7c6868abac84a85853a4e7ebcca400e"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a94c04c32c3ea4d5ab4b49c8950d34e58"><a name="a94c04c32c3ea4d5ab4b49c8950d34e58"></a><a name="a94c04c32c3ea4d5ab4b49c8950d34e58"></a>Filesystem type to mount.</p>
<p id="afa94635d41724d9cb775f5f114f0cef8"><a name="afa94635d41724d9cb775f5f114f0cef8"></a><a name="afa94635d41724d9cb775f5f114f0cef8"></a>Must be a filesystem type supported by the host operating system. Ex. "ext4", "xfs", "ntfs". Implicitly inferred to be "ext4" if unspecified.</p>
</td>
</tr>
</tbody>
</table>

**Table  48**  Data structure of the ports field

<a name="en-us_topic_0079614930_table5972994"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row392368"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p31781818"><a name="en-us_topic_0079614930_p31781818"></a><a name="en-us_topic_0079614930_p31781818"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p57836167596"><a name="p57836167596"></a><a name="p57836167596"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1778351675919"><a name="p1778351675919"></a><a name="p1778351675919"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row1072131"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p19733807"><a name="en-us_topic_0079614930_p19733807"></a><a name="en-us_topic_0079614930_p19733807"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p54934568"><a name="en-us_topic_0079614930_p54934568"></a><a name="en-us_topic_0079614930_p54934568"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p20515029"><a name="en-us_topic_0079614930_p20515029"></a><a name="en-us_topic_0079614930_p20515029"></a>If specified, this must be an IANA_SVC_NAME and unique within the pod. Each named port in a pod must have a unique name. Name for the port that can be referred to by services.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row50417539"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p57288858"><a name="en-us_topic_0079614930_p57288858"></a><a name="en-us_topic_0079614930_p57288858"></a>hostPort</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p9885913"><a name="en-us_topic_0079614930_p9885913"></a><a name="en-us_topic_0079614930_p9885913"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p62561513"><a name="en-us_topic_0079614930_p62561513"></a><a name="en-us_topic_0079614930_p62561513"></a>Number of port to expose on the host. If specified, this must be a valid port number, 0 &lt; x &lt; 65536. If HostNetwork is specified, this must match ContainerPort. Most containers do not need this.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row26182711"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p40424835"><a name="en-us_topic_0079614930_p40424835"></a><a name="en-us_topic_0079614930_p40424835"></a>containerPort</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p53186163"><a name="en-us_topic_0079614930_p53186163"></a><a name="en-us_topic_0079614930_p53186163"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p13111919"><a name="en-us_topic_0079614930_p13111919"></a><a name="en-us_topic_0079614930_p13111919"></a>Number of port to expose on the pod's IP address. This must be a valid port number, 0 &lt; x &lt; 65536.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row50898414"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p29130856"><a name="en-us_topic_0079614930_p29130856"></a><a name="en-us_topic_0079614930_p29130856"></a>protocol</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p10789155"><a name="en-us_topic_0079614930_p10789155"></a><a name="en-us_topic_0079614930_p10789155"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p1506375"><a name="en-us_topic_0079614930_p1506375"></a><a name="en-us_topic_0079614930_p1506375"></a>Protocol for port. Must be UDP or TCP. Defaults to "TCP".</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row13557375"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24405586"><a name="en-us_topic_0079614930_p24405586"></a><a name="en-us_topic_0079614930_p24405586"></a>hostIP</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p30695458"><a name="en-us_topic_0079614930_p30695458"></a><a name="en-us_topic_0079614930_p30695458"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p3304150"><a name="en-us_topic_0079614930_p3304150"></a><a name="en-us_topic_0079614930_p3304150"></a>What host IP to bind the external port to.</p>
</td>
</tr>
</tbody>
</table>

**Table  49**  Data structure of the env field

<a name="en-us_topic_0079614930_table53756949"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row48372684"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p25873364"><a name="en-us_topic_0079614930_p25873364"></a><a name="en-us_topic_0079614930_p25873364"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p47851716175916"><a name="p47851716175916"></a><a name="p47851716175916"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1378541619599"><a name="p1378541619599"></a><a name="p1378541619599"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row30124781"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p24188198"><a name="en-us_topic_0079614930_p24188198"></a><a name="en-us_topic_0079614930_p24188198"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p13087056"><a name="en-us_topic_0079614930_p13087056"></a><a name="en-us_topic_0079614930_p13087056"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p53418643"><a name="en-us_topic_0079614930_p53418643"></a><a name="en-us_topic_0079614930_p53418643"></a>Name of the environment variable. Must be a C_IDENTIFIER.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row11005741"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p19049799"><a name="en-us_topic_0079614930_p19049799"></a><a name="en-us_topic_0079614930_p19049799"></a>value</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p66638733"><a name="en-us_topic_0079614930_p66638733"></a><a name="en-us_topic_0079614930_p66638733"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p29028329"><a name="en-us_topic_0079614930_p29028329"></a><a name="en-us_topic_0079614930_p29028329"></a>Variable references $(VAR_NAME) are expanded using the previous defined environment variables in the container and any service environment variables. If a variable cannot be resolved, the reference in the input string will be unchanged. The $(VAR_NAME) syntax can be escaped with a double $$, for example, $$(VAR_NAME). Escaped references will never be expanded, regardless of whether the variable exists or not. Defaults to "".</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row59928369"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p22359750"><a name="en-us_topic_0079614930_p22359750"></a><a name="en-us_topic_0079614930_p22359750"></a>valueFrom</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p66309348"><a name="en-us_topic_0079614930_p66309348"></a><a name="en-us_topic_0079614930_p66309348"></a><a href="#en-us_topic_0079614930_table9975229">valueFrom</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p2348082"><a name="en-us_topic_0079614930_p2348082"></a><a name="en-us_topic_0079614930_p2348082"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  50**  Data structure of the resources field

<a name="t5532c616d0de49d2aabe5e4cad89e370"></a>
<table><thead align="left"><tr id="r5c106f8c400e4799b618758f6faa4156"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="ad6d59c06de8c431798339fd238aa9f60"><a name="ad6d59c06de8c431798339fd238aa9f60"></a><a name="ad6d59c06de8c431798339fd238aa9f60"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p178620165598"><a name="p178620165598"></a><a name="p178620165598"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1378681616593"><a name="p1378681616593"></a><a name="p1378681616593"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="rd3f86ba2d74c4537ba67ae670c124525"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="a8b8216428b514d7290a8e07307fbad9b"><a name="a8b8216428b514d7290a8e07307fbad9b"></a><a name="a8b8216428b514d7290a8e07307fbad9b"></a>limits</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a7b6ea12dc6b54160babf63e5ca79d6dc"><a name="a7b6ea12dc6b54160babf63e5ca79d6dc"></a><a name="a7b6ea12dc6b54160babf63e5ca79d6dc"></a>object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="a1ff084a3efbc448e89f15738eda41145"><a name="a1ff084a3efbc448e89f15738eda41145"></a><a name="a1ff084a3efbc448e89f15738eda41145"></a>Limits describes the maximum amount of compute resources allowed.</p>
</td>
</tr>
<tr id="r160489b9c18f4850a2077093db598127"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="aadab18dcbee9464eb6e4bde71ee81a45"><a name="aadab18dcbee9464eb6e4bde71ee81a45"></a><a name="aadab18dcbee9464eb6e4bde71ee81a45"></a>requests</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a484d187d508942c29c321af45f97e29c"><a name="a484d187d508942c29c321af45f97e29c"></a><a name="a484d187d508942c29c321af45f97e29c"></a>object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="afe2b3ea807264a7c8c24320583b3fe92"><a name="afe2b3ea807264a7c8c24320583b3fe92"></a><a name="afe2b3ea807264a7c8c24320583b3fe92"></a>Requests describes the minimum amount of compute resources required. If Requests is omitted for a container, it defaults to Limits if that is explicitly specified, otherwise to an implementation-defined value.</p>
</td>
</tr>
</tbody>
</table>

**Table  51**  Data structure of the volumeMounts field

<a name="en-us_topic_0079614930_table14050500"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row1190341"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p29308772"><a name="en-us_topic_0079614930_p29308772"></a><a name="en-us_topic_0079614930_p29308772"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1678716161598"><a name="p1678716161598"></a><a name="p1678716161598"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p978791645915"><a name="p978791645915"></a><a name="p978791645915"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row50167500"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p37035725"><a name="en-us_topic_0079614930_p37035725"></a><a name="en-us_topic_0079614930_p37035725"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p47103787"><a name="en-us_topic_0079614930_p47103787"></a><a name="en-us_topic_0079614930_p47103787"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p57310413"><a name="en-us_topic_0079614930_p57310413"></a><a name="en-us_topic_0079614930_p57310413"></a>This must match the Name of a Volume.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row46031676"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p37578239"><a name="en-us_topic_0079614930_p37578239"></a><a name="en-us_topic_0079614930_p37578239"></a>readOnly</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p23938556"><a name="en-us_topic_0079614930_p23938556"></a><a name="en-us_topic_0079614930_p23938556"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p59974873"><a name="en-us_topic_0079614930_p59974873"></a><a name="en-us_topic_0079614930_p59974873"></a>Mounted read-only if true, read-write otherwise (false or unspecified). Defaults to false.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row2902947"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p33812148"><a name="en-us_topic_0079614930_p33812148"></a><a name="en-us_topic_0079614930_p33812148"></a>mountPath</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p54429433"><a name="en-us_topic_0079614930_p54429433"></a><a name="en-us_topic_0079614930_p54429433"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p46707930"><a name="en-us_topic_0079614930_p46707930"></a><a name="en-us_topic_0079614930_p46707930"></a>Path within the container at which the volume should be mounted.</p>
</td>
</tr>
<tr id="r2521cd19e7e840febafba65c82b757a9"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="a7fbdfafa12ee47c0a01e792c32e1bc48"><a name="a7fbdfafa12ee47c0a01e792c32e1bc48"></a><a name="a7fbdfafa12ee47c0a01e792c32e1bc48"></a>subPath</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a5064aea188af4256bd33ab5f55d23793"><a name="a5064aea188af4256bd33ab5f55d23793"></a><a name="a5064aea188af4256bd33ab5f55d23793"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="a7ebc39db02ca480c910f60bdd800086e"><a name="a7ebc39db02ca480c910f60bdd800086e"></a><a name="a7ebc39db02ca480c910f60bdd800086e"></a>Path within the volume from which the container's volume should be mounted.</p>
<p id="en-us_topic_0079614930_p032882882812"><a name="en-us_topic_0079614930_p032882882812"></a><a name="en-us_topic_0079614930_p032882882812"></a>Defaults to "" (volume's root).</p>
</td>
</tr>
</tbody>
</table>

**Table  52**  Data structure of the livenessProbe field

<a name="en-us_topic_0079614930_table59345638"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row62863761"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p58799890"><a name="en-us_topic_0079614930_p58799890"></a><a name="en-us_topic_0079614930_p58799890"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.330000000000002%" id="mcps1.2.4.1.2"><p id="p37901716115912"><a name="p37901716115912"></a><a name="p37901716115912"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.61%" id="mcps1.2.4.1.3"><p id="p279071635914"><a name="p279071635914"></a><a name="p279071635914"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row34074728"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p8589563"><a name="en-us_topic_0079614930_p8589563"></a><a name="en-us_topic_0079614930_p8589563"></a>exec</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="ad7f4b1bad97a4a289f56e6bb6cf75216"><a name="ad7f4b1bad97a4a289f56e6bb6cf75216"></a><a name="ad7f4b1bad97a4a289f56e6bb6cf75216"></a><a href="#en-us_topic_0079614930_table22668197">exec</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p51786882"><a name="en-us_topic_0079614930_p51786882"></a><a name="en-us_topic_0079614930_p51786882"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row63428758"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p37455741"><a name="en-us_topic_0079614930_p37455741"></a><a name="en-us_topic_0079614930_p37455741"></a>httpGet</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="ad8c45c2a529248198684b536898323ef"><a name="ad8c45c2a529248198684b536898323ef"></a><a name="ad8c45c2a529248198684b536898323ef"></a><a href="#en-us_topic_0079614930_table2687184">httpGet</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p61570530"><a name="en-us_topic_0079614930_p61570530"></a><a name="en-us_topic_0079614930_p61570530"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row17263863"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p56195629"><a name="en-us_topic_0079614930_p56195629"></a><a name="en-us_topic_0079614930_p56195629"></a>tcpSocket</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="a11876c77e8b24e53b20491cf62eaef22"><a name="a11876c77e8b24e53b20491cf62eaef22"></a><a name="a11876c77e8b24e53b20491cf62eaef22"></a><a href="#en-us_topic_0079614930_table24184664">tcpSocket</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p3426243"><a name="en-us_topic_0079614930_p3426243"></a><a name="en-us_topic_0079614930_p3426243"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row30836194"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p14703761"><a name="en-us_topic_0079614930_p14703761"></a><a name="en-us_topic_0079614930_p14703761"></a>initialDelaySeconds</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p50153981"><a name="en-us_topic_0079614930_p50153981"></a><a name="en-us_topic_0079614930_p50153981"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p35940621"><a name="en-us_topic_0079614930_p35940621"></a><a name="en-us_topic_0079614930_p35940621"></a>Number of seconds after the container has started before liveness probes are initiated.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row55030134"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p28255864"><a name="en-us_topic_0079614930_p28255864"></a><a name="en-us_topic_0079614930_p28255864"></a>timeoutSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p7023634"><a name="en-us_topic_0079614930_p7023634"></a><a name="en-us_topic_0079614930_p7023634"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p32043501"><a name="en-us_topic_0079614930_p32043501"></a><a name="en-us_topic_0079614930_p32043501"></a>Number of seconds after which the probe times out. Defaults to 1 second. Minimum value is 1.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row19956058"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p5828025"><a name="en-us_topic_0079614930_p5828025"></a><a name="en-us_topic_0079614930_p5828025"></a>periodSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p2308012"><a name="en-us_topic_0079614930_p2308012"></a><a name="en-us_topic_0079614930_p2308012"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p52731292"><a name="en-us_topic_0079614930_p52731292"></a><a name="en-us_topic_0079614930_p52731292"></a>How often (in seconds) to perform the probe. Default to 10 seconds. Minimum value is 1.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row43376240"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p23814545"><a name="en-us_topic_0079614930_p23814545"></a><a name="en-us_topic_0079614930_p23814545"></a>successThreshold</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p49929958"><a name="en-us_topic_0079614930_p49929958"></a><a name="en-us_topic_0079614930_p49929958"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p17794775"><a name="en-us_topic_0079614930_p17794775"></a><a name="en-us_topic_0079614930_p17794775"></a>Minimum consecutive successes for the probe to be considered successful after having failed. Defaults to 1. Must be 1 for liveness. Minimum value is 1.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row25935254"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p20380862"><a name="en-us_topic_0079614930_p20380862"></a><a name="en-us_topic_0079614930_p20380862"></a>failureThreshold</p>
</td>
<td class="cellrowborder" valign="top" width="30.330000000000002%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p40237110"><a name="en-us_topic_0079614930_p40237110"></a><a name="en-us_topic_0079614930_p40237110"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.61%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p37980454"><a name="en-us_topic_0079614930_p37980454"></a><a name="en-us_topic_0079614930_p37980454"></a>Minimum consecutive failures for the probe to be considered failed after having succeeded. Defaults to 3. Minimum value is 1.</p>
</td>
</tr>
</tbody>
</table>

**Table  53**  Data structure of the lifecycle field

<a name="en-us_topic_0079614930_table64348702"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row4240049"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p7899687"><a name="en-us_topic_0079614930_p7899687"></a><a name="en-us_topic_0079614930_p7899687"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p179411165596"><a name="p179411165596"></a><a name="p179411165596"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p279421612593"><a name="p279421612593"></a><a name="p279421612593"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row21312323"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p48576570"><a name="en-us_topic_0079614930_p48576570"></a><a name="en-us_topic_0079614930_p48576570"></a>postStart</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="afa14dbe327584092a1535af0ea8fa01d"><a name="afa14dbe327584092a1535af0ea8fa01d"></a><a name="afa14dbe327584092a1535af0ea8fa01d"></a><a href="#en-us_topic_0079614930_table16335389">postStart/preStop</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p10885567"><a name="en-us_topic_0079614930_p10885567"></a><a name="en-us_topic_0079614930_p10885567"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row30861244"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p16732802"><a name="en-us_topic_0079614930_p16732802"></a><a name="en-us_topic_0079614930_p16732802"></a>preStop</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a7dbde56db2324974bda611e3e8f68bcb"><a name="a7dbde56db2324974bda611e3e8f68bcb"></a><a name="a7dbde56db2324974bda611e3e8f68bcb"></a><a href="#en-us_topic_0079614930_table16335389">postStart/preStop</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p60924472"><a name="en-us_topic_0079614930_p60924472"></a><a name="en-us_topic_0079614930_p60924472"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  54**  Data structure of the securityContext field

<a name="en-us_topic_0079614930_table42267412"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row23912794"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p57888134"><a name="en-us_topic_0079614930_p57888134"></a><a name="en-us_topic_0079614930_p57888134"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1879531645918"><a name="p1879531645918"></a><a name="p1879531645918"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1479551612596"><a name="p1479551612596"></a><a name="p1479551612596"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row15710183"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p64565334"><a name="en-us_topic_0079614930_p64565334"></a><a name="en-us_topic_0079614930_p64565334"></a>capabilities</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p62409561"><a name="en-us_topic_0079614930_p62409561"></a><a name="en-us_topic_0079614930_p62409561"></a><a href="#en-us_topic_0079614930_table12800776">capabilities</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p22009689"><a name="en-us_topic_0079614930_p22009689"></a><a name="en-us_topic_0079614930_p22009689"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row63869475"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p6044968"><a name="en-us_topic_0079614930_p6044968"></a><a name="en-us_topic_0079614930_p6044968"></a>privileged</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p19880414"><a name="en-us_topic_0079614930_p19880414"></a><a name="en-us_topic_0079614930_p19880414"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p66809708"><a name="en-us_topic_0079614930_p66809708"></a><a name="en-us_topic_0079614930_p66809708"></a>Run container in privileged mode. Processes in privileged containers are essentially equivalent to root on the host. Defaults to false.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row64416468"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p50351451"><a name="en-us_topic_0079614930_p50351451"></a><a name="en-us_topic_0079614930_p50351451"></a>seLinuxOptions</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p51935693"><a name="en-us_topic_0079614930_p51935693"></a><a name="en-us_topic_0079614930_p51935693"></a><a href="#en-us_topic_0079614930_table44862393">seLinuxOptions</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p46041620"><a name="en-us_topic_0079614930_p46041620"></a><a name="en-us_topic_0079614930_p46041620"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row11721403"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p9909596"><a name="en-us_topic_0079614930_p9909596"></a><a name="en-us_topic_0079614930_p9909596"></a>runAsUser</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p64479813"><a name="en-us_topic_0079614930_p64479813"></a><a name="en-us_topic_0079614930_p64479813"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p55482399"><a name="en-us_topic_0079614930_p55482399"></a><a name="en-us_topic_0079614930_p55482399"></a>The UID to run the entrypoint of the container process. Defaults to user specified in image metadata if unspecified. May also be set in PodSecurityContext. If set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row29579550"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p47133348"><a name="en-us_topic_0079614930_p47133348"></a><a name="en-us_topic_0079614930_p47133348"></a>runAsNonRoot</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p59704814"><a name="en-us_topic_0079614930_p59704814"></a><a name="en-us_topic_0079614930_p59704814"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p4251748"><a name="en-us_topic_0079614930_p4251748"></a><a name="en-us_topic_0079614930_p4251748"></a>Indicates that the container must run as a non-root user. If true, the Kubelet will validate the image at runtime to ensure that it does not run as UID 0 (root) and fail to start the container if it does. If unset or false, no such validation will be performed. May also be set in PodSecurityContext. If set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence.</p>
</td>
</tr>
</tbody>
</table>

**Table  55**  Data structure of the seLinuxOptions field

<a name="en-us_topic_0079614930_table44862393"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row51424131"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p4605057"><a name="en-us_topic_0079614930_p4605057"></a><a name="en-us_topic_0079614930_p4605057"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p167971716175915"><a name="p167971716175915"></a><a name="p167971716175915"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p18797191610598"><a name="p18797191610598"></a><a name="p18797191610598"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row57196205"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p2381053"><a name="en-us_topic_0079614930_p2381053"></a><a name="en-us_topic_0079614930_p2381053"></a>user</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p58647622"><a name="en-us_topic_0079614930_p58647622"></a><a name="en-us_topic_0079614930_p58647622"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p52836911"><a name="en-us_topic_0079614930_p52836911"></a><a name="en-us_topic_0079614930_p52836911"></a>User is a SELinux user label that applies to the container.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row5770151"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p64729059"><a name="en-us_topic_0079614930_p64729059"></a><a name="en-us_topic_0079614930_p64729059"></a>role</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p8562452"><a name="en-us_topic_0079614930_p8562452"></a><a name="en-us_topic_0079614930_p8562452"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p22470050"><a name="en-us_topic_0079614930_p22470050"></a><a name="en-us_topic_0079614930_p22470050"></a>Role is a SELinux role label that applies to the container.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row903863"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p6104091"><a name="en-us_topic_0079614930_p6104091"></a><a name="en-us_topic_0079614930_p6104091"></a>type</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p24669326"><a name="en-us_topic_0079614930_p24669326"></a><a name="en-us_topic_0079614930_p24669326"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p52058427"><a name="en-us_topic_0079614930_p52058427"></a><a name="en-us_topic_0079614930_p52058427"></a>Type is a SELinux type label that applies to the container.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row65872662"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p34085386"><a name="en-us_topic_0079614930_p34085386"></a><a name="en-us_topic_0079614930_p34085386"></a>level</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p9452875"><a name="en-us_topic_0079614930_p9452875"></a><a name="en-us_topic_0079614930_p9452875"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p27485376"><a name="en-us_topic_0079614930_p27485376"></a><a name="en-us_topic_0079614930_p27485376"></a>Level is SELinux level label that applies to the container.</p>
</td>
</tr>
</tbody>
</table>

**Table  56**  Data structure of the items field

<a name="en-us_topic_0079614930_table1108358"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row1243712"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p33631824"><a name="en-us_topic_0079614930_p33631824"></a><a name="en-us_topic_0079614930_p33631824"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p379814164592"><a name="p379814164592"></a><a name="p379814164592"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p17981916145916"><a name="p17981916145916"></a><a name="p17981916145916"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row25427556"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p46366183"><a name="en-us_topic_0079614930_p46366183"></a><a name="en-us_topic_0079614930_p46366183"></a>path</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p64673322"><a name="en-us_topic_0079614930_p64673322"></a><a name="en-us_topic_0079614930_p64673322"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p4047701"><a name="en-us_topic_0079614930_p4047701"></a><a name="en-us_topic_0079614930_p4047701"></a>Required: Path is the relative path name of the file to be created. Must not be absolute or contain the '..' path. Must be utf-8 encoded. The first item of the relative path must not start with '..'</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row36429313"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p65093277"><a name="en-us_topic_0079614930_p65093277"></a><a name="en-us_topic_0079614930_p65093277"></a>fieldRef</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p38064052"><a name="en-us_topic_0079614930_p38064052"></a><a name="en-us_topic_0079614930_p38064052"></a><a href="#en-us_topic_0079614930_table48098122">fieldRef</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p63289392"><a name="en-us_topic_0079614930_p63289392"></a><a name="en-us_topic_0079614930_p63289392"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  57**  Data structure of the valueFrom field

<a name="en-us_topic_0079614930_table9975229"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row30238483"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p33398050"><a name="en-us_topic_0079614930_p33398050"></a><a name="en-us_topic_0079614930_p33398050"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p17799171625920"><a name="p17799171625920"></a><a name="p17799171625920"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p18799116175917"><a name="p18799116175917"></a><a name="p18799116175917"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row6946132"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p25765781"><a name="en-us_topic_0079614930_p25765781"></a><a name="en-us_topic_0079614930_p25765781"></a>fieldRef</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p6653511"><a name="en-us_topic_0079614930_p6653511"></a><a name="en-us_topic_0079614930_p6653511"></a><a href="#en-us_topic_0079614930_table48098122">fieldRef</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p2063505"><a name="en-us_topic_0079614930_p2063505"></a><a name="en-us_topic_0079614930_p2063505"></a>-</p>
</td>
</tr>
<tr id="r69c78bd61d9245059b619f92aa1e1060"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p53846543114"><a name="en-us_topic_0079614930_p53846543114"></a><a name="en-us_topic_0079614930_p53846543114"></a>resourceFieldRef</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p163841559315"><a name="en-us_topic_0079614930_p163841559315"></a><a name="en-us_topic_0079614930_p163841559315"></a><a href="#t1d4186ca4f8d41b6802b56b71011f7a8">resourceFieldRef</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="a2b82b2ba44454e83b4bf86bfe99fcb80"><a name="a2b82b2ba44454e83b4bf86bfe99fcb80"></a><a name="a2b82b2ba44454e83b4bf86bfe99fcb80"></a>Selects a resource of the container: only resources limits and requests (limits.cpu, limits.memory, requests.cpu and requests.memory) are currently supported.</p>
</td>
</tr>
</tbody>
</table>

**Table  58**  Data structure of the exec field

<a name="en-us_topic_0079614930_table22668197"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row50448563"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p59801811"><a name="en-us_topic_0079614930_p59801811"></a><a name="en-us_topic_0079614930_p59801811"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p1680113163592"><a name="p1680113163592"></a><a name="p1680113163592"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1780181611598"><a name="p1780181611598"></a><a name="p1780181611598"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row54104749"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p20408526"><a name="en-us_topic_0079614930_p20408526"></a><a name="en-us_topic_0079614930_p20408526"></a>command</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p42477941"><a name="en-us_topic_0079614930_p42477941"></a><a name="en-us_topic_0079614930_p42477941"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p18161159"><a name="en-us_topic_0079614930_p18161159"></a><a name="en-us_topic_0079614930_p18161159"></a>Command is the command line to execute inside the container, the working directory for the command is root ('/') in the container's filesystem. The command is simply exec'd, it is not run inside a shell, so traditional shell instructions ('|', etc) do not work. To use a shell, you need to explicitly call out to that shell. Exit status of 0 is treated as live/healthy and non-zero is unhealthy.</p>
</td>
</tr>
</tbody>
</table>

**Table  59**  Data structure of the httpGet field

<a name="en-us_topic_0079614930_table2687184"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row26632111"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p9717417"><a name="en-us_topic_0079614930_p9717417"></a><a name="en-us_topic_0079614930_p9717417"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p14802141615593"><a name="p14802141615593"></a><a name="p14802141615593"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p1580212166591"><a name="p1580212166591"></a><a name="p1580212166591"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row5837642"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p3086998"><a name="en-us_topic_0079614930_p3086998"></a><a name="en-us_topic_0079614930_p3086998"></a>path</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p48720282"><a name="en-us_topic_0079614930_p48720282"></a><a name="en-us_topic_0079614930_p48720282"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p54028799"><a name="en-us_topic_0079614930_p54028799"></a><a name="en-us_topic_0079614930_p54028799"></a>Path to access on the HTTP server.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row16497149"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p61200726"><a name="en-us_topic_0079614930_p61200726"></a><a name="en-us_topic_0079614930_p61200726"></a>port</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p58311779"><a name="en-us_topic_0079614930_p58311779"></a><a name="en-us_topic_0079614930_p58311779"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p25633677"><a name="en-us_topic_0079614930_p25633677"></a><a name="en-us_topic_0079614930_p25633677"></a>Name or number of the port to access on the container. Number must be in the range 1 to 65535. Name must be an IANA_SVC_NAME.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row29376504"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p30686615"><a name="en-us_topic_0079614930_p30686615"></a><a name="en-us_topic_0079614930_p30686615"></a>host</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p2587911"><a name="en-us_topic_0079614930_p2587911"></a><a name="en-us_topic_0079614930_p2587911"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p8294256"><a name="en-us_topic_0079614930_p8294256"></a><a name="en-us_topic_0079614930_p8294256"></a>Host name to connect to, defaults to the pod IP.</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row7539441"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p6714945"><a name="en-us_topic_0079614930_p6714945"></a><a name="en-us_topic_0079614930_p6714945"></a>scheme</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p7039645"><a name="en-us_topic_0079614930_p7039645"></a><a name="en-us_topic_0079614930_p7039645"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p33340398"><a name="en-us_topic_0079614930_p33340398"></a><a name="en-us_topic_0079614930_p33340398"></a>Scheme to use for connecting to the host. Defaults to HTTP.</p>
</td>
</tr>
</tbody>
</table>

**Table  60**  Data structure of the tcpSocket field

<a name="en-us_topic_0079614930_table24184664"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row65930648"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p38782309"><a name="en-us_topic_0079614930_p38782309"></a><a name="en-us_topic_0079614930_p38782309"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p38042169593"><a name="p38042169593"></a><a name="p38042169593"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p20804201605912"><a name="p20804201605912"></a><a name="p20804201605912"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row34957613"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p12994411"><a name="en-us_topic_0079614930_p12994411"></a><a name="en-us_topic_0079614930_p12994411"></a>port</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p45914410"><a name="en-us_topic_0079614930_p45914410"></a><a name="en-us_topic_0079614930_p45914410"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p28079762"><a name="en-us_topic_0079614930_p28079762"></a><a name="en-us_topic_0079614930_p28079762"></a>Number or name of the port to access on the container. Number must be in the range 1 to 65535. Name must be an IANA_SVC_NAME.</p>
</td>
</tr>
</tbody>
</table>

**Table  61**  Data structure of the postStart/preStop field

<a name="en-us_topic_0079614930_table16335389"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row65732647"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p22744204"><a name="en-us_topic_0079614930_p22744204"></a><a name="en-us_topic_0079614930_p22744204"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p15805616105917"><a name="p15805616105917"></a><a name="p15805616105917"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p78051216115911"><a name="p78051216115911"></a><a name="p78051216115911"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row23863445"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p53890875"><a name="en-us_topic_0079614930_p53890875"></a><a name="en-us_topic_0079614930_p53890875"></a>exec</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a7ddc1436f962492fad4079cbb22ffc92"><a name="a7ddc1436f962492fad4079cbb22ffc92"></a><a name="a7ddc1436f962492fad4079cbb22ffc92"></a><a href="#en-us_topic_0079614930_table22668197">exec</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p48541486"><a name="en-us_topic_0079614930_p48541486"></a><a name="en-us_topic_0079614930_p48541486"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row34220196"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p20372514"><a name="en-us_topic_0079614930_p20372514"></a><a name="en-us_topic_0079614930_p20372514"></a>httpGet</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="aa46a45fc7dc04a1e82fe1a2e10517def"><a name="aa46a45fc7dc04a1e82fe1a2e10517def"></a><a name="aa46a45fc7dc04a1e82fe1a2e10517def"></a><a href="#en-us_topic_0079614930_table2687184">httpGet</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p50317270"><a name="en-us_topic_0079614930_p50317270"></a><a name="en-us_topic_0079614930_p50317270"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row50202250"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p39850440"><a name="en-us_topic_0079614930_p39850440"></a><a name="en-us_topic_0079614930_p39850440"></a>tcpSocket</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a2109314a61634d72ad350a3388b682cb"><a name="a2109314a61634d72ad350a3388b682cb"></a><a name="a2109314a61634d72ad350a3388b682cb"></a><a href="#en-us_topic_0079614930_table24184664">tcpSocket</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p2606194"><a name="en-us_topic_0079614930_p2606194"></a><a name="en-us_topic_0079614930_p2606194"></a>TCPSocket specifies an action involving a TCP port. TCP hooks not yet supported.</p>
</td>
</tr>
</tbody>
</table>

**Table  62**  Data structure of the capabilities field

<a name="en-us_topic_0079614930_table12800776"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row9493201"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p30751803"><a name="en-us_topic_0079614930_p30751803"></a><a name="en-us_topic_0079614930_p30751803"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p080610167596"><a name="p080610167596"></a><a name="p080610167596"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p98070169594"><a name="p98070169594"></a><a name="p98070169594"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row16114973"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p30244474"><a name="en-us_topic_0079614930_p30244474"></a><a name="en-us_topic_0079614930_p30244474"></a>add</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p33883319"><a name="en-us_topic_0079614930_p33883319"></a><a name="en-us_topic_0079614930_p33883319"></a><a href="#t32d1ae0b791b43ada220117e4f918910">Table68 Data structure of the add field</a></p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p60194300"><a name="en-us_topic_0079614930_p60194300"></a><a name="en-us_topic_0079614930_p60194300"></a>Added capabilities</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row4877794"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p59556999"><a name="en-us_topic_0079614930_p59556999"></a><a name="en-us_topic_0079614930_p59556999"></a>drop</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p59387592"><a name="en-us_topic_0079614930_p59387592"></a><a name="en-us_topic_0079614930_p59387592"></a><a href="#t32d1ae0b791b43ada220117e4f918910">Table 65</a></p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p45665679"><a name="en-us_topic_0079614930_p45665679"></a><a name="en-us_topic_0079614930_p45665679"></a>Removed capabilities</p>
</td>
</tr>
</tbody>
</table>

**Table  63**  Data structure of the fieldRef field

<a name="en-us_topic_0079614930_table48098122"></a>
<table><thead align="left"><tr id="en-us_topic_0079614930_row52349424"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p12444953"><a name="en-us_topic_0079614930_p12444953"></a><a name="en-us_topic_0079614930_p12444953"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p4808716135911"><a name="p4808716135911"></a><a name="p4808716135911"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p7808101625917"><a name="p7808101625917"></a><a name="p7808101625917"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614930_row45993305"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p34470196"><a name="en-us_topic_0079614930_p34470196"></a><a name="en-us_topic_0079614930_p34470196"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p40622496"><a name="en-us_topic_0079614930_p40622496"></a><a name="en-us_topic_0079614930_p40622496"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p2087876"><a name="en-us_topic_0079614930_p2087876"></a><a name="en-us_topic_0079614930_p2087876"></a>Version of the schema the FieldPath is written in terms of, defaults to "v1"</p>
</td>
</tr>
<tr id="en-us_topic_0079614930_row18790891"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p45667223"><a name="en-us_topic_0079614930_p45667223"></a><a name="en-us_topic_0079614930_p45667223"></a>fieldPath</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p8057616"><a name="en-us_topic_0079614930_p8057616"></a><a name="en-us_topic_0079614930_p8057616"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p48687165"><a name="en-us_topic_0079614930_p48687165"></a><a name="en-us_topic_0079614930_p48687165"></a>Path of the field to select in the specified API version.</p>
</td>
</tr>
</tbody>
</table>

**Table  64**  Data structure of the resourceFieldRef field

<a name="t1d4186ca4f8d41b6802b56b71011f7a8"></a>
<table><thead align="left"><tr id="r349d25501ca74176a76a2d7d12fcdffc"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614930_p129724816411"><a name="en-us_topic_0079614930_p129724816411"></a><a name="en-us_topic_0079614930_p129724816411"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.2.4.1.2"><p id="p28091916115917"><a name="p28091916115917"></a><a name="p28091916115917"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="p48091516105914"><a name="p48091516105914"></a><a name="p48091516105914"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r59d8c9249f50491db175524d5eb0e1c8"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="af30802d2778043beb044724d1bddd9da"><a name="af30802d2778043beb044724d1bddd9da"></a><a name="af30802d2778043beb044724d1bddd9da"></a>containerName</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p736171064317"><a name="en-us_topic_0079614930_p736171064317"></a><a name="en-us_topic_0079614930_p736171064317"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p183691094313"><a name="en-us_topic_0079614930_p183691094313"></a><a name="en-us_topic_0079614930_p183691094313"></a>Container name:   required for volumes, optional for env vars.</p>
</td>
</tr>
<tr id="rce36e307c4b74eb1a25f604d6050d625"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="a6182e0c9922343dfb74af1af7d91b758"><a name="a6182e0c9922343dfb74af1af7d91b758"></a><a name="a6182e0c9922343dfb74af1af7d91b758"></a>resource</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p173621024317"><a name="en-us_topic_0079614930_p173621024317"></a><a name="en-us_topic_0079614930_p173621024317"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="a33d440f9b0a1468d99d092e065bf6482"><a name="a33d440f9b0a1468d99d092e065bf6482"></a><a name="a33d440f9b0a1468d99d092e065bf6482"></a>Required: resource to   select.</p>
</td>
</tr>
<tr id="r9c8a022b9a02467c874d2a795c23d80d"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="a4088a39d5b8e4d5080e00419529528d3"><a name="a4088a39d5b8e4d5080e00419529528d3"></a><a name="a4088a39d5b8e4d5080e00419529528d3"></a>divisor</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="p1688916572920"><a name="p1688916572920"></a><a name="p1688916572920"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p43618106438"><a name="en-us_topic_0079614930_p43618106438"></a><a name="en-us_topic_0079614930_p43618106438"></a>Specifies the output   format of the exposed resources, defaults to "1".</p>
</td>
</tr>
</tbody>
</table>

**Table  65**  Data structure of the add field

<a name="t32d1ae0b791b43ada220117e4f918910"></a>
<table><thead align="left"><tr id="r3de984aa47c7415294d6b8da46e19ba1"><th class="cellrowborder" valign="top" width="25.06%" id="mcps1.2.4.1.1"><p id="a3fd83a91b0f746fcaed57aca5f6e63d6"><a name="a3fd83a91b0f746fcaed57aca5f6e63d6"></a><a name="a3fd83a91b0f746fcaed57aca5f6e63d6"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.14%" id="mcps1.2.4.1.2"><p id="p181113165598"><a name="p181113165598"></a><a name="p181113165598"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.800000000000004%" id="mcps1.2.4.1.3"><p id="p2811516155918"><a name="p2811516155918"></a><a name="p2811516155918"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="re862a5869d2c4a4497691109047d3f37"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="a2500bb788f0f4b1d9e40bf11ce723947"><a name="a2500bb788f0f4b1d9e40bf11ce723947"></a><a name="a2500bb788f0f4b1d9e40bf11ce723947"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a6d16fae516014d8e925bb4fd604a0f35"><a name="a6d16fae516014d8e925bb4fd604a0f35"></a><a name="a6d16fae516014d8e925bb4fd604a0f35"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="aa3f5ccf836c74113952c5a8e8d7ee20f"><a name="aa3f5ccf836c74113952c5a8e8d7ee20f"></a><a name="aa3f5ccf836c74113952c5a8e8d7ee20f"></a>name is the name of the resource.</p>
</td>
</tr>
<tr id="ra5c8656a6da24d8e9b276bfd07c17a08"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="a7879b604e1704f2a9c33774298747ac6"><a name="a7879b604e1704f2a9c33774298747ac6"></a><a name="a7879b604e1704f2a9c33774298747ac6"></a>namespaced</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a3240b6ebbc1d413e9e23dd938c3ce8e1"><a name="a3240b6ebbc1d413e9e23dd938c3ce8e1"></a><a name="a3240b6ebbc1d413e9e23dd938c3ce8e1"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="aca7fc11a4e29440bb12fa3a6b81122c4"><a name="aca7fc11a4e29440bb12fa3a6b81122c4"></a><a name="aca7fc11a4e29440bb12fa3a6b81122c4"></a>namespaced indicates if a resource is namespaced or not.</p>
<p id="ad4860642f3444e77bbe8b7d642c94352"><a name="ad4860642f3444e77bbe8b7d642c94352"></a><a name="ad4860642f3444e77bbe8b7d642c94352"></a>Default: false.</p>
</td>
</tr>
<tr id="r178105d154024f30be0d1da4c29b2aea"><td class="cellrowborder" valign="top" width="25.06%" headers="mcps1.2.4.1.1 "><p id="a00594a1c0b16405a99803ea665ea878f"><a name="a00594a1c0b16405a99803ea665ea878f"></a><a name="a00594a1c0b16405a99803ea665ea878f"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30.14%" headers="mcps1.2.4.1.2 "><p id="a9a23bd10737c42eebef20001647b8cec"><a name="a9a23bd10737c42eebef20001647b8cec"></a><a name="a9a23bd10737c42eebef20001647b8cec"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.800000000000004%" headers="mcps1.2.4.1.3 "><p id="a19ed190ca00447aba70a0af137c25683"><a name="a19ed190ca00447aba70a0af137c25683"></a><a name="a19ed190ca00447aba70a0af137c25683"></a>kind is the kind for the resource.</p>
</td>
</tr>
</tbody>
</table>

**Table  66**  Data structure of the ReplicationControllerCondition field

<a name="t0136d24c39ae4df89959d36b2119f260"></a>
<table><thead align="left"><tr id="r3cdaa47a76e2437f8a25f925733c8f39"><th class="cellrowborder" valign="top" width="25.252525252525253%" id="mcps1.2.4.1.1"><p id="a2b6a1243cf574addb319333c360c54a9"><a name="a2b6a1243cf574addb319333c360c54a9"></a><a name="a2b6a1243cf574addb319333c360c54a9"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.303030303030305%" id="mcps1.2.4.1.2"><p id="p88137169599"><a name="p88137169599"></a><a name="p88137169599"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.44444444444445%" id="mcps1.2.4.1.3"><p id="p1681301675910"><a name="p1681301675910"></a><a name="p1681301675910"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="rfe32d7b8e56b4ba9a9cf3bac395f90fb"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="a9755e853a8864a5a93492a4d5733cfd4"><a name="a9755e853a8864a5a93492a4d5733cfd4"></a><a name="a9755e853a8864a5a93492a4d5733cfd4"></a>lastTransitionTime</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p199542118405"><a name="en-us_topic_0079614930_p199542118405"></a><a name="en-us_topic_0079614930_p199542118405"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="a7bcd0a6ebaf945f09d63fb4566cd65d8"><a name="a7bcd0a6ebaf945f09d63fb4566cd65d8"></a><a name="a7bcd0a6ebaf945f09d63fb4566cd65d8"></a>The last time the condition transitioned from one status to another.</p>
</td>
</tr>
<tr id="r142ba66979704805a5d4284b8753ad8c"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="a7c6b6a3547d54527b9f6c494c9546f2d"><a name="a7c6b6a3547d54527b9f6c494c9546f2d"></a><a name="a7c6b6a3547d54527b9f6c494c9546f2d"></a>message</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p152431218409"><a name="en-us_topic_0079614930_p152431218409"></a><a name="en-us_topic_0079614930_p152431218409"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p554612154015"><a name="en-us_topic_0079614930_p554612154015"></a><a name="en-us_topic_0079614930_p554612154015"></a>A human readable message indicating details about the transition.</p>
</td>
</tr>
<tr id="rf0b1e8b3183c4de7b5f926b59afb796f"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p878912134011"><a name="en-us_topic_0079614930_p878912134011"></a><a name="en-us_topic_0079614930_p878912134011"></a>reason</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="ac2d5b8b4490840748e4bd1b79f15bda4"><a name="ac2d5b8b4490840748e4bd1b79f15bda4"></a><a name="ac2d5b8b4490840748e4bd1b79f15bda4"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="a744286d7c6bc4a4ea3b6471fd485a3e6"><a name="a744286d7c6bc4a4ea3b6471fd485a3e6"></a><a name="a744286d7c6bc4a4ea3b6471fd485a3e6"></a>The reason for the condition's last transition.</p>
</td>
</tr>
<tr id="r151ea787e5b74dbd9abcc300f145af13"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="ab552d6145bac4cf38f894d786403c49b"><a name="ab552d6145bac4cf38f894d786403c49b"></a><a name="ab552d6145bac4cf38f894d786403c49b"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614930_p164962421418"><a name="en-us_topic_0079614930_p164962421418"></a><a name="en-us_topic_0079614930_p164962421418"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="ae84db2b0603c4f4e9bc0ba89b30062d1"><a name="ae84db2b0603c4f4e9bc0ba89b30062d1"></a><a name="ae84db2b0603c4f4e9bc0ba89b30062d1"></a>Status of the condition, one of True, False, Unknown.</p>
</td>
</tr>
<tr id="r26c875af796640d48588914943e5f375"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="a4320aff34fe5422d9f2e3af07e762ac0"><a name="a4320aff34fe5422d9f2e3af07e762ac0"></a><a name="a4320aff34fe5422d9f2e3af07e762ac0"></a>type</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="ae6e5f3ed4e9b47c2b35ef5bd03f3ccfb"><a name="ae6e5f3ed4e9b47c2b35ef5bd03f3ccfb"></a><a name="ae6e5f3ed4e9b47c2b35ef5bd03f3ccfb"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="ab6658f1bcbd343328b9967aba6bcaec0"><a name="ab6658f1bcbd343328b9967aba6bcaec0"></a><a name="ab6658f1bcbd343328b9967aba6bcaec0"></a>Type of replication controller condition.</p>
</td>
</tr>
</tbody>
</table>

**Table  67**  Data structure of the metadata field

<a name="tf50171b557ef4ebdafb2cc0bcb724d1b"></a>
<table><thead align="left"><tr id="r1893423f49864701824a66b2055df20b"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.4.1.1"><p id="a0d847fe09883492b80c890e6ab45948b"><a name="a0d847fe09883492b80c890e6ab45948b"></a><a name="a0d847fe09883492b80c890e6ab45948b"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.2.4.1.2"><p id="p8814101685915"><a name="p8814101685915"></a><a name="p8814101685915"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="p178141916145917"><a name="p178141916145917"></a><a name="p178141916145917"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r725cd03c33ec49e79f1666b2283b3236"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="a640a4bb48fa04ba9bbe5b9e09c10938e"><a name="a640a4bb48fa04ba9bbe5b9e09c10938e"></a><a name="a640a4bb48fa04ba9bbe5b9e09c10938e"></a>resourceVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="a20301e8689274dc19cdcb38d619b30b7"><a name="a20301e8689274dc19cdcb38d619b30b7"></a><a name="a20301e8689274dc19cdcb38d619b30b7"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p171463218201"><a name="en-us_topic_0079614930_p171463218201"></a><a name="en-us_topic_0079614930_p171463218201"></a>String that identifies the server's internal version of this object that can be used by clients to determine when objects have changed. Value must be treated as opaque by clients and passed unmodified back to the server. Populated by the system. Read-only.</p>
</td>
</tr>
<tr id="r17687a2c28784b859780dad77b72a6c6"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614930_p136004832111"><a name="en-us_topic_0079614930_p136004832111"></a><a name="en-us_topic_0079614930_p136004832111"></a>selfLink</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="a2a8ebb2a4c9842bca1bcf6b280e87428"><a name="a2a8ebb2a4c9842bca1bcf6b280e87428"></a><a name="a2a8ebb2a4c9842bca1bcf6b280e87428"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614930_p860017815212"><a name="en-us_topic_0079614930_p860017815212"></a><a name="en-us_topic_0079614930_p860017815212"></a>SelfLink is a URL representing this object. Populated by the system. Read-only.</p>
</td>
</tr>
</tbody>
</table>

