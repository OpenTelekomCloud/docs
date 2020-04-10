# Creating a Pod<a name="cce_02_0034"></a>

## Function<a name="scc86678262934086bfbe32385da35788"></a>

This API is used to create a Pod object under a specified Namespace.

## URI<a name="s83bc1fb06185462cb2e2665b169bc85c"></a>

POST /api/v1/namespaces/\{namespace\}/pods

[Table 1](#en-us_topic_0079615001_table32114614)  describes the parameters of this API.

**Table  1**  Parameter description

<a name="en-us_topic_0079615001_table32114614"></a>
<table><thead align="left"><tr id="en-us_topic_0079615001_row42303331"><th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.1"><p id="en-us_topic_0079615001_p4017754"><a name="en-us_topic_0079615001_p4017754"></a><a name="en-us_topic_0079615001_p4017754"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.2"><p id="p27173000203043"><a name="p27173000203043"></a><a name="p27173000203043"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.2.4.1.3"><p id="p53529377203043"><a name="p53529377203043"></a><a name="p53529377203043"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615001_row63986108"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079615001_p15492278"><a name="en-us_topic_0079615001_p15492278"></a><a name="en-us_topic_0079615001_p15492278"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079615001_p46914996"><a name="en-us_topic_0079615001_p46914996"></a><a name="en-us_topic_0079615001_p46914996"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079615001_p42018335"><a name="en-us_topic_0079615001_p42018335"></a><a name="en-us_topic_0079615001_p42018335"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
<tr id="en-us_topic_0079615001_row29042598"><td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.1 "><p id="en-us_topic_0079615001_p3640263"><a name="en-us_topic_0079615001_p3640263"></a><a name="en-us_topic_0079615001_p3640263"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.2 "><p id="en-us_topic_0079615001_p26425925"><a name="en-us_topic_0079615001_p26425925"></a><a name="en-us_topic_0079615001_p26425925"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.2.4.1.3 "><p id="en-us_topic_0079615001_p60125191"><a name="en-us_topic_0079615001_p60125191"></a><a name="en-us_topic_0079615001_p60125191"></a>Object name and auth scope, such as for teams and projects.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="en-us_topic_0079615001_d0e16631"></a>

**Request parameters**:

For the description about request parameters, see  [Table 3](data-structure-of-request-parameters.md#en-us_topic_0079614925_table60388168).

**Example request**:

```
{
    "apiVersion": "v1",
    "kind": "Pod",
    "metadata": {
        "labels": {
            "name": "pod-test"
        },
        "name": "pod-test"
    },
    "spec": {
        "containers": [
            {
                "image": "172.16.5.235:20202/test/nginx",
                "imagePullPolicy": "Always",
                "name": "test",
                "resources": {
                    "requests": {
                        "cpu": "100m"
                    }
                }
            }
        ],
        "imagePullSecrets": [
            {
                "name": "default-secret"
            }
        ],
        "restartPolicy": "Always"
    }
}
```

## Response<a name="s23649bc4d7154135b7153a5743022fcd"></a>

**Response parameters**:

For the description about response parameters, see the parameter description in  [Request](#en-us_topic_0079615001_d0e16631).

**Example response**:

```
{
    "kind": "Pod",
    "apiVersion": "v1",
    "metadata": {
        "name": "pod-test",
        "namespace": "default",
        "selfLink": "/api/v1/namespaces/default/pods/pod-test",
        "uid": "8917ec2a-fc20-11e7-9c3c-fa163eb8ad1a",
        "resourceVersion": "486125",
        "creationTimestamp": "2018-01-18T07:23:52Z",
        "labels": {
            "name": "pod-test"
        },
        "enable": true
    },
    "spec": {
        "volumes": [
            {
                "name": "default-token-512lg",
                "secret": {
                    "secretName": "default-token-512lg",
                    "defaultMode": 384
                }
            }
        ],
        "containers": [
            {
                "name": "test",
                "image": "172.16.5.235:20202/test/nginx",
                "resources": {
                    "requests": {
                        "cpu": "100m"
                    }
                },
                "volumeMounts": [
                    {
                        "name": "default-token-512lg",
                        "readOnly": true,
                        "mountPath": "/var/run/secrets/kubernetes.io/serviceaccount"
                    }
                ],
                "terminationMessagePath": "/dev/termination-log",
                "terminationMessagePolicy": "File",
                "imagePullPolicy": "Always"
            }
        ],
        "restartPolicy": "Always",
        "terminationGracePeriodSeconds": 30,
        "dnsPolicy": "ClusterFirst",
        "serviceAccountName": "default",
        "serviceAccount": "default",
        "securityContext": {},
        "imagePullSecrets": [
            {
                "name": "default-secret"
            }
        ],
        "schedulerName": "default-scheduler"
    },
    "status": {
        "phase": "Pending",
        "qosClass": "Burstable"
    }
}
```

## Status Code<a name="sbb2d9f14fc4a4197a3a609e7c568ab4d"></a>

[Table 2](#en-us_topic_0079615001_table20596071)  describes the status code of this API.

**Table  2**  Status code

<a name="en-us_topic_0079615001_table20596071"></a>
<table><thead align="left"><tr id="en-us_topic_0079615001_row9746163"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p57545694203043"><a name="p57545694203043"></a><a name="p57545694203043"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p30689603203043"><a name="p30689603203043"></a><a name="p30689603203043"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="en-us_topic_0079615001_row48621261"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="en-us_topic_0079615001_p46008046"><a name="en-us_topic_0079615001_p46008046"></a><a name="en-us_topic_0079615001_p46008046"></a>201</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="en-us_topic_0079615001_p35664277"><a name="en-us_topic_0079615001_p35664277"></a><a name="en-us_topic_0079615001_p35664277"></a>This operation succeeds, and a Pod resource object is returned.</p>
</td>
</tr>
</tbody>
</table>

For the description about status codes, see section  [Status Code](status-code.md).

