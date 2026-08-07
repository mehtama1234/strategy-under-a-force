# Research Notes — Google (Alphabet) AI Strategy

Date baseline: 2026-08-05

Working notes, open questions, and follow-up leads. Compact and additive; not a polished report.

## Framing decisions

- Google is the **incumbent's-dilemma / cannibalization** case, not a pure constraint-shift (Amazon) or margin (Microsoft) case. The reframed sharp question: not "does Google have AI?" (yes, the best) but "can the company with the best AI technology *survive AI's disruption of its own Search cash cow* while turning its full-stack lead into Cloud + Gemini profit?"
- Keep the **two-clocks race** explicit: new AI profit (Cloud + Gemini + AI-Mode ads) growing vs classic Search economics eroding. The thesis works only if the first clock beats the second.
- Preserve the **co-design moat** (owns Gemini *and* TPU → co-designs model + silicon) as Google's deepest structural edge — no rival has it.
- Give the Search-cannibalization risk its **own report** (`search-disruption.md`), matching how the Microsoft dossier gave the OpenAI relationship its own file. This is the Google-specific crux and deserves standalone treatment.

## Evidence-strength convention

Every number carries a tag: **Disclosed** (Alphabet filing/call), **Reported** (credible press), **Estimated** (analyst/derived), **Speculative** (inference), **[verify]** (pending confirmation). Reconcile all quantitative claims against `sources/source-ledger.md`.

## Open questions (living)

1. **The crux — AI-Search monetization rate.** Per-query RPM on AI Overviews / AI Mode vs classic Search is UNDISCLOSED and unauditable in real time; management asserts "approximately the same rate." Biggest missing number; watch aggregate Search growth as the proxy.
2. **Google Cloud growth %.** The sibling Amazon dossier cites "~82%" — this appears basis-dependent/erroneous. Reconcile to the defensible ~30-34% range against Alphabet's own Q2 2026 release. Second-biggest reconciliation item.
3. **2026 capex guide.** Assembled from Q3-2025 "significant increase" + the sibling's ~$180-205B range; retrieve the exact Q2-2026-updated number.
4. **Cloud operating margin trajectory** and how much is TPU-cost-driven (undisclosed TPU-vs-NVIDIA mix).
5. **External TPU adoption beyond Anthropic** — is there named non-Anthropic scale, or is it Anthropic + internal?
6. **Gemini frontier standing** — 2.5 vs 3; benchmark leadership shifts monthly; keep [verify].
7. **FCF under capex** — confirm Alphabet stays FCF-positive through the ramp (the edge over Amazon's negative FCF).
8. **DOJ remedy final state** — Sept 2025 ruling (no Chrome/Android divestiture) is the baseline; appeals possible.

## Follow-up leads

- Pull Alphabet Q2 2026 10-Q/release: Search "& other" ad line + growth; Cloud revenue/operating income/backlog; capex; FCF.
- Earnings-call transcripts: monetization-rate language on AI Overviews/AI Mode; Cloud capacity-constraint commentary; capex trajectory.
- Anthropic–Google TPU deal terms (Oct 2025): committed ceiling (~1M TPUs / >1 GW) vs drawn-down; note Anthropic multi-silicon (also Trainium + NVIDIA).
- TPU generations: Ironwood (v7) specs, Trillium (v6); XLA/JAX stack maturity; any external-customer TPU wins beyond Anthropic.
- Power: Kairos SMR (~500 MW by 2035), Commonwealth Fusion (~200 MW ARC PPA), Fervo geothermal — energization timelines (all early-2030s).
- DOJ remedy docket + any appeal filings; distribution-deal (default-placement) economics post-remedy.
- DeepMind pipeline: AlphaFold (2024 Nobel), AlphaProof/AlphaGeometry (IMO gold), Genie world models, Veo — the long-dated capability option.

## Reconciliation log

Assembled from FY2025 actuals + Q3-2025 guidance + press (2026-08-05). Firm the following against the Q2 2026 release:

- [~] Capex: FY2024 ~$52.5B; FY2025 ~$91-93B; **FY2026 "significant increase," ~$180-205B [verify]** (sibling/press-sourced).
- [~] Cloud: profitable, margin rising, backlog ~$100B+ [verify]; **growth ~30-34% — NOT the sibling's "~82%"** (correct/verify).
- [x] TPU: Ironwood (v7) / Trillium (v6); **Anthropic up to ~1M TPUs, >1 GW online 2026, "tens of billions"** [G-T6, verify]; Anthropic multi-silicon.
- [x] Search: still growing while AI Overviews (~2B reach) / AI Mode scale; monetization "approximately the same rate" = management claim [verify].
- [x] Regulatory: **Sept 2025 DOJ remedy — no Chrome/Android divestiture**, limits on exclusive defaults, some data-sharing; broadly favorable [G-P4].
- [x] Power: Kairos SMR, Commonwealth Fusion, Fervo — all early-2030s (intent, not near-term relief).
- [x] DeepMind: AlphaFold (2024 Nobel Chemistry, Hassabis & Jumper), IMO-gold math, Genie, Veo.

### Thesis-affecting notes found in drafting

1. **Google's capital story is the INVERSE of Amazon's cash risk.** Larger higher-margin cash engine + TPU keeping spend off NVIDIA's margin → Alphabet expected FCF-positive through the ramp, vs Amazon's negative FCF. Reframed capex report around "well-covered, but the same engine must also insure Search."
2. **The "~82% Google Cloud growth" figure is almost certainly wrong.** The sibling Amazon dossier itself flagged it for verification; corrected here to ~30-34% and made it the top reconciliation item.
3. **Regulatory tail-risk eased more than expected.** The Sept 2025 DOJ remedy avoiding Chrome/Android divestiture means Google fights the AI-Search transition from a still-strong distribution position — a materially better setup than the bear case. Elevated in `search-disruption.md` §7.
4. **The crux is structurally UNAUDITABLE.** Unlike Amazon (where the missing number, Trainium share, could eventually be disclosed), Google's crux — AI-surface RPM vs classic — is unlikely to ever be broken out. So the thesis will be judged on the *aggregate Search growth-rate proxy*, not a clean disclosure. Stated plainly in `search-disruption.md`.

### Still unresolved (carry forward)
- Per-query AI-Search monetization rate (undisclosed — the crux).
- Exact Cloud growth % (reconcile the "~82%"), operating margin, backlog.
- Exact 2026 capex guide.
- Non-Anthropic external TPU scale.
- Gemini's real-time frontier standing (2.5 vs 3).
