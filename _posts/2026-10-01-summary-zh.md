---
layout: default
title: "Horizon Summary: 2026-10-01 (ZH)"
date: 2026-10-01
lang: zh
---

> 从 40 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [谷歌公布 Gemini 4 Argon：代理编码进展与未开放状态](#item-tech-news-1) ⭐️ 9.0/10
2. [32 位研究者发布现代 NLP 分词综合综述](#item-tech-news-2) ⭐️ 8.0/10
3. [Reddit 将停用 RSS 订阅并关闭公开 API](#item-tech-news-3) ⭐️ 8.0/10
4. [OpenAI 称瓦解模型蒸馏活动，指向月之暗面相关人员](#item-tech-news-4) ⭐️ 8.0/10
5. [特朗普与六大科技巨头签署一页 AI 安全协议](#item-tech-news-5) ⭐️ 7.0/10
6. [Cloudflare 宣布计划成为公共证书颁发机构](#item-tech-news-6) ⭐️ 7.0/10
7. [B 站开源 Index-Translate 翻译模型，支持 150 种语言](#item-tech-news-7) ⭐️ 7.0/10

**财经新闻**
1. [盘前个股异动：波音拿下 200 亿美元战机合同上涨，Moderna 遭花旗下调评级下跌](#item-finance-news-1) ⭐️ 7.0/10
2. [北京警告欧盟：若限制中国企业将坚决回应](#item-finance-news-2) ⭐️ 7.0/10
3. [中国为人形机器人 IPO 设三项新门槛，多数申请企业恐难达标](#item-finance-news-3) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [谷歌公布 Gemini 4 Argon：代理编码进展与未开放状态](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-4-argon/) ⭐️ 9.0/10

谷歌发布了 Gemini 4 Argon 的公告，但该模型尚未面向开发者、企业和消费者普遍开放。公告称，Argon 代理正在将 Google 的 C/C++ 代码库迁移到 Rust，公司会继续从早期测试者收集反馈并迭代护栏，然后尽快开放。现有摘录没有给出模型参数、基准分数或具体发布日期，因此目前能确认的是公告与早期测试状态，而非已完成的广泛发布或独立测得的性能结果。

hackernews · bradleyg223 · 9月30日 20:04 · [社区讨论](https://news.ycombinator.com/item?id=49913571)

**「背景」** Gemini 4 Argon 属于 Google 的 Gemini 模型系列，Google 官方博客将其定位为面向真实编码、企业知识工作和网络防御的前沿模型，并称其“即将推出”。据 DataCamp 报道，Google DeepMind 高级副总裁 Koray Kavukcuoglu 于 2026 年 9 月 30 日发布该模型，其覆盖范围是长周期任务，包括真实软件工程、法律与金融知识工作以及网络防御，且这一版本会先提供给网络安全团队，之后才面向开发者和企业。

**「对开发者的影响」** Argon 目前还无法直接使用：官方发布页称其“即将推出”，Google 表示会先继续收集早期测试者的反馈、迭代 guardrails，之后才向开发者、企业和消费者开放（tool-3-3）。Google 说明的内部用途集中在 C/C++ 到 Rust 的大规模迁移、数据中心内存优化和性能调优（tool-3-2），因此关心代码迁移的团队需要等待正式开放及访问条件公布，而不是现在就能接入。一个被引用的具体案例是 libgav1 视频解码器迁移中 Argon 替换了约 3.2 万行 SIMD 汇编，产出比原有 Rust 实现快 2.7 倍且输出逐位一致（tool-3-1）；该数字出自第三方整理而非 Google 官方基准，应谨慎看待。

**「社区讨论」** 评论区中，taylorfinley 称 Gemini 3.8 Flash 曾帮助其用 GDB 逆向 GPU 驱动并编写 LD\_PRELOAD shim，以便在 128GB Strix Halo 上运行 ROCm llama.cpp；nickysielicki 则认为今年的模型交替领先表明 AI 并非赢家通吃，而是更分散。也有评论关注 Argon 尚未开放、护栏仍在迭代，并提到其代理被用于将 C/C++ 迁移到 Rust。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-4-argon/">Introducing Gemini 4 Argon - The Keyword</a></li>
<li><a href="https://www.datacamp.com/blog/gemini-4-argon">Gemini 4 Argon: Benchmarks, Pricing, and Access | DataCamp</a></li>
<li><a href="https://saascity.io/blog/gemini-4-argon-benchmarks-pricing-fairwind-2026">Gemini 4 Argon: Benchmarks, Pricing &amp; Fairwind (2026)</a></li>
<li><a href="https://promptblueprints.tech/news-article/what-google-says-gemini-4-argon-agents-do-internally/">What Gemini 4 Argon Agents Do at Google - promptblueprints.tech</a></li>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-4-argon/">Introducing Gemini 4 Argon - The Keyword</a></li>

</ul>
</details>

**标签**: `#Gemini 4`, `#large language models`, `#AI agents`, `#Google`, `#code migration`

---

<a id="item-tech-news-2"></a>
### [32 位研究者发布现代 NLP 分词综合综述](https://www.reddit.com/r/MachineLearning/comments/1wuccjf/tokenization_a_survey_for_modern_nlp_r/) ⭐️ 8.0/10

一项覆盖现代自然语言处理（NLP）中分词（tokenization）的大型协作综述已发布，参与者共有 32 位分词研究者，历时约 8 个月完成。该综述覆盖分词算法、评测、多语言、编码、理论等主题，并讨论潜在 tokenization、视觉 tokenization 等可能替代分词器的方向。它还涉及与分词密切相关的约束生成、token healing 和分词器安全问题。全文可在 alphaxiv 链接查看；目前这是综述性发布，而非新的模型、工具或基准结果。

reddit · r/MachineLearning · /u/mcmcmcmcmcmcmcmcmc\_ · 9月30日 18:13

**「背景」** 分词器把文本切分为词元，是语言模型处理输入输出的前置步骤。该帖称，这一领域尽管影响遍及整个 NLP，却仍未被充分研究，因此需要一份覆盖多个子方向的系统梳理。

**「影响」** 对 NLP 研究者和工程师来说，这份综述的直接用途是提供一个汇总算法、评测、多语言与理论等方向的参考入口，便于按主题查找相关工作；但选择具体分词方案时仍需结合自身模型与任务做验证。

**标签**: `#NLP`, `#tokenization`, `#survey`, `#language modeling`, `#machine learning`

---

<a id="item-tech-news-3"></a>
### [Reddit 将停用 RSS 订阅并关闭公开 API](https://techcrunch.com/2026/09/30/reddit-is-killing-rss-feeds-ending-public-api-access-because-of-ai-bots/) ⭐️ 8.0/10

Reddit 宣布将于 11 月 13 日停止支持 RSS 订阅，并计划在 2027 年 3 月关闭公开 API 访问。该公司称 RSS 已成为大规模抓取和自动化滥用的常见渠道，尤其涉及 AI 机器人。Reddit 建议版主改用 Discord Relay，并提醒第三方应用和机器人开发者须在 2027 年 1 月 12 日前完成注册，否则将被移除 API 访问权限。上述均为 Reddit 公布的停用时间表，而非已经完成的变化。

telegram · zaihuapd · 10月1日 00:27

**「背景」** RSS 是一种标准化的网络订阅格式，用户和应用程序可通过它按统一格式获取网站更新，而无需直接抓取页面。Reddit 的公开 API 此前也为第三方应用和机器人提供了程序化读取内容的渠道，因此 RSS 与公开 API 的先后关闭将同时切断这两种非官方访问路径。

**「对开发者的直接影响」** 对第三方应用和机器人开发者而言，最直接的后果是必须在 2027 年 1 月 12 日前完成向 Reddit 的注册，否则将被移除 API 访问权限（tool-3-1、tool-3-2）。Reddit 为合规开发者设立 100 万美元迁移基金，单个获批应用最高可获 1000 美元，同时建议依赖 RSS 的版主改用 Discord Relay 这一 Devvit 应用作为部分替代（tool-3-2、tool-3-3）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/09/30/reddit-is-killing-rss-feeds-ending-public-api-access-because-of-ai-bots/">Reddit is killing RSS feeds and ending public API access because of...</a></li>
<li><a href="https://daily.dev/posts/reddit-is-killing-rss-feeds-and-ending-public-api-access-because-of-ai-bots-etgqokzhb">Reddit is killing RSS feeds and ending public API access...</a></li>
<li><a href="https://mrsinternet.com/reddit-ceases-rss-support-and-limits-public-api-access-citing-scraping-and-monetization-goals/">Reddit Ceases RSS Support and Limits Public API Access, Citing...</a></li>
<li><a href="https://diasporadigitalmedia.com/reddit-cuts-public-api-access-and-rss-feeds-over-ai-bots/">Reddit Cuts Public API Access and RSS Feeds Over AI Bots...</a></li>

</ul>
</details>

**标签**: `#Reddit`, `#API access`, `#RSS`, `#AI scraping`, `#platform policy`

---

<a id="item-tech-news-4"></a>
### [OpenAI 称瓦解模型蒸馏活动，指向月之暗面相关人员](https://openai.com/index/disrupting-a-coordinated-model-distillation-campaign/) ⭐️ 8.0/10

OpenAI 表示已瓦解一起针对其模型的蒸馏活动，攻击者通过操纵交互来提取受保护的推理内容。据 OpenAI 的说法，该活动最早出现在 2026 年 7 月初，7 月 24 至 25 日达到高峰，涉及 4000 多名用户的约 1.6 万次请求；到 7 月 28 日，OpenAI 已瓦解与 1.5 万余名用户相关的活动。OpenAI 将核心活动归因于与月之暗面（Kimi 开发商）有关的人员，并通过 Frontier Model Forum 等渠道与业界和政府共享了相关信息。上述为 OpenAI 单方面的公告结论，来源为简要转述，尚未见到独立核实或月之暗面的回应。

telegram · zaihuapd · 10月1日 01:18

**「背景」** 模型蒸馏在此类争议中指通过大量交互提取模型受保护的推理内容，OpenAI 将这种逐步解题的中间过程视为受保护对象（tool-2-2）。这并非首次出现类似指控：TokenPost 报道称，Anthropic 曾指责月之暗面通过 Claude 转发 Kimi 请求以提取受保护推理数据，OpenAI 也披露过与 DeepSeek 相关的蒸馏活动（tool-2-3）；wccftech 的报道则称 OpenAI 正将月之暗面标为蒸馏活动的“惯犯”（tool-2-1）。

**「影响」** 由于 OpenAI 已将调查结果提交至 Frontier Model Forum 及政府渠道，其他前沿模型厂商和采用这些 API 的团队可能据此把批量交互式提取行为判定为安全事件并纳入信息共享流程。该公告未说明对月之暗面或涉事人员的具体处置（如封禁、法律行动），也未给出被提取内容涉及哪些模型或权重。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://wccftech.com/moonshot-ai-of-kimi-k3-fame-tried-to-crack-openais-encrypted-reasoning-through-16000-requests-bolstering-trump-administrations-distillation-claims/">Moonshot AI Of Kimi K3 Fame Tried To Crack OpenAI &#x27;s Encrypted...</a></li>
<li><a href="https://cryptobriefing.com/openai-disrupts-moonshot-ai-kimi-extraction/">OpenAI disrupts extraction attempts linked to Moonshot AI &#x27;s Kimi</a></li>
<li><a href="https://www.tokenpost.com/news/technology/25922">OpenAI and Anthropic Detail Separate AI Distillation ... | TokenPost</a></li>

</ul>
</details>

**标签**: `#AI security`, `#model distillation`, `#OpenAI`, `#Moonshot AI`, `#AI policy`

---

<a id="item-tech-news-5"></a>
### [特朗普与六大科技巨头签署一页 AI 安全协议](https://www.zaobao.com.sg/news/world/story20260930-9758185) ⭐️ 7.0/10

美国总统特朗普当地时间 9 月 29 日与谷歌、Anthropic、Meta、OpenAI、xAI 和英伟达的负责人共同签署了一份人工智能协议，并将一页文件发布在 Truth Social 上，特朗普称该文件具有“道义约束力”。协议要求企业建立四层控制机制：配合外部审计机构对 AI 管控系统进行独立评估，设立董事会独立委员会进行监督，并在模型训练和部署期间围绕网络安全、生物和化学威胁监控 AI 能力与对齐情况，确保措施按预期运行。该协议为自愿性质，未包含强制执行机制或具体技术细节。

telegram · zaihuapd · 9月30日 02:30

**「背景」** 这项协议由白宫推动、性质为自愿承诺，而非国会立法或强制性监管要求。它出台之际，外界正不断呼吁对能力强大的 AI 施加更严格的约束，因此签署方的承诺能否替代正式规则仍是核心争议点。

**「实际影响」** 由于该协议是自愿且“道义约束力”的一页文件，外部审计结果可能仅向董事会独立委员会报告，而不要求向公众披露，因此依赖这些 AI 系统的开发者和企业无法仅凭签署事实确认合规。相关企业宜在采购或合作时要求可核验的审计证据或合同保障，而不是把该协议当作已认证的安全保证。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/09/30/openai-google-and-meta-pledge-outside-ai-audits-under-voluntary-white-house-deal">OpenAI, Google and Meta pledge independent AI safety audits ...</a></li>
<li><a href="https://www.cbsnews.com/news/trump-ai-constitution-tech-execs-openai-anthropic-voluntary-controls/">Trump and major AI executives sign &quot;morally binding ...</a></li>
<li><a href="https://xenospectrum.com/en/white-house-ai-safety-accord/">Six Major AI Firms Sign Voluntary Safety Accord With Board ...</a></li>
<li><a href="https://ravody.com/when-ai-labs-self-police-voluntary-safety-commitments/">When AI Labs Self-Police: The Debate Over Voluntary Safety ...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#AI governance`, `#AI policy`, `#tech industry`

---

<a id="item-tech-news-6"></a>
### [Cloudflare 宣布计划成为公共证书颁发机构](https://blog.cloudflare.com/cloudflare-certificate-authority/) ⭐️ 7.0/10

Cloudflare 宣布计划进军公共证书颁发机构（CA）业务，已申请加入 Chrome、Apple、Microsoft 和 Mozilla 的根证书计划，并与 GlobalSign 签署协议收购一个被广泛信任的根证书。该公司表示，新 CA 将优先支持 ACME 自动签发和续期，并计划在 2027 年第一季度签发生产级默克尔树证书（MTC），以服务后量子互联网。需要说明的是，这些都是尚未落地的规划：Cloudflare 目前尚未开始签发任何证书，生产级 MTC 也要到 2027 年才预计推出。

telegram · zaihuapd · 9月30日 06:26

**「背景」** 公共证书颁发机构签发的 TLS 证书要被浏览器普遍信任，前提是其根证书被 Chrome、Apple、Microsoft、Mozilla 等根证书计划接纳，这也解释了 Cloudflare 为何先申请根计划并通过收购取得受信任根证书。默克尔树证书（MTC）则是面向后量子 HTTPS 的新证书格式：据 The Hacker News 报道，Google 正在 Chrome 中测试 MTC，并计划到 2027 年推出新的根存储。Cloudflare 此前已与 Chrome 联合启动 MTC 实验，评估其能否在不降低性能、不改变 WebPKI 信任关系的前提下工作，这构成其 2027 年第一季度生产级 MTC 计划的先导工作。

**「实际影响」** 对目前依赖其他 CA 或 Cloudflare 现有证书服务的网站运营者来说，短期内无法切换到 Cloudflare 签发的证书：Cloudflare 尚未开始签发任何证书，且必须先通过 Chrome、Apple、Microsoft 和 Mozilla 根证书计划的审核，其从 GlobalSign 收购的受信任根证书也才能承载被普遍接受的信任链。若计划如期推进，优先支持 ACME 意味着现有自动化签发与续期流程可继续沿用，而面向后量子互联网的生产级默克尔树证书要到 2027 年第一季度才计划签发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thehackernews.com/2026/03/google-develops-merkle-tree.html">Google Develops Merkle Tree Certificates to Enable...</a></li>
<li><a href="https://blog.cloudflare.com/bootstrap-mtc/">Keeping the Internet fast and secure- introducing Merkle Tree ...</a></li>

</ul>
</details>

**标签**: `#Cloudflare`, `#公共证书颁发机构`, `#后量子密码学`, `#ACME`, `#网络安全`

---

<a id="item-tech-news-7"></a>
### [B 站开源 Index-Translate 翻译模型，支持 150 种语言](https://www.ithome.com/1/008/914.htm) ⭐️ 7.0/10

哔哩哔哩 Index LLM 团队于 9 月 30 日开源 Index-Translate 多语言翻译模型家族，2B、9B 和 35B-A3B（预览版）文本模型权重已在 Hugging Face 与 ModelScope 开放，支持 150 种语言。模型基于 Qwen3.5 构建，支持术语、格式和保留内容等翻译指令，并扩展至语音翻译、音节可控翻译和长文档翻译。其中 35B-A3B 仍为预览版，官方公告未提供基准测试或评测结果。

telegram · zaihuapd · 9月30日 14:08

**「技术底座与依据」** Index-Translate 建立在 Qwen3.5 之上，这一底座决定了它的多语言与指令跟随能力，权重按 2B、9B、35B-A3B 等不同规模分别发布。官方模型卡称 9B 版本在家族自建评测中翻译质量可对标 100B 级翻译模型与前沿 LLM，这属于厂商自述而非独立测试结果；GitHub 仓库同时提供在线演示与技术报告入口。

**「对开发者与本地化流程的影响」** 对需要自托管翻译能力的团队而言，2B、9B 与 35B-A3B（preview）权重已在 Hugging Face 与 ModelScope 开放下载，可按规模与算力自行部署，无需依赖闭源翻译 API；模型基于 Qwen3.5 构建，因此本地推理环境需支持该架构。术语、格式与保留内容等指令控制对有术语一致性要求的本地化流程更直接可用，但公告未给出任何质量基准或与现有翻译系统的对比，35B-A3B 仍标注为 preview，实际选型前仍需自行评测。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/IndexTeam/Index-Translate-9B">IndexTeam/Index-Translate-9B · Hugging Face</a></li>
<li><a href="https://github.com/bilibili/Index-Translate">GitHub - bilibili/Index-Translate</a></li>

</ul>
</details>

**标签**: `#open source`, `#machine translation`, `#large language models`, `#multilingual AI`, `#model release`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [盘前个股异动：波音拿下 200 亿美元战机合同上涨，Moderna 遭花旗下调评级下跌](https://www.cnbc.com/2026/09/30/stocks-making-the-biggest-moves-premarket-hood-ba-mrna-.html) ⭐️ 7.0/10

波音盘前上涨 2%，此前美国国防部授予其 200 亿美元合同，开发第六代 F/A-XX 舰载战斗机；Moderna 下跌逾 6%，因花旗将其评级下调至“卖出”，给出的目标价较周二收盘价低 60%。Concentrix 因第三财季营收略低于预期下跌 9.5%，Cal-Maine Foods 因第一财季每股亏损 1.26 美元、大于分析师预期的 77 美分而下跌逾 6.5%。

rss · CNBC Finance · 9月30日 11:38

**「背景」** 波音的这份合同由美国海军于 2026 年 9 月 29 日公布，属于“下一代空中优势”计划，要求其研制用于接替 F/A-18 的第六代舰载战斗机；此前也曾参与竞标的诺斯罗普·格鲁曼表示已提交方案，并期待获得更多遴选信息。莫德纳方面，花旗分析师 Geoff Meacham 将其评级从“持有”下调至“卖出”，目标价虽从 60 美元上调至 80 美元，但仍远低于该股近期约 203 美元的交易水平。

**「影响」** 这份合同意味着同样参与竞标的诺斯罗普·格鲁曼出局，其股价盘前下跌 3.5%，将无法从这批第六代战机研发订单中获得收入。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.yahoo.com/news/politics/articles/navy-awards-boeing-20b-contract-161132914.html?fr=sycsrp_catchall">Navy awards Boeing $20B contract for F/A-XX sixth-generation ...</a></li>
<li><a href="https://www.defensenews.com/industry/techwatch/2026/09/29/us-navy-selects-boeing-to-build-next-generation-fa-xx-fighter/">US Navy selects Boeing to build next-generation F/A-XX fighter</a></li>
<li><a href="https://247wallst.com/investing/2026/09/30/moderna-sinks-6-on-citi-downgrade-merck-and-pfizer-stay-flat/">Moderna Sinks 6% on Citi Downgrade ; Merck and... - 24/7 Wall St.</a></li>
<li><a href="https://www.marketscreener.com/news/citigroup-downgrades-moderna-to-sell-from-neutral-adjusts-price-target-to-80-from-60-ce785ad2dc80f024">Citigroup Downgrades Moderna to Sell From Neutral, Adjusts Price ...</a></li>
<li><a href="https://www.cnbc.com/2026/09/30/stocks-making-the-biggest-moves-premarket-hood-ba-mrna-.html">Stocks making the biggest moves premarket: HOOD, BA, MRNA - CNBC</a></li>

</ul>
</details>

**标签**: `#premarket-stock-movers`, `#defense-contracts`, `#earnings-results`, `#analyst-ratings`, `#online-brokerage`

---

<a id="item-finance-news-2"></a>
### [北京警告欧盟：若限制中国企业将坚决回应](https://www.cnbc.com/2026/09/30/china-warns-europe-increases-trade-pressure.html) ⭐️ 7.0/10

中国商务部警告欧盟，如果在贸易谈判期间对中国企业或产品设限，中方将“坚决回应”，并称此举会“严重破坏互信”、干扰谈判。此前欧盟贸易委员马罗什·谢夫乔维奇要求北京在 10 月前拿出“具体成果”，否则将面临“更严厉措施”；据欧洲官员说法，德法正敲定一份联合文件，推动欧盟委员会加快发展一种类似美国“301 条款”的工具，中国商务部称其声明正是针对欧方考虑此类工具。欧盟表示，计入服务贸易后，去年欧中贸易总额为 8800 亿欧元（近 1 万亿美元），欧盟对华货物贸易逆差为全球最大。

rss · CNBC Finance · 9月30日 03:39

**「背景」** 欧盟目前主要依靠反倾销和反补贴调查来应对贸易争端，而所谓“301 条款”式工具源自美国法律，允许政府对被认定采取不公平贸易做法的国家加征关税（tool-1-3）。此次摩擦的背景是，欧盟希望中国在 10 月前拿出具体成果，以削减其对华创纪录的贸易逆差。

**「潜在影响」** 若欧盟最终推出针对中国企业或产品的限制，每年近 1 万亿美元的中欧双边贸易所涉及的欧洲进口商与中国出口商将直接承担更高关税和市场准入成本；一项 2026 年 6 月的研究已量化欧盟与中国关税升级及相互反制在三种情景下的经济代价。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.firstpost.com/business/china-eu-trade-tensions-section-301-trade-tool-beijing-eu-trade-policy-14049259.html">China warns of ‘resolute response’ as EU weighs US- style trade tool...</a></li>
<li><a href="https://feb.kuleuven.be/VIVES/publications/discussion_papers/dp-2026/the-impact-of-eu-china-tariff-escalation-and-retaliation">The Impact of EU-China Tariff Escalation and Retaliation</a></li>

</ul>
</details>

**标签**: `#EU-China trade`, `#trade policy`, `#retaliation warning`, `#tariffs`, `#geopolitics`

---

<a id="item-finance-news-3"></a>
### [中国为人形机器人 IPO 设三项新门槛，多数申请企业恐难达标](https://www.cnbc.com/2026/09/29/china-criteria-humanoid-robot-ipos.html) ⭐️ 7.0/10

据三名了解中国证监会思路的知情人士，证监会以&quot;窗口指导&quot;方式要求拟上市的人形机器人（即&quot;具身智能&quot;）企业满足三项条件：拥有可持续的营收和商业订单；亏损收窄，一名消息人士称需提供三年预测；掌握&quot;机器人大脑&quot;或灵巧手等核心技术。两名消息人士称，仅在香港递交上市申请的人形机器人相关企业就至少有 24 家，但即使只须满足其中两项，也难有公司达标，这让市场预期降至仅少数甚至没有企业能上市；证监会未立即回应置评请求，香港交易所拒绝置评。

rss · CNBC Finance · 9月30日 02:50

**「背景」** 中国证监会是内地证券市场的监管机构，内地企业无论在上海上市还是赴香港上市，都需获得其批准。据行业媒体报道，证监会是在审阅了 2025 年底至 2026 年中期提交的十余份人形机器人上市申请后制定这三项标准的，其中多数企业的卖点仍是原型机而非已部署的产品，同时该板块估值已从 2026 年初的高点明显回落。

**「影响」** 若这一门槛落地，这批拟赴港上市的人形机器人初创企业的上市进程可能被推迟或搁置，其背后政府基金与私募投资者的退出通道也将相应收窄。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.roboticsintl.com/article/csrc-imposes-three-tier-ipo-screen-on-humanoid-robotics-startups-in-china">CSRC Imposes Three-Tier IPO Screen on Humanoid Robotics ...</a></li>

</ul>
</details>

**标签**: `#China regulation`, `#Humanoid robots`, `#IPOs`, `#Embodied AI`, `#Valuations`

---