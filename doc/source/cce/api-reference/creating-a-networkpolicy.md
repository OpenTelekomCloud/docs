# Creating a NetworkPolicy<a name="cce_02_0276"></a>

## Function<a name="section1333055875"></a>

This API is used to create a NetworkPolicy.

## URL<a name="section114001717323"></a>

POST /apis/networking.k8s.io/v1/namespaces/\{namespace\}/networkpolicies

[Table 1](#table1420670321)  describes the parameters of this API.

**Table  1**  Parameter description

<a name="table1420670321"></a>
<table><thead align="left"><tr id="row13419167183218"><th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.1"><p id="p164191473326"><a name="p164191473326"></a><a name="p164191473326"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="17.169999999999998%" id="mcps1.2.4.1.2"><p id="p041910713219"><a name="p041910713219"></a><a name="p041910713219"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="60.61%" id="mcps1.2.4.1.3"><p id="p174195753211"><a name="p174195753211"></a><a name="p174195753211"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row94192783211"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p0419373326"><a name="p0419373326"></a><a name="p0419373326"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p114193703213"><a name="p114193703213"></a><a name="p114193703213"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p17419147153212"><a name="p17419147153212"></a><a name="p17419147153212"></a>Object name and auth scope, such as for teams and projects.</p>
</td>
</tr>
<tr id="row1541915711328"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p5419873324"><a name="p5419873324"></a><a name="p5419873324"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p7419167133218"><a name="p7419167133218"></a><a name="p7419167133218"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p941918773219"><a name="p941918773219"></a><a name="p941918773219"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
<tr id="row1442011716321"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p164190723212"><a name="p164190723212"></a><a name="p164190723212"></a>body</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p1941911703216"><a name="p1941911703216"></a><a name="p1941911703216"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p14419107123212"><a name="p14419107123212"></a><a name="p14419107123212"></a>See <a href="#d0e42951">Table 2</a>.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="section111265663810"></a>

**Request parameters**:

For the description about request parameters, see  [Table 2](#d0e42951).

**Table  2**  Request parameters

<a name="d0e42951"></a>
<table><thead align="left"><tr id="row29055885"><th class="cellrowborder" valign="top" width="22.222222222222225%" id="mcps1.2.5.1.1"><p id="p4716456"><a name="p4716456"></a><a name="p4716456"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="14.141414141414144%" id="mcps1.2.5.1.2"><p id="p46488660"><a name="p46488660"></a><a name="p46488660"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="20.202020202020204%" id="mcps1.2.5.1.3"><p id="p7485112"><a name="p7485112"></a><a name="p7485112"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="43.43434343434344%" id="mcps1.2.5.1.4"><p id="p2314365"><a name="p2314365"></a><a name="p2314365"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row772562671320"><td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.2.5.1.1 "><p id="p772532621317"><a name="p772532621317"></a><a name="p772532621317"></a>apiVersion</p>
</td>
<td class="cellrowborder" valign="top" width="14.141414141414144%" headers="mcps1.2.5.1.2 "><p id="p16725132617134"><a name="p16725132617134"></a><a name="p16725132617134"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20.202020202020204%" headers="mcps1.2.5.1.3 "><p id="p17725142619139"><a name="p17725142619139"></a><a name="p17725142619139"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="43.43434343434344%" headers="mcps1.2.5.1.4 "><p id="p1772519266135"><a name="p1772519266135"></a><a name="p1772519266135"></a>APIVersion defines the versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values.</p>
</td>
</tr>
<tr id="row63487140"><td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.2.5.1.1 "><p id="p14792753151115"><a name="p14792753151115"></a><a name="p14792753151115"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="14.141414141414144%" headers="mcps1.2.5.1.2 "><p id="p13790153101115"><a name="p13790153101115"></a><a name="p13790153101115"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20.202020202020204%" headers="mcps1.2.5.1.3 "><p id="p10789155381112"><a name="p10789155381112"></a><a name="p10789155381112"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="43.43434343434344%" headers="mcps1.2.5.1.4 "><p id="p978795341120"><a name="p978795341120"></a><a name="p978795341120"></a>Kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase.</p>
</td>
</tr>
<tr id="row36873674"><td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.2.5.1.1 "><p id="p6785175341110"><a name="p6785175341110"></a><a name="p6785175341110"></a>metadata</p>
</td>
<td class="cellrowborder" valign="top" width="14.141414141414144%" headers="mcps1.2.5.1.2 "><p id="p1378375321115"><a name="p1378375321115"></a><a name="p1378375321115"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20.202020202020204%" headers="mcps1.2.5.1.3 "><p id="p1578195321111"><a name="p1578195321111"></a><a name="p1578195321111"></a><a href="#en-us_topic_0079615000_table43837055">metadata</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="43.43434343434344%" headers="mcps1.2.5.1.4 "><p id="p1977810533112"><a name="p1977810533112"></a><a name="p1977810533112"></a>Standard object's metadata.</p>
</td>
</tr>
<tr id="row899203"><td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.2.5.1.1 "><p id="p1177617531118"><a name="p1177617531118"></a><a name="p1177617531118"></a>spec</p>
</td>
<td class="cellrowborder" valign="top" width="14.141414141414144%" headers="mcps1.2.5.1.2 "><p id="p4774175316112"><a name="p4774175316112"></a><a name="p4774175316112"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20.202020202020204%" headers="mcps1.2.5.1.3 "><p id="p157721753151112"><a name="p157721753151112"></a><a name="p157721753151112"></a><a href="#en-us_topic_0079615000_table58989182">spec</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="43.43434343434344%" headers="mcps1.2.5.1.4 "><p id="p19771175311119"><a name="p19771175311119"></a><a name="p19771175311119"></a>Specification of the desired behavior for this NetworkPolicy.</p>
</td>
</tr>
</tbody>
</table>

**Table  3**  Data structure of the metadata field

<a name="en-us_topic_0079615000_table43837055"></a>
<table><thead align="left"><tr id="en-us_topic_0079615000_row29476029"><th class="cellrowborder" valign="top" width="22%" id="mcps1.2.5.1.1"><p id="en-us_topic_0079615000_p38748148"><a name="en-us_topic_0079615000_p38748148"></a><a name="en-us_topic_0079615000_p38748148"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="19%" id="mcps1.2.5.1.2"><p id="p19758610205444"><a name="p19758610205444"></a><a name="p19758610205444"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="20%" id="mcps1.2.5.1.3"><p id="p56943584205444"><a name="p56943584205444"></a><a name="p56943584205444"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="39%" id="mcps1.2.5.1.4"><p id="p49027631205444"><a name="p49027631205444"></a><a name="p49027631205444"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615000_row51840373"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0079615000_p38320646"><a name="en-us_topic_0079615000_p38320646"></a><a name="en-us_topic_0079615000_p38320646"></a>annotations</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0079615000_p16964616"><a name="en-us_topic_0079615000_p16964616"></a><a name="en-us_topic_0079615000_p16964616"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0079615000_p31956642"><a name="en-us_topic_0079615000_p31956642"></a><a name="en-us_topic_0079615000_p31956642"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="en-us_topic_0079615000_p19441857"><a name="en-us_topic_0079615000_p19441857"></a><a name="en-us_topic_0079615000_p19441857"></a>Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects.</p>
</td>
</tr>
<tr id="r59e9b08f407d496eac092f809321b53f"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="aeefc6fe8fca8446685053b6d0902640e"><a name="aeefc6fe8fca8446685053b6d0902640e"></a><a name="aeefc6fe8fca8446685053b6d0902640e"></a>clusterName</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0079615000_p541213427308"><a name="en-us_topic_0079615000_p541213427308"></a><a name="en-us_topic_0079615000_p541213427308"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0079615000_p641274253010"><a name="en-us_topic_0079615000_p641274253010"></a><a name="en-us_topic_0079615000_p641274253010"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="a7814694051a0406dbbba95ba61cb3e8f"><a name="a7814694051a0406dbbba95ba61cb3e8f"></a><a name="a7814694051a0406dbbba95ba61cb3e8f"></a>The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request.</p>
</td>
</tr>
<tr id="row1243774431910"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p24375449197"><a name="p24375449197"></a><a name="p24375449197"></a>creationTimestamp</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p1943714418192"><a name="p1943714418192"></a><a name="p1943714418192"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p1243715444198"><a name="p1243715444198"></a><a name="p1243715444198"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p101482549231"><a name="p101482549231"></a><a name="p101482549231"></a>CreationTimestamp is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists.</p>
</td>
</tr>
<tr id="row141132424192"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p19113144212196"><a name="p19113144212196"></a><a name="p19113144212196"></a>deletionGracePeriodSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p1711354211191"><a name="p1711354211191"></a><a name="p1711354211191"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p11113942101915"><a name="p11113942101915"></a><a name="p11113942101915"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p71132042121912"><a name="p71132042121912"></a><a name="p71132042121912"></a>Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only.</p>
</td>
</tr>
<tr id="row73343395199"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p83341439191916"><a name="p83341439191916"></a><a name="p83341439191916"></a>deletionTimestamp</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p333433915197"><a name="p333433915197"></a><a name="p333433915197"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p1833493916193"><a name="p1833493916193"></a><a name="p1833493916193"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p159875142520"><a name="p159875142520"></a><a name="p159875142520"></a>DeletionTimestamp is RFC 3339 date and time at which this resource will be deleted. This field is set by the server when a graceful deletion is requested by the user, and is not directly settable by a client. The resource is expected to be deleted (no longer visible from resource lists, and not reachable by name) after the time in this field, once the finalizers list is empty. As long as the finalizers list contains items, deletion is blocked. Once the deletionTimestamp is set, this value may not be unset or be set further into the future, although it may be shortened or the resource may be deleted prior to this time. For example, a user may request that a pod is deleted in 30 seconds. The Kubelet will react by sending a graceful termination signal to the containers in the pod. After that 30 seconds, the Kubelet will send a hard termination signal (SIGKILL) to the container and after cleanup, remove the pod from the API. In the presence of network partitions, this object may still exist after this timestamp, until an administrator or automated process can determine the resource is fully terminated. If not set, graceful deletion of the object has not been requested. Populated by the system when a graceful deletion is requested. Read-only.</p>
</td>
</tr>
<tr id="row1323812362219"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p19238113682110"><a name="p19238113682110"></a><a name="p19238113682110"></a>finalizers</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p2238153619213"><a name="p2238153619213"></a><a name="p2238153619213"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p1023883616213"><a name="p1023883616213"></a><a name="p1023883616213"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p16238736112120"><a name="p16238736112120"></a><a name="p16238736112120"></a>Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed.</p>
</td>
</tr>
<tr id="row54415193223"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p84471992210"><a name="p84471992210"></a><a name="p84471992210"></a>generateName</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p154421962217"><a name="p154421962217"></a><a name="p154421962217"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p13441219182217"><a name="p13441219182217"></a><a name="p13441219182217"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p111961949132220"><a name="p111961949132220"></a><a name="p111961949132220"></a>GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server. If this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header). Applied only if Name is not specified.</p>
</td>
</tr>
<tr id="row14389026102214"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p1638912261228"><a name="p1638912261228"></a><a name="p1638912261228"></a>generation</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p138972692215"><a name="p138972692215"></a><a name="p138972692215"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p938919263228"><a name="p938919263228"></a><a name="p938919263228"></a>Integer</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p20389102617222"><a name="p20389102617222"></a><a name="p20389102617222"></a>A sequence number representing a specific generation of the desired state. Populated by the system. Read-only.</p>
</td>
</tr>
<tr id="row7286428132210"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p1628602842215"><a name="p1628602842215"></a><a name="p1628602842215"></a>initializers</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p528613288229"><a name="p528613288229"></a><a name="p528613288229"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p72861289222"><a name="p72861289222"></a><a name="p72861289222"></a><a href="data-structure-of-request-parameters.md#t693768b66dfa47239c0f155ad4dd18e8">initializers</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p6875616152317"><a name="p6875616152317"></a><a name="p6875616152317"></a>An initializer is a controller which enforces some system invariant at object creation time. This field is a list of initializers that have not yet acted on this object. If nil or empty, this object has been completely initialized. Otherwise, the object is considered uninitialized and is hidden (in list/watch and get calls) from clients that haven't explicitly asked to observe uninitialized objects. When an object is created, the system will populate this list with the current set of initializers. Only privileged users may set or modify this list. Once it is empty, it may not be modified further by any user.</p>
</td>
</tr>
<tr id="row2469153416235"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p14469163413236"><a name="p14469163413236"></a><a name="p14469163413236"></a>labels</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p147083418238"><a name="p147083418238"></a><a name="p147083418238"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p6470634132312"><a name="p6470634132312"></a><a name="p6470634132312"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p104717345234"><a name="p104717345234"></a><a name="p104717345234"></a>Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services.</p>
</td>
</tr>
<tr id="row9249184492313"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p1324912446231"><a name="p1324912446231"></a><a name="p1324912446231"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p12491442236"><a name="p12491442236"></a><a name="p12491442236"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p2024954412311"><a name="p2024954412311"></a><a name="p2024954412311"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p9249154482310"><a name="p9249154482310"></a><a name="p9249154482310"></a>Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated.</p>
</td>
</tr>
<tr id="row12444144010238"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p64441840152320"><a name="p64441840152320"></a><a name="p64441840152320"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p19444540122316"><a name="p19444540122316"></a><a name="p19444540122316"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p144417403230"><a name="p144417403230"></a><a name="p144417403230"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p3732154619242"><a name="p3732154619242"></a><a name="p3732154619242"></a>Namespace defines the space within each name must be unique. An empty namespace is equivalent to the "default" namespace, but "default" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty. Must be a DNS_LABEL. Cannot be updated.</p>
</td>
</tr>
<tr id="row461716372238"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p561717377234"><a name="p561717377234"></a><a name="p561717377234"></a>ownerReferences</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p12617133782317"><a name="p12617133782317"></a><a name="p12617133782317"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p261773702319"><a name="p261773702319"></a><a name="p261773702319"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p11617183710234"><a name="p11617183710234"></a><a name="p11617183710234"></a>List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller.</p>
</td>
</tr>
<tr id="row13222218257"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p53223217255"><a name="p53223217255"></a><a name="p53223217255"></a>resourceVersion</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p532215242511"><a name="p532215242511"></a><a name="p532215242511"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p12322321251"><a name="p12322321251"></a><a name="p12322321251"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p107851058122512"><a name="p107851058122512"></a><a name="p107851058122512"></a>An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources. Populated by the system. Read-only. Value must be treated as opaque by clients.</p>
</td>
</tr>
<tr id="row13173092511"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p101719017252"><a name="p101719017252"></a><a name="p101719017252"></a>selfLink</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p6173016255"><a name="p6173016255"></a><a name="p6173016255"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p81813052517"><a name="p81813052517"></a><a name="p81813052517"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p11811013257"><a name="p11811013257"></a><a name="p11811013257"></a>SelfLink is a URL representing this object. Populated by the system. Read-only.</p>
</td>
</tr>
<tr id="row12738145612247"><td class="cellrowborder" valign="top" width="22%" headers="mcps1.2.5.1.1 "><p id="p13738135616240"><a name="p13738135616240"></a><a name="p13738135616240"></a>uid</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.2 "><p id="p12738145682415"><a name="p12738145682415"></a><a name="p12738145682415"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.5.1.3 "><p id="p67382567242"><a name="p67382567242"></a><a name="p67382567242"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="39%" headers="mcps1.2.5.1.4 "><p id="p149248782613"><a name="p149248782613"></a><a name="p149248782613"></a>UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations. Populated by the system. Read-only.</p>
</td>
</tr>
</tbody>
</table>

**Table  4**  Data structure of the spec field

<a name="en-us_topic_0079615000_table58989182"></a>
<table><thead align="left"><tr id="en-us_topic_0079615000_row48974116"><th class="cellrowborder" valign="top" width="21.8%" id="mcps1.2.5.1.1"><p id="en-us_topic_0079615000_p7480498"><a name="en-us_topic_0079615000_p7480498"></a><a name="en-us_topic_0079615000_p7480498"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="19.17%" id="mcps1.2.5.1.2"><p id="p38367937205444"><a name="p38367937205444"></a><a name="p38367937205444"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="19.74%" id="mcps1.2.5.1.3"><p id="p20795188205444"><a name="p20795188205444"></a><a name="p20795188205444"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="39.290000000000006%" id="mcps1.2.5.1.4"><p id="p6688676205444"><a name="p6688676205444"></a><a name="p6688676205444"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615000_row59285030"><td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.2.5.1.1 "><p id="en-us_topic_0079615000_p37358106"><a name="en-us_topic_0079615000_p37358106"></a><a name="en-us_topic_0079615000_p37358106"></a>ingress</p>
</td>
<td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.2.5.1.2 "><p id="en-us_topic_0079615000_p6107739"><a name="en-us_topic_0079615000_p6107739"></a><a name="en-us_topic_0079615000_p6107739"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19.74%" headers="mcps1.2.5.1.3 "><p id="en-us_topic_0079615000_p24964816"><a name="en-us_topic_0079615000_p24964816"></a><a name="en-us_topic_0079615000_p24964816"></a><a href="#table1180112213109">NetworkPolicyIngressRule</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.2.5.1.4 "><p id="p97961317123012"><a name="p97961317123012"></a><a name="p97961317123012"></a>List of ingress rules to be applied to the selected pods. Traffic is allowed to a pod if there are no NetworkPolicies selecting the pod (and cluster policy otherwise allows the traffic), OR if the traffic source is the pod's local node, OR if the traffic matches at least one ingress rule across all of the NetworkPolicy objects whose podSelector matches the pod. If this field is empty then this NetworkPolicy does not allow any traffic (and serves solely to ensure that the pods it selects are isolated by default)</p>
</td>
</tr>
<tr id="r84d3b4cd4c354a7b8d2c2d8e643f2eb2"><td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.2.5.1.1 "><p id="a20c290dec91e461f9806ac7ddb64b32e"><a name="a20c290dec91e461f9806ac7ddb64b32e"></a><a name="a20c290dec91e461f9806ac7ddb64b32e"></a>podSelector</p>
</td>
<td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.2.5.1.2 "><p id="a792005b9cc9c4b62aa05ca6ba72edb1b"><a name="a792005b9cc9c4b62aa05ca6ba72edb1b"></a><a name="a792005b9cc9c4b62aa05ca6ba72edb1b"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19.74%" headers="mcps1.2.5.1.3 "><p id="a9fd3a2cf6b17488ebf787d90dcdd4806"><a name="a9fd3a2cf6b17488ebf787d90dcdd4806"></a><a name="a9fd3a2cf6b17488ebf787d90dcdd4806"></a><a href="#table1156984163517">LabelSelector</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.2.5.1.4 "><p id="aaca6cae38740430c8d9c48adc947545c"><a name="aaca6cae38740430c8d9c48adc947545c"></a><a name="aaca6cae38740430c8d9c48adc947545c"></a>Selects the pods to which this NetworkPolicy object applies. The array of ingress rules is applied to any pods selected by this field. Multiple network policies can select the same set of pods. In this case, the ingress rules for each are combined additively. This field is NOT optional and follows standard label selector semantics. An empty podSelector matches all pods in this namespace.</p>
</td>
</tr>
<tr id="row823812573016"><td class="cellrowborder" valign="top" width="21.8%" headers="mcps1.2.5.1.1 "><p id="p10323185414332"><a name="p10323185414332"></a><a name="p10323185414332"></a>policyTypes</p>
</td>
<td class="cellrowborder" valign="top" width="19.17%" headers="mcps1.2.5.1.2 "><p id="p52382510302"><a name="p52382510302"></a><a name="p52382510302"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19.74%" headers="mcps1.2.5.1.3 "><p id="p323813563014"><a name="p323813563014"></a><a name="p323813563014"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="39.290000000000006%" headers="mcps1.2.5.1.4 "><p id="p2023814519307"><a name="p2023814519307"></a><a name="p2023814519307"></a>List of rule types that the NetworkPolicy relates to. Valid options are Ingress, Egress, or Ingress,Egress. If this field is not specified, it will default based on the existence of Ingress or Egress rules; policies that contain an Egress section are assumed to affect Egress, and all policies (whether or not they contain an Ingress section) are assumed to affect Ingress. If you want to write an egress-only policy, you must explicitly specify policyTypes [ "Egress" ]. Likewise, if you want to write a policy that specifies that no egress is allowed, you must specify a policyTypes value that includes "Egress" (since such a policy would not include an Egress section and would otherwise default to just [ "Ingress" ]). This field is beta-level in 1.8</p>
</td>
</tr>
</tbody>
</table>

**Table  5**  Data structure of the NetworkPolicyIngressRule field

<a name="table1180112213109"></a>
<table><thead align="left"><tr id="row0816172217101"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="p178192022191014"><a name="p178192022191014"></a><a name="p178192022191014"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.2"><p id="p6822182211010"><a name="p6822182211010"></a><a name="p6822182211010"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="19%" id="mcps1.2.5.1.3"><p id="p128259227100"><a name="p128259227100"></a><a name="p128259227100"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="p17829202218107"><a name="p17829202218107"></a><a name="p17829202218107"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1083142219104"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p3833522101017"><a name="p3833522101017"></a><a name="p3833522101017"></a>from</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="p683532221013"><a name="p683532221013"></a><a name="p683532221013"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.3 "><p id="p9837422201016"><a name="p9837422201016"></a><a name="p9837422201016"></a><a href="#table1062420317129">Networkpolicypeer</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p15839722101013"><a name="p15839722101013"></a><a name="p15839722101013"></a>List of sources which should be able to access the pods selected for this rule. Items in this list are combined using a logical OR operation. If this field is empty or missing, this rule matches all sources (traffic not restricted by source). If this field is present and contains at least on item, this rule allows traffic only if the traffic matches at least one item in the from list.</p>
</td>
</tr>
<tr id="row4840142220103"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p08432228109"><a name="p08432228109"></a><a name="p08432228109"></a>ports</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="p14846222191019"><a name="p14846222191019"></a><a name="p14846222191019"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.3 "><p id="p752121821519"><a name="p752121821519"></a><a name="p752121821519"></a><a href="#table1882263321214">NetworkPolicyPort</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p10850722101014"><a name="p10850722101014"></a><a name="p10850722101014"></a>List of ports which should be made accessible on the pods selected for this rule. Each item in this list is combined using a logical OR. If this field is empty or missing, this rule matches all ports (traffic not restricted by port). If this field is present and contains at least one item, then this rule allows traffic only if the traffic matches at least one port in the list.</p>
</td>
</tr>
</tbody>
</table>

**Table  6**  Data structure of the LableSelector field

<a name="table1156984163517"></a>
<table><thead align="left"><tr id="row15701041358"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="p2027915147359"><a name="p2027915147359"></a><a name="p2027915147359"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.2"><p id="p428117143356"><a name="p428117143356"></a><a name="p428117143356"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="19%" id="mcps1.2.5.1.3"><p id="p928401414359"><a name="p928401414359"></a><a name="p928401414359"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="p11286111423514"><a name="p11286111423514"></a><a name="p11286111423514"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row657019418355"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p12570540357"><a name="p12570540357"></a><a name="p12570540357"></a>matchExpressions</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="p957074203517"><a name="p957074203517"></a><a name="p957074203517"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.3 "><p id="p11570347355"><a name="p11570347355"></a><a name="p11570347355"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p1557019411355"><a name="p1557019411355"></a><a name="p1557019411355"></a>matchExpressions is a list of label selector requirements. The requirements are ANDed.</p>
</td>
</tr>
<tr id="row757016493517"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p457017415350"><a name="p457017415350"></a><a name="p457017415350"></a>matchLabels</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="p057024183514"><a name="p057024183514"></a><a name="p057024183514"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.3 "><p id="p05701410355"><a name="p05701410355"></a><a name="p05701410355"></a>Object</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p9570154123518"><a name="p9570154123518"></a><a name="p9570154123518"></a>matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels map is equivalent to an element of matchExpressions, whose key field is "key", the operator is "In", and the values array contains only "value". The requirements are ANDed.</p>
</td>
</tr>
</tbody>
</table>

**Table  7**  Data structure of the NetworkPolicyPeer field

<a name="table1062420317129"></a>
<table><thead align="left"><tr id="row4635531171213"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="p106371031171216"><a name="p106371031171216"></a><a name="p106371031171216"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.2"><p id="p7640103118129"><a name="p7640103118129"></a><a name="p7640103118129"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="19%" id="mcps1.2.5.1.3"><p id="p1864323131219"><a name="p1864323131219"></a><a name="p1864323131219"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="p7647031131213"><a name="p7647031131213"></a><a name="p7647031131213"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row1065015312125"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p106531031101215"><a name="p106531031101215"></a><a name="p106531031101215"></a>namespaceSelector</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="p865513112129"><a name="p865513112129"></a><a name="p865513112129"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.3 "><p id="p12658123181216"><a name="p12658123181216"></a><a name="p12658123181216"></a><a href="#table1156984163517">LabelSelector</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p4662103171214"><a name="p4662103171214"></a><a name="p4662103171214"></a>Selects Namespaces using cluster scoped-labels. This matches all pods in all namespaces selected by this label selector. This field follows standard label selector semantics. If present but empty, this selector selects all namespaces.</p>
</td>
</tr>
<tr id="row8663153171215"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p1366617314122"><a name="p1366617314122"></a><a name="p1366617314122"></a>podSelector</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="p136681131131213"><a name="p136681131131213"></a><a name="p136681131131213"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.3 "><p id="p19669123191213"><a name="p19669123191213"></a><a name="p19669123191213"></a><a href="#table1156984163517">LabelSelector</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p111295542419"><a name="p111295542419"></a><a name="p111295542419"></a>This is a label selector which selects Pods in this namespace. This field follows standard label selector semantics. If present but empty, this selector selects all pods in this namespace.</p>
</td>
</tr>
</tbody>
</table>

**Table  8**  Data structure of the NetworkPolicyPort field

<a name="table1882263321214"></a>
<table><thead align="left"><tr id="row9835183313124"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="p283773311212"><a name="p283773311212"></a><a name="p283773311212"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="16%" id="mcps1.2.5.1.2"><p id="p158392033181214"><a name="p158392033181214"></a><a name="p158392033181214"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="19%" id="mcps1.2.5.1.3"><p id="p108411733111212"><a name="p108411733111212"></a><a name="p108411733111212"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="40%" id="mcps1.2.5.1.4"><p id="p684416332126"><a name="p684416332126"></a><a name="p684416332126"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row15848113311123"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p6145424122514"><a name="p6145424122514"></a><a name="p6145424122514"></a>port</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="p4853133101218"><a name="p4853133101218"></a><a name="p4853133101218"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.3 "><p id="p38575333129"><a name="p38575333129"></a><a name="p38575333129"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p1859233141213"><a name="p1859233141213"></a><a name="p1859233141213"></a>matchExpressions is a list of label selector requirements. The requirements are ANDed.</p>
</td>
</tr>
<tr id="row14861533111212"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p450583014251"><a name="p450583014251"></a><a name="p450583014251"></a>protocol</p>
</td>
<td class="cellrowborder" valign="top" width="16%" headers="mcps1.2.5.1.2 "><p id="p15865173341212"><a name="p15865173341212"></a><a name="p15865173341212"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.5.1.3 "><p id="p14869173321219"><a name="p14869173321219"></a><a name="p14869173321219"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="40%" headers="mcps1.2.5.1.4 "><p id="p5872163311214"><a name="p5872163311214"></a><a name="p5872163311214"></a>The protocol (TCP or UDP) which traffic must match. If not specified, this field defaults to TCP.</p>
</td>
</tr>
</tbody>
</table>

**Example request:**

```
{
	"apiVersion": "networking.k8s.io/v1",
	"kind": "NetworkPolicy",
	"metadata": {
		"name": "test-network-policy",
		"namespace": "default",
		"labels": {
			"app": "nginx"
		}
	},
	"spec": {
		"podSelector": {
			"matchLabels": {
				"app": "nginx"
			}
		},
		"ingress": [{
			"from": [{
				"podSelector": {
					"matchLabels": {
						"app": "naginx1"
					}
				}
			}],
			"ports": [{
				"protocol": "TCP",
				"port": 6379
			}]
		}]
	}
}
```

## Response<a name="section294685611597"></a>

**Response parameters:**

For the description about response parameters, see  [Table 2](#d0e42951).

**Example response:**

```
{
    "kind": "NetworkPolicy",
    "apiVersion": "networking.k8s.io/v1",
    "metadata": {
	    "name": "test-network-policy",
		"namespace": "default",
		"selfLink": "/apis/networking.k8s.io/v1/namespaces/default/networkpolicies/test-network-policy",
		"uid": "be347ddd-e8af-11e8-b187-fa163e3cca63",
		"resourceVersion": "213982",
		"generation": 1,
		"creationTimestamp": "2018-11-15T08:23:34Z",
            "labels": {
		"app": "nginx"
			}
	},
    "spec": {
	    "podSelector": {
		"matchLabels": {
		    "app": "nginx"
		    }
	    },
	    "ingress": [{
		"from": [{
		    "podSelector": {
		        "matchLabels": {
			    "app": "nginx1"
				    }
			    }
		}],
	    "ports": [{
	        "protocol": "TCP",
		"port": 6379
		}]
	    }],
	    "policyTypes":[
		"Ingress"
        ]
    }
}
```

## Status Code<a name="section7688181432015"></a>

[Table 9](#d0e43055)  describes the status code of this API.

**Table  9**  Status Code

<a name="d0e43055"></a>
<table><thead align="left"><tr id="row20813512"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p8172937"><a name="p8172937"></a><a name="p8172937"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p58028199"><a name="p58028199"></a><a name="p58028199"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2663689"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p14432280"><a name="p14432280"></a><a name="p14432280"></a>202</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p28164027"><a name="p28164027"></a><a name="p28164027"></a>Created</p>
</td>
</tr>
<tr id="row182071116185513"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p420920168551"><a name="p420920168551"></a><a name="p420920168551"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p112096169554"><a name="p112096169554"></a><a name="p112096169554"></a>OK</p>
</td>
</tr>
<tr id="row7451192017555"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p1145102075520"><a name="p1145102075520"></a><a name="p1145102075520"></a>202</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p16451202016550"><a name="p16451202016550"></a><a name="p16451202016550"></a>Accepted</p>
</td>
</tr>
</tbody>
</table>

For the description about error status codes, see  [Status Code](status-code.md).

