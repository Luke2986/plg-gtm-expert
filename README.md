# PLG & GTM Expert — Claude AI Skill

A custom skill for Claude that turns it into a senior Product-Led Growth and Go-To-Market strategist.

Structured discovery, situational framework selection, and actionable deliverables tied to measurable outcomes. Works for any product, market, and team size.

## What this skill does

The skill operates in two modes:

1. **Discovery & Analysis** — A structured 15-question process that builds a complete picture of product, market, business model, constraints, and goals before making any recommendation. One question at a time, no batching, no skipping.

2. **Strategy & Deliverable generation** — Selects the right framework for the situation, explains why, presents alternatives with tradeoffs, and produces deliverables in the format the user chooses.

## Frameworks included

### PLG strategy
PLG Funnel mapping, Bowling Alley (Wes Bush), Time to Value, AHA Moment identification, Hook Model (Nir Eyal), Progressive Commitment, Growth Loops (viral, usage-based, referral, UGC, collaboration, partner), Network Effects, Marketing Tools strategy, Trial mode selection, PQL/PQA model, Churn analysis, Expansion playbook.

### GTM strategy
GTM Power System (Big Plan + Strategic Foundation + Execution Plan), 16-step GTM process, Status Quo + Why it's Broken, POV (Point of View), Dream State, Trade-offs, ECP (Early Customer Profile), Use Case validation, JTBD, STP + segment scoring, Crossing the Chasm, Bullseye Framework, Messaging architecture (Fletch PMM), Strategic narrative.

### Pricing & monetization
Van Westendorp PSM, Value-Based Pricing, Paywall placement strategy, Pricing page optimization.

### Metrics
AARRR funnel analysis, North Star + input metrics, Cohort analysis, Unit economics (CAC, LTV, payback), PLG-specific metrics catalog for acquisition, activation, conversion, retention, expansion, and churn.

## Reference files

The `references/` folder contains detailed documentation for each domain:

| File | Content |
|------|---------|
| `plg-framework.md` | PLG funnel, onboarding, AHA Moment, activation, retention, churn, expansion, team structure, tech stack |
| `gtm-framework.md` | GTM strategy process, Big Plan, Strategic Foundation, research methods, positioning, messaging, launch execution |
| `metrics-toolkit.md` | Complete metrics catalog organized by funnel stage |
| `templates.md` | Ready-to-use templates: discovery summary, GTM Power System, use case validation, positioning, messaging architecture, tactics & experiments, segment scoring, PLG readiness assessment |

## How to use it

This is a [Claude custom skill](https://docs.claude.com). To use it:

1. Clone or download this repo
2. Add the skill to your Claude configuration
3. Start a conversation about any PLG or GTM topic

The skill activates when you ask about growth strategy, GTM planning, PLG, acquisition funnels, retention, monetization, pricing, competitive positioning, launch planning, channel strategy, metrics, or any related topic.

It responds in the language you write in.

## Design principles

- **No improvisation.** If context is missing, the skill asks before recommending.
- **Framework selection is situational.** No defaults by popularity. The right framework depends on the problem.
- **Metrics drive everything.** No strategy without measurable outcomes.
- **Context over theory.** Every recommendation calibrates to actual constraints: budget, team, technical capability, market.
- **No generic advice.** No "best practices" disconnected from the user's situation.

## Structure

```
plg-gtm-expert/
├── SKILL.md                          # Main skill prompt
└── references/
    ├── plg-framework.md              # PLG strategy reference
    ├── gtm-framework.md              # GTM strategy reference
    ├── metrics-toolkit.md            # Metrics catalog
    └── templates.md                  # Deliverable templates
```

## License

MIT
