---
title: Text and Typography
author: Cotes Chung
date: 2020-11-04 11:33:00 +0800
categories: [Blogging, Demo]
tags: [typography]
math: true
image: /assets/img/sample/devices-mockup.png
---

# create 

Revise history:
- 2020.11.04 创建

## 大纲
- [选择github_blog](#选择github_blog)
- [选择jekyll](#选择jekyll)
- [选择theme](#选择theme)
- [本地环境构建](#本地环境构建)
- [github部署](#github部署)
- [开始blog记录](#开始blog记录)
- [彩蛋](#彩蛋)


## 选择github_blog

## 选择jekyll

## 选择theme

## 本地环境构建
&#8195;当对blog界面进行修改时，github需要每次同步到仓库才能预览，这是一个非常繁琐的过程。因此我们会考虑搭建本地环境去方便调试。以下几步按需执行：

- | 基础环境搭建

&#8195;&#8195;按照Jekyll官方doc[Jekyll Docs](https://jekyllrb.com/docs/installation/)完成`Ruby`, `RubyGems` and `Bundler`的安装和配置。`Ruby`官网下载较慢，按需选择fq，`Ruby`版本选择 'with devkit'，安装完后需要勾选安装`msys2`，后面安装`gem`和`jekyll`会用到。在`cmd`中输入命令：
```console
$ gem install jekyll bundle

$ jekyll -v
jekyll 4.1.1

$ bundle -v
Bundler version 2.1.4
```

- | 运行本地服务器

&#8195;&#8195;第一次运行`serve`，需要执行初始化安装必要的`gem`库，并创建和启动本地服务器。然后打开浏览器，访问[http://localhost:4000](#http://localhost:4000) 就能开启预览模式。
```console
$ bundle install

$ bundle exec jekyll serve
```



## 开始blog记录

## 彩蛋
