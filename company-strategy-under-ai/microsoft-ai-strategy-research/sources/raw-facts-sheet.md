# Microsoft AI Strategy — Sourced Facts Sheet

**Compiled: 2026-08-05.** No thesis — sourced facts only.

**Fiscal-year convention:** Microsoft's FY ends June 30. FY2024 ended Jun 30 2024; FY2025 ended Jun 30 2025; FY2026 ended Jun 30 2026 (reported ~Jul 29 2026). Quarters are **fiscal** unless labeled calendar (CY). Map: **FY26 Q1 = CY Jul–Sep 2025; Q2 = Oct–Dec 2025; Q3 = Jan–Mar 2026; Q4 = Apr–Jun 2026.**

**Confidence tags:** **Disclosed** = official filing/release/blog · **Reported** = credible press · **Estimated** = derived/modeled · **Speculative**.

> **Read-me on reliability:** Every anchor number was fetched from a live source by a research agent, with the highest-value items (capex lines, the 27%/$135B OpenAI stake, IP/AGI terms, seat counts) independently cross-checked against a second source. Items that could NOT be verified are flagged inline and consolidated in the "Unverified / flagged" box at the end of each area.

---

## AREA 1 — CAPEX

### Total capex by year — cash "Additions to property and equipment" (cash-flow line)
- **FY2024: $44,477M** — *Disclosed* (MSFT FY25 Q4 comparative cash flows).
- **FY2025: $64,551M (+45% YoY)** — *Disclosed* (MSFT FY25 Q4 cash flows).
- **FY2026: $115,948M (+~80% YoY)** — *Disclosed* (MSFT FY26 Q4 press release / cash flows).

> ⚠️ **Two different "capex" measures circulate.** The cash-flow PP&E line above **excludes** non-cash finance leases. Press figures like "$115.95B FY25 capex" conflate the total-including-leases measure with a fiscal year — be careful. The clean cash-PP&E series is $44.5B → $64.6B → $115.9B.

### Total capex INCLUDING finance leases + finance-lease split (management/earnings-call totals)
Per fiscal quarter — **total incl. leases / finance leases / cash PP&E** — all *Disclosed* (earnings calls):

| Quarter | Total incl. leases | Finance leases | Cash PP&E |
|---|---|---|---|
| Q4 FY25 (Apr–Jun 25) | $24.2B | $6.5B | $17.1B |
| Q1 FY26 (Jul–Sep 25) | $34.9B | $11.1B | $19.4B |
| Q2 FY26 (Oct–Dec 25) | $37.5B | $6.7B | $29.9B |
| Q3 FY26 (Jan–Mar 26) | $31.9B | $4.7B | $30.9B |
| Q4 FY26 (Apr–Jun 26) | $41.0B | $5.6B | $35.8B |

- Finance leases are **non-cash** (excluded from the cash-flow PP&E line); the two measures also differ on payment-vs-receipt timing.
- Q1 FY26 finance-lease spike of **$11.1B** on datacenter leases, then declining — *Reported* (Data Center Dynamics).
- **FY2026 full-year total INCLUDING finance leases is NOT an official single number.** Sum of the four FY26 quarters ≈ **$145.3B** — *Estimated* (arithmetic, not official). ⚠️ flagged.

### Forward guidance
- **Q1 FY2027 (CY Jul–Sep 2026) capex: "over $50 billion"** (incl. a lease-reclassification impact) — *Disclosed* (Q4 FY26 call). Implies continued sequential acceleration from Q4's $41B.
- **FY2027 full year: "will grow year-over-year given demand signals"** — no % given — *Disclosed* (Q4 FY26 call).
- **Calendar-year 2026 capex: ~$190B** guided at Q3 FY26 call (Apr 2026), incl. ~$25B from higher component/memory pricing — *Disclosed* / *Reported* (CNBC). **Later trimmed to ~$175B** at the Q4 FY26 call, driven by the useful-life/lease-reclassification accounting change — *Disclosed*. Hood: "Outside of this useful life impact, our calendar year 2026 CapEx investment expectations remain unchanged."

### How much is AI / data-center
- **"Roughly two-thirds of our capex was for short-lived assets, primarily CPUs and GPUs"** — repeated Q2/Q3/Q4 FY26 — *Disclosed*. The remaining ~one-third = long-lived (datacenters, land, leases).
- Nadella (Q1 FY26): increase total AI capacity **>80% this year**, and **roughly double total datacenter footprint over the next two years** — *Disclosed*.
- **No official standalone "AI-only" capex dollar figure exists.** Press "AI capex" figures equate AI capex with the cash-PP&E line — an interpretation, not a Microsoft disclosure. ⚠️ flagged.

### Nadella & Hood — trajectory / demand-led
- **Demand-led (consistent):** Hood (Q2 FY26): "customer demand continues to exceed our supply." Hood (Q4 FY26): "customer demand continues to exceed available capacity." Nadella (Q4 FY26): expanding "in response to accelerating demand." — *Disclosed*.
- **Moderation → reversal (important nuance):** At Q3 FY25 (May 1 2025) Hood guided FY2026 capex to **"grow at a lower rate than FY2025."** At Q1 FY26 (Oct 2025) she **reversed**: **"We now expect the FY26 growth rate to be higher than FY25,"** citing accelerating demand and rising RPO. The trajectory **re-accelerated**. — *Disclosed* (reversal via CFO Dive).

### Depreciation (rising sharply)
- D&A (cash-flow "depreciation, amortization & other"): **FY2024 $22,287M → FY2025 $34,153M (+53%) → FY2026 $38,534M** — *Disclosed*.
- Quarterly: Q1 FY25 $7,383M → **Q1 FY26 $13,061M** (nearly doubled YoY) — *Disclosed*.
- **Accounting change (Q4 FY26):** useful lives of datacenters/office buildings **extended from 15 → 25 years**, slowing future depreciation growth; Hood said "minimal benefit to FY27 operating income" — *Disclosed*.

### Free cash flow impact
- Operating cash flow: **FY2024 $118,548M → FY2025 $136,162M → FY2026 $182,935M** — *Disclosed*.
- Q2 FY26 FCF **$5.9B** (down sequentially on higher capex/lower finance-lease mix); Q4 FY26 FCF **$19.6B** — *Disclosed*.
- **FY2026 full-year FCF ≈ $67B** (OCF $182.9B − cash PP&E $115.9B) — *Estimated/Reported*; not lifted from a filing. ⚠️ flagged. Hood expects to "remain free cash flow positive in FY27."

### Datacenters / gigawatts brought online
- **FY2026: 88 new datacenters** brought online — *Disclosed* (Nadella, Q4 FY26; *Reported* DCD). Q4 FY26 alone: **31 new datacenters across 5 continents**.
- **~1 GW added per fiscal quarter** through FY26 (Nadella, Q1–Q4) → ~4 GW in FY26 — *Estimated* (no official annual GW total). "On track to roughly double overall capacity in two years" — *Disclosed*.
- **Fairwater (Wisconsin)** AI datacenter online "next year," scaling to **2 GW**; linked with Atlanta via an AI WAN into an "AI superfactory"; "dock-to-live times for new GPUs reduced by nearly 50%" — *Disclosed*.

**⚠️ Area 1 unverified/flagged:** official full-year total-incl-finance-leases (FY24/25/26 — reported only quarterly; FY26 ≈$145.3B is arithmetic); standalone "AI-only" capex $ (not broken out); full-year GW added (only "~1 GW/quarter"); FY26 full-year FCF ~$67B (derived).

---

## AREA 2 — THE OPENAI RELATIONSHIP

