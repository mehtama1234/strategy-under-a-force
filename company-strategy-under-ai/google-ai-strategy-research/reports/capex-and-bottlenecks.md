# Capex and Bottlenecks: The Quantified Ledger (Google)

Date baseline: 2026-08-05

> Evidence tags: **[Disclosed]** Alphabet filing/call · **[Reported]** press · **[Estimated]** analyst/derived · **[Speculative]** inference · **[verify]** pending confirmation. All figures reconcile to `sources/source-ledger.md` (IDs like G-T2, G-P1). Most-recent quarter: **Q2 2026 (ended Jun 30, 2026)**. Many 2026 figures are **[verify]** — assembled from prior-quarter guidance + press, not directly retrieved from the Q2 2026 release. This file is number-forward and updated each earnings cycle (see `reports/watchlist.md`).

Google's bottleneck chain differs from Amazon's in one decisive way: Google largely **owns Layer 1 already** (mature TPU), so its scarce inputs are less "escape NVIDIA's margin" and more **power, capital, and the monetization race on Search**:

```text
capital -> chips (TPU, largely SOLVED) -> data centers -> power -> demand conversion (Cloud)
        -> the OFFSET RACE: does new AI profit outgrow Search-monetization erosion?
```

## 0. The Headline: Capital

Alphabet's capex is stepping up sharply into the AI era — later and (historically) lower than Amazon's, now accelerating hard.

| Period | Capex | Notes | Tag / src |
|---|---|---|---|
| FY2024 | **~$52.5B** | the pre-surge base | [Disclosed] G-T1 |
| FY2025 | **~$91-93B** | ~+75% YoY — the step-up year | [Disclosed] G-T1 |
| FY2026 guide | **"significant increase"** — sibling dossier cites a **~$180-205B** range | flagged on the Q3 2025 call; predominantly servers (TPU + some NVIDIA) + data centers | [Reported] G-P1/G-P2 [verify] |
| Q2 2026 (qtr) | (per release) | AI-server + data-center weighted | [Disclosed] G-T2 [verify] |

Management framing to hold onto: like Amazon, Google says it is **capacity/demand-constrained on Cloud** — it has more committed Cloud demand (backlog) than capacity, which is the stated justification for the capex step-up. **[Disclosed, G-T3, verify]** That is the bull telltale (demand-led spend), but — as with Amazon — it is not independently falsifiable in real time; weigh it against Cloud margin and backlog (§4).

### The capital difference vs Amazon
Two structural cushions make Google's capex less alarming than the raw number:

- **A larger, higher-margin cash engine.** Search + YouTube ads + a now-profitable Cloud throw off enormous operating cash, so Alphabet is expected to fund the step-up while staying **free-cash-flow positive** (unlike Amazon, whose TTM FCF went negative). The capex is large but well-covered. **[Estimated, verify]**
- **TPU means less of the spend leaks to NVIDIA's margin.** A large share of Google's AI servers are its own TPU, so more of each capex dollar builds an owned, cost-advantaged asset rather than renting NVIDIA at ~70-75% gross margin. This is the payoff of the mature-silicon position.

The strategic questions:

```text
1. Does the capex convert to CLOUD REVENUE (utilized, backlog-backed) or to idle capacity?
2. Does Cloud operating margin keep RISING as AI depreciation ramps? (the return test)
3. Does the spend stay FCF-covered by the ad + cloud cash engine?
4. Is TPU keeping enough of the spend off NVIDIA's margin to matter?
```

## 1. Chips — TPU: The Bottleneck Google Largely Already Solved

**The problem others face:** NVIDIA's ~70-75% gross margin **[Reported]** is embedded in any AI compute built on NVIDIA. **Google's position:** it has shipped custom AI silicon (**TPU**) since the mid-2010s and trains/serves its own frontier workloads (Search, Gemini, YouTube) on it — so it escapes that margin more completely than any rival.

| Line | Purpose | Status | Key point | Tag / src |
|---|---|---|---|---|
| **TPU v7 "Ironwood"** | Inference-optimized (also training) | Current external-facing gen; large pod scale | The generation Google is scaling for the inference era | [Disclosed] G-T4 |
| **TPU v6 "Trillium"** | Training + inference | Prior workhorse | Efficiency/perf-per-watt gains | [Disclosed] G-T5 |
| **Axion** | Custom Arm server CPU | Shipping | General-compute analog to Amazon Graviton | [Disclosed] G-T13 |
| NVIDIA GPUs | Offered in Cloud for customers who want CUDA | Available on GCP | Google still *sells* NVIDIA to customers who require it | [Disclosed] |

**The external-validation milestone (the biggest chip update):**

```text
Anthropic committed to access UP TO ~1 MILLION TPUs, with >1 GW of capacity coming online in 2026,
in a deal reported "worth tens of billions of dollars." [G-T6/G-P3, verify]
```

This is the TPU analog of Trainium's OpenAI win: a leading frontier lab contracting Google silicon at gigawatt scale is the strongest possible proof that TPU + its software stack (XLA/JAX) is production-grade *for external customers*, not just internally. Caveat: Anthropic is **multi-silicon** (also Amazon Trainium + NVIDIA), so TPU is winning a large *share*, not exclusivity.

**The number that would clinch it (undisclosed):** Google does not break out TPU-vs-NVIDIA mix or external-TPU revenue inside Cloud. The cost-advantage claim is structural/inferred, not a disclosed line. **[Unverified]**

