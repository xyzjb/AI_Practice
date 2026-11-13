# AI_Practice

在 WorkBuddy 上做的 AI 实践归档仓库。**每个实践一个独立编号目录**，方便持续追加、互不干扰。

## 实践目录

| 目录 | 内容 | 日期 |
|---|---|---|
| [01_视频生成](01_视频生成/) | 每日 AI 科技热点自动化短视频：全网搜热点 → 5 选题打分 → 60–90s 口播稿 → edge-tts 配音 → AI 生图 → VibeKnow + Remotion 竖版成片 | 2026-11-13 |

后续实践按 `02_xxx`、`03_xxx` 依次新增目录，并在上表补一行索引。

## 目录约定

- 每个实践目录**自包含**：`README.md`（含该实践使用的提示词原文）、`docs/`（流程与工作记录）、以及成果文件
- 中间产物由仓库根 `.gitignore` 统一排除：`_bin/` 第三方运行时、`_img/` 重复原图、`*.bg.png`、`*.mp3`、`*.part.mp4`；`.workbuddy/` 本地助手数据同样不入库
- 忽略规则用 `**/` 通配，对任意编号的实践目录都生效；某个实践确需上传音频等例外时，再单独调整规则
- 单个文件不超过 GitHub 100 MB 硬限制；超大素材改用 Release 附件或 Git LFS

## 仓库信息

- 公开仓库，默认分支 `main`
- SSH 地址：`git@github.com:xyzjb/AI_Practice.git`
- 新增实践：`git add 02_xxx/ && git commit -m "feat: 归档 02_xxx 实践" && git push`
