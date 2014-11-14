---
layout: post
title: "PKM 流程及工具系列介绍"
category: productivity
---

说到 PKM(Person Knowledge Management)，大家一定会想到各种麻烦的工具，复杂的理论，实际上，他并不复杂，因为支撑这些工具的原理都是相似的：

![PKM Workflow](/assets/images/pkm-workflow.jpg)

这张图介绍了经典的 PKM 工具帮助我们处理有用的信息（或者叫知识）的流程：

1. 每天我们都会接触各种各样的知识：SNS、RSS、课程等；
2. 我们对于无意义或者自己不感兴趣的东西就直接忽略；
3. 如果是我们需要了解或者感兴趣的东西就开始学习他们，并将知识的精华/框架记忆到大脑中；
4. 但是呢，人脑往往是记忆能力有限的，所以很多细节方面的东西（可能是电子版也可能是纸质）我们将之存档起来，方便我们以后查阅；
5. 有时我们时间不够，但是也不愿意错过眼前的一些知识（贪心），于是我们将之保存在暂存区（比如用个小本本记录要学习的东西），在以后有时间时再把知识消化；

这里，对我们来说最重要的就是存档系统，他决定了一个人的知识的丰富程度。

其次，我们学习知识的目的就是能够在生活中用到他，能够快速的将以前学习过的知识提取出来也是一种非常重要的能力。这就取决于我们存档的知识归类是不是明细，种类够不够丰富了。

以上就是所有的知识管理工具共有的特点，只要按照上面的流程管理，所有操作都变得十分简单。

优点
----

### 暂存区 ------ 灵感的聚集地
欧阳修曾说过：「余平生所作文章，多在三上，乃马上、枕上、厕上也。」

我对上面这句话深有体会，因为自己解决问题的时候通常不在专心思考的时候。所以捕捉到这些灵感非常重要，你可以利用随身携带的笔记本或者手机里面的笔记软件 (Evetnote) 将之记录下，到以后需要用到时你就知道这些思考的价值了。

另一个经典的应用场景就是 Pocket，平时浏览网页时看到了一篇不错的文章，关掉吧，可惜了；保存为书签呢，以后肯定不会去看他了 = =；不关闭标签放在浏览器上面提醒自己以后看，不过几天标签就过百了 T_T

![Chrome tabs](/assets/images/chrome-tabs.jpg)

不过自从有了 Pocket，浏览器不卡了，关标签蛋也不疼了，一键推送到手机，想看就看（用 Readability 和 Instapaper 的表吐槽我）。看完后保存到 PinBoard 或者 Delicious 就完成了存档的步骤。

### 存档区 ------ 装 X 的资本

管理好自己的知识库不是简单的事情，需要一个人对相关的知识有框架性的了解，所以这会促进一个人对知识结构的理解。

当自己的知识库的资料足够丰富以后，遇到相似的问题就可以直接在自己的知识库里面进行搜索快速得到答案（比如写代码的时候找到一段有类似功能的代码，写文章的时候引用自己曾经的一些文章和观点等）。

