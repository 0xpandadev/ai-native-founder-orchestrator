---
name: ai-native-founder-orchestrator
description: Orchestrate AI-native company building and go-to-market across Idea, MVP, Launch, and Scale. Use when founders, operators, or startup advisors ask how to apply Founder Playbook thinking, classify a startup stage, divide work between the human founder, Claude Chat, Claude Code, Claude Cowork, Skills, memory, workflows, GTM, sales, or business development, and create AI-native execution plans, MVP scopes, CLAUDE.md files, GTM packs, workflow maps, bottleneck audits, domain knowledge maps, or weekly operating reviews. Not generic startup advice.
---

# AI-Native Founder Orchestrator

Use this skill to turn messy founder context into an AI-native operating plan.

The core question is not "what should this startup do next?" The core question is:

> If the company is built around AI from day one, what should humans decide, what should AI reason through, what should AI build, how should the company sell, and what should become a reusable workflow, Skill, or memory?

This skill is inspired by public Founder Playbook concepts: Idea, MVP, Launch, Scale; goals; exit criteria; failure modes; AI-powered exercises; Claude Chat; Claude Code; Claude Cowork; Skills; memory; and AI-generated MVP discipline. It also incorporates public AI-at-work sales patterns such as pipeline prioritization, meeting prep, forecast review, account planning, and stalled-deal diagnosis. Do not claim this skill is official Anthropic or OpenAI material.

## Default Behavior

Respond in the user's language unless they ask otherwise.

When the user gives startup context, produce an `AI-Native Execution Plan` before giving optional detail.

Required output:

1. `Stage`: Idea, MVP, Launch, Scale, or a boundary state such as `Idea -> MVP`.
2. `Why this stage`: evidence from the user's context.
3. `Founder-only decisions`: choices that require human judgment, trust, taste, ethics, customer access, or strategy.
4. `Claude Chat tasks`: reasoning, synthesis, hypothesis generation, interview design, prioritization, and critique.
5. `Claude Code tasks`: implementation, tests, refactors, dev automation, security checks, and repo artifacts.
6. `Claude Cowork tasks`: long-document analysis, customer notes, research synthesis, transcript review, and knowledge extraction.
7. `GTM / BD motion`: how AI should support selling, account work, partnerships, pipeline, or distribution when relevant.
8. `Skills / memory / workflow opportunities`: repeatable routines or domain knowledge that should become persistent AI infrastructure.
9. `This week's artifact`: one concrete output to create now.
10. `Exit criteria`: observable evidence needed to move to the next stage.
11. `AI-native failure mode`: the most dangerous way AI could make the founder move faster in the wrong direction.

Keep the first answer decision-ready. Add examples, templates, or prompts only after the plan or when the user asks for a specific artifact.

## Stage Classifier

Classify by evidence, not by founder confidence.

Use `references/stage-playbooks.md` when the user asks for deeper stage guidance or when stage classification is ambiguous.

Quick classifier:

- `Idea`: problem, user, market, or wedge is still being validated. The main work is learning and falsification.
- `MVP`: a narrow product is being built or tested. The main work is scope control, architecture discipline, and proof that someone will use or pay.
- `Launch`: real users, support, bugs, feedback, sales, or onboarding are arriving. The main work is replacing founder attention with AI-assisted workflows without losing customer trust.
- `Scale`: repeatable demand exists. The main work is converting domain knowledge, decisions, and operating routines into reusable Skills, memory, systems, and team workflows.

If evidence is mixed, use a boundary state and name the unresolved proof:

```text
Stage: Idea -> MVP
Unresolved proof: users have expressed interest, but no one has committed data, time, money, or a workflow change.
```

## Operating Frame

Always separate five work surfaces:

```text
Human founder     -> judgment, trust, taste, stakes, customer access
Claude Chat       -> reasoning, critique, synthesis, questions, hypotheses
Claude Code       -> code, tests, repo artifacts, automation, technical review
Claude Cowork     -> long documents, customer notes, transcripts, research corpora
Skills / memory   -> persistent company knowledge and repeatable workflows
```

Do not let the answer collapse into generic "talk to customers", "build an MVP", or "do sales" advice. Tie every recommendation to the AI-native operating model.

