# Business-Model Map: How AI Changes What Microsoft Sells, Meters, and Prices

Date baseline: 2026-08-05

The headline, and the contrast with Amazon:

```text
For Amazon, AI changed the CONSTRAINT structure but not the SKU.
For Microsoft, AI touches the PRODUCT directly: it is a per-seat upsell today,
  and the emerging agent layer points toward consumption/outcome pricing tomorrow.
```

So Microsoft is a genuine hybrid: a *product-transformation* story (does AI change what is sold and how it is priced?) riding on a *bottleneck-structure* story (chips, power, capex — covered in `reports/capex-and-bottlenecks.md`). This map focuses on the product/pricing side.

## 1. Microsoft's Revenue Engines (Baseline)

```text
Productivity & Business Processes  - M365 (Office), Teams, Dynamics, LinkedIn
Intelligent Cloud                  - Azure + server products; the growth/AI engine
More Personal Computing            - Windows, devices, gaming, search/ads
```

Microsoft's crown jewel is a colossal base of **paid seats** and **enterprise agreements**. That base is the surface AI attaches to.

## 2. The Core AI Monetization Move — Attach

Microsoft's primary AI money model is **attach**: sell an AI add-on to a customer who already pays for the underlying product, through an existing enterprise agreement.

| Product | Base SKU | AI attach | Pricing move |
|---|---|---|---|
| Microsoft 365 | Per-seat productivity suite | **M365 Copilot** (~$30/user/mo) | Premium per-seat upsell on the largest install base |
| GitHub | Developer platform seats | **GitHub Copilot** (tiered, incl. free/Pro/Business/Enterprise) | Per-seat upsell + a funnel into Azure/agents |
| Dynamics 365 | Business-apps seats | **Copilot in Dynamics** | Attach on CRM/ERP seats |
| Security | Defender/Sentinel | **Security Copilot** | Consumption-priced (security compute units) |
| Windows / consumer | OS + M365 consumer | **Copilot** (free) + **Copilot Pro** (~$20/mo) | Freemium; funnel + defense |
| Azure | Metered cloud | **Azure OpenAI / AI Foundry / agents** | New metered AI consumption category |

The strategic elegance: Microsoft can grow AI revenue **without owning the frontier model**, because the scarce asset it monetizes is *distribution and trust*, not the model. Each point of attach on a nine-figure seat base is large-dollar, high-margin recurring revenue.

The strategic risk: **attach must be earned continuously.** A $30/seat upsell has to demonstrably save more than it costs, to an enterprise buyer scrutinizing ROI. If perceived value lags price, attach stalls — and priced AI is far more exposed to this than a free feature bundled to defend a franchise.

## 3. Three Pricing Models, and the Drift Toward Consumption

Microsoft is running three monetization models simultaneously, and the mix is shifting:

```text
1. Per-seat subscription   (M365 Copilot, GitHub Copilot) - today's core
2. Consumption / metered   (Azure AI, Security Copilot units, agent message packs) - growing
3. Freemium / defensive    (consumer Copilot, Bing/search) - funnel + franchise defense
```

The important trend is the **drift from seat pricing toward consumption/agent pricing.** As work moves from a human-in-Copilot (naturally seat-priced) to autonomous agents doing tasks (naturally metered by work done), Microsoft is adding pay-as-you-go agent mechanics (message/credit packs, consumption meters). This is the early signal of a genuine business-model change:

```text
seat (a person uses AI)  ->  consumption (an agent does work)  ->  potentially outcome (work completed)
```

Watch whether Microsoft prices agents by *tasks/outcomes* rather than seats — that is the same "value-unit shift" the EDA/tool-vendor case turns on, showing up inside Microsoft.

## 4. Segment-by-Segment Effect

### Intelligent Cloud (Azure) — the engine
AI is a direct **demand tailwind** (Azure AI services, model APIs, agent platform) and a **margin question** (NVIDIA rent + OpenAI compute burden vs what Azure can charge). This is where AI most visibly moves the financials, and where the supply-cost exposure from `technical-primer.md` bites. Net: revenue clearly up; margin trajectory is the thing to watch.

### Productivity & Business Processes (M365, Dynamics, LinkedIn) — the attach base
The purest **product-transformation** surface: Copilot as a premium per-seat tier on Office/Teams/Dynamics. If attach scales, this converts a mature, slower-growth franchise into an AI-growth story at high incremental margin (software attach, not compute-heavy at the app layer). LinkedIn adds AI hiring/learning/feed monetization.

### More Personal Computing (Windows, search, gaming) — mostly defensive
Consumer Copilot and AI in Windows/Bing are largely **defensive**: keep users inside Microsoft surfaces as AI answer-engines threaten search and the classic app funnel. Bing/advertising gets a modest yield boost; the bigger point is franchise defense, not new revenue.

## 5. The Whole-Company Money Logic Under AI

```text
Huge paid installed base (M365/GitHub/Dynamics/Windows) + enterprise trust
        |
        v
Attach Copilot/agents (seat -> consumption pricing) + sell Azure AI
        |
        v
High-margin AI software revenue  ------ funds ------>  capex + NVIDIA rent + OpenAI compute/loss share
        |                                                        |
        +--- de-risk the model layer (MAI/Phi/multi-source) <----+
```

Microsoft's version of the flywheel is **distribution-funded**: its software franchises throw off the cash and the customer relationships that let it monetize AI without owning the scarce physical inputs. The tension is that the physical inputs (compute, OpenAI's needs) are expensive and partly outside its control, so the *margin* of the flywheel depends on layers Microsoft doesn't fully own.

## 6. What Would Signal a Real Business-Model Change

Microsoft's SKUs are recognizable today (subscriptions + metered cloud). Watch for signs the *model* is changing, not just growing:

1. **Agent/outcome pricing at scale**: material revenue from agents priced by task/work-done rather than per seat.
2. **Disclosed Copilot revenue**: Microsoft breaking out a Copilot/AI revenue run-rate (today mostly bundled into segment growth) — a sign it is a real line, not a feature.
3. **Model-plural Copilot as default**: Copilot routing across OpenAI/Anthropic/MAI as standard — evidence the model is now a commodity input, changing Microsoft's cost and dependence structure.
4. **Consumption overtaking seats** in AI revenue mix — the clearest "value-unit shifted" signal.
5. **Security/agent consumption** becoming a large standalone meter.

Until then, the honest framing: AI is today a **high-margin attach upsell on an unmatched distribution base**, drifting toward consumption pricing, funded by heavy capex and a costly frontier-model dependence. The product is changing at the edges; the deeper business-model change is visible but not yet dominant.
