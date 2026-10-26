# E-commerce GEO Readiness

Last updated Oct 26, 2026

A research-based look at how prepared 12 e-commerce sites and 11 marketplaces, including Faire, are for AI search, built from published reports rather than a live audit of each site.

> **Read this first:** the evidence is secondhand. Findings come from search-result summaries of news coverage, not from checking each site directly. Treat this as a hypothesis to confirm, not a final ranking.

**Bottom line:** Target, Walmart, Best Buy, The Home Depot and Sephora show the strongest published evidence of GEO readiness. Each feeds its catalog to ChatGPT and runs its own shopping experience inside it. Amazon is the outlier. It deliberately blocks dozens of AI crawlers, yet it's still one of the most-cited retailers in AI answers. That suggests brand strength can outweigh crawler access for now.

## Scorecard

Sites are grouped into readiness levels rather than given exact ranks, because the evidence isn't precise enough to separate sites within a group. "Not found" means no published source turned up, not that the answer is no.

| Readiness | Site | Tier | AI crawlers allowed | Feeds catalog to AI engines | Shopping inside AI apps | Seen in AI answers |
| --- | --- | --- | --- | --- | --- | --- |
| High | Target | Marketplace | Not found | Yes: OpenAI's Agentic Commerce Protocol (ACP) | Yes: Target app in ChatGPT (Nov 2025) | Yes: among most-cited for product queries |
| High | Walmart | Marketplace | Not found | Yes: ChatGPT Instant Checkout partner (Oct 2025) | Yes: Sparky assistant in ChatGPT (2026) | Yes: among most-cited for product queries |
| High | Best Buy | Marketplace | Not found | Yes: ACP, plus Google's Universal Commerce Protocol | Yes: shopping through ChatGPT (Sept 2026) | Not found |
| High | The Home Depot | Specialty | Not found | Yes: ACP | Yes: Home Depot app in ChatGPT | Not found |
| High | Sephora | Specialty | Not found | Yes: ACP | Yes: Sephora app in ChatGPT, linked to loyalty program | Not found |
| Medium | Etsy | Marketplace | Not found | Yes: first ChatGPT Instant Checkout partner (Sept 2025) | Partial: checkout path changed in 2026 | Yes: 33% ChatGPT visibility in one benchmark |
| Medium | Wayfair | Specialty | Not found | Yes: ACP | Not found | Not found |
| Low or unclear | Nike | DTC | Not found | Partial: Google Gemini and AI Mode integration (weak source) | Partial: Running Shoe Finder in ChatGPT (weak source) | Not found |
| Low or unclear | Glossier | DTC | Likely yes: Shopify's default rules don't block AI search bots | Partial: named as "coming soon" for Instant Checkout via Shopify | Not found | Not found |
| Low or unclear | Allbirds | DTC | Likely yes, if on Shopify defaults (platform not confirmed) | Partial: Shopify Agentic Storefronts turn on for eligible stores | Not found | Not found |
| Low | Warby Parker | DTC | Not found | Not found | Not found (its Google deal is about smart glasses, not shopping) | Not found |
| Opted out | Amazon | Marketplace | No: blocks GPTBot, ChatGPT-User, OAI-SearchBot, ClaudeBot, PerplexityBot, Google-Extended and more | No | No | Yes: 50% ChatGPT visibility in one benchmark |

No source covered the robots.txt rules of any site except Amazon and Shopify stores. That column is the biggest gap, and a live audit would fill it in minutes.

## What the evidence says by tier

**Marketplaces: split between all-in and opted out.** Walmart, Target and Best Buy have each connected their catalogs to ChatGPT and launched shopping experiences there. Best Buy goes furthest, backing Google's Universal Commerce Protocol too and saying it wants its site discoverable by AI agents. Amazon went the other way. It has steadily added AI bots to its robots.txt, reportedly reaching 47 by late 2025. Even so, a ChatGPT visibility benchmark puts Amazon at 50%, which shows that blocking crawlers doesn't remove a brand that's already well known.

