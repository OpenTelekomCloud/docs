# Batch Creating or Deleting EIP Tags<a name="eip_apitag_0004"></a>

## Function<a name="en-us_topic_0201534168_section16984350162413"></a>

This API is used to add multiple tags to or delete multiple tags from an EIP at a time.

This API is idempotent.

If there are duplicate keys in the request body when you add tags, an error is reported.

During tag creation, duplicate keys are not allowed. If a key already exists in the database, its value will be overwritten by the new duplicate key.

During tag deletion, if some tags do not exist, the operation is considered to be successful by default. The character set of the tags will not be checked. When you delete tags, the tag structure cannot be missing, and the key cannot be left blank or be an empty string.

## URI<a name="en-us_topic_0201534168_section49844500244"></a>

POST /v2.0/\{project\_id\}/publicips/\{publicip\_id\}/tags/action

[Table 1](#en-us_topic_0201534168_table27380479)  describes the parameters.

**Table  1**  Parameter description

<a name="en-us_topic_0201534168_table27380479"></a>
<table><thead align="left"><tr id="en-us_topic_0201534168_row28751554"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="en-us_topic_0201534168_p47174532"><a name="en-us_topic_0201534168_p47174532"></a><a name="en-us_topic_0201534168_p47174532"></a><strong id="en-us_topic_0201534168_b189821182914"><a name="en-us_topic_0201534168_b189821182914"></a><a name="en-us_topic_0201534168_b189821182914"></a>Name</strong></p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="en-us_topic_0201534168_p63040734"><a name="en-us_topic_0201534168_p63040734"></a><a name="en-us_topic_0201534168_p63040734"></a><strong id="en-us_topic_0201534168_b14409731296"><a name="en-us_topic_0201534168_b14409731296"></a><a name="en-us_topic_0201534168_b14409731296"></a>Mandatory</strong></p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="en-us_topic_0201534168_p6025849"><a name="en-us_topic_0201534168_p6025849"></a><a name="en-us_topic_0201534168_p6025849"></a><strong id="en-us_topic_0201534168_b1960412572918"><a name="en-us_topic_0201534168_b1960412572918"></a><a name="en-us_topic_0201534168_b1960412572918"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0201534168_row18331773"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0201534168_p8478608"><a name="en-us_topic_0201534168_p8478608"></a><a name="en-us_topic_0201534168_p8478608"></a>project_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0201534168_p15678685"><a name="en-us_topic_0201534168_p15678685"></a><a name="en-us_topic_0201534168_p15678685"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0201534168_p10487112"><a name="en-us_topic_0201534168_p10487112"></a><a name="en-us_topic_0201534168_p10487112"></a>Specifies the project ID. </p>
</td>
</tr>
<tr id="en-us_topic_0201534168_row21254748"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0201534168_p43913021"><a name="en-us_topic_0201534168_p43913021"></a><a name="en-us_topic_0201534168_p43913021"></a>publicip_id</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0201534168_p184914"><a name="en-us_topic_0201534168_p184914"></a><a name="en-us_topic_0201534168_p184914"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0201534168_p14978051"><a name="en-us_topic_0201534168_p14978051"></a><a name="en-us_topic_0201534168_p14978051"></a>Specifies the unique identifier of an EIP.</p>
</td>
</tr>
</tbody>
</table>

## Request Message<a name="en-us_topic_0201534168_section1799117501243"></a>

-   Request parameter

    **Table  2**  Request parameter

    <a name="en-us_topic_0201534168_table8992250172415"></a>
    <table><thead align="left"><tr id="en-us_topic_0201534168_row3711351132413"><th class="cellrowborder" valign="top" width="14.000000000000002%" id="mcps1.2.5.1.1"><p id="en-us_topic_0201534168_p471145111242"><a name="en-us_topic_0201534168_p471145111242"></a><a name="en-us_topic_0201534168_p471145111242"></a><strong id="en-us_topic_0201534168_b842352706193648"><a name="en-us_topic_0201534168_b842352706193648"></a><a name="en-us_topic_0201534168_b842352706193648"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18%" id="mcps1.2.5.1.2"><p id="en-us_topic_0201534168_p47115515247"><a name="en-us_topic_0201534168_p47115515247"></a><a name="en-us_topic_0201534168_p47115515247"></a><strong id="en-us_topic_0201534168_b842352706193653"><a name="en-us_topic_0201534168_b842352706193653"></a><a name="en-us_topic_0201534168_b842352706193653"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="6%" id="mcps1.2.5.1.3"><p id="en-us_topic_0201534168_p10711051202417"><a name="en-us_topic_0201534168_p10711051202417"></a><a name="en-us_topic_0201534168_p10711051202417"></a><strong id="en-us_topic_0201534168_b822883015293"><a name="en-us_topic_0201534168_b822883015293"></a><a name="en-us_topic_0201534168_b822883015293"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="62%" id="mcps1.2.5.1.4"><p id="en-us_topic_0201534168_p117218511241"><a name="en-us_topic_0201534168_p117218511241"></a><a name="en-us_topic_0201534168_p117218511241"></a><strong id="en-us_topic_0201534168_b8423527061645"><a name="en-us_topic_0201534168_b8423527061645"></a><a name="en-us_topic_0201534168_b8423527061645"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="en-us_topic_0201534168_row572951152420"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0201534168_p17721851132411"><a name="en-us_topic_0201534168_p17721851132411"></a><a name="en-us_topic_0201534168_p17721851132411"></a>tags</p>
    </td>
    <td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0201534168_p072551172414"><a name="en-us_topic_0201534168_p072551172414"></a><a name="en-us_topic_0201534168_p072551172414"></a>Array of <a href="#en-us_topic_0201534168_table13242848193719">tag</a> objects</p>
    </td>
    <td class="cellrowborder" valign="top" width="6%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0201534168_p7721851162410"><a name="en-us_topic_0201534168_p7721851162410"></a><a name="en-us_topic_0201534168_p7721851162410"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="62%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0201534168_p67265110244"><a name="en-us_topic_0201534168_p67265110244"></a><a name="en-us_topic_0201534168_p67265110244"></a>Specifies the <strong id="en-us_topic_0201534168_b1010164117297"><a name="en-us_topic_0201534168_b1010164117297"></a><a name="en-us_topic_0201534168_b1010164117297"></a>tag</strong> object list. For details, see <a href="#en-us_topic_0201534168_table13242848193719">Table 3</a>.</p>
    </td>
    </tr>
    <tr id="en-us_topic_0201534168_row57295120245"><td class="cellrowborder" valign="top" width="14.000000000000002%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0201534168_p572115152417"><a name="en-us_topic_0201534168_p572115152417"></a><a name="en-us_topic_0201534168_p572115152417"></a>action</p>
    </td>
    <td class="cellrowborder" valign="top" width="18%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0201534168_p12724511244"><a name="en-us_topic_0201534168_p12724511244"></a><a name="en-us_topic_0201534168_p12724511244"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="6%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0201534168_p3721951162417"><a name="en-us_topic_0201534168_p3721951162417"></a><a name="en-us_topic_0201534168_p3721951162417"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="62%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0201534168_p1562014114112"><a name="en-us_topic_0201534168_p1562014114112"></a><a name="en-us_topic_0201534168_p1562014114112"></a>Specifies the operation. Possible values are as follows:</p>
    <a name="en-us_topic_0201534168_ul2205152413110"></a><a name="en-us_topic_0201534168_ul2205152413110"></a><ul id="en-us_topic_0201534168_ul2205152413110"><li><strong id="en-us_topic_0201534168_b167216507292"><a name="en-us_topic_0201534168_b167216507292"></a><a name="en-us_topic_0201534168_b167216507292"></a>create</strong></li><li><strong id="en-us_topic_0201534168_b19323851132917"><a name="en-us_topic_0201534168_b19323851132917"></a><a name="en-us_topic_0201534168_b19323851132917"></a>delete</strong></li></ul>
    </td>
    </tr>
    </tbody>
    </table>

    **Table  3** **tag**  objects

    <a name="en-us_topic_0201534168_table13242848193719"></a>
    <table><thead align="left"><tr id="en-us_topic_0201534168_row13343144812379"><th class="cellrowborder" valign="top" width="13%" id="mcps1.2.5.1.1"><p id="en-us_topic_0201534168_p15343174853715"><a name="en-us_topic_0201534168_p15343174853715"></a><a name="en-us_topic_0201534168_p15343174853715"></a><strong id="en-us_topic_0201534168_b869595411295"><a name="en-us_topic_0201534168_b869595411295"></a><a name="en-us_topic_0201534168_b869595411295"></a>Attribute</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.060000000000002%" id="mcps1.2.5.1.2"><p id="en-us_topic_0201534168_p13431648163716"><a name="en-us_topic_0201534168_p13431648163716"></a><a name="en-us_topic_0201534168_p13431648163716"></a><strong id="en-us_topic_0201534168_b01012567294"><a name="en-us_topic_0201534168_b01012567294"></a><a name="en-us_topic_0201534168_b01012567294"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="12.24%" id="mcps1.2.5.1.3"><p id="en-us_topic_0201534168_p169809965412"><a name="en-us_topic_0201534168_p169809965412"></a><a name="en-us_topic_0201534168_p169809965412"></a><strong id="en-us_topic_0201534168_b842352706192549"><a name="en-us_topic_0201534168_b842352706192549"></a><a name="en-us_topic_0201534168_b842352706192549"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="56.699999999999996%" id="mcps1.2.5.1.4"><p id="en-us_topic_0201534168_p11344748183719"><a name="en-us_topic_0201534168_p11344748183719"></a><a name="en-us_topic_0201534168_p11344748183719"></a><strong id="en-us_topic_0201534168_b1419325679"><a name="en-us_topic_0201534168_b1419325679"></a><a name="en-us_topic_0201534168_b1419325679"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="en-us_topic_0201534168_row103449487379"><td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0201534168_p183469482373"><a name="en-us_topic_0201534168_p183469482373"></a><a name="en-us_topic_0201534168_p183469482373"></a>key</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.060000000000002%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0201534168_p1434684863710"><a name="en-us_topic_0201534168_p1434684863710"></a><a name="en-us_topic_0201534168_p1434684863710"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="12.24%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0201534168_p298018911544"><a name="en-us_topic_0201534168_p298018911544"></a><a name="en-us_topic_0201534168_p298018911544"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.699999999999996%" headers="mcps1.2.5.1.4 "><a name="en-us_topic_0201534168_en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul2321196023222"></a><a name="en-us_topic_0201534168_en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul2321196023222"></a><ul id="en-us_topic_0201534168_en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul2321196023222"><li>Specifies the tag key.</li><li>Cannot be left blank.</li><li>Can contain a maximum of 36 characters.</li><li>Can contain only the following character types:<a name="en-us_topic_0201534168_en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul11049850105418"></a><a name="en-us_topic_0201534168_en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul11049850105418"></a><ul id="en-us_topic_0201534168_en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul11049850105418"><li>Uppercase letters</li><li>Lowercase letters</li><li>Digits</li><li>Special characters, including hyphens (-) and underscores (_)</li></ul>
    </li><li>The tag key of a VPC must be unique.</li></ul>
    </td>
    </tr>
    <tr id="en-us_topic_0201534168_row2346548163714"><td class="cellrowborder" valign="top" width="13%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0201534168_p1134624816377"><a name="en-us_topic_0201534168_p1134624816377"></a><a name="en-us_topic_0201534168_p1134624816377"></a>value</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.060000000000002%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0201534168_p234619483371"><a name="en-us_topic_0201534168_p234619483371"></a><a name="en-us_topic_0201534168_p234619483371"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="12.24%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0201534168_p679240173317"><a name="en-us_topic_0201534168_p679240173317"></a><a name="en-us_topic_0201534168_p679240173317"></a>Yes (when the value of <strong id="en-us_topic_0201534168_b167984023315"><a name="en-us_topic_0201534168_b167984023315"></a><a name="en-us_topic_0201534168_b167984023315"></a>action</strong> is <strong id="en-us_topic_0201534168_b179164003318"><a name="en-us_topic_0201534168_b179164003318"></a><a name="en-us_topic_0201534168_b179164003318"></a>create</strong>) </p>
    <p id="en-us_topic_0201534168_p209805915417"><a name="en-us_topic_0201534168_p209805915417"></a><a name="en-us_topic_0201534168_p209805915417"></a>No (when the value of <strong id="en-us_topic_0201534168_b1741105620363"><a name="en-us_topic_0201534168_b1741105620363"></a><a name="en-us_topic_0201534168_b1741105620363"></a>action</strong> is <strong id="en-us_topic_0201534168_b104147565369"><a name="en-us_topic_0201534168_b104147565369"></a><a name="en-us_topic_0201534168_b104147565369"></a>delete</strong>)</p>
    </td>
    <td class="cellrowborder" valign="top" width="56.699999999999996%" headers="mcps1.2.5.1.4 "><a name="en-us_topic_0201534168_en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul6706750105539"></a><a name="en-us_topic_0201534168_en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul6706750105539"></a><ul id="en-us_topic_0201534168_en-us_topic_0013935842_en-us_topic_0067805752_en-us_topic_0013859511_ul6706750105539"><li>Specifies the tag value.</li><li>Can contain a maximum of 43 characters.</li><li>Can contain only the following character types:<a name="en-us_topic_0201534168_ul7895160105919"></a><a name="en-us_topic_0201534168_ul7895160105919"></a><ul id="en-us_topic_0201534168_ul7895160105919"><li>Uppercase letters</li><li>Lowercase letters</li><li>Digits</li><li>Special characters, including hyphens (-) and underscores (_)</li></ul>
    </li></ul>
    </td>
    </tr>
    </tbody>
    </table>


-   Request example 1: Creating tags in batches

    ```
    POST https://{Endpoint}/v2.0/{project_id}/publicips/{publicip_id}/tags/action
    
    {
        "action": "create",
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


-   Request example 2: Deleting tags in batches

    ```
    POST https://{Endpoint}/v2.0/{project_id}/publicips/{publicip_id}/tags/action
    
    {
        "action": "delete",
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


## Response Message<a name="en-us_topic_0201534168_section173510241"></a>

-   Response parameter

    None

-   Example response

    None


## Status Code<a name="en-us_topic_0201534168_section31981619"></a>

See  [Status Codes](status-codes.md#eip_api05_0001).

## Error Code<a name="en-us_topic_0201534168_section85821649202813"></a>

See  [Error Codes](error-codes.md#eip_api05_0002).

