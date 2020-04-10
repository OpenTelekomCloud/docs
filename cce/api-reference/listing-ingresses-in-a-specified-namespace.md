# Listing Ingresses in a Specified Namespace<a name="cce_02_0264"></a>

## Function<a name="section53754776"></a>

This API is used to list Ingresses in a specified namespace.

## URI<a name="section14030938"></a>

GET /apis/extensions/v1beta1/namespaces/\{namespace\}/ingresses

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
<tbody><tr id="row19095777"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p3254085"><a name="p3254085"></a><a name="p3254085"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p62254326"><a name="p62254326"></a><a name="p62254326"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p9435611"><a name="p9435611"></a><a name="p9435611"></a>Object name and auth scope, such as for teams and projects.</p>
</td>
</tr>
<tr id="row20522133618302"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p1522836153011"><a name="p1522836153011"></a><a name="p1522836153011"></a>continue</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p10523163603012"><a name="p10523163603012"></a><a name="p10523163603012"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p1852311367308"><a name="p1852311367308"></a><a name="p1852311367308"></a>The continue option should be set when retrieving more results from the server. Since this value is server defined, clients may only use the continue value from a previous query result with identical query parameters (except for the value of continue) and the server may reject a continue value it does not recognize. If the specified continue value is no longer valid whether due to expiration (generally five to fifteen minutes) or a configuration change on the server, the server will respond with a 410 ResourceExpired error indicating the client must restart their list without the continue field. This field is not supported when watch is true. Clients may start a watch from the last resourceVersion value returned by the server and not miss any modifications.</p>
</td>
</tr>
<tr id="row624413343302"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p13244133414304"><a name="p13244133414304"></a><a name="p13244133414304"></a>fieldSelector</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p624483412306"><a name="p624483412306"></a><a name="p624483412306"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p133181535135111"><a name="p133181535135111"></a><a name="p133181535135111"></a>A selector to restrict the list of returned objects by their fields. Defaults to everything.</p>
</td>
</tr>
<tr id="row17811636"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p33456451"><a name="p33456451"></a><a name="p33456451"></a>includeUninitialized</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p25618043"><a name="p25618043"></a><a name="p25618043"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p78266485518"><a name="p78266485518"></a><a name="p78266485518"></a>If true, partially initialized resources are included in the response.</p>
</td>
</tr>
<tr id="row726513605214"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p32651362529"><a name="p32651362529"></a><a name="p32651362529"></a>labelSelector</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p42651667523"><a name="p42651667523"></a><a name="p42651667523"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p026514655219"><a name="p026514655219"></a><a name="p026514655219"></a>A selector to restrict the list of returned objects by their labels. Defaults to everything.</p>
</td>
</tr>
<tr id="row12294495524"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p8294159145215"><a name="p8294159145215"></a><a name="p8294159145215"></a>limit</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p62944918527"><a name="p62944918527"></a><a name="p62944918527"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p1986245813528"><a name="p1986245813528"></a><a name="p1986245813528"></a>limit is a maximum number of responses to return for a list call. If more items exist, the server will set the continue field on the list metadata to a value that can be used with the same initial query to retrieve the next set of results. Setting a limit may return fewer than the requested amount of items (up to zero items) in the event all requested objects are filtered out and clients should only use the presence of the continue field to determine whether more results are available. Servers may choose not to support the limit argument and will return all of the available results. If limit is specified and the continue field is empty, clients may assume that no more results are available. This field is not supported if watch is true.</p>
<p id="p11862958175215"><a name="p11862958175215"></a><a name="p11862958175215"></a>The server guarantees that the objects returned when using continue will be identical to issuing a single list call without a limit - that is, no objects created, modified, or deleted after the first request is issued will be included in any subsequent continued requests. This is sometimes referred to as a consistent snapshot, and ensures that a client that is using limit to receive smaller chunks of a very large result can ensure they see all possible objects. If objects are updated during a chunked list the version of the object that was present at the time the first list result was calculated is returned.</p>
</td>
</tr>
<tr id="row1295919395212"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p1795953195216"><a name="p1795953195216"></a><a name="p1795953195216"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p14959239527"><a name="p14959239527"></a><a name="p14959239527"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p095963165216"><a name="p095963165216"></a><a name="p095963165216"></a>If <em id="i181451410125315"><a name="i181451410125315"></a><a name="i181451410125315"></a>true</em>, then the output is pretty printed.</p>
</td>
</tr>
<tr id="row1217618188539"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p917681815533"><a name="p917681815533"></a><a name="p917681815533"></a>resourceVersion</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p717619188537"><a name="p717619188537"></a><a name="p717619188537"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p1117618181532"><a name="p1117618181532"></a><a name="p1117618181532"></a>When specified with a watch call, shows changes that occur after that particular version of a resource. Defaults to changes from the beginning of history. When specified for list: - if unset, then the result is returned from remote storage based on quorum-read flag; - if it is 0, then we simply return what we currently have in cache, no guarantee; - if set to non zero, then the result is at least as fresh as given rv.</p>
</td>
</tr>
<tr id="row262411209533"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p1062419204531"><a name="p1062419204531"></a><a name="p1062419204531"></a>timeoutSeconds</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p10624172015313"><a name="p10624172015313"></a><a name="p10624172015313"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p106249202539"><a name="p106249202539"></a><a name="p106249202539"></a>Timeout for the list/watch call.</p>
</td>
</tr>
<tr id="row15910162255313"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p18910822105320"><a name="p18910822105320"></a><a name="p18910822105320"></a>watch</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p991015228539"><a name="p991015228539"></a><a name="p991015228539"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p129103228535"><a name="p129103228535"></a><a name="p129103228535"></a>Watch for changes to the described resources and return them as a stream of add, update, and remove notifications. Specify resourceVersion.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="section18662134312520"></a>

