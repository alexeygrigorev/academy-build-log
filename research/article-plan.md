# DataTalksClub Academy: SEO and AEO Article Plan, November 2026 to February 2027

Date: 15 November 2026. I plan 11 long-form articles in English. This plan builds on the [SEO content plan](seo-content-plan.md), the [domain and SEO plan](domain-and-seo-plan.md) and the [competitor keyword research](competitor-keywords.md). It is the source of truth for articles, and the [marketing plan](marketing-plan.md) repeats its list and dates.

On the site the brand is written DataTalks.Club Academy. On social and in this build log it is DataTalksClub Academy.

Goal: rank #1 in Google Germany for the target queries in section 3a before the cohort fills, and be named and cited by AI tools for the same queries. Primary KPI: confirmed (double opt-in) waitlist signups from voucher-eligible people. Rankings, impressions and citations are secondary.

## 1. Ground Rules Used in Every Brief

Product facts, the same in every brief:

- DataTalksClub Academy is a full-time live program in English for experienced developers in Germany (2+ years of experience). 15 seats. Start: April 2027 (no exact day). 3 months (13 weeks), Monday to Friday, 09:00 to 16:30 Berlin time, in Berlin or live online.
- Two programs: Agentic Engineering (based on AI Dev Tools Zoomcamp and my experience running coding agents 24/7 for the last year) and AI Engineering (based on LLM Zoomcamp, AI Engineering Buildcamp, and my experience building AI products and putting them in production).
- Funding wording in every article, meta description, answer block, title and FAQ answer: "Designed for Bildungsgutschein funding (AZAV)." German: "Für die Förderung per Bildungsgutschein nach AZAV konzipiert." No article claims that a voucher is approved. The Agentur für Arbeit decides on each voucher.
- The free Hireable With AI sessions (Mon 23 Nov, Mon 30 Nov, Mon 7 Dec 2026, 17:00 Berlin time, on Zoom) are separate promo events. Articles may link to `/academy/sessions/` but never describe the sessions as part of the course schedule. The three sessions have new titles: "AI Engineering vs Agentic Engineering for Experienced Developers", "How I Build Software with Claude Code and Other Coding Agents" and "AI Engineering for Experienced Developers: How to Build Apps on Top of LLMs".
- Brand: DataTalks.Club Academy on the site and in articles, DataTalksClub Academy on social and in the build log.
- Instructor line: "Taught by Alexey Grigorev. He has taught more than 100,000 students in DataTalks.Club courses."
- No job-placement promises. No unsourced statistics. No dashes as punctuation in article copy. Titles in Title Case. German content lives only on `/academy/bildungsgutschein/`.

Primary CTA and KPI, the same in every brief:

- One primary CTA: **Join the Waitlist**, placed after the answer block and at the end of the article. The link goes to the waitlist form of the matching program and carries `utm_source=article&utm_medium=article&utm_campaign=<slug>`.
- Primary KPI: confirmed voucher-eligible waitlist signups whose source tag is that article. Every signup target in the briefs counts confirmed signups.
- Under the H1 each article has the 2 to 3 sentence answer block, then one line that links the matching program and the waitlist.

What the articles must not do:

- They do not duplicate course intent. "ai bootcamp berlin", "ai bootcamp", "ai engineering course berlin", "agentic engineering course germany" and similar commercial course queries stay mapped to `/academy/` and the two course pages (section 3a). Articles answer informational and comparison questions and hand the reader to those pages.
- They do not target "llm course". Serpstat shows 70 a month in `g_de` with difficulty 1, but the related queries are about a Master of Laws degree ([SEO content plan](seo-content-plan.md)).
- They do not target "weiterbildung auf englisch" (390). The live results are dictionary pages, so the intent is translation ([competitor keyword research](competitor-keywords.md), rejected list). The same holds for "ki weiterbildung" (2,400), which returns German courses for managers and beginners.
- They do not target German-language readers who want a German course. German keywords appear in the briefs only where English speakers in Germany search the German term as a loanword ("Bildungsgutschein", "Widerspruch", "Arbeitslosengeld"), and the German page stays the owner of German-language demand.

URLs. Articles are published on the DataTalksClub blog at `https://datatalks.club/blog/<slug>.html`, and the canonical academy host is `https://datatalks.club/academy/`.

## 2. Data Sources and How to Read the Labels

| Label in the briefs | What it is | How to read it |
| --- | --- | --- |
| Serpstat `g_de` | Monthly search volume and difficulty (0 to 100) from Serpstat's Germany database, pulled 15 November 2026. | Germany only. No Berlin split. |
| "difficulty not pulled" | Serpstat has a row and a volume for this keyword, and the difficulty value is not part of the 15 November pull. | This is not "no row". |
| "no value" | Serpstat has a row and a volume, and the difficulty field is empty. | |
| "unknown (no Serpstat row)" | The keyword was in the 15 November pull and Serpstat returned no row. | Usually means the volume is too low to report, not zero. |
| "unknown (not pulled)" | The keyword is not part of the 15 November Serpstat pull. | No number is assumed. |
| Serpstat cached SERP features | The result page features Serpstat stores for a keyword (for example AI Overview, People Also Ask). | Serpstat's stored snapshot of the Google Germany results page. |
| Web search check | A web search on 15 November 2026 with the exact query quoted in the brief. | Results are in the order the search tool returned them. They are not Google Germany positions. |
| Live top 3, Google Germany | Google Germany, desktop, 15 November 2026, with Moz Domain Authority in brackets ([competitor keyword research](competitor-keywords.md), sections 3, 5 and 6). | 47 queries. This is the position data behind section 3a. |
| AI answers, 15 November baseline | ChatGPT (with web search), Perplexity and Google AI Overviews (Germany) for the three test questions in section 7.1, from the [domain and SEO plan](domain-and-seo-plan.md). | Three questions only. Claude and Gemini join on 16 November. |
| AI summary of a web search tool | The AI-written summary that the web search tool returned with its results on 15 November 2026, and the pages it leaned on. | It is reported separately and never counted as a citation in one of the five tracked tools. |

## 3. Keyword Clusters

Five clusters. Each has one owner page for commercial or German demand and a set of articles for informational demand.

| Cluster | Owner page (not an article) | Articles | Keywords with Serpstat `g_de` volume and difficulty |
| --- | --- | --- | --- |
| A. Brand and entity | `/academy/` | 1 | "datatalks.club academy", "datatalks academy", "hireable with ai": all unknown (no Serpstat row) |
| B. Agentic engineering | `/academy/agentic-engineering/` | 2, 3 | "agentic engineering", "agentic engineering course", "agentic engineering course germany", "coding agents course", "claude code course": unknown (no Serpstat row). "ai software engineering": 140, difficulty 5. "claude code": 135,000, difficulty 38 |
| C. AI engineering | `/academy/ai-engineering/` | 2, 4 | "ai engineering": 3,600, difficulty 12. "ai engineer": 3,600, difficulty 8. "ai engineer course": 210, difficulty 4. "ai engineer salary": 140, difficulty 4. "ai engineering course berlin", "ai engineering bootcamp berlin", "llm engineering course berlin": unknown (no Serpstat row) |
| D. Course choice and comparison | `/academy/` and both course pages | 6, 11 | "ai bootcamp": 170, difficulty 3. "artificial intelligence bootcamp": 170, no value. "ai bootcamp berlin", "ai bootcamp germany", "ai course for experienced developers germany", "ai course bildungsgutschein": unknown (no Serpstat row) |
| E. Bildungsgutschein for English speakers | `/academy/bildungsgutschein/` (German, the only German page) | 5, 7, 8, 9, 10 | "bildungsgutschein in english": 30, difficulty 1. "bildungsgutschein courses in english": 40, no value. "bildungsgutschein": 9,900, difficulty 7. "bildungsgutschein beantragen": 1,900, difficulty 21. "bildungsgutschein voraussetzungen": 1,600, difficulty 38. "arbeitslosengeld weiterbildung": 480, difficulty 15. "bildungsgutschein berlin": 140, difficulty 8. "bildungsgutschein englisch": 40, difficulty 3 (language-school intent, not a target). "bildungsgutschein agentur für arbeit": 5,400, difficulty not pulled. "bildungsgutschein jobcenter": 1,600, difficulty not pulled. "weiterbildung mit bildungsgutschein": 880, difficulty not pulled |

Cannibalization rules:

- Article 2 owns the comparison "AI engineering vs agentic engineering". Article 3 owns the definition "what is agentic engineering". Article 4 owns "backend developer to AI engineer" and the salary question. None of them uses "course", "bootcamp" or a city in the title or H1.
- Article 5 is the English pillar for the voucher cluster. Articles 7 to 10 each answer one narrower question and link up to article 5 and to the German page.
- Article 6 owns the course queries with "experienced developers" and "bildungsgutschein" in them. Article 11 owns the bootcamp list query "ai bootcamp germany". `/academy/` owns "ai bootcamp" and "ai bootcamp berlin", so article 11 has no city in its title and links to `/academy/` with the anchor "AI bootcamp in Berlin for experienced developers".
- The German page keeps every German-language keyword. English articles mention the German terms once, in the form readers see on letters and forms, and link to the German page with German anchor text.

## 3a. Target Keywords and #1 Goal

Source: the [competitor keyword research](competitor-keywords.md) (Serpstat `g_de`, live Google Germany top 3 and Moz Domain Authority, all 15 November 2026). This section folds its target table into the article plan. Every target keyword has one owner: an existing page or one article.

### The Goal

Rank #1 in Google Germany for the queries below where #1 is within reach, and top 3 for the rest, before the cohort fills. The cohort fills before April 2027, so a position reached after April is of little use for this cohort. The dates are therefore front-loaded:

- Where the domain authority of datatalks.club beats the current top 3, or the top 3 has no page that matches the query: top 3 by 31 Jan 2027, #1 by 31 Mar 2027.
- Where stronger domains hold the query (Le Wagon, Ironhack city pages, arbeitsagentur.de): top 3 by 31 Mar 2027, and #1 is a stretch after that.
- Giants (IBM, GitHub, Udemy, Coursera): top 10 and an AI Overview citation by 31 Mar 2027.

Every position and date is a target, not a forecast. Baseline on 15 November 2026: datatalks.club is in no top 10 for any of the 46 non-brand queries checked, and `/academy/` does not appear for "datatalks club academy".

### Target Keyword Table

Priority: P1 = build or change content before 31 Dec 2026. P2 = by 31 Jan 2027. P3 = supporting, by 28 Feb 2027. "unknown" = no Serpstat row. Top 3 are live, Google Germany desktop, 15 Nov 2026, with Moz DA in brackets (n/m = not measured).

| # | Query | Volume | Difficulty | Top 3 now | Target page or article | Content needed | Target position and timeframe |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | bildungsgutschein in english | 30 | 1 | digitalcareerinstitute.org (32), startsteps.org (21), theberlinlife.com (16) | Article 5 | Two-sentence definition under the H1, who is eligible, steps, what an experienced developer says in the appointment, FAQ, links to arbeitsagentur.de sources | P1. Top 3 by 31 Jan 2027, #1 by 31 Mar 2027 |
| 2 | bildungsgutschein courses in english | 40 | no value | digitalcareerinstitute.org (32), cybersteps.de (23), reddit.com (92) | Article 5 (section "Voucher Courses Taught in English"), supported by articles 6 and 8 | A dated list of English-taught voucher courses by field with provider, length, language and level | P1. Top 3 by 31 Jan 2027, #1 by 31 Mar 2027 |
| 3 | ai bootcamp berlin | unknown | unknown | tsa-bildung.de (12), reddit.com (92), info.lewagon.com (59) | `/academy/` | Title and H1 with "AI Bootcamp in Berlin" and "experienced developers", the facts block, links to both programs, Join the Waitlist above the fold | P1. Top 3 by 31 Jan 2027, #1 by 31 Mar 2027 |
| 4 | ai bootcamp | 170 | 3 | artificialintelligencebootcamp.de (8), zeb-business-school.com (9), ironhack.com (58) | `/academy/` | Same page. First lines say it is for developers who already ship code | P1. Top 3 by 31 Jan 2027, #1 by 31 Mar 2027 |
| 5 | ai engineering course berlin | unknown | unknown | spiced-academy.com (25), ironhack.com (58), tu.berlin (n/m) | `/academy/ai-engineering/` | "AI Engineering Course in Berlin" in title and H1, syllabus by week, tools, dates, language, Course structured data | P1. Top 3 by 31 Mar 2027, #1 a stretch after that |
| 6 | ai engineering bootcamp berlin | unknown | unknown | ironhack.com (58), spiced-academy.com (25), lewagon.com (59) | `/academy/ai-engineering/` | Same page, "bootcamp" in the first paragraph and one H2, a line comparing 32-week programs for career starters with 3 months for developers with 2+ years | P1. Top 3 by 31 Mar 2027, #1 a stretch after that |
| 7 | agentic engineering course germany | unknown | unknown | nobleprog.de (n/m), cee.ed.tum.de (n/m), ciis.uni-koeln.de (n/m) | `/academy/agentic-engineering/` | "Agentic Engineering Course in Germany" in title and H1, first sentence states full-time and 3 months against 2 to 5 day workshops | P1. Top 3 by 31 Jan 2027, #1 by 31 Mar 2027 |
| 8 | agentic engineering course | unknown | unknown | udemy.com (92), maven.com (52), agenticschool.dev (12) | `/academy/agentic-engineering/` | Same page, plus listings on comparison pages that already rank | P2. Top 10 by 31 Mar 2027 |
| 9 | ai course for experienced developers germany | unknown | unknown | nobleprog.de (n/m), hlrs.de (n/m), wbscodingschool.com (28) | Article 6 | A table: provider, program, entry level, length, language, funding, date checked, with the Academy in the same columns | P1. Top 3 by 31 Jan 2027, #1 by 31 Mar 2027 |
| 10 | ai course bildungsgutschein | unknown | unknown | iu-akademie.de (32), turingcollege.com (36), wbscodingschool.com (28) | Article 6 | An H2 "AI Courses and the Bildungsgutschein" | P2. Top 3 by 31 Mar 2027, #1 a stretch after that |
| 11 | ai bootcamp germany (also: artificial intelligence bootcamp, 170, no value) | unknown | unknown | lewagon.com (59), wbscodingschool.com (28), artificialintelligencebootcamp.de (8) | Article 11 (new brief) | A list post with one table sorted by entry level | P2. Top 3 by 31 Mar 2027, #1 a stretch after that |
| 12 | ai engineer course (also: ai engineer courses 210) | 210 | 4 | uat.zebrarobotics.com (n/m), udemy.com (92), coursera.org (n/m) | `/academy/ai-engineering/` | "AI engineer course" phrasing in an H2 and the FAQ | P2. Top 10 by 31 Mar 2027 |
| 13 | ai engineer course bildungsgutschein | unknown | unknown | haufe-akademie.de (42), neuefische.de (32), ironhack.com (58) | `/academy/ai-engineering/` | A funding section with the neutral line and a link to the German page | P2. Top 3 by 31 Mar 2027, #1 a stretch after that |
| 14 | llm engineering course berlin | unknown | unknown | ironhack.com (58), spiced-academy.com (25), lewagon.com (59) | `/academy/ai-engineering/` | One H2 "LLM Engineering" with RAG, evaluation and monitoring, plus a link to the free LLM Zoomcamp | P2. Top 3 by 31 Mar 2027, #1 a stretch after that |
| 15 | ai engineering bootcamp | unknown | unknown | ironhack.com (58), school.digitale-leute.de (36), udemy.com (92) | `/academy/ai-engineering/` | Same page, no extra content | P3. Top 10 by 31 Mar 2027 |
| 16 | agentic engineering | unknown | unknown | ibm.com (93), github.com (96), innoq.com (48) | Article 3 | Two-sentence definition, the difference to vibe coding, a worked example | P1. Top 10 and an AI Overview citation by 31 Mar 2027 |
| 17 | ai software engineering | 140 | 5 | newsletter.pragmaticengineer.com (n/m), iese.fraunhofer.de (n/m), linkedin.com (n/m) | `/academy/agentic-engineering/` | An H2 "AI Software Engineering for Working Developers" | P3. Top 10 by 31 Mar 2027 |
| 18 | ai engineering | 3,600 | 12 | github.com (96), aiengineeringfromscratch.com (18), ai-engineer.de (27) | Article 2 | A definition block for each term and a comparison table | P2. Top 20 by 31 Jan 2027, top 10 by 31 Mar 2027 |
| 19 | ai engineer | 3,600 | 8 | roadmap.sh (47), ai.engineer (n/m), learn.microsoft.com (n/m) | Article 4 | A "What Does an AI Engineer Do" block and a skills map from backend to AI | P3. Top 20 by 31 Mar 2027 |
| 20 | ai engineer salary (also: salary ai engineer 170, ai engineering salary 140) | 140 | 4 | reddit.com (92), wbscodingschool.com (28), optimaeurope.com (n/m) | Article 4 (new section "AI Engineer Salary in Germany") | Sourced salary ranges with links and dates | P3. Top 10 by 31 Mar 2027 |
| 21 | ki weiterbildung bildungsgutschein | unknown | unknown | kurse.tuv.com (74), wbscodingschool.com (28), reddit.com (92) | `/academy/bildungsgutschein/` | German H2 that states the course language plainly | P2. Top 10 by 31 Mar 2027 |
| 22 | ki weiterbildung für softwareentwickler | unknown | unknown | gfu.net (37), haufe-akademie.de (42), iu-akademie.de (32) | `/academy/bildungsgutschein/` | One German section on who the program is for | P3. Top 10 by 31 Mar 2027 |
| 23 | datatalks club academy (also: datatalks academy, hireable with ai) | unknown | unknown | github.com/DataTalksClub (96), datatalks.club/ (34), linkedin.com (n/m) | `/academy/`, supported by article 1 | Links from the datatalks.club homepage and the GitHub organization profile, Organization structured data, sitemap | P1. #1 by 15 Dec 2026 |
| 24 | arbeitslosengeld weiterbildung | 480 | 15 | arbeitsagentur.de (70), mein-now.de (n/m), dekra-akademie.de (n/m) | Article 10 | The § 148 SGB III counting rule in English with a worked example | P3. Top 3 by 31 Mar 2027, #1 a stretch after that |

