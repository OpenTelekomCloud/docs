# Enabling a CMK<a name="kms_02_0013"></a>

## Function<a name="en-us_topic_0112992351_s1731a14fb0144c79bf0fa90c694f34f7"></a>

This API allows you to enable a CMK. Only an enabled CMK can be used.

>![](/images/icon-note.gif) **NOTE:**   
>Only a disabled CMK can be enabled.  

## URI<a name="en-us_topic_0112992351_se70c3e5518a04f60b06032524dddfef4"></a>

-   URI format

    POST /v1.0/\{project\_id\}/kms/enable-key

-   Parameter description

    **Table  1**  Parameters

    <a name="en-us_topic_0112992351_t982da1e0196d4ec1a28d1fbff2cc8191"></a>
    <table><thead align="left"><tr id="en-us_topic_0112992351_r6e963322c1e740d181726d2f0e91df5a"><th class="cellrowborder" valign="top" width="22.74%" id="mcps1.2.5.1.1"><p id="en-us_topic_0112992351_a3b5bbe5a7f644fd3a74cecbfb3f7ed60"><a name="en-us_topic_0112992351_a3b5bbe5a7f644fd3a74cecbfb3f7ed60"></a><a name="en-us_topic_0112992351_a3b5bbe5a7f644fd3a74cecbfb3f7ed60"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="23.68%" id="mcps1.2.5.1.2"><p id="en-us_topic_0112992351_ad98d2f62bd064b4e96ea922645197c24"><a name="en-us_topic_0112992351_ad98d2f62bd064b4e96ea922645197c24"></a><a name="en-us_topic_0112992351_ad98d2f62bd064b4e96ea922645197c24"></a>Mandatory</p>
    </th>
    <th class="cellrowborder" valign="top" width="18.8%" id="mcps1.2.5.1.3"><p id="en-us_topic_0112992351_a3becf0b3aec9468984c2efc8d5abbea5"><a name="en-us_topic_0112992351_a3becf0b3aec9468984c2efc8d5abbea5"></a><a name="en-us_topic_0112992351_a3becf0b3aec9468984c2efc8d5abbea5"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="34.78%" id="mcps1.2.5.1.4"><p id="en-us_topic_0112992351_a6bb6f1fe56a2454982832e8d56d354d8"><a name="en-us_topic_0112992351_a6bb6f1fe56a2454982832e8d56d354d8"></a><a name="en-us_topic_0112992351_a6bb6f1fe56a2454982832e8d56d354d8"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="en-us_topic_0112992351_r69bf37b65d3f446eab7b3f4d1b2fcec0"><td class="cellrowborder" valign="top" width="22.74%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0112992351_ae42d73592f58424ea93a11e52d2478dd"><a name="en-us_topic_0112992351_ae42d73592f58424ea93a11e52d2478dd"></a><a name="en-us_topic_0112992351_ae42d73592f58424ea93a11e52d2478dd"></a>project_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="23.68%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0112992351_a56440c0f0ae34ba3b8033d1247673984"><a name="en-us_topic_0112992351_a56440c0f0ae34ba3b8033d1247673984"></a><a name="en-us_topic_0112992351_a56440c0f0ae34ba3b8033d1247673984"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.8%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0112992351_a1a4a71c11a4a45a58d0de2fbe009e9d9"><a name="en-us_topic_0112992351_a1a4a71c11a4a45a58d0de2fbe009e9d9"></a><a name="en-us_topic_0112992351_a1a4a71c11a4a45a58d0de2fbe009e9d9"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="34.78%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0112992351_a1314869d2dc147b38461e037d622f7b4"><a name="en-us_topic_0112992351_a1314869d2dc147b38461e037d622f7b4"></a><a name="en-us_topic_0112992351_a1314869d2dc147b38461e037d622f7b4"></a>Project ID</p>
    </td>
    </tr>
    </tbody>
    </table>


## Requests<a name="en-us_topic_0112992351_seb7b7901701247fab30a59b76f1c7f93"></a>

**Table  2**  Request parameters

