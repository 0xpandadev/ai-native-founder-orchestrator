# AI-Native Founder Orchestrator

Build with AI. Sell with AI. Keep founder judgment where it matters.

Turn public AI-native founder and Codex-for-sales playbooks into an operating system for building and selling your startup.

## GitHub Intro

**English**  
An AI-native founder operating skill inspired by Anthropic's Founder Playbook and OpenAI Academy's Codex-for-sales guide. It helps founders build, sell, and scale by separating founder judgment, AI reasoning, Codex/Claude Code implementation, customer-context analysis, GTM motion, Skills, memory, and workflows.

**Japanese**  
Anthropic Founder Playbook と OpenAI Academy の Codex 営業ガイドを参考にした、AI-native 創業者向けの運用Skillです。創業者が判断すること、AIに考えさせること、Codex / Claude Codeに作らせること、顧客文脈を読ませること、GTM / 営業 / BizDevを回すこと、Skill・memory・workflow化することを分けます。

**Chinese**  
一个受 Anthropic Founder Playbook 和 OpenAI Academy Codex 销售指南启发的 AI-native 创业者运营 Skill。它帮助创始人区分：人类判断、AI 推理、Codex / Claude Code 构建、客户上下文分析、GTM / 销售 / BD 动作，以及可复用的 Skills、memory 和 workflows。

This is a plain `SKILL.md` skill for founders, operators, and startup advisors who want to build companies around AI from day one.

It helps you decide:

- what the human founder must decide,
- what Claude Chat should reason through,
- what Claude Code should build,
- what Claude Cowork should analyze,
- how AI should support GTM, sales, accounts, and business development,
- what should become reusable Skills, memory, or workflows.

It is not a generic startup advisor. It is an AI-native company-building orchestrator across:

```text
Idea -> MVP -> Launch -> Scale
```

Based on public playbooks:

- Anthropic Founder Playbook: AI-native company building across Idea, MVP, Launch, and Scale.
- OpenAI Academy Codex-for-sales guide: pipeline briefs, meeting prep, forecast review, account plans, and stalled-deal diagnosis.

This repo is independent and unofficial.

References:
- Anthropic Founder Playbook: https://claude.com/blog/the-founders-playbook
- OpenAI Academy, sales teams and Codex: https://openai.com/academy/codex-for-work/how-sales-teams-use-codex/

## Share Hooks

### English

```text
Most AI startup advice says: "use AI to build faster."

That is incomplete.

AI-native founders need an operating system for:
- what humans decide,
- what AI reasons through,
- what Codex/Claude Code builds,
- what AI reads across customer context,
- how GTM and sales turn into repeatable workflows.

I built AI-Native Founder Orchestrator: a plain SKILL.md repo inspired by Anthropic's Founder Playbook and OpenAI Academy's Codex-for-sales guide.
```

### Japanese

```text
AI時代の起業は「速く作る」だけでは足りない。

本当に必要なのは、
- 創業者が何を判断するか
- AIに何を考えさせるか
- Codex / Claude Codeに何を作らせるか
- 顧客メモや商談情報をどう読ませるか
- GTM / 営業 / BizDevをどうAI-nativeに回すか
を分けるOSです。

Anthropic Founder Playbook と OpenAI AcademyのCodex営業ガイドを参考に、AI-Native Founder OrchestratorというSKILL.md repoを作りました。
```

### Chinese

```text
AI 创业不只是“更快地写代码”。

真正需要的是一套 AI-native operating system：
- 创始人必须亲自判断什么
- AI 应该推理和整理什么
- Codex / Claude Code 应该构建什么
- AI 应该如何阅读客户记录和销售上下文
- GTM、销售和 BD 如何变成可复用的 AI 工作流

I built AI-Native Founder Orchestrator: a plain SKILL.md repo inspired by Anthropic's Founder Playbook and OpenAI Academy's Codex-for-sales guide.
```

## Why This Exists

AI makes execution cheaper. That is useful, but dangerous.

Founders can now build before they validate, automate before they understand, and generate sales artifacts before real customers move.

This skill forces the right split:

```text
Human founder     -> judgment, trust, taste, strategy
Claude Chat       -> reasoning, synthesis, critique
Claude Code       -> implementation, tests, automation
Claude Cowork     -> long-doc and customer-note analysis
AI-native GTM     -> pipeline briefs, account plans, meeting prep, deal diagnosis
Skills / memory   -> reusable company knowledge and workflows
```

## New: AI-Native GTM Layer

The GTM layer turns scattered customer context into reviewable action artifacts:

- pipeline prioritization from underworked accounts,
- meeting prep and follow-up,
- forecast / commit risk review,
- strategic account plan refresh,
- stalled deal diagnosis,
- partnership or BD opportunity map.

The principle is simple:

```text
Founder owns relationship strategy and judgment.
AI assembles context, drafts first-pass artifacts, separates sourced facts from inference, and creates next-step options.
```

