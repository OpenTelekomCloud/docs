# Creating a Namespace<a name="cce_02_0050"></a>

## Function<a name="s892e02bfa26441fc9c5f37e55ee37eef"></a>

This API is used to create a Namespace.

## URI<a name="scf08ff5a2d1b418baa3ed1716ca70ed1"></a>

POST /api/v1/namespaces

[Table 1](#en-us_topic_0079615062_table60720217)  describes the parameters of this API.

**Table  1**  Parameter description

<a name="en-us_topic_0079615062_table60720217"></a>
<table><thead align="left"><tr id="en-us_topic_0079615062_row32267243"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079615062_p63509856"><a name="en-us_topic_0079615062_p63509856"></a><a name="en-us_topic_0079615062_p63509856"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p3589811321059"><a name="p3589811321059"></a><a name="p3589811321059"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p2206602921059"><a name="p2206602921059"></a><a name="p2206602921059"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615062_row9439626"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079615062_p26412257"><a name="en-us_topic_0079615062_p26412257"></a><a name="en-us_topic_0079615062_p26412257"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079615062_p59018101"><a name="en-us_topic_0079615062_p59018101"></a><a name="en-us_topic_0079615062_p59018101"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079615062_p15736877"><a name="en-us_topic_0079615062_p15736877"></a><a name="en-us_topic_0079615062_p15736877"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="en-us_topic_0079615062_ref458675483"></a>

**Request parameters**:

[Table 2](#en-us_topic_0079615062_ref458759029)  describes the request parameters.

**Table  2**  Parameter description

<a name="en-us_topic_0079615062_ref458759029"></a>
<table><thead align="left"><tr id="en-us_topic_0079615062_row61660876"><th class="cellrowborder" valign="top" width="21.8%" id="mcps1.2.5.1.1"><p id="en-us_topic_0079615062_p28475059"><a name="en-us_topic_0079615062_p28475059"></a><a name="en-us_topic_0079615062_p28475059"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="19.17%" id="mcps1.2.5.1.2"><p id="p4475307021059"><a name="p4475307021059"></a><a name="p4475307021059"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="19.74%" id="mcps1.2.5.1.3"><p id="p112003821059"><a name="p112003821059"></a><a name="p112003821059"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="39.290000000000006%" id="mcps1.2.5.1.4"><p id="p2361423021059"><a name="p2361423021059"></a><a name="p2361423021059"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615062_row40656116"><td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0079615062_p4811061"><a name="en-us_topic_0079615062_p4811061"></a><a name="en-us_topic_0079615062_p4811061"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0079615062_p54151655"><a name="en-us_topic_0079615062_p54151655"></a><a name="en-us_topic_0079615062_p54151655"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="19.74%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0079615062_p24207921"><a name="en-us_topic_0079615062_p24207921"></a><a name="en-us_topic_0079615062_p24207921"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0079615062_p14684604"><a name="en-us_topic_0079615062_p14684604"></a><a name="en-us_topic_0079615062_p14684604"></a>kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase.</p>
<p id="en-us_topic_0079615062_p65052577"><a name="en-us_topic_0079615062_p65052577"></a><a name="en-us_topic_0079615062_p65052577"></a>The value of this parameter is <strong id="b48602288"><a name="b48602288"></a><a name="b48602288"></a>Namespace</strong>.</p>
</td>
</tr>
<tr id="en-us_topic_0079615062_row34767408"><td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0079615062_p64696659"><a name="en-us_topic_0079615062_p64696659"></a><a name="en-us_topic_0079615062_p64696659"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0079615062_p5938035"><a name="en-us_topic_0079615062_p5938035"></a><a name="en-us_topic_0079615062_p5938035"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="19.74%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0079615062_p11218807"><a name="en-us_topic_0079615062_p11218807"></a><a name="en-us_topic_0079615062_p11218807"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0079615062_p36308168"><a name="en-us_topic_0079615062_p36308168"></a><a name="en-us_topic_0079615062_p36308168"></a>apiVersion defines the versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
<p id="en-us_topic_0079615062_p58338056"><a name="en-us_topic_0079615062_p58338056"></a><a name="en-us_topic_0079615062_p58338056"></a>The value of this parameter is <strong id="b55280461"><a name="b55280461"></a><a name="b55280461"></a>v1</strong>.</p>
</td>
</tr>
<tr id="en-us_topic_0079615062_row27762102"><td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0079615062_p34137829"><a name="en-us_topic_0079615062_p34137829"></a><a name="en-us_topic_0079615062_p34137829"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0079615062_p13700797"><a name="en-us_topic_0079615062_p13700797"></a><a name="en-us_topic_0079615062_p13700797"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="19.74%" headers="mcps1.2.5.1.3 "><p id="a3467669217d84b4c81c113d5e2da8569"><a name="a3467669217d84b4c81c113d5e2da8569"></a><a name="a3467669217d84b4c81c113d5e2da8569"></a><a href="data-structure-of-request-parameters.md#en-us_topic_0079614925_table47756489">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0079615062_p32162181"><a name="en-us_topic_0079615062_p32162181"></a><a name="en-us_topic_0079615062_p32162181"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079615062_row21024178"><td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0079615062_p25236858"><a name="en-us_topic_0079615062_p25236858"></a><a name="en-us_topic_0079615062_p25236858"></a>spec</p>
</td>
<td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0079615062_p30919631"><a name="en-us_topic_0079615062_p30919631"></a><a name="en-us_topic_0079615062_p30919631"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19.74%" headers="mcps1.2.5.1.3 "><p id="a06e8700df468433aa540a2f15c58b358"><a name="a06e8700df468433aa540a2f15c58b358"></a><a name="a06e8700df468433aa540a2f15c58b358"></a><a href="#en-us_topic_0079615062_table19390540">spec</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0079615062_p60714046"><a name="en-us_topic_0079615062_p60714046"></a><a name="en-us_topic_0079615062_p60714046"></a>-</p>
</td>
</tr>
<tr id="en-us_topic_0079615062_row9555503"><td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0079615062_p35798250"><a name="en-us_topic_0079615062_p35798250"></a><a name="en-us_topic_0079615062_p35798250"></a>status</p>
</td>
<td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0079615062_p13977142"><a name="en-us_topic_0079615062_p13977142"></a><a name="en-us_topic_0079615062_p13977142"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19.74%" headers="mcps1.2.5.1.3 "><p id="a3336b15d7dc74a08a73e99cd75f4058f"><a name="a3336b15d7dc74a08a73e99cd75f4058f"></a><a name="a3336b15d7dc74a08a73e99cd75f4058f"></a><a href="#en-us_topic_0079615062_table40297137">status</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0079615062_p33323423"><a name="en-us_topic_0079615062_p33323423"></a><a name="en-us_topic_0079615062_p33323423"></a>-</p>
</td>
</tr>
</tbody>
</table>

**Table  3**  Data structure of the spec field

<a name="en-us_topic_0079615062_table19390540"></a>
<table><thead align="left"><tr id="en-us_topic_0079615062_row42478134"><th class="cellrowborder" valign="top" width="21.8%" id="mcps1.2.5.1.1"><p id="en-us_topic_0079615062_p18176840"><a name="en-us_topic_0079615062_p18176840"></a><a name="en-us_topic_0079615062_p18176840"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="19.17%" id="mcps1.2.5.1.2"><p id="p6641927621059"><a name="p6641927621059"></a><a name="p6641927621059"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="19.74%" id="mcps1.2.5.1.3"><p id="p1125227721059"><a name="p1125227721059"></a><a name="p1125227721059"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="39.290000000000006%" id="mcps1.2.5.1.4"><p id="p3901927921059"><a name="p3901927921059"></a><a name="p3901927921059"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615062_row9967070"><td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0079615062_p2026335"><a name="en-us_topic_0079615062_p2026335"></a><a name="en-us_topic_0079615062_p2026335"></a>finalizers</p>
</td>
<td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0079615062_p29915412"><a name="en-us_topic_0079615062_p29915412"></a><a name="en-us_topic_0079615062_p29915412"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19.74%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0079615062_p7229285"><a name="en-us_topic_0079615062_p7229285"></a><a name="en-us_topic_0079615062_p7229285"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0079615062_p48701244"><a name="en-us_topic_0079615062_p48701244"></a><a name="en-us_topic_0079615062_p48701244"></a>finalizers is an opaque list of values that must be empty to permanently remove object from storage.</p>
</td>
</tr>
</tbody>
</table>

**Table  4**  Data structure of the status field

<a name="en-us_topic_0079615062_table40297137"></a>
<table><thead align="left"><tr id="en-us_topic_0079615062_row62991470"><th class="cellrowborder" valign="top" width="21.8%" id="mcps1.2.5.1.1"><p id="en-us_topic_0079615062_p2035480"><a name="en-us_topic_0079615062_p2035480"></a><a name="en-us_topic_0079615062_p2035480"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="19.17%" id="mcps1.2.5.1.2"><p id="p935719621059"><a name="p935719621059"></a><a name="p935719621059"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="19.74%" id="mcps1.2.5.1.3"><p id="p1973538721059"><a name="p1973538721059"></a><a name="p1973538721059"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="39.290000000000006%" id="mcps1.2.5.1.4"><p id="p5506250321059"><a name="p5506250321059"></a><a name="p5506250321059"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615062_row20002757"><td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0079615062_p9610617"><a name="en-us_topic_0079615062_p9610617"></a><a name="en-us_topic_0079615062_p9610617"></a>phase</p>
</td>
<td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0079615062_p40262542"><a name="en-us_topic_0079615062_p40262542"></a><a name="en-us_topic_0079615062_p40262542"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19.74%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0079615062_p40040492"><a name="en-us_topic_0079615062_p40040492"></a><a name="en-us_topic_0079615062_p40040492"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0079615062_p22054394"><a name="en-us_topic_0079615062_p22054394"></a><a name="en-us_topic_0079615062_p22054394"></a>phase is the current lifecycle phase of the namespace.</p>
</td>
</tr>
</tbody>
</table>

**Example request**:

```
{ 
   "apiVersion":"v1", 
   "kind": "Namespace", 
   "metadata": { 
     "name": "development", 
     "labels": { 
       "name": "development" 
     } 
   }, 
   "spec": { 
     "finalizers": ["kubernetes"] 
   }, 
   "status": { 
     "phase": "Active" 
   } 
 }
```

## Response<a name="sc0e449fc74ae4c4a8a41deb65e63f4f9"></a>

**Response parameters**:

For the description about response parameters, see the parameter description in  [Request](#en-us_topic_0079615062_ref458675483).

**Example response**:

```
{ 
   "kind": "Namespace", 
   "apiVersion": "v1", 
   "metadata": { 
     "name": "development", 
     "selfLink": "/api/v1/namespaces/development", 
     "uid": "c98a9a98-595c-11e6-b444-286ed488fafe", 
     "resourceVersion": "16578", 
   "creationTimestamp": "2016-08-03T09:29:33Z", 
     "labels": { 
       "name": "development" 
     } 
   }, 
   "spec": { 
     "finalizers": [ 
       "kubernetes" 
     ] 
   }, 
   "status": { 
     "phase": "Active" 
   } 
 }
```

## Status Code<a name="sbb5000c5c0ba41d9aee6b95e8e02c0ce"></a>

[Table 5](#en-us_topic_0079615062_table27129916)  describes the status code of this API.

**Table  5**  Status code

<a name="en-us_topic_0079615062_table27129916"></a>
<table><thead align="left"><tr id="en-us_topic_0079615062_row7162954"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p3042097021059"><a name="p3042097021059"></a><a name="p3042097021059"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p4817954021059"><a name="p4817954021059"></a><a name="p4817954021059"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615062_row4477025"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="en-us_topic_0079615062_p27094719"><a name="en-us_topic_0079615062_p27094719"></a><a name="en-us_topic_0079615062_p27094719"></a>201</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="en-us_topic_0079615062_p47188597"><a name="en-us_topic_0079615062_p47188597"></a><a name="en-us_topic_0079615062_p47188597"></a>This operation succeeds, and a Namespace resource object is returned.</p>
</td>
</tr>
</tbody>
</table>

For the description about status codes, see section  [Status Code](status-code.md).

