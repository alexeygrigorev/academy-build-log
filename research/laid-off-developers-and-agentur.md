# Laid-Off Developers, the Agentur and How Many We Can Reach

Desk research, 14 November 2026. 

The question I asked: do experienced developers actually go to the Agentur für Arbeit after a layoff? What do they do instead? And how many of them can we really reach?

Labels: **[BA]** primary source from the Bundesagentur für Arbeit or the law, **[R]** Reddit, **[HN]** Hacker News, **[X]** X, **[estimate]** my own calculation, **[vendor]** a course provider's website (a hint, not proof).

How I searched: Reddit through web search and thread pages (the Reddit JSON API returned 403), Hacker News through the Algolia API (10 queries, 2023 and later), X search (5 queries, German and English), BA documents and laws on gesetze-im-internet.de.

## 1. Summary

1. **Experienced developers do go to the Agentur, but not for a course.** The first advice after a layoff is always: register and apply for ALG I (unemployment insurance). The stories do not tell us what share of seniors register. People get offered a Bildungsgutschein or ask about one, but the first reaction in the community is "this is for career changers, a waste of time for a senior". The main fear is not the Agentur. It is losing time on a weak course instead of job hunting.
2. **The law and the Berlin Agentur support us more than it looks.** § 81 (1a) SGB III says training is necessary when "erweiterte berufliche Kompetenzen" improve employability. The Bildungszielplanung Berlin 2026 says for IT: deepen existing skills "auf Experten-/ und Spezialistenniveau", and a career change into IT is "nur schwer möglich". This confirms the level of our audience. It is not a promise to fund our course.
3. **The main barrier is the Vermittler.** The rule: "Ist eine Arbeitsaufnahme auch ohne eine Förderung realistisch, kann kein Bildungsgutschein ausgehändigt werden". A senior who looks easy to place gets refused. Chances go up when the person brings regional job ads that ask for a skill they do not have, plus a list of failed applications. That is our material: 18% of Berlin developer job ads already name AI coding tools.
4. **The "laid-off senior with a voucher" group in Berlin alone is small.** My estimate: 12 to 145 possible participants from the current pool (not per year), middle case about 53. This is not a measured audience and not a sales forecast. For 15 seats we need real reach and real Agentur approvals.
5. **Verdict: the core audience for the sessions is wider.** Experienced developers (2+ years) in Berlin who are job hunting or were laid off, **and** employed developers who need to upskill for AI. The Bildungsgutschein is one way to pay for people without a job. It does not define the audience.
6. **X is almost useless for this segment.** On "Bildungsgutschein + Entwickler/KI" X has mostly course providers. Developer voices on this topic live on Reddit (r/cscareerquestionsEU, r/InformatikKarriere, r/arbeitsleben, r/de_EDV) and in chats.

## 2. What experienced developers do after a layoff

