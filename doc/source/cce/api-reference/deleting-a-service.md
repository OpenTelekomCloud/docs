# Deleting a Service<a name="cce_02_0026"></a>

## Function<a name="se5309007813b47538be7080cd63898e3"></a>

This API is used to delete a Service object.

## URI<a name="s6d0d073ca7cd41c79bd61a816536f9a2"></a>

DELETE /api/v1/namespaces/\{namespace\}/services/\{name\}

[Table 1](#en-us_topic_0079615016_table17955773)  describes the parameters of this API.

**Table  1**  Parameter description

<a name="en-us_topic_0079615016_table17955773"></a>
<table><thead align="left"><tr id="en-us_topic_0079615016_row34849842"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079615016_p4264914"><a name="en-us_topic_0079615016_p4264914"></a><a name="en-us_topic_0079615016_p4264914"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p47001612205713"><a name="p47001612205713"></a><a name="p47001612205713"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p49034188205713"><a name="p49034188205713"></a><a name="p49034188205713"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615016_row15472413"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079615016_p45305951"><a name="en-us_topic_0079615016_p45305951"></a><a name="en-us_topic_0079615016_p45305951"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079615016_p45903438"><a name="en-us_topic_0079615016_p45903438"></a><a name="en-us_topic_0079615016_p45903438"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079615016_p27190993"><a name="en-us_topic_0079615016_p27190993"></a><a name="en-us_topic_0079615016_p27190993"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
<tr id="en-us_topic_0079615016_row43392350"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079615016_p25119451"><a name="en-us_topic_0079615016_p25119451"></a><a name="en-us_topic_0079615016_p25119451"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079615016_p21409632"><a name="en-us_topic_0079615016_p21409632"></a><a name="en-us_topic_0079615016_p21409632"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079615016_p56458646"><a name="en-us_topic_0079615016_p56458646"></a><a name="en-us_topic_0079615016_p56458646"></a>Object name and auth scope, such as for teams and projects.</p>
</td>
</tr>
<tr id="en-us_topic_0079615016_row38365771"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079615016_p20619724"><a name="en-us_topic_0079615016_p20619724"></a><a name="en-us_topic_0079615016_p20619724"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079615016_p59584979"><a name="en-us_topic_0079615016_p59584979"></a><a name="en-us_topic_0079615016_p59584979"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079615016_p61653957"><a name="en-us_topic_0079615016_p61653957"></a><a name="en-us_topic_0079615016_p61653957"></a>Name of the Service.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="s716a126cd0214f9eac118df493501969"></a>

N/A

## Response<a name="s2203b49907514457834d6215429d3135"></a>

**Response parameters:**

For the description about response parameters, see  [Table 2](deleting-a-secret.md#table13766144711235).

**Example response:**

```
{ 
   "kind": "Status", 
   "apiVersion": "v1", 
   "metadata": {}, 
   "status": "Success", 
   "code": 200 
 }
```

## Status Code<a name="s10d425dd6e6d43a394ec0cd15cf7b233"></a>

[Table 2](#en-us_topic_0079615016_ref458764468)  describes the status code of this API.

**Table  2**  Status code

<a name="en-us_topic_0079615016_ref458764468"></a>
<table><thead align="left"><tr id="en-us_topic_0079615016_row40325647"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p25374999205713"><a name="p25374999205713"></a><a name="p25374999205713"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p42109061205713"><a name="p42109061205713"></a><a name="p42109061205713"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615016_row23578293"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="en-us_topic_0079615016_p30793598"><a name="en-us_topic_0079615016_p30793598"></a><a name="en-us_topic_0079615016_p30793598"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="en-us_topic_0079615016_p11253479"><a name="en-us_topic_0079615016_p11253479"></a><a name="en-us_topic_0079615016_p11253479"></a>Delete a Service resource object successfully.</p>
</td>
</tr>
</tbody>
</table>

For the description about status codes, see section  [Status Code](status-code.md).

