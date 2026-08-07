# Research Notes — Amazon AI Strategy

Date baseline: 2026-08-05

Working notes, open questions, and follow-up leads. Compact and additive; not a polished report.

## Framing decisions

- Amazon is a **constraint-shift / bottleneck** case, not a **product-value-unit** case. The template's sharp question is reframed from "does AI change the SKU?" to "did Amazon buy the scarce inputs (chips, power, land, capital, anchor demand) early enough and cheaply enough to defend AWS returns?"
- Keep the money flywheel explicit: high-margin retail + advertising fund the AWS capex bet; that self-funding ability is Amazon's structural edge vs pure-play AI.
- Preserve the moat-vs-defensive-capex tension as the central unresolved question. Do not resolve it prematurely in Amazon's favor.

## Evidence-strength convention

Every number carries a tag: **Disclosed** (Amazon filing/call), **Reported** (credible press), **Estimated** (analyst/derived), **Speculative** (inference). Reconcile all quantitative claims against `sources/source-ledger.md`.

## Open questions (living)

1. Actual Trainium share of AWS AI compute — rarely disclosed cleanly. Biggest missing number.
2. Amazon's real effective cost per unit of AI compute vs renting NVIDIA — no clean public figure; look for teardown/analyst estimates.
3. AI share of total capex, quarter by quarter — management gives directional language, not a clean split.
4. Firmness of power deals — contracted MW, energization dates, FERC/regulatory status (Talen colocation rejection and restructure especially).
5. Is Anthropic's *frontier* training genuinely on Trainium at scale, or still primarily NVIDIA? Project Rainier scale claims vs reality.
6. Anthropic-stake accounting — how much reported profit is non-cash mark-to-market gains vs operating earnings.
7. Trainium3 / next-gen status and any Trainium4 preview (re:Invent Dec 2025) — verify GA vs preview.

## Follow-up leads

- Pull the latest 10-Q MD&A for capex + "Property and equipment acquired under finance leases" + depreciation trend.
- Earnings-call transcripts: Jassy/CFO language on capex trajectory and "we could serve more demand if we had more capacity/power/chips."
- FERC docket on Talen/Susquehanna colocation; Talen PPA restructure terms.
- X-Energy / Energy Northwest SMR timelines; any energization milestones.
- Bedrock/Nova/Q traction stats from re:Invent and quarterly calls.
- Robotics: current deployed-robot count and productivity/cost claims.

## Reconciliation log

Reconciled against the Q2 2026 facts sheet (5-agent research sweep, 2026-08-05). All figures now in `sources/source-ledger.md`.

- [x] Capex: FY2024 ~$83B; FY2025 ~$131.8B; **FY2026 guide ~$220B** (raised from ~$200B). Q2 2026 qtr ~$53.1B.
- [x] Trainium2 GA Dec 2024 ("30-40% price/perf" vs H100); **Trainium3 GA Dec 2, 2025**; Trainium4 in dev. Chip run-rate **>$25B, triple-digit growth**; ~1.4M chips.
- [x] Anthropic: ~$8B by Nov 2024; **+$5B + up to $20B (Apr 2026) → ~$33B potential**; minority AFS stake; FY2025 +$15.2B other income; **Q2 2026 ~$53.4B unrealized gain** (paper marks). 1M+ Trainium2 chips.
- [x] Talen/Susquehanna: **FERC rejected (2-1, Nov 2024)** the 300→480 MW colocation; rehearing denied; on appeal. SMRs (X-energy/Energy Northwest/Dominion) all early-2030s.
- [x] AWS Q2 2026: **$42.2B, +36.7%** (fastest in 18 quarters), op margin **~39%** (expanding), op income +63%, RPO **~$496B**.

### Thesis-affecting corrections found in reconciliation

1. **Useful-life inverted my hypothesis.** I had speculated a *life extension* could flatter margins; reality is Amazon **shortened** server life 6→5 yrs (more depreciation) and margin **still expanded** — a stronger bull signal than drafted. Corrected in `strategy-thesis.md` + `capex-and-bottlenecks.md`.
2. **Silicon substitution is further along than "unproven."** OpenAI (2 GW) + Apple on Trainium + >$25B chip run-rate = real third-party validation. Upgraded the stance from "credible but unproven" to "validating on operating metrics."
3. **Risk migrated to cash.** FCF negative (−$7.6B) + reported profit inflated by non-cash Anthropic marks is the new center of the bear case, replacing the earlier "watch the margin" framing (margin is fine).
4. **"$2.75B Anthropic tranche" (if seen anywhere) is Google's, not Amazon's.** Amazon pre-2026 = $4B+$4B=$8B.

### Still unresolved (carry forward)
- Clean AI-accelerator custom-vs-NVIDIA share (undisclosed — biggest missing number).
- Exact 10-Q RPO line (the ~$496B is call/press-sourced).
- Project Rainier ~2.2 GW (single tracker).
- Talen 5th-Circuit appeal outcome (pending).
- Verify Google Cloud ~82% / Azure ~40% against those companies' own releases.
