# Example Outputs

> Real examples of what each skill produces — using anonymised, illustrative scenarios.
> Every output shown here meets the system's quality bar: leadership-ready, with a clear recommendation.

---

## PEA — Prompt Enhancement Agent

**Input:**
> "Help me with the quarterly review."

**PEA Response:**
> Three quick things before I build this:
>
> **1.** Who's in the room — is this a performance review with your team, a business review with leadership, or a board-level update?
>
> **2.** Is the goal to communicate results, or to get a decision or budget approved?
>
> **3.** What's the one thing you need people to walk out having agreed to or understood?

**Enhanced Prompt Produced:**
```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
ENHANCED PROMPT — READY FOR SKILL EXECUTION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
WHAT:         Q3 business performance review for the digital transformation programme
FOR WHOM:     Executive committee (CFO, COO, CEO) — results-focused, time-pressured
GOAL:         Communicate Q3 results and secure Q4 budget release
THE ASK:      Approve £2.4M Q4 budget tranche based on Q3 delivery
CONSTRAINTS:  15-minute slot; CFO has flagged cost concerns in prior meetings
STAKES:       Q4 budget delay pushes launch by 6 months
KNOWN RISKS:  CFO likely to challenge ROI timeline; COO may question resource plan
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
ROUTING TO: ENB + SAS
RATIONALE:   Leadership communication with known resistance → narrative + stakeholder simulation
```

---

## ENB — Executive Narrative Builder

**Running:** `ENB | Mode: CFO`

**Input:** Q3 digital transformation review seeking Q4 budget approval

**Output:**

**3-LINE SUMMARY**
> Digital transformation is on track: Q3 delivered 94% of committed milestones, £1.8M under budget, with customer satisfaction up 12 points. Q4 is the go-live quarter — the £2.4M tranche funds the final three workstreams with a confirmed payback period of 14 months. The risk of not approving is a 6-month delay costing £4.1M in deferred benefit.

**STRUCTURED NARRATIVE**

*Recommendation:* Approve the Q4 £2.4M budget tranche to complete the digital transformation programme on schedule.

*Rationale:*
- Q3 performance exceeded plan on delivery (94% milestone completion) and came in under budget
- The three remaining Q4 workstreams are sequenced with clear ownership and no unresolved dependencies
- The business case remains intact: 14-month payback, £8.2M NPV over 3 years

*Evidence:*
- 12-point NPS improvement in pilot markets validates the customer experience investment
- Integration testing completed with zero critical defects
- All regulatory sign-offs received ahead of schedule

**RISKS + MITIGATION**
| Risk | Mitigation |
|---|---|
| CFO challenges ROI timeline | Sensitivity analysis shows 14-month payback holds even at 20% benefit underperformance |
| Resource availability in Q4 | Bench capacity confirmed; 3 contractors already contracted |
| Scope creep in final workstreams | Change freeze in place from week 6 of Q4 |

**THE ASK**
> Approve £2.4M Q4 budget release. Decision needed by [date] to maintain launch schedule.

---

## DIE — Decision Intelligence Engine

**Running:** `DIE`

**Input:** "We can't decide whether to build our AI capability in-house or buy a platform."

**Output:**

**PROBLEM CLARITY FRAME**
> The real decision is not build vs. buy — it is: *what level of AI capability differentiation do we need, and how quickly?* Build offers control and differentiation; buy offers speed and reduced risk. The answer depends on whether AI is a competitive differentiator or an operational enabler for this organisation.

**OPTIONS ARCHITECTURE**
1. **Build in-house** — dedicated team, full IP ownership, 18-24 month runway
2. **Buy a platform** — 3rd-party vendor, faster deployment, dependency risk
3. **Partner + build** — platform for speed now, in-house capability for differentiation later
4. **Do nothing** — defer decision by 6 months pending market clarity

**TRADE-OFF MATRIX**
| Criterion | Weight | Build | Buy | Partner+Build |
|---|---|---|---|---|
| Speed to value | 30% | 2/5 | 5/5 | 4/5 |
| Cost (3-year) | 25% | 3/5 | 4/5 | 3/5 |
| Differentiation | 25% | 5/5 | 2/5 | 4/5 |
| Risk | 20% | 3/5 | 4/5 | 4/5 |
| **Weighted score** | | **3.25** | **3.75** | **3.80** |

**COGNITIVE BIAS CHECK**
- ⚠️ *Not-invented-here bias* — check if "build" preference is driven by engineering culture rather than strategic need
- ⚠️ *Status quo bias* — "do nothing" is rarely neutral; delay has a cost

