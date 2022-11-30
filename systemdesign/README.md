# 系统设计
常用的系统设计方案

## 基础知识
- [Difference between sequential write and random write](https://stackoverflow.com/questions/2100584/difference-between-sequential-write-and-random-write)
- [何为微服务、网关、服务发现/注册？](https://mp.weixin.qq.com/s/EFx-9H5SoquRgTLBzqqa5Q)

## 系统设计方案
- [高可用性系统在大众点评的实践与经验](https://tech.meituan.com/2016/02/04/high-availability-systems-dianping.html)
- [双缓冲机制](https://blog.csdn.net/farmwang/article/details/70054360)
- [使用双buffer无锁化](https://cloud.tencent.com/developer/article/1196271)
- [多线程异步日志系统，高效、强悍的实现方式-双缓冲](https://bbs.huaweicloud.com/blogs/308467)
- [架构与思维：设计容量，到底有多重要 ？](https://mp.weixin.qq.com/s?__biz=MzIzNjM3MDEyMg==&mid=2247515369&idx=2&sn=8ee16447b7b27ec9db0c26924c68f390&chksm=e8da1d4cdfad945ac669b736c2b539320d4350d9861b26dc304f980584ab68ae0b3738e9e606&scene=132#wechat_redirect)
- [面试限流、熔断、高可用，好多人一脸懵！](https://mp.weixin.qq.com/s/mGmda20aS1riuRZvovhiaw)
- [高可用Redis服务架构分析与搭建](https://mp.weixin.qq.com/s/c7KwoEuTSuwzm6lcNijWPQ)
- [【超赞】技术架构的战略和战术原则](https://mp.weixin.qq.com/s/O9EOqzyxp8uBjHqMKeFgIg)
- [一文详解微服务架构](https://www.cnblogs.com/skabyy/p/11396571.html)
- [为什么微服务一定要有网关？](https://cloud.tencent.com/developer/article/1142463)
- [基于redis实现的点赞功能设计](https://www.cnblogs.com/liuyupen/p/14015407.html)
- [无锁队列的实现](https://coolshell.cn/articles/8239.html)

## 性能优化
- [内存优化总结tcmalloc与jemalloc-转载](https://zhuanlan.zhihu.com/p/163764191)
- [磁盘IO性能优化](https://mp.weixin.qq.com/s/ZpNQL7n9RoQ3cZCq_qVMXg)
- [MySQL 数据库连接数 设置多少合适？如何设置呢？](https://www.huaweicloud.com/zhishi/edits-15756286.html)
- [记一次性能优化，单台4核8G机器支撑5万QPS](https://mp.weixin.qq.com/s/5oxix88PCkAJfek6x0nvnw)
- [后台服务架构高性能设计之道](https://mp.weixin.qq.com/s/hsH7LMBEDGe_df9UbfOvbQ)
- [高并发服务的几条优化经验](https://mp.weixin.qq.com/s/oUsqQAThoo1mbvMp3WgH8g)
- [如何提升CPU的缓存命中率？](https://zhuanlan.zhihu.com/p/209181629)
- [Make your programs run faster by better using the data cache](https://johnysswlab.com/make-your-programs-run-faster-by-better-using-the-data-cache/#tips)
- [Multiple threads and CPU cache](https://stackoverflow.com/questions/4802565/multiple-threads-and-cpu-cache)

## 内存管理
- [一篇文章彻底讲懂malloc的实现（ptmalloc）](https://blog.csdn.net/songchuwang1868/article/details/89951543)
- [图解 TCMalloc](https://zhuanlan.zhihu.com/p/29216091)
- [TCMalloc内存分配原理简介](https://www.cnblogs.com/jiujuan/p/13869547.html)
- [TCMalloc解密（一）](https://zhuanlan.zhihu.com/p/51432385)
- [TCMalloc解密（二）](https://zhuanlan.zhihu.com/p/51433411)
- [TCMalloc解密（三）](https://zhuanlan.zhihu.com/p/51433881)
- [「netty源码」12 他山之石：高性能内存分配器 jemalloc 基本原理](https://mp.weixin.qq.com/s/uuCQ4Rri3h88aHO70SZnOQ)
- [jemalloc 源码分析](https://youjiali1995.github.io/allocator/jemalloc/#%E8%83%8C%E6%99%AF%E7%9F%A5%E8%AF%86)
- [ptmalloc、tcmalloc与jemalloc对比分析](https://www.cyningsun.com/07-07-2018/memory-allocator-contrasts.html#tcmalloc)


## 线上问题排查
- [系统CPU飙高排查](https://www.zhihu.com/question/344856364/answer/2435969658)
- [查看线程栈信息](https://blog.csdn.net/swj9099/article/details/82048448)
- [线上服务内存OOM问题定位三板斧](https://blog.csdn.net/jjavaboy/article/details/77773754)
- [能解决 80% 故障的排查思路](https://mp.weixin.qq.com/s/kL2l-0CsZ_KXrVn8Av2d5g)


## RPC
- [如何优雅地重试](https://mp.weixin.qq.com/s/6IkTnUbBlHjM3GM_bT35tA)
- [gRPC and Deadlines](https://grpc.io/blog/deadlines/)
- [gRPC服务发现&负载均衡](https://segmentfault.com/a/1190000008672912)
- [gRPC的重试策略](https://zhuanlan.zhihu.com/p/73747546)
- [高并发下重启服务，接口调用老是超时，你有什么解决办法？](https://cloud.tencent.com/developer/article/1768020)
- [Performance Best Practices](https://grpc.io/docs/guides/performance/)
- [protobuf为什么那么快](https://www.jianshu.com/p/72108f0aefca)
- [高效的数据压缩编码方式 Protobuf](https://halfrost.com/protobuf_encode/)
- [Protocol Buffers 编码](https://taoshu.in/pb-encoding.html)

## brpc
- [Brpc 服务端源码分析](https://juejin.cn/post/7134287973066997797)
- [brpc源码解析](https://blog.csdn.net/wxj1992/category_11267957.html)

## 设计模式
- [原型模式](https://www.runoob.com/design-pattern/prototype-pattern.html)

## 业界系统设计案例
- [短视频个性化Push工程精进之路](https://mp.weixin.qq.com/s/BsMQ1alfSdfaHWkM9K2Vzw)
- [“一天宕机三次”，为什么高并发这么难？](https://mp.weixin.qq.com/s/g4c7ovftzkTYRSfuRtgn7A)