> **Two distinct amendments matter:** the **Oct 28, 2025** restructuring/partnership rewrite (heavily documented, Tier-1) and a **further Apr 27, 2026** revision (press-only on several terms — MEDIUM confidence). Flagged throughout.

### Total Microsoft investment
- **$13B committed; $11.6B funded as of Sep 30 2025** (MSFT Q1 FY26 10-Q) — *Disclosed*. Updated **$11.8B funded as of Mar 31 2026** (Q3 FY26 10-Q) — *Disclosed*.
- A stray "$13.8B total invested" (Al Jazeera) exceeds the $13B commitment — treat as a press variant; the filing figure is authoritative. ⚠️ conflict flagged.

### The late-2025 restructuring (completed Oct 28 2025)
- OpenAI's for-profit arm became a **Public Benefit Corporation, "OpenAI Group PBC"** — *Disclosed/Reported*.
- The nonprofit is renamed the **"OpenAI Foundation"** and continues to **control** the PBC — *Disclosed* (OpenAI).
- **OpenAI Foundation holds ~26% / ~$130B** of OpenAI Group; employees + investors ~47% — *Reported* (TIME, CNBC). Splits are approximate and overlap across tallies. ⚠️ flagged.
- Deal **valued OpenAI at $500 billion**; Foundation initial charitable commitment **$25B** (health + "AI resilience"); reviewed by Delaware and California AGs — *Reported*.

### Microsoft's equity stake — KEY NUMBER (HIGH confidence)
- **~27% on an as-converted, fully-diluted basis, valued at ~$135 billion** — *Disclosed* (Microsoft official blog + 10-Q; corroborated CNBC, TIME, Fortune; independently cross-checked). 27% × $500B ≈ $135B is internally consistent.
- **Prior stake was ~32.5%** (as-converted, pre-latest round); diluted 32.5% → 27% by new capital — *Reported* (Microsoft blog states "previously held 32.5%").

### Revised commercial terms

**Azure exclusivity — NO LONGER exclusive:**
- **Oct 2025:** Microsoft **gave up its right of first refusal (ROFR) to be OpenAI's compute provider.** API products remained Azure-exclusive; non-API products (and US national-security customers) could run on any cloud — *Disclosed* (Microsoft/OpenAI blogs; verified).
- **Apr 2026:** OpenAI can now **serve all products on any cloud, incl. Google and Amazon**; remaining API/product cloud exclusivity eliminated. Microsoft stays "primary cloud provider" / products "ship first on Azure" unless Microsoft decides otherwise — *Reported* (CNBC, Forbes). **MEDIUM confidence (press-only).**

**$250B Azure compute commitment:**
- OpenAI **contracted to purchase an incremental $250B of Azure services** — *Disclosed* (Microsoft/OpenAI blogs; verified). Precise term/end date not fixed in sources — MEDIUM on timing.

**IP rights:**
- **Models & products: through 2032, now including models post-AGI** (with safety guardrails) — *Disclosed* (verified via Microsoft blog).
- **Research IP (confidential methods): until AGI is verified OR 2030, whichever comes first** — *Disclosed*.
- Non-research IP retained indefinitely (excludes weights/architecture/inference code/datacenter IP); IP rights now **exclude OpenAI's consumer hardware** — *Disclosed*.

**AGI-declaration clause:**
- **Before:** OpenAI's board could unilaterally declare AGI, cutting off Microsoft's access.
- **Oct 2025:** an AGI declaration must now be **verified by an independent expert panel**; and because model IP runs through 2032 *even past AGI*, a declaration no longer simply cuts Microsoft off. Microsoft also gained the right to **independently pursue AGI** — *Disclosed* (verified).
- **Apr 2026:** reporting says the clause was effectively neutralized ("Microsoft no longer needs to determine its response if OpenAI reaches AGI") — *Reported*. MEDIUM; exact mechanics undisclosed.

**Revenue sharing:**
- **Oct 2025:** OpenAI→Microsoft revenue share **remains until the expert panel verifies AGI, payments spread over a longer period** — *Disclosed*.
- **Apr 2026:** revenue-share payments continue **through 2030 (independent of AGI), subject to a total cap**; Microsoft will **no longer pay a reverse revenue share to OpenAI** — *Reported*. ⚠️ **The specific cap $-amount and % were NOT disclosed — UNVERIFIED.** The old ~20% figure is **not confirmed** for current terms — do not cite it as current.

### Equity-method accounting impact on Microsoft's income
- Method: **equity method**, flowing through "other income (expense), net" — *Disclosed*.
- **Q1 FY26 (ended Sep 30 2025): OpenAI losses REDUCED Microsoft net income by $3.1B and diluted EPS by $0.41** — *Disclosed* (10-Q; verified via The Register). Implied OpenAI quarterly loss ≈ **$11.5B** ($3.1B ÷ 27%) — *Estimated* (press back-calc). Pre-tax hit ~$4.1B.
- **Q2 FY26 (ended Dec 31 2025): net GAIN of +$7.6B to net income and +$1.02 to diluted EPS** from OpenAI investments — a **remeasurement gain tied to the restructuring**, NOT an operating profit — *Disclosed*. ⚠️ **Opposite sign from Q1 — easy to misread.**
- **Full-year FY2026: other income included ~$6.5B of net gains from OpenAI investments** (primarily net recognized gains on the equity-method investment) — *Disclosed* (per FY26 10-K summary). The one-time restructuring gain outweighed the recurring loss share for the full year.
- Per-quarter loss share beyond Q1/Q2 not separately verified. ⚠️ flagged.

### Stargate and Azure's role
- **Stargate** = OpenAI + SoftBank + Oracle (+ MGX), announced Jan 2025, up to **$500B over ~4 years** ($100B initial) — *Reported* / OpenAI-*Disclosed*.
- Stargate datacenters run on **Oracle Cloud Infrastructure, NOT Azure**; first site live in Abilene, TX (Sep 2025); more US sites announced — *Reported*.
- OpenAI states it committed (Jan 2025) to 10 GW in the US by 2029 and has "already surpassed that milestone," +3 GW in a recent 90-day window — *Disclosed* (via search-surfaced quote; openai.com returned 403 on direct fetch — ⚠️ primary URL not independently fetched).
- OpenAI **pulled back from a Stargate Norway project, with Microsoft taking it over** — *Reported* (CNBC, Apr 15 2026; ⚠️ 403 on fetch, headline-only).
- **Does Stargate dilute Azure's role? YES, materially** — it is OpenAI compute not on Azure, a direct consequence of Microsoft ceding its compute ROFR. Offsetting it: OpenAI simultaneously made the new $250B Azure commitment — *Reported*.

