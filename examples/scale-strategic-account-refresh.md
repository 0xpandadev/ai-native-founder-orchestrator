# Example: Scale-stage strategic account refresh

## User prompt

```text
Use AI-Native Founder Orchestrator.

We are in Scale stage.
Product: compliance automation for healthcare clinics.
Situation:
- 14 paying clinics
- 3 expansion opportunities
- onboarding and renewal knowledge lives in expert notes
- sales calls, support issues, and account plans are scattered
- founder wants a current account strategy for top accounts

Create strategic account plan refreshes and identify what should become Skills or memory.
```

## Expected output style

```text
Stage: Scale

Why this stage:
There is repeatable demand and paying customers. The bottleneck is now account strategy, expansion repeatability, and domain knowledge reuse.

Founder-only decisions:
- Decide which accounts are strategic versus merely large.
- Decide which compliance judgments require human review.
- Decide whether expansion should be product-led, expert-led, or partner-led.

Claude Chat tasks:
- Compare account context against expansion criteria.
- Identify discovery gaps, objections, and next-best actions.
- Draft strategic account plans for the top 3 expansion opportunities.

Claude Code tasks:
- Build a structured account plan template or internal account-plan generator.
- Create tests or fixtures for any automated document review workflow.
- Add exportable account review packets if the team reviews accounts weekly.

Claude Cowork tasks:
- Read sales calls, support issues, renewal notes, account plans, and expert corrections.
- Extract stakeholder maps, risks, repeated objections, and proof points.

Skills / memory / workflow opportunities:
- Strategic account plan refresh Skill.
- Compliance exception triage Skill.
- Renewal risk review memory.
- Expansion objection library.

This week's artifact:
Strategic account plan refresh for the top 3 accounts + domain knowledge to Skill map.

Exit criteria:
- Each top account has a sourced stakeholder map, value hypothesis, open risk, next action, and owner.
- Repeated expert knowledge is converted into at least one Skill spec.
- Expansion next actions are reviewable without the founder reading every raw note.

AI-native failure mode:
Failure: account strategy remains trapped in experts and scattered notes, so scale requires more headcount before better systems.
Countermeasure this week: convert one repeated account review motion into a Skill with trigger, inputs, workflow, output, and validation.
```
