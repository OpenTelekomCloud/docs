# Listing APIResources of GroupVersion batch/v1<a name="cce_02_0196"></a>

## Function<a name="section40622221"></a>

This API is used to list APIResources of GroupVersion "batch/v1".

## URI<a name="section30055677"></a>

GET /apis/batch/v1

## Request<a name="section2065644"></a>

N/A.

## Response<a name="section18590804"></a>

**Response parameters**:

[Table 1](#d0e48039)  describes the response parameters.

**Table  1**  Parameter description

<a name="d0e48039"></a>
<table><thead align="left"><tr id="row48566246"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.4.1.1"><p id="p41551876"><a name="p41551876"></a><a name="p41551876"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30%" id="mcps1.2.4.1.2"><p id="p10258770"><a name="p10258770"></a><a name="p10258770"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="45%" id="mcps1.2.4.1.3"><p id="p25654008"><a name="p25654008"></a><a name="p25654008"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row64708767"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="p6918766"><a name="p6918766"></a><a name="p6918766"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="p23549198"><a name="p23549198"></a><a name="p23549198"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="p28436903"><a name="p28436903"></a><a name="p28436903"></a>Kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated.</p>
</td>
</tr>
<tr id="row54605536"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="p60972256"><a name="p60972256"></a><a name="p60972256"></a>groupVersion</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="p39805676"><a name="p39805676"></a><a name="p39805676"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="p3034349"><a name="p3034349"></a><a name="p3034349"></a>groupVersion specifies the API group and version in the form "group/version"</p>
</td>
</tr>
<tr id="row27309149"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.4.1.1 "><p id="p64557480"><a name="p64557480"></a><a name="p64557480"></a>resources</p>
</td>
<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.4.1.2 "><p id="p61773404"><a name="p61773404"></a><a name="p61773404"></a><a href="#d0e48089">resources</a> object</p>
</td>
<td class="cellrowborder" valign="top" width="45%" headers="mcps1.2.4.1.3 "><p id="p2763807"><a name="p2763807"></a><a name="p2763807"></a>Standard list resource</p>
</td>
</tr>
</tbody>
</table>

**Table  2**  Data structure of the resources field

<a name="d0e48089"></a>
<table><thead align="left"><tr id="row45778201"><th class="cellrowborder" valign="top" width="25.252525252525253%" id="mcps1.2.4.1.1"><p id="p17046778"><a name="p17046778"></a><a name="p17046778"></a>Parameter</p>
</th>
<th class="cellrowborder" valign="top" width="30.303030303030305%" id="mcps1.2.4.1.2"><p id="p38611809"><a name="p38611809"></a><a name="p38611809"></a>Type</p>
</th>
<th class="cellrowborder" valign="top" width="44.44444444444445%" id="mcps1.2.4.1.3"><p id="p40548787"><a name="p40548787"></a><a name="p40548787"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row63226330"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="p21059134"><a name="p21059134"></a><a name="p21059134"></a>categories</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="p28068294"><a name="p28068294"></a><a name="p28068294"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="p58939355"><a name="p58939355"></a><a name="p58939355"></a>categories is a list of the grouped resources this resource belongs to (e.g. 'all')</p>
</td>
</tr>
<tr id="row60692149"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="p17117064"><a name="p17117064"></a><a name="p17117064"></a>kind</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="p44304923"><a name="p44304923"></a><a name="p44304923"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="p31928982"><a name="p31928982"></a><a name="p31928982"></a>kind is the kind for the resource (e.g. 'Foo' is the kind for a resource 'foo')</p>
</td>
</tr>
<tr id="row18925386"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="p56561334"><a name="p56561334"></a><a name="p56561334"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="p18065309"><a name="p18065309"></a><a name="p18065309"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="p54003945"><a name="p54003945"></a><a name="p54003945"></a>name is the plural name of the resource.</p>
</td>
</tr>
<tr id="row16273465"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="p43082263"><a name="p43082263"></a><a name="p43082263"></a>namespaced</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="p2381"><a name="p2381"></a><a name="p2381"></a>Boolean</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="p192900"><a name="p192900"></a><a name="p192900"></a>namespaced indicates if a resource is namespaced or not.</p>
</td>
</tr>
<tr id="row1736103"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="p6406658"><a name="p6406658"></a><a name="p6406658"></a>shortNames</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="p49177265"><a name="p49177265"></a><a name="p49177265"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="p23935517"><a name="p23935517"></a><a name="p23935517"></a>shortNames is a list of suggested short names of the resource.</p>
</td>
</tr>
<tr id="row14093061"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="p687254"><a name="p687254"></a><a name="p687254"></a>singularName</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="p55667608"><a name="p55667608"></a><a name="p55667608"></a>String</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="p12782386"><a name="p12782386"></a><a name="p12782386"></a>singularName is the singular name of the resource. This allows clients to handle plural and singular opaquely. The singularName is more correct for reporting status on a single item and both singular and plural are allowed from the kubectl CLI interface.</p>
</td>
</tr>
<tr id="row47932616"><td class="cellrowborder" valign="top" width="25.252525252525253%" headers="mcps1.2.4.1.1 "><p id="p57336698"><a name="p57336698"></a><a name="p57336698"></a>verbs</p>
</td>
<td class="cellrowborder" valign="top" width="30.303030303030305%" headers="mcps1.2.4.1.2 "><p id="p13760985"><a name="p13760985"></a><a name="p13760985"></a>Array of strings</p>
</td>
<td class="cellrowborder" valign="top" width="44.44444444444445%" headers="mcps1.2.4.1.3 "><p id="p40897996"><a name="p40897996"></a><a name="p40897996"></a>verbs is a list of supported kube verbs (this includes get, list, watch, create, update, patch, delete, deletecollection, and proxy)</p>
</td>
</tr>
</tbody>
</table>

**Example response:**

```
{
    "kind": "APIResourceList",
    "apiVersion": "v1",
    "groupVersion": "batch/v1",
    "resources": [
        {
            "name": "jobs",
            "singularName": "",
            "namespaced": true,
            "kind": "Job",
            "verbs": [
                "create",
                "delete",
                "deletecollection",
                "get",
                "list",
                "patch",
                "update",
                "watch"
            ],
            "categories": [
                "all"
            ]
        },
        {
            "name": "jobs/status",
            "singularName": "",
            "namespaced": true,
            "kind": "Job",
            "verbs": [
                "get",
                "patch",
                "update"
            ]
        }
    ]
}
```

## Status Code<a name="section33099508"></a>

[Table 3](#d0e48190)  describes the status code of this API.

**Table  3**  Status code

<a name="d0e48190"></a>
<table><thead align="left"><tr id="row16910545"><th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.1"><p id="p27576874"><a name="p27576874"></a><a name="p27576874"></a>Status Code</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.2.3.1.2"><p id="p19134283"><a name="p19134283"></a><a name="p19134283"></a>Description</p>
</th>
</tr>
</thead>
<tbody><tr id="row6373085"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.1 "><p id="p46457863"><a name="p46457863"></a><a name="p46457863"></a>200</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.2.3.1.2 "><p id="p4990578"><a name="p4990578"></a><a name="p4990578"></a>This operation succeeds, and a list of APIResources is returned.</p>
</td>
</tr>
</tbody>
</table>

For the description about status codes, see  [Status Code](status-code.md).

