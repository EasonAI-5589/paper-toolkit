# 漫画风 LLM 框架图专题

> 适用于：ACL, NeurIPS, ICML, ICLR 等顶会论文
> 风格：极简线框、漫画风格、icon 丰富

## 风格特点

- **漫画风格** - 卡通化的元素和人物
- **极简线框** - 简洁的边框和连接线
- **布局留白** - 不要堆砌，保持呼吸感
- **配色简单** - 统一色系，2-4 种主色
- **icon 丰富** - 用图标代替文字，增加趣味性

---

## 代表性论文

### 1. MemGen: Weaving Generative Latent Memory for Self-Evolving Agents

> **arXiv**: 2509.24704
> **GitHub**: https://github.com/KANABOON1/MemGen
> **作者**: Zhang, Guibin and Fu, Muxin and Yan, Shuicheng

**框架图特点**：
- 漫画风格的 Agent 形象
- Memory Trigger 和 Memory Weaver 用卡通元素表示
- 流程用简洁箭头连接
- 整体配色统一

**框架图预览**：
![MemGen Framework](https://raw.githubusercontent.com/KANABOON1/MemGen/master/assets/memgen.png)

**核心概念**：
- **Memory Trigger**: 决定何时回忆记忆
- **Memory Weaver**: 将过去经验合成为紧凑的潜在序列

**BibTeX**:
```bibtex
@article{zhang2025memgen,
  title={MemGen: Weaving Generative Latent Memory for Self-Evolving Agents},
  author={Zhang, Guibin and Fu, Muxin and Yan, Shuicheng},
  journal={arXiv preprint arXiv:2509.24704},
  year={2025}
}
```

---

### 2. Towards Explainable Temporal Reasoning in LLMs

> **arXiv**: 2505.15245
> **来源**: 小红书 @每日学习科研绘图

**框架图特点**：
- 漫画风格，极简线框
- 布局留白，整体舒适
- 配色简单，统一色系
- icon 丰富，整体富有质感

---

## 漫画风绘图工具

### AI 工具推荐

| 工具 | 适用场景 | 特点 |
|------|----------|------|
| **Nano Banana Pro** | 科研框架图 | 支持漫画风格，可迭代修改 |
| **Gemini 3 Pro** | 快速草图 | 原生图像生成，理解论文内容 |
| **GPT-4o** | 复杂场景 | 多轮对话优化 |
| **ai-comic-factory** | 漫画面板 | 开源，LLM + SDXL |

### 开源项目

- **ai-comic-factory**: https://github.com/jbilcke-hf/ai-comic-factory
  - 使用 LLM + SDXL 生成漫画面板
  - Hugging Face 托管

### 学术参考

- **Ten simple rules for drawing scientific comics** (PLOS Computational Biology)
  - DOI: 10.1371/journal.pcbi.1005845
  - 科学漫画绘制的 10 条规则

---

## 漫画风绘图 Prompt 模板

### 基础模板

```
Create a comic-style scientific illustration for [YOUR TOPIC].

Style requirements:
- Cartoon/comic aesthetic with clean line art
- Minimalist design with generous whitespace
- Unified color palette (2-4 main colors)
- Rich icons and visual metaphors
- Clear flow arrows connecting components

Components to include:
- [Component 1]: represented as [visual metaphor]
- [Component 2]: represented as [visual metaphor]
- [Component 3]: represented as [visual metaphor]

Layout: [horizontal/vertical] flow, [left-to-right/top-to-bottom]
```

### LLM/Agent 框架图模板

```
Create a comic-style framework diagram for an LLM-based agent system.

Style:
- Cute cartoon robot/character as the agent
- Speech bubbles for inputs/outputs
- Gear icons for processing modules
- Brain icon for memory/reasoning
- Clean arrows showing data flow

Color scheme:
- Primary: soft blue (#4A90D9)
- Secondary: warm orange (#F5A623)
- Accent: light green (#7ED321)
- Background: white with subtle grid

Include labels in English, professional but friendly tone.
```

### 记忆系统模板（参考 MemGen）

```
Create a comic-style illustration of an AI memory system.

Visual elements:
- A cute robot character as the "Agent"
- A filing cabinet or brain as "Memory Storage"
- Light bulbs for "Memory Trigger" moments
- Weaving/knitting metaphor for "Memory Integration"
- Flowing ribbons connecting past experiences to current reasoning

Style: minimalist comic, soft colors, clean lines
```

---

## 配色方案推荐

### 温暖系（适合 Agent/交互类）

```
Primary:   #F5A623 (Orange)
Secondary: #4A90D9 (Blue)
Accent:    #7ED321 (Green)
Text:      #4A4A4A (Dark Gray)
Background:#FFFFFF (White)
```

### 科技系（适合模型架构）

```
Primary:   #6C5CE7 (Purple)
Secondary: #00CEC9 (Cyan)
Accent:    #FD79A8 (Pink)
Text:      #2D3436 (Dark)
Background:#F8F9FA (Light Gray)
```

### 自然系（适合流程/pipeline）

```
Primary:   #00B894 (Green)
Secondary: #0984E3 (Blue)
Accent:    #FDCB6E (Yellow)
Text:      #2D3436 (Dark)
Background:#FFFFFF (White)
```

---

## 绘制流程

### Step 1: 确定内容结构
- 列出所有需要展示的组件
- 确定组件之间的关系（流程/层级/并列）
- 选择合适的视觉隐喻

### Step 2: 生成草图
```
用 Gemini/GPT-4o 生成文字描述：
"请将以下论文方法描述转化为漫画风格框架图的文字草图：
- 列出所有视觉元素
- 描述元素位置和连接关系
- 建议配色方案"
```

### Step 3: AI 生成图像
```
将草图描述喂给 Nano Banana Pro：
"请根据以下描述生成漫画风格的科研框架图：
[草图描述]
要求：极简线框，统一配色，icon 丰富"
```

### Step 4: 迭代优化
- 调整配色/字体
- 检查箭头方向和标注
- 确保整体风格一致

---

## 更多资源

### 小红书教程
- [如何绘制LLM漫画风框架图](http://xhslink.com/o/9DUz0h5UNXP) - @每日学习科研绘图

### 论文参考
- MemGen (arXiv:2509.24704) - Agent Memory 漫画风框架图
- Temporal Reasoning (arXiv:2505.15245) - LLM 漫画风框架图

---

**Tags**: #漫画风 #科研绘图 #LLM #Agent #框架图 #ACL #NeurIPS
