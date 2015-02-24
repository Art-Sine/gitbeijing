---
layout: book
title: 简介
---

# 简介

### 我和 git 的罗曼史

git 和 github 两个词初学者经常搞不清谁是谁？Git 是 ...

“I’m an egotistical bastard, and I name all my projects after myself.
First Linux, now git.” – Linus

Git is a 
- stupid content tracker
- directory content management system
- tree histroy store system
- a toolkit 

Git 是一个很傻瓜式的文件夹内容跟踪管理系统，版本历史存储系统，git 有很多子命令的命令行工具箱。

Global Information Tracker




我应该是 2008 年开始用 git 的，那时候 github.com 还没有诞生。为何那么早呢？因为我研究生时候的研究方向是 Linux 内核，对 Linus 有着无比的崇拜，后来听说他写了 Git 这个软件，就去网上搜了他在 google 讲 git 的演讲视频，应该是听了几十遍。

后来有了 github.com 我就搬进了 github.com。这个是个 life changing 的决定，在 github 我又认识了 ruby 社区，喜欢！所以放弃 c 和 c++ 而转学 ruby on rails 
一直到今天。真是幸运！

### 本书内容

没有使用过任何版本控制工具，包括 git ，的朋友快速上手使用 github.com 。

本书内容不包括：git 的底层数据结构和运行原理

还是老思路，教会人家怎么用这个东西，进一步的理论学习和高级技巧学习不是我要操心的，有其他的书呢

这本书将会是我要写的唯一一本 git 书，任何我自己知识体系中最核心的点都会在书中给出特定的章节，稍微外围一点的知识点会在书中给出参考资料链接。
未来可能会增加章节，所以每一个页面没有给出序号，例如 http://happypeter.github.io/gitbeijing/introduction.html ，防止破坏已有链接。 章节的顺序在 toc 中体现。


点评基本 git 入门书。progit 对于初学者过于庞大深入且全面，一下子难以把握关键
 - peepcode-git.pdf
   - 跟 progit 内容有重合的部分，作者也是 schcon 但是仍然值得一翻，有很多深入的内容
 - http://gitref.org/
   - 是一些最最常用的功能的速查手册，质量极高
 - progit
   - 这个是必看的圣经了，但是作为对初学者友好而言，我的书更好

 - http://www.worldhello.net/gotgithub/
   - 中文资源

 - help.github.com
   - 我的书中很多部分就是梳理一下看这个的思路

 - http://git-scm.com/doc/ext 有更多资源


  - 所以过于深入的知识点，尽量用白话带过，但是最重要的三五个点可能比 progit 讲得还有仔细
  - progit 是脱离实际情景讲的，gitbeijing 操作基于实际的 web 开发工作流，基于 github
  - 这次一定不是只有实际操作的，一定要有图示，文字中以图示原理为主，视频中先原理后操作
  - 要讲的是 github 但是是针对完全没有 git 基础的人讲，所以 git 要讲到什么程度呢？
    - 不必太深，因为不是讲 git 的专著
    - 不能太略，不懂 git 基本实用，也没法用起 github
    - 这是一本给 web 开发新手的书，从整个应用图景把握各个知识点的轻重
      - 让大家花20%的时间掌握80%最常用的操作
  - 内容无所谓，关键是看起来要赏心悦目：http://s3.amazonaws.com/chacon/git-talk.pdf
  - 3d book： https://gist.github.com/happypeter/594db9d9e7d8dba50234
  - 可以以一个类似实际的小项目为例子，一步步的展示清楚各个功能到底能够对于项目开发起到怎样的帮助
    - 先本地，后连 github

### 基本概念介绍
代码仓库 repository 就是一个文件夹。

<!-- 术语会有一些，我要用大白话介绍给大家 -->

### Why Git

版本控制工具挺多，为啥非要用 git?
- 不要给大家上术语，类似于”分布式“，我的目标观众都是一些根本没有用过版本控制的 newb ，要到就是能最快最舒服的把 git 用起来，高深的东西不要瞎扯。

- 最后一个原因，就是 github 了
  - 不会 git 就用不了 github，不用 github 开发者就成了孤军了
  - FOSS 改变世界，github 改变了工程开展的过程

同样的，github.com 比其他的类似网站有啥不可替代性？