---
layout: default
title: "Horizon Summary: 2026-09-27 (EN)"
date: 2026-09-27
lang: en
---

> From 30 items, 7 important content pieces were selected

---

**Technology News**
1. [SemiAnalysis Teardown Promises Look Inside Intel 18A, Panther Lake](#item-tech-news-1) ⭐️ 8.0/10
2. [Conversations leaves Google Play and goes free](#item-tech-news-2) ⭐️ 7.0/10

**Financial News**
1. [10-Year Treasury Yield Hits 5.23%, Highest Since 2007](#item-finance-news-1) ⭐️ 8.0/10
2. [Hong Kong SFC and PwC reach HK$1 billion Evergrande audit settlement](#item-finance-news-2) ⭐️ 8.0/10
3. [Xi says U.S. and China can overcome the &\#x27;Thucydides Trap&\#x27; on first state visit in 11 years](#item-finance-news-3) ⭐️ 7.0/10
4. [Apple faces class action over Apple Pay fees charged to card issuers](#item-finance-news-4) ⭐️ 7.0/10
5. [Volkswagen recalls 2.86 million vehicles worldwide over steering defect](#item-finance-news-5) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [SemiAnalysis Teardown Promises Look Inside Intel 18A, Panther Lake](https://newsletter.semianalysis.com/p/intel-panther-lake-teardown) ⭐️ 8.0/10

SemiAnalysis has published a free STEEL teardown article, dated September 26, 2026, that it describes as looking inside Intel&\#x27;s 18A process technology and Intel&\#x27;s Panther Lake processor. The supplied item is only a teaser for that piece: it contains no findings, measurements, performance figures, or technical detail, so the teardown&\#x27;s specific claims and conclusions cannot be verified or summarized here. No community comments were available for this item.

rss · Semianalysis · Sep 26, 13:36

**「Background」** Panther Lake is Intel&\#x27;s Core Ultra series 3 client processor and the company&\#x27;s first AI PC platform built on its in-house 18A node, which implements RibbonFET gate-all-around transistors and PowerVia backside power delivery. The design is assembled from separate tiles: a CPU tile manufactured on Intel 18A, an integrated graphics tile based on the Arc Xe3 architecture derived from Xe2 \(Battlemage\), and an I/O tile produced on TSMC&\#x27;s N6 process. SemiAnalysis&\#x27;s teardown is positioned as an examination of that 18A silicon and the Panther Lake package.

**「Why per-tile analysis matters」** Panther Lake is reported to be the first consumer chip built on Intel 18A, but only its compute tiles use 18A while the package stacks compute, GPU, and I/O tiles on a passive base tile via Foveros-S, so system-level benchmarks and power figures cannot isolate the process node&\#x27;s contribution. Engineers and foundry customers evaluating 18A will therefore need the teardown&\#x27;s per-tile die-level measurements rather than whole-package numbers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Panther_Lake_%28microprocessor%29">Panther Lake (microprocessor) - Wikipedia</a></li>
<li><a href="https://newsroom.intel.com/client-computing/intel-unveils-panther-lake-architecture-first-ai-pc-platform-built-on-18a">Intel Unveils Panther Lake Architecture: First AI PC Platform Built on 18A</a></li>
<li><a href="https://acemagic.com/blogs/about-ace-mini-pc/intel-panther-lake">Intel Panther Lake Core Ultra 300: Specs, Release Date &amp; 18A Node – ACEMAGIC</a></li>
<li><a href="https://www.tomshardware.com/pc-components/cpus/intel-panther-lake-samples-with-flagship-18a-node-have-been-powered-on-at-eight-customers-co-ceos-dispel-rumors-regarding-poor-silicon-health">Intel Panther Lake samples with flagship 18 A node... | Tom&#x27;s Hardware</a></li>
<li><a href="https://newsletter.semianalysis.com/p/intel-panther-lake-teardown">Intel Panther Lake Teardown, 18 A , BSPD, GAAFET, SemiAnalysis...</a></li>

</ul>
</details>

**Tags**: `#Intel 18A`, `#Panther Lake`, `#semiconductor manufacturing`, `#hardware teardown`, `#process technology`

---

<a id="item-tech-news-2"></a>
### [Conversations leaves Google Play and goes free](https://gultsch.de/posts/breaking-up-with-google-play/) ⭐️ 7.0/10

The developer of Conversations, the open-source XMPP messaging client for Android, published a post explaining the decision to break with Google Play and make the app free of charge. The supplied material does not include the post&\#x27;s text, so specifics such as the previous price, the replacement distribution channels, and any timeline are not established here. The accompanying analysis characterizes it as a notable open-source Android distribution decision, with discussion centering on Play Store support, fees, and platform control.

hackernews · ezst · Sep 26, 10:55 · [Discussion](https://news.ycombinator.com/item?id=49855315)

**「Background」** Google has been tightening who can publish on Android: contemporaneous coverage of the change says Play Console began requiring identity verification for all new developer accounts from September 2026, with a $25 fee and a 12-tester closed-testing requirement for new personal accounts, and that the policy also reaches sideloaded apps. That shift in Play Store access and developer requirements is the backdrop against which the Conversations maintainer&\#x27;s decision to leave Google Play and make the app free is being discussed.

**「Impact」** Android users who installed Conversations through Google Play will have to switch distribution channel to keep receiving updates; the app remains published on F-Droid, so the practical step is moving to that listing \(or a direct build\) rather than finding a replacement app. The Play listing currently shows the client as free, consistent with the move away from paid distribution.

**「Community discussion」** Commenters argued that the 15% Play Store cut bothers developers less than the quality of Google&\#x27;s support and review speed, with one attributing the behavior to the company&\#x27;s monopoly position. Developers described concrete obstacles: one said a year of attempts to list a product failed because Play&\#x27;s support-phone verification assumes a number that can receive a text or be answered instantly by a human, and another said Play now expects a business address and documents, making it a poor fit for hobbyist apps.

<details><summary>References</summary>
<ul>
<li><a href="https://testerbee.com/blog/google-play-developer-verification-2026">Google Play Developer Verification 2026: Deadline, Cost, and ...</a></li>
<li><a href="https://stora.sh/blog/2026-05-12-google-play-developer-verification-2026-complete-indie-guide">Google&#x27;s 2026 Developer Verification: The Complete Indie ...</a></li>
<li><a href="https://play.google.com/store/apps/details?id=eu.siacs.conversations">Conversations (Jabber / XMPP) - Apps on Google Play</a></li>
<li><a href="https://f-droid.org/en/packages/eu.siacs.conversations/">Conversations | F-Droid - Free and Open Source Android App Repository</a></li>

</ul>
</details>

**Tags**: `#Android`, `#Google Play`, `#open source`, `#app distribution`, `#XMPP`

---

## Financial News

<a id="item-finance-news-1"></a>
### [10-Year Treasury Yield Hits 5.23%, Highest Since 2007](https://www.cnbc.com/2026/09/26/10-year-treasury-yield-is-at-its-highest-in-19-years-how-we-got-here.html) ⭐️ 8.0/10

The 10-year U.S. Treasury yield jumped to 5.23% on Friday, its highest level since 2007, from just below 4.8% earlier in September, as investors priced a 64% market-implied chance of an October Fed rate hike, according to CME FedWatch, amid stubborn inflation and heavy government and AI-related bond issuance.

rss · CNBC Finance · Sep 26, 13:30

**「Background」** The 10-year yield is a benchmark for borrowing costs, including mortgages, and yields rise when bond prices fall; Macquarie strategist Thierry Wizman told CNBC that heavy federal borrowing and an AI infrastructure debt boom are adding supply that competes with Treasuries.

**「Impact」** Higher yields can raise costs for households and businesses tied to market rates, such as mortgages, and can weigh on stocks by making bonds more attractive to income-focused investors.

**Tags**: `#Treasury yields`, `#Federal Reserve`, `#inflation`, `#bond issuance`, `#AI infrastructure spending`

---

<a id="item-finance-news-2"></a>
### [Hong Kong SFC and PwC reach HK$1 billion Evergrande audit settlement](https://wallstreetcn.com/articles/3782573) ⭐️ 8.0/10

Hong Kong&\#x27;s Securities and Futures Commission has reached a HK$1 billion settlement with PwC Hong Kong over audit failures related to China Evergrande, under which PwC does not admit liability but agrees to pay the sum to compensate affected independent minority shareholders.

telegram · zaihuapd · Sep 26, 07:18

**「Background」** The SFC&\#x27;s case involved China Evergrande&\#x27;s audited accounts for 2019 and 2020, which the regulator found had overstated revenue, and the SCMP reports this is the first time auditors of a defunct firm have compensated minority shareholders over misleading financial statements.

**「Impact」** The payment comes from PwC Hong Kong rather than from Evergrande&\#x27;s estate, so creditors&\#x27; claim priority is unchanged, while Evergrande&\#x27;s liquidators have filed in court to have the settlement set aside, with the Hong Kong High Court expected to rule around late October.

<details><summary>References</summary>
<ul>
<li><a href="https://www.scmp.com/business/article/3351148/pwc-pay-hk1-billion-minority-shareholders-over-evergrande-audit-failures">PwC to pay US$128 million to Evergrande minority shareholders over audit failures</a></li>
<li><a href="https://www.hubbis.com/news/sfc-reaches-agreement-with-pricewaterhousecoopers-for-shareholder-compensation-of-hk-1-billion-regarding-false-financial-statements-of-china-evergrande-group-for-2019-and-2020">SFC Reaches Agreement with PricewaterhouseCoopers for Shareholder Compensation of ... - Hubbis</a></li>

</ul>
</details>

**Tags**: `#Hong Kong SFC`, `#PwC`, `#Evergrande`, `#audit settlement`, `#regulatory enforcement`

---

<a id="item-finance-news-3"></a>
### [Xi says U.S. and China can overcome the &\#x27;Thucydides Trap&\#x27; on first state visit in 11 years](https://www.cnbc.com/2026/09/26/xi-trump-thucydides-trap-us-china.html) ⭐️ 7.0/10

On his first U.S. state visit in 11 years, Xi Jinping said the U.S. and China can overcome the &quot;Thucydides Trap&quot; and framed their ties as &quot;healthy&quot; competition without confrontation, according to Beijing&\#x27;s official readout of his Thursday talks with President Donald Trump; no concrete agreements or policy outcomes were reported.

rss · CNBC Finance · Sep 26, 05:00

**「Background」** The Thucydides Trap, popularized by Harvard professor Graham Allison in the early 2010s, refers to the historical pattern in which tension between a rising power and a ruling power ended in war; Xi had posed it as an open question at a May summit and referred to it in a 2014 interview. Cui Shoujun, a professor at Renmin University of China, called a bottom line of intense competition without military conflict the summit&\#x27;s &quot;most significant political outcome,&quot; while Trump has not commented on Taiwan despite Xi urging the U.S. to &quot;oppose &\#x27;Taiwan independence,&\#x27;&quot; per Beijing&\#x27;s readout.

**Tags**: `#US-China relations`, `#geopolitics`, `#diplomacy`, `#trade policy`, `#Xi Jinping`

---

<a id="item-finance-news-4"></a>
### [Apple faces class action over Apple Pay fees charged to card issuers](https://9to5mac.com/2026/09/25/apple-faces-class-action-over-apple-pay-fees-charged-to-card-issuers/) ⭐️ 7.0/10

A US federal judge certified an antitrust class action accusing Apple of charging card issuers too much for Apple Pay transactions and blocking rival mobile wallets. The plaintiffs allege Apple charges 0.15% on credit card transactions and 0.5 cents on debit card transactions — up to $1 billion a year — while Android phone wallets charge issuers nothing, and they are seeking refunds plus an injunction; these are allegations, not a finding of liability.

telegram · zaihuapd · Sep 26, 03:32

**「Background」** The suit is an antitrust class action in U.S. federal court; U.S. District Judge Jeffrey White certified the class this week, allowing it to proceed on behalf of any U.S. entity that issued a payment card enabled for Apple Pay and paid Apple a fee on those transactions \[tool-1-3\]. A class action is a single lawsuit brought on behalf of a whole group of similarly affected parties, and certification is a procedural step, not a ruling that Apple broke the law \[tool-1-2\].

**「Impact」** The ruling lets thousands of U.S. banks and credit unions that issue Apple Pay-enabled cards pursue the alleged fees together in one case, rather than suing individually, and they could seek refunds if the suit later succeeds — the judge did not decide whether Apple broke the law or owes anything.

<details><summary>References</summary>
<ul>
<li><a href="https://www.mactech.com/2026/09/25/credit-unions-win-class-certification-in-apple-pay-antitrust-lawsuit/">Credit Unions win class certification in Apple Pay antitrust lawsuit</a></li>
<li><a href="https://www.macrumors.com/2026/09/25/apple-pay-antitrust-lawsuit-advances/">Banks and Credit Unions to Team Up Against Apple Pay Fees</a></li>
<li><a href="https://appleinsider.com/articles/26/09/25/thousands-of-banks-can-now-sue-over-apple-pay-fees-in-one-antitrust-case">Thousands of banks can now sue over Apple Pay fees in one antitrust case</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#Apple Pay`, `#antitrust`, `#class action`, `#mobile payments`

---

<a id="item-finance-news-5"></a>
### [Volkswagen recalls 2.86 million vehicles worldwide over steering defect](https://www.ithome.com/1/007/382.htm) ⭐️ 7.0/10

Volkswagen confirmed a global recall of about 2.86 million vehicles — roughly 2.16 million VW-brand cars and nearly 700,000 Audi Q3s, including some 960,000 vehicles in Germany — because a corroded steering-system fixing bolt could, in extreme cases, cause steering failure. The company described the recall as a precautionary measure and said no injuries linked to the issue have been reported.

telegram · zaihuapd · Sep 26, 10:01

**「Background」** The defect involves the bolt that attaches the right steering rack to the vehicle’s subframe, which can corrode prematurely when moisture enters the area, according to external reports.

**「Who is affected」** Owners of the roughly 2.86 million Volkswagen and Audi Q3 vehicles built between 2013 and 2024 — about 960,000 of them in Germany — face inspection and possible repair, because the corrosion-prone steering bolt could cause a loss of steering.

<details><summary>References</summary>
<ul>
<li><a href="https://qz.com/volkswagen-audi-recall-steering-screw-corrosion-092526">Volkswagen, Audi recall 2.86 million vehicles over steering screw - Quartz</a></li>
<li><a href="https://www.nbcwashington.com/news/consumer/recall-alert/volkswagen-audi-vehicles-recalled-over-potential-steering-problem/4159277/">Volkswagen, Audi recall over 208000 vehicles. See affected models - NBC4 Washington</a></li>
<li><a href="https://www.wrdw.com/2026/09/25/volkswagen-recall-286-million-vw-audi-models/">VW, Audi Recall 2.86 Million Cars Over Steering Risk - WRDW</a></li>
<li><a href="https://www.lemonde.fr/en/economy/article/2026/09/25/volkswagen-recalls-nearly-2-9-million-cars-worldwide-over-risk-of-steering-failure_6757944_19.html">Volkswagen recalls nearly 2.9 million cars worldwide over ...</a></li>

</ul>
</details>

**Tags**: `#Volkswagen`, `#automotive recall`, `#steering defect`, `#Audi Q3`, `#global recall`

---