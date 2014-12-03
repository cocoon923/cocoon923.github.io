---
layout: default
category : sharing
tags : [sharing, technology]
---

# 技术分享

---

## 概述

本文主要是一些工具、开源框架等相关的介绍、使用场景等。

每一章节都可以展开很多内容，本文仅做最基本的介绍，如果对于某些章节感兴趣，请回复我，然后根据需要，再整理更加详细的资料。

## 一、 工具篇

### 1. Markdown

Markdown是一种标记语言，通常为程序员群体使用。可以用于静态博客的编写，也常见于Github的README和Project site。
详细的使用可以参考[Markdown语法说明][markdown.1]。

**Markdown的优点：**

- 纯文本，所以兼容性极强，可以用所有文本编辑器打开。
- 让你专注于文字而不是排版。
- 格式转换方便，Markdown 的文本你可以轻松转换为 html、电子书等。
- Markdown 的标记语法有极好的可读性。

_注：本文的编写参考了[如何编写Markdown语法的邮件][markdown.2]，并选择了一个[在线编辑器][markdown.3]。_

[markdown.1]: http://www.markdown.cn/
[markdown.2]: http://www.zhihu.com/question/21742239
[markdown.3]: https://www.zybuluo.com/mdeditor


### 2. Jekyll

[Jekyll][jekyll.1]是一个静态站点生成器，它会根据网页源码生成静态文件。它提供了模板、变量、插件等功能，所以实际上可以用来编写整个网站。
如果以前你使用Wordpress写博客，Jekyll同样提供了方便的迁移方法，见[博客迁移][jekyll.2]。

**Jekyll有以下特点:**

- 完全免费开源，基于Ruby，效率很不错。
- 默认支持markdown语法，相比HTML更为简洁。
- 无需数据库，完全本地文件同步。
- Github支持Jekyll，可以免费获取个人博客空间。

[Octopress][jekyll.3]是Jekyll的简化版，比Jekyll更加容易上手。

还有一些常见的一些[博客程序][jekyll.4]。

[jekyll.1]: http://jekyllcn.com/
[jekyll.2]: http://jekyllcn.com/docs/migrations/
[jekyll.3]: http://octopress.org/
[jekyll.4]: http://www.zhihu.com/question/21981094


### 3. Emacs

[Emacs][emacs.1]是一个文本编辑器家族，具有强大的可扩展性，在程序员和其他以技术工作为主的计算机用户中广受欢迎。

一篇文章足矣，[一年成为Emacs高手(像神一样使用编辑器)][emacs.2]，文章中列出了很多资源。

[emacs.1]: http://www.gnu.org/software/emacs/
[emacs.2]: http://blog.csdn.net/redguardtoo/article/details/7222501


### 4. Github

> GitHub is the best place to share code with friends, co-workers, classmates, and complete strangers.
> Over seven million people use GitHub to build amazing things together.

以上关于Github的介绍引自其[官网][github.1]。

正是Github，让社会化编程成为现实。[如何高效利用Github][github.2]一文谈论了GitHub的文化、技巧与影响。
_注：这篇博客的作者的其他博文也一样很精彩，推荐阅读。_

关于Git的使用推荐两个教程：

- [Git-简明指南][github.3]
- [Pro Git][github.4]

[github.1]: https://github.com
[github.2]: http://www.yangzhiping.com/tech/github.html
[github.3]: http://rogerdudler.github.io/git-guide/index.zh.html
[github.4]: http://git-scm.com/book/zh/v1


## 二、 框架篇

### 1. Maven

> Apache Maven is a software project management and comprehension tool.
> Based on the concept of a project object model (POM), Maven can manage a project's build,
> reporting and documentation from a central piece of information.

以上关于Maven的介绍引自其[官网][maven.1]。

推荐许晓斌（《Maven实战》作者）博客：

- [iteye][maven.2]博客已经不维护，但依然有很多值得看的文章
- [Juven Xu][maven.3]博客

_注：Maven官网、以上两个博客以及Maven实战这些资料已经足够Maven的入门。_
_如果需要了解更多，如Maven的原理、Plugin和Archetype的编写等。_
_这些主题，官方文档只是介绍了基本，因此需要自己去摸索，或者去[Stackoverflow][maven.4]等网站寻找资料。_

除了Maven，可能你还需要了解Maven私服，如：[Nexus][maven.5]等。


[maven.1]: http://maven.apache.org/
[maven.2]: http://juvenshun.iteye.com/
[maven.3]: http://www.juvenxu.com/
[maven.4]: http://stackoverflow.com/
[maven.5]: http://www.sonatype.com/nexus

### 2. Gradle

