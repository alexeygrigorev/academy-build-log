# SEO and AEO Best Practices for DataTalksClub Academy

Research from 15 November 2026: which SEO, AEO and content practices work for a small, new education brand on a subfolder of an established domain, in a niche market (Germany, Bildungsgutschein, English-language AI courses). It builds on the [domain and SEO plan](domain-and-seo-plan.md) and the [SEO content plan](seo-content-plan.md).

How to read the evidence:

- Evidence strength: Strong = official docs or a large data study. Medium = credible practitioner study or case study. Weak = anecdote or vendor claim.
- Almost all AI citation and conversion studies use US and B2B software data. None of them measures German voucher courses.
- Live site facts come from HTTP requests to datatalks.club and academy.datatalks.club on 15 November 2026.

## Summary: top 10 practices, ranked by expected impact for us

1. Publish one consistent, quotable set of academy facts on every page and every profile, and say plainly how the Academy differs from the free Zoomcamps. Today the pages disagree on the start date, hours, seats and student numbers.
2. Finish the move properly: real server-side 301s (today the old host answers 200 with a meta refresh), the German page and the FAQ live (both 404 today), a complete sitemap, a Search Console property for `/academy/`, and Bing Webmaster Tools.
3. Add contextual internal links to the academy from the datatalks.club pages that already have links and traffic: the LLM Zoomcamp and AI Dev Tools Zoomcamp pages, related blog posts and the courses subdomain. The subfolder alone changes little.
4. Publish the single German page and aim it at the narrow intent we can win (KI-Weiterbildung, auf Englisch, erfahrene Entwickler, Bildungsgutschein). No hreflang. Do not word it as if the course is already fundable.
5. Get onto the third-party sources that AI engines already cite for these queries. Before AZAV: YouTube, LinkedIn, the build log. After AZAV: KURSNET and mein NOW, deinbildungsgutschein.de, Course Report. Choose the Maßnahme title now, because KURSNET requires the listing title to match it.
6. Put each free session on YouTube as a public video with chapters, and publish a recap page for each on `/academy/`. YouTube is the strongest measured correlate of AI brand mentions and the most cited domain in Google AI Overviews.
7. Write bottom-of-funnel pages first: "How to Get a Bildungsgutschein as an Experienced Developer", a cost page, one factual comparison of English-taught AI courses with a voucher, and curriculum deep dives. Skip broad top-of-funnel posts.
8. Measure with a repeated prompt panel (several runs per prompt, share of runs where we are named), the free Search Console and Bing AI reports, UTM-based AI referral tracking, and one "How did you hear about us?" question. The KPI stays confirmed waitlist signups from people in Germany who would pay with a voucher.
9. Name future events with the audience and format in the title, set Meetup topics, and announce a few weeks ahead. Use Luma only for in-person Berlin events, because Luma does not surface online events in Discover.
10. Do not spend time on things with no evidence or with risk: llms.txt, FAQ or Event schema for rich results, scaled AI pages, self-ranked "best" lists, unlabelled testimonials, any job or funding promise.

## Where the two earlier plans should change

