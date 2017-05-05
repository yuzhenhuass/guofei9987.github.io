---
layout: post
title: jekyll安装和配置.
categories: Geek
tags:
keywords:
description:
---


## 安装配置1
- 安装python
- 安装easyinstall
- 安装ruby

## 安装配置2
ruby下：
```ruby
easy_install Pygments#安装Pygments，Pygments是一个语法高亮插件
gem install bundler# 安装bundler
gem install jekyll# 安装 jekyll
```

## 可以开心得玩啦
ruby下：
```ruby
jekyll new site-name # 创建一个新的站点，名字是site-name
jekyll build # 构建
jekyll server # 开启本地服务器查看效果
jekyll server -P 4001 # 指定端口
jekyll server -w # 文件发生变化时，自动重新编译
```