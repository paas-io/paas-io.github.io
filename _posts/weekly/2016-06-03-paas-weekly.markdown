---
layout: post
title:  "【20160603】一周业内技术动态"
date:   2016-06-03 16:38:20
categories: 周刊
tags: 周刊
---
# 20160603期

### 云计算及容器技术

#### 1、DaoliNet宣布开源 为Docker容器量身打造动态敏捷的可编程网络
 
> 要点：DaoliNet + Docker = 轻灵的CPU + 轻灵的网络 + 各司其职的控制 = 适合于PaaS的网络。本文详细介绍DaoliNet是什么，相关技术是如何抓住Docker容器的轻灵性，让网络控制器介入容器生命周期管理，提供满足应用策略的，支撑业务逻辑的PaaS能力属性服务，而非停留在提供IaaS层面资源属性服务。

原文链接：[点击进入][post-link-1.1]

[post-link-1.1]: https://mp.weixin.qq.com/s?__biz=MjM5MjAwODM4MA==&mid=2650686547&idx=1&sn=9db9bd3fe20de4235bc446274c33c837&scene=1&srcid=06039XXJ7fu7C93vxcvZHw9T&key=f5c31ae61525f82e4222fae74a574ce50fa15a66ea884fec664c2bb6525d8a91b7f76db0f5e71a6368682a7baf954e88&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw
 
#### 2、使用Docker Swarm创建Overlay Network
 
> 要点：这篇文章中，我们使用Docker Swarm设置允许主机之间的容器互相访问的网络。实际上，Swarm集群允许我们使用本地Docker单一的主机网络，也允许我们创建依赖VXLAN的Overlay Network。在Overlay中启动的容器可以和容器之外的应用互相通信。这篇文章介绍了使用Docker Swarm如何创建、使用、测试一个Overlay Network。

原文链接：[点击进入][post-link-1.2]

[post-link-1.2]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690195&idx=1&sn=dff679885898490b52d2195091560321&scene=1&srcid=0603rUc2crpFxtiVcEQxMArA&key=f5c31ae61525f82e1046f4baa6459efedfa1beefd25bc06c0dce25a5d36fda7fbb7ce6e7e190cc5d294d9c6630a1cac7&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw
 
#### 3、虚拟化老兵介绍虚拟化技术
 
> 要点：本文从虚拟化的主流技术介绍，前沿技术介绍，Docker技术介绍，MixSAN技术介绍四个方面全面介绍虚拟化技术，内容覆盖虚拟化、容器、存储、网络等大类。

原文链接：[点击进入][post-link-1.3]

[post-link-1.3]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690264&idx=1&sn=299fc0737b6c427d511d015384ca968e&scene=1&srcid=0603Rio5DHGjzyqTWKvsqPeu&key=f5c31ae61525f82e173f7060cb03cc16169d1d453aff37ef15d076886fffe5f0f77d5d1173b477905b60b5e2bf9306ef&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw
 
### PaaS技术落地实践
 
#### 1、 站在运维的角度讲如何打造一个Docker-Mesos平台
 
> 要点：大多数同学都是在技术角度来看待Docker平台，但是对于如何快速、良好、正确、健康的使用Docker/SaaS技术、运维维护却少有人提，到底搭建一个生产级的Docker平台需要结合哪些情况综合考虑、规划？本文将从运维的角度出发，结合真实的案例来讲述如何快速打造一个Docker平台。
 
原文链接：[点击进入][post-link-2.1]

[post-link-2.1]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690283&idx=1&sn=97fa2b30b760cdb30fd8fa0321f650a6&scene=1&srcid=0603L2oETTEPSsee716tk4NF&key=f5c31ae61525f82e0c434a5c7199c47d0b77ced2ae551a639dd891d6fdb11f5f2973ee2bab3cb433e28d46fcfe66583b&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw

### 业内动态
 
#### 1、 DevOps年度报告：Docker、Puppet和Chef，谁更受欢迎？

> 要点：2016年1月，RightScale进行了年度云计算现状调查。此次调查就云计算架构的应用情况询问了大部分典型组织内的技术专家。RightScale对DevOps及DevOps工具（包括Docker）的使用情况也同时进行了调查，本文就是分析后给出的报告。
 
原文链接：[点击进入][post-link-3.1]

[post-link-3.1]: https://mp.weixin.qq.com/s?__biz=MzA4Nzg5Nzc5OA==&mid=2651660009&idx=1&sn=1382cd6e82d2c3e480de13b7013f0557&scene=1&srcid=0603YyEoi2pZiP90PFpzjbdj&key=f5c31ae61525f82e4e753868d1390ac20ed5e463cc7016123bbf13fedf82a1a83f809e1ba0dc977b46c16086628e79f9&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw
 
#### 2、Salesforce 28亿美元收购云商 Demandware

> 要点：北京时间1日晚讯 Salesforce.com Inc（CRM）周三宣布，将以28亿美元现金收购企业云商务公司Demandware（DWRE）。作为交易的一部分，Salesforce将对Demandware的流通股发出每股75美元的收购要约，该出价较Demandware周二收盘价溢价56%。
 
原文链接：[点击进入][post-link-3.2]

[post-link-3.2]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654676304&idx=5&sn=8eb1c9de26f4e02f5ee2d506f95968b8&scene=1&srcid=0603kVZaRjMWHWkeA0qLM2Mw&key=f5c31ae61525f82e05aaf90dfbfbef3a80380557507109302147282bfacdcd82b6f868658c05ed20120e43be887562d8&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw

