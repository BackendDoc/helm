# helm

## 一、概述

作者：[jiker](https://jiker.dev)
公众号: 极客开发者
参考视频： [https://www.bilibili.com/video/BV12D4y1Y7Z7](https://www.bilibili.com/video/BV12D4y1Y7Z7)

## 二、学习基础

helm是一个kubernetes的包管理工具，类似于apt、yum等包管理工具，可以用来管理kubernetes的应用包，也可以用来管理kubernetes的配置文件。

在学习helm之前，我们需要先了解kubernetes的基本概念，包括pod、service、deployment、namespace等。为了方便实际操作，我们需要先安装一个kubernetes集群，可以参考我的另一篇文章[使用kubeadm安装kubernetes集群](https://jiker.dev/posts/kubernetes_basic_build-on-virtual-machine.html)。

## 三、文档目录

[01.chat介绍](./docs/helm_declaration.md)
[02.helm内置对象](./docs/helm_inner_object.md)
[03.helm常用命令和部署示例](./docs/helm_genral_command_and_deployment.md)
[04.helm内置函数](./docs/helm_inner_function.md)
[05.helm流程控制](./docs/helm_process_control.md)
