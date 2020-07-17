# Notice

This series of tuturial is moved and integrated into two of my Zhihu columns: [人工智能与量化投资 https://zhuanlan.zhihu.com/intro-to-quant](https://zhuanlan.zhihu.com/intro-to-quant) and [强化学习前沿 https://zhuanlan.zhihu.com/reinforcementlearning](https://zhuanlan.zhihu.com/reinforcementlearning).
You can find more about quant in the first column - from the basics to the advances, and more about advances of AI in the second column.
Hope you enjoy!

# 量化投资入门简介

Zhihu: [https://zhuanlan.zhihu.com/p/55991656](https://zhuanlan.zhihu.com/p/55991656)

## 写在前面

一年之前量化投资这个领域对我来说还是完全陌生的，没有炒过股，也不知道炒股软件上面花花绿绿的线有什么含义。经过一年的学习，目前自认为勉强算是入了量化投资的门。希望通过这几篇文章给准备入门或者想了解一下量化投资究竟是什么东西的同学们一个大致的介绍。本文适合于**零基础**的同学阅读。

之前一直对于投资或者是金融领域有一些成见，认为金融领域属于投机行为，并没有创造价值。从小被教育要为社会做贡献，因此也不是很看得起这种投机倒把、薅社会主义羊毛的行为。的确，投资并不能创造供人们衣食住行的实实在在的产品，但是投资其实是对于社会资源的一种调配，而资本的逐利性恰好使得这一的资源调配朝着有效率的方向发展。诚然，没有实体经济就没有金融市场，但是在金融市场的调配下，实体经济得以更加有效率的运行。比如，资本市场会关心哪一家工厂的生产管理更有效率，反应在资本市场就是预期的盈利能力更高，资本市场就会把更多的资金（即资源）投放到这一效率更高的工厂上。这一行为加速了实体经济的优胜劣汰，也提高了实体经济的效率。再比如，共享单车大家都觉得很方便，但是要是没有资本市场的投入，ofo等公司也很难募集到大量资金从而快速地让全国人民都使用到方便的共享单车。

过去的一年发生的很多新闻都与资本市场密切相关，如果了解资本市场的运行规律对于我们更加深刻理解当今的社会也是很有好处的。比如红黄蓝事件之后股民在美股市场大规模做空其股票（NYSE:RYB）会对其公司有什么影响？贾跃亭欠了一屁股债跑到国外与乐视网（300104.SZ）在这今年的连续下跌又有什么联系？中央政治局常委名单出炉之后，沪宁股份（300669.SZ）股票为什么会出现短暂飙升？獐子岛（002069.SZ）的扇贝莫名“出逃”对其股价又有什么影响？白百何被爆出轨之后与之没什么直接联系的红墙股份（002809.SZ）为什么出现一波大涨？

小结一下，金融市场和投资的存在同样是有利于社会的发展的，也是符合“三个代表”指导方针的；就算不是为了挣大钱，对于金融投资领域有一定的了解也能够增进对社会中的这一股强大力量认识。这学期齐鲁资管（现在更名中泰资产了）总裁章彪受我导师邀请来我们院讲座，他说量化投资是最适合“宅”理工男赚钱的方式。当然，就目前来看本人还是水平不够，达不到能赚大钱的地步，不过至少对于我而言这个领域确实也是有利于社会发展，同时市场上也有很多有趣的现象和规律，其中也有很多值得研究的东西。

另外，感觉投资领域最神奇的事情就是所有相关的事情，比如舆论、政策，甚至天气、心理学等都会通过大家的逐利行为反映到一个单一的变量——价格上面。你不需要对每一个方面都搞得很清楚，只需要精通其中某一个方面，就可以在资本市场上分到自己的一杯羹。所以目前看来就是，市场那么大，各赚各的钱。

最后要说的是，我也只是写一些自己的理解，很多地方也是一边学一边写，有不准确的地方欢迎指正。

## 目录

[第一讲：投资与股票交易规则](chapter_1.md)

Zhihu: [https://zhuanlan.zhihu.com/p/55992159](https://zhuanlan.zhihu.com/p/55992159)

* 一级市场与二级市场
* 股票是如何交易的？
* 如何看懂行情软件显示的数据？
* 交易所规则：涨跌幅限制
* 交易所规则：停复牌
* 交易所规则：除息除权

[第二讲：量化投资是什么？](chapter_2.md)

Zhihu: [https://zhuanlan.zhihu.com/p/55993709](https://zhuanlan.zhihu.com/p/55993709)

* 传统投资与量化投资
* 量化投资与有效市场假说
* 再谈量化投资概念
* 一种简单的量化模型：现代资产组合理论（MPT）
* 进一步的量化模型：资本资产定价模型（CAPM）
* 更强大的量化模型：单因子模型和多因子模型（Factor Model）
* 再讲一个量化模型：套利与套利定价模型（APT）

[第三讲：如何开展量化投资研究？](chapter_3.md)

Zhihu: [https://zhuanlan.zhihu.com/p/56009964](https://zhuanlan.zhihu.com/p/56009964)

* 怎样搞到数据？——巧妇难为无米之炊
* 怎样测量策略的性能？——搭建回测系统
* 怎样衡量量化策略的好坏？——一箩筐统计指标
* 开始挣钱！——从回测到实盘

[第四讲：机器学习如何与量化投资结合？](chapter_4.md)

Zhihu: [https://zhuanlan.zhihu.com/p/56012917](https://zhuanlan.zhihu.com/p/56012917)

* 基本框架
* 决策树模型
* 支持向量机
* 贝叶斯模型
* 聚类模型

[第五讲：从零开始认识强化学习](chapter_5.md)

Zhihu: [https://zhuanlan.zhihu.com/p/56045177](https://zhuanlan.zhihu.com/p/56045177)

* 强化学习基本概念
* 马可夫决策模型
* 价值函数
* Bellman算子
* Value Iteration和Policy Iteration
* 动态规划方法
* 蒙特卡洛方法

[第六讲：强化学习策略迭代类方法](chapter_6.md)

Zhihu: [https://zhuanlan.zhihu.com/p/56058343](https://zhuanlan.zhihu.com/p/56058343)

* 初识时间差分方法 —— TD(0)
* 从少量状态到数不清的状态 —— 函数逼近技术
* 从TD(0)到MC的过渡 —— TD($\lambda$)
* 用强化学习来玩游戏 —— DQN

[第七讲：强化学习策略梯度类方法](chapter_7.md)

Zhihu: [https://zhuanlan.zhihu.com/p/56128287](https://zhuanlan.zhihu.com/p/56128287)

* 让策略梯度形式简单 —— Policy Gradient Theorem
* 用最简单的采样方法来实现 —— REINFORCE
* 两个网络一台戏 —— Actor-Critic
* 应用到高维行动空间 —— DPG
* 策略梯度类也可以玩Atari —— 从DQN到DDPG

以下的内容还在写作中，如果有相关问题和建议可以留言我的知乎[张楚珩](https://www.zhihu.com/people/zhang-chu-heng/activities)或者在github[此项目](https://github.com/zhangchuheng123/iQuant/issues)下建立issue。感觉写起来真的很麻烦，有点写不动了。先把坑挖好，然后再慢慢填。强化学习专题讲完之后就不这样一讲一讲地写了，会考虑一两篇论文读下来下一篇小的总结。接下来这个教程还是回归量化投资，讲一讲不同标的上的量化投资方法，比如股票、期货、数字货币等。

Update: 下面强化学习算法更新到强化学习前沿中专栏中了。

[第八讲：强化学习高级策略梯度类方法和无导数优化方法](chapter_8.md)

* TRPO Zhihu: [https://zhuanlan.zhihu.com/p/44595815](https://zhuanlan.zhihu.com/p/44595815)
* PPO Zhihu: [https://zhuanlan.zhihu.com/p/44600797](https://zhuanlan.zhihu.com/p/44600797)

[第九讲：基于模型的强化学习方法](chapter_9.md)

* PETS Zhihu: [https://zhuanlan.zhihu.com/p/45418829](https://zhuanlan.zhihu.com/p/45418829)
* iLQG Zhihu: [https://zhuanlan.zhihu.com/p/45618611](https://zhuanlan.zhihu.com/p/45618611)
* GPS Zhihu: [https://zhuanlan.zhihu.com/p/45754995](https://zhuanlan.zhihu.com/p/45754995)

[第十讲：数字货币量化交易概览](chapter_10.md)


## 欢迎访问主站[张楚珩的仓库](http://sealzhang.tk)