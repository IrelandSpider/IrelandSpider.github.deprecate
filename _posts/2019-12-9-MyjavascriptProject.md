---
layout: post
title: 'My path to javascript'
date: 2019-12-09
author: Matrix73
cover: ''
tags: javascript
---
--- updated 2019-12-09 ---
## 如何食用以下内容?*
`*`: 话题有待更新  
## 下载安装编辑器
javascript编辑器有很多款，vscode、sublime、emacs、vim、notepad++,但是这里选用sublime text 3。  
[下载sublime text 3 点击这里](https://www.sublimetext.com/3),选择对应的系统版本和位数，这里使用的是windows10 64位，[windows的位数查看方法点击这里](https://support.microsoft.com/zh-cn/help/15056/windows-32-64-bit-faq)，安装过程一直点 Next 就可以了。  
## 编辑器的常用快捷键*  
<kbd>ctrl+shift+p</kbd>: 打开命令面板  
<kbd>ctrl+p</kbd>: 搜索项目中文件  
<kbd>ctrl+w</kbd>： 关闭当前文件  
<kbd>ctrl+shift+w</kbd>: 关闭所有打开的文件  
<kbd>ctrl+`</kbd>: 打开控制台  
## 常用技能
- 切换编程语言： <kbd>ctrl+shift+p</kbd>->输入ss编程语言  
- 建立html5模板： 在编辑器输入html:5，按下<kbd>Tab</kbd>  

## 配置编辑器的javascript运行环境*  
- package control  
1 什么是 package control ?  
这是一个 sublime 的包管理器，也就是管理插件的插件，可以通过他的安装源 github 和 buck下载安装插件，并且自动更新；  
2 怎么安装?*  
点击进入[packagecontrol.io](https://packagecontrol.io/installation),看到有一段以 import 开头的文段复制下来，如果肉眼找不到使用浏览器搜索功能<kbd>ctrl+f</kbd>搜索；  
返回sublime3，按<kbd>ctrl+`</kbd>打开控制台，将刚刚复制的文段张贴在控制台光标闪烁的位置，回车完成。  
3 如何使用?  
打开命令面板<kbd>ctrl+shift+p</kbd>，然后敲package contrl:install package(package install也可以匹配得到),然后回车。这里可能要过一会，因为要加载插件列表，根据每台电脑环境的不同，时间也不同。加载完后有一个弹窗，搜索想要的插件，然后回车完成。
- emmet  
1 什么是emmet?*  
是一个提高 HTML 和 CSS 开发工作的前端开发者工具。说白了就是可以少敲代码。  
2 怎么安装?  
打开 package control : install package , 搜索 emmet ,回车完成。 emmet 需要 py8 的支持才可以用起来，一般会自动下载。但是因为可能是网络原因，需要手动安装。[py8安装教程](https://www.jianshu.com/p/ab47772fe88e)和[py8项目地址](https://github.com/emmetio/pyv8-binaries).  
3 如何使用?  
这里是一份 emmet 的[cheatsheet](https://docs.emmet.io/cheat-sheet/),里面有详细的介绍。  
- jsFormat  
1 什么是jsFormat?* 
就是把javascript代码格式化；  
2 如何安装?  
打开 package control : install package,搜索jsformat,回车完成。  
3 如何使用?*  
[jsformat项目](https://github.com/jdavisclark/JsFormat)有详细介绍。  
- sublimeCodeIntel
1 什么是sublimeCodeIntel?  
这是一款代码提示插件，支持多种语言，说白了可以作弊，毕竟人的大脑有时反应不过来，需要提醒。  
2 怎么安装？  
打开 package control : install package , 搜索sublimeCodeIntel,回车完成。  
3 如何使用？  
在敲代码过程中自动出翔提示，使用上下箭头键筛选，回车选择。  
# Day01  
