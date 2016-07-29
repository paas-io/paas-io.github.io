---
layout: post
title:  "【20160729】一周业内技术动态"
date:   2016-07-29 16:38:20
categories: 周刊
tags: 周刊
---
# 20160729期

### 云计算及容器技术

#### 1、深入理解虚拟机、容器和Hyper技术

> 要点: 本文首先介绍了操作系统，然后引出容器技术以及虚拟机技术，最后介绍了Docker和Hyper技术。通过本文可以清楚地对三者有感性认识。

原文链接：[点击进入][post-link-1.1]

[post-link-1.1]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690943&idx=1&sn=9f994c4dadcef9b256b8634d563ce795&scene=1&srcid=0729h3Q17pu9CwBf8aAhPrhw&key=8dcebf9e179c9f3a6bb9b79fbe468b3211f0fc3a7194edc317fd01fe958e9c7e2e20e64226f6cf25293664e6d25d1074&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

#### 2、品品Unikernel与Container容器技术

> 要点: 本文探讨了unikernel和container技术的比较，不同场景下体现的不同优势。

原文链接：[点击进入][post-link-1.2]

推荐阅读：[Unikernels带来的安全问题比它能解决的多][post-link-1.2.1]

[post-link-1.2]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690896&idx=1&sn=a5fb02f093251ca62b03b2d03b2ede84&scene=1&srcid=0729rNpivZy4WXbHnh1OoSyW&key=8dcebf9e179c9f3a7177afac1a524b7444e28c318ffd1e62b9625f351b868a834939c878d1c7f9c92b470abadea5a569&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o
[post-link-1.2.1]: https://mp.weixin.qq.com/s?__biz=MzIzNzA5NzM3Ng==&mid=2651856901&idx=1&sn=1989f57bec41163deb1e52ec7f722c04&scene=1&srcid=0729PgkEthaaKHiR3ri8TL5R&key=8dcebf9e179c9f3a525a628d10a1bfad0d3c7b742f59bbec598ab3d17f371a8d4076c3fbbad84c448dce30bcc0c0e6c9&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

#### 3、浅谈Docker安全合规建设

> 要点：容器的安全性一直被拿来跟虚拟机等方面进行比较，虽然我们需要对容器的安全性高度关注，但只要使用得当，完全可以成为一种不低于使用虚拟机或者裸机的安全、高效生产系统。

原文链接：[点击进入][post-link-1.3]

[post-link-1.3]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690923&idx=1&sn=3741c618f186058bae628cc4bb669bb3&scene=1&srcid=0729HGdxA5vxdS0cRnfpHpFw&key=8dcebf9e179c9f3a7fb2030ba20e24bef057eaff84e3423a4fc77c4de0dc9fdbbf2aaec41588d1f0b83cc5b2cdb90630&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

#### 4、Swarm、SwarmKit、Swarm mode 对比

> 要点：Docker1.12的一个重大特性是提供了swarm mode，Docker1.12发布前几周，docker还开源了swarmkit，一个用于编排分布式系统的项目。这三个项目让人颇为困惑，这篇博客中一起看下他们的相似之处以及区别。 

原文链接：[点击进入][post-link-1.4]

[post-link-1.4]: https://mp.weixin.qq.com/s?__biz=MzIzNzA5NzM3Ng==&mid=2651856907&idx=1&sn=53237bf73471ee5a8644cc16965ecd25&scene=1&srcid=0729JFDNNrl8jYxHsxjahcjT&key=8dcebf9e179c9f3af71e6d0f6bcb7c71948c5a56af54f994b81e7f9eb3ed0ee845ec767e91e5cd39401f3bdfd6050514&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

### PaaS技术落地实践

#### 1、爱奇艺基于Docker的App Engine实践

> 要点：基于业务的背景和解决问题的角度出发，爱奇艺基于docker实现了QAE系统。本文详细的剖析QAE平台的架构，各个功能模块的设计与实现，以及未来的展望。

原文链接：[点击进入][post-link-2.1]

