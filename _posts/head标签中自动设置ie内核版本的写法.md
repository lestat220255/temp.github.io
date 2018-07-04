---
title: head标签中自动设置ie内核版本的写法
tags:
- IE
- 兼容
date: 2017-11-11 00:25:35
permalink:
categories:
- mysql
description:
keywords:
---
> 最近在开发中遇到后台管理系统部分样式,js对IE浏览器不兼容的情况,最后通过在head标签中添加如下代码实现自动设置IE内核版本解决:  

```html
<meta http-equiv="X-UA-Compatible" content="IE=edge,Chrome=1" />
<meta name="renderer" content="webkit">
<meta http-equiv="X-UA-Compatible" content="IE=9" />
```
