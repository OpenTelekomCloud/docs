# RDS Monitoring Metrics Description<a name="en-us_topic_0041314720"></a>

## Function Description<a name="section3846020215313"></a>

This section describes namespaces, descriptions, and dimensions of monitoring metrics to be reported to Cloud Eye. Users can retrieve monitoring metrics and alarm information reported to Cloud Eye over its API.

## Namespace<a name="section1688213153437"></a>

SYS.RDS

## Monitoring Metrics<a name="section62571340153511"></a>

**Table  1**  RDS performance metrics

<a name="table46701376141844"></a>
<table><thead align="left"><tr id="re01f141cc21347af98381c27e1a5d524"><th class="cellrowborder" valign="top" width="15.229999999999999%" id="mcps1.2.6.1.1"><p id="a807246cff23b44219a7b4ecb8436420f"><a name="a807246cff23b44219a7b4ecb8436420f"></a><a name="a807246cff23b44219a7b4ecb8436420f"></a><strong id="b842352706112935"><a name="b842352706112935"></a><a name="b842352706112935"></a>Metric</strong></p>
</th>
<th class="cellrowborder" valign="top" width="16.13%" id="mcps1.2.6.1.2"><p id="en-us_topic_0029128243_p468860223835"><a name="en-us_topic_0029128243_p468860223835"></a><a name="en-us_topic_0029128243_p468860223835"></a><strong id="b842352706112940"><a name="b842352706112940"></a><a name="b842352706112940"></a>Name</strong></p>
</th>
<th class="cellrowborder" valign="top" width="19.38%" id="mcps1.2.6.1.3"><p id="a8bcd5efa9ee44b9ea636cef5aa688a8f"><a name="a8bcd5efa9ee44b9ea636cef5aa688a8f"></a><a name="a8bcd5efa9ee44b9ea636cef5aa688a8f"></a><strong id="b842352706112944"><a name="b842352706112944"></a><a name="b842352706112944"></a>Description</strong></p>
</th>
<th class="cellrowborder" valign="top" width="26.32%" id="mcps1.2.6.1.4"><p id="a8653133d56124b96a4e0fff4e8f62019"><a name="a8653133d56124b96a4e0fff4e8f62019"></a><a name="a8653133d56124b96a4e0fff4e8f62019"></a><strong id="b842352706112947"><a name="b842352706112947"></a><a name="b842352706112947"></a>Value Range</strong></p>
</th>
<th class="cellrowborder" valign="top" width="22.939999999999998%" id="mcps1.2.6.1.5"><p id="a762d63ea73c943f5977b57d80ca121d7"><a name="a762d63ea73c943f5977b57d80ca121d7"></a><a name="a762d63ea73c943f5977b57d80ca121d7"></a><strong id="b842352706112951"><a name="b842352706112951"></a><a name="b842352706112951"></a>Remarks</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="ra9c1d6eb3b56483d8a8838e74d31e642"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="aa1c7ecf3758444d4bc8e8f06b897fa96"><a name="aa1c7ecf3758444d4bc8e8f06b897fa96"></a><a name="aa1c7ecf3758444d4bc8e8f06b897fa96"></a>rds001_cpu_util</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a47e9c5cfd53542d5ab746dd1f2cb090e"><a name="a47e9c5cfd53542d5ab746dd1f2cb090e"></a><a name="a47e9c5cfd53542d5ab746dd1f2cb090e"></a>CPU Usage</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a8bbe05cb232b4427b2447d1fc478222e"><a name="a8bbe05cb232b4427b2447d1fc478222e"></a><a name="a8bbe05cb232b4427b2447d1fc478222e"></a>CPU usage of the monitored object</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="acc6eb79dd02047ffbc26cf17e20f38cb"><a name="acc6eb79dd02047ffbc26cf17e20f38cb"></a><a name="acc6eb79dd02047ffbc26cf17e20f38cb"></a>0%–100%</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p45641326164812"><a name="p45641326164812"></a><a name="p45641326164812"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul924933143511"></a><a name="ul924933143511"></a><ul id="ul924933143511"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="rbf6d226456694af083a40de12dbb93cd"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="acfa39719774349a2b4be04f612b28e6e"><a name="acfa39719774349a2b4be04f612b28e6e"></a><a name="acfa39719774349a2b4be04f612b28e6e"></a>rds002_mem_util</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a17120aa5ab7448629c4828548e9ff996"><a name="a17120aa5ab7448629c4828548e9ff996"></a><a name="a17120aa5ab7448629c4828548e9ff996"></a>Memory Usage</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a775c60966f644266948c79c107fa37e8"><a name="a775c60966f644266948c79c107fa37e8"></a><a name="a775c60966f644266948c79c107fa37e8"></a>Memory usage of the monitored object</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a9c00a0a9619443a58af65a447c164a57"><a name="a9c00a0a9619443a58af65a447c164a57"></a><a name="a9c00a0a9619443a58af65a447c164a57"></a>0%–100%</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p112964214487"><a name="p112964214487"></a><a name="p112964214487"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul0613173711475"></a><a name="ul0613173711475"></a><ul id="ul0613173711475"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="r3cea26498b3447b9a3ead17476c7c422"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="abe14ba68980e460183ba7bfe0f78f493"><a name="abe14ba68980e460183ba7bfe0f78f493"></a><a name="abe14ba68980e460183ba7bfe0f78f493"></a>rds003_iops</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a8677e88f532e4667957cfe5c142c3eb4"><a name="a8677e88f532e4667957cfe5c142c3eb4"></a><a name="a8677e88f532e4667957cfe5c142c3eb4"></a>IOPS</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="adcfc613b104e4bbdb236107c7983f544"><a name="adcfc613b104e4bbdb236107c7983f544"></a><a name="adcfc613b104e4bbdb236107c7983f544"></a>Average number of I/O requests processed by the system in a specified period</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a9bd3d08b7e79414c9b05faac03f0e760"><a name="a9bd3d08b7e79414c9b05faac03f0e760"></a><a name="a9bd3d08b7e79414c9b05faac03f0e760"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p775015575476"><a name="p775015575476"></a><a name="p775015575476"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul1975111573479"></a><a name="ul1975111573479"></a><ul id="ul1975111573479"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="r1069941e6a9b4463863c575cb9291d1e"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="ae6176ccfa03a4e18a930e91c5e463fff"><a name="ae6176ccfa03a4e18a930e91c5e463fff"></a><a name="ae6176ccfa03a4e18a930e91c5e463fff"></a>rds004_bytes_in</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a065095b14e394d4b9d85d3b8d9006c0d"><a name="a065095b14e394d4b9d85d3b8d9006c0d"></a><a name="a065095b14e394d4b9d85d3b8d9006c0d"></a>Network Input Throughput</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="ae29cadcafee44fd284f88747e1bab9ea"><a name="ae29cadcafee44fd284f88747e1bab9ea"></a><a name="ae29cadcafee44fd284f88747e1bab9ea"></a>Incoming traffic in bytes per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a3c8adbfbc01f412bb9b939d7cf4402b0"><a name="a3c8adbfbc01f412bb9b939d7cf4402b0"></a><a name="a3c8adbfbc01f412bb9b939d7cf4402b0"></a>≥ 0 byte/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p19652144814"><a name="p19652144814"></a><a name="p19652144814"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul496717114819"></a><a name="ul496717114819"></a><ul id="ul496717114819"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="r9fbd096305194e6b8fca4826a3b597cc"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="af9938a4483844a73b9ac48e277dff019"><a name="af9938a4483844a73b9ac48e277dff019"></a><a name="af9938a4483844a73b9ac48e277dff019"></a>rds005_bytes_out</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a6850346c502e421eba00563c83bdc417"><a name="a6850346c502e421eba00563c83bdc417"></a><a name="a6850346c502e421eba00563c83bdc417"></a>Network Output Throughput</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a8a416bbf839a442a857e6e647144ee09"><a name="a8a416bbf839a442a857e6e647144ee09"></a><a name="a8a416bbf839a442a857e6e647144ee09"></a>Outgoing traffic in bytes per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="abd516c021d294e9383dc76012e2a61bb"><a name="abd516c021d294e9383dc76012e2a61bb"></a><a name="abd516c021d294e9383dc76012e2a61bb"></a>≥ 0 byte/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p184901296484"><a name="p184901296484"></a><a name="p184901296484"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul849113912489"></a><a name="ul849113912489"></a><ul id="ul849113912489"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="r7da2a88062a4486093563f1559ecf0c4"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="ae7df0233eca5494d913068bd92adc282"><a name="ae7df0233eca5494d913068bd92adc282"></a><a name="ae7df0233eca5494d913068bd92adc282"></a>rds006_conn_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a1a5fe64b2b094edea3023662ad0fbaf8"><a name="a1a5fe64b2b094edea3023662ad0fbaf8"></a><a name="a1a5fe64b2b094edea3023662ad0fbaf8"></a>Total Connections</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a135aa42a312d496284933d9cff07e153"><a name="a135aa42a312d496284933d9cff07e153"></a><a name="a135aa42a312d496284933d9cff07e153"></a>Total number of connections that attempt to connect to the MySQL server</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="afa1ae3895f4d401c843020c7fbc3c4f3"><a name="afa1ae3895f4d401c843020c7fbc3c4f3"></a><a name="afa1ae3895f4d401c843020c7fbc3c4f3"></a>≥ 0 counts</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p5332085414379"><a name="p5332085414379"></a><a name="p5332085414379"></a>Monitored object: database</p>
<p id="p1012564514379"><a name="p1012564514379"></a><a name="p1012564514379"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="ra706a410fc654a309f049474098feca9"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a10ebf265ce2d476db917a10ac5e4bc46"><a name="a10ebf265ce2d476db917a10ac5e4bc46"></a><a name="a10ebf265ce2d476db917a10ac5e4bc46"></a>rds007_conn_active_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="add022736f7b34596991a28d4cf3f7cca"><a name="add022736f7b34596991a28d4cf3f7cca"></a><a name="add022736f7b34596991a28d4cf3f7cca"></a>Current Active Connections</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a501d09d5e0db4f13ad022a851d192f4a"><a name="a501d09d5e0db4f13ad022a851d192f4a"></a><a name="a501d09d5e0db4f13ad022a851d192f4a"></a>Number of current active connections</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a22a7c8a5581a4d4ba13d90bfdf560181"><a name="a22a7c8a5581a4d4ba13d90bfdf560181"></a><a name="a22a7c8a5581a4d4ba13d90bfdf560181"></a>≥ 0 counts</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p6672916714379"><a name="p6672916714379"></a><a name="p6672916714379"></a>Monitored object: database</p>
<p id="p6369159214379"><a name="p6369159214379"></a><a name="p6369159214379"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r1c4ff9c240704fadbb1998c880045841"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="af565492e0e2544b7893ea81ae41f8feb"><a name="af565492e0e2544b7893ea81ae41f8feb"></a><a name="af565492e0e2544b7893ea81ae41f8feb"></a>rds008_qps</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a4b0454c0bb3742a0893e325d4a911023"><a name="a4b0454c0bb3742a0893e325d4a911023"></a><a name="a4b0454c0bb3742a0893e325d4a911023"></a>QPS</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a46c6593a5ed447b7902588b218025882"><a name="a46c6593a5ed447b7902588b218025882"></a><a name="a46c6593a5ed447b7902588b218025882"></a>Query times of SQL statements (including storage procedures) per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="ab788e0796e454685b1e22d0d94acbd76"><a name="ab788e0796e454685b1e22d0d94acbd76"></a><a name="ab788e0796e454685b1e22d0d94acbd76"></a>≥ 0 times/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p5894554514379"><a name="p5894554514379"></a><a name="p5894554514379"></a>Monitored object: database</p>
<p id="p6074786014379"><a name="p6074786014379"></a><a name="p6074786014379"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="rbf2541a81a864c308ab28745b46e1103"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="add6acb746169484fbb2c303720ab1cca"><a name="add6acb746169484fbb2c303720ab1cca"></a><a name="add6acb746169484fbb2c303720ab1cca"></a>rds009_tps</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="acfda29393e024334b7a19aff8b9bdae5"><a name="acfda29393e024334b7a19aff8b9bdae5"></a><a name="acfda29393e024334b7a19aff8b9bdae5"></a>TPS</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="ab52ed5869a0b4ee7b2fe668b93391e6a"><a name="ab52ed5869a0b4ee7b2fe668b93391e6a"></a><a name="ab52ed5869a0b4ee7b2fe668b93391e6a"></a>Execution times of submitted and rollback transactions per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a8029df8c6ea74f929f6741ba6a2def9b"><a name="a8029df8c6ea74f929f6741ba6a2def9b"></a><a name="a8029df8c6ea74f929f6741ba6a2def9b"></a>≥ 0 times/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p6044915714379"><a name="p6044915714379"></a><a name="p6044915714379"></a>Monitored object: database</p>
<p id="p717150714379"><a name="p717150714379"></a><a name="p717150714379"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="rb3027a03f6874561974168beda07b80b"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a9644a4d03ac04563ad785bb133a90416"><a name="a9644a4d03ac04563ad785bb133a90416"></a><a name="a9644a4d03ac04563ad785bb133a90416"></a>rds010_innodb_buf_usage</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a99172d34161c4141afd4e3f769bc4922"><a name="a99172d34161c4141afd4e3f769bc4922"></a><a name="a99172d34161c4141afd4e3f769bc4922"></a>Buffer Pool Usage</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="ad490cadfdbaf44eca7b7bc7c192ebb1a"><a name="ad490cadfdbaf44eca7b7bc7c192ebb1a"></a><a name="ad490cadfdbaf44eca7b7bc7c192ebb1a"></a>Ratio of dirty data to all data in the InnoDB buffer</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a857c3f1618e2481ab7548674b09df312"><a name="a857c3f1618e2481ab7548674b09df312"></a><a name="a857c3f1618e2481ab7548674b09df312"></a>0-1</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p6064653214379"><a name="p6064653214379"></a><a name="p6064653214379"></a>Monitored object: database</p>
<p id="p894787614379"><a name="p894787614379"></a><a name="p894787614379"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="rec2319efafe44806bad333417018e7d3"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a14146ef21efe4382b84c6d9d2463862c"><a name="a14146ef21efe4382b84c6d9d2463862c"></a><a name="a14146ef21efe4382b84c6d9d2463862c"></a>rds011_innodb_buf_hit</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a59bbf413e4204f549340e1903820a61a"><a name="a59bbf413e4204f549340e1903820a61a"></a><a name="a59bbf413e4204f549340e1903820a61a"></a>Buffer Pool Hit Rate</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="afaca619fe7af4375a07a613b445650ec"><a name="afaca619fe7af4375a07a613b445650ec"></a><a name="afaca619fe7af4375a07a613b445650ec"></a>Ratio of read hits to read requests in the InnoDB buffer</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a656fc5621a564713be19c821265a1ec0"><a name="a656fc5621a564713be19c821265a1ec0"></a><a name="a656fc5621a564713be19c821265a1ec0"></a>0-1</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p1344211614379"><a name="p1344211614379"></a><a name="p1344211614379"></a>Monitored object: database</p>
<p id="p5387018314379"><a name="p5387018314379"></a><a name="p5387018314379"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r1a884f0ae1cb4514a73f20155eb02efe"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a64a86df7d059412fb22b3f7564c45aae"><a name="a64a86df7d059412fb22b3f7564c45aae"></a><a name="a64a86df7d059412fb22b3f7564c45aae"></a>rds012_innodb_buf_dirty</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a3d3ad6bf14ad4be4a95affa9d0d38ae5"><a name="a3d3ad6bf14ad4be4a95affa9d0d38ae5"></a><a name="a3d3ad6bf14ad4be4a95affa9d0d38ae5"></a>Buffer Pool Dirty Block Rate</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a72bf6233be8d48e095f19ba0e57057f1"><a name="a72bf6233be8d48e095f19ba0e57057f1"></a><a name="a72bf6233be8d48e095f19ba0e57057f1"></a>Ratio of used pages to total pages in the InnoDB buffer</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a39f7316eeed948e98ea03e643940292a"><a name="a39f7316eeed948e98ea03e643940292a"></a><a name="a39f7316eeed948e98ea03e643940292a"></a>0-1</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p58400983143242"><a name="p58400983143242"></a><a name="p58400983143242"></a>Monitored object: database</p>
<p id="p55846803143242"><a name="p55846803143242"></a><a name="p55846803143242"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r07f47da0525c420d8ac738c2ea2811a4"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a4d776c978dc9446a8835728a0b79e571"><a name="a4d776c978dc9446a8835728a0b79e571"></a><a name="a4d776c978dc9446a8835728a0b79e571"></a>rds013_innodb_reads</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a31d86cda9136430caec677a9f11a8025"><a name="a31d86cda9136430caec677a9f11a8025"></a><a name="a31d86cda9136430caec677a9f11a8025"></a>InnoDB Read Throughput</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a357f8d9aa2384163990c6c2ca099b7b6"><a name="a357f8d9aa2384163990c6c2ca099b7b6"></a><a name="a357f8d9aa2384163990c6c2ca099b7b6"></a>Number of read bytes per second in the InnoDB buffer</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a299b8492f65b41a5a23e9a22a6be005c"><a name="a299b8492f65b41a5a23e9a22a6be005c"></a><a name="a299b8492f65b41a5a23e9a22a6be005c"></a>≥ 0 byte/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p44348385143242"><a name="p44348385143242"></a><a name="p44348385143242"></a>Monitored object: database</p>
<p id="p63591148143242"><a name="p63591148143242"></a><a name="p63591148143242"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r523593ba721149e4ade2a332bc4f0884"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="abe6624652521456a808c9f5e15a1f0f1"><a name="abe6624652521456a808c9f5e15a1f0f1"></a><a name="abe6624652521456a808c9f5e15a1f0f1"></a>rds014_innodb_writes</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="ad58cf5270e034bbeabdb37fa51ee9246"><a name="ad58cf5270e034bbeabdb37fa51ee9246"></a><a name="ad58cf5270e034bbeabdb37fa51ee9246"></a>InnoDB Write Throughput</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a8c6b81dd642a435882b136170c07b859"><a name="a8c6b81dd642a435882b136170c07b859"></a><a name="a8c6b81dd642a435882b136170c07b859"></a>Number of write bytes per second in the InnoDB buffer</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="af7d556dfde2b4fd89bb7cace231b2348"><a name="af7d556dfde2b4fd89bb7cace231b2348"></a><a name="af7d556dfde2b4fd89bb7cace231b2348"></a>≥ 0 byte/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p52830813143242"><a name="p52830813143242"></a><a name="p52830813143242"></a>Monitored object: database</p>
<p id="p5715270143242"><a name="p5715270143242"></a><a name="p5715270143242"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r958c764ffcab4a06823c68f387f01b61"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a1cb16b2bbc874a3ab5afea5347869ae2"><a name="a1cb16b2bbc874a3ab5afea5347869ae2"></a><a name="a1cb16b2bbc874a3ab5afea5347869ae2"></a>rds015_innodb_read_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a20f3d173d3a447fbab1d9c79b7951bdd"><a name="a20f3d173d3a447fbab1d9c79b7951bdd"></a><a name="a20f3d173d3a447fbab1d9c79b7951bdd"></a>InnoDB File Read Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="adfaea26f08e84dcf95fdb05bd43c634e"><a name="adfaea26f08e84dcf95fdb05bd43c634e"></a><a name="adfaea26f08e84dcf95fdb05bd43c634e"></a>Number of times that InnoDB reads data from files per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a5002338e8bb64006b7ea212743ccf046"><a name="a5002338e8bb64006b7ea212743ccf046"></a><a name="a5002338e8bb64006b7ea212743ccf046"></a>≥ 0 times/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p5682570143242"><a name="p5682570143242"></a><a name="p5682570143242"></a>Monitored object: database</p>
<p id="p51143138143242"><a name="p51143138143242"></a><a name="p51143138143242"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r9666af210e3b454cb9d62c60907a3767"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a28e70c637aa94339b101e8973d1059de"><a name="a28e70c637aa94339b101e8973d1059de"></a><a name="a28e70c637aa94339b101e8973d1059de"></a>rds016_innodb_write_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="acdd9ac40835343bcb705a84e9469b6b9"><a name="acdd9ac40835343bcb705a84e9469b6b9"></a><a name="acdd9ac40835343bcb705a84e9469b6b9"></a>InnoDB File Write Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a15860f521b924ed09f6552863e5a8b2d"><a name="a15860f521b924ed09f6552863e5a8b2d"></a><a name="a15860f521b924ed09f6552863e5a8b2d"></a>Number of times that InnoDB writes data to files per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a2f9830d93f8f4d7abc6e68b0069f2753"><a name="a2f9830d93f8f4d7abc6e68b0069f2753"></a><a name="a2f9830d93f8f4d7abc6e68b0069f2753"></a>≥ 0 times/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p37928618143242"><a name="p37928618143242"></a><a name="p37928618143242"></a>Monitored object: database</p>
<p id="p5813249143242"><a name="p5813249143242"></a><a name="p5813249143242"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="rc02724b241784deebfaef8a66658a3ec"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="aa41fe6ae760e4efb93665d341c18ea6d"><a name="aa41fe6ae760e4efb93665d341c18ea6d"></a><a name="aa41fe6ae760e4efb93665d341c18ea6d"></a>rds017_innodb_log_write_req_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a4fe8f46aad3c46b2ac963b2eda6d05a9"><a name="a4fe8f46aad3c46b2ac963b2eda6d05a9"></a><a name="a4fe8f46aad3c46b2ac963b2eda6d05a9"></a>InnoDB Log Write Requests per Second</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a1bb0c18e1f4c47418db6286cfb1ed2e4"><a name="a1bb0c18e1f4c47418db6286cfb1ed2e4"></a><a name="a1bb0c18e1f4c47418db6286cfb1ed2e4"></a>Number of InnoDB log write requests per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a1ff97d14f4f54acfaac9c845a7bdc813"><a name="a1ff97d14f4f54acfaac9c845a7bdc813"></a><a name="a1ff97d14f4f54acfaac9c845a7bdc813"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p51363765143230"><a name="p51363765143230"></a><a name="p51363765143230"></a>Monitored object: database</p>
<p id="p59620704143230"><a name="p59620704143230"></a><a name="p59620704143230"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r21a6c4ebd80041f2a604e5ec81953a53"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="ae3d40fc749424ccabab5a47af18c29c4"><a name="ae3d40fc749424ccabab5a47af18c29c4"></a><a name="ae3d40fc749424ccabab5a47af18c29c4"></a>rds018_innodb_log_write_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="aa43ee70ed82b44f090b91c625ade2022"><a name="aa43ee70ed82b44f090b91c625ade2022"></a><a name="aa43ee70ed82b44f090b91c625ade2022"></a>InnoDB Log Physical Write Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a42e15cbc8f274e8cb67a200218680e82"><a name="a42e15cbc8f274e8cb67a200218680e82"></a><a name="a42e15cbc8f274e8cb67a200218680e82"></a>Number of InnoDB physical write times to log files per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a85822d7aa70344a09585df5bde3e05bf"><a name="a85822d7aa70344a09585df5bde3e05bf"></a><a name="a85822d7aa70344a09585df5bde3e05bf"></a>≥ 0 times/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p44058699143230"><a name="p44058699143230"></a><a name="p44058699143230"></a>Monitored object: database</p>
<p id="p60983972143230"><a name="p60983972143230"></a><a name="p60983972143230"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r23790ccf458c4f62b15dd3c128e0d6a5"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a651be825c8d64cb7a3d5e3c8cd8cf1d8"><a name="a651be825c8d64cb7a3d5e3c8cd8cf1d8"></a><a name="a651be825c8d64cb7a3d5e3c8cd8cf1d8"></a>rds019_innodb_log_fsync_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a4d45667f7b9446ab883d5e04e1583cd7"><a name="a4d45667f7b9446ab883d5e04e1583cd7"></a><a name="a4d45667f7b9446ab883d5e04e1583cd7"></a>InnoDB Log fsync() Write Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="addb62df5f82f44778da7ba1d0e78cbc3"><a name="addb62df5f82f44778da7ba1d0e78cbc3"></a><a name="addb62df5f82f44778da7ba1d0e78cbc3"></a>Number of completed fsync() write times to InnoDB log files per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a625b5069275f437595bb462208b9d368"><a name="a625b5069275f437595bb462208b9d368"></a><a name="a625b5069275f437595bb462208b9d368"></a>≥ 0 times/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p31248339143230"><a name="p31248339143230"></a><a name="p31248339143230"></a>Monitored object: database</p>
<p id="p12799595143230"><a name="p12799595143230"></a><a name="p12799595143230"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r9597112ffdb44b169c4dab00b8932c0c"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a411464db50524ca98956ddc7080b0e0c"><a name="a411464db50524ca98956ddc7080b0e0c"></a><a name="a411464db50524ca98956ddc7080b0e0c"></a>rds020_temp_tbl_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a20d84d4d9d5549e68a8d447d32fd7a60"><a name="a20d84d4d9d5549e68a8d447d32fd7a60"></a><a name="a20d84d4d9d5549e68a8d447d32fd7a60"></a>Temporary Tables</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a91c268e9ad824fc48eff4cccd1d70f11"><a name="a91c268e9ad824fc48eff4cccd1d70f11"></a><a name="a91c268e9ad824fc48eff4cccd1d70f11"></a>Number of temporary tables automatically created on hard disks when MySQL statements are executed</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="af83e6819e7724be899d2105a091cd84a"><a name="af83e6819e7724be899d2105a091cd84a"></a><a name="af83e6819e7724be899d2105a091cd84a"></a>≥ 0 counts</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p2772876143230"><a name="p2772876143230"></a><a name="p2772876143230"></a>Monitored object: database</p>
<p id="p24955891143230"><a name="p24955891143230"></a><a name="p24955891143230"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r3ce9b8f17067495993488a2fc0731f10"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a277c48bd12b04338bfa128e2b63de300"><a name="a277c48bd12b04338bfa128e2b63de300"></a><a name="a277c48bd12b04338bfa128e2b63de300"></a>rds021_myisam_buf_usage</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="acdbb880958a84b73bcd23637e2960c6d"><a name="acdbb880958a84b73bcd23637e2960c6d"></a><a name="acdbb880958a84b73bcd23637e2960c6d"></a>Key Buffer Usage</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="afbec1a99e462495a8cda99dccb51cbee"><a name="afbec1a99e462495a8cda99dccb51cbee"></a><a name="afbec1a99e462495a8cda99dccb51cbee"></a>MyISAM key buffer usage</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a0bddbc2c5f0a4997a142df800e292d2c"><a name="a0bddbc2c5f0a4997a142df800e292d2c"></a><a name="a0bddbc2c5f0a4997a142df800e292d2c"></a>0-1</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p6342840143230"><a name="p6342840143230"></a><a name="p6342840143230"></a>Monitored object: database</p>
<p id="p57085565143230"><a name="p57085565143230"></a><a name="p57085565143230"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r3b5651e264b14cd3a5ff71e7ea17f4ce"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a2391dc3c2d424e5e8ec24304cbed3ffa"><a name="a2391dc3c2d424e5e8ec24304cbed3ffa"></a><a name="a2391dc3c2d424e5e8ec24304cbed3ffa"></a>rds022_myisam_buf_write_hit</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a31ea44597e7943ecab307b19bcdc7fae"><a name="a31ea44597e7943ecab307b19bcdc7fae"></a><a name="a31ea44597e7943ecab307b19bcdc7fae"></a>Key Buffer Write Hit Ratio</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a0d06c3188ed24b69b140272949066625"><a name="a0d06c3188ed24b69b140272949066625"></a><a name="a0d06c3188ed24b69b140272949066625"></a>MyISAM key buffer write hit ratio</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="en-us_topic_0029128243_p66622144035"><a name="en-us_topic_0029128243_p66622144035"></a><a name="en-us_topic_0029128243_p66622144035"></a>0-1</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p7612359143159"><a name="p7612359143159"></a><a name="p7612359143159"></a>Monitored object: database</p>
<p id="p1402372143159"><a name="p1402372143159"></a><a name="p1402372143159"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r3565e4201afb4229b93ff6c351ffbd18"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a1d1fd4437c504e7899011dfdab1fa773"><a name="a1d1fd4437c504e7899011dfdab1fa773"></a><a name="a1d1fd4437c504e7899011dfdab1fa773"></a>rds023_myisam_buf_read_hit</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a3be94148df854df9a93bc050f7862b7e"><a name="a3be94148df854df9a93bc050f7862b7e"></a><a name="a3be94148df854df9a93bc050f7862b7e"></a>Key Buffer Read Hit Ratio</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a398f6270c8744dbf9943ca12e0a9591f"><a name="a398f6270c8744dbf9943ca12e0a9591f"></a><a name="a398f6270c8744dbf9943ca12e0a9591f"></a>MyISAM key buffer read hit ratio</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="adc74f84165de4054896627b326bc395b"><a name="adc74f84165de4054896627b326bc395b"></a><a name="adc74f84165de4054896627b326bc395b"></a>0-1</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p15696901143159"><a name="p15696901143159"></a><a name="p15696901143159"></a>Monitored object: database</p>
<p id="p7054385143159"><a name="p7054385143159"></a><a name="p7054385143159"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="rc872bd40ec8247a88b9411d3ae5d16e7"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="af962ca0692d04ed6a10abf74a9393239"><a name="af962ca0692d04ed6a10abf74a9393239"></a><a name="af962ca0692d04ed6a10abf74a9393239"></a>rds024_myisam_disk_write_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="ac0cc9901b69c4f4d954b94b94e1cad17"><a name="ac0cc9901b69c4f4d954b94b94e1cad17"></a><a name="ac0cc9901b69c4f4d954b94b94e1cad17"></a>MyISAM Disk Write Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a3d5e2470b52c4107a30822ef762f78bf"><a name="a3d5e2470b52c4107a30822ef762f78bf"></a><a name="a3d5e2470b52c4107a30822ef762f78bf"></a>Number of times that indexes are written to disks per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a5c14a830457649e98c39786b4b2a98f7"><a name="a5c14a830457649e98c39786b4b2a98f7"></a><a name="a5c14a830457649e98c39786b4b2a98f7"></a>≥ 0 times/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p42373173143159"><a name="p42373173143159"></a><a name="p42373173143159"></a>Monitored object: database</p>
<p id="p45814239143159"><a name="p45814239143159"></a><a name="p45814239143159"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r45ea509430ae48e689252a44cd8f91f7"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a70732c8f51e549a799030f1cf4b7a0b8"><a name="a70732c8f51e549a799030f1cf4b7a0b8"></a><a name="a70732c8f51e549a799030f1cf4b7a0b8"></a>rds025_myisam_disk_read_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="ac39d9021c1b04e99ad9211ab3124f236"><a name="ac39d9021c1b04e99ad9211ab3124f236"></a><a name="ac39d9021c1b04e99ad9211ab3124f236"></a>MyISAM Disk Read Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a74e383341aeb47bc8843201b6d40c952"><a name="a74e383341aeb47bc8843201b6d40c952"></a><a name="a74e383341aeb47bc8843201b6d40c952"></a>Number of times that indexes are read from disks per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="ae4368e33abef458d995c4dfe6de9c43f"><a name="ae4368e33abef458d995c4dfe6de9c43f"></a><a name="ae4368e33abef458d995c4dfe6de9c43f"></a>≥ 0 times/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p45475223143159"><a name="p45475223143159"></a><a name="p45475223143159"></a>Monitored object: database</p>
<p id="p6623823143159"><a name="p6623823143159"></a><a name="p6623823143159"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r9bd8d6c0e0c045f48705705f37d49a59"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a6ce88a2b703747ab8214b4de1845cd2c"><a name="a6ce88a2b703747ab8214b4de1845cd2c"></a><a name="a6ce88a2b703747ab8214b4de1845cd2c"></a>rds026_myisam_buf_write_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a3c0b8486d5fa4779ab25eb0a9c6d311c"><a name="a3c0b8486d5fa4779ab25eb0a9c6d311c"></a><a name="a3c0b8486d5fa4779ab25eb0a9c6d311c"></a>MyISAM Buffer Pool Write Requests per Second</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="ac98ccd6aef2847a68ef5852acde880e0"><a name="ac98ccd6aef2847a68ef5852acde880e0"></a><a name="ac98ccd6aef2847a68ef5852acde880e0"></a>Number of requests for writing indexes into the MyISAM buffer pool per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a37a5891a1ce64ab2b425555864a4e165"><a name="a37a5891a1ce64ab2b425555864a4e165"></a><a name="a37a5891a1ce64ab2b425555864a4e165"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p64038250143159"><a name="p64038250143159"></a><a name="p64038250143159"></a>Monitored object: database</p>
<p id="p39473346143159"><a name="p39473346143159"></a><a name="p39473346143159"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r177d4418ec3b4e57b4b7e394f29af58d"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="aabb939f0a34e4cc39d1347f98e457c69"><a name="aabb939f0a34e4cc39d1347f98e457c69"></a><a name="aabb939f0a34e4cc39d1347f98e457c69"></a>rds027_myisam_buf_read_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="aace7854bfa5140c28076b3b64d88c107"><a name="aace7854bfa5140c28076b3b64d88c107"></a><a name="aace7854bfa5140c28076b3b64d88c107"></a>MyISAM Buffer Pool Read Requests per Second</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a483648d4028044f78b542d1702b3de14"><a name="a483648d4028044f78b542d1702b3de14"></a><a name="a483648d4028044f78b542d1702b3de14"></a>Number of requests for reading indexes from the MyISAM buffer pool per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="aa362cbe50f354952a3f636a9c539457e"><a name="aa362cbe50f354952a3f636a9c539457e"></a><a name="aa362cbe50f354952a3f636a9c539457e"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p33778121143150"><a name="p33778121143150"></a><a name="p33778121143150"></a>Monitored object: database</p>
<p id="p35567636143150"><a name="p35567636143150"></a><a name="p35567636143150"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="rf98061c589db4fb989203077c6e97e54"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a04e5d278b8f04926a16ae0b5980e8955"><a name="a04e5d278b8f04926a16ae0b5980e8955"></a><a name="a04e5d278b8f04926a16ae0b5980e8955"></a>rds028_comdml_del_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a8718077742d646b187cbab3cb4dc0b2f"><a name="a8718077742d646b187cbab3cb4dc0b2f"></a><a name="a8718077742d646b187cbab3cb4dc0b2f"></a>DELETE Statements per Second</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="aa3b479dd4ba145c1a9b7a0ed7051719c"><a name="aa3b479dd4ba145c1a9b7a0ed7051719c"></a><a name="aa3b479dd4ba145c1a9b7a0ed7051719c"></a>Number of DELETE statements executed per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="afbed24ac119b4846bc7a979daa0529e6"><a name="afbed24ac119b4846bc7a979daa0529e6"></a><a name="afbed24ac119b4846bc7a979daa0529e6"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p24785426143150"><a name="p24785426143150"></a><a name="p24785426143150"></a>Monitored object: database</p>
<p id="p21742243143150"><a name="p21742243143150"></a><a name="p21742243143150"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r8b7657074ee9473a9f64c31ad91d9b3c"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a76643f436da04cbb8ecbae32482e73cb"><a name="a76643f436da04cbb8ecbae32482e73cb"></a><a name="a76643f436da04cbb8ecbae32482e73cb"></a>rds029_comdml_ins_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a02b3eb91948748adaba710b383522f74"><a name="a02b3eb91948748adaba710b383522f74"></a><a name="a02b3eb91948748adaba710b383522f74"></a>INSERT Statements per Second</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="ab7d86d48124647df8164bb0061fbbf4f"><a name="ab7d86d48124647df8164bb0061fbbf4f"></a><a name="ab7d86d48124647df8164bb0061fbbf4f"></a>Number of INSERT statements executed per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a4fd948dcf7aa45f0a09abacf78d15d8d"><a name="a4fd948dcf7aa45f0a09abacf78d15d8d"></a><a name="a4fd948dcf7aa45f0a09abacf78d15d8d"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p12403757143150"><a name="p12403757143150"></a><a name="p12403757143150"></a>Monitored object: database</p>
<p id="p44524949143150"><a name="p44524949143150"></a><a name="p44524949143150"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r7c587972d140480baa0c2a3c048a0bfc"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a8506cd394c0c46fda0060a20ccfac125"><a name="a8506cd394c0c46fda0060a20ccfac125"></a><a name="a8506cd394c0c46fda0060a20ccfac125"></a>rds030_comdml_ins_sel_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="ac8e0405d6f594f3da7ff306acebd1f56"><a name="ac8e0405d6f594f3da7ff306acebd1f56"></a><a name="ac8e0405d6f594f3da7ff306acebd1f56"></a>INSERT_SELECT Statements per Second</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a42e3afaa062a462b946dba8c73e58ee3"><a name="a42e3afaa062a462b946dba8c73e58ee3"></a><a name="a42e3afaa062a462b946dba8c73e58ee3"></a>Number of INSERT_SELECT statements executed per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="aadef10d0a5fb417293ce589c8e7b4b9c"><a name="aadef10d0a5fb417293ce589c8e7b4b9c"></a><a name="aadef10d0a5fb417293ce589c8e7b4b9c"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p45106521143150"><a name="p45106521143150"></a><a name="p45106521143150"></a>Monitored object: database</p>
<p id="p3305512143150"><a name="p3305512143150"></a><a name="p3305512143150"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r17779234b7564d7ea95e104227fe4b11"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="ac3aa3fda607f420e8c8e8d19d44ec4d2"><a name="ac3aa3fda607f420e8c8e8d19d44ec4d2"></a><a name="ac3aa3fda607f420e8c8e8d19d44ec4d2"></a>rds031_comdml_rep_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="afa388c5869b34fe4bb7a0340683f13db"><a name="afa388c5869b34fe4bb7a0340683f13db"></a><a name="afa388c5869b34fe4bb7a0340683f13db"></a>REPLACE Statements per Second</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="ab146df5a41854ec09d41933505f32f0f"><a name="ab146df5a41854ec09d41933505f32f0f"></a><a name="ab146df5a41854ec09d41933505f32f0f"></a>Number of REPLACE statements executed per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a91fecf2c2479456ca3ca7778dfd0782e"><a name="a91fecf2c2479456ca3ca7778dfd0782e"></a><a name="a91fecf2c2479456ca3ca7778dfd0782e"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p60908248143150"><a name="p60908248143150"></a><a name="p60908248143150"></a>Monitored object: database</p>
<p id="p11303325143150"><a name="p11303325143150"></a><a name="p11303325143150"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r46ff8a97f73e4038ad365fad3a8202b2"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a665a1b9e39304be1b89d1ac4669823f5"><a name="a665a1b9e39304be1b89d1ac4669823f5"></a><a name="a665a1b9e39304be1b89d1ac4669823f5"></a>rds032_comdml_rep_sel_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a0cf8c7566f99402699f1c3fa333867cd"><a name="a0cf8c7566f99402699f1c3fa333867cd"></a><a name="a0cf8c7566f99402699f1c3fa333867cd"></a>REPLACE_SELECTION Statements per Second</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="ac262948e15bd4a27ba2767eb6a5ae667"><a name="ac262948e15bd4a27ba2767eb6a5ae667"></a><a name="ac262948e15bd4a27ba2767eb6a5ae667"></a>Number of REPLACE_SELECTION statements executed per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="ae209a794ef384e58b49122f15f990ddd"><a name="ae209a794ef384e58b49122f15f990ddd"></a><a name="ae209a794ef384e58b49122f15f990ddd"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p38681473135157"><a name="p38681473135157"></a><a name="p38681473135157"></a>Monitored object: database</p>
<p id="p12588939135157"><a name="p12588939135157"></a><a name="p12588939135157"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="rcf12577bdf15442aaf49a5af2caeb467"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a664edaadf787450e8562353bc20ef7be"><a name="a664edaadf787450e8562353bc20ef7be"></a><a name="a664edaadf787450e8562353bc20ef7be"></a>rds033_comdml_sel_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a2cfa8b16989c4af7b9550bd92ca4e81c"><a name="a2cfa8b16989c4af7b9550bd92ca4e81c"></a><a name="a2cfa8b16989c4af7b9550bd92ca4e81c"></a>SELECT Statements per Second</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="af966d930f87149839f15d28ed5645e5d"><a name="af966d930f87149839f15d28ed5645e5d"></a><a name="af966d930f87149839f15d28ed5645e5d"></a>Number of SELECT statements executed per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="aeeec8247380844e18e1fb72a74bebf27"><a name="aeeec8247380844e18e1fb72a74bebf27"></a><a name="aeeec8247380844e18e1fb72a74bebf27"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p50531529135157"><a name="p50531529135157"></a><a name="p50531529135157"></a>Monitored object: database</p>
<p id="p52130582135157"><a name="p52130582135157"></a><a name="p52130582135157"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r61efb754c8f347a998515ad8dc805a38"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="abffdd2d8e6d94d46899e4490a9a90a61"><a name="abffdd2d8e6d94d46899e4490a9a90a61"></a><a name="abffdd2d8e6d94d46899e4490a9a90a61"></a>rds034_comdml_upd_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a35d3b394d1744de39ee98ad1ec7e3fa4"><a name="a35d3b394d1744de39ee98ad1ec7e3fa4"></a><a name="a35d3b394d1744de39ee98ad1ec7e3fa4"></a>UPDATE Statements per Second</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="ae9532dd93d6c4436b1cc29958bca8a68"><a name="ae9532dd93d6c4436b1cc29958bca8a68"></a><a name="ae9532dd93d6c4436b1cc29958bca8a68"></a>Number of UPDATE statements executed per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a9a79cc586a35432485d3d1f17d4bc02f"><a name="a9a79cc586a35432485d3d1f17d4bc02f"></a><a name="a9a79cc586a35432485d3d1f17d4bc02f"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p19577619135157"><a name="p19577619135157"></a><a name="p19577619135157"></a>Monitored object: database</p>
<p id="p41980851135157"><a name="p41980851135157"></a><a name="p41980851135157"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="rddebdabd7b4a45d980f5a9ae8db0b39b"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="af8b6f2131bfb418ba6c92140ac467947"><a name="af8b6f2131bfb418ba6c92140ac467947"></a><a name="af8b6f2131bfb418ba6c92140ac467947"></a>rds035_innodb_del_row_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a4c3ddb948abf491a85c05eb7ca3893c0"><a name="a4c3ddb948abf491a85c05eb7ca3893c0"></a><a name="a4c3ddb948abf491a85c05eb7ca3893c0"></a>Row Delete Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a9000aa0a606e46cf941148c8254f2118"><a name="a9000aa0a606e46cf941148c8254f2118"></a><a name="a9000aa0a606e46cf941148c8254f2118"></a>Number of rows deleted from the InnoDB table per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a75fed2ab1754488287d755b9ce6b1505"><a name="a75fed2ab1754488287d755b9ce6b1505"></a><a name="a75fed2ab1754488287d755b9ce6b1505"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p2398624135157"><a name="p2398624135157"></a><a name="p2398624135157"></a>Monitored object: database</p>
<p id="p21587618135157"><a name="p21587618135157"></a><a name="p21587618135157"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r7600fe13180f455eae196924969b324e"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a6ac6813e93504bde8e9235a08869941f"><a name="a6ac6813e93504bde8e9235a08869941f"></a><a name="a6ac6813e93504bde8e9235a08869941f"></a>rds036_innodb_ins_row_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="ab7905f7fa660439d929ef701cace31c8"><a name="ab7905f7fa660439d929ef701cace31c8"></a><a name="ab7905f7fa660439d929ef701cace31c8"></a>Row Insert Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="ae2f6cba4e5ee4dcd90592d89bf40b691"><a name="ae2f6cba4e5ee4dcd90592d89bf40b691"></a><a name="ae2f6cba4e5ee4dcd90592d89bf40b691"></a>Number of rows inserted into the InnoDB table per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="ad77db3b1df7e4495984dfec935ce2da3"><a name="ad77db3b1df7e4495984dfec935ce2da3"></a><a name="ad77db3b1df7e4495984dfec935ce2da3"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p33899438135157"><a name="p33899438135157"></a><a name="p33899438135157"></a>Monitored object: database</p>
<p id="p36659490135157"><a name="p36659490135157"></a><a name="p36659490135157"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="rb7cf73319a2e4369aebffbb0e4a15983"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a07c64105d99e45f389af15ff2c5af760"><a name="a07c64105d99e45f389af15ff2c5af760"></a><a name="a07c64105d99e45f389af15ff2c5af760"></a>rds037_innodb_read_row_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a24a9002ab6d94e1998abf1b46580c4ee"><a name="a24a9002ab6d94e1998abf1b46580c4ee"></a><a name="a24a9002ab6d94e1998abf1b46580c4ee"></a>Row Read Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a9059d02b1fa14282b12adec88db6651c"><a name="a9059d02b1fa14282b12adec88db6651c"></a><a name="a9059d02b1fa14282b12adec88db6651c"></a>Number of rows read from the InnoDB table per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a26cdcf2cff7641b4a7b90cb6b49f5c53"><a name="a26cdcf2cff7641b4a7b90cb6b49f5c53"></a><a name="a26cdcf2cff7641b4a7b90cb6b49f5c53"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p15441022135157"><a name="p15441022135157"></a><a name="p15441022135157"></a>Monitored object: database</p>
<p id="p4751477135157"><a name="p4751477135157"></a><a name="p4751477135157"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="rc3a9db89cee34905a66e054a26cdf15d"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a1a903cdba99c4978a4259dbde00e0ccc"><a name="a1a903cdba99c4978a4259dbde00e0ccc"></a><a name="a1a903cdba99c4978a4259dbde00e0ccc"></a>rds038_innodb_upd_row_count</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="a44db68aebd9c4b62963a81a7657a82fa"><a name="a44db68aebd9c4b62963a81a7657a82fa"></a><a name="a44db68aebd9c4b62963a81a7657a82fa"></a>Row Update Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a5bfcdcd102fe4b9cb896376371f9b973"><a name="a5bfcdcd102fe4b9cb896376371f9b973"></a><a name="a5bfcdcd102fe4b9cb896376371f9b973"></a>Number of rows updated into the InnoDB table per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a5858151358e64257915f5371738f1ebc"><a name="a5858151358e64257915f5371738f1ebc"></a><a name="a5858151358e64257915f5371738f1ebc"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p41275217135157"><a name="p41275217135157"></a><a name="p41275217135157"></a>Monitored object: database</p>
<p id="p35932634135157"><a name="p35932634135157"></a><a name="p35932634135157"></a>Monitored instance type: MySQL instances</p>
</td>
</tr>
<tr id="r9f98434644aa4bb1bf05e67fdd90c7b2"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="a64be8ded9a174fc2b638a645164bb00b"><a name="a64be8ded9a174fc2b638a645164bb00b"></a><a name="a64be8ded9a174fc2b638a645164bb00b"></a>rds039_disk_util</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="ac056999825234a86aeb1bde58f13e3ac"><a name="ac056999825234a86aeb1bde58f13e3ac"></a><a name="ac056999825234a86aeb1bde58f13e3ac"></a>Storage Space Usage</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="a227244818c874d2bb5a6f63923d3a22b"><a name="a227244818c874d2bb5a6f63923d3a22b"></a><a name="a227244818c874d2bb5a6f63923d3a22b"></a>Storage space usage of the monitored object</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="a621089c91a5e48b9a70bd2dc3b5ee82e"><a name="a621089c91a5e48b9a70bd2dc3b5ee82e"></a><a name="a621089c91a5e48b9a70bd2dc3b5ee82e"></a>0%–100%</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p759003516483"><a name="p759003516483"></a><a name="p759003516483"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul2592133512487"></a><a name="ul2592133512487"></a><ul id="ul2592133512487"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="row284059149835"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p461393659843"><a name="p461393659843"></a><a name="p461393659843"></a>rds040_transaction_logs_usage</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p8088335992"><a name="p8088335992"></a><a name="p8088335992"></a>Transaction Logs Usage</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p51175371992"><a name="p51175371992"></a><a name="p51175371992"></a>Storage space usage of transaction logs</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p51564412992"><a name="p51564412992"></a><a name="p51564412992"></a>≥ 0 MB</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p15967882992"><a name="p15967882992"></a><a name="p15967882992"></a>Monitored object: database</p>
<p id="p28614813185620"><a name="p28614813185620"></a><a name="p28614813185620"></a>Monitored instance type: PostgreSQL instances</p>
</td>
</tr>
<tr id="row31562129835"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p77229679843"><a name="p77229679843"></a><a name="p77229679843"></a>rds041_replication_slot_usage</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p30752963992"><a name="p30752963992"></a><a name="p30752963992"></a>Replication Slot Usage</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p7962038992"><a name="p7962038992"></a><a name="p7962038992"></a>Storage space usage of replication slot files</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p40945379992"><a name="p40945379992"></a><a name="p40945379992"></a>≥ 0 MB</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p28241392992"><a name="p28241392992"></a><a name="p28241392992"></a>Monitored object: database</p>
<p id="p20027222185615"><a name="p20027222185615"></a><a name="p20027222185615"></a>Monitored instance type: PostgreSQL instances</p>
</td>
</tr>
<tr id="row450899329835"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p128130919843"><a name="p128130919843"></a><a name="p128130919843"></a>rds042_database_connections</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p52662579992"><a name="p52662579992"></a><a name="p52662579992"></a>Database Connections in Use</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p37810472992"><a name="p37810472992"></a><a name="p37810472992"></a>Number of database connections in use</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p42749369992"><a name="p42749369992"></a><a name="p42749369992"></a>≥ 0 counts</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p373704613543"><a name="p373704613543"></a><a name="p373704613543"></a>Monitored object: database</p>
<p id="p3363341713543"><a name="p3363341713543"></a><a name="p3363341713543"></a>Monitored instance type: PostgreSQL instances</p>
</td>
</tr>
<tr id="row348361549835"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p107309549843"><a name="p107309549843"></a><a name="p107309549843"></a>rds043_maximum_used_transaction_ids</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p7622504992"><a name="p7622504992"></a><a name="p7622504992"></a>Maximum Used Transaction IDs</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p13443064992"><a name="p13443064992"></a><a name="p13443064992"></a>Maximum number of transaction IDs that have been used</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p15146409992"><a name="p15146409992"></a><a name="p15146409992"></a>≥ 0 counts</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p2402571413543"><a name="p2402571413543"></a><a name="p2402571413543"></a>Monitored object: database</p>
<p id="p1490483513543"><a name="p1490483513543"></a><a name="p1490483513543"></a>Monitored instance type: PostgreSQL instances</p>
</td>
</tr>
<tr id="row38706839835"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p94263939843"><a name="p94263939843"></a><a name="p94263939843"></a>rds044_transaction_logs_generations</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p20505075992"><a name="p20505075992"></a><a name="p20505075992"></a>Transaction Logs Generation</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p50298377992"><a name="p50298377992"></a><a name="p50298377992"></a>Size of transaction logs generated per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p47636707992"><a name="p47636707992"></a><a name="p47636707992"></a>≥ 0 MB/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p5016649135410"><a name="p5016649135410"></a><a name="p5016649135410"></a>Monitored object: database</p>
<p id="p45149841135410"><a name="p45149841135410"></a><a name="p45149841135410"></a>Monitored instance type: PostgreSQL instances</p>
</td>
</tr>
<tr id="row78866169835"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p502820189843"><a name="p502820189843"></a><a name="p502820189843"></a>rds045_oldest_replication_slot_lag</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p31893805992"><a name="p31893805992"></a><a name="p31893805992"></a>Oldest Replication Slot Lag</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p33261442992"><a name="p33261442992"></a><a name="p33261442992"></a>Lagging size of the most lagging replica in terms of WAL data received</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p9822304992"><a name="p9822304992"></a><a name="p9822304992"></a>≥ 0 MB</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p3510764135411"><a name="p3510764135411"></a><a name="p3510764135411"></a>Monitored object: database</p>
<p id="p31596877135411"><a name="p31596877135411"></a><a name="p31596877135411"></a>Monitored instance type: PostgreSQL instances</p>
</td>
</tr>
<tr id="row83328319835"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p363752969843"><a name="p363752969843"></a><a name="p363752969843"></a>rds046_replication_lag</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p42436472992"><a name="p42436472992"></a><a name="p42436472992"></a>Replication Lag</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p14802198992"><a name="p14802198992"></a><a name="p14802198992"></a>Replication lag delay</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p58127393992"><a name="p58127393992"></a><a name="p58127393992"></a>≥ 0 ms</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p15783187135411"><a name="p15783187135411"></a><a name="p15783187135411"></a>Monitored object: database</p>
<p id="p7830959135411"><a name="p7830959135411"></a><a name="p7830959135411"></a>Monitored instance type: PostgreSQL instances</p>
</td>
</tr>
<tr id="row5950517415252"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p33965557151411"><a name="p33965557151411"></a><a name="p33965557151411"></a>rds047_disk_total_size</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p4325656715335"><a name="p4325656715335"></a><a name="p4325656715335"></a>Total Storage Space</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p1412103815335"><a name="p1412103815335"></a><a name="p1412103815335"></a>Total storage space of the monitored object</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p1878135135412"><a name="p1878135135412"></a><a name="p1878135135412"></a>40–4000 GB</p>
<p id="p8725181468"><a name="p8725181468"></a><a name="p8725181468"></a></p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p240842419505"><a name="p240842419505"></a><a name="p240842419505"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul940912414501"></a><a name="ul940912414501"></a><ul id="ul940912414501"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="row661168615252"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p64829489151411"><a name="p64829489151411"></a><a name="p64829489151411"></a>rds048_disk_used_size</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p556084315335"><a name="p556084315335"></a><a name="p556084315335"></a>Used Storage Space</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p4777512715335"><a name="p4777512715335"></a><a name="p4777512715335"></a>Used storage space of the monitored object</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p119971303217"><a name="p119971303217"></a><a name="p119971303217"></a>0–4000 GB</p>
<p id="p26517211311"><a name="p26517211311"></a><a name="p26517211311"></a></p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p128711320504"><a name="p128711320504"></a><a name="p128711320504"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul829133215509"></a><a name="ul829133215509"></a><ul id="ul829133215509"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="row73463115252"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p16057739151411"><a name="p16057739151411"></a><a name="p16057739151411"></a>rds049_disk_read_throughput</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p1815837015335"><a name="p1815837015335"></a><a name="p1815837015335"></a>Disk Read Throughput</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p6154185215335"><a name="p6154185215335"></a><a name="p6154185215335"></a>Number of bytes read from the disk per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p1883413515335"><a name="p1883413515335"></a><a name="p1883413515335"></a>≥ 0 byte/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p19771183525011"><a name="p19771183525011"></a><a name="p19771183525011"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul127711635175018"></a><a name="ul127711635175018"></a><ul id="ul127711635175018"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="row1499470615252"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p29149396151411"><a name="p29149396151411"></a><a name="p29149396151411"></a>rds050_disk_write_throughput</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p3987662715335"><a name="p3987662715335"></a><a name="p3987662715335"></a>Disk Write Throughput</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p878135015335"><a name="p878135015335"></a><a name="p878135015335"></a>Number of bytes written into the disk per second</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p4020075815335"><a name="p4020075815335"></a><a name="p4020075815335"></a>≥ 0 byte/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p19611145115018"><a name="p19611145115018"></a><a name="p19611145115018"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul1761374595020"></a><a name="ul1761374595020"></a><ul id="ul1761374595020"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="row5386186115252"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p43508968151411"><a name="p43508968151411"></a><a name="p43508968151411"></a>rds051_avg_disk_sec_per_read</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p4688806115335"><a name="p4688806115335"></a><a name="p4688806115335"></a>Disk Read Time</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p3983661115335"><a name="p3983661115335"></a><a name="p3983661115335"></a>Average time required for each disk read in a specified period</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p554006515335"><a name="p554006515335"></a><a name="p554006515335"></a>≥ 0 ms</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p14602104916502"><a name="p14602104916502"></a><a name="p14602104916502"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul16604749145016"></a><a name="ul16604749145016"></a><ul id="ul16604749145016"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="row1344119115252"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p42654571151411"><a name="p42654571151411"></a><a name="p42654571151411"></a>rds052_avg_disk_sec_per_write</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p1217626415335"><a name="p1217626415335"></a><a name="p1217626415335"></a>Disk Write Time</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p4675329015335"><a name="p4675329015335"></a><a name="p4675329015335"></a>Average time required for each disk write in a specified period</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p2892016115335"><a name="p2892016115335"></a><a name="p2892016115335"></a>&gt; 0 ms</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p1645965317507"><a name="p1645965317507"></a><a name="p1645965317507"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul16461553195013"></a><a name="ul16461553195013"></a><ul id="ul16461553195013"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="row3877616715252"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p23778695151411"><a name="p23778695151411"></a><a name="p23778695151411"></a>rds053_avg_disk_queue_length</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p1061468915335"><a name="p1061468915335"></a><a name="p1061468915335"></a>Average Disk Queue Length</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p5448348215335"><a name="p5448348215335"></a><a name="p5448348215335"></a>Number of processes to be written into the monitored object</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p5108595615335"><a name="p5108595615335"></a><a name="p5108595615335"></a>≥ 0</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p5322757175015"><a name="p5322757175015"></a><a name="p5322757175015"></a>Monitored object: ECS. Monitored DB instance type:</p>
<a name="ul1032425714508"></a><a name="ul1032425714508"></a><ul id="ul1032425714508"><li>MySQL</li><li>PostgreSQL</li><li>Microsoft SQL Server</li></ul>
</td>
</tr>
<tr id="row47120437144253"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p58659062144253"><a name="p58659062144253"></a><a name="p58659062144253"></a>rds054_db_connections_in_use</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p33440013144342"><a name="p33440013144342"></a><a name="p33440013144342"></a>Database Connections in Use</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p24286561144342"><a name="p24286561144342"></a><a name="p24286561144342"></a>Number of database connections in use</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p21054425144342"><a name="p21054425144342"></a><a name="p21054425144342"></a>≥ 0 counts</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p42739298144436"><a name="p42739298144436"></a><a name="p42739298144436"></a>Monitored object: database</p>
<p id="p49109367144436"><a name="p49109367144436"></a><a name="p49109367144436"></a>Monitored instance type: Microsoft SQL Server instances</p>
</td>
</tr>
<tr id="row106301028184317"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p1963172819439"><a name="p1963172819439"></a><a name="p1963172819439"></a>rds077_buff_write_rate</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p18631142815432"><a name="p18631142815432"></a><a name="p18631142815432"></a>Buffer Pool Write Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p19631142834316"><a name="p19631142834316"></a><a name="p19631142834316"></a>Write frequency of the database buffer pool</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p153531529468"><a name="p153531529468"></a><a name="p153531529468"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p533155320460"><a name="p533155320460"></a><a name="p533155320460"></a>Monitored object: database</p>
<p id="p99621534154811"><a name="p99621534154811"></a><a name="p99621534154811"></a>Monitored instance type:</p>
</td>
</tr>
<tr id="row740116419438"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p194011441144319"><a name="p194011441144319"></a><a name="p194011441144319"></a>rds078_buff_read_rate</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p172891823155118"><a name="p172891823155118"></a><a name="p172891823155118"></a>Buffer Pool Read Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p2289123105120"><a name="p2289123105120"></a><a name="p2289123105120"></a>Read frequency of the database buffer pool</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p10401104134315"><a name="p10401104134315"></a><a name="p10401104134315"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p189851356135014"><a name="p189851356135014"></a><a name="p189851356135014"></a>Monitored object: database</p>
<p id="p598545645017"><a name="p598545645017"></a><a name="p598545645017"></a>Monitored instance type:</p>
</td>
</tr>
<tr id="row1258163884319"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p172641329535"><a name="p172641329535"></a><a name="p172641329535"></a>rds079_disk_write_rate</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p0165145345215"><a name="p0165145345215"></a><a name="p0165145345215"></a>Disk Write Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p41654532529"><a name="p41654532529"></a><a name="p41654532529"></a>Write frequency of the database disk</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p1658283874316"><a name="p1658283874316"></a><a name="p1658283874316"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p12692458145013"><a name="p12692458145013"></a><a name="p12692458145013"></a>Monitored object: database</p>
<p id="p6693858115011"><a name="p6693858115011"></a><a name="p6693858115011"></a>Monitored instance type:</p>
</td>
</tr>
<tr id="row7523835194317"><td class="cellrowborder" valign="top" width="15.229999999999999%" headers="mcps1.2.6.1.1 "><p id="p1226418212538"><a name="p1226418212538"></a><a name="p1226418212538"></a>rds080_disk_read_rate</p>
</td>
<td class="cellrowborder" valign="top" width="16.13%" headers="mcps1.2.6.1.2 "><p id="p6325135765213"><a name="p6325135765213"></a><a name="p6325135765213"></a>Disk Read Frequency</p>
</td>
<td class="cellrowborder" valign="top" width="19.38%" headers="mcps1.2.6.1.3 "><p id="p12325557165212"><a name="p12325557165212"></a><a name="p12325557165212"></a>Read frequency of the database disk</p>
</td>
<td class="cellrowborder" valign="top" width="26.32%" headers="mcps1.2.6.1.4 "><p id="p1352433574313"><a name="p1352433574313"></a><a name="p1352433574313"></a>≥ 0 count/s</p>
</td>
<td class="cellrowborder" valign="top" width="22.939999999999998%" headers="mcps1.2.6.1.5 "><p id="p19587259115012"><a name="p19587259115012"></a><a name="p19587259115012"></a>Monitored object: database</p>
<p id="p20587195916505"><a name="p20587195916505"></a><a name="p20587195916505"></a>Monitored instance type:</p>
</td>
</tr>
</tbody>
</table>

