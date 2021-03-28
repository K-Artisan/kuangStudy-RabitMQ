#  目录

[TOC]


# 课程地址

视频：

https://www.bilibili.com/video/BV1dX4y1V73G?p=1

资源：

https://www.kuangstudy.com/course/detail/1323452886432944129



# 课程安排

- RabbitMQ-01、什么是中间件
- RabbitMQ-02、聊聊中间件技术及单体和分布式架构
- RabbitMQ-03、基于消息中间件的分布式系统的架构
- RabbitMQ-04、消息队列协议
- RabbitMQ-05、消息队列的持久化
- RabbitMQ-06、消息的分发策略
- RabbitMQ-07、消息队列高可用和高可靠
- RabbitMQ-08、入门及安装
- RabbitMQ-09、Web管理界面及授权操作
- RabbitMQ-10、Docker安装RabbitMQ
- RabbitMQ-11、角色分类
- RabbitMQ-12、快速入门案例
- RabbitMQ-13、AMQP讲解
- RabbitMQ-14、RabbitMQ的组件和架构
- RabbitMQ-15、简单模式理解
- RabbitMQ-16、Fanout模式理解
- RabbitMQ-17、Direct模式理解
- RabbitMQ-18、Topic模式理解
- RabbitMQ-19、Headers模式理解
- RabbitMQ-20、Fanout模式入门案例
- RabbitMQ-21、Direct模式入门案例
- RabbitMQ-22、Topic模式入门案例
- RabbitMQ-23、完整的声明创建方式
- RabbitMQ-24、Work轮询模式讲解
- RabbitMQ-25、Work公平分发讲解
- RabbitMQ-26、MQ的使用场景
- RabbitMQ-27、整合Springboot-生产者-Fanout模式
- RabbitMQ-28、整合Springboot-消费者-Fanout模式
- RabbitMQ-29、整合Springboot-Direct模式
- RabbitMQ-30、整合Springboot-Topic模式
- RabbitMQ-31、高级-ttl队列过期时间
- RabbitMQ-32、高级-ttl消息过期时间
- RabbitMQ-33、高级-死信队列
- RabbitMQ-34、内存磁盘的监控
- RabbitMQ-35、集群搭建
- RabbitMQ-36、集群web界面管理调试
- RabbitMQ-37、高级-分布式事务概述
- RabbitMQ-38、高级-分布式事务案例
- RabbitMQ-39、高级-分布式事务-可靠生产和推送确认
- RabbitMQ-40、高级-分布式事务-可靠消费
- RabbitMQ-41、高级-分布式事务-可靠消费重试机制
- RabbitMQ-42、高级-分布式事务-可靠消费死信队列
- RabbitMQ-43、高级-分布式事务总结
- RabbitMQ-44、小结以及展望





# 什么是中间件

<img src="images/KuangStudy-RabbitMQ/1616849849231.png" alt="1616849849231" />

![1616850145804](images/KuangStudy-RabbitMQ/1616850145804.png)

![1616849979804](images/KuangStudy-RabbitMQ/1616849979804.png)

![1616850201387](images/KuangStudy-RabbitMQ/1616850201387.png)



![1616850318922](images/KuangStudy-RabbitMQ/1616850318922.png)



# 聊聊中间件技术及单体和分布式架构

<img src="images/KuangStudy-RabbitMQ/1616850488182.png" alt="1616850488182" style="zoom: 80%;" />

<img src="images/KuangStudy-RabbitMQ/1616850375114.png" alt="1616850375114" style="zoom:50%;" />





<img src="images/KuangStudy-RabbitMQ/1616850807275.png" alt="1616850807275" style="zoom:50%;" />

<img src="images/KuangStudy-RabbitMQ/1616850730755.png" alt="1616850730755" style="zoom: 50%;" />![1616850807275](images/KuangStudy-RabbitMQ/1616850807275.png)![1616850833320](images/KuangStudy-RabbitMQ/1616850833320.png)![1616850874485](images/KuangStudy-RabbitMQ/1616850874485.png)