### Keyword to Owner Map

| Owner | Target table rows |
| --- | --- |
| `/academy/` | 3, 4, 23 |
| `/academy/ai-engineering/` | 5, 6, 12, 13, 14, 15 |
| `/academy/agentic-engineering/` | 7, 8, 17 |
| `/academy/bildungsgutschein/` (German) | 21, 22 |
| Article 1 | supports 23 |
| Article 2 | 18 |
| Article 3 | 16 |
| Article 4 | 19, 20 (brief extended with the salary section) |
| Article 5 | 1, 2 (brief extended with the section on voucher courses taught in English) |
| Article 6 | 9, 10 |
| Article 7 | no row. It carries the German loanwords "bildungsgutschein beantragen" and "voraussetzungen" for English readers |
| Article 8 | supports 2 |
| Article 9 | no row, kept for audience fit |
| Article 10 | 24 |
| Article 11 (new) | 11 |

What changed in the article list because of this table: article 11 is new, because no article covered the bootcamp comparison query "ai bootcamp germany". Article 6 moved up from 25 January to the week of 4 January, because two of its queries are #1 targets by 31 March. Article 10 moved up from 22 February to the week of 1 February. Articles 4 and 5 gained one section each. Article 8 is rescored without "weiterbildung auf englisch".

Page changes for the rows owned by `/academy/` and the course pages (titles, H1s, facts block, funding line) go through the site fix list.

### Domain Authority Comparison

Moz Domain Authority and referring root domains, pulled 15 November 2026 (full table of 23 domains in the [competitor keyword research](competitor-keywords.md), section 3).

| Domain | Moz DA | Referring root domains | Against datatalks.club |
| --- | --- | --- | --- |
| arbeitsagentur.de | 70 | 74,737 | Stronger |
| lewagon.com | 59 | 5,114 | Stronger |
| ironhack.com | 58 | 4,476 | Stronger |
| careerfoundry.com | 55 | 14,558 | Stronger, no matching keywords |
| wbstraining.de | 42 | 4,902 | Stronger |
| turingcollege.com | 36 | 1,365 | Slightly stronger |
| **datatalks.club** | **34** | **1,140** | |
| neuefische.de | 32 | 918 | Equal (Serpstat ranks it above datatalks.club) |
| digitalcareerinstitute.org | 32 | 797 | Weaker |
| wbscodingschool.com | 28 | 719 | Weaker |
| masterschool.com | 28 | 895 | Weaker |
| spiced-academy.com | 25 | 611 | Weaker |
| cybersteps.de | 23 | 281 | Weaker |
| startsteps.org | 21 | 560 | Weaker |
| tsa-bildung.de | 12 | 391 | Weaker |
| artificialintelligencebootcamp.de | 8 | 24 | Weaker |

- datatalks.club is 12th of the 23 domains compared. It beats most Berlin bootcamps and loses to Le Wagon, Ironhack and the government sites.
- Domain authority is not page authority. The academy pages are new on their URLs, and the competitor pages that rank are years old with their own links.
- #1 by 31 March is set where the current top results are weaker domains or weak pages (rows 1, 2, 3, 4) or where no top 3 page matches the query (rows 7, 9, 23).
- Top 3 by 31 March is set where Ironhack, Le Wagon, Turing College or arbeitsagentur.de hold the query (rows 5, 6, 10, 11, 13, 14, 24).

### Weekly GSC Position Tracking

Every Monday, together with the AI check in section 7.1:

1. Search Console, Domain property for datatalks.club, Performance report, country Germany, last full Monday to Sunday week, with clicks, impressions, CTR and average position.
2. One saved regex view per keyword group G1 to G8 (bootcamp, course, agentic, voucher in English, German KI, head terms, brand, benefit). The regexes are in the [competitor keyword research](competitor-keywords.md), section 8.1.
3. Export queries and pages per group to the sheet tab `gsc_raw`. The tab `targets` has one row per query from the table above with, per week: GSC average position, impressions, clicks, ranking URL, live position, AI Overview shown, Academy named, Academy URL cited, top 3 domains.
4. Live position check for the top 10 queries (Google Germany, logged out, desktop), because Search Console hides queries with very few searches and most of my targets are that small.
5. A target counts as reached when the live check shows the position on two Mondays in a row.
6. The same sheet shows confirmed voucher-eligible waitlist signups by source tag for the week, so positions are always read next to the primary KPI.

## 4. Hub and Spoke Internal Links

Hubs: the two course pages, the German Bildungsgutschein page, and the academy home. Spokes: the 11 articles. `/academy/faq/` links to every article once it exists.

| Article | Links out to (required) | Receives links from |
| --- | --- | --- |
| 1. Zoomcamps vs Academy | `/academy/`, both course pages, `/academy/bildungsgutschein/`, `/academy/sessions/` (until 7 Dec) | `/academy/` (a "Read more" line), datatalks.club homepage or Zoomcamp blog posts, articles 2, 6, 11 |
| 2. AI Engineering vs Agentic Engineering | Both course pages, article 3, article 4, `/academy/bildungsgutschein/` | Both course pages (definition sections), articles 1, 3, 4, 6, 11 |
| 3. What Is Agentic Engineering | `/academy/agentic-engineering/`, article 2, `/academy/ai-engineering/` (cross-module mention), `/academy/bildungsgutschein/` | `/academy/agentic-engineering/`, articles 2, 6 |
| 4. Backend Developer to AI Engineer | `/academy/ai-engineering/`, article 2, `/academy/agentic-engineering/` (cross-module mention), `/academy/bildungsgutschein/` | `/academy/ai-engineering/`, articles 2, 6 |
| 5. Bildungsgutschein in English (pillar) | `/academy/bildungsgutschein/`, both course pages, articles 6, 7, 8, 9, 10 | `/academy/bildungsgutschein/` (one English line: "English overview"), both course pages (funding line), articles 1, 6, 7, 8, 9, 10, 11 |
| 6. AI Courses for Experienced Developers | Both course pages, `/academy/bildungsgutschein/`, articles 2, 5, 11 | `/academy/`, `/academy/faq/`, articles 1, 5, 11 |
| 7. Preparing for the Appointment | `/academy/bildungsgutschein/`, article 5, article 9, both course pages | `/academy/bildungsgutschein/`, articles 5, 8, 9 |
| 8. B2 German and English Courses | `/academy/bildungsgutschein/`, articles 5, 7, 9, both course pages | Articles 5, 7 |
| 9. Bildungsgutschein Refused | `/academy/bildungsgutschein/`, articles 5, 7, 8, both course pages | Articles 5, 7, 8 |
| 10. ALG I During Training | `/academy/bildungsgutschein/`, article 5, both course pages | Articles 5, 7 |
| 11. AI Bootcamps in Germany | `/academy/` (anchor "AI bootcamp in Berlin for experienced developers"), both course pages, articles 2, 5, 6 | `/academy/`, articles 1, 6 |

Link rules: descriptive anchors ("Agentic Engineering program", "German Bildungsgutschein guide"), one "Join the Waitlist" call to action after the answer block and one at the end, and the course pages add a link back to the matching article in the same deploy. Changes to live course pages and the German page go through the site fix list.

## 5. Cadence and Calendar

Eleven articles in 15 weeks, November 2026 to February 2027. One a week while the sessions run, a two-week pause over the holidays, then one a week in January and the last two in early February. The order is front-loaded: every article that owns a #1 or top 3 target is out by 30 January, which leaves at least two months before the 31 March target date.

The week of 15 February is reserved for a refresh pass, not a new article.

