# Claude Certified Architect – Foundations (CCAR-F) — Exam Prep

**Exam name**: Claude Certified Architect – Foundations
**Cert code**: CCAR-F
**Provider**: Anthropic
**Primary language for labs**: Python (Claude Agent SDK, Claude API, MCP, and Claude Code concepts, demonstrated via runnable Python simulations plus an optional real `call_claude()` API helper)
**Depth level**: deep (5 exercises + stretch goals per domain)

## Domain Map

| # | Domain | Weight | Notebook |
|---|--------|--------|----------|
| 1 | Agentic Architecture & Orchestration | 27% | [01-agentic-architecture-and-orchestration.ipynb](./01-agentic-architecture-and-orchestration.ipynb) |
| 2 | Tool Design & MCP Integration | 18% | [02-tool-design-and-mcp-integration.ipynb](./02-tool-design-and-mcp-integration.ipynb) |
| 3 | Claude Code Configuration & Workflows | 20% | [03-claude-code-configuration-and-workflows.ipynb](./03-claude-code-configuration-and-workflows.ipynb) |
| 4 | Prompt Engineering & Structured Output | 20% | [04-prompt-engineering-and-structured-output.ipynb](./04-prompt-engineering-and-structured-output.ipynb) |
| 5 | Context Management & Reliability | 15% | [05-context-management-and-reliability.ipynb](./05-context-management-and-reliability.ipynb) |

**Capstone**: [00-capstone.ipynb](./00-capstone.ipynb) — a customer support resolution agent (Claude Agent SDK + MCP) exercising all 5 domains.

**Exam format note**: the real exam presents 4 scenarios (drawn randomly from a bank of 6: Customer
Support Resolution Agent, Code Generation with Claude Code, Multi-Agent Research System, Developer
Productivity with Claude, Claude Code for CI, Structured Data Extraction). The capstone here is built
around the Customer Support scenario; the domain notebooks' exercises draw on all 6.

## Prerequisites

- Python 3.10+
- `pip install jupyterlab anthropic`
- (Optional) an `ANTHROPIC_API_KEY` environment variable for the few cells that call the real API
- Familiarity with the Claude Agent SDK, Claude Code, and MCP is assumed — review the official docs linked below if you're new to any of them

## How to Use

Open notebooks in order (01 → 05, then the capstone). Run all cells top-to-bottom. Complete the `# TODO:` exercises before moving to the next notebook. Each notebook ends with a 5-question self-assessment.

## Estimated Study Time

| Depth | Per domain | Capstone | Total |
|---|---|---|---|
| quick | ~25 min | ~1.5 hr | ~3.5 hr |
| standard | ~50 min | ~3.5 hr | ~7.5 hr |
| **deep (this pack)** | ~75-100 min | ~5-8 hr | ~13-16 hr |

## Recommended Resources

### 📋 Official Exam Resources
| Resource | URL |
|----------|-----|
| Official Exam Guide (PDF) | https://anthropic-partners.skilljar.com/claude-certified-architect-foundations-certification |
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

### 🎓 Training & Courses
| Resource | URL |
|----------|-----|
| Claude Certified Architect – Foundations Prep Path (free) | https://anthropic-partners.skilljar.com/claude-certified-architect-foundations-certification |
| Building with the Claude API | https://anthropic-partners.skilljar.com/claude-with-the-anthropic-api |
| Introduction to Model Context Protocol | https://anthropic-partners.skilljar.com/introduction-to-model-context-protocol |
| Claude Code in Action | https://anthropic-partners.skilljar.com/claude-code-in-action |
| Claude with Amazon Bedrock | https://anthropic-partners.skilljar.com/claude-in-amazon-bedrock |
| Claude on Google Cloud | https://anthropic-partners.skilljar.com/claude-with-google-vertex |

### 📝 Cheat Sheets & Quick Reference
| Resource | URL |
|----------|-----|
| Exam blueprint & scenario bank (this README's Domain Map above) | ./README.md |
| CLAUDE.md hierarchy & rules quick reference | See Domain 3 notebook, "Key Concepts" section |

### 🛠️ Key Docs by Exam Domain
| Domain | Topic | URL |
|--------|-------|-----|
| Domain 1 | Claude Agent SDK — agent loops, subagents, hooks | — search: "Claude Agent SDK subagents hooks documentation" |
| Domain 2 | Model Context Protocol tool/resource design | — search: "MCP server tools resources specification" |
| Domain 3 | Claude Code CLAUDE.md, skills, slash commands | — search: "Claude Code CLAUDE.md skills slash commands" |
| Domain 4 | Tool use & structured output (JSON schema) | — search: "Claude tool use structured output JSON schema" |
| Domain 5 | Context window & prompt caching | — search: "Claude context window prompt caching documentation" |

### 🧪 Practice Exams & Labs
| Resource | URL |
|----------|-----|
| Official sample questions (12 scenario-based questions) | Included in the Exam Guide PDF (Section 9) — see Official Exam Resources above |
| Hands-on labs | This prep pack's notebooks (01-05 + capstone) |

### 🏘️ Community & Support
| Resource | URL |
|----------|-----|
| Anthropic Partner Network | https://partnerportal.anthropic.com/s/partner-registration |
| Exam scheduling support (Pearson VUE) | https://www.pearsonvue.com/us/en/anthropic.html |
| Certification support email | certifications-support@anthropic.com |
