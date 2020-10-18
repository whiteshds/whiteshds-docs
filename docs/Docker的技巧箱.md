# 很棒的Docker [![太棒了](https://camo.githubusercontent.com/13c4e50d88df7178ae1882a203ed57b641674f94/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f643733303566333864323966656437386661383536353265336136336531353464643865383832392f6d656469612f62616467652e737667)](https://github.com/sindresorhus/awesome) [![网络状态](Docker的技巧箱.assets/68747470733a2f2f6170692e6e65746c6966792e636f6d2f6170692f76312f6261646765732f38636138363731372d313162612d343664342d396430612d3730306438353237663133622f6465706c6f792d737461747573)](https://app.netlify.com/sites/awesome-docker/deploys)

> 精选的Docker资源和项目清单

如果您想贡献，请先阅读[CONTRIBUTING.md](https://github.com/veggiemonk/awesome-docker/blob/master/.github/CONTRIBUTING.md)。它包含许多技巧和指南，可帮助您使事情井井有条。只需单击[README.md](https://github.com/veggiemonk/awesome-docker/edit/master/README.md)即可提交[拉取请求](https://github.com/veggiemonk/awesome-docker/edit/master/README.md)。如果此列表不完整，您可以[为此做出贡献](https://github.com/veggiemonk/awesome-docker/edit/master/README.md)。这是一个很棒的视频教程，学习如何[在Github](https://egghead.io/lessons/javascript-identifying-how-to-contribute-to-an-open-source-project-on-github)上[做出贡献](https://egghead.io/lessons/javascript-identifying-how-to-contribute-to-an-open-source-project-on-github)

***您可以从[TWITTER](https://twitter.com/awesome_docker)查看更新\***

> **请**帮助组织这些资源，以便新手*容易找到*和*理解*。请参阅如何**[贡献](https://github.com/veggiemonk/awesome-docker/blob/master/.github/CONTRIBUTING.md)**技巧！

***如果您发现此处的链接不再（不再）合适，则可以通过提交[拉取请求](https://github.com/veggiemonk/awesome-docker/edit/master/README.md)来改进此文件，以解决此问题。谢谢！\***

此列表的创建者和维护者不会接受任何付款方式来接受任何贡献者所做的更改。该页面无论如何都不是正式的Docker产品。它是项目链接的列表，由志愿者维护。欢迎大家贡献力量。此仓库的目的是索引开源项目，而不是为了牟利而做广告。

所有链接都使用家庭烘焙的[Node.js脚本](https://github.com/veggiemonk/awesome-docker/blob/master/pull_request.js)进行监视和测试

# 内容

- [传说](https://github.com/veggiemonk/awesome-docker#legend)
- [什么是Docker](https://github.com/veggiemonk/awesome-docker#what-is-docker)
- [从哪儿开始](https://github.com/veggiemonk/awesome-docker#where-to-start)
- [从哪里开始（Windows）](https://github.com/veggiemonk/awesome-docker#where-to-start-windows)
- 专案
  - 集装箱作业
    - [容器组成](https://github.com/veggiemonk/awesome-docker#container-composition)
    - [部署和基础架构](https://github.com/veggiemonk/awesome-docker#deployment-and-infrastructure)
    - [监控方式](https://github.com/veggiemonk/awesome-docker#monitoring)
    - [联网](https://github.com/veggiemonk/awesome-docker#networking)
    - [编排](https://github.com/veggiemonk/awesome-docker#orchestration)
    - [PaaS](https://github.com/veggiemonk/awesome-docker#paas)
    - [反向代理](https://github.com/veggiemonk/awesome-docker#reverse-proxy)
    - [运行](https://github.com/veggiemonk/awesome-docker#runtime)
    - [安全](https://github.com/veggiemonk/awesome-docker#security)
    - [服务发现](https://github.com/veggiemonk/awesome-docker#service-discovery)
    - [卷管理/数据](https://github.com/veggiemonk/awesome-docker#volume-management--data)
    - 用户界面
      - [桌面](https://github.com/veggiemonk/awesome-docker#desktop)
      - [终奌站](https://github.com/veggiemonk/awesome-docker#terminal)
      - [网页](https://github.com/veggiemonk/awesome-docker#web)
  - Docker映像
    - [基础工具](https://github.com/veggiemonk/awesome-docker#base-tools)
    - [建造者](https://github.com/veggiemonk/awesome-docker#builder)
    - [Docker文件](https://github.com/veggiemonk/awesome-docker#dockerfile)
    - [林特](https://github.com/veggiemonk/awesome-docker#linter)
    - [元数据](https://github.com/veggiemonk/awesome-docker#metadata)
    - [登记处](https://github.com/veggiemonk/awesome-docker#registry)
  - 使用Docker开发
    - [API客户端](https://github.com/veggiemonk/awesome-docker#api-client)
    - [CI / CD](https://github.com/veggiemonk/awesome-docker#cicd)
    - [开发环境](https://github.com/veggiemonk/awesome-docker#development-environment)
    - [垃圾收集](https://github.com/veggiemonk/awesome-docker#garbage-collection)
    - [无服务器](https://github.com/veggiemonk/awesome-docker#serverless)
    - [测试中](https://github.com/veggiemonk/awesome-docker#testing)
    - [包装纸](https://github.com/veggiemonk/awesome-docker#wrappers)
  - 基于Docker的服务（💲）
    - [CI服务](https://github.com/veggiemonk/awesome-docker#ci-services)
    - [a](https://github.com/veggiemonk/awesome-docker#caas)
    - [监控服务](https://github.com/veggiemonk/awesome-docker#monitoring-services)
- 有用的资源
  - [很棒的清单](https://github.com/veggiemonk/awesome-docker#awesome-lists)
  - [演示与范例](https://github.com/veggiemonk/awesome-docker#demos-and-examples)
  - [好提示](https://github.com/veggiemonk/awesome-docker#good-tips)
  - [Raspberry Pi和ARM](https://github.com/veggiemonk/awesome-docker#raspberry-pi--arm)
  - [安全](https://github.com/veggiemonk/awesome-docker#security-1)
  - [影片](https://github.com/veggiemonk/awesome-docker#videos)
- 社区和聚会
  - [巴西人](https://github.com/veggiemonk/awesome-docker#brazilian)
  - [中文](https://github.com/veggiemonk/awesome-docker#chinese)
  - [英语](https://github.com/veggiemonk/awesome-docker#english)
  - [俄语](https://github.com/veggiemonk/awesome-docker#russian)
  - [西班牙文](https://github.com/veggiemonk/awesome-docker#spanish)
  - [随着时间的推移观星人](https://github.com/veggiemonk/awesome-docker#stargazers-over-time)

# 传说

- 弃 💀
- 贝塔 🚧
- 营利 💲

# 什么是Docker

> Docker是一个开放的平台，供开发人员和系统管理员构建，交付和运行分布式应用程序。Docker由便携式引擎，轻量级运行时和打包工具Docker Engine以及用于共享应用程序和自动化工作流的云服务Docker Hub组成，使应用程序可以从组件快速组装，并消除了开发，质量保证和生产环境之间的摩擦。结果，IT可以更快地交付并在笔记本电脑，数据中心VM和任何云上运行相同的应用程序，而无需更改。

*资料来源：* [什么是Docker](https://www.docker.com/why-docker)

# 从哪儿开始

- [使用Docker](https://semaphoreci.com/blog/docker-benefits)进行开发和交付的[好处以及采用](https://semaphoreci.com/blog/docker-benefits)的实用路线图。
- [Docker课程](https://github.com/prakhar1989/docker-curriculum)：关于Docker入门的综合教程。教您如何使用Docker以及如何通过Elastic Beanstalk和Elastic Container Service在AWS上部署dockerized应用程序。
- [Docker Documentation](https://docs.docker.com/)：官方文档。
- [面向初学者的Docker](https://github.com/groda/big_data/blob/master/docker_for_beginners.md)：面向需要从“ Hello world！”学习Docker基础的[初学者](https://github.com/groda/big_data/blob/master/docker_for_beginners.md)的教程。与容器的基本交互，以及对基本概念的简单说明。
- [面向初学者](https://www.youtube.com/watch?v=xsjSadjKXns)的Docker，面向从未使用过Docker的开发人员和测试人员。（视频1h40，录制于linux.conf.au 2019-新西兰基督城），作者是Alex Clews。
- [Docker培训](https://training.mirantis.com/) 💲
- [初学者Docker教程（2019年更新）](https://hashnode.com/post/docker-tutorial-for-beginners-cjrj2hg5001s2ufs1nker9he2) -在此Docker教程中，您将学习所有基础知识并学习如何容器化Node.js和Go应用程序。即使您不熟悉这些语言，也应该很容易阅读本教程并使用任何其他语言。
- [Katacoda](https://www.katacoda.com/courses/docker)：使用基于交互式浏览器的实验室学习Docker
- 通过[@dwyl](https://github.com/dwyl)[学习Docker](https://github.com/dwyl/learn-docker)：分步教程和更多资源（视频，文章，备忘单）
- [与Docker一起玩](https://training.play-with-docker.com/)：PWD是从初学者到高级用户入门Docker的绝佳方法。Docker直接在您的浏览器中运行。
- [关于西班牙语的Docker命令的实用指南](https://github.com/brunocascio/docker-espanol)该西班牙语指南包含基本docker命令和实际示例的使用。
- [容器术语实用介绍](https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction/)容器技术的前景不仅限于码头工人。如果没有良好的术语处理，可能很难把握docker和（选择您的最爱，CRI-O，rkt，lxc / lxd）之间的关键区别，或者难以理解开放容器倡议正在采取哪些措施来标准化容器技术。
- [Docker手册](https://www.freecodecamp.org/news/the-docker-handbook/)这10,000多个单词的文章分为38个部分，并通过项目示例向读者介绍Docker的所有基础知识。

**备忘**通过

- [@ eon01](https://github.com/eon01/DockerCheatSheet)
- [@dimonomid](https://github.com/dimonomid/docker-quick-ref)（PDF）
- [@JensPiegsa](https://github.com/JensPiegsa/docker-cheat-sheet)
- [@wsargent](https://github.com/wsargent/docker-cheat-sheet)（最受欢迎）

# 从哪里开始（Windows）

- [Windows Server与Linux平台上Docker引擎的比较研究](https://collabnix.com/a-comparative-study-of-docker-engine-on-windows-server-vs-linux-platform/)比较Windows和Linux上Docker的功能集和实现
- [构建并运行您的第一个Docker Windows Server容器](https://www.docker.com/blog/build-your-first-docker-windows-server-container/)演练在Windows 10上安装Docker，构建Docker映像并运行Windows容器
- [码头工人在Windows防火墙后](https://toedter.com/2015/05/11/docker-on-windows-behind-a-firewall/)通过[@kaitoedter](https://twitter.com/kaitoedter)
- [Docker快速教程](https://vegibit.com/docker-quick-tutorial/)向您介绍使用Windows 10和Hyper-V的官方入门指南。
- [Docker参考架构：传统.NET Framework应用程序的现代化](https://success.mirantis.com/article/modernizing-traditional-dot-net-applications)-您将学习确定适合容器化的“ .NET Framework”应用程序的类型，容器化是“提升和转移”的容器化方法。
- [带有Microsoft SQL 2016 + ASP.NET的Docker](https://blog.alexellis.io/docker-does-sql2016-aspnet/)演示在Docker中运行ASP.NET和SQL Server工作负载
- 在Linux和Windows容器中使用[Docker](https://docs.docker.com/docker-for-windows/)[探索ASP.NET Core，并使用Windows Docker在Linux和Windows容器中](https://www.hanselman.com/blog/ExploringASPNETCoreWithDockerInBothLinuxAndWindowsContainers.aspx)运行ASP.NET Core应用程序
- [在Windows容器中运行旧版ASP.NET应用程序](https://blog.sixeyed.com/dockerizing-nerd-dinner-part-1-running-a-legacy-asp-net-app-in-a-windows-container/)进行Docker化旧式ASP.NET应用程序并作为Windows容器运行的步骤
- [Windows容器和Docker：101](https://www.youtube.com/watch?v=N7SG2wEyQtM) 🎥 -20分钟的概述，使用Docker运行PowerShell，ASP.NET Core和ASP.NET应用程序
- [Windows容器快速入门](https://docs.microsoft.com/en-us/virtualization/windowscontainers/about/)Windows容器概述，深入到Windows 10和Windows Server 2016快速入门

------

# 专案

- Moby =开源开发
- Docker CE =基于Moby的免费产品发布
- Docker EE =基于Docker CE的商业产品发布。

> Docker EE与Docker CE在相同的代码基础上，因此也是从Moby构建的，并添加了商业组件，例如“ docker数据中心/通用控制平面”

- [白鲸](https://github.com/moby/moby)
- [Docker映像](https://hub.docker.com/)
- [Docker Compose](https://github.com/docker/compose/)（使用Docker定义和运行多容器应用程序）
- [Docker Machine](https://github.com/docker/machine)（用于以容器为中心的世界的机器管理）
- [Docker Registry](https://github.com/docker/distribution)（用于打包，运送，存储和交付内容的Docker工具集）
- [Docker Swarm](https://github.com/docker/swarm)（Swarm：Docker本地集群系统）

## 集装箱作业

### 容器组成

- [bocker](https://github.com/icy/bocker)（2）-用Bash完全编写Dockerfile。可扩展且简单。->可重复使用[@icy](https://github.com/icy)
- [博克](https://github.com/p8952/bocker)（1）💀-通过[p8952](https://github.com/p8952)在100行bash中实现Docker
- [框](https://github.com/box-builder/box)-使用mruby DSL构建Dockerfile映像，包括展平和层操作
- [匹](https://github.com/byrnedo/capitan)-可组合泊坞窗编排与添加脚本支持[@byrnedo](https://github.com/byrnedo)。
- [compose_plantuml](https://github.com/funkwerk/compose_plantuml) 💀-通过[@funkwerk](https://github.com/funkwerk)从docker-compose文件生成Plantuml图
- [Composerize-](https://github.com/magicmark/composerize)将docker run命令转换为docker-compose文件
- [人群](https://github.com/polonskiy/crowdr)-`docker-compose`通过[@polonskiy](https://github.com/polonskiy/)管理多个Docker容器的工具（替代）
- [docker-compose-graphviz](https://github.com/abesto/docker-compose-graphviz) 💀-通过[@abesto将docker](https://github.com/abesto) -compose.yml文件转换为Graphviz .dot文件
- [docker-config ](https://github.com/sudo-bmitch/docker-config-update)[-update-](https://github.com/sudo-bmitch)通过[@ sudo-bmitch](https://github.com/sudo-bmitch)更新用于在组成文件中部署[的docker](https://github.com/sudo-bmitch)配置和机密的实用程序
- [画作](https://github.com/Alexis-benoist/draw-compose) 💀-由[@ Alexis-benoist绘制docker](https://github.com/Alexis-benoist)架构的实用程序
- [elsy-](https://github.com/cisco/elsy)一个基于Docker和Docker Compose的多语言，自以为是的构建工具
- [体质](https://github.com/cloud66-oss/habitus)-一个构建流程工具泊坞窗由[@ cloud66](https://github.com/cloud66)
- [kompose-](https://github.com/kubernetes/kompose)从Docker Compose转到Kubernetes
- [大师](https://github.com/toscanini/maestro) 💀[-Maestro](https://github.com/toscanini)通过[@tascanini](https://github.com/toscanini)提供了轻松启动，编排和管理多个Docker容器作为单个单元的[功能](https://github.com/toscanini)
- [Percheron](https://github.com/ashmckenzie/percheron) 💀-通过[@ashmckenzie灵活](https://github.com/ashmckenzie)组织您的Docker容器
- [podman-](https://github.com/containers/podman-compose) compose-使用@containers的[podman](https://github.com/containers)运行docker-compose.yml的脚本
- [plash-](https://github.com/ihucos/plash)容器运行和构建引擎-在[docker](https://github.com/ihucos/plash)内部运行。
- [摇摆乐](https://github.com/grammarly/rocker-compose) 💀-具有幂等功能的Docker组合工具，用于部署由多个容器组成的应用程序。通过[@grammarly](https://github.com/veggiemonk/awesome-docker/blob/master/grammarly)。
- [摇杆](https://github.com/grammarly/rocker) 💀-扩展的Dockerfile构建器。通过[@grammarly](https://github.com/veggiemonk/awesome-docker/blob/master/grammarly)支持多个FROM，MOUNTS，模板等。
- [Stacker](https://github.com/stacker/stacker-cli) -Docker Compose模板。Stacker在Docker Compose之上提供了一个抽象层，并提供了更好的DX（开发人员体验）。
- [Stitchocker-](https://github.com/alexaandrov/stitchocker)一种轻量级且快速的命令行实用程序，用于方便地将[docker](https://github.com/alexaandrov/stitchocker) -compose多个容器服务分组。通过[@alexaandrov](https://github.com/alexaandrov)
- [Smalte](https://github.com/roquie/smalte) –动态配置需要在Docker容器中进行静态配置的应用程序。通过[@roquie](https://github.com/roquie)
- [生肖](https://github.com/CenturyLinkLabs/zodiac) 💀-轻型工具，可轻松部署和回滚dockerized应用程序。通过[@CenturyLinkLabs](https://github.com/CenturyLinkLabs)

### 部署和基础架构

- [黑鱼](https://gitlab.com/blackfish/blackfish)-一个CoreOS VM打造簇群的开发和生产的[@blackfish](https://gitlab.com/blackfish/)
- [BosnD](https://gitlab.com/n0r1sk/bosnd) -BosnD，boatswain守护程序-动态配置文件编写器和服务重新加载器，用于动态更改容器环境。
- [Centurion](https://github.com/newrelic/centurion) -Centurion是适用于Docker舰队的大规模部署工具。它从Docker注册表中获取容器，并在具有正确环境变量，主机卷映射和端口映射的主机群中运行它们。通过[@newrelic](https://github.com/newrelic)
- [Clocker](https://github.com/brooklyncentral/clocker) -Clocker创建和管理Docker云基础架构。Clocker支持多节点应用程序的单击部署和运行时管理，这些应用程序作为在多个主机上分布在Docker和Marathon上的容器运行。它利用[Calico](https://github.com/projectcalico/calicoctl)和[Weave](https://github.com/weaveworks/weave)进行网络连接，并利用[Brooklyn](https://brooklyn.apache.org/)进行应用程序蓝图。通过[@brooklyncentral](https://github.com/brooklyncentral)
- [管道](https://github.com/ehazlett/conduit)- [@ehazlett的](https://github.com/ehazlett)Docker实验部署系统
- [depcon](https://github.com/ContainX/depcon) -Depcon用Go语言编写，可让您轻松地将Docker容器部署到Apache Mesos / Marathon，Amazon ECS和Kubernetes。通过[@ContainX](https://github.com/ContainX)
- [部署](https://github.com/ttiny/deploy) 💀-Git和Docker部署工具。简单的Docker组合工具与[@ttiny](https://github.com/ttiny)全面编制的集群编排之间的中间立场
- [码头](https://github.com/humblec/dockit) 💀-做docker动作并部署gluster容器！通过[@humblec](https://github.com/humblec)
- [gitkube](https://github.com/hasura/gitkube) -Gitkube是一个用于使用Kubernetes构建和部署Docker映像的工具`git push`。通过[@Hasura](https://github.com/hasura/)。
- [Grafeas-](https://github.com/grafeas/grafeas)一种通用的API，用于处理有关容器的元数据，从图像和构建详细信息到安全漏洞。由[grafeas](https://github.com/grafeas)
- [浪人](https://github.com/longshoreman/longshoreman) 💀-Longshoreman使用Docker自动化应用程序部署。只需创建一个Docker存储库（或使用服务），使用AWS或Digital Ocean（或您喜欢的任何东西）配置集群，然后使用类似Heroku的CLI工具部署应用程序。由[longshoreman](https://github.com/longshoreman)
- [SwarmManagement](https://github.com/DIPSAS/SwarmManagement) -Swarm Management是一个Python应用程序，与pip一起安装。通过配置单个yaml文件，该文件可描述要部署的堆栈以及要创建的网络，配置或机密信息，该应用程序可轻松管理Docker Swarm。
- [werf](https://github.com/werf/werf) -werf是一个CI / CD工具，可有效构建Docker映像并将其使用@flant使用GitOps将其部署到[Kubernetes](https://github.com/flant)

### 监控方式

- [自动修复](https://github.com/willfarrell/docker-autoheal)-[自动](https://github.com/willfarrell/docker-autoheal)监视并重新启动不健康的Docker容器。
- [Axibase Collector](https://github.com/axibase/atsd-use-cases/tree/master/integrations/docker) -Axibase Collector将来自Docker引擎的性能计数器，配置更改和生命周期事件流到Axibase时间序列数据库中，以汇总仪表盘并与上游监控系统集成。
- [cAdvisor-](https://github.com/google/cadvisor)分析正在运行的容器的资源使用情况和性能特征。由[@Google](https://github.com/google)创建
- [dockprom](https://github.com/stefanprodan/dockprom) -泊坞窗主机和容器用普罗米修斯，Grafana，cAdvisor，NodeExporter和AlertManager监控[@stefanprodan](https://github.com/stefanprodan)
- [Docker-Alertd-](https://github.com/deltaskelta/docker-alertd)根据[Docker](https://github.com/deltaskelta/docker-alertd)容器资源使用情况/统计信息监视和发送警报
- [Docker-Flow-Monitor-](https://github.com/docker-flow/docker-flow-monitor)由[@ docker-flow](https://github.com/docker-flow)自动更新或部署新服务时重新配置Prometheus
- [码头工人](https://github.com/dockerana/dockerana) 💀 -Graphite和Grafana的打包版本，专门针对Docker的指标。
- [DockProc-进程级别上](https://gitlab.com/n0r1sk/dockproc)的容器的I / O监视。
- [Dozzle-](https://github.com/amir20/dozzle)监视容器使用浏览器或移动设备实时记录。[ami](https://github.com/amir20)
- [动态痕迹](https://www.dynatrace.com/technologies/docker-monitoring/) 💲 -监视容器化的应用程序，而无需安装代理或修改运行命令
- [眼神](https://github.com/nicolargo/glances)-用Python编写基于诅咒一个跨平台的系统监控工具[@nicolargo](https://github.com/nicolargo)
- [Grafana Docker仪表板模板](https://grafana.com/grafana/dashboards/179)-适用于Docker，Grafana和Prometheus堆栈[@vegasbrianc的模板](https://github.com/vegasbrianc)
- [InfluxDB，cAdvisor，Grafana](https://github.com/vegasbrianc/docker-monitoring) - InfluxDB时间序列数据库通过与Grafana和cAdvisor组合[@vegasbrianc](https://github.com/vegasbrianc)
- [僵局](https://github.com/gocardless/logjam)-僵局是一个日志转发专听一个本地端口上，通过UDP接收日志条目，并转发这些消息到一个日志采集服务器（如logstash）由[@gocardless](https://github.com/gocardless)
- [Logspout](https://github.com/gliderlabs/logspout) -日志由路由的码头工人集装箱原木[@gliderlabs](https://github.com/gliderlabs)
- [monit-docker-](https://github.com/decryptus/monit-docker)监视Docker容器资源的使用或状态并执行docker命令或在容器内部。[@decryptus] [decryptus]
- [NexClipper](https://github.com/NexClipper/NexClipper) - NexClipper是一家专业从事码头工人，阿帕奇Mesos，马拉松，DC / OS，中间层，Kubernetes容器监测和性能管理解决方案[@Nexclipper](https://github.com/NexClipper)
- [开箱即用的主机/容器监视/日志记录/警报堆栈](https://github.com/uschtwill/docker_monitoring_logging_alerting)-Docker主机和容器监视，开箱即用cAdvisor，Prometheus，Grafana进行监视，Elasticsearch，Kibana和Logstash进行日志记录和警报以进行日志记录以及elastalert和Alertmanager提醒。设置5分钟。内置的[自动Nginx反向代理（jwilder's）](https://github.com/nginx-proxy/nginx-proxy)用于生产的安全模式。
- [SwarmAlert-](https://github.com/gpulido/SwarmAlert)监视Docker Swarm并在发现没有运行正常服务任务的容器时发送Pushover警报。
- [Zabbix Docker模块](https://github.com/monitoringartist/Zabbix-Docker-Monitoring)-Zabbix模块，可发现正在运行的容器，CPU /内存/ blk IO /网络容器指标。还支持系统化Docker和LXC执行驱动程序。它是一个动态链接的共享对象库，因此其性能比任何脚本解决方案都要好（〜10倍）。
- [Zabbix Docker-](https://github.com/gomex/docker-zabbix)使用[zabbix](https://github.com/gomex/docker-zabbix) LLD功能自动监视容器。

### 联网

- [Calico-Docker](https://github.com/projectcalico/calicoctl) -Calico是一个纯第3层虚拟网络，它允许多个docker-hosts上的容器相互通信。
- [法兰](https://github.com/coreos/flannel/)-法兰是一个虚拟网络，为每个主机提供一个子网，以供容器运行时使用。通过[@coreos](https://github.com/coreos)
- [Freeflow](https://github.com/Microsoft/Freeflow) -Linux上的高性能容器覆盖网络。启用RDMA（在InfiniBand和RoCE上）并加速TCP到裸机的性能。通过[@Microsoft](https://github.com/Microsoft)
- [netshoot](https://github.com/nicolaka/netshoot) -netshoot容器具有一组功能强大的网络工具，可帮助解决[@nicolaka的](https://github.com/nicolaka)Docker网络问题
- [Pipework-](https://github.com/jpetazzo/pipework)适用于Linux容器的软件定义网络，Pipework可与“普通” LXC容器以及出色的Docker一起使用。通过[@jpetazzo](https://github.com/jpetazzo)
- [Weave](https://github.com/weaveworks/weave)（Docker网络）-Weave创建一个虚拟网络，该网络连接跨多个主机部署的Docker容器。

### 编排

- [athena-](https://github.com/athena-oss/athena)具有插件架构的自动化平台，可让您轻松创建和共享服务。
- [飞艇](https://github.com/tubesandlube/blimp) 💀-使用Docker Machine轻松地将容器从一个Docker主机移至另一台Docker主机，显示针对所有主机运行的容器，跨多个主机复制容器以及[@defermat](https://github.com/defermat)和[@schvin](https://github.com/schvin)
- [CloudSlang](https://github.com/CloudSlang/cloud-slang) -CloudSlang是用于创建Docker流程自动化的工作流引擎
- [clusterdock-](https://github.com/clusterdock/clusterdock)用于测试长期运行的集群部署的Docker容器编排
- [集装箱船](https://github.com/containership/containership) 💀 -一个简单的容器管理平台
- [起重机](https://github.com/Dataman-Cloud/crane)基于泊坞窗控制平面内置群- [@ DATAMAN云](https://github.com/Dataman-Cloud)
- [Docker Flow Swarm Listener](https://github.com/docker-flow/docker-flow-swarm-listener) -Docker Flow Swarm Listener项目用于侦听Docker Swarm事件并在发生更改时发送请求。通过[@ docker-flow](https://github.com/docker-flow)
- [龙门式](https://github.com/DevTable/gantryd) 💀-通过[@DevTable](https://github.com/DevTable)跨机器轻松管理基于[docker的](https://github.com/DevTable)组件的[框架](https://github.com/DevTable)
- [Haven](https://github.com/codeabovelab/haven-platform) -Haven是一个简化的容器管理平台，集成了容器，应用程序，群集，映像和注册表管理。由[@codeabovelab](https://github.com/codeabovelab)
- [太阳神](https://github.com/spotify/helios) 💀-通过[@spotify](https://github.com/spotify)在整个服务器[群中](https://github.com/spotify)部署和管理容器的简单平台
- [康特纳](https://github.com/kontena/kontena) 💀-开发人员友好的容器和微服务平台。可在任何云上运行，易于设置，易于使用。
- [Kubernetes](https://github.com/kubernetes/kubernetes) -Google的Docker容器的开源编排系统
- [ManageIQ-](https://github.com/ManageIQ/manageiq)发现，优化和控制您的混合IT。通过[ManageIQ](https://github.com/ManageIQ)
- [Mantl](https://github.com/mantl/mantl) -Mantl是用于快速部署全球分布式服务的现代平台
- [马拉松](https://github.com/mesosphere/marathon)-马拉松是基于Mesos构建的私有PaaS。它会自动处理硬件或软件故障，并确保应用程序“始终在线”
- [Mesos](https://github.com/apache/mesos) -资源/作业调度为容器，虚拟机和物理主机[@apache](https://mesos.apache.org/)
- [Nebula-](https://github.com/nebula-orchestrator)一种Docker编排工具，旨在管理大规模分布式集群。
- [Nomad-](https://github.com/hashicorp/nomad)轻松部署任何规模的应用程序。[@hashicorp的](https://github.com/hashicorp)分布式，高度可用的，支持数据中心的调度程序
- [巴拿马型](https://github.com/CenturyLinkLabs/panamax-ui) 💀-一个开源项目，使部署复杂的容器化应用程序就像[@CenturyLinkLabs进行的](https://github.com/CenturyLinkLabs)拖放操作一样容易。
- [Rancher-](https://github.com/rancher/rancher)一个开放源代码项目，提供了一个完整的平台，用于[@rancher](https://github.com/rancher)在生产中操作Docker 。
- [Swarm-cronjob- ](https://github.com/crazy-max/swarm-cronjob)[@ crazy-max](https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max)在Swarm上基于时间的时间表创建作业

### PaaS

- [亚特兰蒂斯](https://github.com/ooyala/atlantis) 💀 -亚特兰蒂斯（Atlantis）是一个基于Docker并以Go编写的HTTP应用程序的开源PaaS
- [caprover-](https://github.com/caprover/caprover) [以前称为CaptainDuckDuck]自动化可伸缩Web服务器程序包（自动化Docker + nginx）-类固醇上的Heroku
- [Convox Rack](https://github.com/convox/rack) -Convox Rack是开源PaaS，建立在专家基础架构自动化和最佳实践之上。
- [Dcw](https://github.com/pbertera/dcw) -Docker-compose SSH包装器：一个非常可怜的人PaaS，公开了容器标签中定义的docker-compose和custom-container命令。
- [Dokku](https://github.com/dokku/dokku) -Docker支持的mini-Heroku，可帮助您构建和管理应用程序的生命周期（最初为[@progrium](https://github.com/progrium)）
- [帝国](https://github.com/remind101/empire)-基于Amazon EC2容器服务（ECS）构建的PaaS
- [Exoframe-](https://github.com/exoframejs/exoframe)一种自托管工具，允许使用Docker进行简单的单命令部署
- [Flynn-](https://github.com/flynn/flynn)下一代开源平台即服务
- [Hephy Workflow](https://github.com/teamhephy/workflow) - [Kubernetes的](https://github.com/teamhephy/workflow)开源PaaS，它向任何Kubernetes集群添加了开发人员友好的层，从而使部署和管理应用程序变得容易。[Deis工作流程](https://github.com/deis/workflow)的[分支](https://github.com/deis/workflow)
- [纳米盒](https://github.com/nanobox-io/nanobox) 💲 -创建本地环境的应用程序开发平台，然后可以在云中进行部署和扩展。
- [OpenShift-](https://www.okd.io/)基于[Kubernetes](https://kubernetes.io/)构建的开源PaaS，并针对[Red Hat](https://www.redhat.com/en)优化的Dockerized应用开发和部署进行了优化
- [Tsuru](https://github.com/tsuru/tsuru) -Tsuru是可扩展的开源平台即服务软件

### 反向代理

- [Docker Dnsmasq](https://github.com/moonbuggy/docker-dnsmasq-updater) Updater-使用Docker容器主机名更新远程dnsmasq服务器。
- [docker-flow-](https://github.com/docker-flow/docker-flow-proxy) proxy-每次部署新服务或扩展服务时重新配置代理。通过[@ docker-flow](https://github.com/docker-flow)
- [码头工人代理](https://github.com/silarsis/docker-proxy) 💀-Docker容器的透明代理，在Docker容器中运行。通过[@silarsis](https://github.com/silarsis)
- [fabio-](https://github.com/fabiolb/fabio)一种快速，现代的零配置负载平衡HTTP（S）路由器，用于部署由领事管理的微服务。通过[@magiconair](https://github.com/magiconair)（弗兰克·施罗德）
- [水-代理](https://github.com/zchee/h2o-proxy) 💀-Docker容器的自动化H2O反向代理。一个替代[jwilder / nginx的代理](https://github.com/nginx-proxy/nginx-proxy)通过[@zchee](https://github.com/zchee)
- [让我们加密Nginx-proxy伴侣](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion)-一个轻量级的nginx-proxy伴侣容器。它允许自动创建/更新“加密我们的证书”。通过[@JrCs](https://github.com/JrCs)
- [穆格](https://github.com/mattallty/muguet) 💀-适用于Docker环境的DNS服务器和反向代理。通过[@mattallty](https://github.com/mattallty)
- [nginx- ](https://github.com/nginx-proxy/nginx-proxy)[proxy-@jwilder](https://github.com/jwilder)使用[docker](https://github.com/jwilder) -gen为Docker容器提供的自动nginx代理
- [Nginx代理管理器](https://github.com/jc21/nginx-proxy-manager)-一个漂亮的Web界面，用于使用SSL代理基于Web的服务。由[@ jc21](https://github.com/jc21)
- [群入口路由器](https://github.com/tpbowden/swarm-ingress-router) 💀-根据标签将DNS名称路由到Swarm服务。通过[@tpbowden](https://github.com/tpbowden/)
- [Swarm路由器](https://github.com/flavioaiello/swarm-router)-一种基于“零配置”服务名称的路由器，适用于docker swarm模式，提供了一种全新且更安全的方法。通过[@flavioaiello](https://twitter.com/flavioaiello)
- [Træfɪk-](https://github.com/containous/traefik)用于Docker，Mesos，Consul，Etcd的自动化反向代理和负载平衡器... [@EmileVauge](https://github.com/emilevauge)

### 运行

- [aind](https://github.com/aind-containers/aind) -AinD通过[@ aind-containers](https://github.com/aind-containers)在Docker内部嵌套Anbox容器，在Docker中启动Android应用
- [cri-o-](https://github.com/cri-o/cri-o)通过[cri-o](https://github.com/cri-o)基于开放容器倡议的Kubernetes容器运行时接口的[实现](https://github.com/cri-o)
- [lxc](https://github.com/lxc/lxc) -LXC-Linux容器
- [podman](https://github.com/containers/libpod) -libpod是用于创建容器Pod的库。Podman的家[@containers](https://github.com/containers)
- [rlxc](https://github.com/brauner/rlxc) -书面拉斯特LXC二进制[@brauner](https://github.com/brauner)
- [运行时工具](https://github.com/opencontainers/runtime-tools)-oci-runtime-tool是[@opencontainers](https://github.com/opencontainers)用来与OCI运行时规范一起使用的工具的集合

### 安全

- [Anchor ](https://github.com/anchore/anchore)[Engine-](https://github.com/anchore)通过[@Anchor](https://github.com/anchore)分析映像中的CVE漏洞和自定义安全策略
- [水上安全](https://www.aquasec.com/) 💲 -在任何平台上保护从开发到生产的基于容器的应用程序的安全
- [祸根](https://github.com/genuinetools/bane)-为Docker容器用AppArmor配置文件生成[@genuinetools](https://github.com/genuinetools)
- [CIS Docker基准测试](https://github.com/dev-sec/cis-docker-benchmark)-此[InSpec](https://github.com/inspec/inspec)合规性配置文件以自动化方式实现CIS Docker 1.12.0基准测试，以在生产环境中围绕Docker守护程序和容器提供安全性最佳实践测试。通过[@ dev-sec](https://github.com/dev-sec)
- [Clair](https://github.com/quay/clair) -Clair是一个开源项目，用于静态分析appc和docker容器中的漏洞。通过[@coreos](https://github.com/coreos)
- [Dagda](https://github.com/eliasgranderubio/dagda) -Dagda是一种工具，用于对Docker映像/容器中的已知漏洞，特洛伊木马，病毒，恶意软件和其他恶意威胁进行静态分析，并监视Docker守护程序和运行Docker容器以检测异常活动。通过[@eliasgranderubio](https://github.com/eliasgranderubio)
- [深度围栏企业](https://deepfence.io/) 💲-用于kubernetes，虚拟机和无服务器的完整生命周期Cloud Native Workload Protection平台。通过[@deepfence](https://github.com/veggiemonk/awesome-docker/blob/master/deepfence)
- [Deepfence Threat Mapper-](https://github.com/deepfence/ThreatMapper)强大的运行时漏洞扫描程序，适用于kubernetes，虚拟机和无服务器。通过[@deepfence](https://github.com/veggiemonk/awesome-docker/blob/master/deepfence)
- [docker-bench-security-](https://github.com/docker/docker-bench-security)用于检查在生产环境中部署Docker容器的数十种常见最佳实践的脚本。通过[@docker](https://github.com/docker)
- [docker-explorer-](https://github.com/google/docker-explorer)一种工具，用于对[@Google进行的](https://github.com/google)离线[docker](https://github.com/google)收购进行[取证](https://github.com/google)
- [公证人](https://github.com/theupdateframework/notary)-服务器和客户端，用于运行可信集合并与之交互。通过[@TUF](https://github.com/theupdateframework)
- [oscap-docker-](https://github.com/OpenSCAP/openscap) OpenSCAP提供了oscap-docker工具，该工具用于扫描Docker容器和图像。通过[OpenSCAP](https://github.com/OpenSCAP)
- [声音安全](https://phonito.io/?b=b) 💲 -具有持续的Kubernetes监视和管道集成的Docker漏洞扫描程序。
- [棱镜云](https://www.paloaltonetworks.com/prisma/cloud) 💲 -（以前为Twistlock Security Suite）可检测漏洞，强化容器映像并在应用程序的整个生命周期内实施安全策略。
- [Sysdig Falco](https://github.com/falcosecurity/falco) -Sysdig Falco是一个开源容器安全监视器。它可以监视应用程序，容器，主机和网络活动，并在发生未经授权的活动时发出警报。
- [Sysdig安全](https://sysdig.com/products/kubernetes-security/runtime-security/) 💲 -Sysdig Secure通过行为监视和防御解决运行时安全问题，并基于开源Sysdig提供深度的取证，以进行事件响应。
- [趋势科技趋势科技服务器深度安全防护系统](https://www.trendmicro.com/en_us/business/products/hybrid-cloud/deep-security.html) 💲 -趋势科技趋势科技服务器深度安全防护系统提供了针对容器工作负载和主机的运行时保护，并提供了对图像的运行前扫描，以识别漏洞，恶意软件和诸如硬编码机密之类的内容。
- [Trivy]（https://github.com/aquasecurity/trivy）-Aqua Security的开源简单，全面的容器漏洞扫描程序（适用于CI）。

### 服务发现

- [docker ](https://github.com/progrium)[-consul](https://github.com/gliderlabs/docker-consul)由[@progrium](https://github.com/progrium)
- [etcd- ](https://github.com/etcd-io/etcd)[@ etcd-io](https://github.com/etcd-io)（[CoreOS的](https://github.com/etcd-io)前身）为分布式系统的最关键数据提供了分布式可靠键值存储
- [istio-](https://github.com/istio/istio)通过[@IstioMesh](https://github.com/veggiemonk/awesome-docker/blob/master/istio)连接，管理和保护微服务的开放平台
- [代理](https://github.com/factorish/proxy) 💀-使用注册器提供的服务发现，基于nginx的轻量级负载均衡器自我。通过[@factorish](https://github.com/factorish)
- [注册器](https://github.com/gliderlabs/registrator)- [@gliderlabs](https://github.com/gliderlabs)和[@progrium的](https://github.com/progrium)Docker服务注册桥

### 卷管理/数据

- [Blockbridge](https://github.com/blockbridge/blockbridge-docker-volume) 💲-Blockbridge插件是一个卷插件，可用于访问一组可扩展的基于容器的持久性存储选项。它支持单主机和多主机Docker环境，其功能包括租户隔离，自动配置，加密，安全删除，快照和QoS。通过[@blockbridge](https://github.com/blockbridge)
- [Convoy-](https://github.com/rancher/convoy)开源Docker卷驱动程序，可以在任何地方快照，备份和还原Docker卷。通过[@rancher](https://github.com/rancher)
- [Docker Machine NFS](https://github.com/adlogix/docker-machine-nfs)为通过OS X上的Docker Machine创建的现有boot2docker框激活NFS。
- [Docker Unison](https://github.com/leighmcculloch/docker-unison)一个使用Unison进行快速双向文件夹同步的docker卷容器。创建以替代OS X上缓慢的boot2docker卷。作者：[@leighmcculloch](https://github.com/leighmcculloch)
- [Local Persist](https://github.com/MatchbookLab/local-persist)为本地卷指定一个挂载点（通过创建`docker volume create`），这样文件将始终存在，因此您可以挂载到不同容器中的不同目录。
- [Minio](https://github.com/minio/minio) -Docker容器中的S3兼容对象存储服务器
- [Netshare](https://github.com/ContainX/docker-volume-netshare) Docker NFS，AWS EFS，Ceph和Samba / CIFS卷插件。通过[@ContainX](https://github.com/ContainX)
- [portworx](https://portworx.com/) 💲 -用于持久，共享和复制卷的分散存储解决方案。
- [字节](https://www.quobyte.com/) 💲 -具有Docker卷驱动程序的完全容错的分布式文件系统
- [REX-Ray](https://github.com/rexray/rexray)提供了与供应商无关的存储编排引擎。主要设计目标是为Docker，Kubernetes和Mesos提供持久性存储。由[@thecodeteam](https://github.com/thecodeteam)（DELL Technologies）
- [斯托里奇](https://github.com/Storidge/quick-start#step-1-install-cio-software) 💲 -用于Kubernetes和Docker Swarm的软件定义的持久存储

### 用户界面

#### 桌面

用于管理和监视Docker主机和集群的本机桌面应用程序

- [船长](https://getcaptain.co/)- [@RickWong](https://github.com/rickwong)从MacOSX菜单栏中管理容器
- [Dockeron-](https://github.com/dockeron/dockeron)一个在Electron + Vue.js上为桌面Docker构建的项目。[@ fluency03](https://github.com/fluency03)
- [DockerStacks-](http://docker-stacks.com/)本地LAMP / LEMP开发工作室[@ sfx101](https://github.com/sfx101)
- [DockStation-](https://github.com/DockStation/dockstation)以开发人员为中心的UI，用于配置，监视和管理服务和容器[@dock_station](https://twitter.com/dock_station)
- [救生艇](https://github.com/jplhomer/lifeboat)-在Mac上使用图形界面启动Docker项目的简便方法。[@jplhomer](https://github.com/jplhomer)

#### 终奌站

- [船长](https://github.com/jenssegers/captain)-从任何目录轻松启动和停止docker compose项目。通过[@jenssegers](https://github.com/jenssegers)
- [ctop（1）](https://github.com/yadutaf/ctop) -基于命令行/文本的Linux容器监视工具，其作用与[@yadutaf所](https://github.com/yadutaf)期望的（Python）[一样](https://github.com/yadutaf)
- [CTOP（2）](https://github.com/bcicen/ctop) -顶部样通过接口，用于容器的度量（Golang）[@bcicen](https://github.com/bcicen/)
- [dext-docker-registry-](https://github.com/vutran/dext-docker-registry-plugin) plugin-使用Dext智能启动器搜索Docker注册表。
- [潜水](https://github.com/wagoodman/dive)-用于探索docker映像中每个图层的工具。由[瓦古德曼（Wagoodman）](https://github.com/wagoodman)。
- [搬运工-LS](https://github.com/mayflower/docker-ls) -通过浏览和操纵搬运工登记CLI工具[@mayflower](https://github.com/mayflower)
- [docker-ssh](https://github.com/jeroenpeeters/docker-ssh) -Docker容器的SSH服务器〜因为每个容器都应该可访问。通过[@jeroenpeeters](https://github.com/jeroenpeeters)
- [码头工人](https://github.com/icecrime/docker-mon) 💀-通过[@icecrime](https://github.com/icecrime)进行基于控制台的Docker监控
- [docker.el](https://github.com/Silex/docker.el)通过[Silex](https://github.com/Silex)从Emacs管理[docker](https://github.com/Silex/docker.el)
- [dockercraft](https://github.com/docker/dockercraft) -Docker +我的世界= @docker的[Dockercraft](https://github.com/docker)
- [dockerfile-mode](https://github.com/spotify/dockerfile-mode)通过[@spotify](https://github.com/spotify)处理Dockerfile的emacs模式
- [docker pushrm-](https://github.com/christian-korneck/docker-pushrm)一个Docker CLI插件，可让您将README.md文件从当前目录推送到Docker Hub。还支持码头和港口。通过[@ christian-korneck](https://github.com/christian-korneck)
- [dockersql-](https://github.com/crosbymichael/dockersql)通过[@crosbymichael](https://github.com/crosbymichael)使用SQL查询Docker的命令行界面
- [DockSTARTer](https://github.com/GhostWriters/DockSTARTer) - DockSTARTer帮助您开始使用由码头工人跑回家服务器应用程序（[代笔](https://github.com/GhostWriters)）
- [dockly-](https://github.com/lirantal/dockly)通过[@lirantal](https://github.com/lirantal)管理Docker容器的交互式shell UI
- [干](https://github.com/moncho/dry)-对Docker容器通过一个交互式CLI [@moncho](https://github.com/moncho)
- [DVM](https://github.com/howtowhale/dvm) -由泊坞版本管理[@howtowhale](https://github.com/howtowhale)
- [goinside-](https://github.com/iamsoorena/goinside)轻松进入正在运行的[docker](https://github.com/iamsoorena/goinside)容器。通过[@iamsoorena](https://github.com/iamsoorena)
- [lazydocker-](https://github.com/jesseduffield/lazydocker)管理所有[docker](https://github.com/jesseduffield/lazydocker)的懒惰方式。用于docker和docker-compose的简单终端UI，使用gocui库用Go编写。通过[@jesseduffield](https://github.com/jesseduffield)
- [MultiDocker-](https://github.com/marty90/multidocker)创建一个安全的多用户Docker计算机，其中每个用户都被隔离到一个独立的容器中。
- [ns- ](https://github.com/jpetazzo/nsenter)[enter-](https://github.com/jpetazzo)不再使用ssh，通过[@jpetazzo](https://github.com/jpetazzo)输入容器的名称空间
- [Pdocker- ](https://github.com/g31s/Pdocker)[@ g31s](https://github.com/veggiemonk/awesome-docker/blob/master/g31s)管理和维护个人项目Docker的简单工具
- [Powerline-Docker](https://github.com/adrianmo/powerline-docker) -Powerline部分，用于显示[@adrianmo](https://github.com/adrianmo)的Docker容器的[状态](https://github.com/adrianmo)
- [proco](https://github.com/shiwaforce/poco) -Proco将使用简单的YAML配置文件帮助您组织和管理任何复杂程度的Docker，Docker-Compose，Kubernetes项目，以缩短从查找项目到在本地环境中初始化项目的路线。通过[@shiwaforce](https://github.com/shiwaforce)
- [REG](https://github.com/genuinetools/reg) -由码头工人注册表V2命令行客户端[@genuinetools](https://github.com/genuinetools)
- [水肺](https://github.com/JonathonReinhart/scuba)-透明地使用Docker容器封装软件生成环境，通过[@JonathonReinhart](https://github.com/JonathonReinhart)
- [sen](https://github.com/TomasTomecek/sen) - [docker](https://github.com/TomasTomecek)引擎的终端用户界面，由[@TomasTomecek](https://github.com/TomasTomecek)
- [skopeo-](https://github.com/containers/skopeo)使用远程图像注册中心-通过[@containers](https://github.com/containers)检索信息，图像和签名内容
- [supdock-](https://github.com/segersniels/supdock)通过交互式提示允许对Docker进行更多可视化使用。通过[@segersniels](https://github.com/segersniels)
- [tsaotun- ](https://github.com/qazbnm456/tsaotun)[@ qazbnm456](https://github.com/qazbnm456)为Docker提供基于Python的协助
- [wharfee](https://github.com/j-bennet/wharfee) -Docker命令的自动完成和语法突出显示。通过[@ j-bennet](https://github.com/j-bennet)

#### 网页

- [Container Web TTY-](https://github.com/wrfly/container-web-tty)通过Web-tty [@wrfly](https://github.com/wrfly)连接容器
- [Docker Compose](https://github.com/francescou/docker-compose-ui) UI-通过HTTP管理docker-compose docker-compose-ui在Docker容器中运行，安装主机docker套接字并公开RESTful API和AngularJS GUI
- [Docker注册表浏览器](https://github.com/klausmeyer/docker-registry-browser)- [@klausmeyer](https://github.com/klausmeyer)的Docker注册表HTTP API v2的Web界面
- [Docker Registry ](https://github.com/atcol/docker-registry-ui)[UI-](https://github.com/atcol)通过[@atcol](https://github.com/atcol)轻松实现私有/本地Docker Registry集成的Web UI
- [码头工人注册UI（Joxit）](https://github.com/Joxit/docker-registry-ui) -由私人注册的最简单和干净的UI [@Joxit](https://github.com/Joxit)
- [docker-registry- ](https://github.com/mkuchin/docker-registry-web)[web-@mkuchin的](https://github.com/mkuchin)专用[docker](https://github.com/mkuchin) Registry v2的Web UI，身份验证服务和事件记录器
- [docker-swarm-visualizer-](https://github.com/dockersamples/docker-swarm-visualizer)可视化Docker Swarm上的Docker服务（用于运行演示）。
- [码头上的码头](https://github.com/Electrofenster/dockerding-on-rails) 💀- [@Electrofenster](https://github.com/Electrofenster/)提供的具有许多功能的[适用](https://github.com/Electrofenster/)于Docker的简单Web接口
- [DockerSurfer](https://github.com/Simone-Erba/DockerSurfer) 💀-用于分析和浏览Docker注册表中Docker映像之间的依赖关系的Web服务，[@ Simone-Erba](https://github.com/Simone-Erba/)
- [Kubevious](https://github.com/kubevious/kubevious) - [Kubernetes](https://github.com/kubevious/kubevious)的高度可视化的Web UI，通过[@rubenhak](https://github.com/rubenhak)以应用程序为中心的方式呈现配置和状态。
- [OctoLinker](https://github.com/OctoLinker/OctoLinker) -GitHub的浏览器扩展，使图像名称`Dockerfile`可单击，并将您重定向到相关的Docker Hub页面。
- [Portainer](https://github.com/portainer/portainer) -通过管理您的码头工人的主机或码头群簇一个轻量级的管理UI [@portainer](https://github.com/portainer)
- [Rapid Dashboard- ](https://github.com/ozlerhakan/rapid)[@ozlerhakan的](https://github.com/ozlerhakan/)简单查询仪表板，可使用Docker Remote API
- [Seagull-](https://github.com/tobegit3hub/seagull)友好的Web UI监视docker守护程序 通过[@ tobegit3hub](https://github.com/tobegit3hub)
- [Swarmpit](https://github.com/swarmpit/swarmpit) -Swarmpit为您的Docker Swarm集群提供了简单易用的界面。您可以管理堆栈，服务，机密信息，卷，网络等。
- [Swirl](https://github.com/cuigh/swirl) -Swirl是Docker的Web管理工具，专注于swarm集群作者[@cuigh](https://github.com/cuigh/)
- [Theia-](https://github.com/eclipse-theia/theia)可扩展的平台，可使用最新的Web技术开发功能全面的多语言类云和桌面IDE产品。

## Docker映像

### 基础工具

安装在容器内或设计为可在[边车上](https://docs.microsoft.com/en-us/azure/architecture/patterns/sidecar)运行的工具和应用程序

- [amicontained-](https://github.com/genuinetools/amicontained)容器自省工具。找出正在使用的容器运行时以及[@genuinetools](https://github.com/genuinetools)提供的[功能](https://github.com/genuinetools)
- [AUTODOCK](https://github.com/prologic/autodock) -守护泊坞自动化通过[@prologic](https://github.com/prologic)
- [伴侣](https://github.com/garywiz/chaperone)-为Docker容器设计的单个PID1进程。将用户管理，日志管理，启动，僵尸收割全部打包在一个小包装中。通过[@garywiz](https://github.com/garywiz)
- [ckron-用于docker](https://github.com/nicomt/ckron)的cron式作业调度程序，由[@nicomt提供](https://github.com/nicomt)
- [CoreOS-](https://github.com/coreos)适用于大规模服务器部署的Linux
- [distroless-@GoogleContainerTools](https://github.com/GoogleContainerTools/distroless)减去操作系统后，以语言为中心的[docker映像](https://github.com/GoogleContainerTools)
- [搬运工高山](https://github.com/gliderlabs/docker-alpine)-甲超小泊坞基本图像*（5MB）*使用高山的Linux通过[@gliderlabs](https://github.com/gliderlabs)
- [泊坞窗根](https://github.com/jwilder/docker-gen)-生成由搬运工人容器元数据文件[@jwilder](https://github.com/jwilder)
- [dockerize-](https://github.com/jwilder/dockerize)通过[@jwilder](https://github.com/jwilder)简化在[Docker](https://github.com/jwilder)容器中运行应用程序的实用程序
- [GoSu-](https://github.com/tianon/gosu)以该特定用户身份运行此特定应用程序，并通过[@tianon](https://github.com/tianon)退出管道（入口点脚本工具）
- [is- ](https://github.com/sindresorhus/is-docker)[docker-@sindresorhus](https://github.com/sindresorhus/awesome)检查进程是否在Docker容器中运行
- [lstags-](https://github.com/ivanilves/lstags)通过[@ivanilves](https://github.com/ivanilves)在各个注册表之间同步Docker映像
- [NVIDIA- ](https://github.com/NVIDIA/nvidia-docker)[Docker-@ ](https://github.com/nvidia)[NVIDIA的Docker](https://github.com/NVIDIA/nvidia-docker)的NVIDIA容器运行时
- [苏](https://github.com/theAkito/sue)-执行程序从用户运行起诉用户不同。这是ncopa / su-exec的可维护替代方法，后者是更好的tianon / gosu。它比原始的gosu更好（更高的性能，更小的尺寸），但是比用纯C语言编写的su-exec维护起来容易得多。[@theAkito](https://github.com/theAkito)
- [su-exec-](https://github.com/ncopa/su-exec)这是一个简单的工具，可以简单地执行具有不同特权的程序。该程序将直接被执行，而不是像su和sudo一样像孩子一样运行，从而避免了TTY和信号问题。为什么要重塑gosu？这项功能与gosu差不多，但只有10kb，而不是1.8MB。由[ncopa](https://github.com/ncopa)
- [supercronic-](https://github.com/aptible/supercronic)与crontab兼容的工作运行程序，专门设计用于由[@aptible](https://github.com/aptible/)在容器中运行
- [TrivialRC-](https://github.com/vorakl/TrivialRC)容器[@vorakl的](https://github.com/vorakl)简约运行时配置系统和过程管理器

### 建造者

旨在帮助或简化构建**新**映像的应用程序

- [ansible本德尔](https://github.com/ansible-community/ansible-bender)-利用工具`ansible`和`buildah`通过[@TomasTomecek](https://github.com/TomasTomecek)
- [buildah-](https://github.com/containers/buildah)通过[@containers](https://github.com/containers)有助于构建OCI图像的[工具](https://github.com/containers)
- [BuildKit](https://github.com/moby/buildkit) -并发，高速缓存效率，并Dockerfile无关的建设者工具[@moby项目](https://github.com/moby)
- [cekit](https://github.com/cekit/cekit) - [openshift](https://github.com/cekit/cekit)用于@cekit使用不同构建引擎构建基础映像的[工具](https://github.com/cekit)。
- [container-](https://github.com/GoogleContainerTools/container-diff) diff-一种图像工具，用于通过[@GoogleContainerTools](https://github.com/GoogleContainerTools)比较和分析容器图像
- [container- ](https://github.com/mutable/container-factory)[factory-](https://github.com/mutable)通过[@mutable](https://github.com/mutable)从应用程序源代码的压缩文件中生成Docker映像
- [copy- ](https://github.com/mdlavin/copy-docker-image)[docker-image-@mdlavin](https://github.com/mdlavin)无需完整安装Docker就在注册表之间复制Docker映像
- [德里克](https://github.com/alibaba/derrick)-一个工具，帮助您自动Dockerfile的产生，并通过扫描代码dockerize应用。通过[@alibaba](https://github.com/alibaba)。
- [dlayer](https://github.com/wercker/dlayer) -统计收集器，用于通过泊坞层[@wercker](https://github.com/wercker)
- [docker-companion-](https://github.com/mudler/docker-companion)用Golang编写的命令行工具，用于通过[@mudler](https://github.com/mudler/)压缩[和解](https://github.com/mudler/)压缩[docker映像](https://github.com/mudler/)
- [docker-](https://github.com/CtripCloud/docker-make) make-通过单个命令构建，标记和推送一堆相关的docker映像。
- [docker-replay-](https://github.com/bcicen/docker-replay)`docker run`从正在运行的容器生成命令和选项。通过[bcicen](https://github.com/bcicen)
- [DockerMake-](https://github.com/avirshup/DockerMake)用于复杂软件堆栈的可复制Docker映像构建系统。通过[@avirshup](https://github.com/avirshup)
- [DockerSlim](https://github.com/docker-slim/docker-slim)缩小胖的Docker映像，以创建尽可能小的映像。
- [Dockly](https://github.com/swipely/dockly) -Dockly是为减轻[@@ swipely](https://github.com/swipely/)将应用程序打包在Docker中的痛苦而制作的[瑰宝](https://github.com/swipely/)
- [码头](https://github.com/jlhawn/dockramp) 💀-概念验证：[@jlhawn的](https://github.com/jlhawn)客户端驱动的Docker Image Builder
- [埃塞克斯](https://github.com/utensils/essex)-样板为基础的多克项目：埃塞克斯是写在bash快速设置清晰一致的泊坞项目生成文件的工作流驱动一个CLI工具。[@jamesbrink](https://github.com/jamesbrink)
- [HPC Container](https://github.com/NVIDIA/hpc-container-maker) Maker-从高级Python配方生成Dockerfile，包括[@NVIDIA](https://github.com/nvidia)的高性能计算组件的构建块
- [IMG](https://github.com/genuinetools/img) -独立，守护进程少，非特权Dockerfile和OCI兼容容器由图像生成器[@genuinetools](https://github.com/genuinetools)
- [kaniko-](https://github.com/GoogleContainerTools/kaniko)在Kubernetes中构建容器映像 通过[@GoogleContainerTools](https://github.com/GoogleContainerTools)
- [makisu](https://github.com/uber/makisu) -Uber针对Mesos和Kubernetes的快速灵活的非特权图像生成器，具有分布式缓存支持。通过[@uber](https://github.com/uber)
- [MicroBadger-](https://microbadger.com/)分析图像的内容并添加元数据标签
- [packer](https://www.packer.io/docs/builders/docker) -Hashicorp工具，用于构建机器映像，包括与配置管理工具（如chef，puppet，ansible）集成的docker映像
- [portainer](https://github.com/duedil-ltd/portainer) -通过建立多克图像的Apache Mesos框架[@ duedil-LTD](https://github.com/duedil-ltd)
- [生产就绪型Python容器 💲](https://pythonspeed.com/products/pythoncontainer/) -用于为Python应用程序创建生产就绪的Docker映像的模板。
- [runlike-](https://github.com/lavie/runlike)`docker run`通过[@lavie](https://github.com/lavie)从运行的容器生成命令和选项
- [瘦鲸](https://github.com/djosephsen/skinnywhale) 💀 -Skinnywhale帮助您制作更小（以兆字节为单位）的Docker容器。
- [Smith](https://github.com/oracle/smith) -Micocontainer Builder，可以在构建映像后执行多阶段构建[Oracle](https://github.com/oracle)
- [捕鲸船](https://github.com/P3GLEG/Whaler)-计划通过反向泊坞窗图像转换成Dockerfiles [@ P3GLEG](https://github.com/P3GLEG/)。
- [鲸鱼](https://github.com/Gueils/whales)-@icalialabs自动对您的应用程序进行[泊坞](https://github.com/IcaliaLabs)工具的工具。

### Docker文件

- [chaperone-docker-](https://github.com/garywiz/chaperone-docker)使用Chaperone流程管理器的一组图像，包括精益Alpine图像，LAMP，LEMP和准基本套件。
- [Dockerfile Generator](https://github.com/ozankasikci/dockerfile-generator) `dfg`既是Go库又是可执行文件，它使用各种输入通道生成有效的Dockerfile。
- [Dockerfile生成器](https://jrruethe.github.io/blog/2015/09/20/dockerfile-generator/)
- [Dockerfile项目](https://dockerfile.github.io/)-受信任的自动化Docker构建。Dockerfile Project为可在Docker容器上运行的各种流行的开源软件服务维护Dockerfile的中央存储库。
- [Dockershelf-](https://github.com/Dockershelf/dockershelf)一个用作通用，高效且苗条的[Docker](https://github.com/Dockershelf/dockershelf)配方的收集器的存储库。图像每天都会通过Travis cron作业进行更新，测试和发布。由[@CollageLabs](https://github.com/CollageLabs)维护。
- [码头](https://github.com/MeneDev/dockmoor) 🚧-管理Docker映像参考，并帮助使用Docker创建可复制的构建。通过[@MeneDev](https://github.com/MeneDev)
- [Vektorcloud-](https://github.com/vektorcloud)最少的基于阿尔卑斯的Docker映像的集合

范例：

- [@阿伦·古普塔](https://github.com/arun-gupta/docker-images)
- [@ awesome-startup](https://github.com/awesome-startup/docker-compose)
- [@crosbymichael](https://github.com/crosbymichael/Dockerfiles)
- [@jessfraz](https://github.com/jessfraz/dockerfiles)
- [@komljen](https://github.com/komljen/dockerfile-examples)
- [@kstaken](https://github.com/kstaken/dockerfile-examples)
- [@ondrejmo](https://github.com/ondrejmo/Dockerfiles)
- [@pandrew](https://gitlab.com/pandrew/dockerfiles)
- [@vimagick](https://github.com/vimagick/dockerfiles)

### 林特

- [docker-image-size-](https://github.com/wemake-services/docker-image-size-limit) limit-一种监视docker映像大小的工具。
- [Dockerfile Linter操作](https://github.com/buddy-works/dockerfile-linter)-通过[Linter](https://github.com/buddy-works/dockerfile-linter)，您可以验证Dockerfile语法，以确保其遵循构建高效Docker映像的最佳实践。
- [码头](https://github.com/jessfraz/dockfmt) 🚧- Dockerfile格式化器和解析器通过[@jessfraz](https://github.com/jessfraz)
- [FROM：](https://github.com/replicatedhq/dockerfilelint) latest-@replicatedhq的自以为是的Dockerfile [linter](https://github.com/replicatedhq)
- [Hadolint-](https://github.com/hadolint/hadolint)一个Dockerfile Linter，用于检查最佳实践，常见错误，并且还可以清除`RUN`指令中编写的所有bash ；通过[@lukasmartinelli](https://github.com/lukasmartinelli)
- [鲸鱼棉短绒](https://github.com/jeromepin/whale-linter)-一个简单的小Dockerfile棉短绒写在Python3 +不通过依赖[@jeromepin](https://github.com/jeromepin)

### 元数据

- [opencontainer-](https://github.com/opencontainers/image-spec/blob/master/annotations.md)由OCI Image Spec定义的Docker标签的约定和共享名称空间。

### 登记处

安全地存储您的Docker映像的服务。

- [Amazon EC2容器注册表 💲](https://aws.amazon.com/ecr/) -Amazon EC2容器注册表（ECR）是完全托管的Docker容器注册表，使开发人员可以轻松存储，管理和部署Docker容器映像。
- [Azure容器注册表 💲](https://azure.microsoft.com/en-us/services/container-registry/) -将Docker私有注册表作为一流的Azure资源进行管理
- [CargoOS-](https://github.com/RedCoolBeans/cargos-buildroot)在裸机或云上运行Docker引擎的裸机必备操作系统。通过[@RedCoolBeans](https://github.com/RedCoolBeans)
- [云史密斯 💲](https://cloudsmith.com/docker-registry/)-全面管理的软件包管理SaaS，对公共和私有Docker注册管理机构（以及许多其他服务，包括Kubernetes生态系统的Helm图表）提供一流的支持。具有慷慨的免费层，并且对于开源也完全免费。
- [循环 💲](https://cycle.io/) -裸金属容器托管。
- [cleanreg-](https://github.com/hcguersoy/cleanreg)一个小工具，用于从实现API v2的Docker注册表中删除映像清单，并通过[@hcguersoy将其清单](https://github.com/hcguersoy)引用给GC
- [距离 💲](https://www.dist.cloud/product/container-registry/) -基于私有云的Docker容器注册表
- Docker Inc.提供的Docker [Hub](https://hub.docker.com/)。
- [Docker Registry](https://github.com/docker/distribution) v2-用于打包，运送，存储和交付内容的Docker工具集
- [文案](https://github.com/netvarun/docket)-自定义码头工人的注册表，通过允许快如闪电的展开时通过BitTorrent的[@netvarun](https://github.com/netvarun/)
- [GCE容器注册 💲](https://cloud.google.com/container-registry/) Google Cloud Platform上的快速私有Docker映像存储
- [GitLab容器注册表](https://docs.gitlab.com/ce/user/project/container_registry.html)-专注于在GitLab CI中使用它的存储库
- [Harbor](https://github.com/goharbor/harbor)一个可存储，签名和扫描内容的开源可信云本机注册表项目。支持复制，用户管理，访问控制和活动审核。由[CNCF](https://github.com/veggiemonk/awesome-docker/blob/master/Sandbox)以前是[VMWare](https://github.com/vmware)
- [JFrog工艺品厂 💲](https://jfrog.com/artifactory/) -Artifact Repository Manager，也可以用作私有Docker Registry
- [Kraken](https://github.com/uber/kraken) -Uber的高度可扩展P2P docker注册表，能够在几秒钟内分发TB的数据。
- [Portus酒店](https://github.com/SUSE/Portus)-授权服务和前端的码头工人注册表（V2）由[@SUSE](https://github.com/SUSE)
- [私人Docker注册表 💲](https://private-docker-registry.com/) -专用的Conainer Registry Service，具有无限的私有存储库，用户，团队，名称空间以及企业级身份验证LDAP / AD / OAuth / SAML。
- [码头 💲](https://quay.io/) （CoreOS的一部分）-私有Docker存储库的安全托管
- [Rescoyl](https://github.com/noteed/rescoyl) -私人码头工人注册表（自由和开放源码）由[@noteed](https://github.com/noteed)
- [Sonatype Nexus-](https://www.sonatype.com/nexus/repository-oss)具有通用支持的存储库，也适用于Docker映像
- [TreeScale-](https://github.com/treescale)构建和分发基于容器的应用程序。由[@tigranbs](https://github.com/tigranbs)

## 使用Docker开发

### API客户端

- [亚哈](https://github.com/instacart/ahab)-泊坞窗事件通过使用Python处理[@instacart](https://github.com/instacart)
- [clj-docker-client](https://github.com/lispyclouds/clj-docker-client) 🚧-Docker远程API的惯用Clojure客户端。通过[@lispyclouds](https://github.com/lispyclouds)
- [用于JVM的Docker客户端-用于JVM](https://github.com/gesellix/docker-client)的Docker远程api客户端库，由[@gesellix](https://github.com/gesellix)用Groovy[编写](https://github.com/gesellix)
- [Docker客户端TypeScript-](https://gitlab.com/masaeedu/docker-client)用于JavaScript的Docker API客户端，由Moby存储库中的Swagger API定义自动生成。通过[@masaeedu](https://github.com/masaeedu)
- [码头客户](https://github.com/spotify/docker-client) 💀-Docker远程API的Java客户端。通过[@spotify](https://github.com/spotify)
- [docker-it-scala-Scala的](https://github.com/whisklabs/docker-it-scala)Docker集成测试套件（[@whisklabs）](https://github.com/whisklabs)
- [docker-java-api](https://github.com/amihaiemil/docker-java-api) -Docker API的轻量级，真正面向对象的Java客户端。通过[@amihaiemil](https://github.com/amihaiemil)
- [docker-maven- ](https://github.com/fabric8io/docker-maven-plugin)[plugin-一个](https://github.com/fabric8io)由[@ fabric8io](https://github.com/fabric8io)运行和创建Docker映像的Maven插件
- [Docker-PowerShell-](https://github.com/Microsoft/Docker-PowerShell)用于Docker的PowerShell模块
- [Docker.DotNet](https://github.com/Microsoft/Docker.DotNet) -用于由远程多克尔API C＃/ NET HTTP客户端[@ahmetalpbalkan](https://github.com/veggiemonk/awesome-docker/blob/master/ahmetalpbalkan)
- [Docker.Registry.DotNet-.NET](https://github.com/ChangemakerStudios/Docker.Registry.DotNet)（C＃）客户端库，用于与Docker Registry API（v2）[@rquackenbush进行交互](https://github.com/rquackenbush)
- [dockerfile-maven-](https://github.com/spotify/dockerfile-maven)一个通过[@spotify](https://github.com/spotify)构建和推送Docker映像的Maven插件
- [dockerode](https://github.com/apocas/dockerode) -泊坞窗远程API Node.js的模块通过[@apocas](https://github.com/apocas)
- [DoMonit-](https://github.com/eon01/DoMonit)用于Docker API的简单Docker监控包装器
- [去-dockerclient](https://github.com/fsouza/go-dockerclient/) -围棋HTTP客户端通过远程多克尔API [@fsouza](https://github.com/fsouza/)
- [Gradle Docker插件](https://github.com/gesellix/gradle-docker-plugin)- [@gesellix的](https://github.com/gesellix)Gradle Docker远程api插件
- [libcompose-](https://github.com/docker/libcompose)用于Docker Compose的Go库
- [Portainer堆栈工具](https://github.com/greenled/portainer-stack-utils) 🚧-Bash脚本，用于从docker-compose yaml文件中的Portainer实例中部署/更新/取消部署Docker堆栈。通过[@greenled](https://github.com/greenled)。
- [sbt-docker-](https://github.com/Tapad/sbt-docker-compose) compose-通过[@kurtkopchik](https://github.com/kurtkopchik/)将Docker Compose功能集成到[sbt中](https://github.com/kurtkopchik/)
- [sbt-](https://github.com/marcuslonnberg/sbt-docker) docker- [@marcuslonnberg](https://github.com/marcuslonnberg)直接从sbt创建Docker映像

### CI / CD

- [伙伴 💲](https://buddy.works/) -最好的Git，构建和部署工具组合成一个强大的工具，为我们的开发增添了力量。
- [船长](https://github.com/harbur/captain)-将您的Git工作流程转换为Docker容器，以准备通过[@harbur](https://github.com/harbur)进行持续交付。
- [旋风](https://github.com/caicloud/cyclone)-功能强大的工作流引擎，并通过与本地Kubernetes资源实现年底到终端的解决方案，管道[@caicloud](https://github.com/caicloud)。
- [Diun-](https://github.com/crazy-max/diun)通过[@ crazy-max](https://github.com/veggiemonk/awesome-docker/blob/master/crazy-max)在Docker注册表上更新映像或存储库时接收通知。
- [适用于Jenkins的Docker插件-Docker插件](https://github.com/jenkinsci/docker-plugin/)的目的是能够使用[Docker](https://github.com/jenkinsci/docker-plugin/)主机动态预配一个从属服务器，运行单个构建，然后拆除该从属服务器。
- [Dockupdater-](https://github.com/dockupdater/dockupdater)自动使您的[Docker](https://github.com/dockupdater/dockupdater)服务和[Docker](https://github.com/dockupdater/dockupdater)容器保持最新
- [无人机](https://github.com/drone/drone)-建立在Docker上并使用YAML文件配置的持续集成服务器。
- [GitLab运行程序](https://gitlab.com/gitlab-org/gitlab-runner)-GitLab已集成CI，可以使用GitLab运行程序测试，构建和部署您的代码。
- [GOCD-Docker](https://github.com/gocd/gocd-docker) 💀 -在Docker容器中转到服务器和代理进行配置。
- 微服务[持续部署](https://github.com/francescou/docker-continuous-deployment)-微服务应用程序的持续部署。
- [亩](https://github.com/stelligent/mu)-通过AWS CodePipeline，CodeBuild和ECS工具的您的容器应用程序配置CI / CD [@Stelligent](https://github.com/stelligent)
- [衔尾蛇](https://github.com/pyouroboros/ouroboros) 💀 -通过通知自动更新正在运行的Docker容器
- [Popper](https://github.com/systemslab/popper) -Github操作工作流（HCL语法）执行引擎。
- [螺丝刀 💲](https://screwdriver.cd/) -专为持续交付而设计的Yahoo OpenSource构建平台。
- [船长](https://github.com/Stratoscale/skipper)-通过[@Stratoscale](https://github.com/Stratoscale)轻松地将您的Git存储库[泊坞窗](https://github.com/Stratoscale)
- [SwarmCI-](https://github.com/ghostsquad/swarmci)在Docker Swarm中创建一个分布式的隔离任务管道。
- [守望台](https://github.com/containrrr/watchtower)-自动更新正在运行的Docker容器

### 开发环境

- [batect](https://github.com/batect/batect) -构建和测试环境为代码的工具：Dockerised构建和测试环境中容易被制成[@charleskorn](https://github.com/charleskorn)
- [Binci-](https://github.com/binci/binci)容器化您的开发工作流程。（以前由[@TechnologyAdvice](https://github.com/TechnologyAdvice)开发的[DevLab](https://github.com/TechnologyAdvice)）
- [Boot2Docker-](https://github.com/boot2docker/boot2docker)适用于OSX和Windows的Docker
- [construi](https://github.com/lstephen/construi) -运行你的构建中一个码头工人通过定义的环境[@lstephen](https://github.com/lstephen)
- [Crashcart-将](https://github.com/oracle/crashcart)Linux二进制文件侧载到正在运行的容器中，以通过[@Oracle](https://github.com/oracle)进行故障排除
- [dde](https://github.com/whatwedo/dde) 🚧-基于Docker的本地开发环境工具集。通过[@whatwedo](https://github.com/whatwedo)
- [Devstep](https://github.com/fgrehm/devstep) 💀-由Docker驱动的开发环境和[@fgrehm的](https://github.com/fgrehm)buildpack
- [帆船](https://github.com/codekitchen/dinghy)-一种替代方式使用泊坞窗机在VirtualBox中，VMware的，xhyve或相似之处使用泊坞窗上的Mac OS X
- [DIP](https://github.com/bibendi/dip) -CLI实用程序，用于直接配置和与docker-compose配置的应用程序进行交互。通过[@bibendi](https://github.com/bibendi)
- [德力特](https://github.com/nlf/dlite) 💀-在OSX上使用Docker的最简单方法，无需VM。由[@nlf](https://github.com/nlf)
- [dobi-](https://github.com/dnephin/dobi)用于Docker应用程序的构建自动化工具。通过[@dnephin](https://github.com/dnephin)
- [DockerBuildManagement](https://github.com/DIPSAS/DockerBuildManagement) -Build Management是一个Python应用程序，与pip一起安装。该应用程序通过配置一个描述如何构建，测试，运行或发布容器化解决方案的yaml文件，使基于Docker的构建系统管理变得容易。
- [Docker Missing Tools-](https://github.com/nandoquintana/docker-missing-tools)一组bash命令，用于简化典型的docker dev-ops。在代码存储库中创建典型的辅助脚本（如“ build.sh”和“ deploy.sh”）的替代方法。通过[@NandoQuintana](https://github.com/nandoquintana)。
- [Docker OSX开发](https://github.com/brikis98/docker-osx-dev) 💀- [@ brikis98](https://github.com/brikis98)在OS X上使用Docker生产的开发环境
- [Docker-](https://github.com/Ph3nol/Docker-Arch) Arch-从1个简单的YAML文件生成Web / CLI项目Dockerized开发环境。通过[@ Ph3nol](https://github.com/ph3nol)
- [Docker- ](https://github.com/EugenMayer/docker-sync)[sync-](https://github.com/EugenMayer/docker-sync/wiki/4.-Performance)使用Docker在Mac OS X / Windows和Linux上进行开发时，与容器共享代码时，可[大大](https://github.com/EugenMayer/docker-sync/wiki/4.-Performance)提高性能（[50-70x](https://github.com/EugenMayer/docker-sync/wiki/4.-Performance)）。通过[@EugenMayer](https://github.com/EugenMayer)
- docker [-](https://github.com/shyiko/docker-vm) vm-@shyiko替代boot2docker（由Vagrant支持）的简单透明的替代[方法](https://github.com/shyiko)
- [Dusty](https://github.com/gamechanger/dusty) -OS X上的托管Docker开发环境
- [Eclipse](https://github.com/eclipse/che) Che-具有Docker运行时，云IDE，下一代Eclipse IDE的开发人员工作区服务器
- [EnvCLI-](https://github.com/EnvCLI/EnvCLI)用特定于项目的[Docker容器](https://github.com/EnvCLI/EnvCLI)替换本地安装的Node，Go，...。通过[@EnvCLI](https://github.com/EnvCLI)
- [footloose-](https://github.com/weaveworks/footloose)旋转看起来像虚拟机的容器- [@dlespiau](https://github.com/dlespiau)
- [forward2docker](https://github.com/bsideup/forward2docker) 💀-通过[@bsideup将](https://github.com/bsideup)来自本地主机的端口自动转发到在boot2docker虚拟机中运行的Docker容器的端口的实用程序
- [Gebug-](https://github.com/moshebe/gebug)通过无缝启用Debugger和Hot-Reload功能，使Dockerized Go应用程序的调试变得非常容易的工具。
- [Lando](https://github.com/lando/lando) -Lando适用于希望快速指定并轻松开发项目所需的服务和工具的开发人员。通过[串联](https://thinktandem.io/)
- [Vagga](https://github.com/tailhook/vagga) -Vagga是一个没有守护程序的容器化工具。这是一个受Vagrant和Docker启发的全用户空间容器引擎，专用于[@tailhook](https://github.com/tailhook/)开发环境
- [Zsh-in-Docker-](https://github.com/deluan/zsh-in-docker)用一行代码在Docker容器中安装Zsh，Oh-My-Zsh和插件！由[Deluan](https://www.deluan.com/)

### 垃圾收集

- [caduc-](https://github.com/tjamet/caduc)一个[docker](https://github.com/tjamet/caduc)垃圾收集器清理您近期未使用的东西
- [Docker ](https://github.com/ZZROTDesign/docker-clean)[Clean-使用@zzrotdesign](https://github.com/ZZROTDesign)清理Docker容器，图像和卷的[脚本](https://github.com/ZZROTDesign)
- [Docker清理](https://github.com/meltwater/docker-cleanup) 💀- [@meltwater](https://github.com/meltwater)自动清理Docker映像，容器和卷
- [docker-custodian-](https://github.com/Yelp/docker-custodian)保持docker主机整洁。通过[@Yelp](https://github.com/Yelp)
- [搬运工-garby](https://github.com/konstruktoid/docker-garby) -由码头工人垃圾收集脚本[@konstruktoid](https://github.com/konstruktoid)。
- [码头工人](https://github.com/spotify/docker-gc) 💀-一项cron作业，将通过[@spotify](https://github.com/spotify)删除旧的已停止容器和未使用的图像
- [docker_gc-](https://github.com/pdacity/docker_gc)用于自动删除未使用的Docker Swarm对象的图像。也像[@pdacity的](https://github.com/pdacity)Docker服务[一样工作](https://github.com/pdacity)
- [牛rd](https://github.com/rancher/sherdock) 💀-通过[@rancher](https://github.com/rancher)基于正则表达式的图像的自动GC

### 无服务器

- [安培](https://github.com/appcelerator-archive/amp) 💀-用于Docker的开源统一CaaS / FaaS平台，包括电池。通过[@Appcelerator](https://github.com/appcelerator-archive)
- [Apache OpenWhisk-](https://github.com/apache/openwhisk)一种无服务器的开源云平台，可以执行各种功能以响应各种规模的事件。通过[@apache](https://github.com/apache)
- [Docker-](https://github.com/lambci/docker-lambda) Lambda-复制实时AWS Lambda环境的Docker映像和测试运行器。通过[@ lamb-ci](https://github.com/lambci)
- [Funker-](https://github.com/bfirsh/funker-example-voting-app)充当Docker容器示例投票应用程序。通过[@bfirsh](https://github.com/bfirsh)
- [IronFunctions-](https://github.com/iron-io/functions)无服务器微服务平台FaaS（功能即服务），该平台使用Docker容器运行任何语言或AWS Lambda函数
- [OpenFaaS](https://github.com/openfaas/faas) -Docker和Kubernetes的完整无服务器功能框架。通过[OpenFaaS](https://github.com/openfaas)
- [SCAR-](https://github.com/grycap/scar)无服务器容器感知体系结构（SCAR）是一种无服务器框架，允许[@grycap](https://github.com/grycap)在无服务器环境（例如Lambda）中轻松部署和执行容器（例如Docker）

### 测试中

- [容器结构测试](https://github.com/GoogleContainerTools/container-structure-test)-一种通过检查命令输出或文件系统内容来验证映像结构的框架。通过[@GoogleContainerTools](https://github.com/GoogleContainerTools)
- [dgoss-](https://github.com/aelsabbahy/goss/tree/master/extras/dgoss)一种基于YAML的快速工具，用于验证[Docker](https://github.com/aelsabbahy/goss/tree/master/extras/dgoss)容器。
- [DockerSpec-](https://github.com/zuazo/dockerspec)一个小的Ruby Gem，可以轻松地对Dockerfiles或Docker映像运行RSpec和Serverspec，Infrataster和Capybara测试。通过[@zuazo](https://github.com/zuazo)
- [码头单位](https://github.com/dockunit/platform) 💀-基于Docker的集成测试。一个简单的基于Node的实用程序，用于运行基于Docker的单元测试。通过[@dockunit](https://github.com/dockunit)
- [InSpec](https://github.com/inspec/inspec) -InSpec是用于基础结构的开放源代码测试框架，具有人类和机器可读的语言，用于指定合规性，安全性和策略要求。通过[@chef](https://github.com/chef)
- [Pull Dog-](https://github.com/apps/pull-dog)一个GitHub应用，可从docker-compose文件自动为您的请求创建基于Docker的测试环境。不是开源的。
- [Pumba](https://github.com/alexei-led/pumba) -Docker的混沌测试工具。可以部署在kubernetes和CoreOS集群上。由[@ alexei-led](https://github.com/alexei-led)

### 包装纸

- [Ansible-](https://docs.ansible.com/ansible/latest/collections/community/general/docker_container_module.html)管理Docker容器的生命周期 由RedHat
- [AZK](https://github.com/azukiapp/azk) -通过在本地机器上协调发展环境[@azukiapp](https://github.com/azukiapp)
- [白鲸](https://github.com/cortexmedia/Beluga) 💀-CLI将Docker容器部署在单个服务器或少量服务器上。通过[@cortextmedia](https://github.com/cortexmedia)
- [dexec-](https://github.com/docker-exec/dexec)用Go编写的命令行界面，用于使用Docker Exec映像运行代码。
- [dockerized-](https://github.com/benzaita/dockerized-cli)在容器中无缝执行命令。
- [Dray-](https://github.com/CenturyLinkLabs/dray)一种由[@CenturyLinkLabs](https://github.com/CenturyLinkLabs)管理基于容器的工作流执行的引擎
- [福谷](https://github.com/mattes/fugu) 💀-无需[@mattes](https://github.com/mattes)编排的Docker运行包装器
- [Shutit-@ianmiell提供的](https://github.com/ianmiell/shutit)用于构建和维护复杂Docker部署的[工具](https://github.com/ianmiell)
- [子用户](https://github.com/subuser-security/subuser)-轻松安全地在Docker中运行图形桌面应用程序
- [TADS样板](https://github.com/Thomvaill/tads-boilerplate)-Ansible和Terraform的功能+ Docker Swarm的简单性=基础架构作为代码和DevOps最佳实践。通过[@Thomvaill](https://github.com/Thomvaill)
- [Turbo-](https://github.com/ramitsurana/turbo)适用于docker的简单而强大的实用程序。通过[@ramitsurana](https://github.com/ramitsurana)
- [udocker-](https://github.com/indigo-dc/udocker)一种通过[@ inidigo-dc](https://github.com/indigo-dc)在没有root特权的情况下在批处理或交互式系统中执行简单[docker](https://github.com/indigo-dc/udocker)容器的工具
- [流浪-泊坞窗提供商](https://www.vagrantup.com/docs/providers/docker/basics.html)-良好的出发点是[无业游民，码头工人，例如](https://github.com/bubenkoff/vagrant-docker-example)通过[@bubenkoff](https://github.com/bubenkoff)

## 基于Docker的服务（💲）

### CI服务

- [CircleCI](https://circleci.com/) 💲 -从构建环境中推送或拉取Docker映像，或者直接在CircleCI上构建和运行容器。
- [代码刷新](https://codefresh.io/) 💲-构建，测试和共享Docker应用程序所需的一切。提供自动化的端到端测试。
- [代码船](https://cms.codeship.com/features/pro) 💲 -使用已建立的Docker工作流程，同时使用我们专用于速度和安全性的托管平台来自动化您的测试和部署任务。
- [大堂CI](https://concourse-ci.org/) 💲 -针对开发人员和DevOps团队面向管道的CI SaaS平台。
- [信号量CI](https://semaphoreci.com/) 💲 —高性能的云解决方案，可轻松构建，测试和运送容器以进行生产。
- [可运送](https://app.shippable.com/) 💲 -为开发人员和DevOps团队使用的SaaS平台，可大大减少构建，测试和部署代码到生产所需的时间。
- [TravisCI](https://travis-ci.org/) 💲 -一个免费的github项目，为开发人员和Devops提供持续集成的Saas平台。

### a

- [亚马逊ECS](https://aws.amazon.com/ecs/) 💲 -EC2上的一种管理服务，支持Docker容器。
- [Azure AKS](https://azure.microsoft.com/en-us/services/kubernetes-service/) 💲-简化Kubernetes的管理，部署和操作。使用完全托管的Kubernetes容器编排服务。
- [云66](https://www.cloud66.com/) 💲 -全栈托管容器管理即服务
- [Codenvy](https://codenvy.com/) 💲 -开发团队的一键式Docker环境和云工作区
- [Dockhero](https://dockhero.io/) 💲-Dockhero是Heroku插件，可将Docker映像转换为附加到Heroku应用程序的微服务。目前处于测试阶段。
- [巨群](https://www.giantswarm.io/) 💲-简单的微服务基础架构。在几秒钟内部署容器。
- [Google容器引擎](https://cloud.google.com/kubernetes-engine/docs/) 💲-由[Kubernetes](https://kubernetes.io/)支持的Google Cloud Computing上的Docker容器。
- [杰弹性云](https://jelastic.cloud/) 💲-具有垂直和水平自动缩放功能的“易于使用”容器托管平台。全球超过50多家托管服务提供商可用。
- [Mesosphere DC / OS平台](https://d2iq.com/products/dcos) 💲- [@mesosphere](https://d2iq.com/)在Apache Mesos上构建的用于数据和容器的集成平台
- [OpenShift专用](https://www.openshift.com/products/dedicated/) 💲-一个托管的[OpenShift](https://www.okd.io/)集群，用于运行由Red Hat管理的Docker容器。
- [Sloppy.io](https://sloppy.io/en/) 💲 -集装箱部署和托管的一站式解决方案-在德国制造和托管
- [特里顿](https://www.joyent.com/) 💲 -Joyent的弹性容器原生基础架构。

### 监控服务

- [AppDynamics](https://www.appdynamics.com/community/exchange/extension/docker-monitoring-extension/) 💲 -AppDynamics可为企业提供有关应用程序性能，用户性能和业务性能的实时洞察，从而使他们能够在日益复杂，软件驱动的世界中更快地移动。
- [Axibase时间序列数据库](https://axibase.com/products/axibase-time-series-database/writing-data/docker-cadvisor/) 💲-长期保留Docker的容器统计信息和内置仪表板。使用本机Google cAdvisor存储驱动程序收集。
- [Broadcom Docker监控](https://www.broadcom.com/info/aiops/docker-monitoring) 💲-Broadcom的敏捷运营解决方案提供了现代Docker监控业务，企业需要加速和优化微服务以及运行它们的动态Docker环境的性能。监视Docker环境及其内部运行的应用程序。（以前的CA Technologies）
- [使用Splunk收集Docker日志和统计信息](https://www.splunk.com/en_us/blog/cloud/collecting-docker-logs-and-stats-with-splunk.html)
- [数据狗](https://www.datadoghq.com/) 💲-Datadog是针对大型云环境的全栈监视服务，可聚合来自服务器，数据库和应用程序的指标/事件。它包括对Docker，Kubernetes和Mesos的支持。
- [普罗米修斯](https://prometheus.io/) 💲 -开源服务监控系统和时间序列数据库
- [Site24x7](https://www.site24x7.com/docker-monitoring.html) 💲 -用于DevOps和IT的Docker监控是SaaS按主机付费的模型
- [Docker的SPM](https://github.com/sematext/sematext-agent-docker) 💲-监视主机和容器指标，Docker事件和日志。自动日志解析器。异常检测和警报，以度量和日志。[@sematext](https://github.com/sematext)
- [Sysdig监控器](https://sysdig.com/products/monitor/) 💲-Sysdig Monitor既可以用作软件，也可以用作SaaS服务，以使用系统调用来监视，警报容器并对其进行故障排除。它具有适用于Docker和Kubernetes的特定于容器的功能。

# 有用的资源

- **[有价值的Docker链接](http://nane.kratzke.pages.mylab.th-luebeck.de/about/blog/2014/08/24/valuable-docker-links/)**有关docker的高质量文章！**必看**
- [使用Visual Studio Code成为Docker高级用户](https://www.thebyte.io/become-docker-power-user-with-vs-code)-💲 培训课程，可帮助您使用Visual Studio Code成为Docker Power用户
- [云原生景观](https://github.com/cncf/landscape)
- [Docker周刊](https://www.docker.com/blog/docker-weekly-archives/)巨大资源
- [编程社区策划的资源以学习Docker](https://hackr.io/tutorials/learn-docker)
- [Docker in Action，第二版](https://www.manning.com/books/docker-in-action-second-edition)
- [Hashnode上的Docker社区](https://hashnode.com/n/docker)
- [Docker实践第二版](https://www.manning.com/books/docker-in-practice-second-edition)
- [Docker开发者书签](https://www.bookmarks.dev/search?q=docker)-使用标签[docker](https://www.bookmarks.dev/tagged/docker)
- [适用于Python的Docker打包指南](https://pythonspeed.com/docker/)-一系列有关适用于Python的Docker打包细节的详细文章。
- [在一个月的午餐中学习Docker](https://www.manning.com/books/learn-docker-in-a-month-of-lunches)

## 很棒的清单

- [很棒的CI / CD-](https://github.com/cicdops/awesome-ciandcd)不特定于docker但相关。
- [很棒的Kubernetes](https://github.com/ramitsurana/awesome-kubernetes)（[@ramitsurana）](https://github.com/ramitsurana)
- [很棒的Linux](https://github.com/Friz-zy/awesome-linux-containers)容器，比[@ rez-zy](https://github.com/Friz-zy)通过此仓库更全面地介绍了容器。
- [很棒的自托管](https://github.com/awesome-selfhosted/awesome-selfhosted)的免费软件网络服务和Web应用程序列表，可以通过以经典方式运行（在本地设置本地Web服务器并从此处运行应用程序）或在Docker容器中本地运行。通过[@Kickball](https://github.com/Kickball)
- [真棒系统管理员](https://github.com/n1trux/awesome-sysadmin)通过[@ n1trux](https://github.com/n1trux)
- [ToolsOfTheTrade @cjbarber](https://github.com/cjbarber/ToolsOfTheTrade)提供的SaaS和[本地](https://github.com/cjbarber)应用程序[列表](https://github.com/cjbarber)

## 演示与范例

- [Webstack-micro](https://github.com/ferbs/webstack-micro)演示Web应用程序，展示了如何使用Docker Compose来将API网关，集中式身份验证，后台工作程序和WebSockets设置为容器化服务。
- [用于前端Web开发的带注释的Docker Config](https://nystudio107.com/blog/an-annotated-docker-config-for-frontend-web-development)使用Docker的本地开发环境可让您将项目所需的devop打包为config，从而使入职过程变得顺畅。

## 好提示

- 通过[@rochacbruno处理docker ](https://github.com/rochacbruno)[-compose中](http://brunorocha.org/python/dealing-with-linked-containers-dependency-in-docker-compose.html)的[链接容器依赖性](http://brunorocha.org/python/dealing-with-linked-containers-dependency-in-docker-compose.html)
- [码头工人注意事项](http://docker-saigon.github.io/post/Docker-Caveats/)是什么，你应该知道跑码头工人在生产（书面2016年4月11日）**MUST SEE**
- [Docker容器在桌面上](https://blog.jessfraz.com/post/docker-containers-on-the-desktop/)-的**最有趣的方式**来了解由搬运工人[@jessfraz](https://github.com/jessfraz)谁也做了[演示](https://www.youtube.com/watch?v=1qlLUf7KtAw)一下吧@ DockerCon 2015年
- [Docker与VM？结合两者实现云可移植性](https://www.flexera.com/blog/cloud/docker-vs-vms-combining-both-for-cloud-portability-nirvana/)
- [不要用锚，别名和扩充码头工人撰写的文件重复自己](https://medium.com/@kinghuang/docker-compose-anchors-aliases-extensions-a1e4105d70bd)通过[@King黄涌](https://github.com/kinghuang)
- [带有Docker](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)的[GUI应用程序](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)by [@fgrehm](https://github.com/fgrehm)

## Raspberry Pi和ARM

- [带有](https://blog.hypriot.com/)大量[爆炸性内容的Docker Pirates武装](https://blog.hypriot.com/)有关Raspberry Pi上用于SD卡的群集，群集，[docker和](https://blog.hypriot.com/)预安装映像的大量资源
- [三个步骤即可启动Docker并在RaspberryPi上运行](https://github.com/umiddelb/armhf/wiki/Get-Docker-up-and-running-on-the-RaspberryPi-(ARMv6)-in-three-steps)
- [git](https://www.balena.io/)利用git和Docker将Docker[容器推送到linux设备上](https://www.balena.io/)用于物联网的现代DevOps。
- [在armhf（ARMv7）设备上安装，运行和使用Docker](https://github.com/umiddelb/armhf/wiki/Installing,-running,-using-docker-on-armhf-(ARMv7)-devices)

## 安全

- [为Docker带来新的安全功能](https://opensource.com/business/14/9/security-for-docker)
- [CVE](https://github.com/tomwillfixit/alpine-cvecheck)通过[@tomwillfixit](https://twitter.com/tomwillfixit)[在Docker 17.05中使用多阶段构建扫描阿尔卑斯山图像](https://github.com/tomwillfixit/alpine-cvecheck)
- [Docker和SELinux](https://www.projectatomic.io/docs/docker-and-selinux/)
- [Docker安全部署指南](https://github.com/AonCyberLabs/Docker-Secure-Deployment-Guidelines)
- [Docker安全性-快速参考](https://binarymist.io/publication/docker-security/)
- [Docker安全备忘单](https://github.com/konstruktoid/Docker/blob/master/Security/CheatSheet.adoc)
- [Docker安全性：您的容器是否牢固地固定在船上？幻灯片分享](https://fr.slideshare.net/MichaelBoelen/docker-security-are-your-containers-tightly-secured-to-the-ship)
- [如何在官方Docker映像上处理CVE](https://github.com/docker-library/official-images/issues/1448)
- [Lynis是一个开源安全审核工具，包括Docker审核](https://cisofy.com/lynis/)
- [构建Docker映像的安全性最佳实践](https://linux-audit.com/tag/docker/)
- [Docker安全团队负责人（DiogoMónica）接受软件工程电台采访](https://www.se-radio.net/2017/05/se-radio-episode-290-diogo-monica-on-docker-security/)
- [十个Docker Image Security最佳实践备忘单](https://snyk.io/blog/10-docker-image-security-best-practices/)
- [十大最受欢迎的Docker映像每个都包含至少30个漏洞](https://snyk.io/blog/top-ten-most-popular-docker-images-each-contain-at-least-30-vulnerabilities/)
- [使用最新的安全性增强来调整Docker](https://opensource.com/business/15/3/docker-security-tuning)

## 影片

- [由Andrew“ Tianon” Page（InfoSiftr）为Docker贡献](https://www.youtube.com/watch?v=1jwo8-1HYYg)（34:31）
- [部署以及与码头工人，群，和Python的魔术一点点扩展应用](https://www.youtube.com/watch?v=GpHMTR7P2Ms)的（3时11分06秒）[@jpetazzo](https://github.com/jpetazzo)
- [Docker和SELinux，来自Red Hat的Daniel Walsh](https://www.youtube.com/watch?v=zWGFqMuEHdw)（40:23）
- [Docker课程](https://www.youtube.com/watch?v=UZpyvK6UGFo)（西班牙语）[@pablokbs](https://github.com/pablokbs)
- [Docker for Developers](https://www.youtube.com/watch?v=FdkNAjjO5yQ)（54:26）by [@jpetazzo](https://github.com/jpetazzo) <==不错的介绍，上下文，演示
- 巴黎Nakita Kejser在YouTube上[从零开始](https://www.youtube.com/playlist?list=PLLhEJK7fQIxD-btrjrqdEfQHbkZnQrmqE)（1:22:01）的[Docker](https://www.youtube.com/playlist?list=PLLhEJK7fQIxD-btrjrqdEfQHbkZnQrmqE)
- [Docker：如何使用自己的私有注册表](https://www.youtube.com/watch?v=CAewZCBT4PI)（15:01）
- [@jpetazzo](https://github.com/jpetazzo)[制作](https://www.youtube.com/watch?v=Glk5d5WP6MI)的[Docker](https://github.com/jpetazzo)（36:05）
- 通过LoginRadius在YouTube上将[Docker Primer转换为Docker Compose](https://www.youtube.com/watch?v=G-s2GXGAjTk)（1:56:45）
- Paris Nakita Kejser在YouTube上[从零开始](https://www.youtube.com/playlist?list=PLLhEJK7fQIxAz3d4Fj3edq7UcxEhdTCBm)（44:40）的[Docker Registry](https://www.youtube.com/playlist?list=PLLhEJK7fQIxAz3d4Fj3edq7UcxEhdTCBm)
- 巴黎Nakita Kejser在YouTube上[从零开始](https://www.youtube.com/playlist?list=PLLhEJK7fQIxAY4gZd1Wl-GsLvg-e9Ap1e)（1:41:28）的[Docker Swarm](https://www.youtube.com/playlist?list=PLLhEJK7fQIxAY4gZd1Wl-GsLvg-e9Ap1e)
- [使用插件扩展Docker](https://vimeo.com/110835013)（15:21）
- [从当地码头工人开发到生产部署](https://www.youtube.com/watch?v=7CZFpHUPqXw)由[@jpetazzo](https://github.com/jpetazzo) @ AWS重：2015年发明
- [带有Docker和EC2的不可变基础架构，作者Michael Bryzek（Gilt）](https://www.youtube.com/watch?v=GaHzdqFithc)（42:04）
- [简介泊坞窗和容器](https://www.youtube.com/watch?v=ZVaRK10HBjo)（3时09分00秒）由[@jpetazzo](https://github.com/jpetazzo)
- [登录Docker：您需要了解的内容](https://vimeo.com/123341629)（51:27）
- [Docker的性能分析](https://www.youtube.com/watch?v=6f2E6PKYb0w)-Jeremy [Eder](https://www.youtube.com/watch?v=6f2E6PKYb0w)（1:36:58）
- [Kubernetes](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615) Free Udacity课程[可扩展的微服务](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615)
- [容器状态：与CoreOS，VMware和Google的辩论](https://www.youtube.com/watch?v=IiITP3yIRd8)（27:38）

# 社区和聚会

## 巴西人

- [Slack上的Docker BR-](http://docker-br.herokuapp.com/)自动邀请网址
- [电报上的Docker BR](https://telegram.me/dockerbr)

## 中文

- [DockerOne](http://dockone.io/) Docker社区[@LiYingJie](http://dockone.io/people/李颖杰)

## 英语

- [Docker社区](https://www.docker.com/docker-community)
- [Docker活动](https://events.docker.com/)
- [Docker在线聚会](https://www.meetup.com/Docker-Online-Meetup/)
- [Docker Reddit社区](https://www.reddit.com/r/docker/)

## 俄语

- [Docker俄语社区](https://t.me/docker_ru)

## 西班牙文

- [Docker技巧](https://dockertips.com/)

## 随着时间的推移观星人

[![随着时间的推移观星人](Docker的技巧箱.assets/68747470733a2f2f7374617263686172742e63632f7665676769656d6f6e6b2f617765736f6d652d646f636b65722e737667)](https://starchart.cc/veggiemonk/awesome-docker)