# Strategic Finance Report on Incremental Compute, Product, and GTM Allocation

## Scope and assumptions

This report uses only public signals and an explicit finance model because OpenAI does not publicly disclose product-line revenue, direct cost-to-serve, enterprise list pricing, or cohort-level churn. The highest-confidence public anchors are: more than 900 million weekly active users, more than 50 million consumer subscribers, more than 9 million paying business users, enterprise representing more than 40% of revenue, more than 15 billion API tokens processed per minute, and an ads pilot that crossed $100 million of annualized revenue within six weeks. Public reporting also put annualized revenue at roughly $25 billion as of end-February 2026, while company leadership described 2023–2025 revenue and compute scaling as moving roughly in lockstep. citeturn12view0turn12view1turn24view0turn25view0turn15view0

The model below is anchored on public prices and usage policies: Go at $8 per month, Plus at $20, Pro at $100 and $200, Business at $25 monthly or $20 annual, API prices ranging from GPT-5.4 mini at $0.75 input and $4.50 output per million tokens up to GPT-5.5 at $5 input and $30 output, plus Batch API discounts of 50%, Flex processing for lower-priority traffic, and credit-based pricing for advanced ChatGPT features and Codex in Business and Enterprise. I also use the enterprise usage report showing more than 7 million workplace seats, 9x growth in ChatGPT Enterprise seats, 19x growth in Custom GPTs and Projects users, strong API production depth, and materially higher value from advanced-feature-heavy usage. citeturn30view0turn29search3turn6view2turn6view0turn23view0turn23view2turn21view0turn32view1turn33view0turn33view1turn7view1

I use “durable economics” to mean five things at once: high revenue per compute dollar, recurring retention, expansion potential, pricing power, and low sensitivity to abusive or spiky usage. Under that lens, the best businesses are the ones where heavy usage is both sticky and metered. That is the core conclusion of this report.

## Executive answer

If the question is where to put the *next* dollar of scarce inference capacity, product effort, and GTM spend, the answer is: put it first into metered enterprise and developer workloads, second into enterprise workflow products that convert seat usage into credit consumption, and only third into consumer subscriptions. The most durable economics are in core API text and mini-model production traffic, Enterprise seats with shared credit pools, Business seats that expand into credits and Codex, and large Codex or agentic deployments sold on usage-based or hybrid pricing. The least durable economics are in free-tier usage and consumer Pro-style flat-price bundles for the heaviest users, where demand is real but monetization can lag compute consumption. citeturn12view0turn12view1turn15view2turn15view3turn32view1turn33view0

That ranking is supported by three public facts. First, enterprise is already more than 40% of revenue and management says it is on track to reach parity with consumer by end-2026, which means the business mix is already improving toward higher-value, more contractual demand. Second, APIs are processing more than 15 billion tokens per minute, and the enterprise report shows deep production usage with more than 9,000 organizations already above 10 billion tokens and nearly 200 above 1 trillion tokens. Third, Codex has moved from early traction to broad adoption, with more than 2 million weekly users in early April, more than 3 million a few days later, and more than 4 million by April 21, while team adoption inside Business and Enterprise was growing 6x since January; that is exactly the profile of a product that deserves more product and GTM energy, but with tighter metering. citeturn12view0turn15view1turn33view0turn15view2turn15view3

My recommended allocation of incremental spend is therefore straightforward. For compute, roughly 45% should go to core enterprise/API traffic on efficient models, 30% to metered Codex and agentic enterprise workloads, 15% to Business and high-conversion consumer paid experiences, and no more than 10% to free-tier expansion beyond reliability and search coverage. For product, I would bias toward enterprise workflow substrate, routing and cost controls, and monetization infrastructure. For GTM, I would bias toward partner-led and post-sales deployment rather than pure top-of-funnel acquisition.

## Product-line economics

The table below is a modeled current run-rate view, not a disclosed segment P&L. It allocates the publicly reported roughly $25 billion annualized revenue figure across consumer, seats, and API lines in a way that is consistent with public subscriber counts, paid business-user counts, enterprise revenue share, API token volume, and public pricing. Contribution margin here excludes central frontier-model R&D and long-dated training commitments; it is meant to answer the narrower question, “Which revenue lines look best on direct serving economics?” citeturn25view0turn12view0turn12view1turn30view0turn6view0turn23view0turn23view2

