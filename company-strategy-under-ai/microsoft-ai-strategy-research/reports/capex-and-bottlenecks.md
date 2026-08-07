# Capex and Bottlenecks: The Quantified Ledger

Date baseline: 2026-08-05

> Evidence tags: **[Disclosed]** · **[Reported]** · **[Estimated]** · **[Speculative]**. Reconciles to `sources/source-ledger.md` and `sources/raw-facts-sheet.md`. MSFT FY ends June 30 (FY26 Q1 = Jul-Sep 2025 … Q4 = Apr-Jun 2026). Number-forward; updated each earnings cycle (see `reports/watchlist.md`).

Microsoft's bottleneck profile is the **mirror image of Amazon's**. Amazon's binding risk migrated to *capital* (negative free cash flow); Microsoft's capital position is healthier, but its binding risks are **power** ("warm shells") and **supply cost** (heavy NVIDIA rent + a trailing own-silicon program). This ledger walks the chain:

```text
capital  ->  silicon (NVIDIA rent + Maia)  ->  data centers  ->  power  ->  demand conversion  ->  returns
```

## 0. Capital — Big, But Still Self-Funding

| Measure | FY2024 | FY2025 | FY2026 | Tag |
|---|---|---|---|---|
| Cash capex (P&E additions) | $44.5B | $64.6B (+45%) | **$115.9B (+~80%)** | [Disclosed] |
| Operating cash flow | $118.5B | $136.2B | **$182.9B** | [Disclosed] |
| Free cash flow | — | — | **≈ $67B (positive)** | [Estimated/Reported] |
| Depreciation & amortization | $22.3B | $34.2B (+53%) | $38.5B | [Disclosed] |

Forward: **CY2026 capex guided ~$190B, later trimmed to ~$175B** (the trim driven by a useful-life accounting change, not a demand change); **Q1 FY27 capex "over $50B"**; FY27 "grows YoY." **[Disclosed]**

**Two things distinguish Microsoft's capital story from Amazon's:**

1. **It is still free-cash-flow positive (~$67B FY26).** Microsoft's cash capex ($116B) is large but comfortably below its operating cash flow ($183B). Contrast Amazon, whose ~$220B capex pushed TTM FCF *negative*. Microsoft is spending heavily but not out-spending its cash generation. **[Estimated from Disclosed lines]**
2. **It EXTENDED asset useful lives (15→25 yrs) in Q4 FY26** — the *opposite* of Amazon (which shortened server life 6→5 yrs). Extending lives *slows* depreciation growth and *flatters* future margin. Microsoft says the FY27 operating-income benefit is "minimal," but the direction matters: **Amazon took a depreciation headwind; Microsoft took a tailwind.** Watch whether 25-year lives are realistic for AI-era buildings/infrastructure, or whether they defer a future write-down. **[Disclosed]**

**Composition:** *"roughly two-thirds of capex was for short-lived assets, primarily CPUs and GPUs"* (repeated Q2-Q4 FY26). So the majority of Microsoft's AI capex is **chips** — and, given weak own-silicon (§1), a large share of that is **NVIDIA**. There is no disclosed standalone "AI-only" capex figure. **[Disclosed / flagged]**

**Trajectory is demand-led — and re-accelerated.** In May 2025 CFO Amy Hood guided FY26 capex to "grow at a lower rate than FY25." By Oct 2025 she **reversed** it: "we now expect the FY26 growth rate to be higher than FY25," citing accelerating demand and rising backlog. The moderation narrative flipped back to acceleration. **[Disclosed]**

## 1. Silicon — Microsoft's Weakest Layer (Heavy NVIDIA Rent)

This is where Microsoft is most exposed versus Amazon and Google.

| Chip | Role | Status | Tag |
|---|---|---|---|
| Maia 100 | AI accelerator (1st gen) | Nov 2023; Microsoft was **last of the big-4** to field one | [Reported] |
| **Maia 200** ("Braga") | Inference accelerator | Unveiled Jan 2026 (3nm, 216GB HBM3e, **inference-only**); **mass production slipped 2025→2026**, partly from OpenAI-requested design changes + staff turnover | [Disclosed / Reported] |
| Cobalt 100 / 200 | Arm CPU | Cobalt 100 GA 2024; Cobalt 200 announced Ignite 2025, GA 2026 | [Disclosed] |

**The exposure, quantified:** analyst models put 2026 custom-accelerator volumes at roughly **~900k Google TPU, ~600k AWS Trainium, ~250k Microsoft Maia** **[Estimated — no primary source]**. Maia is the *smallest* of the three and *inference-only*, so Microsoft **rents NVIDIA at scale** for training and much inference:

- The **GB300 NVL72** cluster on Azure (Oct 2025) — the world's first large-scale production GB300 deployment, **>4,600 Blackwell Ultra GPUs**, built **for OpenAI**, targeting "hundreds of thousands" of GPUs. **[Disclosed]**
- Continued NVIDIA roadmap dependence (planning for "large-scale Rubin deployments"); **AMD MI300X** in production for Azure OpenAI Service. **[Disclosed]**

**First-principles consequence:** NVIDIA's ~70-75% gross margin is embedded in more of Microsoft's AI cost of goods than in Amazon's or Google's. Microsoft has **less of the silicon cost-escape** that Trainium/TPU give its rivals. Its AI margin must therefore be defended from the **demand side** (charging more via distribution) rather than the **supply side** (paying less via own silicon). Maia's marketing claims (e.g. "3× Trainium3 FP4") are **not independently benchmarked** — treat as marketing until verified. **[flagged]**

## 2. Data Centers — Building Fast

