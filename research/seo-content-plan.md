# DataTalks.Club Academy: SEO and AI-search content plan (15 November 2026)

I approved this plan on 15 November 2026. Updated the same day: German content is minimal. There is only one German page, the Bildungsgutschein guide at `/academy/bildungsgutschein/`. Every other academy page and every post is in English. German keywords map to that single German page.

Action plan after two decisions: move to `datatalks.club/academy` and show both courses as existing programs with a waitlist, and use the instructor line "more than 100,000 students". Builds on [the domain and SEO plan](domain-and-seo-plan.md). No domain was purchased.

Course page drafts, the approved instructor line, the approved program basis and the selected public testimonials live in our copy bank. The public testimonials are in [testimonials.md](testimonials.md).

## Priorities

1. Move the canonical site to `https://datatalks.club/academy/` now, with 301s from every `academy.datatalks.club` URL. Put both course pages live as existing programs, no active cohort, "Join the Waitlist", plus the approved instructor line on home and both course pages.
2. Publish the factual set in English: home, two course pages, Hireable With AI sessions, and a short FAQ. The only German page is the Bildungsgutschein guide. Then one public post in English (blog, newsletter, LinkedIn) that states the same facts and links to the waitlists and to the German voucher page.
3. Measure weekly: Monday AI-search check (ChatGPT, Perplexity, Google AI Overviews) with the three baseline questions; Search Console; Umami; confirmed waitlist leads by source.

## Site structure

Canonical host: `https://datatalks.club/academy/`. One canonical, not both. Redirect `https://academy.datatalks.club/*` to the matching `/academy/` path. Update Meetup, emails, and copy-bank links in the same pass. Link to the academy from the datatalks.club homepage and from relevant Zoomcamp pages.

All pages below are in English, except the Bildungsgutschein guide.

| Path | Page | Language | Status |
| --- | --- | --- | --- |
| `/academy/` | Home: both programs, instructor line, waitlists, link to sessions and to the German voucher page | English | Rebuild (live home still frames tracks as a vote) |
| `/academy/agentic-engineering/` | Agentic Engineering, waitlist, short voucher line with a link to the German page | English | Rebuild from draft |
| `/academy/ai-engineering/` | AI Engineering, waitlist, short voucher line with a link to the German page | English | Rebuild from draft |
| `/academy/sessions/` | Hireable With AI series (titles already approved) | English | Keep, retarget URLs |
| `/academy/bildungsgutschein/` | Bildungsgutschein guide: what the voucher is, AZAV certification in progress, how to prepare for the Berater, links to both English course pages | German (the only German page) | New |
| `/academy/faq/` | Short FAQ: who it's for, format, voucher, April 2027 | English | New (can share answers with course FAQs) |
| `/academy/impressum/`, `/academy/privacy/` | Legal pages | German legal text as required, otherwise keep as they are | Keep, retarget |
| The German voucher page, after AZAV | Maßnahmenummer | German | After certification |

There is no `/academy/bildungsgutschein/de/` and no English duplicate of the voucher guide. A short English voucher line stays on the course pages and the home, and points to the German page.

## Target keywords

This is the list of keywords that matter for us. Volumes are monthly averages from Serpstat's German Google database (`g_de`), pulled on 15 November 2026. "Unknown" means Serpstat had no row for that exact query, not that nobody searches it. Berlin-specific volumes are unknown: this check had no Berlin database, only Germany. A query like "bildungsgutschein berlin" still has a Germany volume (140); that is not a Berlin-only figure.

Google Keyword Planner was not available in this check. Re-check volumes in Keyword Planner and Search Console once the pages are live.

Close word-order variants that share the same volume are listed once, with the variants named in the notes. German-language keywords all target `/academy/bildungsgutschein/`. English course and brand keywords target the English pages. The German page should link clearly to both English waitlists.

