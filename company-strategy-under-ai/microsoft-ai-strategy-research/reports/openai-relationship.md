# The OpenAI Relationship: Asset, Cost, and Competitor at Once

Date baseline: 2026-08-05

> Evidence tags: **[Disclosed]** official filing/blog · **[Reported]** credible press · **[Estimated]** derived · **[Speculative]**. Reconciles to `sources/source-ledger.md` and the raw facts sheet at `sources/raw-facts-sheet.md`. MSFT fiscal year ends June 30 (FY26 Q1 = Jul-Sep 2025; Q2 = Oct-Dec 2025). Two amendments matter: the **Oct 28, 2025** restructuring (heavily Tier-1 documented) and a **further Apr 27, 2026** revision (several terms press-only — flagged MEDIUM).

This is the Microsoft-specific crux with no analog in the Amazon dossier. The OpenAI relationship is simultaneously:

```text
Microsoft's biggest AI ASSET       - early frontier-model access + a ~27% / ~$135B stake
Microsoft's biggest AI COST        - equity-method loss share + a $250B compute commitment
Microsoft's biggest AI COMPETITOR  - OpenAI now multi-clouds, sells enterprise seats, ships a browser
```

Understanding Microsoft's AI strategy is largely understanding how it is trying to keep the asset, cap the cost, and contain the competitor — all at once.

## 1. The Investment

- Microsoft has **committed $13B**; **$11.8B funded as of Mar 31, 2026** **[Disclosed, 10-Q]**. This is the cumulative figure across the 2019/2021/2023 rounds — not new money each quarter.
- The stake is accounted for under the **equity method**, flowing through "other income (expense), net" — which is why OpenAI's results move Microsoft's reported EPS (see §4).

## 2. The October 2025 Restructuring — What Changed

On **Oct 28, 2025**, OpenAI completed its long-running recapitalization, and Microsoft and OpenAI rewrote the partnership. The structure now:

```text
OpenAI Foundation (nonprofit)  --controls-->  OpenAI Group PBC (public benefit corp, for-profit)
   ~26% / ~$130B                                 valued at ~$500B
Microsoft: ~27% (as-converted, fully diluted) / ~$135B   [down from ~32.5% pre-round]
Employees + other investors: ~47%
```

- **Microsoft's stake: ~27%, valued at ~$135B** **[Disclosed — Microsoft blog + 10-Q; cross-checked CNBC/TIME/Fortune]**. This is a *high-confidence* number and internally consistent (27% × $500B ≈ $135B). It was diluted from ~32.5% by the new capital raised.
- The nonprofit (renamed the **OpenAI Foundation**) retains **control** of the PBC and made an initial **$25B** charitable commitment; the recap was reviewed by the Delaware and California AGs **[Reported]**.

The strategic significance: OpenAI became a normal-ish for-profit that can raise capital and be valued — turning Microsoft's stake into a **marked, ~$135B financial asset** (a big driver of reported income; see §4), while the Foundation's control preserves the nonprofit-governance veneer.

## 3. The Revised Commercial Terms

This is where Microsoft traded exclusivity for durability. Four terms matter.

### (a) Azure exclusivity — GIVEN UP
```text
Before:  Microsoft had a right of first refusal (ROFR) to be OpenAI's compute provider.
Oct 2025: Microsoft GAVE UP the ROFR. API products stayed Azure-exclusive;
          non-API products (and US national-security customers) could run on any cloud.  [Disclosed]
Apr 2026: OpenAI can serve ALL products on any cloud (incl. Google, AWS);
          Microsoft remains "primary cloud provider" / products "ship first on Azure."   [Reported — MEDIUM]
```
This is the single most consequential change: Microsoft stopped being OpenAI's mandatory compute landlord. The direct visible consequence is **Stargate** (OpenAI's mega-buildout) running on **Oracle, not Azure** (§5).

### (b) The $250B Azure commitment — the offset
In exchange, **OpenAI contracted to purchase an incremental $250B of Azure services** **[Disclosed]**. So Microsoft gave up *exclusivity* but locked in an enormous *contracted demand* floor. Net: less control, more guaranteed revenue. (Term/end-date not fixed in sources — MEDIUM on timing.)

### (c) IP rights — extended, and de-risked against AGI
```text
Models & products:  Microsoft's IP rights run THROUGH 2032, now INCLUDING models post-AGI (with guardrails).
Research IP (methods): until AGI is verified OR 2030, whichever comes first.
Excluded:            OpenAI's consumer hardware; weights/architecture/inference/datacenter IP.   [Disclosed]
```
Extending model IP to 2032 *even past an AGI declaration* is the key protection — it means an AGI event can no longer instantly strip Microsoft of access.

### (d) The AGI clause — neutralized as a cliff
```text
Before:  OpenAI's board could unilaterally declare AGI and cut off Microsoft's access. A cliff risk.
Oct 2025: an AGI declaration must be VERIFIED BY AN INDEPENDENT EXPERT PANEL; and because model IP
          runs to 2032 regardless, a declaration no longer cuts Microsoft off. Microsoft also gained
          the right to INDEPENDENTLY PURSUE AGI.                                            [Disclosed]
Apr 2026: reporting says the clause was effectively neutralized.                            [Reported — MEDIUM]
```
Removing the unilateral-AGI-cutoff is a major de-risking of the relationship for Microsoft.

### (e) Revenue sharing — continues, now capped and one-directional
```text
Oct 2025: OpenAI->Microsoft revenue share continues until the expert panel verifies AGI; payments
          spread over a longer period.                                                     [Disclosed]
Apr 2026: rev-share continues THROUGH 2030 (independent of AGI), subject to a TOTAL CAP; Microsoft
          will NO LONGER pay a reverse revenue share to OpenAI.                             [Reported]
```
**Do not cite the old ~20% figure as current — it is not confirmed, and the Apr-2026 cap ($ and %) was not disclosed. [Unverified]**

