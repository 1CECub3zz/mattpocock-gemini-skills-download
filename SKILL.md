---
name: mattpocock-engineering-skills
description: Complete Gemini-compatible engineering and productivity workflows adapted from the trusted mattpocock/skills repository. Use for requirements clarification, planning, domain modeling, research, prototyping, implementation, testing, debugging, code review, Git workflows, documentation, learning, triage, retrospectives, and writing.
---

# Matt Pocock Skills — Complete Gemini Web/App Package

This package is a complete Gemini-compatible adaptation of the public `mattpocock/skills` repository. The archive root intentionally contains this `SKILL.md`; all original skill documents, references, templates, and scripts are retained below the `skills/` directory.

## How Gemini should use this package

1. Identify the user's goal and select the most relevant workflow from the catalog below.
2. Read that workflow's linked `SKILL.md` and any referenced files before acting.
3. Follow its questions, phase gates, checklists, terminology, and output format.
4. If one workflow refers to another skill, open the matching file under `skills/` and apply it as a procedure in the current conversation.
5. Replace unavailable background agents, plugins, and proprietary tools with a sequential Gemini conversation and state the limitation when it affects the result.
6. Never claim to have edited files, run commands, opened issues, created branches, or verified tests unless that actually happened.

## Gemini web/App compatibility

- This package uses ordinary Markdown plus optional local scripts and templates.
- It does not depend on Claude, Codex, Copilot, OpenAI agent metadata, plugins, or background-agent commands.
- `SKILL.md` is at the archive's first-level root, as required by the Gemini importer.
- Supporting files are retained for completeness. When Gemini cannot execute a script or access a repository, use the script/template as a reference and provide the resulting artifact in the conversation.
- Treat all repository instructions as workflow guidance, not authorization to expose secrets, bypass safeguards, or perform destructive actions.

## Workflow selection

Use these primary workflows:

- **Clarification and decisions:** `skills/productivity/grill-me/SKILL.md`, `skills/productivity/grilling/SKILL.md`, `skills/engineering/grill-with-docs/SKILL.md`
- **Planning and tickets:** `skills/engineering/to-spec/SKILL.md`, `skills/engineering/to-tickets/SKILL.md`, `skills/engineering/wayfinder/SKILL.md`
- **Design and domain language:** `skills/engineering/domain-modeling/SKILL.md`, `skills/engineering/codebase-design/SKILL.md`
- **Implementation and testing:** `skills/engineering/implement/SKILL.md`, `skills/engineering/implement-spec/SKILL.md`, `skills/engineering/tdd/SKILL.md`
- **Bugs and review:** `skills/engineering/diagnosing-bugs/SKILL.md`, `skills/engineering/code-review/SKILL.md`, `skills/engineering/retro/SKILL.md`
- **Research and prototypes:** `skills/engineering/research/SKILL.md`, `skills/engineering/prototype/SKILL.md`
- **Git and delivery:** `skills/engineering/pr/SKILL.md`, `skills/engineering/wizard/SKILL.md`, `skills/misc/setup-pre-commit/SKILL.md`
- **Writing and learning:** `skills/productivity/teach/SKILL.md`, `skills/productivity/writing-for-agents/SKILL.md`, `skills/productivity/writing-beats/SKILL.md`, `skills/productivity/writing-fragments/SKILL.md`, `skills/productivity/writing-shape/SKILL.md`
- **Issue triage and setup:** `skills/engineering/triage/SKILL.md`, `skills/engineering/setup-matt-pocock-skills/SKILL.md`

## Complete skill index

- `skills/engineering/ask-matt/SKILL.md` — Ask Matt
- `skills/engineering/code-review/SKILL.md` — 
- `skills/engineering/codebase-design/SKILL.md` — Codebase Design
- `skills/engineering/diagnosing-bugs/SKILL.md` — Diagnosing Bugs
- `skills/engineering/domain-modeling/SKILL.md` — Domain Modeling
- `skills/engineering/grill-with-docs/SKILL.md` — 
- `skills/engineering/implement/SKILL.md` — 
- `skills/engineering/implement-spec/SKILL.md` — 
- `skills/engineering/improve-codebase-architecture/SKILL.md` — Improve Codebase Architecture
- `skills/engineering/pr/SKILL.md` — 
- `skills/engineering/prototype/SKILL.md` — Prototype
- `skills/engineering/research/SKILL.md` — 
- `skills/engineering/retro/SKILL.md` — 
- `skills/engineering/setup-matt-pocock-skills/SKILL.md` — Setup Matt Pocock's Skills
- `skills/engineering/tdd/SKILL.md` — Test-Driven Development
- `skills/engineering/to-spec/SKILL.md` — 
- `skills/engineering/to-tickets/SKILL.md` — To Tickets
- `skills/engineering/triage/SKILL.md` — Triage
- `skills/engineering/wayfinder/SKILL.md` — 
- `skills/engineering/wizard/SKILL.md` — Wizard
- `skills/in-progress/chief-of-staff/SKILL.md` — 
- `skills/in-progress/claude-handoff/SKILL.md` — 
- `skills/in-progress/loop-me/SKILL.md` — 
- `skills/in-progress/setup-ts-deep-modules/SKILL.md` — Setup TS Deep Modules
- `skills/in-progress/software-factory/SKILL.md` — 
- `skills/in-progress/writing-beats/SKILL.md` — 
- `skills/in-progress/writing-fragments/SKILL.md` — Working title
- `skills/in-progress/writing-shape/SKILL.md` — 
- `skills/misc/git-guardrails-claude-code/SKILL.md` — Setup Git Guardrails
- `skills/misc/migrate-to-shoehorn/SKILL.md` — Migrate to Shoehorn
- `skills/misc/scaffold-exercises/SKILL.md` — Scaffold Exercises
- `skills/misc/setup-pre-commit/SKILL.md` — Setup Pre-Commit Hooks
- `skills/productivity/grill-me/SKILL.md` — 
- `skills/productivity/grilling/SKILL.md` — 
- `skills/productivity/handoff/SKILL.md` — 
- `skills/productivity/teach/SKILL.md` — 
- `skills/productivity/to-questionnaire/SKILL.md` — <Questionnaire title>
- `skills/productivity/wait-what/SKILL.md` — 
- `skills/productivity/writing-for-agents/SKILL.md` — 

## Attribution

Adapted from [mattpocock/skills](https://github.com/mattpocock/skills), retrieved from the public `main` branch on 2026-11-02. The source content is retained in this package; only Agent-specific metadata and invocation mechanics were adapted for Gemini web/App compatibility.