Do not target "llm course" or "llm courses" for the academy. Serpstat reports 70 and 70 monthly in `g_de`, but the related queries are about a Master of Laws degree (courses in the UK, India, legal practice), not large language models.

| Keyword | Lang | Volume DE | Volume Berlin | Priority | Intent | Target page |
| --- | --- | --- | --- | --- | --- | --- |
| bildungsgutschein | DE | 9,900 | unknown | High | Commercial (broad) | `/academy/bildungsgutschein/` |
| bildungsgutschein agentur für arbeit | DE | 5,400 | unknown | High | Informational | `/academy/bildungsgutschein/`. Same volume: "bildungsgutschein von der agentur für arbeit", "agentur für arbeit bildungsgutschein" |
| ki weiterbildung | DE | 2,400 | unknown | High | Informational | `/academy/bildungsgutschein/` |
| bildungsgutschein beantragen | DE | 1,900 | unknown | High | Informational | `/academy/bildungsgutschein/`. Same volume: "beantragung bildungsgutschein" |
| bildungsgutschein voraussetzungen | DE | 1,600 | unknown | High | Informational | `/academy/bildungsgutschein/`. Several word-order variants at 1,600 |
| bildungsgutschein jobcenter | DE | 1,600 | unknown | High | Informational | `/academy/bildungsgutschein/`. Close variants: "jobcenter bildungsgutschein" 1,300, "bildungsgutschein vom jobcenter" 1,300, "bildungsgutschein arbeitsagentur" 1,300 |
| weiterbildung ki | DE | 1,000 | unknown | High | Informational | `/academy/bildungsgutschein/` |
| weiterbildung mit bildungsgutschein | DE | 880 | unknown | High | Informational / commercial | `/academy/bildungsgutschein/`. Same volume: "weiterbildung bildungsgutschein", "weiterbildungen bildungsgutschein", "bildungsgutschein für weiterbildung" |
| weiterbildung auf englisch | DE | 390 | unknown | High | Informational | `/academy/bildungsgutschein/` |
| weiterbildung softwareentwickler | DE | 170 | unknown | Medium | Informational | `/academy/bildungsgutschein/` |
| umschulung softwareentwickler | DE | 140 | unknown | Medium | Informational | `/academy/bildungsgutschein/` |
| bildungsgutschein berlin | DE | 140 | unknown | High | Commercial | `/academy/bildungsgutschein/` |
| bildungsgutschein englisch | DE | 40 | unknown | High | Informational | `/academy/bildungsgutschein/` |
| ki in der weiterbildung | DE | 30 | unknown | Low | Informational | `/academy/bildungsgutschein/` |
| ki weiterbildung bildungsgutschein | DE | unknown | unknown | High | Commercial | `/academy/bildungsgutschein/` |
| ki weiterbildung berlin | DE | unknown | unknown | High | Commercial | `/academy/bildungsgutschein/` |
| bildungsgutschein ki weiterbildung berlin | DE | unknown | unknown | High | Commercial | `/academy/bildungsgutschein/` |
| bildungsgutschein ki kurs | DE | unknown | unknown | Medium | Commercial | `/academy/bildungsgutschein/` |
| weiterbildung ki entwickler | DE | unknown | unknown | Medium | Informational | `/academy/bildungsgutschein/` |
| umschulung ki | DE | unknown | unknown | Medium | Informational | `/academy/bildungsgutschein/` |
| english courses bildungsgutschein | DE / EN | unknown | unknown | High | Commercial | `/academy/bildungsgutschein/` |
| ai engineering weiterbildung | DE / EN | unknown | unknown | Medium | Commercial | `/academy/bildungsgutschein/` |
| ki kurs berlin | DE | unknown | unknown | Medium | Commercial | `/academy/bildungsgutschein/` |
| ki bootcamp berlin | DE | unknown | unknown | Medium | Commercial | `/academy/bildungsgutschein/` |
| claude code kurs | DE | unknown | unknown | Low | Commercial | `/academy/bildungsgutschein/` |
| ai engineering course | EN | unknown | unknown | High | Commercial | `/academy/ai-engineering/` |
| ai engineering course germany | EN | unknown | unknown | High | Commercial | `/academy/ai-engineering/` |
| ai engineering course berlin | EN | unknown | unknown | High | Commercial | `/academy/ai-engineering/` |
| ai engineering bootcamp | EN | unknown | unknown | Medium | Commercial | `/academy/ai-engineering/` |
| ai bootcamp berlin | EN | unknown | unknown | Medium | Commercial | `/academy/ai-engineering/` |
| ai course berlin | EN | unknown | unknown | Medium | Commercial | `/academy/ai-engineering/` |
| ai course for experienced developers germany | EN | unknown | unknown | Medium | Commercial | `/academy/` |
| ai course with bildungsgutschein berlin | EN | unknown | unknown | High | Commercial | `/academy/bildungsgutschein/` (only dedicated voucher URL; English course pages keep a short line and a link) |
| agentic engineering | EN | unknown | unknown | Medium | Informational / AI-search | `/academy/agentic-engineering/` |
| agentic engineering course | EN | unknown | unknown | Medium | Commercial / AI-search | `/academy/agentic-engineering/` |
| agentic engineering course germany | EN | unknown | unknown | Medium | Commercial / AI-search | `/academy/agentic-engineering/` |
| coding agents course | EN | unknown | unknown | Medium | Commercial | `/academy/agentic-engineering/` |
| claude code course | EN | unknown | unknown | Low | Commercial | `/academy/agentic-engineering/` |
| hireable with ai | EN | unknown | unknown | Medium | Navigational | `/academy/sessions/` |
| datatalks academy | EN | unknown | unknown | Medium | Navigational | `/academy/` |
| datatalks.club academy | EN | unknown | unknown | Medium | Navigational | `/academy/` |

