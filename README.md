# FBS-BookWriter · OpenClaw 技能包 v2.1.2

本仓库发布 **FBS-BookWriter** 的 [OpenClaw](https://docs.openclaw.ai/tools/creating-skills) 通道技能包：与主仓同源 **v2.1.2**，入口为 OpenClaw 专用 `SKILL.md`（`name: fbs_bookwriter`），不含 WorkBuddy / CodeBuddy 市场清单。

## 下载

| 文件 | 说明 |
|------|------|
| `fbs-bookwriter-v212-openclaw.zip` | 解压后根目录名为 `fbs_bookwriter`，放入 OpenClaw 技能扫描路径 |

## 安装摘要

1. 解压到 `fbs_bookwriter/`（文件夹名与 `SKILL.md` 中 `name` 一致）。
2. 在技能根目录执行：`npm install`（Node ≥ 18；可选依赖见 `package.json`）。
3. 重启 Gateway 或会话，用 `openclaw skills list` 确认加载。详细步骤见包内 `SKILL.md`「安装（OpenClaw）」。

## 构建

由主项目执行 `npm run pack:openclaw` 生成；若需自证完整性，可对照主仓 `dist/` 下打包校验报告。
