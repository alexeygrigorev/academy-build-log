# DataTalks.Club Academy: where the school should live, and a first SEO plan

Research only, 15 November 2026. Nothing was purchased. It started from a post about the Morrowen / ChatGPT “AI shelf” experiment and my question about a separate domain and SEO: is it better to stay on datatalks.club?

**Update, same day:** after this research I decided to move the academy to `https://datatalks.club/academy/` now, with 301 redirects from `academy.datatalks.club`. The [SEO content plan](seo-content-plan.md) follows that decision. The analysis below is kept as it was.

## Recommendation

Stay on the datatalks.club property. Do not make a new domain the canonical site of the school before the April 2027 start.

Between a subfolder (`https://datatalks.club/academy/`) and the live subdomain (`https://academy.datatalks.club/`), the subfolder is a modest long-term plus, not a must. The live subdomain is a reasonable choice. It already matches how free courses live at `courses.datatalks.club`. The work that actually moves SEO and AI-search visibility is links, clear pages, and getting the academy sitemap into Search Console. A URL move during the November and December sessions is not worth the risk.

A short brand domain (best option: `datatalks.academy`) can be bought later as a redirect. It should not replace the canonical URLs before April 2027.

This confirms the “stay on datatalks.club, maybe buy a brand domain later as a redirect” part of the hypothesis. It does not confirm that a subfolder is clearly better than the subdomain already in use.

### Why a new canonical domain is the wrong move now

- `datatalks.club` was registered on 19 September 2020 (RDAP, registrar GoDaddy, expires 19 September 2030). The Wayback Machine’s first successful capture is 20 October 2020. The domain is a little over six years old.
- Moz URL Metrics, last crawl 1 October 2026: Domain Authority 34, homepage Page Authority 45, spam score 5. The root domain has 1,140 referring domains. The homepage itself has 591. That is already in the same range as neue fische (DA 32, 918 referring domains) and above Spiced Academy (DA 25, 611). Le Wagon is in a different league (DA 59, 5,114). A new domain starts near zero and would have to catch up with those sites in about four and a half months (15 November 2026 to 1 April 2027 is 137 days).
- The main site currently publishes 1,548 URLs in its sitemaps (846 in `https://datatalks.club/sitemap.xml`, 702 in `https://datatalks.club/podwiki/sitemap.xml`). A 15 November Google `site:datatalks.club` search returned indexed pages (books, docs, FAQ, people, and `courses.datatalks.club`). `site:courses.datatalks.club` is also indexed (Zoomcamp years 2024 to 2026). `site:academy.datatalks.club` returned no results in the same check. The academy site is new and is not in Google’s index yet.
- Moz has not crawled `academy.datatalks.club` (HTTP code 0, 0 referring domains to the page or the subdomain). `courses.datatalks.club` already has Page Authority 34 and 52 referring domains to that subdomain. Subdomains of this root can gain indexation and links over time. They do not get it automatically on day one.
- The Morrowen experiment (Deana Burke, reported by Cybernews, Inc. and others in 2026) showed that a 3-page site plus one Substack post can be named by ChatGPT with browsing on, for four narrow queries, after three weeks, with no fake reviews. That is a real tactic for long-tail questions. It is a weak reason to leave a six-year-old domain. The queries we care about (“Bildungsgutschein AI course Berlin”, “KI Weiterbildung Bildungsgutschein”) already have dedicated pages from Spiced, Le Wagon, WBS, neue fische, Turing College, Ironhack and others. A new brand also splits the entity that language models already know as DataTalks.Club.
- Today the datatalks.club homepage does not link to the academy at all. It does link to `courses.datatalks.club` and to blog posts about the Zoomcamps. That missing link is a bigger problem than the choice between a subfolder and a subdomain.

HypeStat still lists traffic and a “Google Index 575” figure for datatalks.club, but that profile was last updated about 1,263 days before this check (around mid-2023). Those numbers are not used here.

### Subfolder versus the live subdomain

