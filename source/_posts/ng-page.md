---
title: angular-cli-ghpages发布Angular项目到github pages
date: 2019-03-25 16:41:58
tags: 
- Angular
- 前端
- 鹿途管理系统
categories: Angular
keywords:
- Angular
- github pages
- angular-cli-ghpages
---
GitHub有一个很实用的功能就是GitHub Pages，他相当于为Github项目建立了一个可视化的web页面。angular-cli-ghpages的功能就与这个类似
> 1.首先新建一个Github空项目，比如ng-deerway

然后使用angular-cli工具生成一个新项目

安装angular-cli-ghpages包 

``` bash
npm install angular-cli-ghpages -g
```

> 2.打包项目代码，并设置项目链接地址 

``` bash
ng build --prod --base-href "https://xxxx.github.io/项目仓库名/"

```
> 3.初始化git

``` bash
git init
git remote add origin [url]
```

> 4.发布（默认push到gh-pages分支上）

``` bash
npx ngh --dir=dist/[PROJECT-NAME]

```
>PROJECT-NAME项目的名称。如果使用的是Angular 5及更低版本，运行不带项目名称的命令

``` bash 
npx ngh --dir=dist
```