| Step | What people do | Evidence |
|---|---|---|
| Register | Register as arbeitsuchend at least 3 months before the job ends, or within 3 days of notice if less time is left. Register as arbeitslos separately, at the latest on the first day without work. No data on how many do it. | "Immediately go to the Arbeitsagentur and register as unemployed. You **have** to do this within three days" ([r/askberliners, Feb 2024](https://www.reddit.com/r/askberliners/comments/1al4i0p/got_laid_off_my_work_whats_next/)) **[R]** |
| Money | ALG I is usually 60% (67% with children) of the calculated net pay, with a cap. You usually need 12 months of insurance in the last 30 months. That gives 6 months of benefit; 24 months of contributions give 12 months for people under 50. Not everyone can afford a long course. | [BA: ALG I conditions, amount and duration](https://www.arbeitsagentur.de/arbeitslos-arbeit-finden/arbeitslosengeld/finanzielle-hilfen/arbeitslosengeld-anspruch-hoehe-dauer) **[BA]**. Reddit advice like "one year of work = one year of benefit" is wrong. An engineer on ALG I: "some roles actually pay less than my current benefit" ([r/Germany_Jobs, Oct 2025](https://www.reddit.com/r/Germany_Jobs/comments/1o84mi1/30m_engineer_laid_off_from_ev_industry_using/)) **[R]** |
| Severance | People negotiate an Abfindung, often with a lawyer. An Aufhebungsvertrag or quitting can lead to a 12-week Sperrzeit. "Betriebsbedingt" alone does not rule it out. | "He should not sign the mutual severance contract" and "negotiate a better package (up to 1 months salary per year of employment is achievable)" ([r/berlinsocialclub, Aug 2022](https://www.reddit.com/r/berlinsocialclub/comments/wv1k22/a_friend_got_fired_and_needs_some_help_in_getting/)) **[R]**; Sperrzeit: [§ 159 SGB III](https://www.gesetze-im-internet.de/sgb_3/__159.html) **[BA]** |
| Job search | The main activity. Long and hard, especially for expats without C1 German. | Senior / tech lead, 10 years: "close to 1,000 applications" in 18 months, did an "intensive Machine Learning/AI bootcamp", ALG I ran out ([r/cscareerquestionsEU, 2026](https://www.reddit.com/r/cscareerquestionsEU/comments/1w56zu6/18_months_1000_applications_tech_market/)) **[R]**. Frontend, 4 years, Berlin, laid off from a startup: "I didn't really have much time to properly work on myself, study, or prepare for interviews" ([r/cscareerquestionsEU, 2026](https://www.reddit.com/r/cscareerquestionsEU/comments/1ur03ei/frontend_dev_in_berlin_laid_off_how_should_i/)) **[R]** |
| Learning | People think about Weiterbildung but doubt it. The community more often says "learn on your own, get an AWS or CKA cert, build a portfolio". | C# developer, laid off: "I'm unsure whether these programs actually help people get jobs, or if it's better to keep applying" ([r/Germany_Jobs, Mar 2026](https://www.reddit.com/r/Germany_Jobs/comments/1rq6v4c/45_years_c_developer_in_germany_recently_laid_off/)); reply: "Do both. Apply for new jobs while doing a Weiterbildung" **[R]** |
| Freelancing | Possible, but on ALG I only up to 15 hours a week, and income above a small allowance is deducted. | [r/askberliners: Freelancing during unemployment](https://www.reddit.com/r/askberliners/comments/1jety2x/freelancing_during_unemployment/); [§ 138 (3) SGB III](https://www.gesetze-im-internet.de/sgb_3/__138.html), [§ 155 SGB III](https://www.gesetze-im-internet.de/sgb_3/__155.html) **[BA]** |
| Own company | Gründungszuschuss (discretionary) for people who start a solo business. | "in Germany, the radio says, 1 people company is booming because people are laid off" ([HN, Sep 2026](https://news.ycombinator.com/item?id=49732979)) **[HN]** |
| Break or move | People take a break (health, German), some leave Germany. Blue Card holders with less than 2 years risk losing their permit after 3 months without work. A course in April is not their priority. | [r/germany: ALG I after being laid off, can I take a break first?](https://www.reddit.com/r/germany/comments/1vjq289/alg_i_after_being_laid_off_can_i_take_a_break/) **[R]** |
| Transfergesellschaft | In mass layoffs, up to 12 months in a Transfergesellschaft with Transferkurzarbeitergeld and training. This is a B2B channel (outplacement), not a landing page. | [§ 111 SGB III](https://www.gesetze-im-internet.de/sgb_3/__111.html) **[BA]** |

Conclusion: experienced developers have a clear money reason to register with the Agentur, and the stories show that they do. We do not know how many. In the stories, a course competes with job hunting and self-study. Our message must answer "will I lose time?", not "how do I get to the Agentur?".

## 3. The Bildungsgutschein for experienced people: stories and objections

### 3.1 Stories

1. Master in Informatik, several years of full-stack, unemployed: "wurde mir ein Bildungsgutschein in Aussicht gestellt. Ich habe mir mal ein paar Angebote angesehen aber die waren alle für Umsteiger und auf Anfänger Niveau" ([r/informatik, ~2023](https://www.reddit.com/r/informatik/comments/149zf7t/empfehlung_f%C3%BCr_weiterbildung_auf_h%C3%B6herem_niveau/)) **[R]**. A clear signal that people need a harder course. Not proof of conversion.
2. Senior TYPO3 / full-stack, 10+ years, on Bürgergeld, can do a Weiterbildung with a voucher and wants AI/LLM integration, but: "Mir ist bewusst, dass viele „KI-Kurse" eher oberflächlich sind" ([r/InformatikKarriere, 2026](https://www.reddit.com/r/InformatikKarriere/comments/1t0qeav/senior_web_developer_typo3_ki_mit/)) **[R]**. Replies recommend Turing College and WBS AI Agents, our direct competitors.
3. Laid off in Hamburg, the Vermittler offers a course at the VHS: "what if it's too basic/generic and doesn't actually help me get hired? Or if it just wastes time" ([r/hamburg, 2026](https://www.reddit.com/r/hamburg/comments/1r21h6u/i_got_laid_off_a_few_weeks_back_and_my_case/)) **[R]**.
4. How one person got a voucher (data science, after 4 years of work): "Zusätzlich konnte ich 5-10 regionale Stellenanzeigen listen, die das als Anforderung hatten, was mir noch fehlte. Ich hatte noch zusätzlich eine Liste mit Stellen, auf die ich mich (erfolglos) beworben habe" ([r/arbeitsleben, Oct 2025](https://www.reddit.com/r/arbeitsleben/comments/1nxzox9/fragen_zum_bildungsgutschein_der_bundesagentur/)) **[R]**.

### 3.2 Objections, strongest first

| Objection | In their words | Our answer |
|---|---|---|
| Courses are for beginners, useless for a senior | "Sobald du mehr als 2-3 Jahre relevante BE hast ist das einfach nur Zeitverschwendung" ([r/InformatikKarriere, May 2026](https://www.reddit.com/r/InformatikKarriere/comments/1t0qeav/senior_web_developer_typo3_ki_mit/)) **[R]** | Only experienced people, with a code check at entry. The program follows job ads, it does not start from zero. |
| I lose time I need for job hunting | Hamburg and C# stories above **[R]** | Live teaching, a portfolio project, job search in parallel. The message is about getting hired, not learning for its own sake. |
| The Vermittler says "Sie sind doch gut qualifiziert" | "Ist eine Arbeitsaufnahme auch ohne eine Förderung realistisch, kann kein Bildungsgutschein ausgehändigt werden" ([Agentur Ludwigsburg FAQ](https://www.arbeitsagentur.de/vor-ort/ludwigsburg/faq-foerderleistungen)) **[BA]** | A pack for the Vermittler: § 81 (1a), Bildungszielplanung Berlin, job ads with AI requirements, a list of applications. Do this after AZAV. |
| "You are already a Fachinformatiker, they won't retrain you" | "Die werden keine [große Summe] in die Hand nehmen um aus dir irgendeine eine System Integrator Variante zu machen" ([r/antiarbeit, Oct 2025](https://www.reddit.com/r/antiarbeit/comments/1nykdv6/umschulung_bei_der_agentur_raus_aus/)) **[R]** | That is about Umschulung (a new vocational degree). We are an Anpassungsqualifizierung of 3 to 4 months, a different legal basis. |
| The Agentur does not care about white-collar workers | "They don't really care about white collar workers making much more money than they do anyway" ([HN, Jan 2023](https://news.ycombinator.com/item?id=34428763)) **[HN]** | Out of date: since 2024 IT unemployment is at a 10-year high, and the BA itself writes about deepening expert skills (section 4). |
| The Agentur only wants you in a job | "Ziel einer Förderung der Arbeitsagentur ist … immer die Aufnahme einer sozialversicherungspflichtigen Tätigkeit" (a Vermittler on [r/arbeitsleben, Oct 2025](https://www.reddit.com/r/arbeitsleben/comments/1nxzox9/fragen_zum_bildungsgutschein_der_bundesagentur/)) **[R]** | Same goal as ours: the course leads to hiring. We need an employment track and graduate data. |
| ALG I runs out | Checked against the current law | [§ 148 (1) Nr. 7 SGB III](https://www.gesetze-im-internet.de/sgb_3/__148.html): 2 days of training use up 1 day of ALG I, and the rest never drops below 3 months. Example: with 180 days left, a 120-day course uses 60, and 120 stay. This is only for approved Weiterbildung. We do not promise everyone an automatic "longer benefit". **[BA]** |
| Sperrzeit | "Du hast gekündigt? Dann bist du eh erstmal 3 Monate von allem gesperrt" ([r/de_EDV, May 2026](https://www.reddit.com/r/de_EDV/comments/1ta2lxi/bald_auf_jobsuche_java_fullstack_entwickler_hilfe/)) **[R]** | We do not use this blunt advice. Quitting or an Aufhebungsvertrag can lead to a Sperrzeit, but there are exceptions. No legal advice in the FAQ; we send people to the Agentur. |

### 3.3 X

5 queries (German and English, 2025 to 2026). Almost all posts on "Bildungsgutschein + Entwickler/Senior/KI" come from course providers **[X, vendor]**. Only a few personal posts, for example someone unemployed again after a one-year search with 80 applications **[X]**. X is not a channel for this segment.

## 4. What the BA itself says

1. **The law.** [§ 81 (1a) SGB III](https://www.gesetze-im-internet.de/sgb_3/__81.html): "Anerkannt wird die Notwendigkeit der Weiterbildung bei arbeitslosen Arbeitnehmerinnen und Arbeitnehmern auch, wenn durch den Erwerb erweiterter beruflicher Kompetenzen die individuelle Beschäftigungsfähigkeit verbessert wird und sie nach Lage und Entwicklung des Arbeitsmarktes zweckmäßig ist." This is the legal basis for a course for experienced people. **[BA]**
2. **Berlin, IT.** [Bildungszielplanung Berlin 2026](https://www.arbeitsagentur.de/vor-ort/datei/bildungszielplanung_berlin_2026_ba264851.pdf): "Die Weiterbildung sollte darauf ausgerichtet sein, dass vorhandene digitale Kernkompetenzen (z. B. Programmierung, IT- Sicherheit, Cloud- Anwendungen, Datenmanagement) auf Experten-/ und Spezialistenniveau vertieft werden." And: "Aktuell ist ein Quereinstieg in der IT-Branche nur schwer möglich, erforderlich ist eine akademische Vorbildung." The IT section does not mention "KI" or coding agents; AI appears in the introduction as a driver of change. **[BA]**
3. **Germany.** [BA press release 2026-24](https://www.arbeitsagentur.de/presse/2026-24-arbeitsmarkt-in-der-informations-und-kommunikationstechnik-ikt-im-spannungsfeld-konjunkturelle-schwaeche-trifft-auf-strukturellen-wandel): "Für alle Fachkräfte in dieser Branche gilt: Kontinuierliche Weiterbildung ist der Schlüssel". The same release has the counterpoint: "Hochqualifizierte Expertinnen und Experten sind von Arbeitslosigkeit kaum betroffen (Quote: 3,5 Prozent)." **[BA]**
4. **Berlin, scale.** 7,431 unemployed people in ICT on average in 2025, and 686 open positions at the Agentur ([BA RD BB 16/2026](https://www.arbeitsagentur.de/vor-ort/rd-bb/presse/2026-16-berlin-ist-der-fuhrende-standort-fur-ikt-beschaftigung-unterstutzung-von-zukunftsbranchen-macht-hoffnung)) **[BA]**; about 8,000 in early 2026 according to an IBB report ([rbb24, Apr 2026](https://www.rbb24.de/wirtschaft/beitrag/2026/04/programmierer-jobs-arbeit-ki-berlin.html)). The BA also names software development among the groups with many unemployed skilled workers ([BA RD BB 19/2026](https://www.arbeitsagentur.de/vor-ort/rd-bb/presse/2026-19-berlinbrandenburg-fachkrafte-sichern-bevor-sie-fehlen-ba-und-uvb-rufen-unternehmen-zum-handeln-auf)) **[BA]**.
5. **Who is in funded training in Berlin** (BA FbW spreadsheet, 12 months to July 2026, without training for employed people) **[BA]**: 23,031 entries. 8,792 (38%) have no completed vocational training, and 9,508 (41%) are foreign nationals. The other 14,239 (61.8%) are not in the "no completed vocational training" group. That is not a clean share of graduates. The table has no split for academics or for people with an IT job before the course. Only a special evaluation by the BA statistics service can give the exact share of former developers.

## 5. Where laid-off Berlin developers gather

| Place | Size | How to use it |
|---|---|---|
| r/cscareerquestionsEU | ~179,000 (third-party counter) | Read and quote. No ads (the rules forbid them). |
| r/InformatikKarriere, r/de_EDV, r/arbeitsleben, r/Germany_Jobs | not measured | German threads on "Bildungsgutschein + Senior", the best source of real wording. |
| Alumni groups of companies with layoffs (Slack, LinkedIn, Signal) | per company | The most precise channel: after a layoff, former colleagues gather in their own rooms. [LayoffCheck Berlin](https://layoffcheck.com/locations/berlin/) lists 70 companies, 98 rounds and 15,410 people since 2022. Entry only through people we know. No cold messages. See also [WARNTracker on alumni communities](https://www.warntracker.com/blog/company-alumni-communities). |
| LinkedIn #opentowork, Berlin | group sizes not visible without login | My own LinkedIn posts and comments under posts about Berlin layoffs. |
| Berlin Tech Workers Coalition | ~1,200 on Telegram | Talks about layoffs, but not an ad channel. |
| Berlin job newsletters for internationals | a few thousand to ~12,000 readers each | Paid placements. Details are in a separate media list that I keep private. |
| Outplacement firms and Transfergesellschaften | not public | Later, B2B: a free session for their cohorts. |
| Russian- and Ukrainian-speaking IT chats in Germany | small (1,000 to 2,000 members) | Only through the admins. |
| Kununu | employer reviews, not a community | Not a channel. |

## 6. Reach: an estimate with the math

Goal: check if the group "experienced developer in Berlin without a job who takes a voucher course" is big enough for 15 seats in April 2027. Important: the starting number is a stock of people at one point in time, not a yearly flow.

| Step | Value | Basis |
|---|---|---|
| Unemployed developers (KldB 434), Berlin | 3,280 | September 2026, see [market sizing](market-sizing.md) |
| Plus job seekers still in their notice period | ×1.54 → **~5,100** | ratio 32,651 / 21,144 for Germany, October 2026 **[estimate]** |
| With 2+ years of experience | 60–80% → **3,031–4,041** | **[estimate]** |
| Ready to take a full-time course of 3 to 4 months | 5–15% → **152–606** | Reddit: most people advise to search and self-study **[estimate]** |
| Get a voucher for such a course | 40–60% → **61–364** | the "realistic without funding" rule against § 81 (1a) **[estimate]** |
| People we reach before enrollment | 20–40% → **12–145**, middle **~53** | channels from section 5 **[estimate]** |

Rest of Germany, online: (21,144 − 3,280) × 1.54 × 70% × 10% × 50% × reach 5–15% ≈ **48–144** **[estimate]**. A voucher can be "regional begrenzt" ([§ 81 (4) SGB III](https://www.gesetze-im-internet.de/sgb_3/__81.html)), so for an online course we need to check this with the Agentur.

Middle case: 3,280 × 1.54 × 70% × 10% × 50% × 30% = 53. All factors except 3,280 and 1.54 are unconfirmed assumptions. 15 seats are possible, but I am not confident in a Berlin, voucher-only segment yet. We need a test with qualified leads and probably participants from the rest of Germany.

**Verdict**

1. Core of the sessions and the landing page: **experienced developers (2+ years) in Berlin who are job hunting, in their notice period or laid off**, plus **employed experienced developers who need to upskill for AI**. Both groups go in the hero. Beginners and career changers go to the free Zoomcamps.
2. The Bildungsgutschein is a way to pay for the unemployed part of the audience (plus § 82 for employed people through their employer, and Transfergesellschaften in mass layoffs). It does not define the segment. We do not shout about it in ads. We explain it in the FAQ and in session 1.
3. For the course decision we look at the signup form answers (situation and location): the share of "job hunting / laid off" in Berlin and interest in a long course. RSVPs or interest in agentic engineering alone are not buying demand.
4. Free next checks: a special BA evaluation (training entries with a previous job in 434, Berlin, 2024 to 2026), and a call to the Berlin Bildungsberatung about an online voucher course. 

## 7. What this means for headlines and copy

1. The hero says "experienced" and "at least two years". "Developers in Berlin" alone also reads as beginners.
2. Their words: "job hunting", "notice period", "laid off", "upskill". "Bildungsgutschein" stays out of the headline and goes to the FAQ.
3. The answer to "I'll lose time": a 60-minute free session, a recording, a real project on GitHub.
4. Positioning as a fact about us: "These sessions assume you already write production code". No claim that all courses are bad (half of that hypothesis did not hold, see [supply and bootcamps](supply-jobs-and-bootcamps.md)).
5. Session 1 can answer the Agentur question: what the Bildungszielplanung Berlin 2026, § 81 (1a) and § 148 say. This is rare knowledge, and it ties the audience to Berlin.

## 8. Limits

1. Reddit quotes come from search excerpts and thread pages; the Reddit API returned 403. Some quotes have few upvotes, so they are a weak signal.
2. The shares in section 6 are my assumptions, and the ranges are wide.
3. Hacker News is weak on this topic (few German stories, some before 2024).

