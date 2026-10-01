---
layout: default
title: "Horizon Summary: 2026-10-01 (EN)"
date: 2026-10-01
lang: en
---

> From 40 items, 10 important content pieces were selected

---

**Technology News**
1. [Google announces Gemini 4 Argon, limited to early testers](#item-tech-news-1) ⭐️ 9.0/10
2. [32 Researchers Release Comprehensive Tokenization Survey for Modern NLP](#item-tech-news-2) ⭐️ 8.0/10
3. [Reddit to end RSS feeds and public API access over AI scraping](#item-tech-news-3) ⭐️ 8.0/10
4. [OpenAI says it disrupted model distillation campaign linked to Moonshot AI](#item-tech-news-4) ⭐️ 8.0/10
5. [Trump and six tech giants sign one-page AI safety agreement](#item-tech-news-5) ⭐️ 7.0/10
6. [Cloudflare plans to become a public certificate authority](#item-tech-news-6) ⭐️ 7.0/10
7. [Bilibili open-sources Index-Translate models with 150-language support](#item-tech-news-7) ⭐️ 7.0/10

**Financial News**
1. [Premarket Movers: Boeing Rises on $20 Billion Fighter Contract, Moderna Falls on Downgrade](#item-finance-news-1) ⭐️ 7.0/10
2. [China Warns EU of Firm Response Over Possible Curbs on Chinese Businesses](#item-finance-news-2) ⭐️ 7.0/10
3. [China Regulator Sets Three Criteria for Humanoid Robot IPOs, Sources Say](#item-finance-news-3) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Google announces Gemini 4 Argon, limited to early testers](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-4-argon/) ⭐️ 9.0/10

Google has announced Gemini 4 Argon, a new Gemini model version, but it is not yet broadly available. The announcement, as quoted in the Hacker News thread, says Google will continue gathering feedback from early testers and iterating on guardrails before making Argon available to developers, enterprises, and consumers &\#x27;as soon as possible.&\#x27; Discussion around the release points to agentic coding capabilities, including Argon agents working on migrating C/C++ codebases to Rust across Google, while the supplied excerpt lacks technical specifics such as benchmarks, pricing, or context limits.

hackernews · bradleyg223 · Sep 30, 20:04 · [Discussion](https://news.ycombinator.com/item?id=49913571)

**「Background」** Google DeepMind SVP Koray Kavukcuoglu introduced Gemini 4 Argon on September 30, 2026 as the company&\#x27;s frontier model for long-horizon work covering real-world software engineering, legal and financial knowledge work, and cyber defense. According to DataCamp&\#x27;s coverage of the announcement, the release reaches cybersecurity teams before it reaches developers, which is why access is described as forthcoming rather than already available.

**「What changes for developers」** Google says it is still gathering early-tester feedback and iterating on Argon&\#x27;s guardrails before making it available to developers, enterprises, and consumers, so teams cannot yet build against the model or plan migration work around it, and no firm release date has been given. The described internal use is large-scale code work — Google says Argon agents handle C/C++-to-Rust migrations and performance tuning, and one third-party writeup reports that Argon agents replaced roughly 32,000 lines of SIMD assembly in a Rust port of the libgav1 video decoder with code that ran 2.7x faster at bit-identical output — so the earliest measurable effect is inside Google&\#x27;s own engineering rather than in external developer toolchains.

**「Community Discussion」** Commenters debated competitive dynamics, with one arguing that continued leapfrogging this year contradicts Dario Amodei&\#x27;s &\#x27;concentrating&\#x27; winner-take-all thesis and another criticizing Google for not yet shipping Argon. One reported experience described Gemini 3.8 Flash attaching GDB to a GPU driver and authoring an LD\_PRELOAD shim to get ROCm llama.cpp working on a Strix Halo machine.

<details><summary>References</summary>
<ul>
<li><a href="https://www.datacamp.com/blog/gemini-4-argon">Gemini 4 Argon: Benchmarks, Pricing, and Access | DataCamp</a></li>
<li><a href="https://saascity.io/blog/gemini-4-argon-benchmarks-pricing-fairwind-2026">Gemini 4 Argon: Benchmarks, Pricing &amp; Fairwind (2026)</a></li>
<li><a href="https://promptblueprints.tech/news-article/what-google-says-gemini-4-argon-agents-do-internally/">What Gemini 4 Argon Agents Do at Google - promptblueprints.tech</a></li>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-4-argon/">Introducing Gemini 4 Argon - The Keyword</a></li>

</ul>
</details>

**Tags**: `#Gemini 4`, `#large language models`, `#AI agents`, `#Google`, `#code migration`

---

<a id="item-tech-news-2"></a>
### [32 Researchers Release Comprehensive Tokenization Survey for Modern NLP](https://www.reddit.com/r/MachineLearning/comments/1wuccjf/tokenization_a_survey_for_modern_nlp_r/) ⭐️ 8.0/10

A collaborative survey on tokenization in modern NLP has been posted to AlphaXiv, written by 32 tokenizer researchers over roughly eight months, according to the announcement. The authors say it covers algorithms, evaluation, multilinguality, encodings, and theory, plus alternatives to tokenizers such as latent and visual tokenization. It also addresses adjacent topics including constrained generation, token healing, and tokenizer security concerns. The post presents this as a literature survey rather than a new model, tokenizer, or benchmark release, and no measured results or versioned artifacts are described.

reddit · r/MachineLearning · /u/mcmcmcmcmcmcmcmcmc\_ · Sep 30, 18:13

**「Background」** Tokenization is the preprocessing step that splits raw text into the subword units a language model consumes, so vocabulary and segmentation choices shape sequence length and multilingual coverage. The post argues the area has been &quot;wildly understudied&quot; relative to its effects across NLP, which is the gap the survey is framed as addressing.

**「Impact」** For researchers and engineers weighing tokenizer design or replacement, the survey claims to consolidate evaluation methods, multilingual considerations, and practical failure modes such as token healing and tokenizer security into one reference. Because the announcement includes no benchmarks, code, or comparative results, it should be treated as a literature overview whose specific claims still need to be checked against the paper itself.

**Tags**: `#NLP`, `#tokenization`, `#survey`, `#language modeling`, `#machine learning`

---

<a id="item-tech-news-3"></a>
### [Reddit to end RSS feeds and public API access over AI scraping](https://techcrunch.com/2026/09/30/reddit-is-killing-rss-feeds-ending-public-api-access-because-of-ai-bots/) ⭐️ 8.0/10

Reddit said it will discontinue RSS feed support on November 13, calling RSS a common channel for large-scale scraping and automated abuse, particularly by AI bots, and will also close off public API access in March 2027. The company is directing moderators to switch to Discord Relay, and third-party apps and bot developers must complete registration by January 12, 2027 or have their API access removed. These are announced changes with stated deadlines; the item does not detail the registration requirements or what replaces the affected interfaces.

telegram · zaihuapd · Oct 1, 00:27

**「Background」** RSS \(Really Simple Syndication or Rich Site Summary\) is a standardized web feed format that lets users and applications access updates to a website in a consistent format, separate from a platform&\#x27;s public API. Reddit said RSS became a common channel for large-scale scraping and automated abuse, particularly by AI bots, which it cited as the reason for ending support.

**「Developer and moderator action required」** Third-party app and bot developers that depend on Reddit&\#x27;s public API must register their applications by January 12, 2027 or lose API access, with RSS-based integrations breaking earlier on November 13, 2026. Moderators who used RSS feeds are being directed to the Discord Relay Devvit app, and Reddit has set up a $1 million migration fund that can pay qualifying developers up to $1,000 per approved application to move onto its official Developer Platform.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/09/30/reddit-is-killing-rss-feeds-ending-public-api-access-because-of-ai-bots/">Reddit is killing RSS feeds and ending public API access because of...</a></li>
<li><a href="https://daily.dev/posts/reddit-is-killing-rss-feeds-and-ending-public-api-access-because-of-ai-bots-etgqokzhb">Reddit is killing RSS feeds and ending public API access...</a></li>
<li><a href="https://mrsinternet.com/reddit-ceases-rss-support-and-limits-public-api-access-citing-scraping-and-monetization-goals/">Reddit Ceases RSS Support and Limits Public API Access, Citing...</a></li>
<li><a href="https://diasporadigitalmedia.com/reddit-cuts-public-api-access-and-rss-feeds-over-ai-bots/">Reddit Cuts Public API Access and RSS Feeds Over AI Bots...</a></li>

</ul>
</details>

**Tags**: `#Reddit`, `#API access`, `#RSS`, `#AI scraping`, `#platform policy`

---

<a id="item-tech-news-4"></a>
### [OpenAI says it disrupted model distillation campaign linked to Moonshot AI](https://openai.com/index/disrupting-a-coordinated-model-distillation-campaign/) ⭐️ 8.0/10

OpenAI says it disrupted a coordinated model-distillation campaign in which operators manipulated interactions to extract protected reasoning content, and it attributes the core activity to individuals associated with Moonshot AI, the developer of Kimi. According to OpenAI, the activity began in early July 2026, peaked on July 24–25 with about 16,000 requests from more than 4,000 user accounts, and related activity involving more than 15,000 users had been disrupted by July 28. OpenAI says it shared its findings with industry and government channels, including the Frontier Model Forum. The account is OpenAI&\#x27;s own announcement: the source reports no response from Moonshot AI and no independent verification.

telegram · zaihuapd · Oct 1, 01:18

**「Background」** Model distillation normally involves training one model on another model&\#x27;s outputs; OpenAI describes the disrupted activity here as manipulating interactions to extract protected reasoning content. The accusation follows earlier industry distillation disputes: a TokenPost report says OpenAI had disclosed adversarial distillation activity tied to DeepSeek, while Anthropic accused Moonshot AI of routing Kimi requests through Claude and extracting protected reasoning data. Moonshot AI is the developer of the Kimi model family, including the widely used Kimi K3.

**「Impact」** OpenAI&\#x27;s decision to route the findings through the Frontier Model Forum and government channels means other model providers and regulators may receive the same account-level indicators behind the enforcement action. Because the source records no statement from Moonshot AI, organizations evaluating Kimi or assessing distillation risk currently have only OpenAI&\#x27;s unattributed-by-third-parties account to rely on.

<details><summary>References</summary>
<ul>
<li><a href="https://wccftech.com/moonshot-ai-of-kimi-k3-fame-tried-to-crack-openais-encrypted-reasoning-through-16000-requests-bolstering-trump-administrations-distillation-claims/">Moonshot AI Of Kimi K3 Fame Tried To Crack OpenAI &#x27;s Encrypted...</a></li>
<li><a href="https://www.tokenpost.com/news/technology/25922">OpenAI and Anthropic Detail Separate AI Distillation ... | TokenPost</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#model distillation`, `#OpenAI`, `#Moonshot AI`, `#AI policy`

---

<a id="item-tech-news-5"></a>
### [Trump and six tech giants sign one-page AI safety agreement](https://www.zaobao.com.sg/news/world/story20260930-9758185) ⭐️ 7.0/10

President Trump and the heads of Google, Anthropic, Meta, OpenAI, xAI, and Nvidia signed a one-page AI safety agreement on Sept. 29 local time and posted it on Truth Social. Trump described the document as &quot;morally binding.&quot; The agreement calls for four layers of control: independent external audits of companies&\#x27; AI control systems, oversight by an independent board committee, and monitoring of AI capabilities and alignment for cybersecurity, biological, and chemical threats during model training and deployment. It is a voluntary, high-level text with no stated enforcement mechanism or technical detail, and the source report does not show that the controls have been implemented.

telegram · zaihuapd · Sep 30, 02:30

**「Background」** The agreement is a voluntary White House pact, not a statute, and Trump described the one-page document as &quot;morally binding.&quot; CBS News reported it was signed as calls mounted for tighter guardrails on powerful AI systems.

**「Verification gap for users and regulators」** Because the agreement is only &quot;morally binding&quot; and routes oversight through company boards and external auditors rather than public disclosure, affected users, downstream developers, and regulators get no external way to confirm that the audits, board reviews, or cyber/bio/chem monitoring actually took place. Analysis of the pact specifically flags the gap between board-level reporting and public disclosure, and notes that voluntary commitments gain verification weight only when independent audit bodies have access comparable to financial auditors.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/09/30/openai-google-and-meta-pledge-outside-ai-audits-under-voluntary-white-house-deal">OpenAI, Google and Meta pledge independent AI safety audits ...</a></li>
<li><a href="https://www.cbsnews.com/news/trump-ai-constitution-tech-execs-openai-anthropic-voluntary-controls/">Trump and major AI executives sign &quot;morally binding ...</a></li>
<li><a href="https://xenospectrum.com/en/white-house-ai-safety-accord/">Six Major AI Firms Sign Voluntary Safety Accord With Board ...</a></li>
<li><a href="https://ravody.com/when-ai-labs-self-police-voluntary-safety-commitments/">When AI Labs Self-Police: The Debate Over Voluntary Safety ...</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#AI governance`, `#AI policy`, `#tech industry`

---

<a id="item-tech-news-6"></a>
### [Cloudflare plans to become a public certificate authority](https://blog.cloudflare.com/cloudflare-certificate-authority/) ⭐️ 7.0/10

Cloudflare announced plans to become a public certificate authority, saying it has applied to the Chrome, Apple, Microsoft, and Mozilla root certificate programs and signed an agreement with GlobalSign to acquire a widely trusted root certificate. The company has not yet begun issuing certificates, so this is an announced plan rather than a shipped capability. Cloudflare says the new CA will prioritize ACME for automated issuance and renewal, and it intends to issue production Merkle Tree Certificates \(MTC\) in the first quarter of 2027 to serve a post-quantum internet.

telegram · zaihuapd · Sep 30, 06:26

**「Background」** Cloudflare’s public-CA plan follows its earlier experiment with Chrome to evaluate Merkle Tree Certificates for fast, scalable, quantum-ready TLS without changing WebPKI trust relationships. Google has also been testing MTCs in Chrome as a route to quantum-resistant HTTPS, aiming to reduce TLS handshake data and launch a new root store by 2027.

**「Impact」** The practical effect for current certificate users is minimal for now: Cloudflare has not started issuing certificates, so existing certificate choices, ACME clients, and renewal workflows continue to run against today&\#x27;s CAs unchanged. Any move to Cloudflare-issued certificates depends on approval from the Chrome, Apple, Microsoft, and Mozilla root programs and on completing the GlobalSign root acquisition, and production Merkle Tree Certificates are only targeted for the first quarter of 2027 — so teams should treat this as a future option rather than something to plan a migration around yet.

<details><summary>References</summary>
<ul>
<li><a href="https://thehackernews.com/2026/03/google-develops-merkle-tree.html">Google Develops Merkle Tree Certificates to Enable...</a></li>
<li><a href="https://blog.cloudflare.com/bootstrap-mtc/">Keeping the Internet fast and secure- introducing Merkle Tree ...</a></li>

</ul>
</details>

**Tags**: `#Cloudflare`, `#公共证书颁发机构`, `#后量子密码学`, `#ACME`, `#网络安全`

---

<a id="item-tech-news-7"></a>
### [Bilibili open-sources Index-Translate models with 150-language support](https://www.ithome.com/1/008/914.htm) ⭐️ 7.0/10

Bilibili&\#x27;s Index LLM team released Index-Translate, a multilingual translation model family, on September 30, with 2B, 9B, and 35B-A3B \(preview\) text model weights now open on Hugging Face and ModelScope. The models support 150 languages and are built on Qwen3.5. According to the announcement, they accept translation instructions covering terminology, formatting, and content to be preserved, and the family extends to speech translation, syllable-controllable translation, and long-document translation. No benchmark results were disclosed, so the claimed translation quality is not independently verified.

telegram · zaihuapd · Sep 30, 14:08

**「Background」** Index-Translate is a family of multilingual translation models built on the Qwen3.5 backbone, which the Index LLM team adapted specifically for translation rather than general-purpose chat. The released text variants span 2B, 9B, and 35B-A3B sizes — the last labeled a preview — and the 9B model card claims translation quality comparable to 100B-scale translation models and frontier LLMs on the family&\#x27;s own evaluations.

**「Impact」** Developers and localization teams can now download the 2B, 9B, and 35B-A3B weights from Hugging Face and ModelScope and self-host or adapt them, with translation instructions for terminology, formatting, and preserved content aimed at controlled, glossary-consistent output. The 35B-A3B release is explicitly labeled a preview, so production users evaluating that size should treat it as pre-final, while the announced speech, syllable-controllable, and long-document extensions are described in the announcement without published benchmarks.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/IndexTeam/Index-Translate-9B">IndexTeam/Index-Translate-9B · Hugging Face</a></li>
<li><a href="https://github.com/bilibili/Index-Translate">GitHub - bilibili/Index-Translate</a></li>

</ul>
</details>

**Tags**: `#open source`, `#machine translation`, `#large language models`, `#multilingual AI`, `#model release`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Premarket Movers: Boeing Rises on $20 Billion Fighter Contract, Moderna Falls on Downgrade](https://www.cnbc.com/2026/09/30/stocks-making-the-biggest-moves-premarket-hood-ba-mrna-.html) ⭐️ 7.0/10

Boeing shares rose 2% in premarket trading after it secured a $20 billion U.S. Defense Department contract to develop the next-generation Sixth-Generation F/A-XX Strike Fighter, while Moderna fell more than 6% after Citi downgraded the stock to sell with a price target 60% below Tuesday&\#x27;s closing price. Cal-Maine Foods dropped more than 6.5% after reporting a fiscal first-quarter loss of $1.26 per share, wider than the 77-cent loss analysts polled by FactSet had expected.

rss · CNBC Finance · Sep 30, 11:38

**「Background」** The Boeing contract was awarded by the U.S. Navy on Sept. 29, 2026 under the Next Generation Air Dominance program, after Northrop Grumman had also competed for the work. Citi analyst Geoff Meacham downgraded Moderna to Sell from Hold and raised his price target to $80 from $60, a level still far below the stock&\#x27;s recent trading price of about $203.

<details><summary>References</summary>
<ul>
<li><a href="https://www.yahoo.com/news/politics/articles/navy-awards-boeing-20b-contract-161132914.html?fr=sycsrp_catchall">Navy awards Boeing $20B contract for F/A-XX sixth-generation ...</a></li>
<li><a href="https://www.defensenews.com/industry/techwatch/2026/09/29/us-navy-selects-boeing-to-build-next-generation-fa-xx-fighter/">US Navy selects Boeing to build next-generation F/A-XX fighter</a></li>
<li><a href="https://www.thedefensenews.com/Boeing-Wins-20-Billion-US-Navy-Contract-for-FA-XX-Sixth-Generation-Fighter/">Boeing Wins $20 Billion U.S. Navy Contract for F/A-XX Sixth ...</a></li>
<li><a href="https://247wallst.com/investing/2026/09/30/moderna-sinks-6-on-citi-downgrade-merck-and-pfizer-stay-flat/">Moderna Sinks 6% on Citi Downgrade ; Merck and... - 24/7 Wall St.</a></li>
<li><a href="https://www.marketscreener.com/news/citigroup-downgrades-moderna-to-sell-from-neutral-adjusts-price-target-to-80-from-60-ce785ad2dc80f024">Citigroup Downgrades Moderna to Sell From Neutral, Adjusts Price ...</a></li>

</ul>
</details>

**Tags**: `#premarket-stock-movers`, `#defense-contracts`, `#earnings-results`, `#analyst-ratings`, `#online-brokerage`

---

<a id="item-finance-news-2"></a>
### [China Warns EU of Firm Response Over Possible Curbs on Chinese Businesses](https://www.cnbc.com/2026/09/30/china-warns-europe-increases-trade-pressure.html) ⭐️ 7.0/10

China&\#x27;s commerce ministry said it will &quot;respond firmly&quot; if the European Union imposes restrictions on Chinese businesses or products, warning such steps would &quot;seriously undermine mutual trust&quot; and disrupt ongoing trade talks. The statement came ahead of expected high-level talks in Beijing next week, after EU Trade Commissioner Maroš Šefčovič said Beijing must deliver &quot;concrete results&quot; by October to cut Europe&\#x27;s record trade deficit with China or face &quot;harsher measures&quot;; European officials are reportedly weighing &quot;301&quot;-style tools, which have not been enacted.

rss · CNBC Finance · Sep 30, 03:39

**「Background」** The warning comes ahead of expected high-level talks in Beijing next week, as the EU presses China to reduce its record trade deficit by October and reportedly weighs a Section 301-style mechanism—similar to the U.S. law used to justify tariffs on Chinese goods. The EU currently relies on anti-dumping and anti-subsidy investigations for such trade disputes.

**「Impact」** If Brussels moves ahead with restrictions, EU exporters selling into China and Chinese firms selling into Europe would face higher tariffs and possible countermeasures, putting at risk the nearly $1 trillion in goods and services the two sides traded last year.

<details><summary>References</summary>
<ul>
<li><a href="https://www.firstpost.com/business/china-eu-trade-tensions-section-301-trade-tool-beijing-eu-trade-policy-14049259.html">China warns of ‘resolute response’ as EU weighs US- style trade tool...</a></li>
<li><a href="https://feb.kuleuven.be/VIVES/publications/discussion_papers/dp-2026/the-impact-of-eu-china-tariff-escalation-and-retaliation">The Impact of EU-China Tariff Escalation and Retaliation</a></li>

</ul>
</details>

**Tags**: `#EU-China trade`, `#trade policy`, `#retaliation warning`, `#tariffs`, `#geopolitics`

---

<a id="item-finance-news-3"></a>
### [China Regulator Sets Three Criteria for Humanoid Robot IPOs, Sources Say](https://www.cnbc.com/2026/09/29/china-criteria-humanoid-robot-ipos.html) ⭐️ 7.0/10

China&\#x27;s securities regulator, the China Securities Regulatory Commission \(CSRC\), has set three criteria through informal &\#x27;window guidance&\#x27; for humanoid robot startups seeking IPOs—sustainable revenue and commercial orders, narrowing losses, and core technology such as robotic brain or hands—according to three sources familiar with the CSRC&\#x27;s thinking. The sources said at least two dozen humanoid-related embodied AI companies have filed to list in Hong Kong, and the CSRC did not immediately respond to a request for comment.

rss · CNBC Finance · Sep 30, 02:50

**「Background」** Mainland Chinese companies need approval from the China Securities Regulatory Commission \(CSRC\) to list overseas, including in Hong Kong, where confidential IPO filings began in May 2025; the criteria described in the report are informal &quot;window guidance&quot; rather than published rules. Robotics International reported that the CSRC drew up the standards after reviewing more than a dozen humanoid robot IPO filings submitted between late 2025 and mid-2026 that centered on prototypes rather than deployed fleets, as sector valuations retreated from an early-2026 peak.

**「Impact」** The sources said the criteria have lowered expectations to just a handful, or none, of those companies making it to public markets, which could block most of them from raising public-market funding in Hong Kong.

<details><summary>References</summary>
<ul>
<li><a href="https://www.roboticsintl.com/article/csrc-imposes-three-tier-ipo-screen-on-humanoid-robotics-startups-in-china">CSRC Imposes Three-Tier IPO Screen on Humanoid Robotics ...</a></li>

</ul>
</details>

**Tags**: `#China regulation`, `#Humanoid robots`, `#IPOs`, `#Embodied AI`, `#Valuations`

---