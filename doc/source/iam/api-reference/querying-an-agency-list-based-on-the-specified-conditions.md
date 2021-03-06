# Querying an Agency List Based on the Specified Conditions<a name="en-us_topic_0079467614"></a>

## Function Description<a name="s351a53087b624bf68c88f723526bd5d4"></a>

This interface is used to query an agency list based on the specified conditions.

## URI<a name="s08fde0a01f0a4ead8e8fc38549803afc"></a>

-   URI format

    GET /v3.0/OS-AGENCY/agencies\{?domain\_id,name,trust\_domain\_id\}


-   Query parameter description

    <a name="tc955f64c43f647049fb9c0165b18cdc2"></a>
    <table><thead align="left"><tr id="r79b5dc33889447b7a605f44df82b31e8"><th class="cellrowborder" valign="top" width="18.360000000000003%" id="mcps1.1.5.1.1"><p id="a5cf140b235a143eab767f5bff8c9f08f"><a name="a5cf140b235a143eab767f5bff8c9f08f"></a><a name="a5cf140b235a143eab767f5bff8c9f08f"></a><strong id="en-us_topic_0026586105_b842352706143612"><a name="en-us_topic_0026586105_b842352706143612"></a><a name="en-us_topic_0026586105_b842352706143612"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.48%" id="mcps1.1.5.1.2"><p id="a4b51552dc6024331908f59e52aededb1"><a name="a4b51552dc6024331908f59e52aededb1"></a><a name="a4b51552dc6024331908f59e52aededb1"></a><strong id="b84235270616358_1"><a name="b84235270616358_1"></a><a name="b84235270616358_1"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.86%" id="mcps1.1.5.1.3"><p id="a09624a05c0a041a48f058a0658b9cff2"><a name="a09624a05c0a041a48f058a0658b9cff2"></a><a name="a09624a05c0a041a48f058a0658b9cff2"></a><strong id="b842352706143526_1"><a name="b842352706143526_1"></a><a name="b842352706143526_1"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="44.3%" id="mcps1.1.5.1.4"><p id="a9403c6c94f0449c18818099a34847fff"><a name="a9403c6c94f0449c18818099a34847fff"></a><a name="a9403c6c94f0449c18818099a34847fff"></a><strong id="b20601766145329_1"><a name="b20601766145329_1"></a><a name="b20601766145329_1"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="rb603c04755804200b8a9db46f374bfbe"><td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.1 "><p id="a70ffef7b605940ceab2554ffa2e9c9e0"><a name="a70ffef7b605940ceab2554ffa2e9c9e0"></a><a name="a70ffef7b605940ceab2554ffa2e9c9e0"></a>domain_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.48%" headers="mcps1.1.5.1.2 "><p id="a193d0d26deaf43b6b0783d496d91b15d"><a name="a193d0d26deaf43b6b0783d496d91b15d"></a><a name="a193d0d26deaf43b6b0783d496d91b15d"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.86%" headers="mcps1.1.5.1.3 "><p id="a4863d79620a24f2d8b953e5e6fe79902"><a name="a4863d79620a24f2d8b953e5e6fe79902"></a><a name="a4863d79620a24f2d8b953e5e6fe79902"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.3%" headers="mcps1.1.5.1.4 "><p id="acaf56792cac247aeb78c01f3d94681fd"><a name="acaf56792cac247aeb78c01f3d94681fd"></a><a name="acaf56792cac247aeb78c01f3d94681fd"></a>ID of the current domain.</p>
    </td>
    </tr>
    <tr id="ra0d821ace5f643878bec108d34734201"><td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.1 "><p id="a1ca6e155158f459593999840eb90a1da"><a name="a1ca6e155158f459593999840eb90a1da"></a><a name="a1ca6e155158f459593999840eb90a1da"></a>name</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.48%" headers="mcps1.1.5.1.2 "><p id="aa704c8457ad2413aaa8f8f704a57d9cb"><a name="aa704c8457ad2413aaa8f8f704a57d9cb"></a><a name="aa704c8457ad2413aaa8f8f704a57d9cb"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.86%" headers="mcps1.1.5.1.3 "><p id="a802ff17d536848c3a3626be288e81f2c"><a name="a802ff17d536848c3a3626be288e81f2c"></a><a name="a802ff17d536848c3a3626be288e81f2c"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.3%" headers="mcps1.1.5.1.4 "><p id="a98a47a8d92ec42209fed0c3a5dad302c"><a name="a98a47a8d92ec42209fed0c3a5dad302c"></a><a name="a98a47a8d92ec42209fed0c3a5dad302c"></a>Name of an agency.</p>
    </td>
    </tr>
    <tr id="row0981727204512"><td class="cellrowborder" valign="top" width="18.360000000000003%" headers="mcps1.1.5.1.1 "><p id="p2982142724519"><a name="p2982142724519"></a><a name="p2982142724519"></a>trust_domain_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.48%" headers="mcps1.1.5.1.2 "><p id="p39824274453"><a name="p39824274453"></a><a name="p39824274453"></a>No</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.86%" headers="mcps1.1.5.1.3 "><p id="p1798212715451"><a name="p1798212715451"></a><a name="p1798212715451"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.3%" headers="mcps1.1.5.1.4 "><p id="p698232764511"><a name="p698232764511"></a><a name="p698232764511"></a>ID of the delegated domain.</p>
    </td>
    </tr>
    </tbody>
    </table>


