# 数据库
数据库知识汇总

## 关系型数据库

### 数据库基础
- [数据库系统原理](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E6%95%B0%E6%8D%AE%E5%BA%93%E7%B3%BB%E7%BB%9F%E5%8E%9F%E7%90%86.md#%E5%85%ADnext-key-locks)
- [如何理解关系型数据库的常见设计范式？](https://www.zhihu.com/question/24696366/answer/29189700)
- [深入浅出数据库索引原理](https://zhuanlan.zhihu.com/p/23624390)
- [MySQL索引背后的数据结构及算法原理](http://blog.codinglabs.org/articles/theory-of-mysql-index.html)
- [MYSQL-索引](https://segmentfault.com/a/1190000003072424)
- [Hash索引](https://www.jianshu.com/p/1c307a1e17fd)
- [一张图搞懂MySQL的索引失效](https://segmentfault.com/a/1190000021464570)
- [MySQL-当前读、快照读、MVCC](https://www.jianshu.com/p/eb3f56565b42)
- [A Visual Explanation of SQL Joins](https://blog.codinghorror.com/a-visual-explanation-of-sql-joins/)

### MySQL
- [查找算法 – B树 B+树](https://www.hadoop1024.com/2018/08/28/b-tree/)
- [数据库事务的四大特性（ACID）以及事务的隔离级别](https://blog.csdn.net/qq_25448409/article/details/78110430)
- [MySQL事务隔离级别](https://mp.weixin.qq.com/s/WIqoR0-l7h9SObIzmGDatQ)
- [详解 MySql InnoDB 中意向锁的作用](https://juejin.im/post/5b85124f5188253010326360)
- [MySQL 分库分表方案，总结的非常好](https://juejin.im/entry/5b5eb7f2e51d4519700f7d3c)
- [Database Structure and Design Tutorial](https://www.lucidchart.com/pages/database-diagram/database-design)
- [MySQL MVCC机制](https://juejin.im/post/5c68a4056fb9a049e063e0ab)
- [乐观锁与悲观锁](https://zhuanlan.zhihu.com/p/40211594)
- [innodb redo undo](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651961444&idx=1&sn=830a93eb74ca484cbcedb06e485f611e&chksm=bd2d0db88a5a84ae5865cd05f8c7899153d16ec7e7976f06033f4fbfbecc2fdee6e8b89bb17b&scene=21#wechat_redirect)
- [MySQL最左前缀匹配](https://blog.csdn.net/SkySuperWL/article/details/52583579)
- [MyISAM 和 INNODB的区别(注：innodb从5.6以后支持全文索引)](https://blog.csdn.net/weixin_30834019/article/details/97562340?depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromBaidu-3&utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromBaidu-3)
- [MySQL 对于千万级的大表要怎么优化？](https://www.zhihu.com/question/19719997/answer/81930332)
- [如何保障mysql和redis之间的数据一致性？](https://zhuanlan.zhihu.com/p/91770135)
- [MySQL中的几种日志了解](https://www.cnblogs.com/myseries/p/10728533.html)
- [游标的作用和概念](https://www.cnblogs.com/WayneZeng/p/3352230.html)
- [SQL中Truncate的用法](https://www.cnblogs.com/zhoufangcheng04050227/p/7991759.html)
- [InnoDB Gap锁](https://amsimple.com/blog/article/72.html)
- [为什么要使用自增ID作为主键](https://www.cnblogs.com/lanqi/p/10185172.html)
- [mysql日志系统之redo log和bin log](https://www.jianshu.com/p/4bcfffb27ed5)
- [mysql主从延迟](https://zhuanlan.zhihu.com/p/434300434)
- [缓冲池(buffer pool)，这次彻底懂了！！！](https://juejin.cn/post/6844903874172551181)
- [写缓冲(change buffer)，这次彻底懂了！！！](https://juejin.cn/post/6960555140189257741)
- [redolog与binlog为什么需要两阶段提交？](https://cloud.tencent.com/developer/article/1790507)
- [MySQL 性能优化神器 Explain 使用分析](https://segmentfault.com/a/1190000008131735)

### TiDB
- [三篇文章了解 TiDB 技术内幕 - 说存储](https://cn.pingcap.com/blog/tidb-internal-1)
- [三篇文章了解 TiDB 技术内幕 - 说计算](https://cn.pingcap.com/blog/tidb-internal-2)
- [三篇文章了解 TiDB 技术内幕 - 谈调度](https://cn.pingcap.com/blog/tidb-internal-3)
- [Embracing NewSQL: Why We Chose TiDB over MongoDB and MySQL](https://www.pingcap.com/case-study/embracing-newsql-why-we-chose-tidb-over-mongodb-and-mysql/)

  
## 非关系型数据库
- [Explanation of BASE terminology](https://stackoverflow.com/questions/3342497/explanation-of-base-terminology)

### HBase
- [HBase Java API Demo](https://blog.csdn.net/zhu_tianwei/article/details/48829125)
- [五分钟轻松了解Hbase列式存储](https://juejin.cn/post/6844903750012780558)
- [LSM树 VS B+树](https://blog.csdn.net/iteye_14608/article/details/82507468?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-4&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-4)


### MongoDB
- [Aggregations in MongoDB by Example](https://www.compose.com/articles/aggregations-in-mongodb-by-example/)

### Redis
- [redis系列：分布式锁](https://juejin.im/post/5b737b9b518825613d3894f4)
- [Redis高可用方案-哨兵与集群](https://blog.csdn.net/sunhuiliang85/article/details/78361211)
- [HyperLogLog 算法的原理讲解以及 Redis 是如何应用它的](https://juejin.im/post/5c7900bf518825407c7eafd0)
- [缓存雪崩、缓存穿透、缓存预热、缓存更新、缓存降级等问题](https://mp.weixin.qq.com/s?__biz=MzI1NDQ3MjQxNA==&mid=2247485464&idx=1&sn=8d690fc6f878aadf75977aa7e76cfd08&chksm=e9c5f1a9deb278bf512d8b40c30240d0168cdf2cf02142ee913bc11ec39637ca380a4dad524b&scene=21#wechat_redirect)
- [Redis官方亲儿子，RedisCluster是怎么一回事](https://baijiahao.baidu.com/s?id=1643461909684941861&wfr=spider&for=pc)
- [Redis缓存穿透和缓存雪崩](https://baijiahao.baidu.com/s?id=1655304940308056733&wfr=spider&for=pc)
- [Redis 排行榜 相同分数根据时间优先排行](https://blog.csdn.net/zeus_9i/article/details/51025175)
- [说说持久化机制及RDB/AOF应用场景分析！](https://cloud.tencent.com/developer/article/1828400)
- [Redis为什么这么快？Redis的线程模型与Redis多线程](https://mp.weixin.qq.com/s/WbaHoVIY_RayCnDx06lsfw)
- [发现并处理Redis的大Key和热Key](https://help.aliyun.com/document_detail/353223.html)
- [Redis的事务满足原子性吗？](https://www.51cto.com/article/681240.html)
- [如何保证缓存与数据库双写时的数据一致性？](https://mp.weixin.qq.com/s/uL1EW1W2mwrzAbtFNyAruw)
- [Redis 内存优化在 vivo 的探索与实践](https://mp.weixin.qq.com/s/DII_XLQ5hrLtOWH2YoU0Cw)
- [Redis10大性能优化策略](https://mp.weixin.qq.com/s/A_cAHMTRM-BsmwBoq_CK6g)

### Elasticsearch
- [Elasticsearch系列---初识Elasticsearch](https://juejin.cn/post/6844903994054148110)
