---
title: "利用Hugo搭建博客并部署在Github上的方法"
date: 2018-05-09T18:20:13+08:00
draft: false
tags: [hugo]
comments: true
---
##### 本文主要参考[Hugo中文文档](http://www.gohugo.org/)及[浮世尘烟](https://gdzhu8023.github.io/post/buildblog/)博文
## 1.搭建博客目的
主要为记录一些软件及平时科研学习笔记
## 2.准备工作
### 2.1 基础知识
- Git基本操作（参考[廖雪峰老师Git教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000))
- Github网站基本了解

### 2.2 软件列表
- [Git](https://git-scm.com/)
- [Hugo](https://github.com/gohugoio/hugo/releases)
- [Github账户申请](https://github.com/)

### 2.3 软件安装
#### 1) Git软件的安装
#### 2）Hugo软件的安装
#### 3）Github账户申请
## 3.生成静态博客

## 4.部署在Github上

## 5.博客编写
```
hugo new post/blog.md
hugo --theme=blackburn --buildDrafts --baseUrl="https://cuglilong.github.io/"
cd public
git add .
git commit -m "add new blog"
git push origin master
```
