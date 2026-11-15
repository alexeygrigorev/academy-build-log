# DataTalksClub Academy Content Audit, November 2026

Date: 15 November 2026 (Europe/Berlin). I audited the academy content: the three free Hireable With AI sessions, the academy pages (home, both course pages, sessions page), this build log and newsletter mentions of the academy. Related pages: [marketing plan](marketing-plan.md), [article plan](article-plan.md), [competitor keyword research](competitor-keywords.md).

On the site the brand is written DataTalks.Club Academy. On social and in this build log it is DataTalksClub Academy.

How I judged each item:

- Target fit: does it speak to experienced developers (2+ years) in Germany who are voucher-eligible?
- AEO (answer engine optimization): does it give a direct answer an AI tool can quote for a question people ask?
- Title options use Title Case, no dashes, no placement promises and only sourced numbers.
- The primary CTA on every academy page is "Join the Waitlist", and the primary KPI is confirmed voucher-eligible waitlist signups. Expected impact is stated against that KPI where it applies.

Sources: the page text of the academy site, the Meetup snapshot of 14 November 2026 (attendee counts come from it), and live page checks on 15 November 2026.

## 1. The Three Hireable With AI Sessions on Meetup

Shared facts from the live check on 15 Nov 2026: all three are online events, the description opens with the approved intro, and none of the three descriptions contains a link to `datatalks.club/academy/` or to the sessions page. The group has 10,735 members on the live page (10,742 in the snapshot of 14 Nov).

On 15 November 2026 I approved new titles for the three sessions. They name the audience, experienced developers, and for 30 November the tool people search for: "claude code" has 135,000 searches a month in Germany (Serpstat). The sessions also get an "Academy" tag on the DataTalksClub site, as a separate Academy brand next to the regular community events.

### 1.1 Event 317427871, Mon 23 Nov 2026, 17:00 Berlin

- Old title: "AI Engineering vs Agentic Engineering".
- New title: "AI Engineering vs Agentic Engineering for Experienced Developers".
- Summary: free session for developers with 2+ years who were laid off, are in their notice period or are looking for a job. It defines both terms in one sentence each. A 15 to 20 minute talk on how they differ, what companies want, which to pick as a backend, frontend or data person, and how to get a Bildungsgutschein. Then Q&A. 11 attendees in the snapshot.
- Target fit: yes. It names 2+ years, the three job situations and the Bildungsgutschein. Missing in the description: the word "Germany" (only "Berlin time" appears), and any hint that German level matters for the voucher.
- AEO: partly. The two definitions are quotable answers to "what is the difference between AI engineering and agentic engineering". Missing in the description: who is speaking (no name or one-line bio), the series name "Hireable With AI", a link to a page that stays online after the event, and the organiser name.
- Expected impact: the new title tells beginners the session is not for them. The link and speaker line matter more: they let Meetup visitors reach the email form and let AI tools connect the event to the academy. Target: 40% of Meetup RSVPs also fill the sessions form.

### 1.2 Event 317427748, Mon 30 Nov 2026, 17:00 Berlin

- Old title: "Agentic Engineering: How I Build Software with Coding Agents".
- New title: "How I Build Software with Claude Code and Other Coding Agents".
- Summary: same intro. It defines agentic engineering as using tools like Claude Code or Cursor to write most of the code while you decide what to build and check the result. I talk about how my work changed, what I still do myself, what companies expect, and the voucher. Then Q&A. 12 attendees in the snapshot.
- Target fit: yes, same strengths and the same missing "Germany".
- AEO: partly. The definition is a clean one-sentence answer to "what is agentic engineering". Missing in the description: the same four items as session 1. The term "agentic engineering" is almost never searched (Google Trends value near 0 against 38 to 65 for "Claude Code" in 2026, [market sizing research](market-sizing.md), section 6.1). The new title puts the searched tool name, Claude Code, first.
- Expected impact: with the tag, the link and the speaker line, the event reads as part of one Academy series. Target: 40% of Meetup RSVPs also fill the sessions form.

### 1.3 Event 317427758, Mon 7 Dec 2026, 17:00 Berlin