**RECOMMENDATION**
> **Partner + Build.** Deploy a platform to generate value in months 1–12 while building in-house capability in parallel for the differentiating use cases. This is not a compromise — it is a sequenced strategy that buys time without sacrificing long-term differentiation.
>
> **First move:** Issue an RFP to 3 shortlisted vendors within 2 weeks, in parallel with defining the in-house capability roadmap.

---

## SAS — Stakeholder Alignment Simulator

**Running:** `SAS`

**Input:** Presenting a new operating model to executive committee next Thursday

**Output (excerpt):**

**STAKEHOLDER SIMULATION CARD — CFO**
| | |
|---|---|
| **Surface objection** | "The cost projections look optimistic — what's the sensitivity analysis?" |
| **Hidden agenda** | Concerned about headcount implications before the annual budget cycle locks |
| **Response strategy** | Lead with the sensitivity analysis unprompted. Show the worst-case scenario holds. Address headcount separately — frame as reallocation, not addition. |

**STAKEHOLDER SIMULATION CARD — COO**
| | |
|---|---|
| **Surface objection** | "How does this affect day-to-day operations during transition?" |
| **Hidden agenda** | Worried about being held accountable for delivery risk without sufficient resource |
| **Response strategy** | Provide a transition timeline with clear operational continuity commitments. Name the transition lead. Give COO a visible governance role. |

**MEETING STRATEGY**
> Pre-wire the CFO 48 hours before the meeting with the financial model. The COO needs a private briefing — not because they'll oppose publicly, but because surprise in the room will read as lack of preparation. Start the presentation with operational continuity, not the org chart.

---

## BCB — Business Case Builder

**Running:** `BCB | Mode: CFO`

**Input:** Justify investment in an AI-powered skills assessment tool

**Output (summary excerpt):**

**3-LINE CFO TEST**
> Total investment: £1.2M over 18 months. Projected annual benefit: £3.4M (productivity recovery + reduced external assessment cost). Payback: 13 months. NPV at 3 years: £6.8M.

**INVESTMENT SUMMARY**
| | |
|---|---|
| **Total Cost of Investment** | £1.2M (Year 1: £800K, Year 2: £400K) |
| **Annual Benefit (steady state)** | £3.4M |
| **ROI** | 183% |
| **Payback period** | 13 months |
| **NPV (3-year, 10% discount)** | £6.8M |

**SCENARIO ANALYSIS**
| Scenario | Assumption | NPV |
|---|---|---|
| Base case | 80% adoption, benefits as modelled | £6.8M |
| Conservative | 60% adoption, 20% benefit haircut | £4.1M |
| Worst case | 40% adoption, 35% benefit haircut | £1.9M |

> *Even in the worst case, the investment returns positive NPV.*

---

## IMRA — Institutional Memory Reconstruction Agent

**Running:** `IMRA | Mode: McKinsey`

**Input:** "Why does our vendor approval process take 6 weeks? Everyone works around it."

**Output (excerpt):**

**TRUE OPTIMISATION TARGET**
> The process is not optimising for speed or quality — it is optimising for *audit defensibility*. Every 6-week step exists because of a historical audit finding, not a current business need.

**ORIGINAL DESIGN INTENT (RECONSTRUCTED)**
> The process was designed in 2019 following a procurement audit that found 3 instances of unapproved vendor spend. The 6-week timeline was set to accommodate a monthly Finance sign-off cycle, not because 6 weeks was operationally necessary.

**DRIFT ANALYSIS**
> Since 2019: Finance sign-off moved to weekly (2021), removing the original reason for the monthly cycle. The 6-week timeline was never updated. Two additional approval layers were added in 2022 (post-acquisition) and never removed after integration completed.

**SACRED VS. ACCIDENTAL RULES**
| Rule | Type | Reason |
|---|---|---|
| Legal review for contracts >£50K | **Sacred** | Regulatory requirement |
| Finance sign-off | **Sacred** | Audit requirement |
| 4-week standard processing time | **Accidental** | Legacy of monthly cycle — no longer needed |
| Secondary procurement review | **Accidental** | Post-acquisition addition — integration complete |

**CHANGE-SAFE LEVER MAP**
> Removing the 4-week processing time and secondary procurement review reduces the process to ~10 days with zero regulatory or audit risk. Expected resistance: Procurement team (loss of control); Finance (habit). Neither objection is substantive.

---

## TM — Thinking Modes

**Running:** `TM | Mode: McKinsey` applied to a restructuring decision

> *Output framing shifts to: hypothesis-led, MECE structure, pyramid logic, issue tree before recommendation.*

**Running:** `TM | Mode: CFO` applied to the same decision

> *Output framing shifts to: ROI-first, payback period leads, sensitivity analysis prominent, headcount as cost per FTE.*

*The underlying analysis is identical. The cognitive lens changes what leads, what's prominent, and how trade-offs are framed.*

---

*More examples will be added as the system is used in real consulting contexts. Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).*
