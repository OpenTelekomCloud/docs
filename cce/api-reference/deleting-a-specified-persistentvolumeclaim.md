# Deleting a Specified PersistentVolumeClaim<a name="cce_02_0068"></a>

## Function<a name="sdc08610ef8314ab09a5b279ba59294bc"></a>

This API is used to delete a PersistentVolumeClaim in a specified namespace.

## URI<a name="sc869e0507a5d4e9faa97547f45765876"></a>

DELETE  /api/v1/namespaces/\{namespace\}/persistentvolumeclaims/\{name\}

[Table 1](#t101edc7f76364f35a20a711cac4e7e02)  describes the parameters of this API.

**Table  1**  Parameter description

<a name="t101edc7f76364f35a20a711cac4e7e02"></a>
<table><thead align="left"><tr id="r187debc2c7c34469b9f2583f2eeb9928"><th class="cellrowborder" valign="top" width="20.369999999999997%" id="mcps1.2.4.1.1"><p id="a730c657a0f4643748672df8aae5ac8f9"><a name="a730c657a0f4643748672df8aae5ac8f9"></a><a name="a730c657a0f4643748672df8aae5ac8f9"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="17.54%" id="mcps1.2.4.1.2"><p id="p1012132753815"><a name="p1012132753815"></a><a name="p1012132753815"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="62.09%" id="mcps1.2.4.1.3"><p id="p21317272382"><a name="p21317272382"></a><a name="p21317272382"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="rd35b6f7dc57e485c83f6957833107cba"><td class="cellrowborder" valign="top" width="20.369999999999997%" headers="mcps1.2.4.1.1 "><p id="a28cc38f3119547b592dc91e1000a7517"><a name="a28cc38f3119547b592dc91e1000a7517"></a><a name="a28cc38f3119547b592dc91e1000a7517"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="17.54%" headers="mcps1.2.4.1.2 "><p id="a95bfd344105d4ebab55910f85a97dc35"><a name="a95bfd344105d4ebab55910f85a97dc35"></a><a name="a95bfd344105d4ebab55910f85a97dc35"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="62.09%" headers="mcps1.2.4.1.3 "><p id="ab985f967c6f94490a4b361584729c653"><a name="ab985f967c6f94490a4b361584729c653"></a><a name="ab985f967c6f94490a4b361584729c653"></a>Name of the PersistentVolumeClaim</p>
</td>
</tr>
<tr id="rcd79f787734e4b1ea19393086e0d375b"><td class="cellrowborder" valign="top" width="20.369999999999997%" headers="mcps1.2.4.1.1 "><p id="adde653272a1b46dea2847e736a370392"><a name="adde653272a1b46dea2847e736a370392"></a><a name="adde653272a1b46dea2847e736a370392"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="17.54%" headers="mcps1.2.4.1.2 "><p id="ab409c5ae31c74754a217fa95e74c0570"><a name="ab409c5ae31c74754a217fa95e74c0570"></a><a name="ab409c5ae31c74754a217fa95e74c0570"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="62.09%" headers="mcps1.2.4.1.3 "><p id="ae8c8eca27302446f8cfa3a2b8dde481a"><a name="ae8c8eca27302446f8cfa3a2b8dde481a"></a><a name="ae8c8eca27302446f8cfa3a2b8dde481a"></a>Object name and auth scope, such as for teams and projects.</p>
</td>
</tr>
<tr id="r9dde66d7099e4471b134e6a91a4b9ac3"><td class="cellrowborder" valign="top" width="20.369999999999997%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079615049_p620075391118"><a name="en-us_topic_0079615049_p620075391118"></a><a name="en-us_topic_0079615049_p620075391118"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="17.54%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079615049_p565547941118"><a name="en-us_topic_0079615049_p565547941118"></a><a name="en-us_topic_0079615049_p565547941118"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="62.09%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079615049_p175355641118"><a name="en-us_topic_0079615049_p175355641118"></a><a name="en-us_topic_0079615049_p175355641118"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
<tr id="r11b3dd0b982e4e78a1cb87a12b30f0e3"><td class="cellrowborder" valign="top" width="20.369999999999997%" headers="mcps1.2.4.1.1 "><p id="abc9c23c101404c82b8d9b4ae89d795a5"><a name="abc9c23c101404c82b8d9b4ae89d795a5"></a><a name="abc9c23c101404c82b8d9b4ae89d795a5"></a>gracePeriodSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="17.54%" headers="mcps1.2.4.1.2 "><p id="ab07b1d5d925a4b749b6650227f896f79"><a name="ab07b1d5d925a4b749b6650227f896f79"></a><a name="ab07b1d5d925a4b749b6650227f896f79"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="62.09%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079615049_p166287132138"><a name="en-us_topic_0079615049_p166287132138"></a><a name="en-us_topic_0079615049_p166287132138"></a>The duration in seconds before the object should be deleted. Value must be non-negative integer. The value zero indicates delete immediately. If this value is nil, the default grace period for the specified type will be used. Defaults to a per object value if not specified.</p>
</td>
</tr>
<tr id="r5b7add32b2624ea89cad862fc2f557f7"><td class="cellrowborder" valign="top" width="20.369999999999997%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079615049_p915302817133"><a name="en-us_topic_0079615049_p915302817133"></a><a name="en-us_topic_0079615049_p915302817133"></a>orphanDependents</p>
</td>
<td class="cellrowborder" valign="top" width="17.54%" headers="mcps1.2.4.1.2 "><p id="af990c0414a0f4cffa8a93df2ed505b39"><a name="af990c0414a0f4cffa8a93df2ed505b39"></a><a name="af990c0414a0f4cffa8a93df2ed505b39"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="62.09%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079615049_p115382812137"><a name="en-us_topic_0079615049_p115382812137"></a><a name="en-us_topic_0079615049_p115382812137"></a>Deprecated: please use the PropagationPolicy, this field will be deprecated in 1.7. Should the dependent objects be orphaned. If true/false, the "orphan" finalizer will be added to/removed from the object's finalizers list. Either this field or PropagationPolicy may be set, but not both.</p>
</td>
</tr>
<tr id="ra374123fff5543b784cfc69a57c520c7"><td class="cellrowborder" valign="top" width="20.369999999999997%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079615049_p878183016139"><a name="en-us_topic_0079615049_p878183016139"></a><a name="en-us_topic_0079615049_p878183016139"></a>propagationPolicy</p>
</td>
<td class="cellrowborder" valign="top" width="17.54%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079615049_p27823091319"><a name="en-us_topic_0079615049_p27823091319"></a><a name="en-us_topic_0079615049_p27823091319"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="62.09%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079615049_p197853091318"><a name="en-us_topic_0079615049_p197853091318"></a><a name="en-us_topic_0079615049_p197853091318"></a>Whether and how garbage collection will be performed. Either this field or OrphanDependents may be set, but not both. The default policy is decided by the existing finalizer set in the metadata.finalizers and the resource-specific default policy.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="sb038a48d22e547e3a9a0545b572cf8b6"></a>

**Request parameters:**

For the description about request parameters, see  [Table 2](deleting-an-endpoints-object.md#en-us_topic_0079614926_table29580916).

**Example request:**

```
{ 
   "kind": "DeleteOptions", 
   "apiVersion": "v1", 
   "gracePeriodSeconds": 0 
 }
```

## Response<a name="se3a9951114354928a0998dcc1d2e25fe"></a>

**Response parameters:**

For the description about response parameters, see  [Table 2](deleting-a-secret.md#table13766144711235).

**Example response:**

```
{
    "kind": "PersistentVolumeClaim",
    "apiVersion": "v1",
    "metadata": {
        "name": "db-mysql-0",
        "namespace": "default",
        "selfLink": "/api/v1/namespaces/default/persistentvolumeclaims/db-mysql-0",
        "uid": "9d070d77-8ce1-11e8-8ee0-fa163e49263c",
        "resourceVersion": "4202924",
        "creationTimestamp": "2018-07-21T12:28:46Z",
        "labels": {
            "app": "mysql",
            "failure-domain.beta.kubernetes.io/region": "eu-de",
            "failure-domain.beta.kubernetes.io/zone": "eu-de-01"
        },
        "annotations": {
            "pv.kubernetes.io/bind-completed": "yes",
            "pv.kubernetes.io/bound-by-controller": "yes",
            "volume.beta.kubernetes.io/storage-class": "sata",
            "volume.beta.kubernetes.io/storage-provisioner": "flexvolume-huawei.com/fuxivol"
        }
    },
    "spec": {
        "accessModes": [
            "ReadWriteMany"
        ],
        "resources": {
            "requests": {
                "storage": "5Gi"
            }
        },
        "volumeName": "pvc-9d070d77-8ce1-11e8-8ee0-fa163e49263c",
        "volumeNamespace": "default"
    },
    "status": {
        "phase": "Bound",
        "accessModes": [
            "ReadWriteMany"
        ],
        "capacity": {
            "storage": "5Gi"
        }
    }
}
```

## Status Code<a name="sa8b72c0600224440a2fe1daf83f5b73a"></a>

[Table 2](#t10fde947e6644cfa87987be473137d2b)  describes the status code of this API.

**Table  2**  Status code

<a name="t10fde947e6644cfa87987be473137d2b"></a>
<table><thead align="left"><tr id="ra98a80c0400848a18557491c3f9e4f64"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p8110102753818"><a name="p8110102753818"></a><a name="p8110102753818"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p10112627143814"><a name="p10112627143814"></a><a name="p10112627143814"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r3e3f40d0ede848c4bbbb7b4863b6af4c"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="a9e2f86eb816746e280d1ec69bef19894"><a name="a9e2f86eb816746e280d1ec69bef19894"></a><a name="a9e2f86eb816746e280d1ec69bef19894"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="a97163082ddd5447b884268416909cc62"><a name="a97163082ddd5447b884268416909cc62"></a><a name="a97163082ddd5447b884268416909cc62"></a>A PersistentVolumeClaim resource object is deleted successfully.</p>
</td>
</tr>
</tbody>
</table>

For the description about error status codes, see  [Status Code](status-code.md).

