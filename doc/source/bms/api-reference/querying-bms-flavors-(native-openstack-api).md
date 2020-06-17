# Querying BMS Flavors \(Native OpenStack API\)<a name="EN-US_TOPIC_0053158684"></a>

## Function<a name="section57769674"></a>

This API is used to query BMS flavors.

## Constraints<a name="section60580832213029"></a>

The flavors you obtained using this API are all the flavors in the system. The flavors whose names starting with  **physical**  are BMS flavors and can be used to create BMSs.

## URI<a name="section50165025"></a>

GET /v2.1/\{project\_id\}/flavors/detail\{?minDisk=\{minDisk\}&minRam=\{minRam\}&sort\_key=\{sort\_key\}&sort\_dir=\{sort\_dir\}\}

[Table 1](#table1687344817416)  lists the parameters.

**Table  1**  Parameter description

<a name="table1687344817416"></a>
<table><thead align="left"><tr id="row138741548164116"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p5187119"><a name="p5187119"></a><a name="p5187119"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p17503500"><a name="p17503500"></a><a name="p17503500"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p8497414"><a name="p8497414"></a><a name="p8497414"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row28741048144119"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p51178607"><a name="p51178607"></a><a name="p51178607"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p51826478"><a name="p51826478"></a><a name="p51826478"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p37195178"><a name="p37195178"></a><a name="p37195178"></a>Specifies the project ID.</p>
<p id="p9141450142010"><a name="p9141450142010"></a><a name="p9141450142010"></a>For how to obtain the project ID, see <a href="https://docs.otc.t-systems.com/en-us/api/apiug/apig-en-api-180328009.html" target="_blank" rel="noopener noreferrer">Obtaining Required Information</a>.</p>
</td>
</tr>
</tbody>
</table>

[Table 2](#table1719300427)  lists the optional parameters that can be used to query BMS flavors.

**Table  2**  Optional parameters

<a name="table1719300427"></a>
<table><thead align="left"><tr id="row57253084215"><th class="cellrowborder" valign="top" width="20.830000000000002%" id="mcps1.2.5.1.1"><p id="p59978491115233"><a name="p59978491115233"></a><a name="p59978491115233"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="20.39%" id="mcps1.2.5.1.2"><p id="p15431544654"><a name="p15431544654"></a><a name="p15431544654"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="20.07%" id="mcps1.2.5.1.3"><p id="p26419641115233"><a name="p26419641115233"></a><a name="p26419641115233"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="38.71%" id="mcps1.2.5.1.4"><p id="p64181866115233"><a name="p64181866115233"></a><a name="p64181866115233"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row107363044215"><td class="cellrowborder" valign="top" width="20.830000000000002%" headers="mcps1.2.5.1.1 "><p id="p7618124412423"><a name="p7618124412423"></a><a name="p7618124412423"></a>minDisk</p>
</td>
<td class="cellrowborder" valign="top" width="20.39%" headers="mcps1.2.5.1.2 "><p id="p14421144857"><a name="p14421144857"></a><a name="p14421144857"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20.07%" headers="mcps1.2.5.1.3 "><p id="p26202446424"><a name="p26202446424"></a><a name="p26202446424"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="38.71%" headers="mcps1.2.5.1.4 "><p id="p116242044134216"><a name="p116242044134216"></a><a name="p116242044134216"></a>Specifies the minimum disk size in GB. Only the BMSs with a disk size greater than or equal to the minimum size can be queried.</p>
</td>
</tr>
<tr id="row17730303422"><td class="cellrowborder" valign="top" width="20.830000000000002%" headers="mcps1.2.5.1.1 "><p id="p1562994419427"><a name="p1562994419427"></a><a name="p1562994419427"></a>minRam</p>
</td>
<td class="cellrowborder" valign="top" width="20.39%" headers="mcps1.2.5.1.2 "><p id="p104224419515"><a name="p104224419515"></a><a name="p104224419515"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20.07%" headers="mcps1.2.5.1.3 "><p id="p146323449428"><a name="p146323449428"></a><a name="p146323449428"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="38.71%" headers="mcps1.2.5.1.4 "><p id="p863714412422"><a name="p863714412422"></a><a name="p863714412422"></a>Specifies the minimum memory size in MB. Only the BMSs with the memory size greater than or equal to the minimum size can be queried.</p>
</td>
</tr>
<tr id="row1673103013428"><td class="cellrowborder" valign="top" width="20.830000000000002%" headers="mcps1.2.5.1.1 "><p id="p12651144417421"><a name="p12651144417421"></a><a name="p12651144417421"></a>sort_key</p>
</td>
<td class="cellrowborder" valign="top" width="20.39%" headers="mcps1.2.5.1.2 "><p id="p1040164413513"><a name="p1040164413513"></a><a name="p1040164413513"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20.07%" headers="mcps1.2.5.1.3 "><p id="p196558447427"><a name="p196558447427"></a><a name="p196558447427"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="38.71%" headers="mcps1.2.5.1.4 "><p id="p366084404210"><a name="p366084404210"></a><a name="p366084404210"></a>Specifies the sorting field. The default value is <strong id="b842352706101459"><a name="b842352706101459"></a><a name="b842352706101459"></a>flavorid</strong>. The value of this parameter can also be <strong id="b842352706101549"><a name="b842352706101549"></a><a name="b842352706101549"></a>name</strong>, <strong id="b842352706101555"><a name="b842352706101555"></a><a name="b842352706101555"></a>memory_mb</strong>, <strong id="b842352706101622"><a name="b842352706101622"></a><a name="b842352706101622"></a>vcpus</strong>, <strong id="b842352706101625"><a name="b842352706101625"></a><a name="b842352706101625"></a>root_gb</strong>, or <strong id="b84235270610301"><a name="b84235270610301"></a><a name="b84235270610301"></a>flavorid</strong>.</p>
</td>
</tr>
<tr id="row87303017423"><td class="cellrowborder" valign="top" width="20.830000000000002%" headers="mcps1.2.5.1.1 "><p id="p16663174412421"><a name="p16663174412421"></a><a name="p16663174412421"></a>sort_dir</p>
</td>
<td class="cellrowborder" valign="top" width="20.39%" headers="mcps1.2.5.1.2 "><p id="p104012441155"><a name="p104012441155"></a><a name="p104012441155"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20.07%" headers="mcps1.2.5.1.3 "><p id="p466510447425"><a name="p466510447425"></a><a name="p466510447425"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="38.71%" headers="mcps1.2.5.1.4 "><p id="p381417538211"><a name="p381417538211"></a><a name="p381417538211"></a>Specifies the sorting of BMS flavors.</p>
<p id="p19672104424217"><a name="p19672104424217"></a><a name="p19672104424217"></a>The value can be <strong id="b114969111578"><a name="b114969111578"></a><a name="b114969111578"></a>asc</strong> or <strong id="b6657414475"><a name="b6657414475"></a><a name="b6657414475"></a>desc</strong>, and is <strong id="b1815251272"><a name="b1815251272"></a><a name="b1815251272"></a>asc</strong> by default.</p>
</td>
</tr>
</tbody>
</table>

## Request Message<a name="section48832041"></a>

-   Request parameters

    None

-   Example request
    -   With no optional parameter

        ```
        GET https://{ECS Endpoint}/v2.1/bbf1946d374b44a0a2a95533562ba954/flavors/detail
        ```

    -   With an optional parameter

        ```
        GET https://{ECS Endpoint}/v2.1/bbf1946d374b44a0a2a95533562ba954/flavors/detail?minDisk=3725
        ```

    -   With multiple optional parameters

        ```
        GET https://{ECS Endpoint}/v2.1/bbf1946d374b44a0a2a95533562ba954/flavors/detail?minDisk=3725&is_public=true
        ```



## Response Message<a name="section36835188"></a>

-   Response parameters

    <a name="table23477058"></a>
    <table><thead align="left"><tr id="row2792905"><th class="cellrowborder" valign="top" width="23.94%" id="mcps1.1.4.1.1"><p id="p151621239131213"><a name="p151621239131213"></a><a name="p151621239131213"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="25.09%" id="mcps1.1.4.1.2"><p id="p17165183912124"><a name="p17165183912124"></a><a name="p17165183912124"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="50.970000000000006%" id="mcps1.1.4.1.3"><p id="p716920393129"><a name="p716920393129"></a><a name="p716920393129"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row9994955"><td class="cellrowborder" valign="top" width="23.94%" headers="mcps1.1.4.1.1 "><p id="p4284989"><a name="p4284989"></a><a name="p4284989"></a>flavors</p>
    </td>
    <td class="cellrowborder" valign="top" width="25.09%" headers="mcps1.1.4.1.2 "><p id="p62312200"><a name="p62312200"></a><a name="p62312200"></a>Array of objects</p>
    </td>
    <td class="cellrowborder" valign="top" width="50.970000000000006%" headers="mcps1.1.4.1.3 "><p id="p60002101"><a name="p60002101"></a><a name="p60002101"></a>Specifies <span id="text18472201045814"><a name="text18472201045814"></a><a name="text18472201045814"></a>BMS</span><span id="text547221045820"><a name="text547221045820"></a><a name="text547221045820"></a></span> flavors. For details, see <a href="#table13194498">Table 3</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

    **Table  3** **flavors**  field data structure description

    <a name="table13194498"></a>
    <table><thead align="left"><tr id="row35873632"><th class="cellrowborder" valign="top" width="24.22%" id="mcps1.2.4.1.1"><p id="p1934639181313"><a name="p1934639181313"></a><a name="p1934639181313"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="24.46%" id="mcps1.2.4.1.2"><p id="p1134716921317"><a name="p1134716921317"></a><a name="p1134716921317"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="51.32%" id="mcps1.2.4.1.3"><p id="p535259131314"><a name="p535259131314"></a><a name="p535259131314"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row15349251"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p35329809"><a name="p35329809"></a><a name="p35329809"></a>id</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p24536113173145"><a name="p24536113173145"></a><a name="p24536113173145"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p56261663"><a name="p56261663"></a><a name="p56261663"></a>Specifies the <span id="text56903119317"><a name="text56903119317"></a><a name="text56903119317"></a>BMS</span><span id="text186911411031"><a name="text186911411031"></a><a name="text186911411031"></a></span> flavor ID.</p>
    </td>
    </tr>
    <tr id="row36592919"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p11236435"><a name="p11236435"></a><a name="p11236435"></a>name</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p54383891173145"><a name="p54383891173145"></a><a name="p54383891173145"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p61525259"><a name="p61525259"></a><a name="p61525259"></a>Specifies the <span id="text99412167310"><a name="text99412167310"></a><a name="text99412167310"></a>BMS</span><span id="text99425161931"><a name="text99425161931"></a><a name="text99425161931"></a></span> flavor name.</p>
    </td>
    </tr>
    <tr id="row16856419"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p23192694"><a name="p23192694"></a><a name="p23192694"></a>vcpus</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p61992247173145"><a name="p61992247173145"></a><a name="p61992247173145"></a>Integer</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p60827539"><a name="p60827539"></a><a name="p60827539"></a>Specifies the number of CPU cores in the <span id="text456310281232"><a name="text456310281232"></a><a name="text456310281232"></a>BMS</span><span id="text956414289317"><a name="text956414289317"></a><a name="text956414289317"></a></span> flavor.</p>
    </td>
    </tr>
    <tr id="row3097644510336"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p3929432310349"><a name="p3929432310349"></a><a name="p3929432310349"></a>ram</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p51423198173145"><a name="p51423198173145"></a><a name="p51423198173145"></a>Integer</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p154673810349"><a name="p154673810349"></a><a name="p154673810349"></a>Specifies the memory size (MB) in the <span id="text111996335313"><a name="text111996335313"></a><a name="text111996335313"></a>BMS</span><span id="text1020119331138"><a name="text1020119331138"></a><a name="text1020119331138"></a></span> flavor.</p>
    </td>
    </tr>
    <tr id="row10576944"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p51426113"><a name="p51426113"></a><a name="p51426113"></a>disk</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p31344710173145"><a name="p31344710173145"></a><a name="p31344710173145"></a>Integer</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p19756352"><a name="p19756352"></a><a name="p19756352"></a>Specifies the disk size (GB) in the <span id="text495612955816"><a name="text495612955816"></a><a name="text495612955816"></a>BMS</span><span id="text1495610298587"><a name="text1495610298587"></a><a name="text1495610298587"></a></span> flavor.</p>
    </td>
    </tr>
    <tr id="row56760689"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p34213098"><a name="p34213098"></a><a name="p34213098"></a>swap</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p31087024173145"><a name="p31087024173145"></a><a name="p31087024173145"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p3906895110328"><a name="p3906895110328"></a><a name="p3906895110328"></a>This is a reserved attribute.</p>
    </td>
    </tr>
    <tr id="row56925253"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p47542785"><a name="p47542785"></a><a name="p47542785"></a>OS-FLV-EXT-DATA:ephemeral</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p18132829173145"><a name="p18132829173145"></a><a name="p18132829173145"></a>Integer</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p2710719510328"><a name="p2710719510328"></a><a name="p2710719510328"></a>This is a reserved attribute.</p>
    </td>
    </tr>
    <tr id="row44806966"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p5485596"><a name="p5485596"></a><a name="p5485596"></a>OS-FLV-DISABLED:disabled</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p52585611173145"><a name="p52585611173145"></a><a name="p52585611173145"></a>Boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p3113915110328"><a name="p3113915110328"></a><a name="p3113915110328"></a>This is a reserved attribute.</p>
    </td>
    </tr>
    <tr id="row42184651"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p61513540"><a name="p61513540"></a><a name="p61513540"></a>rxtx_factor</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p7527547173145"><a name="p7527547173145"></a><a name="p7527547173145"></a>Float</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p1764564010328"><a name="p1764564010328"></a><a name="p1764564010328"></a>This is a reserved attribute.</p>
    </td>
    </tr>
    <tr id="row51313205"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p62728917"><a name="p62728917"></a><a name="p62728917"></a>os-flavor-access:is_public</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p43117912173145"><a name="p43117912173145"></a><a name="p43117912173145"></a>Boolean</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p3503996211722"><a name="p3503996211722"></a><a name="p3503996211722"></a>This is a reserved attribute.</p>
    </td>
    </tr>
    <tr id="row2047803919452"><td class="cellrowborder" valign="top" width="24.22%" headers="mcps1.2.4.1.1 "><p id="p6509154919455"><a name="p6509154919455"></a><a name="p6509154919455"></a>links</p>
    </td>
    <td class="cellrowborder" valign="top" width="24.46%" headers="mcps1.2.4.1.2 "><p id="p3792414219455"><a name="p3792414219455"></a><a name="p3792414219455"></a>Array of objects</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.32%" headers="mcps1.2.4.1.3 "><p id="p6495712119455"><a name="p6495712119455"></a><a name="p6495712119455"></a>Specifies shortcut links of the BMS flavor. For details, see <a href="#table15913898194628">Table 4</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

    **Table  4** **links**  field data structure description

    <a name="table15913898194628"></a>
    <table><thead align="left"><tr id="row37608132194628"><th class="cellrowborder" valign="top" width="23.1%" id="mcps1.2.4.1.1"><p id="p1387423241319"><a name="p1387423241319"></a><a name="p1387423241319"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="25.790000000000003%" id="mcps1.2.4.1.2"><p id="p1487693221320"><a name="p1487693221320"></a><a name="p1487693221320"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="51.11%" id="mcps1.2.4.1.3"><p id="p187911326136"><a name="p187911326136"></a><a name="p187911326136"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row17692319194628"><td class="cellrowborder" valign="top" width="23.1%" headers="mcps1.2.4.1.1 "><p id="p23791739194628"><a name="p23791739194628"></a><a name="p23791739194628"></a>rel</p>
    </td>
    <td class="cellrowborder" valign="top" width="25.790000000000003%" headers="mcps1.2.4.1.2 "><p id="p48082703194628"><a name="p48082703194628"></a><a name="p48082703194628"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.11%" headers="mcps1.2.4.1.3 "><p id="p2384900194628"><a name="p2384900194628"></a><a name="p2384900194628"></a>Specifies the shortcut link marker name.</p>
    <a name="ul207311644172510"></a><a name="ul207311644172510"></a><ul id="ul207311644172510"><li><strong id="en-us_topic_0131326852_b320113110516"><a name="en-us_topic_0131326852_b320113110516"></a><a name="en-us_topic_0131326852_b320113110516"></a>self</strong>: resource link that contains the version number. It is used when immediate tracing is required.</li><li><strong id="en-us_topic_0131326852_b84171947711"><a name="en-us_topic_0131326852_b84171947711"></a><a name="en-us_topic_0131326852_b84171947711"></a>bookmark</strong>: resource link that can be stored for a long time.</li></ul>
    </td>
    </tr>
    <tr id="row21464106194628"><td class="cellrowborder" valign="top" width="23.1%" headers="mcps1.2.4.1.1 "><p id="p60871059194628"><a name="p60871059194628"></a><a name="p60871059194628"></a>href</p>
    </td>
    <td class="cellrowborder" valign="top" width="25.790000000000003%" headers="mcps1.2.4.1.2 "><p id="p31608752194628"><a name="p31608752194628"></a><a name="p31608752194628"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="51.11%" headers="mcps1.2.4.1.3 "><p id="p10172138194628"><a name="p10172138194628"></a><a name="p10172138194628"></a>Specifies the corresponding shortcut link.</p>
    </td>
    </tr>
    </tbody>
    </table>


-   Example response

    ```
    {
        "flavors": [
            {
                "name": "physical.o2.medium",
                "links": [
                    {
                        "href": "https://openstack.example.com/v2/c685484a8cc2416b97260938705deb65/flavors/physical.o2.medium",
                        "rel": "self"
                    },
                    {
                        "href": "https://openstack.example.com/c685484a8cc2416b97260938705deb65/flavors/physical.o2.medium",
                        "rel": "bookmark"
                     }
                ],
                "ram": 321725,
                "OS-FLV-DISABLED:disabled": false,
                "vcpus": 56,
                "swap": "",
                "os-flavor-access:is_public": true,
                "rxtx_factor": 1,
                "OS-FLV-EXT-DATA:ephemeral": 0,
                "disk": 3725,
                "id": "physical.o2.medium"
            }
        ]
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

