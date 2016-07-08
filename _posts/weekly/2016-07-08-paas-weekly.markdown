---
layout: post
title:  "【20160708】一周业内技术动态"
date:   2016-07-08 16:38:20
categories: 周刊
tags: 周刊
---
# 20160708期

### 云计算及容器技术

#### 1、新一代etcd：etcd3

> 要点: etcd 3.0正式发布，相较于2.0最大的优点在于使用了gRPC协议通信，对大规模使用效率上达到明显提升。同时本文介绍了数据模型、并发控制的改进对稳定性，扩展性的提升。

原文链接：[点击进入][post-link-1.1]

[post-link-1.1]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690569&idx=1&sn=7e806888a44ffedd45af3a1126df9886&scene=1&srcid=0708osGnqPm1SbqsJHZb9Evy&key=77421cf58af4a65394523938c341c823111c54dcb3478a20fe9c042c27f776be38411a70e192ea1c37e4f540af4dfa72&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 2、将Docker网络方案进行到底

> 要点: 本文简单介绍现有容器网络方案介绍，并重点讲解Calico的特性及技术点，作为引申和对比再介绍下Contiv的特性，最后给出对比测试结果。

原文链接：[点击进入][post-link-1.2]

[post-link-1.2]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690618&idx=1&sn=03472edbd3d3038c72064bfa352b2f30&scene=1&srcid=0708qI219XoClhESEp1GUnK6&key=77421cf58af4a65366210b0782343c7cec24c1ec98c0e3f4d11643445fd0686f739effec7b52fb4efe2a1029bded5d8d&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 3、Fluented，Kubernetes和谷歌云平台——处理日志流的解决方案

> 要点：kitchen-docker是chef公司出品的kitchen test的一个开源社区的插件。

原文链接：[点击进入][post-link-1.3]

[post-link-1.3]:https://mp.weixin.qq.com/s?__biz=MzI0NTE4NjA0OQ==&mid=2658351079&idx=2&sn=59b34abf4fa792f71003d90a9f505646&scene=1&srcid=0701UI7ChTk9QwKTompEWa4F&key=77421cf58af4a653d2be3edd590f9feacdfd65c53514222b2bf70d7d8f5023640df790ffd3b21c60be3c4eb07781a482&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

#### 4、使用Docker实现丝般顺滑的持续集成

> 要点：主要介绍了有容云AppSoar和AppHouse进行持续集成的方案，有一定参考价值。

原文链接：[点击进入][post-link-1.4]

[post-link-1.4]: https://mp.weixin.qq.com/s?__biz=MzA3NzUwMDg1Mg==&mid=2651291696&idx=1&sn=d2e27402dd0f191b663b1eaeebbf20a8&scene=1&srcid=07084rB1F4C9YoFGwyRBfjur&key=77421cf58af4a65397ec30d454c08bc81f09f19264cc5d901a4db62cfc6e87bac2b0455de70ea4de79d400211baa6793&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 5、Kubernetes 1.3: Bridging Cloud Native and Enterprise Workloads

> 要点：Kubernetes 1.3的产品亮点包括跨多个云的桥接服务能力（包括on-prem）、多个节点类型的支持、有状态的服务（比如键值存储和数据库）的集成支持，并大大简化了在笔记本电脑上的集群安装和部署。

原文链接：[点击进入][post-link-1.5]

[post-link-1.5]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690664&idx=1&sn=a601205beb0956585a3f03263b5dce7c&scene=1&srcid=0708E0eMQP1rTMX4x3NUfiez&key=77421cf58af4a653a53e62bbf08a07dde0b6309c7d71a8b17d547b53cfdbb36a5933ce7b030d2654ae9a1b6a06038fd3&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

### PaaS技术落地实践

#### 1、中国移动Kubernetes多集群统一管理实践

> 要点：中国移动以Docker、Kubernetes、Mesos、Ansible为核心支撑技术框架来实现了多集群统一管理，本文主要介绍在项目团队是如何应对资源指数级增长带来的挑战。

原文链接：[点击进入][post-link-2.1]

[post-link-2.1]: https://mp.weixin.qq.com/s?__biz=MzIzNzA5NzM3Ng==&mid=2651856849&idx=1&sn=ac41a6e673aa432d95481d3bf515954b&scene=0&key=77421cf58af4a65350fea5a180f456a70111b0fd5d81b9505ccf1bd737d4a4e01dd294826fde9d88467c9c2bf98284da&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 2、去哪儿网利用Mesos和Docker构建dev—beta环境

> 要点：本文介绍了去哪儿网在docker + mesos选型方案落地实践的经验。

原文链接：[点击进入][post-link-2.2]