Google’s public position (John Mueller, on the record in several Search Central sessions) is that a subdomain and a subfolder can both rank, and that you should pick a structure you can keep. Changing URLs has a cost because Google has to recrawl them.

Practical differences in this case:

- A subfolder sits on a site Google already crawls and that already has 1,140 referring domains. New academy pages would be internal pages of that site. Homepage links would be ordinary internal links.
- The subdomain does not inherit those links automatically. Moz currently shows zero backlinks to it, and Google did not return it in a `site:` search on 15 November 2026. That can be fixed: add homepage and blog links, submit `https://academy.datatalks.club/sitemap.xml` (6 URLs today: home, both tracks, sessions, privacy, impressum) in Search Console, and request indexing.
- The organisation already runs a successful course property on a sibling subdomain (`courses.datatalks.club`). Keeping the paid school on `academy.datatalks.club` is consistent with that.
- The sessions on 23 November, 30 November and 7 December 2026 already use academy.datatalks.club URLs, including the registration form. A move in the next three weeks can break that funnel.
- Because the academy subdomain has almost no inbound links yet, a later move to `datatalks.club/academy/` (with 301s from every academy URL) is still cheap if we decide we want one URL tree. After the sessions, in January 2027, there are still about three months before the April start.

What to do now:

1. Keep `https://academy.datatalks.club/` as the live site through the Hireable With AI sessions.
2. Add a clear link from the datatalks.club homepage, and from the relevant Zoomcamp blog posts, to the academy. Use the approved copy bank for the wording.
3. In Google Search Console, confirm there is a Domain property for datatalks.club (the DNS TXT records already exist; see Tools) and submit the academy sitemap. Do the same in Bing Webmaster Tools.
4. After the sessions, decide whether to move to `datatalks.club/academy/` or stay on the subdomain. Either is acceptable. Do not run the same pages on both.
5. Do not buy a domain until I say yes. If a brand domain is bought later, point it at the canonical academy URLs; do not build a second site on it.

## Backup domains, if a redirect is wanted later

Checked with RDAP on 15 November 2026. Available (registry returned 404 / “no such domain”): `datatalks.academy`, `datatalks.school`, `datatalks.education`, `datatalksacademy.com`, `datatalksacademy.de`, `datatalks-academy.com`, `datatalks-academy.de`, `datatalksschule.de`. Already taken: `dtc.academy` (since 2020), `dtc.school` (since 2019), `dtcacademy.com` (since 14 March 2005), `datatalks.de` (active, last changed 5 September 2022), `datatalks.com` (re-registered 17 October 2026 through DropCatch.com, nameservers at Afternic, so it is on the aftermarket, not a standard registration). RDAP for `datatalks.dev` and `datatalks.io` failed from this network (TLS errors); they were not used in the shortlist.

If one domain is bought later as a redirect, these three are the shortlist. Preferred first: `datatalks.academy`.

- `datatalks.academy`: short, says “DataTalks” and “school”, easy to say. Best brand match for a redirect. First-year promos are much cheaper than renewal, so plan for the renewal.
- `datatalksacademy.com`: familiar TLD, cheaper to keep than .academy, slightly longer to say. Good if we also want a .com we control.
- `datatalksacademy.de`: cheapest, useful for German searchers and Berater who type a .de. Needs a German administrative contact at many registrars.

I compared registrar prices (Porkbun, Cloudflare, INWX, Namecheap) on 15 November 2026; I do not publish them here.

Trademark notes, not a legal opinion: `dtcacademy.com` has been registered since 2005, so “DTC Academy” as a standalone .com brand is a poor idea. `datatalks.com` was drop-caught in October 2026 and is sitting on Afternic; it is not a normal new-registration price. `datatalks.de` is already registered by someone else. Using “DataTalks.Club Academy” and a `datatalks.*` redirect extends the existing brand. No EUIPO or DPMA search was filed for this note.

## SEO plan

### Target queries

The valuable queries are specific, not generic “AI course”. English and German both matter: the programme is taught in English, the voucher conversation is in German, and Berater search in German.