- Old title: "AI Engineering: How to Build Apps on Top of LLMs".
- New title: "AI Engineering for Experienced Developers: How to Build Apps on Top of LLMs".
- Summary: same intro. It defines AI engineering as building products that use LLMs. I talk about what AI engineers build day to day, which skills from backend, frontend or data work carry over, what to learn first, and the voucher. Then Q&A. The snapshot shows no attendee count.
- Target fit: yes. "Which skills you already have" speaks directly to experienced people. Same missing "Germany".
- AEO: partly. Good definition. Missing in the description: the same four items. "Python helps for 7 December" is on the sessions page but not in the event.
- Expected impact: the group is broad, so the new title and the description both filter for experience. Target: at least 60% of registrants report 2+ years in the sessions form.

### 1.4 Description Edits That Apply to All Three

1. Add one closing line with the page that collects email and the recording: "Recordings and materials go to everyone who registers at datatalks.club/academy/sessions/" (link with `utm_source=meetup&utm_medium=event&utm_campaign=hireable_with_ai`).
2. Add one line with the waitlist: "Join the waitlist for the full-time programs at datatalks.club/academy/" (same UTM values).
3. Add a speaker line: "I'm Alexey Grigorev. I have taught more than 100,000 students in DataTalks.Club courses."
4. Add "in Germany" once in the Bildungsgutschein bullet, for example "how to get a Bildungsgutschein for your training in Germany".
5. Use the series name "Hireable With AI" in the first line.

### 1.5 Where the Session Titles Are Published

On 15 November the old titles appeared in these places, and each one moves to the new titles:

- Meetup events 317427871, 317427748 and 317427758 in the Berlin DataTalksClub group.
- `datatalks.club/academy/sessions/`: the hero list, the form checkboxes and the schedule.
- The session copy that every other text starts from.

They are not on luma.com/dtc-events and not on `datatalks.club/events.html`. The "Academy" tag fixes the second gap: tagged sessions appear on the events page as Academy events.

## 2. Site Pages

Live state at the time of the check on 15 Nov 2026: the pages return 200 at `https://datatalks.club/academy/...` with canonicals pointing there. The same pages still returned 200 on `academy.datatalks.club` with self-referencing canonicals, because the move to the new path was under way that day and the 301 redirects were not live at that moment. The home, Agentic Engineering and sessions pages carried no JSON-LD. `/academy/faq/`, `/academy/bildungsgutschein/` and `llms.txt` returned 404.

Every page change below is on my site fix list, and every fact follows one fact sheet that all pages share.

### 2.1 Sessions Page, `/academy/sessions/`

- Current title tag and H1: "Between jobs: the AI skills that get experienced developers hired".
- Summary: three free online sessions for developers with 2+ years who were laid off, are in a notice period or are job hunting; Berlin first, anyone can join. Form with session choice, track interest, situation, years, location, voucher interest. Session blocks with the approved texts. Two sourced numbers (match.dev on 4,820 postings; Stellenradar on 3,280 unemployed developers and 100 vacancies in Berlin). FAQ with seven questions.
- Target fit: yes. This is the best-targeted page of the site. It names experience, the job situations and Berlin, and the form measures eligibility signals. Gaps: the form does not ask German level; "Germany" appears only in the FAQ.
- AEO: partly. Strong: session dates and times in text, direct FAQ answers ("Is it really free? Yes."), sourced numbers with month. Missing: `Event` structured data; the series name "Hireable With AI", which is a target keyword for this page and is not on the page; a short answer block under the H1; a link to the German voucher page.
- Decisions: the series name is "Hireable With AI". The instructor line is "I have taught more than 100,000 students in DataTalks.Club courses", so the older figure of 12,755 comes off the page.
- New title tag: "Hireable With AI: Free Sessions for Experienced Developers | DataTalks.Club". The H1 headline stays as it is, and the session titles on the page move to the new titles.
- CTA: "Choose my sessions" stays the primary CTA until 7 Dec 2026, with a secondary "Join the Waitlist" link. After 7 Dec the primary CTA becomes "Join the Waitlist" with the recordings.
- Expected impact: a series name that matches across page, Meetup and posts lets AI tools and Google treat it as one series. `Event` markup and the recap blocks give the page a life after 7 December. Target: page indexed by 23 Nov; 80 registrations per session; 25 confirmed waitlist signups per session.

### 2.2 Agentic Engineering, `/academy/agentic-engineering/`

