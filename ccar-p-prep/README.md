# Claude Certified Architect – Professional (CCAR-P) — Exam Prep

**Exam name**: Claude Certified Architect – Professional
**Cert code**: CCAR-P
**Provider**: Anthropic
**Primary language for labs**: Python (architecture/decision-framework simulations, plus an optional real `call_claude()` API helper for a few cells)
**Depth level**: deep (5 exercises + stretch goals per domain)

## Domain Map

| # | Domain | Weight | Notebook |
|---|--------|--------|----------|
| 1 | Solution Design & Architecture | 17% | [01-solution-design-and-architecture.ipynb](./01-solution-design-and-architecture.ipynb) |
| 2 | Claude Models, Prompting & Context Engineering | 13% | [02-claude-models-prompting-and-context-engineering.ipynb](./02-claude-models-prompting-and-context-engineering.ipynb) |
| 3 | Integration | 19% | [03-integration.ipynb](./03-integration.ipynb) |
| 4 | Evaluation, Testing & Optimization | 16% | [04-evaluation-testing-and-optimization.ipynb](./04-evaluation-testing-and-optimization.ipynb) |
| 5 | Governance, Safety & Risk Management | 14% | [05-governance-safety-and-risk-management.ipynb](./05-governance-safety-and-risk-management.ipynb) |
| 6 | Stakeholder Communication & Lifecycle Management | 14% | [06-stakeholder-communication-and-lifecycle-management.ipynb](./06-stakeholder-communication-and-lifecycle-management.ipynb) |
| 7 | Developer Productivity & Operational Enablement | 7% | [07-developer-productivity-and-operational-enablement.ipynb](./07-developer-productivity-and-operational-enablement.ipynb) |

**Capstone**: [00-capstone.ipynb](./00-capstone.ipynb) — end-to-end enterprise claims-processing assistant exercising all 7 domains.

## Prerequisites

- Python 3.10+
- `pip install jupyterlab anthropic`
- (Optional) an `ANTHROPIC_API_KEY` environment variable for the few cells that call the real API
- Recommended: prior completion of CCAR-F (Architect – Foundations) or equivalent hands-on Claude API/Agent SDK/MCP experience

## How to Use

Open notebooks in order (01 → 07, then the capstone). Run all cells top-to-bottom. Complete the `# TODO:` exercises before moving to the next notebook. Each notebook ends with a 5-question self-assessment.

## Estimated Study Time

| Depth | Per domain | Capstone | Total |
|---|---|---|---|
| quick | ~25 min | ~2 hr | ~4 hr |
| standard | ~55 min | ~4 hr | ~10.5 hr |
| **deep (this pack)** | ~80-110 min | ~5-8 hr | ~15-18 hr |

## Recommended Resources

### 📋 Official Exam Resources
| Resource | URL |
|----------|-----|
| Official Exam Guide (PDF) | https://anthropic-partners.skilljar.com/claude-certified-architect-professional-certification |
| Certification Program Overview | https://www.pearsonvue.com/us/en/anthropic.html |
| Certification Terms & Conditions | — search: "Anthropic Certification Terms and Conditions PDF" |
| Anthropic Certification Exam Policy | — search: "Anthropic Certification Exam Policy PDF" |
| Register / Schedule Exam (Pearson VUE) | https://wsr.pearsonvue.com/testtaker/signin/SignInPage/ANTHROPIC |

### 📚 Official Documentation
| Resource | URL |
|----------|-----|
| Claude Platform Docs | https://platform.claude.com/docs |
| Claude Agent SDK docs | — search: "Claude Agent SDK documentation" |
| Model Context Protocol docs | — search: "Model Context Protocol documentation modelcontextprotocol.io" |
| Prompt caching guide | — search: "Claude prompt caching documentation" |

### 🎓 Training & Courses
| Resource | URL |
|----------|-----|
| Claude Certified Architect – Professional Prep Path (free) | https://anthropic-partners.skilljar.com/path/claude-certified-architect-professional |
| Building with the Claude API | https://anthropic-partners.skilljar.com/claude-with-the-anthropic-api |
| Introduction to Model Context Protocol | https://anthropic-partners.skilljar.com/introduction-to-model-context-protocol |
| Model Context Protocol: Advanced Topics | https://anthropic-partners.skilljar.com/model-context-protocol-advanced-topics |
| Claude with Amazon Bedrock | https://anthropic-partners.skilljar.com/claude-in-amazon-bedrock |
| Claude on Google Cloud | https://anthropic-partners.skilljar.com/claude-with-google-vertex |

### 📝 Cheat Sheets & Quick Reference
| Resource | URL |
|----------|-----|
| Exam blueprint (this README's Domain Map above) | ./README.md |
| Architecture decision-communication template | See Domain 6 notebook, "decision_summary" concept |

### 🛠️ Key Docs by Exam Domain
| Domain | Topic | URL |
|--------|-------|-----|
| Domain 1 | Agentic vs. workflow architecture patterns | — search: "building effective agents Anthropic" |
| Domain 2 | Context windows & prompt caching | — search: "Claude context window prompt caching documentation" |
| Domain 3 | RAG / retrieval best practices with Claude | — search: "Claude retrieval augmented generation best practices" |
| Domain 4 | Evaluating LLM applications | — search: "Anthropic evaluating AI applications guide" |
| Domain 5 | Anthropic Responsible Scaling / safety practices | https://www.anthropic.com/news/announcing-our-updated-responsible-scaling-policy |
| Domain 6 | Anthropic trust & compliance center | https://trust.anthropic.com/ |
| Domain 7 | Claude Code documentation | — search: "Claude Code documentation CLAUDE.md" |

### 🧪 Practice Exams & Labs
| Resource | URL |
|----------|-----|
| Official sample questions | Included in the Exam Guide PDF (Section 8) — see Official Exam Resources above |
| Hands-on labs | This prep pack's notebooks (01-07 + capstone) |

### 🏘️ Community & Support
| Resource | URL |
|----------|-----|
| Anthropic Partner Network | https://partnerportal.anthropic.com/s/partner-registration |
| Exam scheduling support (Pearson VUE) | https://www.pearsonvue.com/us/en/anthropic.html |
| Certification support email | certifications-support@anthropic.com |