**Specialty retailers: Home Depot and Sephora lead.** Both have their own apps inside ChatGPT. Sephora ties its app to its Beauty Insider loyalty program, and Home Depot says it works with OpenAI, Anthropic, Google and Microsoft. Wayfair is connected to OpenAI's discovery protocol but has focused its public AI work on its own app and site.

**DTC brands: least evidence.** None of the four has a confirmed AI shopping integration of its own. Glossier and Allbirds may benefit from Shopify's platform-level work (Agentic Storefronts and Shopify Catalog), which turns on for eligible stores automatically. That makes them prepared by default rather than by choice. Nike's ChatGPT and Gemini work comes from a single LinkedIn post, so it needs confirming. Warby Parker's Google partnership is about smart glasses, not AI search.

**The pattern:** big retailers are building direct pipes into AI platforms (feeds, protocols, in-chat apps). Smaller DTC brands mostly rely on their e-commerce platform to do it for them.

## Faire and other marketplaces

Marketplaces split into three approaches: selective gatekeepers (eBay, and Amazon above), marketplaces building their own AI agents (Alibaba.com, Mercari), and those with no visible AI strategy. Visibility in ChatGPT doesn't follow preparation: eBay and OfferUp are the most-recommended marketplace apps in ChatGPT without announcing any AI integration.

