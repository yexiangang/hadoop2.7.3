# hadoop2.7.3
初步配置好伪分布式集群，下载即可用。
 注意的点：
 * 放在当前账户的路径，放在/usr/local因为/tmp的权限问题很蛋疼
 * 单台机器配置的伪分布式在maprd-site.xml中配置uber模式，就不会因为申请不到资源卡住。
