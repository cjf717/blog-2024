---
title: Hexo快速入门
date: 2024-05-08 09:00:00
katex: true
categories: hexo
tags: 
- 入门
---
欢迎使用 [Hexo](https://hexo.io/)! 更多信息请访问： [官方文档](https://hexo.io/docs/) 。If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

辅助函数
<%- url_for('/a/path') %>

<%- link_to('http://www.google.com') %>
hexo.locals.get('posts')

数学符号

$\overline{abc}$

$$
a^2 + b^2 = c^2 \\
e=mc^2
$$

$$
\begin{cases}
x=\rho\cos\theta \\
y=\rho\sin\theta \\
\end{cases}
$$



## 快速开始

### 创建一篇新的文章

``` bash
$ hexo new "文章名称"
```

更多方法请查看: [Writing](https://hexo.io/docs/writing.html)

### 启动服务

``` bash
$ hexo server
```

更多方法请查看: [Server](https://hexo.io/docs/server.html)

### 生成静态文件

``` bash
$ hexo generate
```

更多方法请查看: [Generating](https://hexo.io/docs/generating.html)

### 发布到远程站点

``` bash
$ hexo clean
$ hexo deploy
```

更多方法请查看: [Deployment](https://hexo.io/docs/one-command-deployment.html)
