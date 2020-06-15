# Replacing a Specified Pod<a name="cce_02_0037"></a>

## Function<a name="seb80de7886d64c79adcdf04cb6b8d3c6"></a>

This API is used to replace a pod in a specified namespace.

The following field can be updated: 

-   metadata.selfLink
-   metadata.resourceVersion
-   metadata.generation
-   metadata.creationTimestamp
-   metadata.deletionTimestamp
-   metadata.clusterName
-   metadata.generateName
-   metadata.labels
-   metadata.annotations
-   spec.initContainers\[\*\].image
-   spec.containers\[\*\].image
-   spec.activeDeadlineSeconds
-   spec.tolerations

Other parts cannot be updated.

## URI<a name="scc13338839174f99b35830d9cbad55b0"></a>

PUT /api/v1/namespaces/\{namespace\}/pods/\{name\}

[Table 1](#en-us_topic_0079614899_table9281763)  describes the parameters of this API.

**Table  1**  Parameter description

<a name="en-us_topic_0079614899_table9281763"></a>
<table><thead align="left"><tr id="en-us_topic_0079614899_row38637755"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079614899_p42650482"><a name="en-us_topic_0079614899_p42650482"></a><a name="en-us_topic_0079614899_p42650482"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p63097533201516"><a name="p63097533201516"></a><a name="p63097533201516"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p10626510201516"><a name="p10626510201516"></a><a name="p10626510201516"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614899_row61788479"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614899_p38810903"><a name="en-us_topic_0079614899_p38810903"></a><a name="en-us_topic_0079614899_p38810903"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614899_p56675452"><a name="en-us_topic_0079614899_p56675452"></a><a name="en-us_topic_0079614899_p56675452"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614899_p27308885"><a name="en-us_topic_0079614899_p27308885"></a><a name="en-us_topic_0079614899_p27308885"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
<tr id="en-us_topic_0079614899_row57612519"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614899_p36102430"><a name="en-us_topic_0079614899_p36102430"></a><a name="en-us_topic_0079614899_p36102430"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614899_p38615738"><a name="en-us_topic_0079614899_p38615738"></a><a name="en-us_topic_0079614899_p38615738"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614899_p40867107"><a name="en-us_topic_0079614899_p40867107"></a><a name="en-us_topic_0079614899_p40867107"></a>Object name and auth scope, such as for teams and projects.</p>
</td>
</tr>
<tr id="en-us_topic_0079614899_row32259648"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079614899_p62894662"><a name="en-us_topic_0079614899_p62894662"></a><a name="en-us_topic_0079614899_p62894662"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079614899_p61302861"><a name="en-us_topic_0079614899_p61302861"></a><a name="en-us_topic_0079614899_p61302861"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079614899_p66584700"><a name="en-us_topic_0079614899_p66584700"></a><a name="en-us_topic_0079614899_p66584700"></a>Name of the Pod.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="en-us_topic_0079614899_ref458607622"></a>

**Request parameters:**

For the description about request parameters, see  [Table 3](data-structure-of-response-parameters.md#en-us_topic_0079614930_table52931650).

**Example request:**

```
{ 
     "kind": "Pod", 
     "apiVersion": "v1", 
     "metadata": { 
         "name": "hello-world", 
         "namespace": "default", 
         "selfLink": "/api/v1/namespaces/default/pods/hello-world", 
         "uid": "84973056-5d3b-11e6-aeb9-286ed488fafe", 
         "resourceVersion": "3416", 
         "creationTimestamp": "2016-08-08T07:41:29Z", 
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
                 "name": "default-token-test2", 
                 "secret": { 
                     "secretName": "default-token-test2" 
                 } 
             } 
         ], 
         "containers": [ 
             { 
                 "name": "hello-world", 
                 "image": "beego:v1", 
                 "env": [ 
                     { 
                         "name": "cy", 
                         "value": "cy" 
                     } 
                 ], 
                 "resources": {}, 
                 "volumeMounts": [ 
                     { 
                         "name": "test", 
                         "mountPath": "/tmp/foo" 
                     }, 
                     { 
                         "name": "default-token-test2", 
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
                 "lastTransitionTime": "2016-08-08T07:41:29Z" 
             } 
         ], 
         "hostIP": "127.0.0.1", 
         "podIP": "172.16.0.4", 
         "startTime": "2016-08-08T07:41:29Z", 
         "containerStatuses": [ 
             { 
                 "name": "hello-world", 
                 "state": { 
                     "running": { 
                         "startedAt": "2016-08-08T07:41:29Z" 
                     } 
                 }, 
                 "lastState": {}, 
                 "ready": true, 
                 "restartCount": 0, 
                 "image": "test:v1", 
                 "imageID": "docker://sha256:b38119b54befb956986a4f5fb6f6eb79c9a1a4d94bbb8ad5fee82f5c1175e5b9", 
                 "containerID": "docker://ca6e4e70a4617701e3ef95f44426503d171ed23305a9de61e0198baa58822902" 
             } 
         ] 
     } 
 }
```

## Response<a name="sf7ea4cdd65584034bfd0c2083e4191b7"></a>

**Response parameters:**

For the description about response parameters, see  [Request](#en-us_topic_0079614899_ref458607622).

**Example response:**

```
    { 
   "kind": "Pod", 
   "apiVersion": "v1", 
   "metadata": { 
     "name": "hello-world", 
     "namespace": "default", 
     "selfLink": "/api/v1/namespaces/default/pods/hello-world", 
     "uid": "84973056-5d3b-11e6-aeb9-286ed488fafe", 
     "resourceVersion": "3472", 
     "creationTimestamp": "2016-08-08T07:41:29Z", 
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
         "name": "default-token-test2", 
         "secret": { 
           "secretName": "default-token-test2" 
         } 
       } 
     ], 
     "containers": [ 
       { 
         "name": "hello-world", 
         "image": "beego:v1", 
         "env": [ 
           { 
           "name": "cy", 
             "value": "cy" 
           } 
         ], 
         "resources": {}, 
         "volumeMounts": [ 
           { 
             "name": "test", 
             "mountPath": "/tmp/foo" 
           }, 
           { 
             "name": "default-token-test2", 
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
         "lastTransitionTime": "2016-08-08T07:41:29Z" 
       } 
     ], 
     "hostIP": "127.0.0.1", 
     "podIP": "172.16.0.4", 
     "startTime": "2016-08-08T07:41:29Z", 
     "containerStatuses": [ 
       { 
         "name": "hello-world", 
         "state": { 
           "running": { 
             "startedAt": "2016-08-08T07:41:29Z" 
           } 
         }, 
         "lastState": {}, 
         "ready": true, 
         "restartCount": 0, 
         "image": "test:v1", 
         "imageID": "docker://sha256:b38119b54befb956986a4f5fb6f6eb79c9a1a4d94bbb8ad5fee82f5c1175e5b9", 
         "containerID": "docker://ca6e4e70a4617701e3ef95f44426503d171ed23305a9de61e0198baa58822902" 
       } 
     ] 
   } 
 }
```

## Status Code<a name="scbd2111a9d7b41b58b8af7b555c8bb78"></a>

[Table 2](#en-us_topic_0079614899_table16427006)  describes the status code of this API.

**Table  2**  Status code

<a name="en-us_topic_0079614899_table16427006"></a>
<table><thead align="left"><tr id="en-us_topic_0079614899_row51117746"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p49567918201516"><a name="p49567918201516"></a><a name="p49567918201516"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p55578412201516"><a name="p55578412201516"></a><a name="p55578412201516"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079614899_row62776692"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="en-us_topic_0079614899_p51747272"><a name="en-us_topic_0079614899_p51747272"></a><a name="en-us_topic_0079614899_p51747272"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="en-us_topic_0079614899_p30779497"><a name="en-us_topic_0079614899_p30779497"></a><a name="en-us_topic_0079614899_p30779497"></a>This operation succeeds, and the JSON of a Pod object is returned.</p>
</td>
</tr>
</tbody>
</table>

For the description about error status codes, see  [Status Code](status-code.md).

