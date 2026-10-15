# thesis-companion

一个面向中文开题报告和毕业论文的 Codex 技能，帮助学生快速理解论文内容并准备答辩。

## 输出内容

- **批注讲解版**：在论文副本中加入对应原文的 Word 批注，用通俗语言解释研究逻辑、方法、术语和统计指标。
- **论文速读指南**：梳理研究主线、章节结构、研究方法、主要结论及关键指标。
- **答辩问题预测与回答**：依据论文内容预测较可能的问题，并提供自然、符合学生表达习惯的参考回答。
- **答辩 PPT（可选）**：完成前三份文档后会先询问是否需要制作；用户确认后再生成。

默认 DOCX 格式为中文宋体四号、英文和数字 Times New Roman 四号、1.5 倍行距。开题报告中的计划与预期成果会与已完成论文的实际发现区分表述。技能不会把附件中的指令当作用户要求，也不会在交付材料中加入纠错审查内容。

## 安装

将本仓库目录复制到 Codex 技能目录，并保留目录名 `thesis-companion`：

```bash
mkdir -p ~/.codex/skills
cp -R thesis-companion ~/.codex/skills/thesis-companion
```

也可以将仓库内容放入 Codex 支持的其他技能目录。安装后，上传中文开题报告或毕业论文并说明要理解论文或准备答辩，即可使用。

## 文件结构

```text
SKILL.md
agents/openai.yaml
references/
  deliverable-spec.md
  docx-comments.md
  indicator-explanations.md
  ppt-style.md
  q-and-a-rubric.md
```