## Dimension<a name="section34967986154738"></a>

<a name="table20447661154756"></a>
<table><thead align="left"><tr id="row58418561154756"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p34282994154756"><a name="p34282994154756"></a><a name="p34282994154756"></a>Key</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p25459095154756"><a name="p25459095154756"></a><a name="p25459095154756"></a>Value</p>
</th>
</tr>
</thead>
<tbody><tr id="row48920792154756"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p3161247154756"><a name="p3161247154756"></a><a name="p3161247154756"></a>rds_instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p54734417154756"><a name="p54734417154756"></a><a name="p54734417154756"></a>Specifies the MySQL DB instance ID.</p>
</td>
</tr>
<tr id="row19239953174347"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p14932367174347"><a name="p14932367174347"></a><a name="p14932367174347"></a>postgresql_instance_id</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p1562254174347"><a name="p1562254174347"></a><a name="p1562254174347"></a>Specifies the PostgreSQL DB instance ID.</p>
</td>
</tr>
<tr id="row66237070144518"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p63602487144518"><a name="p63602487144518"></a><a name="p63602487144518"></a>rds_instance_sqlserver_id</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p51527828144518"><a name="p51527828144518"></a><a name="p51527828144518"></a>Specifies the Microsoft SQL Server DB instance ID.</p>
</td>
</tr>
</tbody>
</table>

