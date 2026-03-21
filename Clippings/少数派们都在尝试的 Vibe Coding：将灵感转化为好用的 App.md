---
title: "少数派们都在尝试的 Vibe Coding：将灵感转化为好用的 App"
source: "https://mp.weixin.qq.com/s/G83y83orFcRu2mJFAlLesA"
author:
  - "[[Matrix机器人]]"
published:
created: 2026-03-21
description: "告别繁琐的语法束缚，Vibe Coding 让我们仅凭自然语言，就能让 AI 将灵感瞬间转化为代码。"
tags:
  - "clippings"
---
原创 Matrix机器人 *2026年3月21日 12:32*

**告别繁琐的语法束缚，Vibe Coding 让我们仅凭自然语言，就能让 AI 将灵感瞬间转化为代码。这种全新的体验正在重塑开发日常。本期一派，一起来聊聊和 AI 共舞的心流时刻。**

**

翻看大家的分享，不少派友已经把这份体验变成了实打实的作品。涵盖了移动端 App、效率工具，甚至还有「远古软件」的平替。只要有个好点子，Vibe Coding 就能带你跨越技术门槛。

**

****▍移动端 App****

****目录****

📞 Pixel Telo：拦截通讯骚扰来电

🧭 Pixel Geo：：显示朝向与经纬度

🔗 LinkSet：云端分组管理链接

👐 GestureExplode：画个手势直达应用

🎶 SOENT：播放专注放松音频  

Pixel 工具：电话拦截与指南针

@ Mystery0：继 PixelMeter 尝到 Vibe 的甜头之后，又列出了几个需要自己开发的需求想法，最近完成的 Pixel Telo 和 Pixel Geo 都是通过 Vibe coding 生成的，和 Pixel Meter 一样，先和 Gemini 讨论需求与技术实现方案，然后搭建项目框架、代码原型验证、使用 Claude Code 按照完整需求进行开发、运行调试、上架准备与申请。 都是一些小众或者很简单的需求，就不考虑收费相关了，反正 Claude 订阅，不用就感觉亏了。

Pixel Telo：适用于 Pixel 手机的电话拦截 App，一定程度上可以视为 CC 来电拦截 N+ 的继任者，我昨天写了专门的文章介绍它：

https://sspai.com/post/107136

