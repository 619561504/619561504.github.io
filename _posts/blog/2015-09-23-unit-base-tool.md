---
layout: page
title: "unit基本工具"
teaser: ""
categories:
    - blog
tags:
    - wifi
---
[awk命令详解]('http://www.cnblogs.com/ggjucheng/archive/2013/01/13/2858470.html')：awk是一个强大的文本分析工具，相对于grep的查找，sed的编辑，awk在其对数据分析并生成报告时，显得尤为强大。简单来说awk就是把文件逐行的读入，以空格为默认分隔符将每行切片，切开的部分再进行各种分析处理。

[sed命令详解]('http://www.cnblogs.com/ggjucheng/archive/2013/01/13/2856901.html')：sed 是一种在线编辑器，它一次处理一行内容。处理时，把当前处理的行存储在临时缓冲区中，称为“模式空间”（pattern space），接着用sed命令处理缓冲区中的内容，处理完成后，把缓冲区的内容送往屏幕。接着处理下一行，这样不断重复，直到文件末尾。文件内容并没有 改变，除非你使用重定向存储输出。Sed主要用来自动编辑一个或多个文件；简化对文件的反复操作；编写转换程序等。

[grep命令详解]('http://www.cnblogs.com/ggjucheng/archive/2013/01/13/2856896.html')：是一种强大的文本搜索工具，它能使用正则表达式搜索文本，并把匹配的行打印出来。

[sort,uniq,cut,wc命令详解]('http://www.cnblogs.com/ggjucheng/archive/2013/01/13/2858385.html')

> sort：sort 命令对 File 参数指定的文件中的行排序，并将结果写到标准输出。如果 File 参数指定多个文件，那么 sort 命令将这些文件连接起来，并当作一个文件进行排序。

> uniq：uniq命令可以去除排序过的文件中的重复行，因此uniq经常和sort合用。也就是说，为了使uniq起作用，所有的重复行必须是相邻的。

