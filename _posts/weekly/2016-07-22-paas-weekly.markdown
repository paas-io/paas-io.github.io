---
layout: post
title:  "【20160722】一周业内技术动态"
date:   2016-07-22 16:38:20
categories: 周刊
tags: 周刊
---
# 20160722期

### 云计算及容器技术

#### 1、Docker基础技术学习：Linux Namespace

> 要点: 本文通过亲手操作涉及Linux Namespace以及cgroup的相关系统调用，更好的理解这些底层技术。

原文链接：[点击进入][post-link-1.1]

[post-link-1.1]: https://mp.weixin.qq.com/s?__biz=MzI0NTE4NjA0OQ==&mid=2658351463&idx=2&sn=7406cde92080853f95d238b41a5b35fa&scene=1&srcid=0722O9PGUHDgiFH62WVUybcu&key=77421cf58af4a653476441f4da6846c6f4bc28fc28c59a691963634aca375791732e744548e5895a332f367a8b4bcfb2&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

#### 2、基于容器的分布式系统的设计模式

> 要点: 这篇论文描述了我们观察到的三种基于容器分布式系统的设计模型：单个容器模式，密切合作模式容器的单节点模式，以及分布式算法的多节点模式。跟面向对象编程的设计模式类似，这些模式包含了最佳实践，简化了开发，使系统更加可靠。

原文链接：[点击进入][post-link-1.2]

[post-link-1.2]: https://mp.weixin.qq.com/s?__biz=MzIzMzExNDQ3MA==&mid=2650091855&idx=1&sn=f2b521a2d9aa44141613e7d063226c5d&scene=1&srcid=07227rW59V52xYuNAwXdwieo&key=77421cf58af4a653414af3dbf391d37c2d85b41b2bd69e8b0bd9cbb1944664bcba2c0b2cd36a04d38b264c1556a03e10&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

#### 3、应用容器env化实战

> 要点：本文主要介绍应用容器在配置管理中遇到的问题。首先是介绍现有容器常用的配置文件加载方式，接下来重点介绍在自动化打包和发布遇到的问题和解决方法。

原文链接：[点击进入][post-link-1.3]

[post-link-1.3]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690855&idx=1&sn=ae9139466bc66e6bea61e0153b3a3fe0&scene=1&srcid=0722w8hRTpopKuIUcWyh10w1&key=77421cf58af4a6532bf595d1d75ad3cd79ad0c9e1f581d756a0ad2dc7af4a642757b52bc0767e7b53e0efafbd68f1c60&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

### PaaS技术落地实践

#### 1、从Docker到容器服务 ——Docker 云端实践之路

> 要点：本文是阿里巴巴在线技术峰会的分享，主要从Docker的编排技术，Docker在一个大规模生产环境中的使用开始切入，围绕Docker应用的深化，像谷歌，AWS，阿里云都推出了这样的容器服务，分享并分析了新的概念——Container as a Service，着重讲解了微服务支持和DevOps，并谈及了容器服务解决了哪些问题，最后介绍了Docker的最新发展趋势。

原文链接：[点击进入][post-link-2.1]

[post-link-2.1]: https://mp.weixin.qq.com/s?__biz=MzI0NTE4NjA0OQ==&mid=2658351522&idx=1&sn=dccfa6a06b1d0ec6011026a457528593&scene=1&srcid=0722fWZTjeZu1pEwSoDvGQOx&key=77421cf58af4a6530ab923d1b7b52af23eb7bdd45ce3e0bc6e34d45bd82759a5e573432031ce71daf0d9fc716528241e&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

#### 2、Docker1.12+Swarm构建动态微服务应用

> 要点：本文主要介绍了Docker Swarm动手构建小型微服务的过程，相比之前独立的swarm命令，集成后的docker使用上更为便捷，功能也日趋完善。

原文链接：[点击进入][post-link-2.2]

