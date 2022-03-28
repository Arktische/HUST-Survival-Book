---
description: 有关后端找工作的一些经验
---

# 后端

> By [Yuxing Tu](https://app.gitbook.com/u/zCVwg7WHFegf8CEuy6yiP5B39Tu2 "mention")

### 后端的定位

后端工程师主要进行业务架构设计和业务逻辑实现。各种应用俗称的“后台”就属于后端范畴。

### 课程学习

后端由于涉及面广，因此需要很多计算机基础知识。通常来说，需要如下四门课的前置知识：

1. 数据结构与算法
2. 计算机网络
3. 操作系统
4. 数据库原理

其中1是一切后端相关技能树的基石，而2与3是理解各种后端逻辑的基础。对于我校学子，大三下学期前掌握1、2、3基本上可以找到后端相关的实习。而4的学习是更加进阶地理解数据的建模与查询策略，涉及到很多系统设计知识，可以最后掌握。

### 课程资源

对应于前期的学习，有如下非常好的课程资源推荐（以下推荐均为可选项并不意味着都要学）。请学会使用Google来搜索以下资源的相关讲解～

1. 数据结构与算法：
   * [Berkeley CS61b](https://inst.eecs.berkeley.edu/\~cs61b/sp22/)
2. 计算机网络：
   * [Stanford CS144](https://cs144.github.io)
   * Unix Network Programming, 俗称UNNP
   * TCP/IP详解卷I II
3. 操作系统：
   * [Operating System: Three Easy Pieces(OSTEP)](https://github.com/remzi-arpacidusseau/ostep-translations/tree/master/chinese)
4. 数据库：
   1. [PingCAP Talent Plan](https://github.com/pingcap/talent-plan)
   2. [CMU 15445/645](https://15445.courses.cs.cmu.edu/fall2021/)

### 学习路线

因为专业、背景、基础不同，后端工程师并没有一个通用的学习路线。因此下面把后端的学习路线分为几个方面并对其难度进行打分，读者可以自行组合形成自己的学习路线

#### 1. 源码阅读（进阶，🌟🌟🌟）

**网络:**&#x20;

* _nginx：_[_相关资源_](https://static.kancloud.cn/digest/understandingnginx/202586)__
  * [ ] event部分、upstream部分
  * [ ] 基础数据数据部分

**存储（**🌟🌟🌟**）:**&#x20;

* _redis_：
  * [ ] 数据结构实现部分 ：ZSET、Hash...
  * [ ] 持久化逻辑
  * [ ] redis集群
* leveldb：
  * [ ] LSM树的实现：MemTable,SSTable部分
  * [ ] compact逻辑，Write Ahead Log实现等

**分布式系统（**🌟🌟🌟🌟**）:**&#x20;

* CAP定理&#x20;
* Raft/Paxos：
  * [ ] etcd v0.2.x raft module
* 2pc（2阶段提交）
  * [ ] Google percolator论文

#### 2.项目（必须，🌟🌟）

#### 3. 语言（必须）

#### 4. Linux使用（进阶，🌟🌟🌟）

#### 5. 课设与Lab（进阶）



### 后端如何选部门

#### 面试难度上

面试难度应该和自身面试情况相匹配

* 算法、基础架构相对业务部门要难
* 缺人的时候不那么难
* 公认的核心部门相对更难

#### 发展前景上

结合部门业务前景去看适不适合自己

* 核心盈利的部门会比较卷，收益可能较高
* 高增长的部门晋升机会多，收益也可能高
* 架构类部门较稳定，业务部门上升机会更多
* 有的成功业务会有部门光环，有利于跳槽
