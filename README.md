# 《大厂面试指北》

最佳阅读地址：http://notfound9.github.io/interviewGuide/

Github项目主页：https://github.com/NotFound9/interviewGuide

作者博客地址：https://juejin.im/user/5b370a42e51d4558ce5eb969

关注我的公众号"大厂面试"，可以领取《大厂面试指北》的PDF版本，为了方便技术交流，也建了一个技术交流群，欢迎大家扫码加入！（如果下面的图挂了，是你所在的网络访问不了Github域名下的图片，可以去[最佳阅读地址里面看图](http://notfound9.github.io/interviewGuide/#/)，或者是去[gitee的项目主页](https://gitee.com/notfound9/interviewGuide)里面看，谢谢了）

![](http://notfound9.github.io/interviewGuide/static/wdsfsdfsmaster.png)

<figure class="half">

<img src="http://notfound9.github.io/interviewGuide/static/49160c2basfdsf.jpeg" width="30%"/>

<img src="http://notfound9.github.io/interviewGuide/static/image1.jpg" width="30%"/>

</figure>

## 目录

- [首页](README.md)
- [大厂面试系列](docs/BATInterview.md)
  -[【大厂面试01期】高并发场景下，如何保证缓存与数据库一致性？](https://mp.weixin.qq.com/s/hwMpAVZ1_p8gLfPAzA8X9w)
  -[【大厂面试02期】Redis过期key是怎么样清理的？](https://mp.weixin.qq.com/s/J_nOPKS17Uax2zGrZsE8ZA)
  - [【大厂面试03期】MySQL是怎么解决幻读问题的？](https://mp.weixin.qq.com/s/8D6EmZM3m6RiSk0-N5YCww)
  - [【大厂面试04期】讲讲一条MySQL更新语句是怎么执行的？](https://mp.weixin.qq.com/s/pNe1vdTT24oEoJS_zs-5jQ)
* Java
  - [基础](docs/JavaBasic.md)
    - [1.Java中的多态是什么？](docs/JavaBasic.md#Java中的多态是什么？)
    - [2.Java中变量，代码块，构造器之间执行顺序是怎么样的？](docs/JavaBasic.md#java中变量，代码块，构造器之间执行顺序是怎么样的？)
    - [3.final关键字有哪些作用？](docs/JavaBasic.md#final关键字有哪些作用？)
    - [4.Integer类会进行缓存吗？](docs/JavaBasic.md#Integer类会进行缓存吗？)
    - [5.抽象类有哪些特点？](docs/JavaBasic.md#抽象类有哪些特点？)
    - [6.String，StringBuffer和StringBuilder之间的区别是什么？](docs/JavaBasic.md#String，StringBuffer和StringBuilder之间的区别是什么？)
    - [7.编译型编程语言，解释型编程语言，伪编译型语言的区别是什么？](docs/JavaBasic.md#编译型编程语言，解释型编程语言，伪编译型语言的区别是什么？)
    - [8.Java中的访问控制符有哪些？](docs/JavaBasic.md#Java中的访问控制符有哪些？)
    - [9.Java的构造器有哪些特点？](docs/JavaBasic.md#Java的构造器有哪些特点？)
    - [10.Java中的内部类是怎么样的？](docs/JavaBasic.md#Java中的内部类是怎么样的？)
  * 容器
    - [ArrayList和LinkedList](docs/ArrayList.md)
      - [1.ArrayList与LinkedList的区别是什么？](docs/ArrayList.md#ArrayList与LinkedList的区别是什么？)
      - [2.怎么使ArrayList，LinkedList变成线程安全的呢？](docs/ArrayList.md#怎么使ArrayList，LinkedList变成线程安全的呢？)
      - [3.ArrayList遍历时删除元素有哪些方法？](docs/ArrayList.md#ArrayList遍历时删除元素有哪些方法？)
      - [4.ConcurrentModificationException是什么？](docs/ArrayList.md#ConcurrentModificationException是什么？)
      - [5.java容器类的层次是怎么样的？](docs/ArrayList.md#java容器类的层次是怎么样的？)
    - [HashMap和ConcurrentHashMap](docs/HashMap.md)
      - [1.HashMap添加一个键值对的过程是怎么样的？](docs/HashMap.md#HashMap添加一个键值对的过程是怎么样的？)
      - [2.ConcurrentHashMap添加一个键值对的过程是怎么样的？](docs/HashMap.md#ConcurrentHashMap添加一个键值对的过程是怎么样的？)
      - [3.HashMap与HashTable，ConcurrentHashMap的区别是什么？](docs/HashMap.md#HashMap与HashTable，ConcurrentHashMap的区别是什么？)
      - [4.HashMap扩容后是否需要rehash？](docs/HashMap.md#HashMap扩容后是否需要rehash？)
      - [5.HashMap扩容是怎样扩容的，为什么都是2的N次幂的大小？](docs/HashMap.md#HashMap扩容是怎样扩容的，为什么都是2的N次幂的大小？)
      - [6.ConcurrentHashMap是怎么记录元素个数size的？](docs/HashMap.md#ConcurrentHashMap是怎么记录元素个数size的？)
      - [7.为什么ConcurrentHashMap，HashTable不支持key，value为null？](docs/HashMap.md#为什么ConcurrentHashMap，HashTable不支持key，value为null？)
      - [8.HashSet和HashMap的区别？](docs/HashMap.md#HashSet和HashMap的区别？)
      - [9.HashMap遍历时删除元素的有哪些实现方法？](docs/HashMap.md#HashMap遍历时删除元素的有哪些实现方法？)
  - [多线程](docs/JavaMultiThread.md)
    - [1.进程与线程的区别是什么？](docs/JavaMultiThread.md#进程与线程的区别是什么？)
    - [2.进程间如何通信？](docs/JavaMultiThread.md#进程间如何通信？)
    - [3.Java中单例有哪些写法？](docs/JavaMultiThread.md#Java中单例有哪些写法？)
    - [4.Java中创建线程有哪些方式?](docs/JavaMultiThread.md#Java中创建线程有哪些方式?)
    - [5.如何解决序列化时可以创建出单例对象的问题?](docs/JavaMultiThread.md#如何解决序列化时可以创建出单例对象的问题?)
    - [6.悲观锁和乐观锁是什么？](docs/JavaMultiThread.md#悲观锁和乐观锁是什么？)
    - [7.volatile关键字有什么用？怎么理解可见性，一般什么场景去用可见性？](docs/JavaMultiThread.md#volatile关键字有什么用？怎么理解可见性，一般什么场景去用可见性？)
    - [8.sychronize的实现原理是怎么样的？](docs/JavaMultiThread.md#sychronize的实现原理是怎么样的？)
* Redis
  - [基础](docs/RedisBasic.md)
    - [1.Redis是什么？](docs/RedisBasic.md#Redis是什么？)
    - [2.Redis过期key是怎么样清理的？](docs/RedisBasic.md#Redis过期key是怎么样清理的？)
    - [3.Redis为什么是单线程的？](docs/RedisBasic.md#Redis为什么是单线程的？)
    - [4.Redis的性能为什么这么高？](docs/RedisBasic.md#Redis的性能为什么这么高？)
    - [5.Linux中IO模型一共有哪些？](docs/RedisBasic.md#Linux中IO模型一共有哪些？)
    - [6.同步与异步的区别是什么？](docs/RedisBasic.md#同步与异步的区别是什么？)
    - [7.阻塞与非阻塞的区别是什么？](docs/RedisBasic.md#阻塞与非阻塞的区别是什么？)
    - [8.如何解决Redis缓存穿透问题？](docs/RedisBasic.md#如何解决Redis缓存穿透问题？)
    - [9.如何解决Redis缓存击穿问题？](docs/RedisBasic.md#如何解决Redis缓存击穿问题？)
    - [10.如何解决Redis缓存雪崩问题？](docs/RedisBasic.md#如何解决Redis缓存雪崩问题？)
    - [11.如何解决缓存与数据库的数据一致性问题？](docs/RedisBasic.md#如何解决缓存与数据库的数据一致性问题？)
  - [数据结构](docs/RedisDataStruct.md)
    - [1.Redis常见的数据结构有哪些？](docs/RedisDataStruct.md#Redis常见的数据结构有哪些？)
    - [2.谈一谈你对Redis中简单动态字符串的理解？](docs/RedisDataStruct.md#谈一谈你对Redis中简单动态字符串的理解？)
    - [3.谈一谈你对Redis中hash对象的理解？](docs/RedisDataStruct.md#谈一谈你对Redis中hash对象的理解？)
    - [4.谈一谈你对Redis中List的理解？](docs/RedisDataStruct.md#谈一谈你对Redis中List的理解？)
    - [5.谈一谈你对Redis中Set的理解？](docs/RedisDataStruct.md#谈一谈你对Redis中Set的理解？)
    - [6.谈一谈你对Redis中有序集合ZSet的理解？](docs/RedisDataStruct.md#谈一谈你对Redis中有序集合ZSet的理解？)
    - [7.布隆过滤器是什么？](docs/RedisDataStruct.md#布隆过滤器是什么？)
  - [持久化(AOF和RDB)](docs/RedisStore.md)
    - [1.Redis的持久化是怎么实现的？](docs/RedisStore.md#Redis的持久化是怎么实现的？)
    - [2.AOF和RDB的区别是什么？](docs/RedisStore.md#AOF和RDB的区别是什么？)
    - [3.怎么防止AOF文件越来越大？](docs/RedisStore.md#怎么防止AOF文件越来越大？)
    - [4.Redis持久化策略该如何进行选择？](docs/RedisStore.md#Redis持久化策略该如何进行选择？)
  - [高可用(主从切换和哨兵机制)](docs/RedisUserful.md)
    - [1.Redis主从同步是怎么实现的？](docs/RedisUserful.md#Redis主从同步是怎么实现的？)
    - [2.Redis中哨兵是什么？](docs/RedisUserful.md#Redis中哨兵是什么？)
    - [3.客户端是怎么接入哨兵系统的？](docs/RedisUserful.md#客户端是怎么接入哨兵系统的？)
    - [4.Redis哨兵系统是怎么实现自动故障转移的？](docs/RedisUserful.md#Redis哨兵系统是怎么实现自动故障转移的？)
* MySQL
  - [面试题总结](docs/MySQLNote.md)
    - [1.一条MySQL更新语句的执行过程是什么样的？](docs/MySQLNote.md#一条MySQL更新语句的执行过程是什么样的？)
    - [2.脏页是什么？](docs/MySQLNote.md#脏页是什么？)
    - [3.Checkpoint是什么？](docs/MySQLNote.md#Checkpoint是什么？)
    - [4.undo log，redo log，bin log是什么？](docs/MySQLNote.md#undolog，redolog，binlog是什么？)
    - [5.MySQL中的事务是什么？](docs/MySQLNote.md#MySQL中的事务是什么？)
    - [6.MySQL的隔离级别是怎么样的？](docs/MySQLNote.md#MySQL的隔离级别是怎么样的？)
    - [7.MVCC的实现原理是怎么样的？](docs/MySQLNote.md#MVCC的实现原理是怎么样的？)
    - [8.MySQL是怎么解决幻读的问题的？](docs/MySQLNote.md#MySQL是怎么解决幻读的问题的？)
    - [9.MySQL中有哪些锁？](docs/MySQLNote.md#MySQL中有哪些锁？)
    - [10.B树是什么？](docs/MySQLNote.md#B树是什么？)
    - [11.B树与B+树的区别是什么？](docs/MySQLNote.md#B树与B+树的区别是什么？)
    - [12.索引是什么？](docs/MySQLNote.md#索引是什么？)
    - [13.字符串索引和数字类型索引的区别？](docs/MySQLNote.md#字符串索引和数字类型索引的区别？)
    - [14.union和union all的区别是什么？](docs/MySQLNote.md#union和union)
    - [15.Join的工作流程是怎么样的，怎么进行优化？](docs/MySQLNote.md#Join的工作流程是怎么样的，怎么进行优化)
    - [16.聚集索引是什么？](docs/MySQLNote.md#聚集索引是什么？)
    - [17.联合索引是什么？](docs/MySQLNote.md#联合索引是什么？)
    - [18.覆盖索引是什么？](docs/MySQLNote.md#覆盖索引是什么？)
    - [19.哪些情况不要建索引？](docs/MySQLNote.md#哪些情况不要建索引？)
    - [20.主键，唯一性索引，普通索引的区别是什么？](docs/MySQLNote.md#主键，唯一性索引，普通索引的区别是什么？)
    - [21.InnoDB和MyISAM的区别是什么？](docs/MySQLNote.md#InnoDB和MyISAM的区别是什么？)
    - [22.什么是分库分表？](docs/MySQLNote.md#什么是分库分表？)
    - [23.怎么实现跨库分页查询？](docs/MySQLNote.md#怎么实现跨库分页查询？)
    - [24.MySQL主从复制的工作流程是什么样的？](docs/MySQLNote.md#MySQL主从复制的工作流程是什么样的？)
    - [25.char类型与varchar类型的区别？](docs/MySQLNote.md#char类型与varchar类型的区别？)
    - [26.查询数量SELECT Count(*)怎么优化？](docs/MySQLNote.md#怎么优化数量查询？)
    - [27.如何优化MySQL慢查询？](docs/MySQLNote.md#如何优化MySQL慢查询？) 
    - [28.MySQL的join的实现是怎么样的？](docs/MySQLNote.md#MySQL的join的实现是怎么样的？)
  - [慢查询优化实践](docs/MySQLWork.md) 
* JVM
  - [面试题总结](docs/JavaJVM.md)
    - [1.Java内存区域怎么划分的？](docs/JavaJVM.md#Java内存区域怎么划分的？)
    - [2.Java中对象的创建过程是怎么样的？](docs/JavaJVM.md#Java中对象的创建过程是怎么样的？)
    - [3.Java对象的内存布局是怎么样的？](docs/JavaJVM.md#Java对象的内存布局是怎么样的？)
    - [4.垃圾回收有哪些特点？](docs/JavaJVM.md#垃圾回收有哪些特点？)
    - [5.在垃圾回收机制中，对象在内存中的状态有哪几种？](docs/JavaJVM.md#在垃圾回收机制中，对象在内存中的状态有哪几种？)
    - [6.对象的强引用，软引用，弱引用和虚引用的区别是什么？](docs/JavaJVM.md#对象的强引用，软引用，弱引用和虚引用的区别是什么？)
    - [7.垃圾回收算法有哪些？](docs/JavaJVM.md#垃圾回收算法有哪些？)
    - [8.Minor GC和Full GC是什么？](docs/JavaJVM.md#MinorGC和FullGC是什么？)
    - [9.如何确定一个对象可以回收？](docs/JavaJVM.md#如何确定一个对象是否可以被回收？)
    - [10.目前通常使用的是什么垃圾收集器？](docs/JavaJVM.md#目前通常使用的是什么垃圾收集器？)
    - [11.双亲委派机制是什么？](docs/JavaJVM.md#双亲委派机制是什么？)
    - [12.怎么自定义一个类加载器？](docs/JavaJVM.md#怎么自定义一个类加载器？)
- [Kafka](docs/Kafka.md)
- [ZooKeeper](docs/ZooKeeper.md)
- [HTTP](docs/HTTP.md)
- [《剑指Offer》解题思考](docs/CodingInterviews.md)
* 读书笔记
  - [《Redis设计与实现》读书笔记 上](docs/RedisBook1.md)
  - [《Redis设计与实现》读书笔记 下](docs/RedisBook2.md)
  - [《MySQL必知必会》读书笔记](docs/MySQLBook1.md)
  - [《深入理解Java虚拟机-第三版》读书笔记](docs/JVMBook.md)  
- [好书推荐](docs/bookRecommend.md)

## 为什么要做这个开源项目？

我就是个普通的程序员，只是喜欢在空闲时看一些技术书籍，但是发现看完后，即便每一章都写了读书笔记，看到一些相关的面试题时，自己还是一脸茫然，所以我认为学习一项技术分为三个阶段：

1.看过入门教程，会用API。

2.看过相关的技术书籍，了解一部分原理。

3.能够对面试题进行分析，做出正确的解答，这样才能对技术有较为深入的理解，在工作中遇到复杂问题时，才能解决。

所以我发起了这个项目，
* 一方面是督促自己学习。
* 一方面是将这些面试题整理后，写完解答后分享给大家，希望可以帮助到大家，也欢迎大家一起来完善这个项目，为开源做贡献。


## 如何为这个开源项目做贡献？

如果你想一起参与这个项目，可以提Pull Request，可以扫上面的入群二维码进群，如果入群二维码失效了，也可以扫我的微信，我们一起聊聊！

## 关于我

我平时比较喜欢看书，写技术文章，也比较喜欢讨论技术。这是我的[掘金主页](https://juejin.im/user/5b370a42e51d4558ce5eb969)，希望大家可以关注一下，谢谢了！大家如果有事需要联系我，或者想进技术群，一起讨论技术，也可以扫描[主页中我的微信二维码](http://notfound9.github.io/interviewGuide/#/)加我，谢谢了！

## 关于转载

如果你需要转载本仓库的一些文章到自己的博客的话，记得注明原文地址就可以了。

