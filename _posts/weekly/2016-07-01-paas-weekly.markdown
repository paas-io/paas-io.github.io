---
layout: post
title:  "【20160701】一周业内技术动态"
date:   2016-07-01 16:38:20
categories: 周刊
tags: 周刊
---
# 20160701期

### 云计算及容器技术

#### 1、浅谈Docker安全：技术、生态和最新的安全特性

> 要点: 本文从容器安全、镜像安全、安全生态（Twistlock、Aqua、clair等）等方面介绍当前docker安全相关话题。这是个很大的话题，本文只是简单提及，在生产环境的实践过程中，还需要细细考量。

原文链接：[点击进入][post-link-1.1.1]

推荐阅读：[这些关于Docker的安全性信息 你确定都了解吗？] [post-link-1.1.2]

[post-link-1.1.1]: https://mp.weixin.qq.com/s?__biz=MzI0NTE4NjA0OQ==&mid=2658351228&idx=1&sn=c11d59c2aae60d07284388781ac8db82&scene=1&srcid=0701f5zi45MLwEZNCstjMGEg&key=77421cf58af4a653f14745cd4e7f699a1e5be044f7a99c93d0ed0c675cba024f1396f015e914ea3390b3f403c74bc707&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

[post-link-1.1.2]: https://mp.weixin.qq.com/s?__biz=MzIzNzA5NzM3Ng==&mid=2651856822&idx=1&sn=76182f54ff2a7b72dbac122662707342&scene=1&srcid=0701G8kDukoUUeWdcxOybbl9&key=77421cf58af4a6533fed0870719101da105f6177bf984e698512dc66d4e7ac68136518d88fab517e7b9ff1ba192f8e06&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

#### 2、深度解读Weaveworks提供的容器集群网络和监控解决方案

> 要点: Weaveworks' Weave Net是容器化部署的网络解决方案，其Micro SDN方案具有高易用性、可用性和健壮性等特点。目前weave net还可以配合scope一起使用，可视化地展示目前集群的主机，容器，进程，以及他们之间的通信关系。

原文链接：[点击进入][post-link-1.2]

[post-link-1.2]: https://mp.weixin.qq.com/s?__biz=MzI0NTE4NjA0OQ==&mid=2658351204&idx=2&sn=de9e3d0b01417b095fe4b520b8309c0e&scene=1&srcid=0701aDEFDF3knkNjydwWtgz6&key=77421cf58af4a6532463e2c62208eee94953f034ebe14cf87a2ba9abbc23dd8085e5c723ad901f0f4cc17a64a65c12df&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

#### 3、在DockerCon 2016上宣布的内置编排（Orchestration）能力该如何玩呢？

> 要点：Docker官方将提供内置的编排（Orchestration）能力，从而能使得Docker Engine原生支持集群管理和服务生命周期管理。这个宣布对每个Docker开发者和厂商都有重要影响，也会左右现有Docker编排市场格局，Solomon把这称为自Docker发布以来最大的一次改变。本文主要从尝鲜角度使用构建docker编排系统（基于阿里云ecs），并验证了service和可用性等功能。

原文链接：[点击进入][post-link-1.3]

[post-link-1.3]:https://mp.weixin.qq.com/s?__biz=MzI0NTE4NjA0OQ==&mid=2658351079&idx=2&sn=59b34abf4fa792f71003d90a9f505646&scene=1&srcid=0701UI7ChTk9QwKTompEWa4F&key=77421cf58af4a653d2be3edd590f9feacdfd65c53514222b2bf70d7d8f5023640df790ffd3b21c60be3c4eb07781a482&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

#### 4、关于Docker 1.12中的最新功能，你需要了解这些

> 要点：新版本的发布对存储层面来说，最值得关注的自然是分卷驱动器支持能力的强化。这些变更不仅能够使我们对分卷进行标记，从而明确其属于本地抑或全局可访问对象，同时也能够提供与可用分卷相关的驱动器具体信息。

原文链接：[点击进入][post-link-1.4]

[post-link-1.4]: https://mp.weixin.qq.com/s?__biz=MzA3MDg4Nzc2NQ==&mid=2652133608&idx=1&sn=ea2bb95d345d1be628c7dc0b0dadd5cf&scene=1&srcid=0701Dh7FZN5m7lkyFqbv6ttw&key=77421cf58af4a6536299348b74a1883aec6a3d5646b31aec5e1899d6c21435fff4e758e18fafc594ca646a1c8718677e&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

### PaaS技术落地实践

#### 1、Kubernetes Master High Availability 高级实践

