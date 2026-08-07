# Company Strategy Under AI

Reusable research repository for analyzing how AI changes company strategy.

The core question across folders:

```text
How is AI changing the company's products, cost structure, scarce inputs,
capital allocation, moat, and business model?
```

Each company folder should be a self-contained dossier with:

- `GOAL.md`
- `README.md`
- `reports/strategy-thesis.md`
- `reports/technical-primer.md`
- `reports/business-model-map.md`
- `reports/capex-and-bottlenecks.md`
- `reports/company-comparison.md`
- `reports/watchlist.md`
- `sources/source-ledger.md`
- `notes/research-notes.md`

This is the **default** structure. Each company's own `GOAL.md` is authoritative and may add or substitute reports where the company type warrants it — treat the list above as the baseline, not a rigid contract. Documented per-company deviations:

- **Microsoft** adds `reports/openai-relationship.md` (its partner-dependence crux).
- **Google** adds `reports/search-disruption.md` (its core-cannibalization crux).
- **Cadence** substitutes `reports/agentic-products-matrix.md` for `reports/capex-and-bottlenecks.md` — a ~88%-margin software/IP business has no capex/power/silicon bottleneck story; the relevant "bottleneck" (the compute economics of the agentic loop) is covered inside the matrix. Same convention as the sibling `synopsys-agentic-eda-research`.

## Current Folders

- `amazon-ai-strategy-research/` — own the supply (constraint-shift); complete
- `microsoft-ai-strategy-research/` — own the demand (margin/dependence); complete
- `google-ai-strategy-research/` — own both axes (cannibalization); complete
- `cadence-ai-strategy-research/` — product value-unit (tool → outcome); complete

## Strategy Lens

The useful framing is not:

```text
Does this company use AI?
```

The useful framing is:

```text
What did AI make scarce, cheap, defensible, risky, or newly monetizable?
```

For infrastructure-heavy companies, the answer may be chips, data centers, power, capital, and utilization.

For software or tool companies, the answer may be product value units, workflow ownership, validators, and outcome pricing.
