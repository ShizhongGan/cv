---
layout: cv
title: Shizhong Gan
email:
  url: gan_shizhong@163.com
  text: gan_shizhong@163.com
homepage:
  url: https://shizhonggan.github.io/
  text: https://shizhonggan.github.io/
phone:
  url: 15822523657
  text: 15822523657
---

# **甘士忠**

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}


## Experience

### **爱立信（中国）通信有限公司** `2022.10 - `
_运维开发工程师_<br>
- 主要维护保障爱立信私有云运行稳定，包括物理集群、虚拟机、K8s集群、Ceph存储等;
- 配置、监控、维护物理集群，与IT运维部门处理硬件问题;
- 维护Permethus, grafana, OnCall，zabbix，netdata等监控工具，添加更新监控对象;
- 维护、更新针对物理集群批量化配置、以及CE、K8s等平台版本更新升级与补丁的自动化脚本;
- 跟踪相关工具的版本变化，引入新的开源工具、技术，参与如Netdata, K8s新版本的更新迭代;
- 写Ansible 脚本，Spinnaker pipeline, jenkins 处理各种自动化任务
- 基于各种平台工具的API进行二次开发，完成数据采集、分析和处理，以及自动化配置、调度等任务。
- 支持全球对爱立信私有云的使用，处理用户VM、K8s使用中存在的问题

#### [基于redfish API方式的物理机信息采集与批量化配置]()
- 针对HPE，DELL类型的机器，通过统一的Redfish API方式，完成自动化批量配置，并实现了对集群信息的快速统一处理，完成对物理机器的数据统计分析。

#### [采用OnCall集成多平台Zabbix、Permethus报警分类]()
- 完成OnCall的部署，并采用本地数据库避免数据在更新过程的丢失，解决了监控平台的历史消息堆积问题，
- 并采用分类算法对报警进行分类，提高了对重点类别日志的响应与处理速度
- 基于其API二次开发，解决一些消失时间的日志堆积问题。


### **北京光环新网科技股份有限公司** `2019.6 - 2022.10`

_云计算研发工程师_<br>

- 主要负责基于Opnstack架构的公司云平台的代码维护，解决系统漏扫存在的安全问题 
- 解决客户在云资源使用过程中的疑惑、解答云主机、网络配置、组网等问题，及时响应工信部对目标云主机的调查，包括：挖矿、网络攻击等问题
- 参与相关项目的部署实施，实现批量化文件配置、基础环境检查、私有云部署、日志监控工具部署等
- 基于django框架完成后端开发任务，主要包括：云平台公网IP信息检索功能、结合celery模块优化公司邮箱系统群发功能

#### [AWS云平台资源批量自动化取证]() 

- 针对AWS云平台违规、违法用户，协助司法、公安机关对指定云主机进行数据取证，基于AWS Boto3开发工具实现本地对云资源的远程操作，采用paramiko模块实现对云主机的远程控制，并基于PyQT5开发了一款自动化批处理云数据软件，通过简单的配置即可实现对云数据一键化处理。完成软著。
- Environment：AWS boto3+paramiko+PyQT5
  
#### [苏州移动研发中心移动云贵州节点部署实施]() 

- 参加苏州移动研发中心移动云贵州节点建设，主要负责ceph对象存储部署、健康检查与处理，优化pg映射提高集群打分（10个集群，每个集群106-126台服务器，其中6台作为MON节点, 大约2000个OSD）；py脚本完成软负载均衡配置；云平台环境自动化检测；neutron网络测试等。

#### [分布式邮箱系统开发]() 

- 为缓解公司邮箱服务器压力、提高邮箱并发能力，避免服务器存储空间浪费。采用celery任务调度框架，Redis作为消息队列，MySQL作为数据库存储，基于django架构和SMTP协议完成新邮箱web客户端开发，最后采用docker部署在公司的云平台上，并添加多联系人文本识别、状态查询等功能，便于销售使用。
- Environment：分布式+celery+Redis+MySQL+Docker+Boostrap

## Education

### **天津工业大学** `2016.9 -2019.4`

- 信息与通信工程 工学硕士

### **南洋理工大学[交流]** `2017.7 - 2018.12`

```
NTU, Singapore
```

- _Research Assistant_  

### **天津商业大学** `2012.9 - 2016.6`

- 数学与应用数学 理学学士

## Publications

**甘士忠**, 肖志涛, 陈雷, 南瑞杰. **基于高阶非线性模型的多目标高光谱图像解混算法**.  _红外与激光工程_(EI). 2019.  [[PDF](http://www.irla.cn/cn/article/doi/10.3788/IRLA201948.1026002)]

陈雷,  **甘士忠**,  孙茜. **基于回溯优化的非线性高光谱图像解混**.  _红外与激光工程_. 2017.  [[PDF](http://www.irla.cn/article/app/id/3126/cn/article/doi/10.3788/IRLA201746.0638001)]

陈雷, **甘士忠**,张立毅,王光艳. **基于样条插值与人工蜂群优化的非线性盲源分离算法**. _通信学报_(EI). 2017. [[PDF](http://www.infocomm-journal.com/txxb/CN/10.11959/j.issn.1000-436x.2017147)]

---

## Honors & Awards

第十三届中国研究生电子设计竞赛 二等奖 `2018` <br>
第十二届中国研究生电子设计竞赛 二等奖 `2017` <br>
中国大学生数学建模竞赛 **国家二等奖**、天津市一等奖 `2014` <br>

## Skills

- 擅长语言：python， matlab<br>
- 熟悉Linux系统命令<br>
- 熟悉Ansible, spinnaker, jenkins, Elastic Stack, Zabbix, gitlab, docker等自动化工具的使用<br>
- 熟悉HPE，DELL机器，以及其API<br>
- -熟悉Kubernetes <br>
- 熟悉Openstack开发与部署，后端和前端的代码维护<br>

<!-- ### Footer

Last updated: May 2022 -->
