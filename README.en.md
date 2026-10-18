# SynomosAI (Nomos AI) — Organization Home

[![Org](https://img.shields.io/badge/SynomosAI-Nomos%20AI-blue.svg)](https://github.com/SynomosAI)
[![Governance](https://img.shields.io/badge/line-AI%20Governance-6f42c1.svg)](https://github.com/SynomosAI)
[![Pillars](https://img.shields.io/badge/pillars-4-blue.svg)](https://github.com/SynomosAI)

**When AI enters business, trust is the only hard currency.**
SynomosAI (Nomos AI) is a theory-and-engineering system built on four pillars — **Identity · Traceability · Governance · Symbiosis** — making every AI decision **traceable, explainable, auditable, and accountable**.

> Full theory stance (Chinese + 9-language index): [`traceability-audit`](https://github.com/SynomosAI/traceability-audit)

---

## Four Pillars

| Pillar | Meaning | Representative repos |
|---|---|---|
| **Identity** | AI actors need verifiable identity anchors | `synomosai-gov-tooling` (identity-code lookup) |
| **Traceability** | Every decision can be reconstructed as a fact chain | `traceability-audit`, `traceability-audit-team` |
| **Governance** | From doctrine to auditable evidence base | `ai-governance-audit-chain`, `human-oversight-gate`, `premise-and-config-audit` |
| **Symbiosis** | Long-term collaboration order between humans and AI | `ai-consciousness`, `ai-grader` (AI consciousness scale) |

## Skill Ecosystem

Ready-to-use Agent Skills (SKILL.md convention, compatible with mainstream AI agent frameworks): **full ecosystem at [`synomosai-skills`](https://github.com/SynomosAI/synomosai-skills)**

- Governance chain: `ai-governance-audit-chain` · `audit-trail-keeper` · `human-oversight-gate` · `publish-quality-gate` · `regulatory-review-planner`
- Quality gates: `research-quality-gate` · `code-review-standard` · `continuous-test-review-loop` · `academic-pre-review-committee` · `autoreview`
- Cognition assessment: `ai-grader` · `premise-and-config-audit` · `traceability-audit-team`

## Quick start

1. Read the theory stance: https://github.com/SynomosAI/traceability-audit
2. Browse the skill ecosystem: https://github.com/SynomosAI/synomosai-skills
3. Try the governance tools: `synomosai-gov-tooling` (MCP Server + OpenAPI governance API)

```bash
# list organization repositories
gh repo list SynomosAI --limit 50

# clone the skill ecosystem
git clone https://github.com/SynomosAI/synomosai-skills.git
```

---

## Disclaimer

Content in this organization reflects SynomosAI's **theory stance and tooling exploration**, not any claim of certification, commercial delivery, or service to specific customers; external standards cited (ISO/IEC 42001, NIST AI RMF, GB/Z 185, EU AI Act) are public-source references — **verify independently** before formal use. API, authorization codes and ambassador programs are roadmap items, not yet live.

---

## Core 5 · Governance Line Entry

**What we do** — an AI full-lifecycle governance engineering system built around "registry, evidence, gates": theory, protocol, verification tools, and public entry, four layers connected.

| Layer | Repo (`owner/repo`) | Description |
|---|---|---|
| Theory | [`zhaoxinghua09-cell/lgd-theory`](https://github.com/zhaoxinghua09-cell/lgd-theory) | LGD full-lifecycle governance doctrine · concept DOI 10.5281/zenodo.22456647 |
| Protocol | [`zhaoxinghua09-cell/uibc-core`](https://github.com/zhaoxinghua09-cell/uibc-core) | Reference implementation + conformance tests (code Apache-2.0) |
| Verification | [`zhaoxinghua09-cell/silent-failure-catalog`](https://github.com/zhaoxinghua09-cell/silent-failure-catalog) · [`zhaoxinghua09-cell/assayance`](https://github.com/zhaoxinghua09-cell/assayance) | Silent-failure catalog · meta-method judging "whether a check is a check" |
| Entry | [`zhaoxinghua09-cell/LGD`](https://github.com/zhaoxinghua09-cell/LGD) | Public entry & contribution system: RUN IT / BREAK IT / BUILD IT |

## Repository structure

`.github` is the organization-level configuration and facade repository (GitHub convention name; the org home page renders `profile/README.md`):

- `profile/README.md` — org home page content (same source as this README)
- `SECURITY.md` — organization-level security policy
- `CODEOWNERS` — code review ownership
- `llms.txt` / `llms-full.txt` / `AGENTS.md` / `README.en.md` — AI discoverability files

## License / License notice

This repository is an **organization facade & configuration repo and carries no standalone LICENSE file**. Page content and org theory/spec text are not covered by any code license; each code repository's license governs its own content (e.g. LGD governance-line code repos are Apache-2.0). Confirm the terms with the maintainers before redistributing org documents.

## Security & contributing

- Report security issues per [SECURITY.md](SECURITY.md)
- Contribution conventions per [CONTRIBUTING.md](CONTRIBUTING.md) (where configured) and each code repo's guide

### Ownership declaration (verbatim from "LGD External Representation Standard" v1.4 §3.2)

```
© 2026 赵兴华 / Steven Zhao·China (ORCID 0009-0001-0512-1237). All rights reserved.
Attribution: LGD (Lifecycle Governance Doctrine) — SynomosAI initiative
Name status: "SynomosAI" / "MedXpert" — not a registered legal entity; no trademark registered
Production reference (self-reported): MedXpert — not a certification or endorsement
Code license: this page carries no code; LGD governance-line code repos are Apache-2.0 (see repo LICENSE)
Cite as: no standalone DOI — theory source zhaoxinghua09-cell/lgd-theory · concept DOI 10.5281/zenodo.22456647
```
