# 变更记录

遵循语义化版本：修 bug → patch，新增能力 → minor，改变契约 → major。

## v1.0.7 — 2026-10-30

影响面：memo-qahelper(README.md)

### 变更

- README 顶部增加「墨卡大师 · 专业制卡工作流」在线介绍页链接。

## v1.0.6 — 2026-10-26

影响面：memo-qahelper(SKILL.md, scripts/import_guide.py)

### 修复

- TXT 导入教程改为脚本把 GIF 复制到当前工作区并输出相对路径，修复 DSH / WorkBuddy 无法预览技能目录绝对路径的问题。

## v1.0.5 — 2026-10-26

影响面：memo-qahelper(README.md) / skill-publisher(scripts/memo_publish.py, scripts/test_memo_release.py)

### 修复

- README 标题版本改为随 release 自动更新，修复 GitHub 页面标题停留在 v1.0.0 的问题。

## v1.0.4 — 2026-10-26

影响面：memo-qahelper(SKILL.md, references/sources.md)

### 变更

- 允许来源增加本机同级的 Memo 系列技能说明，与论坛同级（非官方）；只读文件，不调用技能、不触发 S0/写入/API。

## v1.0.3 — 2026-10-26

影响面：memo-qahelper(SKILL.md, references/assets/import-flow-36b59d.gif)

### 变更

- 新增「TXT 导入」固定答案：用户问 TXT 导入步骤时直接发内置教程（四步 + GIF），不检索；白名单规则不适用于该固定答案。

## v1.0.2 — 2026-10-24

### 变更

- 新增 MIT `LICENSE`，README 补 License 说明。

## v1.0.1 — 2026-10-23

- README 的「Memo 系列」表与 `references/satellites.md` 改由 `memo-series.json` 生成（`sync-series`）。

## v1.0.0 — 2026-10-22

- 首个版本：墨墨记忆卡使用答疑，三档检索（墨墨百科官方 → 墨记论坛用户反馈 → 邮件兜底），白名单硬红线，不凭记忆作答。
