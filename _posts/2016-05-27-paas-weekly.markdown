---
layout: post
title:  "【20160527】一周业内技术动态"
date:   2016-05-27 16:38:20
categories: 动态
tags: 动态
---
#20160527期

## 云计算及容器技术

####1、2016中国云计算技术大会精彩PPT干货分享
 
> 要点：本次大会议题内容涵盖Hadoop、OpenStack、Spark、Container、微服务等云计算大数据领域的核心技术和应用，并重点分享这些技术在国内外知名企业的落地案例。文章整理了一些讲师的精彩PPT，分享给大家，干货满满。

原文链接：[点击进入][post-link-1.1]

[post-link-1.1]: https://mp.weixin.qq.com/s?__biz=MjM5MjAwODM4MA==&mid=2650686539&idx=2&sn=f5f59887e621d3bb899dad9de6e2d551&scene=0&uin=MTM4MDQwNjQyMA%3D%3D&key=f5c31ae61525f82ee916856b9ca800392a9dbc0b2dfb2296dd9d5a61ed0c51644f4ae2a09f885c8bb7f95f08d4d894a7&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&lang=zh_CN&pass_ticket=e2On1792pUwV2mzPAN7ls2JqUb5nON8SxJJ5t2Q7VMCANrcC9h3tVYvd9FOAbTix
 
####2、Docker开源组件：HyperKit、VPNKit和DataKit介绍

> 要点：HyperKit：OSX上运行的轻量级虚拟化工具包；DataKit：现代化分布式组件框架；VPNKit：嵌入式虚拟网络库

原文链接：[点击进入][post-link-1.2]

[post-link-1.2]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690174&idx=1&sn=e3644d42d225762f8c816d4b5ab7bdcf&scene=0&uin=MjEwOTk0OTU0MA%3D%3D&key=f5c31ae61525f82e8f23cd222f0e273f9f7d8b42f21408e15fd6d85e2577a19fb74230a6f7d3cf655f2e3ba1a7a63c89&devicetype=iMac+MacBookPro11%2C1+OSX+OSX+10.10.1+build(14B25)&version=11000003&lang=zh_CN&pass_ticket=1x%2BjTmTo5jM8Gbe8IP4i7G%2BK5DOUs2WhLnI7jFKNDAP51irbHAdRY0fvokV3za3V

####3、Docker 1.11增强功能：直接在runC和Containerd上构建引擎
 
> 要点：最近Docker对整个平台发布了新的版本，Docker引擎升级至1.11版本，Swarm升级至1.2版本，Compose和Machine也分别升级至1.7和0.7版本。这次升级也开始支持Mac和Windows 10 Bete版的操作系统。底层的引擎经过大规模的重构保证了首个兼容Open Container Initiative（OCI）的运行时。更具体的说，现在用户可以直接在runC和containerd上构建引擎了。
 
原文链接：[点击进入][post-link-1.3]

[post-link-1.3]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690186&idx=1&sn=918289ba88c400b46258ae20704bb648&scene=0&uin=MTM4MDQwNjQyMA%3D%3D&key=f5c31ae61525f82e6585e94ed288fa2c4de225d8c86f0c8064f5cc886709168c79c9431a1401e173ad796eab0d77a4ec&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&lang=zh_CN&pass_ticket=e2On1792pUwV2mzPAN7ls2JqUb5nON8SxJJ5t2Q7VMCANrcC9h3tVYvd9FOAbTix
 
####4、Hypernetes：为Kubernetes带来安全性与多租户机制
 
> 要点：尽管很多开发者与安全专家乐于强调Linux容器所拥有的明确边界，但大多数用户仍然希望进一步提升其隔离性水平，特别是在多租户运行环境当中，这就会带来启动速度拖慢、资源损耗过多的问题，无法发挥云原生应用的诸多固有优势。本文将介绍HyperContainer这种基于虚拟化技术的容器实现，了解它如何契合于Kubernetes的设计理念并帮助用户直接为使用者提供一套虚拟化技术加持的容器——而不是将它们打包进虚拟机当中。

原文链接：[点击进入][post-link-1.4]

[post-link-1.4]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690191&idx=1&sn=c837bf641c8cf869ab570244fda52bdf&scene=0&uin=MTM4MDQwNjQyMA%3D%3D&key=f5c31ae61525f82e1bbe6db8e06d44349efe47fdc1bd00bdfe6c358788961c058059057bb180d2cb923cbb5c0aa0deb6&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&lang=zh_CN&pass_ticket=e2On1792pUwV2mzPAN7ls2JqUb5nON8SxJJ5t2Q7VMCANrcC9h3tVYvd9FOAbTix
 
## PaaS技术落地实践
 
####1、 数人云操作系统2.0发布 在企业实践中将Docker技术快速落地
 
> 要点：升级后的数人云操作系统具有应用管理，监控告警&日志查询，应用编排&应用目录，持续集成&镜像构建四大功能，实现了从私有代码管理到应用实例发布的全流程支持，全面支持Docker Compose编排，实现应用实例的灰度发布和自动扩缩。
 
原文链接：[点击进入][post-link-2.1]

[post-link-2.1]: https://mp.weixin.qq.com/s?__biz=MzA3MDg4Nzc2NQ==&mid=2652133385&idx=1&sn=aaeb052a1eca679eb09914eae423b6b3&scene=0&key=f5c31ae61525f82e977c13313e6776086fc0ae6e7b424fb243055575bd2af527765f8567a8b2a30cc428b7055bfb36a0&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=rUSsNQ%2BGFCIMG7JvW4hiOX%2BrqAuLzCnN4SHJD98AjIXeLIFwRCqVZEcVwfyDexhT

