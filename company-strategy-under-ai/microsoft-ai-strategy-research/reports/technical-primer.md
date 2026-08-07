# Technical Primer: The AI Value Stack and Where Microsoft Sits

Date baseline: 2026-08-05

Amazon's primer (in the sibling dossier) walks the *physical* supply chain — electrons → chips → capacity. Microsoft's story is best told through the **value stack**: the layers of the AI business and where margin, lock-in, and dependence accrue. Microsoft is strong at the *top* of this stack (apps, distribution) and dependent at the *bottom* (silicon, frontier models). That inversion versus Amazon is the whole point.

Specific numbers live in `reports/capex-and-bottlenecks.md`, `reports/openai-relationship.md`, and `sources/source-ledger.md`. This file is the conceptual spine.

## 1. The Six Layers

```text
Layer 6  APPLICATIONS + DISTRIBUTION   Copilot in M365/Teams/GitHub/Dynamics; the installed base
Layer 5  ORCHESTRATION / AGENTS        Copilot Studio, Foundry Agent Service, agent frameworks
Layer 4  FRONTIER MODELS               GPT (via OpenAI), Anthropic (multi-sourced), MAI, Phi
Layer 3  AI CLOUD PLATFORM             Azure AI Foundry, Azure OpenAI/model APIs, training/inference
Layer 2  DATA-CENTER CAPACITY          buildings, power, networking, cooling
Layer 1  ACCELERATOR SILICON           NVIDIA (rented at scale), Maia (own, trailing), AMD
```

The first-principles question for any AI company is: **at which layers do you own the scarce, defensible thing, and at which are you a price-taker?**

- Own a layer → you keep its margin and control your destiny there.
- Rent/depend on a layer → someone else's margin is your cost, and their roadmap is your constraint.

Amazon spent a decade buying down layers 1-2 (silicon + data centers). Microsoft's strength is layers 5-6 (orchestration + distribution) and its historic lock on the enterprise. The strategic drama is what happens at layers 1 and 4, where Microsoft is *dependent*.

## 2. Layer 6 — Distribution: Microsoft's Real Moat

This is the layer almost no one else has at Microsoft's scale. Microsoft sells paid software to a huge fraction of the world's knowledge workers and developers: Windows, Microsoft 365 (Office), Teams, Outlook, GitHub, Dynamics, and the Azure enterprise relationship. That installed base is the distribution engine for AI.

The first-principles advantage:

```text
For a startup, every AI user must be ACQUIRED.
For Microsoft, every AI feature can be ATTACHED to a seat the customer already pays for,
  sold through an existing enterprise agreement, to an admin who already trusts Microsoft.
```

This is why Microsoft's AI monetization thesis is fundamentally a **distribution/attach** thesis, not a "build the best model" thesis. If even a fraction of hundreds of millions of paid seats attach a $30/user/month Copilot, the revenue is enormous *without* Microsoft owning the frontier model. Distribution is the layer where Microsoft's incumbency converts directly into AI dollars.

The risk at this layer is **attach economics**: the value of Copilot must clearly exceed its price for the buyer, or attach stalls — and unlike a free feature, a priced upsell must continuously justify itself.

## 3. Layer 5 — Orchestration / Agents: The New Battleground

As AI moves from "answer a prompt" to "complete a task," value shifts from the model to the *system around it*: tools, memory, data grounding, governance, and multi-step control. Microsoft is investing heavily here (Copilot Studio, Azure AI Foundry Agent Service, agent frameworks) because:

```text
The orchestration layer is where enterprise lock-in re-forms.
Whoever owns the agents, their permissions, their data grounding, and their audit trail
owns the customer relationship - even if the underlying model is swappable.
```

This is strategically crucial because it is Microsoft's hedge against layer-4 dependence. If the model becomes a swappable commodity underneath a sticky orchestration + data + governance layer, then owning layer 5-6 matters more than owning layer 4 — and Microsoft's OpenAI dependence becomes less dangerous.

## 4. Layer 4 — Frontier Models: The Dependence

Microsoft's frontier-model access has run primarily through **OpenAI**. This gave Microsoft an early, decisive lead (GPT-4-class models in Copilot before rivals could match) — but it created a structural dependence that is the defining feature of Microsoft's AI strategy and has no analog in the Amazon case.

The first-principles problem with depending on one frontier lab:

```text
- their model roadmap is your product roadmap
- their pricing is part of your cost
- their compute needs pull on your capacity and capital
- if they succeed enough, they can compete with you directly
```

Microsoft's response is **multi-sourcing and self-build**:

