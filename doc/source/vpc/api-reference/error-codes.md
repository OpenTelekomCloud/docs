# Error Codes<a name="vpc_api_0003"></a>

## Description<a name="section25523120121746"></a>

If an error occurs when an API is called, error information is returned. This section describes the error information for VPC APIs \(excluding native OpenStack APIs\).

## Example of Returned Error Information<a name="section17199210121746"></a>

```
{
    "code": "VPC.0002",
    "message": "Available zone Name is null."
}
```

## Error Code Description<a name="section37734636121746"></a>

<a name="table6539068618568"></a>
<table><thead align="left"><tr id="row4038622718568"><th class="cellrowborder" valign="top" width="11.07%" id="mcps1.1.7.1.1"><p id="p5005893918568"><a name="p5005893918568"></a><a name="p5005893918568"></a><strong id="b58488247121454"><a name="b58488247121454"></a><a name="b58488247121454"></a>Module</strong></p>
</th>
<th class="cellrowborder" valign="top" width="12.27%" id="mcps1.1.7.1.2"><p id="p4721162910"><a name="p4721162910"></a><a name="p4721162910"></a><strong id="b170187709114474"><a name="b170187709114474"></a><a name="b170187709114474"></a>HTTP Status Code</strong></p>
</th>
<th class="cellrowborder" valign="top" width="12.740000000000002%" id="mcps1.1.7.1.3"><p id="p5285352818568"><a name="p5285352818568"></a><a name="p5285352818568"></a><strong>Error Code</strong></p>
</th>
<th class="cellrowborder" valign="top" width="18.91%" id="mcps1.1.7.1.4"><p id="p973434118568"><a name="p973434118568"></a><a name="p973434118568"></a><strong>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="14.01%" id="mcps1.1.7.1.5"><p id="p83051937597"><a name="p83051937597"></a><a name="p83051937597"></a><strong id="b84235270616424"><a name="b84235270616424"></a><a name="b84235270616424"></a>Error Message</strong></p>
</th>
<th class="cellrowborder" valign="top" width="31%" id="mcps1.1.7.1.6"><p id="p12344135618107"><a name="p12344135618107"></a><a name="p12344135618107"></a><strong id="b84235270616428"><a name="b84235270616428"></a><a name="b84235270616428"></a>Handling Measure</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row1164545218568"><td class="cellrowborder" rowspan="4" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p1361751693612"><a name="p1361751693612"></a><a name="p1361751693612"></a>Public</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p197219616919"><a name="p197219616919"></a><a name="p197219616919"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p375755218568"><a name="p375755218568"></a><a name="p375755218568"></a>VPC.0002</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p3592632518568"><a name="p3592632518568"></a><a name="p3592632518568"></a>The AZ is left blank.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p53051137097"><a name="p53051137097"></a><a name="p53051137097"></a>Available zone Name is null.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p9171742121019"><a name="p9171742121019"></a><a name="p9171742121019"></a>Verify whether the <strong id="b842352706201122"><a name="b842352706201122"></a><a name="b842352706201122"></a>availability_zone</strong> field in the request body for creating a subnet is empty.</p>
</td>
</tr>
<tr id="row5490147518568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p87211866911"><a name="p87211866911"></a><a name="p87211866911"></a>404</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1783452418568"><a name="p1783452418568"></a><a name="p1783452418568"></a>VPC.0003</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p3531034518568"><a name="p3531034518568"></a><a name="p3531034518568"></a>The VPC does not exist.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1130523713914"><a name="p1130523713914"></a><a name="p1130523713914"></a>VPC does not exist.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p101712042101016"><a name="p101712042101016"></a><a name="p101712042101016"></a>Check whether the VPC ID is correct or whether the VPC exists under the tenant.</p>
</td>
</tr>
<tr id="row4935765518568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p872117618913"><a name="p872117618913"></a><a name="p872117618913"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p3854711818568"><a name="p3854711818568"></a><a name="p3854711818568"></a>VPC.0004</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p3530884518568"><a name="p3530884518568"></a><a name="p3530884518568"></a>The status of the VPC is abnormal.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p153051371692"><a name="p153051371692"></a><a name="p153051371692"></a>VPC is not active, please try later.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1171124217107"><a name="p1171124217107"></a><a name="p1171124217107"></a>Try again later or contact technical support.</p>
</td>
</tr>
<tr id="row72451356101712"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p6246205619177"><a name="p6246205619177"></a><a name="p6246205619177"></a>401</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p9246165651718"><a name="p9246165651718"></a><a name="p9246165651718"></a>VPC.0009</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p62461456181712"><a name="p62461456181712"></a><a name="p62461456181712"></a>Real-name authentication fails.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p16246125611712"><a name="p16246125611712"></a><a name="p16246125611712"></a>real-name authentication fail.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1824605601711"><a name="p1824605601711"></a><a name="p1824605601711"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row19195507612"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p6160115516611"><a name="p6160115516611"></a><a name="p6160115516611"></a>Public</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p583215616287"><a name="p583215616287"></a><a name="p583215616287"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p183210616283"><a name="p183210616283"></a><a name="p183210616283"></a>VPC.0007</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p283218622812"><a name="p283218622812"></a><a name="p283218622812"></a>Inconsistent tenant IDs.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p7832116102818"><a name="p7832116102818"></a><a name="p7832116102818"></a>urlTenantId is not equal tokenTenantId</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p1783213618285"><a name="p1783213618285"></a><a name="p1783213618285"></a>The tenant ID in the URL is different from that parsed in the token.</p>
</td>
</tr>
<tr id="row1233414201673"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p7551181118544"><a name="p7551181118544"></a><a name="p7551181118544"></a>401</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p155511011155413"><a name="p155511011155413"></a><a name="p155511011155413"></a>VPC.0008</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p355281114541"><a name="p355281114541"></a><a name="p355281114541"></a>Invalid token.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p0552141125417"><a name="p0552141125417"></a><a name="p0552141125417"></a>Invalid token in the header.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p555210116547"><a name="p555210116547"></a><a name="p555210116547"></a>Check whether the token in the request header is valid.</p>
</td>
</tr>
<tr id="row112148301910"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p103653230435"><a name="p103653230435"></a><a name="p103653230435"></a>403</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p8381172314437"><a name="p8381172314437"></a><a name="p8381172314437"></a>VPC.2701</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p739052315435"><a name="p739052315435"></a><a name="p739052315435"></a>You do not have permission to perform this operation, or your account balance is insufficient.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p154061123114311"><a name="p154061123114311"></a><a name="p154061123114311"></a>Token not allowed to do this action.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p84163230436"><a name="p84163230436"></a><a name="p84163230436"></a>Check whether the account balance is insufficient or whether your account has been frozen.</p>
</td>
</tr>
<tr id="row3637672612183"><td class="cellrowborder" rowspan="2" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p124661255123"><a name="p124661255123"></a><a name="p124661255123"></a>Public</p>
<p id="p41216584121913"><a name="p41216584121913"></a><a name="p41216584121913"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p2858086212183"><a name="p2858086212183"></a><a name="p2858086212183"></a>403</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p3334849512183"><a name="p3334849512183"></a><a name="p3334849512183"></a>VPC.0010</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p1687357612183"><a name="p1687357612183"></a><a name="p1687357612183"></a>Insufficient permissions to make calls to the underlying system.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p2458245012183"><a name="p2458245012183"></a><a name="p2458245012183"></a>Rules on xx by ** disallowed by policy</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p4502146112183"><a name="p4502146112183"></a><a name="p4502146112183"></a>Obtain the required permissions.</p>
</td>
</tr>
<tr id="row46905098121913"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p50209011121913"><a name="p50209011121913"></a><a name="p50209011121913"></a>403</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p40398066121913"><a name="p40398066121913"></a><a name="p40398066121913"></a>VPC.2201</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p40241608121942"><a name="p40241608121942"></a><a name="p40241608121942"></a>Insufficient fine-grained permissions.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p38809358121913"><a name="p38809358121913"></a><a name="p38809358121913"></a>Policy doesn't allow &lt;x:x:x&gt; to be performed</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p56550266121913"><a name="p56550266121913"></a><a name="p56550266121913"></a>Obtain the required permissions.</p>
</td>
</tr>
<tr id="row4934415618568"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p3745367518568"><a name="p3745367518568"></a><a name="p3745367518568"></a>Creating a VPC</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p37211668914"><a name="p37211668914"></a><a name="p37211668914"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p1384882318568"><a name="p1384882318568"></a><a name="p1384882318568"></a>VPC.0101</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p4801283918568"><a name="p4801283918568"></a><a name="p4801283918568"></a>VPC parameters are incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p1430610372913"><a name="p1430610372913"></a><a name="p1430610372913"></a>Param is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p18171442121017"><a name="p18171442121017"></a><a name="p18171442121017"></a>Check whether the parameter values are valid based on the returned error message and API reference document.</p>
</td>
</tr>
<tr id="row2946236818568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p47211610913"><a name="p47211610913"></a><a name="p47211610913"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p3764160218568"><a name="p3764160218568"></a><a name="p3764160218568"></a>VPC.0114</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2907090818568"><a name="p2907090818568"></a><a name="p2907090818568"></a>The number of VPCs has reached the maximum allowed limit specified by the quota.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p73061371098"><a name="p73061371098"></a><a name="p73061371098"></a>Quota exceeded for resources: ['router'].</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1757878104411"><a name="p1757878104411"></a><a name="p1757878104411"></a>Clear VPC resources that no longer will be used or apply for expanding the VPC resource quota.</p>
</td>
</tr>
<tr id="row6031158618568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1172186499"><a name="p1172186499"></a><a name="p1172186499"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p5340030818568"><a name="p5340030818568"></a><a name="p5340030818568"></a>VPC.0115</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p3045771518568"><a name="p3045771518568"></a><a name="p3045771518568"></a>The VPC name already exists.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1830673714913"><a name="p1830673714913"></a><a name="p1830673714913"></a>The router name has exist.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p3171174210108"><a name="p3171174210108"></a><a name="p3171174210108"></a>Change the VPC name.</p>
</td>
</tr>
<tr id="row161511213104917"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p5774943518568"><a name="p5774943518568"></a><a name="p5774943518568"></a>Querying a VPC</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p101341020184917"><a name="p101341020184917"></a><a name="p101341020184917"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p11141132024915"><a name="p11141132024915"></a><a name="p11141132024915"></a>VPC.0101</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p71481720124915"><a name="p71481720124915"></a><a name="p71481720124915"></a>VPC parameters are incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p12155112019491"><a name="p12155112019491"></a><a name="p12155112019491"></a>getVpc error vpcId is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p8162320134916"><a name="p8162320134916"></a><a name="p8162320134916"></a>Ensure that the specified VPC ID is correct.</p>
</td>
</tr>
<tr id="row568398218568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1872115611911"><a name="p1872115611911"></a><a name="p1872115611911"></a>404/500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4719264818568"><a name="p4719264818568"></a><a name="p4719264818568"></a>VPC.0105</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p6450812518568"><a name="p6450812518568"></a><a name="p6450812518568"></a>The interface fails to invoke the background service.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1030620378915"><a name="p1030620378915"></a><a name="p1030620378915"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p201711642181017"><a name="p201711642181017"></a><a name="p201711642181017"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row4370221918568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p472296196"><a name="p472296196"></a><a name="p472296196"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p5021881618568"><a name="p5021881618568"></a><a name="p5021881618568"></a>VPC.0106</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p4119227318568"><a name="p4119227318568"></a><a name="p4119227318568"></a>An error is returned for the failure to invoke the background service.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1230615374914"><a name="p1230615374914"></a><a name="p1230615374914"></a>get router is null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p13171239125513"><a name="p13171239125513"></a><a name="p13171239125513"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row137801020439"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p3150544818568"><a name="p3150544818568"></a><a name="p3150544818568"></a>Querying VPCs</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p1834472616439"><a name="p1834472616439"></a><a name="p1834472616439"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p9350112694312"><a name="p9350112694312"></a><a name="p9350112694312"></a>VPC.0101</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p13573262439"><a name="p13573262439"></a><a name="p13573262439"></a>Failed to query the VPCs.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p6364192618434"><a name="p6364192618434"></a><a name="p6364192618434"></a>Query vpc list error.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p336922620432"><a name="p336922620432"></a><a name="p336922620432"></a>Check whether the parameter values are valid based on the returned error message.</p>
</td>
</tr>
<tr id="row3518614418568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p872218610916"><a name="p872218610916"></a><a name="p872218610916"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p180448018568"><a name="p180448018568"></a><a name="p180448018568"></a>VPC.0105</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1194516818568"><a name="p1194516818568"></a><a name="p1194516818568"></a>The interface fails to invoke the background service.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p9306337196"><a name="p9306337196"></a><a name="p9306337196"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p632611441551"><a name="p632611441551"></a><a name="p632611441551"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row4039765318568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p672217618917"><a name="p672217618917"></a><a name="p672217618917"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p5098446118568"><a name="p5098446118568"></a><a name="p5098446118568"></a>VPC.0106</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p3610069018568"><a name="p3610069018568"></a><a name="p3610069018568"></a>The response result of calls to the IaaS OpenStack system is null or empty.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1130612376912"><a name="p1130612376912"></a><a name="p1130612376912"></a>query routers or getList are null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p19498344115512"><a name="p19498344115512"></a><a name="p19498344115512"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row14911194513332"><td class="cellrowborder" rowspan="14" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p1072855118568"><a name="p1072855118568"></a><a name="p1072855118568"></a>Deleting a VPC</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p258882133411"><a name="p258882133411"></a><a name="p258882133411"></a>400/404</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p1159513210343"><a name="p1159513210343"></a><a name="p1159513210343"></a>VPC.0101</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p206012233417"><a name="p206012233417"></a><a name="p206012233417"></a>Invalid parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p177361608352"><a name="p177361608352"></a><a name="p177361608352"></a>Delete router error xx is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p176149203420"><a name="p176149203420"></a><a name="p176149203420"></a>Check whether the parameter values are valid based on the returned error message.</p>
</td>
</tr>
<tr id="row5647075618568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p167221661912"><a name="p167221661912"></a><a name="p167221661912"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p6370628218568"><a name="p6370628218568"></a><a name="p6370628218568"></a>VPC.0102</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p5993518918568"><a name="p5993518918568"></a><a name="p5993518918568"></a>The interface fails to obtain the routing resources.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1830616371917"><a name="p1830616371917"></a><a name="p1830616371917"></a>Delete router fail.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1172134261018"><a name="p1172134261018"></a><a name="p1172134261018"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row254579318568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p5722156495"><a name="p5722156495"></a><a name="p5722156495"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p488271718568"><a name="p488271718568"></a><a name="p488271718568"></a>VPC.0103</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p5995576418568"><a name="p5995576418568"></a><a name="p5995576418568"></a>The VPC cannot be deleted because it is being created.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p930614372911"><a name="p930614372911"></a><a name="p930614372911"></a>Resource status is busy, try it again later.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p517216428107"><a name="p517216428107"></a><a name="p517216428107"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row273097018568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1172286593"><a name="p1172286593"></a><a name="p1172286593"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1988204018568"><a name="p1988204018568"></a><a name="p1988204018568"></a>VPC.0104</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p6694138218568"><a name="p6694138218568"></a><a name="p6694138218568"></a>The VPC cannot be deleted because it contains subnets.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p103068371491"><a name="p103068371491"></a><a name="p103068371491"></a>Router contains subnets, please delete subnet first.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p131721842191019"><a name="p131721842191019"></a><a name="p131721842191019"></a>Delete the subnet in the VPC.</p>
</td>
</tr>
<tr id="row1659255017339"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1562731973412"><a name="p1562731973412"></a><a name="p1562731973412"></a>404/500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4633151913342"><a name="p4633151913342"></a><a name="p4633151913342"></a>VPC.0105</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p106393192348"><a name="p106393192348"></a><a name="p106393192348"></a>The interface fails to invoke the background service.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p126491519143416"><a name="p126491519143416"></a><a name="p126491519143416"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p165691910349"><a name="p165691910349"></a><a name="p165691910349"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row6560152618568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p19722261895"><a name="p19722261895"></a><a name="p19722261895"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1212340818568"><a name="p1212340818568"></a><a name="p1212340818568"></a>VPC.0107</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p4247198218568"><a name="p4247198218568"></a><a name="p4247198218568"></a>Failed to delete the VPC because it has firewalls associated.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p17306123713910"><a name="p17306123713910"></a><a name="p17306123713910"></a>Delete the firewall first before deleting the router.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p417274221016"><a name="p417274221016"></a><a name="p417274221016"></a>Delete the firewalls of the tenant first.</p>
</td>
</tr>
<tr id="row4670352218568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p9722196596"><a name="p9722196596"></a><a name="p9722196596"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p2488896218568"><a name="p2488896218568"></a><a name="p2488896218568"></a>VPC.0108</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p274005918568"><a name="p274005918568"></a><a name="p274005918568"></a>Failed to delete the VPC because it contains EIPs.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p9306937793"><a name="p9306937793"></a><a name="p9306937793"></a>Router is used not allow deleted.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p417294291019"><a name="p417294291019"></a><a name="p417294291019"></a>Delete EIPs of the tenant first.</p>
</td>
</tr>
<tr id="row2466053218568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p4722861915"><a name="p4722861915"></a><a name="p4722861915"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p5134603618568"><a name="p5134603618568"></a><a name="p5134603618568"></a>VPC.0109</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p6538822418568"><a name="p6538822418568"></a><a name="p6538822418568"></a>Failed to delete the VPC because one or more VPNs have been created for it.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p930633711914"><a name="p930633711914"></a><a name="p930633711914"></a>Router is used not allow deleted.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p6172114271010"><a name="p6172114271010"></a><a name="p6172114271010"></a>Delete VPNs of the tenant.</p>
</td>
</tr>
<tr id="row5162311118568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p2072216898"><a name="p2072216898"></a><a name="p2072216898"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p2072244918568"><a name="p2072244918568"></a><a name="p2072244918568"></a>VPC.0110</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p79682818568"><a name="p79682818568"></a><a name="p79682818568"></a>The VPC cannot be deleted because its status is unstable.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1330616371599"><a name="p1330616371599"></a><a name="p1330616371599"></a>deleteDefaultNetworkFromRouter router status is invalid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p317274211105"><a name="p317274211105"></a><a name="p317274211105"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row717145718568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p17722261912"><a name="p17722261912"></a><a name="p17722261912"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4401716818568"><a name="p4401716818568"></a><a name="p4401716818568"></a>VPC.0111</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p862085118568"><a name="p862085118568"></a><a name="p862085118568"></a>An internal VPC exception occurs.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1930611371393"><a name="p1930611371393"></a><a name="p1930611371393"></a>Database Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p8172134231017"><a name="p8172134231017"></a><a name="p8172134231017"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row1047880018568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p57221061894"><a name="p57221061894"></a><a name="p57221061894"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4347646118568"><a name="p4347646118568"></a><a name="p4347646118568"></a>VPC.0112</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p3193243418568"><a name="p3193243418568"></a><a name="p3193243418568"></a>The VPC cannot be deleted because it contains security groups.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p73061037499"><a name="p73061037499"></a><a name="p73061037499"></a>Delete the securitygroup first before deleting the router.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p141722422101"><a name="p141722422101"></a><a name="p141722422101"></a>Delete security groups of the tenant.</p>
</td>
</tr>
<tr id="row6351755110243"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1672218613912"><a name="p1672218613912"></a><a name="p1672218613912"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4464803110243"><a name="p4464803110243"></a><a name="p4464803110243"></a>VPC.0118</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p5972077610243"><a name="p5972077610243"></a><a name="p5972077610243"></a>The VPC cannot be deleted because it contains load balancers.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p33061374913"><a name="p33061374913"></a><a name="p33061374913"></a>ELB exists under this router, delete ELB firstly.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p917284261014"><a name="p917284261014"></a><a name="p917284261014"></a>Delete load balancers in the VPC.</p>
</td>
</tr>
<tr id="row2942461410425"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p127224610913"><a name="p127224610913"></a><a name="p127224610913"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p3458352910425"><a name="p3458352910425"></a><a name="p3458352910425"></a>VPC.0119</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p4980247310425"><a name="p4980247310425"></a><a name="p4980247310425"></a>An error occurred when the VPC service makes calls to the ELB service.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p93067371299"><a name="p93067371299"></a><a name="p93067371299"></a>ELB Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p31726425109"><a name="p31726425109"></a><a name="p31726425109"></a>Check whether the ELB service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row1895645618568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1772217612912"><a name="p1772217612912"></a><a name="p1772217612912"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p5907793318568"><a name="p5907793318568"></a><a name="p5907793318568"></a>VPC.0120</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p447281111056"><a name="p447281111056"></a><a name="p447281111056"></a>The VPC cannot be deleted because it contains extension routes.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p83063371797"><a name="p83063371797"></a><a name="p83063371797"></a>exroutes exists under this router, delete exroutes firstly.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p12172124261019"><a name="p12172124261019"></a><a name="p12172124261019"></a>Delete extension routes in the VPC.</p>
</td>
</tr>
<tr id="row19634124612269"><td class="cellrowborder" rowspan="5" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p3991030118568"><a name="p3991030118568"></a><a name="p3991030118568"></a>Updating a VPC</p>
<p id="p16611259122318"><a name="p16611259122318"></a><a name="p16611259122318"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p106346466265"><a name="p106346466265"></a><a name="p106346466265"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p4634746192612"><a name="p4634746192612"></a><a name="p4634746192612"></a>VPC.0101</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p1960143410308"><a name="p1960143410308"></a><a name="p1960143410308"></a>Invalid parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p234105023216"><a name="p234105023216"></a><a name="p234105023216"></a>Update router xx is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p147263414302"><a name="p147263414302"></a><a name="p147263414302"></a>Check whether the parameter values are valid based on the returned error message.</p>
</td>
</tr>
<tr id="row12550154462614"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p205501844112618"><a name="p205501844112618"></a><a name="p205501844112618"></a>404/500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p255074422612"><a name="p255074422612"></a><a name="p255074422612"></a>VPC.0105</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p574521615309"><a name="p574521615309"></a><a name="p574521615309"></a>The interface fails to invoke the background service.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p14752101653011"><a name="p14752101653011"></a><a name="p14752101653011"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p12759111613301"><a name="p12759111613301"></a><a name="p12759111613301"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row5103149318568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p07226614910"><a name="p07226614910"></a><a name="p07226614910"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1150893318568"><a name="p1150893318568"></a><a name="p1150893318568"></a>VPC.0113</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p5980835718568"><a name="p5980835718568"></a><a name="p5980835718568"></a>The VPC cannot be updated because the status of the VPC is abnormal.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p9306837892"><a name="p9306837892"></a><a name="p9306837892"></a>Router status is not active.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1917216426104"><a name="p1917216426104"></a><a name="p1917216426104"></a>Try again later or contact technical support.</p>
</td>
</tr>
<tr id="row140430618568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1772236198"><a name="p1772236198"></a><a name="p1772236198"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4663996218568"><a name="p4663996218568"></a><a name="p4663996218568"></a>VPC.0115</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1974059118568"><a name="p1974059118568"></a><a name="p1974059118568"></a>The VPC name already exists.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1530612371499"><a name="p1530612371499"></a><a name="p1530612371499"></a>The router name has exist.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p12172184212106"><a name="p12172184212106"></a><a name="p12172184212106"></a>Change the VPC name.</p>
</td>
</tr>
<tr id="row361065919235"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p11722861098"><a name="p11722861098"></a><a name="p11722861098"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4831771118568"><a name="p4831771118568"></a><a name="p4831771118568"></a>VPC.0117</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2142049018568"><a name="p2142049018568"></a><a name="p2142049018568"></a>The subnet parameters are invalid. The network segment of the VPC does not contain all those of the subnets.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p113061237799"><a name="p113061237799"></a><a name="p113061237799"></a>Cidr can not contain subnetList cidr.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1417214221010"><a name="p1417214221010"></a><a name="p1417214221010"></a>Change the CIDR block of the VPC.</p>
</td>
</tr>
<tr id="row5856668618568"><td class="cellrowborder" rowspan="5" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p18854294243"><a name="p18854294243"></a><a name="p18854294243"></a>Creating a subnet</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p19722206598"><a name="p19722206598"></a><a name="p19722206598"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p4628116218568"><a name="p4628116218568"></a><a name="p4628116218568"></a>VPC.0201</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p5778660918568"><a name="p5778660918568"></a><a name="p5778660918568"></a>Incorrect subnet parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p930615371795"><a name="p930615371795"></a><a name="p930615371795"></a>Subnet name is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p531613172711"><a name="p531613172711"></a><a name="p531613172711"></a>Check whether the parameter values are valid based on the returned error message and API reference document.</p>
</td>
</tr>
<tr id="row5031743918568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p167224620912"><a name="p167224620912"></a><a name="p167224620912"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4918078118568"><a name="p4918078118568"></a><a name="p4918078118568"></a>VPC.0202</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2422029918568"><a name="p2422029918568"></a><a name="p2422029918568"></a>An internal error occurs in the subnet.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p5306103714914"><a name="p5306103714914"></a><a name="p5306103714914"></a>Create subnet failed.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1617324281012"><a name="p1617324281012"></a><a name="p1617324281012"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row1665609918568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p107221462093"><a name="p107221462093"></a><a name="p107221462093"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p696679718568"><a name="p696679718568"></a><a name="p696679718568"></a>VPC.0203</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2743967518568"><a name="p2743967518568"></a><a name="p2743967518568"></a>The CIDR block of the subnet is not in the range of the VPC.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p9306143719915"><a name="p9306143719915"></a><a name="p9306143719915"></a>Subnet is not in the range of VPC.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p5173134241020"><a name="p5173134241020"></a><a name="p5173134241020"></a>Change the CIDR block of the subnet.</p>
</td>
</tr>
<tr id="row4563048718568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p8722361913"><a name="p8722361913"></a><a name="p8722361913"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p508199118568"><a name="p508199118568"></a><a name="p508199118568"></a>VPC.0204</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p898814418568"><a name="p898814418568"></a><a name="p898814418568"></a>The CIDR block of the subnet already exists in the VPC.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1630683718915"><a name="p1630683718915"></a><a name="p1630683718915"></a>The subnet has already existed in the VPC, or has been in conflict with the VPC subnet.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p12173204281011"><a name="p12173204281011"></a><a name="p12173204281011"></a>Change the CIDR block of the subnet.</p>
</td>
</tr>
<tr id="row066732011442"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p2668520194417"><a name="p2668520194417"></a><a name="p2668520194417"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p15668820124415"><a name="p15668820124415"></a><a name="p15668820124415"></a>VPC.0212</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p5668112094418"><a name="p5668112094418"></a><a name="p5668112094418"></a>Invalid subnet CIDR block.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p26681820174419"><a name="p26681820174419"></a><a name="p26681820174419"></a>The subnet cidr is not valid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p9668820154417"><a name="p9668820154417"></a><a name="p9668820154417"></a>Check whether the subnet CIDR block is valid.</p>
</td>
</tr>
<tr id="row1378443318568"><td class="cellrowborder" rowspan="2" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p4279724918568"><a name="p4279724918568"></a><a name="p4279724918568"></a>Querying a subnet</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p12722461797"><a name="p12722461797"></a><a name="p12722461797"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p4402511718568"><a name="p4402511718568"></a><a name="p4402511718568"></a>VPC.0201</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p926475018568"><a name="p926475018568"></a><a name="p926475018568"></a>Invalid subnet ID.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p113064374912"><a name="p113064374912"></a><a name="p113064374912"></a>Subnet ID is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p01731442111011"><a name="p01731442111011"></a><a name="p01731442111011"></a>Check whether the subnet ID is valid.</p>
</td>
</tr>
<tr id="row495312195518"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p12954192115514"><a name="p12954192115514"></a><a name="p12954192115514"></a>404/500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p119541921175512"><a name="p119541921175512"></a><a name="p119541921175512"></a>VPC.0202</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p595417219557"><a name="p595417219557"></a><a name="p595417219557"></a>Failed to query the subnet.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p195452117558"><a name="p195452117558"></a><a name="p195452117558"></a>Query subnet fail.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p5954321145512"><a name="p5954321145512"></a><a name="p5954321145512"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row1627389418568"><td class="cellrowborder" rowspan="2" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p4311705718568"><a name="p4311705718568"></a><a name="p4311705718568"></a>Querying subnets</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p56131834175619"><a name="p56131834175619"></a><a name="p56131834175619"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p3612334105613"><a name="p3612334105613"></a><a name="p3612334105613"></a>VPC.0201</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p1861103416564"><a name="p1861103416564"></a><a name="p1861103416564"></a>Failed to query the subnets.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p196101734155616"><a name="p196101734155616"></a><a name="p196101734155616"></a>Query subnets list error.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p13588123425616"><a name="p13588123425616"></a><a name="p13588123425616"></a>Check whether the parameter values are valid based on the returned error message.</p>
</td>
</tr>
<tr id="row08251726115516"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p187224618911"><a name="p187224618911"></a><a name="p187224618911"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p282074118568"><a name="p282074118568"></a><a name="p282074118568"></a>VPC.0202</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2715343218568"><a name="p2715343218568"></a><a name="p2715343218568"></a>Failed to query the subnets.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p103068378918"><a name="p103068378918"></a><a name="p103068378918"></a>List subnets error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1717354221016"><a name="p1717354221016"></a><a name="p1717354221016"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row3241191619710"><td class="cellrowborder" rowspan="8" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p035814437428"><a name="p035814437428"></a><a name="p035814437428"></a>Deleting a subnet</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p1398553418712"><a name="p1398553418712"></a><a name="p1398553418712"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p499293415718"><a name="p499293415718"></a><a name="p499293415718"></a>VPC.0201</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p190535677"><a name="p190535677"></a><a name="p190535677"></a>Invalid subnet ID.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p1733517714"><a name="p1733517714"></a><a name="p1733517714"></a>Subnet ID is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p171316351479"><a name="p171316351479"></a><a name="p171316351479"></a>Check whether the parameter values are valid based on the returned error message.</p>
</td>
</tr>
<tr id="row65353181373"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p32410356719"><a name="p32410356719"></a><a name="p32410356719"></a>404/500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p18311835678"><a name="p18311835678"></a><a name="p18311835678"></a>VPC.0202</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1041123517713"><a name="p1041123517713"></a><a name="p1041123517713"></a>An internal error occurs in the subnet.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p961381219820"><a name="p961381219820"></a><a name="p961381219820"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p2541735371"><a name="p2541735371"></a><a name="p2541735371"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row2980855718568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p07222617911"><a name="p07222617911"></a><a name="p07222617911"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p6568292318568"><a name="p6568292318568"></a><a name="p6568292318568"></a>VPC.0206</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1871658618568"><a name="p1871658618568"></a><a name="p1871658618568"></a>The subnet cannot be deleted because it is being used by the VPN.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p163070374918"><a name="p163070374918"></a><a name="p163070374918"></a>Subnet has been used by VPN, please remove the subnet from the VPN and try again.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p15173104220108"><a name="p15173104220108"></a><a name="p15173104220108"></a>Delete the subnet that is used by the VPN.</p>
</td>
</tr>
<tr id="row3423155418568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p17722061695"><a name="p17722061695"></a><a name="p17722061695"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p2129245218568"><a name="p2129245218568"></a><a name="p2129245218568"></a>VPC.0207</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p4696706718568"><a name="p4696706718568"></a><a name="p4696706718568"></a>This operation is not allowed because the subnet does not belong to the VPC.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p143061637693"><a name="p143061637693"></a><a name="p143061637693"></a>Subnet does not belong to the VPC.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p9173174210101"><a name="p9173174210101"></a><a name="p9173174210101"></a>Check whether the subnet is in the VPC.</p>
</td>
</tr>
<tr id="row2005042618568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p13722369911"><a name="p13722369911"></a><a name="p13722369911"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1347181918568"><a name="p1347181918568"></a><a name="p1347181918568"></a>VPC.0208</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1747555618568"><a name="p1747555618568"></a><a name="p1747555618568"></a>The subnet cannot be deleted because it is being used by the private IP address.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1330618371098"><a name="p1330618371098"></a><a name="p1330618371098"></a>Subnet is used by private IP, can not be deleted.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p81731142131011"><a name="p81731142131011"></a><a name="p81731142131011"></a>Delete the private IP address of the subnet.</p>
</td>
</tr>
<tr id="row6677462695928"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p10722763913"><a name="p10722763913"></a><a name="p10722763913"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4003561595928"><a name="p4003561595928"></a><a name="p4003561595928"></a>VPC.0209</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2165936495928"><a name="p2165936495928"></a><a name="p2165936495928"></a>The subnet cannot be deleted because it is being used by an ECS or load balancer.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p73062377914"><a name="p73062377914"></a><a name="p73062377914"></a>Subnet is still used, such as computer, LB.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p417394291014"><a name="p417394291014"></a><a name="p417394291014"></a>Delete the ECS or load balancer in the subnet.</p>
</td>
</tr>
<tr id="row3241309595921"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1172276794"><a name="p1172276794"></a><a name="p1172276794"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p821502095921"><a name="p821502095921"></a><a name="p821502095921"></a>VPC.0210</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p6143689895921"><a name="p6143689895921"></a><a name="p6143689895921"></a>The subnet cannot be deleted because it is being used by the custom route.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1230611371695"><a name="p1230611371695"></a><a name="p1230611371695"></a>Subnet has been used by routes, please remove the routes first and try again.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p917384271019"><a name="p917384271019"></a><a name="p917384271019"></a>Delete the custom route.</p>
</td>
</tr>
<tr id="row2306228418568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1472318619916"><a name="p1472318619916"></a><a name="p1472318619916"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p5610570118568"><a name="p5610570118568"></a><a name="p5610570118568"></a>VPC.0211</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p4826793118568"><a name="p4826793118568"></a><a name="p4826793118568"></a>The subnet cannot be deleted because it is being used by load balancers.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p5306143712910"><a name="p5306143712910"></a><a name="p5306143712910"></a>subnet is still used by LBaas.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p817311427102"><a name="p817311427102"></a><a name="p817311427102"></a>Delete load balancers in the subnet.</p>
</td>
</tr>
<tr id="row7270729125813"><td class="cellrowborder" rowspan="4" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p2227705518568"><a name="p2227705518568"></a><a name="p2227705518568"></a>Updating a subnet</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p1250841610592"><a name="p1250841610592"></a><a name="p1250841610592"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p185152164599"><a name="p185152164599"></a><a name="p185152164599"></a>VPC.0201</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p5521191614594"><a name="p5521191614594"></a><a name="p5521191614594"></a>Incorrect subnet parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p1352811167598"><a name="p1352811167598"></a><a name="p1352811167598"></a>xx is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p8535101615919"><a name="p8535101615919"></a><a name="p8535101615919"></a>Check whether the parameter values are valid based on the returned error message.</p>
</td>
</tr>
<tr id="row183512619582"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p20547141620598"><a name="p20547141620598"></a><a name="p20547141620598"></a>404/500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p11553111645918"><a name="p11553111645918"></a><a name="p11553111645918"></a>VPC.0202</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p855921635912"><a name="p855921635912"></a><a name="p855921635912"></a>An internal error occurs in the subnet.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1840101210618"><a name="p1840101210618"></a><a name="p1840101210618"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1557211611591"><a name="p1557211611591"></a><a name="p1557211611591"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row728031512421"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p167221869919"><a name="p167221869919"></a><a name="p167221869919"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1808387618568"><a name="p1808387618568"></a><a name="p1808387618568"></a>VPC.0205</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p5550784518568"><a name="p5550784518568"></a><a name="p5550784518568"></a>The subnet cannot be updated because it is being processed.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p20306237390"><a name="p20306237390"></a><a name="p20306237390"></a>Subnet states is invalid, please try again later.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p15173154231015"><a name="p15173154231015"></a><a name="p15173154231015"></a>Try again later or contact technical support.</p>
</td>
</tr>
<tr id="row3175819618568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p187237612910"><a name="p187237612910"></a><a name="p187237612910"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p5961103518568"><a name="p5961103518568"></a><a name="p5961103518568"></a>VPC.0207</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p6376452718568"><a name="p6376452718568"></a><a name="p6376452718568"></a>This operation is not allowed because the subnet does not belong to the VPC.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p181202044134419"><a name="p181202044134419"></a><a name="p181202044134419"></a>Subnet does not belong to the VPC.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p211844414446"><a name="p211844414446"></a><a name="p211844414446"></a>Check whether the subnet is in the VPC.</p>
</td>
</tr>
<tr id="row1112562513312"><td class="cellrowborder" rowspan="11" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p4500692218568"><a name="p4500692218568"></a><a name="p4500692218568"></a>Assigning an EIP</p>
<p id="p15539136382"><a name="p15539136382"></a><a name="p15539136382"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p171251225237"><a name="p171251225237"></a><a name="p171251225237"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p11251025832"><a name="p11251025832"></a><a name="p11251025832"></a>VPC.0301</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p81251425339"><a name="p81251425339"></a><a name="p81251425339"></a>The specified bandwidth parameter for assigning an EIP is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p21251725137"><a name="p21251725137"></a><a name="p21251725137"></a>Bandwidth name or share_type is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p91253253313"><a name="p91253253313"></a><a name="p91253253313"></a>Check whether the specified bandwidth parameter is valid.</p>
</td>
</tr>
<tr id="row3700983818568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p97233612916"><a name="p97233612916"></a><a name="p97233612916"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p2168209918568"><a name="p2168209918568"></a><a name="p2168209918568"></a>VPC.0501</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1141960018568"><a name="p1141960018568"></a><a name="p1141960018568"></a>Invalid EIP parameters.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p2030733710917"><a name="p2030733710917"></a><a name="p2030733710917"></a>Bandwidth share_type is invalid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p19173194261018"><a name="p19173194261018"></a><a name="p19173194261018"></a>Check whether the parameter values are valid based on the returned error message and API reference document.</p>
</td>
</tr>
<tr id="row3566754218568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p19723126594"><a name="p19723126594"></a><a name="p19723126594"></a>403</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p338978918568"><a name="p338978918568"></a><a name="p338978918568"></a>VPC.0502</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p613748418568"><a name="p613748418568"></a><a name="p613748418568"></a>You are not allowed to assign the EIP.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p12307133720911"><a name="p12307133720911"></a><a name="p12307133720911"></a>Tenant status is op_restricted.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1317313425108"><a name="p1317313425108"></a><a name="p1317313425108"></a>Check whether the account balance is insufficient or whether your account has been frozen.</p>
</td>
</tr>
<tr id="row5523736318568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1272316995"><a name="p1272316995"></a><a name="p1272316995"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4504139418568"><a name="p4504139418568"></a><a name="p4504139418568"></a>VPC.0503</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2447428618568"><a name="p2447428618568"></a><a name="p2447428618568"></a>Failed to assign the EIP.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p103074378911"><a name="p103074378911"></a><a name="p103074378911"></a>Creating publicIp failed.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p16173164210107"><a name="p16173164210107"></a><a name="p16173164210107"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row1894198218568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p072315613915"><a name="p072315613915"></a><a name="p072315613915"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p5790553518568"><a name="p5790553518568"></a><a name="p5790553518568"></a>VPC.0504</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p5983675318568"><a name="p5983675318568"></a><a name="p5983675318568"></a>Failed to assign the EIP because no IP address is found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p430711371911"><a name="p430711371911"></a><a name="p430711371911"></a>FloatIp is null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p12173124210104"><a name="p12173124210104"></a><a name="p12173124210104"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row3840327718568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p27231466912"><a name="p27231466912"></a><a name="p27231466912"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p2365771318568"><a name="p2365771318568"></a><a name="p2365771318568"></a>VPC.0508</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p3722659418568"><a name="p3722659418568"></a><a name="p3722659418568"></a>Port-related resources could not be found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p14307337595"><a name="p14307337595"></a><a name="p14307337595"></a>Port is invalid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p131731442201014"><a name="p131731442201014"></a><a name="p131731442201014"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row6660389018568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p16723666918"><a name="p16723666918"></a><a name="p16723666918"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p2620601618568"><a name="p2620601618568"></a><a name="p2620601618568"></a>VPC.0510</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p4231259118568"><a name="p4231259118568"></a><a name="p4231259118568"></a>The EIP has already been bound with another ECS.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p33079371590"><a name="p33079371590"></a><a name="p33079371590"></a>Floatingip has already associated with port.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p4173342121014"><a name="p4173342121014"></a><a name="p4173342121014"></a>Unbind the EIP from the ECS.</p>
</td>
</tr>
<tr id="row86735494720"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p187231168919"><a name="p187231168919"></a><a name="p187231168919"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p314688394720"><a name="p314688394720"></a><a name="p314688394720"></a>VPC.0511</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p5357097694720"><a name="p5357097694720"></a><a name="p5357097694720"></a>The port has already been bound with an EIP.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p730743715920"><a name="p730743715920"></a><a name="p730743715920"></a>Port has already associated with floatingip.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1173114261016"><a name="p1173114261016"></a><a name="p1173114261016"></a>Unbind the port from the EIP.</p>
</td>
</tr>
<tr id="row4215075894947"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p67231564918"><a name="p67231564918"></a><a name="p67231564918"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p5876823294947"><a name="p5876823294947"></a><a name="p5876823294947"></a>VPC.0521</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p6260633894947"><a name="p6260633894947"></a><a name="p6260633894947"></a>Insufficient EIP quota.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p83072371697"><a name="p83072371697"></a><a name="p83072371697"></a>Quota exceeded for resources: ['floatingip'].</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p19173174220102"><a name="p19173174220102"></a><a name="p19173174220102"></a>Release the unbound EIPs or request to increase the EIP quota.</p>
</td>
</tr>
<tr id="row49932129501"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p17723461799"><a name="p17723461799"></a><a name="p17723461799"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p17970059501"><a name="p17970059501"></a><a name="p17970059501"></a>VPC.0522</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p113397489501"><a name="p113397489501"></a><a name="p113397489501"></a>The IP address is invalid or in use.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1530712371799"><a name="p1530712371799"></a><a name="p1530712371799"></a>The IP address is in use.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p19173184217109"><a name="p19173184217109"></a><a name="p19173184217109"></a>Check whether the IP address format is valid or replace it to another IP address.</p>
</td>
</tr>
<tr id="row953836683"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p95391561980"><a name="p95391561980"></a><a name="p95391561980"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p17540196888"><a name="p17540196888"></a><a name="p17540196888"></a>VPC.0532</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p6540760819"><a name="p6540760819"></a><a name="p6540760819"></a>Failed to assign the IP address because no IP addresses are available.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p2054016788"><a name="p2054016788"></a><a name="p2054016788"></a>No more IP addresses available on network.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p9540964819"><a name="p9540964819"></a><a name="p9540964819"></a>Release unbound EIPs or try again later.</p>
</td>
</tr>
<tr id="row932545518568"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p1716440018568"><a name="p1716440018568"></a><a name="p1716440018568"></a>Querying an EIP</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p67231616914"><a name="p67231616914"></a><a name="p67231616914"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p4813916118568"><a name="p4813916118568"></a><a name="p4813916118568"></a>VPC.0501</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p695800318568"><a name="p695800318568"></a><a name="p695800318568"></a>Invalid EIP parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p13307103714919"><a name="p13307103714919"></a><a name="p13307103714919"></a>Invalid floatingip_id.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p517312421104"><a name="p517312421104"></a><a name="p517312421104"></a>Check whether the EIP ID is valid.</p>
</td>
</tr>
<tr id="row359277171018"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p759212716102"><a name="p759212716102"></a><a name="p759212716102"></a>404</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p95925719102"><a name="p95925719102"></a><a name="p95925719102"></a>VPC.0504</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p259237141012"><a name="p259237141012"></a><a name="p259237141012"></a>The EIP could not be found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1959219718104"><a name="p1959219718104"></a><a name="p1959219718104"></a>Floating IP could not be found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p48510545106"><a name="p48510545106"></a><a name="p48510545106"></a>Check whether the specified EIP ID is valid.</p>
</td>
</tr>
<tr id="row6262203418568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p16723761094"><a name="p16723761094"></a><a name="p16723761094"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p3921999218568"><a name="p3921999218568"></a><a name="p3921999218568"></a>VPC.0514</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2270275418568"><a name="p2270275418568"></a><a name="p2270275418568"></a>An exception occurs in the IaaS OpenStack system.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p4307163719916"><a name="p4307163719916"></a><a name="p4307163719916"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p12173184213106"><a name="p12173184213106"></a><a name="p12173184213106"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row299819618568"><td class="cellrowborder" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p4152732818568"><a name="p4152732818568"></a><a name="p4152732818568"></a>Querying EIPs</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p117231261894"><a name="p117231261894"></a><a name="p117231261894"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p827040418568"><a name="p827040418568"></a><a name="p827040418568"></a>VPC.0501</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p6592301718568"><a name="p6592301718568"></a><a name="p6592301718568"></a>Invalid EIP parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p03073371392"><a name="p03073371392"></a><a name="p03073371392"></a>Invalid limit.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p917344213103"><a name="p917344213103"></a><a name="p917344213103"></a>Check whether the parameter values are valid based on the returned error message and API reference document.</p>
</td>
</tr>
<tr id="row5643624718568"><td class="cellrowborder" rowspan="7" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p793332818568"><a name="p793332818568"></a><a name="p793332818568"></a>Releasing an EIP</p>
<p id="p1453846115010"><a name="p1453846115010"></a><a name="p1453846115010"></a></p>
<p id="p161841830125119"><a name="p161841830125119"></a><a name="p161841830125119"></a></p>
<p id="p1518403018518"><a name="p1518403018518"></a><a name="p1518403018518"></a></p>
<p id="p14184163016512"><a name="p14184163016512"></a><a name="p14184163016512"></a></p>
<p id="p418411306518"><a name="p418411306518"></a><a name="p418411306518"></a></p>
<p id="p1418433012517"><a name="p1418433012517"></a><a name="p1418433012517"></a></p>
<p id="p141849308511"><a name="p141849308511"></a><a name="p141849308511"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p13723563914"><a name="p13723563914"></a><a name="p13723563914"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p3861983718568"><a name="p3861983718568"></a><a name="p3861983718568"></a>VPC.0501</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p4119911118568"><a name="p4119911118568"></a><a name="p4119911118568"></a>Invalid EIP parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p830793719920"><a name="p830793719920"></a><a name="p830793719920"></a>Invalid param.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p51732042201019"><a name="p51732042201019"></a><a name="p51732042201019"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row1192716378133"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p86482039111311"><a name="p86482039111311"></a><a name="p86482039111311"></a>404</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p17659123912139"><a name="p17659123912139"></a><a name="p17659123912139"></a>VPC.0504</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p566853971317"><a name="p566853971317"></a><a name="p566853971317"></a>The EIP could not be found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p187041639111314"><a name="p187041639111314"></a><a name="p187041639111314"></a>Floating IP could not be found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p971614391133"><a name="p971614391133"></a><a name="p971614391133"></a>Check whether the specified EIP ID is valid.</p>
</td>
</tr>
<tr id="row2608950318568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1172314610915"><a name="p1172314610915"></a><a name="p1172314610915"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p3287498718568"><a name="p3287498718568"></a><a name="p3287498718568"></a>VPC.0512</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p4562825118568"><a name="p4562825118568"></a><a name="p4562825118568"></a>The EIP status is abnormal.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1730720371919"><a name="p1730720371919"></a><a name="p1730720371919"></a>Resource status is busy, try it again later.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p8173142171010"><a name="p8173142171010"></a><a name="p8173142171010"></a>Try again later or contact technical support.</p>
</td>
</tr>
<tr id="row800107618568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p197231061693"><a name="p197231061693"></a><a name="p197231061693"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4410741418568"><a name="p4410741418568"></a><a name="p4410741418568"></a>VPC.0513</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1593076818568"><a name="p1593076818568"></a><a name="p1593076818568"></a>Network resources cannot be found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p3307123719912"><a name="p3307123719912"></a><a name="p3307123719912"></a>getElementByKey error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1717316427105"><a name="p1717316427105"></a><a name="p1717316427105"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row915919018568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p17723661916"><a name="p17723661916"></a><a name="p17723661916"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p369693618568"><a name="p369693618568"></a><a name="p369693618568"></a>VPC.0516</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p3101642318568"><a name="p3101642318568"></a><a name="p3101642318568"></a>Failed to release the EIP because it is being used by a load balancer.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p3307153713911"><a name="p3307153713911"></a><a name="p3307153713911"></a>Publicip is in used by ELB.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p71731042191012"><a name="p71731042191012"></a><a name="p71731042191012"></a>Unbind the EIP from the load balancer.</p>
</td>
</tr>
<tr id="row1071235418568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p37231064910"><a name="p37231064910"></a><a name="p37231064910"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p6239438318568"><a name="p6239438318568"></a><a name="p6239438318568"></a>VPC.0517</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2078025218568"><a name="p2078025218568"></a><a name="p2078025218568"></a>Failed to release the EIP because it is bound to an ECS.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1530719371197"><a name="p1530719371197"></a><a name="p1530719371197"></a>Floatingip has associated with port, please disassociate it firstly.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p161739429100"><a name="p161739429100"></a><a name="p161739429100"></a>Unbind the EIP from the ECS.</p>
</td>
</tr>
<tr id="row4506810894522"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p3723764916"><a name="p3723764916"></a><a name="p3723764916"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p2663816194522"><a name="p2663816194522"></a><a name="p2663816194522"></a>VPC.0518</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1020745594522"><a name="p1020745594522"></a><a name="p1020745594522"></a>Failed to release the EIP because it is being used by a firewall.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p330715371690"><a name="p330715371690"></a><a name="p330715371690"></a>Public IP has firewall rules.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p7173242181019"><a name="p7173242181019"></a><a name="p7173242181019"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row4338549318568"><td class="cellrowborder" rowspan="7" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p2456408418568"><a name="p2456408418568"></a><a name="p2456408418568"></a>Updating an EIP</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p372310617916"><a name="p372310617916"></a><a name="p372310617916"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p4353382018568"><a name="p4353382018568"></a><a name="p4353382018568"></a>VPC.0501</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p3657851618568"><a name="p3657851618568"></a><a name="p3657851618568"></a>Invalid EIP parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p2307193715916"><a name="p2307193715916"></a><a name="p2307193715916"></a>Port id is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p14173104261014"><a name="p14173104261014"></a><a name="p14173104261014"></a>Check whether the port ID is valid.</p>
</td>
</tr>
<tr id="row16355185031317"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p318055271315"><a name="p318055271315"></a><a name="p318055271315"></a>404</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p12187052171318"><a name="p12187052171318"></a><a name="p12187052171318"></a>VPC.0504</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p8195952111318"><a name="p8195952111318"></a><a name="p8195952111318"></a>The EIP could not be found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p120875251310"><a name="p120875251310"></a><a name="p120875251310"></a>Floating IP could not be found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p821517524134"><a name="p821517524134"></a><a name="p821517524134"></a>Check whether the specified EIP ID is valid.</p>
</td>
</tr>
<tr id="row6077118918568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p17231610910"><a name="p17231610910"></a><a name="p17231610910"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p2351930518568"><a name="p2351930518568"></a><a name="p2351930518568"></a>VPC.0509</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2601555318568"><a name="p2601555318568"></a><a name="p2601555318568"></a>The port has already been bound with an EIP.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p5307143718917"><a name="p5307143718917"></a><a name="p5307143718917"></a>Floating ip double status is invalid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p14173124213102"><a name="p14173124213102"></a><a name="p14173124213102"></a>Unbind the port from the EIP.</p>
</td>
</tr>
<tr id="row3281339018568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p207231862916"><a name="p207231862916"></a><a name="p207231862916"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4063896818568"><a name="p4063896818568"></a><a name="p4063896818568"></a>VPC.0510</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p342213918568"><a name="p342213918568"></a><a name="p342213918568"></a>The EIP has already been bound with another ECS.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p81495218402"><a name="p81495218402"></a><a name="p81495218402"></a>Floatingip has already associated with port.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p32014527408"><a name="p32014527408"></a><a name="p32014527408"></a>Unbind the EIP from the ECS.</p>
</td>
</tr>
<tr id="row3079925318568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p17236619918"><a name="p17236619918"></a><a name="p17236619918"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1171153518568"><a name="p1171153518568"></a><a name="p1171153518568"></a>VPC.0511</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p911026118568"><a name="p911026118568"></a><a name="p911026118568"></a>Failed to bind the EIP to the ECS because another EIP has already been bound to the ECS.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1116218453418"><a name="p1116218453418"></a><a name="p1116218453418"></a>Port has already associated with floatingip.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p61681450416"><a name="p61681450416"></a><a name="p61681450416"></a>Unbind the EIP from the ECS.</p>
</td>
</tr>
<tr id="row1488349318568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p5723166293"><a name="p5723166293"></a><a name="p5723166293"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p6471228118568"><a name="p6471228118568"></a><a name="p6471228118568"></a>VPC.0512</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p720343818568"><a name="p720343818568"></a><a name="p720343818568"></a>The EIP status is abnormal.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p2025595417421"><a name="p2025595417421"></a><a name="p2025595417421"></a>Resource status is busy, try it again later.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p172592548421"><a name="p172592548421"></a><a name="p172592548421"></a>Try again later or contact technical support.</p>
</td>
</tr>
<tr id="row16317111441420"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p13908203810142"><a name="p13908203810142"></a><a name="p13908203810142"></a>404/500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p14915153861419"><a name="p14915153861419"></a><a name="p14915153861419"></a>VPC.0514</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1392215387146"><a name="p1392215387146"></a><a name="p1392215387146"></a>An exception occurs in the IaaS OpenStack system.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p149291238131418"><a name="p149291238131418"></a><a name="p149291238131418"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p109361438131420"><a name="p109361438131420"></a><a name="p109361438131420"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row6483094818568"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p1681546918568"><a name="p1681546918568"></a><a name="p1681546918568"></a>Querying a bandwidth</p>
<p id="p147298244250"><a name="p147298244250"></a><a name="p147298244250"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p207235612914"><a name="p207235612914"></a><a name="p207235612914"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p1987575418568"><a name="p1987575418568"></a><a name="p1987575418568"></a>VPC.0301</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p6643226018568"><a name="p6643226018568"></a><a name="p6643226018568"></a>The bandwidth parameters are incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p1430715371095"><a name="p1430715371095"></a><a name="p1430715371095"></a>getBandwidth error bandwidthId is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p101731242171017"><a name="p101731242171017"></a><a name="p101731242171017"></a>Check whether the bandwidth ID is valid.</p>
</td>
</tr>
<tr id="row6101943118568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p157231361394"><a name="p157231361394"></a><a name="p157231361394"></a>404</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p4362687018568"><a name="p4362687018568"></a><a name="p4362687018568"></a>VPC.0306</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p4411560618568"><a name="p4411560618568"></a><a name="p4411560618568"></a>The bandwidth object does not exist.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1530715379912"><a name="p1530715379912"></a><a name="p1530715379912"></a>No Eip bandwidth exist with id.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p12173144220109"><a name="p12173144220109"></a><a name="p12173144220109"></a>The bandwidth object to be queried does not exist.</p>
</td>
</tr>
<tr id="row19728102414259"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p5224115772514"><a name="p5224115772514"></a><a name="p5224115772514"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1922725752513"><a name="p1922725752513"></a><a name="p1922725752513"></a>VPC.0302</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p122351057172518"><a name="p122351057172518"></a><a name="p122351057172518"></a>An exception occurs in the IaaS OpenStack system.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p524411576258"><a name="p524411576258"></a><a name="p524411576258"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p122521557112512"><a name="p122521557112512"></a><a name="p122521557112512"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row6149614018568"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p1513143218568"><a name="p1513143218568"></a><a name="p1513143218568"></a>Querying bandwidths</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p4723176495"><a name="p4723176495"></a><a name="p4723176495"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p1768644018568"><a name="p1768644018568"></a><a name="p1768644018568"></a>VPC.0301</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p2331550818568"><a name="p2331550818568"></a><a name="p2331550818568"></a>The bandwidth parameters are incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p53071937499"><a name="p53071937499"></a><a name="p53071937499"></a>Get bandwidths error limit is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p171731942151012"><a name="p171731942151012"></a><a name="p171731942151012"></a>Check whether the parameter values are valid based on the returned error message and API reference document.</p>
</td>
</tr>
<tr id="row3695636192919"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1269643617299"><a name="p1269643617299"></a><a name="p1269643617299"></a>404</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p10696436162918"><a name="p10696436162918"></a><a name="p10696436162918"></a>VPC.0306</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p0807349182911"><a name="p0807349182911"></a><a name="p0807349182911"></a>The bandwidth object does not exist.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p18696143602915"><a name="p18696143602915"></a><a name="p18696143602915"></a>No Eip bandwidth exist with id.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p457613560295"><a name="p457613560295"></a><a name="p457613560295"></a>The bandwidth object to be queried does not exist.</p>
</td>
</tr>
<tr id="row851298718568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p97241262093"><a name="p97241262093"></a><a name="p97241262093"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1846333318568"><a name="p1846333318568"></a><a name="p1846333318568"></a>VPC.0302</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1913502418568"><a name="p1913502418568"></a><a name="p1913502418568"></a>An exception occurs in the IaaS OpenStack system.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p16307437395"><a name="p16307437395"></a><a name="p16307437395"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p41737423104"><a name="p41737423104"></a><a name="p41737423104"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row3799749318568"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p5789811618568"><a name="p5789811618568"></a><a name="p5789811618568"></a>Updating a bandwidth</p>
<p id="p86261337173912"><a name="p86261337173912"></a><a name="p86261337173912"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p3724196992"><a name="p3724196992"></a><a name="p3724196992"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p5923581518568"><a name="p5923581518568"></a><a name="p5923581518568"></a>VPC.0301</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p3337171918568"><a name="p3337171918568"></a><a name="p3337171918568"></a>The bandwidth parameters are incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p5307737396"><a name="p5307737396"></a><a name="p5307737396"></a>updateBandwidth input param is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p1217344231017"><a name="p1217344231017"></a><a name="p1217344231017"></a>Check whether the parameter values are valid based on the returned error message and API reference document.</p>
</td>
</tr>
<tr id="row3191001718568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p15724146292"><a name="p15724146292"></a><a name="p15724146292"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p3457456618568"><a name="p3457456618568"></a><a name="p3457456618568"></a>VPC.0302</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p4907647618568"><a name="p4907647618568"></a><a name="p4907647618568"></a>Failed to obtain underlying resources.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p19307163711918"><a name="p19307163711918"></a><a name="p19307163711918"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p11733425103"><a name="p11733425103"></a><a name="p11733425103"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row3903510518568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1672418614915"><a name="p1672418614915"></a><a name="p1672418614915"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p772691418568"><a name="p772691418568"></a><a name="p772691418568"></a>VPC.0305</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p2190032918568"><a name="p2190032918568"></a><a name="p2190032918568"></a>An internal error occurs during the bandwidth update.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p9307237999"><a name="p9307237999"></a><a name="p9307237999"></a>updateBandwidth error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p517312423101"><a name="p517312423101"></a><a name="p517312423101"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row3929541144916"><td class="cellrowborder" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p8930154117498"><a name="p8930154117498"></a><a name="p8930154117498"></a>Querying quotas</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p1793064134918"><a name="p1793064134918"></a><a name="p1793064134918"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p159301415494"><a name="p159301415494"></a><a name="p159301415494"></a>VPC.1207</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p11930174144913"><a name="p11930174144913"></a><a name="p11930174144913"></a>The specified resource type does not exist.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p159301241174912"><a name="p159301241174912"></a><a name="p159301241174912"></a>resource type is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p993084104912"><a name="p993084104912"></a><a name="p993084104912"></a>Use an existing resource type.</p>
</td>
</tr>
<tr id="row73838107289"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p738421012815"><a name="p738421012815"></a><a name="p738421012815"></a>Assigning a private IP address</p>
<p id="p76023822817"><a name="p76023822817"></a><a name="p76023822817"></a></p>
<p id="p2387101122811"><a name="p2387101122811"></a><a name="p2387101122811"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p10384121015281"><a name="p10384121015281"></a><a name="p10384121015281"></a>500</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p6384191062815"><a name="p6384191062815"></a><a name="p6384191062815"></a>VPC.0701</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p5384171022817"><a name="p5384171022817"></a><a name="p5384171022817"></a>The private IP address already exists.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p438410105281"><a name="p438410105281"></a><a name="p438410105281"></a>The IP has been used.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p138411109281"><a name="p138411109281"></a><a name="p138411109281"></a>Change another private IP address and try again.</p>
</td>
</tr>
<tr id="row1660212817289"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1560288142811"><a name="p1560288142811"></a><a name="p1560288142811"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p560320892816"><a name="p560320892816"></a><a name="p560320892816"></a>VPC.0705</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p106031184284"><a name="p106031184284"></a><a name="p106031184284"></a>Invalid private IP address</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1760378112818"><a name="p1760378112818"></a><a name="p1760378112818"></a>IP address is not a valid IP for the specified subnet.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p76031388281"><a name="p76031388281"></a><a name="p76031388281"></a>Check whether the specified IP address in the request body is within the subnet CIDR block.</p>
</td>
</tr>
<tr id="row1238720110286"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p33871617281"><a name="p33871617281"></a><a name="p33871617281"></a>404</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p17387151102810"><a name="p17387151102810"></a><a name="p17387151102810"></a>VPC.2204</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p838781132817"><a name="p838781132817"></a><a name="p838781132817"></a>The resource does not exist or the permission is insufficient.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p2038717132811"><a name="p2038717132811"></a><a name="p2038717132811"></a>Query resource by id fail.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1138720119282"><a name="p1138720119282"></a><a name="p1138720119282"></a>Check whether the specified subnet in the request body exists or the current account has the permission to query the subnet.</p>
</td>
</tr>
<tr id="row18535657152719"><td class="cellrowborder" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p1153619573276"><a name="p1153619573276"></a><a name="p1153619573276"></a>Querying a Private IP Address</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p8537105762719"><a name="p8537105762719"></a><a name="p8537105762719"></a>404</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p853725772713"><a name="p853725772713"></a><a name="p853725772713"></a>VPC.0704</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p753715711273"><a name="p753715711273"></a><a name="p753715711273"></a>The private IP address does not exist.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p16537657102711"><a name="p16537657102711"></a><a name="p16537657102711"></a>Query resource by id fail.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p1953785720273"><a name="p1953785720273"></a><a name="p1953785720273"></a>Check whether the private IP address exists.</p>
</td>
</tr>
<tr id="row8916551268"><td class="cellrowborder" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p59105517262"><a name="p59105517262"></a><a name="p59105517262"></a>Querying Private IP Addresses</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p10911655182617"><a name="p10911655182617"></a><a name="p10911655182617"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p1991125542616"><a name="p1991125542616"></a><a name="p1991125542616"></a>VPC.0702</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p791135513269"><a name="p791135513269"></a><a name="p791135513269"></a>Invalid parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p119145517265"><a name="p119145517265"></a><a name="p119145517265"></a>query privateIps error.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p891155511269"><a name="p891155511269"></a><a name="p891155511269"></a>Check whether the parameter values are valid based on the returned error message.</p>
</td>
</tr>
<tr id="row1578918522269"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p9789155219268"><a name="p9789155219268"></a><a name="p9789155219268"></a>Releasing a Private IP Address</p>
<p id="p16696050162618"><a name="p16696050162618"></a><a name="p16696050162618"></a></p>
<p id="p168604489265"><a name="p168604489265"></a><a name="p168604489265"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p13789145262615"><a name="p13789145262615"></a><a name="p13789145262615"></a>404</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p194001733144112"><a name="p194001733144112"></a><a name="p194001733144112"></a>VPC.0704</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p10406133104111"><a name="p10406133104111"></a><a name="p10406133104111"></a>The private IP address does not exist.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p841433394118"><a name="p841433394118"></a><a name="p841433394118"></a>Query resource by id fail.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p141943354114"><a name="p141943354114"></a><a name="p141943354114"></a>Check whether the private IP address exists.</p>
</td>
</tr>
<tr id="row106961850132616"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p06961750192614"><a name="p06961750192614"></a><a name="p06961750192614"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p8696450112613"><a name="p8696450112613"></a><a name="p8696450112613"></a>VPC.0706</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p7696135052618"><a name="p7696135052618"></a><a name="p7696135052618"></a>An error occurs when the private IP address is being released.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p196964507267"><a name="p196964507267"></a><a name="p196964507267"></a>Delete port fail.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p196967502265"><a name="p196967502265"></a><a name="p196967502265"></a>Try again later or contact technical support.</p>
</td>
</tr>
<tr id="row14860204814261"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p58604483264"><a name="p58604483264"></a><a name="p58604483264"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1086084862611"><a name="p1086084862611"></a><a name="p1086084862611"></a>VPC.0707</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p186084819265"><a name="p186084819265"></a><a name="p186084819265"></a>The private IP address is in use.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p7860104816266"><a name="p7860104816266"></a><a name="p7860104816266"></a>privateIp is in use.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p158601448132619"><a name="p158601448132619"></a><a name="p158601448132619"></a>Check whether the private IP address is being used by other resource.</p>
</td>
</tr>
<tr id="row6288523318568"><td class="cellrowborder" rowspan="3" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p6053909718568"><a name="p6053909718568"></a><a name="p6053909718568"></a>Creating a security group</p>
<p id="p7770282229"><a name="p7770282229"></a><a name="p7770282229"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p37241066915"><a name="p37241066915"></a><a name="p37241066915"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p471980118568"><a name="p471980118568"></a><a name="p471980118568"></a>VPC.0601</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p4675961018568"><a name="p4675961018568"></a><a name="p4675961018568"></a>The parameters of the security group are incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p12308143715916"><a name="p12308143715916"></a><a name="p12308143715916"></a>Creating securitygroup name is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p176081352145013"><a name="p176081352145013"></a><a name="p176081352145013"></a>Check whether the parameter values are valid based on the returned error message and API reference document.</p>
</td>
</tr>
<tr id="row1818331018568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p12724461695"><a name="p12724461695"></a><a name="p12724461695"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p6356201918568"><a name="p6356201918568"></a><a name="p6356201918568"></a>VPC.0602</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p4824990018568"><a name="p4824990018568"></a><a name="p4824990018568"></a>An internal error occurs in the security group.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p3308193716913"><a name="p3308193716913"></a><a name="p3308193716913"></a>Add security group fail.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p4173342191019"><a name="p4173342191019"></a><a name="p4173342191019"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row137693872212"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p2771138132220"><a name="p2771138132220"></a><a name="p2771138132220"></a>409</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p37711786228"><a name="p37711786228"></a><a name="p37711786228"></a>VPC.0604</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1277110814223"><a name="p1277110814223"></a><a name="p1277110814223"></a>Insufficient security group quota.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p147719813225"><a name="p147719813225"></a><a name="p147719813225"></a>Quota exceeded for resources: ['security_group'].</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p167711289224"><a name="p167711289224"></a><a name="p167711289224"></a>Delete the security group that is no longer required or apply for increasing the quota.</p>
</td>
</tr>
<tr id="row3159592018568"><td class="cellrowborder" rowspan="4" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p913270718568"><a name="p913270718568"></a><a name="p913270718568"></a>Querying a security group</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p5724126799"><a name="p5724126799"></a><a name="p5724126799"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p155177418568"><a name="p155177418568"></a><a name="p155177418568"></a>VPC.0601</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p5858487418568"><a name="p5858487418568"></a><a name="p5858487418568"></a>The parameters of the security group are incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p163082371592"><a name="p163082371592"></a><a name="p163082371592"></a>Securitygroup id is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p1317314271011"><a name="p1317314271011"></a><a name="p1317314271011"></a>Check whether the security group ID is valid.</p>
</td>
</tr>
<tr id="row5750182218568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p3724146192"><a name="p3724146192"></a><a name="p3724146192"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p2713597318568"><a name="p2713597318568"></a><a name="p2713597318568"></a>VPC.0602</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p5053022518568"><a name="p5053022518568"></a><a name="p5053022518568"></a>An internal error occurs in the security group.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p83084371920"><a name="p83084371920"></a><a name="p83084371920"></a>Query security group fail.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p141731642181019"><a name="p141731642181019"></a><a name="p141731642181019"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row5211884918568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1972412619914"><a name="p1972412619914"></a><a name="p1972412619914"></a>404</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p6087721518568"><a name="p6087721518568"></a><a name="p6087721518568"></a>VPC.0603</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p3210734918568"><a name="p3210734918568"></a><a name="p3210734918568"></a>The security group does not exist.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1308123717915"><a name="p1308123717915"></a><a name="p1308123717915"></a>Securitygroup is not exist.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p01731642181013"><a name="p01731642181013"></a><a name="p01731642181013"></a>Check whether the security group ID is correct or whether the security group exists under the tenant.</p>
</td>
</tr>
<tr id="row1818921231"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p3820328239"><a name="p3820328239"></a><a name="p3820328239"></a>404/500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p08202210233"><a name="p08202210233"></a><a name="p08202210233"></a>VPC.0612</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p482022182313"><a name="p482022182313"></a><a name="p482022182313"></a>An internal error occurs in the security group.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p549114910245"><a name="p549114910245"></a><a name="p549114910245"></a>Neutron Error.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p24991249112411"><a name="p24991249112411"></a><a name="p24991249112411"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row2053068918568"><td class="cellrowborder" rowspan="2" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p5237310318568"><a name="p5237310318568"></a><a name="p5237310318568"></a>Querying security groups</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p57243615919"><a name="p57243615919"></a><a name="p57243615919"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p1436295418568"><a name="p1436295418568"></a><a name="p1436295418568"></a>VPC.0601</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p2254860118568"><a name="p2254860118568"></a><a name="p2254860118568"></a>The parameters of the security group are incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p330819370912"><a name="p330819370912"></a><a name="p330819370912"></a>Query security groups error limit is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p12173154218106"><a name="p12173154218106"></a><a name="p12173154218106"></a>Check whether the parameter values are valid based on the returned error message and API reference document.</p>
</td>
</tr>
<tr id="row161082018568"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p37248617915"><a name="p37248617915"></a><a name="p37248617915"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p6336756518568"><a name="p6336756518568"></a><a name="p6336756518568"></a>VPC.0602</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p3249910218568"><a name="p3249910218568"></a><a name="p3249910218568"></a>An internal error occurs in the security group.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p11308737299"><a name="p11308737299"></a><a name="p11308737299"></a>Query security groups fail.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p817374261014"><a name="p817374261014"></a><a name="p817374261014"></a>Check whether the Neutron service is normal or contact technical support.</p>
</td>
</tr>
<tr id="row14736125992520"><td class="cellrowborder" rowspan="11" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p37711137172619"><a name="p37711137172619"></a><a name="p37711137172619"></a>Associating multiple NIC ports to or disassociating them from a security group at a time</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p1312492682619"><a name="p1312492682619"></a><a name="p1312492682619"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p103651915122617"><a name="p103651915122617"></a><a name="p103651915122617"></a>VPC.0606</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p159742153270"><a name="p159742153270"></a><a name="p159742153270"></a>Invalid security group ID.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p1219163182711"><a name="p1219163182711"></a><a name="p1219163182711"></a>Security group id is invalid</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p282811042814"><a name="p282811042814"></a><a name="p282811042814"></a>Use a valid security group ID.</p>
</td>
</tr>
<tr id="row3501125902510"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1412462615261"><a name="p1412462615261"></a><a name="p1412462615261"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p83651915182614"><a name="p83651915182614"></a><a name="p83651915182614"></a>VPC.0606</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p11974201515275"><a name="p11974201515275"></a><a name="p11974201515275"></a>The request structure is missing.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p319931112715"><a name="p319931112715"></a><a name="p319931112715"></a>Request is invalid</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p13828100162813"><a name="p13828100162813"></a><a name="p13828100162813"></a>Use a valid request body.</p>
</td>
</tr>
<tr id="row9309145915256"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p13124192692610"><a name="p13124192692610"></a><a name="p13124192692610"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p936561572619"><a name="p936561572619"></a><a name="p936561572619"></a>VPC.0606</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p597410158275"><a name="p597410158275"></a><a name="p597410158275"></a>The request is empty.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p131910314271"><a name="p131910314271"></a><a name="p131910314271"></a>Request is null</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p58283017283"><a name="p58283017283"></a><a name="p58283017283"></a>Use a valid request body.</p>
</td>
</tr>
<tr id="row2110259192513"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p6124526142616"><a name="p6124526142616"></a><a name="p6124526142616"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1365515162618"><a name="p1365515162618"></a><a name="p1365515162618"></a>VPC.0606</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1397431532711"><a name="p1397431532711"></a><a name="p1397431532711"></a>Invalid action value.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1119143115271"><a name="p1119143115271"></a><a name="p1119143115271"></a>Action is invalid</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p882814092810"><a name="p882814092810"></a><a name="p882814092810"></a>Use a valid action value (<strong id="b84235270611028"><a name="b84235270611028"></a><a name="b84235270611028"></a>add</strong> or <strong id="b84235270611032"><a name="b84235270611032"></a><a name="b84235270611032"></a>remove</strong>).</p>
</td>
</tr>
<tr id="row592510589257"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p71247269267"><a name="p71247269267"></a><a name="p71247269267"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p143651415122620"><a name="p143651415122620"></a><a name="p143651415122620"></a>VPC.0606</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p18974915192711"><a name="p18974915192711"></a><a name="p18974915192711"></a>The <strong id="b84235270611354"><a name="b84235270611354"></a><a name="b84235270611354"></a>ports</strong> are an empty list.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p219143172720"><a name="p219143172720"></a><a name="p219143172720"></a>Ports list is empty</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p68281707280"><a name="p68281707280"></a><a name="p68281707280"></a>Use a valid <strong id="b8423527061140_1"><a name="b8423527061140_1"></a><a name="b8423527061140_1"></a>ports</strong> list.</p>
</td>
</tr>
<tr id="row18731858192518"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p2012414266263"><a name="p2012414266263"></a><a name="p2012414266263"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p536521572612"><a name="p536521572612"></a><a name="p536521572612"></a>VPC.0606</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p397441516270"><a name="p397441516270"></a><a name="p397441516270"></a>The <strong id="b127297171011417"><a name="b127297171011417"></a><a name="b127297171011417"></a>ports</strong> list contains invalid port IDs.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p6198314279"><a name="p6198314279"></a><a name="p6198314279"></a>Port id is invalid</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p17828407286"><a name="p17828407286"></a><a name="p17828407286"></a>Use a valid <strong id="b8423527061140_3"><a name="b8423527061140_3"></a><a name="b8423527061140_3"></a>ports</strong> list.</p>
</td>
</tr>
<tr id="row16544175811256"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1124172611269"><a name="p1124172611269"></a><a name="p1124172611269"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p73653155262"><a name="p73653155262"></a><a name="p73653155262"></a>VPC.0609</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p697410153272"><a name="p697410153272"></a><a name="p697410153272"></a>The <strong id="b84235270611511"><a name="b84235270611511"></a><a name="b84235270611511"></a>ports</strong> list contains more than 20 IDs.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p719931202710"><a name="p719931202710"></a><a name="p719931202710"></a>Ports list exceeds limit</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p382819062811"><a name="p382819062811"></a><a name="p382819062811"></a>Use a valid <strong id="b8423527061140_5"><a name="b8423527061140_5"></a><a name="b8423527061140_5"></a>ports</strong> list.</p>
</td>
</tr>
<tr id="row18372758112512"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p512592618269"><a name="p512592618269"></a><a name="p512592618269"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p6365315112613"><a name="p6365315112613"></a><a name="p6365315112613"></a>VPC.0606</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p6974121592717"><a name="p6974121592717"></a><a name="p6974121592717"></a>Invalid endpoint.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p4191231112719"><a name="p4191231112719"></a><a name="p4191231112719"></a>Endpoint is invalid</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p188298014286"><a name="p188298014286"></a><a name="p188298014286"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row218912584255"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p18125726142618"><a name="p18125726142618"></a><a name="p18125726142618"></a>200</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1236571572612"><a name="p1236571572612"></a><a name="p1236571572612"></a>VPC.0607</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p6974161572717"><a name="p6974161572717"></a><a name="p6974161572717"></a>The security group does not exist.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p151903112713"><a name="p151903112713"></a><a name="p151903112713"></a>Security group of this instance doesn't exist</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p782920002813"><a name="p782920002813"></a><a name="p782920002813"></a>Use a valid security group ID.</p>
</td>
</tr>
<tr id="row6970257122516"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p8125526192617"><a name="p8125526192617"></a><a name="p8125526192617"></a>200</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p123661215202618"><a name="p123661215202618"></a><a name="p123661215202618"></a>VPC.0607</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p18974171592714"><a name="p18974171592714"></a><a name="p18974171592714"></a>Do not disassociate the instance from the security group when it is associated with only one security group.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p91903111279"><a name="p91903111279"></a><a name="p91903111279"></a>An instance must belong to at least one security group</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p882910172818"><a name="p882910172818"></a><a name="p882910172818"></a>Perform other operations.</p>
</td>
</tr>
<tr id="row775855792516"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p31251026102612"><a name="p31251026102612"></a><a name="p31251026102612"></a>200</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p193666152269"><a name="p193666152269"></a><a name="p193666152269"></a>VPC.0608</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1397441522715"><a name="p1397441522715"></a><a name="p1397441522715"></a>An internal error occurs when you perform batch operations.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p172013116270"><a name="p172013116270"></a><a name="p172013116270"></a>Neutron Error</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p78291407287"><a name="p78291407287"></a><a name="p78291407287"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row69815714449"><td class="cellrowborder" rowspan="4" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p1450319174441"><a name="p1450319174441"></a><a name="p1450319174441"></a>Flow log</p>
<p id="p79564934415"><a name="p79564934415"></a><a name="p79564934415"></a></p>
<p id="p4550810194419"><a name="p4550810194419"></a><a name="p4550810194419"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p2628194234419"><a name="p2628194234419"></a><a name="p2628194234419"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p6628164264411"><a name="p6628164264411"></a><a name="p6628164264411"></a>VPC.3001</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p116286423445"><a name="p116286423445"></a><a name="p116286423445"></a>Invalid parameters.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p66281342124416"><a name="p66281342124416"></a><a name="p66281342124416"></a>resource could not be found, flowlog id is invalid</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p13628114213443"><a name="p13628114213443"></a><a name="p13628114213443"></a>Check whether the parameters are valid.</p>
</td>
</tr>
<tr id="row1195617918445"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p26281042194419"><a name="p26281042194419"></a><a name="p26281042194419"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p162834217441"><a name="p162834217441"></a><a name="p162834217441"></a>VPC.3002</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p15628184234415"><a name="p15628184234415"></a><a name="p15628184234415"></a>An error occurred during log topic creation in LTS.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p13628124212442"><a name="p13628124212442"></a><a name="p13628124212442"></a>create its topic failed</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p86281942144411"><a name="p86281942144411"></a><a name="p86281942144411"></a>Check whether the parameters are valid.</p>
</td>
</tr>
<tr id="row34319159595"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p34860253566"><a name="p34860253566"></a><a name="p34860253566"></a>404</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p3486225185615"><a name="p3486225185615"></a><a name="p3486225185615"></a>VPC.3002</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1248652518564"><a name="p1248652518564"></a><a name="p1248652518564"></a>Failed to query the flow log.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p204861825195612"><a name="p204861825195612"></a><a name="p204861825195612"></a>NeutronError</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p10486825125611"><a name="p10486825125611"></a><a name="p10486825125611"></a>Check whether the parameters are valid.</p>
</td>
</tr>
<tr id="row5550181084414"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p362814264413"><a name="p362814264413"></a><a name="p362814264413"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p14628114215443"><a name="p14628114215443"></a><a name="p14628114215443"></a>VPC.3002</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p176281428444"><a name="p176281428444"></a><a name="p176281428444"></a>Failed to create the flow log.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p6628144274412"><a name="p6628144274412"></a><a name="p6628144274412"></a>NeutronError</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p96287422444"><a name="p96287422444"></a><a name="p96287422444"></a>Contact technical support.</p>
</td>
</tr>
<tr id="row7723152818104"><td class="cellrowborder" rowspan="23" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p1382812962016"><a name="p1382812962016"></a><a name="p1382812962016"></a>Resource tags</p>
<p id="p1137813468104"><a name="p1137813468104"></a><a name="p1137813468104"></a></p>
<p id="p8248185541011"><a name="p8248185541011"></a><a name="p8248185541011"></a></p>
<p id="p1924815517106"><a name="p1924815517106"></a><a name="p1924815517106"></a></p>
<p id="p1247155181011"><a name="p1247155181011"></a><a name="p1247155181011"></a></p>
<p id="p11247105541017"><a name="p11247105541017"></a><a name="p11247105541017"></a></p>
<p id="p1824613557105"><a name="p1824613557105"></a><a name="p1824613557105"></a></p>
<p id="p19245145510104"><a name="p19245145510104"></a><a name="p19245145510104"></a></p>
<p id="p7244555191011"><a name="p7244555191011"></a><a name="p7244555191011"></a></p>
<p id="p10243655151015"><a name="p10243655151015"></a><a name="p10243655151015"></a></p>
<p id="p1824295581015"><a name="p1824295581015"></a><a name="p1824295581015"></a></p>
<p id="p13242255151011"><a name="p13242255151011"></a><a name="p13242255151011"></a></p>
<p id="p424115561018"><a name="p424115561018"></a><a name="p424115561018"></a></p>
<p id="p5241155561017"><a name="p5241155561017"></a><a name="p5241155561017"></a></p>
<p id="p1424075515100"><a name="p1424075515100"></a><a name="p1424075515100"></a></p>
<p id="p52409555100"><a name="p52409555100"></a><a name="p52409555100"></a></p>
<p id="p22391155131015"><a name="p22391155131015"></a><a name="p22391155131015"></a></p>
<p id="p523875512105"><a name="p523875512105"></a><a name="p523875512105"></a></p>
<p id="p52383551101"><a name="p52383551101"></a><a name="p52383551101"></a></p>
<p id="p11237125519101"><a name="p11237125519101"></a><a name="p11237125519101"></a></p>
<p id="p1023715591020"><a name="p1023715591020"></a><a name="p1023715591020"></a></p>
<p id="p15236135513107"><a name="p15236135513107"></a><a name="p15236135513107"></a></p>
<p id="p13235955131012"><a name="p13235955131012"></a><a name="p13235955131012"></a></p>
<p id="p52351255151015"><a name="p52351255151015"></a><a name="p52351255151015"></a></p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p148282912209"><a name="p148282912209"></a><a name="p148282912209"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p88281995204"><a name="p88281995204"></a><a name="p88281995204"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p48281396209"><a name="p48281396209"></a><a name="p48281396209"></a>Incorrect resource ID.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p193321028141110"><a name="p193321028141110"></a><a name="p193321028141110"></a>resource id is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p1482819911201"><a name="p1482819911201"></a><a name="p1482819911201"></a>Use a correct resource ID.</p>
</td>
</tr>
<tr id="row1364104311013"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p118287916202"><a name="p118287916202"></a><a name="p118287916202"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p082818912016"><a name="p082818912016"></a><a name="p082818912016"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p128281591200"><a name="p128281591200"></a><a name="p128281591200"></a>Invalid action value.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p144561722912"><a name="p144561722912"></a><a name="p144561722912"></a>action is invalid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p08281090209"><a name="p08281090209"></a><a name="p08281090209"></a>Ensure that the value of <strong id="b84235270619500"><a name="b84235270619500"></a><a name="b84235270619500"></a>action</strong> is <strong id="b842352706194113"><a name="b842352706194113"></a><a name="b842352706194113"></a>create</strong> or <strong id="b842352706194117"><a name="b842352706194117"></a><a name="b842352706194117"></a>delete</strong>.</p>
</td>
</tr>
<tr id="row176461743181014"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1982812910207"><a name="p1982812910207"></a><a name="p1982812910207"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p10828189162017"><a name="p10828189162017"></a><a name="p10828189162017"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p78285992011"><a name="p78285992011"></a><a name="p78285992011"></a>Invalid key length. The key can contain 1 to 36 characters.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1033042814112"><a name="p1033042814112"></a><a name="p1033042814112"></a>Tag length is invalid. The key length must be in range [1,36] and value in range [0,43]</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p48281998201"><a name="p48281998201"></a><a name="p48281998201"></a>Use a valid key value.</p>
</td>
</tr>
<tr id="row12846134313101"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1182816942017"><a name="p1182816942017"></a><a name="p1182816942017"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1582815918205"><a name="p1582815918205"></a><a name="p1582815918205"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p0828189162014"><a name="p0828189162014"></a><a name="p0828189162014"></a>Invalid value length.</p>
<p id="p5828995207"><a name="p5828995207"></a><a name="p5828995207"></a>The value can contain 0 to 43 characters.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p5329182881111"><a name="p5329182881111"></a><a name="p5329182881111"></a>Tag length is invalid. The key length must be in range [1,36] and value in range [0,43]</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1682815914202"><a name="p1682815914202"></a><a name="p1682815914202"></a>Use a value of valid length.</p>
</td>
</tr>
<tr id="row1533174412107"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p2828129172014"><a name="p2828129172014"></a><a name="p2828129172014"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p6828119192018"><a name="p6828119192018"></a><a name="p6828119192018"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1582929172015"><a name="p1582929172015"></a><a name="p1582929172015"></a>Incorrect resource type.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p23282282114"><a name="p23282282114"></a><a name="p23282282114"></a>Resource_type xxx is invalid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p178291792204"><a name="p178291792204"></a><a name="p178291792204"></a>Ensure that the value of <strong id="b842352706172048"><a name="b842352706172048"></a><a name="b842352706172048"></a>resource_type</strong> is <strong id="b842352706172041"><a name="b842352706172041"></a><a name="b842352706172041"></a>vpcs</strong>.</p>
</td>
</tr>
<tr id="row1322414449102"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p11829189142013"><a name="p11829189142013"></a><a name="p11829189142013"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p382915932011"><a name="p382915932011"></a><a name="p382915932011"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p168291492202"><a name="p168291492202"></a><a name="p168291492202"></a>The tag list contains value null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p103273280119"><a name="p103273280119"></a><a name="p103273280119"></a>Tag can not be null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p148295922015"><a name="p148295922015"></a><a name="p148295922015"></a>Use valid tags.</p>
</td>
</tr>
<tr id="row4408124411015"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p68291391202"><a name="p68291391202"></a><a name="p68291391202"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p16829597201"><a name="p16829597201"></a><a name="p16829597201"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p9829199122020"><a name="p9829199122020"></a><a name="p9829199122020"></a>The matches list contains value null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1932611285117"><a name="p1932611285117"></a><a name="p1932611285117"></a>The list of matches contains null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1183120912016"><a name="p1183120912016"></a><a name="p1183120912016"></a>Use valid matches.</p>
</td>
</tr>
<tr id="row877644416105"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p583119917202"><a name="p583119917202"></a><a name="p583119917202"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p283115915204"><a name="p283115915204"></a><a name="p283115915204"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1183109162010"><a name="p1183109162010"></a><a name="p1183109162010"></a>The tags exist, but their values are null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1032517281119"><a name="p1032517281119"></a><a name="p1032517281119"></a>Tag value can not be null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p583117962015"><a name="p583117962015"></a><a name="p583117962015"></a>Use valid tags.</p>
</td>
</tr>
<tr id="row1696444451016"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p2083139152019"><a name="p2083139152019"></a><a name="p2083139152019"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1883113902018"><a name="p1883113902018"></a><a name="p1883113902018"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p283110912012"><a name="p283110912012"></a><a name="p283110912012"></a>The matches exist, and the value is null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p10324182851117"><a name="p10324182851117"></a><a name="p10324182851117"></a>The value of Matches in resourceInstancesReq is null.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p198311915209"><a name="p198311915209"></a><a name="p198311915209"></a>Use valid matches.</p>
</td>
</tr>
<tr id="row17156134515109"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1483114922013"><a name="p1483114922013"></a><a name="p1483114922013"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p583139182013"><a name="p583139182013"></a><a name="p583139182013"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p16831297206"><a name="p16831297206"></a><a name="p16831297206"></a>The tag list contains more than 10 keys.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p19323182871116"><a name="p19323182871116"></a><a name="p19323182871116"></a>number of tags exceeds max num of 10.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1983115916206"><a name="p1983115916206"></a><a name="p1983115916206"></a>Use valid tags.</p>
</td>
</tr>
<tr id="row1933574501018"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p118312919205"><a name="p118312919205"></a><a name="p118312919205"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p283116910207"><a name="p283116910207"></a><a name="p283116910207"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p88318911204"><a name="p88318911204"></a><a name="p88318911204"></a>The tag list contains duplicate keys.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p9323928101111"><a name="p9323928101111"></a><a name="p9323928101111"></a>Tag key is repeated.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p128312910207"><a name="p128312910207"></a><a name="p128312910207"></a>Use valid tags.</p>
</td>
</tr>
<tr id="row7522545201017"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p08316915209"><a name="p08316915209"></a><a name="p08316915209"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1383289202017"><a name="p1383289202017"></a><a name="p1383289202017"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p68321952010"><a name="p68321952010"></a><a name="p68321952010"></a>There are duplicate tag values in the tag list.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1632218282118"><a name="p1632218282118"></a><a name="p1632218282118"></a>Value of tags in resourceInstancesReq is duplicate.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p18832169172010"><a name="p18832169172010"></a><a name="p18832169172010"></a>Use valid tags.</p>
</td>
</tr>
<tr id="row18721164510101"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p13832149132018"><a name="p13832149132018"></a><a name="p13832149132018"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p13832109152020"><a name="p13832109152020"></a><a name="p13832109152020"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1832199202019"><a name="p1832199202019"></a><a name="p1832199202019"></a>The tag in the tag list has more than 10 tag values.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p13321228181117"><a name="p13321228181117"></a><a name="p13321228181117"></a>number of tags exceeds max num of 10.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p108321795201"><a name="p108321795201"></a><a name="p108321795201"></a>Use valid tags.</p>
</td>
</tr>
<tr id="row11913164551010"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p58321993204"><a name="p58321993204"></a><a name="p58321993204"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p198328952015"><a name="p198328952015"></a><a name="p198328952015"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p188324932015"><a name="p188324932015"></a><a name="p188324932015"></a>The key in <strong id="b8423527062004"><a name="b8423527062004"></a><a name="b8423527062004"></a>matches</strong> is not the resource name.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p15320928141112"><a name="p15320928141112"></a><a name="p15320928141112"></a>The key of matches is invalid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p17834189152011"><a name="p17834189152011"></a><a name="p17834189152011"></a>Use valid matches.</p>
</td>
</tr>
<tr id="row811374611109"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p68341962010"><a name="p68341962010"></a><a name="p68341962010"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1483419915209"><a name="p1483419915209"></a><a name="p1483419915209"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1583417912018"><a name="p1583417912018"></a><a name="p1583417912018"></a>Invalid <strong id="b84235270620010"><a name="b84235270620010"></a><a name="b84235270620010"></a>limit</strong> or <strong id="b84235270620013"><a name="b84235270620013"></a><a name="b84235270620013"></a>offset</strong> value.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p1331852812116"><a name="p1331852812116"></a><a name="p1331852812116"></a>Limit in resourceInstancesReq is invalid.</p>
<p id="p14358452631"><a name="p14358452631"></a><a name="p14358452631"></a>Offset in resourceInstancesReq is invalid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p9834189112019"><a name="p9834189112019"></a><a name="p9834189112019"></a>Use valid <strong id="b159777198122"><a name="b159777198122"></a><a name="b159777198122"></a>limit</strong> and <strong id="b682542441213"><a name="b682542441213"></a><a name="b682542441213"></a>offset</strong> values.</p>
</td>
</tr>
<tr id="row18335164691013"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p583449142011"><a name="p583449142011"></a><a name="p583449142011"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p9834139112017"><a name="p9834139112017"></a><a name="p9834139112017"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p083459122016"><a name="p083459122016"></a><a name="p083459122016"></a>The tags dictionary structure is missing.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p73173288117"><a name="p73173288117"></a><a name="p73173288117"></a>ResourceInstancesReq is null or invalid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1783413911209"><a name="p1783413911209"></a><a name="p1783413911209"></a>Use a valid tags dictionary structure.</p>
</td>
</tr>
<tr id="row195286465103"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p583429162010"><a name="p583429162010"></a><a name="p583429162010"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p16834139182011"><a name="p16834139182011"></a><a name="p16834139182011"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1983418913201"><a name="p1983418913201"></a><a name="p1983418913201"></a>The key in tags exceeds the maximum length or is left blank.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p6444102474010"><a name="p6444102474010"></a><a name="p6444102474010"></a>Tag length is invalid. The key length must be in range [1,36] and value in range [0,43]</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1834189182013"><a name="p1834189182013"></a><a name="p1834189182013"></a>Use valid keys in tags.</p>
</td>
</tr>
<tr id="row13710546171017"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p178341192205"><a name="p178341192205"></a><a name="p178341192205"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p19834196201"><a name="p19834196201"></a><a name="p19834196201"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p17834109152019"><a name="p17834109152019"></a><a name="p17834109152019"></a>A value in tags exceeds the maximum length.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p152775184402"><a name="p152775184402"></a><a name="p152775184402"></a>Tag length is invalid. The key length must be in range [1,36] and value in range [0,43]</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1783415910203"><a name="p1783415910203"></a><a name="p1783415910203"></a>Use valid values in tags.</p>
</td>
</tr>
<tr id="row15902134641015"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p283409112015"><a name="p283409112015"></a><a name="p283409112015"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p1683620972013"><a name="p1683620972013"></a><a name="p1683620972013"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p58362099201"><a name="p58362099201"></a><a name="p58362099201"></a>The matches dictionary structure is missing.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p3315728171115"><a name="p3315728171115"></a><a name="p3315728171115"></a>ResourceInstancesReq is null or invalid.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p48364902010"><a name="p48364902010"></a><a name="p48364902010"></a>Use a valid matches dictionary structure.</p>
</td>
</tr>
<tr id="row3285144781017"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p28369917205"><a name="p28369917205"></a><a name="p28369917205"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p38361698204"><a name="p38361698204"></a><a name="p38361698204"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1483717912017"><a name="p1483717912017"></a><a name="p1483717912017"></a>The matches are an empty list.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p6314128141114"><a name="p6314128141114"></a><a name="p6314128141114"></a>The number of Matches in resourceInstancesReq is 0.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p18837095201"><a name="p18837095201"></a><a name="p18837095201"></a>Use a valid matches list.</p>
</td>
</tr>
<tr id="row1947994711108"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p1483899182018"><a name="p1483899182018"></a><a name="p1483899182018"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p183810916209"><a name="p183810916209"></a><a name="p183810916209"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p183918932013"><a name="p183918932013"></a><a name="p183918932013"></a>The matches list contains tag values that contain more than 255 Unicode characters.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p16313162813114"><a name="p16313162813114"></a><a name="p16313162813114"></a>The value's length of Matches in resourceInstancesReq is more than 255.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p20839189202020"><a name="p20839189202020"></a><a name="p20839189202020"></a>Use a valid matches list.</p>
</td>
</tr>
<tr id="row36767479103"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p188398972015"><a name="p188398972015"></a><a name="p188398972015"></a>500</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p583929152016"><a name="p583929152016"></a><a name="p583929152016"></a>VPC.1801</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p984020913203"><a name="p984020913203"></a><a name="p984020913203"></a>Incorrect request body format.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p17312828101111"><a name="p17312828101111"></a><a name="p17312828101111"></a>InvalidInput</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1684009172018"><a name="p1684009172018"></a><a name="p1684009172018"></a>Use the correct request body format.</p>
</td>
</tr>
<tr id="row186084711108"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p5378194619105"><a name="p5378194619105"></a><a name="p5378194619105"></a>404</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p193788467107"><a name="p193788467107"></a><a name="p193788467107"></a>VPC.2204</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p1537854681012"><a name="p1537854681012"></a><a name="p1537854681012"></a>The resource does not exist or the permission is insufficient.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p15289142831115"><a name="p15289142831115"></a><a name="p15289142831115"></a>Query subnet by id fail.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p13378104619104"><a name="p13378104619104"></a><a name="p13378104619104"></a>Use an existing resource or obtain required permission.</p>
</td>
</tr>
<tr id="row1130111169191"><td class="cellrowborder" rowspan="2" valign="top" width="11.07%" headers="mcps1.1.7.1.1 "><p id="p1043612404199"><a name="p1043612404199"></a><a name="p1043612404199"></a>Querying the network IP address usage</p>
</td>
<td class="cellrowborder" valign="top" width="12.27%" headers="mcps1.1.7.1.2 "><p id="p1230219169198"><a name="p1230219169198"></a><a name="p1230219169198"></a>400</p>
</td>
<td class="cellrowborder" valign="top" width="12.740000000000002%" headers="mcps1.1.7.1.3 "><p id="p2302316131918"><a name="p2302316131918"></a><a name="p2302316131918"></a>VPC.2301</p>
</td>
<td class="cellrowborder" valign="top" width="18.91%" headers="mcps1.1.7.1.4 "><p id="p230211167191"><a name="p230211167191"></a><a name="p230211167191"></a>The request parameter is incorrect.</p>
</td>
<td class="cellrowborder" valign="top" width="14.01%" headers="mcps1.1.7.1.5 "><p id="p18302216101916"><a name="p18302216101916"></a><a name="p18302216101916"></a>parameter network_id is invalid.</p>
</td>
<td class="cellrowborder" valign="top" width="31%" headers="mcps1.1.7.1.6 "><p id="p173021016111913"><a name="p173021016111913"></a><a name="p173021016111913"></a>Enter a valid network ID.</p>
</td>
</tr>
<tr id="row222742641919"><td class="cellrowborder" valign="top" headers="mcps1.1.7.1.1 "><p id="p5227226191919"><a name="p5227226191919"></a><a name="p5227226191919"></a>400</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.2 "><p id="p18227126131916"><a name="p18227126131916"></a><a name="p18227126131916"></a>VPC.2302</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.3 "><p id="p6227172641916"><a name="p6227172641916"></a><a name="p6227172641916"></a>The network is not found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.4 "><p id="p622811263193"><a name="p622811263193"></a><a name="p622811263193"></a>Network xxx could not be found.</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.1.7.1.5 "><p id="p1122812617192"><a name="p1122812617192"></a><a name="p1122812617192"></a>Ensure that the network ID exists.</p>
</td>
</tr>
</tbody>
</table>

