# Stage Playbooks

Use this reference when the user asks for deeper stage guidance, when classification is ambiguous, or when generating a complete operating plan.

## Idea

Goal: validate whether a real problem, user, wedge, and timing exist.

Founder-only decisions:
- Which customer segment matters enough to pursue.
- Which pain is morally, strategically, or personally worth solving.
- Which conversations require trust and direct human presence.
- Whether the idea fits the founder's edge.

Claude Chat tasks:
- Break the idea into falsifiable hypotheses.
- Generate customer interview scripts.
- Map competitors, alternatives, and workarounds.
- Critique the founder's assumptions.
- Draft landing page copy only after the pain is clear.

Claude Code tasks:
- Build only tiny research utilities, landing page prototypes, survey pages, or data scrapers when needed.
- Avoid product code unless the validation artifact requires it.

Claude Cowork tasks:
- Analyze long market reports, user transcripts, call notes, or competitor docs.
- Extract patterns from interviews.

Skills / memory / workflow opportunities:
- Customer interview analysis routine.
- Competitive landscape update routine.
- Problem hypothesis log.

Common artifacts:
- AI-native validation plan.
- Interview script.
- Evidence ledger.
- Competitor/workaround map.

Exit criteria:
- Specific customer segment named.
- Clear painful workflow or economic cost identified.
- Evidence from real customers, not only founder intuition.
- A narrow MVP wedge becomes obvious.

AI-native failure mode:
- Outsourcing judgment to AI and mistaking generated plausibility for real customer truth.

## MVP

Goal: build the smallest useful product while preserving scope, architecture, security, and learning speed.

Founder-only decisions:
- Which user and use case define the MVP.
- What will not be built.
- What proof counts as meaningful use or willingness to pay.
- Which tradeoffs are acceptable.

Claude Chat tasks:
- Turn evidence into MVP requirements.
- Prioritize use cases and kill features.
- Draft scope docs, user stories, and test scenarios.
- Challenge whether building is premature.

Claude Code tasks:
- Implement the smallest working product.
- Create tests, linting, setup docs, and reproducible dev commands.
- Draft or update `CLAUDE.md`.
- Run security and technical debt reviews.

Claude Cowork tasks:
- Analyze user feedback, tickets, specs, and research notes.
- Compare MVP behavior against original hypotheses.

Skills / memory / workflow opportunities:
- Repo-specific `CLAUDE.md`.
- Product decision log.
- Reusable code review checklist.
- Customer feedback triage Skill.

Common artifacts:
- MVP scope document.
- `CLAUDE.md`.
- Claude Code implementation prompt.
- Technical debt and security checklist.

Exit criteria:
- Users can complete the core workflow.
- The MVP proves or disproves a specific hypothesis.
- At least one real user commits time, data, money, or repeated usage.
- Scope remains narrow enough to change quickly.

AI-native failure mode:
- Building because AI makes building cheap, while demand evidence stays weak.

## Launch

Goal: serve real users without letting founder attention become the operating system.

Founder-only decisions:
- Which users deserve high-touch attention.
- Which quality, trust, or brand standards cannot be automated.
- Which feedback changes strategy versus merely requests features.
- Which metrics define real traction.

Claude Chat tasks:
- Summarize feedback themes.
- Draft response templates.
- Analyze PMF signals versus hype.
- Prioritize issues and roadmap choices.

Claude Code tasks:
- Add instrumentation, support tooling, admin utilities, bug fixes, test coverage, and workflow automation.
- Build scripts or internal tools that reduce manual founder work.

Claude Cowork tasks:
- Analyze support threads, sales notes, call transcripts, bug reports, onboarding docs, and usage reports.
- Extract repeated failure patterns and customer language.

Skills / memory / workflow opportunities:
- Support triage workflow.
- Customer feedback summarizer.
- Sales call next-action extractor.
- Weekly metrics review.

Common artifacts:
- AI workflow map.
- AI-native GTM pack.
- PMF signal dashboard spec.
- Founder bottleneck audit.
- Launch operating review.

Exit criteria:
- Repeated user behavior is visible.
- Founder can see what matters without reading every raw message.
- Common operational loops are at least partly AI-assisted.
- Metrics distinguish durable usage from novelty or hype.

AI-native failure mode:
- Founder attention and GTM context become the hidden bottleneck while the product appears to be growing.

## Scale

Goal: convert repeated knowledge, decisions, and workflows into AI-usable systems before headcount becomes the default answer.

Founder-only decisions:
- Which culture, judgment, and strategy should remain human-owned.
- Which workflows are safe to automate or delegate.
- Which knowledge creates advantage.
- Which roles need humans versus AI leverage.

Claude Chat tasks:
- Design operating cadences.
- Draft policy, process, and decision frameworks.
- Identify bottlenecks and delegation opportunities.
- Red-team automation risks.

Claude Code tasks:
- Build internal tools, integrations, evals, automations, data pipelines, and repo-level Skills.
- Harden tests, access boundaries, observability, and deployment workflows.

Claude Cowork tasks:
- Read and synthesize large bodies of customer data, internal docs, support logs, product specs, training docs, and research.
- Convert tacit knowledge into structured playbooks.

Skills / memory / workflow opportunities:
- Domain Skills.
- Team onboarding Skill.
- Support and sales knowledge Skill.
- Product principles memory.
- Governance and review workflows.

Common artifacts:
- Domain knowledge to Skill map.
- Strategic account plan refresh.
- AI-native GTM pack.
- Founder bottleneck audit.
- Operating cadence.
- AI governance and review map.

Exit criteria:
- Repeated decisions are documented and reusable.
- New team members and AI agents can use the same knowledge base.
- Founder is no longer the only routing layer.
- AI workflows improve speed without degrading trust or quality.

AI-native failure mode:
- Company knowledge, account strategy, and GTM judgment remain trapped in people, chat history, and scattered docs instead of becoming AI-usable infrastructure.
