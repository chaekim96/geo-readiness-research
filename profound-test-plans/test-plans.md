# Profound Value Test Plans

Four tests, run over about 12 weeks, to show whether Profound changes decisions and results. Tests 1 and 2 prove AEO work moves AI citations. Tests 5 and 8 show value outside marketing.

## Shared setup (weeks 1 to 3)

All four tests share one baseline and one tracking sheet, so set these up once before changing anything.

1. **Lock the prompt set.** Write 100 to 150 prompts that buyers actually ask, grouped by topic. Tag each prompt with the test it belongs to. Don't edit the set after the baseline starts.
2. **Pick engines.** Track the same engines in every test. At minimum ChatGPT, Perplexity and Google AI Overviews. Add Gemini and Claude if your plan includes them.
3. **Run a 3-week baseline.** Record daily visibility, citation share and position per prompt. This shows how much the numbers move on their own.
4. **Turn on Agent Analytics.** Confirm AI bot visits are logging for your site before Test 2 starts.
5. **Set up one tracking sheet.** Pull weekly exports (or API calls) into one place, with one tab per test.

Rules for all tests:

- Write down the hypothesis and success criteria before you see any results.
- Compare weekly averages, not single days. AI answers change daily even when nothing else does.
- Log every outside event (site redesign, press hit, competitor launch) with a date, so it isn't mistaken for a test effect.

## Test 1: Holdout page test

Optimized pages should earn more AI citations than matched pages left alone. This is the main proof that AEO work, guided by Profound, causes a lift.

**Hypothesis:** Pages optimized for AI answers gain at least 10 percentage points more citation rate than unchanged control pages over 8 weeks.

**Design**

1. Pick 20 pages of the same type (for example, product or comparison pages) with similar traffic and baseline citation rates.
2. Map 3 to 5 prompts from the locked set to each page.
3. Pair pages by baseline citation rate, then randomly assign one of each pair to test and one to control. Random assignment stops you from picking pages that were going to win anyway.
4. Optimize only the 10 test pages: a direct answer in the first 2 sentences, an FAQ block, schema markup, current stats with sources, and a visible updated date.
5. Ship all changes in the same week. Don't touch the control pages at all.

**Metrics**

| Metric | Source | Role |
| --- | --- | --- |
| Citation rate (share of mapped prompts citing the page) | Profound prompt tracking | Primary |
| Brand visibility on mapped prompts | Profound | Secondary |
| AI-referred sessions and conversions to the page | Profound Agent Analytics + web analytics | Secondary |
| Bot crawls of the page | Agent Analytics | Check that changes were picked up |

**Timeline:** baseline weeks 1 to 3, changes ship week 4, measure weeks 5 to 12.

**Success criteria:** the test group's citation rate rises at least 10 points more than control, and the gap holds for the last 3 weeks. A smaller gap is still worth reporting if it also shows up in AI-referred traffic.

**Watch out for:** content changes on control pages made by other teams. Ask web and content teams to freeze them for 12 weeks.

## Test 2: Time from crawl to citation

This test measures how many days each AI engine takes to crawl and then cite new content. The answer tells the team when to expect results from any future AEO work.

**Hypothesis:** Each engine has a typical lag that can be measured. For example, Perplexity may cite new pages within days, while ChatGPT may take weeks.

**Design**

1. Publish 8 to 10 new pages, each targeting 2 or 3 prompts where you aren't cited today.
2. Submit each page to your sitemap and IndexNow on the day it publishes, and record the publish date.
3. In Agent Analytics, log the first visit from each AI bot (GPTBot, OAI-SearchBot, PerplexityBot, Google-Extended, ClaudeBot and others).
4. In prompt tracking, log the first day each page is cited, by engine.
5. Run Test 1's page changes through the same log too. They give you more data points at no extra cost.

**Metrics**

| Metric | Source |
| --- | --- |
| Days from publish to first bot crawl, per engine | Agent Analytics |
| Days from first crawl to first citation, per engine | Agent Analytics + prompt tracking |
| Share of pages cited at all within 8 weeks | Prompt tracking |

**Timeline:** publish in week 4, track daily through week 12.

**Success criteria:** a median lag for each engine, plus a list of pages that were crawled but never cited. That list is a separate finding, since it points to content problems rather than access problems.

**Watch out for:** pages that are never crawled. Check robots.txt, firewall bot rules and JavaScript rendering before blaming the content.

## Test 5: Accuracy audit

This test measures how often AI engines get facts about you wrong, then shows those errors going down after the sources are fixed. It usually finds problems quickly, and support, product and legal teams care about the results too.

**Hypothesis:** At least 15% of AI answers about your company contain a factual error. Fixing the sources behind those errors cuts that rate by half within 8 weeks.

**Design**

