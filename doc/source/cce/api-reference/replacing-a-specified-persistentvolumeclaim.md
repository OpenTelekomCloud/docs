# Replacing a Specified PersistentVolumeClaim<a name="cce_02_0070"></a>

## Function<a name="sa5928b0d99984d7081f2c931c933d69d"></a>

This API is used to replace a PersistentVolumeClaim in a specified namespace.

The following fields can be updated:

-   metadata.labels
-   metadata.generateName

## URI<a name="s87b8218f53d444f49f38d904a12edb17"></a>

PUT /api/v1/namespaces/\{namespace\}/persistentvolumeclaims/\{name\}

[Table 1](#tb472e3e9893d440e8123378d55bae83f)  describes the parameters of this API.

**Table  1**  Parameter description

<a name="tb472e3e9893d440e8123378d55bae83f"></a>
<table><thead align="left"><tr id="r9d44a43a0e2b4c249a00d113fb83ec02"><th class="cellrowborder" valign="top" width="22.06%" id="mcps1.2.4.1.1"><p id="a5b306c85a6024e728db73ca561e2601d"><a name="a5b306c85a6024e728db73ca561e2601d"></a><a name="a5b306c85a6024e728db73ca561e2601d"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="17.169999999999998%" id="mcps1.2.4.1.2"><p id="p2047943620171"><a name="p2047943620171"></a><a name="p2047943620171"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="60.77%" id="mcps1.2.4.1.3"><p id="p4822159920171"><a name="p4822159920171"></a><a name="p4822159920171"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="r8973bf87127645c6b482a034f8581e04"><td class="cellrowborder" valign="top" width="22.06%" headers="mcps1.2.4.1.1 "><p id="a1c5b00e82749496b9a5ce76266641a8e"><a name="a1c5b00e82749496b9a5ce76266641a8e"></a><a name="a1c5b00e82749496b9a5ce76266641a8e"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="ab83a23bf0acc4db0be0aba137dc173a5"><a name="ab83a23bf0acc4db0be0aba137dc173a5"></a><a name="ab83a23bf0acc4db0be0aba137dc173a5"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="60.77%" headers="mcps1.2.4.1.3 "><p id="af90d022586e74e73b19fe1d7d78f5ea2"><a name="af90d022586e74e73b19fe1d7d78f5ea2"></a><a name="af90d022586e74e73b19fe1d7d78f5ea2"></a>Name of the PersistentVolumeClaim.</p>
</td>
</tr>
<tr id="r4cd4f7f44d374e1ab56368e02debfd56"><td class="cellrowborder" valign="top" width="22.06%" headers="mcps1.2.4.1.1 "><p id="a7dd414a86f704898a67131ed07f488cd"><a name="a7dd414a86f704898a67131ed07f488cd"></a><a name="a7dd414a86f704898a67131ed07f488cd"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="a26b256f4f4f74a119a2460832bf7cf3f"><a name="a26b256f4f4f74a119a2460832bf7cf3f"></a><a name="a26b256f4f4f74a119a2460832bf7cf3f"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="60.77%" headers="mcps1.2.4.1.3 "><p id="adc067b71f30f407e85b8926683814f39"><a name="adc067b71f30f407e85b8926683814f39"></a><a name="adc067b71f30f407e85b8926683814f39"></a>Object name and auth scope, such as for teams and projects.</p>
</td>
</tr>
<tr id="r947f59587e6e4d3bbcc63201427d90f6"><td class="cellrowborder" valign="top" width="22.06%" headers="mcps1.2.4.1.1 "><p id="a2510fcb356b3400ab1a04f5c6c82a1e8"><a name="a2510fcb356b3400ab1a04f5c6c82a1e8"></a><a name="a2510fcb356b3400ab1a04f5c6c82a1e8"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="af00a18f9ab564e7088ab67cd2df9c4ac"><a name="af00a18f9ab564e7088ab67cd2df9c4ac"></a><a name="af00a18f9ab564e7088ab67cd2df9c4ac"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.77%" headers="mcps1.2.4.1.3 "><p id="a47770adf1d3c45af8939d3d07fd6aa5d"><a name="a47770adf1d3c45af8939d3d07fd6aa5d"></a><a name="a47770adf1d3c45af8939d3d07fd6aa5d"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="sea7dee5d358f49a39d539b20e6aaa64a"></a>

**Request parameters:**

For the description about request parameters, see  [Table 2](creating-a-persistentvolumeclaim.md#t8268aeafde034542ab17a36c7fca65c3).

**Example request:**

```
{
    "kind": "PersistentVolumeClaim",
    "apiVersion": "v1",
    "metadata": {
        "name": "db-mysql-0",
        "namespace": "default",
        "selfLink": "/api/v1/namespaces/default/persistentvolumeclaims/db-mysql-0",
        "uid": "f6585eb2-8cdd-11e8-a538-fa163e082286",
        "resourceVersion": "4198033",
        "creationTimestamp": "2018-07-21T12:02:38Z",
        "labels": {
            "failure-domain.beta.kubernetes.io/region": "eu-de",
            "failure-domain.beta.kubernetes.io/zone": "eu-de-01",
            "app":"mysql"
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
        "volumeName": "pvc-f6585eb2-8cdd-11e8-a538-fa163e082286",
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

## Response<a name="sa1c46b09ebf345e6bb23a1502709a639"></a>

**Response parameters:**

For the description about response parameters, see  [Table 2](creating-a-persistentvolumeclaim.md#t8268aeafde034542ab17a36c7fca65c3).

**Example response:**

```
{
    "kind": "PersistentVolumeClaim",
    "apiVersion": "v1",
    "metadata": {
        "name": "db-mysql-0",
        "namespace": "default",
        "selfLink": "/api/v1/namespaces/default/persistentvolumeclaims/db-mysql-0",
        "uid": "f6585eb2-8cdd-11e8-a538-fa163e082286",
        "resourceVersion": "4201550",
        "creationTimestamp": "2018-07-21T12:02:38Z",
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
        "volumeName": "pvc-f6585eb2-8cdd-11e8-a538-fa163e082286",
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

## Status Code<a name="sfa20934b9ee24b2fa016b29e7345d356"></a>

[Table 2](#t668f7dd3090a42978732e583cc84d7c0)  describes the status code of this API.

**Table  2**  Status code

<a name="t668f7dd3090a42978732e583cc84d7c0"></a>
<table><thead align="left"><tr id="rf6bc622186054c718b25b71fd3b36d83"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p408989920171"><a name="p408989920171"></a><a name="p408989920171"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p6284643120171"><a name="p6284643120171"></a><a name="p6284643120171"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="rb0025aac94e44cd181e28eea627b03c5"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="af7dba24c4dda4252bbbe016cee1a28e6"><a name="af7dba24c4dda4252bbbe016cee1a28e6"></a><a name="af7dba24c4dda4252bbbe016cee1a28e6"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="a9318460675b44b2085529a621c4b985a"><a name="a9318460675b44b2085529a621c4b985a"></a><a name="a9318460675b44b2085529a621c4b985a"></a>This operation succeeds, and a PersistentVolumeClaim resource object is returned.</p>
</td>
</tr>
</tbody>
</table>

For the description about error status codes, see  [Status Code](status-code.md).