当你感到自己某方面的知识做的非常满意以后，就可以share给大家看了。比如你搜集的某类型书籍的豆列，比如你写的某个开源项目 (Github)，比如一个漂亮的设计 (Dribble)，比如一个专题的思维导图 (MindPin)，比如 Google Plus 上牛人们的 Circle。正如刘未鹏在「[怎样花两年时间去面试一个人](http://mindhacks.cn/2011/11/04/how-to-interview-a-person-for-two-years/)」中说到的，这些才是一个人最好的简历。


工具列表
------
最后看看这个系列文章中要介绍的工具，他们都遵循前文介绍的原则。

<table border="1px" cellspacing="0px" align="center">
  <tbody>
    <tr>
      <th>类别</th>
      <th>Web 服务</th>
      <th>平台支持</th>
      <th>云端存储</th>
      <th>版本控制</th>
      <th>分享平台</th>
      <th>索引支持</th>
    </tr>
    <tr>
      <td>电子书</td>
      <td>无</td>
      <td>全平台：Calibre<br>OS X：iDocument</td>
      <td colspan="2">借助Dropbox</td>
      <td>Douban Book</td>
      <td>软件内置</td>
    </tr>
    <tr>
      <td>音乐</td>
      <td>Google Music</td>
      <td>OS X/Windows：iTunes</td>
      <td colspan="2">Google Music</td>
      <td>虾米音乐/QQ音乐/豆瓣音乐</td>
      <td>iTunes 内置</td>
    </tr>
    <tr>
      <td>思维导图</td>
      <td>MindPin</td>
      <td>全平台：XMind<br>OS X：MindNote Pro</td>
      <td colspan="2" rowspan="2">借助 Dropbox</td>
      <td>MindPin</td>
      <td>MindNote Pro 内置</td>
    </tr>
    <tr>
      <td>照片管理</td>
      <td>Flickr</td>
      <td>OS X：iPhoto/Aperture</td>
      <td>Instagram/Flickr</td>
      <td>软件内置</td>
    </tr>
    <tr>
      <td>邮件</td>
      <td>Gmail</td>
      <td>OS X: Sparrow</td>
      <td colspan="2" rowspan="7">本身就是 web 服务</td>
      <td>无</td>
      <td>Gmail 内置</td>
    </tr>
    <tr>
      <td>书签管理</td>
      <td>PinBoard（或者免费的 Delicious）</td>
      <td>OS X: Delish</td>
      <td>PinBoard</td>
      <td>PinBoard 内置</td>
    </tr>
    <tr>
      <td>RSS聚合</td>
      <td>Google Reader</td>
      <td>OSX: Reeder</td>
      <td>Google Reader</td>
      <td>Google Reader 内置</td>
    </tr>
    <tr>
      <td>Read Later</td>
      <td>Pocket</td>
      <td>OS X: Pocket</td>
      <td>Pocket</td>
      <td>Pocket 内置</td>
    </tr>
    <tr>
      <td>笔记管理</td>
      <td>Evernote（或者搭建其他的 wiki 系统）</td>
      <td>Evernote 支持全平台，Linux 下叫 NixNote</td>
      <td>Evernote</td>
      <td>Evernote 内置</td>
    </tr>
    <tr>
      <td>密码管理</td>
      <td>1Password（或者免费的 Lastpass）</td>
      <td>全平台</td>
      <td>无</td>
      <td>软件内置</td>
    </tr>
    <tr>
      <td>GTD</td>
      <td>Doit.im</td>
      <td>全平台：Doit.im<br>OS X：OmniFocus</td>
      <td>Schemer</td>
      <td>软件内置</td>
    </tr>
    <tr>
    <td colspan="8">以下是程序员专有工具</td>
    </tr>
    <tr>
      <td>代码托管</td>
      <td>Github</td>
      <td>全平台</td>
      <td>都在云端</td>
      <td>必须支持</td>
      <td>Github 就是最好的分享平台</td>
      <td>Github 内置</td>
    </tr>
    <tr>
      <td>代码片段</td>
      <td>Gist</td>
      <td>OS X：Dash</td>
      <td colspan="2" rowspan="2">借助 Dropbox/Github</td>
      <td>Gist</td>
      <td>Dash 内置</td>
    </tr>
    <tr>
      <td>配置文件</td>
      <td>Git</td>
      <td>全平台</td>
      <td>Github 分享</td>
      <td>Ack</td>
    </tr>
  </tbody>
</table>

后记
----

和 PKM 有关的核心概念还有 Mind Hacks 和 GTD，他们都是在这篇文章中没有提到的概念（其实这篇文章也没有说多少 PKM 的东西，仅仅是工具介绍），三者配合使用，相辅相成才能发挥最大的威力。我自己并没有对之做过多的研究，只能推荐一些不错的资源给大家：

- [Mind Hacks](http://mindhacks.cn)
- [战隼的学习探索](http://www.read.org.cn)
- [时间管理行动家](http://www.gtdlife.com)
