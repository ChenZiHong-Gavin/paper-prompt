# Paper Prompt

> 覆盖学术论文全生命周期的 Prompt 集合（25 个 Prompt，6 个阶段）。

---

### 1. 选题与构思

| Prompt | 说明 |
|--------|------|
| [学术idea生成](1-选题与构思/学术idea生成.txt) | 发散思维选论文 idea |

### 2. 文献调研

| Prompt | 说明 |
|--------|------|
| [搜索论文](2-文献调研/搜索论文.txt) | 核心文献推荐、分类文献库、研究空白识别 |
| [论文精读](2-文献调研/论文精读.txt) | 单篇论文结构化深度解读：核心解构、批判性分析、关联启发 |

### 3. 大纲与结构

| Prompt | 说明 |
|--------|------|
| [论文大纲生成](3-大纲与结构/论文大纲生成.txt) | 基于研究信息生成完整英文大纲 |
| [实验设计](3-大纲与结构/实验设计.txt) | Baseline 选取、消融设计、评估指标论证、实验漏洞自查 |
| [标题优化](3-大纲与结构/标题优化.txt) | 多风格论文标题生成 + 五维度评估筛选 |

### 4. 论文写作

| Prompt | 说明 |
|--------|------|
| [Introduction撰写](4-论文写作/Introduction撰写.txt) | 五段式漏斗结构：背景→局限→洞察→贡献→结构 |
| [Method撰写](4-论文写作/Method撰写.txt) | 方法论章节：问题形式化→框架→核心模块→训练目标 |
| [摘要撰写](4-论文写作/摘要撰写.txt) | 四段式 Abstract：问题→思路→方法→结果 |
| [Related Work撰写](4-论文写作/Related%20Work撰写.txt) | 主题/维度/演进三分组策略，文献定位与过渡句式 |
| [Results撰写](4-论文写作/Results撰写.txt) | 实验章节：设置→主结果→消融→深入分析，数据叙事 |
| [段落扩写](4-论文写作/段落扩写.txt) | 将草稿片段扩写为学术规范段落 |
| [图表描述](4-论文写作/图表描述.txt) | Figure/Table Caption 规范 + 正文结果描述 |
| [Discussion撰写](4-论文写作/Discussion撰写.txt) | 解释结果背后的机制、与已有工作对话、意外现象与启示 |
| [Conclusion撰写](4-论文写作/Conclusion撰写.txt) | 回顾→方法→结果→局限→未来方向 |
| [Limitations撰写](4-论文写作/Limitations撰写.txt) | 方法/实验/应用/伦理四维度局限 + Broader Impact 声明 |

### 5. 翻译与润色

| Prompt | 说明 |
|--------|------|
| [中译英](5-翻译与润色/中译英.txt) | 中文学术段落 → 地道学术英文 |
| [英译中](5-翻译与润色/英译中.txt) | 英文论文 → 中文（精读/引用/概览三种模式） |
| [论文修改](5-翻译与润色/论文修改.txt) | 论文深度润色：原文分析→修改建议→差异解释 |
| [降重](5-翻译与润色/降重.txt) | 三力度改写（保守/结构/深度）针对查重优化 |
| [一致性检查](5-翻译与润色/一致性检查.txt) | 术语/符号/图表/引用/逻辑五维度投稿前检查 |

### 6. 审稿与投稿

| Prompt | 说明 |
|--------|------|
| [审稿](6-审稿与投稿/审稿.txt) | 模拟审稿人视角，输出完整 Review + 审查清单 |
| [Rebuttal](6-审稿与投稿/rebuttal.txt) | 逐条回应审稿意见，含常见质疑应对模板 |
| [Cover Letter撰写](6-审稿与投稿/Cover%20Letter撰写.txt) | 投稿信：顶会/期刊/修改重投三模板 + 审稿人推荐 |

---

## 完整写作流建议

```
选题构思 → 文献调研 → 大纲结构 → 论文写作 → 翻译润色 → 审稿投稿
    ↓          ↓          ↓          ↓          ↓          ↓
 idea生成   搜索论文   大纲生成   Introduction  中译英     审稿模拟
            论文精读   实验设计   Method        英译中     Rebuttal
             (精读     标题优化   Abstract      论文修改   Cover Letter
             关键论文)            Related Work  降重
                                 Results       一致性检查
                                 Discussion
                                 图表描述
                                 Conclusion
                                 Limitations
                                 段落扩写
```

---

## Project Structure

```
├── 1-选题与构思/
│   └── 学术idea生成.txt
├── 2-文献调研/
│   ├── 搜索论文.txt
│   └── 论文精读.txt
├── 3-大纲与结构/
│   ├── 论文大纲生成.txt
│   ├── 实验设计.txt
│   └── 标题优化.txt
├── 4-论文写作/
│   ├── Introduction撰写.txt
│   ├── Method撰写.txt
│   ├── 摘要撰写.txt
│   ├── Related Work撰写.txt
│   ├── Results撰写.txt
│   ├── 段落扩写.txt
│   ├── 图表描述.txt
│   ├── Discussion撰写.txt
│   ├── Conclusion撰写.txt
│   └── Limitations撰写.txt
├── 5-翻译与润色/
│   ├── 中译英.txt
│   ├── 英译中.txt
│   ├── 论文修改.txt
│   ├── 降重.txt
│   └── 一致性检查.txt
├── 6-审稿与投稿/
│   ├── 审稿.txt
│   ├── rebuttal.txt
│   └── Cover Letter撰写.txt
└── README.md
```

## Contributing

欢迎通过 Issue 或 PR 贡献新的 Prompt 或改进现有 Prompt。

## License

MIT
