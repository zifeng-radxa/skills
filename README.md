# Radxa Skills

这是一个面向 Radxa SBC 用户与 agent 的 skills 仓库。

当前只搭建基础框架，不预置任何具体业务 skill。仓库的基本组织方式只有两类：

- 通用 skill
- 型号专属 skill

## 仓库结构

```text
.
├── AGENTS.md
├── CONTRIBUTING.md
├── catalog/
│   └── skills.yaml
├── templates/
│   └── skill/
│       ├── SKILL.md.example
│       └── agents/
│           └── openai.yaml.example
└── skills/
    ├── common/
    └── models/
```

## 目录约定

- `skills/common/<skill-id>/`
  适合放多款 Radxa SBC 可复用的 skill
- `skills/models/<board>/<skill-id>/`
  适合放某个具体型号专属的 skill

## 当前状态

- 已完成仓库入口文件
- 已完成技能索引框架
- 已完成通用 / 型号专属两类目录
- 已完成 skill 模板
- 未添加任何具体 skill
