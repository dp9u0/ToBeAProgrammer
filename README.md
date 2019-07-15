# To Be A Programmer

程序员应该掌握的技能

## 基础学科

* 离散数学
* 概率论与统计
* 线性代数

机器学习,推荐算法等都是对数学知识的应用.同时算法分析和设计本身就需要数学理论证明.越往深处挖掘,越会发现计算机跟数学的联系非常紧密.

* 英语 : 虽然越来越多的技术文档官方会提供中文版,但是更多时候还是只有原版文档文档可以阅读.并且很多技术的论文不存在中文版的.

### 基础学科推荐阅读

* [离散数学及其应用](https://book.douban.com/subject/2130743)
* [概率统计](https://book.douban.com/subject/10827481/)
* [线性代数及其应用](https://book.douban.com/subject/1425950/)
* [数学之美](https://book.douban.com/subject/26163454/)

## 计算机体系

* 编码
  * 整数 : 原码 反码 补码(为什么需要补码?加法器实现减法)
  * 浮点数 : IEEE 754
  * 字符 : ASCII Unicode(UTF-8 UTF-16 UTF-32)
* CPU ：
  * 指令流水线执行
  * SMP NUMA MPP
    * [NUMA架构的CPU -- 你真的用好了么？](http://cenalulu.github.io/linux/numa/)
  * 缓存
    * WriteThought/WriteBack
    * 一致性 : [关于volatile、MESI、内存屏障、Lock](https://www.jianshu.com/p/6745203ae1fe)
* 存储器 : 分层  物理内存(虚拟内存) 硬盘
* 网络 : 网络分层 ,网络协议 ,TCP/IP ,HTTP (RFC)

### 计算机体系推荐阅读

* [**深入理解计算机系统**](https://book.douban.com/subject/1896753/)
* [**TCP-IP详解卷**](https://book.douban.com/series/12438)
* [计算机程序设计艺术](https://book.douban.com/series/46236) : 计算机学科的圣经

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

### 操作系统推荐阅读

* [现代操作系统](https://book.douban.com/subject/3667744/)
* [操作系统-精髓与设计原理](https://book.douban.com/subject/30770794/)
* [Linux内核设计与实现](https://book.douban.com/subject/1503819/)
* [UNIX 编程艺术](https://book.douban.com/subject/11609943/)
* [UNIX 网络编程](https://book.douban.com/subject/1500149/)  [Vol2](https://book.douban.com/subject/4118577/)
* [Linux 系统编程](https://book.douban.com/subject/25828773/)
* [UNIX 环境高级编程](https://book.douban.com/subject/25900403/)
* [Windows 核心编程](https://book.douban.com/subject/3235659/) : Windows Via C/C++
* [程序员的自我修养](https://book.douban.com/subject/3652388/) : 关于程序链接的知识

## 编译原理

### 编译原理推荐阅读

* [计算机程序的构造和解释](https://book.douban.com/subject/1148282/)
* [编译原理](https://book.douban.com/subject/3296317/)

## 数据存储

* sql
* nosql
* 分布式文件系统

### 数据存储推荐阅读

* [SQL Server2012实施与管理实战指南](https://book.douban.com/subject/21823753/)
* [数据库系统概念](https://book.douban.com/subject/10548379/)

## 软件架构

* 设计模式
* 微内核(Plugin)
* 分层
* DDD
* MVVM

### 软件架构推荐阅读

* [代码整洁之道](https://book.douban.com/subject/26919457/)
* [重构:改善既有代码的设计](https://book.douban.com/subject/4262627/)

## 系统架构

* 原则 : 合适(Keep Simple) 演化
* 分布式架构复杂度 : 系统之间的通信标准不统一 调用链长 系统结构复杂
* 理论与文章
  * SOA
  * MicroService
    * [MicroServices Resource Guide by Martin Fowler](https://martinfowler.com/microservices/)
    * [MicroServices by Martin Fowler](https://martinfowler.com/articles/microservices.html)
    * [微服务架构](http://dockone.io/article/3687)
  * 分布式系统理论  
    * [CAP Wiki](https://en.wikipedia.org/wiki/CAP_theorem)
    * [Fallacies of Distributed Computing @Wiki](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing) [Pdf](http://www.rgoarchitects.com/Files/fallacies.pdf):  分布式系统中的错误假设
    * [Distributed systems theory for the distributed systems engineer](https://www.the-paper-trail.org/post/2014-08-09-distributed-systems-theory-for-the-distributed-systems-engineer/) : 分布式系统理论
    * [Distributed systems for fun and profit](http://book.mixu.net/distsys/) : 分布式系统中的关键问题
    * [notes-on-distributed-systems-for-young-bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/) : 分布式系统实践笔记
    * [A Note on Distributed Computing](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.41.7628) : 为什么在分布式系统中,远程调用不能像本地对象那样进行
    * [An introduction to distributed systems](https://github.com/aphyr/distsys-class) : 分布式系统提纲
    * [可扩展的 Web 架构和分布式系统](http://www.aosabook.org/en/distsys.html) : 可扩展的 Web 架构和分布式系统
    * [Principles of Distributed System](https://disco.ethz.ch/courses/podc_allstars/lecture/podc.pdf) : Books 分布式系统中会用到的算法
    * [数据密集型应用系统设计](https://book.douban.com/subject/30329536/) : Books
  * ACID BASE
  * 一致性 : 强一致性 顺序一致性 弱一致性
  * 分布式事务
    * 两段提交
    * 三段提交
    * 一致性算法 : Paxos
    * [事务补偿](https://docs.microsoft.com/en-us/azure/architecture/patterns/compensating-transaction) : TCC
    * 最终一致性
  * 分布式锁 : 数据库 redis zookeeper 实现分布式锁
  * 乐观锁(CAS)
  * 共识/一致性算法 Paxos Raft Zap
    * [Paxos](http://harry.me/blog/2014/12/27/neat-algorithms-paxos/)
    * [RAFT](https://www.infoq.cn/article/raft-paper/)
    * [Zap](https://cwiki.apache.org/confluence/display/ZOOKEEPER/Zab+vs.+Paxos) : Zookeeper的一致性协议
    * [Vector Clock](https://riak.com/posts/technical/vector-clocks-revisited)
    * [Gossip](https://www.cs.cornell.edu/home/rvr/papers/flowgossip.pdf)
  * [一致性哈希算法](https://www.akamai.com/us/en/multimedia/documents/technical-publication/consistent-hashing-and-random-trees-distributed-caching-protocols-for-relieving-hot-spots-on-the-world-wide-web-technical-publication.pdf)
  * 分布式数据库
    * [Spanner](http://static.googleusercontent.com/media/research.google.com/zh-CN//archive/spanner-osdi2012.pdf) : CockroachDB TiDB 的理论依据
    * [AWS Aurora](https://www.allthingsdistributed.com/files/p1041-verbitski.pdf) : AWS Aurora
  * 康威定律
  * [Azure 云设计模式](https://docs.microsoft.com/zh-cn/azure/architecture/patterns/)
* 分布式架构设计模式
  * 高性能
    * 缓存 : (分布式)缓存如何分区和查找 失效/更新(WriteThough),分布式服务意味着 单点缓存/分布式缓存 缓存要设置过期时间 预防爬虫
    * [Scaling Memcache at Facebook](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf) : Cache Aside更新->失效
    * Read/Write Though : 更新缓存,同步更新数据库
    * Write Back : 更新缓存,异步更新数据库
  * 负载均衡 : 路由算法 服务发现
  * 异步处理 : 消息队列 异步+分布式事务
  * 数据镜像(读写分离) : 数据同步 数据一致性 [CQRS]
  * 数据分片(分库分表) : Data Access Layer Proxy
  * 可用性/一致性(AP)
    * 隔离设计 : 拆分和冗余,隔离故障,防止单点故障. 按照服务隔离(分布式事务) 数据存储隔离(读写分离 数据分区)  
    * 通信隔离 : 消息队列(事件驱动设计) 通过消息队列中间件方式环节服务依赖问题
  * 幂等性 : 全局ID+去重表
  * 服务状态 : 无状态服务(分布式数据存储支持) 有状态服务(通过长连接/基于session的负载均衡)让服务请求负载到同一个实例
  * 补偿事务 : Try Commit / Rollback
  * 重试机制 : 重试策略 考虑幂等性
  * 熔断 : Close -> Open -> Half-Close 失败一定次数直接返回(调用代理 API Gateway)
  * 限流 : 队列 [漏斗算法](https://en.wikipedia.org/wiki/Leaky_bucket) 令牌桶算法 基于系统响应时间动态限流
  * 降级 : 服务降级(停止不重要的服务) 数据一致性降级(强一致性->最终一致性)
  * 多中心
  * 可扩展
    * 配置中心
  * Service Mesh / SideCar : [Service Mesh](https://buoyant.io/2017/04/25/whats-a-service-mesh-and-why-do-i-need-one/)
  * Gateway
  * 安全性 : 接入安全 数据安全 传输安全
* 分布式架构工程与实践
  * 监控和管理 : 监控与预警(硬件性能监控 中间件指标监控 服务调用监控) 资源地图(跨系统调用链,业务出现问题 可以找到问题链路) zipkin ELK skywalking
  * 分布式服务 : 服务治理(服务依赖 服务发现 服务生命周期 服务路由) zookeeper dubbo docker k8s
  * 分布式数据 : 1.分布式事务/数据镜像导致数据一致性问题 Paxos(数据层) 两/三段提交(应用层) 最终一致性 2.数据调度(数据分片) 数据分片中间件/业务层分片
  * 流量控制 : 降级/限流/熔断 服务保护 API Gateway
  * 运维 : DevOps
* 系统故障
  * 定位 : 重点不在于debug 而是在于快速系统可用(必要时降级)
  * 改进 : 处理过程 问题根源 根源出现的原因(5+ why) How
* PaaS IaaS SaaS

### 系统架构推荐阅读

* [Google Dapper](https://research.google.com/pubs/pub36356.html)
* [分布式系统的事务处理](https://coolshell.cn/articles/10910.html)

## 框架与应用

* 容器 : docker k8s
* sql : mysql
* nosql : redis elasticsearch mongodb
* mq : kafka
* actor : orleans akka
* reactive : rx.net
* netty : dotnetty
* nginx
* dubbo
* zipkin
* zookeeper
* skywalking
* Zuul
* Service Mesh
* Consul
* [Hystrix](https://github.com/Netflix/Hystrix) : 容错系统
* [高性能队列——Disruptor](https://tech.meituan.com/2016/11/18/disruptor.html)

## 编程范式

* 算法
* 数据结构 : 线程安全 & LockFree 数据结构
* 面向对象
  * [A Theory of Objects](https://book.douban.com/subject/1761931/)
* 面向过程
* 异步 : APM TAP EAP Promise Observer
* Actor
* Reactive

### 编程范式推荐阅读

* [**算法导论**](https://book.douban.com/subject/20432061/)

## 编程语言

### Java

* [深入理解 Java 虚拟机](https://book.douban.com/subject/24722612/)

### .NET

* [**CLR Via C#**](https://book.douban.com/subject/4924165/)
* [ECMA 335](http://www.ecma-international.org/publications/standards/Ecma-335.htm) : CLI
* [The Book of the Runtime](https://github.com/dotnet/coreclr/tree/master/Documentation/botr) : CLR
* [design and implementation of generics](https://www.microsoft.com/en-us/research/wp-content/uploads/2001/01/designandimplementationofgenerics.pdf)

* Collection
* Threading
  * [**there is no thread**](https://blog.stephencleary.com/2013/11/there-is-no-thread.html)
* Task
* Native Call
* 内存管理
  * [**Memory-Usage-Inside-the-CLR**](https://mattwarren.org/2017/07/10/Memory-Usage-Inside-the-CLR/)
  * [**learning-how-garbage-collectors-work-part**](https://mattwarren.org/2016/02/04/learning-how-garbage-collectors-work-part-1)
  * [**Drill Into .NET Framework Internals to See How the CLR Creates Runtime Objects**](https://web.archive.org/web/20080919091745/)
  * [**Back to basic: Series on dynamic memory management**](https://blogs.msdn.microsoft.com/abhinaba/2009/01/25/back-to-basic-series-on-dynamic-memory-management/)
* GC
* JIT

### C/C++

* [C陷阱与缺陷](https://book.douban.com/subject/2778632/)
* [C标准库](https://book.douban.com/subject/3775842/)
* [C++标准库](https://book.douban.com/subject/26419721/)
* [C++ Primer](https://book.douban.com/subject/1767741/)
* [Effective C++](https://book.douban.com/subject/1231590/)

### js/nodejs

* [**You Don't Know JS**](https://book.douban.com/subject/25883834/)

### 工具类

* gdb windbg
* shell : awk sed
* git
  * [Git WorkFlow](https://nvie.com/posts/a-successful-git-branching-model/)
  * [GitHub Workflow](http://scottchacon.com/2011/08/31/github-flow.html)
  * [Gitlab Workflow](https://about.gitlab.com/2014/09/29/gitlab-flow/)
* makefile

## 其他技术

### 区块链与数字货币

### Machine Learning

* [机器学习 by 周志华](https://book.douban.com/subject/26708119/)
* [机器学习 By Andrew Ng](https://www.coursera.org/learn/machine-learning) [@网易公开课](http://open.163.com/special/opencourse/machinelearning.html)
* [机器学习 By Tom Mitchell](http://www.cs.cmu.edu/~tom/10701_sp11/lectures.shtml)

### 量子计算

### 前端

* Flutter
* vue
* react
* angular
* webpack
  
## 软技能

* 计划与时间管理 : to do list 番茄时钟 四象限任务分类 保持专注
* 学习与知识管理 : 知识树 通读->细节
* 沟通
* ToBeALeader : 技术领导能力 项目管理能力
* 面试
* 金融市场和金融机构

### 推荐阅读

* [随机漫步的傻瓜](https://book.douban.com/subject/10773362/)
