<div align="center">
   <img width="160" src="docs/mirai.png" alt="logo"></br>

   <img width="95" src="docs/mirai.svg" alt="title">

----

![Gradle CI](https://github.com/mamoe/mirai/workflows/Gradle%20CI/badge.svg?branch=master)
[![Download](https://api.bintray.com/packages/him188moe/mirai/mirai-core/images/download.svg)](https://bintray.com/him188moe/mirai/mirai-core/)
[![Maven Central](https://img.shields.io/maven-central/v/net.mamoe/mirai-core-api.svg?label=Maven%20Central)](https://search.maven.org/search?q=net.mamoe%20mirai)
[![Gitter](https://badges.gitter.im/mamoe/mirai.svg)](https://gitter.im/mamoe/mirai?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

mirai 是一个在全平台下运行，提供 QQ Android 协议支持的高效率机器人库

这个项目的名字来源于
     <p><a href = "http://www.kyotoanimation.co.jp/">京都动画</a>作品<a href = "https://zh.moegirl.org.cn/zh-hans/%E5%A2%83%E7%95%8C%E7%9A%84%E5%BD%BC%E6%96%B9">《境界的彼方》</a>的<a href = "https://zh.moegirl.org.cn/zh-hans/%E6%A0%97%E5%B1%B1%E6%9C%AA%E6%9D%A5">栗山未来(Kuriyama <b>mirai</b>)</a></p>
     <p><a href = "https://www.crypton.co.jp/">CRYPTON</a>以<a href = "https://www.crypton.co.jp/miku_eng">初音未来</a>为代表的创作与活动<a href = "https://magicalmirai.com/2019/index_en.html">(Magical <b>mirai</b>)</a></p>
图标以及形象由画师<a href = "https://github.com/DazeCake">DazeCake</a>绘制
</div>


## mirai

**[English](README-eng.md)**  

## 声明

### 一切开发旨在学习，请勿用于非法用途

- mirai 是完全免费且开放源代码的软件，仅供学习和娱乐用途使用
- mirai 不会通过任何方式强制收取费用，或对使用者提出物质条件
- mirai 由整个开源社区维护，并不是属于某个个体的作品，所有贡献者都享有其作品的著作权。

### 许可证

    Copyright (C) 2019-2021 Mamoe Technologies and contributors.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as
    published by the Free Software Foundation, either version 3 of the
    License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

`mirai` 采用 `AGPLv3` 协议开源。为了整个社区的良性发展，我们**强烈建议**您做到以下几点：

- **间接接触（包括但不限于使用 `Http API` 或 跨进程技术）到 `mirai` 的软件使用 `AGPLv3` 开源**
- **不鼓励，不支持一切商业使用**

鉴于项目的特殊性，开发团队可能在任何时间**停止更新**或**删除项目**。

### **mirai 的形象图及项目图标都拥有著作权保护。**
**在未经过允许的情况下，任何人都不可以使用形象图和图标，或本文初的有关 mirai 名称来历的介绍原文，用于商业用途或是放置在项目首页，或其他未许可的行为。**

### 衍生软件需声明引用

- 若引用 mirai 发布的软件包而不修改 mirai，则衍生项目需在描述的任意部位提及使用 mirai。
- 若修改 mirai 源代码再发布，**或参考 mirai 内部实现发布另一个项目**，则衍生项目必须在**文章首部**或 'mirai' 相关内容**首次出现**的位置**明确声明**来源于本仓库 (`https://github.com/mamoe/mirai`)。不得扭曲或隐藏免费且开源的事实。

## 协议支持

<details>
  <summary>支持的协议列表</summary>

**消息相关**

- 文字
- 原生表情
- 商城表情
- 戳一戳
- 图片 （自定义表情）
- XML，JSON 等富文本消息
- 长消息（5000 字符 + 50 图片）
- 引用回复
- 合并转发
- 撤回
- 提及群员
- 提及全体成员
- 语音
- 闪照
- 撤回群员消息
- 自定义消息
- 音乐分享

**群相关**
- 群列表
- 成员列表
- 群员权限
- 禁言
- 全体禁言
- 群公告管理
- 群设置（自动审批、入群公告、坦白说、成员邀请、匿名聊天）
- 处理入群申请
- 移除群员

**好友相关**
- 完整好友列表
- 处理新好友申请
- 删除好友

**其他客户端**
- 同步其他客户端的消息
- 向其他客户端发送消息

</details>

#### 不会支持的协议
- 金钱相关，如点赞、收付款
- 敏感操作，如主动添加好友、主动加入群、主动邀请好友加群
- 安全相关，获取账号登录凭证(token，cookie等)

**一切开发旨在学习，请勿用于非法用途**

## 开始

- 开发文档: [docs](docs/README.md)
- 更新日志: [release](https://github.com/mamoe/mirai/releases)
- 开发计划: [milestones](https://github.com/mamoe/mirai/milestones)
- 讨论: [GitHub Discussions](https://github.com/mamoe/mirai/discussions) 和 [Gitter](https://gitter.im/mamoe/mirai?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
  > 在 GitHub Discussions 提出的问题可能会收到 mirai 维护者的回复, 也欢迎分享你基于 mirai 的项目或想法.
  >
  > *除这两个途径外，Mirai 在各个平台均没有官方交流群或论坛*

- mirai 官方系列项目: [project-mirai](https://github.com/project-mirai)
- mirai 社区相关项目: [awesome-mirai](https://github.com/project-mirai/awsome-mirai/blob/master/README.md)

- 帮助 mirai: [CONTRIBUTING](CONTRIBUTING.md)

## 鸣谢

> [IntelliJ IDEA](https://zh.wikipedia.org/zh-hans/IntelliJ_IDEA) 是一个在各个方面都最大程度地提高开发人员的生产力的 IDE，适用于 JVM 平台语言。

特别感谢 [JetBrains](https://www.jetbrains.com/?from=mirai) 为开源项目提供免费的 [IntelliJ IDEA](https://www.jetbrains.com/idea/?from=mirai) 等 IDE 的授权  
[<img src=".github/jetbrains-variant-3.png" width="200"/>](https://www.jetbrains.com/?from=mirai)
