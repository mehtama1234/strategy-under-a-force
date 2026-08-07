# Company Comparison: Google vs the Other AI Players

Date baseline: 2026-08-05

> Evidence tags: **[Disclosed]** · **[Reported]** · **[Estimated]** · **[Speculative]**; **[verify]** = pending confirmation. Figures reconcile to `sources/source-ledger.md`. The point is relative positioning on the AI axes — *supply, demand, and core-business risk* — not precise league tables. This mirrors the Amazon dossier's scorecard, re-centered on Google.

The right comparison is not "who has the best chatbot." It is **who owns which layers of the AI stack**, and — the Google-specific axis — **whose existing business AI threatens versus augments**.

## 1. The Scorecard

| Axis | Google | Amazon | Microsoft | Meta | Oracle | NVIDIA |
|---|---|---|---|---|---|---|
| Custom training silicon | **TPU** (most mature, many gens) | Trainium2/3 (production, maturing) | Maia (early, behind) | MTIA (internal only) | None (rents) | Is the silicon |
| Custom CPU | Axion (Arm) | **Graviton** (proven at scale) | Cobalt (early) | — | — | Grace (Arm) |
| Frontier model | **Gemini — OWNS it (DeepMind)** | Anthropic (stake) + Nova | **OpenAI** (partner) + own MAI | Llama (owns, open) | Rents/partners | Sells to all |
| Cloud to sell externally | **Google Cloud** (3rd, profitable, fast) | **AWS** (largest) | **Azure** (2nd, OpenAI demand) | No (internal) | **OCI** (fast, rents NVIDIA) | No |
| Owns model **AND** silicon | **YES — the only one** | stake-in-model + own silicon | partner-model + weak silicon | own model + own silicon (internal) | neither | is the silicon |
| Power/nuclear posture | Kairos SMR + CFS fusion + Fervo | Talen + X-Energy SMRs | Three Mile Island/Constellation | gas + nuclear interest | co-located, Stargate | N/A |
| Capex: FY2025 actual | ~**$91-93B** | ~**$132B** | ~$100B+ | ~$72B | rising fast | harvests demand |
| Capex: 2026 guide | ~**$180-205B** [verify] | ~**$220B** | ~$190B run-rate | ~$125-145B | huge (Stargate) | — |
| Self-funding cash engine | **Search + YouTube ads + profitable Cloud** | Ads + AWS + retail | Enterprise SW + Azure | Ads | Enterprise SW + OCI | Chip margin |
| **Core-business AI risk** | **HIGH — Search ads is what AI disrupts** | Low (AI augments the store) | Low (AI augments productivity) | Low-Med (AI augments ads) | Low | Low (AI *is* demand) |
| Free cash flow under capex | **positive** [Estimated, verify] | **negative** (−$7.6B TTM) | positive | positive | strained (leverage) | very positive |

