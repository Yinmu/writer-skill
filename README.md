<div align="center">

# Writer.skill

> *「文字是作家的指纹。蒸馏它，是为了理解并复刻那种灵魂的节奏。」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**Writer.skill 帮你蒸馏任何作家的写作灵魂，让海明威、鲁迅、余华、马尔克斯都成为你的专属文案教练。**

<br>

**只需输入一位作家的名字，Writer.skill 自动完成：风格语料研判 -> 语法节律提取 -> 写作 DNA 注入 -> 风格化改写。**

<br>

[效果示例](#效果示例) · [安装](#安装) · [它蒸馏了什么](#它蒸馏了什么) · [工作原理](#工作原理) · [关于作者](#关于作者)

<br>

**其他语言 / Other Languages:**

[English](README_EN.md)

</div>

---

## 效果示例

```
用户      > 用鲁迅的风格，锐评现在的“职场内卷”

鲁迅      > 我向来是不惮以最坏的恶意，来推测现在的职场法则的。
            但见那一群年轻人，如没头的苍蝇，在写字楼里乱撞。
            这叫什么？这叫“卷”。
            其实，不过是换了一种吃人的方式。
```

```
用户      > 蒸馏海明威，重写这段话：我们必须在截止日期前完成任务，否则就会被开除。

海明威    > 截止日期就在那里。那是一堵墙。我们必须撞过去。
            如果不撞过去，就没命了。
            就是这样。
```

---

## 安装

```bash
npx skills add Yinmu/writer-skill
```

然后在 Claude Code 或 Hermes 中直接调用：

```bash
> 蒸馏鲁迅
> 用海明威的风格重写我的工作周报
> 切换到余华视角，改写这段描述
```

---

## 它蒸馏了什么

| 层次 | 说明 |
|---|---|
| **词汇特征图谱** | 偏好词汇、禁止词、特有俚语 |
| **语法节律重构** | 长短句节奏、从句嵌套逻辑、标点习惯 |
| **意象映射** | 描写对象（如海明威的自然 vs 马尔克斯的魔幻） |
| **写作 DNA** | 如何开篇、如何收尾、叙事视角切换 |

---

## 工作原理

**1. 多维研判**：6 个 Agent 并行采集（著作、访谈、书信、评论家视角）。
**2. 三重提炼**：
   - **语义指纹**：提取作者最独特的用词组合。
   - **节奏锚点**：解构作者标志性的句子结构。
   - **意象库**：建立作者专属的感官描写辞典。
**3. 风格注入**：将这些“指纹”注入你的原稿，进行语义对齐改写。

---

## 已蒸馏作家库

| 作家 | 领域 | 独立仓库 | 一键安装 |
|---|---|---|---|
| 鲁迅 | 批判现实/白描 | [lu-xun-perspective](examples/lu-xun-perspective) | `npx skills add Yinmu/lu-xun-perspective` |
| 余华 | 极简叙事/苦难 | [yu-hua-perspective](examples/yu-hua-perspective) | `npx skills add Yinmu/yu-hua-perspective` |
| 汪曾祺 | 生活美学/通透 | [wang-zengqi-perspective](examples/wang-zengqi-perspective) | `npx skills add Yinmu/wang-zengqi-perspective` |
| 当年明月 | 历史解构/通俗 | [dangnian-mingyue-perspective](examples/dangnian-mingyue-perspective) | `npx skills add Yinmu/dangnian-mingyue-perspective` |
| 莫言 | 魔幻现实/本能 | [mo-yan-perspective](examples/mo-yan-perspective) | `npx skills add Yinmu/mo-yan-perspective` |
| 刘震云 | 世俗逻辑/循环 | [liu-zhenyun-perspective](examples/liu-zhenyun-perspective) | `npx skills add Yinmu/liu-zhenyun-perspective` |
| 王朔 | 反叛/解构 | [wang-shuo-perspective](examples/wang-shuo-perspective) | `npx skills add Yinmu/wang-shuo-perspective` |
| 海明威 | 冰山叙事/硬汉 | [ernest-hemingway-perspective](examples/ernest-hemingway-perspective) | `npx skills add Yinmu/ernest-hemingway-perspective` |
| 马尔克斯 | 魔幻/诗意 | [gabriel-garcia-marquez-perspective](examples/gabriel-garcia-marquez-perspective) | `npx skills add Yinmu/gabriel-garcia-marquez-perspective` |
| 莎士比亚 | 戏剧/诗意 | [william-shakespeare-perspective](examples/william-shakespeare-perspective) | `npx skills add Yinmu/william-shakespeare-perspective` |

---

## 关于作者

**[Yinmu](https://github.com/Yinmu)**————一个关注思维框架拆解、喜欢研究作家风格与 AI 协作的实践者。
| 平台 | 链接 |
|---|---|
| **公众号** | BookNote |
![示例图](/ "本地演示图")
---

<div align="center">

**Nuwa.skill 蒸馏人的思维。**<br>
**Writer.skill 蒸馏人的文字。**
感谢 [@花生](https://github.com/alchaincyf)

<br>

MIT License © 2026 [Yinmu](https://github.com/Yinmu)

</div>