"Agentic engineering" phrases stay on the list for AI-search and for people who already use the term, not because they have large Google volume.

## What each page answers

### Home, `/academy/` (English)

Answers: what the academy is, who it's for (experienced developers, 2+ years), that both programs exist, next start April 2027, about 15 seats, English, Berlin or live online, instructor, waitlist, link to the free series and to the German voucher page.

### Agentic Engineering, `/academy/agentic-engineering/` (English)

Answers: what agentic engineering is (approved session wording), what the program is based on (approved wording), who it's for, what you'll build, modules including Introduction to AI Engineering and interview prep, format, waitlist, a short Bildungsgutschein line with a link to the German page.

### AI Engineering, `/academy/ai-engineering/` (English)

Answers: what AI engineering is (approved session wording), what the program is based on (approved wording), who it's for, what you'll build, modules including the agentic cross-module and interview prep, format, waitlist, a short Bildungsgutschein line with a link to the German page.

### Sessions, `/academy/sessions/` (English)

Answers: the three free evenings, dates, format, registration. Titles stay in the copy bank.

### Bildungsgutschein guide, `/academy/bildungsgutschein/` (German, the only German page)

Answers: what the voucher is, that AZAV certification is in progress, how to apply and what the Voraussetzungen are, Agentur and Jobcenter, that the programs are taught in English, how to prepare for the Berater conversation, and links to both English course waitlists. Concrete and honest, no "we cannot guarantee" boilerplate in the marketing body (that belongs in purchase terms).

This is the page Berater, comparison sites, and German Google queries should land on.

### FAQ, `/academy/faq/` (English)

Answers: who it's for, duration, language, Berlin or online, waitlist, voucher (with a link to the German page), both programs, no active cohort, April 2027. Same facts as the course FAQs, in one place a model can quote.

## Posts, next six weeks

All public copy starts from the copy bank. Draft first; nothing is posted or sent without my yes. Session titles below are approved. Posts are in English. There is no German blog post or German newsletter issue in this plan.