1. Write a fact sheet of 20 to 30 facts that matter: pricing, plans, key features, integrations, limits, policies, company details. Have product or legal sign off on it.
2. Write 30 to 50 prompts that should produce those facts ("How much does X cost?", "Does X integrate with Y?").
3. Pull every answer from Profound and score each claim with the rubric below.
4. For each error, use Profound's cited sources to find where it comes from: an old page of yours, an outdated review, a third-party listing, or no source at all.
5. Fix the sources: update or redirect old pages, add a clear facts or pricing page, and ask third-party sites to correct their listings.
6. Re-score every 2 weeks with the same prompts and rubric.

Full prompt list: [Test 5 prompt set](test-5-prompt-set.md)

Fact sheet template: [Test 5 fact sheet](test-5-fact-sheet.md)

**Scoring rubric**

| Score | Meaning | Example |
| --- | --- | --- |
| Correct | Matches the fact sheet | Current price, current plan names |
| Outdated | Was true once | Last year's pricing |
| Wrong | Never true | A feature you don't offer |
| Missing | Engine says it doesn't know or skips it | "Pricing isn't publicly available" |

**Metrics:** error rate (outdated + wrong as a share of all scored claims), by engine and by fact type. Also count errors that would cost money, such as a lower price or a missing key feature.

**Timeline:** audit in weeks 1 to 2, fixes in weeks 3 to 4, re-score in weeks 6, 8, 10 and 12.

**Success criteria:** error rate down at least 50% from the first audit. Report the 5 most costly errors with before and after screenshots, since those are the strongest evidence.

**Watch out for:** two people scoring differently. Have two people score the first 50 claims and agree on edge cases before one person scores the rest.

## Test 8: Launch tracking

This test tracks how quickly and how accurately AI engines learn about your next launch, compared with a recent competitor launch. It has a fixed date and a clear before and after, which makes it easy to explain to leadership.

**Hypothesis:** With an AEO launch checklist, AI engines mention the new product accurately within 30 days, faster than they did for the competitor's last launch.

**Design**

1. Choose the launch. Set up 15 to 25 prompts 2 weeks before it goes live: category prompts ("best tool for..."), comparison prompts ("X vs Y") and direct prompts ("What is [product]?").
2. Choose a competitor launch from the past 6 months as the benchmark. Run the same prompt types for it and record how long it took to appear, using Profound's history if it covers that period.
3. Before launch, prepare the AEO checklist: a launch page with a direct summary and FAQ, schema markup, a press release, a docs or help page, and outreach to 2 or 3 sources Profound shows engines cite in your category.
4. After launch, track daily for 30 days and weekly until day 60.
5. Score each mention for accuracy with Test 5's rubric.

**Metrics**

| Metric | Source |
| --- | --- |
| Days to first mention, per engine | Prompt tracking |
| Share of launch prompts mentioning the product at day 30 and day 60 | Prompt tracking |
| Accuracy of mentions (Test 5 rubric) | Manual scoring |
| Sources cited for the launch | Profound citations |
| AI-referred visits to the launch page | Agent Analytics + web analytics |

**Timeline:** prompts set 2 weeks before launch, then 60 days of tracking. Fit it to the real launch date. It doesn't need to match the other tests.

**Success criteria:** mentioned by at least 3 engines within 30 days, at least 80% of mentions accurate, and faster than the competitor benchmark.

**Watch out for:** a launch that's much bigger or smaller than the competitor's. Note press coverage and launch spend for both so the comparison is fair.

## Timeline

All four tests read out by week 12. Test 8 follows the real launch date instead.

| Week | Shared setup | Test 1: Holdout pages | Test 2: Crawl to citation | Test 5: Accuracy audit |
| --- | --- | --- | --- | --- |
| 1 | Baseline | Baseline | | Audit |
| 2 | Baseline | Baseline | | Audit |
| 3 | Baseline | Baseline | | Fix sources |
| 4 | | Ship changes | Publish new pages | Fix sources |
| 5 | | Measure vs control | Track crawls and citations | |
| 6 | | Measure vs control | Track crawls and citations | Re-score |
| 7 | | Measure vs control | Track crawls and citations | |
| 8 | | Measure vs control | Track crawls and citations | Re-score |
| 9 | | Measure vs control | Track crawls and citations | |
| 10 | | Measure vs control | Track crawls and citations | Re-score |
| 11 | | Measure vs control | Track crawls and citations | |
| 12 | | Measure vs control, readout | Track, readout | Re-score, readout |

Test 8: set prompts 2 weeks before launch, then track for 60 days.

One shared baseline in weeks 1 to 3 feeds Tests 1, 2 and 5. Changes ship in week 4, so everything except Test 8 can report at week 12.

## Open questions before kickoff

- [ ] Does our Profound plan cover enough prompts (about 150) and engines for all four tests at once?
- [ ] Is Agent Analytics connected to our site or CDN, and are bot visits logging?
- [ ] Can web and content teams freeze the 10 control pages in Test 1 for 12 weeks?
- [ ] Who signs off on the Test 5 fact sheet (product, legal or both)?
- [ ] Which launch is Test 8 for, and what's its date?
- [ ] Which competitor launch is the Test 8 benchmark, and does Profound's history cover it?
- [ ] Who owns the weekly tracking sheet, and who gets the final readout?
