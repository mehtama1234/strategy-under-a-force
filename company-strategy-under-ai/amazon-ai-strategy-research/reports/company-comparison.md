# Company Comparison: Amazon vs the Other AI-Infrastructure Players

Date baseline: 2026-08-05

> Evidence tags: **[Disclosed]** · **[Reported]** · **[Estimated]** · **[Speculative]**; **[verify]** = pending source confirmation. All figures reconcile to `sources/source-ledger.md`. The point is relative positioning on the *constraint-shift* axes, not precise league tables.

The right comparison is not "who has the best chatbot." It is **who owns which scarce inputs** of the AI era — chips, power, data centers, capital, and anchor demand — and how exposed each is to renting versus owning.

## 1. The Scorecard

| Axis | Amazon | Microsoft | Google | Meta | Oracle | NVIDIA |
|---|---|---|---|---|---|---|
| Custom training silicon | **Trainium2/3** (production, maturing) | Maia (early, behind) | **TPU** (mature, many gens) | MTIA (internal only) | None (rents) | Is the silicon |
| Custom CPU | **Graviton** (proven at scale) | Cobalt (early) | Axion (newer) | — | Ampere-based options | Grace (Arm) |
| Frontier model access | Anthropic (stake + anchor) + Nova | **OpenAI** (deep partnership) + own | **Gemini** (owns frontier lab, DeepMind) | Llama (owns, open) | Rents/partners | Sells to all |
| Cloud to sell externally | **AWS** (largest) | **Azure** (2nd, OpenAI demand) | **Google Cloud** (3rd, fast) | No (internal) | **OCI** (fast-growing) | No (sells chips) |
| Power/nuclear posture | Aggressive (Talen, X-Energy SMRs) | Aggressive (Three Mile Island/Constellation) | Aggressive (Kairos SMRs) | Large (gas + nuclear interest) | Large (co-located, Stargate) | N/A (customer of all) |
| Capex: FY2025 actual | **~$132B** | ~$100B+ FY25 | ~$91-93B | ~$72B | rising fast | spends less; harvests demand |
| Capex: 2026 guide | **~$220B** | ~$190B run-rate | **$180-205B** | **$125-145B** | huge (OCI/Stargate) | — |
| Self-funding cash engine | Ads + AWS + retail | Enterprise SW + Azure | Ads + Cloud | Ads | Enterprise SW + OCI | Chip sales (huge margin) |
| Core exposure | Cost/capacity of AI compute | Model-demand + Azure margin | Full-stack + Search disruption | Internal efficiency + ads | Backlog vs NVIDIA-margin | Demand durability + competition |

*(Capex: FY2025 actuals and 2026 guidance from filings/press/earnings, reconciled in `sources/source-ledger.md` — Amazon [Disclosed T1/T3/P2], others [Reported P19/P20/P21]. The striking fact is that all four hyperscalers roughly *doubled* capex into 2026.)*

**Cloud growth, same calendar quarter (ended Jun 30, 2026)** — the demand-capture scoreboard: **AWS ~37%** (its fastest in 18 quarters), **Azure ~40%**, **Google Cloud ~82%** **[Reported, P14]**. Read carefully: AWS is the largest base (so ~37% is more absolute dollars) and is *re-accelerating*, but Google Cloud and Azure are growing faster off smaller bases — evidence that Amazon's supply-cost strength has not (yet) translated into the fastest *demand* growth. The "Google Cloud ~82%" figure is striking and basis-dependent — flag for verification against Alphabet's own release. This is exactly the "demand capture is the contested axis" point.

## 2. The Two Most Instructive Comparisons

### Google — the sharpest "own the silicon" mirror
Google is the *only* peer with both a mature custom training chip (**TPU**, many generations, years of production) **and** a frontier lab it owns outright (**DeepMind/Gemini**). It is arguably *further along* than Amazon on training silicon and owns its model rather than taking a stake.

```text
Google:  owns the model + owns the silicon (most complete vertical stack), smaller enterprise-cloud base
Amazon:  larger enterprise cloud + Anthropic stake, but Trainium is younger than TPU
```

Read-through: If you believe "own the silicon" is the winning AI-cloud strategy, Google is the proof-of-concept and Amazon is the fast-follower with a bigger customer base. Amazon's counter is AWS's install-base breadth and switching costs, plus Anthropic as a best-in-class model without owning the lab's cost structure.

