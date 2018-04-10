---
title: 使用hexo+github发布博客简易教程
---
- [TOC] 

Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)

### 新建博客
hexo使用[Front-matter](https://hexo.io/docs/front-matter.html)配置博客的名称，在markdown文件头添加YAML语句


```
---
title: ubuntu安装包管理 
data: 2018/4/11 1:28:00
---  

```

* * *

```shell
hexo g
hexo d
```
发布后，github有延迟，等一分左右才能刷新出新的内容



