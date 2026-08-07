# End-to-End Goal

Date baseline: 2026-08-05

## Objective

Build a source-backed research dossier on Amazon's strategy under AI-driven constraint shifts, with enough technical and business detail to answer:

```text
How is AI changing the constraint structure of Amazon's business,
what has management done in response,
and does it improve future economics?
```

The target outcome is not a generic "Amazon AI initiatives" overview. Amazon is a different *type* of AI-strategy case than a tool vendor whose product-value-unit is changing. Amazon's core AI story is about **the bottleneck structure of the business** moving underneath it:

```text
AI demand explosion
  -> compute bottleneck
  -> chip bottleneck (NVIDIA supply + cost)
  -> data-center bottleneck (land, construction, water)
  -> power bottleneck (grid interconnect, generation)
  -> capital-allocation shift (capex, depreciation, FCF)
  -> AWS margin and ROIC implications
  -> competitive position vs Microsoft, Google, Meta, Oracle, NVIDIA
```

The dossier explains where Amazon is *spending* to relieve each bottleneck, whether those investments are demand-creating or defensive, and what they imply for the durability of AWS economics.

## The Framework (Reusable Across Companies)

This dossier instantiates a reusable "company strategy under AI" template. The general lens is:

```text
current business baseline
  -> AI exposure map (demand / cost / threat / new-infrastructure)
  -> bottleneck analysis (compute, chips, power, data centers, data, talent, capital)
  -> strategic response (build / buy / partner / vertically integrate / M&A / pricing / capex)
  -> evidence ledger
  -> investment implication (moat, margin, capex, pricing power, cannibalization, new lines)
  -> watch items (what proves it, what breaks it, what to track next quarter)
```

For a *product-transformation* case (e.g. an EDA/CAE vendor), the sharp question is "does AI change the value unit sold?" For Amazon the sharp question is "does AI change what is scarce, and did Amazon buy the scarce thing early enough and cheaply enough to defend its returns?"

## Core Thesis To Test

```text
Amazon is converting an AI-demand shock into a vertically integrated
compute-supply position: custom silicon (Trainium/Inferentia/Graviton),
owned data centers, and long-dated power (including nuclear),
in order to defend AWS margin and ROIC against an NVIDIA-priced,
power-constrained, capex-heavy cloud market.
```

The commercially important question is whether this vertical integration:

- lowers Amazon's effective cost per unit of AI compute versus renting NVIDIA at market price,
- secures enough power and data-center capacity to convert AI demand into billable AWS revenue,
- does so without capex and depreciation destroying free cash flow and ROIC,
- and whether the Anthropic relationship + Bedrock + Nova give Amazon a durable software/demand layer on top of the silicon.

## Required Evidence Classes

Separate evidence by strength.

### Tier 1: Primary Company Evidence
Amazon 10-K / 10-Q, earnings-call transcripts, About Amazon / AWS press releases, SEC filings, investor materials. Also primary sources from Microsoft, Alphabet, Meta, Oracle, NVIDIA where needed for comparison.

### Tier 2: Technical / Operational Evidence
Chip specs and roadmaps (Trainium2/3, Inferentia, Graviton), Project Rainier disclosures, data-center and power-deal filings (FERC, Talen, X-Energy, Energy Northwest), benchmark or price/performance claims, robotics deployments.

### Tier 3: Strategic / Market Evidence
Credible press (Reuters, Bloomberg, CNBC, The Information, Data Center Dynamics), analyst estimates, and industry data used to size bottlenecks and compare capex — clearly labeled as reported/estimated, not disclosed.

## Deliverables

The dossier maintains these files:

- `reports/strategy-thesis.md`
  - Investor/strategist-facing thesis: constraint shifts, vertical-integration bet, moat/margin/ROIC implications, bull/bear cases.
- `reports/technical-primer.md`
  - First-principles explanation of the AI-compute supply chain and why each layer (chips, data centers, power) is a bottleneck; how Trainium/Inferentia/Graviton and the model/agent layer fit.
- `reports/business-model-map.md`
  - How AI changes what Amazon sells, meters, and prices across AWS, retail, advertising, and devices.
- `reports/capex-and-bottlenecks.md`
  - Quantified bottleneck ledger: capex, depreciation, chips, data centers, power, and the economics of relieving each.
- `reports/company-comparison.md`
  - Amazon vs Microsoft, Google, Meta, Oracle, NVIDIA on capex, custom silicon, power, and business-model exposure.
- `sources/source-ledger.md`
  - Source list with URL, use, and reason for inclusion; evidence strength per source.
- `reports/watchlist.md`
  - What would prove the thesis, what would break it, and what to track next quarter.
- `notes/research-notes.md`
  - Working notes, open questions, follow-up leads.

## Completion Criteria

Review-ready when it can answer, with cited and strength-labeled evidence:

1. What are Amazon's disclosed capex plans, and how much is AI/data-center driven?
2. What is the custom-silicon strategy (Trainium/Inferentia/Graviton) and how far along is it?
3. How dependent is AWS on NVIDIA, and is vertical integration actually reducing that?
4. What is the Anthropic relationship, financially and technically (Project Rainier)?
5. How is Amazon securing power, and how central is nuclear?
6. What is the software/demand layer (Bedrock, Nova, Q, Alexa+, Rufus) and does it create pricing power or just parity?
7. What are AWS growth, margin, and backlog trends, and how do they compare to Azure/Google Cloud?
8. Where does AI reduce Amazon's own cost structure (robotics, ops, code, support)?
9. Which claims are disclosed vs reported vs estimated vs speculative?
10. What would prove or break the vertical-integration thesis?

## Review Checklist

- every major claim points to `sources/source-ledger.md`
- disclosed numbers separated from reported/estimated ones
- capex framed against depreciation, FCF, and ROIC — not just headline spend
- custom-silicon claims distinguished from NVIDIA-dependence reality
- power/nuclear deals labeled by structure (equity, PPA, offtake) and status
- Amazon compared against Microsoft, Google, Meta, Oracle on the same axes
- open questions kept visible, not smoothed over

## Practical Framing

The central distinction to preserve:

```text
"Amazon uses AI":
  chatbots, coding assistants, feature parity

"AI changed Amazon's constraint structure":
  scarce inputs (chips, power, land, capital) became the binding limit,
  and Amazon is buying/building/integrating to own them before rivals do
```

That distinction is the bridge from an "AI features" story to a durable strategic-economics story.