| Product line | Modeled current ARR | Modeled cost-to-serve | Modeled contribution | Modeled CM % | Read-through |
|---|---:|---:|---:|---:|---|
| Free + ads | $0.3B | $0.9B | $(0.6)B | -200% | Strategic acquisition funnel, not a place to dump scarce compute |
| Go | $0.8B | $0.5B | $0.3B | 40% | Good conversion tier if ads offset low ARPU |
| Plus | $9.6B | $4.3B | $5.3B | 55% | Strong consumer core with acceptable direct economics |
| Pro | $3.4B | $2.9B | $0.5B | 15% | Valuable users, but flat pricing is fragile against heavy usage |
| Business seats | $1.6B | $0.6B | $1.0B | 60% | Attractive self-serve PLG seat motion |
| Enterprise seats + credits | $2.0B | $0.6B | $1.4B | 68% | Best seat-based economics because advanced usage monetizes |
| API core text/mini | $4.7B | $1.2B | $3.5B | 75% | Highest-quality direct margin and best compute efficiency |
| API frontier, Codex, realtime | $2.7B | $1.4B | $1.3B | 48% | Worth scaling, but only under metered or hybrid packaging |
| **Total modeled** | **$25.0B** | **$12.4B** | **$12.6B** | **50%** | Direct economics can be healthy even while company-level P&L remains investment-heavy |

The main message is not the exact decimal. It is the shape of the economics. The best-product-line economics are where OpenAI charges by usage or where high-value seat products spill into credits. The weakest direct economics are where OpenAI bundles expensive frontier usage into low or flat prices. Public AI-company benchmarks suggest durable AI businesses often land closer to about 60% gross margins rather than mature SaaS’s roughly 77% median; this modeled mix, at about 50% contribution margin before central R&D and long-cycle infrastructure, is directionally consistent with a scaled foundation-model company that is already better than consumer-heavy AI wrappers but not yet at mature software margins. citeturn34view0turn34view2

Two pricing facts matter especially here. First, Business and Enterprise have already moved advanced features toward credits, which is directionally the right architecture. Second, Codex’s own published rate card says average spend is now about $100–$200 per developer per month, suggesting that a meaningful portion of the highest-value coding demand is already willing to pay far above a standard Business seat or a light consumer subscription. That is exactly why Codex should be treated as a high-value usage product, not as a blanket entitlement. citeturn21view0turn7view1

## Cohort value and retention

The enterprise usage picture looks unusually strong. More than 7 million workplace seats are already deployed; ChatGPT Enterprise seats were up about 9x year over year; weekly enterprise messages were up about 8x since November 2024; and the average worker was sending 30% more messages. Workflow depth is also increasing, not just seat count: weekly users of Custom GPTs and Projects were up about 19x year to date, and roughly 20% of all enterprise messages were already flowing through a Custom GPT or Project. On the API side, more than 9,000 organizations have processed over 10 billion tokens and nearly 200 have exceeded 1 trillion, while reasoning-token consumption per organization rose about 320x in the past year. Those are the usage signatures of low-churn, high-expansion cohorts. citeturn32view1turn33view0

The user-value side is equally important. In the enterprise report, 75% of surveyed workers said AI improved speed or quality, average time saved was 40–60 minutes per active day, data science, engineering, and communications were above average, and accounting and finance users reported the highest benefits per message. Usage intensity also strongly correlated with value creation: workers saving more than 10 hours per week were using about 8x more credits than workers reporting no time savings. That argues for leaning into cohorts where value is easy to measure and expansion is self-funding, especially finance, analytics, engineering, and cross-functional workflow automation. citeturn33view1turn32view3

The table below converts those public signals into a modeled cohort view of LTV/CAC.

| Cohort | Modeled monthly ARPU | Modeled LTV | Modeled CAC | LTV/CAC | Payback |
|---|---:|---:|---:|---:|---:|
| Consumer self-serve Go/Plus | $17 | $253 | $18 | 14.0x | 2.0 months |
| Consumer Pro | $140 | $458 | $60 | 7.6x | 2.4 months |
| Business self-serve seat | $22 | $880 | $90 | 9.8x | 6.8 months |
| Enterprise deployed seat | $60 | $6,800 | $720 | 9.4x | 17.6 months |
| API production account | $1,500 | $70,000 | $7,500 | 9.3x | 7.1 months |
| Frontier/Codex large account | $20,000 | $800,000 | $150,000 | 5.3x | 15.6 months |