[post-link-2.2]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690642&idx=1&sn=743b677c866a4596a881c5824d0388f4&scene=1&srcid=0708wmETQ3xEUigERu8LvyF1&key=77421cf58af4a653a1c72fff3e8d967dfe564bd9f01366247ae985fff7a95ed3c5fba612f2eca902f1769d125956f149&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 3、Travix是如何部署应用程序到Kubernetes上的

> 要点：在这篇文章中，我们来看Travix是如何部署应用程序到Kubernetes，以及如何将它作为一个公共服务的。

原文链接：[点击进入][post-link-2.3]

[post-link-2.3]: https://mp.weixin.qq.com/s?__biz=MzIzMzExNDQ3MA==&mid=2650091794&idx=1&sn=73875a60e1168d501787a3cfbc01dd9f&scene=1&srcid=0708dMqIGBzuRLnNSHJxMw74&key=77421cf58af4a653b74296ae7af223676aba2278408be2c113df55ce7c43d0bcac9aa26d18b7ecb5e4b68577f2560339&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 4、容器驱动的PaaS平台实现方案

> 要点：本文基于上海容器大会现场演讲内容，立足于实战跟大家分享了新一代PaaS平台构建中遇到的问题、当下主流PaaS平台解析、企业交付经验及心得体会等。文章较长，分为上、下两个部分。

原文链接：[上篇][post-link-2.4.1] | [下篇][post-link-2.4.2]

[post-link-2.4.1]:https://mp.weixin.qq.com/s?__biz=MzA3NzUwMDg1Mg==&mid=2651291673&idx=1&sn=7a301ccdc94a1292736fa46adaf05625&scene=1&srcid=070881M386kqc1yW5fQLgBEV&key=77421cf58af4a65330b0730751d1405ff81601fe782ae34cfc41eba2657f17b6a9971dbb468781c4ed7b0050e56ae3cc&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

[post-link-2.4.2]: https://mp.weixin.qq.com/s?__biz=MzA3NzUwMDg1Mg==&mid=2651291689&idx=1&sn=6e67eb0e34bda21231f8b935f202f105&scene=1&srcid=0708ARqclZYT0nFiXcvIpC5X&key=77421cf58af4a653316f3ddc4bcab2d151ef300ac626d6aaa58478427a3e7c073a470acea1898bbebb9d65de1c539b23&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 5、云端基于Docker的微服务与持续交付实践

> 要点：本文作者是阿里容器技术产品负责人，从Docker与微服务、云端生产环境部署、应用Docker化改造、持续交付流程实践等方面介绍了实践经验。大型互联网公司如何推进docker开源生态落地，本文可窥探一斑。

原文链接：[点击进入][post-link-2.5]

[post-link-2.5]: https://mp.weixin.qq.com/s?__biz=MzA4Nzg5Nzc5OA==&mid=2651660751&idx=1&sn=4c2e1ef539a4534ad4fd6fecff4c12de&scene=1&srcid=0708RYI41GEi9r9KoU6wxxUe&key=77421cf58af4a653de30ecc7a1e3e6be8bfb31ee49ee7b10fa4e65519c88dc983ea9f93b6d85d56d1b24e5e2e36f8ec8&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

### 业内动态

#### 1、OpenStack拥抱容器，有容云与Unitedstack有云展开合作

> 要点：近日，容器云服务提供商Yourun Cloud有容云与中国首家开源云服务公司Unitedstack有云达成战略合作协议，就OpenStack与容器技术的融合展开合作。

原文链接：[点击进入][post-link-3.1]

[post-link-3.1]: https://mp.weixin.qq.com/s?__biz=MzA3NzUwMDg1Mg==&mid=2651291699&idx=1&sn=64f064580c144402e21e106a40bae424&scene=1&srcid=0708ETikXVVoCyuEmVBZ2Fta&key=77421cf58af4a65345e5eb6af17d82a74d858f5a057ef22816ed42b8672f456489c767b475f2f33cb3e2a08069b638f0&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 2、容联云通讯完成7000万美元C轮融资，开始着眼海外市场

> 要点：企业通讯云服务商容联云通讯（以下简称“容联”)宣布完成7000万美元C轮融资，由红杉资本中国基金领投，多家投资机构参与，包括B轮投资方挚信资本以及新的国际战略投资方。此前，容联在2013年获得红杉资本400万美元A轮融资， 2015年获得挚信资本1500万美元B轮融资。

原文链接：[点击进入][post-link-3.2]

