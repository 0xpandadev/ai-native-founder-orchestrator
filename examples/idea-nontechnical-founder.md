# Example: Idea-stage nontechnical founder

## User prompt

```text
Use AI-Native Founder Orchestrator.

Context:
- Company / idea: AI tool that creates sales proposals for small B2B agencies.
- Target customer: boutique agencies with 5-30 people.
- What exists today: landing page, mock screenshots, no product.
- Evidence from users: 8 friendly conversations; 3 people said "interesting"; 1 asked for a demo.
- Current bottleneck: I want to start building the app with Claude Code.
- What I am tempted to do next: build the full proposal editor.

Return an AI-Native Execution Plan.
```

## Expected output style

```text
Stage: Idea -> MVP

Why this stage:
You have conversation interest and one demo request, but no proof that agencies will provide real proposal data, change their workflow, or pay.

Founder-only decisions:
- Decide which agency segment you will personally interview first.
- Decide what proof counts: data access, paid pilot, repeated use, or signed pilot.
- Decide whether this problem is strategic enough to pursue beyond "AI can generate proposals."

Claude Chat tasks:
- Turn the idea into 5 falsifiable hypotheses.
- Draft interview questions focused on current proposal workflow, cost, urgency, and payment authority.
- Generate a competitor/workaround map.

Claude Code tasks:
- Do not build the full editor yet.
- If needed, build a tiny demo shell that accepts one brief and returns a static generated proposal.

Claude Cowork tasks:
- Analyze interview notes after at least 5 real agency calls.
- Extract repeated language, objections, and buying triggers.

Skills / memory / workflow opportunities:
- Create a reusable customer interview analysis routine after the first batch of interviews.

This week's artifact:
AI-native validation plan.

Exit criteria:
- At least 2 agencies agree to test with real proposal materials.
- At least 1 buyer names a concrete budget or paid pilot condition.
- The must-have workflow is narrow enough to prototype in one week.

AI-native failure mode:
Failure: building because Claude Code makes building feel cheap.
Countermeasure this week: no product code until the founder completes 5 problem interviews or receives real customer data.
```
