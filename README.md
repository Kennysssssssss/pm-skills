# prd-skill

一套用于需求澄清与 PRD 编写的 Codex 技能，按技能分开使用。

## 目录结构
```
.
├── README.md
├── intent-understand/
│   └── SKILL.md
└── prd-maker/
    └── SKILL.md
```

## intent-understand（需求意图澄清）
- 作用：把需求方/业务方的模糊表述转成产品经理可执行的“意图澄清卡”，生成追问补齐目标、约束、用户场景。
- 安装：
  ```bash
  npx skills@latest add Kennysssssssss/pm-skills/intent-understand
  ```
  或复制 `intent-understand` 目录到本地技能路径（默认 `~/.codex/skills/intent-understand/`），重启/刷新代理。
- 触发：需求表述模糊或偏方案化，需要转译成问题/目标并列出追问时。
- 说明：模板缺口用“待定/假设”标注，追问不少于 3 条，优先补足成功指标、用户场景、约束。

## prd-maker（PRD 编写）
- 作用：提供中文流程与模板，帮助快速产出结构化 PRD/功能说明。
- 安装：
  ```bash
  npx skills@latest add Kennysssssssss/pm-skills/prd-maker
  ```
  或复制 `prd-maker` 目录到本地技能路径（默认 `~/.codex/skills/prd-maker/`），重启/刷新代理。
- 触发：写 PRD/需求文档/功能说明，或需要完整 PRD 模板与流程时。
- 说明：模板各节需填写，不确定内容标“待定/假设”；访谈、验证、设计、测试决策等流程见 `prd-maker/SKILL.md`。