- Current title tag: "Agentic Engineering | DataTalks.Club Academy". H1: "Ship Software with Coding Agents".
- Summary: definition of agentic engineering, a 3-month (13-week) full-time course for developers who already write code, 15 seats, taught live by me, program basis line, waitlist form with a two-question survey, seven outcomes, final project, instructor block, fit and non-fit lists, 16 modules, funding block, why 15 seats, admission steps, ten FAQ questions.
- Target fit: partly. Strong on full-time, English, and "including if you are between jobs". But the stated baseline is "developers who already write code" and "You can write basic code in Python", not 2+ years of experience. Germany appears only in the FAQ. The start is absent: the FAQ says "There is no active cohort right now" and never says April 2027. German level and the voucher path for experienced people are not addressed, and there is no link to a voucher guide.
- AEO: partly. Strong: a one-sentence definition at the top, a fact table (format, where, language, seats), direct FAQ answers, module outputs. Missing: the start, the experience threshold, "in Germany" near the top, `Course` and `FAQPage` markup, and a question that matches the test question "Is there an agentic engineering course for experienced developers in Germany?".
- Decisions: daily hours are Monday to Friday, 09:00 to 16:30 Berlin time; the 16:00 on the live page is replaced. Location is "Berlin or live online", without the district or station name. The start line is "Start: April 2027". The funding line is "Designed for Bildungsgutschein funding (AZAV)."
- Rule check: the instructor block says "teach paid cohort courses on Maven" and shows a "Cohort Courses on Maven" link. Maven courses are my personal courses and I promote them only from my personal accounts, so the block comes off the academy page.
- New title tag: "Agentic Engineering Course in English for Experienced Developers | DataTalks.Club Academy". Meta description: "Learn to ship software with coding agents like Claude Code. Full-time live program in English for developers with 2+ years in Germany. Start: April 2027." The H1 can stay. One open point from the [competitor keyword research](competitor-keywords.md): "Germany" in the title or H1, for the target query "agentic engineering course germany".
- Answer block under the H1: "Agentic Engineering is a 3-month full-time live program in English for developers with 2+ years of experience in Germany. You learn to use coding agents like Claude Code or Cursor to write most of the code, while you decide what to build and check the result. Start: April 2027, 15 seats, designed for Bildungsgutschein funding (AZAV)."
- Expected impact: this is the page that should be cited for the agentic test question, where today's answers list 2 to 5 day workshops and no full-time program. Target: named for that question in one of three tools by 7 Dec; top 3 for "agentic engineering course germany" by 31 Jan 2027 and #1 by 31 Mar 2027.

### 2.3 AI Engineering, `/academy/ai-engineering/`

- Current title tag: "AI Engineering | DataTalks.Club Academy". H1: "Build and Evaluate LLM Applications".
- Summary: same structure as the Agentic page. Definition of AI engineering, seven outcomes (LLM API assistant, RAG, tools and MCP, human approval, evaluation, deployment and tracing, quality, latency and cost), final project, 16 modules, same funding, seats and admission blocks.
- Target fit: partly, with the same gaps: no 2+ years, no April 2027, Germany only in the FAQ. The prerequisites are clearer than on the Agentic page ("comfortable programming, preferably in Python... command line, Git and basic Docker").
- AEO: partly. Same strengths and gaps as 2.2. This page competes for the test question "What AI engineering courses in Berlin can I pay for with a Bildungsgutschein?", where Turing College holds most cited sources. Turing's landing states a 1-year coding prerequisite, B2+ language, next start date and funding in plain text ([live check, 15 Nov](https://www.turingcollege.com/ai-engineering-bildungsgutschein)). With the fix list my page states the same kinds of facts in its first lines.
- Decisions: the same four points as 2.2 (hours 09:00 to 16:30, "Berlin or live online", "Start: April 2027", the funding line).
- Rule check: the same Maven mention and link as 2.2. It comes off the page.
- New title tag: "AI Engineering Course in English for Experienced Developers | DataTalks.Club Academy". Meta description: "Learn to build and evaluate LLM products. Full-time live program in English for developers with 2+ years in Germany. Start: April 2027, 15 seats." One open point from the competitor keyword research: "Berlin" in the title or H1, for the target queries "ai engineering course berlin" and "ai engineering bootcamp berlin".
- Answer block under the H1: "AI Engineering is a 3-month full-time live program in English for developers with 2+ years of experience in Germany. You learn to build and evaluate products that use LLMs, like chatbots, search over company documents and agents. Start: April 2027, 15 seats, designed for Bildungsgutschein funding (AZAV)."
- Expected impact: a correct description by AI tools, and a candidate for the Berlin and German test questions. Target: named for one of them in two of three tools by 31 Mar 2027; top 3 for "ai engineering course berlin" by 31 Mar 2027.