**⚠️ Area 2 unverified/flagged:** Apr-2026 revenue-share cap $-amount and %; historical ~20% rate (not confirmed as current — don't cite); OpenAI Foundation exact % (26–27% range across tallies); per-quarter OpenAI equity-method figures beyond Q1/Q2 FY26; several Apr-2026 terms are press-only (MEDIUM).

---

## AREA 3 — CUSTOM SILICON

### Maia 200 (codename "Braga")
- **Unveiled Jan 26, 2026** via official Microsoft blog (Scott Guthrie). Positioned as "the most performant first-party silicon any hyperscaler has deployed to date," **inference-focused** — *Disclosed*.
- **Specs (Disclosed, official blog):** TSMC 3nm (N3); **140B+ transistors**; **>10 PFLOPS FP4**; **>5 PFLOPS FP8**; **216GB HBM3e @ 7 TB/s**; **272MB on-chip SRAM**; **750W SoC TDP**; **2.8 TB/s bidirectional scale-up**; standard-Ethernet fabric scaling to **clusters of 6,144 accelerators** (4 Maia/tray, direct non-switched links).
- **Microsoft's performance claims (Disclosed as marketing, NOT independently verified):** "3× the FP4 performance of 3rd-gen Amazon Trainium"; "FP8 above Google's 7th-gen TPU"; "30% better performance/dollar than latest-gen hardware." ⚠️ The Register (Jan 26 2026) only independently framed Maia 200 vs **NVIDIA B200** (inference-only), did NOT verify the Trainium3/TPU-v7 claims, and stressed Maia is inference-only vs Blackwell's train+inference versatility.
- **Deployment (Disclosed):** running in **US Central (Des Moines, IA)**; **US West 3 (Phoenix, AZ)** next. Powers **OpenAI GPT-5.2**, **M365 Copilot**, **Microsoft Foundry**. **Not** a provisionable Azure VM SKU — customers benefit indirectly via Azure OpenAI/Copilot throughput.

### Maia 200 delay history
- Mass production **delayed ≥6 months, slipped 2025 → 2026** — *Reported* (DCD citing The Information, ~Jun 2025). Reasons: design changes (**OpenAI-requested features made the chip unstable in simulations**), staffing constraints, high turnover ("as many as one-fifth of staff on some chip design teams" left).

### Maia 100 (first gen) & Cobalt CPU
- **Maia 100** announced **Nov 2023** at Ignite, Microsoft's first in-house AI accelerator; Microsoft was **last of the big-4 hyperscalers** to field one — *Reported* (SemiAnalysis/GeekWire).
- **Cobalt 100:** 128-core Arm CPU, GA'd across Azure in 2024 — *Disclosed*.
- **Cobalt 200:** announced Ignite 2025 — **132 Arm Neoverse-V3 cores** (two 66-core chiplets), TSMC 3nm, per-core DVFS; claims **up to 50% better perf vs Cobalt 100**; production servers already in datacenters; **public Azure GA expected in 2026** — *Disclosed*.
- **Networking/HBM:** no standalone Microsoft networking ASIC disclosed; Maia 200 uses a **custom transport over standard Ethernet** (no proprietary switch chip). HBM effort = HBM3e sourcing on Maia 200 (216GB).

### How far behind AWS Trainium / Google TPU
- **Estimated 2026 deployment volumes (analyst/tracker models, NO primary source):** ~1.9M total hyperscaler custom accelerators — **~900k Google TPU, ~600k AWS Trainium, ~250k Microsoft Maia, ~180k Meta MTIA** — *Estimated*; directional only. ⚠️ flagged.
- **Maturity gap (Reported/Estimated):** Google leads on maturity/software/scale/external customers; AWS leads on raw commercial volume. Microsoft's Maia **"is not yet the backbone of Azure AI the way NVIDIA GPUs are"**; Azure AI infra "remains deeply tied to NVIDIA"; Microsoft/Meta are "catching up."

### Continued NVIDIA dependence
- **GB300 NVL72 — world's first large-scale production cluster on Azure (NDv6 GB300):** announced **Oct 9, 2025** (Azure blog). **>4,600 NVIDIA GB300 (Blackwell Ultra) GPUs**; per rack: 72 Blackwell Ultra + 36 Grace CPUs, 18 VMs, 37TB fast memory, up to 1,440 PFLOPS FP4, 130 TB/s NVLink intra-rack, 800 Gb/s/GPU cross-rack via Quantum-X800 InfiniBand. For **OpenAI** workloads. Stated goal: **"hundreds of thousands of Blackwell Ultra GPUs"** — *Disclosed*.
- **GB200 NVL2** clusters already in production for OpenAI/Microsoft on Azure — *Disclosed*.
- **Rubin:** Azure describes planning for "seamless large-scale NVIDIA Rubin deployments" — continued NVIDIA roadmap dependence — *Disclosed/Reported*.

### AMD Instinct usage
- **MI300X:** in production — **Azure ND MI300X v5 VMs** power Azure OpenAI Service (GA from ~2024) — *Disclosed* (AMD IR).
- **MI355X / MI350X:** **No confirmed Azure GA found.** MI355X (launched Q3 2025) is GA on Oracle OCI, CoreWeave, Vultr, DigitalOcean — but **Azure MI355X/MI350X not verified** — ⚠️ *Unverified*.

**⚠️ Area 3 unverified/flagged:** Maia 200 vs Trainium3/TPU-v7 claims = Microsoft marketing, not independently benchmarked; 2026 volume estimates are analyst models with no primary source; AMD MI355X on Azure not verified (only MI300X confirmed).

---

## AREA 4 — AZURE / CLOUD FINANCIALS

### FY2026 Q1 (quarter ended Sep 30 2025; released Oct 29 2025) — all *Disclosed*
| Metric | Value |
|---|---|
| Total revenue | **$77.7B, +18% YoY** (+17% cc) |
| Operating income | **$38.0B, +24% YoY** (+22% cc) |
| **Microsoft Cloud revenue** | **$49.1B, +26% YoY** (+25% cc) |
| Microsoft Cloud gross margin | **~68%** (down YoY on AI investment) |
| **Intelligent Cloud revenue** | **$30.9B, +28% YoY** (+27% cc) |
| **Azure & other cloud services growth** | **+40% YoY (+39% cc)** — beat ~38% consensus |
| **Commercial RPO (backlog)** | **$392B, +51% YoY** |

### Azure growth by fiscal quarter (FY2026)
- **FY26 Q1 (CY Jul–Sep 2025): +40% (+39% cc)** — *Disclosed*.
- **FY26 Q2 guidance (CY Oct–Dec 2025): "approximately 37% in constant currency"** (Amy Hood) — *Disclosed* (guidance, not actual).
- FY26 Q3/Q4 Azure actuals: **not confirmed in fetched sources** in this research pass (only Q1 actual + Q2 guidance verified). ⚠️ flagged. (Note: Q4 FY26 press release did confirm **Azure surpassed $100B annual revenue** — *Disclosed* via news.microsoft.com — but the quarterly Azure growth % for Q3/Q4 was not pinned here.)

### Azure AI contribution to growth
- **Not quantified.** The Q1 FY26 call stated only that **"Azure AI services revenue was generally in line with expectations"** and did NOT break out points of growth from AI — *Disclosed* (explicitly not disclosed as a figure). ⚠️ no verified "X points from AI" number.
- Adoption context: Nadella cited **900M monthly active users of AI features** and **>150M MAU of first-party Copilots** (Q1 FY26) — *Disclosed*.

### Intelligent Cloud operating margin
- **~43%** per earnings-call commentary (down slightly YoY; AI investment mostly offset by operating leverage) — *Disclosed* (transcript). ⚠️ management's stated figure; exact IC segment operating-income line not independently recomputed.

### Capacity-constraint commentary (Disclosed direct quotes, Q1 FY26 call, Oct 29 2025)
- **Amy Hood:** "We now expect to be **capacity constrained through at least the end of our fiscal year**, with **demand exceeding current infrastructure build-out, resulting in lost revenue opportunities for Azure**..."
- On Q2 guidance: "...as **demand remains significantly ahead of the capacity** we have available."
- **Satya Nadella (BG2 podcast, week of Nov 3 2025):** "you may actually have a bunch of chips sitting in inventory that I can't plug in... It's not a supply issue of chips; it's the fact that I don't have **warm shells** to plug into." — *Disclosed quote* (via TechCrunch, Nov 3 2025). ⚠️ one search summary mis-dated this to Nov 2024; verified date is **early Nov 2025**.

**⚠️ Area 4 unverified/flagged:** no "points of Azure growth from AI" figure; IC 43% margin is management's stated figure (not recomputed); FY26 Q3/Q4 Azure quarterly growth % not pinned (only Q1 actual +40% and Q2 guidance +37% cc; Azure crossed $100B annual by Q4).

---

## AREA 5 — COPILOT / APPLICATION LAYER

### Microsoft 365 Copilot ($30/user/mo) — seats & traction
- **Over 30 million paid seats** — FY26 Q4 (call Jul 29 2026); net paid-seat adds "more than doubled" sequentially, fastest quarterly pace in product history — *Disclosed*.
- Seat timeline: **15M** (FY26 Q2, Jan 28 2026, *Reported*) → **20M** (FY26 Q3, Apr 29 2026, +5M in quarter, *Reported*) → **30M+** (FY26 Q4).
- **Over 90% of the Fortune 500** use M365 Copilot (FY26 Q1, Oct 2025; repeated Ignite Nov 18 2025) — *Disclosed*. ⚠️ A conflicting ~70% figure also surfaced in some 2026 press — treat **70–90% as a range across time/scope**; 90%+ is the figure attributed directly to Nadella.
- Customers with **50,000+ seats grew >7× YoY** (FY26 Q4; was "quadrupled YoY" at FY25 Q3) — *Reported*.
- Named rollouts: **NHS England 505,000; HSBC 200,000; EY ~400,000** (FY26 Q4); earlier Accenture **740,000+**, Barclays 100,000, UBS all-employees, PwC 200,000+ — *Disclosed/Reported*.
- Engagement context: **900M MAU of AI features**; **150M MAU first-party Copilots** (FY26 Q1) — *Disclosed*.

### Disclosed AI / Copilot revenue run-rate
- **AI business annual run-rate >$13B (+175% YoY)** — FY25 Q2 (Jan 2025) — *Disclosed*.
- **AI business annual run-rate >$37B (+123% YoY)** — FY25 Q3 (Apr 2025) — *Disclosed*. ⚠️ **Not restated since — stale; do not present as current.**
- **Copilot revenue accelerated >60% sequentially after usage-based billing** — FY26 Q4 (Jul 29 2026) — *Reported*. ⚠️ scope muddy (M365 vs GitHub) across sources.
- **Microsoft has NEVER disclosed a standalone M365-Copilot or GitHub-Copilot-only revenue dollar figure.** Any pure-Copilot revenue number is *Estimated/Speculative*.

### GitHub Copilot — subscribers & revenue
- **Over 4.7 million paid subscribers (+~75% YoY)** — Jan 28 2026 (FY26 Q2), per GitHub COO Kyle Daigle — *Disclosed*. (Supersedes stale "1.3M" on aggregators.)
- **Over 20 million all-time users** — Jul 30 2025 (FY25 Q4); GitHub confirmed this is *all-time*, not active; 26M cited FY26 Q1 — *Disclosed*.
- **~90% of the Fortune 100** use GitHub Copilot; **140,000 organizations** — *Disclosed*.
- **Revenue:** last official framing — **GitHub total run-rate $2B; Copilot >40% of GitHub's revenue growth** (FY24 Q4, Jul 31 2024) — *Disclosed*. Any Copilot-only figure is *Estimated*.

### Pricing → consumption / agents (the shift)
- Baseline M365 Copilot **$30/user/mo**; new SMB **Microsoft 365 Copilot Business = $21/user/mo** from Dec 2025 — *Disclosed*.
- Nadella (Jul 29 2026): "first time... an enterprise-wide tool with both a per-seat and usage-based pricing. The TAM is much more expansive." — *Reported*.
- **Copilot Credits** replaced "messages" on **Sept 1 2025** — *Reported/Disclosed*.
- **Copilot Studio pricing (Disclosed):** prepaid **$200/pack/mo = 25,000 Copilot Credits**; **pay-as-you-go $0.01/credit** (Azure-billed); per-action rates (classic answer 1, generative 2, agent action 5, tenant-graph grounding 10, premium/reasoning ~100 per 10 responses).
- **GitHub AI Credits** replaced premium-request units **effective Jun 1 2026**; **1 credit = $0.01**; tiers Free $0 / Pro $10 / Pro+ $39 / Max $100 (+Business/Enterprise); agent mode across all tiers incl. Free — *Disclosed*.

### Copilot Studio & agent-building
- **1M+ custom agents built (Copilot Studio + SharePoint) in one quarter (+130% QoQ)** across **230,000+ organizations** (incl. 90% Fortune 500) — FY25 Q3 (Nadella) — *Disclosed*.
- **Agent 365** (unified control plane) announced Ignite 2025 (Nov 18 2025); **~40M agents registered** ~2 months post-launch (Nadella, FY26 Q4) — *Disclosed*. IDC projection Microsoft cites: **1.3 billion agents by 2028** — *Reported* (IDC, not a Microsoft number).

### Security Copilot
- **GA Apr 1 2024** as capacity-based service; **~$4/Security Compute Unit (SCU)/hr** provisioned (⚠️ example-only on pricing page — *Reported*); **$6/SCU/hr overage** — *Disclosed*.
- **6 Microsoft + 5 partner security agents** announced Mar 24 2025; dozen+ embedded in Defender/Entra/Intune/Purview by late 2025 — *Disclosed*.
- **E5/E7 inclusion** (Ignite 2025, Nov 18 2025): **400 SCUs/mo per 1,000 paid E5 licenses, up to 10,000 SCUs/mo** — *Disclosed*.

### Dynamics 365 Copilot
- **Sales Agent** + customer-service agents GA; as of Sep 2025 offered to M365 Copilot paying customers at no extra cost; consume Copilot Credits — *Reported/Disclosed*.
- FY26 Q4: Dynamics 365 customer-service consumption-based credit usage **rose ~4× sequentially** — *Reported*.
- ⚠️ The customer-service agent in the original 10 (introduced Oct 21 2024) is the **Case Management Agent** (GA Oct 31 2025), not literally "Customer Service Agent." The **"$500M saved"** figure = Microsoft's internal call-center AI (leaked Jul 2025 deck), **NOT** the Dynamics Sales Agent — common conflation to avoid.

### Copilot consumer (free / Pro $20)
- Copilot bundled into **M365 Personal & Family** on Jan 16 2025 — **+$3/mo** (Personal $69.99→$99.99/yr; Family $99.99→$129.99/yr); includes AI credits (now 60/mo) — *Disclosed* (+$3, credits) / *Reported* (absolute prices).
- **Copilot Pro ($20/mo) discontinued for new customers Oct 1 2025**, replaced by **Microsoft 365 Premium ($19.99/mo / $199.99/yr)** bundling Office + 1TB + Copilot Chat + agents — *Reported*.
- Consumer app **daily users grew ~50% QoQ** (FY26 Q1) — *Disclosed*. Standalone consumer MAU not officially disclosed (third-party "420M all-surface" is *Estimated*).
- **UK CMA opened an investigation (Jul 29 2026)** into whether Microsoft misled consumers via auto-upgrades to Copilot-bundled plans vs cheaper Classic tiers — *Reported*.

**⚠️ Area 5 unverified/flagged:** $37B/+123% AI run-rate is stale (Apr 2025); "+60%" Copilot growth scope muddy; no standalone M365/GitHub Copilot revenue $; "$500M saved" is call-center AI not Sales Agent; Security Copilot alert-triage metrics (6.5×/77%/53%) unverified; consumer MAU absolute figures estimated.

---

## AREA 6 — MICROSOFT'S OWN MODELS & AI ORG

### Microsoft AI org (Mustafa Suleyman)
- Suleyman (ex-DeepMind co-founder, ex-Inflection) joined **Mar 2024** as **EVP & CEO of Microsoft AI** — *Disclosed*.
- **MAI Superintelligence Team** announced **Nov 6 2025** — mission "**Humanist Superintelligence (HSI)**"; focus AI Companions, **Medical Superintelligence** (cites MAI-DxO ~85% on medical cases), Clean Energy — *Disclosed*.
- **Self-sufficiency strategy (FT, ~Feb 12 2026):** "We have to develop our own foundation models, which are at the absolute frontier... That's our true self-sufficiency mission." — *Reported* (direct quote).
- **Strategic pivot:** Apr 4 2025 Suleyman described a deliberately trailing **"off-frontier"/"tight second"** strategy (models "3–6 months behind"); by early 2026 shifted to "**at the absolute frontier**" — *Reported*.
- **Mar 2026 reorg:** Suleyman shifted off day-to-day Copilot oversight to focus on frontier model development — *Reported*.
- Headcount not officially disclosed ("lean"); any number is *Speculative*.

### MAI models
- **MAI-1-preview** — announced **Aug 28 2025**; **mixture-of-experts**; trained on **~15,000 NVIDIA H100 GPUs**; on LMArena (~#13); rolling into Copilot text scenarios; **parameter count NOT disclosed** — *Disclosed*.
- **MAI-Voice-1** — Aug 28 2025; **~1 min of audio in <1 sec on a single GPU**; powers Copilot Daily/Podcasts/Labs — *Disclosed*.
- **Apr 2 2026:** MAI-Voice-1, **MAI-Transcribe-1, MAI-Image-2** GA in Microsoft Foundry — *Disclosed*.
- **Build 2026 (Jun 2 2026): seven new in-house MAI models** — **MAI-Thinking-1** (flagship reasoning), MAI-Code-1-Flash, MAI-Image-2.5(+Flash), MAI-Transcribe-1.5, MAI-Voice-2(+Flash); emphasizes in-house training, custom silicon (Maia 200), **no distillation from external labs** — *Disclosed*. MAI-Thinking-1 specs (~35B active/~1T total, 256K context) are *Reported/secondary*, not official. ⚠️ don't attribute these specs to MAI-1-preview.
- Stated ambition: general-purpose GPT-5-class LLM by ~2027 — *Reported/Speculative*.

### Phi small-model family (all on Azure AI Foundry + Hugging Face, MIT)
| Model | Params | Date | Tag |
|---|---|---|---|
| Phi-4 | 14B | Dec 12 2024 (preview); MIT weights Jan 8 2025 | Reported/Disclosed |
| Phi-4-mini / -multimodal | 3.8B / 5.6B | Feb 26 2025 | Disclosed |
| Phi-4-reasoning / -plus / -mini-reasoning | 14B / 14B / 3.8B | Apr 30 2025 | Disclosed |
| Phi-4-mini-flash-reasoning | 3.8B (SambaY) | Jul 9 2025 | Disclosed |
| Phi-4-reasoning-vision-15B (latest) | 15B multimodal | Mar 4 2026 | Disclosed |
| **Phi-5** | — | **No official release as of 2026-08-05** | Speculative |

### Model router / multi-model
- **Azure AI Foundry "model router":** preview May 2025 (Build), GPT-5 support Aug 2025, **GA Nov 2025 (Ignite)** — routes across OpenAI, xAI Grok, DeepSeek, Meta Llama, gpt-oss, **and Anthropic Claude**; Microsoft claims "up to 50% lower latency, ~15% quality improvement" — *Disclosed*.
- **M365 Copilot** uses **GPT-5's real-time router** to auto-select fast vs deep-reasoning models (GPT-5 in M365 Copilot Aug 7 2025) — *Disclosed*.

### Anthropic Claude in Microsoft products — THREE separate doors, three dates
- **(a) GitHub Copilot — EARLIEST:** Claude 3.5 Sonnet public preview **Nov 1 2024**; then 3.7 Sonnet (Feb 2025), Sonnet 4/Opus 4 (GA Jun 25 2025), Opus 4.1 (Sep 23 2025), Sonnet 4.5 (Oct 13 2025), Haiku 4.5 incl. Copilot Free (Nov 10 2025), Opus 4.5 (Dec 18 2025), later 4.6+ — *Disclosed* (github.blog changelog).
- **(b) M365 Copilot & Copilot Studio — Sept 24 2025:** **Claude Opus 4.1** as alternative engine for **Researcher**; **Claude Sonnet 4 + Opus 4.1** selectable in **Copilot Studio**; admin opt-in, OpenAI default — *Disclosed*. Opus 4.5 added to Copilot Studio Nov 24 2025.
- **(c) Azure / Microsoft Foundry — Nov 18 2025:** Microsoft + NVIDIA + Anthropic **strategic partnership**; Claude (Sonnet 4.5, Opus 4.1, Haiku 4.5) GA in Foundry catalog — "Azure is the only cloud with both Claude and GPT frontier models" (Asha Sharma). Deal: Anthropic to buy **$30B** Azure compute; NVIDIA up to **$10B** and Microsoft up to **$5B** into Anthropic — *Disclosed*. Azure-hosted Claude (on NVIDIA GB300) GA **Jun 29 2026**. Later Opus 4.6 (Feb 5 2026) — *Disclosed*.

**⚠️ Area 6 unverified/flagged:** MAI-1-preview parameter count undisclosed; MAI-Thinking-1 specs are secondary; Phi-5 does not exist; MAI org headcount not disclosed; premise correction — there was NO distinct ~Sept 2025 Azure Foundry Claude launch (Sept 24 was M365/Studio; Foundry catalog was Nov 18 2025).

---

## AREA 7 — AZURE AI PLATFORM

### Naming & positioning
- Azure AI Studio → **Azure AI Foundry** (Ignite 2024, Nov 2024); at Ignite 2025 (Nov 2025) rebranded again to **"Microsoft Foundry"** (dropped "Azure") — *Reported/Disclosed*.
- Positioning: "**AI app and agent factory**" — unified platform to build, govern, scale agents — *Disclosed* (May 19 2025).

### Models catalog
- **"over 10,000 models"** (Foundry Models, incl. Hugging Face OSS) — May 19 2025 — *Disclosed*.
- **"more than 11,000 frontier models"** — Nov 18 2025 (Microsoft Foundry blog) — *Disclosed*. Growing 10k→11k over 2025.
- Notable adds through 2025: Grok 3 (xAI), Flux Pro 1.1, Sora, GPT-5 family, DeepSeek V3.2 (preview Dec 15 2025), Anthropic Claude — *Reported/Disclosed*.

### Foundry Agent Service
- **GA at Build 2025 (May 2025)** — *Disclosed*.
- Connects to **"1,400 enterprise data sources"** (May 2025) → **"more than 1,400 connectors"** (Nov 2025); **"over 1,000 curated Microsoft and partner tools"** — *Disclosed*.
- Supports custom-code agents from Microsoft Agent Framework, LangGraph, CrewAI into a managed runtime; governed MCP-tool catalog — *Disclosed*.
- Named adopters: KPMG, NTT DATA, Fujitsu, YoungWilliams, Aon — *Disclosed*.

### Developer / usage traction
- **"more than 70,000 customers"** on Azure AI Foundry (May 19 2025) — *Disclosed*.
- **"More than 10,000 organizations"** using Foundry Agent Service (May 2025) — *Disclosed*.
- **"100 trillion tokens last quarter"** processed (May 2025) — *Disclosed*.
- **"2 billion daily enterprise search queries"** (May 2025) → **"more than 3 billion/day"** (Nov 2025) — *Disclosed*.
- Broader (GitHub/Copilot-wide, NOT Foundry-specific) at Ignite 2025: 180M+ GitHub developers, 26M+ GitHub Copilot users, 500M+ PRs merged with AI coding agents this year, Foundry Local on 560M devices — *Disclosed*.
- ⚠️ **No Foundry-specific "# of agents deployed" or "# of developers" aggregate disclosed** in fetched primary sources. Press "80,000 enterprises / 80% Fortune 500 on Foundry" appeared only in secondary summaries — *Unverified*.

### Microsoft Fabric (data + AI)
- **"over 28,000 customers,"** incl. 80% of the Fortune 500 — *Reported* (Ignite 2025 coverage; exact 28,000 not confirmed vs a primary Fabric blog).
- Ignite 2025: launched **Fabric IQ**, expanded **Fabric Data Agents**; Foundry integrates "Foundry IQ with Microsoft Fabric IQ and Work IQ from M365 Copilot" — *Disclosed* (Nov 18 2025).

**⚠️ Area 7 unverified/flagged:** no Foundry-specific agent-count or developer-count aggregate; "80,000 enterprises / 80% Fortune 500 on Foundry" and Fabric "28,000 customers" are secondary/unconfirmed; model count is date-dependent (10k May → 11k Nov 2025).

---

## AREA 8 — POWER / ENERGY

### Three Mile Island / Constellation "Crane Clean Energy Center" (fission — headline deal)
- **20-year PPA** with Microsoft, announced **Sept 20 2024** — *Disclosed* (Constellation).
- Restarts **TMI Unit 1**, renamed **Crane Clean Energy Center (CCEC)**; adds **~835 MW** carbon-free power — *Disclosed*.
- Original in-service target **2028** — *Disclosed*. ⚠️ **Accelerated to 2027**: per the one-year update (Constellation, **Sept 23 2025**), accelerated PJM interconnection moved the restart to **2027**, one year early; plant ~80% staffed (~500 FTEs). **Range: 2027 (current) vs 2028 (original).**
- Capex ~**$1.6B** to restart — *Reported* (Utility Dive). License extension filing to NRC through at least **2054** — *Disclosed*.
- Economic impact: 3,400 direct+indirect jobs, >$3B state/federal taxes, $16B added to PA GDP — *Disclosed*. ~$1B DOE loan reported Nov 2025 — *Reported* (NucNet).
- ⚠️ This is a **large conventional reactor restart, NOT an SMR.**

### Helion fusion agreement
- **World's first fusion PPA**, announced **May 10 2023** — *Disclosed* (Helion/CNBC).
- Microsoft to offtake **50 MW or greater** after a 1-year ramp; target online **2028** — *Disclosed*. Constellation is power marketer/transmission manager.
- Plant: **Orion**, Chelan County, WA; construction underway (2025); long-term aim ~1 GW — *Reported* (DCD/NucNet).
- ⚠️ Fusion at commercial scale is unproven — treat 2028 delivery as *Speculative*.

### Other nuclear / SMR PPAs
- **No separately verified Microsoft SMR PPA found.** Microsoft is reported to be *exploring* SMRs, but no signed SMR offtake confirmed. Confirmed nuclear commitments = **Crane fission restart + Helion fusion** — *Reported/unverified*.

### Renewable / carbon-free portfolio
- **34 GW of carbon-free electricity contracted across 24 countries** (~18× vs 2020) — *Disclosed* (Microsoft 2025 Environmental Sustainability Report, May 29 2025). In 2024 alone: **19 GW new renewables across 16 countries** — *Disclosed*.
- ⚠️ Later press: **40+ GW across 26 countries via 400+ agreements**, ~19 GW online, matching **100% of 2025 electricity use** with renewables — *Reported* (DCD, 2025–26). **Range: 34 GW (official May 2025) → 40+ GW (press, later).**
- **Brookfield framework agreement:** pathway for **>10.5 GW** of new renewables (US/Europe), ~8× the largest prior corporate PPA — *Reported/Disclosed* (2024).

### Data-center power-constraint commentary
- **Nadella (BG2 podcast, week of Nov 3 2025):** "warm shells" quote — chips sitting in inventory that can't be plugged in for lack of powered shells (see Area 4) — *Disclosed*.
- **Brad Smith** (blog on ~$80B FY25 DC capex): pledged Microsoft "will pay our way... to ensure our data centers don't increase your electricity prices" — *Disclosed*. Reiterated CNBC Jan 13 2026 — *Reported*.

**⚠️ Area 8 unverified/flagged:** Crane restart 2027 (current) vs 2028 (original); renewables 34 GW (official) vs 40+ GW (press); no signed Microsoft SMR PPA verified; Helion 2028 delivery speculative.

---

## AREA 9 — MICROSOFT-SPECIFIC COMPETITIVE / STRATEGIC CONTEXT

### OpenAI-as-frenemy dynamic
- **OpenAI cloud diversification:** post-Oct-2025, OpenAI splits workloads across **AWS (7-yr, $38B, signed Nov 3 2025), Oracle (~$300B), CoreWeave (~$22.4B total), Google Cloud**, in addition to Microsoft — *Reported*. Aggregate ~$1.15T committed across ~7 vendors (Broadcom $350B, Oracle $300B, Microsoft $250B, NVIDIA $100B, AMD $90B, AWS $38B, CoreWeave $22B) — *Reported/Estimated* (press aggregation; individual line items firmer than the sum).
- **Stargate** (OpenAI + SoftBank + Oracle + MGX, Jan 2025): $500B / up to 10 GW; runs on **Oracle OCI, not Azure**; original Microsoft $100B/5GW mega-DC talks reportedly fell apart in 2024 — *Reported*. OpenAI pulled back from **Stargate Norway; Microsoft took it over** — *Reported* (CNBC, Apr 15 2026; ⚠️ 403/headline-only).
- **Direct competition (PYMNTS, May 12 2025):** four vectors — ChatGPT vs Copilot (consumer), OpenAI API vs Azure OpenAI (dev services), OpenAI's own DCs vs Microsoft footprint (infra), OpenAI signing Fortune 500 enterprise deals — *Reported*.
- **Enterprise share shift:** ChatGPT winning against Copilot in some accounts (Bloomberg, Jun 24 2025: Amgen bought Copilot for 20,000 employees; ~13 months later employees were using ChatGPT) — *Reported*. OpenAI crossed **1M business customers (Nov 2025)** and **7M+ ChatGPT workplace seats** — *Reported*. ChatGPT **800M+ weekly active users (Dec 2025)** — *Disclosed (OpenAI, via search)*.
- **OpenAI browser:** **ChatGPT Atlas** launched **Oct 21 2025** (Chromium, macOS first) with Agent Mode — adjacent to Edge/Copilot — *Disclosed*.

### Model competition & Microsoft's hedging
- **Rivals:** Google Gemini + Anthropic Claude framed as competitive pressure on the OpenAI models Microsoft resells (Fortune, May 21 2026) — *Reported*.
- **xAI Grok:** Grok 3 + Grok 3 mini added to Azure AI Foundry at Build (May 19 2025), hosted/billed by Microsoft; Musk appeared with Nadella; Copilot did NOT switch off GPT to Grok — *Reported*.
- **Anthropic Claude (major hedge):** added across GitHub Copilot (Nov 2024) → M365 Copilot/Studio (Sept 24 2025) → Foundry catalog (Nov 18 2025) — see Area 6. "Azure is the only cloud providing both Claude and GPT frontier models on one platform" (Asha Sharma) — *Disclosed*.
- **Own models (MAI):** MAI-Voice-1 + MAI-1-preview (Aug 28 2025); multi-source model strategy — see Area 6 — *Disclosed*.

### Enterprise-distribution advantage (the moat framing)
- **M365 commercial installed base: 450 million+ commercial paid seats** — *Disclosed* (via Nadella statements).
- **M365 Copilot paid seats 30M+** (FY26 Q4); **>90% Fortune 500** (⚠️ 70–90% range across sources) — see Area 5.
- Named proof point: **Accenture 740,000+ Copilot seats** — *Reported*.
- **Counter-signal:** CNBC (Nov 23 2025) — Microsoft faces an "uphill climb" turning enterprise dominance into chatbot adoption vs ChatGPT — *Reported*.
- ⚠️ **No verbatim "distribution is our moat" Nadella quote verified** — the framing rests on his penetration/seat statistics plus press interpretation.

**⚠️ Area 9 unverified/flagged:** several OpenAI/CNBC pages 403'd (Stargate 10GW-surpassed, Norway handoff verified via headline/search only); Fortune 500 penetration 70% vs 90% range; $1.15T aggregate is press aggregation; no direct "distribution is the moat" executive quote.

---

# CONSOLIDATED SOURCE LIST

## Tier 1 — Official (Microsoft / OpenAI / GitHub / Anthropic / partners)

**Financials / filings**
- MSFT FY26 Q4 earnings (press release + call) — https://www.microsoft.com/en-us/investor/earnings/fy-2026-q4/press-release-webcast — *authoritative FY26 lines: cash PP&E $115.9B, D&A $38.5B, OCF $182.9B, Q4 capex $41B/$5.6B leases, FY27 guidance, $175B CY26, useful-life 15→25yr change, 88 DCs, Azure >$100B, 30M Copilot seats.*
- MSFT FY26 Q1/Q2/Q3 earnings — https://www.microsoft.com/en-us/investor/events/fy-2026/earnings-fy-2026-q1 (+q2/q3) — *quarterly capex/lease splits, "growth higher than FY25" reversal, two-thirds short-lived assets, $190B CY26, capacity-constrained quotes, Azure +40%/+37% cc, RPO $392B.*
- MSFT FY25 Q4 cash flows/call — https://www.microsoft.com/en-us/investor/earnings/fy-2025-q4/cash-flows — *FY25 PP&E $64.55B, FY24 $44.48B; D&A; Q4 FY25 $24.2B/$6.5B leases.*
- MSFT FY2026 10-K (SEC) — https://www.sec.gov/Archives/edgar/data/0000789019/000119312526323660/msft-20260630.htm — *annual filing; finance-lease + OpenAI equity-method disclosures; ~$6.5B FY26 net OpenAI gains.*
- MSFT Q1 FY26 8-K/10-Q (SEC) — https://www.sec.gov/Archives/edgar/data/789019/000119312526027198/msft-ex99_1.htm — *$3.1B/$0.41 OpenAI loss hit; $13B/$11.6B funded.*
- MSFT FY26 Q1 8-K (SEC) — https://www.sec.gov/Archives/edgar/data/0000789019/000119312526323632/msft-ex99_1.htm — *official Q1 FY26 segment + consolidated figures.*

**OpenAI relationship**
- Microsoft blog, "The next chapter of the Microsoft–OpenAI partnership" (Oct 28 2025) — https://blogs.microsoft.com/blog/2025/10/28/the-next-chapter-of-the-microsoft-openai-partnership/ — *27%/$135B stake, IP through 2032 / research to 2030, expert-panel AGI verification, $250B Azure, ROFR removal, independently-pursue-AGI right.*
- OpenAI blog, same title (Oct 28 2025) — https://openai.com/index/next-chapter-of-microsoft-openai-partnership/ — *OpenAI-side confirmation.*
- OpenAI, Stargate announcement — https://openai.com/index/announcing-the-stargate-project/ — *Stargate scale/partners; Foundation controls PBC.*
- Microsoft blog (Apr 27 2026) — https://blogs.microsoft.com/blog/2026/04/27/... — *OpenAI exclusivity ends; non-exclusive license.*

**Silicon / infra**
- Maia 200 official blog (Scott Guthrie, Jan 26 2026) — https://blogs.microsoft.com/blog/2026/01/26/maia-200-the-ai-accelerator-built-for-inference/ — *all Maia 200 specs + Trainium3/TPU-v7 claims.*
- Cobalt 200 (Nov 2025) — https://techcommunity.microsoft.com/blog/azureinfrastructureblog/announcing-cobalt-200-azures-next-cloud-native-cpu/ — *132 Neoverse-V3 cores, 3nm, +50% vs Cobalt 100.*
- Azure GB300 NVL72 blog (Oct 9 2025) — https://azure.microsoft.com/en-us/blog/microsoft-azure-delivers-the-first-large-scale-cluster-with-nvidia-gb300-nvl72-for-openai-workloads/ — *>4,600 GB300 GPUs; OpenAI; NVIDIA dependence.*
- AMD IR (Azure MI300X) — https://ir.amd.com/news-events/press-releases/ — *ND MI300X v5 VMs power Azure OpenAI Service.*

**Copilot / models / platform**
- MSFT FY26 Q4 Source blog (Jul 29 2026) — https://news.microsoft.com/source/2026/07/29/ — *30M+ Copilot seats; Azure >$100B.*
- Copilot Studio pricing — https://www.microsoft.com/microsoft-365-copilot/pricing/copilot-studio — *$30/user/mo, $200/25k Credits, PAYG.*
- M365 Copilot PAYG — https://learn.microsoft.com/microsoft-365/copilot/pay-as-you-go/overview — *usage-based service scope (dated 2026-07-17).*
- GitHub Copilot plans + billing — https://github.com/features/copilot/plans and https://github.blog/changelog/ — *tiers, AI Credits ($0.01), Claude-in-Copilot preview/GA dates.*
- M365 Copilot model choice (Sept 24 2025) — https://www.microsoft.com/microsoft-365/blog/2025/09/24/expanding-model-choice-in-microsoft-365-copilot/ — *Claude Sonnet 4 + Opus 4.1 in M365/Studio.*
- Ignite 2025 Copilot/agents (Nov 18 2025) — https://www.microsoft.com/microsoft-365/blog/2025/11/18/ — *90% Fortune 500, Agent 365, Copilot Business $21.*
- Security Copilot GA — https://www.microsoft.com/security/blog/2024/03/13/ and E5 inclusion https://www.microsoft.com/security/blog/2025/11/18/ — *SCU pricing; E5/E7 inclusion.*
- microsoft.ai — MAI models https://microsoft.ai/news/two-new-in-house-models/ (Aug 28 2025); HSI team https://microsoft.ai/news/towards-humanist-superintelligence/ (Nov 6 2025); seven MAI models https://microsoft.ai/news/building-a-hillclimbing-machine-launching-seven-new-mai-models/ (Jun 2 2026) — *Microsoft's own-model strategy.*
- Azure AI Foundry (May 19 2025) — https://azure.microsoft.com/en-us/blog/azure-ai-foundry-your-ai-app-and-agent-factory/ — *70k customers, 100T tokens, 10k+ models, Agent Service GA.*
- Microsoft Foundry (Nov 18 2025) — https://azure.microsoft.com/en-us/blog/microsoft-foundry-scale-innovation-on-a-modular-interoperable-and-secure-agent-stack/ — *11,000+ models, 3B queries/day, 1,400 connectors, Fabric IQ, rename.*
- Claude in Foundry (Nov 18 2025) — https://azure.microsoft.com/en-us/blog/introducing-anthropics-claude-models-in-microsoft-foundry-bringing-frontier-intelligence-to-azure/ ; Azure-hosted GA (Jun 29 2026) — https://azure.microsoft.com/en-us/blog/claude-in-microsoft-foundry-is-now-generally-available/ — *Claude hedge; "only cloud with both Claude and GPT."*
- Anthropic — https://www.anthropic.com/news/microsoft-nvidia-anthropic-announce-strategic-partnerships ; https://claude.com/blog/claude-now-available-in-microsoft-365-copilot — *$30B Azure / $10B NVIDIA / $5B MSFT terms; Sept-2025 M365 confirmation.*

**Power / energy**
- Constellation — Crane launch (Sept 20 2024) https://www.constellationenergy.com/news/2024/Constellation-to-Launch-Crane-Clean-Energy-Center-Restoring-Jobs-and-Carbon-Free-Power-to-The-Grid.html ; one-year update (Sept 23 2025) https://www.constellationenergy.com/news/2025/09/one-year-later-crane-clean-energy-center-still-in-the-spotlight-and-ahead-of-schedule.html — *20-yr PPA, 835 MW, 2028→2027 restart.*
- Helion (May 10 2023) — https://www.helionenergy.com/newsroom/helion-announces-worlds-first-fusion-ppa-with-microsoft — *50 MW+, 2028, 1-yr ramp.*
- Microsoft 2025 Sustainability Report (May 29 2025) — https://blogs.microsoft.com/on-the-issues/2025/05/29/environmental-sustainability-report/ — *34 GW CFE / 24 countries, 19 GW added 2024.*

## Tier 2 — Credible press

- CNBC — OpenAI restructure/Microsoft shareholder (Oct 28 2025) https://www.cnbc.com/2025/10/28/open-ai-for-profit-microsoft.html ; $3.1B net-income hit (Oct 29 2025) https://www.cnbc.com/2025/10/29/microsoft-open-ai-investment-earnings.html ; Q3 FY26 $190B CY26 (Apr 29 2026) ; Q4 FY26 (Jul 29 2026) ; communities/energy prices (Jan 13 2026) https://www.cnbc.com/2026/01/13/microsoft-data-centers-energy-ai-prices.html — *equity-method impacts, capex, energy pledge.*
- The Register — Maia 200 skepticism (Jan 26 2026) https://www.theregister.com/2026/01/26/microsoft_maia_200/ ; implied OpenAI ~$11.5B quarterly loss (Oct 29 2025) https://www.theregister.com/software/2025/10/29/microsoft-earnings-suggest-115b-openai-quarterly-loss/ — *independent silicon check; loss derivation.*
- TIME — $135B stake (Oct 2025) https://time.com/7329062/openai-microsoft-investment-restructure/ — *Foundation $130B, prior 32.5%, $25B commitment, AG review.*
- Forbes — exclusivity/rev-share end (Apr 27 2026) https://www.forbes.com/sites/aliciapark/2026/04/27/ — *Apr-2026 multi-cloud + rev-share cap.*
- CFO Dive — "capex to grow at slower rate" (May 1 2025) https://www.cfodive.com/news/microsoft-capex-grow-slower-rate-cfo-ai/746947/ — *moderation guidance later reversed.*
- Data Center Dynamics — $11.1bn Q1 2026 leases ; 88 DCs FY2026 ; Maia 200 delay ; Helion 50MW ; 40GW+ renewables ; GPUs "in inventory" — https://www.datacenterdynamics.com/ — *buildout scale, silicon delay, energy.*
- Utility Dive — Crane ~$1.6B / 2028 https://www.utilitydive.com/news/constellation-three-mile-island-nuclear-power-plant-microsoft-data-center-ppa/727652/ — *restart capex/PJM.*
- TechCrunch — Nadella "warm shells" (Nov 3 2025) https://techcrunch.com/2025/11/03/altman-and-nadella-need-more-power-for-ai-but-theyre-not-sure-how-much/ ; Grok 3 to Azure (May 19 2025) https://techcrunch.com/2025/05/19/xais-grok-3-comes-to-microsoft-azure ; GitHub Copilot 20M all-time (Jul 30 2025) — *power constraint; model hedge; user metric.*
- Bloomberg — ChatGPT vs Copilot (Jun 24 2025) https://www.bloomberg.com/news/articles/2025-06-24/chatgpt-vs-copilot-inside-the-openai-and-microsoft-rivalry — *enterprise share shift; Amgen example.*
- PYMNTS — Microsoft protects turf (May 12 2025) https://www.pymnts.com/artificial-intelligence-2/2025/microsoft-moves-to-protect-its-turf-as-openai-turns-into-rival — *four OpenAI-vs-Microsoft vectors.*
- Fortune — Copilot vs Gemini/Claude (May 21 2026) https://fortune.com/2026/05/21/microsoft-copilot-ai-openai-satya-nadella-gemini-claude/ — *model competition pressure.*
- Built In — OpenAI's $1T infra plan (2025) https://builtin.com/articles/openai-cloud-deals — *AWS $38B, multi-vendor $1.15T aggregation.*
- CNBC — Copilot uphill climb (Nov 23 2025) https://www.cnbc.com/2025/11/23/microsoft-faces-uphill-climb-to-win-in-ai-chatbots-with-copilot.html — *distribution ≠ automatic win.*
- Benzinga — Copilot crosses 30M seats (Jul 2026) https://www.benzinga.com/markets/tech/26/07/60788224/ — *seat count.*
- Semafor / CNBC / FT — MAI coverage (Aug 28 2025; Apr 4 2025; Feb 2026) — *Suleyman strategy pivot; MAI independence.*
- github.blog / linkedin (Kyle Daigle) — GitHub Copilot 4.7M paid (Jan 2026) — *paid-subscriber count.*
- The Register — UK CMA Copilot probe (Jul 29 2026) — *consumer bundling investigation.*

---

## MASTER LIST OF FLAGGED / UNVERIFIED ITEMS
1. **OpenAI restructuring: Apr-2026 revenue-share cap ($ and %) NOT disclosed;** historical ~20% rate not confirmed as current — do not cite as current.
2. **Exact OpenAI stake:** Microsoft ~27%/$135B is HIGH confidence (Tier-1 + cross-checked); OpenAI Foundation ~26%/$130B varies 26–27% across tallies.
3. **Several Apr-2026 OpenAI terms are press-only (MEDIUM):** full multi-cloud freedom, AGI-clause neutralization, rev-share-through-2030.
4. **No standalone "AI-only" capex $;** no full-year total-incl-finance-leases official number (FY26 ≈$145.3B is arithmetic); FY26 FCF ~$67B is derived.
5. **Maia 200 vs Trainium3/TPU-v7 = Microsoft marketing,** not independently benchmarked; 2026 custom-silicon volumes (~250k Maia/600k Trainium/900k TPU) are analyst estimates, no primary source.
6. **AMD MI355X on Azure not verified** (only MI300X confirmed).
7. **No "points of Azure growth from AI" figure disclosed;** FY26 Q3/Q4 Azure quarterly growth % not pinned (Azure crossed $100B annual by Q4).
8. **$37B/+123% AI run-rate is stale (Apr 2025);** no standalone M365/GitHub Copilot revenue $ ever disclosed; "+60% Copilot growth" scope muddy.
9. **Phi-5 does not exist** as of 2026-08-05; MAI-1-preview param count undisclosed; MAI-Thinking-1 specs are secondary.
10. **No Foundry-specific agent/developer aggregate;** "80,000 enterprises on Foundry" and Fabric "28,000 customers" unconfirmed vs primary.
11. **No signed Microsoft SMR PPA;** Crane restart 2027 (accelerated) vs 2028 (original); renewables 34 GW (official) vs 40+ GW (press).
12. **No verbatim Nadella "distribution is our moat" quote;** Fortune 500 penetration 70–90% range; $1.15T OpenAI infra aggregate is a press sum.
13. **Several primary URLs 403'd** (openai.com Stargate 10GW; CNBC Stargate Norway) — verified via search snippet/headline only.