A few conclusions matter more than the exact point estimates. Consumer self-serve has excellent *headline* LTV/CAC because the funnel is incredibly organic; more than 900 million weekly users and 50 million subscribers imply that paid conversion is happening inside a massive owned audience. But durability is better in Business, Enterprise, and API because the product gets embedded into team workflows and customer products, not just daily personal habits. Public software benchmarks put healthy net dollar retention around 110%–120%; OpenAI’s own enterprise usage signals, especially the seat, message, workflow, and token-growth data, are consistent with cohorts that can clear that bar once deployed. citeturn12view0turn12view1turn2view4turn34view3

The most fragile cohort is consumer Pro. It can look good on LTV/CAC because CAC is low, but it is highly sensitive to two things: spiky heavy usage and competitive switching among sophisticated users. A five-point margin hit matters much more there than it does in Business or Enterprise. For finance, that means Pro should be managed like a monetization problem, not just a growth product.

## Compute allocation and pricing

The best single public fact for compute planning is that company leadership showed revenue and available compute scaling almost one-for-one from 2023 through 2025: about $2 billion ARR on 0.2 GW in 2023, $6 billion on 0.6 GW in 2024, and $20 billion-plus on about 1.9 GW in 2025. That implies an observed historical monetization rate of roughly $10 billion of annualized revenue per GW of available compute, and management explicitly said that more compute in those periods would have driven faster monetization. In other words, compute is not just an infrastructure input; it is the pacing item for revenue growth. citeturn15view0

That does **not** mean every workload earns the same return on compute. Public pricing makes the spread obvious. GPT-5.4 mini is priced at $0.75 input and $4.50 output per million tokens, GPT-5.5 at $5 and $30, realtime audio at $32 and $64, web search at $10 per 1,000 calls, and Batch API offers a 50% discount for asynchronous jobs; Flex lowers costs in exchange for slower or lower-priority service. Meanwhile, Business and Enterprise already use credits for expensive features like reasoning, deep research, voice, images, and Codex, and ChatGPT itself increasingly routes lightweight tasks to smaller models. That combination strongly supports a portfolio strategy: put high-volume, low-latency-insensitive work on the cheapest effective model and reserve premium compute for workloads that are either metered or demonstrably high-value. citeturn23view0turn23view2turn21view0turn7view0

My compute-ROI ranking is therefore:

| Workload | Compute ROI today | Why |
|---|---|---|
| Core API text and mini-model production traffic | Highest | Metered, efficient, predictable, and easy to route |
| Enterprise seats with credit pools | High | Sticky seats plus monetized overages |
| Business seats that spill into credits | High | Strong PLG motion with expansion path |
| Metered Codex and agentic workflows | High after pricing discipline | Very strong demand and willingness to pay |
| Consumer Plus | Medium | Large base, acceptable margin, valuable for brand and upsell |
| Consumer Pro flat bundles | Low-medium | Valuable users but spiky compute draw |
| Free tier beyond search/reliability | Low direct | Strategic funnel, not a direct compute-return engine |

The pricing opportunities follow directly from that ranking.

First, extend credit-based monetization deeper into the heaviest consumer and team workflows. OpenAI already sells credits for Codex and Sora in consumer tiers and advanced-feature credits in Business and Enterprise. The next logical move is to preserve a generous baseline in Pro, but meter the most expensive advanced workloads more explicitly once users cross a clear threshold. citeturn9view0turn21view0turn7view1

Second, push more non-urgent developer traffic to mini, Batch, and Flex by default. This is the cleanest margin lever available because it improves unit economics without requiring a headline list-price increase. The product asks for it: better workload classification, customer-facing cost controls, and migration tooling that nudges teams toward the cheapest model that still clears the task. citeturn23view2turn3view5turn21view0

Third, scale the ad-supported and commerce-supported free and Go funnel, but do so with strict compute guardrails. The ad pilot already crossed $100 million in annualized revenue, there are more than 600 advertisers, roughly 85% of users are eligible to see ads, and fewer than 20% of eligible users are actually shown ads daily. That means monetization headroom exists *without* needing to open the compute floodgates on the free tier. citeturn24view0turn30view0

## Forecast

I model the next twelve months, starting from the current public run-rate base. The key drivers are enterprise/API mix, Codex monetization, free-tier ad scaling, and whether premium consumer usage remains flat-priced or becomes more usage-aligned. The public setup is favorable: enterprise is already more than 40% of revenue and management says it is on track to reach parity with consumer by end-2026; consumer is still adding subscribers rapidly; and historical revenue growth has tracked compute availability closely. citeturn12view0turn25view0turn15view0turn31view0

