# To Be A Programmer

程序员应该掌握的技能

## 基础学科

* 离散数学
* 概率论与统计
* 线性代数

机器学习,推荐算法等都是对数学知识的应用.同时算法分析和设计本身就需要数学理论证明.越往深处挖掘,越会发现计算机跟数学的联系非常紧密.

* 英语 : 虽然越来越多的技术文档官方会提供中文版,但是更多时候还是只有原版文档文档可以阅读.并且很多技术的论文不存在中文版的.

### 推荐书籍

* [ ] [离散数学及其应用](https://book.douban.com/subject/2130743)
* [ ] [概率统计](https://book.douban.com/subject/10827481/)
* [ ] [线性代数及其应用](https://book.douban.com/subject/1425950/)
* [ ] [数学之美](https://book.douban.com/subject/26163454/)

### 推荐文章

## 计算机体系

* 编码
  * 整数 : 原码 反码 补码(为什么需要补码?加法器实现减法)
  * 浮点数 : IEEE 754
  * 字符 : ASCII Unicode(UTF-8 UTF-16 UTF-32)
* CPU ：指令流水线执行 ,SMP NUMA MPP ,缓存(WriteThought 一致性)
* 存储器 : 分层  物理内存(虚拟内存) 硬盘
* 网络 : 网络分层 ,网络协议 ,TCP/IP ,HTTP (RFC)

### 推荐书籍

* [x] [深入理解计算机系统](https://book.douban.com/subject/1896753/)
* [x] [TCP-IP详解卷](https://book.douban.com/series/12438)
* [ ] [计算机程序设计艺术](https://book.douban.com/series/46236) : 计算机学科的圣经

### 推荐文章

## 操作系统(Windows Linux)

* 内核 : 中断
* 驱动
* Process
* Thread
* 竞态与同步
* 内存管理 : 内存管理(分配 替换 缺页)
* 文件系统
* IO : IO模型 阻塞和非阻塞 同步异步
* 链接(静态链接和动态链接)

### 推荐书籍

* [ ] [现代操作系统](https://book.douban.com/subject/3667744/)
* [ ] [操作系统-精髓与设计原理](https://book.douban.com/subject/30770794/)
* [ ] [Linux内核设计与实现](https://book.douban.com/subject/1503819/)
* [ ] [UNIX 编程艺术](https://book.douban.com/subject/11609943/)
* [ ] [UNIX 网络编程](https://book.douban.com/subject/1500149/)  [Vol2](https://book.douban.com/subject/4118577/)
* [ ] [Linux 系统编程](https://book.douban.com/subject/25828773/)
* [ ] [UNIX 环境高级编程](https://book.douban.com/subject/25900403/) 
* [ ] [Windows 核心编程](https://book.douban.com/subject/3235659/) : Windows Via C/C++
* [ ] [程序员的自我修养](https://book.douban.com/subject/3652388/) : 关于程序链接的知识

### 推荐文章

## 编译原理

### 推荐书籍

* [ ] [计算机程序的构造和解释](https://book.douban.com/subject/1148282/)
* [ ] [编译原理](https://book.douban.com/subject/3296317/)

## 编程范式

* 算法
* 数据结构 : 线程安全&LockFree 数据结构
* 面向对象 面向过程
* 异步 : APM TAP EAP Promise Observer
* Actor
* Reactive

### 推荐书籍

* [x] [算法导论](https://book.douban.com/subject/20432061/)

## 数据存储

* sql
* nosql
* 分布式文件系统

### 推荐书籍

* [ ] [SQL Server2012实施与管理实战指南](https://book.douban.com/subject/21823753/)
* [ ] [数据库系统概念](https://book.douban.com/subject/10548379/)

## 软件架构

* 设计模式
* 微内核(Plugin)
* 分层
* DDD
* MVVM

### 推荐书籍

* [ ] [代码整洁之道](https://book.douban.com/subject/26919457/)
* [ ] [重构:改善既有代码的设计](https://book.douban.com/subject/4262627/)

## 系统架构

* 原则 合适 简单 演化
* 理论
  * SOA
  * microservice
  * CAP
  * BASE
  * 分布式事务
  * 分布式锁
  * 共识算法 paxos raft zap
* 设计模式
  * 高性能
  * 高可用
  * 可伸缩
  * 安全性
* 工程与实践
  * 服务
  * 数据
  * 控制
  * 监控
  * 运维 DevOps

## 框架与应用

* 容器 : docker k8s
* sql : mysql
* nosql : redis elasticsearch mongodb
* mq : kafka
* Actor : orleans akka
* netty
* nginx
* rpc : dubbo

## 编程语言

### Java

* [ ] [深入理解 Java 虚拟机](https://book.douban.com/subject/24722612/)

### .NET

* [x] [CLR Via C#](https://book.douban.com/subject/4924165/)

### C/C++

* [ ] [C陷阱与缺陷](https://book.douban.com/subject/2778632/)
* [ ] [C标准库](https://book.douban.com/subject/3775842/)
* [ ] [C++标准库](https://book.douban.com/subject/26419721/)
* [ ] [C++ Primer](https://book.douban.com/subject/1767741/)
* [ ] [Effective C++](https://book.douban.com/subject/1231590/)

### js/nodejs

* [x] [You Don't Know JS](https://book.douban.com/subject/25883834/)

### 虚拟机

* Metadata
* Type System
* JIT
* 内存管理
* Call Native Code

### 工具类

* gdb windbg
* shell : awk sed
* git
* makefile

## 其他技术

### 区块链与数字货币

### Machine Learning

* [ ] [机器学习原来这么有趣](https://zhuanlan.zhihu.com/p/24339995)

### 量子计算

### 前端

  * Flutter
  * vue
  * react
  * angular
  * webpack
  
## 软技能

* 学习与知识管理
* 沟通
* 面试
* 管理
* 金融市场和金融机构

### 推荐书籍

* [ ] [随机漫步的傻瓜](https://book.douban.com/subject/10773362/)

