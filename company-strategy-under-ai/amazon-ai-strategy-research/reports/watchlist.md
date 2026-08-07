# Watchlist: What Proves the Thesis, What Breaks It, What To Track

Date baseline: 2026-08-05

The thesis (see `reports/strategy-thesis.md`): Amazon is converting an AI-demand shock into a vertically integrated compute-supply position — custom silicon, owned data centers, long-dated power — to defend AWS margin and ROIC. This file is the falsification and tracking layer.

## 0. Scorecard as of Q2 2026 (what has actually materialized)

```text
PROVE-signals that have fired (bull):
  [x] Silicon substitution rising      -> chip run-rate >$25B, triple-digit growth; ~1.4M Trainium chips
  [x] Third-party Trainium adoption     -> OpenAI (2 GW) + Apple named, beyond Anthropic
  [x] AWS margin holds/expands           -> ~39%, up ~650 bps YoY, EVEN AFTER shortening server life 6->5 yrs
  [x] AWS growth re-accelerates + backlog -> +36.7% (fastest in 18 quarters); RPO ~$496B
  [~] Anthropic capacity utilized/expanding -> 1M+ Trainium2 chips; Project Rainier live; investment -> ~$33B

BREAK-signals that have fired (bear):
  [x] Free cash flow negative            -> TTM FCF -$7.6B (from +$18.2B); capex ~$220B > op cash flow ~$161B
  [x] Power slips / regulatory pushback  -> FERC rejected Talen colocation; SMRs early-2030s; VA moratoria
  [~] Reported profit quality            -> Q2 net income inflated by ~$53.4B UNREALIZED Anthropic mark
  [ ] Workloads stay on NVIDIA           -> NOT confirmed; substitution appears to be rising, share undisclosed
  [ ] AWS ceding cloud-AI share          -> mixed: AWS re-accelerating BUT Google Cloud/Azure growing faster off smaller bases

Net: thesis validating on the income statement; risk has migrated to the cash-flow statement.
```

## 1. What Would PROVE the Thesis

Signals that vertical integration is producing a real cost/capacity moat:

1. **Silicon substitution rises**: disclosed or credibly reported growth in the share of AWS AI compute running on Trainium/Inferentia rather than NVIDIA. The single most important number.
2. **Third-party Trainium adoption**: named customers *beyond Anthropic* training or serving on Trainium at scale — proof the chip + Neuron stack is a product, not just an internal hedge.
3. **AWS margin holds or expands *through* the capex cycle**: operating margin stable/up even as depreciation from AI assets ramps — evidence the spend is earning its cost of capital.
4. **AWS growth re-accelerates and backlog (RPO) grows**: demand converting into booked, contracted revenue faster than capacity is added.
5. **Firm power energized on schedule**: contracted nuclear/renewable MW actually coming online and powering AI campuses, not just announced.
6. **Anthropic capacity fully utilized and expanding**: Project Rainier scaling and Anthropic's Trainium consumption growing — the anchor demand filling the capacity.
7. **Effective cost per unit of AI compute falling**: any disclosure or credible teardown showing Amazon's $/training-hour or $/token below the NVIDIA-rental benchmark.

## 2. What Would BREAK the Thesis

Signals that the integration is defensive capex compressing returns:

- **Workloads stay on NVIDIA**: Trainium share stalls; customers (and even Anthropic) keep training frontier models on NVIDIA because of performance or ecosystem gaps.
- **Neuron/software friction persists**: developers won't port off CUDA, so Trainium remains niche and Amazon still pays NVIDIA's margin at scale.
- **Depreciation outruns operating income**: AWS margin visibly compresses as AI assets depreciate faster than they generate revenue; the useful-life assumptions on chips prove too generous.
- **Free cash flow turns sharply negative and stays there**: capex so large that the cash engines (retail, ads) can't cover it and the balance sheet strains.
- **Power slips**: contracted MW delayed, regulatory pushback (e.g. FERC rejections of colocated nuclear structures, state moratoria), stranding data-center capacity.
- **AI demand disappoints / digests**: an "AI capex hangover" where booked demand doesn't materialize and capacity sits idle.
- **AWS keeps ceding cloud-AI share**: Azure (OpenAI) and Google Cloud (Gemini/TPU) grow AI cloud faster, suggesting Amazon's model-layer weakness offsets its silicon strength.

## 3. The Key Ratios To Track (from the primer scorecard)

```text
1. Silicon substitution:  Trainium/Inferentia share of AWS AI compute
2. Cost per unit:         Amazon $/training-hour or $/token vs NVIDIA-rental benchmark
3. Capacity conversion:   firm MW contracted AND energized vs MW needed for booked demand
4. Capital efficiency:    AWS operating income & ROIC vs capex & depreciation growth
5. Demand anchor health:  Anthropic + Bedrock consumption vs capacity being built
6. Ecosystem adoption:    non-Anthropic workloads on Neuron/Trainium
```

## 4. Track Next Quarter (Concrete)

Each Amazon earnings cycle, extract and update:

- [ ] Total capex actual + updated full-year guidance; management's language on trajectory ("continue to increase" vs "moderate")
- [ ] AWS revenue, YoY growth %, operating margin, and RPO/backlog
- [ ] Any disclosed Trainium2/Trainium3 milestones, capacity, or customer names
- [ ] Anthropic-related disclosures (investment marks/gains, Project Rainier scale)
- [ ] New power/nuclear deals or status changes on existing ones (Talen/Susquehanna, X-Energy, Energy Northwest, others); FERC/regulatory developments
- [ ] Bedrock / Nova / Q / AgentCore traction statements
- [ ] Robotics deployment counts and productivity claims (retail cost lever)
- [ ] Free cash flow (trailing twelve months) and the capex/FCF relationship

## 5. Cross-Read Signals (Competitors)

Watch these as leading indicators for the whole AI-cloud economics question:

- **NVIDIA** data-center revenue, gross margin, and any softness — a proxy for whether the "chip bottleneck" (and thus the value of escaping it) is easing or intensifying.
- **Microsoft / Google / Meta / Oracle** capex guidance — whether the industry is still in escalation or beginning to digest.
- **Microsoft-OpenAI** and **Google-Gemini** cloud-AI revenue disclosures — the demand-layer competition Amazon must match with Bedrock/Nova/Anthropic.
- **Power/utility** signals: PJM capacity auction prices, FERC rulings on colocated load, SMR project milestones — the gating physical constraint.

## 6. Open Questions (Living List)

Kept in `notes/research-notes.md`; the highest-value unresolved ones:

1. What is the *actual* Trainium share of AWS AI compute? (Rarely disclosed cleanly.)
2. What is Amazon's real effective cost per unit of AI compute vs renting NVIDIA?
3. How much of Amazon's capex is AI vs the rest of the business, quarter by quarter?
4. How firm are the power deals — contracted MW, energization dates, regulatory status?
5. Is Anthropic's frontier training genuinely on Trainium, or still primarily NVIDIA?
6. How is the Anthropic stake accounted for, and how much reported "profit" is non-cash marks?
