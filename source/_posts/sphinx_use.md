---
title: 使用Sphinx制作文档
---
## 简介
* Sphinx 是一种工具，它允许开发人员以纯文本格式编写文档，以便采用满足不同需求的格式轻松生成输出。这在使用 Version Control System 追踪变更时非常有用。纯文本文档对不同系统之间的协作者也非常有用。纯文本是当前可以采用的最便捷的格式之一。

* 虽然 Sphinx 是用 Python 编写的，并且最初是为 Python 语言文档而创建，但它并不一定是以语言为中心，在某些情况下，甚至不是以程序员为中心。Sphinx 有许多用处，比如可以用它来编写整本书！

 * 突出显示
默认情况下，Sphinx 会为 Python 突出显示代码，但它还允许定义其他编程语言，比如 C 和 Ruby。

* 可以将 Sphinx 想像成为一种文档框架：它会抽象化比较单调的部分，并提供自动函数来解决一些常见问题，比如突出显示标题索引和特殊代码（在显示代码示例时），以及突出显示适当的语法。
Sphinx 使用 reStructuredText 标记语法（和其他一些语法）来提供文档控制 。 命令行界面是与 Sphinx 进行互动的主要方式
## 使用
### install
``` shell
$ sudo easy_install sphinx`
$ pip install sphinx --upgrade
$ pip install sphinx-intl
$ sudo apt-get install sphinx3-doc
```
### 创建工程
执行 sphinx-quickstart
>
```
├── Makefile
├── _build
├── _static
├── conf.py
└── index.rs
```
 ### 生成html
 make html 命令的输出、
 
 ### 生成静态网站
随着我们完成第一步操作，从两个文件中生成 HTML 之后，我们就拥有一个完整的函数式（静态）网站。

在 _build 目录内，现在应该有两个目录：doctrees 和 HTML。我们对于这个存储了文档网站所需的全部文件的 HTML 目录很感兴趣。使用浏览器打开 index.html 文件，就会发现如 图 1 所示的内容。

[1](https://www.ibm.com/developerworks/cn/opensource/os-sphinx-documentation/figure001.jpg)

参考文档
[1 IBM] https://www.ibm.com/developerworks/cn/opensource/os-sphinx-documentation/