[post-link-2.2]: https://mp.weixin.qq.com/s?__biz=MzA3NzUwMDg1Mg==&mid=2651291730&idx=1&sn=7fffdcec0bd34f088584a67d1e9aa744&scene=1&srcid=0714jG5VX9wzextk32K2N7LV&key=77421cf58af4a6537028009cacbc060c243b8f984547df45b9dba109f9ba2df1e0884d609487064335f69e2b631b1d1f&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

#### 3、微服务实战：从架构到部署

> 要点：如今，微服务“Microservices”已经成为软件架构领域最流行的热词之一。市面上也有很多与微服务的基础知识以及优点相关的学习资料，但是关于如何在真实的企业场景中应用微服务的资料还是不多。在这篇文章里，计划涵盖微服务架构（MSA）的核心架构概念，以及如何在实践中使用这些架构理论。

原文链接：[点击进入][post-link-2.3]

[post-link-2.3]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690838&idx=1&sn=3311478250ddf0b487efb4b1ff0f9b4a&scene=1&srcid=07229CxROMi0DcDKzn6GUoZy&key=77421cf58af4a6535f036f9bbb471d60c6addf04bcb93e06c5071d70510bec2f170603dd0fc13b5b68affb1a6447c515&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

#### 4、腾讯Gaia平台的Docker应用实践

> 要点：本文介绍了腾讯在容器实践的gaia系统，一个基于Hadoop的YARN改造的Docker的调度系统。文章侧重点在gaia的docker部分的功能使用实践，包括docker热升级改造、网络模式扩展、Container数据存储等方面。

原文链接：[点击进入][post-link-2.4]

[post-link-2.4]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690887&idx=1&sn=46593cf8defbc39e728d0e19bb2f61bb&scene=1&srcid=0722pBCsm9bLWEhASzhe4AKn&key=77421cf58af4a653c6eb767f59e22ddbb1731405719d722ea3721719e67a875583ce39993f7678b34db3708a297ddc05&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

### 业内动态

#### 1、银监会十三五意见新出台，云平台走势再推高

> 要点：银监会于7月15日发布《中国银行业信息科技“十三五”发展规划监管指导意见（征求意见稿）》（下称“意见”），像是一滴滚水投入一锅辣油，硬是在IT圈内炸开了锅。银行业面向互联网场景的重要信息系统将全部迁移至云计算架构平台， 并联合开展面向银行业的公共云平台规划和建设，这意味着银行在后续布局中将有六成以上信息系统迁至云平台。

原文链接：[点击进入][post-link-3.1]

[post-link-3.1]: https://mp.weixin.qq.com/s?__biz=MzA3NzUwMDg1Mg==&mid=2651291735&idx=1&sn=151f14ef7af5176c474e18f27bb9912e&scene=1&srcid=0722tQQwMwKsAYnhayxSi2kR&key=77421cf58af4a653633c68b02c1f40189239421798e2a21a3b90eed5c250b2f44561ed2c91daa364b18d8c66474a2713&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

#### 2、为什么Kubernetes相较于谷歌云更可能威胁到Amazon

> 要点：Kubernetes社区正在建立一种竞争性基础设施设计思路，而这也许会给AWS带来巨大冲击。Redmonk公司分析师James Governor断言，作为容器管理项目的Kubernetes可能会立足于“除Amazon外的一切领域”并对AWS造成巨大威胁。

原文链接：[点击进入][post-link-3.2]

[post-link-3.2]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690818&idx=1&sn=57dab1f8588deb6234bde6f87f5e6dc0&scene=1&srcid=0722fQ5L385b9orSPhi9rkxY&key=77421cf58af4a65350d4199b81dfcf3fe357173fd2c992e3cc2b9d17aea3eff398efec3f18ab1569273a1c67b243fde3&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

#### 3、容器之后的下一波浪潮？Amazon CTO谈无服务器计算

> 要点：应用程序正整体从服务器当中剥离出来，只需代码即可实现运行，这意味着未来我们再也不用为服务器分神了。