<img src="images/KuangStudy-RabbitMQ/1616850730755.png" alt="1616850730755" style="zoom: 50%;" />



<img src="images/KuangStudy-RabbitMQ/1616850807275.png" alt="1616850807275" style="zoom:50%;" />

![1616852306685](images/KuangStudy-RabbitMQ/1616852306685.png)

![1616852766016](images/KuangStudy-RabbitMQ/1616852766016.png)

![1616852659824](images/KuangStudy-RabbitMQ/1616852659824.png)

![1616852877646](images/KuangStudy-RabbitMQ/1616852877646.png)

![1616852839414](images/KuangStudy-RabbitMQ/1616852839414.png)

![1616853074167](images/KuangStudy-RabbitMQ/1616853074167.png)

![1616853260227](images/KuangStudy-RabbitMQ/1616853260227.png)



# 基于消息中间件的分布式系统的架构

![1616854043296](images/KuangStudy-RabbitMQ/1616854043296.png)

![1616854073871](images/KuangStudy-RabbitMQ/1616854073871.png)

![1616854211138](images/KuangStudy-RabbitMQ/1616854211138.png)

![1616854360898](images/KuangStudy-RabbitMQ/1616854360898.png)

10w并发量

![1616854596941](images/KuangStudy-RabbitMQ/1616854596941.png)

![1616854701935](images/KuangStudy-RabbitMQ/1616854701935.png)

![1616854921122](images/KuangStudy-RabbitMQ/1616854921122.png)

![1616855250026](images/KuangStudy-RabbitMQ/1616855250026.png)

# 消息队列协议

<img src="images/KuangStudy-RabbitMQ/1616855304730.png" alt="1616855304730" style="zoom:50%;" />

什么是协议

![1616855376084](images/KuangStudy-RabbitMQ/1616855376084.png)

![1616856184504](images/KuangStudy-RabbitMQ/1616856184504.png)

![1616856304669](images/KuangStudy-RabbitMQ/1616856304669.png)

![1616856433656](images/KuangStudy-RabbitMQ/1616856433656.png)

![1616857006778](images/KuangStudy-RabbitMQ/1616857006778.png)

![1616857085203](images/KuangStudy-RabbitMQ/1616857085203.png)

![1616857180117](images/KuangStudy-RabbitMQ/1616857180117.png)





# 消息队列的持久化

![1616857335220](images/KuangStudy-RabbitMQ/1616857335220.png)

 ![1616857570808](images/KuangStudy-RabbitMQ/1616857570808.png)



# 消息的分发策略

![1616857726130](images/KuangStudy-RabbitMQ/1616857726130.png)

![1616857872347](images/KuangStudy-RabbitMQ/1616857872347.png)

![1616857859096](images/KuangStudy-RabbitMQ/1616857859096.png)

![1616857933948](images/KuangStudy-RabbitMQ/1616857933948.png)

![1616858027289](images/KuangStudy-RabbitMQ/1616858027289.png)

# 消息队列高可用和高可靠

<img src="images/KuangStudy-RabbitMQ/1616859219291.png" alt="1616859219291" style="zoom:50%;" />

![1616859108876](images/KuangStudy-RabbitMQ/1616859108876.png)

![1616859451683](images/KuangStudy-RabbitMQ/1616859451683.png)

![1616859470100](images/KuangStudy-RabbitMQ/1616859470100.png)

不存在消息副本

![1616859536212](images/KuangStudy-RabbitMQ/1616859536212.png)

存在消息副本，单写多读

![1616859764430](images/KuangStudy-RabbitMQ/1616859764430.png)

> 解释：和上面的区别不大，但是 他的写入可以往任意节点去写入

![1616860108703](images/KuangStudy-RabbitMQ/1616860108703.png)

![1616860282015](images/KuangStudy-RabbitMQ/1616860282015.png)

> 小公司一般不会使用这种模式，成本比较大，至少需要6台服务器？



反正终归三局话：

- 要么消息共享
- 要么消息同步
- 要么元数据共享

