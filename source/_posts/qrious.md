---
title: 基于qrious生成二维码。
date: 2019-04-26 11:11:20
tags: 
- 前端
- 鹿途管理系统
- 二维码
categories: 插件
---
<img src="https://wx4.sinaimg.cn/mw690/8954143dgy1g1f67hvkgmj21400u0e85.jpg" class="full-image" />

# 基于[qrious](https://github.com/neocotic/qrious#api)生成二维码。

``` ts
npm i --save qrious
```
# 代码示例

```html
<canvas id="qr"></canvas>
```

```ts
  this.qr = new QRious({
      element: document.getElementById('qr'),
      value: this.value
    });
```
# 注意

默认 QRModule 并没有强制依赖 qrious，因此还需要额外在 angular.json 的 scripts 节点引用它。

```json
"scripts": [
  "node_modules/qrious/dist/qrious.min.js"
]
```

# 示例 
[鹿途](https://zhourenyou.github.io/web-deerway/passport/login)管理系统——插件工坊——二维码


# api

| 参数            |             说明             |   类型 |  默认值 |
|-----------------|:----------------------------:|-------:|--------:|
| background      |             背景             | string | "white" |
| backgroundAlpha | 背景透明级别，范围：0-1 之间 | number |     1.0 |
| foreground      |             前景             | string |   white |
| foregroundAlpha | 前景透明级别，范围：0-1 之间 | number |     1.0 |
| padding         |      内边距（单位：px）      | number |      10 |
| size            |       大小（单位：px）       | number |     220 |

