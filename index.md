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

## Education

### **天津工业大学** `2016.9 -2019.4`

- 信息与通信工程 工学硕士

### **南洋理工大学[交流]** `2017.7 - 2018.12`

```
NTU, Singapore
```

- _Research Assistant_  

### **天津商业大学** `2012.9 - 2016.5`

- 数学与应用数学 理学学士

## Experience

### **北京光环新网科技股份有限公司** `2019.6 -`

_云计算研发工程师_<br>
主要负责基于Opnstack架构的公司云平台的代码维护、解决客户云资源使用过程中存在的问题；以及自动化运维、web开发、容器等技术的应用与研发。

#### [云平台公网IP检索web开发]() `2022.1-2022.2`

- 基于django开发的IP搜索web应用，基于pymysql实现多数据库处理，并通过docker完成部署。
- Environment：django+pymysql+mysql+docker
 
#### [集群状态与日志监控预警平台构建与应用]() `2021.6-2021.12`

- 采用ELK搜集日志信息，通过Zabbix监控预警，并通过Ansible完成集群化安装部署，针对集群、云主机、私有云等进行定制化日志监控。
- Environment：ELK+Zabbix+MySQL+Ansible

#### [AWS云平台资源批量自动化取证]() `2021.3 - 2021.6`

- 针对AWS云平台违规、违法用户，协助司法、公安机关对指定云主机进行数据取证，基于AWS Boto3开发工具实现本地对云资源的远程操作，采用paramiko模块实现对云主机的远程控制，并基于PyQT5开发了一款自动化批处理云数据软件，通过简单的配置即可实现对云数据一键化处理。完成软著。
- Environment：AWS boto3+paramiko+PyQT5
  
#### [苏州移动研发中心移动云贵州节点部署实施]() `2020.10 - 2020.12` 

- 参加苏州移动研发中心移动云贵州节点建设，主要负责ceph对象存储部署、健康检查与处理，优化pg映射提高集群打分（10个集群，每个集群106-126台服务器，其中6台作为MON节点, 大约2000个OSD）；py脚本完成软负载均衡配置；云平台环境自动化检测；neutron网络测试等。

#### [分布式邮箱系统开发]() `2020.1 - 2020.6` 

- 为缓解公司邮箱服务器压力、提高邮箱并发能力，避免服务器存储空间浪费。采用celery任务调度框架，Redis作为消息队列，MySQL作为数据库存储，基于django架构和SMTP协议完成新邮箱web客户端开发，最后采用docker部署在公司的云平台上，并添加多联系人文本识别、状态查询等功能，便于销售使用。
- Environment：分布式+celery+Redis+MySQL+Docker+Boostrap

#### [SDN架构、VR算法与应用开发等自研项目]()

- Open vSwitch、Mininet、OpenDayLight等安装部署，学习相关概念和命令操作，完成几个云主机间流表创建删除、通信模拟测试等。
- 根据VR眼镜3D视觉机制，利用opencv完成SIFT特征点匹配、RANSAC算法拼接、中心视图裁剪等算法，获得能够3D成像的左右眼视图。采用django开发算法的API接口，基于Flutter完成Android应用开发，实现手机拍摄照片和算法API调用，完成左右视图处理并在手机上显示，通过VR眼镜能够初步观赏到3D效果。
- Environment： SDN+opencv+Flutter+django

### **泰康集团** `2019.3 - 2019.4`
_NLP语音算法实习生_<br>
基于注意力机制的LSTM的保单审核评级分类算法demo 准确率94.5%

### **南洋理工大学计算机工程学院[交流]** `2017.7 - 2018.12`

_Research Assistant_<br>
- 海量数据处理，新加坡 Open-street-map 的百万条数据处理，企业的 GPS 海量数据处理，基于概率矩阵分解的缺失值插补；
- 在 Linux 系统与 Docker 容器平台下，实现基于隐马尔可夫模型的 GPS 数据与地图匹配
- 基于 LSTM 深度学习网络，完成交通流量预测分析；
- 基于多种机器学习分类算法完成交通工具特征识别。
- 基于 GAN 网络的数据生成、分布学习。

## Publications

**甘士忠**, 肖志涛, 陈雷, 南瑞杰. **基于高阶非线性模型的多目标高光谱图像解混算法**.  _红外与激光工程_(EI). 2019.  [[PDF](http://www.irla.cn/cn/article/doi/10.3788/IRLA201948.1026002)]

陈雷,  **甘士忠**,  孙茜. **基于回溯优化的非线性高光谱图像解混**.  _红外与激光工程_. 2017.  [[PDF](http://www.irla.cn/article/app/id/3126/cn/article/doi/10.3788/IRLA201746.0638001)]

陈雷, **甘士忠**,张立毅,王光艳. **基于样条插值与人工蜂群优化的非线性盲源分离算法**. _通信学报_(EI). 2017. [[PDF](http://www.infocomm-journal.com/txxb/CN/10.11959/j.issn.1000-436x.2017147)]

## Honors & Awards

第十三届中国研究生电子设计竞赛 二等奖 `2018` <br>
第十二届中国研究生电子设计竞赛 二等奖 `2017` <br>
中国大学生数学建模竞赛 **国家二等奖**、天津市一等奖 `2014` <br>

## Skills

- 擅长语言：python， matlab<br>
- 工作中主要使用Python：Django web开发；基于Paramiko模块的批量处理服务器资源；基于Celery分布式任务调度；Tensorflow, Pytorch深度学习库; Nampy, Pandas, Spicy等数值矩阵计算;基于Request, Selenium, beautifulsoup网络爬虫。<br>
- 熟悉Linux系统命令, 计算机网络<br>
- 掌握Ansible, Elastic Stack, Zabbix, gitlab, docker等自动化运维、日志监控等相关工具的使用和集群化部署<br>
- 熟悉Openstack开发与部署，后端和前端的代码维护<br>

## Service

IEEE ACCESS 邀请审稿人 `2019` <br>

<!-- ### Footer

Last updated: May 2022 -->