N/A

## Response<a name="section1125154334817"></a>

**Response parameters:**

For the description about response parameters, see  [Table 2](creating-an-ingress.md#d0e42951).

**Example response:**

```
{
    "kind": "IngressList",
    "apiVersion": "extensions/v1beta1",
    "metadata": {
        "selfLink": "/apis/extensions/v1beta1/namespaces/default/ingresses",
        "resourceVersion": "1494741"
    },
    "items": [
        {
            "metadata": {
                "name": "ingress-test",
                "namespace": "default",
                "selfLink": "/apis/extensions/v1beta1/namespaces/default/ingresses/ingress-test",
                "uid": "29817662-7adb-11e8-a5f8-fa163e458c2a",
                "resourceVersion": "1494672",
                "generation": 1,
                "creationTimestamp": "2018-06-28T13:57:14Z",
                "labels": {
                    "isExternal": "true",
                    "zone": "data"
                },
                "annotations": {
                    "ingress.beta.kubernetes.io/role": "data",
                    "ingress.kubernetes.io/secure-backends": "false",
                    "kubernetes.io/elb.id": "203e27c4-ceaa-4bca-b652-6947f77d1ce0",
                    "kubernetes.io/elb.ip": "10.154.199.81",
                    "kubernetes.io/elb.port": "80",
                    "kubernetes.io/ingress.class": "public-elb",
                    "protocol": "HTTP"
                }
            },
            "spec": {
                "rules": [
                    {
                        "host": "test",
                        "http": {
                            "paths": [
                                {
                                    "path": "/sssss",
                                    "backend": {
                                        "serviceName": "ingress-test",
                                        "servicePort": 8086
                                    },
                                    "property": {
                                        "ingress.beta.kubernetes.io/url-match-mode": "STARTS_WITH"
                                    }
                                }
                            ]
                        }
                    }
                ]
            },
            "status": {
                "loadBalancer": {
                    "ingress": [
                        {
                            "ip": "10.154.199.81",
                            "hostname": "test"
                        }
                    ]
                }
            }
        }
    ]
}
```

## Status Code<a name="section991874063016"></a>

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
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p105909395615"><a name="p105909395615"></a><a name="p105909395615"></a>success</p>
</td>
</tr>
</tbody>
</table>

For the description about error status codes, see  [Status Code](status-code.md).