- **Multi-source** the model layer: make Copilot and Azure model-plural (route across OpenAI, Anthropic's Claude, Microsoft's own, and open models) so no single lab is load-bearing.
- **Build own models**: the Microsoft AI org (under Mustafa Suleyman) developing **MAI** frontier models, and the **Phi** small-model family for cheap, on-device, or high-volume tasks.

The strategic logic: Microsoft does not need to *beat* OpenAI at the frontier. It needs to make OpenAI *replaceable enough* that the dependence stops being an existential risk — turning the model layer from a single-supplier bottleneck into a competitive input market. (The full relationship — investment, restructuring, stake, terms, frenemy dynamics — is in `reports/openai-relationship.md`.)

## 5. Layer 3 — AI Cloud Platform: Where It Gets Billed

Azure is where model access, training, and inference get metered and sold. **Azure AI Foundry** is the platform surface: a model catalog, agent service, tooling, and governance. This is the layer that converts Microsoft's capex and its model relationships into recurring, metered revenue — and it is genuinely strong, because Azure carries the enterprise trust, compliance, and integration that regulated buyers require.

The economics here depend on layers 1-2: Azure's *margin* on AI is set by what it pays for silicon and power (below) versus what it can charge. This is exactly where Microsoft is more exposed than Amazon.

## 6. Layers 1-2 — Silicon and Capacity: The Exposure

This is Microsoft's weak layer relative to Amazon and Google.

- **Silicon**: Microsoft's custom accelerator (**Maia**) is real but **trails** AWS Trainium and Google TPU in maturity and deployment. So Microsoft **rents NVIDIA at scale** to serve AI demand — meaning NVIDIA's ~70-75% gross margin is embedded in Microsoft's AI cost of goods, and Microsoft has less of the cost-escape that Amazon's Trainium and Google's TPU provide. It also uses some AMD.
- **Capacity/power**: Microsoft is building data centers and securing power aggressively (including the high-profile restart of a nuclear unit and a fusion agreement), but like everyone it faces the power and construction bottleneck, and it must also supply a large share of *OpenAI's* compute needs, which competes for the same capacity and capital.

The first-principles consequence:

```text
Microsoft's cost per unit of AI compute is more exposed to NVIDIA's price
than Amazon's or Google's is. Its advantage must therefore come from DEMAND
(charging more via distribution) rather than from SUPPLY (paying less via own silicon).
```

That is the cleanest way to state the Microsoft-vs-Amazon contrast.

## 7. Putting It Together — Strong Top, Dependent Bottom

```text
Layer 6 Distribution     ████████████  Microsoft's core moat (unmatched)
Layer 5 Orchestration    █████████     strong, strategically central (the hedge)
Layer 4 Frontier models  ████          DEPENDENT (OpenAI) -> de-risking via MAI/Phi/multi-source
Layer 3 AI cloud         ████████      strong (Azure/Foundry), margin set by layers below
Layer 2 Capacity/power   ██████        building hard; also carries OpenAI's needs
Layer 1 Silicon          ███           EXPOSED: Maia trails; rents NVIDIA at scale
```

Read against the Amazon primer, the two companies are near mirror images:

```text
Amazon:     strong at the BOTTOM (owns silicon, data centers, power) - must win DEMAND capture
Microsoft:  strong at the TOP (owns distribution, orchestration)     - must manage SUPPLY cost + model dependence
```

Neither position is obviously superior. Owning the bottom gives cost/capacity control but requires winning customers; owning the top gives demand and pricing power but requires paying market rates for compute and managing a model dependence. The investment question for Microsoft, developed in `reports/strategy-thesis.md`, is whether the demand/distribution advantage at layers 5-6 out-earns the cost and dependence exposure at layers 1 and 4.

## 8. The First-Principles Scorecard

Watch these to judge the bet:

```text
1. Copilot attach:        paid Copilot seats as a share of the M365/GitHub installed base
2. AI attach economics:   Copilot/agent revenue per seat vs the cost (compute + model) to serve it
3. Model de-risking:      share of AI workloads NOT dependent on OpenAI (MAI/Phi/Anthropic/open)
4. Azure AI margin:       Intelligent Cloud / Azure margin as AI mix rises (is NVIDIA rent eating it?)
5. OpenAI drag:           equity-method loss share + compute commitment vs the value received
6. Capacity conversion:   Azure backlog/RPO vs capex vs "demand exceeds capacity" commentary
```

If Copilot attach and Azure AI grow at high margin while model-dependence falls, the demand-led thesis is working. If NVIDIA rent and the OpenAI drag compress Azure margin while Copilot attach stalls, Microsoft is paying full price for compute *and* carrying a costly, competitive dependence — the bear case.
