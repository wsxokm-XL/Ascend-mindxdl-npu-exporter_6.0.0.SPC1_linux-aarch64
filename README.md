# Ascend-mindxdl-npu-exporter_6.0.0.SPC1_linux-aarch64
Ascend-mindxdl-npu-exporter_6.0.0.SPC1_linux-aarch64.zip 备份保存

官方文档：https://www.hiascend.com/document/detail/zh/mindx-dl/600/clusterscheduling/clusterschedulingig/clusterschedulingig/dlug_installation_009.html#ZH-CN_TOPIC_0000002246004981__section10979172103311
下载地址：https://gitee.com/ascend/mind-cluster/releases/tag/v6.0.0.SPC1


MindCluster 7.2.RC1版本 mind-cluster-master-component-npu-exporter.zip
参考：https://gitcode.com/Ascend/mind-cluster/tree/master/component/npu-exporter

执行以下命令，进入Npu-Exporter构建目录，执行构建脚本，在“output“目录下生成二进制npu-exporter、yaml文件和Dockerfile等文件。

```
cd /home/mind-cluster/component/npu-exporter/build/
chmod +x build.sh
./build.sh
```
执行以下命令，查看output生成的软件列表。
```
ll /home/mind-cluster/component/npu-exporter/output
```
```
drwxr-xr-x  2 root root     4096 Feb 23 07:10 .
drwxr-xr-x 10 root root     4096 Feb 23 07:10 ..
-r--------  1 root root      623 Feb 23 07:10 Dockerfile
-r--------  1 root root      623 Feb 23 07:10 Dockerfile-310P-1usoc
-r--------  1 root root      623 Feb 23 07:10 metricConfiguration.json
-r-x------  1 root root 25481072 Feb 23 07:10 npu-exporter
-r--------  1 root root     3438 Feb 23 07:10 npu-exporter-310P-1usoc-v6.0.0.yaml
-r--------  1 root root     3438 Feb 23 07:10 npu-exporter-v6.0.0.yaml
-r--------  1 root root      623 Feb 23 07:10 pluginConfiguration.json
-r-x------  1 root root     2579 Feb 23 07:10 run_for_310P_1usoc.sh
```