原文链接：[点击进入][post-link-3.3]

[post-link-3.3]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654677136&idx=4&sn=886c91f4b405fbf42026270db5a5a9da&scene=1&srcid=0722I16SZ1rqsk6OhSE9HJHk&key=77421cf58af4a653006b4a27a05679fba45f8c9d059f70bad1cb77f74ff5c8365d9d82f7aac3bb8435c218a2bfaa0cec&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

#### 4、微软第四财季收益报告：净利润超31亿美元，云平台Azure营收翻番

> 要点：微软今日发布了2016年第四财政季度收益报告。这也是其宣布收购LinkedIn后公开的第一份财报。报告显示，公司的非GAAP（GAAP：美国通用会计准则）收入为226亿美元（GAAP收入为206亿美元），非GAAP每股利润为0.69美元，远远超出预期。与以往数季相同，该结果反映了微软在云业务领域的强劲增长。

原文链接：[点击进入][post-link-3.4]

[post-link-3.4]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654677185&idx=5&sn=aad0de4b24aff3318a863ca9b4d75d7b&scene=1&srcid=0722gHIZwR3cF6P4aVSk7HB4&key=77421cf58af4a65382aaaf6fbb0c1ac61f3347dd4d820927bacb719d6daa4baa3f71ae677cd01d892844e1c80d869643&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

### 大杂烩

#### 1、探秘阿里分布式任务调度服务SchedulerX

> 要点：SchedulerX是阿里巴巴集团中间件团队开发的一款高性能、分布式任务调度产品，在阿里内部有着广泛的使用，

原文链接：[点击进入][post-link-4.1]

[post-link-4.1]: https://mp.weixin.qq.com/s?__biz=MzI0NTE4NjA0OQ==&mid=2658351476&idx=1&sn=bc8b996a8a77b835a0e5320a44147eb7&scene=1&srcid=0722ypF8FhBDMpAST2rePezB&key=77421cf58af4a653a90b18d4b502405606cd0691b218429570517017dbf368606a74dd0fedca98718654d482d9f65573&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

#### 2、Mesos高可用解决方案剖析

> 要点：本文系作者根据自己对Mesos的高可用（High-Availability）设计方案的了解以及在Mesos社区贡献的经验，深度剖析了Mesos集群高可用的解决方案，以及对未来的展望。

原文链接：[点击进入][post-link-4.2]

[post-link-4.2]: https://mp.weixin.qq.com/s?__biz=MjM5MjAwODM4MA==&mid=2650686823&idx=1&sn=7f20850fa92f03fddcbc92a3971f17a5&scene=1&srcid=0722GZbC1XuKknTtNPt644bN&key=77421cf58af4a6533b45838616e07ecea71a0761668a305827c8fcbf5ee4d52ef1f4facc3a56cdc176f2823210a33908&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO

#### 3、Docker和容器云落地一年后的反思

> 要点：很多企业一开始受到Docker现象的鼓吹，认为Docker是万灵药，然而在自己尝试进行开发、生产使用时才发现 Docker 带来的不仅仅是“坑”，更多的是局限和对已有流程的颠覆。本文基于容器研发大规模生产平台的经验谈了现有Docker和谷歌容器环境的差别，并通过Caicloud的实际案例落地经验总结下Docker自身所带来的一些“谎言”和误区。

原文链接：[点击进入][post-link-4.3]

[post-link-4.3]: https://mp.weixin.qq.com/s?__biz=MzIzMzExNDQ3MA==&mid=2650091905&idx=1&sn=a3db1b6ff412db7946942710447f120a&scene=1&srcid=0722xFck7jmFUq3NIBF0ZtpG&key=77421cf58af4a653706a2193e154bacb7359a1356420f6abaadbf7ec5b031388e62d60391920596b4fe630730314b07b&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=Lt%2FbEsHxhkfYqTV%2B8QUgppKe6r%2Fj20JDflykVmqVdyv4Ifm4m628gX3ZygpWSsgO