# 搭建一个属于自己的CDN静态资源公共库

## 引言

你是否在打造一个网站？相信你在一段时间之后就会发现，你会频繁地引用各种重复的资源，比如每个网页的"favicon.ico"，亦或者是各类JavaScript框架，自己网站通用的CSS样式表等等，这些都是静态资源，那么什么是静态资源公共库呢？

静态资源库中的内容主要是各种主流框架如jQuery，Bootstrap等。因为每个网站都可以从这个库中引入这些框架等内容，所以也就称之为静态资源公共库。一些大公司已经提供了一些常见的前端库的静态资源CDN加速服务，使用这些库一来可以让用户加速访问这些资源，二来还可节约自己服务器的流量，一举两得，下面列举一些常见的库：

>[七牛云存储 https://www.staticfile.org/](https://www.staticfile.org/)

>[又拍云 http://jscdn.upai.com/](http://jscdn.upai.com/)

>[字节跳动静态资源公共库 http://cdn.bytedance.com/](http://cdn.bytedance.com/)

>[360前端静态资源库 https://cdn.baomitu.com/](https://cdn.baomitu.com/)

现在，你已经知道什么是静态资源公共库了，照目前状态来看，各个大厂也都在“卷”他们的云服务器，比如阿里云和腾讯云等，当然还有百度智能云，华为云，亿速云等等，但只是部署静态网页的话他们都有提供静态资源部署这样的服务，具体控制台名称可以去翻阅他们各自的帮助文档，要知道这类服务天生自带全站加速的BUFF，他们本身就有质量高速度快的CDN节点，而且这类服务有的免费有的价格贼低，**白嫖他不香吗！！！**，所以说我们完全可以搭建自己的静态资源公共库。

## 介绍

目前提出了这样一个想法，然后用 PhotoShop 简单设计出来了这个站点的雏形，大家可以走这个 [传送门](https://cdn.lhlnb.top/) 去查看，PS的工程文件我也放在仓库里面了，感兴趣的小伙伴也可以提提建议参与设计等，等一切准备就绪后（指6月左右期末考试结束），我就把他给码出来！

最后更新时间：2022年4月28日