*(Capex actuals/guides from filings + press, reconciled in `sources/source-ledger.md`; the striking fact is all four hyperscalers roughly doubled capex into 2026. Note Google's ~$180-205B 2026 guide is sibling/press-sourced and **[verify]**.)*

**The one row that defines Google:** every peer's existing business is *augmented* by AI; only Google's core (**Search advertising**) is directly *threatened* by it. That is Google's distinctive risk — and the reason it also carries the distinctive asset (owning the whole stack to manage the transition).

## 2. The Two Most Instructive Comparisons

### Amazon — the "own the silicon" sibling, one step behind
Amazon is the closest mirror of Google's *supply* strategy: both build custom AI silicon to escape NVIDIA. But:

```text
Google:  owns the MODEL (Gemini) + the SILICON (TPU, more mature) - co-designs them together; FCF-positive
Amazon:  takes a STAKE in the model (Anthropic) + owns younger silicon (Trainium); FCF now negative
```

Read-through: If "own the silicon" is the winning AI-cloud strategy, **Google is the proof-of-concept and Amazon is the fast-follower** — Google is further along on training silicon and owns its model outright, while Amazon has the larger enterprise-cloud install base. Google's counter-risk (Search) is unique; Amazon's (cash/capital) is more conventional.

### Microsoft — the "own the demand" opposite
Microsoft bet on demand (OpenAI, Copilot, enterprise distribution) more than supply (Maia trails TPU and Trainium; it rents NVIDIA heavily).

```text
Microsoft:  strongest model-DEMAND + distribution; weakest silicon; depends on a partner (OpenAI)
Google:     strongest SUPPLY (TPU) + owns its own model; must defend a threatened core (Search)
```

Read-through: Microsoft captures more premium AI *demand* today and has no Search-style core risk; Google owns a cheaper *supply* and its own model but must out-earn its own disruption. Microsoft's risk is margin/dependence; Google's is cannibalization.

## 3. The Others

### OpenAI + Anthropic — customers and competitors at once
The labs are a two-faced comparison for Google. **Anthropic is now a major TPU customer** (up to ~1M TPUs) — validating Google's silicon — *while* Claude and ChatGPT are the consumer answer-engines that threaten Search and that AI Mode/Gemini must beat. Read-through: Google both *sells to* and *competes with* the frontier labs. No lab is single-sourced (Anthropic runs TPU + Trainium + NVIDIA), so TPU wins share, not lock-in.

### Meta — validates own-silicon, no Search-style risk
Meta spends enormously and builds MTIA, but internal-only (ads ranking, Llama) — not a cloud seller. Its core (ads feed) is *augmented* by AI, not disrupted. Read-through: Meta competes with Google for the scarce inputs (chips, power, talent) and in the ad market, but not for Cloud customers, and it doesn't share Google's cannibalization dilemma.

### Oracle — the rent-the-stack cautionary tale
OCI booked enormous AI backlog fast but largely **rents NVIDIA**, concentrated in a huge OpenAI/Stargate contract. Read-through: Oracle is the opposite of Google's model — backlog carried on rented, NVIDIA-margin silicon with leverage and counterparty concentration. Google's TPU is precisely the asset that avoids becoming Oracle-like at scale.

### NVIDIA — the margin Google escapes most completely
Google serves its own frontier workloads on TPU, so it escapes NVIDIA's margin more fully than any rival while *also reselling* NVIDIA to Cloud customers who want CUDA. Read-through: NVIDIA data-center trends are a barometer for the whole thesis; TPU is Google's hedge against paying that margin at scale.

## 4. Where Google Wins, Loses, and Is Contested

```text
Google WINS on:
  - the ONLY complete self-owned stack (model + silicon + cloud + research)
  - the co-design loop (Gemini + TPU) - the deepest efficiency moat in AI
  - TPU maturity + external validation (Anthropic up to ~1M TPUs)
  - a profitable, FCF-positive model (best cash cushion of the three)
  - DeepMind - the deepest research lab (AlphaFold Nobel, IMO-gold math, world models)

Google LOSES / TRAILS on:
  - Cloud is still 3rd by size (AWS, Azure ahead)
  - enterprise AI-demand pull vs Microsoft-OpenAI's distribution
  - a UNIQUE core-business exposure no rival has (Search ads = the AI-disruption target)

CONTESTED:
  - Gemini's frontier standing vs GPT/Claude (leadership shifts monthly)
  - power/nuclear/fusion execution (all hyperscalers aggressive; timelines early-2030s)
  - capex discipline (everyone is spending; return anxiety hits all)
  - whether AI-native Search monetizes at ~the old rate (the crux - see reports/search-disruption.md)
```

## 5. The One-Line Positioning

```text
Google:     owns the WHOLE stack + co-designs model & silicon; best technology, must survive Search disruption
Amazon:     owns cost/capacity (proven silicon + DCs + power) + Anthropic; must win demand; FCF now negative
Microsoft:  owns demand (OpenAI) + distribution; weaker silicon; rents NVIDIA; no core-disruption risk
Meta:       owns silicon + power for itself; not a cloud seller; core augmented not disrupted
Oracle:     rents the stack; books backlog fast; carries NVIDIA margin + leverage
NVIDIA:     is the stack; wins on AI-compute growth regardless of cloud winner
```

Google's distinctive claim is **the only complete, self-owned, co-designed AI stack, self-funded and FCF-positive**. Its distinctive risk is **cannibalization** — turning the best AI toolkit on earth into new profit *faster than* that same AI erodes the Search franchise that pays for everything. That is the axis to watch it on, tracked quarter-to-quarter in `reports/watchlist.md` and `reports/search-disruption.md`.
