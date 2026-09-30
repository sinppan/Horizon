---
layout: default
title: "Horizon Summary: 2026-09-30 (EN)"
date: 2026-09-30
lang: en
---

> From 47 items, 12 important content pieces were selected

---

**Technology News**
1. [OpenAI announces GPT-6.1 Sol, claiming near-Astra quality at one-fifth price](#item-tech-news-1) ⭐️ 7.0/10
2. [Public PS5 Relapse Exploit released on GitHub](#item-tech-news-2) ⭐️ 7.0/10
3. [Privacy analysis of web and mobile conversational AI agents](#item-tech-news-3) ⭐️ 7.0/10
4. [OpenAI Introduces Dots, an Always-On Agent Product](#item-tech-news-4) ⭐️ 7.0/10
5. [Anthropic: GLM-5.3 and Claude Mythos Preview cross binary exploitation threshold](#item-tech-news-5) ⭐️ 7.0/10
6. [China&\#x27;s generative AI users surpass 700 million, CNNIC reports](#item-tech-news-6) ⭐️ 7.0/10
7. [Cloudflare launches cf CLI beta for AI agents, covering 3,000+ API operations](#item-tech-news-7) ⭐️ 7.0/10
8. [Google fixes Firebase backend bug that crashed iOS apps](#item-tech-news-8) ⭐️ 7.0/10

**Financial News**
1. [China to subsidize new first-home mortgages by 1 percentage point a year from Oct. 1](#item-finance-news-1) ⭐️ 8.0/10
2. [Fair Isaac Falls 18% on Mortgage Pricing Change; CarMax, AMD Gain](#item-finance-news-2) ⭐️ 7.0/10
3. [China Raises IPO Bar for Humanoid Robot Startups, Sources Say](#item-finance-news-3) ⭐️ 7.0/10
4. [Oracle Issues Force Majeure Notice on Stargate Data Center](#item-finance-news-4) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [OpenAI announces GPT-6.1 Sol, claiming near-Astra quality at one-fifth price](https://openai.com/index/introducing-gpt-6-1-sol/) ⭐️ 7.0/10

OpenAI announced GPT-6.1 Sol, marketed as delivering near-Astra intelligence for one-fifth the price. The supplied Hacker News discussion highlights a quoted cached-input price of $0.10 per million tokens, which commenters say is 95% lower than standard input pricing and 50% lower than GPT-6 Sol&\#x27;s cached rate. The supplied material does not include independent benchmarks, an availability date, context-window limits, or compatibility details, so the quality and price-performance claims remain vendor claims rather than verified results.

hackernews · crorella · Sep 29, 17:06 · [Discussion](https://news.ycombinator.com/item?id=49896586)

**「Background」** OpenAI&\#x27;s GPT-6 family is tiered: Astra is the flagship, and Sol sits below it, with GPT-6.1 Sol described as an upgrade to the earlier GPT-6 Sol rather than a new top-end model. That hierarchy is the reference point for the announcement&\#x27;s framing of &quot;near-Astra intelligence&quot; at one-fifth of Astra&\#x27;s standard API input and output token prices.

**「Impact」** For developers running cache-heavy agentic coding workloads, the concrete change is cost: cached input is quoted at $0.10 per million tokens, 95% below standard input pricing and half of GPT-6 Sol&\#x27;s cached rate, which directly lowers the cost of long sessions in tools such as Codex where the same context is resent on every turn. External pricing trackers show rivals already discount cache reads sharply — Anthropic at 0.1x base input and 0.05x on Opus 5.5 \($0.20/M\) — so teams deciding whether to move a Codex or Claude Code pipeline should compare effective cost per session rather than headline token rates.

**「Community discussion」** Commenters split over whether Sol 6.1 addresses real quality problems: one said GPT-6/Sol 6 was a regression from Sol 5.6 and switched to Opus 5.5, while another reported using DeepSeek instead and finding the intelligence difference negligible for the much lower cost. Several focused on the quoted cache discount as the substantive change, with one arguing token price is becoming the main competitive battleground, and another speculating that Sol 6.1 was a renamed &quot;Astra-Minor&quot; release.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-gpt-6-1-sol/">Introducing GPT - 6 . 1 Sol | OpenAI</a></li>
<li><a href="https://openrouter.ai/openai/gpt-6.1-sol">GPT - 6 . 1 Sol - API Pricing &amp; Providers | OpenRouter</a></li>
<li><a href="https://www.spheron.network/blog/llm-api-pricing-comparison-gpt-claude-gemini-deepseek-2026/">LLM API Pricing 2026: GPT vs Claude vs Gemini vs DeepSeek | Spheron Blog</a></li>
<li><a href="https://www.morphllm.com/llm-api">LLM API Providers (2026): 12 APIs Compared by Price per 1M Tokens, Rate Limits, and Context</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#GPT-6.1 Sol`, `#LLM pricing`, `#AI model releases`, `#Hacker News`

---

<a id="item-tech-news-2"></a>
### [Public PS5 Relapse Exploit released on GitHub](https://github.com/ntfargo/Relapse-Exploit) ⭐️ 7.0/10

A public PS5 exploit called Relapse Exploit has been released on GitHub via the repository linked in the item. The release prompted Hacker News discussion about PS5 jailbreaking, a possible WebKit/JavaScriptCore bug, and restrictions on game-save backups. The supplied material does not specify supported firmware versions, whether the exploit is reliable, or whether it enables USB save backups.

hackernews · therepanic · Sep 29, 15:44 · [Discussion](https://news.ycombinator.com/item?id=49895304)

**「Background」** PS5 exploit chains generally work in two stages: a browser entry point that achieves code execution, followed by a kernel exploit that yields read/write access to system memory. According to the project&\#x27;s published documentation, Relapse&\#x27;s browser stage combines JavaScriptCore information leaks with an object-pool mismatch in structured clone to corrupt a typed array. Earlier PS5 exploits were scoped to narrower firmware branches and had to be maintained as separate efforts; Relapse is described as consolidating coverage from firmware 7.00 through 13.60 into one project, with the caveat that the chain&\#x27;s reliability is not guaranteed.

**「Impact」** PS5 owners and homebrew developers now have a public artifact to inspect, but its practical capability is unconfirmed because no firmware compatibility or success details are supplied. A commenter’s question about using it for USB game-save backups remains unanswered.

**「Community discussion」** Commenters focused on two issues: MaxBarraclough said the exploit appears to target a WebKit JavaScriptCore bug and asked whether Sony would respond by disabling JIT, while publlus\_enigma asked whether the exploit could enable USB backups of game saves, saying the PS5 otherwise requires per-profile PlayStation Plus cloud backups. Muromec speculated that such communities hold additional zero-day exploits needed for deeper jailbreak stages, while asadm wished the release had waited for GTA6 and Daklone hoped for Steam game support on PS5.

<details><summary>References</summary>
<ul>
<li><a href="https://elsolitario.org/en/2026/09/29/relapse-repo-claims-ps5-exploit-firmware-7-00-to-13-60/">PS5 Jailbreak: What Is Relapse Exploit and Its Scope</a></li>
<li><a href="https://1023jack.com/news/ps5-relapse-exploit/">PS5 Relapse Exploit - 1023 Jack</a></li>
<li><a href="https://dev.to/lu1tr0n/relapse-repo-afirma-exploit-de-ps5-en-firmware-700-1360-1n14">Relapse: repo afirma exploit de PS5 en firmware 7.00-13.60 - DEV Community</a></li>

</ul>
</details>

**Tags**: `#PS5`, `#security exploit`, `#console jailbreak`, `#WebKit`, `#JavaScriptCore`

---

<a id="item-tech-news-3"></a>
### [Privacy analysis of web and mobile conversational AI agents](https://jorgegarciaherrero.com/wp-content/interactivos/20260916-Prompt-like-a-butterfly-sting-like-a-tracker-%28clean%29.pdf) ⭐️ 7.0/10

A paper posted to Hacker News presents a privacy analysis of web and mobile conversational AI agents, with the item framing it as a technical deep-dive into data leakage and tracking risks. The supplied item does not include the paper&\#x27;s full text, so its methodology, measurements, and conclusions could not be independently assessed. Commenters on Hacker News raised concrete examples of prompt and conversation exposure, but the paper&\#x27;s own novelty and broader impact remain uncertain from the available material.

hackernews · damaru2 · Sep 29, 09:03 · [Discussion](https://news.ycombinator.com/item?id=49890226)

**「Background」** Evaluating a conversational AI agent&\#x27;s privacy behavior requires separating what the agent itself transmits from what the platform APIs and permissions around it expose, because the same agent can behave differently on web and mobile. Reader discussion of this paper centered on that distinction, with one commenter asking how much of the privacy risk originates in the agent versus the surrounding platform. The paper&\#x27;s source text was not available in the supplied material, so its specific findings and methodology are not verifiable here.

**「Impact」** For users of web-based conversational AI, the thread&\#x27;s reported examples indicate that sharing a conversation URL may expose the full chat and that partial prompts can be transmitted before send; both behaviors, if confirmed, mean privacy should not be assumed for unsent text or for links containing a conversation identifier.

**「Community Discussion」** Commenters debated how much of the risk comes from the agent itself versus the surrounding platform APIs and permissions, with one calling the web-vs-mobile comparison an open question. Another argued that the issue reinforces the case for running open models locally, citing an earlier dispute over unpublished drafts in private Codex sessions and de-identified product data.

**Tags**: `#privacy`, `#conversational AI`, `#web security`, `#mobile security`, `#tracking`

---

<a id="item-tech-news-4"></a>
### [OpenAI Introduces Dots, an Always-On Agent Product](https://openai.com/index/introducing-dots/) ⭐️ 7.0/10

OpenAI has introduced Dots, an always-on agent product, according to the announcement. The supplied item does not include technical details such as model version, pricing, availability, supported integrations, or compatibility, so the scope of the release is not established here. On Hacker News, the announcement drew 466 points and 353 comments, with discussion centering on platform lock-in and overlap with OpenAI&\#x27;s existing Codex and ChatGPT Work offerings.

hackernews · alvis · Sep 29, 17:07 · [Discussion](https://news.ycombinator.com/item?id=49896604)

**「Background」** Dots is OpenAI&\#x27;s entry into the emerging category of &quot;always-on&quot; agents — systems meant to run continuously on remote machines rather than answer single prompts — which the company says are powered by GPT-6 Astra. The category is not exclusive to OpenAI: search coverage of the launch frames Dots as an answer to Meta&\#x27;s competing always-on agent, Muse.

**「Access and pricing」** ChatGPT Pro and Business Premium subscribers in eligible markets can use one Dot at no extra cost, but members of Enterprise, Edu, and Healthcare workspaces must wait for a workspace admin to enable the beta. Because Dots are priced by agent capacity, teams needing more than the bundled Dot should confirm additional costs and admin controls before broad deployment.

**「Community Discussion」** Commenters debated platform lock-in: aditya\_rs argued that always-on agents create switching costs through integrations and work history, making them harder to replace than models, while johnfahey said OpenAI is now pushing products users do not need and tightening the generous Codex limits that attracted them. wxw described the boundaries between Codex, ChatGPT Work, and Dots as blurry and said they were more bullish on Muse, and jameslk predicted always-on agents will move computing to the cloud and end the PC era for mainstream users.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reddit.com/r/technology/comments/1wtg2cz/openai_introduces_dots_alwayson_longrunning_agents/">OpenAI Introduces Dots: Always-On, Long-Running Agents - Reddit</a></li>
<li><a href="https://x.com/OpenAI/status/2104984504133918973">OpenAI on X: &quot;Introducing dots, powered by GPT-6 Astra ...</a></li>
<li><a href="https://thenewstack.io/openai-dots-gpt6-agents/">OpenAI just launched Dots . Here&#x27;s why they matter... - The New Stack</a></li>
<li><a href="https://www.datacamp.com/blog/openai-dots">OpenAI Dots : Always-On Agents in ChatGPT, Explained | DataCamp</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#AI agents`, `#developer tools`, `#platform lock-in`, `#AI industry`

---

<a id="item-tech-news-5"></a>
### [Anthropic: GLM-5.3 and Claude Mythos Preview cross binary exploitation threshold](https://simonwillison.net/2026/Sep/29/anthropic-frontier-red-team/) ⭐️ 7.0/10

Anthropic&\#x27;s Frontier Red Team reports that on 100 randomly selected tasks from its internal Binary Exploitation benchmark, GLM-5.3 developed full control flow hijacks in 4% of trials and Claude Mythos Preview in 6%, while earlier models including Claude Opus 4.6 and GLM-5.2 succeeded in none. The team frames this as a crossed capability threshold rather than a claim of consistent capability, since both models still failed in the large majority of attempts. A companion summary in the same item adds that GLM-5.3 succeeded in 50 of 410 ExploitBench attempts, close to Claude Mythos Preview&\#x27;s 56, and that Anthropic found GLM-5.3&\#x27;s safeguards could be bypassed by simple methods with a 64% to 100% success rate in simulated tests, with open weights letting users modify the model to weaken refusals. These figures come from Anthropic&\#x27;s own evaluation and have not been independently verified.

rss · Simon Willison · Sep 29, 22:20

**「Background」** According to the research page Anthropic&\#x27;s Frontier Red Team published alongside the quote, Claude models are released with cyber safeguards and any reduced-safeguard versions are limited to vetted users, whereas GLM-5.3 can be downloaded and used by anyone. That distribution difference is the frame for Anthropic&\#x27;s &quot;spread of advanced cyber capabilities&quot; argument: the same class of capability that is gated behind a vendor&\#x27;s safety review in a closed model is freely modifiable in an openly downloadable one.

**「Open weights complicate containment」** Third-party reporting ahead of the release said Z.ai intended to publish GLM-5.3&\#x27;s weights under an MIT license, which would mean a model measured at successfully constructing control-flow hijacks is not gated by any hosted-API safety filter; enterprise AI policies written on the assumption that such offensive capability stays behind vendor APIs would need revisiting. The same openness gives defensive-security teams a model they could run in a controlled or offline environment instead of negotiating usage terms with a hosted provider.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/research/glm-5-3-and-the-spread-of-advanced-cyber-capabilities">GLM - 5 . 3 and the spread of advanced cyber capabilities \ Anthropic</a></li>
<li><a href="https://codersera.com/blog/glm-5-3-cyber-capabilities-explained-2026/">GLM-5.3&#x27;s Cyber Capabilities: What&#x27;s Real, What&#x27;s Verified, What&#x27;s Marketing</a></li>
<li><a href="https://evolink.ai/blog/glm-5-3-cybersecurity">GLM-5.3 Cybersecurity: What the Cyber Benchmarks ...</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#cybersecurity`, `#frontier AI models`, `#Anthropic`, `#autonomous exploit development`

---

<a id="item-tech-news-6"></a>
### [China&\#x27;s generative AI users surpass 700 million, CNNIC reports](https://ysxw.cctv.cn/article.html?toc_style_id=feeds_default&amp;amp;item_id=187569887152346976&amp;amp;channelId=1119) ⭐️ 7.0/10

China&\#x27;s generative AI user base exceeded 700 million by the first half of 2026, with penetration above 50.0%, according to the China Internet Network Information Center&\#x27;s Generative AI Application Development Report \(2026\), released on September 29 and relayed by CCTV News. The report states that question-answering is the largest use case, used by 76.0% of users, while usage of general AI assistants and AI productivity/office tools each grew more than 100% year over year. It also puts China&\#x27;s intelligent computing capacity at 2,185 EFLOPS, up 177% year over year. These are CNNIC&\#x27;s own reported figures and have not been independently verified in the supplied material.

telegram · zaihuapd · Sep 29, 06:39

**「背景」** 中国互联网络信息中心（CNNIC）每年发布的《生成式人工智能应用发展报告》是该国生成式人工智能应用与算力规模的官方统计口径，2026 年版于 9 月 29 日发布，新华社等官方媒体同步转报了其中数据。报告中的用户规模属于测算值（“据测算”），且统计时点为 2026 年上半年，因此 7 亿这一数字反映的是上半年末的水平，而非 9 月发布当月的即时状态。

**「Capacity pressure」** The usage surge lands on compute infrastructure that is already heavily used: at end-June 2026, when generative AI users passed 700 million, national compute facilities reported a rack utilization rate of 71.4%, according to the same reporting round on China&\#x27;s 2185 EFLOPS intelligent compute figure. Organizations scaling AI assistant and office workloads into this environment face tighter headroom for additional capacity, while developers building those tools must plan for the doubling-in-usage segments rather than average growth.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sohu.com/a/1082223433_114760">我国生成式人工智能用户规模突破7亿人，普及率超50%_应用_模型_农业</a></li>
<li><a href="https://finance.sina.com.cn/jjxw/2026-09-29/doc-initnmwm2899391.shtml">我国生成式人工智能用户规模突破7亿人！最新报告发布→_新浪财经_新浪网</a></li>
<li><a href="https://www.news.cn/tech/20260720/63025e398f234092b9876272271417fb/c.html">我国智能算力规模达2185EFLOPS-新华网</a></li>
<li><a href="https://finance.sina.com.cn/jjxw/2026-07-27/doc-inikhckx3016685.shtml">我国智能算力规模达2185EFLOPS_新浪财经_新浪网</a></li>

</ul>
</details>

**Tags**: `#generative AI`, `#China`, `#AI adoption`, `#AI infrastructure`, `#industry report`

---

<a id="item-tech-news-7"></a>
### [Cloudflare launches cf CLI beta for AI agents, covering 3,000+ API operations](https://blog.cloudflare.com/cloudflare-cf-cli-launch/) ⭐️ 7.0/10

Cloudflare has released an open beta of cf, a command-line tool intended to let developers and AI agents call its full API surface from the terminal. Unlike the existing Wrangler CLI, which covers roughly 280 operations, cf is generated from Cloudflare&\#x27;s API schema and covers more than 3,000 API operations. The tool defaults to JSON output and supports command search and guided flows so agents can discover and execute operations and process results, with Cloudflare citing examples such as creating and deploying a Worker, monitoring services, configuring Access and WAF, and purchasing a domain through the same tool. The announcement describes an open beta, so the capability is not yet a finished, generally available product.

telegram · zaihuapd · Sep 29, 13:46

**「Background」** Cloudflare&\#x27;s existing Wrangler CLI covers about 280 operations, while the company&\#x27;s full API surface includes more than 3,000 operations. Earlier coverage described cf as a unified CLI covering nearly 3,000 API operations, with consistent command naming and output optimized for both humans and AI agents \(tool-2-1\).

**「Impact」** Developers and agent builders get a single tool covering API operations that Wrangler does not expose, with JSON-first output suited to programmatic parsing. Because cf is in open beta and Wrangler remains the established tool for Worker workflows at about 280 operations, teams should treat cf as an addition rather than a drop-in replacement until its coverage and stability are proven.

<details><summary>References</summary>
<ul>
<li><a href="https://daily.dev/posts/building-a-cli-for-all-of-cloudflare-g1wqazat0">Building a CLI for all of Cloudflare | daily.dev</a></li>

</ul>
</details>

**Tags**: `#Cloudflare`, `#AI agents`, `#CLI`, `#Developer tools`, `#API`

---

<a id="item-tech-news-8"></a>
### [Google fixes Firebase backend bug that crashed iOS apps](https://github.com/firebase/firebase-ios-sdk/issues/16728) ⭐️ 7.0/10

Google confirmed that the iOS backend for Google Analytics for Firebase returned malformed data, causing apps that integrate the component to crash at launch. The incident began on September 28, 2026 at 17:41 PDT and the fix finished rolling out at 19:52 PDT, according to Google. Google said no SDK or app update is required; because of caching, some apps could continue crashing for up to about four hours after the fix, and residual problems will clear on their own. The account comes from a GitHub issue thread and a 9To5Google report summarized in a Telegram channel, with limited technical detail on the root cause.

telegram · zaihuapd · Sep 29, 16:29

**「Background」** Google Analytics for Firebase is an analytics SDK that iOS apps integrate and initialize as part of app startup, so data returned by Firebase&\#x27;s backend can affect launch behavior. That server-side dependency explains how a malformed backend response could cause startup crashes across many apps without developers needing to ship a new app version.

**「Impact」** Because the fault was server-side, developers integrating Google Analytics for Firebase do not need to ship an SDK or app update; instead, teams should expect launch crashes to continue on cached devices for up to roughly four hours after the 19:52 PT fix, with residual failures clearing without intervention. The immediate work falls to monitoring and support rather than code changes — one account cited crash spikes of about 2.7K in 25 minutes — so developers may need to handle user reports and store complaints until device caches expire.

<details><summary>References</summary>
<ul>
<li><a href="https://x.com/i/trending/2104833461496533360">Firebase SDK Crash Hits Thousands of iPhone Apps / X</a></li>

</ul>
</details>

**Tags**: `#Firebase`, `#iOS`, `#Google Analytics`, `#线上故障`, `#移动开发`

---

## Financial News

<a id="item-finance-news-1"></a>
### [China to subsidize new first-home mortgages by 1 percentage point a year from Oct. 1](https://jrs.mof.gov.cn/zhengcefabu/phjr/202609/t20260929_3998312.htm) ⭐️ 8.0/10

China&\#x27;s Ministry of Finance, the People&\#x27;s Bank of China and the National Financial Regulatory Administration announced on Sept. 29 that newly issued commercial mortgages for first homes nationwide will receive a central-government interest subsidy of 1 percentage point a year, for up to five years, starting Oct. 1, 2026; the policy is tentatively set to run for one year.

telegram · zaihuapd · Sep 29, 10:18

**「Background」** Under the notice, the central government pays the subsidy based on loan principal, lowering the effective interest cost for eligible new first-home mortgages; “first-home” status follows existing rules and can cover new or second-hand homes, but a new loan used only to replace an existing mortgage does not qualify.

**「Impact」** Eligible first-time buyers are those whose home costs 1.5 million yuan or less, is no larger than 120 square metres, and is financed with a new loan — not one that replaces an existing mortgage; because the subsidised principal is capped at 1 million yuan per household, the source estimates a maximum benefit of about 10,000 yuan a year per household.

<details><summary>References</summary>
<ul>
<li><a href="https://sinocism.com/p/incremental-policy-support-wang-yis">Incremental policy support; Wang Yi&#x27;s message to Japan - Sinocism</a></li>

</ul>
</details>

**Tags**: `#China housing policy`, `#mortgage interest subsidy`, `#fiscal stimulus`, `#real estate market`, `#first-time homebuyers`

---

<a id="item-finance-news-2"></a>
### [Fair Isaac Falls 18% on Mortgage Pricing Change; CarMax, AMD Gain](https://www.cnbc.com/2026/09/29/stocks-making-the-biggest-moves-premarket-fair-isaac-spacex-amd-more.html) ⭐️ 7.0/10

Fair Isaac shares plunged 18% in premarket trading after Federal Housing Finance Agency director Bill Pulte said Fannie and Freddie will move to a single mortgage pricing grid, allowing VantageScore to join the existing FICO Classic grid. CarMax gained more than 6% on second-quarter earnings of $1.16 per share and $7.88 billion in revenue, beating FactSet estimates of 73 cents and $7.09 billion, while AMD rose over 1% after acquiring AI firm World Labs for $8.2 billion.

rss · CNBC Finance · Sep 29, 12:03

**「Background」** The Federal Housing Finance Agency said in July 2025 that mortgage lenders could use either VantageScore 4.0 or FICO&\#x27;s Classic credit score, a step toward giving FICO a rival in mortgage pricing. AMD&\#x27;s acquisition target, World Labs, is a San Francisco lab founded by AI researcher Fei-Fei Li that builds &quot;world models,&quot; and the $8.2 billion price is being paid in AMD stock.

<details><summary>References</summary>
<ul>
<li><a href="https://www.fhfa.gov/policy/credit-scores">Credit Scores | FHFA</a></li>
<li><a href="https://www.cnbc.com/2026/09/28/amd-fei-fei-li-world-labs.html">AMD acquiring Fei-Fei Li&#x27;s World Labs AI firm in deal worth $8.2 billion</a></li>

</ul>
</details>

**Tags**: `#Premarket Movers`, `#Mortgage Pricing`, `#M&amp;A`, `#Earnings`, `#Pharma Investment`

---

<a id="item-finance-news-3"></a>
### [China Raises IPO Bar for Humanoid Robot Startups, Sources Say](https://www.cnbc.com/2026/09/29/china-criteria-humanoid-robot-ipos.html) ⭐️ 7.0/10

China&\#x27;s securities regulator has set three criteria for humanoid robot startups seeking to go public — sustainable revenue and commercial orders, narrowing losses with a three-year forecast, and core technology such as a robot brain or hands — according to three anonymous sources familiar with the CSRC&\#x27;s thinking. Two of the sources said at least two dozen humanoid-related &quot;embodied AI&quot; companies have already filed to list in Hong Kong, and the sources expect only a handful, or none, to meet the bar.

rss · CNBC Finance · Sep 29, 07:19

**「Background」** China&\#x27;s securities regulator steers listings through informal &quot;window guidance&quot; — verbal instructions rather than published rules — and earlier reporting said it had already held back some humanoid-robot IPOs after Unitree&\#x27;s volatile Shanghai debut in August 2026. Mainland companies listing in Hong Kong also need the CSRC&\#x27;s approval, which is why its stance affects the two dozen or more humanoid-related firms that have filed there.

**「Who is affected」** The stricter bar falls most directly on the two dozen or more humanoid and embodied-AI companies that have already filed to list in Hong Kong, and on their early-stage investors, since mainland Chinese firms need the CSRC&\#x27;s approval before a Hong Kong listing can go ahead.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reuters.com/business/finance/china-slows-humanoid-robot-ipo-rush-hype-outruns-reality-2026-09-21/">China slows humanoid robot IPO rush as hype outruns reality - Reuters</a></li>
<li><a href="https://www.theinformation.com/articles/china-curbs-humanoid-ipos-unitrees-volatile-debut">China Curbs Humanoid IPOs After Unitree&#x27;s Volatile Debut</a></li>
<li><a href="https://www.cnbc.com/2026/09/29/china-criteria-humanoid-robot-ipos.html">China &#x27;s criteria for humanoid robot IPOs may be hard to meet</a></li>
<li><a href="https://gokhshtein.com/news/2026-09-09-china-tightens-humanoid-robot-ipo-rules-after-unitrees-45">China Tightens Humanoid Robot IPO Rules After Unitree &#x27;s 45...</a></li>

</ul>
</details>

**Tags**: `#China humanoid robots`, `#IPO regulation`, `#CSRC`, `#embodied AI`, `#market valuations`

---

<a id="item-finance-news-4"></a>
### [Oracle Issues Force Majeure Notice on Stargate Data Center](https://www.bloomberg.com/news/articles/2026-09-24/oracle-cites-force-majeure-to-shield-itself-on-controversial-data-center) ⭐️ 7.0/10

Oracle has sent a force majeure notice to the developer of Stargate&\#x27;s Project Jupiter data center in New Mexico, citing stalled environmental and power approvals for its planned 2.45 GW microgrid that put the project&\#x27;s 2028 start-up at risk, according to Bloomberg. The report said the $18 billion syndicated loan tied to the project is trading at a discount.

telegram · zaihuapd · Sep 29, 05:46

**「Background」** Force majeure is a contract clause that lets a party suspend obligations when outside events — here, stalled environmental and power permits — prevent it from performing. Project Jupiter is part of Stargate, the AI data center buildout tied to OpenAI, and its developer is a unit of Blue Owl Capital; Oracle&\#x27;s notice would let it delay payments if the campus misses its 2028 target to come online.

**「Impact」** Banks and other lenders holding the roughly $18 billion syndicated loan tied to Project Jupiter are directly affected, as the debt is trading below face value amid the risk that the New Mexico data center&\#x27;s 2028 start is delayed.

<details><summary>References</summary>
<ul>
<li><a href="https://digg.com/tech/2ea4aafe-0363-47b6-a12d-97b7e81927d1">Oracle reportedly sends force - majeure notice over New Mexico data ...</a></li>
<li><a href="https://www.youtube.com/watch?v=mNozPwLvJIY">Oracle Is Paying for a Data Center It Can&#x27;t Use - YouTube</a></li>
<li><a href="https://techcrunch.com/2026/09/24/oracle-sends-force-majeure-notice-on-its-new-mexico-stargate-data-center/">Oracle sends force majeure notice on its New Mexico Stargate data ...</a></li>
<li><a href="https://www.youtube.com/watch?v=ZrA_SVa961Q">Oracle &#x27;s $ 18 Billion AI Data Center Debt Comes Under... - YouTube</a></li>

</ul>
</details>

**Tags**: `#甲骨文`, `#星际之门`, `#AI数据中心`, `#项目融资`, `#电力审批`

---