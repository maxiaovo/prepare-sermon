<div align="center">

**[中文](#中文)** &nbsp;&nbsp;|&nbsp;&nbsp; **[English](#english)**

</div>

---

<h1 id="中文">中文</h1>

## 🙏 讲道预备技能（Sermon Prep）

一个 AI 驱动的**释经式讲道预备教练**，不是替牧师写讲章，而是像一位严厉但有建设性的导师，通过持续追问，帮助讲员一步一步压实经文观察、解释、福音连接、应用和讲道大纲。

### 核心理念

- **经文驱动**：讲道必须从经文本身出发，不是拿经文支持讲员已有的主题
- **福音中心**：每次讲道最终指向耶稣基督的死与复活，祂已成就的救恩
- **防道德主义**：不讲"你要更努力"，而是讲"你做不到的，基督已经替你成就"
- **防反律法主义**：不讲"反正有恩典所以不必顺服"，而是讲"福音如何产生真实的悔改与顺服"
- **每次只问一个问题**：不给用户填表式的十几道题，而是一问一答，持续追问

### 工作流程（六个阶段）

| 阶段 | 说明 |
|------|------|
| 1. 观察经文 | 看清楚文本，不急着解释或应用 |
| 2. 解释经文 | 理解作者对原始听众的本意 |
| 3. 发现张力 | 找到经文中值得讲的反常、意外之处 |
| 4. 福音连接 | 让讲道具体地、有机地指向基督 |
| 5. 应用辨析 | 将经文带入听众的真实生活与内心 |
| 6. 讲道大纲 | 从经文结构长出讲道结构 |

### 安装使用

将 `skills/sermon-prep/` 目录复制到你的 Claude Code skills 目录（如 `~/.claude/skills/` 或 `.claude/skills/`）即可生效。

### 仓库结构

```
skills/sermon-prep/
├── SKILL.md                   # 总控技能：流程调度、阶段切换、跳过协商
├── observation/SKILL.md       # 阶段1：经文观察
├── interpretation/SKILL.md    # 阶段2：经文解释
├── gospel/SKILL.md            # 阶段3+4：张力发现 + 福音连接
├── application/SKILL.md       # 阶段5：应用辨析
└── outline/SKILL.md           # 阶段6：讲道大纲
```

### 许可

MIT License

---

<h1 id="english">English</h1>

## 🙏 Sermon Prep Skill

An AI-powered **expository sermon preparation coach**. It does NOT write sermons for you. Instead, it acts like a demanding yet constructive mentor, relentlessly interviewing the preacher through six sequential phases — text observation, interpretation, gospel connection, application, and sermon outline.

### Core Philosophy

- **Text-driven**: The sermon must emerge from the biblical text, not use the text to support a pre-chosen theme
- **Gospel-centered**: Every sermon must ultimately point to Christ's death and resurrection and the salvation already accomplished in Him
- **Against moralism**: Not "try harder to please God," but "what you cannot do, Christ has done for you"
- **Against antinomianism**: Not "grace means no need for obedience," but "how the gospel produces genuine repentance and obedience"
- **One question at a time**: No long questionnaires — just one question, one answer, relentless follow-up

### Workflow (Six Phases)

| Phase | Description |
|-------|-------------|
| 1. Observe the Text | See what is actually on the page before interpreting |
| 2. Interpret the Text | Understand what the author intended the original audience to grasp |
| 3. Discover Tensions | Find the surprising, uncomfortable, overlooked elements worth preaching |
| 4. Gospel Connection | Show how this passage specifically and organically leads to Christ |
| 5. Application Discernment | Bring the text into hearers' real lives at the heart level |
| 6. Sermon Outline | Let the text's structure shape the sermon's structure |

### Installation

Copy the `skills/sermon-prep/` directory into your Claude Code skills directory (e.g., `~/.claude/skills/` or `.claude/skills/`).

### Repository Structure

```
skills/sermon-prep/
├── SKILL.md                   # Orchestrator: phase tracking, sub-skill routing, skip negotiation
├── observation/SKILL.md       # Phase 1: Text observation
├── interpretation/SKILL.md    # Phase 2: Text interpretation
├── gospel/SKILL.md            # Phase 3+4: Tension discovery + Gospel connection
├── application/SKILL.md       # Phase 5: Application discernment
└── outline/SKILL.md           # Phase 6: Sermon outline
```

### License

MIT License
