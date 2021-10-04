---
layout: post
title: 搭建jekyll时遇到的问题
date: 2021-08-21 
tags: 技术

---


# 问题一  how to install jekyll (new windows10)

> 1.download [rubyinstaller-devkit-2.6.2-1-x64.exe](https://rubyinstaller.org/downloads/)
>
> 2.gem install jekyll bundler

# 问题二  “Could not find gem 'redcarpet' in locally installed gems”

> 1.bundle install
>
> 2.jekyll server

# 问题三 翻墙才能打开网站，不翻墙打不开，原域名lvasky.github.io能打开

> 原因：dns被翻墙软件污染了。
>
> 办法：域名更改成8.8.8.8，然后再改回来就好了