> 要点：本次分享论述的Master高可用方案主要基于[社区的高可用方案][http://kubernetes.io/docs/admin/high-availability/]的实践，并做了两方面的优化提升：第一，除了kubelet之外，Kubernetes所有组件容器化；第二，通过haproxy和keepalived构建Loadbalancer实现Master的高可用。 

原文链接：[点击进入][post-link-2.1]

[post-link-2.1]: https://mp.weixin.qq.com/s?__biz=MzIzMzExNDQ3MA==&mid=2650091772&idx=1&sn=727c986f602e4de6ad6a2cf66a45aa89&scene=1&srcid=0701xnkJmecwfCvDxpgl4XmM&key=77421cf58af4a653c9e81580fbf55dfd3ba4f98a1fcedd2a27351f997bde8eeb443db477e50caf29c937449d60615dbd&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

#### 2、公有云上的容器实践分享

> 要点：本文介绍了在公有云上的一次容器实践，包括如何选型，做了哪些技术验证，遇到了哪些问题，如何解决的。分享中还包括对于云平台本身高可靠、高性能、持续发布、服务注册发现等方面的设计方案，以及后续的发展愿景及规划，旨在与大家探讨一些关于Docker、Kubernetes、CoreOS、Hystrix等具体技术的实践经验。

原文链接：[点击进入][post-link-2.2]

[post-link-2.2]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690562&idx=1&sn=2143362dbec856c7a9ddcebf7b049022&scene=1&srcid=0701eIygaOFhTZzoYKG01BTH&key=77421cf58af4a6537dcf9fe68c226730eed8076512b8856e36e32a366d5b8f7d1769310a34cdb27104606092529d9278&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

#### 3、如何使用cAdvisor和Wavefront监控容器

> 要点：Docker 1.5中引入的Docker Stats API带来了从容器中输出资源指标（CPU和内存使用量）的能力。而且也有很多开源的项目致力于容器的监控，这其中就包括Google的cAdvisor。本文介绍了如何使用cAdvisor和Wavefront监控docker容器。

原文链接：[点击进入][post-link-2.3]

[post-link-2.3]:https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690495&idx=1&sn=55f98df939044fff52de3db8f07df098&scene=1&srcid=0701mTsvCNriCtiibSkwZ99V&key=77421cf58af4a6533f730ba9420634f471952ee6a6b62470b294d07b27ac5c8219a0a2af3f12534f7d6d24afd9b416ca&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

### 业内动态

#### 1、有消息称：微软试图斥资40亿美金收购Docker

> 要点：在上周于西雅图召开的DockerCon 2016大会上，称微软想斥资数十亿美金收购Docker的消息传得沸沸扬扬。据熟悉这两家公司的多位消息灵通人士表示，过去六个月有传闻称，微软准备斥资40亿美金，收购Docker这家拥有250名员工的容器技术初创公司。

原文链接：[点击进入][post-link-3.1]

[post-link-3.1]:https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654676844&idx=2&sn=5f9bda8e9ed232085a1ec45e709a939d&scene=1&srcid=0701rm7HePvEovTm0hvPEFlX&key=77421cf58af4a653fc1b80af954ccd82b1963eb3812e48fcb76c3281c3e50c684dfc6a51e57ff21ab7e70345c1d69dc6&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

#### 2、Docker推出软件市场（Docker Store）

> 要点：Docker公司近日在西雅图召开的开发者大会上宣布封闭测试的Docker商店（Docker Store），这个新市场面向可信赖的、通过验证的容器化软件。设立商店的初衷是，搭建一个自助式门户网站，以便Docker生态系统的合作伙伴可以通过Docker镜像发布和发行软件，并且让用户更容易部署这些应用程序，这将是docker商业化的最重要的一步。

原文链接：[点击进入][post-link-3.2]

[post-link-3.2]:https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654676796&idx=2&sn=a05ae21dbd857889b33a063a2b5281d5&scene=1&srcid=0701a4fR3J9AFrYHlgcfJomj&key=77421cf58af4a653e9d63377b5389b099d0db6dabe75be60efff62fdbb57a55e61cc19a5e7e2f827697f58f3279f19cd&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

#### 3、容器产品近一年的使用率增长了96%！

> 要点：由ClusterHQ委托DevOps.com进行的一项针对310份IT产品的调查显示，我们惊讶的发现，一年来容器技术应用于生产的比例增长了96%。

原文链接：[点击进入][post-link-3.3]

[post-link-3.3]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690524&idx=1&sn=441587964ca06ad62d77300eeda4b062&scene=1&srcid=0701TguxhWREGuEsNzfUU6KO&key=77421cf58af4a6536d974c12504266df43bd2737c523850ac8f6ceff892fa38d650345d6e7bd7a686ee4e169fd9e8c63&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

### 大杂烩

#### 1、Serverless架构综述

> 要点：本文从两种serverless类型BaaS、FaaS（Aws lambda）概念及例子切入介绍什么是serverless，然后着重解密了什么是FaaS及与PaaS的比较。

原文链接：[点击进入][post-link-4.1]

[post-link-4.1]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690504&idx=1&sn=1bb4850f4b5b35cebb2e2869ffc3aa35&scene=1&srcid=0701K9g8A5Je9iJbBN0u5A9D&key=77421cf58af4a653177862636d9d3cfa6928e213e06ce26fb9f7ee88e46e808b588c628837c1956f5316485cb0d2e3b7&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

#### 2、微信开源：生产级paxos类库PhxPaxos实现原理介绍

> 要点：微信重磅开源生产级Paxos类库PhxPaxos,本文将告诉你Paxos是什么，用来做什么，怎么使用它，如何工程化，如何做到生产级别，以及在工程上会遇到的问题与解决办法。

原文链接：[点击进入][post-link-4.2]

[post-link-4.2]:https://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=2650993105&idx=1&sn=d1566927744480b3b47f06bc9ee86f79&scene=1&srcid=0701Xdp1Sr6y1WwQK7BvvA3b&key=77421cf58af4a65393b4665df0ec05e2598aa146500aa92e2e35cee247b7cbae5748a3f2f0eed4c8f9dc346901ae93b5&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU

#### 3、OpenStack 的“钱”景

> 要点：本文将讨论OpenStack的商业模式，并以Mirantis的商业模式为例，与Red Hat的商业模式做对比。

原文链接：[点击进入][post-link-4.3]

[post-link-4.3]: https://mp.weixin.qq.com/s?__biz=MjM5MjAwODM4MA==&mid=2650686710&idx=1&sn=61ebb640b0cedeae162ac28687173655&scene=1&srcid=0701Jg3r9wEn7zlHaJqmiiNi&key=77421cf58af4a6533eada2226e622b806c8b53ab1d8d513278d0d0f2c2f37e4c9848f4c4f97bd37893700a2d662b28fa&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=gv8YAYuL07YoAhd598zA3gMSv7B05BKsFDunG3s6uQIz7Kd8xndG66PTBZUOc0bU