## Request<a name="s7730776dd0be4258b07cfc8001cc82e3"></a>

-   Request header parameter description

    <a name="t10f54517dbcc4a03831bbfa37e3e0f76"></a>
    <table><thead align="left"><tr id="r7b5c0cd2a702444a8b36935202710c14"><th class="cellrowborder" valign="top" width="18.698130186981302%" id="mcps1.1.5.1.1"><p id="a4f33c3460da84fffbe137fefbd621939"><a name="a4f33c3460da84fffbe137fefbd621939"></a><a name="a4f33c3460da84fffbe137fefbd621939"></a><strong id="b751019581"><a name="b751019581"></a><a name="b751019581"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.188181181881813%" id="mcps1.1.5.1.2"><p id="ac771b1051939406a977f3d01269784e6"><a name="ac771b1051939406a977f3d01269784e6"></a><a name="ac771b1051939406a977f3d01269784e6"></a><strong id="b84235270616358_3"><a name="b84235270616358_3"></a><a name="b84235270616358_3"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.66813318668133%" id="mcps1.1.5.1.3"><p id="a7f14cc65c30d4d29a42772f0f05d699a"><a name="a7f14cc65c30d4d29a42772f0f05d699a"></a><a name="a7f14cc65c30d4d29a42772f0f05d699a"></a><strong id="b842352706143526_3"><a name="b842352706143526_3"></a><a name="b842352706143526_3"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="44.44555544445555%" id="mcps1.1.5.1.4"><p id="aa6efa916a232459fa15ee2c3829955aa"><a name="aa6efa916a232459fa15ee2c3829955aa"></a><a name="aa6efa916a232459fa15ee2c3829955aa"></a><strong id="b20601766145329_3"><a name="b20601766145329_3"></a><a name="b20601766145329_3"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="r6847fe683769403d9f201b63f1a41a37"><td class="cellrowborder" valign="top" width="18.698130186981302%" headers="mcps1.1.5.1.1 "><p id="a20bd172006a745e48fc7d63cc8a6bb07"><a name="a20bd172006a745e48fc7d63cc8a6bb07"></a><a name="a20bd172006a745e48fc7d63cc8a6bb07"></a>Content-Type</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.188181181881813%" headers="mcps1.1.5.1.2 "><p id="a3e14fea6edfc4e5189724017a30c5b20"><a name="a3e14fea6edfc4e5189724017a30c5b20"></a><a name="a3e14fea6edfc4e5189724017a30c5b20"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.66813318668133%" headers="mcps1.1.5.1.3 "><p id="a52e5b54be9144f0eb25f763df7a4ab53"><a name="a52e5b54be9144f0eb25f763df7a4ab53"></a><a name="a52e5b54be9144f0eb25f763df7a4ab53"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.44555544445555%" headers="mcps1.1.5.1.4 "><p id="a1b153a1e9dab46439d82ac79b23ea22e"><a name="a1b153a1e9dab46439d82ac79b23ea22e"></a><a name="a1b153a1e9dab46439d82ac79b23ea22e"></a>Fill <strong id="b842352706161331"><a name="b842352706161331"></a><a name="b842352706161331"></a>application/json;charset=utf8</strong> in this field.</p>
    </td>
    </tr>
    <tr id="r6216c12734e742aa931ef342eb45a7e7"><td class="cellrowborder" valign="top" width="18.698130186981302%" headers="mcps1.1.5.1.1 "><p id="afd66d1ddd49a4892a90a05ad1b71d542"><a name="afd66d1ddd49a4892a90a05ad1b71d542"></a><a name="afd66d1ddd49a4892a90a05ad1b71d542"></a>X-Auth-Token</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.188181181881813%" headers="mcps1.1.5.1.2 "><p id="af6f2e0365f964329b0beff328366d677"><a name="af6f2e0365f964329b0beff328366d677"></a><a name="af6f2e0365f964329b0beff328366d677"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.66813318668133%" headers="mcps1.1.5.1.3 "><p id="a086767e16f914d81a4c0ee48994cee87"><a name="a086767e16f914d81a4c0ee48994cee87"></a><a name="a086767e16f914d81a4c0ee48994cee87"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.44555544445555%" headers="mcps1.1.5.1.4 "><p id="p57174477113315"><a name="p57174477113315"></a><a name="p57174477113315"></a>Authenticated token with the <strong id="b750798910387"><a name="b750798910387"></a><a name="b750798910387"></a>Security Administrator</strong> permission.</p>
    </td>
    </tr>
    </tbody>
    </table>


