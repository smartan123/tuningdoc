[**从零实战-Java 企业级 全方位 性能调优**](http://coding.imooc.com/tms/course/whitelist?courseid=442)



# **课程传送门：**

https://coding.imooc.com/class/442.html



**课程配套在线电子书：**

https://smartan123.github.io/book

# **配套高颜值思维导图：**

![img](D:\Program Files\typora-user-images\0.png)

# **慕女神有话说：**

**攻克企业级性能优化，人生只做【选择题】，不做【填空题】；**



**攻克企业级性能优化，给自己的程序生涯一个【弯道超车】的机会；**



**攻克企业级性能优化，征服丈母娘，迎娶白富美，走上人生巅峰！**



![img](D:\Program Files\typora-user-images\0-1591172531886.png)



**课程章节详情：**





- ##### **第1章 开宗明义：决胜性能调优 【风里雨里，课程等你~“猿”浪们，加油吧！】**

攻克性能调优，钱多事儿少离家近的活儿任君选择！《慕课网献给：年轻一代程序员“硬”技能课：企业级性能调优专题》。少吃一次海底捞，给自己程序人生一次“弯道超车”机会，余生，愿你：只为梦想买单，为未来买单，为优秀买单！加油，后浪们！...

-  1-1 攻克性能调优：给自己的程序生涯一次“弯道超车”的机会**试看**

本章从数据库优化的多个层面来阐述数据库优化的必要性，并带大家在线安装最新的版本的mysql，导入相关测试数据为后面的课程演示做准备，并初步对慢查询日志进行设置及测试，重点讲解慢查日志中的相关统计指标，为后续的sql调优打下坚实的基础。 ...

-  2-1 全方位MySQL调优专题总览：构建知识体系**试看**
-  2-2 数据库优化的必要性
-  2-3 mysql的优化层面详解
-  2-4 mysql在线安装及数据准备
-  2-5 pd逆向导出数据库物理模型
-  2-6 mysql慢查日志设置及测试
-  2-7 jemeter压测mysql&慢查日志统计指标解析

对SQL调优首先得会解读慢查询日志，从慢查询日志中获取相关问题sql信息，从而精准调优。本章两大慢查询分析工具：mysqldumpslow，pt-query-digest，重点讲解和演示用法和示例，通过pt-query-digest利器解读慢查询日志，查找三类问题SQL。 ...

-  3-1 mysqldumpslow用法详解及示例
-  3-2 pt-query-digest安装及常用命令解析
-  3-3 详解pt-query-digest分析慢查询日志报告1
-  3-4 详解pt-query-digest分析慢查询日志报告2&监控死锁
-  3-5 pt-query-digest其他命令演示及详解
-  3-6 利用pt-query-digest利器查找三大类有问题的SQL

找到问题sql，首要是查看并解读sql执行计划，从中了解执行步骤，找到真正造成sql执行缓慢关键点及原因并有针对性优化。本章从如何使用explain查看SQL执行计划开始讲解，着重讲解如何解读执行计划，并针对执行计划中重要指标字段进行详细讲解。 ...

- ##### **第5章 专题一:全方位MySQL调优-企业级调优思维【难度：☆☆ 实用性：☆☆☆挑大梁】**

在掌握了如何解读sql执行计划之后，我们已经初步掌握sql调优的一般步骤，此时需要梳理sql优化的思路并针对最常见的语句整理出调优思路。本章着重讲解常见的慢查询的优化思路，并且详细分析了常见的join语句，order by语句的原理以及优化思路。 ...

-  5-1 慢查询优化思路概述-上
-  5-2 慢查询优化思路概述-下
-  5-3 mysql三种join方式及执行计划详解
-  5-4 揭秘驱动表的选择对性能的影响
-  5-5 join算法详解及优化思路
-  5-6 join优化实操演示
-  5-7 mysql其他几种优化注意点
-  5-8 order by子句优化详解
-  5-9 order by算法详解
-  5-10 order by排序不一致问题&索引生效与否案例演示

本章继续讲解group by语句，distinct语句的原理及优化思路，以及对索引的全面分析及讲解，并且演示了相关索引失效的案例和数据库其他方面的一些优化原则，涉及数据库字段，索引，sql，数据库结构优化等方面。

-  6-1 group by的三种扫描类型详解与演示
-  6-2 group by索引失效案例&distinct案例演示
-  6-3 B-tree索引原理详解
-  6-4 B+tree索引原理详解及创建索引原则
-  6-5 索引失效情况案例详解
-  6-6 mysql优化的终级奥义
-  6-7 详解数据库字段&索引类的优化原则
-  6-8 详解数据库sql类的优化原则
-  6-9 详解数据库结构优化原则
-  6-10 mysql调优知识点复盘

本章主要讲解tomcat的下载及安装部署，以及常见功能的优化配置，如：禁用ajp，设置线程池，调整连接器的执行通道等等，重点讲解并演示tomcat的三大运行模式，让大家对tomcat调优先有个直观的认识。

-  7-1 全视角Tomcat调优专题总览：构建知识体系
-  7-2 部署安装tomcat
-  7-3 禁用ajp
-  7-4 启用线程池
-  7-5 tomcat运行模式总览
-  7-6 tomcat运行模式之阻塞与非阻塞（BIO|NIO）
-  7-7 tomcat运行模式之异步非阻塞与(NIO2|APR)

本章先带大家部署一个java web的servlet测试项目，主要功能是模拟业务延时，打包并部署，为后续讲解tomcat调优做准备。然后通过jmeter对java web项目进行压测，主要压测tomcat设置线程的极限及吞吐量，因为线程是支撑tomcat高效运行的基础，那么线程间又是如何配合完成任务的呢？本章后半部分将通过底层源码跟踪方式讲解t...

-  8-1 部署web项目进行压测
-  8-2 使用ApacheJMeter进行测试
-  8-3 禁用ajp后的吞吐量
-  8-4 修改线程池参数查看吞吐量1
-  8-5 修改线程池参数查看吞吐量2
-  8-6 main线程详解
-  8-7 startstop线程&AsyncFileHandlerWriter线程详解
-  8-8 ContainerBackgroundProcessor线程&Catalina-Utility线程详解
-  8-9 acceptor线程详解
-  8-10 ClientPoller线程详解
-  8-11 exec线程详解
-  8-12 BlockPoller线程&AsyncTimeout线程&其他线程详解

本章主要讲解tomcat工作的总体流程，以及通过源码解读tomcat前端关键组件初始化和启动详细过程， 针对4大通道先讲解BIO通道的优点及存在的问题，以及针对BIO通道的缺点tomcat给出APR通道和NIO通道的解决方案；最后比较proactor模式和reactor模式，引出目前最高效的NIO2通道。...

-  9-1 TOMCAT前端详细流程分解
-  9-2 NIO通道各组件装配原理及源码解析
-  9-3 NIO通道三大线程协调运行原理及源码解析1-
-  9-4 NIO通道三大线程协调运行原理及源码解析2-
-  9-5 NIO通道阻塞回写流程详解及源码解析
-  9-6 BIO通道原理及源码解析
-  9-7 手写单线程模式和多线程模式下的BIO通道并解析原理
-  9-8 手写Selector模拟NIO轮询并解析原理
-  9-9 NIO2通道关键组件源码解析
-  9-10 NIO2通道非阻塞读流程详解及源码解析
-  9-11 NIO2通道阻塞写流程详解及源码解析
-  9-12 APR通道关键组件解析
-  9-13 APR通道中tomcat-native子项目&apr网络包&openssl包详解

tomcat的高性能除了高效的线程模型和通道之外，还借助于其他相关属性，例如sendfile（零拷贝），compression（压缩），deferAccept（延迟接受），keepalive（保活）等技术。本章将从底层源码详细讲解这几种技术在tomcat中的实现。

-  10-1 sendfile机制详解及性能压测
-  10-2 源码解析sendfile在tomcat中的运行机制
-  10-3 compression压缩属性概述-
-  10-4 comression性能压测对比
-  10-5 源码解析compression压缩原理
-  10-6 deferAccept参数优化详解
-  10-7 keepalive原理剖析
-  10-8 源码解析tomcat中keepalive的实现原理
-  10-9 压测比较串行，并行垃圾回收器性能
-  10-10 可视化工具分析串行，并行，g1垃圾回收日志报告
-  10-11 tomcat调优知识点复盘

本章将从jvm常见的调优参数入手，开始讲解jvm调优过程中的常用命令及相关工具，包括jmap，jhat，jstack，jvisualvm等常见调优工具以及MAT等专业故障排查工具，并通过几个实际案例讲解死锁，内存泄漏等故障排查方法及过程。让大家对jvm调优和故障排查过程有一个清晰的认识。 ...

-  11-1 jvm优化概述及优化的必要性
-  11-2 jvm运行参数-标准参数详解
-  11-3 jvm运行参数-非标准参数详解-
-  11-4 jvm内存模型详解
-  11-5 jvm内存模型续&jstat命令详解
-  11-6 jmap使用详解
-  11-7 MAT工具使用详解
-  11-8 内存溢出定位与分析实战
-  11-9 jstack使用详解及定位死锁问题
-  11-10 jvisualvm使用详解
-  11-11 jvm优化及jdk监控工具知识点复盘**试看**

GC是jvm调优环节中非常重要的一环，内存泄漏通常就是由于频繁的FULL GC引起的。本章主要讲解jvm调优过程中常见的GC算法，GC算法的优劣直接关系到GC的执行效率。所以对GC算法的熟练掌握是jvm调优的基础，对jvm的调优有着不可替代的指导意义。...

-  12-1 垃圾回收概述
-  12-2 引用计数法详解
-  12-3 标记清除算法详解
-  12-4 标记压缩算法详解
-  12-5 复制算法详解
-  12-6 分代算法详解
-  12-7 垃圾收集器总体分类
-  12-8 垃圾收集器详细分类
-  12-9 串行垃圾收集器详解
-  12-10 并行垃圾收集器-ParNew详解
-  12-11 并行垃圾收集器-Parallel详解
-  12-12 并发垃圾收集器-CMS详解
-  12-13 G1垃圾收集器详解
-  12-14 垃圾回收机制知识点复盘

内存池是一把双刃剑，如果使用不当，很容易带来内存泄漏和内存非法引用等问题，如何利用好池化技术，重用连接，防止反复申请和释放连接，提高连接使用率。本章将通过多个内存池使用不当导致的内存泄漏的案例做出分析，详细介绍ByteBuf的申请和释放策略，以及Netty内存池的工作原理及优化方案。通过对ByteBuf的故障排查案例...

- ##### **第14章 专题五： Netty调优-并发篇【难度：☆☆☆☆实用性：☆☆☆ 高手过招】**

为了提升性能，如果用户实现的ChannelHandler包含复杂或者可能导致同步阻塞的业务逻辑，例如数据库操作，同步的第三方服务调用等。此时往往需要通过线程池来提升并发处理能力，线程池的策略直接关系到netty的性能，如果使用不当将造成netty性能急剧下降。netty的高并发涉及ChannelHandler方法调用和NioEventLoop线程，以及...

- ##### **第15章 专题六：Nginx调优-参数优化**

Nginx的高效原理和其他组件其实都是差不多的，一般都是从线程模型角度来分析，nginx同样是基于高效的事件驱动模型。除了高效的网络模型之外，nginx还借助于其他辅助的技术实现高性能。例如：压缩，fastCGI,缓存等等。本章基于上述知识点对nginx进行全面的优化。 ...



# **个人简介：**

大家好，我是smart哥，是一名有10余年经验的互联网老兵，历经从传统软件公司到大型互联网公司的洗礼，早年在中兴通讯等大型通信公司担任项目leader，后随着互联网的崛起，先后在前美团支付等大型互联网公司担任架构师。对互联网架构底层技术有相当的研究和独特的见解，在多个领域有着丰富的实战经验。希望我的课程能够给大家带来技能上的飞跃，在升职加薪道路上飞奔。



# **课程简介：**

一句话简介：6+1模式全方位掌握《全技术栈性能调优》，晋升救火队长，实现加官进爵。

# **完整简介：**

本课程的6+1模式是指课程涵盖的【mysql优化】，【tomcat优化】，【jvm优化】，【垃圾回收】，【netty优化】，【nginx优化】这6大专题+【性能优化高频面试集锦】1项面试复盘。



1. 动态源码分析及调试

市面上的性能调优课程，大多数都是教你怎么去调优，但是不会深追为什么要这样调。而在本课程中，例如【tomcat优化】这个专题，针对每一个调优点都会动态的从源码角度进行分析，特别是从线程和内存这两个方面进行源码分析，这两个方面是制约性能的最大因素。



案例重演

【netty优化】专题部分运用了大量的灾难案例进行重演，复现故障，从多个角度分析问题发生的必然性，并跟踪源码进行深入分析，给出最佳优化实践。运用实际案例来演示许多自以为正确的代码其实并不正确，在运行一段时间之后必然发生异常，对异常的分析也会从线程和内存两个方面进行分析，找出故障点之后再从源码角度分析故障原因。



1. 学以致用

在对tomcat或者netty做性能或者故障排查阶段，会直接使用【jvm优化】部分讲解的各种工具和命令现学现用，排查依然是从cpu，线程，内存，gc等角度进行，这也是我们在实际工作中遇到问题时候的排查步骤。



1. 源码分析，别开生面

从最底层源码层面来分析性能是本课程一大特色，在源码分析层面也和市面上其他机构的课程不一样，其他机构的源码分析课程基本上都是静态分析，所谓静态分析就是从main函数开始，代码逐行分析，一路下去。就拿tomcat来说，本课程别开生面的从tomcat的重要线程的源码开始分析tomcat工作原理。



# **课程能学到什么？**

本课程通过源码及灾难案例重演让大家能够真正理解各大组件的底层实现原理，让大家对调优做到心中有数，有的放矢。

从【tomcat调优】课程中大家可以深入了解线程模型对性能的重要性，我们对线程模型孜孜不倦的追求就是为了解决IO的读写效率问题，这就回到了高效性能的本质-高效的性能取决于高效的IO。那么tomcat如何解决IO性能问题呢？其基石就是连接器通道，四大通道的演变和迭代过程就是tomcat性能化茧成蝶的过程。

从【jvm调优】课程中我们可以学到到对于jvm调优的详细步骤和两个重要的依据：线程和内存。首先，dump线程，我们可以查找性能问题是不是出在线程阻塞等方面；其次，dump内存，我们可以查找占用内存最大区域的对象有哪些？有没有频繁的FULL GC？是不是因为这些对象回收不掉引起的内存泄漏？经过以上步骤的排查我们就可以找出制约jvm性能的关键。

从【netty调优】课程中我们从实际案例中可以学到一些习以为常的代码其实有很多都是错误的，这些代码100%会引发netty各种线程积压和内存泄漏问题，从而造成netty性能急剧下降或者直接就是发生故障。通过灾难复现及剖析大家可以学会netty中正确的编码姿势（netty中的故障绝大多数也是高并发时的积压及内存泄漏问题）。

从【mysql调优】课程中我们可以学到排查问题sql的一般步骤及思路，面对各类sql语句，我们都能掌握其背后的工作原理及优化方案，在mysql的最终优化奥义中我们提及对mysql的优化本质其实也是解决它的IO读写能力（我们提出了增加redis和mq的方案）。这和我们对tomcat等其他组件的调优有着共同的目标和本质-解决一切IO问题。

在【nginx调优】课程中我们可以学到linux操作系统级别的调优，主要也是从线程模型，cpu调度，内存等方面入手来对常见的参数进行调优。终上所述调优课程都有一个共同点-调优的层面都是一样的（线程，内存，cpu），通过本课程的学习，提升了大家对调优本质的认知。



# **通过学习本课程，我们可以学习到：**

1. 如何通过修改配置文件对tomcat进行调优？
2. 如何通过jmeter对tomcat进行压测？
3. tomcat配置文件中的调优项分别在源码中位置和作用。
4. tomcat中的10大线程工作原理。
5. tomcat高性能关键线程之-Acceptor线程工作原理
6. tomcat高性能关键线程之-Poller线程工作原理
7. tomcat高性能关键线程之-Exec线程工作原理
8. tomcat线程栈中的线程是如何配合从而保证tomcat高性能的？
9. tomcat是如何体现其reactor线程模型的本质的？
10. tomcat中NIO通道中的关键组件及工作原理。
11. tomcat中的NIO通道是如何保证tomcat高性能的？
12. tomcat中的BIO通道的劣势？
13. 比较tomcat中的BIO和NIO通道。
14. tomcat中NIO2通道中的关键组件及工作原理。
15. tomcat中NIO2通道是如何保证tomcat高性能的？
16. tomcat中APR通道中的关键组件及工作原理。
17. tomcat中APR通道是如何保证tomcat高性能的？
18. tomcat中的sendfile（零拷贝）机制。
19. tomcat中sendfile机制在NIO通道中的实现。
20. tomcat中sendfile机制在APR通道中的实现。
21. tomcat中compression（压缩）机制对性能的影响。
22. tomcat中compression（压缩）机制和sendfile（零拷贝）机制的互斥性。
23. tomcat中的deferAccept属性配置与实现。
24. tomcat中keep-alive的实现逻辑及优化
25. 如何通过调整和tomcat相关的JVM参数进行优化
26. 如何排除筛选有问题的sql？
27. 如何通过jmeter来压测mysql？
28. 如何解读MySQL慢查询日志？
29. 如何使用mysqldumpslow来分析慢查询日志？
30. 如何使用pt-query-digest来分析慢查询日志？
31. 如何使用pt-query-digest来查找三大有问题的sql？
32. 如何解读pt-query-digest分析结果？
33. 如何解读explain分析SQL执行计划？
34. mysql中join的原理及优化思路及案例
35. mysql中order by的原理及优化思路及案例
36. mysql中group by的原理及优化思路及案例
37. mysql中distinct的原理及优化思路及案例
38. mysql中的索引原理
39. mysql中索引失效案例
40. mysql优化的终级奥义
41. mysql中的表结构优化思路及案例
42. JVM的参数标准参数和非标准参数的设置
43. jmap工具的使用和分析
44. jhat工具的使用和分析
45. mat工具的使用和分析
46. jstat工具的使用和分析
47. jvm内存模型的分析
48. 内存溢出的定位与分析
49. 线程死锁的定位与分析
50. jvisualvm工具的使用和分析
51. GC的概念
52. GC的常见算法分析
53. GC常见垃圾收集器原理分析及演示
54. GC Easy可视化工具的使用及分析结果解读
55. 不同的netty线程模型比较分析
56. 案例演示netty意外退出及优化
57. Netty优雅退出原理和源码分析
58. Netty客户端连接池泄漏原理及优化
59. Netty内存池泄漏原因及优化
60. ByteBuf故障排查及优化
61. Netty发送队列积压原因及优化
62. Netty实现api网关高并发性能波动原因及优化
63. Netty之Channelhandler并发安全陷阱
64. Netty之ChannelHandler并发失效及优化
65. Netty之DefaultEventExecutor源码解析
66. Netty之NioEventLoop线程夯住及优化
67. Netty性能统计误区演示
68. Netty事件触发策略使用不当案例解析
69. Netty流量整形案例解析
70. Nginx是如何做到高性能和高可扩展的？
71. Nginx运行工作进程数量优化。
72. Nginx运行CPU亲和力优化。
73. Nginx最大打开文件数优化
74. Nginx事件处理模型优化
75. 如何开启nginx高效传输模式
76. Nginx连接超时时间优化
77. Nginx之fastcgi调优实践
78. Nginx之gzip调优实践
79. Nginx之expires缓存调优实践
80. Nginx之防盗链
81. Nginx之内核参数优化
82. Nginx之系统连接数的优化