[post-link-2.1]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690916&idx=1&sn=bd2bd3ebc6205505c52e5bd0cc2eb970&scene=1&srcid=0729vFb1BovAqHuRzOOViogE&key=8dcebf9e179c9f3a30f22b5f4574a23b08fba1682f4270cd6a8f095aef4ca0621769d92e662c560d7628b6c5a31cad16&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

#### 2、Docker化高可用redis集群

> 要点：本文所做的实践目标是希望搭建一个redis集群镜像，把原先散落各处的redis服务器统一管理起来，并且保障高可用和故障自动迁移。

原文链接：[点击进入][post-link-2.2]

[post-link-2.2]: https://mp.weixin.qq.com/s?__biz=MzI0NTE4NjA0OQ==&mid=2658351573&idx=2&sn=fb194491852b84b793233b2bebc456dc&scene=1&srcid=0729wrQAkebwDxyVlk5oD7d8&key=8dcebf9e179c9f3a75181870a08a12f68728bfeb94d6ae1518f5bcf61041f833fe2f72b63f991bbd42202ddffb13f763&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

#### 3、云时代数据库的核心特点

> 要点：从目前已有的SQL数据库实现方案来看，NewSQL应该是最贴近于云数据库理念的实现。NewSQL本身具有SQL、ACID和Scale的能力，天然就具备了云数据库的一些特点。但是，从NewSQL到云数据库，依然有很多需要挑战的难题，比如多租户、性能等。

原文链接：[点击进入][post-link-2.3]

[post-link-2.3]: https://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=2650993474&idx=3&sn=1059d260d771bdf08b263202107c35e4&scene=1&srcid=0729JP8RMdgztPDKt5yqtOPb&key=8dcebf9e179c9f3aa488b859e0ca0411353f2d011fa775db555a708db6115ec0284c2214abe1e483a2b79e770a58022b&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

### 业内动态

#### 1、庆贺Apache Mesos发布1.0版本：全球最佳集群管理方案更上一层楼

> 要点：经过几年以来为全球多种最具创新性与需求性的应用提供支持，Apache Mesos如今终于迎来了1.0版本。毫无疑问，Mesos 1.0版本所带来的一系列重要新功能一定会让该项目变得更加强大且更具吸引力。本文带你了解新版本的诸多亮点。

原文链接：[点击进入][post-link-3.1]

推荐阅读：[数人云总架构师解读Mesos1.0.0][post-link-3.1.1]

[post-link-3.1]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690948&idx=1&sn=f3f5c828a3ac975c26f9fb5eff98943f&scene=1&srcid=0729nGUNloosiiZLjvGMHQk6&key=8dcebf9e179c9f3a711d2957574e03797f2bff80d88a7309a3fb7cf5bc5562a14929358af2f05e8cb187801e7b249433&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o
[post-link-3.1.1]:https://mp.weixin.qq.com/s?__biz=MzA3MDg4Nzc2NQ==&mid=2652133911&idx=1&sn=2f6a56a1679f2de2914fd81b33a85891&scene=1&srcid=0729cvMKL11q9nGYqFwQzfWT&key=8dcebf9e179c9f3aa131a53784fc2929daa96a702dfa5fa6d05d622198af86b2d5418fbcfa3eded511f454f154b0fc4c&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

#### 2、Gartner放言：到2020年，向云转变带来1万亿美元的开支

> 要点：知名研究机构Gartner本周声称，云计算将是“自数字化时代早期以来影响IT开支的最具颠覆性力量之一”。这种颠覆性到底有多强大？这家研究公司预测，在今后五年，受到向云计算转变直接或间接影响的开支将超过1万亿美元。

原文链接：[点击进入][post-link-3.2]

[post-link-3.2]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654677383&idx=2&sn=bb6d62f87d3a2946d7cf20bcd07532f9&scene=1&srcid=0729zfi3DYHjkryrZWiqiGCx&key=8dcebf9e179c9f3a86fa4d1b5290e10b710e971c1e6bcb46401547d8fa9db37ced5c7343f76096d1c97c30ba883cafa5&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

