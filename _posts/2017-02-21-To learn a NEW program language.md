---
title: To learn a NEW program language
tags: [Python,Spider] 
---

## Case 0

昨天有人给我说，他想学python.

可是，前年他就跟我说过同样的话。

你不早学了么？ 我问他。

学过就忘了。

是啊，当年为了跟随网上潮流进行装逼，我也是一心想好好学学Python，因为它能干好多事

- 爬虫
- 数据分析
- 图像处理
- 做游戏
- and more~

看到这些，我就感觉脑子一热，干劲大发，去网上找关于python的资源，收集到如下:
- python官网文档
- 简明python教程
- python核心编程

这些资料刚开始看看挺好，深入下去到控制流，包，类，感觉像是在喝白开水-没味，而且时间一长又没了印象~

## Case 1
直到某天，我在给一个文档配图时，需要把一张图片中的一部分扣出来，我又想到了Python。 上网折腾，发现了PIL这么个库，导入后几行代码就能处理图片，简单粗暴。

花了一晚上的时间，终于整了出来，代码在这:
[crop.py](https://github.com/kyshel/python_knife/blob/master/crop.py)

这也是刚开始用python作工具吧，对变量赋值，控制流有了个具体的认识。

## Case 2
后来准备6级，我做题时遇到生词习惯一个个标出来，做完后再挨个查。
但这样感觉好麻烦。我就想能不能写个程序，可以一次性把我标的这些单词自己查出来呢。

于是，[BeatCET6](https://github.com/kyshel/BeatCET6) 就这样诞生了。

这次对Python的数据结构也有了基本的概念，包括数组的结构，dict元素的类型，如何包含文件，等等~

## Case 3
又一次，我接触了一款名叫nice的app，有点像国外的Instagram，是一款图片社交软件。我的需求是给尽量多的图片点赞，以增加我的曝光度，让更多的人来关注我。

我首先想，手机端的社交app，网页端也可以查看，上网搜索得对应的域名是oneniceapp.com,可是这个网站跟app差别很大，登陆后只能进首页看它给推荐的图片，点进图片后只能获得最近赞的6个人的信息。一张图片6个人，每个人获取他们的最新图片，然后每张图片又能得到最近赞的6个人……这样一层层下去，不就能得到更多的人了吗？

依照这个想法，我做了个 [nice-spider](https://github.com/kyshel/nice-spider)， 它是一个爬虫程序，输入账户信息，种子图片地址，爬取深度，静静等待就好。

## 写在最后

拿项目作一作，来得比较快~