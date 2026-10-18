# trend-workflow · GitHub 趋势工作流 Skill

> 把 GitHub 趋势变成自己仓库的改进。每天出趋势日报、对照你的仓库提建议，采纳后自动写 PRD、拆任务、开 PR（只开不合并）。

[![skills.sh](https://img.shields.io/badge/skills.sh-trend--workflow-blue)](https://skills.sh)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

- **官方网站 / 趋势雷达**：[https://trend.zhanglu.net](https://trend.zhanglu.net)
- **方法论文章**：[https://trend.zhanglu.net/workflow](https://trend.zhanglu.net/workflow)
- **Skills 详情页**：[https://trend.zhanglu.net/skills](https://trend.zhanglu.net/skills)

---

## ⚡ 1 秒安装（skills.sh / Agent Skills 标准）

适用于 Cursor、Windsurf、Claude Code、Codex、Gemini CLI 等任何支持 Agent Skills 标准的客户端：

```bash
npx skills add zhanglunet/trend-workflow
```

或者作为 Claude Code 官方插件加载：

```bash
claude plugin add zhanglunet/trend-workflow
```

---

## 🛡️ 核心铁律

1. **只开 PR，绝不擅自合并**：自动化工作流只做到在目标仓库开出 Pull Request 为止，合并权永远在人手里。
2. **T1 永远先写设计草稿**：纯加法文档，评审通过后才动实现代码。
3. **许可证严格红线**：严防 AGPL 等强传染协议，借架构思路，零复制代码。

---

## 📖 触发词与使用

对你的 AI Agent（如 Muse、Grok bot、Claude 等）说：

```text
"跑今天的日报"
"看趋势"
"把今天 GitHub 趋势里适合我项目的思路提成 PRD"
```

完整端到端架构与案例，见 [https://trend.zhanglu.net/workflow](https://trend.zhanglu.net/workflow)。
