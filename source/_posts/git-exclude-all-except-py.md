---
title: git过滤所有文件保持指定后缀
date: 2019-04-22 14:56:33
categories:
- 技术
- 工具
- git
tags:
---
gitignore文件内容如下：

    * ##忽略所有文件
    !*/ ##保留文件夹
    !/**/*.py   ##保留所有py后缀的文件
