---
title: '在使用主题之前,先学会配置hexo'
author: xingwangzhe
tags:
  - 教程
  - hexo
categories:
  - 主题教程
abbrlink: 52039
date: 2025-04-08 16:18:28
---
## 什么是hexo

[Hexo](https://hexo.io/zh-cn/)是一个流行已久的静态博客框架,生态丰富,主题插件都很多,现在依然在更新!

## 安装hexo

### 下载nodejs

什么?你不知道nodejs吗,它可是js的引擎,如果没有它,js是无法在浏览器以外的环境下运行的,所以请下载[Node.js — 在任何地方运行 JavaScript](https://nodejs.org/zh-cn)

按照安装程序一步一步地来,当然,建议安装在**非C盘**区域

#### 检查是否安装好nodejs?

打开你的powershell(就是你鼠标右键区域里面的**在终端中打开**),输入下面的命令

> 这条命令的目的是查看当前的nodejs版本号,同时也可以验证nodejs是否安装成功

```bash
node -v
```

> 成功的话,应该会返回版本号,比如说我的nodejs版本返回的是

```bash
v22.14.0
```

当然**不必纠结于nodejs版本**,我认为基本上18之后的偶数大版本都可以的

#### 查看官方文档

官方起手非常简洁,给出了下面的命令,为了让读者尽可能明白,我将详细解释

```bash
npm install hexo-cli -g

hexo init blog

cd blog

npm install

hexo server
```

* npm install hexo-cli -g  安装hexo-cli
* hexo init blog 初始化文件夹
* cd blog 进入文件夹
* npm install 安装依赖
* hexo server 启动预览服务

当你执行完之后,就会发现你已经进入*blog*文件夹下并成功启动hexo了,这意味着,您的博客之旅,开始了!

:::tip
考虑到这是个hexo主题文档,而非hexo文档.希望您多了解hexo之后再来安装本主题,这样更舒心🥰
:::

