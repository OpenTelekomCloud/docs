# Access Keys \(AK/SK\)<a name="obs_03_0208"></a>

OBS supports AK/SK authentication. The access key ID \(AK\)/secret access key \(SK\) encryption method is used to authenticate a request sender. When you use OBS API for secondary development and use the AK/SK for authentication, the signature must be computed based on the algorithm defined by OBS and added to the request.

OBS supports authentication using a permanent AK/SK pair, or using a temporary AK/SK pair and a security token.

**Permanent AK/SK Pair**

You can create permanent AK/SK pair on the  **My Credentials**  page.

-   Access key ID \(AK\): indicates the ID of the access key. It is the unique ID associated with the SK. The AK and SK are used together to obtain an encrypted signature for a request.
-   Secret access key \(SK\): indicates the key used together with its associated private AK to cryptographically sign requests. The AK and SK are used together to identify a request sender to prevent the request from being modified.

**Temporary AK/SK Pair**

A temporary AK/SK pair and the security token are temporary access tokens granted by the system to users. The validity period of the tokens ranges from 15 minutes to 24 hours. After the tokens expire, you need to obtain the tokens again. A temporary AK/SK pair and the security token comply with the least privilege principle and can only be used to temporarily access OBS. A 403 error will be returned if the security token is not available.

-   Temporary access key ID \(AK\): ID of a temporary access key. It is a unique ID associated with the SK. The AK and SK are used together to obtain an encrypted signature for a request.
-   Temporary secret access key \(SK\): indicates the temporary key used together with its associated temporary AK. The AK and SK are used together to identify a request sender to prevent the request from being modified.
-   Security token: indicates the token used together with private temporary AK/SK to access all resources of a specified account.

When using the following tools to access OBS resources, you need to use the AK/SK pair for security authentication.

**Table  1**  OBS resource management tools

<a name="table95276448493"></a>
<table><thead align="left"><tr id="row1527844104914"><th class="cellrowborder" valign="top" width="23.48%" id="mcps1.2.3.1.1"><p id="p352713445495"><a name="p352713445495"></a><a name="p352713445495"></a>Tool</p>
</th>
<th class="cellrowborder" valign="top" width="76.52%" id="mcps1.2.3.1.2"><p id="p1652794404910"><a name="p1652794404910"></a><a name="p1652794404910"></a>AK/SK Configuration</p>
</th>
</tr>
</thead>
<tbody><tr id="row752744464920"><td class="cellrowborder" valign="top" width="23.48%" headers="mcps1.2.3.1.1 "><p id="p752784416490"><a name="p752784416490"></a><a name="p752784416490"></a>OBS Browser</p>
</td>
<td class="cellrowborder" valign="top" width="76.52%" headers="mcps1.2.3.1.2 "><p id="p197185522277"><a name="p197185522277"></a><a name="p197185522277"></a>Configure the AK and SK during account configuration.</p>
</td>
</tr>
<tr id="row17528444194913"><td class="cellrowborder" valign="top" width="23.48%" headers="mcps1.2.3.1.1 "><p id="p1852824444918"><a name="p1852824444918"></a><a name="p1852824444918"></a>SDK</p>
</td>
<td class="cellrowborder" valign="top" width="76.52%" headers="mcps1.2.3.1.2 "><p id="p1728443644914"><a name="p1728443644914"></a><a name="p1728443644914"></a>Configure the AK and SK in the initialization phase.</p>
</td>
</tr>
<tr id="row1152810445492"><td class="cellrowborder" valign="top" width="23.48%" headers="mcps1.2.3.1.1 "><p id="p13528174418494"><a name="p13528174418494"></a><a name="p13528174418494"></a>API</p>
</td>
<td class="cellrowborder" valign="top" width="76.52%" headers="mcps1.2.3.1.2 "><p id="p20251647144417"><a name="p20251647144417"></a><a name="p20251647144417"></a>Add the AK/SK pair to the request during signature calculation.</p>
</td>
</tr>
</tbody>
</table>

## References<a name="section9138185144512"></a>

For details about how to obtain a permanent AK/SK pair, see  [Creating Access Keys \(AK and SK\)](creating-access-keys-(ak-and-sk).md).

For details about how to obtain a temporary AK/SK pair and security token, see  [Obtaining Temporary AK/SK](https://docs.otc.t-systems.com/en-us/api/iam/en-us_topic_0097949518.html).

