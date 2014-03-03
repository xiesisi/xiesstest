OCDC-OCHadoop-V02B00C00-beta-20140227

1、产品完成情况
根据OCDC产品的发布计划，当前redmine中的OCDC-OCHadoop-V02B00C00-beta-20140227的需求/BUG状态统计如下: 
问题总数： 13个（需 求：3个，BUG：10个，DB变更：0个） ，关闭：13个，未关闭：0个。

2、产品主要特征
本次版本以主要包含以下内容：
1).本产品主要融合以下版本的开源产品
     hadoop：2.0.0-cdh4.2.1
     hbase： 0.94.12
     hive：0.12.0和0.11.0
     zookeeper：3.4.5-cdh4.2.1
2).日志审计功能：日志审计主要用于监控集群中服务对数据的访问操作，用作审计报告和分析等，管理员可用此判断集群的健康、安全状态，更直观展示集群的活动和数据的访问。OCHadoop的日志审计也是为了实现上述目标而设计的。更多介绍参考：这里
3).支持LZO的压缩格式。
4).默认设置被删除文件在回收站中的生命周期为24小时（即24小时小时后自动删除HDFS回收站的文件）。

3、	Release Notes
1）	解决了hive0.11.0调用cdh4的MR1的问题。
2）	解决了hive0.12.0 load数据时同名文件存在时报错的问题。
      
4、源码地址
GitHub地址：https://github.com/asiainfo-linkage/ochadoop/releases/tag/och2.0.0-beta

5、问题跟踪
GitHub地址：https://github.com/asiainfo-linkage/ochadoop/issues

6、产品支持人员：
邵 安清 shaoaq@asiainfo-linkage.com   13466327939
张  丽  zhangli3@asiainfo-linkage.com 18610111089
郭 云凯 guoyk@asiainfo-linkage.com    18601153215
欲了解产品发布详情，请访问发布站点：http://10.1.252.21:8088/redmine/projects/ochadoop/wiki/OCDC-OCHadoop-V02B00C00-20140227
