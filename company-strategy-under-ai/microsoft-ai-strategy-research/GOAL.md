# End-to-End Goal

Date baseline: 2026-08-05

## Objective

Build a source-backed research dossier on Microsoft's strategy under AI, with enough technical and business detail to answer:

```text
Can Microsoft convert its distribution reach and its OpenAI relationship
into durable, high-margin AI revenue and pricing power -
without being trapped by supply-cost exposure, OpenAI dependence,
and softer-than-hoped Copilot monetization?
```

Microsoft is the **opposite archetype to Amazon** and a useful second data point for the reusable "company strategy under AI" template (see the sibling `amazon-ai-strategy-research`). Amazon is an *own-the-supply* case (custom silicon, owned data centers, power). Microsoft is an *own-the-demand* case: frontier models via OpenAI, and unmatched enterprise distribution (Windows, Office/M365, Teams, GitHub, Azure, Dynamics) into which it can push AI as a per-seat upsell.

Microsoft is also a **hybrid** that exercises *both* variants of the template:

- **Product-value-unit shift** (like the EDA case): does AI move Microsoft from selling per-seat SaaS to selling *agents / work done*?
- **Bottleneck-structure shift** (like the Amazon case): is Microsoft's growth now gated by chips, power, and capital — and it is more exposed here than Amazon because it rents more NVIDIA and its own silicon (Maia) trails.

## The Core Tension

```text
Microsoft's edge is DEMAND: frontier models (OpenAI) + the world's best enterprise distribution.
Microsoft's exposure is SUPPLY and DEPENDENCE:
  - it rents NVIDIA at scale; its Maia silicon trails Trainium/TPU
  - its frontier-model access runs through OpenAI - now a partner, investee, AND competitor
  - it funds a huge share of OpenAI's compute while OpenAI diversifies away (Stargate, other clouds)
```

The whole dossier tests whether Microsoft's demand advantage is durable enough to out-earn its supply and dependence risks.

## The Framework (Reusable Across Companies)

Same lens as the Amazon dossier:

```text
current business baseline
  -> AI exposure map (demand / cost / threat / new-infrastructure)
  -> bottleneck analysis (compute, chips, power, capital, MODELS, distribution)
  -> strategic response (build / buy / partner / integrate / price)
  -> evidence ledger
  -> investment implication (moat, margin, capex, pricing power, cannibalization, dependence)
  -> watch items (what proves it, what breaks it, what to track next quarter)
```

For Microsoft the analysis adds two axes the Amazon case underweighted: **model dependence** (the OpenAI relationship as its own bottleneck and risk) and **distribution-led monetization** (Copilot attach economics).

## Core Thesis To Test

```text
Microsoft is monetizing AI primarily through DISTRIBUTION - attaching Copilot/agents to an
installed base of hundreds of millions of paid seats and to Azure - while managing down its
dependence on a single frontier-model partner (OpenAI) by building its own models (MAI/Phi)
and multi-sourcing (Anthropic, others). The bet pays off if Copilot attach + Azure AI revenue
grow faster and at higher margin than the capex, OpenAI-loss share, and NVIDIA cost required to serve them.
```

## Required Evidence Classes

### Tier 1: Primary Company Evidence
Microsoft 10-K / 10-Q, FY/quarterly earnings releases and call transcripts, official Microsoft/Azure/GitHub blogs, OpenAI official posts. Note fiscal year ends June 30.

### Tier 2: Technical / Product Evidence
Copilot seat/adoption figures, GitHub Copilot metrics, Azure AI Foundry, Maia/Cobalt silicon specs and status, MAI/Phi model releases, power deals (Constellation/Three Mile Island, Helion).

### Tier 3: Strategic / Market Evidence
Credible press and analyst estimates for the OpenAI restructuring terms, stake value, capex comparisons, and Copilot monetization — clearly labeled as reported/estimated, not disclosed.

## Deliverables

- `reports/strategy-thesis.md` — strategist/investor thesis: demand-led moat, OpenAI dependence, capex/margin, Copilot economics, bull/bear.
- `reports/technical-primer.md` — first-principles map of the AI value stack (silicon → cloud → models → orchestration/agents → apps → distribution) and where Microsoft is strong vs dependent.
- `reports/openai-relationship.md` — dedicated deep dive on the investment, restructuring, stake, commercial terms, and frenemy dynamics (the Microsoft-specific crux).
- `reports/business-model-map.md` — how AI changes what Microsoft sells, meters, and prices across M365, GitHub, Azure, Dynamics, security, consumer.
- `reports/capex-and-bottlenecks.md` — quantified ledger: capex, depreciation, NVIDIA dependence, Maia, power, OpenAI-loss share, FCF.
- `reports/company-comparison.md` — Microsoft vs Amazon, Google, Meta, Oracle, and OpenAI/Anthropic on demand, silicon, distribution, exposure.
- `sources/source-ledger.md` — sources with URL, use, evidence strength.
- `reports/watchlist.md` — what proves/breaks the thesis; what to track next quarter.
- `notes/research-notes.md` — working notes, open questions.

## Completion Criteria

Review-ready when it answers, with cited and strength-labeled evidence:

1. What are Microsoft's disclosed capex plans, and how AI/data-center-driven are they?
2. What exactly is the post-restructuring OpenAI relationship — stake %, Azure exclusivity, IP term, AGI clause, revenue share, loss-sharing?
3. How dependent is Microsoft on OpenAI, and how fast is it building its own models (MAI/Phi) and multi-sourcing?
4. How dependent is Azure on NVIDIA, and how far behind is Maia?
5. What is Copilot's real adoption and monetization — seats, attach, disclosed revenue — and is it seat or agent priced?
6. What are Azure growth, AI contribution, margin, and backlog trends?
7. How is Microsoft securing power (Three Mile Island, Helion)?
8. Which claims are disclosed vs reported vs estimated vs speculative?
9. What would prove or break the demand-led thesis?

## Practical Framing

The central distinction to preserve:

```text
"Microsoft has AI features":
  Copilot buttons in every app

"AI changed Microsoft's strategy":
  it is trying to convert the largest paid-software distribution base on earth into AI attach revenue,
  while de-risking a frontier-model dependence (OpenAI) that is simultaneously its biggest asset,
  its biggest cost, and a rising competitor
```

That distinction is the bridge from an "AI features" story to the real strategic question: durable demand-led monetization vs dependence-and-capex risk.