<a name="en-us_topic_0112992351_table46221022101230"></a>
<table><thead align="left"><tr id="en-us_topic_0112992351_row9315574101230"><th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.1"><p id="en-us_topic_0112992351_p16364058101230"><a name="en-us_topic_0112992351_p16364058101230"></a><a name="en-us_topic_0112992351_p16364058101230"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.2"><p id="en-us_topic_0112992351_p57514295101230"><a name="en-us_topic_0112992351_p57514295101230"></a><a name="en-us_topic_0112992351_p57514295101230"></a><strong id="en-us_topic_0112992351_b8423527061751"><a name="en-us_topic_0112992351_b8423527061751"></a><a name="en-us_topic_0112992351_b8423527061751"></a>Mandatory</strong></p>
</th>
<th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.3"><p id="en-us_topic_0112992351_p50420322101230"><a name="en-us_topic_0112992351_p50420322101230"></a><a name="en-us_topic_0112992351_p50420322101230"></a><strong id="en-us_topic_0112992351_b84235270617453"><a name="en-us_topic_0112992351_b84235270617453"></a><a name="en-us_topic_0112992351_b84235270617453"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.5.1.4"><p id="en-us_topic_0112992351_p28146304101230"><a name="en-us_topic_0112992351_p28146304101230"></a><a name="en-us_topic_0112992351_p28146304101230"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0112992351_row2638193101722"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0112992351_p60294921111618"><a name="en-us_topic_0112992351_p60294921111618"></a><a name="en-us_topic_0112992351_p60294921111618"></a>key_id</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0112992351_p55333918111618"><a name="en-us_topic_0112992351_p55333918111618"></a><a name="en-us_topic_0112992351_p55333918111618"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0112992351_p52050413111618"><a name="en-us_topic_0112992351_p52050413111618"></a><a name="en-us_topic_0112992351_p52050413111618"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0112992351_p21429612171128"><a name="en-us_topic_0112992351_p21429612171128"></a><a name="en-us_topic_0112992351_p21429612171128"></a>36-byte ID of a CMK that matches the regular expression <span class="parmvalue" id="en-us_topic_0112992351_parmvalue80435593163333"><a name="en-us_topic_0112992351_parmvalue80435593163333"></a><a name="en-us_topic_0112992351_parmvalue80435593163333"></a><b>^[0-9a-z]{8}-[0-9a-z]{4}-[0-9a-z]{4}-[0-9a-z]{4}-[0-9a-z]{12}$</b></span></p>
<p id="en-us_topic_0112992351_p52862339111618"><a name="en-us_topic_0112992351_p52862339111618"></a><a name="en-us_topic_0112992351_p52862339111618"></a>Example: 0d0466b0-e727-4d9c-b35d-f84bb474a37f</p>
</td>
</tr>
<tr id="en-us_topic_0112992351_row35142504101726"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0112992351_p269135101746"><a name="en-us_topic_0112992351_p269135101746"></a><a name="en-us_topic_0112992351_p269135101746"></a>sequence</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0112992351_p20967256101746"><a name="en-us_topic_0112992351_p20967256101746"></a><a name="en-us_topic_0112992351_p20967256101746"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0112992351_p21799971101746"><a name="en-us_topic_0112992351_p21799971101746"></a><a name="en-us_topic_0112992351_p21799971101746"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0112992351_p63875345171137"><a name="en-us_topic_0112992351_p63875345171137"></a><a name="en-us_topic_0112992351_p63875345171137"></a>36-byte serial number of a request message</p>
<p id="en-us_topic_0112992351_p20626198101746"><a name="en-us_topic_0112992351_p20626198101746"></a><a name="en-us_topic_0112992351_p20626198101746"></a>Example: 919c82d4-8046-4722-9094-35c3c6524cff</p>
</td>
</tr>
</tbody>
</table>

## Responses<a name="en-us_topic_0112992351_sfadd53a5f4714e8f87811818d62d0296"></a>

**Table  3**  Response parameters

