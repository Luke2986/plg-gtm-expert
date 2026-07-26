# PLG & GTM Expert — Claude AI Skill

A custom skill for Claude that turns it into a senior Product-Led Growth and Go-To-Market strategist.

Structured discovery, situational framework selection, and actionable deliverables tied to measurable outcomes. Works for any product, market, and team size.

## What this skill does

The skill operates in two modes:

1. **Discovery & Analysis** — A structured 15-question process that builds a complete picture of product, market, business model, constraints, and goals before making any recommendation. One question at a time, no batching, no skipping.

2. **Strategy & Deliverable generation** — Selects the right framework for the situation, explains why, presents alternatives with tradeoffs, and produces deliverables in the format the user chooses.

## Frameworks included

### PLG strategy
PLG Funnel mapping, PLG Readiness Checklist, Bowling Alley (Wes Bush), Time to Value, AHA Moment identification, Hook Model (Nir Eyal), Progressive Commitment, Growth Loops (viral, usage-based, referral, UGC, collaboration, partner), Network Effects, Marketing Tools strategy, Trial mode selection, PQL/PQA model, Churn analysis, Expansion playbook.

### GTM strategy
GTM Power System (Big Plan + Strategic Foundation + Execution Plan), 16-step GTM process, Status Quo + Why it's Broken, POV (Point of View), Dream State, Trade-offs, ECP (Early Customer Profile), Anti-ICP, B2B persona structure (User/Champion/Buyer), Use Case validation, JTBD, STP + segment scoring, Crossing the Chasm, Bullseye Framework, Competitive Intelligence + win/loss analysis, 4 positioning strategies × market maturity, 5 differentiation angles, Capability→Feature→Benefit triplet, Messaging architecture (Fletch PMM), strategic narrative.

### Pricing & monetization
Four failure modes (Feature Shock, Minivation, Hidden Gem, Undead), the WTP talk with 5 question types, WTP segmentation, configuration & bundling (Leaders/Fillers/Killers), five monetization models, pricing strategy selection (maximization/penetration/skimming), WTP-based business case, value communication + MOCA, six behavioral pricing tactics, price integrity, Van Westendorp PSM, Gabor-Granger, conjoint analysis, Value-Based Pricing, plus PLG pricing operations: value metric typology, CAC + Cost-to-Serve, feature placement scenarios, paywall placement and pricing-page optimization.

### Sales enablement
5 sales enablement pillars, external vs internal asset taxonomy, Sales Deck 8-section structure, One-Pager design, Battlecard 5-block structure, sales enablement metrics — for B2B and Product-Led Sales motions.

### Digital channels & content
See-Think-Do-Care (Kaushik), SEO + Topic Cluster (Fishkin), AEO — Answer Engine Optimization (LLM discovery), Content Pyramid (Vaynerchuk) + They Ask You Answer (Sheridan), Permission Marketing (Godin) + Email/Newsletter/DEM, Creator & Influencer marketing + Cialdini levers, Full-Funnel Advertising, Brand vs Activation 60/40 (Binet & Field).

### Metrics
AARRR funnel analysis, North Star + input metrics, Cohort analysis, Unit economics (CAC, LTV, payback), PLG-specific metrics catalog for acquisition, activation, conversion, retention, expansion, and churn.

## Reference files

The `references/` folder contains detailed documentation for each domain:

| File | Content |
|------|---------|
| `plg-framework.md` | PLG funnel, onboarding, AHA Moment, activation, retention, churn, expansion, team structure, tech stack |
| `gtm-framework.md` | GTM strategy process, Big Plan, Strategic Foundation (incl. Anti-ICP, User/Champion/Buyer personas), research + Competitive Intelligence, positioning (market maturity, differentiation angles, Capability→Feature→Benefit), messaging, launch execution |
| `digital-channels.md` | Channel-level acquisition & content: See-Think-Do-Care, SEO/GEO, AEO, Content Pyramid, Permission/Email & newsletter, Creator marketing, Full-Funnel ADV, Brand vs Activation |
| `pricing-framework.md` | Full pricing & monetization framework: four failure modes, the WTP talk + segmentation, bundling, monetization models, pricing strategy selection, value communication + MOCA, behavioral tactics, price integrity, and the statistical WTP research layer (Van Westendorp, Gabor-Granger, conjoint, value-based) |
| `pricing-toolkit.md` | PLG pricing operations that complement the framework: value metric typology, CAC + Cost-to-Serve, feature-placement scenarios, paywall & pricing-page tactics |
| `sales-enablement.md` | 5 enablement pillars, asset taxonomy, sales deck, one-pager, battlecard, enablement metrics |
| `metrics-toolkit.md` | Complete metrics catalog organized by funnel stage |
| `templates.md` | Ready-to-use templates: discovery summary, GTM Power System, use case validation, positioning, messaging architecture, tactics & experiments, segment scoring, PLG readiness assessment |

## How to use it

This is a [Claude custom skill](https://docs.claude.com). To use it:

1. Clone or download this repo
2. Add the skill to your Claude configuration
3. Start a conversation about any PLG or GTM topic

The skill activates when you ask about growth strategy, GTM planning, PLG, acquisition funnels, retention, monetization, pricing, packaging, competitive positioning, launch planning, channel strategy, SEO/AEO, content and email marketing, sales enablement, metrics, or any related topic.

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
    ├── digital-channels.md           # Acquisition channels & content
    ├── pricing-framework.md          # Pricing & monetization framework
    ├── pricing-toolkit.md            # PLG pricing operations
    ├── sales-enablement.md           # B2B / PLS sales enablement
    ├── metrics-toolkit.md            # Metrics catalog
    └── templates.md                  # Deliverable templates
```
## Why this exists

I built this skill to run growth and GTM decisions on my own product, Forfettino, a live SaaS for Italian flat-rate freelancers. Everything here comes from work I actually do: the discovery structure is the one I use with users, and the frameworks are the ones I apply, not a survey of the literature.

## License

MIT
