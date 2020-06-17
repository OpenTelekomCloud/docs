# Delete All DaemonSets<a name="cce_02_0135"></a>

## Function<a name="section18947286"></a>

This API is used to delete collection of DaemonSet.

## URI<a name="section36307850"></a>

DELETE /apis/apps/v1/namespaces/\{namespace\}/daemonsets \(Supports only1.9\)

DELETE /apis/extensions/v1beta1/namespaces/\{namespace\}/daemonsets \(Compatible\)

[Table 1](#d0e32232)  describes the parameters of this API.

**Table  1**  Description

<a name="d0e32232"></a>
<table><thead align="left"><tr id="row47582154"><th class="cellrowborder" valign="top" width="21.21%" id="mcps1.2.4.1.1"><p id="p65652297517"><a name="p65652297517"></a><a name="p65652297517"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="19.189999999999998%" id="mcps1.2.4.1.2"><p id="p165661629135114"><a name="p165661629135114"></a><a name="p165661629135114"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="59.599999999999994%" id="mcps1.2.4.1.3"><p id="p14567629115114"><a name="p14567629115114"></a><a name="p14567629115114"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row50350818"><td class="cellrowborder" valign="top" width="21.21%" headers="mcps1.2.4.1.1 "><p id="p51884423"><a name="p51884423"></a><a name="p51884423"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.2 "><p id="p41888712"><a name="p41888712"></a><a name="p41888712"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.2.4.1.3 "><p id="p37542543"><a name="p37542543"></a><a name="p37542543"></a>Object name and auth scope, such as for teams and projects.</p>
</td>
</tr>
<tr id="row2338567"><td class="cellrowborder" valign="top" width="21.21%" headers="mcps1.2.4.1.1 "><p id="p55206223"><a name="p55206223"></a><a name="p55206223"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.2 "><p id="p42519055"><a name="p42519055"></a><a name="p42519055"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.2.4.1.3 "><p id="p21491440"><a name="p21491440"></a><a name="p21491440"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
<tr id="row59205236"><td class="cellrowborder" valign="top" width="21.21%" headers="mcps1.2.4.1.1 "><p id="p30894825"><a name="p30894825"></a><a name="p30894825"></a>fieldSelector</p>
</td>
<td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.2 "><p id="p19452882"><a name="p19452882"></a><a name="p19452882"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.2.4.1.3 "><p id="p32179608"><a name="p32179608"></a><a name="p32179608"></a>A selector to restrict the list of returned objects by their fields. Defaults to everything.</p>
</td>
</tr>
<tr id="row21181017"><td class="cellrowborder" valign="top" width="21.21%" headers="mcps1.2.4.1.1 "><p id="p37940788"><a name="p37940788"></a><a name="p37940788"></a>includeUninitialized</p>
</td>
<td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.2 "><p id="p53304992"><a name="p53304992"></a><a name="p53304992"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.2.4.1.3 "><p id="p3307243"><a name="p3307243"></a><a name="p3307243"></a>If true, partially initialized resources are included in the response.</p>
</td>
</tr>
<tr id="row29765193"><td class="cellrowborder" valign="top" width="21.21%" headers="mcps1.2.4.1.1 "><p id="p62170455"><a name="p62170455"></a><a name="p62170455"></a>labelSelector</p>
</td>
<td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.2 "><p id="p2642069"><a name="p2642069"></a><a name="p2642069"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.2.4.1.3 "><p id="p12681003"><a name="p12681003"></a><a name="p12681003"></a>A selector to restrict the list of returned objects by their labels. Defaults to everything.</p>
</td>
</tr>
<tr id="row47020167"><td class="cellrowborder" valign="top" width="21.21%" headers="mcps1.2.4.1.1 "><p id="p50537173"><a name="p50537173"></a><a name="p50537173"></a>resourceVersion</p>
</td>
<td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.2 "><p id="p66979216"><a name="p66979216"></a><a name="p66979216"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.2.4.1.3 "><p id="p56607391"><a name="p56607391"></a><a name="p56607391"></a>When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.</p>
</td>
</tr>
<tr id="row39704474"><td class="cellrowborder" valign="top" width="21.21%" headers="mcps1.2.4.1.1 "><p id="p61945795"><a name="p61945795"></a><a name="p61945795"></a>timeoutSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.2 "><p id="p51553460"><a name="p51553460"></a><a name="p51553460"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.2.4.1.3 "><p id="p15080726"><a name="p15080726"></a><a name="p15080726"></a>Timeout for the list/watch call.</p>
</td>
</tr>
<tr id="row1508808"><td class="cellrowborder" valign="top" width="21.21%" headers="mcps1.2.4.1.1 "><p id="p55104662"><a name="p55104662"></a><a name="p55104662"></a>watch</p>
</td>
<td class="cellrowborder" valign="top" width="19.189999999999998%" headers="mcps1.2.4.1.2 "><p id="p34292648"><a name="p34292648"></a><a name="p34292648"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="59.599999999999994%" headers="mcps1.2.4.1.3 "><p id="p26241127"><a name="p26241127"></a><a name="p26241127"></a>Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="section58335197"></a>

**Request parameters:**

For the description about request parameters, see  [Table 2](deleting-a-daemonset.md#table191461259175715).

**Example request:**

-   Deleting only the DaemonSet \(the pod is not deleted\):

    ```
    {
        "Kind": "DeleteOptions",
        "apiVersion": "v1",
        "propagationPolicy": "Orphan"
    }
    ```

-   Deleting the pod and then the DaemonSet:

    ```
    {
        "kind": "DeleteOptions",
        "apiVersion": "v1",
        "propagationPolicy": "Foreground"
    }
    ```

-   Deleting the DaemonSet and then the pod:

    ```
    {
        "kind": "DeleteOptions",
        "apiVersion": "v1",
        "propagationPolicy": "Background"
    }
    ```


## Response<a name="section55254728"></a>

**Response parameters:**

For the description about response parameters, see  [Table 2](creating-a-daemonset.md#d0e31376).

**Example response:**

```
{
    "kind": "DaemonSetList",
    "apiVersion": "extensions/v1beta1",
    "metadata": {
        "selfLink": "/apis/extensions/v1beta1/namespaces/ns-12130306-s/daemonsets",
        "resourceVersion": "419060"
    },
    "items": []
}
```

## Status Code<a name="section27530508"></a>

[Table 2](#d0e32361)  describes the status code of this API.

**Table  2**  Status code

<a name="d0e32361"></a>
<table><thead align="left"><tr id="row37455893"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p14028463"><a name="p14028463"></a><a name="p14028463"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p62563701"><a name="p62563701"></a><a name="p62563701"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row34495057"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p42636200"><a name="p42636200"></a><a name="p42636200"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p30980196"><a name="p30980196"></a><a name="p30980196"></a>Delete a DaemonSet resource object successfully.</p>
</td>
</tr>
</tbody>
</table>

For the description about error status codes, see  [Status Code](status-code.md).

