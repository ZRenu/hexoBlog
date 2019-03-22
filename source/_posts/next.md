---
title: Markdown常用语法
date: 2019-03-22 11:41:11
tags: 
- Markdown
categories: 
- 档案馆
---
<img src="https://deerway.oss-cn-beijing.aliyuncs.com/hexoBlog/LrbfNhtq-TM.jpg" class="full-image" />
# 标题
使用#，可表示1-6级标题。
> #一级标题
> ##二级标题
> ###三级标题
# 段落
### 区块引用
在段落的每行或者只在第一行使用符号>,还可使用多个嵌套引用
> 区块引用
>> 嵌套引用
### 代码引用
``` js
/*```js  console.log('Just do it')```*/
console.log('Just do it')

```

``` bash
npm run dev
```
<!-- more -->
### 强调
在强调内容两侧分别加上*或者_
> \*斜体\*，\_斜体\_    
> \*\*粗体\*\*，\_\_粗体\_\_

效果：
> *斜体*，_斜体_    
> **粗体**，__粗体__

### 列表
使用`·`、`+`、或`-`标记无序列表，如：
> \-（+\*） 第一项
> \-（+\*） 第二项
> \- （+\*）第三项

**注意**：标记后面最少有一个_空格_或_制表符_。若不在引用区块中，必须和前方段落之间存在空行。

效果：
> + 第一项
> + 第二项
> + 第三项

有序列表的标记方式是将上述的符号换成数字,并辅以`.`，如：
> 1 . 第一项   
> 2 . 第二项    
> 3 . 第三项    

效果：
> 1. 第一项
> 2. 第二项
> 3. 第三项

###  分割线
分割线最常使用就是三个或以上`*`，还可以使用`-`和`_`。
***
---
___

### 链接

> \[github\]\(https://github.com/ZhouRenYou)。

效果：
> [github](https://github.com/ZhouRenYou)。

### 图片

![cmd-markdown-logo](https://www.zybuluo.com/static/img/logo.png)

### 字体
> <font color=#2196F3 size=2 face="宋体"\>宋体大小为2的字</font\>
效果：
<font color=#2196F3 size=2 face="宋体">宋体大小为2的字</font>

----


# 其它
### 代办事项

> \- [ ] 改进 Cmd 渲染算法，使用局部渲染技术提高渲染效率
> \- [x] 新增 Todo 列表功能


效果：

- [ ] 改进 Cmd 渲染算法，使用局部渲染技术提高渲染效率
- [x] 新增 Todo 列表功能

### 下划线文本
> <u\>下划线文本</u\>

效果：
<u>下划线文本</u>

### 中划线
> \~~markdow中划线~~

~~markdow中划线~~
