# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

## [v0.0.2] - 2025-07-14

### 变更

- 核心模型 User 重命名为 Learner（学习者），预留 `user_id` 关联 auth 领域
- Completion 记录外键 `user_id` 同步更名为 `learner_id`

## [v0.0.1] - 2025-07-14

### 新增

- 初始化学习管理领域仓库
- 注册子模块：`apps/qtcloud-learn`、`packages/quanttide-learn-toolkit`、`examples/default`
- 注册子模块：`data/context`、`data/journal`、`data/intention`
- 注册子模块：`data/profile`、`data/roadmap`、`data/insight`、`data/brochure`、`docs/bylaw`（档案/路线图/洞察/宣传册/章程）
- 注册子模块：`docs/handbook`、`docs/specification`、`docs/tutorial`、`docs/essay`、`docs/gallery`（手册/规范/教程/随笔/案例集）
