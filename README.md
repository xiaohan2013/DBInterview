
<p align='center'>
<a href="https://mp.weixin.qq.com/s/YeyAgD52zCadtrdXLxrT9A" target="_blank"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-@%E6%88%91%E4%B8%8D%E6%98%AF%E5%8C%A0%E4%BA%BA-000000.svg?style=flat-square&logo=WeChat">
<a href="https://www.zhihu.com/people/wan-yi-er-89" target="_blank"><img src="https://img.shields.io/badge/%E7%9F%A5%E4%B9%8E-@姚军-000000.svg?style=flat-square&logo=Zhihu"></a>
<a href="https://space.bilibili.com/30639161?spm_id_from=333.1007.0.0" target="_blank"><img src="https://img.shields.io/badge/dynamic/json?color=fb7299&label=%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9&query=%24.data.follower&suffix=%E4%B8%AA%E7%B2%89%E4%B8%9D&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Frelation%2Fstat%3Fvmid%3D30639161"></a>

</p>

# DBInterview
- 数据库内核高频面试题

## 一、P0字典树
- 什么场景下适合使用字典树？
- 有限状态自动机FST了解吗？跟字典树有什么联系？
- 怎么理解的倒排索引？
## 二、P1缓冲池管理
- 可扩展哈希表如何扩容，如何缩容的？
- LRU-K算法的应用场景？
- LRU-K算法相对于LRU算法的优势有哪些？
- 缓冲池的执行流程
- Page Cache的执行流程
- 什么情况下可以用O_Direct
- 如果页的大小为16KB，而磁盘只保证4KB的读写是原子的，刷脏页的时候只刷了部分页进程就崩溃了，怎么处理？
## 三、B+树
- B+树和B树的区别？
- 为什么MySQL使用B+树而不使用B树？
- B树的应用场景有哪些？
- B+树和LSM-Tree的使用场景？LSM-Tree存在的问题有哪些？针对这些问题有什么解决思路？
- B+树并发处理有哪些优化思路？
- Blink树有什么特点？
## 四、查询执行
- 什么是火山模型？
- 为什么要使用火山模型？有什么优点？有什么缺点？缺点从哪些角度进行优化？
- 解释一下左连接和内连接？
- 怎么理解的数据库回表？
## 五、事务管理
- 2PL原理是什么？2PL存在什么问题？如何解决这些问题？
- 如何基于2PL实现的隔离级别？
- 什么是严格两阶段锁（strict-2PL）？
- 什么是强两阶段锁（strong-2PL）?
- 隔离级别有哪些？分别存在什么问题？
- 什么情况下会导致幻读，举个例子？
- 快照隔离存在什么问题？什么是写偏序问题，举个例子？
- 数据库是怎么实现一致性的？
- 项目中所涉及的几种锁介绍一下，怎么理解隔离级别和锁的关系？
- 为什么MySQL使用B+树而不使用B树？
- 死锁问题怎么解决？
- MySQL怎么保证原子性的？
- MySQL的默认隔离级别是什么？可重复读会有什么问题？既然可重复读有幻读问题那MySQL满足了隔离性吗？如果满足了幻读问题如何解决的？如果没满足如何保证的数据一致性？
