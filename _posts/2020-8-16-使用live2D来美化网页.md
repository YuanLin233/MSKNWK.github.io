---
layout:     post
title:      使用live2D来美化网页
subtitle:   使用live2D来美化网页
date:       2020-8-16
author:     TNXG
header-img: img/home-bg-o.jpg
catalog: true
tags:
    - 博客
---


## 什么是live2D ##
ilve2D简单来说就是一个二维形象，现在的很多个人博客左下角都有live2D

## 那么该如何使用它 ##
很简单，只需要在网页首页加入以下代码就可以了！

``` javascript
<!--LIVE2D-->
<link rel="stylesheet" href="https://api.misakanetwork.ml/live2d/font-awesome.min.css">
<script src="https://api.misakanetwork.ml/live2d/autoload.js"></script>
```
这其实很好理解，首先调用图标库(依赖 Dependencies)
然后加载live2D主体

## 特性 Feature

在网页中添加 Live2D 看板娘。兼容 PJAX，支持无刷新加载。  

**警告：本项目使用了大量 ES6 语法，不支持 IE 11 等老旧浏览器。**  

## 目录结构 Files ##

- `waifu-tips.js` 包含了按钮和对话框的逻辑；
- `waifu-tips.json` 中定义了触发条件（`selector`，CSS 选择器）和触发时显示的文字（`text`）；
- `waifu.css` 是看板娘的样式表。
 当然，我们只是提供了适用于我们网站的live2D对话框及模型，所以希望大家多多包涵啦(当然你也可以使用官方给出的链接下载源代码修改，我们只做方便使用的ilve2D)

## 版权 ##

原作者仓库：https://github.com/stevenjoezhang/live2d-widget
其中的==README.md==提供了更为详细的修改、自定义方法

## 鸣谢 Thanks ##

源代码发布者：==stevenjoezhang #FF5722==

代码自这篇博文魔改而来：  
https://www.fghrsh.net/post/123.html

点击看板娘的纸飞机按钮时，会出现一个彩蛋，这来自于 [WebsiteAsteroids](http://www.websiteasteroids.com)。
## 更多 More

更多内容可以参考：  
https://imjad.cn/archives/lab/add-dynamic-poster-girl-with-live2d-to-your-blog-02  
https://github.com/xiazeyu/live2d-widget.js  
https://github.com/summerscar/live2dDemo

关于后端 API 模型：  
https://github.com/fghrsh/live2d_api  
https://github.com/xiazeyu/live2d-widget-models  
https://github.com/xiaoski/live2d_models_collection

除此之外，还有桌面版本：  
https://github.com/amorist/platelet  
https://github.com/akiroz/Live2D-Widget