![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

Pixel Geo：十分小众的场景，就是看下指南针和经纬度，需求来源于我爸。他用的 iOS，有一天要求截一个带经纬度的图发微信群里，但是国行 iOS 不显示经纬度，他就去下载了一个指南针 App，结果这个 App 绑定订阅，虽然提供试用但是对于老年人来说还是可能会搞不明白付费和订阅，况且我觉得这一个小小的功能不值这点钱。因此 vibe 了一个，直接在 App Store 搜索「Pixel Geo」或者「原点罗盘」就可以下载，Android 端也上架了 Google Play，同样搜索这两个名字。

开源地址：

https://github.com/Mystery00/PixelGeo

LinkSet：云端分组管理链接

@ 臭小子7877：Vibe Coding 了一个链接管理与批量打开多个链接的小工具：LinkSet。

最初是为了解决每天工作需要打开固定的多个网址的问题，将链接进行分组，且可在菜单栏一键打开提高效率。 现在已经变成自己离不开的链接收藏工具了，每次打开 X 或者是少数派都会遇到需要收藏的链接。通通都保存到 LinkSet 中，所以也开发了 iOS 版本。

因为平时一些杂乱的东西也会先丢到 Apple 的备忘录中，所以为了相同的体验（用起来顺手），我直接参考了 iOS 备忘录的操作逻辑进行开发。且 iOS 端没有数量的限制，能 iCloud进行同步。我希望对需要的用户来说这是一个可以长期使用的软件，而不是一个阉割版。

个人感觉现在 Vibe Coding 虽然简单，但是比如整个上架流程以及产品的构思、功能的设计还是需要静下心认真思考的，少数派上的「100 小时后请叫我苹果开发者」栏目也给了我很多帮助，让我从小白可以依靠 Vibe Coding 成功做出产品并上架商店。

以下是我的软件，欢迎体验：  

https://apps.apple.com/cn/app/id6757075244

![Image #0](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #1](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

GestureExplode：画个手势直达应用

@ colorbeta：Android最喜欢的软件，Google 的 gesturesearch，效率 No.1，2015 年停更后一直没有合适的替代。32 位也无法兼容最新的手机了。 基于 AI 自己手搓了一个，可以通过手势输入字母来搜索手机联系人，应用，设置，无需联网权限。 比如输入 gd，就可以查到到高德地图。输入 LDH，就可以找到刘德华。

欢迎大家食用：

github.com/colorbeta/GestureExplode

![Image #0](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

SOENT：播放专注放松音频

@ Jeray：1️⃣最满意也是开发最久的应用 SOENT，用于播放专注、放松、平静、睡眠场景的减压音乐。因为同时要工作，断断续续开发，时间跨度两年，最近终于上架苹果应用商店。也是自己第一次尝试开发的应用。 因为市面上的音乐应用各种信息流，想要个极简不分心的减压场景音乐应用，设计和用户体验打磨了很久。接的是 Apple Music 资源。

2️⃣我是设计师，不懂开发，开发过程遇到无数个问题。一个小问题，AI就是找不到问题核心，折腾好多遍，反复试错。音乐播放类应用涉及很多状态，也增加了开发的复杂度。

3️⃣早期用的是 ChatGPT，两年前还没什么更好的选择。后来主要用的是 Cursor，订阅马上结束了……眼馋 Claude Code 和很多新工具。

4️⃣感觉底层架构能力取决于是完全依赖 AI、还是有自己的思考投入，每个人的情况不同吧。

🔗苹果App Store：

https://apps.apple.com/us/app/soent/id6758525381

![Image #0](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

********▍**** 网页及 Web 应用****

****目录****

🌅 风光摄影模拟器：足不出户拍摄风光

📰 Horizon：轻松速读多源新闻摘要

📑 Post：多端文本与文件分享服务

**风光摄影模拟器：足不出户拍摄风光**

@ HurricaneDD：我来介绍一下我做的「风光摄影模拟器」

去年我在使用一个 App 叫「极摄」，有模拟的地形和卫星图，还能显示太阳、月球轨迹和焦段，进行摄影的时候可以提前得知大致的焦段和光线情况。

可惜它停止运营了，由于有相关的开发经验，我注意到那个 App 基于是一个开源库 CesiumJS，于是我便在AI的帮助下做了个简单版的。

图一是云南迪庆州梅里雪山观景台，图二是在丽江古城看玉龙雪山。

![Image #0](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #1](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

**Horizon：轻松速读多源新闻摘要**

@ Thysrael：大家好，我分享一款我 vibe coding 出的辅助读新闻的 agent -- Horizon

项目地址：

https://github.com/Thysrael/Horizon/  

自用的日报网站：  

https://thysrael.github.io/Horizon/  

平时自己读新闻的时候，要从多个地方去找新闻，而且经常读到很多水文，或者看不懂的文章。 它可以从自定义的新闻源（目前支持 RSS，HackerNews，Reddit，Github，Telegram）上抓取新闻，并用 AI 进行筛选。 对于高质量的新闻，AI 撰写一个总结文章，而且还会搜集社区的讨论与观点（基于 hackernews 和 reddit 的评论区），并补充理解新闻的概念知识（基于网络搜索，避免幻觉），最终生成一份日报，并且发布到网站上（基于 github page）。 欢迎大家 star 支持一下，如果有任何建议，我也会积极处理。

![Image #0](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #1](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #2](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #3](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

****Post** ：多端文本与文件分享服务**

@ mirtle：用 Codex (gpt 5.4）搭了一个文本、文件、网页分享 API 和对应的 Web UI、CLI 和配套的 Agent 的 Skill。

https://github.com/mirtlecn/post （Node 前后端）  

https://github.com/mirtlecn/post-go （Go 纯 API）

https://github.com/mirtlecn/post-cli （CLI）

整个大概花了 4 个会话，一个会话定计划，三个会话做实现，图片是一个大功能迭代 + 数据结构改造里面，我起的作用（我说的话）。

最神奇的： 短短 1 年，AI Agent 类应用的进步之大。我之前有重写 Node 后端 + 拓展功能的想法，但 Cursor 等不能胜任。Codex 则完整重写了整个项目，里面含一些很绕的逻辑，但完成度极高。WebUI 部分我指定了 UI 库，想让设计不落 AI 窠臼，给 PRD，AI 还原的很有品味。而且显然，能力还能再发展。

Codex 类应用，大概率会侵占很多传统 IDE 类应用（Cursor）等份额。

无语时刻也有：

一开始刚用，Codex 确认会让人抓狂：核心是信息过时，去年的新东西大多不清楚，新的 SDK 不会用，导致程序实现，架构设计过于复杂/改需求，譬如认为 Redis 某个数据结构就是不支持 TTL，review 它的代码有一些头疼。而因为他不会像现实的人一样告诉你「这个不会做」，容易把自己绕了进去。这时候人的思路就要开拓一下了。 意识要现实中的产品经验，落地实践，版本迭代流程全部写进 Agent.md，遵循一些技巧。这样，和 Codex 的交流已经变成了「好」、「继续」、「继续」的可无人值守。至少单元测、核心流程的功能测都能通过。

可能一部分不在产研流程的朋友，高估了现实中的研发流程的复杂度和交付质量，个人和 Codex 落地，遇到的问题，同样是现实那些：需求考虑不周，程序断言奇怪，历史逻辑复杂，测试用例覆盖不全 ……

不满意的：

前端交互交付：Agents 在前端还原上还是有提升空间的。不清楚有无 UI/UX 高质量生成。

AI 注意力有限：虽说长上下文声称 1 百万 token，实际上大概到 20 万上下文就开始忘记。这个可能远比不上真人。上下文怎么组织，还得 AI 应用的产品技术多探索。

至于最后一个问题，我觉得长期看，所谓「代码」乃至「架构」只是达成目的的工具，「丢失与否」不是问题，可能焦虑的是自己的饭碗，至少身边不少公司已经在大改产研运营流程。

![Image #0](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

********▍**** 浏览器插件****

****目录****

📖 allai：浓缩长文智能伴读

📝 Dont reset Password：唤醒你的密码记忆

allai：浓缩长文智能伴读

@ 老王以为：作为程序员，算是比较早接触 vibe coding 的，各种工具都试过了，现在的主力还是 cursor 和 Claude Code。最近在优化各种 skills 让他们更好地为我服务。从去年开始陆陆续续开发了一个chrome 插件，主要是为了解决我有的时候在浏览网页时的两个功能：

1\. 有部分内容需要问 AI，如果没有这个工具需要自己复制内容然后再去问 AI，挺麻烦的；

2\. 需要对文章进行总结概述，整篇文章复制麻烦或者会丢失部分图片内容等。

所以就给自己开发了这个插件，最近也在开发一个有意思的功能，就是存储各个 AI 平台的聊天内容，如 DeepSeek、豆包、ChatGPT 等，然后再将各个聊天的内容再进行分析，应该是个挺好玩的东西。插件的地址如下，感兴趣的朋友可以去玩玩。

https://chromewebstore.google.com/detail/llogfbeeebfjkbmajodnjpljpfnaaplm?authuser=0&hl=zh-CN

![Image #0](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #1](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #2](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #3](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

**Dont reset Password：唤醒你的密码记忆**

@ 青南：Dont reset Password:

https://drp.kingname.info/

密码记不住，不一定是因为你记性不好，而是你忘记了这个网站的密码是什么规则。 不敢用密码管理器，担心泄露了就全完了。那你试一试我这个插件。

![Image #0](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #1](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

********▍**** 效率辅助工具****

****目录****

📃 ZotWatch：生成文献推荐 RSS

📒 Bitwarden 拓展：快捷检索本地密码库

ZotWatch：生成文献推荐 RSS

@Yorkson：分享一个我做的工具：ZotWatch，通过 Zotero 数据库中的已有文献信息构建画像，并通过 GitHub Action 结合每天新发表的文献，自动生成文献兴趣推荐的 RSS。 做这个工具的出发点是之前用常规的期刊 RSS 在追踪，但是部分期刊发的东西太多太杂，用关键词之类过滤也很不方便，后来想到自己长期使用后的Zotero文献库就是最好的过滤条件。 一直想写个 sspai 文章介绍一下，但拖了很久到现在也没写。 附图是在 RSS 工具中订阅生成 RSS 源的效果。

更全面的工具介绍：

https://blog.yorks0n.com/articles/zotwatcher/  

链接及配置方法：  

https://github.com/Yorks0n/ZotWatch  

另外写点一派的讨论内容。我最初用过 claude code，但它用起来不太方便（稳定），后来 codex 出来用着也不错，就一直订阅至今。最大的感受是，去年一年 ai 编程能力的提升真是飞快，有个项目早期因为有 bug 一直优化不好就放着了，等了几个月 ai 能力进步，再去修 bug 一会儿就解决了。

![22bbc8079f46c923e28af89d752417ce.png (3052×1992)](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

22bbc8079f46c923e28af89d752417ce.png (3052×1992)

**Bitwarden 拓展** ：快捷检索本地密码库  

@ kusutori：去年底的时候完成的，为微软 Powertoys 的命令面板写了一个 Bitwarden 的拓展，当前还是 Opus4.5，由于微软的命令面板也才正式发布不久，网上压根一个第三方资料都没有，只有微软 Learn 里面的官方文档，模型它自己当然是一点都没学过，而且微软文档写的烂也不是一天两天的了，上来就给你个 API 大全，还得自己去看接口的源代码。

写了很长的提示词告诉模型这个项目是什么，以及应该从哪里去获得资料，得益于 context7 以及 tavily 提供的 web search，模型自己花了很长时间去学习如何做拓展，仅仅使用了两轮 copilot 对话，它就做出了一个完整的原型出来，这个是非常震惊的，我最初对他压根就不抱什么希望，毕竟以前写过 winui3 应用，很多模型生成的结果问题都很大，可能是因为写拓展的时候，只用写逻辑，不用自己写界面，所以比较简单一些。

之后又花了一些时间进行迭代，算是把需要用到的所有功能都加上了，包括：

- 基于密码和 Windows Hello 的密码库解锁
- TOTP 界面（这个问题挺多的，还没修好）
- 密码库列表以及详细信息窗格
- 快捷键实现复制用户名、密码、TOTP 等，对于不同的项目比如银行卡，也会有不同的快捷键
- 以及创建、删除项目也都有，连回收站都做出来了
- 可以说除了 passkey 以外的全部功能都完成了，我个人现在每天都在用
![Image #0](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #1](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #2](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #3](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #4](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #5](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E) ![Image #6](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

  

---

在这个不再被语法局限的时代，每一个能解决实际问题的点子都闪闪发光。你目前最想用 AI 帮自己解决什么痛点？或者已经用 Vibe Coding 做出了哪些有趣的小玩意？更精彩的讨论还在继续。

如果想看到更多派友的经验分享，或者想晒出自己的心路历程，欢迎参与一派讨论话题：  

点击跳转：

晒晒你的 Vibe Coding 作品：代码能有多野？

  

******/** **更多热门文章** **/******

![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

阅读原文

继续滑动看下一个

少数派

向上滑动看下一个