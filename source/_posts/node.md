---
title: Node.js 开发指南
---
Node.js 开发指南, 记录着我学习Node.js整个思路和方法. 一些使用Node.js开发常用的命令和步骤.

<!-- more -->


# Express
高度包容, 快速而极简的Node.js Web框架.

## Express生成命令

使用下面的命令安装express:
```bash
 $ npm install express-generator -g
```

如果希望创建一个名为myapp的express应用程序:
```bash
 $ express myapp
```

需要安装依赖项:
```bash
 $ cd myapp
 $ npm install
```

在mac和linux上, 使用下面的命令运行此应用程序:
```bash
 $ DEBUG=myapp:* npm start
```

## 参考
* [Express官方网站 - 英文](http://expressjs.com/)
* [Express官方网站 - 中文](http://expressjs.com/zh-cn/)
