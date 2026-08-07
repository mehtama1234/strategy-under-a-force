# Capex and Bottlenecks: The Quantified Ledger

Date baseline: 2026-08-05

> Evidence tags: **[Disclosed]** Amazon filing/call · **[Reported]** credible press · **[Estimated]** analyst/derived · **[Speculative]** inference. All figures reconcile to `sources/source-ledger.md` (source IDs like T3, P2). Most-recent quarter: **Q2 2026 (ended Jun 30, 2026)**, reported Jul 30, 2026. This file is number-forward and updated each earnings cycle (see `reports/watchlist.md`).

This report walks the bottleneck chain and attaches numbers and economics to each layer:

```text
capital  ->  chips  ->  data centers  ->  power  ->  demand conversion  ->  returns
```

## 0. The Headline: Capital

Amazon's capex is the clearest single expression of the AI bet — and it is escalating fast.

| Period | Total capex | Notes | Tag / src |
|---|---|---|---|
| FY2023 | ~$48-50B | pre-surge (capex actually fell YoY) | [Disclosed] |
| FY2024 | **~$83B** | +~57% YoY | [Disclosed] T1 |
| FY2025 | **~$131.8B** (GAAP "purchases of P&E"; ~$128.3B on a "cash capex" framing) | +~59% YoY | [Disclosed] T1 |
| FY2026 guide | **~$220B cash capex** — *raised* at Q2 2026 from ~$200B earlier in the year | Jassy: "predominantly in AWS"; increase attributed to higher memory/component prices + AI demand | [Disclosed] T3/P2/P3 |
| Q2 2026 (qtr) | **~$53.1B** | single-quarter capex | [Reported] P1 |

Management framing to hold onto, verbatim **[Disclosed, T4]**: Amazon says it is **capacity-constrained**, not demand-constrained — Jassy: *"even at [$220B] we will still not have enough capacity to meet all the demand we have in 2026, and I believe this dynamic will also be true in 2027."* That is the bull-case telltale (demand-led spend). It is also not independently falsifiable in real time, so weigh it against the hard return metrics below.

### The capital cost is now visible in cash and in depreciation
Two facts turn the capex from an abstraction into a real constraint:

- **Free cash flow turned NEGATIVE.** TTM FCF was **−$7.6B** (to Jun 30, 2026), a swing from **+$18.2B** a year earlier — the entire swing driven by capex. TTM operating cash flow was still strong at **$161.4B (+33%)**, but capex now exceeds it. **[Disclosed, T3]**
- **Amazon SHORTENED server/networking useful life from 6 to 5 years, effective Jan 1, 2025** — which *increases* depreciation and pressures margin. Estimated ~$700M FY2025 operating-income hit from the change, plus ~$920M accelerated depreciation in Q4 2024 and ~$600M more from early retirements. **[Disclosed/Reported, T1/P24]**

This second fact is important and counter-intuitive: a company trying to flatter margins would *extend* useful life. Amazon did the opposite — it took *more* depreciation — and AWS margin **still expanded** (see §5). That is a genuinely bullish signal about underlying AI-capacity economics, and it should be stated plainly.

The strategic questions remain:

```text
1. Does capex convert to REVENUE (utilized capacity) or to IDLE ASSETS?
2. Does the AI revenue/margin outrun the (now-accelerated) depreciation?
3. How long can FCF stay negative before it strains the balance sheet / buybacks?
4. Are the (shortened) useful-life assumptions still realistic if chips obsolete even faster?
```

## 1. Chips — Escaping the NVIDIA Margin (Now With Real Traction)

**The problem:** NVIDIA gross margin (~70-75% **[Reported]**) is embedded in the cost of any AI compute built on NVIDIA. Every workload Amazon moves to its own silicon removes that margin and improves its NVIDIA negotiating position.

**Amazon's silicon lines and status:**

| Line | Purpose | Status | Key claim | Tag / src |
|---|---|---|---|---|
| Graviton (Arm CPU) | General compute | **>50% of all *new* CPU capacity added to AWS runs on Graviton** (3rd straight year); 130k+ customers; Graviton5 GA (agentic-AI tuned) | Proof Amazon can ship silicon customers adopt at scale | [Disclosed] T7 |
| Inferentia2 | Inference | GA Apr 2023 | Lower-cost inference; no Inferentia3 announced (consolidating onto Trainium) | [Disclosed] |
| Trainium2 | Training | **GA Dec 3, 2024**; UltraServers | **"30-40% better price/performance"** vs comparable NVIDIA H100 EC2 instances | [Disclosed claim] T5 |
| Trainium3 | Training (next gen) | **GA Dec 2, 2025** (3nm) | ~"40% better price-performance" / "5x tokens per MW" vs Trn2 (multiplier varies 4-5x by metric) | [Disclosed/Reported] T6/P12 |
| Trainium4 | Training | **In development** | no specs/date | [Disclosed] T7 |

**The scale is now material — this is the biggest update to the thesis:**

