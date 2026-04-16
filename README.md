# FBS-BookWriter · OpenClaw（v2.1.2）

本仓库即 **OpenClaw** 通道技能**源码树**（与主项目 `npm run pack:openclaw` 产出一致），仓库根目录即为技能根：`SKILL.md`、`package.json`、`references/`、`scripts/` 等。不含 WorkBuddy / CodeBuddy 市场清单。

## 使用方式（推荐）

将仓库克隆为技能目录名 **`fbs_bookwriter`**（与 `SKILL.md` 中 `name` 一致），再安装依赖：

```bash
git clone https://github.com/duhongchao-Fbsir/fbs-bookwriter-openclaw.git fbs_bookwriter
cd fbs_bookwriter
npm install
```

然后按包内 [`SKILL.md`](./SKILL.md)「安装（OpenClaw）」配置 OpenClaw 技能扫描路径，并用 `openclaw skills list` 确认加载。

## 版本

当前：**2.1.2**。上游主页：<https://fbs-bookwriter.u3w.com/>
