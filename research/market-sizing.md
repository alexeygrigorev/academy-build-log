# Market Size, Audience and Track Signals

Desk research, 14 November 2026. Nothing was sent to anyone and no money was spent. Original language: Russian. This is a shortened English version. I removed all money figures (course prices, cost rates and revenue estimates).

**What I checked:** DataTalksClub Academy, a full-time live online program, 15 seats, first cohort April 2027, two tracks (Agentic Engineering and AI Engineering), paid through a Bildungsgutschein after AZAV certification. Audience: developers in Berlin first, then in all of Germany, who were laid off, are job hunting or fear a layoff. Funnel: a free online session series and a waitlist on the landing page.

**Builds on** my earlier public research in [research-dump](https://github.com/alexeygrigorev/research-dump/tree/main/courses/ai-engineering-school-germany) (in Russian): layoffs in Berlin, voucher rules, 24 competitor programs, and an analysis of 9,760 AI Engineer job ads.

**Labels:** **[BA]** primary data from the Bundesagentur für Arbeit, opened on 14 November 2026; **[secondary]** a site that re-uses BA data; **[estimate]** my calculation, with the formula next to it; **[S]** search snippet only.

## 1. Summary

1. **The pool is big, and we need a tiny share.** Berlin has 3,280 unemployed developers (KldB 434, September 2026) and only about 100 developer openings at the BA. Germany has 21,144 unemployed and 32,651 job-seeking developers (October 2026), that is +69% unemployed since April 2024. 15 seats are about 0.3% of job-seeking developers in Berlin **[estimate]**.
2. **There is real funding for IT retraining, and Berlin is a big part of it.** In the 12 months to July 2026, Germany had 33,744 entries into BA-funded training with an IT goal (10.4% of all entries), 4,038 of them in Berlin **[BA]**. 15 seats are 0.4% of the Berlin IT flow.
3. **But Berlin got stricter.** IT entries in Berlin fell 14.9% in a year (4,745 → 4,038), while developer unemployment grows **[BA]**. Germany: +3%. The bottleneck is not demand. It is the Vermittler's decision and having AZAV by April.
4. **Job outcomes after IT courses are weaker than average.** Six months after an IT course, 38.7% are employed (48.2% for all courses), 35.6% in Berlin **[BA]**. This is the main point to answer for the Vermittler and in marketing: show how the course leads to a job.
5. **Funnel for 15 seats** **[estimate from benchmarks]**: ~4,000–6,000 visits → ~300 waitlist signups → ~60 applications → ~30 accepted → ~15 with a voucher who start. Three free sessions give about a third of the needed signups. The rest must come from DataTalksClub channels and paid tests.
6. **The tracks send mixed signals.** Job ads and job titles favor **AI Engineering** ("AI Engineer" appears 3.7 times more often than "Claude Code" in the BA Jobbörse). Search interest and weak competition favor **Agentic Engineering** (in Google Trends "Claude Code" is about 7 times higher than "AI Engineer", but almost nobody searches for "Agentic Engineering" itself). Desk research does not pick the track. Clicks and signups in the test and at the sessions decide.

## 2. TAM, SAM, SOM

### 2.1 How many developers

| Metric | Value | Date | Source |
|---|---|---|---|
| Employees with social insurance in ICT jobs, Germany | 1.15 million (+2% year on year); all ICT workers 1.6 million (Mikrozensus) | 2025 | [BA, Akademiker Informatik](https://statistik.arbeitsagentur.de/DE/Statischer-Content/Statistiken/Themen-im-Fokus/Berufe/AkademikerInnen/Berufsgruppen/2-2-Informatik.html) **[BA]** |
| Of them, software development and programming (KldB 434) | **350,000** (30% of ICT) | June 2025 | [BA, AM kompakt IKT](https://statistik.arbeitsagentur.de/DE/Statischer-Content/Statistiken/Themen-im-Fokus/Berufe/Generische-Publikationen/AM-kompakt-IKT.pdf?__blob=publicationFile&v=11) **[BA]** |
| 434 by level (full-time): expert / specialist / skilled worker | 207,431 / 64,048 / 20,510 | 2025 | [Entgeltatlas via entgeltatlas-online.de](https://entgeltatlas-online.de/berufsgruppe/softwareentwicklung-und-programmierung-434) **[secondary]** |
| Employees in ICT, Berlin | 84,599 (+3.5% year on year) | 2025 | [BA RD Berlin-Brandenburg 16/2026](https://www.arbeitsagentur.de/vor-ort/rd-bb/presse/2026-16-berlin-ist-der-fuhrende-standort-fur-ikt-beschaftigung-unterstutzung-von-zukunftsbranchen-macht-hoffnung) **[BA]** |
| Developers (434), Berlin | **~25,700** | 2025 | **[estimate]** 84,599 × 30.4% (the 434 share of ICT in Germany) |

### 2.2 How many are without work or job hunting

| Metric | Value | Date | Source |
|---|---|---|---|
| Unemployed in ICT (group 43), Germany | 54,000 on average (+27%, the highest in 10 years) | 2025 | [BA](https://statistik.arbeitsagentur.de/DE/Statischer-Content/Statistiken/Themen-im-Fokus/Berufe/AkademikerInnen/Berufsgruppen/2-2-Informatik.html) **[BA]** |
| Same, monthly | 57,375 (Oct 2025) → peak 67,457 (Aug 2026) → **65,182** (Oct 2026, +13.6% year on year) | 2025–2026 | [dietechrecruiter, Oct 2026](https://dietechrecruiter.de/posts/it-arbeitsmarkt-deutschland-oktober-2026/) **[secondary]**; [heise](https://www.heise.de/news/Arbeitslosigkeit-bei-ITlern-Hoechster-Stand-seit-zehn-Jahren-11521166.html) confirms ~65,000 |
| Job seekers in ICT (group 43), Germany | 87,941 → **100,428** (+14.2%) | Oct 2025 → Oct 2026 | dietechrecruiter **[secondary]** |
| **Unemployed developers (434), Germany** | 12,534 (Apr 2024) → 21,518 (Sep 2026) → **21,144** (Oct 2026). **+69%** in 2.5 years | 2024–2026 | [dietechrecruiter, Apr 2024](https://dietechrecruiter.de/posts/einblick-in-den-deutschen-it-arbeitsmarkt-softwareentwicklung-april-2024/) **[secondary]** |
| Job-seeking developers (434), Germany | 21,414 (Apr 2024) → **32,651** (Oct 2026) | 2024–2026 | Same source. "Job seeking" includes "unemployed", so ~11,500 look for work before they lose it (notice period and similar) **[estimate]** |
| New developer openings at the BA | 1,790 in October 2026 (−3.7% year on year) | Oct 2026 | dietechrecruiter **[secondary]** |
| **Unemployed developers (434), Berlin** | 3,170 (Sep 2025) → **3,280** (Sep 2026), with 70 → 100 openings; 32.8 per opening (Hamburg 9.5, Munich 11.0). 36.1 per opening in October 2026 | 2025–2026 | [Stellenradar, CSV from BA data](https://stellenradar.org/presse/2026-09-berlin-werbung-gastronomie-software/berlin-grossstaedte-2026-09.csv), [Stellenradar Berlin 434](https://stellenradar.org/jobs/softwareentwicklung-und-programmierung/berlin) **[secondary]** |
| Berlin share of unemployed developers in Germany | **15.2%** | Sep 2026 | **[estimate]** 3,280 / 21,518 |
| Job-seeking developers, Berlin | **~5,060**, of them ~1,780 not yet unemployed | autumn 2026 | **[estimate]** 3,280 × 1.544 |
| Developer unemployment rate | Germany ~5.7%; Berlin **~11%** | 2025–2026 | **[estimate]** 21,144 / (350,000 + 21,144); 3,280 / (25,700 + 3,280) |

The claim "3,280 unemployed developers in Berlin against ~100 BA openings" holds, but the source is still secondary. The claim "IT unemployment is at a 10-year high" is confirmed by the BA itself.

### 2.3 TAM / SAM / SOM

| Level | Definition | People |
|---|---|---|
| **TAM** | IT specialists in Germany who look for work (group 43) | 100,428 (Oct 2026). Real market of funded IT courses: 33,744 entries per year **[BA]** |
| **SAM (Germany)** | Job-seeking developers (434), online course for the whole country | 32,651 |
| **SAM (Berlin)** | Job-seeking developers in Berlin | ~5,060 **[estimate]**; in practice 3,800 IT courses started in Berlin in a year for unemployed people and job seekers **[BA]** |
| **SAM (Berlin, our filter)** | Experienced, want a full-time AI course, English, no short visa timer | ~870 **[estimate]** |
| **SOM** | First cohort | **15** = 0.3% of job-seeking developers in Berlin, 0.4% of the Berlin IT training flow, 1.7% of the filtered SAM |

## 3. The Bildungsgutschein market

### 3.1 How much training goes to IT (BA primary data)

Source: BA statistics, "Förderung der beruflichen Weiterbildung", report month July 2026, [xlsx](https://statistik.arbeitsagentur.de/Statistikdaten/Detail/202607/iiia5/fbw-insgesamt/fbw-insgesamt-dlrdaa-0-202607-xlsx.xlsx?__blob=publicationFile&v=1), 12 months to July 2026 (previous 12 months in brackets). Training goal KldB 43.

| | All entries | IT goal (43) | IT share | Of them, unemployed and job seekers |
|---|---|---|---|---|
| Germany | 325,646 (315,021) | **33,744** (32,761), +3.0% | 10.4% | 28,691 |
| RD Berlin-Brandenburg | 33,447 (33,171) | 4,770 (5,486) | 14.3% | 4,409 |
| **Berlin** | 25,401 (24,906) | **4,038** (4,745), **−14.9%** | 15.9% | **3,800** |

- Berlin has 12% of all IT entries in Germany and a higher IT share than average.
- [DIB](https://dib-bildung.de/bildungsgutschein-berlin/) reports the same 4,038 from BA data: IT is the second biggest field in Berlin after office jobs.
- Berlin has 58 people in funded training per 1,000 unemployed, the German average is 80 (DIB, October 2026 **[secondary]**). Hamburg has 81, Munich 75.

### 3.2 Jobs after the course (Eingliederungsquote)

Same file: the share of people with an insured job 6 months after the course.

| | Finished | Employed after 6 months | Share |
|---|---|---|---|
| Germany, all goals | 238,966 | 115,198 | 48.2% |
| Germany, IT (43) | 27,816 | 10,758 | **38.7%** |
| Berlin, IT (43) | 4,420 | 1,572 | **35.6%** |

The Vermittler sees that IT courses place people worse than other courses. Our one-pager for the Agentur and the landing page must answer "how does this lead to a job": a portfolio project, employers at a demo day, job-ad data.

### 3.3 Vouchers issued and used

- **The BA does not count issued vouchers.** BA answer to a [FragDenStaat request](https://fragdenstaat.de/anfrage/gefoerderte-weiterbildungen-in-it-ai-data-nach-bundesland-und-massnahmekategorie-2025/) (February 2026): the number and goal of issued vouchers "werden … statistisch nicht erfasst". Only entries are counted.
- **Redemption rate:** no fresh data. The last IAB measurement: ~85% of issued vouchers were used (2003–2006) ([IAB DP 17/2008](https://doku.iab.de/discussionpapers/2008/dp1708.pdf)). Only an order of magnitude.
- **Who comes to voucher portals:** 366 requests on DeinBildungsgutschein (July to November 2026): 16.1% already have a voucher, 16.7% are in the process, 57.1% have none; 59.8% get ALG I, 7.9% are "at risk of layoff", 4.9% are employed. The top topic is "Daten & KI" (18.9%), IT/software 16.1% ([Trendbericht 2026](https://deinbildungsgutschein.de/trendbericht) **[secondary]**). For our funnel: most interested people still need to get a voucher, so we must help with the Vermittler conversation.
- **Catalog:** of 3,648 AZAV courses on the same portal, 13.2% are IT/software and 5.8% data/AI; the median length is 13 weeks; 75.5% are online or hybrid.

### 3.4 How the BA cost rate works (B-DKS)

- The B-DKS is the BA's average cost rate per lesson unit (UE) per participant. The 2026 rates apply from 1 July 2026 to 30 June 2028 ([BA table](https://www.arbeitsagentur.de/datei/tabelle-der-kosten-fuer-massnahmen-der-beruflichen-weiterbildung-2024_ba049411.pdf)). The relevant code for us is KldB 43414 (software development, expert level).
- **One UE is 45 minutes, not an hour** ([Beirat recommendations](https://www.arbeitsagentur.de/datei/dok_ba032840.pdf), [Umsetzungshinweis 1/2026](https://www.arbeitsagentur.de/datei/umsetzungshinweis-01-2026_ba055638.pdf)). The rate applies only to live (synchronous) UE. Full-time at providers means 40 UE a week, that is 30 clock hours. So 520 UE are about 3 months (13 weeks).
- **Going above the B-DKS is possible** ([§ 179 (2) SGB III](https://www.gesetze-im-internet.de/sgb_3/__179.html); [§ 3 (4) and (6) AZAV](https://www.gesetze-im-internet.de/azav/__3.html)): up to +25% if the certification body accepts "notwendige besondere Aufwendungen" (more staff, special rooms or tech, special content, accessibility, a justified smaller group; the standard calculation group is 12). Above +25% the BA must also agree. Any course above the B-DKS gets a separate, longer check ([AZAV Wissensportal](https://azav-wissensportal.de/beitraege/bdks-2026-neue-kostensaetze/) **[secondary]**).
- Expensive voucher courses on the market are mostly longer courses (5 to 7 months or more), not higher rates.
- My model: 3 to 4 months full-time, 40 UE a week, KldB 43414. A higher total needs a justified surcharge of about 25% (live code review in small groups, cloud and LLM budgets per participant). The certification body decides that, not us. We do not plan above +25%. We count only live hours.
- The extra Weiterbildungsgeld and bonuses in [§ 87a SGB III](https://www.gesetze-im-internet.de/sgb_3/__87a.html) are only for retraining toward a vocational degree. Our participants do not get them.

### 3.5 Competitors

Full table of 24 programs in [research-dump](https://github.com/alexeygrigorev/research-dump/blob/main/courses/ai-engineering-school-germany/bildungsgutschein/research-notes/germany-azav-programmes.md). Three new ones, from search snippets only **[S]**:

| Provider | Course | Length | AI Engineering / Agentic |
|---|---|---|---|
| StackFuel (Multiverse) | KI-Fachkraft; KI-Automatisierungsexperte | 1 month FT; 8 weeks FT | neither, these are courses for AI users ([StackFuel](https://stackfuel.com/de/weiterbildung/ki-weiterbildung/)) |
| DCI | AI Engineer | ~12 months FT + 3-month internship | AI/data engineering, not agentic ([DCI](https://digitalcareerinstitute.org/en/courses/ai-engineer/)) |
| Morphos | Professional KI Mastery and others | 3 to 13 months | AI tools, not for experienced developers ([Morphos](https://adz-weiterbildung.de/weiterbildungen/weiterbildung-professional-ki-mastery-content-creation-automation-app-building/)) |

Same picture as before: **AI Engineering is crowded** (IfaDW, Turing College, neue fische/Spiced, alfatraining, Ironhack, Masterschool, DCI). **Agentic engineering for experienced developers is almost empty**: alfatraining with Claude Code (2 weeks, German), Viona/IBB (4 weeks, German), WBS AI Software Development (17 weeks, for beginners), Turing "Building with AI Agents" (for non-programmers).

## 4. Employed developers at risk (Qualifizierungschancengesetz, § 82 SGB III)

| Metric | Value | Source |
|---|---|---|
| Employed people who started BA-funded training | 67,788 (May 2025 to April 2026) | [Bitkom guide 08/2026](https://www.bitkom.org/sites/main/files/2026-08/bitkom-leitfaden-qualifizierung-von-beschaeftigten.pdf) |
| IT share | 5.6% (≈3,800) | same |
| IT entries of employed people, 12 months to July 2026 | Germany **~5,050**, Berlin **~240** | **[BA]** difference between "all" and "without employed" |

Rules ([§ 82 SGB III](https://www.gesetze-im-internet.de/sgb_3/__82.html)): course longer than 120 hours, AZAV provider and course, a discretionary decision, the employer shares the cost. Companies under 50 staff: up to 100% of the course; 50–499: 50%; 500+: less. Plus a partial wage subsidy.

Conclusion: a real channel, but small and B2B. In Berlin about 240 employed people a year start an IT course through the Agentur. A full-time course needs the employer to release the person. Not the main path for the first cohort.

## 5. How reachable the audience is

### 5.1 Meetup (Berlin, AI and data), checked 14 November 2026

| Group | Members | Attendance | Fit |
|---|---|---|---|
| [Berlin DataTalksClub Group](https://www.meetup.com/berlin-datatalks-club/) (ours) | **10,742** | online events 6–27 RSVPs | our own group; not all members live in Berlin |
| [BLISS AI Speaker Series](https://www.meetup.com/bliss-speaker-series/) | 6,976 | 219–255 per event | research audience, students, PhDs; weak |
| [Berlin AI Engineering Group (m\|rig)](https://www.meetup.com/de-DE/berlin-ai-engineering-group-by-m-rig/) | 5,580 | 15 past events | AI Engineering, strong for track B |
| [Berlin AI Developers Group (AICamp)](https://www.meetup.com/berlin-ai-tech-talk/) | 4,809 | 2–6 RSVPs on Meetup | broad, many vendor webinars |
| Berlin AI, ML and Computer Vision Meetup | 3,637 **[S]** | — | weak |
| [LGTM Berlin: Programming in the Age of LLMs](https://www.meetup.com/lgtm-berlin/) | 1,279 | **48–51** every month | **exactly about agentic coding**, best fit for track A |

### 5.2 Other channels

| Channel | Size | Note |
|---|---|---|
| r/berlin | ~605,000 | [third-party stats](https://kissmypost.com/subreddit/berlin), general audience |
| r/cscareerquestionsEU | ~179,000 (+15% in a year) | [kissmypost](https://kissmypost.com/subreddit/cscareerquestionsEU) **[secondary]** |
| Berlin job newsletters | ~11,500 to ~12,000 subscribers each | paid placements |
| LinkedIn, Meta | no public numbers | only the ad tools show audience size |
| X (German posts, last 7 days) | "claude code" 145; agentic / coding agents 34; Bildungsgutschein 8; AI Engineer 5 | almost not a channel for this audience |
| Hacker News (comments since July 2025) | 0–4 matches for layoffs in Germany and Bildungsgutschein | not a channel |

## 6. Demand signals by track

### 6.1 Google Trends, Germany, January 2024 to 13 November 2026

Relative values (0–100 within one chart), quarterly averages; Q4 2026 is incomplete.

| Query (one chart, DE) | Q1 2024 | Q1 2025 | Q1 2026 | Q2 2026 | Q3 2026 | Q4 2026 |
|---|---|---|---|---|---|---|
| Claude Code | 0 | 0.8 | 46.6 | **65.5** | 38.9 | 38.0 |
| AI Engineer | 0.5 | 1.0 | 5.4 | **9.5** | 6.8 | 2.5 |
| Bildungsgutschein | 3.9 | 4.8 | 6.3 | 5.6 | 5.2 | 4.2 |
| KI Weiterbildung | 0 | 0.9 | 1.4 | 1.3 | 1.2 | 1.2 |
| Agentic Engineering | 0 | 0 | 0.2 | 1.0 | 0.1 | 0 |

- Berlin looks the same: "Claude Code" 66.2 against "AI Engineer" 10.2 in Q2 2026.
- In a separate chart, "KI Weiterbildung" grew about 5.7 times, "Bildungsgutschein" 1.1 to 1.6 times. Combined queries like "Bildungsgutschein KI" are almost zero: people search for the voucher and the topic separately.
- "Agentic Engineering" almost does not exist as a search query. Ads and session titles need the words people type: "Claude Code", "coding agents", "AI Engineer", "KI Weiterbildung".
- Limit: people who search "Claude Code" are mostly users of the product. This is interest in the topic, not intent to buy a course.

### 6.2 Job ads: BA Jobbörse, 14 November 2026

Public Jobbörse API, full-text search, jobs only, Berlin within 25 km. The numbers show ratios, not the exact market size.

| Query | Germany | Berlin |
|---|---|---|
| Softwareentwickler | 3,030 | 185 |
| Software Engineer | 1,284 | 120 |
| **AI Engineer** | **524** | **88** |
| KI Engineer | 570 | 86 |
| KI-Entwickler | 259 | 24 |
| RAG | 259 | 55 |
| LLM | 209 | 37 |
| KI-Agenten | 228 | 21 |
| Agentic | 181 | 56 |
| Generative AI | 169 | 45 |
| **Claude Code** | **143** | **19** |
| Machine Learning Engineer | 137 | 22 |
| AI Agents | 100 | 32 |
| GitHub Copilot | 74 | 8 |

Also: 20.8% of software development ads on Indeed DE mention AI (November 2025, [Indeed Hiring Lab](https://hiringlab.indeed.com/de/blog/2025/12/11/indeed-jobs-hiring-trends-report-deutschland-2026/)). In my corpus, 25.1% of AI Engineer job ads in November 2026 mention coding agents ([agentic-engineering-analysis](https://github.com/alexeygrigorev/research-dump/tree/main/courses/ai-engineering-school-germany/agentic-engineering-analysis)).

How to read this: "AI Engineer" is a **job title**. "Agentic" is a **requirement inside a normal developer job**. For a Vermittler who needs a clear target job, AI Engineering is easier. For an experienced developer who wants to stay in their job, Agentic is closer.

### 6.3 Tracks side by side

| Signal | AI Engineering | Agentic Engineering |
|---|---|---|
| Job ads with this title (BA, Berlin) | **stronger** (88 vs 19 "Claude Code" and 56 "Agentic") | a requirement inside roles |
| Search interest (Trends) | lower | **stronger** for "Claude Code"; the term itself is almost not searched |
| AZAV competitors | crowded | **almost empty** for experienced people |
| Fits the Berlin Agentur line "deepen existing skills" | yes | **yes, more directly** |
| Clear for a Vermittler | **more** (target job) | less, needs explaining |

No clear winner in open data. AI Engineering wins on job ads and on being clear for the Agentur. Agentic wins on interest and weak competition. The ad test of 17 to 22 November and signups for sessions 1 and 2 decide.

## 7. Are 15 seats realistic, and what funnel do we need?

### 7.1 Conversion benchmarks

| Step | Benchmark | Source |
|---|---|---|
| Visit → signup (landing page, education) | median 8.4%; email traffic 14.1%; paid search 7.3%; paid social 5.1% | [Unbounce, Education](https://unbounce.com/conversion-benchmark-report/education-conversion-rate/) |
| Webinar registration → live attendance | 47.7% (average 175 registrations, 83 viewers) | [Livestorm 2026](https://livestorm.co/webinar-benchmark-report-2026) |
| Lead → enrollment (bootcamp) | 6–27%, practical guide ~10% | [Prooflytics](https://prooflytics.io/blog/why-cpl-is-wrong-metric-edtech) (vendor blog, weak source) |
| Application → enrollment (online bootcamp) | 45–65% | [Prooflytics](https://prooflytics.io/blog/application-to-enrollment-conversion-rate-edtech) (weak source) |
| Has a voucher at the time of the request | 16% (17% more in progress) | [DeinBildungsgutschein Trendbericht](https://deinbildungsgutschein.de/trendbericht) |

### 7.2 Funnel back from 15 seats **[estimate]**

| Step | Rate (assumption) | Needed |
|---|---|---|
| Started | — | **15** |
| Got a voucher and approval | 85% of them start | 18 |
| Accepted by us | 60% get a voucher | 30 |
| Applied | we accept 50% (experience, English, visa) | **~60** |
| Waitlist signups | 20% move on to apply (range 15–25%) | **~300** (240–400) |
| Landing page visits | 5–8% | **~3,750–6,000** |

Second check: lead → enrollment is about 10%, and the voucher roughly halves it, so ~5%: 15 / 0.05 = 300 leads. It matches.

**What the free sessions give:** 3 sessions × ~150 registrations × 47.7% live ≈ 215 live viewers. If 40% of them join the waitlist **[assumption]**, that is ~85 signups, about a third of what we need. The rest: the DataTalksClub newsletter (email converts best), our Meetup group, Slack, my own accounts, partner meetups, Berlin newsletters, a paid social test.

### 7.3 Conclusion

- **15 seats are realistic on demand:** we need ~0.3% of job-seeking developers in Berlin, or ~0.05% in Germany if the course is online.
- **The main risks are not demand:** (1) AZAV by April 2027; (2) the Berlin Agentur cut IT entries by 15% in a year and gives the fewest vouchers per 1,000 unemployed of the big cities; (3) only 36–39% find a job after IT courses, and the Vermittler sees that.
- **What to do about the risks:** prepare a one-pager for the Vermittler (target job, job ads from 6.2, an employment plan); explain on the landing page and in the sessions how to get a voucher; keep an online format for all of Germany as a fallback.

## 8. Cheap next checks

1. A free special evaluation from the BA statistics service: KldB 434 in Berlin, monthly for 2024–2026, and training entries for 434.
2. Audience size forecasts in LinkedIn and Meta ad tools.
3. In the ad test and at the sessions, count by track: ad CTR, waitlist signups, registrations for the track sessions, the "employed / notice period / unemployed" answer and "do you have a voucher".
4. Keyword volumes (see the [SEO content plan](seo-content-plan.md)).

## 9. Limits

- The Berlin numbers for 434 are secondary (Stellenradar, dietechrecruiter on BA data).
- The number of developers in Berlin is my estimate.
- Jobbörse counts are full-text search results on one date, not all openings (only about half of all openings reach the BA).
- Google Trends is relative, with no absolute volumes.
- Conversion benchmarks come from the US and B2B webinars. For a German audience with a voucher, conversion is probably lower. All funnel rates are assumptions to test.
