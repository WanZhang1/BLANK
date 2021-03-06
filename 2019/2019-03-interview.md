# 面试

## 阿里菜鸟

> 03-18，电话一面，25min 左右，应该是凉凉了。

下午 17 点 40 分左右，接到了菜鸟的电话面试，感觉很意外。毕竟投了那么多简历就几乎没有回信的～感谢吧，这次机会。

记录下当时问的问题，以防万一，毕竟我们是要总结反思的。另外，你简历上有啥，那就必须会啥，面试官会着重问你你简历上的东西，如果你不熟悉和了解的话，那就凉凉送给你，比如说我！

好吧，回顾下今天的面试问题：

- 问了下现在的大学和在学校的研究方向
- 拜占庭容错问题是怎么解决的？
    - 我研究的是 DPoS，但我说了 PBFT，CBFT，VBFT
- 问了下简历上的那个 TinyOne 项目
    - 我说用 Linux 的 Socket 实现的，没了
- 上传文件需要几次回应？忘了是啥了
- TCP 三次握手，为啥不是两次呢？
    - 我顺带说了四次挥手
- 问 Go 语言的例程如何实现的？
    - 因为我简历上写了了解 Go 语言，结果打脸，我不知道
- 熟悉 C++ 是吧，问了 STL 的部分源码实现，尤其是关于红黑树的
    - 我就介绍了下红黑树的特点，哪些容器用它实现的
- unordered_map 的底层如何实现的？
    - 我说是和 map 一样，都是红黑树
- TCP 的拥塞控制和流量控制
    - 我说滑动窗口，当时一定是吓懵了
- Redis 了解是吧，说说有几种数据结构，如何实现数据的有序？
    - 我讲了 3 个类型，说总共是有 6 种。一本正经的胡说八道
    - 我说是通过字典来实现有序，然后就没有然后了
- 如何中断或者停止客户端对服务器的连接
    - 我说的是可以直接发送中断信号，或者通过 C-c 来关闭连接
- 如何保证数据的安全，加密
    - 我说身份验证，然后补充了抽取 MD5，利用 salt 盐值加密
- 还问了线程相关的，如何创建，具体的过程
    - 我说了 fork()，join()，exit() 等函数，几乎就没有下文了
- 了解一致性哈希吗，如何实现的？
    - 不了解
- 你还什么要问的？
    - 我说是那个公司来着，没听清
    - 然后问了面试官对我此次面试的评价，还需要在哪些方面继续加强？面试官的回答是没有什么好与坏，这次只是简单的了解，如果合适的话，后续还有更深入的了解。
    - 我猜，面试官内心一定是这样的：自己啥水平还没点数啊，还好意思问？😂

说实话，紧张啊，又是刮风又是在大马路牙子上，频繁听不清面试官的问题，内心还是很奔溃的。

总之，准备的还是不够充分，不懂的就直接说不了解了，感觉是问啥啥不会。😂 所以，还需要继续努力，记录下来，当作教训。

共勉。

> 03-27 阿里面挂。

以为一直没有消息就是已经不再会有任何通知了，深知自己差的太多，没想到，今早 05:36 阿里还是贴心的发来邮件告诉我挂掉了，很是优秀。

为了纪念一下，所以截了个图。

