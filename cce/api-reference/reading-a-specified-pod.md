# Reading a Specified Pod<a name="cce_02_0036"></a>

## Function<a name="s71ad64c953904f0985921f05a66305f4"></a>

This API is used to query the details about a specified Pod object under a specified Namespace.

## URI<a name="sf5f1071056e347eb9822c210cfa0b051"></a>

GET /api/v1/namespaces/\{namespace\}/pods/\{name\}

[Table 1](#en-us_topic_0079614904_table61950116)  describes the parameters of this API.

**Table  1**  Parameter description

<a name="en-us_topic_0079614904_table61950116"></a>
<table><thead align="left"><tr id="en-us_topic_0079614904_row42466880"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614904_p17265247"><a name="en-us_topic_0079614904_p17265247"></a><a name="en-us_topic_0079614904_p17265247"></a>Name</p>
</th>
<th class="cellrowborder" valign="top" width="30.303030303030305%" id="mcps1.2.4.1.2"><p id="p25470926205834"><a name="p25470926205834"></a><a name="p25470926205834"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="36.36363636363636%" id="mcps1.2.4.1.3"><p id="p49879135205834"><a name="p49879135205834"></a><a name="p49879135205834"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614904_row1125057"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614904_p24020754"><a name="en-us_topic_0079614904_p24020754"></a><a name="en-us_topic_0079614904_p24020754"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614904_p66632916"><a name="en-us_topic_0079614904_p66632916"></a><a name="en-us_topic_0079614904_p66632916"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="36.36363636363636%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614904_p28557102"><a name="en-us_topic_0079614904_p28557102"></a><a name="en-us_topic_0079614904_p28557102"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
<tr id="en-us_topic_0079614904_row55687332"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614904_p14380054"><a name="en-us_topic_0079614904_p14380054"></a><a name="en-us_topic_0079614904_p14380054"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614904_p23933749"><a name="en-us_topic_0079614904_p23933749"></a><a name="en-us_topic_0079614904_p23933749"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="36.36363636363636%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614904_p59585512"><a name="en-us_topic_0079614904_p59585512"></a><a name="en-us_topic_0079614904_p59585512"></a>Object name and auth scope, such as for teams and projects.</p>
</td>
</tr>
<tr id="en-us_topic_0079614904_row66507565"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614904_p18403674"><a name="en-us_topic_0079614904_p18403674"></a><a name="en-us_topic_0079614904_p18403674"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614904_p14302607"><a name="en-us_topic_0079614904_p14302607"></a><a name="en-us_topic_0079614904_p14302607"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="36.36363636363636%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614904_p17660533"><a name="en-us_topic_0079614904_p17660533"></a><a name="en-us_topic_0079614904_p17660533"></a>Name of the Pod.</p>
</td>
</tr>
<tr id="r94dded79cd6b4b48a4f5f012fcdfd007"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614904_p865375652118"><a name="en-us_topic_0079614904_p865375652118"></a><a name="en-us_topic_0079614904_p865375652118"></a>exact</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="a5bdb3bb6b715429cb36a6898c2e06f45"><a name="a5bdb3bb6b715429cb36a6898c2e06f45"></a><a name="a5bdb3bb6b715429cb36a6898c2e06f45"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="36.36363636363636%" headers="mcps1.2.4.1.3 "><p id="a025c81775dbc47b7bf3cd51960572a98"><a name="a025c81775dbc47b7bf3cd51960572a98"></a><a name="a025c81775dbc47b7bf3cd51960572a98"></a>Should the export be exact. Exact export maintains cluster-specific fields like 'Namespace'.</p>
</td>
</tr>
<tr id="r3e5af34ff36848cb9e42855c1d173081"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="a194412d25ff14c699f54d9d578dc145f"><a name="a194412d25ff14c699f54d9d578dc145f"></a><a name="a194412d25ff14c699f54d9d578dc145f"></a>export</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="af85e4b0765f84fa29ebaf6149f3d014f"><a name="af85e4b0765f84fa29ebaf6149f3d014f"></a><a name="af85e4b0765f84fa29ebaf6149f3d014f"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="36.36363636363636%" headers="mcps1.2.4.1.3 "><p id="a5cc1c775e2d5462589fffa4ec954aa30"><a name="a5cc1c775e2d5462589fffa4ec954aa30"></a><a name="a5cc1c775e2d5462589fffa4ec954aa30"></a>Should this value be exported. Export strips fields that a user cannot specify.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="sae909138a6384d598a5abdab965f3b5f"></a>

N/A

## Response<a name="sfbfa68773c254ab2aa9a05ac4c2968bd"></a>

**Response parameters**:

For the description about response parameters, see  [Table 3](data-structure-of-response-parameters.md#en-us_topic_0079614930_table52931650).

**Example response**:

```
{ 
   "kind": "Pod", 
   "apiVersion": "v1", 
   "metadata": { 
     "name": "hello-world", 
     "namespace": "default", 
     "selfLink": "/api/v1/namespaces/default/pods/hello-world", 
     "uid": "1087023f-59ef-11e6-b444-286ed488fafe", 
     "resourceVersion": "152187", 
     "creationTimestamp": "2016-08-04T02:56:39Z", 
     "labels": { 
       "name": "brace" 
     } 
   }, 
   "spec": { 
     "volumes": [ 
       { 
         "name": "test", 
         "emptyDir": {} 
       }, 
       { 
         "name": "default-token-brnb9", 
         "secret": { 
           "secretName": "default-token-brnb9" 
         } 
       } 
     ], 
     "containers": [ 
       { 
         "name": "hello-world", 
         "image": "test:v1", 
         "env": [ 
           { 
             "name": "test1", 
             "value": "test1" 
           } 
         ], 
         "resources": {}, 
         "volumeMounts": [ 
           { 
             "name": "test", 
             "mountPath": "/tmp/foo" 
           }, 
       { 
             "name": "default-token-brnb9", 
             "readOnly": true, 
             "mountPath": "/var/run/secrets/kubernetes.io/serviceaccount" 
           } 
         ], 
         "terminationMessagePath": "/dev/termination-log", 
         "imagePullPolicy": "IfNotPresent" 
       } 
     ], 
     "restartPolicy": "Always", 
     "terminationGracePeriodSeconds": 30, 
     "dnsPolicy": "ClusterFirst", 
     "serviceAccountName": "default", 
     "serviceAccount": "default", 
     "nodeName": "127.0.0.1", 
     "securityContext": {} 
   }, 
   "status": { 
     "phase": "Running", 
     "conditions": [ 
       { 
         "type": "Ready", 
         "status": "True", 
         "lastProbeTime": null, 
         "lastTransitionTime": "2016-08-04T02:56:40Z" 
       } 
     ], 
     "hostIP": "127.0.0.1", 
     "podIP": "172.16.0.4", 
     "startTime": "2016-08-04T02:56:39Z", 
     "containerStatuses": [ 
       { 
         "name": "hello-world", 
         "state": { 
           "running": { 
             "startedAt": "2016-08-04T02:56:39Z" 
           } 
         }, 
         "lastState": {}, 
         "ready": true, 
         "restartCount": 0, 
         "image": "test:v1", 
         "imageID": "docker://sha256:b38119b54befb956986a4f5fb6f6eb79c9a1a4d94bbb8ad5fee82f5c1175e5b9", 
         "containerID": "docker://c1d60a8653c4df7362d330d6d9d7d630179a01ae64cc9b7aeae70369040e6d30" 
       } 
     ] 
   } 
 }
```

## Status Code<a name="s4baae12d06434a838dd91d75626b67a1"></a>

[Table 2](#en-us_topic_0079614904_table20680137)  describes the status code of this API.

**Table  2**  Status code

<a name="en-us_topic_0079614904_table20680137"></a>
<table><thead align="left"><tr id="en-us_topic_0079614904_row35122812"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p38215036205834"><a name="p38215036205834"></a><a name="p38215036205834"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p8410240205834"><a name="p8410240205834"></a><a name="p8410240205834"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614904_row43124371"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="en-us_topic_0079614904_p3413175"><a name="en-us_topic_0079614904_p3413175"></a><a name="en-us_topic_0079614904_p3413175"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="en-us_topic_0079614904_p8031722"><a name="en-us_topic_0079614904_p8031722"></a><a name="en-us_topic_0079614904_p8031722"></a>This operation succeeds, and a Pod resource object is returned.</p>
</td>
</tr>
</tbody>
</table>

For the description about status codes, see section  [Status Code](status-code.md).

