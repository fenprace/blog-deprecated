---
layout: post
title: "我的 Blog 折腾记"
description: ""
category: Essays
tags: ["Blog"]
---
{% include JB/setup %}

阮一峰在他的 Blog 里说：

> 喜欢写Blog的人，会经历三个阶段。
>> 第一阶段，刚接触Blog，觉得很新鲜，试着选择一个免费空间来写。
>> 第二阶段，发现免费空间限制太多，就自己购买域名和空间，搭建独立博客。
>> 第三阶段，觉得独立博客的管理太麻烦，最好在保留控制权的前提下，让别人来管，自己只负责写文章。 
> via [Blogging with jekyll](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)

我也折腾过很多 Blog，基本就是按着这个路子走的。

## 第一阶段：Blogbus 和 Blogger
听说 Blog 这个概念，还是从 Blogbus 开始，那时的 Blogbus 还如日中天，是国内最大的
BSD。自己的第一个 Blog 便是基于 Blogbus 的。

Blogbus 确实蛮好用，可以自定义主题。但由于自己产出太慢，Blog 没有活力，慢慢连自
己就把这个 Blog 忘了（掩面）。

后来听说了 Blogger 这个全球最大的 BSD，也尝试过，真心好用，但不久 Blogger 就因为
一些众所周知的原因，在大陆访问不能了。

## 第二阶段：Wordpress
这时期接触了[善用佳软](xbeta.info)、[iPlaySoft](iplaysoft.com)之类众多基于
Wordpress 的独立 Blog，也萌发了自己搭建独立 Blog 的想法。

但因为一直没有能力购买 VPS ，所以迟迟没有进行，只能用 
[Wordpress.org](wordpress.org)、[BLOG.CD](blog.cd)
这样的免费 Wordpress 托管服务。

## 第三阶段: Jekyll, Octopress and more
虽然我早就听说过 Jekyll ，但由于对 Github Pages 不熟悉，一直没有去了解，直到我在
[V2EX][] 上见到了这个帖子：
[http://www.v2ex.com/t/25779](http://www.v2ex.com/t/25779)，
发现还有 [Jekyll-Bootstrap][] 这样方便的工具。

用 Github Pages 托管 Blog 还有另一个选择： Octopress ，我自己也试过，不过其目录
结构真心复杂，写个主题要编辑5个文件以上，自定义真心困难。

其实，专注内容的 Blog 托管方法还有很多，我自己实现过一个将文章全部以 Gist
形式储存的 Blog，不过因为 Github 提供的 API 不是很全面，很多信息需要用户给出，
背离了专注内容的本意，就搁浅了。


[V2EX]: v2ex.com
[Jekyll-Bootstrap]: jekyllbootstrap.com
