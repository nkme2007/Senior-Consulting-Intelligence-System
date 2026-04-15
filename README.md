# Senior Consulting Intelligence System

> *A senior consulting intelligence system built for leaders and teams tackling any strategic challenge — combining 11 specialist skills that work alone or chain end-to-end.*

---

## What This Is

A multi-agent AI system built on Claude that covers the **full consulting lifecycle** — from clarifying a vague brief to delivering a CFO-ready business case, a leadership narrative, or a sprint-ready execution plan.

Every output is **leadership-ready by default**: no hedging without a clear position, no analysis without a recommendation, no jargon without definition.

See examples/ for real output samples from each skill.

---

## The 11 Skills

| # | Skill | Code | Tagline |
|---|---|---|---|
| 0 | Prompt Enhancement Agent | **PEA** | From vague to valuable — in three questions |
| 1 | Executive Narrative Builder | **ENB** | Sell the decision in 60 seconds |
| 2 | Metric & KPI Architect | **MKA** | Measure what actually matters |
| 3 | Execution Breakdown Engine | **EBE** | Turn strategy into action — no ambiguity |
| 4 | Stakeholder Alignment Simulator | **SAS** | Predict resistance before it happens |
| 5 | Decision Intelligence Engine | **DIE** | Make better decisions, faster |
| 6 | Problem-to-Action | **PTA** | From root cause to sprint ticket — no gap |
| 7 | Thinking Modes | **TM** | Same problem. Different brain. |
| 8 | Competitive Intelligence Mapper | **CIM** | Know who you're fighting — and exactly how to win |
| 9 | Business Case Builder | **BCB** | Turn a good idea into an approved investment |
| 10 | Institutional Memory Reconstruction Agent | **IMRA** | Recover what the system forgot it knows |

---

## How It Works

### The Front Door — PEA

Every session begins with a simple question: *Is the context rich enough to execute, or does it need sharpening first?*

```
Context thin or vague? → Run PEA first
Context rich and clear? → Execute immediately
```

PEA asks 2–3 strategic questions — framed as provocations, not intake forms — to draw out the full picture, produce a structured Enhanced Prompt, and route to the right skill(s).

### Skill Execution

Each skill produces structured, leadership-ready outputs:

| Skill | Output |
|---|---|
| **ENB** | 3-line summary, narrative, risks + mitigation, clear ask |
| **MKA** | North Star Metric, Input/Output metrics, Leading Indicators, Tracking Cadence |
| **EBE** | Phased plan, RACI matrix, dependency map, risk register, launch checklist |
| **SAS** | Stakeholder simulation cards, meeting strategy, objection playbook |
| **DIE** | Options architecture, trade-off matrix, bias check, recommendation + first move |
| **PTA** | Problem statement, MECE cause tree, framework build, sprint/waterfall task plan |
| **TM** | Activated cognitive mode applied across all subsequent skill outputs |
| **CIM** | Landscape map, competitor cards, battlecard, differentiation analysis, strategic recs |
| **BCB** | Investment summary, financial model (ROI/TCI), scenario analysis, risk register |
| **IMRA** | Design intent reconstruction, drift analysis, sacred vs. accidental rules, change-safe levers |

---

## Skill Chains

The real power of this system is how skills compound. Use any skill alone or chain them for complex initiatives.

### Full Initiative Chain
*New project or strategy from scratch*
```
PEA → DIE → MKA → EBE → SAS → ENB
Clarify → Decide → Measure → Plan → Align → Communicate
```

### Leadership Pitch Chain
*Need exec approval*
```
PEA → DIE → BCB → ENB → SAS
Clarify → Structure decision → Prove numbers → Build narrative → Simulate room
```

### Problem First Chain
*Messy situation, no clear path*
```
PEA → PTA → DIE → PTA → EBE
Clarify → Diagnose → Decide → Task it → Execute
```

### Market Entry / Competitive Chain
*New market or rivalry*
```
CIM → DIE → BCB → ENB
Map the landscape → Strategic call → Justify investment → Sell it
```

### Institutional Foundation Chain
*Unknown or inherited system*
```
IMRA → DIE → EBE
Reconstruct reality → Informed decision → Execute with clarity
```

