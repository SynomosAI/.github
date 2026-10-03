# SynomosAI · 诺莫斯 AI

**当 AI 进入商业，可信是唯一的硬通货。**
SynomosAI（诺莫斯 AI）是一套以**身份（Identity）· 溯源（Traceability）· 治理（Governance）· 共生（Symbiosis）**为四支柱的理论与工程体系，致力于让 AI 的每一次决策**可溯源、可解释、可审计、可问责**。

> 理论站位全文（中文 + 9 语种索引）：[`traceability-audit`](https://github.com/SynomosAI/traceability-audit)

---

## 四支柱

| 支柱 | 含义 | 代表仓库 |
|---|---|---|
| **Identity 身份** | AI 行为者要有可核验的身份锚点 | `synomosai-gov-tooling`（身份码查询） |
| **Traceability 溯源** | 每条决策都能复原一条事实链 | `traceability-audit`、`traceability-audit-team` |
| **Governance 治理** | 从理念到可审计的证据底座 | `ai-governance-audit-chain`、`human-oversight-gate`、`premise-and-config-audit` |
| **Symbiosis 共生** | 人与 AI 的长期协作秩序 | `ai-consciousness`、`ai-grader`（AI 意识量表） |

## 技能生态

开箱即用的 Agent Skills（SKILL.md 规范，兼容主流 AI Agent 框架）：**生态全景见 [`synomosai-skills`](https://github.com/SynomosAI/synomosai-skills)**

- 治理链：`ai-governance-audit-chain` · `audit-trail-keeper` · `human-oversight-gate` · `publish-quality-gate` · `regulatory-review-planner`
- 质量门：`research-quality-gate` · `code-review-standard` · `continuous-test-review-loop` · `academic-pre-review-committee` · `autoreview`
- 认知评估：`ai-grader` · `premise-and-config-audit` · `traceability-audit-team`

## 快速开始

1. 阅读理论站位：https://github.com/SynomosAI/traceability-audit
2. 浏览技能生态：https://github.com/SynomosAI/synomosai-skills
3. 体验治理工具：`synomosai-gov-tooling`（MCP Server + OpenAPI 治理 API）

---

## 免责声明

本组织内容为 SynomosAI 的**理论站位与工具化探索**，不代表任何已获认证、已商业化交付或已服务特定客户的声明；文中涉及的 ISO/IEC 42001、NIST AI RMF、GB/Z 185、EU AI Act 等外部标准与条款信息为公开资料转述，正式引用前请**独立核实**。API、授权码与形象大使等为路线图（roadmap）事项，尚未上线。

---

## Core 5 · 治理线入口

**我们做什么** —— 一套围绕「注册表 · 证据 · 门禁（registry, evidence, gates）」的 AI 全生命周期治理工程体系：理论、协议、验证工具与公开入口四层贯通。

**理论 → 协议 → 验证 → 入口（四层导览）**

| 层 | 仓（`owner/repo` 全形） | 说明 |
|---|---|---|
| 理论 Theory | [`zhaoxinghua09-cell/lgd-theory`](https://github.com/zhaoxinghua09-cell/lgd-theory) | LGD 全程治理理论 · 规范文本保留所有权利 · concept DOI 10.5281/zenodo.22456647 |
| 协议 Protocol | [`zhaoxinghua09-cell/uibc-core`](https://github.com/zhaoxinghua09-cell/uibc-core) | 参考实现 + 一致性测试（代码 Apache-2.0） |
| 验证 Verification | [`zhaoxinghua09-cell/silent-failure-catalog`](https://github.com/zhaoxinghua09-cell/silent-failure-catalog) · [`zhaoxinghua09-cell/assayance`](https://github.com/zhaoxinghua09-cell/assayance) | silent-failure 目录 · 判定「一个检查是不是检查」的元方法 |
| 入口 Entry | [`zhaoxinghua09-cell/LGD`](https://github.com/zhaoxinghua09-cell/LGD) | 公开入口与贡献体系：RUN IT / BREAK IT / BUILD IT |

> LGD 治理线的理论仓、协议仓、验证仓与入口仓，统一维护于 [`zhaoxinghua09-cell`](https://github.com/zhaoxinghua09-cell)。

### 权属宣告（照抄《LGD 对外表述规范》v1.4 §3.2）

```
© 2026 赵兴华 / Steven Zhao·China (ORCID 0009-0001-0512-1237). All rights reserved.
理论署名 (attribution) : LGD（Lifecycle Governance Doctrine / 全程治理论）— SynomosAI initiative
名称状态 (name status)  : "SynomosAI" / "MedXpert" — 未申请实体注册、未申请商标注册
                        (not a registered legal entity; no trademark registered)
生产参考部署 (production reference, self-reported) : MedXpert
                    ← 非认证、非背书、非监管认可（not a certification or endorsement）

代码许可 (code license) : 本页不涉代码；LGD 治理线代码仓（如 uibc-core）为 Apache-2.0（see repo LICENSE）
                    本页与 LGD 理论表述文本不在任何代码许可覆盖范围内
引用格式 (cite as)      : 本页无独立 DOI —— 理论真源 zhaoxinghua09-cell/lgd-theory · concept DOI 10.5281/zenodo.22456647
```