-   Sample request

    ```
    curl -i -k -H "X-Auth-Token:$token" -H 'Content-Type:application/json;charset=utf8' -X GET https://sample.domain.com/v3.0/OS-AGENCY/agencies?domain_id=0ae9c6993a2e47bb8c4c7a9bb8278d61
    ```


## Response<a name="s198ef18fb06f4e758c416b93700e996d"></a>

-   Response body parameter description

    <a name="t25fa11869fcc4bbe930214e8b3a352a8"></a>
    <table><thead align="left"><tr id="r607717c6cad24f3085d946d96e8706f6"><th class="cellrowborder" valign="top" width="18.891889188918892%" id="mcps1.1.5.1.1"><p id="a60b8a28cb4a14f4d957e11fbb5ed3491"><a name="a60b8a28cb4a14f4d957e11fbb5ed3491"></a><a name="a60b8a28cb4a14f4d957e11fbb5ed3491"></a><strong id="b1113612120"><a name="b1113612120"></a><a name="b1113612120"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.13181318131813%" id="mcps1.1.5.1.2"><p id="a18979c4eb8f144c889953807a71fe2c0"><a name="a18979c4eb8f144c889953807a71fe2c0"></a><a name="a18979c4eb8f144c889953807a71fe2c0"></a><strong id="b842352706161749_1"><a name="b842352706161749_1"></a><a name="b842352706161749_1"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.93189318931893%" id="mcps1.1.5.1.3"><p id="aac65acd7fc7b4c96933b30be7d73b987"><a name="aac65acd7fc7b4c96933b30be7d73b987"></a><a name="aac65acd7fc7b4c96933b30be7d73b987"></a><strong id="b842352706143526_5"><a name="b842352706143526_5"></a><a name="b842352706143526_5"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="44.04440444044405%" id="mcps1.1.5.1.4"><p id="ae0490d31122747f29843f4295fab3147"><a name="ae0490d31122747f29843f4295fab3147"></a><a name="ae0490d31122747f29843f4295fab3147"></a><strong id="b6981351183141_1"><a name="b6981351183141_1"></a><a name="b6981351183141_1"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="rae278792d71a4337b1b3ebb9d3cee2d8"><td class="cellrowborder" valign="top" width="18.891889188918892%" headers="mcps1.1.5.1.1 "><p id="ac8b2e0e1384f4dfc8cdea40e1b2992d5"><a name="ac8b2e0e1384f4dfc8cdea40e1b2992d5"></a><a name="ac8b2e0e1384f4dfc8cdea40e1b2992d5"></a>agencies</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.13181318131813%" headers="mcps1.1.5.1.2 "><p id="a3f02f98df8b4493c810f2017e8d18dd0"><a name="a3f02f98df8b4493c810f2017e8d18dd0"></a><a name="a3f02f98df8b4493c810f2017e8d18dd0"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.93189318931893%" headers="mcps1.1.5.1.3 "><p id="a20eedf6a66c144868d14c84c17b47526"><a name="a20eedf6a66c144868d14c84c17b47526"></a><a name="a20eedf6a66c144868d14c84c17b47526"></a>JSONArray</p>
    </td>
    <td class="cellrowborder" valign="top" width="44.04440444044405%" headers="mcps1.1.5.1.4 "><p id="adba154707b0049a19d9f6c70c5ff6936"><a name="adba154707b0049a19d9f6c70c5ff6936"></a><a name="adba154707b0049a19d9f6c70c5ff6936"></a>List of agencies.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Description for the agency format

    <a name="ta8ec7733f3e249568598f092b2720528"></a>
    <table><thead align="left"><tr id="redb2511c03314e6688cf6683d2c25de8"><th class="cellrowborder" valign="top" width="19.16%" id="mcps1.1.5.1.1"><p id="a9a1c101100ac49d8b01b6fff33850669"><a name="a9a1c101100ac49d8b01b6fff33850669"></a><a name="a9a1c101100ac49d8b01b6fff33850669"></a><strong id="b512049903"><a name="b512049903"></a><a name="b512049903"></a>Parameter</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.13%" id="mcps1.1.5.1.2"><p id="a1346a92b22174e5686a156f2fb7d36f1"><a name="a1346a92b22174e5686a156f2fb7d36f1"></a><a name="a1346a92b22174e5686a156f2fb7d36f1"></a><strong id="b842352706161749_3"><a name="b842352706161749_3"></a><a name="b842352706161749_3"></a>Mandatory</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="18.93%" id="mcps1.1.5.1.3"><p id="a70c10262fdca44c8b6330a1ea18cd1b4"><a name="a70c10262fdca44c8b6330a1ea18cd1b4"></a><a name="a70c10262fdca44c8b6330a1ea18cd1b4"></a><strong id="b842352706143526_7"><a name="b842352706143526_7"></a><a name="b842352706143526_7"></a>Type</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="43.78%" id="mcps1.1.5.1.4"><p id="a6897c47449a749889693a4715dc29b50"><a name="a6897c47449a749889693a4715dc29b50"></a><a name="a6897c47449a749889693a4715dc29b50"></a><strong id="b6981351183141_3"><a name="b6981351183141_3"></a><a name="b6981351183141_3"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="r110078ccf9074b61964145e1ab6b4641"><td class="cellrowborder" valign="top" width="19.16%" headers="mcps1.1.5.1.1 "><p id="a63c3299b0ce34c21b2a46a56bdb3a264"><a name="a63c3299b0ce34c21b2a46a56bdb3a264"></a><a name="a63c3299b0ce34c21b2a46a56bdb3a264"></a>id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.13%" headers="mcps1.1.5.1.2 "><p id="aacfeadabeffa4782b3659e6653070707"><a name="aacfeadabeffa4782b3659e6653070707"></a><a name="aacfeadabeffa4782b3659e6653070707"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.93%" headers="mcps1.1.5.1.3 "><p id="ae17a21f3468e4ff9a3ef45623af3c959"><a name="ae17a21f3468e4ff9a3ef45623af3c959"></a><a name="ae17a21f3468e4ff9a3ef45623af3c959"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.78%" headers="mcps1.1.5.1.4 "><p id="a25157631aeb2483381bbdc786cf25894"><a name="a25157631aeb2483381bbdc786cf25894"></a><a name="a25157631aeb2483381bbdc786cf25894"></a>ID of an agency.</p>
    </td>
    </tr>
    <tr id="r9313bd23c4384e42a2f8807a693ec666"><td class="cellrowborder" valign="top" width="19.16%" headers="mcps1.1.5.1.1 "><p id="a66df6c7fe64e46c9b330d702d2bb4eae"><a name="a66df6c7fe64e46c9b330d702d2bb4eae"></a><a name="a66df6c7fe64e46c9b330d702d2bb4eae"></a>name</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.13%" headers="mcps1.1.5.1.2 "><p id="abb3b9446d1964dcba392ac04363918f2"><a name="abb3b9446d1964dcba392ac04363918f2"></a><a name="abb3b9446d1964dcba392ac04363918f2"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.93%" headers="mcps1.1.5.1.3 "><p id="a7d8a46dfe96143ee965795296322d053"><a name="a7d8a46dfe96143ee965795296322d053"></a><a name="a7d8a46dfe96143ee965795296322d053"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.78%" headers="mcps1.1.5.1.4 "><p id="adf0ce3fd3ecd4eb2a1847aebaa0eccc1"><a name="adf0ce3fd3ecd4eb2a1847aebaa0eccc1"></a><a name="adf0ce3fd3ecd4eb2a1847aebaa0eccc1"></a>Name of an agency.</p>
    </td>
    </tr>
    <tr id="r691ce2d2be9b4f0d9b446bae0c47d44a"><td class="cellrowborder" valign="top" width="19.16%" headers="mcps1.1.5.1.1 "><p id="en-us_topic_0059029098_p27845782253"><a name="en-us_topic_0059029098_p27845782253"></a><a name="en-us_topic_0059029098_p27845782253"></a>domain_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.13%" headers="mcps1.1.5.1.2 "><p id="aaccfb0ccad5f45838c408cf9bfdd15f4"><a name="aaccfb0ccad5f45838c408cf9bfdd15f4"></a><a name="aaccfb0ccad5f45838c408cf9bfdd15f4"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.93%" headers="mcps1.1.5.1.3 "><p id="a807774074d544fd0859de28bcf268291"><a name="a807774074d544fd0859de28bcf268291"></a><a name="a807774074d544fd0859de28bcf268291"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.78%" headers="mcps1.1.5.1.4 "><p id="ae2406e3e6f744fac9745bedcff50f650"><a name="ae2406e3e6f744fac9745bedcff50f650"></a><a name="ae2406e3e6f744fac9745bedcff50f650"></a>ID of the current domain.</p>
    </td>
    </tr>
    <tr id="r325a9bff4b994a34b57507d4be78beb8"><td class="cellrowborder" valign="top" width="19.16%" headers="mcps1.1.5.1.1 "><p id="ad3629c12f37d4d9592921c14bc84cf6a"><a name="ad3629c12f37d4d9592921c14bc84cf6a"></a><a name="ad3629c12f37d4d9592921c14bc84cf6a"></a>trust_domain_id</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.13%" headers="mcps1.1.5.1.2 "><p id="a2b4c52c03e994fdebfb89d893d4783c1"><a name="a2b4c52c03e994fdebfb89d893d4783c1"></a><a name="a2b4c52c03e994fdebfb89d893d4783c1"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.93%" headers="mcps1.1.5.1.3 "><p id="a0f101baff64e42f2b2f4e7992cf53e11"><a name="a0f101baff64e42f2b2f4e7992cf53e11"></a><a name="a0f101baff64e42f2b2f4e7992cf53e11"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.78%" headers="mcps1.1.5.1.4 "><p id="afd114fc907224d158f657dbde21b7cc7"><a name="afd114fc907224d158f657dbde21b7cc7"></a><a name="afd114fc907224d158f657dbde21b7cc7"></a>ID of the delegated domain.</p>
    </td>
    </tr>
    <tr id="r80e0a5d33f4042f380f5dc2508e86d33"><td class="cellrowborder" valign="top" width="19.16%" headers="mcps1.1.5.1.1 "><p id="a11f4b492e6e54a35b90f5fa822632c68"><a name="a11f4b492e6e54a35b90f5fa822632c68"></a><a name="a11f4b492e6e54a35b90f5fa822632c68"></a>trust_domain_name</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.13%" headers="mcps1.1.5.1.2 "><p id="a2e4ea74a231e40a79a3d85832c48c2f7"><a name="a2e4ea74a231e40a79a3d85832c48c2f7"></a><a name="a2e4ea74a231e40a79a3d85832c48c2f7"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.93%" headers="mcps1.1.5.1.3 "><p id="ae068b7139057460cb86f4b8558642212"><a name="ae068b7139057460cb86f4b8558642212"></a><a name="ae068b7139057460cb86f4b8558642212"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.78%" headers="mcps1.1.5.1.4 "><p id="a885ded2f854540519e8453ab8c140d13"><a name="a885ded2f854540519e8453ab8c140d13"></a><a name="a885ded2f854540519e8453ab8c140d13"></a>Name of the delegated domain.</p>
    </td>
    </tr>
    <tr id="rfff3a67faefa4a4d90ccc4d55117e826"><td class="cellrowborder" valign="top" width="19.16%" headers="mcps1.1.5.1.1 "><p id="a3d83a6e80abe424bb89c81a56a345db9"><a name="a3d83a6e80abe424bb89c81a56a345db9"></a><a name="a3d83a6e80abe424bb89c81a56a345db9"></a>description</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.13%" headers="mcps1.1.5.1.2 "><p id="a551138aae7ee4ffc8e5b18e8817ad4a3"><a name="a551138aae7ee4ffc8e5b18e8817ad4a3"></a><a name="a551138aae7ee4ffc8e5b18e8817ad4a3"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.93%" headers="mcps1.1.5.1.3 "><p id="a193994eeb3d54231a63b3f00f9c54356"><a name="a193994eeb3d54231a63b3f00f9c54356"></a><a name="a193994eeb3d54231a63b3f00f9c54356"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.78%" headers="mcps1.1.5.1.4 "><p id="a9898e931b68c425e925bbc45b62cabaa"><a name="a9898e931b68c425e925bbc45b62cabaa"></a><a name="a9898e931b68c425e925bbc45b62cabaa"></a>Description of an agency.</p>
    </td>
    </tr>
    <tr id="r2bcc39d4ccd44d5f960103b0078650dd"><td class="cellrowborder" valign="top" width="19.16%" headers="mcps1.1.5.1.1 "><p id="a331f9511108649f099fca4b621d2e652"><a name="a331f9511108649f099fca4b621d2e652"></a><a name="a331f9511108649f099fca4b621d2e652"></a>duration</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.13%" headers="mcps1.1.5.1.2 "><p id="a849d9919d2e24ccbb99e7c2540d9e6b8"><a name="a849d9919d2e24ccbb99e7c2540d9e6b8"></a><a name="a849d9919d2e24ccbb99e7c2540d9e6b8"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.93%" headers="mcps1.1.5.1.3 "><p id="a6e474dedf75c47aaa89707390041df4d"><a name="a6e474dedf75c47aaa89707390041df4d"></a><a name="a6e474dedf75c47aaa89707390041df4d"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.78%" headers="mcps1.1.5.1.4 "><p id="en-us_topic_0059029098_p332264614915"><a name="en-us_topic_0059029098_p332264614915"></a><a name="en-us_topic_0059029098_p332264614915"></a>Validity period of an agency. The default value is <strong id="b84235270615357"><a name="b84235270615357"></a><a name="b84235270615357"></a>null</strong>, indicating that the agency is permanently valid.</p>
    </td>
    </tr>
    <tr id="r47accea11d2a4656b5f59f9a91d4d0e4"><td class="cellrowborder" valign="top" width="19.16%" headers="mcps1.1.5.1.1 "><p id="a7952ac6cef1748f9b602370442dac4e6"><a name="a7952ac6cef1748f9b602370442dac4e6"></a><a name="a7952ac6cef1748f9b602370442dac4e6"></a>expire_time</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.13%" headers="mcps1.1.5.1.2 "><p id="acde65e73e5884215896fb0dfbacfd4d8"><a name="acde65e73e5884215896fb0dfbacfd4d8"></a><a name="acde65e73e5884215896fb0dfbacfd4d8"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.93%" headers="mcps1.1.5.1.3 "><p id="a233710e9c7a74a359805e3a792fe50eb"><a name="a233710e9c7a74a359805e3a792fe50eb"></a><a name="a233710e9c7a74a359805e3a792fe50eb"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.78%" headers="mcps1.1.5.1.4 "><p id="adc40a6e0b8434d50ac019a190bccf712"><a name="adc40a6e0b8434d50ac019a190bccf712"></a><a name="adc40a6e0b8434d50ac019a190bccf712"></a>Expiration time of an agency.</p>
    </td>
    </tr>
    <tr id="r4da6881b747348288637c6c1d8ec00e2"><td class="cellrowborder" valign="top" width="19.16%" headers="mcps1.1.5.1.1 "><p id="a7ec8cdeeb85a480c8cab8dd98d89e0e8"><a name="a7ec8cdeeb85a480c8cab8dd98d89e0e8"></a><a name="a7ec8cdeeb85a480c8cab8dd98d89e0e8"></a>create_time</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.13%" headers="mcps1.1.5.1.2 "><p id="a01610d2c42324f74afab101741bd4377"><a name="a01610d2c42324f74afab101741bd4377"></a><a name="a01610d2c42324f74afab101741bd4377"></a>Yes</p>
    </td>
    <td class="cellrowborder" valign="top" width="18.93%" headers="mcps1.1.5.1.3 "><p id="a04aed5dc54a746b4846d2044e0854bb8"><a name="a04aed5dc54a746b4846d2044e0854bb8"></a><a name="a04aed5dc54a746b4846d2044e0854bb8"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="43.78%" headers="mcps1.1.5.1.4 "><p id="a411673306f3d4621999f7fbd460d5612"><a name="a411673306f3d4621999f7fbd460d5612"></a><a name="a411673306f3d4621999f7fbd460d5612"></a>Time when an agency is created.</p>
    </td>
    </tr>
    </tbody>
    </table>


