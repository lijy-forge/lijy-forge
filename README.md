### Hi, I'm Jiayao 👋

AI Agent 工程方向。关注怎么让 LLM Agent 在真实业务里**可靠**地跑起来：确定性护栏、可恢复的工作流、证据可追溯，以及失败时说清楚为什么失败。

**常用技术**

- **AI / 后端**：Python · LangGraph · FastAPI · Go · Redis · MySQL · Neo4j · Qdrant · Docker
- **前端**：React · TypeScript

---

### 代表项目

| 项目 | 简介 | 技术要点 |
|---|---|---|
| [**SupplyGuard AI**](https://github.com/lijy-forge/SupplyGuard-Ai) | 面向制造质量与供应链运营的证据驱动智能体平台 | LangGraph + Redis 检查点可恢复工作流；Neo4j 产业链图谱 + Qdrant 规范检索；正式写入前强制人工审批 |
| [**PaperGuide AI**](https://github.com/lijy-forge/PaperGuide-Agent) | 证据驱动的自主论文研究 Agent | 基于 GPT Researcher 二次开发；论文检索、PDF 结构化阅读、证据核验与报告生成的可审计流水线 |
| [**Yield-Stress AutoML Agent**](https://github.com/lijy-forge/Automl-Agent-Yield) | 浆料屈服应力预测的多 Agent AutoML 系统 | 基于 AutoML-Agent（ICML 2025）重构编排层；有界修订回路 + 确定性护栏；完整的基线、消融实验 |
| [**tollgate**](https://github.com/lijy-forge/tollgate) | 多租户 LLM API 网关 | Go；Redis Lua 原子预扣与结算、Redis Stream 账本与对账；按 key 的 RPM/TPM 分布式限流 |
| [**restore-ai-tabs**](https://github.com/lijy-forge/restore-ai-tabs) | 死机后一键把 Claude Code / Codex 会话恢复成终端 tab | 跨平台（iTerm2 / Windows Terminal）；零依赖单文件；三平台 CI |

> 二次开发的项目都在各自 README 中标明了上游来源和代码归属。
