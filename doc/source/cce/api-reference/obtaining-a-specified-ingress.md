# Obtaining a Specified Ingress<a name="cce_02_0263"></a>

## Function<a name="section53754776"></a>

This API is used to read the specified Ingress.

## URI<a name="section14030938"></a>

GET /apis/extensions/v1beta1/namespaces/\{namespace\}/ingresses/\{name\}

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
<tbody><tr id="row10781191719208"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p19781117112019"><a name="p19781117112019"></a><a name="p19781117112019"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p578231710205"><a name="p578231710205"></a><a name="p578231710205"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p978261710207"><a name="p978261710207"></a><a name="p978261710207"></a>Name of the Ingress.</p>
</td>
</tr>
<tr id="row19095777"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p3254085"><a name="p3254085"></a><a name="p3254085"></a>namespace</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p62254326"><a name="p62254326"></a><a name="p62254326"></a>Yes</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p9435611"><a name="p9435611"></a><a name="p9435611"></a>Object name and auth scope, such as for teams and projects.</p>
</td>
</tr>
<tr id="row20522133618302"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p1522836153011"><a name="p1522836153011"></a><a name="p1522836153011"></a>exact</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p10523163603012"><a name="p10523163603012"></a><a name="p10523163603012"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p1852311367308"><a name="p1852311367308"></a><a name="p1852311367308"></a>Should the export be exact. Exact export maintains cluster-specific fields like <em id="i137019818451"><a name="i137019818451"></a><a name="i137019818451"></a>Namespace</em>.</p>
</td>
</tr>
<tr id="row624413343302"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p13244133414304"><a name="p13244133414304"></a><a name="p13244133414304"></a>export</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p624483412306"><a name="p624483412306"></a><a name="p624483412306"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p152441344307"><a name="p152441344307"></a><a name="p152441344307"></a>Should this value be exported. Export strips fields that a user cannot specify.</p>
</td>
</tr>
<tr id="row17811636"><td class="cellrowborder" valign="top" width="22.220000000000002%" headers="mcps1.2.4.1.1 "><p id="p33456451"><a name="p33456451"></a><a name="p33456451"></a>pretty</p>
</td>
<td class="cellrowborder" valign="top" width="17.169999999999998%" headers="mcps1.2.4.1.2 "><p id="p25618043"><a name="p25618043"></a><a name="p25618043"></a>No</p>
</td>
<td class="cellrowborder" valign="top" width="60.61%" headers="mcps1.2.4.1.3 "><p id="p61795587"><a name="p61795587"></a><a name="p61795587"></a>If 'true', then the output is pretty printed.</p>
</td>
</tr>
</tbody>
</table>

## Request<a name="section18662134312520"></a>

N/A

## Response<a name="section734599194717"></a>

**Response parameters:**

For the description about response parameters, see  [Table 2](creating-an-ingress.md#d0e42951).

**Example response:**

```
{
    "kind": "Ingress",
    "apiVersion": "extensions/v1beta1",
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
```

## Status Code<a name="section17621414112913"></a>

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
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p28164027"><a name="p28164027"></a><a name="p28164027"></a>success</p>
</td>
</tr>
</tbody>
</table>

For the description about error status codes, see  [Status Code](status-code.md).