### Budget Approval Chain
*Finance gate to clear*
```
BCB → ENB → SAS
Build financial case → Executive narrative → Pre-wire stakeholders
```

### M&A Integration Chain
*Inheriting another org's systems*
```
IMRA → SAS → DIE → BCB → TM
Reconstruct → Simulate stakeholders → Choose approach → Build case → Apply cognitive lens
```

### New Leader Onboarding Chain
*Inheriting a team or function*
```
IMRA → MKA → ENB
Understand what you've inherited → Define success → Communicate your intent
```

> See [CHAINS.md](chains/CHAINS.md) for the complete chain library with 15+ sequences.

---

## Thinking Modes — The Multiplier

**TM** can be activated alongside any skill at any time. It changes how the output is framed — not what it covers.

| Mode Combination | What it produces |
|---|---|
| McKinsey Mode + ENB | Pyramid-structured executive narrative |
| CFO Mode + BCB | ROI-first case with payback period leading |
| Startup Mode + EBE | Lean plan with riskiest assumption validation |
| VC Mode + CIM | Competitive moat and market timing framing |
| McKinsey Mode + IMRA | Hypothesis-led reconstruction with MECE drift map |
| B2B PM Mode + SAS | Stakeholder map split by economic buyer vs. end user |

---

## Behaviour Standards

- **Always state which skill(s) are running** at the top of every response. Example: `Running: CIM + BCB | Mode: CFO`
- **Always produce a recommendation.** Never end with "it depends" without naming what it depends on and stating a position.
- **Show handoffs explicitly** when chaining skills.
- **Maintain Thinking Modes** consistently throughout — never drift back to generic.
- **Never produce generic output.** Every output is grounded in the user's specific context.
- **Proactively flag** when a different skill would serve better than the one requested.

---

## Quick Reference — Trigger Phrases

| What you say | What runs |
|---|---|
| "Help me with / I need / Sort this out" | PEA first |
| "Sell this / pitch this / get buy-in" | ENB |
| "KPIs / metrics / OKRs / North Star" | MKA |
| "Project plan / roadmap / who owns what" | EBE |
| "Stakeholder prep / who will push back" | SAS |
| "Help me decide / options / trade-offs" | DIE |
| "Root cause / which framework / sprint tasks" | PTA |
| "Think like / mode / lens / act as" | TM |
| "Competitors / differentiation / competitive analysis" | CIM |
| "Business case / ROI / budget / CFO" | BCB |
| "Why this way / institutional memory / what broke" | IMRA |
| "Full chain / end-to-end / the whole thing" | PEA → DIE+MKA+EBE+SAS+ENB |

---

## Applicability

Applicable across **any industry, function, or organisation**:
- Strategy & transformation
- Product management
- Finance & investment
- M&A integration
- Organisational design
- Technology & digital
- Sales & GTM
- Governance & compliance

---

## Repository Structure

```
senior-consulting-intelligence-system/
│
├── README.md                    ← This file
├── PROJECT_INSTRUCTIONS.md      ← Full system prompt for Claude project
│
├── agents/
│   ├── 00_PEA.md               ← Prompt Enhancement Agent
│   ├── 01_ENB.md               ← Executive Narrative Builder
│   ├── 02_MKA.md               ← Metric & KPI Architect
│   ├── 03_EBE.md               ← Execution Breakdown Engine
│   ├── 04_SAS.md               ← Stakeholder Alignment Simulator
│   ├── 05_DIE.md               ← Decision Intelligence Engine
│   ├── 06_PTA.md               ← Problem-to-Action
│   ├── 07_TM.md                ← Thinking Modes
│   ├── 08_CIM.md               ← Competitive Intelligence Mapper
│   ├── 09_BCB.md               ← Business Case Builder
│   └── 10_IMRA.md              ← Institutional Memory Reconstruction Agent
│
├── chains/
│   ├─── CHAINS.md               ← Complete chain library with 15+ sequences
├── CONTRIBUTING.md         ← How to contribute
├── LICENSE                 ← MIT License
├── examples/
│   └── EXAMPLE_OUTPUTS.md  ← Real output examples per skill
```

---

## Built By

**Nithin** — Program Manager & AI Product Manager, Cognizant Technology Solutions

*Built using Claude (Anthropic) as the AI foundation.*
