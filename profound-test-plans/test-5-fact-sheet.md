# Test 5 fact sheet

The source of truth for scoring AI answers in Test 5. Each fact has an ID, the correct answer today, old answers to watch for, and the prompts that check it (numbers from the [Test 5 prompt set](test-5-prompt-set.md)).

## How to fill it in

1. **One fact per row, written so a scorer can check it in seconds.** "Pro is $49 per user per month, billed annually" works. "Competitive pricing" doesn't.
2. **Fill in "Old answers to watch for."** List past prices, retired plan names and removed features. This is how scorers tell "Outdated" from "Wrong."
3. **Link the source of truth.** Use the public page that should be correct. If no public page states the fact, write "none". That's a finding too, since engines can't cite a page that doesn't exist.
4. **Only include what you'd say publicly.** If a fact is confidential (for example, exact customer count), write the public version or remove the row and its prompts.
5. **Freeze it before the first audit.** If a fact changes during the test (say, a price change), add a new row with a date. Don't overwrite the old one, or earlier scores won't make sense.

Any prompt without a fact here can't be scored.

## Pricing and plans

| ID | Fact | Current answer | Old answers to watch for | Source of truth | Prompts |
| --- | --- | --- | --- | --- | --- |
| F1 | Starting price | | | | 1, 8 |
| F2 | Plan names and prices (monthly and annual) | | | | 2 |
| F3 | Free plan and free trial (length, limits) | | | | 3 |
| F4 | What each plan includes | | | | 4 |
| F5 | Pricing model (per user, flat, usage-based) | | | | 5 |
| F6 | Annual billing discount | | | | 6 |
| F7 | Startup, nonprofit or education pricing | | | | 7 |
| F8 | Add-on, setup and overage fees | | | | 9 |

## Features and limits

| ID | Fact | Current answer | Old answers to watch for | Source of truth | Prompts |
| --- | --- | --- | --- | --- | --- |
| F9 | One-sentence product description | | | | 10 |
| F10 | Top 5 features | | | | 11 |
| F11 | Main use cases and who it's for | | | | 12, 44 |
| F12 | Platforms (web, iOS, Android, desktop) | | | | 13 |
| F13 | Limits per plan (users, projects, storage) | | | | 14 |
| F14 | API availability and which plans include it | | | | 15 |
| F15 | Languages and regions supported | | | | 16 |
| F16 | Real limitations today, plus old complaints already fixed | | | | 17, 40, 45 |
| F17 | Major releases in the last 12 months | | | | 18 |

## Integrations

| ID | Fact | Current answer | Old answers to watch for | Source of truth | Prompts |
| --- | --- | --- | --- | --- | --- |
| F18 | Top integrations, and whether each is native or via a connector | | | | 19, 20, 21 |
| F19 | Zapier or other automation support | | | | 22 |
| F20 | Import and migration from each main competitor | | | | 23 |
| F21 | SSO providers supported, and which plans include SSO | | | | 24 |

## Security, policies and support

Legal or security should write these answers, not marketing.

| ID | Fact | Current answer | Old answers to watch for | Source of truth | Prompts |
| --- | --- | --- | --- | --- | --- |
| F22 | Security certifications (SOC 2, ISO 27001) | | | | 25 |
| F23 | GDPR status and where data is stored | | | | 26 |
| F24 | HIPAA or other regulated-industry support | | | | 27 |
| F25 | Whether customer data is used to train AI | | | | 28 |
| F26 | Refund and cancellation terms | | | | 29 |
| F27 | Support channels, hours and uptime SLA | | | | 30, 31 |
| F28 | Publicly disclosed security incidents (or none) | | | | 32 |

## Company facts

| ID | Fact | Current answer | Old answers to watch for | Source of truth | Prompts |
| --- | --- | --- | --- | --- | --- |
| F29 | Ownership, funding status and acquisitions | | | | 33 |
| F30 | CEO and key leaders | | | | 34 |
| F31 | Headquarters and main offices | | | | 35 |
| F32 | Company size and customer count (public figures only) | | | | 36 |
| F33 | Customers you're allowed to name publicly | | | | 37 |

## Comparison claims

Write one row per competitor for F34 to F36. Only score what AI says about you. Claims about competitors are context, not errors.

| ID | Fact | Current answer | Old answers to watch for | Source of truth | Prompts |
| --- | --- | --- | --- | --- | --- |
| F34 | How you differ from [Competitor] (2 or 3 points you can back up) | | | | 38, 43 |
| F35 | Your price compared with [Competitor] | | | | 39 |
| F36 | Gaps vs [Competitor] closed in the last 2 years | | | | 40 |
| F37 | Segments you serve (small business, enterprise, industries) | | | | 41, 42, 44 |
| F38 | Review ratings and where they're published (G2, Capterra) | | | | 45 |

## Sign-off

Each group needs one owner who confirms the answers before the first audit.

| Group | Facts | Suggested owner | Owner | Signed off |
| --- | --- | --- | --- | --- |
| Pricing and plans | F1 to F8 | Product marketing or finance | | |
| Features and limits | F9 to F17 | Product | | |
| Integrations | F18 to F21 | Product or partnerships | | |
| Security, policies and support | F22 to F28 | Legal, security and support | | |
| Company facts | F29 to F33 | Communications | | |
| Comparison claims | F34 to F38 | Product marketing | | |