Serpstat’s German Google database (`g_de`), checked 15 November 2026, returned a monthly volume for only 3 of 27 exact queries. The other 24 had no row. That usually means the volume is too low for the database to report, not that nobody will search them. Reported figures:

| Query | Approx. monthly volume (Germany) | Difficulty (Serpstat 0–100) |
| --- | --- | --- |
| bildungsgutschein | 9,900 | 7 |
| ki weiterbildung | 2,400 | 10 |
| bildungsgutschein berlin | 140 | 8 |

No volume row (among others): “bildungsgutschein bootcamp”, “bootcamp berlin bildungsgutschein”, “KI Weiterbildung Bildungsgutschein”, “Weiterbildung KI Entwickler”, “AI Engineering Bootcamp”, “AI Engineering course Germany”, “AI engineering course Berlin”, “agentic engineering”, “agentic engineering course”, “AI bootcamp Berlin”, “Bildungsgutschein KI Kurs”, “DataTalks Academy”, “Hireable With AI”, “Claude Code Kurs”.

Earlier internal research (academy market sizing, 14 November 2026) already found that “Agentic Engineering” as a phrase is almost never searched, while job titles favour “AI Engineer”. Treat “agentic engineering course” as a page we need for AI-search and for people who already use the term, not as a large Google-volume keyword.

Work the pages around four intents, in both languages where it is natural:

1. Voucher plus topic plus place: “Bildungsgutschein KI Weiterbildung Berlin”, “AI course with Bildungsgutschein Berlin”.
2. Track plus country: “AI Engineering course Germany”, “AI Engineering Weiterbildung”, “agentic engineering course Germany”.
3. Audience plus outcome: “KI Weiterbildung für Entwickler”, “AI course for experienced developers Germany”.
4. Brand and series: “DataTalks.Club Academy”, “Hireable With AI”.

Do not invent a search-volume number where Serpstat had no row. Use Search Console and Keyword Planner (see Tools) once the pages are live to see what actually gets impressions.

### Who ranks now

The 15 November 2026 Google results in Germany (desktop, with AI Overviews) for the three test questions were occupied by existing AZAV bootcamps and by course-comparison blogs. DataTalks.Club Academy did not appear in the organic lists or in the AI Overviews.

Typical pages that do appear:

- Spiced Academy: programme pages (`/en/program/ai-engineering`, `/de/program/agentic-ai`) plus a long Bildungsgutschein explainer (`/de/learn-to-code-free`) and a page for case workers.
- Le Wagon: city page for Data Science & AI in Berlin, plus a financing page that lists AZAV measure numbers.
- WBS Coding School / WBS TRAINING: course pages and a 2027 “KI Weiterbildung mit Bildungsgutschein” guide.
- neue fische: Data Science & KI and machine-learning / agentic tracks, with dates, language, and “100 % Bildungsgutschein” in the title.
- Turing College: a dedicated “AI Engineering … Bildungsgutschein” landing, in German and English, aimed at developers with at least a year of programming.
- Ironhack, IfaDW, Syntax, MSIT, Cybersteps, Digitale Leute School, GFN and others: the same pattern, a course page plus a voucher page.

What those pages have in common, and what we should copy in structure (not in wording): one URL per programme, a separate URL that explains the Bildungsgutschein in plain language, start dates, format, language, duration, and who the course is for. Several also keep a German and an English version. We will use the copy bank, we will not promise a job, and we will not put legal disclaimer blocks in the marketing text (those belong in the terms at purchase, per the 15 November copy rule).

### Pages to build (on the canonical academy host)

One page per intent, written in plain language, titles in Title Case. Start from the copy bank. Suggested set:

- Home, Agentic Engineering, AI Engineering, and Sessions (already live).
- A Bildungsgutschein guide (English and German): what the voucher is, that AZAV certification is planned, how to prepare for the Berater conversation. No “we cannot guarantee” boilerplate in the marketing body; be concrete and honest.
- “AI Engineering Course in Germany” and “Agentic Engineering Course in Germany” (and German equivalents) as the query-shaped programme pages, or as clearly titled sections if we keep a single page per track.
- “AI Course for Experienced Developers” / “KI Weiterbildung für Entwickler”.
- Hireable With AI session pages that can outlive the Meetup event (the series dates, what each evening covers, how to register).
- A short FAQ, including the voucher, who the programme is for, Berlin or online, and duration, using one consistent set of facts.
- After AZAV: a page with the Maßnahmenummer, and listings on KURSNET and mein NOW. Those directories are how many Berater and comparison sites discover a course.

Each page should state the facts in a way a language model can quote: who it is for (experienced developers), what is taught, format, language, start (April 2027), place (Berlin or live online), size (about 15 seats), and that a Bildungsgutschein is the planned payment route after certification.

### How the new URLs should relate to the rest of the club

- Canonical host: `academy.datatalks.club` for now (or `datatalks.club/academy/` if we move after the sessions). One canonical, not both.
- `datatalks.club` should link to the academy from the homepage and from relevant course and blog pages. That is the main internal-link job.
- `courses.datatalks.club` should mention the academy where it is natural (for example on LLM Zoomcamp or AI Dev Tools pages), with a clear difference: those are free community courses, the academy is the full-time paid programme.
- A future `datatalks.academy` (or the other backup domains) should 301 to the canonical academy URLs, including the path where possible.
- If we later move from the subdomain to the subfolder, 301 every published academy URL and update Search Console, Meetup, and the copy-bank links in one pass.

### The honest version of the Morrowen tactic

Burke’s test worked for narrow questions, with browsing on, in ChatGPT, after one clear site and one public post, with no fake reviews and no Reddit spam. Claude and Gemini did not name Morrowen. Broad queries (“best”, “cheapest”) did not either.

For a real school, do the same things, and only those things:

- Publish a few factual pages that answer the exact questions people ask, on the known DataTalks.Club property.
- Write one public post on a property we already have (the DataTalks.Club blog, the newsletter, and a LinkedIn post). Say what the programme is, who it is for, when it starts, and how the voucher is supposed to work once AZAV is done.
- Get listed in the official directories after certification (KURSNET, mein NOW), and on the comparison sites that already rank (the ones that appeared in today’s baselines: deinbildungsgutschein.de, WBS and Turing blog lists, and similar). That is earned presence, not invented reviews.
- Repeat the three test questions in ChatGPT (browsing on), Perplexity, and Google AI Overviews about three weeks after the pages and the post are live, then again after AZAV listings go up.

Do not buy reviews, do not spam Reddit, do not stand up a second brand that pretends to be older than it is.

### Three-week test and baseline (15 November 2026, Europe/Berlin)

Use these three questions each time, in the same wording:

1. “What AI engineering courses in Berlin can I pay for with a Bildungsgutschein?”
2. “Which agentic engineering course is there for experienced developers in Germany?”
3. “Welche Weiterbildung für erfahrene Entwickler in KI gibt es in Berlin mit Bildungsgutschein?”

Check ChatGPT with browsing on, Perplexity, and Google AI Overviews (Germany). Record whether DataTalks.Club Academy is named, which URL is cited, and who else is named. The 15 November baseline:

**ChatGPT (web search on, country DE).** Academy was not named in any of the three answers, and academy.datatalks.club was not cited.

- Q1 named Data Science Retreat, MSIT “AI for Developers”, Syntax Institut, then other online options. Sources were led by deinbildungsgutschein.de, joinmsit.de, ifadw.de, neuefische.de and spiced-academy.com.
- Q2 treated “agentic engineering” as short professional courses for developers who already ship code: Fast Lane (Claude Code), GFU Cyrus, workshops.de, KEGON Academy, hackers&wizards. These are mostly 2 to 5 day paid workshops, not a full-time voucher programme.
- Q3 (German) again led with MSIT, Data Science Retreat and Syntax, plus IfaDW.

**Perplexity.** The brand DataTalks.Club is already visible, but the academy is not yet understood as a full-time voucher programme.

