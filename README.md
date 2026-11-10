# Productivity Skills for AI Agents

[![91 skills](https://img.shields.io/badge/skills-91-0b7285)](#skill-sets)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code, Codex & Claude.ai](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free **Agent Skills** (`SKILL.md`) for everyday knowledge work, for **Claude, Claude Code, OpenAI Codex** and any agent that reads the standard. Each skill gives your agent a careful, repeatable workflow: when to use it, the inputs to ask for, numbered steps, decision rules, templates and a self-check.

By [**Afeez Adebayo**](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/productivity/) · [LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon)

> **This repo is the index.** Each skill set lives in its own repository, one folder per skill (`skill-name/SKILL.md`). Pick the sets you need and clone only those.

## Skill sets

| # | Set | Skills | Repository |
|---|---|---|---|
| 1 | Jobs and Careers | 10 | [jobs-careers-skills](https://github.com/afeezadebayo/jobs-careers-skills) |
| 2 | Planning and Task Management | 10 | [planning-task-management-skills](https://github.com/afeezadebayo/planning-task-management-skills) |
| 3 | Email and Inbox | 10 | [email-inbox-skills](https://github.com/afeezadebayo/email-inbox-skills) |
| 4 | Meetings and Calendar | 7 | [meetings-calendar-skills](https://github.com/afeezadebayo/meetings-calendar-skills) |
| 5 | Workplace Writing | 11 | [workplace-writing-skills](https://github.com/afeezadebayo/workplace-writing-skills) |
| 6 | Communication and Presentations | 6 | [communication-presentations-skills](https://github.com/afeezadebayo/communication-presentations-skills) |
| 7 | Research and Learning | 13 | [research-learning-skills](https://github.com/afeezadebayo/research-learning-skills) |
| 8 | Knowledge Management | 6 | [knowledge-management-skills](https://github.com/afeezadebayo/knowledge-management-skills) |
| 9 | Thinking and Decisions | 5 | [thinking-decisions-skills](https://github.com/afeezadebayo/thinking-decisions-skills) |
| 10 | AI Workflows and Automation | 13 | [ai-workflows-automation-skills](https://github.com/afeezadebayo/ai-workflows-automation-skills) |

More skills in each set are planned. The [online library](https://afeezadebayo.com/skills-md/productivity/) shows what is live today.

## Where to start

| If you want to... | Start with |
|---|---|
| Run a job search | `daily-job-opportunities`, `cv-writer` in Jobs and Careers |
| Get organised | `productivity-system-audit`, `weekly-review` in Planning and Task Management |
| Tame your inbox | `email-system-audit`, `inbox-triage` in Email and Inbox |
| Fix your meetings | `calendar-audit`, `meeting-agenda` in Meetings and Calendar |
| Write clearer documents | `writing-process`, `memos-one-pagers` in Workplace Writing |
| Present with impact | `presentation-storyline`, `slide-design` in Communication and Presentations |
| Research reliably | `research-planning`, `fact-checking` in Research and Learning |
| Keep notes and decisions | `note-system-setup`, `decision-records` in Knowledge Management |
| Make better decisions | `problem-framing`, `decision-frameworks` in Thinking and Decisions |
| Use AI at work safely | `ai-workflow-audit`, `ai-security-privacy` in AI Workflows and Automation |

## Install

```bash
# Example: install one skill from one set in Claude Code
git clone https://github.com/afeezadebayo/planning-task-management-skills.git
cp -r planning-task-management-skills/weekly-review ~/.claude/skills/

# Codex and other agents
cp -r planning-task-management-skills/weekly-review ~/.agents/skills/
```

In Claude.ai or Claude Desktop, zip a single skill folder and upload it under **Settings → Capabilities → Skills**. Then start a new session and ask your agent which skills it can use.

## How skills work

Agents use **progressive disclosure**: they read each skill's `name` and `description` at the start of a session and load the full `SKILL.md` only when your request matches. Install the skills you use; a smaller, relevant set helps the agent pick the right one.

## Related libraries

- [Marketing skills](https://github.com/afeezadebayo/marketing-skills): 172 skills across SEO, growth, CRM, performance marketing, product marketing, content, social media and GTM engineering.

## Licence

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/). Use, share and adapt, including commercially, with credit to Afeez Adebayo and a link to the source page in each file.
