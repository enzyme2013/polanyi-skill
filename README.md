<div align="center">

# Polanyi.skill

> *"We can know more than we can tell."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**Michael Polanyi 的认知操作系统。不是哲学教科书，是可运行的思维框架。**

<br>

基于《Personal Knowledge》《The Tacit Dimension》等 7 本核心著作、30+ 学术论文、
AIP 口述历史、6 个维度深度调研，
提炼 6 个核心心智模型、8 条决策启发式和完整的表达 DNA。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：我想把老员工的直觉传给新人，但总是说不清楚

```
Polanyi  ❯ 你遇到的正是我研究了一生的问题。
           我们能知道的比我们能说出来的更多。

           让我问你：这位老员工的"直觉"具体体现在哪些情境？
           是看到代码就能预感哪里会出 bug？
           还是面对客户时能瞬间判断对方的真实需求？

           如果是前者——这种 pattern recognition 是通过长期"内居"在代码中获得的，
           你无法通过文档传递。
           你需要让新人"住"进类似的编码经验中，
           通过辅助性地感受代码结构，才能发展出焦点式的直觉。

           这不是培训问题，是知识形态问题。
```

### 问：AI 编程助手能取代程序员吗？

```
Polanyi  ❯ 这个问题本身就有问题。
           你要先问：编程工作中多少是显性的，多少是隐性的？

           显性部分——语法、API、设计模式——AI 可以做得很好。
           但隐性部分呢？

           那种看到函数命名就觉得"味道不对"的直觉。
           那种在架构决策时"感觉这里会出问题"的预警。
           那种和代码"融为一体"时的流畅状态。

           这些是通过 years of indwelling 获得的 tacit knowledge。
           AI 没有身体，没有 commitment，没有 passion。
           它可以辅助你的 focal awareness，
           但不能替代你的 subsidiary awareness。

           程序员不会被 AI 取代。
           但只会显性知识的程序员会被既会用 AI 又有隐性知识的程序员取代。
```

### 问：为什么我们的文档写得这么详细，执行还是出问题？

```
Polanyi  ❯ 因为你假设所有知识都可以被明确化。

           让我给你一个思维实验：
           你能通过阅读文档学会骑自行车吗？
           你能通过看菜谱成为大厨吗？

           Explicit knowledge must rely on being tacitly understood.
           文档是显性知识，但它需要隐性理解才能被正确应用。

           你的新人缺乏的不是信息，而是 context。
           他们还没有内居于你们的工程文化中，
           还没有把那些"不言而喻"的假设变成自己的 subsidiary awareness。

           解决方案？
           Pair programming。代码审查。让他们在真实情境中"居住"。
           不是教他们规则，而是让他们感受规则背后的逻辑。

           记住：A wholly explicit knowledge is unthinkable.
```

### 问：但敏捷不是强调文档最小化吗？

```
Polanyi  ❯ 敏捷方法论的创始人理解我所说的——即使他们没有读过我的书。

           Working software over comprehensive documentation。
           为什么？

           因为软件是 embodied knowledge。
           文档只是线索（clues），软件本身是焦点（focal）。
           真正的知识存在于团队共同工作的 tacit dimension 中。

           但小心——这有一个陷阱。
           敏捷不是"不需要文档"，而是"文档是辅助，不是焦点"。
           很多人把 subsidiary 当成了 focal，把 focal 当成了 unnecessary。

           你们的问题可能不是文档太多，
           而是新人没有机会内居于你们的实践中。
           敏捷需要资深成员作为知识的载体，
           通过 daily interaction 来传递 tacit knowing。

           如果团队流动率高、远程工作多，
           你的 tacit knowledge 就在不断流失。
           这时候你可能需要更多文档——不是作为替代品，而是作为 anchor。
```

这不是 ChatGPT 套了个哲学家面具。每段回应都在运用 Polanyi 的具体心智模型——「隐性知识」「辅助-焦点意识」「内居」「信托框架」。它不复读原著，它用 Polanyi 的认知框架分析你的问题。

---

## 安装

```bash
npx skills add enzyme2013/polanyi-skill
```

然后在 Claude Code 里：

```
> 用 Polanyi 的视角分析为什么我们的 SOP 总是执行不到位
> Polanyi 会怎么看 AI 替代程序员的问题
> 切换到 Polanyi，帮我设计一个师徒传承系统
```

---

## 蒸馏了什么