## 2. Data Centers — Owning The Build

Google operates a global owned data-center fleet and decades of build/ops experience — incumbency in an era where the ability to *build* is a constraint. Much of the ~$180-205B [verify] is data-center shell, power infrastructure, and networking, not only chips. The AI era pushes toward higher-density, liquid-cooled facilities co-located with firm power (§3).

## 3. Power — The Gating Resource

Like every hyperscaler, Google's binding physical constraint is **firm, 24/7 power** for AI campuses. Its portfolio leans into clean-firm sources:

| Deal / initiative | Type | Scale | Timeline | Tag / src |
|---|---|---|---|---|
| **Kairos Power** SMRs | Advanced nuclear offtake | ~**500 MW** by 2035; first unit ~2030 | Early-2030s | [Disclosed] G-T10 |
| **Commonwealth Fusion Systems** | Fusion PPA (ARC, Virginia) | ~**200 MW** offtake | Early-2030s (first-of-kind) | [Disclosed] G-T11 |
| **Fervo / enhanced geothermal** | Geothermal PPAs | Multiple projects | Nearer-term than nuclear/fusion | [Disclosed] G-T12 |
| Renewables portfolio | PPAs (solar/wind) | Large corporate buyer | Ongoing | [Disclosed] |

**Two nuances (identical in spirit to Amazon's):**

1. **Nuclear/fusion are early-2030s.** Kairos and CFS signal intent to lock scarce firm power early; they do **not** relieve the 2026-2027 bottleneck. Near-term relief comes from grid PPAs, geothermal, and renewables.
2. **Fusion is a first-of-a-kind bet.** The CFS PPA is a genuine differentiator (first corporate fusion offtake) but carries first-of-kind execution risk — signal, not near-term supply.

```text
The conversion number: firm MW CONTRACTED vs ENERGIZED vs NEEDED for booked Cloud demand.
Nuclear/fusion are mostly early-2030s; geothermal + renewables + grid carry 2026-2027.
```

## 4. Demand Conversion — Cloud As The Return Test

Capacity is stranded capital unless billed. Google's demand engine is **Google Cloud**, and it is where the full-stack advantage must show up as profit:

| Signal | Reading (Q2 2026) | Interpretation |
|---|---|---|
| Google Cloud revenue growth | ~**30-34%** [G-P7, verify] — **NOT the "~82%"** figure in the Amazon dossier (basis-dependent/likely erroneous) | Fast growth off the 3rd-largest base — bull |
| Google Cloud operating margin | Profitable and **rising** [G-T2, verify] | The offset engine is earning, not just growing — bull |
| Cloud backlog / RPO | **~$100B+** and rising [G-P8, verify] | Demand booked ahead of capacity — bull |
| External TPU adoption | Anthropic up to ~1M TPUs [G-T6] | Silicon monetizing externally — bull |
| Capex vs FCF | Capex stepping up sharply, **still FCF-positive** [Estimated, verify] | Well-covered by ad + cloud cash — vs Amazon's negative FCF — relative bull |

**Net read:** Cloud is doing the job the thesis needs — growing fast, turning *profitable*, and differentiated by cheap TPU. The one number to correct loudly is the **"~82% Google Cloud growth"** cited in the sibling Amazon dossier: it is **not reconciled to Alphabet's release** and is treated here as basis-dependent/likely a mis-citation. The defensible figure is the **~30-34%** range. Firming this up is the single most important reconciliation item (see `sources/source-ledger.md`).

## 5. The Return Test — Is The Capex Earning Its Cost Of Capital?

Google's version of Amazon's return question, with a friendlier cash profile:

```text
Google's edge vs Amazon on capital:
  - larger, higher-margin cash engine (Search + YouTube + profitable Cloud) -> stays FCF-positive
  - TPU keeps more of the spend off NVIDIA's margin -> better unit economics per capex dollar
Google's disadvantage vs Amazon on capital:
  - the SAME capex funds an engine (Cloud) that must ALSO offset possible Search erosion -
    so the bar is higher: Cloud isn't just a growth story, it's the INSURANCE against the core.
```

The capex is coherent *because* Cloud is profitable and TPU-differentiated. The risk is the industry-wide one: if AI-cloud demand digests, a ~$180-205B [verify] annual run-rate becomes depreciation that outruns revenue. Google enters that risk with the best cash cushion of the three — but also with the unique obligation that this very engine must cover its own core's disruption (see `reports/search-disruption.md`).

## 6. The Self-Funding Check

```text
Search + YouTube ad cash + profitable Cloud  ->  fund ~$180-205B FY2026 capex [verify]
  -> expected to remain FREE-CASH-FLOW POSITIVE (the key contrast with Amazon's negative FCF)
```

So Google's self-funding thesis is **stronger than Amazon's**: the cash engines are larger relative to the capex, and TPU improves the return on each dollar. The catch is not affordability — it is *allocation*: Google is spending record sums on the very Cloud engine it needs to both grow *and* insure Search. Whether that spend earns its cost of capital depends on Cloud margin holding as depreciation ramps — tracked in `reports/watchlist.md`.

---

### Reconciliation status

Assembled from FY2025 actuals + Q3-2025 capex language + press. Items to firm up against the Q2 2026 release: exact 2026 capex guide (the ~$180-205B is sibling/press-sourced), **Google Cloud growth % (the "~82%" must be corrected/verified — biggest item)**, Cloud operating margin and backlog exact figures, and whether FCF stayed positive through the capex ramp.