Use it when your product has real prospects, pilots, customers, partners, sales notes, support signals, CRM exports, usage signals, or scattered account context.

## Before / After

### Input

```text
Use AI-Native Founder Orchestrator.

Context:
- Company / idea: AI tool that creates sales proposals for small B2B agencies.
- What exists today: landing page and mock screenshots.
- Evidence: 8 friendly conversations, 3 "interesting" replies, 1 demo request.
- GTM context: 18 agency prospects, 2 active pilots, 3 warm intros not followed up.
- Bottleneck: I want to start building the full app with Claude Code.

Return an AI-Native Execution Plan and GTM pack.
```

### Output

```text
Stage: Idea -> MVP / early Launch

Founder-only decisions:
- Decide which agency segment you will directly interview.
- Decide what proof counts: real data, paid pilot, or repeated workflow use.
- Decide which 2 pilots deserve personal founder attention this week.

Claude Chat:
- Break the idea into falsifiable hypotheses.
- Rank agencies by trigger, pain, stakeholder access, urgency, and next action.

Claude Code:
- Do not build the full editor yet.
- Build only a tiny demo shell or account tracker if it helps unlock customer proof.

Claude Cowork:
- Analyze interview notes and pilot notes after 5 real agency calls.

GTM / BD motion:
- Prioritize 18 agencies into focus, nurture, and park.
- Create prep briefs for 2 active pilots.
- Diagnose why 3 warm intros have stalled.

This week's artifact:
AI-native validation plan + AI-native GTM pack.

Exit criteria:
- 2 agencies agree to test with real proposal materials.
- 1 buyer names budget or paid pilot conditions.
- Every focus account has a sourced trigger and dated next action.

AI-native failure mode:
Building and selling artifacts because AI makes them cheap, while customer movement stays weak.
```

## Install

Copy this folder into your skills directory:

```text
~/.claude/skills/ai-native-founder-orchestrator/
```

or for Codex-style skill discovery:

```text
~/.codex/skills/ai-native-founder-orchestrator/
```

The skill has no backend, no API key, no package install, and no external dependency.

## Copy-Paste Prompts

### Diagnose my startup

```text
Use AI-Native Founder Orchestrator.

Context:
- Company / idea:
- Target customer:
- What exists today:
- Evidence from users:
- GTM / sales / BD context:
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
- account planning notes:

Create a domain knowledge to Skill map.
```

## Artifacts It Can Generate

- AI-native validation plan
- MVP scope document
- `CLAUDE.md`
- Claude Code implementation prompt
- AI workflow map
- AI-native GTM pack
- pipeline prioritization brief
- meeting prep and follow-up
- strategic account plan refresh
- stalled-deal diagnosis
- partnership / BD opportunity map
- founder bottleneck audit
- domain knowledge to Skill map
- weekly AI-native operating review

## Quick Start: Japanese

```text
AI-Native Founder Orchestratorを使ってください。

事業状況:
- アイデア:
- 対象顧客:
- いま存在するもの:
- 顧客から得た証拠:
- 営業 / GTM / BizDevの状況:
- ボトルネック:
- 次にやりたくなっていること:

Idea / MVP / Launch / Scale の段階判定、人間が決めること、Claude Chatに考えさせること、Claude Codeに作らせること、Claude Coworkに読ませること、GTM / BizDevでAIに任せること、今週の成果物、exit criteria、AI-native failure modeを出してください。
```

## Quick Start: Chinese

```text
请使用 AI-Native Founder Orchestrator。

创业项目情况：
- 想法：
- 目标客户：
- 现在已经有什么：
- 来自用户的证据：
- GTM / 销售 / BD 情况：
- 当前瓶颈：
- 我接下来想做的事：

请判断当前处于 Idea / MVP / Launch / Scale 哪个阶段，并拆分：
1. 创始人必须亲自决定的事
2. Claude Chat 应该推理的事
3. Claude Code / Codex 应该构建的事
4. Claude Cowork 应该阅读和整理的材料
5. GTM / 销售 / BD 中可以交给 AI 的工作
6. 本周应该产出的 artifact
7. exit criteria
8. AI-native failure mode
```

## Repo Structure

```text
ai-native-founder-orchestrator/
  SKILL.md
  agents/openai.yaml
  references/
    stage-playbooks.md
    artifact-specs.md
    gtm-sales-playbooks.md
  examples/
    idea-nontechnical-founder.md
    mvp-claude-code-builder.md
    launch-chaos-to-ai-workflows.md
    launch-ai-native-gtm-pack.md
    scale-domain-knowledge-to-skills.md
    scale-strategic-account-refresh.md
```

## Design Principles

- Protect founder judgment.
- Do not build just because AI can build.
- Do not generate sales artifacts unless there is real customer context.
- Treat AI as an operating model, not a feature.
- Build and sell with the same AI-native operating logic.
- Produce artifacts that change the next week of work.
- Always include exit criteria and failure modes.

## License

MIT
