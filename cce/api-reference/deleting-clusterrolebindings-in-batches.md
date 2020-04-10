# Deleting ClusterRoleBindings in Batches<a name="cce_02_0298"></a>

## Function<a name="section132011335700"></a>

This API is used to delete a collection of ClusterRoleBindings.

## URL<a name="section18374414014"></a>

DELETE /apis/rbac.authorization.k8s.io/v1/clusterrolebindings

[Table 1](#d0e42906)  describes the parameters of this API.

**Table  1**  Parameter description

<a name="d0e42906"></a>
<table><thead align="left"><tr id="row10640301"><th class="cellrowborder" valign="top" width="22.220000000000002%" id="mcps1.2.4.1.1"><p id="p65652297517"><a name="p65652297517"></a><a name="p65652297517"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="17.169999999999998%" id="mcps1.2.4.1.2"><p id="p165661629135114"><a name="p165661629135114"></a><a name="p165661629135114"></a>Mandatory</p>
</th>
<th class="cellrowborder" valign="top" width="60.61%" id="mcps1.2.4.1.3"><p id="p14567629115114"><a name="p14567629115114"></a><a name="p14567629115114"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row17811636"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p33456451"><a name="p33456451"></a><a name="p33456451"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p25618043"><a name="p25618043"></a><a name="p25618043"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p61795587"><a name="p61795587"></a><a name="p61795587"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
<tr id="row324054917610"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p1124024920612"><a name="p1124024920612"></a><a name="p1124024920612"></a>continue</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p162415491767"><a name="p162415491767"></a><a name="p162415491767"></a>-</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p12411249269"><a name="p12411249269"></a><a name="p12411249269"></a>The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error indicating the client must restart their list without the continue field. This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.</p>
</td>
</tr>
<tr id="row8371453863"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p203719531862"><a name="p203719531862"></a><a name="p203719531862"></a>fieldSelector</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p337185317611"><a name="p337185317611"></a><a name="p337185317611"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p03815531069"><a name="p03815531069"></a><a name="p03815531069"></a>A selector to restrict the list of returned objects by their fields. Defaults to everything.</p>
</td>
</tr>
<tr id="row95502597616"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p10550165911618"><a name="p10550165911618"></a><a name="p10550165911618"></a>includeUninitialized</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p5550859960"><a name="p5550859960"></a><a name="p5550859960"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p1926516398711"><a name="p1926516398711"></a><a name="p1926516398711"></a>If true, partially initialized resources are included in the response.</p>
</td>
</tr>
<tr id="row1172212316137"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p1372217238131"><a name="p1372217238131"></a><a name="p1372217238131"></a>labelSelector</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p137223239131"><a name="p137223239131"></a><a name="p137223239131"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p12722152361313"><a name="p12722152361313"></a><a name="p12722152361313"></a>A selector to restrict the list of returned objects by their labels. Defaults to everything.</p>
</td>
</tr>
<tr id="row198884817818"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p08881481880"><a name="p08881481880"></a><a name="p08881481880"></a>limit</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p14888481680"><a name="p14888481680"></a><a name="p14888481680"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p4889148188"><a name="p4889148188"></a><a name="p4889148188"></a>limit is a maximum number of responses to return for a list call. If more items exist, the server will set the continue field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true. The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.</p>
</td>
</tr>
<tr id="row16889138585"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p388912812820"><a name="p388912812820"></a><a name="p388912812820"></a>resourceVersion</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p1888915810820"><a name="p1888915810820"></a><a name="p1888915810820"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p13889484813"><a name="p13889484813"></a><a name="p13889484813"></a>When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it's 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.</p>
</td>
</tr>
<tr id="row0889481784"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p11889148586"><a name="p11889148586"></a><a name="p11889148586"></a>timeoutSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p198891987812"><a name="p198891987812"></a><a name="p198891987812"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p364910501388"><a name="p364910501388"></a><a name="p364910501388"></a>Timeout for the list/watch call.</p>
</td>
</tr>
<tr id="row488916815820"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p178891816811"><a name="p178891816811"></a><a name="p178891816811"></a>watch</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p988968282"><a name="p988968282"></a><a name="p988968282"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p7889118385"><a name="p7889118385"></a><a name="p7889118385"></a>Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="section18662134312520"></a>

N/A

## Response<a name="section726119112252"></a>

**Response parameters:**

For the description about response parameters, see  [Table 2](creating-a-clusterrolebinding.md#d0e42951).

**Example response:**

```
{
    "kind" : "ClusterRoleBindingList",
    "apiVersion" : "rbac.authorization.k8s.io/v1",
    "metadata" : {
        "selfLink" : "/apis/rbac.authorization.k8s.io/v1/clusterrolebindings",
        "resourceVersion" : "4625"
    },
    "items" : [ {
        "metadata" : {
            "name" : "read-secrets-global",
            "selfLink" : "/apis/rbac.authorization.k8s.io/v1/clusterrolebindings/read-secrets-global",
            "uid" : "8e20ec38-f1e7-11e8-b449-fa163ec24e06",
            "resourceVersion" : "4625",
            "creationTimestamp" : "2018-11-27T01:55:45Z"
        },
        "subjects" : [ {
            "kind" : "Group",
            "apiGroup" : "rbac.authorization.k8s.io",
            "name" : "manager"
        } ],
        "roleRef" : {
            "apiGroup" : "rbac.authorization.k8s.io",
            "kind" : "ClusterRole",
            "name" : "secret-reader"
        }
    } ]
}
```

## Status Code<a name="section534515230266"></a>

[Table 2](#d0e43055)  describes the status code of this API.

**Table  2**  Status code

<a name="d0e43055"></a>
<table><thead align="left"><tr id="row20813512"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p8172937"><a name="p8172937"></a><a name="p8172937"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p58028199"><a name="p58028199"></a><a name="p58028199"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row2663689"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p14432280"><a name="p14432280"></a><a name="p14432280"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p0978454104816"><a name="p0978454104816"></a><a name="p0978454104816"></a>OK</p>
</td>
</tr>
</tbody>
</table>

For the description about error status codes, see  [Status Code](status-code.md).

