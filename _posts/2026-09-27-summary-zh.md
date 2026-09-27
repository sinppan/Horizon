---
layout: default
title: "Horizon Summary: 2026-09-27 (ZH)"
date: 2026-09-27
lang: zh
---

> 从 30 条内容中筛选出 7 条重要资讯。

---

**科技新闻**
1. [SemiAnalysis 发布 Intel 18A 与 Panther Lake 拆解](#item-tech-news-1) ⭐️ 8.0/10
2. [Conversations 离开 Google Play 并转为免费](#item-tech-news-2) ⭐️ 7.0/10

**财经新闻**
1. [10 年期美债收益率升至 5.23%，创 2007 年以来新高](#item-finance-news-1) ⭐️ 8.0/10
2. [香港证监会与普华永道就恒大审计达成 10 亿港元和解](#item-finance-news-2) ⭐️ 8.0/10
3. [习近平称美中可克服“修昔底德陷阱”，主张不走向军事冲突的竞争](#item-finance-news-3) ⭐️ 7.0/10
4. [苹果因 Apple Pay 向发卡机构收费面临反垄断集体诉讼获法院认证](#item-finance-news-4) ⭐️ 7.0/10
5. [大众因转向隐患全球召回约 286 万辆汽车](#item-finance-news-5) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [SemiAnalysis 发布 Intel 18A 与 Panther Lake 拆解](https://newsletter.semianalysis.com/p/intel-panther-lake-teardown) ⭐️ 8.0/10

SemiAnalysis 于 2026 年 9 月 26 日发布了一篇免费的 STEEL 拆解报告，声称将深入剖析 Intel 18A 制程与英特尔的 Panther Lake 处理器，作者为 Adith Shankar。该文面向半导体制造与硬件工程读者，属于对具体芯片和工艺节点的实物级技术分析。不过目前可见的内容只是简短预告，没有给出任何拆解发现、尺寸数据、良率或性能结果，因此其中的具体结论、技术新颖性及其影响均无法从现有材料核实。

rss · Semianalysis · 9月26日 13:36

**「背景」** Panther Lake 是英特尔的客户端处理器平台，按英特尔官方说法即酷睿 Ultra 系列 3，也是其首个基于 Intel 18A 制程打造的 AI PC 平台。该平台采用异构设计：CPU 核心晶片由英特尔自家 18A 制程制造，集成显卡晶片基于由 Xe2（Battlemage）演进而来的 Arc Xe3 架构，I/O 晶片则交由台积电 N6 制程生产。18A 节点引入 RibbonFET 全环绕栅极晶体管与 PowerVia 背面供电两项关键技术，这正是此次拆解所关注的对象。

**「对采用 18A 的团队意味着什么」** 对评估 Intel 18A 的芯片设计与系统团队来说，这份拆解的直接价值在于把 18A 的 BSPD（背面供电）、GAAFET 实现，以及 Panther Lake 将计算、GPU、I/O 三个 Tile 叠加在被动基板上的 Foveros-S 封装作为可核查的对象。据 Tom&\#x27;s Hardware 报道，Panther Lake（Core Ultra 300）预计接替 Arrow Lake-U/H，且两个计算 Tile 变体都使用 18A，因此面向该细分市场的选型与设计验证需针对新节点和新封装重新开展。需要说明，源条目本身只是拆解预告，具体实测结论并未在给定材料中给出。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Panther_Lake_%28microprocessor%29">Panther Lake (microprocessor) - Wikipedia</a></li>
<li><a href="https://newsroom.intel.com/client-computing/intel-unveils-panther-lake-architecture-first-ai-pc-platform-built-on-18a">Intel Unveils Panther Lake Architecture: First AI PC Platform Built on 18A</a></li>
<li><a href="https://acemagic.com/blogs/about-ace-mini-pc/intel-panther-lake">Intel Panther Lake Core Ultra 300: Specs, Release Date &amp; 18A Node – ACEMAGIC</a></li>
<li><a href="https://www.tomshardware.com/pc-components/cpus/intel-panther-lake-samples-with-flagship-18a-node-have-been-powered-on-at-eight-customers-co-ceos-dispel-rumors-regarding-poor-silicon-health">Intel Panther Lake samples with flagship 18 A node... | Tom&#x27;s Hardware</a></li>
<li><a href="https://newsletter.semianalysis.com/p/intel-panther-lake-teardown">Intel Panther Lake Teardown, 18 A , BSPD, GAAFET, SemiAnalysis...</a></li>

</ul>
</details>

**标签**: `#Intel 18A`, `#Panther Lake`, `#semiconductor manufacturing`, `#hardware teardown`, `#process technology`

---

<a id="item-tech-news-2"></a>
### [Conversations 离开 Google Play 并转为免费](https://gultsch.de/posts/breaking-up-with-google-play/) ⭐️ 7.0/10

Conversations 的开发者表示将离开 Google Play，并把这款 XMPP 客户端改为免费。对 Android 用户来说，该应用将不再通过 Google Play 分发和更新，需改用其他渠道获取。现有材料没有给出具体版本号、生效日期或完整替代分发方案，因此这仍是开发者宣布的迁移，而非已独立核实的完成状态。相关讨论围绕 Google Play 的支持质量、抽成和平台垄断权力展开。

hackernews · ezst · 9月26日 10:55 · [社区讨论](https://news.ycombinator.com/item?id=49855315)

**「背景：Google Play 的准入收紧」** Conversations 是一款开源的 Android XMPP 客户端，此前一直通过 Google Play 分发，作者此次宣布退出该商店并将应用改为免费。这一决定发生在 Google 收紧 Android 应用分发准入的背景下：多篇 2026 年的报道称，Play Console 自 2026 年 9 月起要求所有新开发者账号完成身份验证，需提交证件并支付 25 美元费用，同时还伴随“12 名测试者”的封闭测试规则（tool-2-1、tool-2-2）。同一批报道指出，这套验证要求不只针对商店上架，也覆盖侧载应用（tool-2-3）。

**「对用户与开发者的直接影响」** 对现有用户而言，最直接的变化是更新渠道：应用在 F-Droid 上仍可获取，并内置图片、群聊和位置支持，因此改用该来源或开发者直接分发的安装包是继续获得版本更新的路径；Google Play 上仍能查到该应用条目（免费、评分 4.0、2,571 条评价），但开发者已不再以此为主渠道。对其他小团队来说，评论区反映的门槛同样具体：有开发者称因 Google Play 要求客服电话可被短信或人工即时验证、并需提供企业地址等材料，尝试一年仍未成功上架。

**「社区讨论」** 部分 Hacker News 评论者认为，问题不只是 15% 抽成，而是 Google Play 的支持和审核反馈质量：pi-victor 称若反馈及时，开发者不会抱怨付费，4chandaily 则批评大公司客服整体恶化。另有开发者报告因 Google Play 要求支持电话可被短信或人工即时验证，导致其产品一年无法上架，并认为 Google 正逐步限制侧载。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://testerbee.com/blog/google-play-developer-verification-2026">Google Play Developer Verification 2026: Deadline, Cost, and ...</a></li>
<li><a href="https://stora.sh/blog/2026-05-12-google-play-developer-verification-2026-complete-indie-guide">Google&#x27;s 2026 Developer Verification: The Complete Indie ...</a></li>
<li><a href="https://dev.to/dev-arafat-alim/android-is-losing-its-freedom-googles-2026-developer-verification-explained-2b5p">Android Is Losing Its Freedom: Google&#x27;s 2026 Developer ...</a></li>

</ul>
</details>

**标签**: `#Android`, `#Google Play`, `#open source`, `#app distribution`, `#XMPP`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [10 年期美债收益率升至 5.23%，创 2007 年以来新高](https://www.cnbc.com/2026/09/26/10-year-treasury-yield-is-at-its-highest-in-19-years-how-we-got-here.html) ⭐️ 8.0/10

10 年期美国国债收益率周五升至 5.23%，为 2007 年以来最高，本月早些时候还略低于 4.8%。CME FedWatch 工具显示市场预计美联储 10 月加息概率为 64%；密歇根大学调查显示未来一年通胀预期 9 月升至 4.6%，高于 8 月的 4%。

rss · CNBC Finance · 9月26日 13:30

**「背景」** 麦格理策略师 Thierry Wizman 认为，今年推高收益率的主因不是通胀，而是债券供给：联邦政府为赤字融资发债，企业则为 AI 基础设施大举借债。

**「影响」** 收益率上升会通过抬高房贷和企业借贷成本影响家庭与企业，也可能因债券吸引力上升而拖累股票估值。

**标签**: `#Treasury yields`, `#Federal Reserve`, `#inflation`, `#bond issuance`, `#AI infrastructure spending`

---

<a id="item-finance-news-2"></a>
### [香港证监会与普华永道就恒大审计达成 10 亿港元和解](https://wallstreetcn.com/articles/3782573) ⭐️ 8.0/10

香港证监会与普华永道香港就恒大审计失职达成和解，普华永道不承认责任，但同意支付 10 亿港元补偿受影响的独立小股东。

telegram · zaihuapd · 9月26日 07:18

**「背景」** 香港证监会此前认定，中国恒大 2019 财年和 2020 财年经审计的年收入分别虚增人民币 2139 亿元（44.79%）和 3502 亿元，本次和解针对的正是这一审计失职（tool-1-3）。据南华早报报道，这是首次有已倒闭公司的审计机构就误导性财务报表向小股东作出赔偿（tool-1-1）。

**「影响」** 若和解最终生效，受影响独立小股东可获补偿，且款项来自普华永道香港而非恒大财产，因此不改变债权人申索的优先次序；但恒大清盘人已入禀法院要求撤销，香港高院预计 10 月底左右判决，结果仍不确定。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.scmp.com/business/article/3351148/pwc-pay-hk1-billion-minority-shareholders-over-evergrande-audit-failures">PwC to pay US$128 million to Evergrande minority shareholders over audit failures</a></li>
<li><a href="https://www.hubbis.com/news/sfc-reaches-agreement-with-pricewaterhousecoopers-for-shareholder-compensation-of-hk-1-billion-regarding-false-financial-statements-of-china-evergrande-group-for-2019-and-2020">SFC Reaches Agreement with PricewaterhouseCoopers for Shareholder Compensation of ... - Hubbis</a></li>

</ul>
</details>

**标签**: `#Hong Kong SFC`, `#PwC`, `#Evergrande`, `#audit settlement`, `#regulatory enforcement`

---

<a id="item-finance-news-3"></a>
### [习近平称美中可克服“修昔底德陷阱”，主张不走向军事冲突的竞争](https://www.cnbc.com/2026/09/26/xi-trump-thucydides-trap-us-china.html) ⭐️ 7.0/10

中国国家主席习近平在 11 年来首次对美国进行国事访问期间对美国总统特朗普表示，“修昔底德陷阱”可以克服，并主张两国进行不走向军事冲突的健康竞争。上述表述来自中方官方通稿，报道未提及具体政策成果。

rss · CNBC Finance · 9月26日 05:00

**「背景」** “修昔底德陷阱”由哈佛大学教授格雷厄姆·艾利森推广，指历史上崛起大国与守成大国之间的紧张关系常常以战争告终。习近平今年 5 月峰会时曾以疑问方式提出两国能否避免这一陷阱。

**标签**: `#US-China relations`, `#geopolitics`, `#diplomacy`, `#trade policy`, `#Xi Jinping`

---

<a id="item-finance-news-4"></a>
### [苹果因 Apple Pay 向发卡机构收费面临反垄断集体诉讼获法院认证](https://9to5mac.com/2026/09/25/apple-faces-class-action-over-apple-pay-fees-charged-to-card-issuers/) ⭐️ 7.0/10

美国联邦法官认证了一起针对苹果的反垄断集体诉讼，原告指控苹果就 Apple Pay 交易向支付卡发卡机构收取过高费用，并阻止竞争对手开发竞争性手机钱包。原告称苹果对信用卡交易收取 0.15%、对借记卡交易每笔收取 0.5 美分，而安卓手机钱包不向发卡机构收费，苹果每年因此最高收取 10 亿美元；集体成员为所有在美国发行支持 Apple Pay 卡片并支付相关费用的发卡机构，原告要求退还费用并寻求禁令。这些均为原告的指控，法院尚未就责任作出最终裁决。

telegram · zaihuapd · 9月26日 03:32

**「背景」** 美国联邦法官 Jeffrey White 本周认证了这起集体诉讼的原告集体，成员包括所有在美国发行支持 Apple Pay 的支付卡并就该卡上交易向苹果付费的发卡机构；集体认证使案件可代表该群体推进，但不代表法院已认定苹果违法。原告指控苹果按信用卡交易 0.15%、借记卡交易 0.5 美分收费，而安卓手机钱包不向发卡机构收费。

**「影响」** 这次认证让美国数千家发行 Apple Pay 卡片的银行和信用合作社可以合并成一案共同索赔，而不必各自单独起诉；但裁决并未认定苹果违反反垄断法或需要向发卡机构退款。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.mactech.com/2026/09/25/credit-unions-win-class-certification-in-apple-pay-antitrust-lawsuit/">Credit Unions win class certification in Apple Pay antitrust lawsuit</a></li>
<li><a href="https://www.macrumors.com/2026/09/25/apple-pay-antitrust-lawsuit-advances/">Banks and Credit Unions to Team Up Against Apple Pay Fees</a></li>
<li><a href="https://www.macrumors.com/2026/09/25/apple-pay-antitrust-lawsuit-advances/">Banks and Credit Unions to Team Up Against Apple Pay Fees - MacRumors</a></li>
<li><a href="https://appleinsider.com/articles/26/09/25/thousands-of-banks-can-now-sue-over-apple-pay-fees-in-one-antitrust-case">Thousands of banks can now sue over Apple Pay fees in one antitrust case</a></li>

</ul>
</details>

**标签**: `#Apple`, `#Apple Pay`, `#antitrust`, `#class action`, `#mobile payments`

---

<a id="item-finance-news-5"></a>
### [大众因转向隐患全球召回约 286 万辆汽车](https://www.ithome.com/1/007/382.htm) ⭐️ 7.0/10

大众汽车集团证实，因转向系统固定螺栓可能因腐蚀断裂、极端情况下导致转向失灵，将在全球召回约 286 万辆汽车，其中德国约 96 万辆。此次召回涉及约 216 万辆大众品牌汽车和近 70 万辆奥迪 Q3，大众称这是预防性措施，目前暂无相关伤人事故报告。

telegram · zaihuapd · 9月26日 10:01

**「背景」** 此次召回的核心机制是水汽进入右侧转向机与副车架连接螺栓附近，可能使该固定螺栓提前腐蚀甚至断裂，大众因此以预防性措施的名义发起召回。

**「影响」** 此次召回涉及 2013 至 2024 年生产的大众品牌汽车和奥迪 Q3，相关车主需确认自己的车辆是否在召回范围内并安排检修，以排除极端情况下转向失灵的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://qz.com/volkswagen-audi-recall-steering-screw-corrosion-092526">Volkswagen, Audi recall 2.86 million vehicles over steering screw - Quartz</a></li>
<li><a href="https://www.nbcwashington.com/news/consumer/recall-alert/volkswagen-audi-vehicles-recalled-over-potential-steering-problem/4159277/">Volkswagen, Audi recall over 208000 vehicles. See affected models - NBC4 Washington</a></li>
<li><a href="https://www.wrdw.com/2026/09/25/volkswagen-recall-286-million-vw-audi-models/">VW, Audi Recall 2.86 Million Cars Over Steering Risk - WRDW</a></li>
<li><a href="https://www.lemonde.fr/en/economy/article/2026/09/25/volkswagen-recalls-nearly-2-9-million-cars-worldwide-over-risk-of-steering-failure_6757944_19.html">Volkswagen recalls nearly 2.9 million cars worldwide over ...</a></li>

</ul>
</details>

**标签**: `#Volkswagen`, `#automotive recall`, `#steering defect`, `#Audi Q3`, `#global recall`

---