- Q1 recommended Turing College’s AZAV AI Engineering programme and said it did not find DataTalks.Club Academy as a Bildungsgutschein provider. It cited the Meetup group and datatalks.club, plus several Turing pages and a WBS comparison post.
- Q2 pointed at the free AI Dev Tools Zoomcamp and the Nebius production-agents course. It mentioned a “DataTalks.Club Academy landing-page property” but then described the free club courses, not the April 2027 programme.
- Q3 recommended Turing College, Cybersteps and neue fische. It cited datatalks.club and a podcast page, but it did not name the academy as a Weiterbildung.

**Google AI Overviews (Germany, desktop).** Academy was not named.

- Q1 Overview named Spiced, WBS Coding School, Le Wagon Berlin, Ironhack and TSA. Organic results were led by the WBS “best AI bootcamps” post, Spiced, Le Wagon, TSA, Ironhack and WBS’s voucher page.
- Q2 Overview named the AI Engineering Summit Berlin (16–20 November 2026), embarc’s Agentic Engineering Bootcamp, neue fische’s Agentic Machine Learning Engineer track, and the AI Coding Summit. Organic results for this wording were weak (Udemy and certificate pages, a KnowledgeHut blog).
- Q3 Overview named WBS TRAINING, WBS Coding School, “AI Academy Berlin”, and referred to alfatraining, Mod Education and DCI. Organic results were led by IfaDW, WBS TRAINING, HCO, the WBS 2027 guide and other voucher blogs.

Re-check around 6 December 2026 (three weeks after this baseline, and after the first two sessions), and again once the factual academy pages and a public post are live. A later check should follow the KURSNET listing.

## Tools

### Google Search Console

What it does for us: shows which queries already get impressions, indexation errors, and whether Google has the academy sitemap. The URL Inspection tool is how we ask Google to crawl new pages. A Domain property covers every subdomain, including academy and courses.