- **88 new data centers brought online in FY26** (31 in Q4 alone, across 5 continents); **~1 GW added per fiscal quarter** (~4 GW in FY26); "on track to roughly double overall capacity in two years." **[Disclosed]**
- Flagship **Fairwater (Wisconsin)** AI data center scaling to **2 GW**, linked to Atlanta via an "AI WAN" into an "AI superfactory." **[Disclosed]**

Microsoft is not build-constrained on shells the way it is power-constrained (below); its construction machine is formidable.

## 3. Power — The Binding Near-Term Constraint ("Warm Shells")

Microsoft's own executives named power, not chips, as the binding limit:

> Nadella (Nov 2025): *"you may actually have a bunch of chips sitting in inventory that I can't plug in… It's not a supply issue of chips; it's the fact that I don't have **warm shells** to plug into."* **[Disclosed]**
> Hood (Q1 FY26): *"capacity constrained through at least the end of our fiscal year, with demand exceeding current infrastructure build-out, resulting in **lost revenue** opportunities for Azure."* **[Disclosed]**

That is management explicitly saying AI revenue is being *left on the table* for lack of powered capacity. Microsoft's power moves:

| Deal | Type | Scale | Status | Tag |
|---|---|---|---|---|
| Constellation "Crane Clean Energy Center" (Three Mile Island Unit 1) | Nuclear **restart**, 20-yr PPA | **835 MW** | Restart **accelerated to 2027** (from 2028); ~$1.6B; NRC license to 2054 | [Disclosed/Reported] |
| Helion | **Fusion** PPA (world's first) | 50 MW+ | Target 2028 — commercial fusion unproven | [Disclosed / Speculative on delivery] |
| Renewables portfolio | PPAs (Brookfield >10.5 GW framework) | **34 GW** carbon-free contracted (official); 40+ GW per later press | Ongoing; largest-scale corporate procurement | [Disclosed / Reported] |
| SMRs | — | — | **No signed SMR PPA verified** (exploring only) | [Unverified] |

**Note the contrast with Amazon:** Amazon's marquee nuclear play (Talen colocation) hit a **FERC rejection**; Microsoft's marquee play (restarting an existing licensed reactor via a straight PPA) is a *cleaner* regulatory path and was *accelerated* a year early. Microsoft's nuclear posture is arguably lower-risk, though still ~2027+ and small relative to need. Near-term, power remains the gating constraint.

## 4. Demand Conversion — Strong, and Contracted Ahead

Microsoft's demand signal is unusually strong and well-documented:

- **Azure grew +40% (FY26 Q1)**, guided +37% cc for Q2; **Azure crossed $100B annual revenue** by Q4 FY26. **[Disclosed]**
- **Commercial RPO (backlog) $392B, +51% YoY** (FY26 Q1) — demand booked far ahead of capacity. **[Disclosed]**
- **Microsoft Cloud revenue $49.1B/qtr, +26%**, but **Microsoft Cloud gross margin ~68%, down YoY on AI investment** — the margin pressure from AI is visible. **[Disclosed]**
- Demand anchors that convert capacity to revenue: **OpenAI's $250B Azure commitment**, **Anthropic's $30B Azure commitment** (Nov 2025), plus the Copilot/Foundry demand engine (`business-model-map.md`).

## 5. Returns — Healthier Capital, but Margin Is the Watch Item

| Signal | Reading | Interpretation |
|---|---|---|
| Free cash flow | **~$67B positive (FY26)** | Self-funding intact — better than Amazon's negative FCF — bull |
| Useful-life change | **Extended 15→25 yrs** | Slows depreciation, flatters future margin — bull (but watch realism) |
| Azure growth + backlog | **+40%, RPO $392B (+51%)** | Demand booked far ahead — bull |
| Microsoft Cloud gross margin | **~68%, down YoY on AI** | AI is diluting cloud margin — the key watch item — caution |
| Silicon | Maia trails, inference-only; NVIDIA rent heavy | Less supply-cost offset than rivals — bear on unit cost |
| OpenAI equity-method | recurring loss share (−$3.1B Q1 FY26) | A recurring drag on reported EPS — caution (see `openai-relationship.md`) |

**Net read:** Microsoft's *capital* story is healthier than Amazon's — still FCF-positive, with a depreciation *tailwind* from life extension. But its *unit-cost* story is weaker: it pays market rates for NVIDIA with little silicon offset, and its cloud gross margin is being diluted by AI. So the return question for Microsoft is not "can it afford the capex" (it can, for now) but "can it hold margin while paying full price for compute and carrying the OpenAI drag" — i.e., whether the **demand-side** advantage (Copilot attach, Azure pricing) out-earns the **supply-side** disadvantage.

## 6. The Self-Funding Check

```text
Operating cash flow $182.9B (+34%)  vs  ~$116B cash capex (~$175B CY2026 guide incl. leases)
  -> free cash flow still POSITIVE (~$67B FY26)
```

Microsoft can sustain its buildout from internal cash — a genuine advantage over both neoclouds and (currently) Amazon. The tension is not solvency; it is **margin quality**: the majority of capex is short-lived NVIDIA silicon, cloud gross margin is drifting down on AI, and the OpenAI loss share adds noise. Microsoft is funding the bet comfortably; the open question is how *profitable* the bet is per dollar of compute it rents.

---

### Reconciliation status

Reconciled to the Q4-FY26 facts sheet (`sources/raw-facts-sheet.md`). Unverified items carried forward: no standalone AI-only capex $; FY26 FCF ~$67B is derived (not a filing line); Maia perf claims unbenchmarked; 2026 silicon volumes are analyst estimates; FY26 Q3/Q4 Azure quarterly growth % not pinned (only Q1 +40% actual, Q2 +37% cc guide, and "Azure >$100B annual" by Q4); Crane restart 2027 (accelerated) vs 2028 (original).
