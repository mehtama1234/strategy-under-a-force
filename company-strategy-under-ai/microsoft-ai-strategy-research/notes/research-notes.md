# Research Notes — Microsoft AI Strategy

Date baseline: 2026-08-05

Working notes, open questions, follow-up leads. Compact and additive.

## Framing decisions

- Microsoft = **"own the demand" archetype**, the deliberate mirror of Amazon's "own the supply." Told through the **AI value stack** (silicon → cloud → models → orchestration → apps → distribution): strong at the top, dependent at the bottom.
- Microsoft is a **hybrid** exercising both template variants: product-value-unit shift (Copilot seat → agent/consumption pricing) AND bottleneck-structure (capex, NVIDIA rent, power).
- The **OpenAI relationship** is the Microsoft-specific crux with no Amazon analog — asset, cost, and competitor at once. It gets its own report (`openai-relationship.md`).
- Fiscal year ends June 30; be explicit about fiscal vs calendar quarters.

## Evidence-strength convention

Every number tagged **Disclosed** / **Reported** / **Estimated** / **Speculative**; reconcile to `sources/source-ledger.md`.

## Open questions (living)

1. Post-restructuring OpenAI stake (% and $ value) and exact terms — Azure exclusivity status, IP term (2030/2032?), AGI clause, revenue share. Hardest and most important.
2. Real Copilot attach rate + any disclosed AI revenue run-rate.
3. Size and trajectory of Microsoft's equity-method share of OpenAI losses.
4. True Azure AI margin as AI mix rises (is NVIDIA rent eating it?).
5. How real is model de-risking (MAI/Phi/Anthropic share of workloads off OpenAI)?
6. How much capex effectively serves OpenAI vs Microsoft's own products?
7. Maia 200 status/delays; extent of continued NVIDIA dependence.

## Follow-up leads

- 10-K/10-Q: capex (purchased + finance leases), "equity method investments" / OpenAI loss line, RPO, Intelligent Cloud margin.
- Earnings-call transcripts: Nadella/Hood on capex trajectory, Azure AI contribution points, "demand exceeds capacity," Copilot momentum.
- OpenAI official post + press on the late-2025 restructuring (PBC / Foundation) and Microsoft's stake.
- Copilot adoption stats from MSFT blogs / Ignite / Build.
- Constellation / Three Mile Island (Crane Clean Energy Center) restart timeline; Helion agreement.

## Reconciliation log

Reconciled against the Q4-FY26 facts sheet (research sweep, 2026-08-05). Full sourced sheet preserved at `sources/raw-facts-sheet.md`; curated index in `sources/source-ledger.md`.

- [x] Capex: cash PP&E FY24 $44.5B → FY25 $64.6B → **FY26 $115.9B**; CY2026 guide ~$190B **trimmed to ~$175B**; Q1 FY27 "over $50B". ~2/3 = short-lived GPUs/CPUs. Moderation (May 2025) **reversed** to acceleration (Oct 2025).
- [x] OpenAI: $13B committed / $11.8B funded; **Oct 2025 restructuring → PBC under Foundation, $500B val; MSFT ~27% / ~$135B** (from 32.5%); Azure exclusivity **given up** (ROFR); **$250B Azure commitment**; **IP to 2032 incl post-AGI**, research to 2030; **AGI cliff neutralized**; rev-share capped (amount undisclosed). Equity-method: **Q1 FY26 −$3.1B**, Q2 FY26 +$7.6B (one-time), FY26 ~+$6.5B net.
- [x] Azure: **+40% (Q1 FY26)**, +37% cc Q2 guide, crossed **$100B annual** by Q4; **RPO $392B (+51%)**; IC margin ~43%; **Microsoft Cloud gross margin ~68%, down YoY on AI**.
- [x] Copilot: **M365 Copilot 30M+ seats**, >90% Fortune 500; **GitHub Copilot 4.7M paid**; Agent 365 ~40M agents; $37B AI run-rate stale (Apr 2025).
- [x] Silicon: **Maia 200 (Jan 2026, inference-only, delayed)**; Cobalt 200; heavy NVIDIA (GB300 NVL72 >4,600 GPUs for OpenAI); AMD MI300X. Est volumes ~250k Maia vs 600k Trainium vs 900k TPU.
- [x] Power: **Crane/TMI 835 MW, restart accelerated to 2027**; Helion 50MW+ (2028, fusion); 34 GW CFE; no signed SMR.

### Thesis-defining contrasts with the Amazon dossier (useful for the template)

1. **Depreciation direction is OPPOSITE.** Microsoft **extended** asset lives 15→25yr (margin tailwind); Amazon **shortened** servers 6→5yr (headwind). Note in both `capex` files.
2. **Capital health is OPPOSITE.** Microsoft FCF **positive** (~$67B); Amazon FCF **negative** (−$7.6B). Microsoft's binding risk is *margin*, not *capital*.
3. **Silicon position is OPPOSITE.** Amazon's Trainium is ahead (600k, OpenAI/Apple adoption); Microsoft's Maia trails (250k, inference-only). Microsoft rents more NVIDIA → less cost-escape.
4. **The OpenAI relationship has NO Amazon analog** — asset+cost+competitor; got its own report.
5. Both are "capacity-constrained, demand exceeds supply" — but Microsoft named **power ("warm shells")** as the binding limit, not chips.

### Housekeeping
- Research agent mistakenly saved the facts file into the *amazon* folder; moved to `microsoft-ai-strategy-research/sources/raw-facts-sheet.md`. Amazon folder verified clean.

### Still unresolved (carry forward)
- Standalone Copilot/AI revenue $ (never disclosed); real attach rate.
- Recurring (ex-one-time) OpenAI loss-share trajectory.
- Azure AI's points-of-growth and its effect on Azure gross margin.
- Maia's real share of Azure serving; when NVIDIA dependence falls.
- Apr-2026 OpenAI rev-share cap ($/%); several Apr-2026 terms press-only.
