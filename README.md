# OpenAI Strategic Finance — Li's Note

## Context

I've been curious about how OpenAI is doing from a strategic-finance standpoint, so I posed myself a question:

> **Where should OpenAI allocate the next dollar of compute, product, and GTM?**

To answer it, I ran deep research with the help of AI on public signals (ARR, subscriber counts, token throughput, enterprise share, pricing, ads pilot), then built a strategic-finance analysis on top — product-line unit economics, cohort LTV/CAC, compute ROI by workload, pricing levers, and an NTM forecast with Monte Carlo. A few of the findings genuinely surprised me, and I'd love to share and discuss them if I get the chance.

> **Disclaimer:** This is an *open case* — based entirely on **public data**, current as of **April 25, 2026**. No internal OpenAI data was used; all segment-level numbers are modeled, back-solved, or calibrated to public anchors. Conclusions may be wrong.

## TL;DR

**Question:** Where should we allocate the next dollar of compute, product, and GTM?

**Answer:** **75% to metered enterprise & API, 25% to consumer paid** — put the next scarce dollar where usage is *both sticky and metered*.

Granular split of incremental compute:

| Bucket | Share | Why |
|---|---:|---|
| Core API text / mini production | 45% | Highest $/compute, predictable, easy to route |
| Metered Codex / agentic enterprise | 30% | Strong demand + WTP; meter to capture |
| Business + high-conversion consumer paid | 15% | Sticky seat motion → credit expansion |
| Free-tier reliability + search | ≤10% | Strategic funnel, compute-guardrailed |

Paired with routing/pricing discipline (mini-model defaults, Batch/Flex, Pro overages, enterprise credit packaging), the modeled base case reaches **$35.2B ARR, $17.8B contribution, ~50% contribution margin** over the next twelve months, with a Monte Carlo 80% interval of **$32.6B–$37.8B**. The biggest free lunch is the allocation rule itself: it changes nothing for the user but materially shifts where the next dollar earns.

## Repository contents

| File | What it is |
|---|---|
| [openai_stratfin_report_deck.html](openai_stratfin_report_deck.html) | Reporting deck — the executive-facing presentation of findings and recommendations. |
| [openai_stratfin_analysis.ipynb](openai_stratfin_analysis.ipynb) | Analysis notebook — the financial model, product-line economics, and scenario work behind the recommendation. |
| [deep-research-report.md](deep-research-report.md) | Source research data — the underlying public-signal research powering this analysis, produced via ChatGPT / Claude Deep Research. |