![1616860515370](images/KuangStudy-RabbitMQ/1616860515370.png)





# RabbitMQ入门及安装

官方网站：https://www.rabbitmq.com/



![1616861311882](images/KuangStudy-RabbitMQ/1616861311882.png)



![1616861588244](images/KuangStudy-RabbitMQ/1616861588244.png)

![1616861816859](images/KuangStudy-RabbitMQ/1616861816859.png)

![1616944705111](images/KuangStudy-RabbitMQ/1616944705111.png)

![1616944674078](images/KuangStudy-RabbitMQ/1616944674078.png)

## 下载

### **RabbitMQ**下载

https://www.rabbitmq.com/download.html

> 因为现在安装包已经放到了Github上，下载比较慢，故：先下载到本机，在上传到云服务器

这里我们下载：[CentOS7.x版本](https://github-releases.githubusercontent.com/924551/01217e00-7b7e-11eb-9ba0-11817d4f9778?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20210327%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210327T161048Z&X-Amz-Expires=300&X-Amz-Signature=b672a597bd510fcac071a09e81bb2cd9dcafa56b69eade8a0d05d46233d7a68e&X-Amz-SignedHeaders=host&actor_id=35329755&key_id=0&repo_id=924551&response-content-disposition=attachment%3B filename%3Drabbitmq-server-3.8.14-1.el7.noarch.rpm&response-content-type=application%2Foctet-stream)

rabbitmq-server-3.8.14-1.el7.noarch.rpm

看到文件，知道其版本号为3.814



### **Erlang**下载

**Erlang**官网https://www.erlang-solutions.com/downloads/

RabbitMQ 与Erlang版本对应：https://www.rabbitmq.com/which-erlang.html

![1616941060194](images/KuangStudy-RabbitMQ/1616941060194.png)



https://www.rabbitmq.com/download.html

![1616942699992](images/KuangStudy-RabbitMQ/1616942699992.png)



https://github.com/rabbitmq/erlang-rpm

https://github.com/rabbitmq/erlang-rpm/releases/tag/v23.3

 Redhat7\CentOS7对应的版本： [erlang-23.3-2.el7.x86_64.rpm](https://github.com/rabbitmq/erlang-rpm/releases/download/v23.3/erlang-23.3-2.el7.x86_64.rpm)



## 安装

### 安装Erlang

```shell
[root@centos7 ~]# mkdir -p /usr/rabbitmq
[root@centos7 ~]# cd /usr/rabbitmq/
# 本地上传安装文件
[root@centos7 rabbitmq]# ls
erlang-23.3-2.el7.x86_64.rpm  rabbitmq-server-3.8.14-1.el7.noarch.rpm

# 解压?安装?
[root@centos7 rabbitmq]# rpm -Uvh erlang-23.3-2.el7.x86_64.rpm 
警告：erlang-23.3-2.el7.x86_64.rpm: 头V4 RSA/SHA1 Signature, 密钥 ID 6026dfca: NOKEY
准备中...                          ################################# [100%]
	软件包 erlang-23.3-2.el7.x86_64 已经安装
	
#yum安装
[root@centos7 rabbitmq]# yum install -vy erlang-23.3-2.el7.x86_64
加载 "fastestmirror" 插件
加载 "langpacks" 插件
Adding zh_CN.UTF-8 to language list
Config time: 0.014
Yum version: 3.4.3
rpmdb time: 0.001
设置软件包群集
Loading mirror speeds from cached hostfile
 * base: mirrors.ustc.edu.cn
 * extras: mirrors.ustc.edu.cn
 * updates: mirrors.aliyun.com
base                                                                                                                                                                                      | 3.6 kB  00:00:00     
docker-ce-stable                                                                                                                                                                          | 3.5 kB  00:00:00     
extras                                                                                                                                                                                    | 2.9 kB  00:00:00     
updates                                                                                                                                                                                   | 2.9 kB  00:00:00     
updates/7/x86_64/primary_db                                                                                                                                                               | 6.5 MB  00:00:01     
pkgsack time: 4.825
检测 erlang-23.3-2.el7.x86_64 提供的依赖或文件
无须任何处理

# 检查安装成功
[root@centos7 rabbitmq]# erl -v
Erlang/OTP 23 [erts-11.2] [source] [64-bit] [smp:4:4] [ds:4:4:10] [async-threads:1] [hipe]

```

说明：

rpm命令：https://www.linuxcool.com/rpm

yum 命令：https://www.linuxcool.com/yum



### 安装socat

安装RabbitMQ过程中要依赖一个插件`socat`，所以先安装socat

```shell
[root@centos7 rabbitmq]# yum install -y socat
已加载插件：fastestmirror, langpacks
Loading mirror speeds from cached hostfile
 * base: mirrors.ustc.edu.cn
 * extras: mirrors.ustc.edu.cn
 * updates: mirrors.aliyun.com
正在解决依赖关系
--> 正在检查事务
---> 软件包 socat.x86_64.0.1.7.3.2-2.el7 将被 安装
--> 解决依赖关系完成

依赖关系解决

=================================================================================================================================================================================================================
 Package                                         架构                                             版本                                                      源                                              大小
=================================================================================================================================================================================================================
正在安装:
 socat                                           x86_64                                           1.7.3.2-2.el7                                             base                                           290 k

事务概要
=================================================================================================================================================================================================================
安装  1 软件包

总下载量：290 k
安装大小：1.1 M
Downloading packages:
socat-1.7.3.2-2.el7.x86_64.rpm                                                                                                                                                            | 290 kB  00:00:00     
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
警告：RPM 数据库已被非 yum 程序修改。
  正在安装    : socat-1.7.3.2-2.el7.x86_64                                                                                                                                                                   1/1 
  验证中      : socat-1.7.3.2-2.el7.x86_64                                                                                                                                                                   1/1 

已安装:
  socat.x86_64 0:1.7.3.2-2.el7                                                                                                                                                                                   

完毕！
```

### 安装RabbitMQ

这里使用本地上传的安装包安装：

```shell
[root@centos7 rabbitmq]# rpm -Uvh rabbitmq-server-3.8.14-1.el7.noarch.rpm 
警告：rabbitmq-server-3.8.14-1.el7.noarch.rpm: 头V4 RSA/SHA256 Signature, 密钥 ID 6026dfca: NOKEY
准备中...                          ################################# [100%]
正在升级/安装...
   1:rabbitmq-server-3.8.14-1.el7     ################################# [100%]

[root@centos7 rabbitmq]# yum install rabbitmq-server
已加载插件：fastestmirror, langpacks
Loading mirror speeds from cached hostfile
 * base: mirrors.ustc.edu.cn
 * extras: mirrors.ustc.edu.cn
 * updates: mirrors.aliyun.com
无须任何处理

```



### 启动服务

```shell
#启动服务，停止用：systemctl start rabbitmq-server
[root@centos7 rabbitmq]# systemctl start rabbitmq-server

# 查看服务状态
[root@centos7 rabbitmq]# systemctl status rabbitmq-server
● rabbitmq-server.service - RabbitMQ broker
   Loaded: loaded (/usr/lib/systemd/system/rabbitmq-server.service; disabled; vendor preset: disabled)
   Active: active (running) since 日 2021-03-28 23:24:25 CST; 29s ago
 Main PID: 11372 (beam.smp)
   Status: "Initialized"
    Tasks: 28
   Memory: 75.1M
   CGroup: /system.slice/rabbitmq-server.service
           ├─11372 /usr/lib64/erlang/erts-11.2/bin/beam.smp -W w -MBas ageffcbf -MHas ageffcbf -MBlmbcs 512 -MHlmbcs 512 -MMmcs 30 -P 1048576 -t 5000000 -stbt db -zdbbl 128000 -sbwt none -sbwtdcpu none -sbw...
           ├─11388 erl_child_setup 32768
           ├─11415 /usr/lib64/erlang/erts-11.2/bin/epmd -daemon
           ├─11440 inet_gethost 4
           └─11486 inet_gethost 4

3月 28 23:23:36 centos7.6 rabbitmq-server[11372]: ##########  Licensed under the MPL 2.0. Website: https://rabbitmq.com
3月 28 23:23:36 centos7.6 rabbitmq-server[11372]: Doc guides: https://rabbitmq.com/documentation.html
3月 28 23:23:36 centos7.6 rabbitmq-server[11372]: Support:    https://rabbitmq.com/contact.html
3月 28 23:23:36 centos7.6 rabbitmq-server[11372]: Tutorials:  https://rabbitmq.com/getstarted.html
3月 28 23:23:36 centos7.6 rabbitmq-server[11372]: Monitoring: https://rabbitmq.com/monitoring.html
3月 28 23:23:36 centos7.6 rabbitmq-server[11372]: Logs: /var/log/rabbitmq/rabbit@centos7.log
3月 28 23:23:36 centos7.6 rabbitmq-server[11372]: /var/log/rabbitmq/rabbit@centos7_upgrade.log
3月 28 23:23:36 centos7.6 rabbitmq-server[11372]: Config file(s): (none)
3月 28 23:24:25 centos7.6 rabbitmq-server[11372]: Starting broker... completed with 0 plugins.
3月 28 23:24:25 centos7.6 systemd[1]: Started RabbitMQ broker.

#开启启动服务
[root@centos7 rabbitmq]# systemctl enable rabbitmq-server
Created symlink from /etc/systemd/system/multi-user.target.wants/rabbitmq-server.service to /usr/lib/systemd/system/rabbitmq-server.service.

```

![1616945313807](images/KuangStudy-RabbitMQ/1616945313807.png)

```shell
firewall-cmd --zone=public --add-port=15672/tcp --permanent 
```



## Docker 安装

镜像仓储：https://registry.hub.docker.com/_/rabbitmq/

下载镜像：

```shell
[root@centos7 ~]# docker pull rabbitmq:management
management: Pulling from library/rabbitmq
6e0aa5e7af40: Pull complete 
d47239a868b3: Pull complete 
49cbb10cca85: Pull complete 
b7c2edd50e35: Pull complete 
a6bdd84df6f2: Pull complete 
db4e517e38d3: Pull complete 
b3982db455b0: Pull complete 
9f6708aa7fd0: Pull complete 
21c9ffa1be59: Pull complete 
5c6680e36ae7: Pull complete 
fffa3770b398: Pull complete 
213b533bb8a3: Pull complete 
97df3b39dc36: Pull complete 
Digest: sha256:7ac3902a85940c5c1cf4cdf0f528196b8139344bc79e9b3fa8c9b60c7a4ea293
Status: Downloaded newer image for rabbitmq:management
docker.io/library/rabbitmq:management

```



运行容器：

```shell
[root@centos7 ~]# docker run -di --name myrabitt -e RABBITMQ_DEFAULT_USER=admin  -e RABBITMQ_DEFAULT_PASS=admin -p 15672:15672 -p 25672:25672 -p 61613:61613 -p 1883:1883 rabbitmq:management 
2357e6b49c268ccb4709027662ed99bcbdca15026dd33054cca5528b286d60e3
docker: Error response from daemon: driver failed programming external connectivity on endpoint myrabitt (0754377287f0d53bd0a6d04dd7430782f2b04b53c9786edc1f21be9e1fb0758c): Error starting userland proxy: listen tcp4 0.0.0.0:61613: bind: address already in use.


```

因为我们在同一个虚拟机中安装了RabbitMQ，然后由使用同一个端口去安装Docker，为了避免端口冲突和练习的混淆，徒增学习复杂度，我们新建一个虚拟机**(192.168.130.130)**，使用Docker的方式安装RabbitMQ；

```shell
[root@centos7 ~]# docker run -di --name myrabitt -e RABBITMQ_DEFAULT_USER=admin  -e RABBITMQ_DEFAULT_PASS=admin -p 15672:15672 -p 25672:25672 -p 61613:61613 -p 1883:1883 rabbitmq:management 
4f795f5970b7bf00be344b6b516b7e1c28170210a5cb460d3f70fca2a119be0f
[root@centos7 ~]# docker ps 
CONTAINER ID   IMAGE    COMMAND        CREATED    STATUS       PORTS     NAMES
4f795f5970b7   rabbitmq:management   "docker-entrypoint.s…"   11 seconds ago   Up 6 seconds   4369/tcp, 5671-5672/tcp, 0.0.0.0:1883->1883/tcp, 15671/tcp, 0.0.0.0:15672->15672/tcp, 0.0.0.0:25672->25672/tcp, 0.0.0.0:61613->61613/tcp, 15691-15692/tcp   myrabitt

```

查看日志：

```shell
[root@centos7 ~]#docker logs myrabitt
```

访问：http://192.168.130.130:15672/ 就可以看到一个管理界面

![](images/KuangStudy-RabbitMQ/1616961355951.png)默认的账号和密码都是admin（创建docker容器时我们指定的）：

```shell
docker run -di --name myrabitt -e RABBITMQ_DEFAULT_USER=admin  -e RABBITMQ_DEFAULT_PASS=admin ......
```





## Linux 相关排除命令

```shell
more xxx.log  查看日志
netstat -naop | grep 5672 查看端口是否被占用
ps -ef |grep 5672 查看进程
systemctl stop 服务名
```





# Web管理界面及授权操作

RabbitMQ插件:https://www.rabbitmq.com/management.html



![1616945456813](images/KuangStudy-RabbitMQ/1616945456813.png)



虚拟机192.168.130.129中安装RabbitMQ管理插件失败：

```shell
[root@centos7 ~]# rabbitmq-plugins enable rabbitmq_management
{:query, :rabbit@centos7, {:badrpc, :timeout}}
```



<img src="images/KuangStudy-RabbitMQ/1616962474176.png" alt="1616962474176" style="zoom:80%;" />

安装RabbitMQ管理插件失败：好像这个版本不用安装，默认就已经开启了这个管理插件，账号和密码都是guest

并且这个账号是admin角色

<img src="images/KuangStudy-RabbitMQ/1616963635987.png" alt="1616963635987" style="zoom:80%;" />

>只是：
>
>- 虚拟机外（windows 10 宿主主机）无法访问这个管理界面，这就好比远程云服务器安装的RabbitMQ，在本地无法访问其管理界面，目前不知道怎么设置，以下方法无效：
>
>  ```shell
>  firewall-cmd --zone=public --add-port=15672/tcp --permanent 
>  ```
>
>  现在感受到docker真是好，依赖环境都打包好了，起码对练习学习来讲



因为在虚拟机192.168.130.129中直接安装的RabbitMQ,不知道为什么无法其中插件见  <a id="#m1">安装RabbitMQ管理插件失败</a>  ，错误如上所示。

故之后的练习都是在安装了RabbitMQ-Docker的虚拟机192.168.130.130 中进行练习。

访问：http://192.168.130.130:15672/

![](images/KuangStudy-RabbitMQ/1616961355951.png)

因为在创建容器时，我们创建了默认的账号和密码都是admin

```shell
[root@centos7 ~]# docker run -di --name myrabitt -e RABBITMQ_DEFAULT_USER=admin  -e RABBITMQ_DEFAULT_PASS=admin -p 15672:15672 -p 25672:25672 -p 61613:61613 -p 1883:1883 rabbitmq:management 
```

使用这个账号密码登录。

![1616961547743](images/KuangStudy-RabbitMQ/1616961547743.png)



# 快速入门案例-Simple简单模式

Docs:https://www.rabbitmq.com/getstarted.html

![1616965746131](images/KuangStudy-RabbitMQ/1616965746131.png)

![1616965890185](images/KuangStudy-RabbitMQ/1616965890185.png)

![1616965845833](images/KuangStudy-RabbitMQ/1616965845833.png)

![1616965917636](images/KuangStudy-RabbitMQ/1616965917636.png)

![1616965941040](images/KuangStudy-RabbitMQ/1616965941040.png)

![1616966010864](images/KuangStudy-RabbitMQ/1616966010864.png)





![1616966176121](images/KuangStudy-RabbitMQ/1616966176121.png)



![1616966387783](images/KuangStudy-RabbitMQ/1616966387783.png)



### 生产者

![1616966743339](images/KuangStudy-RabbitMQ/1616966743339.png)

![1616966693646](images/KuangStudy-RabbitMQ/1616966693646.png)



![1616966886085](images/KuangStudy-RabbitMQ/1616966886085.png)

![1616966919951](images/KuangStudy-RabbitMQ/1616966919951.png)

>问：非持久化会存盘吗？
>
>答：会存盘，但是会随着RabbitMQ服务的重启而消失
>
>$ systemctl restart rabbitmq-server 



运行，在管理界面中查看

**连接**

![1616967054494](images/KuangStudy-RabbitMQ/1616967054494.png)

![1616967259706](images/KuangStudy-RabbitMQ/1616967259706.png)

通道：

![1616967118039](images/KuangStudy-RabbitMQ/1616967118039.png)



**Exchange**：

本示例指明使用那个Exchange，故使用默认的。



**Queues:**

队列名为：

![1616967291990](images/KuangStudy-RabbitMQ/1616967291990.png)

![1616967215526](images/KuangStudy-RabbitMQ/1616967215526.png)



注意现在打了断点，还没发送消息，**Read:NaN**说明还没有消息；



发送消息：

![1616967385169](images/KuangStudy-RabbitMQ/1616967385169.png)

发送成功后**Read:NaN**变成了**Read:1**

![1616967484360](images/KuangStudy-RabbitMQ/1616967484360.png)





### 消费者

![1616967736705](images/KuangStudy-RabbitMQ/1616967736705.png)

![1616967901929](images/KuangStudy-RabbitMQ/1616967901929.png)

下面的关闭代码跟生产者的代码一样

运行消费者代码：

![1616967963144](images/KuangStudy-RabbitMQ/1616967963144.png)



收到了消息，于是：

![1616967981099](images/KuangStudy-RabbitMQ/1616967981099.png)

**`Queue1`队列的`Ready=0`**



>注意:
>
>此时消费者端因如下代码
>
>![1616968199019](images/KuangStudy-RabbitMQ/1616968199019.png)
>
>还等带用户输入，故此时，消费者还没被释放，即连接还没断开

由于生成者在发送消息的时，队列被设置为**非持久化队列**

![1616968067281](images/KuangStudy-RabbitMQ/1616968067281.png)



然后，再输入任意键，这时消费者自动被释放，即连接断开，故**非持久化队列**`Queue1`被自动删除了

![1616968380572](images/KuangStudy-RabbitMQ/1616968380572.png)







# AMQP讲解

![1616969037457](images/KuangStudy-RabbitMQ/1616969037457.png)

![1616969064490](images/KuangStudy-RabbitMQ/1616969064490.png)

![1616969175873](images/KuangStudy-RabbitMQ/1616969175873.png)





# RabbitMQ的组件和架构



![1616964429012](images/KuangStudy-RabbitMQ/1616964429012.png)

![1616964102558](images/KuangStudy-RabbitMQ/1616964102558.png)

![1616964499206](images/KuangStudy-RabbitMQ/1616964499206.png)

Routing key相当于where 条件一样，根据这个条件进行消息的分发



![1616964946403](images/KuangStudy-RabbitMQ/1616964946403.png)

![1616965017230](images/KuangStudy-RabbitMQ/1616965017230.png)

![1616965167134](images/KuangStudy-RabbitMQ/1616965167134.png)

![1616965277437](images/KuangStudy-RabbitMQ/1616965277437.png)

![1616965297310](images/KuangStudy-RabbitMQ/1616965297310.png)