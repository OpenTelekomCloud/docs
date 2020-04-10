# Error Codes<a name="cce_02_0250"></a>

<a name="table16560203141610"></a>
<table><thead align="left"><tr id="row184692918116"><th class="cellrowborder" valign="top" width="32.95%" id="mcps1.1.5.1.1"><p id="p1231114141612"><a name="p1231114141612"></a><a name="p1231114141612"></a>Error Type</p>
</th>
<th class="cellrowborder" valign="top" width="20.04%" id="mcps1.1.5.1.2"><p id="p7321847161"><a name="p7321847161"></a><a name="p7321847161"></a>Error Code</p>
</th>
<th class="cellrowborder" valign="top" width="22.46%" id="mcps1.1.5.1.3"><p id="p3325416161"><a name="p3325416161"></a><a name="p3325416161"></a>Error Description</p>
</th>
<th class="cellrowborder" valign="top" width="24.55%" id="mcps1.1.5.1.4"><p id="p193234121611"><a name="p193234121611"></a><a name="p193234121611"></a>Handling Suggestions (Optional)</p>
</th>
</tr>
</thead>
<tbody><tr id="row18461429216"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p13216411165"><a name="p13216411165"></a><a name="p13216411165"></a>GET_USER_INFO_ERROR</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p193210411168"><a name="p193210411168"></a><a name="p193210411168"></a>SVCSTG.CCECAM.5000001</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p1832949162"><a name="p1832949162"></a><a name="p1832949162"></a>Failed to obtain user information.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p7323417162"><a name="p7323417162"></a><a name="p7323417162"></a>Check whether the user token is correct.</p>
</td>
</tr>
<tr id="row88461329816"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p032041162"><a name="p032041162"></a><a name="p032041162"></a>INVALID_REQUEST_BODY</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p203218419163"><a name="p203218419163"></a><a name="p203218419163"></a>SVCSTG.CCECAM.5000002</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p17329431617"><a name="p17329431617"></a><a name="p17329431617"></a>The structure of the request body is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p4323431617"><a name="p4323431617"></a><a name="p4323431617"></a>Check whether the request body structure and parameters meet specified requirements.</p>
</td>
</tr>
<tr id="row208471929517"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p153217411611"><a name="p153217411611"></a><a name="p153217411611"></a>PARSE_REQUEST_BODY_ERROR</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p203315421612"><a name="p203315421612"></a><a name="p203315421612"></a>SVCSTG.CCECAM.4000003</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p15332451611"><a name="p15332451611"></a><a name="p15332451611"></a>Failed to parse the request body.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p19331481619"><a name="p19331481619"></a><a name="p19331481619"></a>Check whether the request body structure and parameters meet specified requirements.</p>
</td>
</tr>
<tr id="row1284718291817"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p16333419164"><a name="p16333419164"></a><a name="p16333419164"></a>UNMARSHAL_CHART_VALUE_ERROR</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p23311413165"><a name="p23311413165"></a><a name="p23311413165"></a>SVCSTG.CCECAM.5000101</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p103320411163"><a name="p103320411163"></a><a name="p103320411163"></a>Failed to decode the template parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p103310413162"><a name="p103310413162"></a><a name="p103310413162"></a>-</p>
</td>
</tr>
<tr id="row18847629413"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p1339411612"><a name="p1339411612"></a><a name="p1339411612"></a>INVALID_CHART_REQUEST_BODY</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p7331245169"><a name="p7331245169"></a><a name="p7331245169"></a>SVCSTG.CCECAM.4030102</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p433174151611"><a name="p433174151611"></a><a name="p433174151611"></a>Failed to update some template parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p1233194191613"><a name="p1233194191613"></a><a name="p1233194191613"></a>Check whether the name, domain, and version parameters, which have fixed values, are modified in the template.</p>
</td>
</tr>
<tr id="row1584719291016"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p103354131610"><a name="p103354131610"></a><a name="p103354131610"></a>INVALID_CHART_NAME</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p734194131612"><a name="p734194131612"></a><a name="p734194131612"></a>SVCSTG.CCECAM.4000103</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p19341416165"><a name="p19341416165"></a><a name="p19341416165"></a>Invalid template name format.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p13346461619"><a name="p13346461619"></a><a name="p13346461619"></a>Check whether the template name format is correct.</p>
</td>
</tr>
<tr id="row128489291317"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p1234549161"><a name="p1234549161"></a><a name="p1234549161"></a>INVALID_CHART_VERSION</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p43413411612"><a name="p43413411612"></a><a name="p43413411612"></a>SVCSTG.CCECAM.4000104</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p15341243162"><a name="p15341243162"></a><a name="p15341243162"></a>Invalid template version format.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p33416415167"><a name="p33416415167"></a><a name="p33416415167"></a>Check whether the template version format is correct.</p>
</td>
</tr>
<tr id="row78489291414"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p73412431616"><a name="p73412431616"></a><a name="p73412431616"></a>INVALID_CHART_ID</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p934154171610"><a name="p934154171610"></a><a name="p934154171610"></a>SVCSTG.CCECAM.4000105</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p2341420166"><a name="p2341420166"></a><a name="p2341420166"></a>Invalid template ID format.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p103418401612"><a name="p103418401612"></a><a name="p103418401612"></a>Check whether the template ID format is correct.</p>
</td>
</tr>
<tr id="row1784882910111"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p11345416162"><a name="p11345416162"></a><a name="p11345416162"></a>INVALID_DOMAIN_NAME</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p16346431612"><a name="p16346431612"></a><a name="p16346431612"></a>SVCSTG.CCECAM.4000106</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p8341461613"><a name="p8341461613"></a><a name="p8341461613"></a>Invalid tenant name format.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p103424101620"><a name="p103424101620"></a><a name="p103424101620"></a>-</p>
</td>
</tr>
<tr id="row78491291716"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p6341047162"><a name="p6341047162"></a><a name="p6341047162"></a>SAVE_CHART_TO_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p173411481610"><a name="p173411481610"></a><a name="p173411481610"></a>SVCSTG.CCECAM.4000107</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p11348411164"><a name="p11348411164"></a><a name="p11348411164"></a>Failed to write template data to the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p6341648166"><a name="p6341648166"></a><a name="p6341648166"></a>-</p>
</td>
</tr>
<tr id="row58491529412"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p163464131612"><a name="p163464131612"></a><a name="p163464131612"></a>SAVE_CHART_TO_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p034647162"><a name="p034647162"></a><a name="p034647162"></a>SVCSTG.CCECAM.4040107</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p15342451613"><a name="p15342451613"></a><a name="p15342451613"></a>Failed to write template data to the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p1341344166"><a name="p1341344166"></a><a name="p1341344166"></a>-</p>
</td>
</tr>
<tr id="row1884919296119"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p12348419168"><a name="p12348419168"></a><a name="p12348419168"></a>SAVE_CHART_TO_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p143416414169"><a name="p143416414169"></a><a name="p143416414169"></a>SVCSTG.CCECAM.5000107</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p2341042163"><a name="p2341042163"></a><a name="p2341042163"></a>Failed to write template data to the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p113454101615"><a name="p113454101615"></a><a name="p113454101615"></a>-</p>
</td>
</tr>
<tr id="row1985072917111"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p123518431617"><a name="p123518431617"></a><a name="p123518431617"></a>GET_CHART_LIST_FROM_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p23544111617"><a name="p23544111617"></a><a name="p23544111617"></a>SVCSTG.CCECAM.4000108</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p14354412163"><a name="p14354412163"></a><a name="p14354412163"></a>Failed to obtain the template list from the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p1835164111616"><a name="p1835164111616"></a><a name="p1835164111616"></a>-</p>
</td>
</tr>
<tr id="row585015291118"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p33519420162"><a name="p33519420162"></a><a name="p33519420162"></a>GET_CHART_LIST_FROM_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p1351141166"><a name="p1351141166"></a><a name="p1351141166"></a>SVCSTG.CCECAM.4040108</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p33520481620"><a name="p33520481620"></a><a name="p33520481620"></a>Failed to obtain the template list from the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p113514171619"><a name="p113514171619"></a><a name="p113514171619"></a>-</p>
</td>
</tr>
<tr id="row68516291514"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p143515411612"><a name="p143515411612"></a><a name="p143515411612"></a>GET_CHART_LIST_FROM_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p17351046167"><a name="p17351046167"></a><a name="p17351046167"></a>SVCSTG.CCECAM.5000108</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p163610413164"><a name="p163610413164"></a><a name="p163610413164"></a>Failed to obtain the template list from the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p1336114151612"><a name="p1336114151612"></a><a name="p1336114151612"></a>-</p>
</td>
</tr>
<tr id="row785272916116"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p203634201616"><a name="p203634201616"></a><a name="p203634201616"></a>GET_CHART_FROM_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p163634161611"><a name="p163634161611"></a><a name="p163634161611"></a>SVCSTG.CCECAM.4000109</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p15363481611"><a name="p15363481611"></a><a name="p15363481611"></a>Failed to obtain the information about a template from the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p83644131610"><a name="p83644131610"></a><a name="p83644131610"></a>-</p>
</td>
</tr>
<tr id="row168521299114"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p1336746161"><a name="p1336746161"></a><a name="p1336746161"></a>GET_CHART_FROM_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p1136946162"><a name="p1136946162"></a><a name="p1136946162"></a>SVCSTG.CCECAM.4040109</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p6365417168"><a name="p6365417168"></a><a name="p6365417168"></a>Failed to obtain the information about a template from the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p93674161617"><a name="p93674161617"></a><a name="p93674161617"></a>-</p>
</td>
</tr>
<tr id="row2085212297112"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p2369431619"><a name="p2369431619"></a><a name="p2369431619"></a>GET_CHART_FROM_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p1837124151612"><a name="p1837124151612"></a><a name="p1837124151612"></a>SVCSTG.CCECAM.5000109</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p123714451610"><a name="p123714451610"></a><a name="p123714451610"></a>Failed to obtain the information about a template from the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p33719411615"><a name="p33719411615"></a><a name="p33719411615"></a>-</p>
</td>
</tr>
<tr id="row158525298115"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p2374481619"><a name="p2374481619"></a><a name="p2374481619"></a>UPDATE_CHART_TO_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p137124101613"><a name="p137124101613"></a><a name="p137124101613"></a>SVCSTG.CCECAM.4000110</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p20373411168"><a name="p20373411168"></a><a name="p20373411168"></a>Failed to update template data in the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p637134201611"><a name="p637134201611"></a><a name="p637134201611"></a>-</p>
</td>
</tr>
<tr id="row108521291516"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p1437134201619"><a name="p1437134201619"></a><a name="p1437134201619"></a>UPDATE_CHART_TO_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p203744201614"><a name="p203744201614"></a><a name="p203744201614"></a>SVCSTG.CCECAM.4040110</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p83714141614"><a name="p83714141614"></a><a name="p83714141614"></a>Failed to update template data in the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p1537134121613"><a name="p1537134121613"></a><a name="p1537134121613"></a>-</p>
</td>
</tr>
<tr id="row1853152912118"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p138643161"><a name="p138643161"></a><a name="p138643161"></a>UPDATE_CHART_TO_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p8384415164"><a name="p8384415164"></a><a name="p8384415164"></a>SVCSTG.CCECAM.5000110</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p73874191616"><a name="p73874191616"></a><a name="p73874191616"></a>Failed to update template data in the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p1381848164"><a name="p1381848164"></a><a name="p1381848164"></a>-</p>
</td>
</tr>
<tr id="row1285320291712"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p153894121619"><a name="p153894121619"></a><a name="p153894121619"></a>DELETE_CHART_FROM_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p1538048161"><a name="p1538048161"></a><a name="p1538048161"></a>SVCSTG.CCECAM.4000111</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p183811461613"><a name="p183811461613"></a><a name="p183811461613"></a>Failed to delete a template from the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p183874131612"><a name="p183874131612"></a><a name="p183874131612"></a>-</p>
</td>
</tr>
<tr id="row48533291215"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p038644160"><a name="p038644160"></a><a name="p038644160"></a>DELETE_CHART_FROM_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p143814181616"><a name="p143814181616"></a><a name="p143814181616"></a>SVCSTG.CCECAM.4040111</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p103916413160"><a name="p103916413160"></a><a name="p103916413160"></a>Failed to delete a template from the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p4391842169"><a name="p4391842169"></a><a name="p4391842169"></a>-</p>
</td>
</tr>
<tr id="row48541129818"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p739124111619"><a name="p739124111619"></a><a name="p739124111619"></a>DELETE_CHART_FROM_DB_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p33924151611"><a name="p33924151611"></a><a name="p33924151611"></a>SVCSTG.CCECAM.5000111</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p18391749163"><a name="p18391749163"></a><a name="p18391749163"></a>Failed to delete a template from the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p18391546168"><a name="p18391546168"></a><a name="p18391546168"></a>-</p>
</td>
</tr>
<tr id="row58541229611"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p1839241164"><a name="p1839241164"></a><a name="p1839241164"></a>CHART_ALREADY_EXISTED_IN_DB</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p839642162"><a name="p839642162"></a><a name="p839642162"></a>SVCSTG.CCECAM.4090112</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p123974171615"><a name="p123974171615"></a><a name="p123974171615"></a>The template with the same name already exists in the database.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p12391448165"><a name="p12391448165"></a><a name="p12391448165"></a>Change the name of the template to be uploaded.</p>
</td>
</tr>
<tr id="row168541291514"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p0391848166"><a name="p0391848166"></a><a name="p0391848166"></a>UPLOAD_CHART_FILE_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p153915410161"><a name="p153915410161"></a><a name="p153915410161"></a>SVCSTG.CCECAM.5000113</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p12391446161"><a name="p12391446161"></a><a name="p12391446161"></a>Failed to upload the template file to a remote volume.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p53916418163"><a name="p53916418163"></a><a name="p53916418163"></a>-</p>
</td>
</tr>
<tr id="row1685418291715"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p104019419162"><a name="p104019419162"></a><a name="p104019419162"></a>UPDATE_CHART_PROPERTY_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p6409415162"><a name="p6409415162"></a><a name="p6409415162"></a>SVCSTG.CCECAM.5000114</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p04018419167"><a name="p04018419167"></a><a name="p04018419167"></a>Failed to update template attributes on a remote volume.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p5400411619"><a name="p5400411619"></a><a name="p5400411619"></a>-</p>
</td>
</tr>
<tr id="row78558296115"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p1140184121617"><a name="p1140184121617"></a><a name="p1140184121617"></a>DELETE_CHART_FROM_STORAGE_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p16401443168"><a name="p16401443168"></a><a name="p16401443168"></a>SVCSTG.CCECAM.5000115</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p14084141613"><a name="p14084141613"></a><a name="p14084141613"></a>Failed to delete the template from a remote volume.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p17418491618"><a name="p17418491618"></a><a name="p17418491618"></a>-</p>
</td>
</tr>
<tr id="row14855152917114"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p74111411615"><a name="p74111411615"></a><a name="p74111411615"></a>DOWNLOAD_CHART_FROM_STORAGE_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p10411417168"><a name="p10411417168"></a><a name="p10411417168"></a>SVCSTG.CCECAM.5000116</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p15411419162"><a name="p15411419162"></a><a name="p15411419162"></a>Failed to download the template from a remote volume.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p3414415168"><a name="p3414415168"></a><a name="p3414415168"></a>-</p>
</td>
</tr>
<tr id="row1185572911116"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p10421142162"><a name="p10421142162"></a><a name="p10421142162"></a>SAVE_CHART_LOCAL_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p2423471616"><a name="p2423471616"></a><a name="p2423471616"></a>SVCSTG.CCECAM.5000117</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p942442168"><a name="p942442168"></a><a name="p942442168"></a>Failed to save the template file to a local directory.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p24234151619"><a name="p24234151619"></a><a name="p24234151619"></a>-</p>
</td>
</tr>
<tr id="row148551291612"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p18423461615"><a name="p18423461615"></a><a name="p18423461615"></a>PARSE_LOCAL_ARCHIVE_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p1042643164"><a name="p1042643164"></a><a name="p1042643164"></a>SVCSTG.CCECAM.5000120</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p1742184171614"><a name="p1742184171614"></a><a name="p1742184171614"></a>Failed to parse a local template file.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p10422413164"><a name="p10422413164"></a><a name="p10422413164"></a>-</p>
</td>
</tr>
<tr id="row14855182912119"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p24216412166"><a name="p24216412166"></a><a name="p24216412166"></a>INVALID_CHART_FILE_FORMAT</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p1642104151611"><a name="p1642104151611"></a><a name="p1642104151611"></a>SVCSTG.CCECAM.4000121</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p642544163"><a name="p642544163"></a><a name="p642544163"></a>The content of the template file is incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p74244151619"><a name="p74244151619"></a><a name="p74244151619"></a>-</p>
</td>
</tr>
<tr id="row148558291311"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p64354181612"><a name="p64354181612"></a><a name="p64354181612"></a>CHECK_STORAGE_ERROR</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p84318491617"><a name="p84318491617"></a><a name="p84318491617"></a>SVCSTG.CCECAM.5000122</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p1843348163"><a name="p1843348163"></a><a name="p1843348163"></a>The remote volume information is incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p16431341168"><a name="p16431341168"></a><a name="p16431341168"></a>-</p>
</td>
</tr>
<tr id="row128558291816"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p134318401611"><a name="p134318401611"></a><a name="p134318401611"></a>CHART_NAME_CONFLICT_WITH_OFFICIAL_CHARTS</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p5431640160"><a name="p5431640160"></a><a name="p5431640160"></a>SVCSTG.CCECAM.4090123</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p1243144161614"><a name="p1243144161614"></a><a name="p1243144161614"></a>The name of the template to be uploaded conflicts with the name of the official template.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p7431842167"><a name="p7431842167"></a><a name="p7431842167"></a>Change the name of the template to be uploaded.</p>
</td>
</tr>
<tr id="row2856182910110"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p144311410168"><a name="p144311410168"></a><a name="p144311410168"></a>DOWNLOAD_OFFICIAL_CHARTS_FORBIDDEN</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p144319441615"><a name="p144319441615"></a><a name="p144319441615"></a>SVCSTG.CCECAM.4030124</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p3431343161"><a name="p3431343161"></a><a name="p3431343161"></a>Official templates cannot be downloaded.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p444194141616"><a name="p444194141616"></a><a name="p444194141616"></a>-</p>
</td>
</tr>
<tr id="row1985692915112"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p544840167"><a name="p544840167"></a><a name="p544840167"></a>INVALID_RELEASE_NAME</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p11441145161"><a name="p11441145161"></a><a name="p11441145161"></a>SVCSTG.CCECAM.4000201</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p24410418165"><a name="p24410418165"></a><a name="p24410418165"></a>The name of the template-based application is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p11443412166"><a name="p11443412166"></a><a name="p11443412166"></a>-</p>
</td>
</tr>
<tr id="row138571729413"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p54411412165"><a name="p54411412165"></a><a name="p54411412165"></a>GET_CLUSTER_INFO_ERROR</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p114411461613"><a name="p114411461613"></a><a name="p114411461613"></a>SVCSTG.CCECAM.5000202</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p1144441169"><a name="p1144441169"></a><a name="p1144441169"></a>Failed to obtain the cluster information.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p9441412168"><a name="p9441412168"></a><a name="p9441412168"></a>-</p>
</td>
</tr>
<tr id="row148574297118"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p154474111617"><a name="p154474111617"></a><a name="p154474111617"></a>CREATE_HELM_CLIENT_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p844747163"><a name="p844747163"></a><a name="p844747163"></a>SVCSTG.CCECAM.5000203</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p144164141617"><a name="p144164141617"></a><a name="p144164141617"></a>Failed to create the template-based application client.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p104474191616"><a name="p104474191616"></a><a name="p104474191616"></a>-</p>
</td>
</tr>
<tr id="row158585296112"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p16456471610"><a name="p16456471610"></a><a name="p16456471610"></a>GET_RELEASE_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p94511417166"><a name="p94511417166"></a><a name="p94511417166"></a>SVCSTG.CCECAM.5000204</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p1746341163"><a name="p1746341163"></a><a name="p1746341163"></a>Failed to obtain the information about the installed template-based application.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p6461542163"><a name="p6461542163"></a><a name="p6461542163"></a>-</p>
</td>
</tr>
<tr id="row1685817294119"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p3461491617"><a name="p3461491617"></a><a name="p3461491617"></a>GET_RELEASE_HISTORY_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p9461949164"><a name="p9461949164"></a><a name="p9461949164"></a>SVCSTG.CCECAM.5000205</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p174694141610"><a name="p174694141610"></a><a name="p174694141610"></a>Failed to obtain the historical information about the installed template-based application.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p4469410164"><a name="p4469410164"></a><a name="p4469410164"></a>-</p>
</td>
</tr>
<tr id="row1285914299119"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p134614151611"><a name="p134614151611"></a><a name="p134614151611"></a>GET_RELEASE_LIST_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p184610441614"><a name="p184610441614"></a><a name="p184610441614"></a>SVCSTG.CCECAM.5000206</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p7466421619"><a name="p7466421619"></a><a name="p7466421619"></a>Failed to obtain the installed template-based application list.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p84610411166"><a name="p84610411166"></a><a name="p84610411166"></a>-</p>
</td>
</tr>
<tr id="row128591729413"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p24620414164"><a name="p24620414164"></a><a name="p24620414164"></a>FILTER_RELEASE_LIST_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p2469417162"><a name="p2469417162"></a><a name="p2469417162"></a>SVCSTG.CCECAM.5000207</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p114614417162"><a name="p114614417162"></a><a name="p114614417162"></a>Failed to filter the installed template-based application list.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p134715481616"><a name="p134715481616"></a><a name="p134715481616"></a>-</p>
</td>
</tr>
<tr id="row1685917291314"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p647741168"><a name="p647741168"></a><a name="p647741168"></a>CREATE_RELEASE_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p1347549164"><a name="p1347549164"></a><a name="p1347549164"></a>SVCSTG.CCECAM.5000208</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p16471843162"><a name="p16471843162"></a><a name="p16471843162"></a>Failed to create the template-based application.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p19472414160"><a name="p19472414160"></a><a name="p19472414160"></a>-</p>
</td>
</tr>
<tr id="row88604291710"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p74714417166"><a name="p74714417166"></a><a name="p74714417166"></a>DELETE_RELEASE_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p8477413161"><a name="p8477413161"></a><a name="p8477413161"></a>SVCSTG.CCECAM.5000209</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p547541163"><a name="p547541163"></a><a name="p547541163"></a>Failed to delete the template-based application.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p648194171619"><a name="p648194171619"></a><a name="p648194171619"></a>-</p>
</td>
</tr>
<tr id="row28609291816"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p3481144163"><a name="p3481144163"></a><a name="p3481144163"></a>UPDATE_RELEASE_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p1248846162"><a name="p1248846162"></a><a name="p1248846162"></a>SVCSTG.CCECAM.5000210</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p44810414168"><a name="p44810414168"></a><a name="p44810414168"></a>Failed to update the template-based application.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p124816451610"><a name="p124816451610"></a><a name="p124816451610"></a>-</p>
</td>
</tr>
<tr id="row158603299120"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p1948124101615"><a name="p1948124101615"></a><a name="p1948124101615"></a>ROLLBACK_RELEASE_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p1448134171617"><a name="p1448134171617"></a><a name="p1448134171617"></a>SVCSTG.CCECAM.5000211</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p154824191619"><a name="p154824191619"></a><a name="p154824191619"></a>Failed to roll back the template-based application.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p748144161615"><a name="p748144161615"></a><a name="p748144161615"></a>-</p>
</td>
</tr>
<tr id="row686120291915"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p184819481610"><a name="p184819481610"></a><a name="p184819481610"></a>CONVERT_RELEASE_RESPONSE_FAILED</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p9487471615"><a name="p9487471615"></a><a name="p9487471615"></a>SVCSTG.CCECAM.5000212</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p104817418164"><a name="p104817418164"></a><a name="p104817418164"></a>Failed to convert the template-based application information.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p0487412164"><a name="p0487412164"></a><a name="p0487412164"></a>-</p>
</td>
</tr>
<tr id="row13861192914111"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p114810412168"><a name="p114810412168"></a><a name="p114810412168"></a>RELEASE_NAME_ALREADY_EXISTED_ON_CLUSTER</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p14483451612"><a name="p14483451612"></a><a name="p14483451612"></a>SVCSTG.CCECAM.4090213</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p0491246163"><a name="p0491246163"></a><a name="p0491246163"></a>A template-based application with the same name has been deployed on the cluster.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p1449194171616"><a name="p1449194171616"></a><a name="p1449194171616"></a>Change the name of the template-based application to be deployed.</p>
</td>
</tr>
<tr id="row128617297112"><td class="cellrowborder" valign="top" width="32.95%" headers="mcps1.1.5.1.1 "><p id="p104914161614"><a name="p104914161614"></a><a name="p104914161614"></a>INVALID_UPDATE_ACTION</p>
</td>
<td class="cellrowborder" valign="top" width="20.04%" headers="mcps1.1.5.1.2 "><p id="p104904181613"><a name="p104904181613"></a><a name="p104904181613"></a>SVCSTG.CCECAM.4000214</p>
</td>
<td class="cellrowborder" valign="top" width="22.46%" headers="mcps1.1.5.1.3 "><p id="p18496491615"><a name="p18496491615"></a><a name="p18496491615"></a>The operation type of the template-based application is incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="24.55%" headers="mcps1.1.5.1.4 "><p id="p1449544162"><a name="p1449544162"></a><a name="p1449544162"></a>A template-based application can only be upgraded or rolled back.</p>
</td>
</tr>
</tbody>
</table>

