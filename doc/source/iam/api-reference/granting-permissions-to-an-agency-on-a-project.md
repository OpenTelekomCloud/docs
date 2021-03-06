# Granting Permissions to an Agency on a Project<a name="en-us_topic_0079467620"></a>

## Function Description<a name="s2797c145faa84a30b7c688cb7f61f5c3"></a>

This interface is used to grant permissions to an agency on a project.

## URI<a name="s33eb51d4240d45959c5b1509bf93c747"></a>

-   URI format

    PUT /v3.0/OS-AGENCY/projects/\{project\_id\}/agencies/\{agency\_id\}/roles/\{role\_id\}


-   URI parameter description

    <a name="t2eed66c3cdf04e7eafc8940b4e47a42d"></a>
    <table><thead align="left"><tr id="r3303e8efeb8c42588e93c4ec47e7dd31"><th class="cellrowborder" valign="top" width="18.360000000000003%" id="mcps1.1.5.1.1"><p id="af0d01a64b0264402b85cf188013060d9"><a name="af0d01a64b0264402b85cf188013060d9"></a><a name="af0d01a64b0264402b85cf188013060d9"></a><strong id="a173ae121cc9e48328ca613e72f2a1504"><a name="a173ae121cc9e48328ca613e72f2a1504"></a><a name="a173ae121cc9e48328ca613e72f2a1504"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.48%" id="mcps1.1.5.1.2"><p id="a51bb4888c6574784877430bda7164e12"><a name="a51bb4888c6574784877430bda7164e12"></a><a name="a51bb4888c6574784877430bda7164e12"></a><strong id="b842352706161940_1"><a name="b842352706161940_1"></a><a name="b842352706161940_1"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.86%" id="mcps1.1.5.1.3"><p id="ad5ff1e377ac740e78b98e5e25e1bb323"><a name="ad5ff1e377ac740e78b98e5e25e1bb323"></a><a name="ad5ff1e377ac740e78b98e5e25e1bb323"></a><strong id="b842352706143526_1"><a name="b842352706143526_1"></a><a name="b842352706143526_1"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="44.3%" id="mcps1.1.5.1.4"><p id="a9446ba7048504152bc6f8961a7b9cbc8"><a name="a9446ba7048504152bc6f8961a7b9cbc8"></a><a name="a9446ba7048504152bc6f8961a7b9cbc8"></a><strong id="b20601766145329_1"><a name="b20601766145329_1"></a><a name="b20601766145329_1"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="rd4510339dfb84de2b564d282aa07519a"><td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.1 "><p id="ad754c479a7924ca6b77190ef5029ce63"><a name="ad754c479a7924ca6b77190ef5029ce63"></a><a name="ad754c479a7924ca6b77190ef5029ce63"></a>project_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.48%" headers="mcps1.1.5.1.2 "><p id="aa466f08b8cb54b04aa3f5358716df255"><a name="aa466f08b8cb54b04aa3f5358716df255"></a><a name="aa466f08b8cb54b04aa3f5358716df255"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.86%" headers="mcps1.1.5.1.3 "><p id="a9ab05e62f509498b987dccd76d1bd1c8"><a name="a9ab05e62f509498b987dccd76d1bd1c8"></a><a name="a9ab05e62f509498b987dccd76d1bd1c8"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.3%" headers="mcps1.1.5.1.4 "><p id="a5bc7b47e2ee040219626bbc5f22983cb"><a name="a5bc7b47e2ee040219626bbc5f22983cb"></a><a name="a5bc7b47e2ee040219626bbc5f22983cb"></a>ID of a project under the current domain.</p>
    </td>
    </tr>
    <tr id="rc27b213d6d194784a87ec2d4fc386013"><td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.1 "><p id="a0f5d61a82c3045a8acec6c1b898c8637"><a name="a0f5d61a82c3045a8acec6c1b898c8637"></a><a name="a0f5d61a82c3045a8acec6c1b898c8637"></a>agency_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.48%" headers="mcps1.1.5.1.2 "><p id="a336128957f3a44ce9ae88461fbf8131c"><a name="a336128957f3a44ce9ae88461fbf8131c"></a><a name="a336128957f3a44ce9ae88461fbf8131c"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.86%" headers="mcps1.1.5.1.3 "><p id="aa3934a8762264b039e99d785b1039d36"><a name="aa3934a8762264b039e99d785b1039d36"></a><a name="aa3934a8762264b039e99d785b1039d36"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.3%" headers="mcps1.1.5.1.4 "><p id="a43e09d5d6d8247e3bff922f088a1bde2"><a name="a43e09d5d6d8247e3bff922f088a1bde2"></a><a name="a43e09d5d6d8247e3bff922f088a1bde2"></a>ID of an agency.</p>
    </td>
    </tr>
    <tr id="rfca21f3538d94b1cbb658a3691b2aa0d"><td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.1 "><p id="a0a35a40f930048a59e8c156d11d327a3"><a name="a0a35a40f930048a59e8c156d11d327a3"></a><a name="a0a35a40f930048a59e8c156d11d327a3"></a>role_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.48%" headers="mcps1.1.5.1.2 "><p id="a6dbaa703f5ab4b1b99820238781f2141"><a name="a6dbaa703f5ab4b1b99820238781f2141"></a><a name="a6dbaa703f5ab4b1b99820238781f2141"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.86%" headers="mcps1.1.5.1.3 "><p id="a93375c8c7d8d4449ba041840782131df"><a name="a93375c8c7d8d4449ba041840782131df"></a><a name="a93375c8c7d8d4449ba041840782131df"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.3%" headers="mcps1.1.5.1.4 "><p id="a0fcca67673fa47f297bb04aefc41c295"><a name="a0fcca67673fa47f297bb04aefc41c295"></a><a name="a0fcca67673fa47f297bb04aefc41c295"></a>ID of a role.</p>
    </td>
    </tr>
    </tbody>
    </table>

    >![](/images/icon-note.gif) **NOTE:**   
    >The role name corresponding to  **role\_id**  in a request body is controlled by a blacklist. The role name cannot be  **secu\_admin**  or  **te\_agency**.  