![](https://github.com/i0Ek3/BLANK/blob/master/images/alibaba-over.jpg)

接下来继续吧，但我会在文末重新规划一下，做事要有计划，上战场要有策略。


## 华为/招银网络

> 03-19，夭折在娘胎中。

因为第一学历，无法在官网投递简历，这也是一道很大的门槛儿了。现在也一样，虽然找人做了华为的内推，以为会有改善，结果还是不行。

招银也一样，就像我之前提问的问题一样，不能手写出算法就一定不是好工程师吗？不去大公司就一定是能力不行吗？显然不是的。任何事情都有自己的运行机制，不用在意太多，你是你而已。

继续复习吧，面朝大海，春暖花开吧。

> 03-21

跟华为的 HR 多次沟通，最终成功投递简历，至于简历的筛选那就听天由命了，总之感谢华为的 HR，能让我有这次投递的机会。



## POP IM

> 03-19，22:00，电话一面，28min。

还是能力不足，基础不够扎实。

还是要回顾下具体的问题，反思自己哪里不到位：

- 就简单介绍啊，学历，考研，为啥选择计算机的原因
- 聊了下工作地点，实习相关的问题
- 问了其他语言的学习情况，Go 语言作为主要开发语言的问题等
- 对我们公司的产品有了解吗？
    - POP IM 一个视频社交类软件
- Go 语言的语法，切片是啥
    - 对，我绝对是在胡说八道
- GitHub 的工作流是怎样
- MySQL 的索引有哪些
- 对 B+ 树的了解，是一个什么样的存在
    - 对，我又开始一本正经的胡说八道了
- Redis 中都有那些数据结构，做什么用的
    - 源码了解的不够深，说完数据结构后，就开始一本正经的胡说
- Redis 中 ttl 的具体实现
- 简述下区块链共识机制的具体研究点
- 你是用 Linux + vim 吗
- 你需要做些什么才能更好的胜任我们的工作
- 你个人的劣势或者不足
- 聊一下你一天的学习或者工作日程
- 问了面试官一些对我的评价
    - 团队协作，项目合作要加强
    - 广度可以有，但最好在某一方面有深度

最好可以把你准备好的东西都可以展示出来，不要面试官问啥就只说啥，适当的推销自己。虽然我准备了很多东西，但是没有深度，也就无话可聊了，这个是不足，还需要弥补。不过总算可以休息了，今天很累。

另一个，项目还是要做的有深度一点，我这个太 low 了。今天就这样吧，好好休息，明天继续。


> 03-22 15:00，远程视频面试，58min。

发现自己是真的 low，动手能力欠缺的厉害。即便是见过的代码，也不一定能写得出来。另一个，已经形成定式思维了，这个不好，需要尽快改善。

来看看远程面试的问题吧，很简单，但我是真的....一起来反思下吧。

- N 个台阶，你每次可以走一个或者两个，问有多少种走法？
    - 是不是很熟悉，我立刻就能想到动态规划或者回溯法，但实战的少，没能写出相关代码，只写了递归的，而且效率也不好，总之编码差的一批
- SQL 语句编写
    - 说实话，当时还是很懵的，MySQL 和 SQL 虽然差不多，但是我已经忘掉了很多细节，写出来的语句也是错漏百出
- 如何判断一个只有头指针的单向链表是否有环呢？
    - 我说用快慢指针吧，但似乎不太对，想了半天没有思路
- 实现二分查找
    - 这个不会那面试肯定是不能通过，遗憾的是我写错了，却一时又没发现哪里有问题
- LRU 知道吗？讲讲它是什么，怎么实现的？
    - 我说用栈，队列，链表或者哈希表，还有双端链表都行
    - 具体的代码实现我是肯定不会的，找时间学习一下
- 面试结束，有什么想问的吗？
    - 我都不好意思问啥了，自己实在是太菜了
    - 最后还是问了下那个 SQL 中如何去找第二大的数据，用 order by 关键字

说实话，面试的内容还是很简单的，没有我想象中的那么难，只不过自己代码功底实在太差，也就没好意思问面试官什么问题，我自己深知自己的不足，所以，继续写代码吧！

> 03-25 17:41，通知我挂了。

当时在健身，其实也没有什么情绪，首先觉着还是自己的问题，立刻反思了下，然后回复之后便愉快的继续去健身了，比较身体才是革命的本钱。但无论如何，这是一段经历，或好或坏，都是值得的。也感谢 POP IM 给予的这次机会，学习到很多。

没有什么好说的，总之，这个经历很难得，我也很珍惜。继续加油吧～


## 总结

计划和策略都应该充足与明确。

如果自己还不是很优秀，那么可以先找一些小的公司尝试一下，不然内推的话，会浪费掉上船的机会，尤其像我这样的选手。

这个月应该还是会投一些简历，但重心应该在项目和代码本身。但时间拖的越久机会就越少，毕竟今年的岗位的确没有去年那么多，所以要好好把握机会，争分夺秒。

未完待续...

