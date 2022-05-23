---
title: 切换node版本
date: 2022-05-23 17:18:42
tags:
---

## 1.卸载node

``` code
npm ls -g --depth=0   // 查看全局安装中是否有早前安装的node
```

## 2.安装nvm

[参考文档地址](http://nvm.uihtm.com/)


## 3.nvm常用命令

```
nvm                  // 会提示nvw下的相关命令
nvm ls               // 查看已安装node版本
nvm install vXX      // 安装对应vXX版本的node
nvm uninstall vXX    // 卸载对应vXX版本的node
nvm use xxx          // 选择使用XXX版本

```

至此就可以随心所欲切换node版本啦