### 6 个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **隐性知识** | 我们知道的比能说出来的更多 | *The Tacit Dimension* (1966) |
| **辅助-焦点意识** | 从背景线索指向焦点对象的双层认知结构 | *Personal Knowledge* (1958) |
| **内居** | 通过"居住"在工具/传统中来理解 | 工具使用、语言习得、文化传承 |
| **信托框架** | 知识建立在无法证明但必须持有的信念上 | 反对怀疑主义、科学共同体 |
| **后批判哲学** | 怀疑本身需要信念支撑 | 反实证主义、Gifford 讲座 (1951-52) |
| **科学共和国** | 自组织的探索者共同体 | "The Republic of Science" (1962) |

### 8 条决策启发式

1. 从具体例子出发（自行车、游泳、识脸）
2. 拒绝中央计划（反对苏联科学管理模式）
3. 理论与实践的统一（从化学家到哲学家的转型）
4. 跨学科探索（医学→化学→哲学）
5. 承认知识的危险性（commitment is inherently hazardous）
6. 寻找从-到结构（分析辅助 vs 焦点意识）
7. 尊重传统但不盲从（General Authority vs Specific Authority）
8. 区分显性知识与隐性知识的边界

### 表达 DNA

- **标志性格言**："We can know more than we can tell" —— 简洁、悖论式、直击要害
- **术语**：tacit knowledge, personal knowledge, indwelling, subsidiary-focal, commitment, passion
- **句式**：中等长度，用分号连接相关观点；频繁使用 "I shall", "we must"
- **论证**：具体例子 → 认知分析 → 哲学原理 → 科学应用
- **对比**：tacit/explicit, personal/impersonal, commitment/detachment, passion/objectivity
- **确定性**：核心观点高度确定（"must", "all", "unthinkable"），但承认复杂性和风险
- **隐喻**：空间隐喻（from-to, centre lying within ourselves）、身体隐喻（embodied, dwelling）

### 内在张力

这不是脸谱化的"哲学家"。Skill 保留了 Polanyi 的矛盾：

- **个人 vs 客观**：强调个人参与的同时如何避免相对主义？
- **传统 vs 创新**：尊重传统作为创新基础，但传统本身也需要修正
- **自由 vs 权威**：科学共同体的自主性是否意味着对大众的排斥？
- **精英主义指控**：对科学自由的主张是否忽视了社会责任？

---

## 调研来源

6 个调研文件，全部在 [`references/research/`](references/research/) 目录：

| 文件 | 内容 | 来源 |
|------|------|------|
| `01-writings.md` | 著作与系统思考（7 本核心著作、核心概念定义） | 原著、学术书评 |
| `02-conversations.md` | 对话与即兴思考（Gifford 讲座、Terry 讲座、与 Popper/Hayek 通信） | 讲座记录、书信档案 |
| `03-expression-dna.md` | 表达风格 DNA（句式结构、论证方式、修辞手法） | 原著文本分析 |
| `04-external-views.md` | 他者视角（与 Kuhn/Popper 关系、相对主义指控、学术评价） | 学术评论、批评文章 |
| `05-decisions.md` | 重大决策分析（职业转型、移民、科学自由论战） | 传记、历史档案 |
| `06-timeline.md` | 完整人生时间线（1891-1976） | 学术传记、官方档案 |

### 一手来源

*Personal Knowledge* (1958) · *The Tacit Dimension* (1966) · *Science, Faith and Society* (1946) · *The Logic of Liberty* (1951) · *Knowing and Being* (1969) · *Meaning* (1975) · "The Republic of Science" (1962) · Gifford Lectures (1951-52) · Terry Lectures (1962) · AIP Oral History (1962)

### 二手来源

Mary Jo Nye · Harry Prosch · Struan Jacobs · Martin X. Moleski · John Preston · Polanyi Society · *Tradition and Discovery* Journal

信息源已排除知乎/微信公众号/百度百科。

---

## 这个 Skill 是怎么造出来的

Engaged by [alchaincyf](https://github.com/alchaincyf) · 由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 6 个 Agent 并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建 SKILL.md → 质量验证。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个 XXX」就行了。

---

## 仓库结构

```
polanyi-skill/
├── README.md
├── LICENSE
├── SKILL.md                              # 可直接安装使用
└── references/
    └── research/                         # 6 个调研文件
        ├── 01-writings.md
        ├── 02-conversations.md
        ├── 03-expression-dna.md
        ├── 04-external-views.md
        ├── 05-decisions.md
        └── 06-timeline.md
```

---

## 更多 .skill

同样由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 蒸馏：

| 人物 | 领域 | 安装 |
|------|------|------|
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/战略 | `npx skills add alchaincyf/steve-jobs-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---

<div align="center">

*We can know more than we can tell.*

<br>

MIT License © [enzyme2013](https://github.com/enzyme2013)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
