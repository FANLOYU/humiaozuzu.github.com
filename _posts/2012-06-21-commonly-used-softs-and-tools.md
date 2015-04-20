---
layout: post
title: "常用软件和工具的选择原则和使用技巧"
category: mac
---

作为Win/Linux/Mac都玩过几年的菜鸟，下面将简单的介绍下我喜欢的软件以及喜欢的原因。

软件选择原则
=========
* 专注
* 统一
* 跨平台
* 云+版本控制

这里可以先pass，后面很多的例子会说明。

手机常用服务
==========
![Google同步](/assets/images/google-sync.png)

只需要一个Google帐号，就可以将你的联系人，Gmail，谷歌日历以及音乐(强推Google Music服务)从Google服务器同步到你的手机上。是不是很方便，这就是统一的好处(原则三)。同样，你是不是觉得每天同时开QQ/飞信/人人桌面这些很麻烦呢，试试Pidgin吧。

另外，这也是喜欢刷机的同学必备的技能啊:P(喜欢刷机的同学的另一个神器就是「钛备份」啦)。就算你的手机丢失了，所有重要的信息也不会丢失，因为他们都在云端(原则四)。

电脑常用服务
==========
* 个人资料 - Dropbox(跨平台)，空间不够的去淘宝花10块钱扩容吧:)
* 编程相关的配置文件 - 可以参考我的[「如何备份与分享Linux下的配置文件」](/blog/2012/03/23/howto-backup-and-share-linux-config-files/)
* 音乐 - iTunes(仅仅支持Win+Mac，可以同步到Google Music)，这里也可以参考我的[「如何用iTunes管理音乐」](/blog/2012/06/15/manage-music-with-itunes/)
* 电子文档 - Calibre(跨平台)
* 密码管理 - Lastpass(因为是浏览器插件，所以跨平台了)
* 笔记 - Evernote，Linux下叫Nixnote，也可以用Web版
* 信息源 - Google Reader(跨平台/统一)
* IM聊天记录 - 我主要使用Gtalk，所有的聊天记录都会在Gmail中保存，下图演示了在Gmail中搜索聊天记录的功能

![Search Chats in Gmail](/assets/images/gmail-chats.jpg)


说完了推荐的服务也说下不推荐的：

* 不推荐用rar格式压缩文件(原因Google之)
* 不推荐用M$的文档，用pdf吧(小心简历直接被删:P)
* 不推荐用盛大的麦库等国内的云笔记，因为麦库不仅仅没有跨平台(没有Mac和Linux版)，而且没有跨软件。未来的某天你发现盛大流氓了想换国外的服务，突然发现他根本没有提供数据导出的功能，那时候你就欲哭无泪了。Evernote的三大原则：数据是用户的；数据是受保护的；数据是可转移的，国内的服务基本上一条都做不到。
* 不要用国内的服务
* 不要用M$的服务

接下来是使用软件的一些好的习惯：

专注
====
专注在一个模式里面，而不是在多个模式中导出切换就可以得到效率的极大提高。

* 不要老在键盘和鼠标间切换
* 不要老在gui和cli中切换


但是，他们2个各有精通，完全离开另一个也是不可能的，所以我们要做的就是把切换的代价减到最小。于是，Apple发明了Trackpad和各种神奇的手势解决了鼠标的问题。后面的可以用下面的方法解决：

* 使用Lancher和Dock快速启动程序

![Alfred](/assets/images/alfred.png)
![Dock](/assets/images/dock.jpg)

* 在文件浏览器中可以快速的切换到终端

![Open in Terminal](/assets/images/open-in-terminal.jpg)

* 在终端中可以快速的执行Gui程序，Linux下直接执行gui程序对应的命令或者用`xdg-open`，Mac下用`open -a Application`

了解事物的本质
===========
* 学习一门[Lightweight markup language](http://en.wikipedia.org/wiki/Lightweight_markup_language)，而不是可视化编辑器
* 学习使用Editor，而不是IDE，继续推荐自己的[「为什么你应该用Editor而不是IDE」](http://miao.hu/2012/06/07/why-you-should-use-editor-and-not-ide/)


学会使用filter
============
这是一种缩小范围，逐步求精的思维

* Google中进行搜索：

![Google Search](/assets/images/google-search.png)

* Spotlight搜索文件：

![Spotlight](/assets/images/spotlight.png)

* Chrome中搜索目标配置选项的位置：

![Chrome Settings](/assets/images/chrome-settings.jpg)

* Chrome标签页中搜索关键字：

![Chrome Find](/assets/images/chrome-find.jpg)

包括前面的Gmail中搜索聊天记录也是。如果你足够细心，会发现设计优秀的软件或多或少会引入filter的功能。

统一化
=====
* Mac下统一的快捷键，用过会发现Mac做的是做好的
* 学会Vim后就可一编辑所有的编程语言了！
* Pidgin/Adium可以登录很多IM！
* Android上的Google账户同步功能真的太方便了！
* 学习[readline](http://linuxtoy.org/archives/readline.html)这个行编辑库的[快捷键](http://www.bigsmoke.us/readline/shortcuts)，因为unix下的软件只要有行编辑，基本都会用到他，bash会，Firefox会，Chrome也会。
