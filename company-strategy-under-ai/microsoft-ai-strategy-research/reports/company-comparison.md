# Company Comparison: Microsoft vs the Field

Date baseline: 2026-08-05

> Evidence tags: **[Disclosed]** · **[Reported]** · **[Estimated]** · **[Speculative]**. Reconciles to `sources/source-ledger.md`. The comparison is about *positioning on the demand-vs-supply axes*, not a precise league table. Figures blend fiscal calendars — noted where it matters.

The organizing idea: every AI-infrastructure player sits somewhere on two axes — **do you own the demand** (frontier models + distribution) and **do you own the supply** (custom silicon + power + capital). Microsoft is strong on demand, weak on supply. That single fact positions it against everyone.

## 1. The Scorecard

| Axis | Microsoft | Amazon | Google | Meta | Oracle | OpenAI/Anthropic |
|---|---|---|---|---|---|---|
| Frontier model | **OpenAI (stake) + own MAI** | Anthropic (stake) + Nova | **Gemini (owns)** | Llama (owns, open) | rents/partners | **own the frontier** |
| Enterprise distribution | **unmatched** (450M+ seats) | strong (AWS) | strong (Workspace/Cloud) | none | strong (apps/DB) | growing (ChatGPT enterprise) |
| Custom training silicon | Maia (**trails**, inference-only) | Trainium (maturing) | **TPU (mature)** | MTIA (internal) | none (rents) | none (buys) |
| NVIDIA dependence | **high** | lower (Trainium) | lower (TPU) | high | high | high |
| Capex 2026 guide | ~$175B (CY, trimmed from $190B) | **~$220B** | $180-205B | $125-145B | huge (OCI/Stargate) | via partners (~$1T commitments) |
| Free cash flow | **positive (~$67B FY26)** | **negative (−$7.6B TTM)** | positive | positive | levered | deeply negative |
| Custom-silicon volume (2026, est) | ~250k Maia | ~600k Trainium | **~900k TPU** | ~180k MTIA | — | — |
| Core exposure | **margin** (rent compute) | **capital** (FCF, depreciation) | Search disruption | internal ROI | concentration/leverage | funding the losses |

*(Capex 2026 figures blend calendar/fiscal guidance from earnings/press; custom-silicon volumes are analyst estimates with no primary source — [Estimated]. Reconciled in `sources/source-ledger.md`.)*

## 2. The Defining Comparison — Microsoft vs Amazon (Demand vs Supply)

This is the cleanest pairing in the whole two-dossier set:

```text
Amazon:     owns the SUPPLY (Trainium, owned DCs, power) -> must prove DEMAND capture
Microsoft:  owns the DEMAND (OpenAI + 450M+ seats)       -> must prove MARGIN (renting compute profitably)
```

- **On capital:** Microsoft is healthier — FCF *positive* (~$67B) vs Amazon's FCF *negative* (−$7.6B TTM). Microsoft's capex ($116B cash) sits comfortably under its OCF ($183B); Amazon's ~$220B capex exceeds its OCF. **[Disclosed / Estimated]**
- **On depreciation:** opposite accounting moves — Microsoft **extended** asset lives (15→25yr, a margin tailwind); Amazon **shortened** server life (6→5yr, a headwind). **[Disclosed]**
- **On silicon:** Amazon is ahead — Trainium (~600k units, third-party adoption from OpenAI/Apple) vs Maia (~250k, inference-only, delayed). Amazon has more of the NVIDIA cost-escape. **[Estimated]**
- **On demand proof:** Microsoft is ahead — 30M+ Copilot seats and $392B RPO are a more concrete, higher-margin demand signal than Amazon's (which is heavily infra/Anthropic-anchored).

Read-through: **Amazon has the better cost structure; Microsoft has the better demand and balance sheet.** Whoever closes their gap first — Amazon capturing demand, or Microsoft lowering unit cost (own silicon) / holding distribution pricing power — wins the AI-cloud margin war.

## 3. Microsoft vs Google — The Full-Stack Threat

Google is the one rival strong on *both* axes Microsoft is weak on:

```text
Google:     owns a frontier model (Gemini) AND mature training silicon (TPU). Fastest-growing cloud
            (~82% same calendar quarter). The most complete vertical stack.
Microsoft:  owns neither the model outright (OpenAI) nor competitive silicon (Maia trails).
            Counters with distribution + enterprise trust Google lacks at the same scale.
```

Read-through: Google is the structural threat — it needs no OpenAI and pays itself for silicon. Microsoft's defense is the enterprise moat: incumbency, compliance, integration, and a sales motion into the Fortune 500 that Google Cloud has not matched. If AI reduces to "best model on cheapest silicon," Google wins; if it reduces to "trusted AI attached to the tools enterprises already run," Microsoft wins.

## 4. The Others

### Meta — validates owning silicon+power, not a cloud rival
Huge capex ($125-145B 2026 guide) and its own MTIA silicon, but for *internal* workloads (ads, Llama). Competes with Microsoft for chips, power, and talent — not for enterprise AI customers. Read-through: reinforces the "own your silicon and power" logic Microsoft is *weakest* on, without being a demand competitor.

### Oracle — the rent-the-stack extreme
Booked enormous AI backlog (RPO ~$523B, ~54% tied to one OpenAI/Stargate contract) by *renting NVIDIA* — and, notably, **won Stargate off Azure**. Read-through: Oracle is both a cautionary tale (concentration + NVIDIA-margin + leverage) and a live competitor that took OpenAI's marquee buildout that Microsoft's exclusivity once implied would be Azure's.

### OpenAI & Anthropic — the model layer as counterparty
Not cloud sellers in the same sense, but central: Microsoft has a **stake in OpenAI** (asset + cost + competitor) and **invested up to $5B in Anthropic** (hedge). Both are simultaneously suppliers (models Microsoft resells), customers (OpenAI's $250B and Anthropic's $30B Azure commitments), and — for OpenAI — a competitor. Read-through: Microsoft's model-layer position is a *portfolio of relationships* rather than ownership, which is more flexible but less controlling than Google owning Gemini outright.

### NVIDIA — the cost Microsoft is most exposed to
Microsoft benefits *least* among the big three from own-silicon cost-escape, so it is the most sensitive to NVIDIA's pricing power. Read-through: any NVIDIA price relief helps Microsoft's margin most; any continued NVIDIA strength hurts Microsoft's margin most.

## 5. The One-Line Positioning

```text
Microsoft:  owns DEMAND (OpenAI + unmatched distribution); rents SUPPLY -> must prove margin
Amazon:     owns SUPPLY (Trainium + DCs + power); FCF-negative -> must prove demand + afford the build
Google:     owns BOTH (Gemini + TPU); fastest cloud growth -> Search-disruption is its distinct risk
Meta:       owns silicon+power for ITSELF; not a cloud seller
Oracle:     RENTS the stack; books huge concentrated backlog; won Stargate off Azure
OpenAI:     owns the FRONTIER; multi-clouds; competes with its own backer (Microsoft)
NVIDIA:     IS the supply; Microsoft is the most exposed big-three buyer
```

Microsoft's distinctive claim is **demand-led monetization from an unmatched distribution base, funded comfortably from internal cash.** Its distinctive risk is **margin** — turning that demand into profit while paying market price for compute and carrying a costly, competitive model dependence. That is the axis to watch it on, tracked quarter-to-quarter in `reports/watchlist.md`.