| Week (Mon to Sat) | Article | Why this week |
| --- | --- | --- |
| 16 to 21 Nov 2026 | 1. Zoomcamps vs Academy | The [SEO content plan](seo-content-plan.md) schedules "one factual public post" as soon as the new URLs are live. Supports the brand target (#1 by 15 Dec) |
| 23 to 28 Nov | 2. AI Engineering vs Agentic Engineering | Session 1 on 23 Nov covers the same topic. Publish Tue 24 Nov |
| 30 Nov to 5 Dec | 3. What Is Agentic Engineering | Session 2 on 30 Nov. Publish Tue 1 Dec |
| 7 to 12 Dec | 4. Backend Developer to AI Engineer | Session 3 on 7 Dec. Publish Tue 8 Dec |
| 14 to 19 Dec | 5. Bildungsgutschein in English | The [SEO content plan](seo-content-plan.md) schedules the English voucher explainer for this week. It owns two #1 targets (rows 1 and 2), so it gets six weeks before the 31 Jan top 3 date |
| 21 Dec to 2 Jan 2027 | No new article | Holidays. Fix internal links, check indexation |
| 4 to 9 Jan | 6. AI Courses for Experienced Developers | Moved up from 25 Jan. It owns a #1 target (row 9) and a top 3 target (row 10) |
| 11 to 16 Jan | 7. Preparing for the Appointment | Readers need 8 to 10 weeks for appointments before April |
| 18 to 23 Jan | 8. B2 German and English Courses | Follows article 7 |
| 25 to 30 Jan | 11. AI Bootcamps in Germany | New. Owns "ai bootcamp germany" (row 11) and gives nine weeks before the 31 Mar top 3 date |
| 1 to 6 Feb | 10. ALG I During Training | Moved up from 22 Feb. Owns row 24, and it is the last planning question before an April 2027 start |
| 8 to 13 Feb | 9. Bildungsgutschein Refused | First refusals from January appointments arrive around now |
| 15 to 20 Feb | Refresh pass on all articles | Recheck every fact against the fact sheet, update tables and check dates |
| 22 to 27 Feb | No new article | Buffer week for drafts that slipped, inbound links and the positions that are short of target |

Workflow per article: I start from the brief in this plan, draft from the approved copy, check the facts against the fact sheet, publish, request indexing in Search Console, add inbound links from the hub pages and log the article in the public build log.

## 6. AEO as a First-Class Goal

What makes an article quotable, applied in every brief:

1. A 2 to 3 sentence answer block directly under the H1, written so it stands alone when quoted. It states the fact first and names DataTalksClub Academy only where the question is about the Academy. One line after it links the matching program and the waitlist.
2. H2s phrased as the questions people type into AI tools.
3. One set of facts across all pages, in the wording of the fact sheet: experienced developers in Germany, 2+ years, 15 seats, Start: April 2027, 3 months, Monday to Friday, 09:00 to 16:30 Berlin time, Berlin or live online, English, two programs, designed for Bildungsgutschein funding (AZAV). The 15 November baseline shows Perplexity already cites datatalks.club but describes the free courses, not the Academy ([domain and SEO plan](domain-and-seo-plan.md)), so consistency matters more than volume.
4. Primary sources linked inline for every legal or statistical claim (gesetze-im-internet.de, arbeitsagentur.de PDFs, the public build log research pages).
5. A visible FAQ block with matching FAQPage JSON-LD, plus Article and Organization markup from the site template.
6. Dates on every time-bound claim ("checked 15 November 2026").

Two limits. FAQPage structured data is not a promise of rich results: Google decides whether to show them and restricts FAQ rich results for most sites, so the markup is there to make question and answer pairs machine-readable, and the visible FAQ is what readers and models read. `llms.txt` is experimental: no search engine or AI vendor confirms it as a ranking or citation signal, so it is a small extra that lists the academy pages and articles, not a lever this plan depends on.

Off-page work that earns citations (KURSNET and mein NOW listings, comparison sites, Reddit and LinkedIn mentions) is in the [marketing plan](marketing-plan.md). Articles 6 and 11 are the on-site pieces that support those listings.

## 7. Measurement

### 7.1 Weekly Monday AI Check

Every Monday at about 09:00 Europe/Berlin, starting 16 November 2026. The three test questions come from the [domain and SEO plan](domain-and-seo-plan.md) and are used in exactly this wording:

1. "What AI engineering courses in Berlin can I pay for with a Bildungsgutschein?"
2. "Which agentic engineering course is there for experienced developers in Germany?"
3. "Welche Weiterbildung für erfahrene Entwickler in KI gibt es in Berlin mit Bildungsgutschein?"

Tools: ChatGPT (web search on), Perplexity, Google AI Overviews (Germany), Claude (web search on) and Gemini. The [SEO content plan](seo-content-plan.md) lists the first three. I add Claude and Gemini here, and their first run on 16 November is their baseline.

Procedure: one run per tool per question, in a new chat, logged out or with memory off where possible, location Germany. That is 3 questions × 5 tools = 15 cells a week.

What to record per cell: date, tool, question, whether DataTalksClub Academy is named (yes or no), the exact cited URL if any, whether a `datatalks.club` URL is cited without naming the Academy, which other providers are named, and a screenshot or saved answer.

Mention rate and its denominator:

- Per tool and question: weeks in which the Academy was named ÷ weeks checked for that cell. Report it over the trailing 4 weeks, so the denominator is 4 per cell.
- Per tool: mentions ÷ 12 (3 questions × 4 weeks).
- Overall: mentions ÷ 60 (15 cells × 4 weeks).
- A week in which Google shows no AI Overview for a question counts as checked and not named, and is flagged "no AIO shown" so it can be separated later.
- Citation rate is tracked separately: cells where an academy or article URL is cited ÷ cells checked. A mention without a link and a link without a mention are different outcomes.

Baseline, 15 November 2026 ([domain and SEO plan](domain-and-seo-plan.md)): the Academy was named in 0 of 9 cells (3 questions × ChatGPT, Perplexity, Google AI Overviews). Perplexity cited datatalks.club and the Meetup group for questions 1 and 3 but did not present the Academy as a voucher program. The competitor keyword research adds: 0 of 10 Google AI Overviews for the top 10 target queries name the Academy.

Added from the [competitor keyword research](competitor-keywords.md): the top 10 target queries are checked in Google AI Overviews every Monday with the live position check (section 3a), and three of them as questions in ChatGPT and Perplexity ("best ai bootcamp in berlin for experienced developers", "bildungsgutschein courses in english for software developers", "agentic engineering course in germany").

Article questions: each article adds one question (listed in its brief). It is checked in ChatGPT, Perplexity and Google AI Overviews every Monday for the first 4 weeks after publication, then on the first Monday of each month. Denominator: 3 tools × weeks checked.

### 7.2 Search Console, Umami and the Waitlist

| Tool | What is tracked | How |
| --- | --- | --- |
| Google Search Console (Domain property for datatalks.club) and Bing Webmaster Tools | Weekly position tracking for the 24 target queries (section 3a). Per article: indexed or not, impressions, clicks, average position, queries | Country Germany. Query filter with the regex groups G1 to G8, page filter on the article URL. Checked Mondays, exported to the `targets` sheet |
| Live position check | Position of the first datatalks.club URL for the top 10 target queries, top 3 domains, AI Overview shown or not | Google Germany, logged out, desktop, Mondays |
| Umami | Pageviews per article, referrers, `utm_*` parameters, events | Events: `cta_click` (with `page`, `position`, and for articles `article` = `a01` to `a11` and `target` = `agentic`, `ai` or `bildungsgutschein`), `waitlist_submit`, `waitlist_confirmed` |
| UTM on the in-article CTA | Every "Join the Waitlist" link in an article carries `utm_source=article&utm_medium=article&utm_campaign=<slug>&utm_content=top` or `end` | The slug is the article slug in the brief |
| UTM on links that point to an article from outside | `utm_source` = `newsletter`, `linkedin`, `x`, `slack`, `meetup`. `utm_medium` = `email`, `social` or `event`. `utm_campaign` = the article slug. `utm_content` = issue number or post id | Only on external promotion links. Links between articles carry no UTM parameters |
| Waitlist source tag | First-touch `utm_source`, `utm_medium`, `utm_campaign`, `utm_content` and `document.referrer`, stored with each signup as `source_tag` | The waitlist form stores the tag (an item on the site fix list). A signup counts for an article when its `utm_campaign` is the article slug. AI referrers map to `source_tag=ai` |
| AI referrals | Sessions with referrer `chatgpt.com`, `chat.openai.com`, `perplexity.ai`, `claude.ai`, `gemini.google.com`, `copilot.microsoft.com`, and landings with `utm_source=chatgpt.com` | Umami referrer report, filtered weekly, per landing page |

Limit of first-touch tags: a reader who first came from the newsletter and later joins through an article keeps the newsletter tag. The Umami path from `cta_click` with `article` = `aNN` to `waitlist_confirmed` is the second count, reported next to the source tag.

Limits of AI referral data. Referrers undercount AI use and the gap cannot be estimated from my side. Many AI apps and in-app browsers send no referrer. People read an answer and type the URL or search the brand later, which shows up as direct or branded search. Google AI Overviews clicks arrive as ordinary Google organic traffic, and Search Console does not report them separately. A mention with no link sends nobody. So AI referrals are a floor, the Monday check measures visibility, and the two are reported side by side without converting one into the other. Supporting signals: branded impressions in Search Console for "datatalks academy" and "datatalks.club academy", and a "How did you hear about us?" field on the waitlist survey with "An AI assistant (ChatGPT, Perplexity, Gemini, Claude)" as an option.

### 7.3 What Counts as a Voucher-Eligible Waitlist Signup

A confirmed (double opt-in) waitlist signup whose survey answers say the person lives in Germany, has 2+ years as a developer, is unemployed, in their notice period or registered as job-seeking, and can study full days. The waitlist survey asks about location, years as a developer, current situation, payment route, German level and full days.

### 7.4 Plan-Level Targets (All Are Targets, Not Forecasts)

The [market sizing research](market-sizing.md) (section 7.2) estimates that 15 seats need about 300 waitlist signups (range 240 to 400), an estimate built from stated benchmark assumptions.

- Primary target: 50 confirmed waitlist signups whose `utm_campaign` is an article slug by 31 March 2027, about 17% of the 300 estimate. The per-article targets in the briefs add up to 50. The voucher-eligible share of these is reported every Monday.
- Ranking targets: the #1 and top 3 dates in section 3a. In short: #1 for the brand query by 15 Dec 2026; top 3 by 31 Jan 2027 and #1 by 31 Mar 2027 for "bildungsgutschein in english", "bildungsgutschein courses in english", "ai bootcamp berlin", "ai bootcamp", "agentic engineering course germany" and "ai course for experienced developers germany"; top 3 by 31 Mar 2027 for the queries held by stronger domains.
- Target: all 11 articles indexed in Google within 7 days of their publication date.
- Target: the Academy named in at least 3 of the 15 weekly cells (3 questions × 5 tools) in at least one Monday check by 1 March 2027, from 0 of 9 on 15 November 2026.
- Target: the Academy named in the Google AI Overview for at least 3 of the top 10 target queries by 31 Jan 2027 and at least 6 by 31 Mar 2027.
- Target: at least one academy or article URL cited by Perplexity for test question 1 or 2 by 11 January 2027.
- Target: at least 5 of the 11 article questions return a `datatalks.club` citation in at least one of the three tools by 31 March 2027.

## 8. Priority Scoring

Score = volume × audience fit × feasibility, each from 1 to 5, maximum 125.

- Volume: 5 for 5,000 or more a month in Serpstat `g_de`, 4 for 1,000 to 4,999, 3 for 100 to 999, 2 for 1 to 99, 1 for unknown. The score uses the article's primary keyword. When the primary keyword is a German phrase and the article is in English, the score drops one level, because an English page reaches only the part of that demand that reads English.
- Audience fit: 5 when the reader is an experienced developer in Germany who could hold a voucher by April 2027.
- Feasibility: 5 when the current results are weak or I hold material nobody else has. 1 when official or very strong domains own the page. Feasibility uses the live top 3 and their Moz DA where a row exists in section 3a.

| # | Article | Primary keyword (volume, difficulty) | Volume | Fit | Feasibility | Score | Week |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2 | AI Engineering vs Agentic Engineering | "ai engineering" (3,600, 12) | 4 | 5 | 3 | 60 | 23 Nov |
| 5 | Bildungsgutschein in English | "bildungsgutschein in english" (30, 1) | 2 | 5 | 5 | 50 | 14 Dec |
| 7 | Preparing for the Appointment | "bildungsgutschein beantragen" (1,900, 21), German term | 3 | 5 | 3 | 45 | 11 Jan |
| 11 | AI Bootcamps in Germany | "ai bootcamp germany" (unknown, no Serpstat row), scored on its measured variant "artificial intelligence bootcamp" (170, no value) | 3 | 5 | 3 | 45 | 25 Jan |
| 8 | B2 German and English Courses | "bildungsgutschein courses in english" (40, no value) | 2 | 5 | 4 | 40 | 18 Jan |
| 1 | Zoomcamps vs Academy | "datatalks.club academy" (unknown, no Serpstat row) | 1 | 5 | 5 | 25 | 16 Nov |
| 6 | AI Courses for Experienced Developers | "ai course for experienced developers germany" (unknown, no Serpstat row) | 1 | 5 | 5 | 25 | 4 Jan |
| 3 | What Is Agentic Engineering | "agentic engineering" (unknown, no Serpstat row) | 1 | 5 | 4 | 20 | 30 Nov |
| 10 | ALG I During Training | "arbeitslosengeld weiterbildung" (480, 15), German term | 2 | 4 | 2 | 16 | 1 Feb |
| 9 | Bildungsgutschein Refused | "bildungsgutschein abgelehnt" (unknown, not pulled) | 1 | 5 | 3 | 15 | 8 Feb |
| 4 | Backend Developer to AI Engineer | "how to become an ai engineer" (unknown, not pulled) | 1 | 4 | 3 | 12 | 7 Dec |

What changed in the scores after the [competitor keyword research](competitor-keywords.md):

- I score article 5 on "bildungsgutschein in english" (30, difficulty 1) instead of "bildungsgutschein englisch", whose live results are language schools. Feasibility rises to 5 because datatalks.club beats all three current top domains on authority. Score 50, was 40.
- I rescored article 8. I reject "weiterbildung auf englisch" (390) on intent: the live results are dictionary pages. The article is now scored on "bildungsgutschein courses in english" (40), the measured query it supports. Volume stays at level 2 (before: 390 with the German-term discount; now 40 in English), so the score stays 40, but it no longer rests on a keyword with the wrong intent. Article 5 owns that query; article 8 answers the German-level question inside it and links up.
- I score article 6 on "ai course for experienced developers germany", which has no Serpstat row. "ai bootcamp" (170) moved to `/academy/`. Volume falls to 1 and feasibility rises to 5, because no page in the live top 3 matches the query. Score 25, was 45. It still moves up to 4 January because it owns a #1 target.
- Article 10 now has a measured keyword: "arbeitslosengeld weiterbildung" (480, difficulty 15). Volume is 2 after the German-term discount and feasibility is 2, because arbeitsagentur.de holds the top. Score 16, was 12.
- Article 11 is new and scores 45.

Why low or no-volume articles stay in the plan and why the order is not the score order:

- Article 1 scores 25 and goes first. It is the "one public post" the [SEO content plan](seo-content-plan.md) asks for, and it fixes a measured problem: on 15 November Perplexity cited datatalks.club but described the free courses when asked about the Academy, and the Google AI Overview for the brand query says the courses are "completely free". Feasibility is 5 because I am the only source for my own facts.
- Article 3 has no Serpstat row. The term is the name of a program and the subject of test question 2, where the 15 November AI answers named short workshops and conferences and organic results were weak. The [domain and SEO plan](domain-and-seo-plan.md) treats "agentic engineering" as an AI-search and early-adopter term.
- Article 6 scores 25 and goes in the first week of January: it is the page for two top 10 target queries, and no competitor page answers them.
- Article 9 has no measured volume. My discovery interviews and the [Berater objections research](berater-objections.md) name refusal of experienced people as the main conversion risk. A reader who finds this article is exactly the person a cohort needs.
- Article 4 scores 12. I publish it because session 3 on 7 December produces the material in the same week, and it now carries the salary section for rows 19 and 20.
- Article 10 answers the money question that decides whether a voucher holder can commit to full days for 3 months.
- Article 2 goes in week 2, not week 1, because session 1 gives it questions from real attendees.

---

## 9. Article Briefs

Each brief uses the same fields. The current results list the first five distinct URLs the web search returned, in returned order.

---

### Article 1. Free Zoomcamps or the Full-Time Academy: Which DataTalks.Club Course Fits You

**Publication week:** 16 to 21 November 2026. **Priority score:** 25 (volume 1, fit 5, feasibility 5). Low-volume exception explained in section 8.

**Slug:** `zoomcamps-vs-academy`

**Meta title:** Free Zoomcamps vs DataTalks.Club Academy: Which Fits You
**Meta description:** Zoomcamps are free and open to everyone. The Academy is a full-time live program for developers in Germany with 2+ years of experience. See which fits.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| datatalks.club academy | Primary | unknown (no Serpstat row) | unknown (no Serpstat row) |
| datatalks academy | Secondary | unknown (no Serpstat row) | unknown (no Serpstat row) |
| hireable with ai | Secondary | unknown (no Serpstat row) | unknown (no Serpstat row) |
| llm zoomcamp, ai dev tools zoomcamp | Secondary | unknown (not pulled) | unknown (not pulled) |

Serpstat cached SERP features: none available, no rows.

**Current results, web search.** Query: "DataTalks.Club Academy full-time program Germany Zoomcamp difference". Date: 15 November 2026.

1. https://www.everydev.ai/developers/datatalks-club
2. https://github.com/nenalukic/de-zoom-camp
3. https://datatalks.club/docs/courses/zoomcamp-logistics/before-you-start/
4. https://datatalks.club/blog/machine-learning-zoomcamp.html
5. https://info.lewagon.com/ai-data-academy

No academy URL was returned. The 15 November `site:academy.datatalks.club` check in the [domain and SEO plan](domain-and-seo-plan.md) also returned nothing.

**My angle to beat them.** No page in these results states the difference between the free Zoomcamps and the Academy. A page on datatalks.club that states it in the first three sentences, with one comparison table and the same facts as the course pages, is the only primary source. Third-party directory pages cannot match that.

**Thesis.** DataTalksClub now has two different things under one name: free Zoomcamps anyone can take, and a small full-time Academy for experienced developers in Germany. They suit different people, and the Academy is built on the Zoomcamp material.

**Reader benefit.** In two minutes the reader knows which one to take and what the Academy asks of them (Monday to Friday, 09:00 to 16:30 Berlin time, 3 months, 2+ years of experience, English).

**Problem it solves for the reader.** People who know the Zoomcamps assume the Academy is another free course, or assume it replaces them. People who never heard of DataTalksClub cannot tell who is behind the Academy.

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=<slug>` (the slug above). Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** Send experienced developers in Germany to the waitlist of the program that fits, and send everyone else to the free Zoomcamps without a hard sell. Target: 4 confirmed waitlist signups with `utm_campaign=zoomcamps-vs-academy` by 31 March 2027.

**AI questions this article answers**

- "Is DataTalks.Club Academy the same as the Zoomcamps?"
- "What is DataTalks.Club Academy?"
- "Does DataTalks.Club have a full-time course in Germany?"

Article question for the Monday check: "What is DataTalks.Club Academy and how is it different from the Zoomcamps?"

**Quotable answer block (directly under the H1)**

> DataTalks.Club Zoomcamps are free online courses that anyone can join. DataTalks.Club Academy is a separate full-time live program in English for experienced developers in Germany, with two programs, Agentic Engineering and AI Engineering, each 3 months, Monday to Friday, 09:00 to 16:30 Berlin time, with 15 seats. Start: April 2027, and the programs are designed for Bildungsgutschein funding (AZAV).

One line after the block links both programs and the waitlist ("Join the Waitlist").

**Outline**

- H1: Free Zoomcamps or the Full-Time Academy: Which DataTalks.Club Course Fits You
- Answer block
- H2: What the Zoomcamps Are (free, online, open to everyone, link to the course list)
- H2: What the Academy Is (full-time, live, English, 15 seats, Start: April 2027, 3 months, Monday to Friday 09:00 to 16:30 Berlin time, Berlin or live online)
- H2: The Two Academy Programs and What Each Is Based On (the program basis lines from the approved copy)
- H2: Side by Side (one table: cost, schedule, who it is for, group size, who teaches, how to join)
- H2: Who Should Stay with the Free Zoomcamps
- H2: Who the Academy Is For (2+ years of experience, in Germany, able to study full days)
- H2: The Academy and the Bildungsgutschein (the neutral line "Designed for Bildungsgutschein funding (AZAV).", link to the German page)
- H2: Who Teaches (the instructor line from the approved copy)
- H2: How to Join the Waitlist
- H2: FAQ

**Internal links.** `/academy/` (anchor "DataTalks.Club Academy"), `/academy/agentic-engineering/` ("Agentic Engineering program"), `/academy/ai-engineering/` ("AI Engineering program"), `/academy/bildungsgutschein/` ("German Bildungsgutschein guide"), `/academy/sessions/` ("free Hireable With AI sessions", remove the dated line after 7 December), the Zoomcamp course pages on datatalks.club.

**FAQ**

1. Is the Academy free like the Zoomcamps? No. The Zoomcamps are free. The Academy is a paid full-time program, designed for Bildungsgutschein funding (AZAV).
2. Do I need to finish a Zoomcamp before I join the Academy? No. The Academy is for developers with 2+ years of experience. The Zoomcamps are a good start if you have less experience.
3. When does the Academy start? Start: April 2027, with 15 seats. Join the waitlist and you hear first when applications open.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Is DataTalks.Club Academy free like the Zoomcamps?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. The Zoomcamps are free online courses. DataTalks.Club Academy is a paid full-time live program, designed for Bildungsgutschein funding (AZAV)."
      }
    },
    {
      "@type": "Question",
      "name": "Do I need to finish a Zoomcamp before I join DataTalks.Club Academy?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. The Academy is for developers with 2+ years of experience. The free Zoomcamps are a good start if you have less experience."
      }
    },
    {
      "@type": "Question",
      "name": "When does DataTalks.Club Academy start?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Start: April 2027, with 15 seats. Join the waitlist and you hear first when applications open."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- 15 November baseline ([domain and SEO plan](domain-and-seo-plan.md)), nearest question is test question 2: Perplexity pointed to the free AI Dev Tools Zoomcamp, mentioned a "DataTalks.Club Academy landing-page property" and then described the free club courses. ChatGPT and Google AI Overviews did not name the Academy.
- AI summary of a web search tool, 15 November 2026, for the web search query: it said it found no DataTalksClub Academy full-time program and suggested the user meant Le Wagon's AI and Data Academy, leaning on info.lewagon.com, datatalks.club Zoomcamp docs and a third-party directory.
- First Monday check for the article question: 23 November 2026.

**Expected results (targets)**

- Target: indexed within 7 days of publication.
- Target: `/academy/` at #1 in Google Germany for "datatalks club academy" and "datatalks academy" by 15 December 2026, with this article in the top 5 for the same queries (section 3a, row 23; tracked weekly in Search Console and the live check).
- Target: Perplexity describes the Academy as a full-time paid program, not as the free courses, in the Monday check by 14 December 2026.
- Target: 4 confirmed waitlist signups with `utm_campaign=zoomcamps-vs-academy` by 31 March 2027.

**Tracking.** GSC page filter `/blog/zoomcamps-vs-academy`, query regex `datatalks.*academy|zoomcamp.*academy|hireable with ai`. Umami events `cta_click`, `waitlist_submit` and `waitlist_confirmed` with `article=a01`. Waitlist source tag `utm_medium=article&utm_campaign=zoomcamps-vs-academy`; external links to the article carry the same `utm_campaign`. Monday AI check: article question in three tools for 4 weeks, then monthly.

---

### Article 2. AI Engineering vs Agentic Engineering: Which One Should an Experienced Developer Learn

**Publication week:** 23 to 28 November 2026 (Tuesday 24 November, the day after session 1). **Priority score:** 60 (volume 4, fit 5, feasibility 3).

**Slug:** `ai-engineering-vs-agentic-engineering`

**Meta title:** AI Engineering vs Agentic Engineering for Developers
**Meta description:** AI engineering is building apps on LLMs. Agentic engineering is shipping code with tools like Claude Code. How they differ and which to pick by background.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| ai engineering | Primary | 3,600 | 12 |
| agentic engineering | Secondary | unknown (no Serpstat row) | unknown (no Serpstat row) |
| ai engineering vs agentic engineering | Secondary | unknown (not pulled) | unknown (not pulled) |
| claude code | Context only, not a target | 135,000 | 38 |

Serpstat cached SERP features for "ai engineering": knowledge graph card, related searches, top ads, People Also Ask, AI Overview. Intents: commercial and informational. A head term with ads and an AI Overview sends few clicks to a new page, so the realistic win is the comparison long tail and a citation.

**Current results, web search.** Query: "AI engineering vs agentic engineering difference". Date: 15 November 2026.

1. https://arxiv.org/pdf/2606.05608
2. https://metavert.io/agentic-engineering-vs-ai-native-development
3. https://tessl.io/patterns/changing-roles/agentic-coding-vs-ai-engineering/
4. https://uxcel.com/glossary/agentic-engineering
5. https://www.turingcollege.com/blog/agentic-engineering-vs-vibe-coding

**My angle to beat them.** The returned pages are glossary entries, a vendor pattern page and "vs vibe coding" posts. The AI summary of the web search tool noted that almost no source contrasts the two terms directly. This article contrasts them head on, in the one-sentence definitions from the approved copy, adds "which to pick if you are a backend, frontend or data person" (the session 1 agenda), and cites job-ad counts from my own research instead of opinion.

**Thesis.** These are two different kinds of work. AI engineering puts LLMs inside a product. Agentic engineering uses coding agents to build any product. An experienced developer can start with either, and the choice depends on the work they already do.

**Reader benefit.** A clear definition of each term, what job ads ask for under each, and a way to choose based on current background.

**Problem it solves for the reader.** Job ads now mention "AI", "agents", "LLM" and "Claude Code" in the same breath, and developers cannot tell which skill set an ad means or which to learn first.

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=<slug>` (the slug above). Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** The reader picks one program and joins that program's waitlist. Target: 5 confirmed signups with `utm_campaign=ai-engineering-vs-agentic-engineering` by 31 March 2027.

**AI questions this article answers**

- "What is the difference between AI engineering and agentic engineering?"
- "Should a backend developer learn AI engineering or agentic engineering?"

Article question for the Monday check: "What is the difference between AI engineering and agentic engineering?"

**Quotable answer block**

> AI engineering is building apps that use LLMs, like chatbots, search over documents or agents. Agentic engineering is using tools like Claude Code or Cursor to write and ship code faster. The first changes what you build, the second changes how you build it, and an experienced developer can learn either one first.

**Outline**

- H1: AI Engineering vs Agentic Engineering: Which One Should an Experienced Developer Learn
- Answer block
- H2: What AI Engineering Is
- H2: What Agentic Engineering Is
- H2: How They Are Different (one table: what you build, daily work, tools, what you show in an interview)
- H2: What Companies Ask For in Each (sourced: 88 "AI Engineer" listings in BA Jobbörse for Berlin on 14 November 2026. On arbeitnow, 86 of 588 developer jobs in Germany named Claude Code, Cursor, Copilot, Codex or AI-assisted coding in the week of 7 to 14 November 2026, an approximate regex count. Both from the [supply, jobs and bootcamps research](supply-jobs-and-bootcamps.md))
- H2: Which One to Pick If You Are a Backend Developer
- H2: Which One to Pick If You Are a Frontend Developer
- H2: Which One to Pick If You Work with Data
- H2: Where the Two Overlap (each Academy program includes a module on the other)
- H2: How to Learn Each (free Zoomcamps first, then the two Academy programs, one paragraph each, no syllabus copy)
- H2: FAQ

**Internal links.** `/academy/ai-engineering/` ("AI Engineering program"), `/academy/agentic-engineering/` ("Agentic Engineering program"), article 3, article 4, `/academy/bildungsgutschein/` in one sentence about funding ("German Bildungsgutschein guide").

**FAQ**

1. Is agentic engineering the same as building AI agents? No. Building agents that do tasks for users is part of AI engineering. Agentic engineering means you use coding agents such as Claude Code or Cursor to write software, and you decide what to build and check the result.
2. Do I need a machine learning background for either one? No. Both start from software development experience. In a sample of 83 AI engineering job ads analysed by match.dev, 10% asked for model training.
3. Can I learn both? Yes. They complement each other. In DataTalks.Club Academy each program includes a module on the other.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is the difference between AI engineering and agentic engineering?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "AI engineering is building apps that use LLMs, like chatbots, search over documents or agents. Agentic engineering is using tools like Claude Code or Cursor to write and ship code faster."
      }
    },
    {
      "@type": "Question",
      "name": "Is agentic engineering the same as building AI agents?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. Building agents that do tasks for users is part of AI engineering. Agentic engineering means you use coding agents such as Claude Code or Cursor to write software, and you decide what to build and check the result."
      }
    },
    {
      "@type": "Question",
      "name": "Do I need a machine learning background for AI engineering or agentic engineering?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. Both start from software development experience. In a sample of 83 AI engineering job ads analysed by match.dev, 10% asked for model training."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- 15 November baseline, test question 2: ChatGPT read "agentic engineering" as short professional workshops (Fast Lane, GFU Cyrus, workshops.de, KEGON Academy, hackers&wizards). Google AI Overviews named the AI Engineering Summit Berlin, embarc's Agentic Engineering Bootcamp, neue fische's Agentic Machine Learning Engineer track and the AI Coding Summit. Perplexity pointed to the free AI Dev Tools Zoomcamp.
- AI summary of a web search tool, 15 November 2026, for the web search query: leaned on tessl.io, developertoolkit.ai (glossary), uxcel.com and turingcollege.com, and said the terms are not settled.
- First Monday check for the article question: 30 November 2026.

**Expected results (targets)**

- Target: indexed within 7 days.
- Target: top 10 in Google Germany for "ai engineering vs agentic engineering" by 31 January 2027.
- Target: top 20 for "ai engineering" (3,600) by 31 January 2027 and top 10 by 31 March 2027 (section 3a, row 18).
- Target: 300 Search Console impressions in the first 60 days.
- Target: cited or named for the article question in at least one of ChatGPT, Perplexity or Google AI Overviews by 11 January 2027.
- Target: 5 confirmed waitlist signups with `utm_campaign=ai-engineering-vs-agentic-engineering` by 31 March 2027.

**Tracking.** GSC page filter `/blog/ai-engineering-vs-agentic-engineering`, query regex `ai engineering|agentic engineering`. Umami `cta_click` with `article=a02` and `target` = `ai` or `agentic`, so the split shows which program readers choose. Waitlist source tag `utm_medium=article&utm_campaign=ai-engineering-vs-agentic-engineering`; external links to the article carry the same `utm_campaign`. Monday AI check: article question plus test question 2.

---

### Article 3. What Is Agentic Engineering: How I Build Software with Coding Agents

**Publication week:** 30 November to 5 December 2026 (Tuesday 1 December, the day after session 2). **Priority score:** 20 (volume 1, fit 5, feasibility 4). No-volume exception explained in section 8.

**Slug:** `what-is-agentic-engineering`

**Meta title:** What Is Agentic Engineering? A Working Developer's Guide
**Meta description:** Agentic engineering means coding agents write most of the code while you decide what to build and check the result. How the work changes for developers.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| agentic engineering | Primary | unknown (no Serpstat row) | unknown (no Serpstat row) |
| coding agents course | Secondary, mention only | unknown (no Serpstat row) | unknown (no Serpstat row) |
| claude code course | Secondary, mention only | unknown (no Serpstat row) | unknown (no Serpstat row) |
| claude code | Context, not a realistic target | 135,000 | 38 |

Serpstat cached SERP features for "claude code": AI Overview, People Also Ask, related searches, video. The market-sizing research found that in Google Trends for Germany "Claude Code" runs at about 7 times "AI Engineer", while almost nobody searches "Agentic Engineering" itself. The article therefore uses "Claude Code" and "Cursor" in H2s and examples, and treats the head term "claude code" as out of reach.

**Current results, web search.** Query: "what is agentic engineering coding agents developers". Date: 15 November 2026.

1. https://arxiv.org/pdf/2509.06216
2. https://letsdatascience.com/news/developers-adopt-agentic-engineering-for-automated-coding-815dbf2c
3. https://www.zenml.io/llmops-database/agentic-engineering-building-production-systems-with-coding-agents
4. https://www.sonarsource.com/resources/library/agentic-engineering/
5. https://resources.anthropic.com/hubfs/2026%20Agentic%20Coding%20Trends%20Report.pdf

Also returned: https://www.ibm.com/topics/agentic-engineering.

**My angle to beat them.** IBM, Sonar and Anthropic own the corporate definition, and a new page does not outrank them on the bare term. None of them is a first-person account from someone who runs agents every day and teaches it. The article is written in the first person from the line in the approved copy ("my experience running coding agents 24/7 for the last year"), shows what I still do myself and where agents make mistakes (the session 2 agenda), and links to my Substack posts as evidence. That is material a model can attribute to a named person.

**Thesis.** Agentic engineering is ordinary software engineering where the agent writes most of the code and the developer owns the spec, the checks and the result. The skill is in specifying, reviewing and verifying.

**Reader benefit.** A definition they can repeat in an interview, a picture of a working day with agents, and a list of what to practise.

**Problem it solves for the reader.** Experienced developers tried an assistant in the editor, did not use agents on real work, and have nothing to show for it. The [persona research](persona.md) states this in almost these words.

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=<slug>` (the slug above). Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** Readers who want to practise this full time join the Agentic Engineering waitlist. Target: 4 confirmed signups with `utm_campaign=what-is-agentic-engineering` by 31 March 2027.

**AI questions this article answers**

- "What is agentic engineering?"
- "How do experienced developers work with coding agents like Claude Code?"
- "Is agentic engineering different from vibe coding?"

Article question for the Monday check: "What is agentic engineering and how do developers work with coding agents?"

**Quotable answer block**

> Agentic engineering is using tools like Claude Code or Cursor to write most of the code, while you decide what to build and check the result. The developer writes the spec, splits it into small tasks, reviews every change and runs the tests before anything ships. It is still software engineering, and you answer for what goes to production.

**Outline**

- H1: What Is Agentic Engineering: How I Build Software with Coding Agents
- Answer block
- H2: What Agentic Engineering Means
- H2: How My Work Changed Since I Started Using Agents
- H2: What I Still Do Myself
- H2: Where Agents Make Mistakes
- H2: How Agentic Engineering Differs from Vibe Coding (verification is the difference)
- H2: What Companies Expect from Developers Who Use Agents (sourced: Stack Overflow Developer Survey 2026 figures as cited in the [supply, jobs and bootcamps research](supply-jobs-and-bootcamps.md): 66% use coding assistants or agents, and 48% trust AI output "when it is easy to check")
- H2: What to Practise First (specs and tasks, working in an existing codebase, tests, reviewing diffs, CI)
- H2: Where to Learn It (free AI Dev Tools Zoomcamp, then one paragraph on the Agentic Engineering program)
- H2: FAQ

**Internal links.** `/academy/agentic-engineering/` ("Agentic Engineering program"), article 2, `/academy/ai-engineering/` once (the AI Engineering program has an agentic module), `/academy/bildungsgutschein/` in the funding sentence, AI Dev Tools Zoomcamp page, my Substack.

**FAQ**

1. Is agentic engineering the same as vibe coding? No. In vibe coding you accept what the tool produces. In agentic engineering you write the spec, review every change and run tests before anything ships.
2. Which tools count as coding agents? Claude Code and Cursor are the two this article uses as examples. Codex and GitHub Copilot's agent mode work in a similar way.
3. Do I need experience with coding agents to start learning this? No. You need to be able to write and read code, use Git and the command line, and run tests.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is agentic engineering?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Agentic engineering is using tools like Claude Code or Cursor to write most of the code, while you decide what to build and check the result."
      }
    },
    {
      "@type": "Question",
      "name": "Is agentic engineering the same as vibe coding?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. In vibe coding you accept what the tool produces. In agentic engineering you write the spec, review every change and run tests before anything ships."
      }
    },
    {
      "@type": "Question",
      "name": "Do I need experience with coding agents to start learning agentic engineering?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. You need to be able to write and read code, use Git and the command line, and run tests."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- 15 November baseline, test question 2: see article 2. No tool named the Academy. Perplexity cited the free AI Dev Tools Zoomcamp, which is the opening this article uses.
- AI summary of a web search tool, 15 November 2026, for the web search query: leaned on ibm.com, sonarsource.com, the Anthropic 2026 Agentic Coding Trends Report, zenml.io and an arXiv paper.
- AI summary of a web search tool for test question 2 (15 November 2026): named andrena, ITLS, Simpliaxis, Haufe Akademie and HLRS Stuttgart, with no DataTalksClub page.
- First Monday check for the article question: 7 December 2026.

**Expected results (targets)**

- Target: indexed within 7 days.
- Target: 150 Search Console impressions in the first 60 days, from long-tail queries containing "agentic engineering", "coding agents" or "claude code".
- Target: top 10 in Google Germany for "agentic engineering" and cited in its AI Overview by 31 March 2027 (section 3a, row 16).
- Target: a `datatalks.club` URL cited for test question 2 in Perplexity or ChatGPT by 11 January 2027.
- Target: 4 confirmed waitlist signups with `utm_campaign=what-is-agentic-engineering` by 31 March 2027.

**Tracking.** GSC page filter `/blog/what-is-agentic-engineering`, query regex `agentic|coding agent|claude code|cursor`. Umami `cta_click` with `article=a03`. Waitlist source tag `utm_medium=article&utm_campaign=what-is-agentic-engineering`; external links to the article carry the same `utm_campaign`. Monday AI check: article question plus test question 2.

---

### Article 4. From Backend Developer to AI Engineer: What You Already Know and What to Learn First

**Publication week:** 7 to 12 December 2026 (Tuesday 8 December, the day after session 3). **Priority score:** 12 (volume 1, fit 4, feasibility 3). Exception explained in section 8.

**Slug:** `backend-developer-to-ai-engineer`

**Meta title:** Backend Developer to AI Engineer: Skills You Already Have
**Meta description:** What AI engineers build day to day, which backend, frontend and data skills carry over, and what to learn first. Based on job ads, not on ML theory.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| how to become an ai engineer | Primary | unknown (not pulled) | unknown (not pulled) |
| ai engineer skills | Secondary | unknown (not pulled) | unknown (not pulled) |
| ai engineer | Secondary (section 3a, row 19) | 3,600 | 8 |
| ai engineer salary | Secondary, one section (section 3a, row 20) | 140 | 4 |
| ai engineering | Secondary, owned by article 2 | 3,600 | 12 |
| weiterbildung softwareentwickler | German, owned by the German page, listed for the link only | 170 | difficulty not pulled |

**Current results, web search.** Query: "software engineer to AI engineer what skills do backend developers already have Germany". Date: 15 November 2026.

1. https://ai-jobs.net/job/170922-ai-platform-engineer/
2. https://www.iu.org/blog/career-guides/how-to-become-an-ai-engineer/
3. https://found.dev/job/sopra-steria-ai-backend-developer-m-w-d-xlup
4. https://www.arbeitnow.com/jobs/companies/stackfuel/senior-forward-deployed-engineer-ai-fullstack-berlin-155508
5. https://www.arbeitnow.com/jobs/companies/tripleten/remote-ai-developer-berlin-52009

Guides further down: imaginarycloud.com (AI engineer roadmap), interviewkickstart.com (AI skills for backend engineers), coderhouse.com.

**My angle to beat them.** The results are job ads and generic roadmaps that still tell developers to start with ML theory and model training. My research says otherwise with numbers: in 83 AI engineering ads analysed by match.dev, 81% asked for agents or tool use, 76% for distributed systems and APIs, and 10% for model training (the [supply, jobs and bootcamps research](supply-jobs-and-bootcamps.md), section 2.2). The article maps each requirement to a skill a backend developer already has and to the gap. Germany-specific data makes it more useful to my reader than a US roadmap.

**Thesis.** For most companies an AI engineer is a product developer who shipped an LLM feature. Backend developers already have most of what the ads ask for, and the gap is retrieval, tool calling, evaluation and cost and latency tracking.

**Reader benefit.** A two-column list: what carries over, what to learn, in which order.

**Problem it solves for the reader.** Experienced developers believe they need a machine learning degree to apply for AI engineer roles, and so do not apply or pick a course that starts with 2019-era ML.

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=<slug>` (the slug above). Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** Readers who want to close the gap in 3 months join the AI Engineering waitlist. Target: 3 confirmed signups with `utm_campaign=backend-developer-to-ai-engineer` by 31 March 2027.

**AI questions this article answers**

- "How do I become an AI engineer as a backend developer?"
- "What skills does an AI engineer need?"
- "Do I need machine learning to be an AI engineer?"

Article question for the Monday check: "How does an experienced backend developer become an AI engineer?"

**Quotable answer block**

> AI engineering is building products that use LLMs, like chatbots, search over your company's documents or agents that do tasks for users. A backend developer already has most of what the job ads list: APIs, tests, deployment and monitoring. What is new is retrieval over documents, tool calling, evaluating answers, and tracking cost and latency.

**Outline**

- H1: From Backend Developer to AI Engineer: What You Already Know and What to Learn First
- Answer block
- H2: What AI Engineers Build Day to Day
- H2: What Job Ads Ask For (match.dev sample of 83 ads, the 58-ad sample from my research: 35 of 58 senior, staff or lead, 2 junior)
- H2: Skills You Already Have from Backend Work
- H2: Skills You Already Have from Frontend Work
- H2: Skills You Already Have from Data Work
- H2: What Is New (retrieval, tool calling and MCP, evaluation, tracing, cost and latency, guardrails)
- H2: What You Can Skip at the Start (model training, advanced mathematics, a GPU)
- H2: What to Learn First, in Order
- H2: A Project That Shows the Skill in an Interview (no hiring promise, framed as interview preparation)
- H2: AI Engineer Salary in Germany (added for target row 20: sourced salary ranges with links and dates, no figure without a source. WBS Coding School and Turing College both feed their course page from a salary post)
- H2: Where to Learn It (free LLM Zoomcamp, then one paragraph on the AI Engineering program)
- H2: FAQ

**Internal links.** `/academy/ai-engineering/` ("AI Engineering program"), article 2, `/academy/agentic-engineering/` once (the program's agentic module), `/academy/bildungsgutschein/` in the funding sentence, LLM Zoomcamp page.

**FAQ**

1. Do I need a machine learning background to become an AI engineer? No. In a sample of 83 AI engineering job ads analysed by match.dev, 10% asked for model training and 76% asked for distributed systems and APIs.
2. Which language should I use? Python is the most common language for LLM applications. If you program in another language, the concepts carry over.
3. What should I build first? A small service on an LLM API that answers questions from documents with sources, and a test set that shows where it fails.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Do I need a machine learning background to become an AI engineer?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. In a sample of 83 AI engineering job ads analysed by match.dev, 10% asked for model training and 76% asked for distributed systems and APIs."
      }
    },
    {
      "@type": "Question",
      "name": "What skills does a backend developer already have for AI engineering?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "APIs, tests, deployment and monitoring carry over. What is new is retrieval over documents, tool calling, evaluating answers, and tracking cost and latency."
      }
    },
    {
      "@type": "Question",
      "name": "What should I build first to learn AI engineering?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A small service on an LLM API that answers questions from documents with sources, and a test set that shows where it fails."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- 15 November baseline: no test question matches this topic.
- AI summary of a web search tool, 15 November 2026, for the web search query: leaned on coderhouse.com, imaginarycloud.com, interviewkickstart.com, a TripleTen job ad and iu.org, and told the reader the gap is "machine learning theory, model training, and ML-specific tooling". That is the claim this article answers with job-ad data.
- First Monday check for the article question: 14 December 2026.

**Expected results (targets)**

- Target: indexed within 7 days.
- Target: 150 Search Console impressions in the first 60 days.
- Target: top 20 in Google Germany for "ai engineer" and top 10 for "ai engineer salary" by 31 March 2027 (section 3a, rows 19 and 20).
- Target: cited for the article question in at least one of ChatGPT, Perplexity or Google AI Overviews by 28 February 2027.
- Target: 3 confirmed waitlist signups with `utm_campaign=backend-developer-to-ai-engineer` by 31 March 2027.

**Tracking.** GSC page filter `/blog/backend-developer-to-ai-engineer`, query regex `ai engineer|backend.*ai|become.*ai`. Umami `cta_click` with `article=a04`. Waitlist source tag `utm_medium=article&utm_campaign=backend-developer-to-ai-engineer`; external links to the article carry the same `utm_campaign`. Monday AI check: article question.

---

### Article 5. Bildungsgutschein in English: How the Education Voucher Works for Developers in Germany

**Publication week:** 14 to 19 December 2026 (matches the [SEO content plan](seo-content-plan.md)). **Priority score:** 50 (volume 2, fit 5, feasibility 5). This is the English pillar of the voucher cluster and the owner of two #1 targets (section 3a, rows 1 and 2).

**Slug:** `bildungsgutschein-in-english`

**Meta title:** Bildungsgutschein in English: A Guide for Developers
**Meta description:** What a Bildungsgutschein is, who decides, what AZAV means and how the Agentur für Arbeit judges experienced developers. With links to the official rules.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| bildungsgutschein in english | Primary (section 3a, row 1) | 30 | 1 |
| bildungsgutschein courses in english | Secondary, one section (section 3a, row 2) | 40 | no value |
| bildungsgutschein | Secondary (loanword English speakers search) | 9,900 | 7 |
| bildungsgutschein berlin | Secondary | 140 | 8 |
| bildungsgutschein agentur für arbeit | Secondary | 5,400 | difficulty not pulled |
| education voucher germany | Secondary | unknown (not pulled) | unknown (not pulled) |
| bildungsgutschein englisch | Not a target: the live top 5 are language schools | 40 | 3 |

Live top 3, Google Germany, 15 November 2026 ([competitor keyword research](competitor-keywords.md)): "bildungsgutschein in english": digitalcareerinstitute.org (DA 32), startsteps.org (21), theberlinlife.com (16). "bildungsgutschein courses in english": digitalcareerinstitute.org (32), cybersteps.de (23), a reddit.com thread. datatalks.club has DA 34.

Serpstat cached SERP features: "bildungsgutschein englisch" shows related searches, People Also Ask and an AI Overview, with Reddit among social domains. "bildungsgutschein" shows People Also Ask, an AI Overview, related searches and bottom ads, with commercial intent.

**Current results, web search.** Query: "Bildungsgutschein in English guide education voucher Germany how it works". Date: 15 November 2026.

1. https://www.turingcollege.com/blogs/asdfad
2. https://www.turingcollege.com/blog/apply-for-an-education-voucher-in-germany
3. https://cybersteps.de/en/?p=9526
4. https://cybersteps.de/en/blog/what-is-a-bildungsgutschein/
5. https://codelabsacademy.com/blog/why-bildungsgutschein-the-benefits-of-germanys-education-voucher-system

Also returned: neuefische.de (several), careerfoundry.com, en.alfatraining.de, de.masterschool.com, digitalcareerinstitute.org.

**My angle to beat them.** Every result is a provider guide for career changers, and the AI summary of the web search tool noted that they give conflicting eligibility details and do not cite official pages. Mine is the only one written for people who already have a profession, it quotes the law that covers them (§ 81 Abs. 1a SGB III), it links every claim to arbeitsagentur.de or gesetze-im-internet.de, and it states my own program's funding in one neutral line. It also carries a dated list of voucher courses taught in English across providers, where competitors list only their own. Sourcing is the differentiator for both readers and models.

**Thesis.** The voucher is a discretionary decision about one question: is work realistic for this person without this course. Experienced developers can qualify, but they have to show the gap.

**Reader benefit.** The whole system on one page in English, with the German terms they see on forms, and links to four deeper articles.

**Problem it solves for the reader.** English-speaking developers in Germany hear about the voucher from colleagues and Reddit, meet German-only official pages, and get contradictory advice from provider blogs.

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=<slug>` (the slug above). Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** Readers who are registered or about to register with the Agentur join the waitlist of one program. Target: 6 confirmed signups with `utm_campaign=bildungsgutschein-in-english` by 31 March 2027.

**AI questions this article answers**

- "What is a Bildungsgutschein?"
- "Can I get a Bildungsgutschein as a foreigner or expat in Germany?"
- "Who decides on a Bildungsgutschein?"

Article question for the Monday check: "How does the Bildungsgutschein work for an experienced software developer in Germany?"

**Quotable answer block**

> A Bildungsgutschein is a voucher from the Agentur für Arbeit that pays the course fees for approved further training. The adviser decides case by case in a counselling appointment before the course starts, and both the provider and the course must be AZAV certified. Since 1 January 2025 the Agentur für Arbeit also handles the voucher for people at the Jobcenter.

Sources for the block: the BA Bildungsgutschein page, § 81 SGB III and the BMAS note of 19 December 2024, all linked in the [Berater objections research](berater-objections.md).

**Outline**

- H1: Bildungsgutschein in English: How the Education Voucher Works for Developers in Germany
- Answer block
- H2: What a Bildungsgutschein Pays For
- H2: Who Can Get One (unemployed, at risk of unemployment, and the § 82 route for employed people in one paragraph)
- H2: Who Decides and On What Basis (§ 81 Abs. 1, the necessity test, discretion)
- H2: What the Law Says About People Who Already Have a Profession (§ 81 Abs. 1a)
- H2: What AZAV Means and How to Check a Course (the provider and the course are both AZAV certified, Maßnahmenummer, mein NOW)
- H2: Agentur für Arbeit or Jobcenter (the split since 1 January 2025)
- H2: The Steps, From First Appointment to Course Start (short, links to article 7)
- H2: German Level and Courses Taught in English (short, links to article 8)
- H2: If the Answer Is No (short, links to article 9)
- H2: What Happens to Arbeitslosengeld During the Course (short, links to article 10)
- H2: Voucher Courses Taught in English (added for target row 2: a dated list by field with provider, length, language and level, links to articles 6 and 8)
- H2: DataTalks.Club Academy and the Bildungsgutschein (the neutral line "Designed for Bildungsgutschein funding (AZAV).", Join the Waitlist)
- H2: German Terms on Letters and Forms (a short glossary)
- H2: FAQ

**Internal links.** `/academy/bildungsgutschein/` twice (anchor "German Bildungsgutschein guide" and "Bildungsgutschein Leitfaden auf Deutsch"), both course pages, articles 7, 8, 9, 10.

**FAQ**

1. Can non-German citizens get a Bildungsgutschein? The rules in § 81 SGB III do not mention citizenship. What counts is that you are registered with the Agentur für Arbeit in Germany and that the adviser finds the training necessary.
2. Is there a legal right to a Bildungsgutschein? No. For further training of people who already have a profession it is a discretionary decision. You have a right to a decision that uses that discretion correctly.
3. Can I pay for DataTalks.Club Academy with a Bildungsgutschein? The programs are designed for Bildungsgutschein funding (AZAV). The Agentur für Arbeit decides on each voucher in a counselling appointment before the course starts.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is a Bildungsgutschein?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A Bildungsgutschein is a voucher from the Agentur für Arbeit that pays the course fees for approved further training. The adviser decides case by case in a counselling appointment before the course starts, and both the provider and the course must be AZAV certified."
      }
    },
    {
      "@type": "Question",
      "name": "Is there a legal right to a Bildungsgutschein?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. For further training of people who already have a profession it is a discretionary decision. You have a right to a decision that uses that discretion correctly."
      }
    },
    {
      "@type": "Question",
      "name": "Can I pay for DataTalks.Club Academy with a Bildungsgutschein?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The programs are designed for Bildungsgutschein funding (AZAV). The Agentur für Arbeit decides on each voucher in a counselling appointment before the course starts."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- 15 November baseline, test question 1: ChatGPT's sources were led by deinbildungsgutschein.de, joinmsit.de, ifadw.de, neuefische.de and spiced-academy.com. Perplexity cited several Turing College pages and a WBS comparison post, plus datatalks.club and the Meetup group. Google AI Overviews named Spiced, WBS Coding School, Le Wagon Berlin, Ironhack and TSA.
- AI summary of a web search tool, 15 November 2026, for the web search query: leaned on turingcollege.com, cybersteps.de, neuefische.de, careerfoundry.com and en.alfatraining.de, and warned that these are provider blogs with a commercial interest.
- First Monday check for the article question: 21 December 2026.

**Expected results (targets)**

- Target: indexed within 7 days.
- Target: top 3 in Google Germany by 31 January 2027 and #1 by 31 March 2027 for "bildungsgutschein in english" (30, difficulty 1) and "bildungsgutschein courses in english" (40) (section 3a, rows 1 and 2).
- Target: 400 Search Console impressions in the first 60 days.
- Target: an article or academy URL cited by Perplexity or ChatGPT for test question 1 by 1 February 2027.
- Target: 6 confirmed waitlist signups with `utm_campaign=bildungsgutschein-in-english` by 31 March 2027.

**Tracking.** GSC page filter `/blog/bildungsgutschein-in-english`, query regex `bildungsgutschein|education voucher`. Umami `cta_click` with `article=a05` and `target`. Waitlist source tag `utm_medium=article&utm_campaign=bildungsgutschein-in-english`; external links to the article carry the same `utm_campaign`. Monday AI check: article question plus test question 1.

---

### Article 6. AI Courses in Germany for Experienced Developers: What the Voucher Catalogue Offers in 2027

**Publication week:** 4 to 9 January 2027 (moved up from 25 January, because it owns a #1 target). **Priority score:** 25 (volume 1, fit 5, feasibility 5). Placed early as an exception explained in section 8.

**Slug:** `ai-courses-germany-experienced-developers`

**Meta title:** AI Courses in Germany for Experienced Developers (2027)
**Meta description:** Which AI courses in Germany ask for programming experience, how long they run, what language they use and how they are funded. Checked January 2027.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| ai course for experienced developers germany | Primary (section 3a, row 9) | unknown (no Serpstat row) | unknown (no Serpstat row) |
| ai course bildungsgutschein | Secondary, one H2 (section 3a, row 10) | unknown (no Serpstat row) | unknown (no Serpstat row) |
| ai bootcamp | Mention only (owned by `/academy/`) | 170 | 3 |
| ai bootcamp germany | Mention only (owned by article 11) | unknown (no Serpstat row) | unknown (no Serpstat row) |
| ai engineering bootcamp | Mention only (owned by `/academy/ai-engineering/`) | unknown (no Serpstat row) | unknown (no Serpstat row) |
| ki weiterbildung | German, not a target (German-course intent), one mention as the term used in the catalogue | 2,400 | 10 |

Live top 3, Google Germany, 15 November 2026 ([competitor keyword research](competitor-keywords.md)): "ai course for experienced developers germany": nobleprog.de, hlrs.de, wbscodingschool.com (DA 28), none with a page that matches the query. "ai course bildungsgutschein": iu-akademie.de (32), turingcollege.com (36), wbscodingschool.com (28).

Serpstat cached SERP features for "ai bootcamp": video and People Also Ask, no AI Overview in the stored snapshot, Reddit among social domains. "ki weiterbildung" shows an AI Overview.

How this avoids duplicating course intent: the course pages answer "what is this program". This article answers "which programs exist and how do they differ". The title has no city and no "best", and my own row is one line in a table.

**Current results, web search.** Query: "AI bootcamp Germany Bildungsgutschein English experienced developers 2026". Date: 15 November 2026.

1. https://www.turingcollege.com/blog/best-ai-bootcamps-germany-2026
2. https://info.lewagon.com/ai-data-academy?hsLang=en
3. https://www.turingcollege.com/blog/how-to-get-a-bildungsgutschein-in-2026-a-5-step-playbook
4. https://www.neuefische.de/en/community/career/11-best-ai-bootcamps-in-germany-for-2026-expert-picks
5. https://www.turingcollege.com/blog/best-programs-funded-with-bildungsgutschein

15 November Google Germany baseline for test question 1 ([domain and SEO plan](domain-and-seo-plan.md)): organic results were led by the WBS "best AI bootcamps" post, Spiced, Le Wagon, TSA, Ironhack and the WBS voucher page.

**My angle to beat them.** Every list is written by a provider that puts itself first. Mine is built from the BA catalogue: 2,217 AI voucher courses classified and 24 programs read in detail on 14 November 2026 ([supply, jobs and bootcamps research](supply-jobs-and-bootcamps.md)). It sorts by the one thing an experienced developer cares about, the entry level, and it shows my own program in the same columns as every other provider. It also credits strong competitors where the research found them (GFN, alfatraining, Turing College). A list that is fair to competitors is more likely to be quoted than one more "expert picks" page.

**Thesis.** The voucher catalogue has many AI courses and few for people who already ship code. Short German modules of 2 to 4 weeks teach coding agents well. Longer programs mostly start from beginner level or from classic machine learning.

**Reader benefit.** One table to filter by entry level, length, language and content, plus how to verify AZAV status in mein NOW.

**Problem it solves for the reader.** Experienced developers say voucher courses are for beginners. The complaint research quotes a reply on r/InformatikKarriere: "Sobald du mehr als 2-3 Jahre relevante BE hast ist das einfach nur Zeitverschwendung" ([voucher course complaints research](voucher-course-complaints.md)). They need a way to find the exceptions.

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=<slug>` (the slug above). Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** Readers for whom a full-time English program fits join the waitlist. Readers who need a different format find the alternatives in the table. Target: 6 confirmed signups with `utm_campaign=ai-courses-germany-experienced-developers` by 31 March 2027.

**AI questions this article answers**

- "What AI engineering courses in Berlin can I pay for with a Bildungsgutschein?" (test question 1)
- "Which AI bootcamps in Germany are for experienced developers?"
- "Which agentic engineering course is there for experienced developers in Germany?" (test question 2)

Article question for the Monday check: "Which AI courses in Germany are meant for experienced developers, not beginners?"

**Quotable answer block**

> For developers who already ship code, the voucher catalogue in Germany offers two kinds of AI courses: short German modules of 2 to 4 weeks on coding agents, and longer programs that mostly start from beginner level or from classic machine learning. English programs of about 3 months include Turing College AI Engineering, which asks for at least 1 year of Python or JavaScript, and Digitale Leute School AI Software Engineering, which also accepts beginners. DataTalks.Club Academy is a 3-month full-time live program in English for developers with 2+ years of experience. Start: April 2027, 15 seats, designed for Bildungsgutschein funding (AZAV).

Provider facts: checked 14 November 2026. The article shows the check date.

**Outline**

- H1: AI Courses in Germany for Experienced Developers: What the Voucher Catalogue Offers in 2027
- Answer block
- H2: How I Checked (BA catalogue, date, what was counted, link to the public research page)
- H2: Why Most AI Voucher Courses Are Not for Developers (14,559 voucher courses match "KI". Of 2,217 pulled, 924 target managers, office work and no-code automation, an approximate count)
- H2: Short Modules on Coding Agents (alfatraining, GFN, the IBB franchise: length, language, content)
- H2: Programs of About 3 Months in English (Turing College, Digitale Leute School)
- H2: Long Programs That Start from Beginner Level or Classic ML (named with their own entry-level wording)
- H2: The Table (provider, course, entry level, length, language, coding agents, evaluation, funding, date checked)
- H2: AI Courses and the Bildungsgutschein (added for target row 10: which of the listed courses are in the voucher catalogue, and how to read a catalogue entry)
- H2: Where DataTalks.Club Academy Fits and Where It Does Not (2+ years, Monday to Friday 09:00 to 16:30 Berlin time, English, Start: April 2027, designed for Bildungsgutschein funding (AZAV))
- H2: How to Check Any Course Yourself (mein NOW, Maßnahmenummer, the syllabus questions to ask)
- H2: FAQ

**Internal links.** `/academy/agentic-engineering/`, `/academy/ai-engineering/`, `/academy/bildungsgutschein/`, article 2 (to choose a direction), article 5 (how the voucher works), article 11 (the bootcamp list) once it is live.

**FAQ**

1. Are there voucher courses for developers with several years of experience? Yes, but few. Most are short German modules of 2 to 4 weeks. Longer programs mostly start from beginner level or from classic machine learning.
2. How do I check whether a course can be paid with a Bildungsgutschein? Look it up in mein NOW, the official course database of the Bundesagentur für Arbeit, and ask the provider for the Maßnahmenummer.
3. Can a Bildungsgutschein pay for DataTalks.Club Academy? The programs are designed for Bildungsgutschein funding (AZAV). The Agentur für Arbeit decides on each voucher in a counselling appointment before the course starts.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Are there Bildungsgutschein AI courses for developers with several years of experience?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, but few. Most are short German modules of 2 to 4 weeks. Longer programs mostly start from beginner level or from classic machine learning."
      }
    },
    {
      "@type": "Question",
      "name": "How do I check whether an AI course can be paid with a Bildungsgutschein?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Look it up in mein NOW, the official course database of the Bundesagentur für Arbeit, and ask the provider for the Maßnahmenummer."
      }
    },
    {
      "@type": "Question",
      "name": "Can a Bildungsgutschein pay for DataTalks.Club Academy?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The programs are designed for Bildungsgutschein funding (AZAV). The Agentur für Arbeit decides on each voucher in a counselling appointment before the course starts."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- 15 November baseline, test question 1: ChatGPT named Data Science Retreat, MSIT "AI for Developers" and Syntax Institut, with sources led by deinbildungsgutschein.de, joinmsit.de, ifadw.de, neuefische.de and spiced-academy.com. Perplexity recommended Turing College's AZAV AI Engineering program, did not name DataTalksClub Academy, and cited the Meetup group, datatalks.club, several Turing pages and a WBS comparison post. Google AI Overviews named Spiced, WBS Coding School, Le Wagon Berlin, Ironhack and TSA.
- AI summary of a web search tool, 15 November 2026, for test question 1: named Turing College AI Engineering first, then Masterschool and neue fische, leaning on turingcollege.com (six URLs), learn.masterschool.com, genaumeinkurs.de and neuefische.de.
- AI summary of a web search tool, 15 November 2026, for the query above: called Turing College the closest match for experienced developers and recommended checking mein NOW.
- First Monday check for the article question: 11 January 2027.

**Expected results (targets)**

- Target: indexed within 7 days.
- Target: top 3 in Google Germany by 31 January 2027 and #1 by 31 March 2027 for "ai course for experienced developers germany" (section 3a, row 9).
- Target: top 3 by 31 March 2027 for "ai course bildungsgutschein" (row 10). #1 is a stretch after that.
- Target: 500 Search Console impressions in the first 60 days.
- Target: the Academy named with the facts from the fact sheet for test question 1 in at least one of the five tools by 1 March 2027.
- Target: 6 confirmed waitlist signups with `utm_campaign=ai-courses-germany-experienced-developers` by 31 March 2027.

**Tracking.** GSC page filter `/blog/ai-courses-germany-experienced-developers`, query regex `ai bootcamp|ai course|ki weiterbildung|experienced`. Umami `cta_click` with `article=a06` and `target`. Waitlist source tag `utm_medium=article&utm_campaign=ai-courses-germany-experienced-developers`; external links to the article carry the same `utm_campaign`. Monday AI check: article question plus test questions 1 and 2. Refresh the table monthly and show the new check date.

---

### Article 7. How to Prepare for the Bildungsgutschein Appointment as an Experienced Developer

**Publication week:** 11 to 16 January 2027. **Priority score:** 45 (volume 3 after the German-term discount, fit 5, feasibility 3).

**Slug:** `bildungsgutschein-appointment-experienced-developers`

**Meta title:** Bildungsgutschein Appointment: Prep for Experienced Devs
**Meta description:** What the adviser has to decide, which documents to bring and how to answer "you are already qualified". Based on § 81 SGB III and BA guidance.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| bildungsgutschein beantragen | Primary (German term, English article) | 1,900 | 21 |
| bildungsgutschein voraussetzungen | Secondary | 1,600 | 38 |
| bildungsgutschein agentur für arbeit | Secondary | 5,400 | difficulty not pulled |
| bildungsgutschein jobcenter | Secondary | 1,600 | difficulty not pulled |
| how to get a bildungsgutschein | Secondary | unknown (not pulled) | unknown (not pulled) |

Serpstat cached SERP features: "bildungsgutschein beantragen" shows an AI Overview, related searches and People Also Ask, with YouTube among social domains. "bildungsgutschein voraussetzungen" shows People Also Ask, related searches and an AI Overview. Difficulty 38 on "voraussetzungen" is the highest in the voucher cluster, so that term is secondary and the German page carries it.

**Current results, web search.** Query: "how to get a Bildungsgutschein approved Agentur für Arbeit advisor conversation tips". Date: 15 November 2026.

1. https://www.neuefische.de/en/community/career/bildungsgutschein-unlock-your-potential-with-education
2. https://www.neuefische.de/en/community/career/how-hard-is-it-to-get-a-bildungsgutschein
3. https://cybersteps.de/en/?p=12292
4. https://www.neuefische.de/en/community/bootcamps-and-community/does-everyone-qualify-for-a-bildungsgutschein
5. https://cybersteps.de/en/?p=16049

Also returned: en.alfatraining.de, codelabsacademy.com, turingcollege.com (5-step playbook), de.masterschool.com, genaumeinkurs.de.

**My angle to beat them.** The AI summary of a web search tool found "little specific advice on advisor conversations" in these pages and conflicting processing times. They are written for career changers. Mine addresses the refusal that experienced people hear, "you are already qualified", with the BA's own wording of the necessity test, the paragraph of the law written for people with a profession, the Berlin 2026 planning document, and a concrete list of documents. All of it comes from the [Berater objections research](berater-objections.md), which uses primary sources only for legal rules.

**Thesis.** The adviser is not judging whether you are good. The adviser has to answer whether placement is realistic without this course. Prepare evidence for that question.

**Reader benefit.** A checklist of documents, the four arguments that match the legal test, and what to ask for if the answer is no.

**Problem it solves for the reader.** In one of my discovery interviews a test engineer with about 10 years of experience was refused at 4 or 5 appointments with "big experience, no need to study" ([Berater objections research](berater-objections.md), section 1). Experienced developers walk in unprepared for that.

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=<slug>` (the slug above). Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** Readers who intend to ask for a voucher for an AI program join the waitlist so they receive the course documents for their appointment. Target: 6 confirmed signups with `utm_campaign=bildungsgutschein-appointment-experienced-developers` by 31 March 2027.

**AI questions this article answers**

- "How do I get a Bildungsgutschein approved?"
- "What do I say to my Agentur für Arbeit adviser to get a Bildungsgutschein?"
- "Can an experienced developer get a Bildungsgutschein?"

Article question for the Monday check: "How does an experienced software developer get a Bildungsgutschein approved?"

**Quotable answer block**

> To get a Bildungsgutschein you need a counselling appointment at the Agentur für Arbeit before the course starts, and the adviser must find that the training is necessary for you to get work. Experienced developers are often told they are already qualified, so bring 5 to 10 current job ads that ask for skills you do not have and a dated list of unsuccessful applications. § 81 Abs. 1a SGB III also recognises necessity when added skills improve your employability.

**Outline**

- H1: How to Prepare for the Bildungsgutschein Appointment as an Experienced Developer
- Answer block
- H2: What the Adviser Has to Decide (the necessity test, quoted from the BA guidance and the Ludwigsburg FAQ)
- H2: Why Experienced Developers Hear "You Are Already Qualified"
- H2: The Paragraph Written for People Who Already Have a Profession (§ 81 Abs. 1a)
- H2: What the Berlin 2026 Plan Says About IT (deepening existing skills at expert and specialist level)
- H2: What to Bring (job ads with date and source, rejections or an application list, CV, a short note on the gap, course documents)
- H2: How to Describe the Course (further training that adds skills, not retraining for a new profession)
- H2: Things Advisers Sometimes Say That the Rules Do Not Mention (5 years of work in Germany, taxes paid, "our office does not give vouchers")
- H2: What Not to Do (do not enrol or quit a job on the assumption that a voucher comes, per Merkblatt 6)
- H2: If You Are Employed (§ 82 SGB III in one paragraph, link to the BA page)
- H2: DataTalks.Club Academy and the Bildungsgutschein (the neutral line "Designed for Bildungsgutschein funding (AZAV).", Join the Waitlist)
- H2: FAQ

**Internal links.** `/academy/bildungsgutschein/` (the German page has the same guide in German for the adviser), article 5 (overview), article 9 (if refused), article 8 (German level), both course pages.

**FAQ**

1. Do I need to pick a course before the appointment? You can go without one, but a specific course with a written offer makes the conversation concrete. The appointment must take place before the course starts.
2. Can the course provider apply for me? No. BA guidance says a provider must not file the application under a power of attorney. A provider can give you documents and a draft letter that you sign and file yourself.
3. Should I go to the Jobcenter instead? If you receive Arbeitslosengeld, your contact is the Agentur für Arbeit. Since 1 January 2025 the Agentur also decides on the voucher for Jobcenter clients, who are referred there.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Can an experienced software developer get a Bildungsgutschein?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, it is possible, but it is a discretionary decision. The adviser must find that the training is necessary for you to get work. § 81 Abs. 1a SGB III also recognises necessity when added skills improve your employability."
      }
    },
    {
      "@type": "Question",
      "name": "What should I bring to a Bildungsgutschein appointment?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Bring 5 to 10 current job ads that ask for skills you do not have, a dated list of unsuccessful applications or rejection letters, your CV, and a short note on the skills gap."
      }
    },
    {
      "@type": "Question",
      "name": "Can the course provider apply for a Bildungsgutschein for me?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. Guidance from the Bundesagentur für Arbeit says a provider must not file the application under a power of attorney. A provider can give you documents and a draft letter that you sign and file yourself."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- AI summary of a web search tool, 15 November 2026, for the query above: leaned on cybersteps.de, turingcollege.com, neuefische.de, codelabsacademy.com and help.de.masterschool.com, and said it found general process guidance but little about the conversation itself. It cited conflicting approval times (1 to 3 weeks versus 4 to 8 weeks).
- First Monday check for the article question: 18 January 2027.

**Expected results (targets)**

- Target: indexed within 7 days.
- Target: 400 Search Console impressions in the first 60 days.
- Target: cited for the article question in at least one of ChatGPT, Perplexity or Google AI Overviews by 15 March 2027.
- Target: 6 confirmed waitlist signups with `utm_campaign=bildungsgutschein-appointment-experienced-developers` by 31 March 2027.

**Tracking.** GSC page filter `/blog/bildungsgutschein-appointment-experienced-developers`, query regex `bildungsgutschein.*(beantragen|voraussetzungen|appointment|approved|berater|agentur|jobcenter)`. Umami `cta_click` with `article=a07`. Waitlist source tag `utm_medium=article&utm_campaign=bildungsgutschein-appointment-experienced-developers`; external links to the article carry the same `utm_campaign`. Monday AI check: article question plus test question 3, because German-language answers lean on the same sources.

---

### Article 8. Do You Need B2 German for a Bildungsgutschein If the Course Is in English

**Publication week:** 18 to 23 January 2027. **Priority score:** 40 (volume 2, fit 5, feasibility 4), rescored on "bildungsgutschein courses in english" after "weiterbildung auf englisch" was rejected on intent (section 8).

**Slug:** `bildungsgutschein-b2-german-english-course`

**Meta title:** B2 German for a Bildungsgutschein? English Courses in 2027
**Meta description:** Since September 2026 certifier guidance says funded training needs German "as a rule B2". What that means for English courses and what to bring.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| bildungsgutschein courses in english | Scoring keyword. Owned by article 5 (section 3a, row 2); this article answers the German-level question inside it and links up | 40 | no value |
| bildungsgutschein englisch | Not a target: the live top 5 are language schools | 40 | 3 |
| weiterbildung auf englisch | Rejected on intent: the live results are dictionary pages (pons, linguee) | 390 | 7 |
| bildungsgutschein voraussetzungen | Secondary | 1,600 | 38 |
| english courses bildungsgutschein | Secondary | unknown (no Serpstat row) | unknown (no Serpstat row) |
| bildungsgutschein b2 | Secondary | unknown (not pulled) | unknown (not pulled) |

Serpstat cached SERP features: "bildungsgutschein englisch" shows an AI Overview and Reddit among social domains, which fits the Reddit threads in my research.

**Current results, web search.** Query: "Bildungsgutschein English course B2 German required 2026". Date: 15 November 2026.

1. https://cybersteps.de/en/?p=11391
2. https://www.wbstraining.de/weiterbildung-sprachen/spanisch
3. https://www.match-talent.org/learn-more/faq
4. https://www.studysmarter.de/s/weiterbildung/k/wirtschaftsenglisch-advanced-business-english-b2-2-lecturio-gmbh/
5. https://match-doctors.com/en/blog-match-doctors-by-lingoda/what-is-a-bildungsgutschein-for-doctors

**My angle to beat them.** This is the weakest result set of the ten: language course listings and one provider list, none of which mentions Umsetzungshinweis 2/2026. The AI summary of a web search tool concluded there is "no official rule" and did not find the September 2026 guidance at all. My research has the exact quotes, the date it took effect, the BA language-level table with its "slightly below" exception, and the Krefeld planning sentence about English courses ([B2 German rule research](b2-german-rule.md)). Publishing the primary sources in English fills a real gap.

**Thesis.** There is no statute that sets a German level for the voucher. There is certifier guidance since 10 September 2026 that says "as a rule B2", advisers do cite it, and approval of an English course depends on showing that the target jobs hire in English.

**Reader benefit.** The reader learns where they stand by German level (B2 or better, B1, A2 and below) and what evidence helps at each level, without false hope.

**Problem it solves for the reader.** English-speaking developers are told "learn German first" and cannot tell whether that is a rule or one adviser's view. Two of my discovery interviews report exactly this ([B2 German rule research](b2-german-rule.md), section 3).

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=<slug>` (the slug above). Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** The first target segment in the research is developers with B2 or better German who want an English AI course. This article attracts them and tells them so. Target: 5 confirmed signups with `utm_campaign=bildungsgutschein-b2-german-english-course` by 31 March 2027.

**AI questions this article answers**

- "Do I need B2 German to get a Bildungsgutschein?"
- "Can I get a Bildungsgutschein for a course taught in English?"
- "Does the Agentur für Arbeit fund English-language courses?"

Article question for the Monday check: "Do I need B2 German to get a Bildungsgutschein for a course taught in English?"

**Quotable answer block**

> No law sets a German level for a Bildungsgutschein. Since 10 September 2026, guidance for AZAV certifiers (Umsetzungshinweis 2/2026) says participants in funded further training need sufficient German, as a rule B2, and advisers can cite it even when the course is taught in English. The decision stays individual, so bring proof that your target jobs hire in English and, if your German is below B2, a plan for learning German alongside the course.

**Outline**

- H1: Do You Need B2 German for a Bildungsgutschein If the Course Is in English
- Answer block
- H2: What Changed on 10 September 2026 (the two quoted sentences, who the guidance addresses)
- H2: What "As a Rule" Means
- H2: What the Adviser's Own Guidance Says (no fixed level in the BA instructions valid from 1 January 2026)
- H2: The BA Language Table and the "Slightly Below" Exception
- H2: When an English Course Can Be Approved (the Krefeld sentence and its converse)
- H2: What Berlin's 2026 Plan Says About German and English in IT
- H2: Where You Stand by German Level (B2 or better, B1, A2 and below)
- H2: What to Bring (English or German-optional job ads, proof of English, a German plan)
- H2: How Many Tech Jobs in Berlin Work in English (67.1% of Berlin startups say they work in English, Deutscher Startup Monitor 2025. 31% of AI developer job ads in Germany were written in English, IW study published December 2024, an average of first quarters 2019 to 2024. Both from the [German vs skills research](german-vs-skills.md))
- H2: What I Decided for DataTalks.Club Academy (the program stays in English. No voucher is promised to people at A2 and below)
- H2: FAQ

**Internal links.** `/academy/bildungsgutschein/`, article 5, article 7 (general preparation), article 9 (written decision and appeal), both course pages.

**FAQ**

1. Is B2 German a legal requirement for a Bildungsgutschein? No. It appears in guidance for AZAV certifiers as "as a rule B2". The adviser decides each case.
2. Can a course taught in English be funded? Yes, such courses exist in the BA catalogue. Approval depends on whether the jobs you are aiming for hire in English.
3. My German is B1. Is there a chance? It depends on the adviser. The BA language table says a level slightly below the stated one can be enough, for example with German classes alongside.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Is B2 German a legal requirement for a Bildungsgutschein?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. No law sets a German level. Since 10 September 2026, guidance for AZAV certifiers says participants in funded further training need sufficient German, as a rule B2. The adviser decides each case."
      }
    },
    {
      "@type": "Question",
      "name": "Can a course taught in English be funded with a Bildungsgutschein?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, such courses exist in the catalogue of the Bundesagentur für Arbeit. Approval depends on whether the jobs you are aiming for hire in English."
      }
    },
    {
      "@type": "Question",
      "name": "Can I get a Bildungsgutschein with B1 German?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "It depends on the adviser. The language table of the Bundesagentur für Arbeit says a level slightly below the stated one can be enough, for example with German classes alongside."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- AI summary of a web search tool, 15 November 2026, for the query above: said it found "no official rule tying a Bildungsgutschein for an English course to a specific German level in 2026", leaning on cybersteps.de, match-talent.org, careerfoundry.com, berlitz.com and wbstraining.de. It did not surface Umsetzungshinweis 2/2026.
- First Monday check for the article question: 25 January 2027.

**Expected results (targets)**

- Target: indexed within 7 days.
- Target: top 10 in Google Germany for "bildungsgutschein b2" style queries in English by 31 March 2027.
- Target: 250 Search Console impressions in the first 60 days.
- Target: cited for the article question in at least one of ChatGPT, Perplexity or Google AI Overviews by 15 March 2027. This is the article with the best odds, because no competing page states the rule.
- Target: 5 confirmed waitlist signups with `utm_campaign=bildungsgutschein-b2-german-english-course` by 31 March 2027.

**Tracking.** GSC page filter `/blog/bildungsgutschein-b2-german-english-course`, query regex `b2|englisch|english|deutschkenntnisse`. Umami `cta_click` with `article=a08`. Waitlist source tag `utm_medium=article&utm_campaign=bildungsgutschein-b2-german-english-course`; external links to the article carry the same `utm_campaign`. Monday AI check: article question.

---

### Article 9. Bildungsgutschein Refused: What Experienced Developers Can Do Next

**Publication week:** 8 to 13 February 2027. **Priority score:** 15 (volume 1, fit 5, feasibility 3). No-volume exception explained in section 8.

**Slug:** `bildungsgutschein-refused`

**Meta title:** Bildungsgutschein Refused: Written Decision and Appeal
**Meta description:** An oral no is not a decision you can appeal. How to ask for a written Bescheid, when a Widerspruch is due and what else you can try.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| bildungsgutschein abgelehnt | Primary (German term, English article) | unknown (not pulled) | unknown (not pulled) |
| bildungsgutschein widerspruch | Secondary | unknown (not pulled) | unknown (not pulled) |
| bildungsgutschein rejected | Secondary | unknown (not pulled) | unknown (not pulled) |
| bildungsgutschein voraussetzungen | Secondary | 1,600 | 38 |

**Current results, web search.** Query: "Bildungsgutschein rejected what to do Widerspruch appeal Agentur für Arbeit". Date: 15 November 2026.

1. https://www.turingcollege.com/blog/bildungsgutschein-rejected-how-to-appeal-and-win
2. https://www.wbstraining.de/ratgeber/artikel/bildungsgutschein-abgelehnt/
3. https://en.alfatraining.de/info/ratgeber/Bildungsgutschein_abgelehnt
4. https://www.gegen-hartz.de/?p=224751
5. https://cybersteps.de/en/?p=12292

Also returned: genaumeinkurs.de (Widerspruch template), skill-sprinters.de (three pages), a Bavarian court ruling on gesetze-bayern.de.

**My angle to beat them.** Competitors are stronger here than in article 8: Turing College, WBS and alfatraining each have a dedicated page, and one title promises "how to appeal and win". I do not promise a win. My page covers what theirs skip: the oral no that never becomes a written decision, the three refusal lines experienced developers hear that the rules do not mention, the duty to give reasons in § 35 SGB X, and the plain statement that a provider cannot file for you. It quotes Merkblatt 6 and § 84 SGG directly.

**Thesis.** A refusal in conversation is not the end, and it is nothing you can contest at that point. The path is a written application, a written Bescheid with reasons, and then a decision about a Widerspruch within one month.

**Reader benefit.** A sequence of steps with deadlines and the exact documents, and a sober view of alternatives.

**Problem it solves for the reader.** Refusal of experienced people is the main conversion risk named in the interview research ([Berater objections research](berater-objections.md), section 1). People leave the appointment with an oral no and give up.

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=<slug>` (the slug above). Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** Readers who still want an AI program after a refusal join the waitlist to get the course documents for a new application. Target: 4 confirmed signups with `utm_campaign=bildungsgutschein-refused` by 31 March 2027.

**AI questions this article answers**

- "My Bildungsgutschein was refused. What can I do?"
- "How long do I have to appeal a Bildungsgutschein rejection?"
- "Can I ask for a different adviser at the Agentur für Arbeit?"

Article question for the Monday check: "My Bildungsgutschein was refused because I am already qualified. What can I do?"

**Quotable answer block**

> An oral no from your adviser is not a decision you can appeal. File a written application and ask for a written Bescheid with reasons. If you disagree with the Bescheid, you can file a Widerspruch within one month of receiving it, at the Agentur für Arbeit that issued it.

Sources: Merkblatt 6 (sections 8 and 9), § 16 SGB I, § 35 SGB X, § 84 SGG, all linked in the [Berater objections research](berater-objections.md).

**Outline**

- H1: Bildungsgutschein Refused: What Experienced Developers Can Do Next
- Answer block
- H2: Why Experienced Developers Get Refused (the necessity test in one paragraph, link to article 7)
- H2: An Oral No Is Not a Decision
- H2: How to Get a Written Bescheid (written application, no special form needed, § 16 SGB I)
- H2: What the Bescheid Has to Contain (reasons, and for discretionary decisions the points considered, § 35 SGB X)
- H2: Widerspruch: Deadline, Form and Where to Send It (one month, in writing or in person for the record, follow the instructions on the Bescheid)
- H2: Three Reasons the Rules Do Not Mention (5 years of work in Germany, taxes paid, "our office does not give vouchers")
- H2: If the Reason Is Your German Level (link to article 8)
- H2: Other Things You Can Try (a further appointment, a review by a team lead, the § 82 route if you find a job. No sourced legal right to a new adviser)
- H2: What a Course Provider Can and Cannot Do for You
- H2: FAQ

**Internal links.** `/academy/bildungsgutschein/`, article 7 (preparation), article 8 (German level), article 5 (overview), both course pages in the closing section.

**FAQ**

1. How long do I have to file a Widerspruch? One month from the day you receive the written Bescheid, unless the instructions on the Bescheid say otherwise.
2. Can I appeal if the adviser only said no in the appointment? Not yet. Without a written decision there is nothing to appeal. File a written application so that a written Bescheid has to be issued.
3. Can I ask for a different adviser? You can ask for a further appointment or a review by a team lead. The rules name no legal right to a new adviser.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What can I do if my Bildungsgutschein was refused?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "An oral no from your adviser is not a decision you can appeal. File a written application and ask for a written Bescheid with reasons. If you disagree with the Bescheid, you can file a Widerspruch within one month of receiving it."
      }
    },
    {
      "@type": "Question",
      "name": "How long do I have to file a Widerspruch against a refused Bildungsgutschein?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "One month from the day you receive the written Bescheid, unless the instructions on the Bescheid say otherwise."
      }
    },
    {
      "@type": "Question",
      "name": "Can I ask for a different adviser at the Agentur für Arbeit?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "You can ask for a further appointment or a review by a team lead. The rules name no legal right to a new adviser."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- AI summary of a web search tool, 15 November 2026, for the query above: leaned on turingcollege.com, wbstraining.de, en.alfatraining.de, cybersteps.de and genaumeinkurs.de. It gave the one-month deadline, mentioned an "Ombudsmann" at the Bundesagentur and a three-month decision time for the appeal, and said it found no current official source.
- First Monday check for the article question: 15 February 2027.

**Expected results (targets)**

- Target: indexed within 7 days.
- Target: 200 Search Console impressions in the first 60 days.
- Target: cited for the article question in at least one of ChatGPT, Perplexity or Google AI Overviews by 31 March 2027.
- Target: 4 confirmed waitlist signups with `utm_campaign=bildungsgutschein-refused` by 31 March 2027.

**Tracking.** GSC page filter `/blog/bildungsgutschein-refused`, query regex `abgelehnt|widerspruch|rejected|refused|denied`. Umami `cta_click` with `article=a09`. Waitlist source tag `utm_medium=article&utm_campaign=bildungsgutschein-refused`; external links to the article carry the same `utm_campaign`. Monday AI check: article question.

---

### Article 10. Arbeitslosengeld During Full-Time Training: What Happens to Your ALG I

**Publication week:** 1 to 6 February 2027 (moved up from 22 February). **Priority score:** 16 (volume 2 after the German-term discount, fit 4, feasibility 2). Exception explained in section 8.

**Slug:** `alg-1-during-training`

**Meta title:** ALG I During Full-Time Training with a Bildungsgutschein
**Meta description:** If you start approved training on Arbeitslosengeld, the benefit usually continues. How § 148 SGB III counts course days, with a worked example.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| arbeitslosengeld weiterbildung | Primary (German term, English article; section 3a, row 24) | 480 | 15 |
| arbeitslosengeld bei weiterbildung | Secondary | unknown (not pulled) | unknown (not pulled) |
| weiterbildung mit bildungsgutschein | Secondary | 880 | difficulty not pulled |
| bildungsgutschein | Secondary | 9,900 | 7 |

Live top 3, Google Germany, 15 November 2026 ([competitor keyword research](competitor-keywords.md)): arbeitsagentur.de (DA 70), mein-now.de, dekra-akademie.de.

**Current results, web search.** Query: "Arbeitslosengeld during Weiterbildung Bildungsgutschein unemployment benefit while studying full-time Germany". Date: 15 November 2026.

1. https://www.deutschland.de/de/topic/leben/gesellschaft-und-integration/deutsches-sozialsystem-arbeit
2. https://verwaltung.bund.de/leistungsverzeichnis/DE/leistung/99007025017000
3. https://www.arbeitsagentur.de/karriere-und-weiterbildung/bildungsgutschein
4. https://www.service.bremen.de/dienstleistungen/bildungsgutschein-beantragen-11545
5. https://www.bundestag.de/resource/blob/906956/WD-6-047-22-pdf.pdf

Also returned: wbstraining.de (two guides on Arbeitslosengeld during training), skill-sprinters.de, genaumeinkurs.de.

**My angle to beat them.** Official German pages own the top, and arbeitsagentur.de (DA 70) holds position 1. No returned page explains the counting rule in English with a worked example for a 3-month course. That narrow English answer is the way in: the target is top 3 by 31 March 2027, with #1 a stretch after that, plus an AI citation and a page other articles link to. This is the weakest ranking target in the plan.

**Thesis.** Approved training does not stop Arbeitslosengeld and uses up the remaining entitlement at half speed. That makes 3 months of full days affordable for someone with enough months left, and it only applies to training that the Agentur approves.

**Reader benefit.** They can calculate their own remaining entitlement after a course with one formula.

**Problem it solves for the reader.** The persona research lists "cannot lose half a year on studying" and the fear that ALG I runs out during a course ([persona research](persona.md); [laid-off developers and Agentur research](laid-off-developers-and-agentur.md), section 3.2).

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=<slug>` (the slug above). Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** Readers who see that the timing works for an April 2027 start join the waitlist. Target: 2 confirmed signups with `utm_campaign=alg-1-during-training` by 31 March 2027.

**AI questions this article answers**

- "Do I keep Arbeitslosengeld during a Bildungsgutschein course?"
- "Does a Weiterbildung extend my ALG I?"
- "Can I study full time while on unemployment benefit in Germany?"

Article question for the Monday check: "What happens to my Arbeitslosengeld I during a full-time Bildungsgutschein course?"

**Quotable answer block**

> If you receive Arbeitslosengeld I and start approved further training with a Bildungsgutschein, the benefit usually continues during the course. Under § 148 Abs. 1 Nr. 7 SGB III, two days of training use up one day of your remaining entitlement. Example: with 180 days left, a course of 120 days uses 60 days, and 120 remain.

Source for the block: § 148 Abs. 1 Nr. 7 SGB III, as summarised in the [laid-off developers and Agentur research](laid-off-developers-and-agentur.md), section 3.2.

**Outline**

- H1: Arbeitslosengeld During Full-Time Training: What Happens to Your ALG I
- Answer block
- H2: Does Arbeitslosengeld Continue During Approved Training (quoted from the BA Bildungsgutschein page)
- H2: How Course Days Count Against Your Entitlement (§ 148 Abs. 1 Nr. 7, the worked example, a second example for a 3-month course)
- H2: What "Approved" Means (the voucher comes first. Training you start on your own is a different case)
- H2: What You Do Not Get (the extra Weiterbildungsgeld in § 87a SGB III is only for retraining toward a vocational degree, per the [market sizing research](market-sizing.md), section 3.4)
- H2: What to Ask Your Adviser Before You Start (remaining days in writing, start and end dates)
- H2: If Your ALG I Ends Before the Course Does (ask the Agentur. No promise of an automatic longer benefit)
- H2: Planning Backwards from an April 2027 Start
- H2: FAQ

**Internal links.** `/academy/bildungsgutschein/`, article 5 (overview), article 7 (the appointment), both course pages in the planning section.

**FAQ**

1. Do I keep Arbeitslosengeld during a course paid by a Bildungsgutschein? Usually yes. The Bundesagentur für Arbeit states that the benefit usually continues when you start approved further training while receiving Arbeitslosengeld.
2. Does the course use up my entitlement? Yes, at half speed. Two days of approved training use up one day of remaining Arbeitslosengeld I.
3. Is there an extra monthly payment for taking a course? Not for this kind of further training. The extra Weiterbildungsgeld applies to retraining toward a vocational degree.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Do I keep Arbeitslosengeld during a course paid by a Bildungsgutschein?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Usually yes. The Bundesagentur für Arbeit states that the benefit usually continues when you start approved further training while receiving Arbeitslosengeld."
      }
    },
    {
      "@type": "Question",
      "name": "Does a Bildungsgutschein course use up my Arbeitslosengeld I entitlement?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, at half speed. Under § 148 Abs. 1 Nr. 7 SGB III, two days of approved training use up one day of remaining Arbeitslosengeld I. With 180 days left, a course of 120 days uses 60 days, and 120 remain."
      }
    },
    {
      "@type": "Question",
      "name": "Is there an extra monthly payment for taking a further training course?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Not for this kind of further training. The extra Weiterbildungsgeld applies to retraining toward a vocational degree."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- AI summary of a web search tool, 15 November 2026, for the query above: leaned on arbeitsagentur.de, wbstraining.de, deutschland.de, verwaltung.bund.de and skill-sprinters.de. It stated the half-speed rule.
- First Monday check for the article question: 8 February 2027.

**Expected results (targets)**

- Target: indexed within 7 days.
- Target: 150 Search Console impressions in the first 60 days.
- Target: top 3 in Google Germany for "arbeitslosengeld weiterbildung" (480, difficulty 15) by 31 March 2027 (section 3a, row 24). #1 against arbeitsagentur.de is a stretch after that.
- Target: cited for the article question in at least one of ChatGPT, Perplexity or Google AI Overviews by 31 March 2027.
- Target: 2 confirmed waitlist signups with `utm_campaign=alg-1-during-training` by 31 March 2027.

**Tracking.** GSC page filter `/blog/alg-1-during-training`, query regex `arbeitslosengeld|alg|unemployment benefit`. Umami `cta_click` with `article=a10`. Waitlist source tag `utm_medium=article&utm_campaign=alg-1-during-training`; external links to the article carry the same `utm_campaign`. Monday AI check: article question.

---

### Article 11. AI Bootcamps in Germany in 2027: Which Ones Are Built for Experienced Developers

**Publication week:** 25 to 30 January 2027. **Priority score:** 45 (volume 3, fit 5, feasibility 3). New brief, added because no article covered the bootcamp comparison query in the target table (section 3a, row 11).

**Slug:** `ai-bootcamps-germany-experienced-developers`

**Meta title:** AI Bootcamps in Germany 2027: A List for Experienced Devs
**Meta description:** AI bootcamps in Germany compared by entry level, length, language and format. Most are for career starters. Which ones fit developers who already code.

**Keywords (Serpstat `g_de`, 15 November 2026)**

| Keyword | Role | Volume | Difficulty |
| --- | --- | --- | --- |
| ai bootcamp germany | Primary (section 3a, row 11) | unknown (no Serpstat row) | unknown (no Serpstat row) |
| artificial intelligence bootcamp | Secondary, the measured variant used for the volume score | 170 | no value |
| ai engineering bootcamp | Secondary, mention only (owned by `/academy/ai-engineering/`) | unknown (no Serpstat row) | unknown (no Serpstat row) |
| ai bootcamp | Mention only (owned by `/academy/`) | 170 | 3 |
| ai bootcamp berlin | Mention only, as anchor text of the link to `/academy/` | unknown (no Serpstat row) | unknown (no Serpstat row) |
| coding bootcamp germany | Context, not a target (beginner intent) | 30 | 16 |

Serpstat positions for the measured variant "artificial intelligence bootcamp" (15 November 2026): ironhack.com at 3 with its Berlin city page, neuefische.de at 12 with a "10 best AI bootcamps 2026" list post. A list post already ranks on page two for this term with a domain of about the same authority as mine.

How this avoids duplicating course intent: `/academy/` owns "ai bootcamp" and "ai bootcamp berlin". This article has no city in its title or H1, compares providers and sends the reader to `/academy/` with the anchor "AI bootcamp in Berlin for experienced developers". Article 6 covers courses in the voucher catalogue; this one covers bootcamps as a format, whatever the funding.

**Current results, live Google Germany.** Query: "ai bootcamp germany". Date: 15 November 2026. Source: the live top 5 in the [competitor keyword research](competitor-keywords.md) (Google Germany, desktop), with Moz DA.

1. lewagon.com (DA 59)
2. wbscodingschool.com (DA 28), the list post `/blog/best-ai-bootcamps-germany/`
3. artificialintelligencebootcamp.de (DA 8)
4. ironhack.com (DA 58)
5. neuefische.de (DA 32)

The AI Overview for this query cited artificialintelligencebootcamp.de, lewagon.com, spiced-academy.com, ironhack.com and hpi.de. The Academy was not named.

**My angle to beat them.** Position 2 is a list post on a domain with less authority than mine (DA 28 against 34), so a list post can rank here. Every existing list is written by a school that puts itself first and mixes career starters with working developers. Mine sorts by entry level, which is the one column an experienced developer needs, and it states lengths as the providers publish them: Spiced Academy and neue fische run 32-week programs for career starters, Ironhack runs 9 weeks and Le Wagon 2 months, while Turing College and Digitale Leute School address people who already code ([competitor keyword research](competitor-keywords.md), section 7). The two sites that lead "ai bootcamp" sell 5-day no-code and finance bootcamps, which the article names as a different product.

**Thesis.** "AI bootcamp" in Germany mostly means a long program for career starters or a short no-code course. A developer with several years of experience needs a shorter, deeper format, and only a few programs offer it.

**Reader benefit.** One table to pick from in five minutes: who each bootcamp is for, how long it runs, in which language and in which format.

**Problem it solves for the reader.** Experienced developers search "AI bootcamp", land on beginner programs of 32 weeks, and conclude that bootcamps are not for them. The complaint research quotes the same view for voucher courses: "Sobald du mehr als 2-3 Jahre relevante BE hast ist das einfach nur Zeitverschwendung" ([voucher course complaints research](voucher-course-complaints.md)).

**Primary CTA and KPI.** One primary CTA, "Join the Waitlist", after the answer block and at the end of the article, linking to the waitlist form with `utm_source=article&utm_medium=article&utm_campaign=ai-bootcamps-germany-experienced-developers`. Primary KPI: confirmed voucher-eligible waitlist signups with this article's slug as `utm_campaign`.

**Waitlist goal.** Readers with 2+ years of experience who want a full-time program in English join the waitlist. Career starters get pointed to the programs built for them and to the free Zoomcamps. Target: 5 confirmed signups with `utm_campaign=ai-bootcamps-germany-experienced-developers` by 31 March 2027.

**AI questions this article answers**

- "What are the best AI bootcamps in Germany?"
- "Is there an AI bootcamp in Germany for experienced developers?"
- "How long is an AI bootcamp in Germany?"

Article question for the Monday check: "Which AI bootcamps in Germany are built for experienced developers?"

**Quotable answer block**

> Most AI bootcamps in Germany are built for career starters: Spiced Academy and neue fische run 32-week programs, Ironhack runs 9 weeks and Le Wagon 2 months. Turing College and Digitale Leute School address people who already code. DataTalks.Club Academy is a 3-month full-time live program in English for developers with 2+ years of experience, with 15 seats. Start: April 2027, designed for Bildungsgutschein funding (AZAV).

Provider facts: checked 15 November 2026. The article shows the check date. One line after the block links `/academy/` and the waitlist.

**Outline**

- H1: AI Bootcamps in Germany in 2027: Which Ones Are Built for Experienced Developers
- Answer block
- H2: What "AI Bootcamp" Means in Germany (long career-starter programs, short no-code courses, programs for working developers)
- H2: The Table (provider, program, entry level, length, language, format, city or online, date checked)
- H2: AI Bootcamps for Career Starters (named with their own entry-level wording)
- H2: AI Bootcamps for Developers Who Already Code
- H2: Short Courses and Workshops (5-day and 2 to 5 day formats, what they cover and what they leave out)
- H2: How to Choose by Experience Level (under 2 years, 2+ years, team leads)
- H2: AI Bootcamps in Berlin (one paragraph, links to `/academy/` with the anchor "AI bootcamp in Berlin for experienced developers")
- H2: Where DataTalks.Club Academy Fits (2+ years, Monday to Friday 09:00 to 16:30 Berlin time, 3 months, English, Berlin or live online, 15 seats, Start: April 2027, designed for Bildungsgutschein funding (AZAV))
- H2: Questions to Ask Any Bootcamp Before You Sign (entry level of the group, who teaches, group size, what you build)
- H2: FAQ

**Internal links.** `/academy/` ("AI bootcamp in Berlin for experienced developers"), `/academy/ai-engineering/` ("AI Engineering program"), `/academy/agentic-engineering/` ("Agentic Engineering program"), article 6 (courses in the voucher catalogue), article 2 (to choose a direction), article 5 (how the voucher works).

**FAQ**

1. Are AI bootcamps in Germany only for beginners? No, but most are. Several run 32 weeks and start from career-starter level. A few programs are built for developers who already code.
2. How long does an AI bootcamp in Germany take? From 5 days for short courses to 32 weeks for career-starter programs. Programs for experienced developers run about 3 months.
3. Is DataTalks.Club Academy an AI bootcamp? It is a 3-month full-time live program in English for developers with 2+ years of experience, with two programs, Agentic Engineering and AI Engineering. Start: April 2027.

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Are AI bootcamps in Germany only for beginners?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No, but most are. Several run 32 weeks and start from career-starter level. A few programs are built for developers who already code."
      }
    },
    {
      "@type": "Question",
      "name": "How long does an AI bootcamp in Germany take?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "From 5 days for short courses to 32 weeks for career-starter programs. Programs for experienced developers run about 3 months."
      }
    },
    {
      "@type": "Question",
      "name": "Is DataTalks.Club Academy an AI bootcamp?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "It is a 3-month full-time live program in English for developers with 2+ years of experience, with two programs, Agentic Engineering and AI Engineering. Start: April 2027."
      }
    }
  ]
}
</script>
```

**Sources AI tools cite today**

- Google AI Overview, Germany, 15 November 2026, for "ai bootcamp germany": cited artificialintelligencebootcamp.de, lewagon.com, spiced-academy.com, ironhack.com and hpi.de. For "ai bootcamp": artificialintelligencebootcamp.de, reddit.com, zeb-business-school.com, ironhack.com, udemy.com and youtube.com. For "ai engineering bootcamp": ironhack.com, uchicago.edu, neuefische.de, udemy.com, lunartech.ai, hyperskill.org and school.digitale-leute.de. The Academy was named in none ([competitor keyword research](competitor-keywords.md), section 5).
- Across the 47 live queries of that check, Ironhack was cited in 10 AI Overviews, WBS Coding School in 9, and Spiced, Le Wagon and neue fische in 6 each.
- ChatGPT, Perplexity, Claude and Gemini for the article question: first check Monday 1 February 2027, which is the baseline.

**Expected results (targets)**

- Target: indexed within 7 days.
- Target: top 3 in Google Germany for "ai bootcamp germany" by 31 March 2027 (section 3a, row 11). #1 means passing Le Wagon and is a stretch after that.
- Target: top 20 for "artificial intelligence bootcamp" (170) by 31 March 2027.
- Target: 300 Search Console impressions in the first 60 days.
- Target: the Academy named in the Google AI Overview for "ai bootcamp germany" or "ai bootcamp berlin" by 31 March 2027.
- Target: 5 confirmed waitlist signups with `utm_campaign=ai-bootcamps-germany-experienced-developers` by 31 March 2027.

**Tracking.** GSC page filter `/blog/ai-bootcamps-germany-experienced-developers`, query regex group G1 (`(?i)(ai|ki|artificial intelligence)( engineering| engineer)? bootcamp`). Umami `cta_click` with `article=a11` and `target`. Waitlist source tag `utm_medium=article&utm_campaign=ai-bootcamps-germany-experienced-developers`; external links to the article carry the same `utm_campaign`. Monday AI check: article question, plus the weekly live position check for "ai bootcamp germany". The cannibalization view in Search Console ([competitor keyword research](competitor-keywords.md), section 8.1, step 9) shows whether this article or `/academy/` ranks for "ai bootcamp berlin"; if the article does, its Berlin paragraph is cut to one line.

---

## 10. How This Plan Lines Up with the Marketing Plan

This plan is my source of truth for articles. My [marketing plan](marketing-plan.md) (section 5.2) lists the same 11 articles with the same numbers, titles and weeks, and its SEO section carries the #1 goal, the top 10 target queries and the weekly Search Console tracking from section 3a.

Article ideas from the first version of my marketing plan that have no brief here and are not scheduled:

| Idea | Status |
| --- | --- |
| What Berlin Job Ads Ask Developers About AI Tools | No brief. The job-ad counts are used inside articles 2 and 4 and as a LinkedIn data post |
| Laid Off as a Developer in Germany: The First Four Weeks | No brief. Article 9 took its week, because its reader already asked for a voucher |
| Three Months Full Time or a Four Week Claude Code Course | No brief. The comparison is one section of articles 6 and 11 |
| What 14,559 Funded KI Courses Teach | Merged into article 6 as its method section |

One slot is free under the cap of 12 articles. It stays open for a question that comes up in the free sessions or in discovery calls.
