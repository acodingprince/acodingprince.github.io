---
layout: post
title: "my first blog"
date: 2016-03-18 08:09:37 +0800
comments: true
categories: 
---
**hello world**是我们学习一门语言的时候做的第一件事，**thank you** 就是我在这里特别想说的话，对于教会我搭建这个博客的老师--icodeyou(来自极客学院)！学习网址：[http://www.jikexueyuan.com/course/887.html](http://www.jikexueyuan.com/course/887.html)

### 搭建Octopress静态博客网站遇到的`问题`和`解决方法` ###
1.win10 更换ruby软件源为[https://ruby.taobao.org](https://ruby.taobao.org)时发生SSL应答错误。由于ruby没有包含SSL证书，所以Https的链接被服务器拒绝。解决方法很简单，首先在这里[http://curl.haxx.se/ca/cacert.pem](http://curl.haxx.se/ca/cacert.pem)下载证书, 然后再环境变量里设置SSL_CERT_FILE这个环境变量，并把value指向这个文件