## Request<a name="sfdcf4579d43c4d36ae6a8a98cc64cb2a"></a>

-   Request header parameter description

    <a name="ta266f5738ff14cb6868a9231a8be51c9"></a>
    <table><thead align="left"><tr id="rc1641e1a53cf401c9c4bc9d09800cbf2"><th class="cellrowborder" valign="top" width="19.36%" id="mcps1.1.5.1.1"><p id="af11531211535426bb301bc9057e7bb11"><a name="af11531211535426bb301bc9057e7bb11"></a><a name="af11531211535426bb301bc9057e7bb11"></a><strong id="b10602794144020"><a name="b10602794144020"></a><a name="b10602794144020"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="16.73%" id="mcps1.1.5.1.2"><p id="a543e04fb4d184684bf9989f3677e0967"><a name="a543e04fb4d184684bf9989f3677e0967"></a><a name="a543e04fb4d184684bf9989f3677e0967"></a><strong id="b842352706161940_3"><a name="b842352706161940_3"></a><a name="b842352706161940_3"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="19.6%" id="mcps1.1.5.1.3"><p id="a2d08b1ad2b294a68b8b4c160c40d839b"><a name="a2d08b1ad2b294a68b8b4c160c40d839b"></a><a name="a2d08b1ad2b294a68b8b4c160c40d839b"></a><strong id="b842352706143526_3"><a name="b842352706143526_3"></a><a name="b842352706143526_3"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="44.31%" id="mcps1.1.5.1.4"><p id="ad364918facff4854b55d0ae5ef795925"><a name="ad364918facff4854b55d0ae5ef795925"></a><a name="ad364918facff4854b55d0ae5ef795925"></a><strong id="b20601766145329_3"><a name="b20601766145329_3"></a><a name="b20601766145329_3"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="re4a659ac4e714cde8104f2cb5268a012"><td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.5.1.1 "><p id="a40f465ebf10f4541938410adf13de6bc"><a name="a40f465ebf10f4541938410adf13de6bc"></a><a name="a40f465ebf10f4541938410adf13de6bc"></a>Content-Type</p>
    </td>
    <td class="cellrowborder" valign="top" width="16.73%" headers="mcps1.1.5.1.2 "><p id="a61755322e2684ad98c7997ccc6f3f9e1"><a name="a61755322e2684ad98c7997ccc6f3f9e1"></a><a name="a61755322e2684ad98c7997ccc6f3f9e1"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.6%" headers="mcps1.1.5.1.3 "><p id="a2426320f8bb54f0b8907accae3493275"><a name="a2426320f8bb54f0b8907accae3493275"></a><a name="a2426320f8bb54f0b8907accae3493275"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.31%" headers="mcps1.1.5.1.4 "><p id="a1f7b007c29334466b830f2836af4fe3f"><a name="a1f7b007c29334466b830f2836af4fe3f"></a><a name="a1f7b007c29334466b830f2836af4fe3f"></a>Fill <strong id="b842352706161331"><a name="b842352706161331"></a><a name="b842352706161331"></a>application/json;charset=utf8</strong> in this field.</p>
    </td>
    </tr>
    <tr id="rf51395632af147a2a93a7a4b44d42823"><td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.5.1.1 "><p id="a152e454a198b465e8fc3da237ae6acf5"><a name="a152e454a198b465e8fc3da237ae6acf5"></a><a name="a152e454a198b465e8fc3da237ae6acf5"></a>X-Auth-Token</p>
    </td>
    <td class="cellrowborder" valign="top" width="16.73%" headers="mcps1.1.5.1.2 "><p id="a99b29c8fef87474cb8fb9f2dc928c5bc"><a name="a99b29c8fef87474cb8fb9f2dc928c5bc"></a><a name="a99b29c8fef87474cb8fb9f2dc928c5bc"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="19.6%" headers="mcps1.1.5.1.3 "><p id="a0e0e7ec28c2e4e6f92346246996f47ea"><a name="a0e0e7ec28c2e4e6f92346246996f47ea"></a><a name="a0e0e7ec28c2e4e6f92346246996f47ea"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.31%" headers="mcps1.1.5.1.4 "><p id="p56210016113658"><a name="p56210016113658"></a><a name="p56210016113658"></a>Authenticated token with the <strong id="b750798910387"><a name="b750798910387"></a><a name="b750798910387"></a>Security Administrator</strong> permission.</p>
    </td>
    </tr>
    </tbody>
    </table>