| Scenario | Modeled next-twelve-month ARR | Modeled next-twelve-month contribution | Modeled CM % | What has to be true |
|---|---:|---:|---:|---|
| Downside | $29.2B | $12.6B | 43% | Price pressure, slower enterprise conversion, underpriced Pro/free usage persists |
| Base | $35.2B | $17.8B | 50% | Enterprise/API mix rises, ads expand, metering improves, Codex scales |
| Upside | $41.1B | $22.7B | 55% | Enterprise reaches near-parity early, Codex/agents accelerate, product routing and pricing get sharper |

The biggest swing factor is not top-of-funnel demand. Demand already exists on all three fronts: consumer, business, and developer. The swing factor is whether OpenAI can keep shifting the mix toward monetized heavy use. If yes, enterprise/API can do most of the growth and the margin lifting. If not, growth still happens, but consumer bundles absorb too much of the compute gain. The upside case is especially plausible if Codex continues compounding at current velocity and if partner-led deployment helps enterprises move from pilots to broad adoption faster than internal services capacity alone would allow. citeturn15view2turn15view3turn2view4

## Recommendations and leadership asks

The operating recommendation is to treat the portfolio as four motions, not one.

| Motion | Recommendation | Why |
|---|---|---|
| Scale | Core API text/mini, Enterprise seats + credits, Business-to-credits expansion, Codex in metered enterprise workflows | Best combination of compute ROI, retention, and expansion |
| Optimize | Model routing, Batch/Flex adoption, credit UX, workload observability, cost-aware defaults | Fastest margin improvement without harming demand |
| Reprice | Consumer Pro heavy usage, premium Business/Enterprise overages, frontier agentic workloads | Current flat pricing understates willingness to pay for the most expensive work |
| Constrain | Free-tier premium multimodal usage, unlimited Pro abuse, underpriced coding-heavy team seats | Scarce compute should not flow to the weakest direct returns |
| Investigate | Outcome-based pricing in finance, healthcare, and science; ads and commerce expansion; reserved-capacity contracts | These are the highest-potential next monetization layers |

There is also a clear GTM implication. The best near-term verticals for direct revenue are professional services, finance, and technology because they already have the most scale. The best “next wave” verticals are healthcare and manufacturing because they are among the fastest-growing sectors. And because company leadership has said demand to deploy Codex is outpacing the ability to support adoption directly, partner enablement, solution engineering, and post-sales deployment should get more GTM dollars than pure top-of-funnel acquisition. Consumer familiarity already shortens business pilots, so the incremental enterprise dollar is better spent on success and expansion than on awareness. citeturn32view4turn33view1turn15view3turn2view4

The decisions I would ask leadership to make now are these:

| Decision required | Recommendation | Immediate next step |
|---|---|---|
| Incremental compute allocation | Approve a default bias of 75% of new inference capacity toward metered enterprise/API traffic and 25% toward consumer paid reliability and conversion | Stand up a monthly compute allocation review using revenue per compute-dollar and queue-level utilization |
| Consumer packaging | Preserve broad consumer access, but move the heaviest Pro and advanced-tool usage toward credits beyond generous baseline limits | Run pricing experiments on Pro overages, usage buckets, and auto-top-up |
| Enterprise packaging | Make credits the default monetization path for advanced workflows; keep instant usage abundant, meter premium reasoning/agentic features clearly | Simplify rate cards, overage controls, and ROI dashboards for admins |
| GTM mix | Increase partner-led deployment, customer success, and vertical solutions capacity in finance, professional services, technology, healthcare, and manufacturing | Reallocate headcount from generalist demand gen into solutions and post-sales |
| Finance instrumentation | Build a product-line P&L with per-feature serving cost and cohort-level LTV/CAC | Launch a weekly operating cadence across finance, product, infra, and sales ops |

## Open questions and limitations

The biggest unknowns are the ones OpenAI does not publicly disclose: exact enterprise seat pricing, the split between Business and Enterprise seats, the split between API core and frontier revenue, discounting on large contracts, and actual serving cost by feature and model. Those unknowns change the *exact* segment P&L, but they do not change the ranking very much. The robust directional conclusion is that the next dollar should go where usage is both sticky and metered: enterprise seats with credits, API production traffic, and Codex or agentic workflows that are sold on usage-aligned terms. The weakest place for scarce compute is anywhere OpenAI is still offering frontier-heavy behavior under low or flat pricing.