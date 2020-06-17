# Updating a Specified Node<a name="cce_02_0180"></a>

## Function<a name="section44508986"></a>

This API is used to update the specified Node.

The following fields can be updated:

-   metadata.selfLink
-   metadata.resourceVersion
-   metadata.creationTimestamp
-   metadata.name
-   metadata.namespace
-   metadata.labels

## URI<a name="section65036556"></a>

PATCH /api/v1/nodes/\{name\}

[Table 1](#d0e44992)  describes the parameters of this API.

**Table  1**  Description

<a name="d0e44992"></a>
<table><thead align="left"><tr id="row47118076"><th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.1"><p id="p65652297517"><a name="p65652297517"></a><a name="p65652297517"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="17.169999999999998%" id="mcps1.2.4.1.2"><p id="p165661629135114"><a name="p165661629135114"></a><a name="p165661629135114"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="60.61%" id="mcps1.2.4.1.3"><p id="p14567629115114"><a name="p14567629115114"></a><a name="p14567629115114"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row29746628"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p60666680"><a name="p60666680"></a><a name="p60666680"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p15054011"><a name="p15054011"></a><a name="p15054011"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p11415416"><a name="p11415416"></a><a name="p11415416"></a>Name of the Job.</p>
</td>
</tr>
<tr id="row42281790"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p2273005"><a name="p2273005"></a><a name="p2273005"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p49895749"><a name="p49895749"></a><a name="p49895749"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p15023853"><a name="p15023853"></a><a name="p15023853"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="section48458099"></a>

**Request parameters:**

For the description about the  **Content-Type**  field, see  [Patch Request Method Operation Description](patch-request-method-operation-description.md).

**Example request:**

```
Content-Type: application/merge-patch+json 
```

```
{
    "metadata": {
        "labels": {
            "node-12130306-key": "node-12130306-value"
        }
    }
}
```

## Response<a name="section33469711"></a>

**Response parameters:**

For the description about response parameters, see  [Table 2](creating-a-job.md#table8040885).

**Example response:**

```
{
    "kind": "Node",
    "apiVersion": "v1",
    "metadata": {
        "name": "192.168.0.197",
        "namespace": "default",
        "selfLink": "/api/v1/namespaces/default/nodes/192.168.0.197",
        "uid": "868ecebc-dc8e-11e7-9c19-fa163e2d897b",
        "resourceVersion": "417845",
        "creationTimestamp": "2017-12-09T03:10:35Z",
        "labels": {
            "beta.kubernetes.io/arch": "amd64",
            "beta.kubernetes.io/os": "linux",
            "kubernetes.io/hostname": "192.168.0.197",
            "node-12130306-key": "node-12130306-value",
            "os.architecture": "amd64",
            "os.name": "EulerOS_2.0_SP5",
            "os.version": "3.10.0-327.44.58.35.x86_64",
            "supportContainer": "true"
        },
        "annotations": {
            "alpha.kubernetes.io/provided-node-ip": "192.168.0.197",
            "node.alpha.kubernetes.io/ttl": "0"
        },
        "enable": true
    },
    "spec": {
        "externalID": "192.168.0.197",
        "loginSecret": {},
        "schedulerHints": {}
    },
    "status": {
        "capacity": {
            "cpu": "2",
            "memory": "3744212Ki",
            "pods": "110"
        },
        "allocatable": {
            "cpu": "2",
            "memory": "3641812Ki",
            "pods": "110"
        },
        "phase": "Running",
        "conditions": [
            {
                "type": "OutOfDisk",
                "status": "False",
                "lastHeartbeatTime": "2017-12-13T03:05:57Z",
                "lastTransitionTime": "2017-12-09T03:10:35Z",
                "reason": "KubeletHasSufficientDisk",
                "message": "kubelet has sufficient disk space available"
            },
            {
                "type": "MemoryPressure",
                "status": "False",
                "lastHeartbeatTime": "2017-12-13T03:05:57Z",
                "lastTransitionTime": "2017-12-09T03:10:35Z",
                "reason": "KubeletHasSufficientMemory",
                "message": "kubelet has sufficient memory available"
            },
            {
                "type": "NetworkCardNotFound",
                "status": "False",
                "lastHeartbeatTime": "2017-12-13T03:05:57Z",
                "lastTransitionTime": "2017-12-09T03:10:35Z",
                "reason": "NetworkCardFound",
                "message": "network card has found"
            },
            {
                "type": "DiskPressure",
                "status": "False",
                "lastHeartbeatTime": "2017-12-13T03:05:57Z",
                "lastTransitionTime": "2017-12-09T03:10:35Z",
                "reason": "KubeletHasNoDiskPressure",
                "message": "kubelet has no disk pressure"
            },
            {
                "type": "Ready",
                "status": "True",
                "lastHeartbeatTime": "2017-12-13T03:05:57Z",
                "lastTransitionTime": "2017-12-09T03:10:35Z",
                "reason": "KubeletReady",
                "message": "kubelet is posting ready status"
            }
        ],
        "addresses": [
            {
                "type": "InternalIP",
                "address": "192.168.0.197"
            },
            {
                "type": "Hostname",
                "address": "192.168.0.197"
            },
            {
                "type": "DataIP",
                "address": "192.168.0.197"
            }
        ],
        "daemonEndpoints": {
            "kubeletEndpoint": {
                "Port": 10250
            }
        },
        "nodeInfo": {
            "machineID": "6f7a744cc4094fea9ed9558f18f59093",
            "systemUUID": "E73BC002-0E0C-4166-8321-6FE46B5AD12D",
            "bootID": "747fd7db-1e6c-400b-a703-a1f43371f56f",
            "kernelVersion": "3.10.0-327.44.58.35.x86_64",
            "osImage": "EulerOS 2.0 (SP5)",
            "containerRuntimeVersion": "docker://1.11.2",
            "kubeletVersion": "v1.13.10-r0",
            "kubeProxyVersion": "v1.13.10-r0",
            "operatingSystem": "linux",
            "architecture": "amd64"
        },
        "images": [
            {
                "names": [
                    "canal-agent:2.5.T3.B020",
                    "canal-agent:latest"
                ],
                "sizeBytes": 461728195
            },
            {
                "names": [
                    "cfe-kubedns-amd64:2.11.25"
                ],
                "sizeBytes": 334909612
            },
            {
                "names": [
                    "cfe-exechealthz-amd64:2.11.25"
                ],
                "sizeBytes": 326663593
            },
            {
                "names": [
                    "cfe-kube-dnsmasq-amd64:2.11.25"
                ],
                "sizeBytes": 325558483
            },
            {
                "names": [
                    "euleros:2.2.5"
                ],
                "sizeBytes": 288596478
            },
            {
                "names": [
                    "172.16.5.235:20202/test/apache-php:latest"
                ],
                "sizeBytes": 244663227
            },
            {
                "names": [
                    "172.16.5.235:20202/test/redis:latest",
                    "172.16.5.235:20202/test/redis:v1"
                ],
                "sizeBytes": 109208225
            },
            {
                "names": [
                    "172.16.5.235:20202/lwx348993/mysql:v1"
                ],
                "sizeBytes": 108362139
            },
            {
                "names": [
                    "cfe-pause:2.11.25"
                ],
                "sizeBytes": 350164
            }
        ],
        "nodeState": {},
        "hostname": "node-v17.novalocal"
    }
}
```

## Status Code<a name="section32791945"></a>

[Table 2](#d0e45084)  describes the status code of this API.

**Table  2**  Status code

<a name="d0e45084"></a>
<table><thead align="left"><tr id="row62523568"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p31244286"><a name="p31244286"></a><a name="p31244286"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p47759248"><a name="p47759248"></a><a name="p47759248"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row43293903"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p17145250"><a name="p17145250"></a><a name="p17145250"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p46588018"><a name="p46588018"></a><a name="p46588018"></a>This operation succeeds, and a Node resource object is returned.</p>
</td>
</tr>
</tbody>
</table>

For the description about error status codes, see  [Status Code](status-code.md).