<a name="en-us_topic_0112992351_t98d238e10953421e84a073707024c329"></a>
<table><thead align="left"><tr id="en-us_topic_0112992351_r144a2c52c5054c6d9243eb2ef3875a21"><th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.1"><p id="en-us_topic_0112992351_a9156e0b03f054d4e8547e0787f88a51b"><a name="en-us_topic_0112992351_a9156e0b03f054d4e8547e0787f88a51b"></a><a name="en-us_topic_0112992351_a9156e0b03f054d4e8547e0787f88a51b"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.2"><p id="en-us_topic_0112992351_a1851157c81e14d7f82db752a5737195a"><a name="en-us_topic_0112992351_a1851157c81e14d7f82db752a5737195a"></a><a name="en-us_topic_0112992351_a1851157c81e14d7f82db752a5737195a"></a><strong id="en-us_topic_0112992351_b84235270617535"><a name="en-us_topic_0112992351_b84235270617535"></a><a name="en-us_topic_0112992351_b84235270617535"></a>Mandatory</strong></p>
</th>
<th class="cellrowborder" valign="top" width="17%" id="mcps1.2.5.1.3"><p id="en-us_topic_0112992351_a39360acf5daf4c01a1ebddeff5d68a1c"><a name="en-us_topic_0112992351_a39360acf5daf4c01a1ebddeff5d68a1c"></a><a name="en-us_topic_0112992351_a39360acf5daf4c01a1ebddeff5d68a1c"></a><strong id="en-us_topic_0112992351_b84235270617532"><a name="en-us_topic_0112992351_b84235270617532"></a><a name="en-us_topic_0112992351_b84235270617532"></a>Type</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.5.1.4"><p id="en-us_topic_0112992351_a0097000016b14857972b7929bcaaa038"><a name="en-us_topic_0112992351_a0097000016b14857972b7929bcaaa038"></a><a name="en-us_topic_0112992351_a0097000016b14857972b7929bcaaa038"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0112992351_r3c4af7b36e9240d197ab56255e37b83c"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0112992351_p43705601102713"><a name="en-us_topic_0112992351_p43705601102713"></a><a name="en-us_topic_0112992351_p43705601102713"></a>key_id</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0112992351_p63384753102713"><a name="en-us_topic_0112992351_p63384753102713"></a><a name="en-us_topic_0112992351_p63384753102713"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0112992351_p50492797102713"><a name="en-us_topic_0112992351_p50492797102713"></a><a name="en-us_topic_0112992351_p50492797102713"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0112992351_p33891398102713"><a name="en-us_topic_0112992351_p33891398102713"></a><a name="en-us_topic_0112992351_p33891398102713"></a>CMK ID</p>
</td>
</tr>
<tr id="en-us_topic_0112992351_rf212a916c502452a8e151eba2f118272"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0112992351_p64792915111712"><a name="en-us_topic_0112992351_p64792915111712"></a><a name="en-us_topic_0112992351_p64792915111712"></a>key_state</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0112992351_p38773827111712"><a name="en-us_topic_0112992351_p38773827111712"></a><a name="en-us_topic_0112992351_p38773827111712"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0112992351_p13734761111712"><a name="en-us_topic_0112992351_p13734761111712"></a><a name="en-us_topic_0112992351_p13734761111712"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0112992351_p53672265111712"><a name="en-us_topic_0112992351_p53672265111712"></a><a name="en-us_topic_0112992351_p53672265111712"></a>CMK status:</p>
<a name="en-us_topic_0112992351_ul38541215195435"></a><a name="en-us_topic_0112992351_ul38541215195435"></a><ul id="en-us_topic_0112992351_ul38541215195435"><li><span class="parmvalue" id="en-us_topic_0112992351_parmvalue555125744163642"><a name="en-us_topic_0112992351_parmvalue555125744163642"></a><a name="en-us_topic_0112992351_parmvalue555125744163642"></a><b>2</b></span> indicates that the CMK is enabled.</li><li><span class="parmvalue" id="en-us_topic_0112992351_parmvalue890467586163649"><a name="en-us_topic_0112992351_parmvalue890467586163649"></a><a name="en-us_topic_0112992351_parmvalue890467586163649"></a><b>3</b></span> indicates that the CMK is disabled.</li><li><span class="parmvalue" id="en-us_topic_0112992351_parmvalue7929059216370"><a name="en-us_topic_0112992351_parmvalue7929059216370"></a><a name="en-us_topic_0112992351_parmvalue7929059216370"></a><b>4</b></span> indicates that the CMK is scheduled for deletion.</li></ul>
</td>
</tr>
</tbody>
</table>