### 2.4 Home, `/academy/`

- Current title tag: "DataTalks.Club Academy | Live Full-Time Courses with Alexey Grigorev". H1 area: "Live Full-Time Courses in Berlin or Online".
- Summary: one paragraph from me, two program cards with three outcomes each, a fact table and a short funding block.
- Target fit: partly. It says "developers who already write code". It does not say experienced or 2+ years, does not say Germany, does not say April 2027, and does not link to the sessions page or a voucher guide (the page links only to the two course pages). There is no waitlist button on the page.
- AEO: no. This should be the page that answers "What is DataTalks.Club Academy?". The brand search on 15 Nov returned only free-course pages. The home page has no single sentence that states who, what, when, how many, in which language and how it is funded, no FAQ, no `Organization` markup and no instructor line.
- Title options:
  1. "DataTalks.Club Academy: Full Time AI Programs for Experienced Developers in Germany".
  2. "DataTalks.Club Academy: AI Bootcamp in Berlin for Experienced Developers". This one carries the target queries "ai bootcamp berlin" and "ai bootcamp" from the competitor keyword research.
  3. "Live AI Engineering Programs for Experienced Developers in Germany | DataTalks.Club Academy".
- My pick: option 2, because `/academy/` is the target page for two of the top 10 queries and the current #1 results are weak sites.
- Answer block under the H1: "DataTalks.Club Academy is a full-time live program in English for experienced developers in Germany, taught by Alexey Grigorev, who has taught more than 100,000 students in DataTalks.Club courses. There are two programs, Agentic Engineering and AI Engineering, each 3 months, Monday to Friday, 09:00 to 16:30 Berlin time, in Berlin or live online, with 15 seats. Start: April 2027, and the programs are designed for Bildungsgutschein funding (AZAV)."
- Meta description: "Full-time live programs in English for experienced developers in Germany: Agentic Engineering and AI Engineering. Designed for Bildungsgutschein funding (AZAV)."
- Primary CTA: one "Join the Waitlist" button above the fold.
- Expected impact: the highest AEO return of any single edit, because every tool that mentions the brand needs this paragraph. Target: by 7 Dec, Perplexity and ChatGPT describe the academy as a full-time program, not as the free courses; `/academy/` at #1 for "datatalks club academy" by 15 Dec 2026.

### 2.5 Build Log, `https://alexeygrigorev.com/academy-build-log/`

- Current title: "Building the Academy in Public | DataTalksClub Academy Build Log". Three entries: "Why I'm Starting an Academy" (13 Nov), "Finding the Audience and Testing Two Tracks" (14 Nov), "A Closed Coaching Program, Signup Emails, and a Home for the Academy" (15 Nov), plus a research index.
- Summary: first-person record of decisions with sources, charts and links: the survey, audience estimates, session naming, the domain decision, the AI-search baseline, the B2 German question, the case of a competitor school.
- Target fit: partly. The index names "experienced developers in Germany" and April 2027 in its first paragraph, which is more than the academy home does. The readers it attracts are followers and builders, not mainly job seekers. The 15 Nov entry's section on the voucher decision is the most direct text for voucher-eligible readers.
- AEO: partly. Strong: it sits on a second domain, states the facts with dates, and cites sources, which is the kind of independent text AI tools use to confirm a new entity. Weak: entry titles describe the diary ("A Closed Coaching Program, Signup Emails...") and answer no question; links point to `academy.datatalks.club`; the 15 Nov entry says the new path "still returns 404", which was no longer true at the time of the check; the repo README lists the 15 Nov entry under a different title ("Simple Signup Emails and a Home for the Academy") than the entry itself.
- Decision on the brand spelling: the build log is a social surface, so "DataTalksClub Academy" is correct here, and the site keeps "DataTalks.Club Academy". The structured data on the site declares the second spelling as `alternateName`.
- Title options:
  1. Index: "Building DataTalksClub Academy in Public: A Full Time AI Program for Experienced Developers in Germany".
  2. 15 Nov entry: "How the Bildungsgutschein Decision Works, and Where the Academy Lives".
  3. 14 Nov entry: "Who the Academy Is for and How Many People I Can Reach".
- Expected impact: question-shaped entry titles make each entry a citable answer and a ready LinkedIn link. Target: 3 entries cited or linked by third parties by 31 Mar 2027, and 15 confirmed waitlist signups with the build log as first touch.

