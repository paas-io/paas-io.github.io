---
layout: post
title:  "【20160715】一周业内技术动态"
date:   2016-07-15 16:38:20
categories: 周刊
tags: 周刊
---
# 20160715期

### 云计算及容器技术

#### 1、Docker网络和服务发现

> 要点: 本文是《Docker网络和服务发现》一书的全文，作者是Michael Hausenblas。本文介绍了Docker世界中的网络和服务发现的工作原理，并提供了一系列解决方案, 这是一篇非常全面的扫盲介绍，推荐阅读。

原文链接：[上篇][post-link-1.1.1]|[下篇][post-link-1.1.2]

[post-link-1.1.1]: https://mp.weixin.qq.com/s?__biz=MzIzNzA5NzM3Ng==&mid=2651856852&idx=1&sn=974b919c13d1b164c71adc964856e34e&scene=1&srcid=0714qQ4RlTcx6tHkr0ba0jrx&key=77421cf58af4a653899fd5f9b23e8cb5096cd3b70dc1d8e717729d1e1a94a19030b8a26313a1cdacc98415dcb6aea584&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u
[post-link-1.1.2]:https://mp.weixin.qq.com/s?__biz=MzIzNzA5NzM3Ng==&mid=2651856852&idx=2&sn=3e8724cb3cf32107f385fb3d195b64a6&scene=1&srcid=0714z7bWliVgDhqqsnlToNx3&key=77421cf58af4a653f9a64924e3139c1e5964f7fe530cea14ca9669398aebabe7369e41c33df0180ed45b9d51403f3432&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

#### 2、Docker 1.12实践：Docker Service、Stack与分布式应用捆绑包

> 要点: 本文介绍1.12的一些新特性实践，并介绍如何利用Docker Compose创建一套分布式应用捆绑包，同时将其作为Docker Stack在Docker Swarm Mode中进行部署

原文链接：[点击进入][post-link-1.2]

[post-link-1.2]: https://mp.weixin.qq.com/s?__biz=MzA3MDg4Nzc2NQ==&mid=2652133690&idx=1&sn=3796e41193168c09c21530d3d83515c1&scene=1&srcid=0714PvShBlSSWOlP3eDsvg0B&key=77421cf58af4a6538440dc7afd676d04eba08e60e617ad3fc1b863b119595f92dcd520ee187fd03eb24d972a4e729498&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

#### 3、Docker五种存储驱动原理及应用场景和性能测试对比

> 要点：没有单一的驱动适合所有的应用场景，要根据不同的场景选择合适的存储驱动，才能有效的提高Docker的性能。目前，Docker支持AUFS、Btrfs、Device mapper、OverlayFS、ZFS五种存储驱动，如何选择适合的存储驱动，要先了解存储驱动原理才能更好的判断，本文介绍一下Docker五种存储驱动原理详解及应用场景及IO性能测试的对比。

原文链接：[点击进入][post-link-1.3]

[post-link-1.3]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690685&idx=1&sn=9cbb9246f24f5d2b19aff8b92d9ea322&scene=1&srcid=0714Lg8z1EHg82pgpeP8r5M9&key=77421cf58af4a6532c91f27f77b7749a1ea58fa6f05ffe80287a57a65dd4320a586fc7635f1b01a4aefeb41e2735956d&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

#### 4、Docker Security Overview

> 要点：docker安全性概览的介绍。

原文链接：[点击进入][post-link-1.4]

[post-link-1.4]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690770&idx=2&sn=f65c1f60f6e1927f8e96ecedd78fef76&scene=1&srcid=0714REp8YmAGBjMa0leGwknd&key=77421cf58af4a65318a4042ce6f8b6630f448399806be2842b1ff96527744a5f70cad2748bc9971a5deef44393619d47&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

### PaaS技术落地实践

#### 1、用微服务创建可扩展API

> 要点：本文演示了如何基于kubernetes创建一个前端和后端服务，他们互相通讯并且独立扩展。

原文链接：[点击进入][post-link-2.1]

[post-link-2.1]: https://mp.weixin.qq.com/s?__biz=MzIzNzA5NzM3Ng==&mid=2651856855&idx=1&sn=c0f25fdc9944344b4bf023ffe45cb1c8&scene=1&srcid=07140x7snxia1I7fPVJ93CZ6&key=77421cf58af4a6530cd02bfb6c36fb24718feb4b08a5b94e86c4e45f1ddb339a2f85b50be29c0a52e33bfa458545426b&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

#### 2、微服务容器化的挑战和解决之道

> 要点：微服务相较传统服务架构具有很多优势，但同时也带给devops很多挑战。本文从面向微服务的容器网络和存储实现架构讨论、微服务横向扩展、容器化下安全架构考虑、日志聚合设计、镜像服务等方面介绍了解决方案。

原文链接：[点击进入][post-link-2.2]

[post-link-2.2]: https://mp.weixin.qq.com/s?__biz=MzA3NzUwMDg1Mg==&mid=2651291730&idx=1&sn=7fffdcec0bd34f088584a67d1e9aa744&scene=1&srcid=0714jG5VX9wzextk32K2N7LV&key=77421cf58af4a6537028009cacbc060c243b8f984547df45b9dba109f9ba2df1e0884d609487064335f69e2b631b1d1f&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

#### 3、新浪公有云Docker编排实践

> 要点：本文介绍了微博DCP系统——基于Docker容器混合云架构的应用实践，主要分为微博业务背景介绍、业界趋势及DCP系统架构、弹性调度、具体实践踩坑等部分。