-   Sample request

    ```
    curl -i -k -H "X-Auth-Token:$token" -H 'Content-Type:application/json;charset=utf8' -X PUT https://sample.domain.com/v3.0/OS-AGENCY/projects/0945241c5ebc4660bac540d48f2a2c14/agencies/37f90258b820472bbc8a0f4f0bfd720d/roles/0f3a2d418ed747fa8be46e92757be9ff
    ```


## Response<a name="s55abe3ea283b41bf8851146d228a8d2a"></a>

-   No response: indicates that the response is successful.

-   Sample response \(request failed\)

    ```
    {
       "error" : {
           "message" : "Could not find role: 0f3a2d418ed747fa8be46e92757be9ddff",
           "code" : 404,
           "title" : "Not Found"
         }
    }
    ```


## **Status Codes**<a name="sd2bed1967bd143fa9958ce8637393c3d"></a>

<a name="td457a25ce4ce42cc8623de8314cdd29a"></a>
<table><thead align="left"><tr id="r579973beeff54b9eaef8ea5afd2572bc"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="a631978ce233c4e6cb1466c167c4c5fb6"><a name="a631978ce233c4e6cb1466c167c4c5fb6"></a><a name="a631978ce233c4e6cb1466c167c4c5fb6"></a><strong id="b56183929144020"><a name="b56183929144020"></a><a name="b56183929144020"></a>Status Code</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="a3389effc57924ada945200b39e2d0cb9"><a name="a3389effc57924ada945200b39e2d0cb9"></a><a name="a3389effc57924ada945200b39e2d0cb9"></a><strong id="b20601766145329_5"><a name="b20601766145329_5"></a><a name="b20601766145329_5"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r017a3c4a4d97482a80643dec0665ad8e"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a26319fb22245422e87a355d449086f25"><a name="a26319fb22245422e87a355d449086f25"></a><a name="a26319fb22245422e87a355d449086f25"></a>204</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a11689316d0be466e89d8d613a91029f3"><a name="a11689316d0be466e89d8d613a91029f3"></a><a name="a11689316d0be466e89d8d613a91029f3"></a>The request is successful.</p>
</td>
</tr>
<tr id="r41552fcee9ee49f6808e589b2e5e879d"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="abb25ab36d1d946f3a63e5e03e14bd574"><a name="abb25ab36d1d946f3a63e5e03e14bd574"></a><a name="abb25ab36d1d946f3a63e5e03e14bd574"></a>401</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a14defd1b9f8e4238b8eea6105ff0fb75"><a name="a14defd1b9f8e4238b8eea6105ff0fb75"></a><a name="a14defd1b9f8e4238b8eea6105ff0fb75"></a>You must enter a username and password to access the requested page.</p>
</td>
</tr>
<tr id="raec138a11d8944989ec3365f4d90a0bf"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a3815ddaa49484df4a7152116385079b5"><a name="a3815ddaa49484df4a7152116385079b5"></a><a name="a3815ddaa49484df4a7152116385079b5"></a>403</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a68e35c52defe44b590f69b74ab7be527"><a name="a68e35c52defe44b590f69b74ab7be527"></a><a name="a68e35c52defe44b590f69b74ab7be527"></a>You are forbidden to access the requested page.</p>
</td>
</tr>
<tr id="rb0808d3dee1f4362843e5f56adc95331"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a038534e207d54a6ea9119e857cbe8fed"><a name="a038534e207d54a6ea9119e857cbe8fed"></a><a name="a038534e207d54a6ea9119e857cbe8fed"></a>404</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="aa212176a1d0f410aace33ee4ce7ba676"><a name="aa212176a1d0f410aace33ee4ce7ba676"></a><a name="aa212176a1d0f410aace33ee4ce7ba676"></a>The server could not find the requested page.</p>
</td>
</tr>
<tr id="r2aa8fe61fb0249fc8ceff1ed8d9d8696"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="adce97889cfdc404698cc9e26948fa1c7"><a name="adce97889cfdc404698cc9e26948fa1c7"></a><a name="adce97889cfdc404698cc9e26948fa1c7"></a>500</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a50ff0331786f48e0aa854125a1fdfc4b"><a name="a50ff0331786f48e0aa854125a1fdfc4b"></a><a name="a50ff0331786f48e0aa854125a1fdfc4b"></a>Failed to complete the request because of an internal service error.</p>
</td>
</tr>
</tbody>
</table>