## 3. Newsletter

State on 15 Nov 2026:

- No published newsletter issue mentions the academy or the sessions. The [sponsor page](https://datatalks.club/blog/sponsor-datatalks-club.html) says the newsletter goes out every Monday to more than 130,000 subscribers.
- The 13 November survey campaign ran only on my personal accounts; the newsletter, Slack, Telegram and Meetup were outside it (build log entry of 13 November 2026). The block in issue #303, due 16 November, moved from the survey form to the academy shortlist with source tags (build log entry of 14 November 2026).
- My personal Substack ([aishippingblog.com](https://aishippingblog.com/archive)): the five most recent post titles are about the generative media course (13 Nov), dark software factories (6 Nov), trends in agentic engineering (20 Oct), trends in AI engineering (12 Oct) and Kubernetes (7 Oct). No title mentions the academy or the sessions.

So the audit item is the #303 block before it goes out.

- Target fit of a default block: at risk. Only 25.1% of the community is in Europe (2025 community survey, cited in the build log), so a block that does not name Germany in its first words spends most of its clicks on people who cannot use a Bildungsgutschein.
- AEO: not applicable to email. If the issue has a public web version, it becomes a second public statement of the facts, which helps.
- Headline options for the block:
  1. "For Experienced Developers in Germany: Three Free Sessions on AI Engineering and Agentic Engineering".
  2. "Hireable With AI: Three Free Monday Sessions for Experienced Developers in Germany".
  3. "New: DataTalks.Club Academy, a Full Time Program for Experienced Developers in Germany".
- Block text: "3 free online sessions for developers with 2+ years of experience who were laid off, are in their notice period or are looking for a job. Mondays 23 Nov, 30 Nov and 7 Dec at 17:00 Berlin time, on Zoom. I skip the basics and assume you already ship code at work." Link: the sessions page with `utm_source=newsletter&utm_medium=email&utm_campaign=hireable_with_ai&utm_content=issue_303`.
- Expected impact: the newsletter is the largest owned channel. Target for #303: 400 clicks, 40 session registrations, 15 confirmed waitlist signups.

## 4. Top Findings

1. The facts an AI tool needs were missing or disagreed on the live pages, and one fact sheet now settles them. "April 2027" and "2+ years" are not on the course pages, "Germany" is only in FAQs, and the home page has no sentence that says what the academy is. Three contradictions are resolved: daily hours are Monday to Friday, 09:00 to 16:30 Berlin time (the live pages said 16:00); the instructor line is "more than 100,000 students" (the sessions page said 12,755, which comes off); the location is "Berlin or live online" everywhere. The start is written "Start: April 2027" and the funding line is "Designed for Bildungsgutschein funding (AZAV)." The site has no FAQ page, no German voucher page, no structured data and no llms.txt. On 15 Nov no AI tool or search result named the academy. All page changes are on my site fix list.

2. At the time of the check on 15 Nov, the move to `datatalks.club/academy/` was under way. Both hosts served the same pages with 200 and their own canonicals, the main sitemap and robots.txt did not reference the academy sitemap, the DataTalksClub events page did not list the three sessions, the blog had no academy post, and the build log still linked to the old host. The 301 redirects go live before any paid click or newsletter send.

3. The three session events are the best-targeted content of the academy, and they are under-promoted. Sessions 1 and 2 had 11 and 12 attendees in the snapshot, eight days before session 1, in a group of 10,742. The event descriptions carry no link to the page that collects email and survey answers, no speaker line and no series name. The 16 November launch stream (31 attendees) and the newsletter (more than 130,000 subscribers, about a quarter in Europe) did not carry the sessions before 15 Nov. The new titles name the audience; the other levers are the description edits in 1.4 and the "Academy" tag.

4. Series and brand names: resolved. The series is "Hireable With AI"; it goes into the sessions page title tag, the first line of the Meetup descriptions and the newsletter block. The brand is "DataTalks.Club Academy" on the site, pages and emails and "DataTalksClub Academy" on social and in the build log, with the second spelling declared as `alternateName` in the structured data. The three sessions have new titles and get an "Academy" tag on the DataTalksClub site, which also lists them on `datatalks.club/events.html`. The sessions page headline stays as it is.

5. Both course pages mention and link the Maven course page. The academy pages should stand on their own, so that block comes off.