---
title: 占领未来的打包工具---Parcel（介绍）
date: 2018-03-19 22:01:32
tags:
    - 导航
    - 分享
categories: 打包工具
---
# 基本概况

最近大家都在关注一个很流行的类似 webpack 的前端构建工具 Parcel。这个库刚出来没多久(截至目前发布几十天)，但是很受欢迎，看下图就知道它到底有多火了。

![图片](/images/picblog/parcel1.png)

**这么火的东西我们怎么能不学呢？那么它到底火在哪儿？来看看我的示例分析(教程)吧！！！**

## 官方介绍地址

**官方地址：**https://parceljs.org/

**GitHub地址：**https://github.com/parcel-bundler/parcel

# Parcel VS Webpack

## 听我扯一扯

介绍这个库之前，我来说一下我个人觉得 webpack 的一些不好的地方（相对于 Parcel）。
 
  1、需要写配置文件（webpack.config.js），可能每使用一个功能，比如加载图片或 css，都要添加配置，要维护配置文件，而 Parcel 不需要。

  2、感觉编译或加载速度有些慢，特别是库多或项目复杂的时候，虽然有一些办法代码拆分的方法可以解决，比如 CommonsChunkPlugin 或 DLLPlugin 之类的，但这些方法有些复杂。

## 官方数据

  **打包速度**
  
  真的飞一般的感觉吧！！！

  ![图片](/images/picblog/parcel2.png)

## 学习成本

 webpack需要一定的时间去学习如何使用而 Parcel 有很多优点，可以不使用配置文件，也就是说你只管写代码，它会自动运行，很智能化，打个比方吧，比如在 webpack 中如果要处理 css，那得要安装和加载一个 css 的 loader，然后配置文件写上几行，可是 Parcel 不需要，直接用就行。Parcel 学习起来比较简单，基本上可以说 "不用学习"，只是使用就可以了。**除此之外** 模块热替换和代码拆分的功能，Parcel 也有，还有，如果要你用 Parcel 写一个 react 的运行环境，可能不需要配置任何内容，只要安装几个 react 的包就可以用起来了。

**说了这么多，我还是要把官方对它的特性进行概括的图片放出来：**

![图片](/images/picblog/parcel3.png)

>**说到这里小伙伴们是不是和我当初一样心动了呢？  下一篇博客我们一起上手玩起来吧！！！**