####2、 章文嵩：构建大型云计算平台分布式技术的实践
 
> 要点：本文是章博士在2014年ArchSummit深圳峰会上的演讲，内容主要分为五个部分：云计算的挑战与需求；ECS的分布式存储设计；SLB、RDS与OCS的设计；全链路监控与分析系统；未来工作展望

原文链接：[点击进入][post-link-2.2]

[post-link-2.2]: https://mp.weixin.qq.com/s?__biz=MzA5Nzc4OTA1Mw==&mid=2659597258&idx=1&sn=2073afe6896d86ee2af881f24937196b&scene=0&uin=MTM4MDQwNjQyMA%3D%3D&key=f5c31ae61525f82e1df0ff25abbb53a4b0be9f7c86a43369056cb00c8d61a4f0607a249dc797147c35b275d9d0e9cccc&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&lang=zh_CN&pass_ticket=e2On1792pUwV2mzPAN7ls2JqUb5nON8SxJJ5t2Q7VMCANrcC9h3tVYvd9FOAbTix
 
## 业内动态
 
####1、 云安全初创企业 vArmour 获4100万美元D轮融资

> 要点：旨在为企业跨云应用提供安全解决方案的云安全初创企业 vArmour 近日获得了 4100 万美元的 D 轮融资。vArmour 的安全解决方案完全是基于软件的，其安全服务利用了大数据分析技术，通过扫描进入网络的每一块数据来筛查疑似非法数据并对其进行标记，然后跟踪此数据及其流向，这种做法提高了识别可疑行为的几率，并且能有效应对内部出现的威胁事件。

原文链接：[点击进入][post-link-3.1]

[post-link-3.1]: http://36kr.com/p/5047364.html
 
####2、Open DC/OS大中华区官方发布会在京隆重召开

> 要点：DC/OS创建基于容器的完美管理平台，能够创建一个Single逻辑的数据中心，一个自我修复的基础架构，更是一个带监控和问题发现的完整运维系统。
 
原文链接：[点击进入][post-link-3.2]

[post-link-3.2]: http://geek.csdn.net/news/detail/75923
 
####3、《2016第一期公有云测评报告》，阿里云、腾讯云、UCloud位列前三

> 要点：听云又一重磅报告《2016第一期云评测报告》正式发布。此次报告是听云iDaaS中心利用自主研发的听云Network产品，从模拟真实用户的角度对不同云服务的使用效果进行对比，同时结合听云Server、听云Sys产品进行测试，实现端到端的评测效果，从首屏时间、总下载时间、首包时间、建连时间、Apdex等几个维度对国内13家云服务提供商进行测试评分，并在业界公开基于用户体验感知的公有云评测。
 
原文链接：[点击进入][post-link-3.3]

[post-link-3.3]: https://mp.weixin.qq.com/s?__biz=MjM5NDE0MjI4MA==&mid=2656298708&idx=1&sn=df9a775b0d167f9492766c9d0e35efa9&scene=0&uin=MTM4MDQwNjQyMA%3D%3D&key=f5c31ae61525f82e930a2d78ec94cbdc5519983b2da08b12418249507b8807d079c0db9a570768c52542a75fa4fa17c4&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&lang=zh_CN&pass_ticket=e2On1792pUwV2mzPAN7ls2JqUb5nON8SxJJ5t2Q7VMCANrcC9h3tVYvd9FOAbTix
 
 
## 大杂烩
 
####1、从 Salesforce 身上学到 SaaS 公司走向成功的 7 个必备条件
 
> 要点：本文作者是 Ron Pragides，他曾是 Salesforce 的资深经理，如今是  Bigcommerce 的工程技术人员。他给我们分享了 Salesforce 成功的原因，而且几乎行业内每一个人气爆棚的 SaaS 公司都脱离不开这 7 个必备条件
 
原文链接：[点击进入][post-link-4.1]

[post-link-4.1]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654676111&idx=4&sn=fe471c8d506304bfd76a6e983619953c&scene=0&key=f5c31ae61525f82eefd585bcfb4b4c63cf5737b6e1965c90e930757dd18680d9f27396a6d42e918c7853aabe70933bc8&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=rUSsNQ%2BGFCIMG7JvW4hiOX%2BrqAuLzCnN4SHJD98AjIXeLIFwRCqVZEcVwfyDexhT
 
####2、揭秘：亚马逊云计算内部基础设施
 
>要点：
 
原文链接：[点击进入][post-link-4.2]

[post-link-4.2]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654676111&idx=4&sn=fe471c8d506304bfd76a6e983619953c&scene=0&key=f5c31ae61525f82eefd585bcfb4b4c63cf5737b6e1965c90e930757dd18680d9f27396a6d42e918c7853aabe70933bc8&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=rUSsNQ%2BGFCIMG7JvW4hiOX%2BrqAuLzCnN4SHJD98AjIXeLIFwRCqVZEcVwfyDexhT
  
####3、 Docker暴露2375端口，引起安全漏洞
 
> 要点：为了实现集群管理，Docker提供了远程管理接口，***把2375端口作为非加密端口暴露出来***，一般是用在测试环境中。此时，没有任何加密和认证过程，只要知道Docker主机的IP，任何人都可以管理这台主机上的容器和镜像。
 
原文链接：[点击进入][post-link-4.3]

[post-link-4.3]: http://geek.csdn.net/news/detail/75236