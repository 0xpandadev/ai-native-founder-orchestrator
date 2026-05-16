# Example: MVP-stage Claude Code builder

## User prompt

```text
Use AI-Native Founder Orchestrator.

We are in MVP stage.
Product: AI support agent for Shopify stores.
Current state: one pilot store, early repo, working chat widget, no tests, no admin panel.
Evidence: store owner wants to test FAQ automation for 2 weeks.
Concern: Claude Code can build fast, but scope is expanding.

Create my MVP scope document and CLAUDE.md.
```

## Expected output style

```text
Stage: MVP

Why this stage:
There is one real pilot and a working early product, but the MVP has not yet proven durable use, payment, or safe operation.

Founder-only decisions:
- Decide whether the MVP is FAQ deflection, order-status support, or sales assistance. Pick one.
- Decide what risk is unacceptable for the pilot store.
- Decide what evidence after 2 weeks counts as success.

Claude Chat tasks:
- Convert pilot goals into must-build and must-not-build requirements.
- Draft success metrics: deflection rate, owner time saved, wrong-answer rate, customer satisfaction.
- Red-team the scope for hidden complexity.

Claude Code tasks:
- Add tests around FAQ retrieval, fallback behavior, and answer refusal.
- Implement only the pilot workflow.
- Create setup commands and update CLAUDE.md.
- Add logging for unresolved questions and wrong-answer review.

Claude Cowork tasks:
- Review store FAQs, prior support tickets, product pages, and policy docs.
- Extract answer boundaries and escalation rules.

Skills / memory / workflow opportunities:
- Store-specific support policy memory.
- Support answer review checklist.

This week's artifact:
MVP scope document + CLAUDE.md.

Exit criteria:
- Pilot store runs the widget for 2 weeks.
- Owner confirms time saved.
- Wrong-answer rate stays within agreed threshold.
- At least one workflow is clearly worth paying for.

AI-native failure mode:
Failure: shipping a broad agent that sounds impressive but cannot be trusted.
Countermeasure this week: define refusal, escalation, and review boundaries before adding features.
```
