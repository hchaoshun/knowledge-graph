# 推荐系统
推荐系统知识汇总

- [一文带你掌握推荐系统](http://www.chanpin100.com/article/108436)
- [推荐系统 I 关于推荐策略的整理与思考](https://www.iambigboss.top/post/49420_1_1.html)
- [23张图，带你入门推荐系统](https://mp.weixin.qq.com/s/d6bCGT8B4h5pfI77TvLicA)
- [推荐系统架构与算法流程详解](https://mp.weixin.qq.com/s/xfzUJupEG2C2_6Wl1qxaDA)
- [电商搜索全链路复盘](https://mp.weixin.qq.com/s/R40TRBGD9J_WgXIbBaDoGw)
- [完整的推荐系统架构设计](https://xie.infoq.cn/article/e1db36aecf60b4da29f56eeb4)
- [推荐系统技术综述](https://mp.weixin.qq.com/s/e9xjwefYk2toN9CGK5uPXg)
- [推荐系统魔术手: 推荐中的偏差与消偏策略总结](https://mp.weixin.qq.com/s/e8Axw70TaoDeqlYgbTua8g)

## 算法
- [推荐系统系列之隐语义模型](https://www.jianshu.com/p/7b6bb28c1753)

## 机器学习平台
- [机器学习平台建设](https://microsoft.github.io/ai-edu/%E5%AE%9E%E8%B7%B5%E6%A1%88%E4%BE%8B/B10-%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E5%B9%B3%E5%8F%B0%E5%BB%BA%E8%AE%BE/)
- [一篇文章读懂什么是机器学习平台](https://www.woshipm.com/ai/4872402.html)
- [云原生深度学习平台 PAI-DLC 架构设计](https://mp.weixin.qq.com/s/73JWA2cmY2JPszE5CX1unQ)

## 推荐工程问题
- [vivo 短视频推荐去重服务的设计实践](https://www.51cto.com/article/705399.html)

## 推荐系统模型
### 传统模型
- [FM（Factorization Machines）的理论与实践](https://zhuanlan.zhihu.com/p/50426292)
- [谈谈因子分解机模型（FM）](https://liam.page/2019/03/25/Factorization-Machine/)
(本质是二阶多项式核wij是xi和xj共有， 完全由xi * xj决定，xi和xj只要有一个值为0，wij就总是0。
<vi, vj> 两个参数是分开的，不完全由xi * xj决定，只要有一个xi * xk 不为0, vi就能学到东西，同理vj也一样，
这样即使 xi * xj 为0， vi, vj也能学习更新)

## 产品
- [Feed 是什么](https://zhuanlan.zhihu.com/p/31440655)
- [CTR预估解析](https://www.meihua.info/a/72378)
- [关于UGC、PGC、OGC三者详细区别！](https://zhuanlan.zhihu.com/p/35596590)
- [灰度测试是什么意思](http://www.appadhoc.com/blog/what-is-grey-release/)
- [如何清楚易懂的解释“UV和PV＂的定义？](https://www.zhihu.com/question/20448467)
- [转化率](https://wiki.mbalib.com/wiki/%E8%BD%AC%E5%8C%96%E7%8E%87#:~:text=%E8%BD%AC%E5%8C%96%E7%8E%87%E6%98%AF%E6%8C%87%E5%9C%A8,%E7%82%B9%E5%87%BB%E9%87%8F%EF%BC%89%C3%97100%25%E3%80%82&text=%E6%8C%87%E6%A0%87%E6%84%8F%E4%B9%89%EF%BC%9A%E8%A1%A1%E9%87%8F%E7%BD%91%E7%AB%99%E5%86%85%E5%AE%B9,%E4%BB%A5%E5%8F%8A%E7%BD%91%E7%AB%99%E7%9A%84%E5%AE%A3%E4%BC%A0%E6%95%88%E6%9E%9C%E3%80%82)
- [数据指标有哪些？什么是好的数据指标？](http://www.woshipm.com/data-analysis/3747471.html)
- [小视频向左，短视频向右：快手们时长限制背后的逻辑](http://www.woshipm.com/it/813398.html)
- [从狂热到理性：大模型训练三堵墙，一场少数人的游戏 | 钛媒体深度](https://mp.weixin.qq.com/s/mWW3dcpyp9BuUs0XVUMg9A)

## 特征工程
- [机器学习之特征工程](https://blog.csdn.net/Dream_angel_Z/article/details/49388733)
- [Feature extraction](https://en.wikipedia.org/wiki/Feature_extraction)
- [美团外卖特征平台的建设与实践](https://tech.meituan.com/2021/03/04/featureplatform-in-mtwaimai.html)
- [Uber 机器学习平台实践](https://www.infoq.cn/article/ptie38l08imqcznhh3ym)
- [特征平台（Feature Store）综述：序论篇](https://zhuanlan.zhihu.com/p/406897374)
- [工业界推荐系统怎么做特征？](https://www.zhihu.com/question/419906651/answer/1459124132)
- [推荐系统特征工程高级技巧总结](https://mp.weixin.qq.com/s/NzbrfI9h_vjllUCkDyKadg)
- [机器学习中的数据清洗与特征处理综述](https://tech.meituan.com/2015/02/10/machinelearning-data-feature-process.html)
- [特征平台：定义、架构、工作流程和开源实现概述](https://mp.weixin.qq.com/s/fdtaDiMmIZosTJp615hK9Q)


## 用户画像
- [终于有人把用户画像的流程、方法讲明白了](https://maimai.cn/article/detail?fid=1555064528&efid=rLyx_R8kghLbng2YFJ_Z-Q&share_channel=10&use_rn=1&_share_channel=dingtalk)
- [王志杰：如何构建好的用户画像？](https://mp.weixin.qq.com/s/9sHusGBlh6cN2-GG74i5dw)
- [网易严选DMP标签系统建设实践](https://mp.weixin.qq.com/s/1nN7wy42jYEshokr0nyaxA)

## 召回
- [腾讯万字长文——推荐系统 embedding 技术实践总结](https://zhuanlan.zhihu.com/p/328481154)
- [Faiss: A library for efficient similarity search](https://engineering.fb.com/2017/03/29/data-infrastructure/faiss-a-library-for-efficient-similarity-search/)
- [亿级向量相似度检索库Faiss 原理+应用](https://mp.weixin.qq.com/s/EtnTDkaXwVNMXKagIw9JCg)
- [Hierarchical Navigable Small Worlds (HNSW)](https://www.pinecone.io/learn/hnsw/)
- [「向量召回」相似检索算法——HNSW](https://mp.weixin.qq.com/s/dfdNj9CZ3Kj2UwDr9PQcVg)
- [推荐系统中的召回算法——HNSW[1]](https://mp.weixin.qq.com/s/cpL69BE2AU7ODYpKw6c9YQ)
- [推荐系统中的召回算法——HNSW[2]](https://mp.weixin.qq.com/s?__biz=Mzg5MzczMjc3Nw==&mid=2247484999&idx=1&sn=7d3b80b6e95d6b51bb0937992cbdb103&chksm=c02b1481f75c9d978bfc90e9763ed8d271e1e516c3fe311674d4fcd34beda81a625f1cd3800a&cur_album_id=2364738455672356865&scene=189#wechat_redirect)
- [赋能阿里多业务场景，达摩院自研向量检索引擎 Proxima 公开](https://damo.alibaba.com/events/112?lang=zh)
- [推荐系统召回四模型之：全能的FM模型](https://zhuanlan.zhihu.com/p/58160982)
- [闲聊推荐系统中的曝光过滤机制](https://mp.weixin.qq.com/s?__biz=MzI2MDU3OTgyOQ==&mid=2247500277&idx=1&sn=17d7277c0e7c664b0750c3020a8e6d47&chksm=ea65096fdd1280797e63d66fe023a3ad4bcb693afbdfe44106872a089e8baf8228e63795ff68&scene=21#wechat_redirect)
- [SENet双塔模型：在推荐领域召回粗排的应用及其它](https://zhuanlan.zhihu.com/p/358779957)
- [推荐系统的中的正排和倒排](https://blog.csdn.net/weixin_44441131/article/details/115796765)
- [「召回层」回顾一下传统召回方法](https://www.modb.pro/db/103252)
- [「召回层」深度召回中的i2i](https://www.modb.pro/db/103251)
- [「召回层」深度召回中的u2i](https://www.modb.pro/db/103250)
- [召回模型中的负样本构造](https://zhuanlan.zhihu.com/p/358450850)

## 个性化排序
- [个性化推荐排序详解](https://www.jianshu.com/p/1fd2b97fc765)
- [推荐系统评测指标](https://blog.csdn.net/checkche/article/details/84673650?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-4.channel_param&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-4.channel_param)
- [粗排拟合精排](https://zhuanlan.zhihu.com/p/352961688)
- [推荐系统全链路（2）召回粗排精排-级联漏斗上篇](https://mp.weixin.qq.com/s?__biz=MzI2MDU3OTgyOQ==&mid=2247502357&idx=1&sn=b79aab51a1271b7702942ed8cb6914e4&chksm=ea65028fdd128b993a373ee098419f95444b0e92f4e6c5508c9b5e6c0ea498c4b59cec351993&cur_album_id=1446013116592308224&scene=189#rd)
- [推荐系统全链路（4）打压保送重排策略-拍不完的脑袋](https://mp.weixin.qq.com/s?__biz=MzI2MDU3OTgyOQ==&mid=2247502371&idx=1&sn=e6543ac1e4cda691300e07c82737c750&chksm=ea6502b9dd128baf46c2226e6e80d448390cacb4b5cb3280a7be17c9100cc3f9f3c8b5f38f07&cur_album_id=1446013116592308224&scene=189#rd)

## AB Test
- [AB测试](https://baike.baidu.com/item/AB%E6%B5%8B%E8%AF%95)
- [一文搞懂AB Testing的分层分流](http://www.woshipm.com/pd/1080730.html)
- [数据埋点](https://www.zhihu.com/question/36411025)

## 工程常识
- [第95个百分位（95th percentile）是什么概念？](https://www.zhihu.com/question/20575291)
- [推荐系统的实时性](https://zhuanlan.zhihu.com/p/74813776)
- [线上线下效果一致性杂谈](https://mp.weixin.qq.com/s/Lwnl5W2ZS3CjxrA46yMwyw)
- [线下指标涨为什么没带来线上指标提升？](https://mp.weixin.qq.com/s/sOoBQqmXVypOBqiXRbRA-A)

## 数据仓库
- [数据库 与 数据仓库的本质区别是什么？](https://www.zhihu.com/question/20623931)
- [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load#:~:text=In%20computing%2C%20extract%2C%20transform%2C,than%20the%20source(s).)
- [Airflow快速学习入门](https://segmentfault.com/a/1190000039923621?utm_source=tag-newest)
- [什么是实时数仓](https://mp.weixin.qq.com/s/8SdXPbntu6IUXZxLf9kGcw)

## 业界推荐系统
- [小红书 | 高时效召排推荐架构](https://mp.weixin.qq.com/s/svORhpgwiOauwEfUAeM-_Q)
- [微信「看一看」 推荐排序技术揭秘](https://www.jiqizhixin.com/articles/2020-07-21-16)
- [推荐系统中模型训练及使用流程的标准化](https://mp.weixin.qq.com/s/NrPWwx1N68UH6RmnJi1uGw)
- [蜻蜓FM信息流推荐探索与实践](https://mp.weixin.qq.com/s/NTwW1CvnvRJjxHoUjWxAmA)
- [全民 K 歌内容挖掘与召回](https://www.infoq.cn/article/Qg3uV88ghB0qL09G7o54?utm_source=related_read&utm_medium=article)
- [美图个性化推荐的探索与实践](https://www.infoq.cn/article/XuzDM0DBpb8fasLpYVFC?utm_source=related_read_bottom&utm_medium=article)
- [微博推荐算法实践与机器学习平台演进](https://zhuanlan.zhihu.com/p/447415588)
- [美团搜索粗排优化的探索与实践](https://mp.weixin.qq.com/s/L-ut5sH7VjaVk3IuR7ZRmw)
- [详解闲鱼推荐系统（长文收藏）](https://mp.weixin.qq.com/s/ymedjPLZXYXZQ3A4NUnFsQ)
- [AI 训练加速原理解析与工程实践分享 | Q推荐](https://mp.weixin.qq.com/s/6uw8Su4dOrJl63lQgqbrJw)
- [AI 推理加速原理解析与工程实践分享 | Q推荐](https://mp.weixin.qq.com/s/aMW-nHcugrDQLnZCxdAKOg)
- [解密游戏推荐系统的建设之路](https://mp.weixin.qq.com/s/WU5BvODf3oc_1UAsZ3fQ8A)
- [亿级用户，腾讯看点信息流推荐系统的架构挑战](https://www.cnblogs.com/qcloud1001/p/13841020.html)
- [降本提效，贝壳搜索推荐架构统一之路](https://www.cnblogs.com/qcloud1001/p/13841056.html)

## 广告
- [计算广告生态概述](https://www.zhihu.com/column/fuliucansheng)
- [广告系统架构解密](https://www.infoq.cn/article/1yweyltgti5bigenuklx)
- [Ad Exchange](https://baike.baidu.com/item/Ad%20Exchange/3811429)
- [DSP、ADX、SSP、DMP之间的关系](https://blog.csdn.net/programme_carefree/article/details/72764879)
- [广告归因：是什么和为什么](https://zhuanlan.zhihu.com/p/353558479)
- [不懂归因，也许你广告还没入门](https://zhuanlan.zhihu.com/p/339730526)
- [计算广告与推荐系统有哪些区别？ - 王喆的回答 - 知乎](https://www.zhihu.com/question/19662693/answer/757347092)
- [达观数据：计算广告系统算法与架构综述](https://zhuanlan.zhihu.com/p/60544294)

## 电商
- [电商项目中的 SPU 和 SKU 有什么区别？ 原创](https://blog.51cto.com/u_15287666/3021182)

## 架构
- [超详细：完整的推荐系统架构设计](https://mp.weixin.qq.com/s/kC1zSpBTAlswGBL7pw7cUA)
- [搜索引擎场景下Debug架构设计](https://www.modb.pro/db/190113)
- [旅游推荐系统的演进](https://tech.meituan.com/2017/03/24/travel-recsys.html)

