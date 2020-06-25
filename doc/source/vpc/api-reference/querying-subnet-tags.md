# Querying Subnet Tags<a name="subnet_tag_0002"></a>

## Function<a name="section14965143712214"></a>

This API is used to query tags of a specified subnet.

## URI<a name="section6965123722113"></a>

GET /v2.0/\{project\_id\}/subnets/\{subnet\_id\}/tags

[Table 1](#table27380479)  describes the parameters.

**Table  1**  Parameter description

<a name="table27380479"></a>
<table><thead align="left"><tr id="row28751554"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="p47174532"><a name="p47174532"></a><a name="p47174532"></a><strong id="b1153619238"><a name="b1153619238"></a><a name="b1153619238"></a>Name</strong></p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p63040734"><a name="p63040734"></a><a name="p63040734"></a><strong id="b51512016310"><a name="b51512016310"></a><a name="b51512016310"></a>Mandatory</strong></p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p6025849"><a name="p6025849"></a><a name="p6025849"></a><strong id="b49307204316"><a name="b49307204316"></a><a name="b49307204316"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row18331773"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p8478608"><a name="p8478608"></a><a name="p8478608"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p15678685"><a name="p15678685"></a><a name="p15678685"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p10487112"><a name="p10487112"></a><a name="p10487112"></a>Specifies the project ID. </p>
</td>
</tr>
<tr id="row21254748"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="p43913021"><a name="p43913021"></a><a name="p43913021"></a>subnet_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="p184914"><a name="p184914"></a><a name="p184914"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="p14978051"><a name="p14978051"></a><a name="p14978051"></a>Specifies the subnet ID, which uniquely identifies the subnet.</p>
</td>
</tr>
</tbody>
</table>

## Request Message<a name="section6971143716213"></a>

Request parameter

None

Example request

```
GET https://{Endpoint}/v2.0/{project_id}/subnets/{subnet_id}/tags
```

## Response Message<a name="section1297213732115"></a>

Response parameter

**Table  2**  Response parameter

<a name="table697233732118"></a>
<table><thead align="left"><tr id="row191823822110"><th class="cellrowborder" valign="top" width="13.18868113188681%" id="mcps1.2.4.1.1"><p id="p1818138132113"><a name="p1818138132113"></a><a name="p1818138132113"></a><strong id="b842352706193648"><a name="b842352706193648"></a><a name="b842352706193648"></a>Parameter</strong></p>
</th>
<th class="cellrowborder" valign="top" width="21.977802219778024%" id="mcps1.2.4.1.2"><p id="p2018133872118"><a name="p2018133872118"></a><a name="p2018133872118"></a><strong id="b842352706193653"><a name="b842352706193653"></a><a name="b842352706193653"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="64.83351664833516%" id="mcps1.2.4.1.3"><p id="p1181438152116"><a name="p1181438152116"></a><a name="p1181438152116"></a><strong id="b8423527061645"><a name="b8423527061645"></a><a name="b8423527061645"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row118173820215"><td class="cellrowborder" valign="top" width="13.18868113188681%" headers="mcps1.2.4.1.1 "><p id="p101853892115"><a name="p101853892115"></a><a name="p101853892115"></a>tags</p>
</td>
<td class="cellrowborder" valign="top" width="21.977802219778024%" headers="mcps1.2.4.1.2 "><p id="p1181438182118"><a name="p1181438182118"></a><a name="p1181438182118"></a>Array of <a href="#table13242848193719">tag</a> objects</p>
</td>
<td class="cellrowborder" valign="top" width="64.83351664833516%" headers="mcps1.2.4.1.3 "><p id="p8181038162110"><a name="p8181038162110"></a><a name="p8181038162110"></a>Specifies the <strong id="b132294813316"><a name="b132294813316"></a><a name="b132294813316"></a>tag</strong> object list. For details, see <a href="#table13242848193719">Table 3</a>.</p>
</td>
</tr>
</tbody>
</table>

**Table  3** **tag**  objects

<a name="table13242848193719"></a>
<table><thead align="left"><tr id="row13343144812379"><th class="cellrowborder" valign="top" width="17.46%" id="mcps1.2.4.1.1"><p id="p15343174853715"><a name="p15343174853715"></a><a name="p15343174853715"></a><strong id="b11111175211311"><a name="b11111175211311"></a><a name="b11111175211311"></a>Attribute</strong></p>
</th>
<th class="cellrowborder" valign="top" width="20.84%" id="mcps1.2.4.1.2"><p id="p13431648163716"><a name="p13431648163716"></a><a name="p13431648163716"></a><strong id="b14102175512311"><a name="b14102175512311"></a><a name="b14102175512311"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="61.7%" id="mcps1.2.4.1.3"><p id="p11344748183719"><a name="p11344748183719"></a><a name="p11344748183719"></a><strong id="b19423568318"><a name="b19423568318"></a><a name="b19423568318"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row103449487379"><td class="cellrowborder" valign="top" width="17.46%" headers="mcps1.2.4.1.1 "><p id="p183469482373"><a name="p183469482373"></a><a name="p183469482373"></a>key</p>
</td>
<td class="cellrowborder" valign="top" width="20.84%" headers="mcps1.2.4.1.2 "><p id="p1434684863710"><a name="p1434684863710"></a><a name="p1434684863710"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="61.7%" headers="mcps1.2.4.1.3 "><a name="en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul2321196023222"></a><a name="en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul2321196023222"></a><ul id="en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul2321196023222"><li>Specifies the tag key.</li><li>Cannot be left blank.</li><li>Can contain a maximum of 36 characters.</li><li>Can contain only the following character types:<a name="en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul11049850105418"></a><a name="en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul11049850105418"></a><ul id="en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul11049850105418"><li>Uppercase letters</li><li>Lowercase letters</li><li>Digits</li><li>Special characters, including hyphens (-) and underscores (_)</li></ul>
</li><li>The tag key of a VPC must be unique.</li></ul>
</td>
</tr>
<tr id="row2346548163714"><td class="cellrowborder" valign="top" width="17.46%" headers="mcps1.2.4.1.1 "><p id="p1134624816377"><a name="p1134624816377"></a><a name="p1134624816377"></a>value</p>
</td>
<td class="cellrowborder" valign="top" width="20.84%" headers="mcps1.2.4.1.2 "><p id="p234619483371"><a name="p234619483371"></a><a name="p234619483371"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="61.7%" headers="mcps1.2.4.1.3 "><a name="en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul6706750105539"></a><a name="en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul6706750105539"></a><ul id="en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul6706750105539"><li>Specifies the tag value.</li><li>Can contain a maximum of 43 characters.</li><li>Can contain only the following character types:<a name="ul7895160105919"></a><a name="ul7895160105919"></a><ul id="ul7895160105919"><li>Uppercase letters</li><li>Lowercase letters</li><li>Digits</li><li>Special characters, including hyphens (-) and underscores (_)</li></ul>
</li></ul>
</td>
</tr>
</tbody>
</table>

Example response

```
{
    "tags": [
        {
            "key": "key1",
            "value": "value1"
        },
        {
            "key": "key2",
            "value": "value3"
        }
    ]
}
```

## Status Code<a name="section31981619"></a>

See  [Status Codes](status-codes.md).

## Error Code<a name="section85821649202813"></a>

See  [Error Codes](error-codes.md).