Price: free. [Search Console](https://search.google.com/search-console)

Already set up for the root domain, at least at the DNS level: on 15 November 2026, `datatalks.club` had two Google site-verification TXT records. Two records usually mean two Google accounts or two properties were verified over time. `academy.datatalks.club` has no `google-site-verification` TXT of its own (its only TXT value was `datatalksclub.github.io.`). If the existing property is a Domain property (`datatalks.club`), academy is already in scope and we only need to add the sitemap and confirm access. If it is only a URL-prefix property for `https://datatalks.club`, academy is not included and we should add a Domain property (the TXT records are already there) or a prefix property for `https://academy.datatalks.club`. Someone with the Search Console login needs to check which it is.

### Bing Webmaster Tools

What it does for us: indexation and queries in Bing, which also feeds some Copilot answers. You can import a verified site from Search Console.

Price: free. [Bing Webmaster Tools](https://www.bing.com/webmasters)

No Bing verification TXT (`MS=…`) was present on datatalks.club in this DNS check, and the homepage had no `msvalidate` meta tag. Treat this as not yet set up.

### Analytics: what is on the site now, and Plausible or Umami

On 15 November 2026:

- `academy.datatalks.club` has no analytics snippet in the HTML or in the main Astro script. The script sends form submits to a backend and can open a Google Form. There is no Plausible, Umami, Google Analytics, or GTM tag on the academy site.
- `datatalks.club` uses Google Tag Manager. Which tags sit inside the container cannot be seen from the HTML alone.
- `courses.datatalks.club` had no obvious analytics tag on the homepage in this check.

[Plausible](https://plausible.io/): cookie-free, EU-hosted, can show Search Console queries in the same dashboard. No free cloud plan; a 30-day trial.

[Umami](https://umami.is/pricing): cookie-free, open source, and a real free cloud tier (Hobby: one website, 100,000 events per month, 6 months of retention). Self-hosting is also free.

For a German-facing school, a cookie-free tool is simpler than adding the main GTM container, which may load Google Analytics and a cookie banner. Umami Hobby is enough to start. Plausible is the nicer EU-hosted option if we are willing to pay after the trial, and it has a built-in Search Console view.

### AI visibility trackers

These repeat prompts in ChatGPT, Google AI Overviews, Perplexity and others, and tell you whether the brand is named. Useful once we are tired of doing the three-question test by hand. Not needed on day one.

- [Otterly.ai](https://otterly.ai/pricing): tracks prompts across AI search engines, daily. The cheapest dedicated option. No free plan, a free trial.
- [Peec AI](https://peec.ai/pricing): prompt tracking on three models you choose, daily. No free plan.
- [Profound](https://www.tryprofound.com/pricing): enterprise AI-search analytics. A 7-day free trial only.
- [Semrush AI Visibility Toolkit](https://www.semrush.com/kb/1493-ai-visibility-toolkit): prompt tracking next to the rest of Semrush. No free trial for the toolkit.

### Ahrefs, Semrush, and Keyword Planner

[Ahrefs](https://ahrefs.com/pricing): backlinks, keyword ideas, and site audits. Paid plans, plus a free account with limited tools (keyword generator, website authority checker, limited backlink checker).

[Semrush](https://www.semrush.com/pricing/): keywords, competitors, site audit, plus the AI toolkit above. Paid plans, plus a free plan with 1 demo project and 10 reports per day.

[Google Keyword Planner](https://ads.google.com/home/tools/keyword-planner/): the closest thing to official search-volume data. Free with a Google Ads account (billing details usually have to be entered; you do not have to run ads). This is the tool to use when we want volume numbers beyond the three Serpstat rows above.

### What to use now, and the one paid tool to add later

Minimal free stack:

1. Google Search Console, as a Domain property for datatalks.club (DNS verification is already there). Submit the academy sitemap and inspect the four public pages.
2. Bing Webmaster Tools, imported from Search Console.
3. Google Keyword Planner, for German and English volume once we have a query list.
4. Umami Hobby on academy.datatalks.club, so the school has its own traffic log (it currently has none). Or Plausible after the 30-day trial if we prefer EU hosting and the Search Console panel.
5. A short spreadsheet with the three test questions, repeated every three weeks, until a paid tracker is worth it.

The one paid tool to add later: Otterly's smallest plan, after the factual pages and the first public post are live. It is the cheapest dedicated way to watch ChatGPT, AI Overviews and Perplexity without buying a full Semrush or Ahrefs plan. Do not start with Peec, Profound, Semrush, or Ahrefs. Revisit Ahrefs or Semrush only if we also need a paid backlink and keyword suite, which Keyword Planner and Search Console do not fully replace.

## Method and sources

- Domain age and registrar: RDAP for `datatalks.club` at `rdap.nic.club`, 15 November 2026. First archive: [Wayback CDX](https://web.archive.org/web/20201020203303/https://www.datatalks.club/).
- Authority and referring domains: Moz URL Metrics, 15 November 2026, for datatalks.club, academy.datatalks.club, courses.datatalks.club, neuefische.de, spiced-academy.com and lewagon.com.
- Indexation: sitemaps fetched the same day; Google `site:` queries; academy homepage, robots.txt and sitemap checked live.
- DNS and Search Console: TXT records for datatalks.club and academy.datatalks.club via Google DNS and Cloudflare DNS-over-HTTPS, 15 November 2026.
- Keyword volumes: Serpstat `g_de`, 15 November 2026.
- Baselines: ChatGPT (country DE, web search on), Perplexity, Google organic + AI Overviews (Germany). A separate Google “AI Mode” crawl returned no answer or failed; the Overviews above are the Google AI baseline.
- Analytics: live HTML and the academy Astro bundle, 15 November 2026.
- Morrowen write-ups: [Cybernews](https://cybernews.com/ai-news/chatgpt-fake-deodorant/), Inc., Marketplace, and Burke’s own description of a cheap domain, a 3-page site, and one Substack post.
- Google’s subdomain vs subfolder comments: Search Engine Journal write-ups of John Mueller’s Search Central remarks (linked from the research notes above).
