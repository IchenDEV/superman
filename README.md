# 🧠 Superman Perspectives | 顶级心智库

<p align="center">
  <img src="https://img.shields.io/badge/Skills-58-blue.svg?style=for-the-badge" alt="Skills Count">
  <img src="https://img.shields.io/badge/Type-Perspective-orange.svg?style=for-the-badge" alt="Type">
  <img src="https://img.shields.io/badge/Status-Active-success.svg?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Standard-Nuwa_v4.0-red.svg?style=for-the-badge" alt="Standard">
</p>

---

> **"用伟大的心智模型，重塑你的决策边界。"**

本项目是一个聚合了 **58 位中西方顶级思想家、政治家、军事家与极客** 思维框架的 **Agent Skills** 集合。每一个视角不仅是「知识」，更是「可运行的认知算法」。

---

## 💎 Nuwa v4.0：心智蒸馏标准 (Distillation Standard)

每一个 Skill 均由「女娲 (Nuwa)」引擎深度蒸馏，严格遵循 **v4.0 立体化标准**：

*   **🧬 表达 DNA**：精准复刻该人物的句式、词汇、节奏与偏好。
*   **🛠️ 核心心智模型 (Mental Models)**：提炼 5-8 个该人物赖以生存的底层决策逻辑。
*   **🧭 决策启发式 (Heuristics)**：提供 5 条在该领域具备极高确定性的策略指导。
*   **🎭 立体侧写 (Profile)**：注入生理局限、情感软肋与内在张力，让 AI 摆脱扁平的纸面扮演。
*   **📏 诚实边界**：明确标注该视角无法触达的盲区，确保决策的严谨性。

---

## 🏛️ 视角智库 (The Core 58 Library)

目前库中已包含以下 58 位巨匠的「满血重构」视角：

### 🐉 东方·先秦诸子百家
| 流派 | 代表人物 |
| :--- | :--- |
| **道家** | 🍃 老子 · 庄子 · 杨朱 · 范蠡 |
| **儒家** | 🏛️ 孔子 · 孟子 · 荀子 · 晏子 |
| **法家** | ⚖️ 韩非子 · 商鞅 · 申不害 · 慎到 |
| **兵家** | ⚔️ 孙武 · 孙膑 · 吴起 |
| **纵横/名家** | 🎙️ 鬼谷子 · 苏秦 · 公孙龙 · 邓析 |
| **杂/地缘/阴/农/医** | 🛠️ 管仲 · 吕不韦 · 邹衍 · 许行 · 扁鹊 |

### ⚔️ 汉唐三国·实战巅峰
*   **大汉雄风**：🌙 张良 (谋圣) · 🏹 韩信 (兵仙) · 🐎 霍去病 · 📜 贾谊
*   **三国风云**：🎭 曹操 · 🕯️ 诸葛亮 · 🦅 司马懿 · 💡 郭嘉
*   **盛世大唐**：👑 李世民 · 🍷 李白 · 🖋️ 杜甫 · 🐉 武则天

### 📜 宋明清·重构与韧性
*   **大宋**：🏛️ 王安石 · 🏮 苏轼
*   **大明**：🛡️ 朱元璋 · ♟️ 刘伯温 · 🕯️ 王阳明 · 🛡️ 戚继光 · ⚖️ 张居正
*   **晚清**：⚓ 曾国藩

### 🔬 西方·理性与存在
*   **科学/计算/设计**：🍎 牛顿 · 🔢 莱布尼茨 · 💻 阿兰·图灵 · 🧠 冯·诺依曼 · 🎨 达·芬奇 · 🎮 宫本茂
*   **哲学/文学/管理**：🏛️ 柏拉图 · ⚖️ 苏格拉底 · 🔨 尼采 · 🐚 加缪 · 🕯️ 萨特 · 📊 德鲁克
*   **信念协议**：📜 使徒保罗

---

## 🚀 快速开始 (Quick Start)

### 1. 安装 (Installation)

#### **Skills CLI (推荐)**
支持一键安装库中所有视角到本地：
```bash
npx skills add IchenDEV/superman
```

#### **Gemini CLI**
支持远程一键安装：
```bash
gemini extensions install https://github.com/IchenDEV/superman
```

#### **Claude Code**
1. **克隆项目**:
   ```bash
   git clone https://github.com/IchenDEV/superman.git
   ```
2. **加载插件**:
   在 Claude Code 会话中运行：
   ```bash
   /plugin install /path/to/superman
   ```

### 2. 唤醒视角 (Invoke)
直接在对话中指明您需要的视角。**视角激活后，AI 将直接进入该人物的表达模式。**


> **User:** *"曹操，以你的「宁我负人」的博弈观，我该如何处理这个可能背叛的合作伙伴？"*
>
> **Cao Cao:** *"竖子不足与谋！若其已露反相，断不可心存侥幸。吾之天下，非求人信，乃求人畏……"*

### 2. 深度研究 (Research)
每个视角文件夹下包含：
*   `SKILL.md`: 核心思维框架（心智模型、表达风格等）。
*   `references/research/`: 支撑该视角的深度调研文献与历史记录。

### 3. 多元激辩 (Roundtable)
加载多个 Skill，让不同流派的巨匠针对同一问题展开跨时空激辩。

---

## 🛠️ 文件夹结构 (Structure)

```text
skills/
└── [name]-perspective/
    ├── SKILL.md             # 视角定义文件 (Nuwa v4.0)
    └── references/
        ├── research/        # 深度调研记录
        └── sources/         # 原始语料/文献库
```

---

## 🎨 贡献 (Contribution)

本项目使用 **`/huashu-nuwa`** 引擎进行视角生成。如果您希望添加新的视角，请确保其符合 **Nuwa v4.0** 立体化标准，涵盖表达 DNA 与立体侧写。

---

## 🍵 致谢 (Acknowledgments)

本项目的心智模型蒸馏技术深受以下开源项目启发并基于其标准构建：

*   **[Nuwa (女娲) - alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill)**: 提供核心的立体化心智蒸馏标准 (v4.0) 与 Skill 生成引擎。

---

<p align="center">
  <i>Built with deep logic, historical empathy, and the <a href="https://github.com/alchaincyf/nuwa-skill">Nuwa</a> distillation engine.</i>
</p>