-   Sample response \(request successful\)

    ```
    {
      "agencies": [
        {
          "trust_domain_name": "exampledomain",
          "description": " testsfdas ",
          "trust_domain_id": "b3f266d0c08544a0859740de8b84e850",
          "id": "afca8ddf2e92469a8fd26a635da5206f",
          "duration": null,
          "create_time": "2017-01-04T09:09:15.000000",
          "expire_time": null,
          "domain_id": "0ae9c6993a2e47bb8c4c7a9bb8278d61",
          "name": "exampleagency"
        }
      ]
    }
    ```


-   Sample response \(request failed\)

    ```
    {
      "error": {
        "message": "You are not authorized to perform the requested action: identity:list_agencies",
        "code": 403,
        "title": "Forbidden"
      }
    }
    ```


## **Status Codes**<a name="s5265144bfc06480cb5006e53b414094b"></a>

<a name="t10316128f6d1479d8eb3c20842d6cb05"></a>
<table><thead align="left"><tr id="r41c0a862739b4129a1e7477f0148c7e2"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="a2d85218ca7f644028b00cf625ce46cec"><a name="a2d85218ca7f644028b00cf625ce46cec"></a><a name="a2d85218ca7f644028b00cf625ce46cec"></a><strong id="b842352706183230_3"><a name="b842352706183230_3"></a><a name="b842352706183230_3"></a>Status Code</strong></p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="ae7d197d8cff948488553163ca813095d"><a name="ae7d197d8cff948488553163ca813095d"></a><a name="ae7d197d8cff948488553163ca813095d"></a><strong id="b20601766145329_5"><a name="b20601766145329_5"></a><a name="b20601766145329_5"></a>Description</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="r41ba72042c6a484cbf3b90b8aa4c7f60"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="ac3b0732dbcb44954bd7c67a20b9752ed"><a name="ac3b0732dbcb44954bd7c67a20b9752ed"></a><a name="ac3b0732dbcb44954bd7c67a20b9752ed"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="ac4b9041eb5c746518c888bc5653d3e5b"><a name="ac4b9041eb5c746518c888bc5653d3e5b"></a><a name="ac4b9041eb5c746518c888bc5653d3e5b"></a>The request is successful.</p>
</td>
</tr>
<tr id="r4a7c11abcd714755aa9c7b10ead1e3bc"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a4cab802f9df940daaba760aa19116435"><a name="a4cab802f9df940daaba760aa19116435"></a><a name="a4cab802f9df940daaba760aa19116435"></a>401</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="aa922b46662de42e28dbe8b28f954c12c"><a name="aa922b46662de42e28dbe8b28f954c12c"></a><a name="aa922b46662de42e28dbe8b28f954c12c"></a>You must enter a username and password to access the requested page.</p>
</td>
</tr>
<tr id="r5637e9b3de70452f8811b285d3ee63f6"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a6153873f5cb54b94bc6f6ca0ef4c98ae"><a name="a6153873f5cb54b94bc6f6ca0ef4c98ae"></a><a name="a6153873f5cb54b94bc6f6ca0ef4c98ae"></a>403</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a5b992477df8a4cbba92d8c4bd8e5b355"><a name="a5b992477df8a4cbba92d8c4bd8e5b355"></a><a name="a5b992477df8a4cbba92d8c4bd8e5b355"></a>You are forbidden to access the requested page.</p>
</td>
</tr>
<tr id="row166461220388"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p206471620982"><a name="p206471620982"></a><a name="p206471620982"></a>404</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p564720201881"><a name="p564720201881"></a><a name="p564720201881"></a>The server could not find the requested page.</p>
</td>
</tr>
<tr id="r10c22aac01bf4282914d5c6811a28c0f"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="a5e6bd16dc1fb412ebf7aaa4b1dfc20eb"><a name="a5e6bd16dc1fb412ebf7aaa4b1dfc20eb"></a><a name="a5e6bd16dc1fb412ebf7aaa4b1dfc20eb"></a>500</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="a9efd6c5584d642b49f94fd416155ecca"><a name="a9efd6c5584d642b49f94fd416155ecca"></a><a name="a9efd6c5584d642b49f94fd416155ecca"></a>Failed to complete the request because of an internal service error.</p>
</td>
</tr>
</tbody>
</table>