#### 3、一张图看出AWS各产品使用率

> 要点：亚马逊网络服务（AWS）咨询公司2nd Watch本周发布了一项调查的结果，调查分析了100000个公共云实例，确定客户使用的30种最受欢迎的服务。

原文链接：[点击进入][post-link-3.3]

[post-link-3.3]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654676186&idx=1&sn=dcde3358303a9345408e329e729c95a3&scene=1&srcid=0603Z3pQEChSk3mqxIOJf3yi&key=f5c31ae61525f82eba94ed86043db356d72cd820f16dcb5315841385a5e72bf08c162be96cc1de1c862422130f98bb24&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw
 
### 大杂烩
 
#### 1、Twitter再开源！这回是分布式高性能日志复制服务
 
> 要点：继开源分布式流计算系统Heron之后，Twitter又开源了其分布式高性能日志复制服务。不得不说，Twitter真是开源界的良心。
 
原文链接：[点击进入][post-link-4.1]

[post-link-4.1]: https://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=2650992712&idx=1&sn=727ce15ad3651ce43a710a165ed2495a&scene=1&srcid=0603fWbhSq6XisjBlkBik5Xn&key=f5c31ae61525f82e7d9c46655a5ae561ff4b2ed140116f74733f603821d007bac6b4a900ee5f09fb1e4ca97f3c304600&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw
 
#### 2、微服务的两种模式：应用中心和任务中心
 
>要点：微服务来自于运行大规模分布式应用程序的挑战，处理不可变基础设施和大规模可编排的服务意味着需要在运维方面的投入。本文介绍了微服务两种模式下（根据同步/异步区别），不同的对照管理服务的原则和方式。
 
原文链接：[点击进入][post-link-4.2]

[post-link-4.2]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690219&idx=1&sn=bc57ba006635f58c5af3b6056c6efddb&scene=1&srcid=0603sz22VtdbAzhJuFI6xlnz&key=f5c31ae61525f82eb9af43eaafa0cb52a9f7f2e50120bebc8002873c3a1461ad4bcdda0bc98b2c9ae776667614f8e80e&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw

#### 3、 别总是去中心，我对分布式多中心架构的几点看法
 
> 要点：本文作者从事的是传统企业的架构改造工作，介绍了如何融合传统服务体系与微服务于一体，构造一个平衡的、安全的、易于扩展的、易于维护的、高效的企业内服务架构。
 
原文链接：[点击进入][post-link-4.3]

[post-link-4.3]: https://mp.weixin.qq.com/s?__biz=MzA5Nzc4OTA1Mw==&mid=2659597293&idx=1&sn=53efc97757fb888593fb6390a0c490b4&scene=1&srcid=0603xg66Z4D7ovJDVnPVXRZi&key=f5c31ae61525f82e7a963374311a77a7942965d32f54dd84b5f9060bc16490d541edad277d792f032a9411069895c104&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw
 
#### 4、BAT解密：聊聊技术发展的驱动力

> 要点：是什么推动了一个互联网企业的技术发展？本文从业务类和服务类的互联网产品创新模式触发，探讨了推动互联网技术发展的背后驱动力。对于我们来说，无论做内部的支持平台还是对外提供解决方案，文中提到的思路都是蛮有启发的。
 
原文链接：[点击进入part1][post-link-4.4.1] [点击进入part2][post-link-4.4.2]

[post-link-4.4.1]: https://mp.weixin.qq.com/s?__biz=MzA5Nzc4OTA1Mw==&mid=2659597279&idx=1&sn=dd9280bc0101098c21c493803deb8543&scene=1&srcid=0603BKXBKKEZLtTJeNe7w8C5&key=f5c31ae61525f82e883b3b87b9d14ee16524eb8d2d8b0d2dc84b7991fc087001254daad439c5d7f18fc3ec593e5a84d6&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw
[post-link-4.4.2]: https://mp.weixin.qq.com/s?__biz=MzA5Nzc4OTA1Mw==&mid=2659597334&idx=1&sn=870e786a34ecdb50053a2ed67182114f&scene=1&srcid=0603hO8yQJlKna1LN5tHNqLy&key=f5c31ae61525f82ee0175f9e6a93ad5cb48385d7fa420e799191a8ff59dcfa3656c94be24ea286444ecc82eaaceabd54&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw

#### 5、 谷歌云服务如何抗衡巨头？

> 要点：作为科技界的卓越女性，谷歌的云服务高级副总裁黛安·格林（Diane Greene）日前在TiEcon年会上与风投机构合伙人重点探讨了谷歌云服务策略，指出谷歌云服务将通过开源与亚马逊、微软抗衡
 
原文链接：[点击进入][post-link-4.5]

[post-link-4.5]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654676186&idx=2&sn=455f95ca90e44736e41a061b40acb0b5&scene=1&srcid=0603zR5FExrZAnOSFeocmxHA&key=f5c31ae61525f82ed23c85025c2cf3e4b136e29973bc36ae9e178089aa311c6f84e396e5054a7d37cc31dbdf15428cd8&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=owTkWwEG3LqSyp358ElCkwsEGObib4rBHxSqQ9vyBRhGmshRBMclggt5k%2FYQiPuw