| Earlier plan said | What the research shows | Change |
| --- | --- | --- |
| Domain plan: stay on the subdomain through the sessions, decide in January. | The move happened today. The old host is on GitHub Pages and cannot send a 301. It returns HTTP 200 with a canonical tag, a JavaScript redirect and an instant meta refresh (checked 15 Nov 2026). | Keep the move. Replace the stub pages with server-side 301s (section 2.1). |
| Content plan: FAQ page whose answers a model can quote, FAQ can share answers with course pages. | Good for readers and for answer engines. Google removed FAQ rich results for all sites on 7 May 2026 ([Google changelog](https://developers.google.com/search/updates)). | Keep the visible FAQ. Expect no rich result. FAQPage markup is optional. |
| Content plan: 25 German keywords, including "bildungsgutschein" at 9,900 searches a month ([content plan](seo-content-plan.md)), all mapped to one page. | Only 1.74% of new pages reach the top 10 within a year ([Ahrefs, 15 May 2025](https://ahrefs.com/blog/how-long-does-it-take-to-rank-in-google-and-how-old-are-top-ranking-pages/)). One page cannot serve the generic voucher intent and our niche intent equally. | Keep one page. Treat the head terms as context, and write the page for the modifier queries (section 2.4). |
| Content plan: weekly Monday check, three questions, one run each. | AI answers vary between runs. There is less than a 1 in 100 chance of getting the same brand list twice ([SparkToro and Gumshoe, 28 Jan 2026](https://sparktoro.com/blog/new-research-ais-are-highly-inconsistent-when-recommending-brands-or-products-marketers-should-take-care-when-tracking-ai-visibility/)). | More prompts, several runs each, report the share of runs. Every two weeks is enough (section 7). |
| Both plans: Otterly Lite later as the first paid tool. | Google Search Console now has a generative AI report, and Bing Webmaster Tools has an AI Performance report with citations and grounding queries. Both are free (section 1.9). | Use the two free reports first. Decide on a paid tracker in January. |
| Both plans: "list on KURSNET and mein NOW" and "a page with the Maßnahmenummer". | KURSNET bans promotional wording and bans the Maßnahmenummer inside the listing. The listing title must be the title on the Maßnahmezulassung ([BA Eingabehilfe, 31 Mar 2025](https://www.arbeitsagentur.de/datei/kursnet-eingabehilfe-weiterbildungsangebote_ba035945.pdf)). | Decide the Maßnahme titles with search in mind before certification. Keep the Maßnahmenummer on our own page only (section 1.7). |
| Content plan: recordings go to registrants by email. | Public replays get 3.7 times as many on-demand views as gated ones ([Livestorm, 1 Sep 2026](https://livestorm.co/webinar-benchmark-report-2026)), and YouTube mentions correlate most strongly with AI brand mentions ([Ahrefs, 12 Dec 2025](https://ahrefs.com/blog/ai-brand-visibility-correlations)). | Publish the recordings publicly on the DataTalks.Club YouTube channel as well. |
| Content plan: "hireable with ai" maps to `/academy/sessions/`. | The live sessions page is titled "Between jobs: the AI skills that get experienced developers hired" and does not contain the phrase "Hireable With AI" (live pages, 15 Nov 2026). | Pick one series name and use it in the page title, Meetup, YouTube and posts. |
| German draft meta description: "Mit Bildungsgutschein, nächste Gruppe April 2027." (draft) | The snippet reads as if funding is available now. Misleading statements about an approval fall under [§ 5 UWG](https://www.gesetze-im-internet.de/uwg_2004/__5.html). | Change the snippet to say that AZAV certification is in progress (section 5.4). |

## 1. AEO: being named and cited by AI engines

### 1.1 Treat AEO as SEO first: be indexed, crawlable and specific

**Do.** Make sure every academy page is indexed in Google and Bing, is readable without JavaScript, and is not blocked for search crawlers (Googlebot, Bingbot, OAI-SearchBot, PerplexityBot, Claude-SearchBot).

**Evidence.**

- Google, "AI features and your website": "To be eligible to be shown as a supporting link in AI Overviews or AI Mode, a page must be indexed" and "There are no additional technical requirements." ([Google Search Central](https://developers.google.com/search/docs/appearance/ai-features), no date on page).
- Google's Think with Google article of 17 June 2026: "That's why good SEO is good GEO (or AEO, or AI SEO, or whatever)." It says AI Mode is "built directly on top of our core ranking systems" ([Think with Google](https://business.google.com/us/think/search-and-video/ai-search-era-brand-authority-strategy/)). This is the original behind the X post by alexgroberman. The page I retrieved has no byline. The attribution to Brendon Kraham comes from [PPC Land](https://ppc.land/googles-vp-of-search-tells-cmos-good-seo-is-still-all-you-need-for-ai/).
- Google's AI optimization guide: "optimizing for generative AI search is optimizing for the search experience, and thus still SEO." ([Google Search Central](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide), no date on page).
- OpenAI: "Sites that are opted out of OAI-SearchBot will not be shown in ChatGPT search answers" ([OpenAI crawler docs](https://developers.openai.com/api/docs/bots), no date).
- Perplexity recommends "allowing PerplexityBot in your site's robots.txt file" ([Perplexity docs](https://docs.perplexity.ai/guides/bots), no date).
- Anthropic lists three bots (ClaudeBot, Claude-User, Claude-SearchBot) that honour robots.txt ([Anthropic support](https://support.claude.com/en/articles/8896518-does-anthropic-crawl-data-from-the-web-and-how-can-site-owners-block-the-crawler)). Brave Search is on Anthropic's subprocessor list with the purpose "Web Search" ([Anthropic trust centre](https://trust.anthropic.com/subprocessors); first reported by [TechCrunch, 21 Mar 2025](https://techcrunch.com/2025/03/21/anthropic-appears-to-be-using-brave-to-power-web-searches-for-its-claude-chatbot/)). That confirms the Claude and Brave claim from the Tim Soulo X post.
- Major AI crawlers did not execute JavaScript in a large log study ([Vercel and MERJ, 17 Dec 2024](https://vercel.com/blog/the-rise-of-the-ai-crawler)).
- Microsoft: "traditional SEO fundamentals still matter" ([Microsoft Advertising blog, 8 Oct 2025](https://about.ads.microsoft.com/en/blog/post/october-2025/optimizing-your-content-for-inclusion-in-ai-search-answers)).

**Strength.** Strong (official docs from Google, OpenAI, Perplexity, Anthropic, Microsoft).

**For us.** The root `robots.txt` blocks no AI or search bot and lists `https://datatalks.club/academy/sitemap.xml` (checked 15 Nov 2026). Keep it that way. The Astro pages ship their text in the HTML, which is what non-rendering crawlers need. The waitlist form needs JavaScript, and that is fine. Bing Webmaster Tools and a Search Console Domain property were set up on 15 November, with the academy sitemap submitted to both. What is still missing is real redirects from the old host (section 2.1). Bing matters because ChatGPT search works with "other search providers" ([OpenAI help](https://help.openai.com/en/articles/9237897-chatgpt-search)) and Copilot is grounded on Bing.

### 1.2 Direct answer blocks near the top of each page

**Do.** Open every page with two or three plain sentences that answer the page's main question and carry the core facts. Use definite wording. Keep one fact block that is identical across pages.

**Evidence.**

- Where ChatGPT quotes from: 44.2% of citations come from the first 30% of a page. Cited text uses definitive language 36.2% of the time against 20.2% for uncited text ([Kevin Indig via Search Engine Journal, 16 Feb 2026](https://www.searchenginejournal.com/the-science-of-how-ai-pays-attention/567597/); 18,012 citations, one platform).
- Microsoft on Q&A pairs: "Assistants can often lift these pairs word for word into AI-generated responses." It warns against putting "important answers in tabs or expandable menus" ([Microsoft Advertising blog, 8 Oct 2025](https://about.ads.microsoft.com/en/blog/post/october-2025/optimizing-your-content-for-inclusion-in-ai-search-answers)).
- Adding statistics, quotations and cited sources raised visibility in a simulated generative engine: "GEO can boost visibility by up to 40% in generative engine responses." ([Aggarwal et al., KDD 2024](https://arxiv.org/abs/2311.09735)). The test systems predate today's products.
- Counterweight from Google: "There's no requirement to break your content into tiny pieces for AI to better understand it." ([Google AI optimization guide](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide)).
- Conflicting detail: question-style headings averaged 3.4 ChatGPT citations against 4.3 for plain headings ([SE Ranking, 24 Nov 2025](https://seranking.com/blog/how-to-optimize-for-chatgpt/)), while Indig found that 78.4% of the questions in cited text came from headings (same Search Engine Journal article). Heading style is not settled.

**Strength.** Medium. One good single-platform study, one academic paper on older systems, official guidance that pulls in two directions.

**For us.** The course pages already open with a definition ("Agentic engineering is using tools like Claude Code or Cursor to write most of the code, while you decide what to build and check the result."). That is the right pattern. What is missing near the top is the fact set. Suggested fact block, built only from approved or live copy, to place directly under the hero on `/academy/`, both course pages, the FAQ and (in German) the voucher page:

> DataTalks.Club Academy is a full-time, live program in English for experienced software developers in Germany. There are two programs, Agentic Engineering and AI Engineering. The first cohort is planned for April 2027 and has about 15 seats. It takes about 3 months of full days, in Berlin or live online. I'm applying for AZAV certification so the Agentur für Arbeit can cover tuition with a Bildungsgutschein.

Do not hide FAQ answers in closed accordions that load on click. If the FAQ uses a disclosure element, the answer text must be in the HTML.

### 1.3 One consistent set of facts, on our pages and everywhere else

**Do.** Fix the contradictions on the live pages, then copy the same facts to every profile we control.

**Evidence.**

- Brand mentions on the web correlate with AI brand mentions more than links do: 0.664 for ChatGPT, 0.709 for AI Mode, 0.656 for AI Overviews, against 0.266 to 0.326 for Domain Rating ([Ahrefs, 12 Dec 2025](https://ahrefs.com/blog/ai-brand-visibility-correlations), 75,000 brands, correlation only).
- When a brand is mentioned in an answer its own URLs are cited 53.1% of the time, and 10.6% when it is not. The author recommends consistent brand naming and calls the mechanism "strongly supported behavioral evidence, not proven architecture" ([Seer Interactive, 24 Mar 2026](https://seerinteractive.com/insights/llm-ghost-citations-why-your-content-is-working-and-your-brand-isnt), 541,213 responses).
- Experts ranked "Citable / Specific Facts" fourth and "Cross-Web Consensus & Corroboration" eighth of 13 factors for Google AI visibility ([Zyppy survey of 130+ experts, 16 Sep 2026](https://signal.zyppy.com/p/google-ai-ranking-factors)). This is opinion, not measurement. It is the original behind the X post by aleyda.
- Our own baseline shows the problem: on 15 November Perplexity mentioned a "DataTalks.Club Academy landing-page property" and then described the free club courses ([domain plan](domain-and-seo-plan.md)).

**Strength.** Medium for brand mentions (large but correlational). Weak for "consistency causes citations": there is no controlled study.

**For us.** Contradictions found on 15 November between live pages and drafts:

| Fact | Version A | Version B |
| --- | --- | --- |
| Start | "There is no active cohort right now" (course page FAQ, live pages, 15 Nov 2026) | April 2027 (sessions page, German draft) |
| Daily hours | 09:00 to 16:00 (live course pages, 15 Nov 2026) | 09:00 to 16:30 (German draft) |
| Seats | 15 (live pages) | about 15 (German draft) |
| Students taught | 12,755 enrolled since 2024 (sessions page, live pages, 15 Nov 2026) | more than 100,000 (instructor.md) |
| Brand name | DataTalks.Club Academy (site) | DataTalksClub Academy (build log title, live pages, 15 Nov 2026) |
| Series name | Between jobs (sessions page) | Hireable With AI (plans, keyword list) |
| Audience | "developers who already write code" (home) | developers with 2+ years (sessions page, German draft) |

A model that reads these pages will repeat whichever line it lands on. Decide each row once, write it down once, and use it on: the four academy pages, the German page, the FAQ, the Meetup group and event descriptions, YouTube video descriptions, the LinkedIn page, the build log, Substack, the datatalks.club homepage and the relevant Zoomcamp pages. On the brand name, the build-log skill asks for "DataTalksClub" in social text. Keep that, but use "DataTalks.Club Academy" in page titles and state the other spelling once as an alternate name.

Add one sentence that separates the two things, on the academy home and the FAQ: "The Zoomcamps are free community courses. The Academy is a separate full-time, live program with about 15 seats."

### 1.4 FAQ and structured data: add a small accurate set, expect nothing from it

**Do.** Add minimal JSON-LD that matches the visible text. Do not expect rich results or AI citations from it.

**Evidence.**

- Google: "There's also no special schema.org structured data that you need to add." and "Structured data isn't required for generative AI search" ([AI features doc](https://developers.google.com/search/docs/appearance/ai-features), [AI optimization guide](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide)).
- Controlled test: "Adding schema produced no major uplift in citations on any platform." 1,885 pages that added JSON-LD against 4,000 controls ([Ahrefs, 11 May 2026](https://ahrefs.com/blog/schema-ai-citations/)). All test pages were already cited, so it says nothing about new pages.
- LLMs read schema as plain text. An address placed only in invalid JSON-LD was still returned by ChatGPT and Perplexity ([Mark Williams-Cook via Search Engine Journal, 16 Jun 2026](https://www.searchenginejournal.com/schema-llms-the-low-bar-for-evidence-in-geo/576090/)).
- FAQ rich results: restricted in August 2023 to "well-known, authoritative government and health websites" ([Google, 8 Aug 2023](https://developers.google.com/search/blog/2023/08/howto-faq-changes)), then removed for everyone: "This feature will no longer appear in Google Search starting May 7, 2026." ([Google changelog](https://developers.google.com/search/updates)).
- Pages with FAQ schema averaged 3.6 ChatGPT citations against 4.2 without ([SE Ranking, 24 Nov 2025](https://seranking.com/blog/how-to-optimize-for-chatgpt/), correlational).
- Course markup: Google deprecated the Course Info rich result on 12 June 2025 ([Google blog](https://developers.google.com/search/blog/2025/06/simplifying-search-results)). The Course list carousel remains, but "You must mark up at least three courses." ([Google Course doc](https://developers.google.com/search/docs/appearance/structured-data/course)). We have two.
- EducationalOccupationalProgram exists in schema.org ([schema.org](https://schema.org/EducationalOccupationalProgram), V30.1) but is not in Google's list of supported features ([Google search gallery](https://developers.google.com/search/docs/appearance/structured-data/search-gallery)).
- Organization markup has no required properties and belongs on the home page ([Google Organization doc](https://developers.google.com/search/docs/appearance/structured-data/organization)).
- Markup rules: "Don't mark up content that is not visible to readers of the page." ([Google structured data policies](https://developers.google.com/search/docs/appearance/structured-data/sd-policies)). Reviews that a business controls about itself are ineligible for stars ([Google review snippet doc](https://developers.google.com/search/docs/appearance/structured-data/review-snippet)).

**Strength.** Strong that Google does not need it and that the FAQ and Course Info rich results are gone. Medium that schema does not lift AI citations.

**For us.** None of the live academy pages has any JSON-LD (checked 15 Nov 2026). Cheap, accurate set to add in the Astro layout:

- `/academy/`: `Organization` (or `EducationalOrganization`) with `name` "DataTalks.Club Academy", `alternateName`, `url`, `logo`, `sameAs` (Meetup group, YouTube channel, LinkedIn, GitHub), `parentOrganization` DataTalks.Club.
- Each course page: `Course` with `name`, `description`, `provider`, `inLanguage` "en", and a `hasCourseInstance` with `courseMode` and the planned start. After AZAV, an `EducationalOccupationalProgram` with `timeToComplete` and `programPrerequisites` is optional. It has no Google feature.
- An instructor page (section 3.4): `ProfilePage` with a `Person`. Google supports this type ([Google ProfilePage doc](https://developers.google.com/search/docs/appearance/structured-data/profile-page)).
- `BreadcrumbList` on all pages. This rich result is still live ([Google Breadcrumb doc](https://developers.google.com/search/docs/appearance/structured-data/breadcrumb)).
- No `Review` or `AggregateRating` markup on our own pages. No `FAQPage` needed.

This is a half-day task. Do it after items 1 to 4 of the summary, not before.

### 1.5 llms.txt: no evidence that it helps AI search

**Do.** Skip it. If someone wants it for completeness it costs minutes and does no harm, but do not count it as AEO work.

**Evidence.**

- Google: "you can also stop worrying about new technical formats or special AI text files like LLMs.txt. At least for Google Search, they're not needed." ([Think with Google, 17 Jun 2026](https://business.google.com/us/think/search-and-video/ai-search-era-brand-authority-strategy/)). The Search Central guide adds "Google Search itself doesn't use them." ([AI optimization guide](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide)).
- John Mueller: "AFAIK none of the AI services have said they're using LLMs.TXT" ([Search Engine Journal, 17 Apr 2025](https://www.searchenginejournal.com/google-says-llms-txt-comparable-to-keywords-meta-tag/544804/)).
- Server logs, 137,210 domains, May 2026: 97% of valid llms.txt files got zero requests. AI bots made 19.5% of the requests that did happen, and OAI-SearchBot 0.74% ([Ahrefs, 15 Jun 2026](https://ahrefs.com/blog/llmstxt-study/)).
- One site, 90 days: 84 of 62,100+ AI bot visits touched llms.txt ([OtterlyAI, updated 5 Feb 2026](https://otterly.ai/blog/the-llms-txt-experiment/)).
- One site, 27 July to 15 August 2026: "the big-three AI crawlers fetched robots.txt 1,150 times combined, llms.txt 4 times" ([DEJAN, 15 Aug 2026](https://dejan.ai/blog/crawler-census-robots-llms-okf/)).
- Citations: "There's no correlation between AI citations and LLMs.txt." across about 300,000 domains ([SE Ranking](https://seranking.com/blog/llms-txt/); first covered by [Search Engine Journal on 20 Nov 2025](https://www.searchenginejournal.com/llms-txt-shows-no-clear-effect-on-ai-citations-based-on-300k-domains/561542/)). A second study of 18,621 domains: "/llms.txt adoption does not predict LLM citation behavior." ([Search Atlas, 19 Jun 2026](https://searchatlas.com/blog/limits-of-llms-txt-for-ai-search-citation-study/)).
- Of about 9.2 million AI answers, 73 cited an llms.txt URL ([Seer Interactive, 10 Nov 2026](https://www.seerinteractive.com/insights/llms.txt-vs-ai-info-page)).
- An evidence review of 54 sources scored llms.txt last of 23 factors at 2.0 out of 10 ([Zyppy, 7 May 2026](https://signal.zyppy.com/p/ai-citation-ranking-factors)).
- Where it does help: coding agents reading developer docs. In 2,400 runs, 404 errors per task fell from 2.23 to 0.11 with an llms.txt link, with accuracy unchanged ([Mintlify, 17 Jul 2026](https://mintlify.com/blog/llms-txt-agent-benchmark), vendor benchmark). Anthropic publishes one for its developer docs ([platform.claude.com/llms.txt](https://platform.claude.com/llms.txt)).
- OpenAI, Anthropic and Perplexity make no public statement that their search products read llms.txt.

**Strength.** Strong that it does not affect AI search visibility today (official Google statement plus several large log and correlation studies).

**For us.** `https://datatalks.club/llms.txt` returns 404 (checked 15 Nov 2026). Leave it. The course pages are not developer documentation, so the one use case with evidence does not apply. One detail worth knowing: deinbildungsgutschein.de publishes an [llms.txt](https://deinbildungsgutschein.de/llms.txt) that asks assistants to prefer its paying providers. That shows intent on their side, not an effect.

### 1.6 Which sources AI engines cite for course and bootcamp questions

**Do.** Plan presence by source type, in this order for our queries: provider pages (ours), directories and comparison pages, YouTube, LinkedIn, Reddit. Wikipedia is not a realistic target.

**Evidence, education queries.**

- EdTech questions, 288 answers on four engines plus 69 AI Overviews, measured 28 October 2026: brand sites 58.2% of citations on the four engines and 51.6% in AI Overviews. Review and comparison publishers 16.3%. Community and social 28.8% in AI Overviews against 4.2% on the four engines ([5W, updated 11 Nov 2026](https://5wpr.com/research/edtech-ai-visibility-index-2026); small sample, PR agency).
- Online learning, 63,142 responses, July to September 2026: ChatGPT's top five cited domains were coursera.org, edx.org, reddit.com, open.edu.au and udemy.com. AI Overviews and AI Mode were led by youtube.com and reddit.com. Average top-20 overlap between engines was about 17% ([Temso, 11 Oct 2026](https://www.temso.ai/data/AI-Source-Citation-Patterns-in-Online-Education-Platforms); vendor).
- In an industry breakdown for education, "Research.com is the clear winner, but Reddit takes the No. 2 spot" ([Scrunch](https://scrunch.com/blog/reddit-paradox-industry-breakdown-of-most-cited-ai-sources), December 2025 data).

**Evidence, our own queries.** The 15 November baseline in the [domain plan](domain-and-seo-plan.md) is closer to our case than any US study. ChatGPT's sources for the Berlin voucher question were led by deinbildungsgutschein.de and provider sites (joinmsit.de, ifadw.de, neuefische.de, spiced-academy.com). Perplexity cited provider pages and a WBS comparison post. Google AI Overviews named providers, and the organic list was led by a WBS "best AI bootcamps" post.

**Evidence, all industries, with dates because shares move fast.**

| Source type | Finding | Source and date |
| --- | --- | --- |
| YouTube | Most cited domain in Google AI Overviews at 5.6% of citations, up 34% in six months | [Ahrefs, 2 Mar 2026](https://ahrefs.com/blog/ai-overview-citations-top-10/) |
| YouTube | Share of citations: 29.5% in AI Overviews, 16.6% in AI Mode, 9.7% in Perplexity, 0.2% in ChatGPT | [BrightEdge, 25 Sep 2025](https://brightedge.com/resources/weekly-ai-search-insights/youtube-presence-ai-search) (sample not disclosed) |
| Reddit | 3.11% of citations across all models, the most cited domain. ChatGPT share fell from about 7% to about 1% in September 2025 | [Profound with Reddit, 10 Nov 2025](https://tryprofound.com/blog/the-data-on-reddit-and-ai-search) |
| Reddit | Cited in close to 60% of ChatGPT responses in early August 2025, around 10% by mid-September | [Semrush, 10 Nov 2025](https://www.semrush.com/blog/most-cited-domains-ai/) |
| Reddit | ChatGPT Search share fell again from 3.83% to 0.52% in August 2026 (single tracker, provisional) | [Search Engine Journal, 19 Aug 2026](https://www.searchenginejournal.com/why-reddits-chatgpt-citation-drop-isnt-fully-explained/534572/) |
| Reddit | Via APIs: OpenAI cited Reddit 3,012 times out of 491,024 retrievals. Anthropic 0 of 139,601. Google about 2% of 697,768 cited sources | [DEJAN, 21 Jul 2026](https://dejan.ai/blog/reddit-ai/) |
| Wikipedia | 7.8% of ChatGPT citations, the top source there | [Profound, 5 Jun 2025](https://www.tryprofound.com/blog/ai-platform-citation-patterns) |
| LinkedIn | Cited in nearly 15% of AI Mode responses | [Semrush, 10 Nov 2025](https://www.semrush.com/blog/most-cited-domains-ai/) |
| LinkedIn | "the #1 most-cited domain for professional queries across all AI Search platforms" | [Profound, 9 Mar 2026](https://tryprofound.com/blog/linkedin-is-the-most-cited-domain-for-professional-queries-in-ai-search) |
| Listicles | 21.88% of citations. Comparison pages 2.20%. Alternatives pages 0.29% | [Peec AI data via Wix, 23 Mar 2026](https://www.wix.com/studio/ai-search-lab/research/content-types-most-cited-by-llms) |
| Review platforms | Domains present on several review platforms averaged 4.6 to 6.3 ChatGPT citations against 1.8 for absent ones | [SE Ranking, 24 Nov 2025](https://seranking.com/blog/how-to-optimize-for-chatgpt/) |
| Organic rank | 37.9% of pages cited in AI Overviews rank in the top 10 for the same query | [Ahrefs, 2 Mar 2026](https://ahrefs.com/blog/ai-overview-citations-top-10/) |
| Organic rank | AI Overview overlap with organic results in education: 72.6% | [BrightEdge, 18 Sep 2025](https://www.brightedge.com/resources/weekly-ai-search-insights/rank-overlap-after-16-months-of-aio) (sample not stated) |

The Tim Soulo X post says LLMs reject Reddit more than 90% of the time. Dan Petrovic's written data supports that for OpenAI's API and contradicts it for Google, which "selects Reddit close to the rate it selects everything else" ([DEJAN, 21 Jul 2026](https://dejan.ai/blog/reddit-ai/)). The X post itself could not be opened.

**Strength.** Medium. Large datasets, but vendor-run, mostly US, and shares change within weeks.

**For us.**

- Our own pages are the main lever. Brand sites take the largest share in the education data.
- YouTube is the second lever and we already own a channel. See section 3.6.
- LinkedIn posts and articles by Alexey that state the same facts are worth doing for AI Mode and for "professional" questions.
- Reddit is too volatile in ChatGPT to plan around. The two discovery posts from 14 November (reddit.md) were research, and that is the right use. Answer questions where people ask about English-taught voucher courses, with your name on it. No seeding.
- Directories and comparison pages matter most in German voucher queries, and most open only after AZAV. See 1.7.

### 1.7 KURSNET, mein NOW and the German lists

**Do.** Prepare the KURSNET account and wording now, publish the listing the week the certificates arrive, then ask the comparison sites that already rank.

**Evidence, KURSNET and mein NOW.**

- Free: "Die Nutzung von KURSNET sowie die Veröffentlichung der Daten ist für Bildungsanbieter kostenlos." ([KURSNET Nutzungsbedingungen, 2 May 2024](https://www.kursnet-online.arbeitsagentur.de/onlinekurs/printNutzungsbedingungen.do)).
- KURSNET is the input side. Publication is on mein NOW "mit bis zu drei Tagen Verzögerung" ([BA Eingabehilfe, 31 Mar 2025](https://www.arbeitsagentur.de/datei/kursnet-eingabehilfe-weiterbildungsangebote_ba035945.pdf)).
- English content is accepted ([BA Redaktionshandbuch, 1 Aug 2025](https://www.arbeitsagentur.de/datei/kursnet-redaktionshandbuch_ba147351.pdf), section I.2.1).
- One account per legal entity. Registration ends with a PIN sent by post that must be activated within two weeks (Redaktionshandbuch, I.5).
- The registration form has an option for providers without an AZAV approval. The Bildungsgutschein box is an optional field (Eingabehilfe, II.2.17). The form text for the non-AZAV option names general education and study offers, so whether a non-certified vocational course is accepted is my inference, not a stated rule.
- To tick the Bildungsgutschein box you must name the certifier and submit the Träger certificate and the Maßnahmenzulassung as PDFs first (Eingabehilfe, I.4.2). With the box ticked, "wird der Veranstaltungstermin in der Suche von mein NOW bei ausgewähltem Filter 'Bildungsgutschein' gefunden."
- The Maßnahmenummer must not appear in any field of the listing (Eingabehilfe, II.2.17).
- No promotional wording: "Vermeiden Sie beispielsweise Superlative, Vergleiche, lobende Aussagen, Erfolgsversprechen, Jobgarantien oder ähnliche Hinweise." BA's own examples of banned phrases include "Gute Jobperspektiven" and "Hohe Vermittlungsquoten" (Eingabehilfe, I.4.3).
- Title: neutral, and for AZAV measures the title on the Maßnahmezulassung. Provider name, format, duration and location may not be in the title (Eingabehilfe, II.1).
- An offer needs a valid date to be published (Redaktionshandbuch, I.9.1).
- Bulk upload exists as XML in open-Qcat format ([BA XML upload page](https://www.arbeitsagentur.de/institutionen/kurse-anbieten/xml-upload)). There is no official public API ([bundesAPI repository](https://github.com/bundesAPI/weiterbildungssuche-api)).

**Evidence, other lists.**

- deinbildungsgutschein.de is run by Arkona Services UG in Berlin. Providers register and upload the AZAV certificate. The site takes a referral fee and says "In Listen zeigen wir angebundene Träger vor nicht angebundenen." and "Im Katalog stehen auch Träger, die nicht angebunden sind und nichts zahlen." ([AGB](https://deinbildungsgutschein.de/agb)). It led ChatGPT's sources in our baseline ([domain plan](domain-and-seo-plan.md)).
- IWWB does not take direct entries: "Sie können Ihre Angebote nicht direkt in unsere Datenbank eingeben." You get in through a partner database such as kursfinder.de, fortbildung24 or Springest ([IWWB provider note](https://www.iwwb.de/information/Hinweis-fuer-Weiterbildungsanbieter-Seminaranbieter-Bildungsinstitute-etc.-weiterbildung-33.html), [partner list](https://www.iwwb.de/information/Partnerdatenbanken-IWWB-weiterbildung-18.html)).
- fortbildung24 charges an annual account fee plus fees per enquiry and booking ([fortbildung24](https://www.fortbildung24.com/kurse-eintragen.html)).
- kursfinder.de sells listings through its sales team and publishes no price ([kursfinder provider page](https://anbieter.kursfinder.de/)).
- Course Report: "New to Course Report? List your school." No prices are published ([Course Report](https://www.coursereport.com/connect)). Its Berlin page lists 14 schools, including Le Wagon with 3,818 reviews and Turing College with 437 ([Course Report Berlin](https://www.coursereport.com/cities/berlin)).
- SwitchUp "makes money through lead generation" ([SwitchUp](https://www.switchup.org/about)).

**Strength.** Strong for the KURSNET rules (official BA documents). Weak for the value of the paid portals (vendor claims only).

**For us.**

1. Now: decide the two Maßnahme titles. The KURSNET title must equal the title on the Maßnahmezulassung, and mein NOW search is full-text ([supply research](supply-jobs-and-bootcamps.md)). A title such as "AI Engineering" or "Agentic Engineering" with a neutral descriptive addition does more for search than an internal code name. Put this to the certifier before the application is final.
2. Now: draft the KURSNET description in neutral language. Our copy rules already forbid hype, so the approved course text is close. Remove any phrase about getting hired.
3. Now: register the KURSNET account, since the PIN comes by post. Check with the KURSNET Redaktion whether a listing without the funding box is accepted before certification. If yes, it gives an early mein NOW entry.
4. On certification: upload certificates, tick the Bildungsgutschein box, add the April 2027 dates. The entry appears on mein NOW within three days.
5. Same week: register on deinbildungsgutschein.de (the catalogue is free, the paid tier gives priority), and ask Course Report for a school page.
6. Skip fortbildung24, kursfinder and Springest until there is evidence that our audience uses them. They are generalist paid portals.
7. On our own German page, the Maßnahmenummer can be shown. The KURSNET ban applies to the listing fields only.

### 1.8 Earn real third-party mentions, and none of the fake kind

**Do.** Get mentioned where the audience already is: the DataTalks.Club podcast and newsletter, guest talks at Berlin meetups, LinkedIn, the build log, replies to real questions. No paid or seeded mentions.

**Evidence.** Brand mention correlations as in 1.3 ([Ahrefs, 12 Dec 2025](https://ahrefs.com/blog/ai-brand-visibility-correlations)). Google: "seeking inauthentic 'mentions' across the web isn't as helpful as it might seem." ([AI optimization guide](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide)). Google added "attempting to manipulate generative AI responses in Google Search" to its spam definition (reported by [Search Engine Roundtable, 15 May 2026](https://www.seroundtable.com/google-spam-policies-apply-ai-responses-41331.html)).

**Strength.** Medium for the correlation, Strong for the policy.

**For us.** The build log at alexeygrigorev.com is itself a third-party-domain mention with links. Each entry should link to the specific `/academy/` page it talks about, with the page's name as the link text.

### 1.9 How to see AI visibility (short version, details in section 7)

**Do.** Use the two free first-party reports, a manual prompt panel with repeated runs, and UTM-based referral tracking.

**Evidence.**

- Search Console has had a generative AI performance report since 3 June 2026, rolled out to all sites by 31 August 2026. It shows impressions by page, country, device and date for AI Overviews and AI Mode ([Google Search Central blog](https://developers.google.com/search/blog/2026/06/gen-ai-performance-reports)). It has no queries and no clicks ([Search Engine Journal, 4 Aug 2026](https://www.searchenginejournal.com/google-reports-ai-search-impressions-how-to-read-them/582824/)). This confirms the RyanYorkSEO X post.
- Bing Webmaster Tools has an AI Performance report since 10 February 2026 with total citations, cited pages and grounding queries for Copilot and Bing AI summaries ([Bing blog](https://blogs.bing.com/webmaster/February-2026/Introducing-AI-Performance-in-Bing-Webmaster-Tools-Public-Preview)).
- Single prompt runs are unreliable ([SparkToro and Gumshoe, 28 Jan 2026](https://sparktoro.com/blog/new-research-ais-are-highly-inconsistent-when-recommending-brands-or-products-marketers-should-take-care-when-tracking-ai-visibility/)).

**Strength.** Strong for the two reports. Medium for the variability study.

**For us.** See section 7.

## 2. SEO for the subfolder launch

### 2.1 Replace the stub pages with server-side 301 redirects

**Do.** Serve an HTTP 301 from every `academy.datatalks.club` path to the matching `/academy/` path. Keep it for at least a year.

**Evidence.**

- Google: "Use server side permanent redirects if technically possible." and "Keep the redirects for as long as possible, generally at least 1 year." ([Google site move doc](https://developers.google.com/search/docs/crawling-indexing/site-move-with-url-changes)).
- Google treats an instant meta refresh as a permanent redirect, but ranks it below server-side redirects for reliability: "If server-side redirects aren't possible to implement on your platform, meta refresh redirects may be a viable alternative." and "Only use JavaScript redirects if you can't do server-side or meta refresh redirects." ([Google redirects doc](https://developers.google.com/search/docs/crawling-indexing/301-redirects)).
- Most AI crawlers do not run JavaScript ([Vercel and MERJ, 17 Dec 2024](https://vercel.com/blog/the-rise-of-the-ai-crawler)). Whether OAI-SearchBot, PerplexityBot or Bingbot follow a meta refresh is undocumented.

**Strength.** Strong (official Google docs).

**For us.** What the old host returns today (checked 15 Nov 2026): `https://academy.datatalks.club/agentic-engineering/` answers HTTP 200 from GitHub Pages with a 606-byte page that contains a canonical link to the new URL, a `location.replace` script and a zero-second meta refresh. `https://academy.datatalks.club/sitemap.xml` returns the same HTML stub instead of XML or a redirect. So these are not HTTP 301s yet.

For Google this setup works, because an instant meta refresh counts as permanent. For other crawlers it is unknown. The fix is small: point the `academy` DNS record at something that can answer with a 301, for example the CDN that already serves the new pages.club (a redirect function for that host name) or a redirect rule at the DNS provider. Then check with `curl -I` that each old path returns `301` and a `Location` header. All Meetup descriptions, emails and saved copy should carry the new URLs so that people do not depend on the redirect.

### 2.2 Change of Address tool: optional here, 301s do the work

**Do.** Do not spend time on it unless Search Console offers it without friction.

**Evidence.** Google's site move doc: "You only need this tool when moving from one domain or subdomain to another". The tool's help page: it "can be used only on properties at the domain level", a subdomain such as m.example.com is a valid source, and "you can use the tool to migrate your site from one domain to a path within another domain." It is not for "Moving some pages from one location to another within your site" ([Change of Address help](https://support.google.com/webmasters/answer/9370220)). The page gives no example of a subdomain moving into a path on its own parent domain.

**Strength.** Strong for the quoted rules. The exact case of a subdomain to subfolder move is not documented.

**For us.** The old subdomain had no indexed pages and no backlinks in Moz on 15 November ([domain plan](domain-and-seo-plan.md)), so there is almost nothing to transfer. If you try the tool, you need a verified property for `https://academy.datatalks.club/`, and its pre-checks may reject a host that does not send a 301. That is one more reason to fix 2.1 first.

### 2.3 Canonicals, sitemap and Search Console

**Do.** Self-referencing canonicals on every new URL, one complete sitemap, a Domain property plus a URL-prefix property for the folder, and a manual indexing request for each of the few pages.

**Evidence.**

- "Each new URL should have a self-referencing rel="canonical" link tag." ([Google site move doc](https://developers.google.com/search/docs/crawling-indexing/site-move-with-url-changes)).
- A URL-prefix property can be a folder: "consider creating a separate Search Console property for each domain or subpath that you want to track" ([Search Console help](https://support.google.com/webmasters/answer/34592?hl=en)).
- Only the root robots.txt counts: "Crawlers don't check for robots.txt files in subdirectories." ([Google robots.txt doc](https://developers.google.com/search/docs/crawling-indexing/robots/robots_txt)).
- "Google ignores priority and changefreq values." ([Google sitemap doc](https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap)).
- Request indexing: "Indexing can take up to a week or two" ([URL Inspection help](https://support.google.com/webmasters/answer/9012289?hl=en)).

**Strength.** Strong.

**For us.** Status on 15 November (HTTP check):

| Item | Status |
| --- | --- |
| Canonical on `/academy/`, `/academy/agentic-engineering/`, `/academy/sessions/` | Present and self-referencing |
| `/academy/sitemap.xml` | Live, 6 URLs, listed in the root robots.txt, no `lastmod` |
| `/academy/bildungsgutschein/` | 404 |
| `/academy/faq/` | 404 |
| Link from datatalks.club header to `/academy/` | Present ("Academy") |
| Links from the academy home to the sessions page or the voucher page | None |
| JSON-LD on academy pages | None |

To do: add the German page and the FAQ to the sitemap when they go live, add `lastmod` dates, link the sessions page and the German page from the academy home and footer, add a URL-prefix property for `https://datatalks.club/academy/` in Search Console (the Domain property question from the domain plan is still open), submit the sitemap there and in Bing Webmaster Tools, and request indexing for each URL.

### 2.4 One German page: what it can and cannot rank for

**Do.** Keep the single German page. Write it for the queries where our offer is the answer. Treat the generic voucher terms as supporting context.

**Evidence.**

- New pages rarely rank fast: "Only 1.74% of newly published pages" reached the top 10 within a year, and the average page in first position is 5 years old ([Ahrefs, 15 May 2025](https://ahrefs.com/blog/how-long-does-it-take-to-rank-in-google-and-how-old-are-top-ranking-pages/)).
- Google judges language per page from the visible text: "Google uses the visible content of your page to determine its language." It recommends "using a single language for content and navigation on each page" ([Google multi-regional doc](https://developers.google.com/search/docs/specialty/international/managing-multi-regional-sites)).
- John Mueller: "it doesn't matter if only a part of your website is translated into a different language." ([Search Engine Roundtable, 20 Dec 2021](https://www.seroundtable.com/google-language-per-page-basis-32620.html)).
- AI engines fan out one question into several searches ([Google AI features doc](https://developers.google.com/search/docs/appearance/ai-features)). Pages that ranked for the main query and at least one fan-out query were cited 51.2% of the time against 19.6% for the main query alone ([Surfer, updated 22 Oct 2026](https://surfer.ai/blog/query-fan-out/); vendor, Gemini used as a proxy).

**Strength.** Strong for the language handling and the ranking odds. Medium for fan-out.

**For us.** The keyword table in the content plan sends 25 German queries to one URL. That is fine as a mapping, because there is no second German page. It is not fine as an expectation. Proposed tiers:

| Tier | Queries (volumes from the [content plan](seo-content-plan.md)) | Expectation |
| --- | --- | --- |
| Win | "weiterbildung auf englisch" (390), "bildungsgutschein englisch" (40), "ki weiterbildung bildungsgutschein", "weiterbildung ki entwickler", "ai engineering weiterbildung", "english courses bildungsgutschein" (no volume data) | Our offer is the direct answer. Put these words in the title, H1, first paragraph and subheadings. |
| Maybe | "ki weiterbildung" (2,400), "weiterbildung ki" (1,000), "weiterbildung softwareentwickler" (170), "ki weiterbildung berlin" (no volume data) | Possible over months if the page earns links and the listings go up. |
| Context | "bildungsgutschein" (9,900), "bildungsgutschein agentur für arbeit" (5,400), "beantragen" (1,900), "voraussetzungen" (1,600), "jobcenter" (1,600) | Generic informational intent. Answer these questions in sections, because fan-out queries and AI answers draw on them, but do not expect page-one rankings before April 2027. |

The draft title "Bildungsgutschein für KI-Weiterbildung auf Englisch" already fits the first tier. Keep the whole page in German, including the button and form labels, since Google recommends one language per page. After four to six weeks, open the Search Console query report for this URL and adjust the subheadings to the queries that actually get impressions.

### 2.5 hreflang: not needed

**Do.** Do not add hreflang. Set `lang="de"` on the German page for browsers and screen readers.

**Evidence.** hreflang is for alternates: "If you have multiple versions of a page for different languages or regions, tell Google about these different variations." and "Google doesn't use hreflang or the HTML lang attribute to detect the language of a page" ([Google localized versions doc](https://developers.google.com/search/docs/specialty/international/localized-versions)). John Mueller: "it doesn't make any sense to use hreflang if you only have one language / region that you're targeting." ([Search Engine Roundtable, 8 Jun 2017](https://www.seroundtable.com/one-language-hreglang-google-23970.html)).

**Strength.** Strong.

**For us.** The German page has no English equivalent, so there is nothing to annotate. hreflang becomes relevant only if we ever publish an English version of the same voucher guide, or German versions of the course pages. Then each pair needs reciprocal tags. Link to the German page from the English pages with German link text, for example "Bildungsgutschein: Informationen auf Deutsch", so that both users and Google see what is behind the link.

### 2.6 Internal links from the established pages

**Do.** Add contextual links to the academy from the pages on datatalks.club that already attract links and visits.

**Evidence.**

- Google: "Every page you care about should have a link from at least one other page on your site." and "Good anchor text is descriptive, reasonably concise, and relevant to the page that it's on." ([Google link best practices](https://developers.google.com/search/docs/crawling-indexing/links-crawlable)).
- In a study of 1,800 sites and 23 million internal links, traffic rose with anchor text variety (correlation, read through a [Wix recap](https://www.wix.com/seo/learn/resource/internal-linking-webinar) because Zyppy's own page refused the fetch).
- Subdomain against subfolder: Google says "do whatever makes sense for your business" ([SEO starter guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)). A documented move from subdomain to subfolder showed no clear change until more content was added ([Ahrefs, 9 Mar 2021](https://ahrefs.com/blog/subdomain-vs-subfolder/)). Public success stories are confounded or anecdotal ([Go Fish Digital case](https://gofishdigital.com/case-study/online-trading-academy/)).

**Strength.** Strong for the Google guidance. Weak for any lift from the subfolder itself.

**For us.** The header link "Academy" on the datatalks.club homepage exists as of today. That covers discovery, not relevance. Add in-content links, each with wording that fits its page:

- LLM Zoomcamp page and related blog posts: one sentence and a link to `/academy/ai-engineering/`, because the program is based on LLM Zoomcamp (programs.md).
- AI Dev Tools Zoomcamp page and posts: the same for `/academy/agentic-engineering/`.
- Podcast pages about AI engineering careers, hiring or coding agents: a short "related" link.
- `courses.datatalks.club`: a line on the two matching course pages. It is a separate host, so this is an external link in Google's eyes, but it is one we control and it puts the difference between free course and paid program in front of the right people.
- In the other direction, the academy pages already link to the free Zoomcamps in "This Is Not for You If". Keep that.

Use one approved sentence. Vary the anchor text between pages ("full-time AI Engineering program", "DataTalks.Club Academy", "Agentic Engineering in Berlin or online").

### 2.7 Topical cluster: small, around the two programs and the voucher

**Do.** Build a cluster of at most 10 to 12 pages by April, each answering one question a voucher-eligible developer asks, each linking to one program page and to the German page where relevant.

**Evidence.** Fan-out coverage as in 2.4 ([Surfer](https://surfer.ai/blog/query-fan-out/)). Experts rated "Organic Fan-Out Coverage Rankings" fifth of 13 factors ([Zyppy, 16 Sep 2026](https://signal.zyppy.com/p/google-ai-ranking-factors)). Site size itself barely correlates with AI mentions, at about 0.194 ([Ahrefs, 12 Dec 2025](https://ahrefs.com/blog/ai-brand-visibility-correlations)).

**Strength.** Medium.

**For us.** The page list is in section 3. The low correlation for page count is the argument against volume.

### 2.8 Realistic timelines

| What | When to expect it | Source |
| --- | --- | --- |
| New `/academy/` URLs indexed | Days to two weeks after sitemap submission and an indexing request | [URL Inspection help](https://support.google.com/webmasters/answer/9012289?hl=en) |
| Google shows new URLs instead of old ones | "a few weeks or more" for small and medium sites | [Google site move doc](https://developers.google.com/search/docs/crawling-indexing/site-move-with-url-changes) |
| Effect of on-page changes | "Some changes might take effect in a few hours, others could take several months." | [SEO starter guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide) |
| Brand queries ("datatalks academy") | Once indexed. My judgment, no study. | |
| Niche long-tail queries (tier "Win" in 2.4) | Weeks to months. Of pages that reach the top 10 at all, 40.82% do so within one month. | [Ahrefs, 15 May 2025](https://ahrefs.com/blog/how-long-does-it-take-to-rank-in-google-and-how-old-are-top-ranking-pages/) |
| Head terms ("bildungsgutschein") | Not before April 2027. Only 1.74% of new pages reach the top 10 within a year. | Same Ahrefs study |
| Google AI Overviews and AI Mode | Eligible as soon as the page is indexed | [Google AI features doc](https://developers.google.com/search/docs/appearance/ai-features) |
| ChatGPT, Perplexity | No study measures time to first citation. Cited pages are fresh: about 50% of Perplexity's and 31% of ChatGPT's citations were from the current year in a 2025 sample. | [Seer Interactive, 25 Jun 2025](https://www.seerinteractive.com/insights/study-ai-brand-visibility-and-content-recency) |
| mein NOW listing | Up to three days after the KURSNET entry | [BA Eingabehilfe](https://www.arbeitsagentur.de/datei/kursnet-eingabehilfe-weiterbildungsangebote_ba035945.pdf) |

The three-week re-check in the domain plan came from one anecdote. Keep the date, but do not read a miss on 6 December as failure.

## 3. Content

### 3.1 Write bottom-of-funnel pages first

**Do.** Spend the limited writing time on pages for people who are already choosing a course or preparing for the Berater. Leave "what is AI engineering" explainers to the sessions and the existing blog.

**Evidence.**

- B2B software data, 95 posts: posts for "alternatives" queries converted at 8.43%, "vs." at 5.45%, category queries at 4.85%, and "typical blog posts that target high volume keywords convert at a rate of 1% or less." ([Grow and Convert, updated 26 Jan 2026](https://www.growandconvert.com/conversion-rate-optimization/average-seo-conversion-rate/); agency client data, not education).
- Bootcamp applicants: "Online reviews are the most popular resource used by students and grads when looking for a bootcamp program", and 66% of applicants decided within one month ([Career Karma, 10 Jun 2021](https://careerkarma.com/blog/bootcamp-outcomes-survey-2021), n = 2,168).
- What bootcamp alumni weighed most when choosing: job placement outcomes first, quality of instruction second, with tuition fifth of seven ([Course Report, 2016](https://www.coursereport.com/reports/2016-coding-bootcamp-job-placement-demographics-report), 1,143 responses).
- Prospective students want program detail and cost on the site: details on a specific program 46%, cost 39%, admissions process 38%, graduate outcomes 23% ([RNL 2025 E-Expectations report](https://learn.ruffalonl.com/rs/395-EOG-977/images/2025_E-Expectations_Report.pdf); US high-school students, weak transfer to our audience).

**Strength.** Medium for the principle, Weak for transfer to German voucher courses.

**For us.** Page types in priority order, all English except the existing German page:

| Priority | Page | URL suggestion | Why |
| --- | --- | --- | --- |
| 1 | The two program pages (live) | existing | They are the conversion pages. Add the fact block from 1.2. |
| 2 | German voucher page (drafted) | `/academy/bildungsgutschein/` | The only page for German queries and for Berater. |
| 3 | FAQ (planned) | `/academy/faq/` | One place with every fact. |
| 4 | "How to Get a Bildungsgutschein as an Experienced Developer" | `/academy/bildungsgutschein-for-developers/` or a blog post | English speakers in Germany ask this in English. The [Berater objections research](berater-objections.md) is the raw material. This replaces the generic "Bildungsgutschein explainer in English" planned for the week of 14 December. |
| 5 | Cost and funding page | `/academy/cost/` | States the cost and what a voucher covers once approved. One URL for a question that is on every prospect's list. |
| 6 | Instructor page | `/academy/alexey-grigorev/` | See 3.4. |
| 7 | Curriculum deep dives, one per program | `/academy/agentic-engineering/syllabus/` and the same for AI Engineering | Week by week, what you produce, which tools. Alexey's own material, which nobody else can copy. |
| 8 | One comparison page | see 3.2 | High intent, but with rules. |
| 9 | Session recaps with video | `/academy/sessions/ai-engineering-vs-agentic-engineering/` and so on | See 3.6. |
| 10 | "AI Engineering vs Agentic Engineering: Which Program Fits You" | from session 1 | The question behind session 1. It also routes people to a waitlist. |

No outcomes page before there are outcomes. After the first cohort, publish what happened with numbers and method. Until then, the honest equivalents are the syllabus, the capstone description and the interview preparation hours that are already on the page.

### 3.2 One factual comparison page, without ranking ourselves

**Do.** Publish one dated table of English-taught, voucher-eligible AI courses in Germany with checkable columns. Do not put ourselves first in a "best" list.

**Evidence.**

- Listicles are the most cited page type at 21.88% of citations. "X vs Y" comparison pages get 2.20% ([Peec AI data via Wix, 23 Mar 2026](https://www.wix.com/studio/ai-search-lab/research/content-types-most-cited-by-llms)).
- "Best X" lists were 43.8% of the page types ChatGPT cited, and 35% of cited lists sat on low-authority domains ([Ahrefs, 4 Dec 2025](https://ahrefs.com/blog/best-lists-research/)).
- Being cited is not being recommended: 224 of 323 self-promotional lists cited in AI Overviews (69%) belonged to brands that the answer did not recommend ([Lily Ray, 17 Jun 2026](https://lilyraynyc.substack.com/p/why-calling-yourself-the-best-could)).
- A controlled comparison found the author brand's recommendation rate rose from about 4% to about 7% when its list was cited, and a competitor was recommended instead in 24.3% of cases (Scrunch, reported by [PPC Land, 25 Sep 2026](https://ppc.land/self-ranked-brands-gain-ai-recommendations-from-4-to-7-scrunch-finds/)).
- Google ranking risk: several sites heavy on self-promotional lists lost 29% to 49% visibility from around 19 to 21 January 2026. The author notes other causes are possible ([Lily Ray, 3 Feb 2026](https://lilyraynyc.substack.com/p/is-google-finally-cracking-down-on)). Google has not confirmed a target. A Google spokesperson said it is "aware of the low-quality listicle content" ([Search Engine Roundtable, 14 Apr 2026](https://www.seroundtable.com/google-warns-against-trying-to-manipulate-llms-41156.html)).
- German law allows comparative advertising under conditions. The comparison must concern offers for the same need and be objective, on relevant and verifiable features or price, and must not disparage a competitor ([§ 6 UWG](https://www.gesetze-im-internet.de/uwg_2004/__6.html); read the statute text before publishing, my summary is a paraphrase).

**Strength.** Medium.

**For us.** A page such as "English-Taught AI Courses in Germany You Can Pay for with a Bildungsgutschein (Checked November 2026)". Columns that anyone can verify from provider pages and mein NOW: provider, program, language, prerequisites, duration, weekly hours, live or self-paced, city or online, price band shown in mein NOW, AZAV status. The supply research already holds much of this ([supply research](supply-jobs-and-bootcamps.md)). List DataTalks.Club Academy in its true state: "AZAV certification in progress, first cohort planned for April 2027". Say who each course suits, and say plainly where another school is the better fit, as the German draft already does for German-taught courses. Date the page and recheck it monthly. This is the only comparison page. Individual "Academy vs Competitor" pages are low on citations and high on legal care, so skip them.

### 3.3 Freshness, facts and sources on every page

**Do.** Show a "Last updated" date, update pages when facts change, and attach a source to every number.

**Evidence.**

- "content updated in the past three months averages 6 citations versus 3.6 for outdated pages" ([SE Ranking, 24 Nov 2025](https://seranking.com/blog/how-to-optimize-for-chatgpt/)).
- 75% of pages cited by AI engines had been updated within one year ([Seer Interactive, 24 Jul 2026](https://www.seerinteractive.com/insights/study-content-recencys-impact-on-ai-visibility-in-2026); four brands).
- URLs cited by AI assistants are on average 1,064 days old against 1,432 days for organic results ([Ahrefs, 28 Jul 2025](https://ahrefs.com/blog/do-ai-assistants-prefer-to-cite-fresh-content/)).
- Pages with 19 or more data points averaged 5.4 ChatGPT citations against 2.8 for pages with few ([SE Ranking, 24 Nov 2025](https://seranking.com/blog/how-to-optimize-for-chatgpt/)).

**Strength.** Medium (large but correlational).

**For us.** The sessions page already does this well with two sourced figures. The AZAV status will change several times before April. Each change is a real update: certifier chosen, audit date, certificate issued, listing live. Put the status and its date in one visible line on the home, both program pages and the German page. Do not change dates without changing content.

### 3.4 An instructor page

**Do.** Publish one page about Alexey as the instructor and link every program page to it.

**Evidence.** Google: "We strongly encourage adding accurate authorship information" and asks "Do bylines lead to further information about the author or authors involved" ([Google helpful content guidance](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)). Google supports `ProfilePage` markup for "An employee page on a company website" ([Google ProfilePage doc](https://developers.google.com/search/docs/appearance/structured-data/profile-page)). A byline test on 123 pages found no significant change in Google AI Overviews and a rise in Bing AI citations of 109% against about 34% for controls ([Seer Interactive](https://www.seerinteractive.com/work/case-studies/author-bylines), inconclusive).

**Strength.** Strong that Google asks for it. Weak that it changes AI citations.

**For us.** The instructor is the main reason to choose this program over a larger school, and "Alexey Grigorev" is an entity that models already know from the Zoomcamps and the book. Page content from approved lines only: the 100,000 students line, founder of DataTalks.Club, the Zoomcamps, Machine Learning Bookcamp, what he teaches in each program, links to GitHub, YouTube, LinkedIn, Substack and the build log. Add `ProfilePage` with `Person` and `sameAs`. Resolve the student-number row in 1.3 first.

### 3.5 The public build log as content and links

**Do.** Keep the log on alexeygrigorev.com as the long form. Link from each entry to the academy page it concerns. Reuse entries as posts on datatalks.club only when rewritten for a reader who wants to join.

**Evidence.**

- Build-in-public results in public cases are small: one founder reported 25,000 social impressions and 38 sign-ups against a goal of 100 ([Michael Drogalis, 19 Nov 2023](https://michaeldrogalis.substack.com/p/week-12-did-it-work)), another 96 signups and 2 paying customers in three months ([Formgrid, 10 Mar 2026](https://formgrid.dev/blog/3-months-96-signups-and-2-paying-customers-what-i-learned-building-formgrid-in-public)).
- Same text on several sites: for syndication Google says "The canonical link element is not recommended" and "The most effective solution is for partners to block indexing of your content." ([Google canonicalization troubleshooting](https://developers.google.com/search/docs/crawling-indexing/canonicalization-troubleshooting)).
- Google on AI-assisted content: "Sharing information about how a piece of content was created can help give your readers more context." ([Google generative AI guidance](https://developers.google.com/search/docs/fundamentals/using-gen-ai-content)).

**Strength.** Weak for build-in-public as an acquisition channel. Strong for the duplication guidance.

**For us.** The log's value for search is as a source of real, dated, first-hand material and as links from a second domain. Three rules. Link each entry to the exact `/academy/` URL with descriptive link text. When an entry becomes a Substack post or a datatalks.club post, rewrite it for that reader so it is not a copy, and link back to the entry. The log's disclosure line "This log is written by AI from my notes" matches what Google asks for, so keep it. The log's audience is other course builders. Voucher-eligible developers will mostly not read it, so do not count it as a signup channel.

### 3.6 Free sessions as videos, recaps and links

**Do.** For each session: a public YouTube video with chapters, a recap page on `/academy/` that embeds it, and a link from the Meetup event to both.

**Evidence.**

- YouTube mentions are the strongest correlate of AI brand mentions, at about 0.737 ([Ahrefs, 12 Dec 2025](https://ahrefs.com/blog/ai-brand-visibility-correlations)), and YouTube is the most cited domain in AI Overviews ([Ahrefs, 2 Mar 2026](https://ahrefs.com/blog/ai-overview-citations-top-10/)).
- "Public webinar replays get 3.7x as many on-demand views as gated replays" ([Livestorm, 1 Sep 2026](https://livestorm.co/webinar-benchmark-report-2026)).
- Google video guidance: one watch page per video, a valid thumbnail, and for YouTube "you can specify the exact timestamps and labels in the video description" ([Google video best practices](https://developers.google.com/search/docs/appearance/video)). YouTube chapters need a first timestamp at 00:00 and at least three timestamps ([YouTube help](https://support.google.com/youtube/answer/9884579?hl=en)).
- Google's Event rich result does not cover these sessions: "Virtual experiences that have no real-world component aren't supported." The online event properties were removed on 5 June 2025 ([Google Event doc](https://developers.google.com/search/docs/appearance/structured-data/event), [changelog](https://developers.google.com/search/updates)).
- Free lessons for cohort courses: send the recording within 48 hours and keep the pitch to two minutes ([Maven guide, 14 Apr 2026](https://help.maven.com/en/articles/9494893-guide-to-successful-lightning-lesson-conversion); platform guidance without disclosed data).
- Old evidence that transcripts bring search visits: 6.26% of search visitors to This American Life landed on a transcript page ([3Play Media case study](https://3playmedia.com/why-3play/case-studies/this-american-life/), 2012 to 2014 data).

**Strength.** Medium for YouTube and public replays. Strong that Event markup will not produce a rich result for online sessions.

**For us.**

- YouTube: upload each recording to the DataTalks.Club channel within 48 hours. Title is the approved session title. The first two lines of the description state who it is for and link to the matching program page and the waitlist. Add chapters (talk sections, then each question in the Q&A as its own chapter, because those are the questions people ask assistants). Add the fact block from 1.2 at the end of the description.
- Recap page per session on `/academy/sessions/<slug>/`: the embedded video, a written summary of the 15 to 20 minute talk, the questions and answers as text, the sourced numbers, and links to the program page and the German page. Mark up with `VideoObject`. These three pages also give the Bildungsgutschein part of each talk a written home in English.
- Meetup: after each session, add a comment and edit the description with the recording and recap links. Past events stay public.
- Skip `Event` markup for the Zoom sessions. If an in-person Berlin evening happens, mark that one up. Germany is in Google's event region list ([Google Event doc](https://developers.google.com/search/docs/appearance/structured-data/event)).
- The email-only recording stays as the fast path for registrants. Public publication is in addition.

## 4. Meetup and event naming

### 4.1 Put audience and format in the title, keywords in the description

**Do.** Pattern for future events: topic first, then audience, then format. Under 80 characters.

**Evidence.**

- Meetup: "Your event title should be less than 80 characters and describe the event with relevant keywords." ([Meetup help](https://help.meetup.com/hc/en-us/articles/39790436736525-Creating-an-event)).
- Meetup's recommendation factors are location, timing, popularity (RSVPs), topic alignment and keyword alignment: "How much the event or group name and description match the user's search request" ([Meetup help](https://help.meetup.com/hc/en-us/articles/32864852208269-Why-are-my-events-or-groups-not-visible-or-not-ranked-among-first-in-my-area)).
- "A detailed, keyword-packed description helps your events appear in more recommendations." ([Meetup blog, 18 Feb 2025](https://www.meetup.com/blog/4-tips-more-rsvps-personal-recommendations/)).
- One title test: a specific topic title converted at 1.8% against 0.62% for a generic one ([NextAfter, February 2017](https://www.nextafter.com/?p=13355); single non-profit test).
- Using the word "webinar" in a title "was associated with a 50% drop in registration" ([Goldcast, 1 Feb 2023](https://www.goldcast.io/blog-post/webinar-benchmarks); correlation, 900 B2B webinars).
- Title length showed "a poor correlation" with registration in over 100 webinars ([Xtalks, 1 Aug 2019](https://xtalks.com/we-analyzed-over-100-webinars-for-title-and-abstract-length-heres-how-they-affect-registration-rate)).

**Strength.** Strong for what Meetup says it matches on. Weak for any specific title pattern.

**For us.** The three approved titles carry the topic and no audience signal. The audience line sits in the description. In the Meetup list they stand next to podcast streams for a general data audience, and on 15 November they had 11 and 12 attendees against 55 and 61 for some regular talks (DataTalksClub Meetup events, 15 Nov 2026). The titles are approved and already promoted, so do not change them now. A title change would also break the match with the landing page and emails. For the next series, test this pattern:

| Pattern | Example | Characters |
| --- | --- | --- |
| Topic for Audience (Format) | AI Engineering vs Agentic Engineering for Experienced Developers (Online) | 73 |
| Topic: Promise, for Audience | Coding Agents at Work: A Session for Developers with 2+ Years | 60 |
| In person | Agentic Engineering for Experienced Developers, Berlin Meetup | 61 |

Rules that follow from the evidence: say "session", "talk" or "meetup", not "webinar". Put "Berlin" in the title only for in-person events, because Meetup shows online events to members everywhere ([Meetup help](https://help.meetup.com/hc/en-us/articles/39489043789325-How-can-I-improve-visibility-for-my-events-and-groups)). The rule against adding "In English" stays, since the text itself is English. Keep the first description sentence as it is, because it names the audience and repeats the search words.

### 4.2 Set event topics and announce early

**Do.** Add up to five topics to every event, and publish events a few weeks ahead.

**Evidence.** "Add up to five (5) topics so prospective attendees with relevant interests are more likely to find your event" ([Meetup help](https://help.meetup.com/hc/en-us/articles/39790436736525-Creating-an-event)). "These topics directly influence how the model aligns your event with potential attendees." ([Meetup help](https://help.meetup.com/hc/en-us/articles/39489043789325-How-can-I-improve-visibility-for-my-events-and-groups)). "Schedule events well in advance (we recommend a few weeks ahead)" ([Meetup blog](https://www.meetup.com/blog/4-tips-more-rsvps-personal-recommendations/)). Meetup sends reminders "typically 7 days, 1 day, and a few hours before the event" ([Meetup help](https://help.meetup.com/hc/en-us/articles/40708711774221-What-notifications-Meetup-can-send)). In webinar data, 49.7% of registrations arrive in the final 7 days ([Livestorm, 1 Sep 2026](https://livestorm.co/webinar-benchmark-report-2026)).

**Strength.** Strong (official Meetup guidance), without published effect sizes.

**For us.** Check that the three session events carry topics such as software development, artificial intelligence, career and job search. The 7 December event had no attendee count yet on 15 November (DataTalksClub Meetup events, 15 Nov 2026). That fits the late-registration pattern, so the reminders planned for the Friday or Saturday before each session are well timed.

### 4.3 Plan for half of the RSVPs to show up

**Do.** Judge sessions by confirmed emails and waitlist joins, not by RSVPs.

**Evidence.** Average webinars converted 47.7% of registrants into live attendees ([Livestorm, 1 Sep 2026](https://livestorm.co/webinar-benchmark-report-2026); B2B webinars). Free in-person events had a median no-show rate of about 28% ([PheedLoop, 29 Apr 2026](https://pheedloop.com/blog/event-data-lab-report-5)).

**Strength.** Medium, with weak transfer.

**For us.** Meetup RSVPs go to Meetup, emails go to the `/sessions` form. Only the form gives a confirmed address and the survey answers, so the form stays the call to action in every post.

### 4.4 Luma: only for in-person events

**Do.** Do not move the online sessions to Luma for discovery. Consider Luma for an in-person Berlin evening.

**Evidence.** "Online events aren't tied to a city, so they don't show up in city search or on the Discover pages." Featured events must be in person, and Luma does "not regularly accept events that have fewer than 5 guests already registered" ([Luma help: search](https://help.luma.com/p/searching-for-events), [Luma help: featuring](https://help.luma.com/p/featuring-your-event-on-luma)). Luma supports registration questions and approval before confirmation ([Luma help](https://help.luma.com/p/collect-registration-questions)). An event can be submitted to other calendars for their admins to accept ([Luma help](https://help.luma.com/p/submitting-events-to-calendars)).

**Strength.** Strong (official Luma docs).

**For us.** For an in-person evening in Berlin, Luma's city page, approval step and registration questions ("Years as a developer", "Based in Germany?") fit the goal of a small qualified room. Submit it to Berlin tech calendars. For Zoom sessions, Meetup's member base and reminders are the better fit.

## 5. What to avoid

### 5.1 Thin pages and scaled AI content

**Avoid.** Pages made in bulk for query variants: one page per city, per job title, per tool, or German variants of one template.

**Evidence.** "Scaled content abuse is when many pages are generated for the primary purpose of manipulating search rankings and not helping users." Doorway abuse covers pages "created to rank for specific, similar search queries" ([Google spam policies](https://developers.google.com/search/docs/essentials/spam-policies)). On generative AI: "It is critical to manually factcheck and review all AI-generated content for accuracy and trustworthiness before publishing." ([Google generative AI guidance](https://developers.google.com/search/docs/fundamentals/using-gen-ai-content)). Rater guidelines describe pages made with generative AI and "likely no original content" as lowest quality (reported by [Search Engine Journal, 26 Jan 2025](https://www.searchenginejournal.com/google-updates-search-quality-rater-guidelines-what-to-know/538259/)). Google ran spam updates in March, June, August and September 2026 and a core update that began on 10 November 2026 ([Google Search Status Dashboard](https://status.search.google.com/products/rGHU1u87FJnkP6W2GwMi/history)).

**Strength.** Strong.

**For us.** The plan of about a dozen hand-checked pages is on the safe side. The temptation will be "KI Weiterbildung München", "KI Weiterbildung Hamburg" and so on. For a program that runs in Berlin or live online, those are doorway pages. One sentence on the German page, that online participation is possible from anywhere in Germany, covers it. AI drafting is fine under our own rules: start from approved copy, check every fact, a human approves.

### 5.2 Site reputation abuse: low risk, with one condition

**Avoid.** Hosting anyone else's commercial content under `/academy/`, or letting the academy section look and read like a different site.

**Evidence.** The policy targets "third-party content" published "mainly because of that host's already-established ranking signals". Google measures sections on their own: "we're measuring them independently, even if they are located within a site." ([Google spam policies](https://developers.google.com/search/docs/essentials/spam-policies), [Google blog, 19 Nov 2024](https://developers.google.com/search/blog/2024/11/site-reputation-abuse)).

**Strength.** Strong.

**For us.** The Academy is first-party: same founder, same brand, courses derived from the Zoomcamps. That is outside the policy. Two practical points follow from "measured independently". The section has to earn its standing with its own quality and links, which is the case for 2.6. And any future partner content (a certifier's page, a sponsor's course) should not live under `/academy/`.

### 5.3 Fake, selective or unlabelled reviews

**Avoid.** Invented reviews, paying for positive reviews, asking only happy participants, and showing Zoomcamp quotes as if they were about the Academy.

**Evidence.**

- Germany: anyone who shows consumer reviews must say "ob und wie" they ensure the reviews come from real users ([§ 5b Abs. 3 UWG](https://www.gesetze-im-internet.de/uwg_2004/__5b.html)). Always unlawful: claiming reviews come from real customers without reasonable checks (Nr. 23b), and commissioning fake reviews (Nr. 23c) ([Anhang zu § 3 Abs. 3 UWG](https://www.gesetze-im-internet.de/uwg_2004/anhang.html)).
- USA: the FTC rule on consumer reviews and testimonials was announced on 14 August 2024 and "went into effect on October 21, 2024". It bans fake reviews, buying reviews with a required sentiment, undisclosed insider reviews and review suppression, and "authorizes courts to impose civil penalties for knowing violations" ([16 CFR Part 465 on eCFR](https://www.ecfr.gov/current/title-16/chapter-I/subchapter-D/part-465)).
- Platforms: "We don't allow incentivized reviews on Trustpilot." ([Trustpilot guidelines, September 2026](https://corporate.trustpilot.com/legal/for-businesses/guidelines-for-businesses)). Google forbids incentives and selective solicitation ([Google contribution policy](https://support.google.com/contributionpolicy/answer/7400114?hl=en)).
- Google will not show stars for reviews a business controls about itself ([Google review snippet doc](https://developers.google.com/search/docs/appearance/structured-data/review-snippet)).

**Strength.** Strong (statute and official rules). This is not legal advice.

**For us.** The Academy has no graduates yet, so it has no reviews. The testimonial library holds verbatim, sourced quotes about AI Dev Tools Zoomcamp, LLM Zoomcamp and the Maven Buildcamp ([testimonials](testimonials.md)). If they go on the course pages: label each with the course it refers to, link to the public source, and add one line that says where the quotes come from and that they are about earlier courses by the same instructor. After the first cohort, invite every participant in the same way to review on Course Report or Google, with no reward.

### 5.4 Claims that funding exists before it does

**Avoid.** Titles, snippets or listings that read as "fundable with a Bildungsgutschein" before the Maßnahmezulassung exists. Also "100% gefördert", "kostenlos" and the BA logo.

**Evidence.**

- Misleading statements about "Befähigung, Status, Zulassung" of the business or about an approval of the service are covered by [§ 5 UWG](https://www.gesetze-im-internet.de/uwg_2004/__5.html). Always unlawful: the untrue claim that a service has been approved by a public or private body (Nr. 4, [Anhang UWG](https://www.gesetze-im-internet.de/uwg_2004/anhang.html)).
- A German court treated advertising a product as eligible for state aid as misleading when eligibility was not established (LG Stuttgart, 36 O 68/21 KfH, summarised by a [law firm](https://www.ra-kotz.de/die-irrefuehrende-foerderfaehigkeit-wettbewerbsrecht-und-falsche-werbung.htm); a different product category).
- "Das Logo der BA und zahlreiche Namen von Produkten und Programmen der BA sind als Marke geschützt." Use needs express permission ([BA Impressum](https://www.arbeitsagentur.de/impressum)).
- The agency can exclude a provider from the voucher for unresolved defects under § 183 SGB III ([BA Hinweisblatt, 19 Mar 2024](https://arbeitsagentur.de/datei/dok_ba015523.pdf)).
- The AZAV and BA rules contain no specific provision about advertising, "100% gefördert" or gifts to voucher holders. The approval rules themselves contain no advertising provision ([§ 176 SGB III](https://www.gesetze-im-internet.de/sgb_3/__176.html), [§ 2 AZAV](https://www.gesetze-im-internet.de/azav/__2.html)). The keyword index of the Beirat recommendations of 17 June 2026 has no entry for Werbung ([BA](https://www.arbeitsagentur.de/datei/dok_ba032840.pdf)). So general competition law is what applies. Ask the certifier whether it has its own rules for using the certificate in advertising.

**Strength.** Strong for the statute text. How it applies to wording before certification is an interpretation; there is no ruling on it.

**For us.** The live pages get this right: "Bildungsgutschein (approval pending)" and "I'm applying for AZAV certification so the Agentur für Arbeit can cover tuition". This is a statement of fact, not a disclaimer, so it does not conflict with the rule against disclaimer boilerplate. The German draft's body copy is also correct. Its meta description is not: "Mit Bildungsgutschein, nächste Gruppe April 2027." will be shown alone in search results. Suggested replacement, for Alexey's review: "KI-Weiterbildung auf Englisch für erfahrene Softwareentwickler in Deutschland. AZAV-Zertifizierung läuft, Bildungsgutschein geplant. Nächste Gruppe April 2027." Apply the same test to every title tag, Meetup line and social post: would this sentence be true if read with nothing around it?

### 5.5 Job placement promises and outcome claims

**Avoid.** Any wording that promises or implies a job, a salary or a success rate.

**Evidence.**

- KURSNET listings may not contain "Erfolgsversprechen, Jobgarantien", and BA lists "Gute Jobperspektiven" and "Hohe Vermittlungsquoten" as banned examples ([BA Eingabehilfe](https://www.arbeitsagentur.de/datei/kursnet-eingabehilfe-weiterbildungsangebote_ba035945.pdf)).
- Statements about results to be expected from a service fall under [§ 5 UWG](https://www.gesetze-im-internet.de/uwg_2004/__5.html). A court barred a school from advertising guaranteed learning success because success depends on the learner (OLG Hamm, 29 Jan 2013, reported by [LTO](https://www.lto.de/recht/nachrichten/n/olg-hamm-urteil-i-4-u-171-12-werbung-tanzschule-unzulaessig); a dance school, not a bootcamp).

**Strength.** Strong for KURSNET, Medium for the case law.

**For us.** The pages already describe preparation, not placement ("Das ist Vorbereitung, kein Versprechen auf eine Stelle."). Two places to watch. The series headline "the AI skills that get experienced developers hired" is approved and the page makes no promise, but an assistant that summarises the page may shorten it to a hiring claim, so keep that phrase out of KURSNET text and out of the German page. And when the first cohort ends, publish outcomes only as counts with a date and method.

### 5.6 Unverifiable numbers

**Avoid.** Any figure without a source and a month, on pages and in listings.

**Evidence.** Google asks whether content is trustworthy and says of E-E-A-T "trust is most important" ([Google helpful content guidance](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)). Statistics and cited sources are among the few on-page traits with evidence for AI citation ([Aggarwal et al., KDD 2024](https://arxiv.org/abs/2311.09735)).

**Strength.** Strong for the principle.

**For us.** This is already house style. The open item is the student count (row 4 in the table in 1.3). "More than 100,000 students" needs a short method note on the instructor page: which courses, which years, what counts as a student. Otherwise the sessions page figure of 12,755 enrolments looks like a contradiction.

## 6. Myths and weak evidence

| Claim | Verdict | Source |
| --- | --- | --- |
| "You need llms.txt to appear in AI answers." | False for Google by its own statement. No measured effect elsewhere. 97% of files are never fetched. | [Think with Google, 17 Jun 2026](https://business.google.com/us/think/search-and-video/ai-search-era-brand-authority-strategy/); [Ahrefs, 15 Jun 2026](https://ahrefs.com/blog/llmstxt-study/) |
| "llms.txt gave us 2.3x Perplexity citations." | Anecdote. The author says it "is not statistically significant at any reasonable confidence interval". | [Alejandro Rioja, 25 Oct 2026](https://alejandrorioja.com/llms-txt-explained-what-it-is-and-whether-it-actually-moves-citations/) |
| "Schema markup gets you cited by LLMs." | Not supported. A controlled test found no uplift. Correlations between schema and citations exist (61% of cited pages had three or more schema types against 25%), but they track general SEO investment. | [Ahrefs, 11 May 2026](https://ahrefs.com/blog/schema-ai-citations/); [AirOps, 18 Jul 2025](https://www.airops.com/report/structuring-content-for-llms) |
| "Microsoft confirmed schema helps its LLMs." | Second-hand. The source is a conference attendee's post, with no direct quote. | [Search Engine Roundtable, 20 Mar 2025](https://www.seroundtable.com/schema-llms-copilot-bing-microsoft-39093.html) |
| "FAQ schema earns rich results and AI citations." | FAQ rich results ended for all sites on 7 May 2026. Pages with FAQ schema averaged fewer ChatGPT citations (3.6 against 4.2). | [Google changelog](https://developers.google.com/search/updates); [SE Ranking, 24 Nov 2025](https://seranking.com/blog/how-to-optimize-for-chatgpt/) |
| "Add Event schema to webinars." | Google's Event feature excludes online-only events. | [Google Event doc](https://developers.google.com/search/docs/appearance/structured-data/event) |
| "Sections of 120 to 180 words are optimal for ChatGPT." | Misread. In the source, sections over 180 words scored higher (5.7) than 120 to 180 words (4.6). | [SE Ranking, 24 Nov 2025](https://seranking.com/blog/how-to-optimize-for-chatgpt/) |
| "Chunk your content into small pieces for AI." | Google says there is no such requirement. Microsoft's advice on liftable Q&A and tables is milder than the myth. | [Google AI optimization guide](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide) |
| "Reddit is the way into ChatGPT." | Unstable. ChatGPT's Reddit share dropped sharply twice (September 2025 and August 2026). Via API, OpenAI cited 3,012 of 491,024 retrieved Reddit sources. | [Semrush, 10 Nov 2025](https://www.semrush.com/blog/most-cited-domains-ai/); [DEJAN, 21 Jul 2026](https://dejan.ai/blog/reddit-ai/) |
| "LLMs reject Reddit more than 90% of the time." | True for OpenAI's API in one dataset, false for Google, where Reddit was about 2% of cited sources and second only to YouTube. | [DEJAN, 21 Jul 2026](https://dejan.ai/blog/reddit-ai/) |
| "Wikipedia and Reddit make up almost half of ChatGPT citations." | Misquote. The 47.9% figure is a share within the top 10 sources only. Wikipedia's share of all ChatGPT citations was 7.8%. | [Profound, 5 Jun 2025](https://www.tryprofound.com/blog/ai-platform-citation-patterns) |
| "AI visitors convert 4.4 times or 23 times better." | Vendor claims from one site or with no disclosed sample. A 54-site study found no significant difference (4.87% against 4.60%, p = 0.794). A 973-shop study found ChatGPT traffic converted worse than most channels. | [Semrush, 21 Jul 2025](https://www.semrush.com/blog/ai-search-seo-traffic-study/); [Ahrefs, 16 Jun 2025](https://ahrefs.com/blog/ai-search-traffic-conversions-ahrefs/); [Amsive, 3 Sep 2025](https://www.amsive.com/insights/seo/llm-traffic-conversion-rate-study/); [University of Hamburg, 26 Nov 2025](https://www.bwl.uni-hamburg.de/en/ueber-die-fakultaet/aktuelles/2025/1106-chatgpt-und-e-commerce.html) |
| "Prompt search volume" in tools. | No platform except Copilot shares query data. Tool figures are modelled. | [Ahrefs, 17 Aug 2026](https://ahrefs.com/blog/how-ahrefs-estimates-ai-search-demand/); [Conductor, 8 Jul 2026](https://www.conductor.com/academy/debunking-ai-prompt-volume/) |
| "Track your rank in ChatGPT." | Lists differ on almost every run. The share of runs in which a brand appears is the usable number. | [SparkToro and Gumshoe, 28 Jan 2026](https://sparktoro.com/blog/new-research-ais-are-highly-inconsistent-when-recommending-brands-or-products-marketers-should-take-care-when-tracking-ai-visibility/) |
| "API-based trackers show what users see." | API and app answers overlapped on 15.5% to 23.8% of brands in one test. | [Surfer, updated 4 Oct 2026](https://surfer.ai/blog/llm-scraped-ai-answers-vs-api-results) (vendor that sells scraped data) |
| "Moving from a subdomain to a subfolder lifts traffic." | No rigorous data. The best documented case showed no clear change. | [Ahrefs, 9 Mar 2021](https://ahrefs.com/blog/subdomain-vs-subfolder/) |
| "A self-published 'best' list gets you recommended." | It gets cited. In 69% of cases the cited brand was not the one recommended. | [Lily Ray, 17 Jun 2026](https://lilyraynyc.substack.com/p/why-calling-yourself-the-best-could) |
| "70% of direct traffic is really AI." | Misquote. The measured figures are shares of identified AI visits that arrive without a referrer, not shares of direct traffic. | [David Rosam, 11 Sep 2026](https://buttondown.com/davidrosam/archive/everyone-quotes-60-nobody-measured-it/) |
| "ChatGPT uses Bing, Gemini uses Google, Claude uses Brave." | Gemini and Google: official. Claude and Brave: on Anthropic's subprocessor list. ChatGPT and Bing: OpenAI only says it partners with "other search providers". Vendor research suggests a mix. | [Google AI Studio docs](https://aistudio.google.com/docs/google-search); [Anthropic trust centre](https://trust.anthropic.com/subprocessors); [OpenAI help](https://help.openai.com/en/articles/9237897-chatgpt-search); [Peec, Sep 2026](https://docs.peec.ai/research/chatgpt-search-result-providers) |

### The X posts from section 9, traced

| X post | Primary source found | Holds up? |
| --- | --- | --- |
| harpreetchatha_, "25 AEO facts" | No underlying article. Closest is his own myths post of 21 January 2026 with no data ([Harps Digital](https://harpsdigital.com/learn/aeo-geo-myths)). | Opinion. The individual points on llms.txt and tracking agree with the studies above. |
| alexgroberman, "Good SEO is good GEO" | [Think with Google, 17 Jun 2026](https://business.google.com/us/think/search-and-video/ai-search-era-brand-authority-strategy/) and the [Search Central AI optimization guide](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide). | Yes. Byline not visible on the page I retrieved. |
| alexgroberman, SE Ranking study | [SE Ranking, 24 Nov 2025](https://seranking.com/blog/how-to-optimize-for-chatgpt/): 129,000 domains, 216,524 pages. | Mostly. The section length claim is misread (see myths table). All findings are correlations. |
| timsoulo on Dan Petrovic | X post not retrievable. Written data at [DEJAN, 21 Jul 2026](https://dejan.ai/blog/reddit-ai/). | Partly. Reddit claim holds for OpenAI's API only. Brave confirmed. Bing not confirmed by OpenAI. |
| aleyda, Cyrus Shepard survey | [Zyppy, 16 Sep 2026](https://signal.zyppy.com/p/google-ai-ranking-factors). Top factors: crawl access (+2.20), query and answer match (+2.15), brand in LLM memory (+2.08), citable facts (+2.07). Structured data (+0.80) and llms.txt (+0.05) at the bottom. | Yes, as expert opinion. |
| isaac_dev0 and hello_code_, llms.txt anecdotes | Anecdotes, no write-up. | Consistent with the log studies in 1.5. |
| RyanYorkSEO, GSC generative AI reports | [Google Search Central blog, 3 Jun 2026](https://developers.google.com/search/blog/2026/06/gen-ai-performance-reports). | Yes. Impressions only. |

## 7. Measurement

### KPIs

| KPI | Definition | Tool |
| --- | --- | --- |
| Confirmed voucher-eligible waitlist signups (the one that matters) | Double opt-in confirmed, located in Germany, payment answer "Bildungsgutschein" or "Not sure yet", per program | Waitlist backend. The form already asks both questions (live pages, 15 Nov 2026). |
| Confirmed waitlist signups, all | Confirmation link clicked, with timestamp | Waitlist backend |
| Signup source | First-touch UTM or referrer, plus the answer to "How did you hear about us?" | Umami and one extra survey field |
| Indexed academy URLs | Count of `/academy/` URLs with status "Indexed" | Search Console |
| Search impressions and clicks for `/academy/` | By page and query, German page separately | Search Console, URL-prefix property |
| Generative AI impressions | Impressions of `/academy/` URLs in AI Overviews and AI Mode | Search Console generative AI report |
| Bing AI citations | Total citations and grounding queries for `/academy/` pages | Bing Webmaster Tools, AI Performance |
| AI answer visibility | Share of prompt runs in which "DataTalks.Club Academy" is named, and share in which an `/academy/` URL is cited, per engine | Manual panel |
| AI referral sessions | Sessions with referrer or `utm_source` from chatgpt.com, perplexity.ai, gemini.google.com, copilot.microsoft.com, claude.ai | Umami |
| Session funnel | RSVPs, form signups, confirmed, attended, waitlist joins per session | Meetup, form backend, Zoom |
| YouTube | Views and click-throughs to `/academy/` per session video | YouTube Studio, UTM links |

Why double opt-in is the unit: German data protection authorities call the double opt-in procedure "geboten" for consent given electronically, and the sender must be able to prove consent ([DSK Orientierungshilfe, November 2018](https://www.datenschutz-bayern.de/dsbk-ent/DSK_96-Werbung.pdf); [§ 7 UWG](https://www.gesetze-im-internet.de/uwg_2004/__7.html)). Unconfirmed submissions are not leads and should not be mailed.

### Baseline, 15 November 2026

| Item | Value | Source |
| --- | --- | --- |
| Academy named in AI answers | 0 of 9 (three questions, three engines, one run each) | [domain plan](domain-and-seo-plan.md) |
| Old subdomain in Google's index | No results for a `site:` query | [domain plan](domain-and-seo-plan.md) |
| datatalks.club authority | Moz Domain Authority 34, 1,140 referring domains | [domain plan](domain-and-seo-plan.md) |
| Academy URLs in sitemap | 6 | HTTP check of `/academy/sitemap.xml` |
| Planned pages that return 404 | 2 (`/academy/bildungsgutschein/`, `/academy/faq/`) | HTTP check |
| Redirect type on old host | HTTP 200 with meta refresh, not 301 | HTTP check |
| Structured data on academy pages | None | HTTP check |
| Analytics tag on academy pages | None found in the page HTML | HTTP check; [domain plan](domain-and-seo-plan.md) |
| Meetup RSVPs for sessions 1 and 2 | 11 and 12 | DataTalksClub Meetup events, 15 Nov 2026 |

Record the waitlist and session form counts from the backend on the same day to complete the baseline.

### Referral tracking in Umami

- Umami's source code has an `llm` channel for the referrer domains chatgpt.com, claude.ai, copilot.microsoft.com, gemini.google.com, meta.ai and perplexity.ai ([Umami source](https://raw.githubusercontent.com/umami-software/umami/master/src/lib/constants.ts)). The rule looks at the referrer domain only.
- Most ChatGPT clicks arrive without a referrer and are recognisable only by `utm_source=chatgpt.com`. In October 2026 a ChatGPT bug dropped that tag from inline links for about a week ([Search Engine Journal, 15 Oct 2026](https://www.searchenginejournal.com/chatgpt-traffic-drop-appears-to-be-a-tracking-problem/593157/)). So read the UTM report as well as the channel view ([Umami UTM docs](https://docs.umami.is/docs/utm)).
- Clicks from Google AI Overviews and AI Mode are counted as ordinary Google search traffic ([Google AI features doc](https://developers.google.com/search/docs/appearance/ai-features)). They cannot be separated in analytics.
- Track the waitlist submit and the double opt-in confirmation as Umami events with `data-umami-event` ([Umami events docs](https://docs.umami.is/docs/track-events)), and set a goal on the confirmation ([Umami goals docs](https://docs.umami.is/docs/goals)).
- Expect small numbers. Across 118,671 sites, AI assistants sent 0.46% of visits in October 2026 against 24.74% for Google ([Ahrefs benchmark, updated 14 Nov 2026](https://ahrefs.com/benchmarks/ai-vs-search)). On a new site with a few hundred visits, that can be zero for weeks. This is why the survey question matters more than the referrer report.
- Plausible is the alternative with a documented "AI Assistants" channel that uses both referrer and UTM ([Plausible changelog, 10 Jun 2026](https://plausible.io/changelog)). Umami's free tier is enough to start ([domain plan](domain-and-seo-plan.md)).

Add one optional question to the post-confirmation survey: "How did you hear about the Academy?" with one-click options (Meetup, Google search, ChatGPT or another AI assistant, LinkedIn, YouTube, DataTalks.Club newsletter or Slack, a friend, Agentur für Arbeit, other). It sits with the two existing optional questions, so the signup form itself stays at name and email.

### Bot visits in server logs

The new pages sit behind a CDN, so access logging can be switched on there. That gives what GitHub Pages could not: a count of fetches by OAI-SearchBot, ChatGPT-User, PerplexityBot, Perplexity-User, ClaudeBot, Claude-SearchBot and Claude-User per URL. ChatGPT-User, Perplexity-User and Claude-User are fetches triggered by a person's question ([OpenAI crawler docs](https://developers.openai.com/api/docs/bots), [Perplexity docs](https://docs.perplexity.ai/guides/bots), [Anthropic support](https://support.claude.com/en/articles/8896518-does-anthropic-crawl-data-from-the-web-and-how-can-site-owners-block-the-crawler)). A monthly count per page is enough. It tells us whether assistants read the pages even when no click follows.

### Manual prompt panel

The current check is three questions, one run each. Change it as follows.

- Prompts: 10 to 12, fixed wording, English and German. Keep the three baseline questions. Add brand questions ("What is DataTalks.Club Academy?", "Does DataTalks.Club offer a full-time course with a Bildungsgutschein?"), instructor questions ("Does Alexey Grigorev teach a full-time AI engineering program in Germany?"), and category questions ("English-taught AI engineering course in Germany with Bildungsgutschein", "Weiterbildung KI auf Englisch für Softwareentwickler mit Bildungsgutschein", "Claude Code course for experienced developers Berlin").
- Runs: 5 per prompt per engine, in a new chat each time, logged out or in temporary chat, location Germany. SparkToro recommends 60 to 100 runs per prompt for stable numbers ([SparkToro and Gumshoe, 28 Jan 2026](https://sparktoro.com/blog/new-research-ais-are-highly-inconsistent-when-recommending-brands-or-products-marketers-should-take-care-when-tracking-ai-visibility/)). Five is my compromise for a manual check, so read small changes as noise.
- Engines: ChatGPT with search, Perplexity, Google AI Overviews and AI Mode (Germany), and once a month Claude and Gemini.
- Record per run: named or not, described correctly or not (full-time, experienced developers, April 2027, AZAV in progress), which of our URLs is cited, which competitors are named, which third-party sources are cited. The last column is the to-do list for 1.7.
- Report: share of runs named, per engine. Not rank.
- Brand prompts should turn positive first, within weeks of indexing. Category prompts are the real test and depend on listings and third-party mentions.

No study quantifies how login state, location or memory change answers, so keep those settings constant and note them.

### Tools

| Tool | Use | Cost |
| --- | --- | --- |
| Google Search Console | Indexing, queries, generative AI impressions | Free |
| Bing Webmaster Tools | Bing indexing, AI Performance (citations, grounding queries) | Free |
| Umami | Sessions, referrers, UTM, signup events | Free tier |
| CDN access logs | AI bot fetches per URL | Low |
| Spreadsheet | Prompt panel and KPI log | Free |

A paid tracker makes sense once the manual panel takes more than an hour per round or once listings go live and we want daily data. Trackers that query model APIs may not match what users see in the apps ([Surfer, updated 4 Oct 2026](https://surfer.ai/blog/llm-scraped-ai-answers-vs-api-results)), so keep a small manual check even then. Test any tracker with German prompts during a trial.

### Cadence

| When | What |
| --- | --- |
| Once, this week | Fix redirects. Publish the German page and FAQ. Complete the sitemap. Add the Search Console URL-prefix property for the folder (the Domain property and Bing are already set up). Install Umami with signup events. Switch on CDN access logs. Record the backend baseline. |
| Weekly (Monday) | Confirmed signups by source, program and voucher answer. Search Console indexing and queries for `/academy/`. Umami referrers and UTM. |
| Every two weeks | Prompt panel. First full round in the week of 16 November, then 30 November, 14 December. |
| Monthly | Search Console generative AI report. Bing AI Performance. Bot fetches from logs. Fact consistency check across pages and profiles. Recheck of the comparison page. |
| On each event | AZAV milestone, KURSNET listing live, session recording published: note the date so later changes in the numbers can be read against it. |

## 8. Sources

Official documentation and statements

- Google Search Central, AI features and your website: https://developers.google.com/search/docs/appearance/ai-features
- Google Search Central, Optimizing your website for generative AI features: https://developers.google.com/search/docs/fundamentals/ai-optimization-guide
- Think with Google, 17 Jun 2026: https://business.google.com/us/think/search-and-video/ai-search-era-brand-authority-strategy/
- Google Search Central blog, generative AI performance reports, 3 Jun 2026: https://developers.google.com/search/blog/2026/06/gen-ai-performance-reports
- Google Search Central blog, succeeding in AI search, 21 May 2025: https://developers.google.com/search/blog/2025/05/succeeding-in-ai-search
- Google documentation changelog: https://developers.google.com/search/updates
- Google blog, simplifying search results, 12 Jun 2025: https://developers.google.com/search/blog/2025/06/simplifying-search-results
- Google blog, HowTo and FAQ changes, 8 Aug 2023: https://developers.google.com/search/blog/2023/08/howto-faq-changes
- Google structured data docs: [Course](https://developers.google.com/search/docs/appearance/structured-data/course), [Organization](https://developers.google.com/search/docs/appearance/structured-data/organization), [Event](https://developers.google.com/search/docs/appearance/structured-data/event), [Video](https://developers.google.com/search/docs/appearance/structured-data/video), [ProfilePage](https://developers.google.com/search/docs/appearance/structured-data/profile-page), [Breadcrumb](https://developers.google.com/search/docs/appearance/structured-data/breadcrumb), [Review snippet](https://developers.google.com/search/docs/appearance/structured-data/review-snippet), [policies](https://developers.google.com/search/docs/appearance/structured-data/sd-policies), [search gallery](https://developers.google.com/search/docs/appearance/structured-data/search-gallery)
- schema.org: https://schema.org/EducationalOccupationalProgram
- Google redirects: https://developers.google.com/search/docs/crawling-indexing/301-redirects
- Google site moves: https://developers.google.com/search/docs/crawling-indexing/site-move-with-url-changes
- Change of Address tool: https://support.google.com/webmasters/answer/9370220
- Search Console property types: https://support.google.com/webmasters/answer/34592?hl=en
- URL Inspection: https://support.google.com/webmasters/answer/9012289?hl=en
- Google localized versions: https://developers.google.com/search/docs/specialty/international/localized-versions
- Google multi-regional sites: https://developers.google.com/search/docs/specialty/international/managing-multi-regional-sites
- Google SEO starter guide: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- Google links: https://developers.google.com/search/docs/crawling-indexing/links-crawlable
- Google sitemaps: https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap
- Google robots.txt: https://developers.google.com/search/docs/crawling-indexing/robots/robots_txt
- Google spam policies: https://developers.google.com/search/docs/essentials/spam-policies
- Google blog, site reputation abuse, 19 Nov 2024: https://developers.google.com/search/blog/2024/11/site-reputation-abuse
- Google generative AI content guidance: https://developers.google.com/search/docs/fundamentals/using-gen-ai-content
- Google helpful content guidance: https://developers.google.com/search/docs/fundamentals/creating-helpful-content
- Google canonicalization troubleshooting: https://developers.google.com/search/docs/crawling-indexing/canonicalization-troubleshooting
- Google video best practices: https://developers.google.com/search/docs/appearance/video
- YouTube chapters: https://support.google.com/youtube/answer/9884579?hl=en
- Google Search Status Dashboard: https://status.search.google.com/products/rGHU1u87FJnkP6W2GwMi/history
- Google contribution policy: https://support.google.com/contributionpolicy/answer/7400114?hl=en
- Google AI Studio, grounding with Google Search: https://aistudio.google.com/docs/google-search
- OpenAI crawlers: https://developers.openai.com/api/docs/bots
- OpenAI help, ChatGPT search: https://help.openai.com/en/articles/9237897-chatgpt-search
- Anthropic crawlers: https://support.claude.com/en/articles/8896518-does-anthropic-crawl-data-from-the-web-and-how-can-site-owners-block-the-crawler
- Anthropic subprocessors: https://trust.anthropic.com/subprocessors
- Anthropic developer docs llms.txt: https://platform.claude.com/llms.txt
- Perplexity crawlers: https://docs.perplexity.ai/guides/bots
- Bing, AI Performance, 10 Feb 2026: https://blogs.bing.com/webmaster/February-2026/Introducing-AI-Performance-in-Bing-Webmaster-Tools-Public-Preview
- Microsoft Advertising, 8 Oct 2025: https://about.ads.microsoft.com/en/blog/post/october-2025/optimizing-your-content-for-inclusion-in-ai-search-answers
- Meetup help and blog: [creating an event](https://help.meetup.com/hc/en-us/articles/39790436736525-Creating-an-event), [ranking factors](https://help.meetup.com/hc/en-us/articles/32864852208269-Why-are-my-events-or-groups-not-visible-or-not-ranked-among-first-in-my-area), [visibility](https://help.meetup.com/hc/en-us/articles/39489043789325-How-can-I-improve-visibility-for-my-events-and-groups), [notifications](https://help.meetup.com/hc/en-us/articles/40708711774221-What-notifications-Meetup-can-send), [RSVP tips](https://www.meetup.com/blog/4-tips-more-rsvps-personal-recommendations/)
- Luma help: [search](https://help.luma.com/p/searching-for-events), [featuring](https://help.luma.com/p/featuring-your-event-on-luma), [registration questions](https://help.luma.com/p/collect-registration-questions), [submitting to calendars](https://help.luma.com/p/submitting-events-to-calendars)
- Umami: [source constants](https://raw.githubusercontent.com/umami-software/umami/master/src/lib/constants.ts), [UTM](https://docs.umami.is/docs/utm), [events](https://docs.umami.is/docs/track-events), [goals](https://docs.umami.is/docs/goals)
- Plausible changelog: https://plausible.io/changelog

German official and legal sources

- KURSNET Nutzungsbedingungen: https://www.kursnet-online.arbeitsagentur.de/onlinekurs/printNutzungsbedingungen.do
- BA Eingabehilfe Weiterbildungsangebote, 31 Mar 2025: https://www.arbeitsagentur.de/datei/kursnet-eingabehilfe-weiterbildungsangebote_ba035945.pdf
- BA KURSNET Redaktionshandbuch, 1 Aug 2025: https://www.arbeitsagentur.de/datei/kursnet-redaktionshandbuch_ba147351.pdf
- BA XML upload: https://www.arbeitsagentur.de/institutionen/kurse-anbieten/xml-upload
- BA Hinweisblatt for providers, 19 Mar 2024: https://arbeitsagentur.de/datei/dok_ba015523.pdf
- Beirat recommendations, 17 Jun 2026: https://www.arbeitsagentur.de/datei/dok_ba032840.pdf
- BA Impressum: https://www.arbeitsagentur.de/impressum
- UWG: [§ 5](https://www.gesetze-im-internet.de/uwg_2004/__5.html), [§ 5b](https://www.gesetze-im-internet.de/uwg_2004/__5b.html), [§ 6](https://www.gesetze-im-internet.de/uwg_2004/__6.html), [§ 7](https://www.gesetze-im-internet.de/uwg_2004/__7.html), [Anhang](https://www.gesetze-im-internet.de/uwg_2004/anhang.html)
- SGB III § 176: https://www.gesetze-im-internet.de/sgb_3/__176.html
- AZAV § 2: https://www.gesetze-im-internet.de/azav/__2.html
- DSK Orientierungshilfe Direktwerbung: https://www.datenschutz-bayern.de/dsbk-ent/DSK_96-Werbung.pdf
- IWWB: https://www.iwwb.de/information/Hinweis-fuer-Weiterbildungsanbieter-Seminaranbieter-Bildungsinstitute-etc.-weiterbildung-33.html and https://www.iwwb.de/information/Partnerdatenbanken-IWWB-weiterbildung-18.html
- deinbildungsgutschein.de: https://deinbildungsgutschein.de/agb and https://deinbildungsgutschein.de/llms.txt
- fortbildung24: https://www.fortbildung24.com/kurse-eintragen.html
- kursfinder: https://anbieter.kursfinder.de/
- bundesAPI repository: https://github.com/bundesAPI/weiterbildungssuche-api
- LTO on OLG Hamm: https://www.lto.de/recht/nachrichten/n/olg-hamm-urteil-i-4-u-171-12-werbung-tanzschule-unzulaessig
- Law firm summary of LG Stuttgart: https://www.ra-kotz.de/die-irrefuehrende-foerderfaehigkeit-wettbewerbsrecht-und-falsche-werbung.htm
- IHK Karlsruhe on the BGH ruling: https://www.ihk.de/karlsruhe/fachthemen/recht/vertragsrecht/coaching-6677500
- FTC rule on consumer reviews and testimonials, 16 CFR Part 465: https://www.ecfr.gov/current/title-16/chapter-I/subchapter-D/part-465
- Trustpilot guidelines: https://corporate.trustpilot.com/legal/for-businesses/guidelines-for-businesses

Studies and practitioner sources

- Ahrefs: [llms.txt study](https://ahrefs.com/blog/llmstxt-study/), [schema test](https://ahrefs.com/blog/schema-ai-citations/), [brand visibility correlations](https://ahrefs.com/blog/ai-brand-visibility-correlations), [AI Overview citations and rank](https://ahrefs.com/blog/ai-overview-citations-top-10/), [freshness](https://ahrefs.com/blog/do-ai-assistants-prefer-to-cite-fresh-content/), [time to rank](https://ahrefs.com/blog/how-long-does-it-take-to-rank-in-google-and-how-old-are-top-ranking-pages/), [best lists](https://ahrefs.com/blog/best-lists-research/), [subdomain vs subfolder](https://ahrefs.com/blog/subdomain-vs-subfolder/), [AI vs search benchmark](https://ahrefs.com/benchmarks/ai-vs-search), [AI conversions on ahrefs.com](https://ahrefs.com/blog/ai-search-traffic-conversions-ahrefs/), [prompt demand estimates](https://ahrefs.com/blog/how-ahrefs-estimates-ai-search-demand/)
- SE Ranking: [ChatGPT citation factors](https://seranking.com/blog/how-to-optimize-for-chatgpt/), [llms.txt](https://seranking.com/blog/llms-txt/)
- Semrush: [most cited domains](https://www.semrush.com/blog/most-cited-domains-ai/), [AI traffic study](https://www.semrush.com/blog/ai-search-seo-traffic-study/)
- Profound: [citation patterns](https://www.tryprofound.com/blog/ai-platform-citation-patterns), [Reddit](https://tryprofound.com/blog/the-data-on-reddit-and-ai-search), [LinkedIn](https://tryprofound.com/blog/linkedin-is-the-most-cited-domain-for-professional-queries-in-ai-search)
- BrightEdge: [rank overlap](https://www.brightedge.com/resources/weekly-ai-search-insights/rank-overlap-after-16-months-of-aio), [YouTube](https://brightedge.com/resources/weekly-ai-search-insights/youtube-presence-ai-search)
- Seer Interactive: [ghost citations](https://seerinteractive.com/insights/llm-ghost-citations-why-your-content-is-working-and-your-brand-isnt), [recency 2026](https://www.seerinteractive.com/insights/study-content-recencys-impact-on-ai-visibility-in-2026), [recency 2025](https://www.seerinteractive.com/insights/study-ai-brand-visibility-and-content-recency), [llms.txt](https://www.seerinteractive.com/insights/llms.txt-vs-ai-info-page), [bylines](https://www.seerinteractive.com/work/case-studies/author-bylines)
- DEJAN: [Reddit](https://dejan.ai/blog/reddit-ai/), [crawler census](https://dejan.ai/blog/crawler-census-robots-llms-okf/)
- Zyppy: [expert survey](https://signal.zyppy.com/p/google-ai-ranking-factors), [evidence review](https://signal.zyppy.com/p/ai-citation-ranking-factors)
- SparkToro and Gumshoe: https://sparktoro.com/blog/new-research-ais-are-highly-inconsistent-when-recommending-brands-or-products-marketers-should-take-care-when-tracking-ai-visibility/
- Aggarwal et al., GEO paper: https://arxiv.org/abs/2311.09735
- Kevin Indig via Search Engine Journal: https://www.searchenginejournal.com/the-science-of-how-ai-pays-attention/567597/
- Search Engine Journal: [llms.txt and Mueller](https://www.searchenginejournal.com/google-says-llms-txt-comparable-to-keywords-meta-tag/544804/), [SE Ranking llms.txt coverage](https://www.searchenginejournal.com/llms-txt-shows-no-clear-effect-on-ai-citations-based-on-300k-domains/561542/), [schema test by Williams-Cook](https://www.searchenginejournal.com/schema-llms-the-low-bar-for-evidence-in-geo/576090/), [AI impressions report](https://www.searchenginejournal.com/google-reports-ai-search-impressions-how-to-read-them/582824/), [Reddit drop](https://www.searchenginejournal.com/why-reddits-chatgpt-citation-drop-isnt-fully-explained/534572/), [ChatGPT tracking bug](https://www.searchenginejournal.com/chatgpt-traffic-drop-appears-to-be-a-tracking-problem/593157/), [rater guidelines](https://www.searchenginejournal.com/google-updates-search-quality-rater-guidelines-what-to-know/538259/)
- Search Engine Roundtable: [hreflang single language](https://www.seroundtable.com/one-language-hreglang-google-23970.html), [language per page](https://www.seroundtable.com/google-language-per-page-basis-32620.html), [spam policies and AI responses](https://www.seroundtable.com/google-spam-policies-apply-ai-responses-41331.html), [listicle statement](https://www.seroundtable.com/google-warns-against-trying-to-manipulate-llms-41156.html), [Canel and schema](https://www.seroundtable.com/schema-llms-copilot-bing-microsoft-39093.html)
- Lily Ray: [cited is not recommended](https://lilyraynyc.substack.com/p/why-calling-yourself-the-best-could), [listicle drops](https://lilyraynyc.substack.com/p/is-google-finally-cracking-down-on)
- PPC Land: [Scrunch study](https://ppc.land/self-ranked-brands-gain-ai-recommendations-from-4-to-7-scrunch-finds/), [Kraham attribution](https://ppc.land/googles-vp-of-search-tells-cmos-good-seo-is-still-all-you-need-for-ai/)
- Peec AI data via Wix: https://www.wix.com/studio/ai-search-lab/research/content-types-most-cited-by-llms
- Peec, ChatGPT search providers: https://docs.peec.ai/research/chatgpt-search-result-providers
- Surfer: [query fan-out](https://surfer.ai/blog/query-fan-out/), [API vs app](https://surfer.ai/blog/llm-scraped-ai-answers-vs-api-results)
- Temso, online education: https://www.temso.ai/data/AI-Source-Citation-Patterns-in-Online-Education-Platforms
- 5W EdTech index: https://5wpr.com/research/edtech-ai-visibility-index-2026
- Scrunch, industry breakdown: https://scrunch.com/blog/reddit-paradox-industry-breakdown-of-most-cited-ai-sources
- AirOps: https://www.airops.com/report/structuring-content-for-llms
- Search Atlas: https://searchatlas.com/blog/limits-of-llms-txt-for-ai-search-citation-study/
- OtterlyAI llms.txt experiment: https://otterly.ai/blog/the-llms-txt-experiment/
- Mintlify benchmark: https://mintlify.com/blog/llms-txt-agent-benchmark
- Alejandro Rioja: https://alejandrorioja.com/llms-txt-explained-what-it-is-and-whether-it-actually-moves-citations/
- Harps Digital: https://harpsdigital.com/learn/aeo-geo-myths
- Vercel and MERJ: https://vercel.com/blog/the-rise-of-the-ai-crawler
- TechCrunch on Claude and Brave: https://techcrunch.com/2025/03/21/anthropic-appears-to-be-using-brave-to-power-web-searches-for-its-claude-chatbot/
- Amsive: https://www.amsive.com/insights/seo/llm-traffic-conversion-rate-study/
- University of Hamburg: https://www.bwl.uni-hamburg.de/en/ueber-die-fakultaet/aktuelles/2025/1106-chatgpt-und-e-commerce.html
- Conductor: https://www.conductor.com/academy/debunking-ai-prompt-volume/
- David Rosam: https://buttondown.com/davidrosam/archive/everyone-quotes-60-nobody-measured-it/
- Grow and Convert: https://www.growandconvert.com/conversion-rate-optimization/average-seo-conversion-rate/
- Career Karma survey: https://careerkarma.com/blog/bootcamp-outcomes-survey-2021
- Course Report: [2016 study](https://www.coursereport.com/reports/2016-coding-bootcamp-job-placement-demographics-report), [connect](https://www.coursereport.com/connect), [Berlin](https://www.coursereport.com/cities/berlin)
- SwitchUp: https://www.switchup.org/about
- RNL 2025 E-Expectations: https://learn.ruffalonl.com/rs/395-EOG-977/images/2025_E-Expectations_Report.pdf
- Livestorm benchmark 2026: https://livestorm.co/webinar-benchmark-report-2026
- Goldcast: https://www.goldcast.io/blog-post/webinar-benchmarks
- Xtalks: https://xtalks.com/we-analyzed-over-100-webinars-for-title-and-abstract-length-heres-how-they-affect-registration-rate
- NextAfter: https://www.nextafter.com/?p=13355
- PheedLoop: https://pheedloop.com/blog/event-data-lab-report-5
- Maven: https://help.maven.com/en/articles/9494893-guide-to-successful-lightning-lesson-conversion
- 3Play Media: https://3playmedia.com/why-3play/case-studies/this-american-life/
- Wix recap of the Zyppy internal link study: https://www.wix.com/seo/learn/resource/internal-linking-webinar
- Go Fish Digital: https://gofishdigital.com/case-study/online-trading-academy/
- Michael Drogalis: https://michaeldrogalis.substack.com/p/week-12-did-it-work
- Formgrid: https://formgrid.dev/blog/3-months-96-signups-and-2-paying-customers-what-i-learned-building-formgrid-in-public

Internal context

- [domain and SEO plan](domain-and-seo-plan.md)
- [SEO content plan](seo-content-plan.md)
- [supply-jobs-and-bootcamps.md](supply-jobs-and-bootcamps.md)
- [berater-objections.md](berater-objections.md)
- Live academy pages and DataTalksClub Meetup events, checked 15 Nov 2026

## 9. What Practitioners Say on X

I searched X for practitioner posts on AEO, GEO and llms.txt (May to November 2026) and for posts from developers in Germany about the Bildungsgutschein or AI courses (2026). Each practitioner post was traced to its primary source in section 6.

Practitioner posts that hold up:

- [Harpreet Chatha, 25 Jun 2026](https://x.com/harpreetchatha_/status/2069991843367198774) (393 likes, 874 bookmarks): SEO drives AI citations; a mention is not a citation; no one has shown ROI from llms.txt or from schema for LLMs; engines behave differently; mass publishing does not win; start by asking AI about your brand before buying a tracker.
- [Summary of Google's "Good SEO is good GEO"](https://x.com/alexgroberman/status/2069447233288954101), 23 Jun 2026. Primary source: [Think with Google](https://business.google.com/us/think/search-and-video/ai-search-era-brand-authority-strategy/). AI Mode and AI Overviews use the same index and ranking systems; no special AI text files; no inauthentic mentions; query fan out rewards coverage across the whole buying journey.
- [Summary of an SE Ranking ChatGPT citation study](https://x.com/alexgroberman/status/2084990154759102592), 5 Aug 2026 (129,000 domains, 100,000 prompts). The poster sells SEO packages; use the [SE Ranking original](https://seranking.com/blog/how-to-optimize-for-chatgpt/) only. Referring domains, traffic, Reddit and Quora mentions, depth, clear sections and recent updates correlate with citations; llms.txt had negligible effect; FAQ schema did not help.
- [Tim Soulo on Dan Petrovic, 28 Aug 2026](https://x.com/timsoulo/status/2093326483158925544): ChatGPT, Gemini and Claude search different indexes (Bing, Google, Brave); Brave for Claude is confirmed by Anthropic's subprocessor list. "Prompt search volume" does not exist. Reddit rejection holds for OpenAI's API in [DEJAN's data](https://dejan.ai/blog/reddit-ai/).
- [Aleyda Solis on Cyrus Shepard's survey, 18 Sep 2026](https://x.com/aleyda/status/2100860016005681355). Primary source: [Zyppy](https://signal.zyppy.com/p/google-ai-ranking-factors). Expert opinion: crawl access, answer match, brand known to the model and citable facts at the top; structured data and llms.txt at the bottom.
- llms.txt anecdotes, consistent with the log studies in 1.5: [4 SaaS sites, 25 prompts each, 4 weeks, citations 16 before and 17 after](https://x.com/isaac_dev0/status/2100302952288403738); [2 AI bot hits on llms.txt against 424 on the HTML sitemap in 30 days](https://x.com/hello_code_/status/2099188229400363338).
- [Roundup, 26 Jun 2026](https://x.com/RyanYorkSEO/status/2070296542993362956): Search Console generative AI reports launched (confirmed by the [Google blog](https://developers.google.com/search/blog/2026/06/gen-ai-performance-reports)); low citation overlap between engines.

Demand side, Germany:

- Very few developers in Germany talk about the Bildungsgutschein on X. German posts with the hashtag are mostly provider ads with "100% gefördert" claims and near zero engagement, for example [this one](https://x.com/talentivo1/status/2052357993023303785). X is not a demand channel for this audience; Reddit and LinkedIn are better places to listen.
- A creator thread aimed at foreign doctors explains that the voucher "is not automatic. You have to request it. In a meeting. With a specific argument." ([thread](https://x.com/DrJakpa/status/2074213819153338708)). The same angle fits our German page and the "How to Get a Bildungsgutschein as an Experienced Developer" article.
- Recurring posts tell laid off Blue Card holders to register with the Agentur within three days ([example](https://x.com/Experttalkswith/status/2120287482193318399)). Laid off non German developers are an audience for an English explainer.
- My own track poll is public: [X post, 13 Nov 2026](https://x.com/Al_Grigor/status/2121166242975551861).

How we use X for AEO: X is not in any citation share study above as a major source for course queries. Use it to distribute the build log, session recaps and YouTube videos, which are cited sources.

This research is written by AI from my notes.