## GTM / BD Layer

Use `references/gtm-sales-playbooks.md` when the user is in Launch or Scale stage, asks about sales, go-to-market, business development, partnerships, pipeline, account planning, meetings, forecast risk, stalled deals, or customer follow-up.

The GTM layer turns scattered customer context into reviewable action artifacts:

- pipeline prioritization from underworked accounts,
- meeting prep and follow-up,
- forecast / commit risk review,
- strategic account plan refresh,
- stalled deal diagnosis,
- partnership or BD opportunity map.

Default GTM rule:

```text
Founder owns relationship strategy and judgment.
AI assembles context, drafts first-pass artifacts, separates sourced facts from inference, and creates next-step options.
```

Never invent commitments, dates, customer facts, or relationship context. If source material is missing, state what is needed.

## Artifact Selection

Use `references/artifact-specs.md` when creating any artifact.

Default artifact by stage:

- Idea: `AI-native validation plan`
- MVP: `MVP scope document` or `CLAUDE.md`
- Launch: `AI workflow map` or `AI-native GTM pack`
- Scale: `Domain knowledge to Skill map` or `strategic account plan refresh`

Choose `Founder bottleneck audit` when the user is overwhelmed or doing too much manually.
Choose `Weekly AI-native operating review` when the user provides a weekly update.
Choose `AI-native GTM pack` when the user has real prospects, accounts, customer conversations, sales notes, BD conversations, pipeline, or launch feedback.

## Failure Mode Checks

Always include one failure mode. Prefer these defaults unless the context points elsewhere:

- Idea: outsourcing judgment to AI too early.
- MVP: building because AI makes building cheap.
- Launch: founder attention and GTM context becoming the bottleneck.
- Scale: company knowledge and account strategy trapped in people or scattered docs instead of AI-usable systems.

Add a countermeasure that changes behavior this week.

## Prompt Patterns

Use these when the user asks how to run the skill.

### Diagnose my startup

```text
Use AI-Native Founder Orchestrator.

Context:
- Company / idea:
- Target customer:
- What exists today:
- Evidence from users:
- Current bottleneck:
- What I am tempted to do next:

Return an AI-Native Execution Plan.
```

### Create my MVP scope

```text
Use AI-Native Founder Orchestrator.

We are in MVP stage. Create:
1. MVP scope document
2. CLAUDE.md
3. Claude Code implementation prompt
4. technical debt and security checklist

Context:
...
```

### Turn launch chaos into AI workflows

```text
Use AI-Native Founder Orchestrator.

We launched and founder attention is overloaded.
Inputs arriving:
- support:
- bugs:
- feature requests:
- sales notes:
- onboarding issues:

Create an AI workflow map and founder bottleneck audit.
```

### Create my AI-native GTM pack

```text
Use AI-Native Founder Orchestrator.

We are in Launch or Scale stage.
Inputs:
- accounts / prospects:
- customer notes:
- meeting notes or transcripts:
- email or CRM exports:
- usage signals:
- support or product signals:
- founder concerns:

Create an AI-native GTM pack with pipeline prioritization, meeting prep, stalled-deal diagnosis, account next actions, and founder-only sales decisions. Separate sourced facts from inferred opportunity.
```

### Convert company knowledge into Skills

```text
Use AI-Native Founder Orchestrator.

We have repeated domain knowledge and workflows.
Raw knowledge:
- customer patterns:
- sales objections:
- support playbooks:
- implementation rules:
- product principles:

Create a domain knowledge to Skill map.
```

## Quality Bar

A strong answer:

- Names the stage with evidence.
- Splits work across human founder, Claude Chat, Claude Code, Claude Cowork, and Skills/memory.
- Produces one artifact, not a long menu of possibilities.
- Defines exit criteria that can be observed.
- Turns GTM and BD context into concrete account or pipeline artifacts when the company has real customer motion.
- Flags the AI-native failure mode.
- Protects founder judgment instead of outsourcing it to AI.

Reject weak answers that:

- sound like generic startup coaching,
- suggest building simply because AI can build,
- treat AI as one tool rather than an operating model,
- omit exit criteria,
- omit the human founder's irreducible decisions.
