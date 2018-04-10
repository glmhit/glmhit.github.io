---
title: ubuntu安装包管理 
data: 2018/4/11 1:28:00
---

## apt-get

- APT package handling utility -- command-line interface 
## dpkg  
- package manager for Debian  


## aptitude
- high-level interface to the package manager

## pip
 - A tool for installing and managing Python packages
 
## yum
- yum is an interactive, rpm based, package manager. 
- It can automatically perform system updates, including dependency analysis and obsolete processing  based  on "repository" metadata. It can also perform installation of new qpackages, removal of old packages and  perform  queries  on the  installed and/or available packages among many other commands/services (see below). yum is similar to other high level package  managers like apt-get and smart.

---


[dpkg ---- apt-get ------ aptitude 三种方式的区别 及命令格式](https://blog.csdn.net/xiaoyanghuaban/article/details/22946987) 


>dpkg绕过apt包管理数据库对软件包进行操作，所以你用dpkg安装过的软件包用apt可以再安装一遍，系统不知道之前安装过了，将会覆盖之前dpkg的安装。
dpkg是用来安装.deb文件,但不会解决模块的依赖关系,且不会关心ubuntu的软件仓库内的软件,可以用于安装本地的deb文件
apt会解决和安装模块的依赖问题,并会咨询软件仓库, 但不会安装本地的deb文件, apt是建立在dpkg之上的软件管理工具
aptitude与 apt-get 一样，是 Debian 及其衍生系统极其强大的包管理工具。与`apt-get` 不同的是，`aptitude`在处理依赖问题上更佳一些。举例来说，aptitude在删除一个包时，会同时删除本身所依赖的包。这样，系统中不会残留无用的包，整个系统更为干净。

_ _ _

       
  - [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ]  \(Optional) Open a pull request