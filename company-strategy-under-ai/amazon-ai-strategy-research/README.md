# Amazon AI-Strategy Research

Research folder analyzing Amazon's strategy under AI-driven constraint shifts: capex, custom silicon, data centers, power (including nuclear), the model/agent software layer, and AWS competitive economics.

This is the first instantiation of a **reusable "company strategy under AI" template** (see `GOAL.md`). Where a tool-vendor dossier asks "does AI change the value unit sold?", the Amazon dossier asks "does AI change what is *scarce*, and did Amazon buy the scarce thing early enough to defend its returns?"

Date baseline: 2026-08-05

## Files

- `GOAL.md` - end-to-end objective, the reusable framework, evidence tiers, deliverables, completion criteria
- `reports/strategy-thesis.md` - strategist/investor thesis on Amazon's vertical-integration bet, moat/margin/ROIC, bull/bear cases
- `reports/technical-primer.md` - first-principles explanation of the AI-compute supply chain and Amazon's position in each layer
- `reports/business-model-map.md` - how AI changes what Amazon sells, meters, and prices across AWS, retail, ads, devices
- `reports/capex-and-bottlenecks.md` - quantified bottleneck ledger: capex, depreciation, chips, data centers, power
- `reports/company-comparison.md` - Amazon vs Microsoft, Google, Meta, Oracle, NVIDIA on capex, silicon, power, exposure
- `reports/watchlist.md` - what proves the thesis, what breaks it, what to track next quarter
- `sources/source-ledger.md` - source list, URL, use, and evidence strength
- `notes/research-notes.md` - working notes and open questions

## Core Question

Amazon is turning an AI-demand shock into a vertically integrated compute-supply position — custom silicon, owned data centers, and long-dated power — to defend AWS economics against an NVIDIA-priced, power-constrained, capex-heavy market. The strategic question is whether that integration lowers Amazon's cost per unit of AI compute and secures enough power/land to convert demand into billable revenue, without capex and depreciation destroying free cash flow and ROIC.

## Early Finding

Amazon's disclosed model is unchanged: AWS sells metered compute/storage/services, retail sells goods, advertising sells placement. AI has not changed *what* Amazon sells so much as *what constrains* how much it can sell and at what margin. The interesting strategy is upstream — in chips, buildings, and electrons — not in the product SKUs.

## Current Strategic Thesis

The bet is a vertical-integration supply play:

```text
AI demand -> compute bottleneck -> chip bottleneck -> data-center bottleneck
  -> power bottleneck -> capex/depreciation -> AWS margin/ROIC -> competitive position
```

Amazon's response to each layer: build custom silicon (Annapurna: Trainium/Inferentia/Graviton) to escape NVIDIA pricing; build/own data centers at scale; sign long-dated power including nuclear (SMRs, offtake, colocated capacity); anchor demand with Anthropic (Project Rainier) plus Bedrock/Nova; and absorb the capex on the balance sheet in exchange for a lower long-run cost of AI compute.

The meaty question is not "does Amazon have AI features." It is whether owning the scarce inputs produces a durable cost and capacity advantage — or whether it is defensive capex that compresses returns while NVIDIA and the frontier-model labs keep the pricing power.