#### 3、Kubernetes成为世界500强数字化转型基础的原因（以及云基础设施管理平台一览表）

> 要点：随着最近越来越多的商业建立在Kubernetes的基础上，我们在这里花一点时间来将它和其它的编排工具进行优缺点对比，以及表述为什么我们坚信Kubernetes会成为容器编排工具之中耀眼的明珠。

原文链接：[点击进入][post-link-3.3]

[post-link-3.3]: https://mp.weixin.qq.com/s?__biz=MzIzMzExNDQ3MA==&mid=2650091927&idx=1&sn=99d71b2ad3d8bdf4df29fb16c4bb91f7&scene=1&srcid=072957IhFVQ1cfXozfLoMUBG&key=8dcebf9e179c9f3afb3f89871c45b4acd8c89c754520f21d0045fc51a244cfb71b93db7197ab3fa83fb66dda73f77894&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

#### 4、OpenStack的未来：Docker工作负载在Kubernetes上运行

> 要点：OpenStack势必会成为一种在Kubernetes上运行的Docker化的应用系统，将帮助谷歌实现开源混合云的计划。OpenStack发行商Mirantis将与谷歌和英特尔合作，重新包装这个云平台，以便通过借助Kubernetes管理的Docker容器加以部署。这是迄今为止OpenStack最重大的改动，会给谷歌计划中的开放标准和开源混合云带来重大的影响。它还表明了OpenStack的未来在多大程度上取决于容器。

原文链接：[点击进入][post-link-3.4]

[post-link-3.4]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654677440&idx=4&sn=dada3e95f0176e38d7ecd1e4192c43f9&scene=1&srcid=0729z2SUZ7uz5WxdWhnekQ2G&key=8dcebf9e179c9f3a7193d7c838ea8b1e268e6f1de7ed99f93c79a496c3d1ed7a3ab9ed54213327c1bf22d62ea6902038&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

### 大杂烩

#### 1、Kubernetes 1.3 的蚌中之珠

> 要点：Kubernetes的首次发布要追溯到两年前。这个项目的社区参与度和创新度都达到了惊人的地步，有个人参与合作，也有行业领导者（谷歌，红帽等等）来推进，并且给所有人带来生产级容器集群管理。这篇博客就是来探究Kubernetes1.3中的一些隐藏功能的。

原文链接：[点击进入][post-link-4.1]

[post-link-4.1]: https://mp.weixin.qq.com/s?__biz=MzIzMzExNDQ3MA==&mid=2650091942&idx=1&sn=61eeec2209b24dda8237d0882be6b3f1&scene=1&srcid=0729zzgzugQXmZbiRV8SuhAp&key=8dcebf9e179c9f3a845d73184b2bf1d109b787bf7642d0feb634de051a8c5eabb36f089c0b82a6f037ec24a38a9ddba3&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o

#### 2、深度漫谈数据系统架构——Lambda architecture

> 要点：Lambda架构的目标是设计出一个能满足实时大数据系统关键特性的架构，包括有：高容错、低延时和可扩展等。Lambda架构整合离线计算和实时计算，融合不可变性（Immunability），读写分离和复杂性隔离等一系列架构原则，可集成Hadoop，Kafka，Storm，Spark，Hbase等各类大数据组件。

原文链接：[点击进入][post-link-4.2]

[post-link-4.2]: https://mp.weixin.qq.com/s?__biz=MzI0NTE4NjA0OQ==&mid=2658351549&idx=1&sn=7b8cb92e6d70b9a16807a860bd91c47b&scene=1&srcid=0729Xr9YWNc3BWvF5y0enllr&key=8dcebf9e179c9f3afcfb796040cff3599463e027d030c0274ea1b43ac0002d7b3738789ec10b9d6c7ed94c328f1df86f&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=RW7CiXGpD6aweGrVAi0tvW0jkLNCRQOcxbMeIUJ3UrlZiyQyFYSebhM8%2Bwgyim1o
