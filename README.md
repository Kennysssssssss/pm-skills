# prd-skill

一套用于写 PRD/功能说明的 Codex 技能，核心文件在 `prd-maker/SKILL.md`，提供中文流程与模板，方便在对话中快速产出结构化 PRD。

## 目录结构
```
.
├── README.md          # 本说明
└── prd-maker/
    └── SKILL.md       # 技能定义与模板
```

## 安装/使用
- **方式一：skills CLI（推荐）**：已发布在 GitHub，直接安装
  ```bash
  npx skills@latest add Kennysssssssss/pm-skills/prd-maker
  ```
  安装后重启/刷新代理即可用技能名 `prd-maker`。
- **方式二：本地/手动**：复制 `prd-maker` 目录到本地技能路径（默认 `~/.codex/skills/prd-maker/`），重启/刷新代理后即可使用技能名 `prd-maker`。
- 触发时机：当用户提到“写 PRD/需求文档/功能说明”或需要梳理需求、输出 PRD 模板时。

## 说明
- 模板每个部分都要填写，不确定的内容标注“待定/假设”。
- 访谈、验证、设计、测试决策等流程见 `prd-maker/SKILL.md`。