[post-link-3.2]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654676967&idx=3&sn=a70413b6326928f47e0a18fe9b20bfea&scene=1&srcid=0708MtMXQh9cELQTt3nyWNeG&key=77421cf58af4a653dc6faed34e10512454d1599482c71dcf95507226ff657f09dfea8cd424f6bb54aaf82fc2fe87fd64&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 3、阿里云北京机房内网故障 引发大面积服务异常

> 要点：阿里云官方公告：2016年7月6日上午10点22分华北2地域可用区A由于网络设备出现异常，导致部分产品访问受到影响；经过紧急处理，网络抖动问题已于11点16分恢复。

原文链接：[点击进入][post-link-3.3]

[post-link-3.3]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654676980&idx=1&sn=a645df36c6e723d72bc1fd199c8389b5&scene=1&srcid=0708sYy4gpqjaUArIqX3ys37&key=77421cf58af4a65325cdac7c0aa70e8162007ad48d5f4817b7ffab948e17ddd3de3efc0c4d2e9fc756ed744b763eb3e9&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

### 大杂烩

#### 1、趟过微服务那些坑后，我才明白这才是最重要的

> 要点：对于即将和已经开始实施微服务的团队，应该如何应对呢？本文结合项目的经验，从DevOps、服务构建、团队和文化四点入手进行了重点解读。

原文链接：[点击进入][post-link-4.1]

[post-link-4.1]: https://mp.weixin.qq.com/s?__biz=MzIzNzA5NzM3Ng==&mid=2651856844&idx=1&sn=a53124ffda976a385ef1da64240a3a81&scene=1&srcid=0708Qux3dsZZuVaVafDZUgvS&key=77421cf58af4a65319680d1ac76bc9cebe636050755cc35edd8722c6d3e0555d3b268f7f0a39433c1f7d757b855e03df&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 2、容器将完全颠覆虚拟化

> 要点：又是一篇谈论容器&&虚拟化的文章，观点可以参考。

原文链接：[点击进入][post-link-4.2]

[post-link-4.2]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654676967&idx=1&sn=ea36e8d9e14d497e77736980fea610ef&scene=1&srcid=0708PxUx8zTviGog876isAOT&key=77421cf58af4a653435c5d64f673289eeb10a5f5a6bf42a2f14088cc6ecaa0504999730b9f3a6c2ed76c0b6b52f50291&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 3、守护微服务安全，这里有两套方案

> 要点：每个人都在讨论微服务，每个人也都希望能够实现微服务架构，而微服务安全也日渐成为大家关注的重要问题。本文就从应用层面深入探讨了应对微服务安全挑战的方案，为微服务安全提供了新的思路。

原文链接：[点击进入][post-link-4.3]

[post-link-4.3]: https://mp.weixin.qq.com/s?__biz=MzA3MDg4Nzc2NQ==&mid=2652133666&idx=1&sn=6a160afc1fb8e84a1e0922d8640cc5da&scene=1&srcid=0708yi8OWbZrLWXGCp8fGHBj&key=77421cf58af4a65391513d5d41166e9a29d1a21a287cbed25fa414091946099d55036c7cc90a5cc517f8749bb40e6669&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

#### 4、从黑天鹅事件说起，谈云计算对于金融系统的意义

> 要点：本文作者为广发证券首席架构师梁启鸿，他讲结合自己的经历，分享他在在传统券商环境引入与推动容器化技术的思考历程，尝试陈述为什么云计算对证券业甚至整个金融业重要，而容器化技术的出现又带来何种契机

原文链接：[点击进入][post-link-4.4.1]

推荐阅读：[交易系统是命根子，为什么广发证券要将它容器化？][post-link-4.4.2]

[post-link-4.4.1]: https://mp.weixin.qq.com/s?__biz=MzA5Nzc4OTA1Mw==&mid=2659597630&idx=1&sn=20e9651a8efe7eaaffc92c43a2162809&scene=1&srcid=0708V3jaHm9DevXWxexrgGOP&key=77421cf58af4a65350b35051bd1c128dfb84652db4f4e77d12683a651c9a01b1c777d0551b1e49dbcb3a799e1f14956c&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE

[post-link-4.4.2]: https://mp.weixin.qq.com/s?__biz=MzA5Nzc4OTA1Mw==&mid=2659597643&idx=1&sn=9e98faf916cb049f308ff7fe81b1827c&scene=1&srcid=07081S19zlUice1fvjm1Sd26&key=77421cf58af4a6534f2d32784faa80336743119a1f5025c56003118e6e1cb5d4ad9432b8feb9352575d0ccbdb9882d06&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=lQLVyiXy0e%2FUpt%2FtBUNTBbFjJwn0T3xKDQnC7QnqI9fzm44rmLmOYNlGSmgfFxpE