[Gradle][gradle.1] 是以 [Groovy][gradle.2] 语言为基础，面向Java应用为主。基于DSL（领域特定语言）语法的自动化构建工具。

Gradle可以很好的集成Ant和Maven。

[Gradle User Guide][gradle.3]是非常好的参考资料。
你可以通过[中文翻译版本][gradle.4]查看，当然翻译工作还在进行中，你可以在[Github][gradle.5]中Fork下来，并贡献你的翻译。

[gradle.1]: http://www.gradle.org/
[gradle.2]: http://groovy.codehaus.org/
[gradle.3]: http://www.gradle.org/docs/current/userguide/userguide.html
[gradle.4]: http://pkaq.github.io/gradledoc/docs/userguide/userguide.html
[gradle.5]: https://github.com/pkaq/gradledoc


### 3. Jenkins

[Jenkins][jenkins:1]是一个开源软件项目，旨在提供一个开放易用的软件平台，使持续集成变成可能。Jenkins的前身是[Hudson][jenkins:2]项目。

主要用于：

- 持续、自动地构建/测试软件项目，如CruiseControl与DamageControl。
- 监控一些定时执行

[jenkins:1]: http://jenkins-ci.org/
[jenkins:2]: http://hudson-ci.org/


### 4. Redis

[Redis][redis:1]是一个开源、支持网络、基于内存、键值对存储数据库，使用ANSI C编写。

关于使用：[Redis命令参考][redis:2]

Windows客户端：[Redis Desktop Manager][redis:3]

相信会用`java.util.Map`，都会觉得使用Redis很简单。
而Redis的关键应该是键值设计和内存优化，这一点经常被忽略。

**Redis应该有更好的用处，而不仅仅是做二级缓存。**

- [什么样的硬件设备在支撑 Stack Overflow？][redis:4]
- [成人网站YouPorn使用Redis之经验谈][redis:5]
- [Twitter 高并发高可用架构][redis:6]

Redis另一个值得学习的地方，即 **[源码][redis:7]**。
Redis的代码写的很整洁，并且代码量相对较小（4.5万行左右），大部分都是单线程的，依赖也很少。
所有的依赖都跟源代码放在一起了，这中做法让编译它变得非常简单：clone它的库，然后输入make即可。

[redis:1]: http://redis.io/
[redis:2]: http://redis.readthedocs.org/en/latest/index.html
[redis:3]: http://redisdesktop.com/
[redis:4]: http://blog.jobbole.com/61646/
[redis:5]: http://blog.jobbole.com/44629/
[redis:6]: http://blog.jobbole.com/44059/
[redis:7]: https://github.com/antirez/redis


### 5. NIO(MINA/Netty)

Java NIO(New IO)是一个可以替代标准Java IO API的IO API（从Java 1.4开始)，Java NIO提供了与标准IO不同的IO工作方式。

相关资料：

- [解读Java NIO技术][nio.1]
- [Java NIO 系列教程][nio.2]

[**Apache MINA**][nio.3](Multipurpose Infrastructure for Network Applications) 是 Apache 组织一个较新的项目，
它为开发高性能和高可用性的网络应用程序提供了非常便利的框架。

[**Netty**][nio.4]是一个高性能、异步事件驱动的NIO框架，它提供了对TCP、UDP和文件传输的支持，作为一个异步NIO框架，Netty的所有IO操作都是异步非阻塞的，
通过Future-Listener机制，用户可以方便的主动获取或者通过通知机制获得IO操作结果。

作为当前最流行的NIO框架，Netty在互联网领域、大数据分布式计算领域、游戏行业、通信行业等获得了广泛的应用，一些业界著名的开源组件也基于Netty的NIO框架构建。

推荐官网的[User Guide][nio.5]。

[nio.1]: http://developer.51cto.com/art/201112/307172.htm
[nio.2]: http://ifeve.com/java-nio-all/
[nio.3]: https://mina.apache.org/
[nio.4]: http://netty.io/
[nio.5]: http://netty.io/wiki/user-guide.html


### 6. Jetty

[Jetty][jetty.1] 是一个开源的servlet容器，它为基于Java的web容器，例如JSP和servlet提供运行环境。

推荐官方的[Documents][jetty.2]。

> 特性（引自官网）：
>
> - Full-featured and standards-based
> - Open source and commercially usable
> - Flexible and extensible
> - Small footprint
> - Embeddable
> - Asynchronous
> - Enterprise scalable
> - Dual licensed under Apache and Eclipse

[jetty.1]: http://eclipse.org/jetty/
[jetty.2]: http://www.eclipse.org/jetty/documentation/current/