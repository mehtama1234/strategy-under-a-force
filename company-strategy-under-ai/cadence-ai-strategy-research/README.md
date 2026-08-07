# Cadence Agentic-AI / EDA Research

Research folder analyzing Cadence Design Systems' agentic-AI strategy: the Cadence.AI product portfolio (Cerebrus, Verisium, Allegro X AI, Virtuoso Studio AI, Optimality), the JedAI data platform, the Millennium AI supercomputer, the NVIDIA partnership, the System Design & Analysis expansion, and whether agentic EDA shifts Cadence from tool licensing toward outcome-oriented engineering automation.

Direct peer to the Synopsys agentic-EDA dossier, and the **product-value-unit instantiation** of the "company strategy under AI" template (contrast the hyperscaler siblings `amazon-/microsoft-/google-ai-strategy-research`, which exercise the bottleneck-structure and cannibalization variants). The sharp question here is not "did AI change what is scarce?" but **"did AI change the unit of value sold — from a tool an engineer operates to a verified outcome an agent produces?"**

Date baseline: 2026-08-05

## Files

- `GOAL.md` - objective, the shared EDA core question, evidence tiers, deliverables, completion criteria
- `reports/strategy-thesis.md` - thesis: agentic EDA, pricing power, outcome-monetization path, Cadence vs Synopsys/Siemens, bull/bear
- `reports/technical-primer.md` - first-principles agentic EDA and Cadence's validator-grounded closure loops
- `reports/agentic-products-matrix.md` - each Cadence.AI product by workflow, input, agents, tools, validator, claimed outcome, evidence strength
- `reports/business-model-map.md` - how AI could shift Cadence monetization from tools toward outcomes
- `reports/company-comparison.md` - Cadence vs Synopsys, Siemens EDA, and the NVIDIA/hyperscaler ecosystem
- `reports/watchlist.md` - what proves the thesis, what breaks it, what to track next quarter
- `sources/source-ledger.md` - source list, URL, use, evidence strength
- `notes/research-notes.md` - working notes and open questions

## Core Question

Can Cadence's agentic products reliably move real designs toward bounded, verifiable outcomes — implementation/PPA closure (Cerebrus), verification/debug closure (Verisium), analog (Virtuoso Studio), PCB (Allegro X AI), multiphysics (Optimality/Millennium) — and does that let Cadence price closer to engineering value rather than only tool access? Same "tool → outcome" thesis tested for Synopsys, now for its nearest peer.

## Early Finding

Like Synopsys, Cadence's disclosed model is expected to remain a time-based license / subscription / ratable-revenue business; outcome-based pricing is best treated as a possible strategic direction enabled by agentic workflows, not the currently disclosed core model. EDA's advantage for the agentic thesis is its richness in **validators** (simulators, formal, timing/power, DRC/LVS, SPICE, multiphysics solvers) that produce hard truth signals — making closed-loop agents more credible here than in softer domains.

## Current Technical Thesis

The state of the art is a tool-grounded closure loop:

```text
design intent + context -> planner/agents -> Cadence engine execution
  -> deterministic validation -> repair/optimization loop -> human signoff
```

The meaty question is not whether an LLM can write RTL. It is whether an agentic system can repeatedly move a real design toward a verified target — PPA closure, coverage/debug closure, DRC repair, analog migration, multiphysics convergence — grounded in Cadence's proprietary engines and EDA data (JedAI), accelerated on GPU compute (Millennium).
