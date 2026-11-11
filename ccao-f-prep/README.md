# Claude Certified Associate – Foundations (CCAO-F) — Exam Prep

**Exam name**: Claude Certified Associate – Foundations
**Cert code**: CCAO-F
**Provider**: Anthropic
**Primary language for labs**: Python (using the Claude API via a `call_claude()` helper — falls back to simulated responses if no `ANTHROPIC_API_KEY` is set, since the real exam centers on using Claude's chat/Projects UI rather than writing code)
**Depth level**: deep (5 exercises + stretch goals per domain)

## Domain Map

| # | Domain | Weight | Notebook |
|---|--------|--------|----------|
| 1 | Prompting and Task Execution | 14% | [01-prompting-and-task-execution.ipynb](./01-prompting-and-task-execution.ipynb) |
| 2 | Output Evaluation and Validation | 21% | [02-output-evaluation-and-validation.ipynb](./02-output-evaluation-and-validation.ipynb) |
| 3 | Product and Model Selection | 12% | [03-product-and-model-selection.ipynb](./03-product-and-model-selection.ipynb) |
| 4 | Workflow Integration and Solution Design | 16% | [04-workflow-integration-and-solution-design.ipynb](./04-workflow-integration-and-solution-design.ipynb) |
| 5 | Configuration and Knowledge Management | 12% | [05-configuration-and-knowledge-management.ipynb](./05-configuration-and-knowledge-management.ipynb) |
| 6 | Governance, Risk, and Responsible Use | 15% | [06-governance-risk-and-responsible-use.ipynb](./06-governance-risk-and-responsible-use.ipynb) |
| 7 | Troubleshooting and Optimization | 10% | [07-troubleshooting-and-optimization.ipynb](./07-troubleshooting-and-optimization.ipynb) |

**Capstone**: [00-capstone.ipynb](./00-capstone.ipynb) — end-to-end client onboarding modernization project exercising all 7 domains.

## Prerequisites

- Python 3.10+
- `pip install jupyterlab anthropic`
- (Optional) an `ANTHROPIC_API_KEY` environment variable — notebooks run without it using simulated responses, but real API calls give a much more realistic study experience
- A free or paid claude.ai account is recommended to practice the real UI features (Projects, Artifacts, research mode) referenced throughout

## How to Use

Open notebooks in order (01 → 07, then the capstone). Run all cells top-to-bottom. Complete the `# TODO:` exercises before moving to the next notebook. Each notebook ends with a 5-question self-assessment — answer before revealing the Answers cell.

## Estimated Study Time

| Depth | Per domain | Capstone | Total |
|---|---|---|---|
| quick | ~20 min | ~1.5 hr | ~3.5 hr |
| standard | ~45 min | ~3.5 hr | ~8.5 hr |
| **deep (this pack)** | ~60-90 min | ~5-8 hr | ~12-18 hr |

## Recommended Resources

### 📋 Official Exam Resources
| Resource | URL |
|----------|-----|
| Official Exam Guide (PDF) | https://anthropic-partners.skilljar.com/claude-certified-associate-foundations-certification |
| Certification Program Overview | https://www.pearsonvue.com/us/en/anthropic.html |
| Certification Terms & Conditions | — search: "Anthropic Certification Terms and Conditions PDF" |
| Anthropic Certification Exam Policy | — search: "Anthropic Certification Exam Policy PDF" |
| Register / Schedule Exam (Pearson VUE) | https://wsr.pearsonvue.com/testtaker/signin/SignInPage/ANTHROPIC |

### 📚 Official Documentation
| Resource | URL |
|----------|-----|
| Claude Docs (platform overview) | https://platform.claude.com/docs |
| Claude Help Center | https://support.claude.com/en/ |
| Claude Projects | — search: "Claude Projects help article" |
| Claude Artifacts | — search: "Claude Artifacts help article" |

### 🎓 Training & Courses
| Resource | URL |
|----------|-----|
| Claude Certified Associate – Foundations Prep Course (free) | https://anthropic-partners.skilljar.com/path/claude-certified-associate-foundations |
| Claude 101 | https://anthropic-partners.skilljar.com/claude-101 |
| AI Fluency: Framework & Foundations | https://anthropic-partners.skilljar.com/ai-fluency-framework-foundations |
| Introduction to Claude Cowork | https://anthropic-partners.skilljar.com/introduction-to-claude-cowork |
| Anthropic Academy (all courses) | https://anthropic-partners.skilljar.com/ |

### 📝 Cheat Sheets & Quick Reference
| Resource | URL |
|----------|-----|
| Exam blueprint summary (this README's Domain Map above) | ./README.md |
| Prompting best practices | — search: "Anthropic prompt engineering overview" |

### 🛠️ Key Docs by Exam Domain
| Domain | Topic | URL |
|--------|-------|-----|
| Domain 1 | Prompting techniques | — search: "Anthropic prompt engineering guide" |
| Domain 2 | Evaluating model output / reducing hallucinations | — search: "Anthropic reducing hallucinations" |
| Domain 3 | Claude models overview (Haiku/Sonnet/Opus) | https://www.anthropic.com/claude |
| Domain 4 | Claude for business workflows | https://claude.com/solutions |
| Domain 5 | Claude Projects & knowledge sources | — search: "Claude Projects knowledge sources help" |
| Domain 6 | Anthropic Usage Policy | https://www.anthropic.com/legal/aup |
| Domain 7 | Troubleshooting prompts | — search: "Anthropic prompt troubleshooting" |

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