| When (Europe/Berlin) | Channel | What it is |
| --- | --- | --- |
| This week, as soon as the new URLs are live (16 to 21 November 2026) | Blog on datatalks.club, newsletter, LinkedIn | One factual public post in English: both programs exist, who they are for, April 2027, about 15 seats, waitlist links, Bildungsgutschein after AZAV certification (link to the German page), instructor line, link to Hireable With AI. This is the "one public post" in the GEO tactic. |
| Friday 20 or Saturday 21 November | Newsletter / LinkedIn / Meetup reminder | Session 1 reminder: AI Engineering vs Agentic Engineering, Monday 23 November, 17:00 Berlin, Zoom. |
| Tuesday 24 November | Blog or LinkedIn, newsletter if there is an issue | Recap of session 1, and waitlist links for both programs. |
| Friday 27 or Saturday 28 November | Reminder | Session 2 reminder: Agentic Engineering: How I Build Software with Coding Agents, Monday 30 November. |
| Tuesday 1 December | Recap | Recap of session 2, focus on the Agentic Engineering waitlist. |
| Friday 4 or Saturday 5 December | Reminder | Session 3 reminder: AI Engineering: How to Build Apps on Top of LLMs, Monday 7 December. |
| Around 6 December | Internal check | Three-week AI-search re-check of the baseline questions (see below). |
| Tuesday 8 December | Recap | Recap of session 3, focus on the AI Engineering waitlist. |
| Week of 14 December | Blog (English) and LinkedIn | Bildungsgutschein explainer in English, pointing at the German page `/academy/bildungsgutschein/`. |
| Week of 21 December | Newsletter and LinkedIn | Waitlist reminder: no active cohort, April 2027, both programs, free session recordings for people who missed the series. |

## After AZAV

When the certificates are in:

- Put the Maßnahmenummer on the German Bildungsgutschein page.
- List both measures on KURSNET and mein NOW. These are how many Berater and comparison sites discover a course.
- Ask to be included on the comparison pages that already rank in the 15 November baseline (deinbildungsgutschein.de, WBS and Turing lists, and similar). 
- Re-run the three AI-search questions after the listings go up.

## How we track success

1. Weekly Monday AI check (routine, about 09:00 Europe/Berlin). Same three questions, same wording, in ChatGPT (browsing on), Perplexity, and Google AI Overviews (Germany). Record whether DataTalks.Club Academy is named, which URL is cited, and who else is named. First scheduled check: Monday 16 November 2026. The 15 November baseline named none of our academy URLs.
   - "What AI engineering courses in Berlin can I pay for with a Bildungsgutschein?"
   - "Which agentic engineering course is there for experienced developers in Germany?"
   - "Welche Weiterbildung für erfahrene Entwickler in KI gibt es in Berlin mit Bildungsgutschein?"
2. Google Search Console (Domain property for datatalks.club, plus Bing). Indexation of the new `/academy/` URLs, sitemap submit, impressions and queries. Use Keyword Planner later for volumes we do not have.
3. Umami on the academy pages (Hobby is enough). Traffic by page, referrer, and campaign.
4. Confirmed waitlist leads (double opt-in) by source and by program. This is the number that matters for April 2027 seats.

Do not buy an AI-visibility tracker on day one. A small paid tracker is a later option, only after I say yes, once the pages and the first public post are live.

## What still needs my yes

The content plan itself is approved. Still open:

- The new and adapted lines in the course page drafts, including "Join the Waitlist", the short Bildungsgutschein wording, the home hero, and the 09:00 to 16:30 schedule (live pages currently say 16:00).
- Each public post or send, as usual, before it goes out.
- The Testimonials block on both course pages: four public quotes per page, verbatim from [testimonials.md](testimonials.md). Slack quotes are not used.
- Copy for the German Bildungsgutschein page, which has not been drafted yet.
