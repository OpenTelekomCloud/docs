# FPGA Logical File Management<a name="EN-US_TOPIC_0132778339"></a>

<a name="table141517564301"></a>
<table><thead align="left"><tr id="row8415105683017"><th class="cellrowborder" valign="top" width="35.901926444833634%" id="mcps1.1.4.1.1"><p id="p15415105620309"><a name="p15415105620309"></a><a name="p15415105620309"></a>APIs</p>
</th>
<th class="cellrowborder" valign="top" width="32.95163680452647%" id="mcps1.1.4.1.2"><p id="p10605125713535"><a name="p10605125713535"></a><a name="p10605125713535"></a>Permissions</p>
</th>
<th class="cellrowborder" valign="top" width="31.146436750639907%" id="mcps1.1.4.1.3"><p id="p194156565302"><a name="p194156565302"></a><a name="p194156565302"></a>Actions</p>
</th>
</tr>
</thead>
<tbody><tr id="row2651640102215"><td class="cellrowborder" valign="top" width="35.901926444833634%" headers="mcps1.1.4.1.1 "><p id="p1516821032316"><a name="p1516821032316"></a><a name="p1516821032316"></a>GET /v1/{project_id}/cloudservers/fpga_image/associations{?image_id,fpga_image_id,page,size}</p>
</td>
<td class="cellrowborder" valign="top" width="32.95163680452647%" headers="mcps1.1.4.1.2 "><p id="p958218610428"><a name="p958218610428"></a><a name="p958218610428"></a>Querying Associations Between an FPGA Image and an ECS Image</p>
</td>
<td class="cellrowborder" valign="top" width="31.146436750639907%" headers="mcps1.1.4.1.3 "><a name="ul21681105233"></a><a name="ul21681105233"></a><ul id="ul21681105233"><li>ecs:cloudServerFpgaImages:getRelations</li></ul>
</td>
</tr>
<tr id="row876855342215"><td class="cellrowborder" valign="top" width="35.901926444833634%" headers="mcps1.1.4.1.1 "><p id="p111681310102310"><a name="p111681310102310"></a><a name="p111681310102310"></a>DELETE /v1/{project_id}/cloudservers/fpga_image/{fpga_image_id}/association</p>
</td>
<td class="cellrowborder" valign="top" width="32.95163680452647%" headers="mcps1.1.4.1.2 "><p id="p1758286104210"><a name="p1758286104210"></a><a name="p1758286104210"></a>Disassociating an FPGA Image from an ECS Image</p>
</td>
<td class="cellrowborder" valign="top" width="31.146436750639907%" headers="mcps1.1.4.1.3 "><a name="ul151681010152313"></a><a name="ul151681010152313"></a><ul id="ul151681010152313"><li>ecs:cloudServerFpgaImages:unrelate</li></ul>
</td>
</tr>
<tr id="row1053216597228"><td class="cellrowborder" valign="top" width="35.901926444833634%" headers="mcps1.1.4.1.1 "><p id="p181681910192315"><a name="p181681910192315"></a><a name="p181681910192315"></a>GET /v1/{project_id}/cloudservers/fpga_image/detail</p>
</td>
<td class="cellrowborder" valign="top" width="32.95163680452647%" headers="mcps1.1.4.1.2 "><p id="p658212624218"><a name="p658212624218"></a><a name="p658212624218"></a>Viewing Details of FPGA Images</p>
</td>
<td class="cellrowborder" valign="top" width="31.146436750639907%" headers="mcps1.1.4.1.3 "><a name="ul5168910122319"></a><a name="ul5168910122319"></a><ul id="ul5168910122319"><li>ecs:cloudServerFpgaImages:list</li></ul>
</td>
</tr>
<tr id="row17471104342218"><td class="cellrowborder" valign="top" width="35.901926444833634%" headers="mcps1.1.4.1.1 "><p id="p616891020237"><a name="p616891020237"></a><a name="p616891020237"></a>DELETE /v1/{project_id}/cloudservers/fpga_image/{fpga_image_id}</p>
</td>
<td class="cellrowborder" valign="top" width="32.95163680452647%" headers="mcps1.1.4.1.2 "><p id="p8522122481317"><a name="p8522122481317"></a><a name="p8522122481317"></a>Deleting an FPGA Image</p>
</td>
<td class="cellrowborder" valign="top" width="31.146436750639907%" headers="mcps1.1.4.1.3 "><a name="ul416831042313"></a><a name="ul416831042313"></a><ul id="ul416831042313"><li>ecs:cloudServerFpgaImages:delete</li></ul>
</td>
</tr>
<tr id="row152011446132211"><td class="cellrowborder" valign="top" width="35.901926444833634%" headers="mcps1.1.4.1.1 "><p id="p10168171072318"><a name="p10168171072318"></a><a name="p10168171072318"></a>POST /v1/{project_id}/cloudservers/fpga_image/{fpga_image_id}/association</p>
</td>
<td class="cellrowborder" valign="top" width="32.95163680452647%" headers="mcps1.1.4.1.2 "><p id="p15583106164215"><a name="p15583106164215"></a><a name="p15583106164215"></a>Associating an FPGA Image with an ECS Image</p>
</td>
<td class="cellrowborder" valign="top" width="31.146436750639907%" headers="mcps1.1.4.1.3 "><a name="ul1616841011231"></a><a name="ul1616841011231"></a><ul id="ul1616841011231"><li>ecs:cloudServerFpgaImages:relate</li></ul>
</td>
</tr>
<tr id="row137161050132212"><td class="cellrowborder" valign="top" width="35.901926444833634%" headers="mcps1.1.4.1.1 "><p id="p616810109231"><a name="p616810109231"></a><a name="p616810109231"></a>POST /v1/{project_id}/cloudservers/fpga_image</p>
</td>
<td class="cellrowborder" valign="top" width="32.95163680452647%" headers="mcps1.1.4.1.2 "><p id="p05830634217"><a name="p05830634217"></a><a name="p05830634217"></a>Registering an FPGA Image</p>
</td>
<td class="cellrowborder" valign="top" width="31.146436750639907%" headers="mcps1.1.4.1.3 "><a name="ul15168410192311"></a><a name="ul15168410192311"></a><ul id="ul15168410192311"><li>ecs:cloudServerFpgaImages:register</li></ul>
</td>
</tr>
</tbody>
</table>

