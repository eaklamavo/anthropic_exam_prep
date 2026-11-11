# Claude Certified Developer – Foundations (CCDV-F) — Exam Prep

**Exam name**: Claude Certified Developer – Foundations
**Cert code**: CCDV-F
**Provider**: Anthropic
**Primary language for labs**: Python (Claude API, Agent SDK, MCP, security/tooling patterns, plus an optional real `call_claude()` API helper)
**Depth level**: deep (5 exercises + stretch goals per domain, except Domains 3/4 which have 3 exercises reflecting their smaller exam weight)

## Domain Map

| # | Domain | Weight | Notebook |
|---|--------|--------|----------|
| 1 | Agents and Workflows | 14.7% | [01-agents-and-workflows.ipynb](./01-agents-and-workflows.ipynb) |
| 2 | Applications and Integration | 33.1% | [02-applications-and-integration.ipynb](./02-applications-and-integration.ipynb) |
| 3 | Claude Code | 3.1% | [03-claude-code.ipynb](./03-claude-code.ipynb) |
| 4 | Eval, Testing, and Debugging | 2.6% | [04-eval-testing-and-debugging.ipynb](./04-eval-testing-and-debugging.ipynb) |
| 5 | Model Selection and Optimization | 16.8% | [05-model-selection-and-optimization.ipynb](./05-model-selection-and-optimization.ipynb) |
| 6 | Prompt and Context Engineering | 11.0% | [06-prompt-and-context-engineering.ipynb](./06-prompt-and-context-engineering.ipynb) |
| 7 | Security and Safety | 8.1% | [07-security-and-safety.ipynb](./07-security-and-safety.ipynb) |
| 8 | Tools and MCPs | 10.6% | [08-tools-and-mcps.ipynb](./08-tools-and-mcps.ipynb) |

**Capstone**: [00-capstone.ipynb](./00-capstone.ipynb) — a production support-ticket triage application exercising all 8 domains.

**Study tip**: spend proportionally more time on Domain 2 (33.1% — the largest by far) and Domain 5 (16.8%); Domains 3 and 4 are individually small but still appear on every exam form.

## Prerequisites

- Python 3.10+ (or TypeScript/Node.js if you prefer — the real exam accepts either; this pack uses Python)
- `pip install jupyterlab anthropic`
- (Optional) an `ANTHROPIC_API_KEY` environment variable for the few cells that call the real API
- 1-5 years of software engineering experience and familiarity with REST APIs/CLI tools is assumed per the official candidate profile

## How to Use

Open notebooks in order (01 → 08, then the capstone). Run all cells top-to-bottom. Complete the `# TODO:` exercises before moving to the next notebook. Each notebook ends with a 5-question self-assessment.

## Estimated Study Time

| Depth | Per domain | Capstone | Total |
|---|---|---|---|
| quick | ~20-30 min | ~1.5 hr | ~4 hr |
| standard | ~45-60 min | ~3.5 hr | ~9.5 hr |
| **deep (this pack)** | ~65-95 min | ~5-8 hr | ~14-17 hr |

## Recommended Resources

### 📋 Official Exam Resources
| Resource | URL |
|----------|-----|
| Official Exam Guide (PDF) | https://anthropic-partners.skilljar.com/claude-certified-developer-foundations-certification |
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
| Claude Code docs | — search: "Claude Code documentation CLAUDE.md" |
| Prompt caching / Message Batches API | — search: "Claude prompt caching Message Batches API documentation" |

### 🎓 Training & Courses
| Resource | URL |
|----------|-----|
| Claude Certified Developer – Foundations Prep Course (free) | https://anthropic-partners.skilljar.com/path/claude-certified-developer-foundations |
| Building with the Claude API | https://anthropic-partners.skilljar.com/claude-with-the-anthropic-api |
| Claude Code in Action | https://anthropic-partners.skilljar.com/claude-code-in-action |
| Introduction to Model Context Protocol | https://anthropic-partners.skilljar.com/introduction-to-model-context-protocol |

### 📝 Cheat Sheets & Quick Reference
| Resource | URL |
|----------|-----|
| Exam blueprint (this README's Domain Map above) | ./README.md |
| Error taxonomy quick reference | See Domain 4 notebook, "Key Concepts" section |

### 🛠️ Key Docs by Exam Domain
| Domain | Topic | URL |
|--------|-------|-----|
| Domain 1 | Building effective agents | — search: "building effective agents Anthropic engineering blog" |
| Domain 2 | Claude API mechanics (messages, streaming, batches) | https://platform.claude.com/docs |
| Domain 3 | Claude Code documentation | — search: "Claude Code documentation CLAUDE.md settings.json" |
| Domain 4 | Debugging Claude applications | — search: "Claude API error handling debugging guide" |
| Domain 5 | Model overview and pricing | https://www.anthropic.com/pricing |
| Domain 6 | Prompt engineering guide | — search: "Anthropic prompt engineering guide" |
| Domain 7 | Anthropic Trust & Compliance | https://trust.anthropic.com/ |
| Domain 8 | MCP specification | — search: "Model Context Protocol specification modelcontextprotocol.io" |

### 🧪 Practice Exams & Labs
| Resource | URL |
|----------|-----|
| Official sample questions | Included in the Exam Guide PDF (Section 8) — see Official Exam Resources above |
| Hands-on labs | This prep pack's notebooks (01-08 + capstone) |

### 🏘️ Community & Support
| Resource | URL |
|----------|-----|
| Anthropic Partner Network | https://partnerportal.anthropic.com/s/partner-registration |
| Exam scheduling support (Pearson VUE) | https://www.pearsonvue.com/us/en/anthropic.html |
| Certification support email | certifications-support@anthropic.com |