- **Custom-silicon (chip) revenue run-rate is >$25B annually, growing triple-digit % YoY** (Jassy, Q2 2026). **[Disclosed, T4/T7]** For scale, that alone is a business bigger than many standalone semiconductor companies.
- **~1.4M Trainium chips deployed** across three generations (~early 2026). **[Reported]**
- **Third-party adoption beyond Anthropic is real:** **OpenAI committed to 2 GW of Trainium through 2027**, **Anthropic to up to 5 GW**, and **Apple** is named among customers. **[Disclosed, T7]** This is the single most important validation that Trainium is a *product*, not just an internal hedge — a competitor's frontier lab (OpenAI) contracting Amazon silicon is a strong signal.

**The moat is still Neuron.** NVIDIA's lock-in is CUDA + ecosystem; Amazon's hardest job is making the **Neuron SDK** good enough that labs/enterprises port off CUDA. Anthropic running **1M+ Trainium2 chips** in production (Project Rainier) is the flagship proof that Neuron+Trainium is production-grade at frontier scale. **[Disclosed, T9]** Caveat: Anthropic and OpenAI both run **multi-chip** strategies (Trainium + Google TPU + NVIDIA), and Anthropic disclosed (Aug 5, 2026) it is building its *own* chip team — so Trainium is winning a *share*, not exclusivity. **[Reported, P13]**

**The number that still decides the bet (undisclosed):**

```text
Trainium/Inferentia share of AWS AI compute.
AWS discloses Graviton's share of NEW CPU capacity, but NOT an AI-accelerator split.
The >$25B chip run-rate + OpenAI/Anthropic/Apple commitments strongly imply the share is rising,
but the clean percentage is not disclosed. [Unverified — biggest missing number]
```

## 2. Data Centers — Owning the Build

**The problem:** high-density AI facilities need land near power+fiber, scarce transformers/switchgear, construction labor, and (increasingly liquid) cooling. Lead times run to years.

**Amazon's position:** the largest owned/operated cloud footprint and decades of build/ops experience — an incumbency advantage precisely when *the ability to build* is the constraint. The $220B is substantially data-center shell, power infrastructure, and networking, not only chips. **Project Rainier** (New Carlisle, Indiana) is the flagship: **~1,200 acres, up to ~30 buildings, $11B Phase I** (Phase II reported ~$15B), went live Oct 2025 dedicated to Anthropic. **[Reported/Disclosed, T8/P4/P25]**

**Watch:** finance-lease additions (some data-center capacity arrives via leases and sits partly off the headline capex line — check "property and equipment acquired under finance leases").

## 3. Power — The Gating Resource, and the FERC Reality Check

**The problem:** an AI campus can need hundreds of MW to >1 GW of *firm, 24/7* power. PJM and Northern Virginia are interconnection-constrained. Firm, carbon-free, gigawatt-scale baseload is scarce — which is exactly what **nuclear** provides. But the near-term path is not clean.

**Amazon's power moves:**

| Deal / initiative | Structure | Scale | Status | Tag / src |
|---|---|---|---|---|
| Talen / Susquehanna (PA) | Bought colocated data-center campus (~$650M, Mar 2024); power in 120-MW increments | up to ~960 MW colocated | **FERC REJECTED (2-1, Nov 1, 2024)** the amended interconnection raising colocated load 300→480 MW; rehearing denied ~Apr 2025; Talen appealed to the 5th Circuit | [Reported] P8/P9 |
| X-energy (SMR) | Climate Pledge Fund anchored ~$500M Series C-1 | joint target **>5 GW** of new US nuclear **by 2039**; Xe-100 = 80 MWe/unit | Development-stage; announced Oct 16, 2024 | [Disclosed] T18 |
| Energy Northwest "Cascade" (WA) | Xe-100 SMRs near Columbia Generating Station | ~320 MW initial → up to ~960 MW; power early 2030s; construction ~2030 | Development-stage | [Disclosed/Reported] P10 |
| Dominion / North Anna (VA) | MOU to explore an SMR | ≥300 MW | MOU only (exploratory) | [Disclosed/Reported] T16/P10 |
| Renewables portfolio | PPAs/solar/wind | world's largest corporate buyer; 500+ projects | "100% matched" 2023 — a **matching (PPA/REC) claim, not 24/7 supply** | [Disclosed claim] T17 |

**Two crucial nuances:**

1. **The colocated-nuclear path hit a regulatory wall.** The **FERC rejection of the Talen/Susquehanna expansion** is the concrete proof that "just plug into a nuclear plant" is contested — the majority cited cost-shifting to other ratepayers and reliability. This is the live example of the power-execution risk. **[Reported, P8/P9]**
2. **SMRs are years out.** X-energy/Energy Northwest capacity targets the **early 2030s**. Nuclear signals strategic intent to lock scarce firm power early; it does **not** relieve the 2026-2027 bottleneck. Near-term relief comes from grid PPAs, gas, and renewables — against **active local pushback** (Loudoun County moves to pause data-center approvals; ~25 Virginia projects reportedly canceled in 2025; new VA rate class for large loads). **[Reported, P11]**

**The conversion number:**

```text
firm MW CONTRACTED vs firm MW ENERGIZED vs MW NEEDED for booked demand.
Announcements are contracted MW; revenue depends on energized MW; nuclear is mostly early-2030s.
```