原文链接：[点击进入][post-link-2.3]

[post-link-2.3]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690770&idx=1&sn=39fcdd5c9d810f979e7c362ee57292d8&scene=1&srcid=0714HVJHEGBIDuKWybHotTsT&key=77421cf58af4a6530b4b4452170b5ab929768077cca0453c64808e2f4a445d2b0e20250c61d86b944e8eff760102de4d&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

### 业内动态

#### 1、容器集群管理技术对比调研报告

> 要点：当前，容器集群已成为容器产业化的事实管理方式，呈现出“百花争鸣”的竞争态势，本文将考虑资源管理和应用管控两个方面，并从生态角度进行简单讨论，对已有容器集群管理技术进行初步分析，可为企业容器集群技术选择提供依据。

原文链接：[点击进入][post-link-3.1]

[post-link-3.1]: https://mp.weixin.qq.com/s?__biz=MzIzNzA5NzM3Ng==&mid=2651856867&idx=1&sn=4fd872d36080f8a59fcace06a6e53012&scene=1&srcid=0714j8jetrqiAJGU5gZzPsNO&key=77421cf58af4a6531dc94caa7f93a5749f0736851b5683ce86e7291e2f7b291df8140cd5aa7b36f9ea4f88da9dd96149&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

#### 2、微软聘请谷歌的首席Kubernetes工程师，加强Azure中对容器编排的支持

> 要点：微软近日聘请了布伦丹·伯恩斯（Brendan Burns），谷歌的这名高级工程师在过去几年里，领导这项工作：为Docker容器开发Kubernetes开源编排技术

原文链接：[点击进入][post-link-3.2]

[post-link-3.2]: https://mp.weixin.qq.com/s?__biz=MjM5MzM3NjM4MA==&mid=2654677108&idx=3&sn=721b124d6b9e19448672f8bf5593183c&scene=1&srcid=0714juTUemWSlkJYRl8ckmf2&key=77421cf58af4a6531a82b720acc3de840ec65dc88a12b77b73e659e7296ce3245faa4950ef37d196e050260d6547e6fd&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

#### 3、容器趋势：计划，编排和CI——来自Bitnami的数据集

> 要点：Bitnami通过他们对整个用户群的用户调研来收集数据，方式是给Bitnami发送了超过850000封邮件，获得了5000多份答案，并从中得出这份调查结果。数据集涵盖了包括容器使用、容器计划的领域，使用容器的编排工具，CI工具和数据库选项，本文会重点关注跟容器和CI有关的数据。

原文链接：[点击进入][post-link-3.3]

[post-link-3.3]: https://mp.weixin.qq.com/s?__biz=MzIzMzExNDQ3MA==&mid=2650091847&idx=1&sn=6da050e1516566485879670ef81f8992&scene=1&srcid=0714YT7dmkfYPXAbrp10cCZz&key=77421cf58af4a6532e065045458832f45af4ea06df2d75c8dc327d29845da81a2ea595626fa469c11648b01e41cbba99&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

### 大杂烩

#### 1、50篇经典珍藏 | Docker、Mesos、微服务、云原生技术干货

> 要点：一篇完整的技术干货整理，按照Mesos、Docker和微服务的标签进行分类。

原文链接：[点击进入][post-link-4.1]

[post-link-4.1]: https://mp.weixin.qq.com/s?__biz=MzA3MDg4Nzc2NQ==&mid=2652133694&idx=1&sn=60914fdd81c09359f81281e590f23a83&scene=1&srcid=0714ihuutvCIefyRaGWoHI16&key=77421cf58af4a6533ffe88e6365360bceabe5d221fdca40c635645c492a998bccf83d870460587a4312b5e58a204b585&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

#### 2、容器简史：从20世纪70年代的chroot到2016的Docker

> 要点：在Docker开启容器大门之前虚拟化容器的历史。请走进我的时光机器，借助Wikipedia以及其他资源，让我们回到1979年，容器的概念被首次提出。

原文链接：[点击进入][post-link-4.2]

[post-link-4.2]: https://mp.weixin.qq.com/s?__biz=MzA5OTAyNzQ2OA==&mid=2649690750&idx=1&sn=8419ad06ad02a95f855ccfcb20bf150d&scene=1&srcid=0714L16EyhJcSGsE9tOZU4Fi&key=77421cf58af4a653dcdb2f2b72b231647aafefc0bebdd1dc810246606db0a1b7b6f2ba261adda6c815c53268abe701af&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u

#### 3、不懂点CAP理论，你好意思说你是做分布式的吗？

> 要点：CAP理论，被戏称为[帽子理论]。CAP理论由Eric Brewer在ACM研讨会上提出，而后CAP被奉为分布式领域的重要理论。

原文链接：[点击进入][post-link-4.3]

[post-link-4.3]: https://mp.weixin.qq.com/s?__biz=MzA4Nzg5Nzc5OA==&mid=2651660931&idx=1&sn=93cccfdcc5a474e92ffd673e7cd115ce&scene=1&srcid=0715wnBHuMkPaZlQJvVflgIp&key=77421cf58af4a653cadf93ddaf2eafb66842c8c212fe0044cd5e6f095bf92886009daee5bb0d0f53805d268333120efa&ascene=0&uin=MTM4MDQwNjQyMA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=qEhSKTTjdDNCLCSbfN9wgsYFyr%2BfITvLJg1wyWuV8r2lnKi%2F%2BCjZTG%2B4hYUSUn4u