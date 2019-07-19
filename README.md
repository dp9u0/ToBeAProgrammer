# To Be A Programmer

程序员应该掌握的技能

## Teach Yourself Programming in Ten Years

[Teach Yourself Programming in Ten Years](http://norvig.com/21-days.html) [翻译](ttps://liuyandong.com/2017/10/25/122/)

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
    * [Memory Barrier](https://irl.cs.ucla.edu/~yingdi/web/paperreading/whymb.2010.06.07c.pdf)
  * SMP NUMA MPP
    * [NUMA架构的CPU -- 你真的用好了么？](http://cenalulu.github.io/linux/numa/)
* 缓存
    * Write Thought/Write Back
    * 缓存/内存访问一致性问题 : volatile,MESI,#Lock
	* [A Tutorial Introduction to the ARM and POWER Relaxed Memory Models](https://www.cl.cam.ac.uk/~pes20/ppc-supplemental/test7.pdf) : ARM 和 POWER 体系结构下多处理器系统内存并发访问一致性的设计思路和使用方法
    * [x86-TSO: A Rigorous and Usable Programmer’s Model for x86 Multiprocessors](https://www.cl.cam.ac.uk/~pes20/weakmemory/cacm.pdf) : x86 的多处理器内存并发访问的一致性模型 TSO
* 存储器 : 分层  物理内存(虚拟内存) 硬盘
  * [What Every Programmer Should Know About Memory](http://futuretech.blinkenlights.nl/misc/cpumemory.pdf)
* 网络 : 网络分层 ,网络协议 ,TCP/IP ,[HTTP](https://developer.mozilla.org/zh-CN/docs/Web/HTTP) [Let's code a TCP/IP stack](https://github.com/saminiir/level-ip)

### 计算机体系推荐阅读

* [**深入理解计算机系统**](https://book.douban.com/subject/1896753/)
* [**TCP-IP详解卷**](https://book.douban.com/series/12438)
* [计算机程序设计艺术](https://book.douban.com/series/46236) : 计算机学科的圣经

#### 计算机网络相关

* [Linux Advanced Routing & Traffic Control](https://lartc.org/)
* [Making Linux TCP Fast](https://netdevconf.org/1.2/papers/bbr-netdev-1.2.new.new.pdf)
* [Congestion Avoidance and Control](https://ee.lbl.gov/papers/congavoid.pdf)
* [http2讲解](https://ye11ow.gitbooks.io/http2-explained/content/)
* RFC : ARP 862 Tunnel 1853 2637 2661 2784 TCP 793 813 879 896 2581 2018 2883 2988 6298

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
* [C_dynamic_memory_allocation](https://en.wikipedia.org/wiki/C_dynamic_memory_allocation#Thread-caching_malloc_(tcmalloc))
* [ptmalloc,tcmalloc和jemalloc内存分配策略研究](https://owent.net/2013/867.html)
* [All about 64-bit programming in one place](https://software.intel.com/en-us/blogs/2011/07/07/all-about-64-bit-programming-in-one-place/)

### Linux 资源

* [kernel planet](http://planet.kernel.org/)
* [linux-insides](https://github.com/0xAX/linux-insides) : A book-in-progress about the linux kernel and its insides.
* [Linux Performance](http://www.brendangregg.com/linuxperf.html) : Page links to various Linux performance material, including the tools maps on the right.

### IO

* [Java 相关的 I/O 模型](https://www.slideshare.net/e456/tyma-paulmultithreaded1)
* [Boost application performance using asynchronous I/O](https://developer.ibm.com/articles/l-async/)
* [Lazy Asynchronous I/O For Event-Driven Servers](https://www.usenix.org/legacy/event/usenix04/tech/general/full_papers/elmeleegy/elmeleegy_html/html.html)
* [I/O Completion Ports](https://docs.microsoft.com/en-us/windows/win32/fileio/i-o-completion-ports)
* [Inside I/O Completion Ports](http://sysinternals.d4rk4.ru/Information/IoCompletionPorts.html)
* Libevent : [Libevent](https://aceld.gitbooks.io/libevent/content/) [libevent-book](http://www.wangafu.net/~nickm/libevent-book/)
* [Libuv](http://docs.libuv.org/en/v1.x/design.html)
* Reactor
  * [Understanding Reactor Pattern: Thread-Based and Event-Driven](https://dzone.com/articles/understanding-reactor-pattern-thread-based-and-eve) 
  * [The Design and Implementation of the Reactor](https://www.dre.vanderbilt.edu/~schmidt/PDF/Reactor2-93.pdf) 
  * [The reactor pattern and non-blocking IO](https://www.celum.com/en/blog/technology/the-reactor-pattern-and-non-blocking-io)
  
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
* [高性能MySQL](https://book.douban.com/subject/23008813/)
* [MySQL技术内幕](https://book.douban.com/subject/24708143/)
* [MySQL Internals Manual](https://dev.mysql.com/doc/internals/en/)
* [NoSQL精粹](https://book.douban.com/subject/25662138/)

## 系统架构

* 原则 : 合适(Keep Simple) 演化
* 分布式架构复杂度 : 系统之间的通信标准不统一 调用链长 系统结构复杂

### 理论与文章

* SOA 
  * [SOA Patterns](https://patterns.arcitura.com/soa-patterns)
  * [Microservices vs. Service-Oriented Architecture](https://www.nginx.com/resources/library/microservices-vs-soa/)
* MicroService
  * [MicroServices Resource Guide by Martin Fowler](https://martinfowler.com/microservices/)
  * [MicroServices by Martin Fowler](https://martinfowler.com/articles/microservices.html)
  * [Microservices architecture style](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/microservices)
  * [AWS-什么是微服务](https://aws.amazon.com/cn/microservices/)
  * [Microservices Best Practices for Java](https://www.redbooks.ibm.com/redbooks/pdfs/sg248357.pdf)
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
  * [Base: An Acid Alternative](https://queue.acm.org/detail.cfm?id=1394128)
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
  * [Zap](https://cwiki.apache.org/confluence/display/ZOOKEEPER/Zab+vs.+Paxos) : Zookeeper的一致性协议 [Paper](https://www.semanticscholar.org/paper/Zab%3A-High-performance-broadcast-for-primary-backup-Junqueira-Reed/b02c6b00bd5dbdbd951fddb00b906c82fa80f0b3)
  * [Vector Clock](https://riak.com/posts/technical/vector-clocks-revisited)
  * [Gossip](https://www.cs.cornell.edu/home/rvr/papers/flowgossip.pdf)
* [一致性哈希算法](https://www.akamai.com/us/en/multimedia/documents/technical-publication/consistent-hashing-and-random-trees-distributed-caching-protocols-for-relieving-hot-spots-on-the-world-wide-web-technical-publication.pdf)
* 分布式数据库
  * [Spanner](http://static.googleusercontent.com/media/research.google.com/zh-CN//archive/spanner-osdi2012.pdf) : CockroachDB TiDB 的理论依据
  * [AWS Aurora](https://www.allthingsdistributed.com/files/p1041-verbitski.pdf) : AWS Aurora
* 康威定律
* [Azure 云设计模式](https://docs.microsoft.com/zh-cn/azure/architecture/patterns/)

### 分布式架构设计模式

#### 高性能

* 缓存 : (分布式)缓存如何分区和查找 失效/更新(WriteThough),分布式服务意味着 单点缓存/分布式缓存 缓存要设置过期时间 预防爬虫
* [Scaling Memcache at Facebook](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf) : Cache Aside更新->失效
* Read/Write Though : 更新缓存,同步更新数据库
* Write Back : 更新缓存,异步更新数据库
* 负载均衡 : 路由算法 服务发现
* 异步处理 : 消息队列 异步+分布式事务
* 数据镜像(读写分离) : 数据同步 数据一致性 [CQRS]
* 数据分片(分库分表) : Data Access Layer Proxy

### 可用性/一致性(AP)

* 隔离设计 : 拆分和冗余,隔离故障,防止单点故障. 按照服务隔离(分布式事务) 数据存储隔离(读写分离 数据分区)  
* 异步通信&通信隔离 : 消息队列(事件驱动设计) 通过消息队列中间件方式环节服务依赖问题
* 幂等性 : 全局ID+去重表
* 服务状态 : 无状态服务(分布式数据存储支持) 有状态服务(通过长连接/基于session的负载均衡)让服务请求负载到同一个实例
* 补偿事务 : Try Commit / Rollback
* 重试机制 : 重试策略 考虑幂等性
* 熔断 : Close -> Open -> Half-Close 失败一定次数直接返回(调用代理 API Gateway)
* 限流 : 队列 [漏斗算法](https://en.wikipedia.org/wiki/Leaky_bucket) 令牌桶算法 基于系统响应时间动态限流
* 降级 : 服务降级(停止不重要的服务) 数据一致性降级(强一致性->最终一致性)
* 多中心

#### 管理

* 配置中心
* Service Mesh / SideCar : [Service Mesh](https://buoyant.io/2017/04/25/whats-a-service-mesh-and-why-do-i-need-one/)
* Gateway
* 安全性 : 接入安全 数据安全 传输安全
* 部署升级 : A/B 蓝绿 金丝雀

[A pattern language for microservices](https://microservices.io/patterns/index.html)

### 分布式架构工程与实践

* 监控和管理 : 监控与预警(硬件性能监控 中间件指标监控 服务调用监控) 资源地图(跨系统调用链,业务出现问题 可以找到问题链路) zipkin ELK skywalking
* 分布式服务 : 服务治理(服务依赖 服务发现 服务生命周期 服务路由) zookeeper dubbo docker k8s
* 分布式数据 : 1.分布式事务/数据镜像导致数据一致性问题 Paxos(数据层) 两/三段提交(应用层) 最终一致性 2.数据调度(数据分片) 数据分片中间件/业务层分片
* 流量控制 : 降级/限流/熔断 服务保护 API Gateway
* 运维 : DevOps

### 公司的架构实践

[公司的架构实践](http://highscalability.com/)

### 系统故障

* 定位 : 重点不在于debug 而是在于快速系统可用(必要时降级)
* 改进 : 处理过程 问题根源 根源出现的原因(5+ why) How

### PaaS IaaS SaaS

### 系统架构推荐阅读

* [Google Dapper](https://research.google.com/pubs/pub36356.html)
* [分布式系统的事务处理](https://coolshell.cn/articles/10910.html)
* [日志：每个软件工程师都应该知道的有关实时数据的统一概念](https://github.com/oldratlee/translations/blob/master/log-what-every-software-engineer-should-know-about-real-time-datas-unifying/README.md)

## 框架与应用

* sql : mysql
* nosql : redis elasticsearch mongodb
* mq : kafka
* actor : orleans akka
* reactive : rx.net
* io : netty dotnetty
* nginx
* dubbo
* zipkin
* zookeeper
* skywalking
* Zuul
* Service Mesh
* Consul
* [Hystrix](https://github.com/Netflix/Hystrix) : 容错系统
* [Disruptor](https://tech.meituan.com/2016/11/18/disruptor.html)
* [swagger](https://swagger.io/)

## 软件设计

### 编程思想

* 算法 : [List Of Algorithms](https://www.wikiwand.com/en/List_of_algorithms)
* 数据结构 : 线程安全 & LockFree 数据结构
* 命令式(imperative) :
  * 面向对象 (object oriented): 封装 多态 继承 消息传递 ,[A Theory of Objects](https://book.douban.com/subject/1761931/)
  * 过程式 (procedural): 流程化过程语句控制
* 声明式 (declarative): 定义计算逻辑 而不是定义流程控制
  * 函数式 (functional): 函数表达式方式避免状态和数据改变 高阶函数 柯里化 Map/Reduce/Filter
  * logical
  * database

 ### 并发并行与异步

* Lock-Free
* 异步 : APM TAP EAP Promise Observer
* Actor/Reactor
* Reactive

* [Lock-Free Data Structures](http://www.drdobbs.com/lock-free-data-structures/184401865)
* [Lock-Free Data Structures](https://erdani.com/publications/cuj-2004-10.pdf)
* [无锁队列的实现](https://coolshell.cn/articles/8239.html)
* [Implementing Lock-Free Queues](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.53.8674&rep=rep1&type=pdf)
* [Non-blocking_algorithm](https://en.wikipedia.org/wiki/Non-blocking_algorithm)
* [Read-copy-update](https://en.wikipedia.org/wiki/Read-copy-update)
* [Seqlock](https://en.wikipedia.org/wiki/Seqlock)
* [Is Parallel Programming Hard, And, If So, What Can You Do About It?](https://mirrors.edge.kernel.org/pub/linux/kernel/people/paulmck/perfbook/perfbook.html)
* [Simple, Fast, and Practical Non-Blocking and Blocking Concurrent Queue Algorithms](http://www.cs.rochester.edu/~scott/papers/1996_PODC_queues.pdf)

### Distributed Programming

* [Distributed Programming Model](https://web.cs.ucdavis.edu/~pandey/Research/Papers/icdcs01.pdf)
* [PSync: a partially synchronous language for fault-tolerant distributed](https://www.di.ens.fr/~cezarad/popl16.pdf)
* [Programming Models for Distributed System](https://heather.miller.am/teaching/cs7680/)
* [Logic and Lattices for Distributed Programming](http://db.cs.berkeley.edu/papers/UCB-lattice-tr.pdf)

### 软件架构

* 设计模式(面向对象) : S.O.L.I.D
  * Common Closure Principle
  * Common Reuse Principle
  * Hollywood Principle : IoC DI
  * High Cohesion & Loose coupling
  * SoC : 关注点分离
  * Convention over Configuration
  * Design by Contract
  * Acyclic Dependencies Principle
* 微内核(Plugin)
* 分层
* DDD
* MVVM

### 软件设计推荐阅读

* [领域驱动设计](https://book.douban.com/subject/26819666/)
* [代码整洁之道](https://book.douban.com/subject/26919457/)
* [重构:改善既有代码的设计](https://book.douban.com/subject/4262627/)
* [泛型编程](http://stepanovpapers.com/genprog.pdf)
* [**算法导论**](https://book.douban.com/subject/20432061/)
* [冒号课堂](https://book.douban.com/subject/4031906/)
* [The Twelve-Factor App](https://12factor.net/) : [ZH-CN](https://12factor.net/zh_cn/)

## 编程语言

### Java

* [深入理解 Java 虚拟机](https://book.douban.com/subject/24722612/)
* [The JSR-133 Cookbook for Compiler Writers](http://gee.cs.oswego.edu/dl/jmm/cookbook.html)
* [Introduction to Java Bytecode](https://dzone.com/articles/introduction-to-java-bytecode)
* [Byte Buddy](http://bytebuddy.net/#/)
* [Java Bytecode and JVMTI Examples](https://github.com/jon-bell/bytecode-examples)

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

### 编码规范

* [Linux kernel coding style](https://www.kernel.org/doc/html/latest/process/coding-style.html)
* [C++ Coding Style](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)
* [Shell](https://google.github.io/styleguide/shell.xml)

## 工具类

* gdb windbg
* shell : awk sed
* git
  * [Git WorkFlow](https://nvie.com/posts/a-successful-git-branching-model/)
  * [GitHub Workflow](http://scottchacon.com/2011/08/31/github-flow.html)
  * [Gitlab Workflow](https://about.gitlab.com/2014/09/29/gitlab-flow/)
* makefile

## 其他技术

### 容器与自动化

* docker 
* k8s

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

* [97 Things Every Programmer Should Know](https://97-things-every-x-should-know.gitbooks.io/97-things-every-programmer-should-know/content/en/index.html)
* 计划与时间管理 : to do list 番茄时钟 四象限任务分类 保持专注
* 学习与知识管理 : 知识树 通读->细节
* 沟通
* ToBeALeader : 技术领导能力 项目管理能力
* 面试
* 金融市场和金融机构

### 推荐阅读

* [随机漫步的傻瓜](https://book.douban.com/subject/10773362/)

## 资源集散地以及Blogs

* [redbooks](https://www.redbooks.ibm.com/)
* [1024cores](http://www.1024cores.net/)
* [Mechanical Sympathy](http://mechanical-sympathy.blogspot.com/)