### Microsoft — the "own the demand" opposite
Microsoft bet on **demand** (OpenAI, Copilot, enterprise distribution) more than on **supply** (its Maia silicon trails Trainium and TPU). It largely rents NVIDIA to serve OpenAI-driven demand.

```text
Microsoft:  strongest model-demand + distribution; weakest custom-silicon of the big three
Amazon:     strongest-proven custom silicon (via Graviton) + power posture; model-demand layer contested
```

Read-through: The Amazon-vs-Microsoft contest is **supply-cost integration vs demand-and-distribution**. Microsoft captures more premium AI demand today; Amazon is better positioned to lower the *cost* of serving AI at scale. Whoever's weakness closes first wins the margin war.

## 3. The Others

### Meta — validates the logic, doesn't compete for AWS customers
Meta spends enormously on AI capex and builds its own **MTIA** silicon, but only for internal workloads (ads ranking, recommendations, Llama). It is not selling cloud. Meta matters to Amazon as a **competitor for the scarce inputs** (chips, power, land, talent) and as proof that even a non-cloud company finds owning silicon+power worthwhile — but not as a demand competitor for AWS.

### Oracle — the cautionary rent-the-stack archetype
Oracle (OCI) booked enormous AI backlog fast — **RPO ~$523B, of which ~54% (~$300B) is tied to a single ~5-year OpenAI/Stargate contract** **[Reported, P22]** — but largely **rents NVIDIA**. It is exactly the model Amazon is trying to avoid: revenue growth that carries NVIDIA's margin, concentrated in one counterparty, and dependent on continuous capex and leverage to sustain. Read-through: Oracle shows demand can be booked quickly, but also illustrates the return and concentration risk of scaling on rented silicon. Amazon's Trainium bet is the hedge against becoming Oracle-like at scale.

### NVIDIA — the substrate and the margin everyone is chasing or escaping
NVIDIA is upstream of all of them and captures the margin the hyperscalers pay. Its position is strongest if AI compute keeps growing regardless of *which* cloud wins. Every custom-silicon program (Trainium, TPU, Maia, MTIA) is an attempt to erode NVIDIA's pricing power. Read-through: NVIDIA data-center revenue/margin trends are a barometer for the entire thesis — softness would signal the chip bottleneck is easing and the value of Amazon's silicon bet with it; continued strength signals the bottleneck (and the prize for escaping it) is intact.

## 4. Where Amazon Wins, Loses, and Is Contested

```text
Amazon WINS on:
  - proven custom-silicon adoption (Graviton) → credibility for Trainium
  - largest owned data-center footprint (build capability in a build-constrained era)
  - self-funding via ads + AWS profit + retail cash
  - a top-tier anchor model (Anthropic) without owning the lab's full cost base

Amazon LOSES / TRAILS on:
  - training-silicon maturity vs Google's TPU
  - frontier model-demand pull vs Microsoft-OpenAI and Google-Gemini
  - it takes a stake in Anthropic rather than owning a frontier lab outright

CONTESTED:
  - power/nuclear (all three hyperscalers are aggressive; execution/regulatory risk is shared)
  - capex discipline (everyone is spending heavily; the market's return anxiety hits all of them)
  - the model layer (Nova/Bedrock must convert AWS's supply edge into demand capture)
```

## 5. The One-Line Positioning

```text
Google:     owns model + owns silicon; most complete stack, smaller cloud base
Microsoft:  owns demand (OpenAI) + distribution; weaker silicon; rents NVIDIA
Amazon:     owns cost/capacity (proven silicon + owned DCs + power) + Anthropic; must win demand capture
Meta:       owns silicon + power for itself; not a cloud seller
Oracle:     rents the stack; books backlog fast; carries NVIDIA margin + leverage
NVIDIA:     is the stack; wins on AI-compute growth regardless of cloud winner
```

Amazon's distinctive claim is **supply-cost and capacity integration at the largest cloud scale, self-funded**. Its distinctive risk is **demand capture** — turning a lower cost of AI compute into workloads that actually run on AWS (and on Trainium) rather than on Azure/OpenAI or Google/Gemini. That is the axis to watch it on, tracked quarter-to-quarter in `reports/watchlist.md`.
