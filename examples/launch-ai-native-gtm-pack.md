# Example: Launch-stage AI-native GTM pack

## User prompt

```text
Use AI-Native Founder Orchestrator.

We are in Launch stage.
Product: AI proposal generator for boutique agencies.
Inputs:
- 18 agencies on a spreadsheet
- 6 discovery calls
- 2 active pilots
- 3 warm intros not followed up
- founder notes in docs
- no CRM yet

Create an AI-native GTM pack with pipeline prioritization, meeting prep, stalled-deal diagnosis, account next actions, and founder-only sales decisions.
Separate sourced facts from inferred opportunity.
```

## Expected output style

```text
Stage: Launch

GTM motion:
Founder-led early sales with pilots, warm intros, and scattered account context.

Source material provided:
- account spreadsheet
- discovery call notes
- pilot notes
- founder docs

Missing source material:
- exact pilot success metrics
- decision-maker names
- budgets or paid pilot conditions
- next meeting dates

Founder-only sales / BD decisions:
- Decide which 2 pilots deserve personal attention this week.
- Decide what proof converts a pilot into paid use.
- Decide whether the wedge is proposal speed, proposal quality, or win-rate improvement.

Claude Chat tasks:
- Rank 18 agencies by trigger, pain, stakeholder access, urgency, and likely next action.
- Turn call notes into account hypotheses and discovery gaps.
- Draft a three-touch follow-up sequence for warm intros.

Claude Code tasks:
- Create a lightweight account tracker from the spreadsheet.
- Add fields for trigger, stage, next action, owner, last contact, and proof needed.
- Generate a simple import/export format so GTM review is repeatable.

Claude Cowork tasks:
- Read discovery notes and founder docs.
- Extract repeated objections, buying triggers, and customer language.

Skills / memory / workflow opportunities:
- Early sales review Skill.
- Account brief generator.
- Pilot-to-paid conversion checklist.

GTM artifacts:
1. Pipeline prioritization: rank 18 agencies into focus, nurture, park.
2. Meeting prep: prep briefs for the 2 pilots.
3. Stalled deal diagnosis: inspect the 3 warm intros with no follow-up.
4. Account next actions: one next step per focus account.

Next account actions:
- Pilot A: schedule paid conversion call and define success metric.
- Pilot B: request real proposal data and confirm buyer.
- Warm intro group: send founder-written reactivation note with one clear ask.

AI-native GTM failure mode:
Failure: pipeline looks active because AI generated briefs, not because customers moved.
Countermeasure this week: every account must have a sourced trigger and a dated next action.
```
