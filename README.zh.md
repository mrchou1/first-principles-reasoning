# 第一性原理推理技能

为 [Claude Code](https://claude.ai/code) 设计的一个结构化推理技能，可引导模型执行严格的 5 阶段协议：挑战假设、将问题分解为不可再分的要素，并从基本真理出发重构创新解决方案。

---

## 安装

1. 将整个 `first-principles-reasoning/` 文件夹复制到 Claude Code 的技能目录：
   - **个人级**：`~/.claude/skills/first-principles-reasoning/`
   - **项目级**：`your-project/.claude/skills/first-principles-reasoning/`
2. 重启 Claude Code（或新建一个会话），技能会被自动识别。

---

## 快速开始

安装后，你可以用类似下面的说法来激活该技能：

- *“从第一性原理分析这个问题”*
- *“把 X 的成本拆解到最基础的材料”*
- *“为什么这样做？从头重新思考一下。”*
- *“用第一性原理对我们的用户引导流程做一次彻底的重设计。”*

也可以显式调用：*“使用第一性原理推理技能。”*

---

## 技能组成

该技能包含一个完整推理协议的 `SKILL.md`，以及一套丰富的配套资源：
first-principles-reasoning/
├── SKILL.md # 主技能定义与协议
└── resources/
├── templates/
│ ├── assumptions_inventory.md # 假设清单模板（表格）
│ ├── mece_decomposition.md # MECE 问题分解树模板
│ ├── concept_morphological_matrix.md # 形态学矩阵模板（用于创意生成）
│ └── experiment_canvas.md # 精益实验画布模板
├── references/
│ ├── cognitive_biases_cheatsheet.md # 最易影响推理的 20 个认知偏误速查表
│ ├── first_principles_case_studies.md # 经典案例集（SpaceX、iPhone、Amazon Prime 等）
│ ├── metaprinciples.md # 跨领域的通用原则（物理、经济、逻辑等）
│ └── logical_fallacies_guide.md # 常见逻辑谬误及规避方法
└── tools/
└── assumption_stress_test_prompt.md # 对假设进行深度拷问的子提示


---

## 五步推理循环

技能被调用时，会遵循以下步骤：

1. **明确元目标** – 剥离所有现有方案，清晰表述最纯粹的功能性目标。
2. **挖掘并摧毁假设** – 列出至少 10 个假设，区分哪些是真正的约束（物理定律），哪些只是惯例，然后摧毁后者。
3. **分解至基础元素** – 用 MECE 分解法找到不可再分的要素（材料、能量、恒定需求等）。
4. **从基本真理重构** – 借助形态学矩阵，生成至少 3 个根本不同的方案概念。
5. **证伪与迭代** – 针对最脆弱的假设设计最简可行实验，如发现矛盾则回到第一阶段。

每个阶段都可以按需加载对应的模板和参考资料，在保持上下文精简的同时，提供深度的思维支撑。

---

## 使用建议

- **适于重大、成本高昂的问题**，不宜用于琐碎决策。
- **信任流程**。协议开始时可能显得繁琐，但正是为了打破思维捷径。
- **与领域知识结合**。技能提供“如何思考”的框架，你（或其他技能）提供“思考什么”的内容。
- **反复迭代**。鼓励在获得新信息后多次循环，逐步逼近真相。

---

## 贡献

本技能可以进行持续改进。如果你发现了更好的模板、更相关的元原理、或者更精准的偏误描述，可以直接编辑资源文件。请保持目录结构不变，以便主 `SKILL.md` 能继续正确引用。

---

## 许可证

本项目基于 MIT 许可证开放。可自由使用、修改和分发。

---

## 作者

- **名称：** Mr.Chou
- **邮箱：** 3965537@qq.com
- **GitHub：** [mrchou1/first-principles-reasoning](https://github.com/mrchou1/first-principles-reasoning)

---