## Examples<a name="en-us_topic_0112992351_section8229115212593"></a>

The following example describes how to enable a CMK whose ID is  **0d0466b0-e727-4d9c-b35d-f84bb474a37f**.

-   Example request

    ```
    {
        "key_id": "0d0466b0-e727-4d9c-b35d-f84bb474a37f"
    }
    ```


-   Example response

    ```
    {
        "key_info": {
            "key_id": "0d0466b0-e727-4d9c-b35d-f84bb474a37f",
            "key_state": "2"
        }
    }
    ```

    or

    ```
    {
        "error": {
            "error_code": "KMS.XXXX",
            "error_msg": "XXX"
        }
    }
    ```


## Status Codes<a name="en-us_topic_0112992351_s811d1a98cd5242509abd6671a9959d55"></a>

[Table 4](#en-us_topic_0112992351_en-us_topic_0112992294_en-us_topic_0079615001_table20596071)  lists the normal status code returned by the response.

**Table  4**  Status codes

<a name="en-us_topic_0112992351_en-us_topic_0112992294_en-us_topic_0079615001_table20596071"></a>
<table><thead align="left"><tr id="en-us_topic_0112992351_en-us_topic_0112992294_en-us_topic_0079615001_row9746163"><th class="cellrowborder" valign="top" width="22%" id="mcps1.2.4.1.1"><p id="en-us_topic_0112992351_en-us_topic_0112992294_p57545694203043"><a name="en-us_topic_0112992351_en-us_topic_0112992294_p57545694203043"></a><a name="en-us_topic_0112992351_en-us_topic_0112992294_p57545694203043"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="32%" id="mcps1.2.4.1.2"><p id="en-us_topic_0112992351_en-us_topic_0112992294_p4531342288"><a name="en-us_topic_0112992351_en-us_topic_0112992294_p4531342288"></a><a name="en-us_topic_0112992351_en-us_topic_0112992294_p4531342288"></a>Status</p>
</th>
<th class="cellrowborder" valign="top" width="46%" id="mcps1.2.4.1.3"><p id="en-us_topic_0112992351_en-us_topic_0112992294_p30689603203043"><a name="en-us_topic_0112992351_en-us_topic_0112992294_p30689603203043"></a><a name="en-us_topic_0112992351_en-us_topic_0112992294_p30689603203043"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0112992351_en-us_topic_0112992294_en-us_topic_0079615001_row48621261"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0112992351_en-us_topic_0112992294_en-us_topic_0079615001_p46008046"><a name="en-us_topic_0112992351_en-us_topic_0112992294_en-us_topic_0079615001_p46008046"></a><a name="en-us_topic_0112992351_en-us_topic_0112992294_en-us_topic_0079615001_p46008046"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0112992351_en-us_topic_0112992294_p7538425819"><a name="en-us_topic_0112992351_en-us_topic_0112992294_p7538425819"></a><a name="en-us_topic_0112992351_en-us_topic_0112992294_p7538425819"></a>OK</p>
</td>
<td class="cellrowborder" valign="top" width="46%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0112992351_en-us_topic_0112992294_p1885682315512"><a name="en-us_topic_0112992351_en-us_topic_0112992294_p1885682315512"></a><a name="en-us_topic_0112992351_en-us_topic_0112992294_p1885682315512"></a>Request processed successfully.</p>
</td>
</tr>
</tbody>
</table>

Exception status code. For details, see  [Status Codes](status-codes.md#kms_02_0301).