## API Calling<a name="section44139388154359"></a>

Use APIs to search for RDS monitoring metrics. For details about calling methods and parameter description, see section "Querying Monitoring Data" in the  _Cloud Eye API Reference_.

Examples:

-   Request

```
/V1.0/{project_id}/metric-data?namespace=SYS.RDS&metric_name=rds001_cpu_usage&dim.0=rds_instance_id,5ea170ad-cc6b-49cd-9020-e94fdbeea391&from=1484123686000&to=1568188853000&period=300&filter=average
```

-   Response:

```
{
    "datapoints": [
        {
            "average": 0.35, 
            "timestamp": 1484123400000, 
            "unit": "Ratio"
        },
        {
            "average": 0.11, 
            "timestamp": 1484123700000, 
            "unit": "Ratio"
        }
    ], 
    "metric_name": "rds001_cpu_usage",
    "httpcode" : 200,
    "header" : {
    "Transfer-Encoding" : "chunked",
    "Server" : "Web Server",
    "X-Request-Id" : "te-I-CES-APISVR25.id-0418d62a-1e76-46ff-9a5f-9ce40b336e29.ts-1484123744291.c-15046",
    "X-Content-Type-Options" : "nosniff",
    "Connection" : "keep-alive",
    "X-Download-Options" : "noopen",
    "Date" : "Wed, 11 Jan 2017 08:35:44 GMT",
    "X-Frame-Options" : "DENY",
    "Strict-Transport-Security" : "max-age=31536000; includeSubdomains;",
    "Cache-Control" : "no-cache",
    "X-XSS-Protection" : "1; mode=block;",
    "Content-Length" : "165",
    "Content-Type" : "application/json"
}
}
```