## 4. The Cost Side — OpenAI in Microsoft's Income Statement

Because Microsoft uses the equity method, its ~27% share of OpenAI's profit or loss hits "other income." Two consecutive quarters show how volatile and easily-misread this is:

| Quarter | Impact on MSFT net income | EPS impact | Nature |
|---|---|---|---|
| Q1 FY26 (Sep 30, 2025) | **−$3.1B** | −$0.41 | Recurring share of OpenAI's operating **losses** (implied OpenAI quarterly loss ≈ $11.5B) **[Disclosed / Estimated back-calc]** |
| Q2 FY26 (Dec 31, 2025) | **+$7.6B** | +$1.02 | **One-time remeasurement GAIN** from the restructuring — NOT operating profit **[Disclosed]** |
| FY2026 (full year) | **~+$6.5B net** | — | The one-time restructuring gain outweighed the recurring loss share for the year **[Disclosed, 10-K]** |

Two cautions for anyone reading Microsoft's income:

1. **The sign flips.** Q1's −$3.1B and Q2's +$7.6B are opposite in nature — one is a recurring loss share, the other a one-time accounting remeasurement. Do not annualize either.
2. **The recurring drag is real and growing with OpenAI's losses.** As OpenAI scales spending, Microsoft's ~27% loss share can become a material, recurring hit to reported EPS — even as the *stake value* (a non-cash mark) can swing income the other way. The quality of Microsoft's reported earnings is now partly a function of OpenAI's P&L and valuation.

## 5. The Competitor Side — The Frenemy Turns

Ceding the compute ROFR (§3a) unleashed OpenAI as a multi-cloud buyer and a direct rival:

- **Compute diversification:** OpenAI has signed large compute deals *away from Azure* — **AWS (7-yr, $38B)**, **Oracle (~$300B, incl. Stargate)**, **CoreWeave (~$22B)**, and **Google Cloud** — on top of the $250B Azure commitment. Press aggregates OpenAI's total compute commitments north of ~$1T across ~7 vendors **[Reported/Estimated]**.
- **Stargate on Oracle, not Azure:** the $500B / up-to-10-GW OpenAI+SoftBank+Oracle buildout runs on **Oracle OCI**. This is OpenAI compute Microsoft neither hosts nor controls — the clearest evidence the exclusivity era is over **[Reported]**.
- **Direct product competition:** ChatGPT vs Copilot (consumer *and* enterprise — OpenAI crossed **1M business customers** and **7M+ workplace seats**, **800M+ weekly active users**); OpenAI API vs Azure OpenAI; and **ChatGPT Atlas**, OpenAI's browser (Oct 2025), encroaching on Edge/Copilot **[Reported]**. Bloomberg documented enterprises (e.g. Amgen) buying Copilot yet drifting to ChatGPT.

So the same partner that gives Microsoft its frontier models is now competing for Microsoft's enterprise AI seats and buying its compute elsewhere.

## 6. Microsoft's Response — Keep the Asset, Cap the Cost, Contain the Competitor

Microsoft's strategy across the relationship is coherent when read as three simultaneous moves:

```text
KEEP THE ASSET:      lock IP to 2032 (past AGI), neutralize the AGI cliff, hold the ~$135B stake,
                     secure the $250B Azure commitment as a contracted-demand floor.
CAP THE COST:        give up exclusivity (stop being forced to fund all OpenAI compute), cap the
                     rev-share, stop paying reverse rev-share, and manage the equity-method drag.
CONTAIN THE RIVAL:   reduce single-model dependence -> build own models (MAI/Phi) and multi-source.
```

The multi-sourcing is concrete and, notably, includes **investing in OpenAI's rival**: in the **Nov 18, 2025** Microsoft-NVIDIA-Anthropic partnership, **Anthropic committed to buy $30B of Azure compute**, **NVIDIA committed up to $10B and Microsoft up to $5B into Anthropic**, and Claude went GA in Microsoft Foundry — making Azure "the only cloud with both Claude and GPT frontier models" **[Disclosed]**. Claude is now available across GitHub Copilot, M365 Copilot/Studio, and Foundry. Combined with Microsoft's own **MAI** frontier models and **Phi** small models (see `technical-primer.md` §4), the model layer under Microsoft's products is deliberately becoming *plural* — the hedge against OpenAI dependence.

## 7. Net Assessment

```text
Was the Oct-2025 / Apr-2026 rewrite good for Microsoft?
  YES on RISK: the AGI cliff is gone, IP is secured to 2032, the rev-share is capped, and a $250B
               demand floor is locked in. Microsoft de-risked the single most dangerous dependency in its AI strategy.
  MIXED on CONTROL: it gave up exclusivity, so OpenAI now competes and multi-clouds - Azure lost
               guaranteed hosting of the frontier lab's growth (Stargate went to Oracle).
  UNRESOLVED on COST: the recurring equity-method loss share grows with OpenAI's spending, and reported
               earnings are now noisy with OpenAI marks. Watch this line every quarter.
```

The relationship has shifted from **exclusive dependence** (Microsoft as OpenAI's sole cloud, with a cliff risk) to **de-risked partnership-plus-competition** (Microsoft as OpenAI's largest-but-not-only backer, protected by IP and a demand floor, while hedging with Anthropic and its own models). That is a *more durable* position — but a less *controlling* one. Whether it was the right trade depends on whether Microsoft's own-model + multi-source hedge matures before OpenAI's competition bites, tracked in `reports/watchlist.md`.
