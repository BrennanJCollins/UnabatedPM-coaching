# Unabated PM Coaching

**27 AI coaching skills that teach you to think like a senior PM.** Not templates that fill in blanks. Coaching that pushes back on your thinking, scores your work, and shows you exactly where it breaks down.

Built from coaching 500+ product managers. 36+ promotions. 4.9/5 course rating on Maven.

## What You Get

Most AI "PM tools" apply a framework like a checklist. These skills coach you through it the way a VP of Product would — with scoring rubrics, real coaching exchanges, error correction, and pushback on weak reasoning. They detect your level and adjust.

27 individual skills across four areas, plus 5 guided workflows that chain skills together for complete coaching sessions.

## How to Use These Skills

### Claude Desktop (Cowork)

Install the plugin from the [Cowork plugin marketplace](https://unabatedproducts.com/ai-tools). Once installed, all 27 skills activate automatically based on what you ask. You can also run any of the five guided workflows as slash commands:

- `/coach-strategy` — Build your vision, pressure-test your strategy, prepare for stakeholder pushback
- `/coach-business-case` — Connect metrics to outcomes, calculate unit economics, translate to P&L
- `/coach-pitch` — Craft your story, compress to 60 seconds, practice under pressure
- `/coach-job-search` — Redesign your resume, narrow your niche, simulate interviews
- `/coach-career-pivot` — Map your background to PM, channel impostor syndrome, plan your first 90 days

### ChatGPT, Gemini, Claude Web, or Any AI Chat

Each skill is a standalone file you can use with any AI tool. Here's how:

1. Browse the skill folders in this repo (organized by category below)
2. Open the `SKILL.md` file for the skill you want
3. Copy the entire contents
4. Paste it into your AI tool as a custom instruction, system prompt, or at the start of a new conversation
5. Add your own context where it says `[Paste your context here]` and start the coaching session

That's it. No installation, no configuration. The skill turns any AI into your PM coach for that topic.

### Claude Code (CLI)

Add the plugin directly from this repo:

```
claude plugin add https://github.com/BrennanJCollins/unabated-pm-coaching
```

All skills and commands will be available immediately.

## Skills by Category

### Strategic Thinking

| Skill | What It Coaches |
|---|---|
| [Order Taker to Outcome Owner](pm-strategic-thinking/skills/order-taker-to-outcome-owner/SKILL.md) | Stop executing tasks. Start owning outcomes. |
| [Four Pillars Check](pm-strategic-thinking/skills/four-pillars-check/SKILL.md) | Score yourself across Strategy, Delivery, CX, and Growth. Find your blind spots. |
| [Vision Synthesis](pm-strategic-thinking/skills/vision-synthesis/SKILL.md) | Build a product vision using the Vision Triangle that passes 4 quality tests. |
| [Strategy Articulation](pm-strategic-thinking/skills/strategy-articulation/SKILL.md) | Pressure-test your strategy with 5 Questions + the DHM Filter. |
| [Stakeholder Request Reframe](pm-strategic-thinking/skills/stakeholder-request-reframe/SKILL.md) | Turn "build this feature" demands into strategic conversations. |
| [AI Career Impact Advisor](pm-strategic-thinking/skills/ai-career-impact-advisor/SKILL.md) | Navigate AI's impact on your PM career with positioning strategy. |

### Business Building

| Skill | What It Coaches |
|---|---|
| [Product Metrics Ladder](pm-business-building/skills/product-metrics-ladder/SKILL.md) | Connect features to business outcomes. Stop pitching vanity metrics. |
| [User-Buyer Bridge](pm-business-building/skills/user-buyer-bridge/SKILL.md) | Translate what users need into what buyers will pay for. |
| [Business Model Canvas](pm-business-building/skills/business-model-canvas/SKILL.md) | Stress-test your business model with real unit economics. |
| [Product Objective Definition](pm-business-building/skills/product-objective-definition/SKILL.md) | Define objectives that drive decisions, not just decorate OKR slides. |
| [Unit Economics Calculator](pm-business-building/skills/unit-economics-calculator/SKILL.md) | Build CAC, LTV, and LTV:CAC models that survive CFO scrutiny. |
| [P&L Translation](pm-business-building/skills/pnl-translation/SKILL.md) | Speak the language of finance. Map product impact to P&L lines. |
| [Bridge Builder](pm-business-building/skills/bridge-builder/SKILL.md) | Connect user jobs to buyer economics through a 5-level bridge. |
| [ROI Calculator Builder](pm-business-building/skills/roi-calculator-builder/SKILL.md) | Build ROI models using Good/Better/Best that pass the 10X Rule. |

### Stakeholder & Customer Influence

| Skill | What It Coaches |
|---|---|
| [Interview Question Design](pm-influence/skills/interview-question-design/SKILL.md) | Design questions that uncover real problems, not confirmation bias. |
| [Journey Map Economic Overlay](pm-influence/skills/journey-map-economic-overlay/SKILL.md) | Turn journey maps from process diagrams into economic stories. |
| [Demo Script Reviewer](pm-influence/skills/demo-script-reviewer/SKILL.md) | Stop touring features. Start closing deals. Five-Act Demo Structure. |
| [Strategic Storytelling Pitch](pm-influence/skills/strategic-storytelling-pitch/SKILL.md) | Transform forgettable pitches into stories that get to "yes." |
| [Cafe Update](pm-influence/skills/cafe-update/SKILL.md) | Compress your impact into 60 seconds that land a follow-up meeting. |
| [Confidence Scenario Simulator](pm-influence/skills/confidence-scenario-simulator/SKILL.md) | Practice high-stakes conversations with realistic pushback. |
| [First 90 Days Playbook](pm-influence/skills/first-90-days-playbook/SKILL.md) | Build influence in a new role by absorbing before directing. |

### Career Growth

| Skill | What It Coaches |
|---|---|
| [Resume as Product](pm-career-growth/skills/resume-as-product-coach/SKILL.md) | Treat your resume as a conversion funnel, not a biography. |
| [PM Interview Coach](pm-career-growth/skills/pm-interview-coach/SKILL.md) | Practice interviews as conversations, not rehearsed STAR performances. |
| [Niche Job Search Strategist](pm-career-growth/skills/niche-job-search-strategist/SKILL.md) | Fewer applications, better results. Run your search like a product launch. |
| [Career Transition Navigator](pm-career-growth/skills/career-transition-navigator/SKILL.md) | Map your non-PM background onto the Four Pillars. You already have 3 of 4. |
| [Impostor to Strategist](pm-career-growth/skills/impostor-to-strategist/SKILL.md) | Convert impostor syndrome into a career development strategy. |
| [Offer Negotiation Playbook](pm-career-growth/skills/offer-negotiation-playbook/SKILL.md) | Negotiate with leverage and total comp analysis, not emotion. |

## Guided Workflows

These chain 3 skills together into a complete coaching session. Available as slash commands in Claude Desktop and Claude Code, or paste the workflow file into any AI tool.

| Workflow | What It Does | Skills Used |
|---|---|---|
| [Coach Strategy](pm-strategic-thinking/commands/coach-strategy.md) | End-to-end strategy development | Vision Synthesis, Strategy Articulation, Stakeholder Reframe |
| [Coach Business Case](pm-business-building/commands/coach-business-case.md) | Build a business case that gets funded | Metrics Ladder, Unit Economics, P&L Translation |
| [Coach Pitch](pm-influence/commands/coach-pitch.md) | Craft and deliver a compelling pitch | Strategic Storytelling, Cafe Update, Confidence Simulator |
| [Coach Job Search](pm-career-growth/commands/coach-job-search.md) | Full job search preparation | Resume Design, Niche Search, Interview Simulation |
| [Coach Career Pivot](pm-career-growth/commands/coach-career-pivot.md) | Transition into product management | Career Mapping, Impostor Strategy, First 90 Days |

## Quick Example

Here's what a coaching session looks like. You provide context, the skill coaches you through the framework:

```
I'm a PM at a B2B analytics platform. My VP asked me to "build a mobile app
because customers keep requesting it." I need to respond strategically
instead of just saying yes.
```

The **Stakeholder Request Reframe** skill will:
1. Identify that you're about to be an order-taker
2. Coach you to ask "what's the underlying need?"
3. Help you generate multiple solutions to that need
4. Guide you to evaluate which solution serves your strategy
5. Give you a reframe script you can actually use in the meeting

No generic advice. Specific coaching with scoring, pushback, and iteration until your response is strong.

## The Proof

500+ PMs coached. 36+ promotions within 6 months. 4.9/5 course rating on Maven. Used by PMs from startups to Fortune 500.

These skills encode 15+ years of product leadership into coaching frameworks that actually push your thinking — not textbook theory repackaged as AI prompts.

## About

Created by [Brennan Collins](https://unabatedproducts.com), founder of Unabated Products and creator of [The Influential PM](https://maven.com/unabated-products/the-influential-pm) course on Maven.

## License

MIT — use these skills however you want. If they help you grow as a PM, that's the goal.