| Readiness | Marketplace | Type | AI crawlers allowed | Feeds catalog to AI engines | Shopping inside AI apps | Seen in AI answers |
| --- | --- | --- | --- | --- | --- | --- |
| Medium (weak evidence) | Faire | Wholesale (B2B) | Not found | Not found | Partial: a Faire-built experience ran inside ChatGPT (one newsletter source) | Not found |
| Selective | eBay | Consumer, new and used | Partial: blocks Perplexity, Anthropic and Amazon bots, allows Google's | Not found | No: terms ban unapproved buy-for-me agents since Feb 20, 2026 | Yes: top marketplace app in ChatGPT (score 88, Apr 2026) |
| Unclear | OfferUp | Local resale | Not found | Not found | Not found | Yes: 2nd marketplace app in ChatGPT (score 85) |
| Own agent | Alibaba.com | Wholesale (B2B) | Not found | Not found | Own agent instead: Accio AI sourcing app (vendor's claims) | Not found |
| Own agent | Mercari | Resale | Not found | Not found | Own agent instead: Merchat AI on its site (2023, current status unknown) | Yes: 3rd marketplace app in ChatGPT (score 54) |
| Low | Poshmark | Fashion resale | Not found | Not found | Not found | Partial: 5th marketplace app in ChatGPT (score 33) |
| Low | Depop | Fashion resale | Not found | Not found | Not found | Not in ChatGPT's top 10 marketplace apps |
| Low | StockX | Sneaker and collectibles resale | Not found | Not found | Not found | Not in ChatGPT's top 10 marketplace apps |
| Low | Ankorstore | Wholesale (B2B, Europe) | Not found | Not found | Not found | Not found |
| Unclear | Temu | Low-cost consumer | Not found | Not found | Not found | Not found |
| Unclear | Shein | Low-cost fashion | Not found | Not found | Not found | Not found |

**What stands out:**

- **Faire is the most interesting gap.** Its buyers are shop owners asking AI tools things like "where can I buy wholesale candles for my boutique." Faire has built natural-language and image search for retailers on its own site, but there's only one weak report of it reaching into ChatGPT. Wholesale prompts are a less crowded space, so a test here could show clear results quickly.
- **eBay wants control, not exclusion.** It blocks some AI bots and bans unapproved shopping agents, but it lets Google's bots in and has hinted at approved partners. It's still the most-recommended marketplace app in ChatGPT.
- **Wholesale marketplaces are building their own agents.** Alibaba's Accio sources suppliers inside Alibaba's own app instead of through ChatGPT. That keeps buyers on its platform but misses people who start their search in general AI tools.
- **Temu and Shein had no findings at all,** which is surprising given their size. A live audit of their robots.txt is the fastest way to fill this in.

The ChatGPT visibility scores come from AppTweak and measure how often each marketplace's *app* is recommended in ChatGPT (US only), not how often its website is cited. They're useful for comparing marketplaces but aren't the same measure as the Otterly benchmark used above.

## How this was scored, and what it can't prove

Each site was checked against four signals: whether AI crawlers are allowed in, whether the catalog is fed to AI engines, whether shoppers can browse or buy inside an AI app, and whether the brand shows up in AI answers. A site rated "High" has confirmed evidence on at least two of the first three.

Limits to keep in mind:

- **Secondhand evidence.** The research session couldn't open the sites or source pages directly (its network policy blocked them), so findings come from search results summarizing news coverage. Some details, like exact launch dates, conflict between sources.
- **Partnerships aren't the whole picture.** Big retailers announce partnerships. Smaller brands may be well prepared (clean product schema, server-rendered pages) without anything to announce. This method favors big retailers.
- **Readiness isn't results.** Being prepared doesn't prove a site is cited more. Amazon shows the opposite can happen. Only Profound tracking, or a sample of real AI answers, can test that.
- **None of the four Profound value tests were run.** Those tests need a site you control and 8 to 12 weeks. This is closer to the baseline you'd collect before them.

## Next steps to turn this into proof

- [ ] **Run a live audit (same day).** With network access, check each site's robots.txt, product schema, rendering without JavaScript, sitemaps and llms.txt. This fills the empty crawler column and catches DTC brands that are well prepared but unannounced.
- [ ] **Track outcomes in Profound (4 to 8 weeks).** Load 30 to 50 shopping prompts per category (for example, "best running shoes under $150") and record which sites get mentioned and cited, by engine.
- [ ] **Compare readiness with results.** If the "High" group is cited more than the "Low" group on the same prompts, that's evidence readiness pays off. If Amazon still leads while blocking crawlers, that's evidence brand strength matters more, which is a finding worth publishing on its own.
- [ ] **Run an accuracy check (Test 5 method).** Score how accurately each engine describes prices and policies for 3 or 4 of the sites. Retailers that feed catalogs directly should have fewer outdated answers.

## Sources

These pages are summarized from search results. They weren't opened directly, so verify key claims before sharing.

- **Amazon:** [Modern Retail, Amazon blocks more ChatGPT crawlers](https://www.modernretail.co/technology/amazon-quietly-blocks-more-of-openais-chatgpt-web-crawlers-from-accessing-its-site/) · [Modern Retail, Amazon blocks bots from Meta, Google and others](https://www.modernretail.co/technology/amazon-expands-its-fight-to-keep-ai-bots-off-its-e-commerce-site/) · [Hexagon, Amazon blocking 47 AI bots](https://joinhexagon.com/blogs/why-amazon-is-blocking-47-ai-bots-and-what-it-means-for-the-future-of-product-discovery-mmi9c1s2-fdex)
- **Walmart:** [Walmart corporate, OpenAI partnership (Oct 14, 2025)](https://corporate.walmart.com/news/2025/10/14/walmart-partners-with-openai-to-create-ai-first-shopping-experiences) · [Retail Dive, Sparky in ChatGPT](https://www.retaildive.com/news/walmart-sparky-chatgpt-instant-checkout/815647/)
- **Target:** [Digital Commerce 360, Target app in ChatGPT (Nov 19, 2025)](https://www.digitalcommerce360.com/2025/11/19/target-to-launch-app-in-openai-chatgpt/)
- **Best Buy:** [Digital Commerce 360, Best Buy shopping through ChatGPT (Sept 16, 2026)](https://www.digitalcommerce360.com/2026/09/16/best-buy-opens-up-gift-buying-and-discover-through-chatgpt-ahead-of-holidays/amp/) · [AIM Media House, Best Buy AI initiatives](https://aimmediahouse.com/retail/best-buy-beat-expectations-and-disclosed-three-ai-initiatives-in-the-same-quarter)
- **The Home Depot:** [Home Depot corporate, AI and ChatGPT app](https://corporate.homedepot.com/news/company/ai-home-depot-look-future-home-improvement) · [Fortune, Home Depot AI (June 24, 2026)](https://fortune.com/2026/06/24/home-depot-ai-home-improvement-retail/) · [Retail Brew, Home Depot app relaunch](https://www.retailbrew.com/stories/2026/04/16/home-depot-to-relaunch-mobile-app-later-this-year)
- **Sephora:** [FashionNetwork, Sephora app in ChatGPT](https://us.fashionnetwork.com/news/Sephora-launches-an-app-within-chatgpt-as-the-platform-announces-upgrades-to-its-shopping-experience,1818569.html)
- **ACP partner list (Target, Sephora, Best Buy, Home Depot, Wayfair):** [OpenAI, Powering product discovery in ChatGPT](https://openai.com/index/powering-product-discovery-in-chatgpt/) · [Digital Commerce 360, OpenAI agentic commerce updates (Mar 24, 2026)](https://www.digitalcommerce360.com/2026/03/24/openai-agentic-commerce-updates-chatgpt-walmart/)
- **Etsy and Glossier:** [TechCrunch, OpenAI Instant Checkout (Sept 29, 2025)](https://techcrunch.com/2025/09/29/openai-takes-on-google-amazon-with-new-agentic-shopping-system/)
- **Wayfair:** [Retail Dive, Wayfair AI customer experience push](https://www.retaildive.com/news/wayfair-ai-customer-experience-push/804055)
- **Shopify (Glossier, Allbirds):** [Modern Retail, Shopify sets boundaries for buy-for-me bots (July 2025)](https://www.modernretail.co/technology/shopify-has-quietly-set-boundaries-for-buy-for-me-ai-bots-on-merchant-sites/) · [Shopify, Agentic Storefronts](https://www.shopify.com/agentic)
- **Nike:** [LinkedIn post by a Nike strategist](https://sg.linkedin.com/in/jia-yi-ng) (single source)
- **Warby Parker:** [Constellation Research, Warby Parker's third act revolves around AI](https://www.constellationr.com/insights/news/warby-parkers-third-act-revolves-around-ai)
- **AI visibility and citations:** [Otterly.AI e-commerce benchmark](https://benchmark.otterly.ai/dir/178/e-commerce+retail) · [Search Engine Land, how e-commerce brands get discovered in AI search](https://searchengineland.com/guide/ecommerce-ai)

Marketplace sources:

- **Faire:** [Read the Aisle, The AI triumphs and pitfalls at Faire](https://www.readtheaisle.com/p/the-ai-triumphs-and-pitfalls-at-a-5-billion-online-marketplace) · [ZenML, AI-powered product discovery at a wholesale marketplace](https://www.zenml.io/llmops-database/ai-powered-developer-productivity-and-product-discovery-at-wholesale-marketplace)
- **eBay:** [TechSpot, eBay bans AI agents from shopping](https://www.techspot.com/news/111046-ebay-banning-agentic-ai-shopping-though-could-activate.html) · [Stellagent, eBay bans AI shopping bots (Jan 23, 2026)](https://stellagent.ai/insights/ebay-ai-shopping-bot-ban-2026-01-23)
- **eBay, OfferUp, Mercari, Poshmark, Depop, StockX visibility:** [AppTweak, Most visible marketplace apps in ChatGPT (Apr 28, 2026)](https://www.apptweak.com/en/reports/most-visible-marketplace-apps-in-chatgpt?format=md)
- **Mercari:** [Retail Dive, Mercari launches Merchat AI](https://www.retaildive.com/news/mercari-chatgpt-chatbot-merchat-artificial-intelligence-search-recommendations/648032/)
- **Alibaba.com:** [Apple App Store, Accio](https://apps.apple.com/np/app/accio-alibaba-com-ai-agent/id6739872836) (vendor listing)
- **Ankorstore:** [TechCrunch, Ankorstore valuation (2022)](https://techcrunch.com/2022/01/09/ankorstore-reaches-2-billion-valuation-two-years-after-launching-its-wholesale-marketplace)
- **Temu and Shein:** no relevant sources found