## 4. Demand Conversion — Turning Capacity Into Revenue

Capacity is stranded capital unless billed. Amazon's demand anchors:

| Anchor | Role | Scale / notes | Tag / src |
|---|---|---|---|
| Anthropic | Frontier anchor tenant on Trainium | Amazon invested ~$8B by Nov 2024; **+$5B + up to $20B (Apr 2026) → ~$33B potential**; AWS "primary training/cloud provider"; **1M+ Trainium2 chips**; Project Rainier | [Disclosed] T9/P6 |
| OpenAI | Trainium customer | **2 GW of Trainium through 2027** — a rival lab on Amazon silicon | [Disclosed] T7 |
| Bedrock | Managed multi-model API | "tens of thousands" of customers; 100+ models (18 open-weight added at re:Invent 2025) | [Disclosed] T13 |
| Nova | First-party models | Nova (Dec 2024) → Nova 2 + Forge + Act (Dec 2025); "≥75% cheaper" claim; Nova Act agent "90% reliability" | [Disclosed] T10/T11 |
| Q / AgentCore / Kiro | Apps + agent infra | AgentCore 2M+ downloads; Kiro (Claude-powered) GA Nov 2025, usage 3x QoQ; Q internal savings ~$260M/yr | [Disclosed] T12/P15 |
| Rufus / Alexa+ | Consumer AI | Rufus ~$12B downstream sales, 300M+ users; Alexa+ $19.99/free-for-Prime, US-wide ~Feb 2026, Claude for complex queries | [Disclosed/Reported] P23 |

**Anthropic accounting caveat — read reported profit carefully.** Amazon's minority Anthropic stake generated **huge non-cash mark-to-market gains** as Anthropic's valuation rose: **+$15.2B in FY2025 "other income," and a ~$53.4B non-operating pre-tax gain in Q2 2026 alone**, lifting Q2 net income to ~$62.6B. These are **unrealized Level-3 marks** tied to funding-round valuations and **reverse if the valuation falls**. Strip them out to judge operating returns. **[Disclosed, T2/P7]**

## 5. Returns — Is the Capex Earning Its Cost of Capital? (So Far: Yes, With a Cash Caveat)

The whole ledger reduces to one question — and Q2 2026 gave the first strong real-data read:

| Signal | Q2 2026 reading | Interpretation |
|---|---|---|
| AWS revenue growth | **$42.2B, +36.7%** — "fastest in 18 quarters," 5th straight quarter of acceleration | Demand real and re-accelerating — bull |
| AWS operating income | **$16.6B, +~63%** YoY | Profit growing faster than revenue — bull |
| AWS operating margin | **~39%**, up ~650 bps YoY (~520 bps ex a derivative gain) | **Margin EXPANDED despite accelerated (6→5yr) depreciation** — strong bull |
| Backlog / RPO | **~$496B**, +~$132B in the quarter | Demand booked well ahead of capacity — bull [Reported, P1] |
| Chip run-rate | **>$25B, triple-digit growth** | Silicon substitution monetizing — bull |
| Free cash flow (TTM) | **−$7.6B** (from +$18.2B) | Capex now exceeds operating cash — the key risk — bear |
| Reported net income | inflated by ~$53.4B unrealized Anthropic mark | Headline "profit" overstates operating performance — caution |

**Net read:** on the *operating* metrics that matter for the thesis — growth, margin, backlog, chip revenue — Q2 2026 shows the vertical-integration bet **working**: AWS is growing faster *and* at higher margin *even while* absorbing accelerated depreciation. The **one genuine caution is cash**: FCF has turned negative, so the bet is now consuming more cash than it throws off, and reported earnings are flattered by non-cash Anthropic marks. The thesis is validating on the income statement; the risk has migrated to the cash-flow statement and the balance sheet.

## 6. The Self-Funding Check

Amazon's differentiator vs pure-play AI infra is that retail + advertising + AWS profit can fund the bet without leaning on external capital. The stress test, updated:

```text
TTM operating cash flow $161.4B (+33%)  vs  ~$220B FY2026 capex guide
  -> capex now EXCEEDS operating cash flow -> FCF negative (-$7.6B TTM)
```

So the self-funding thesis is now **strained but not broken**: operating cash is enormous and growing, but the capex has outgrown it, so Amazon is funding the gap from its balance sheet. Whether this is prudent front-loading (bull) or the start of the market's broader "AI capex vs returns" problem (bear) depends on how fast the ~$496B backlog and >$25B chip business convert the capacity to cash. Amazon is not immune to the AI-capex-return anxiety — it is now living it, just with the best operating metrics in the peer group to offset it.

---

### Reconciliation status

Reconciled to the Q2 2026 facts sheet (`sources/source-ledger.md`). Remaining unverified items to firm up: exact 10-Q RPO line (the ~$496B is call/press-sourced); the precise AI-accelerator custom-vs-NVIDIA share (undisclosed); Project Rainier's ~2.2 GW (single tracker); and the Talen 5th-Circuit appeal outcome (pending).
