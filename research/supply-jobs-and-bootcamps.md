# Job Market and Course Supply: Bootcamps and Voucher Courses

Desk research, 14 November 2026.  

My question: look not only at demand but at supply. What jobs are open now? What programs exist? How crowded is it, and how many seats are there? It seemed to me that nobody really offers agentic engineering.

**Adds to:** [market sizing](market-sizing.md), and my public research in research-dump: [24 AZAV programs](https://github.com/alexeygrigorev/research-dump/blob/main/courses/ai-engineering-school-germany/bildungsgutschein/research-notes/germany-azav-programmes.md) and the [analysis of 9,760 AI Engineer job ads](https://github.com/alexeygrigorev/research-dump/tree/main/courses/ai-engineering-school-germany/agentic-engineering-analysis).

**New here:** (1) a full scan of the BA course catalog (KURSNET via the mein NOW API) for voucher courses, with a classification; (2) fresh job counts from BA Jobbörse, StepStone, LinkedIn, arbeitnow and Berlin Startup Jobs; (3) a skills analysis of 58 real job ads (Berlin first); (4) a test of the hypothesis "bootcamps are outdated", with quotes from programs; (5) first module sketches for both tracks, weighted by how often skills show up in job ads.

**Labels:** **[BA]** primary BA data (Jobbörse API or the mein NOW / KURSNET catalog), pulled on 14 November 2026; **[F]** I opened the page on 14 November 2026; **[RD]** from my research-dump (pages opened on 12 November 2026); **[S]** search snippet or secondary site; **[auto]** my regex count over the text, approximate; **[estimate]** my calculation.

## 1. Summary

1. **Berlin has hundreds of AI jobs, and almost all are for experienced people.** "AI Engineer": 88 in BA Jobbörse (Berlin, 25 km), 314 on StepStone (Berlin), at least 283 on LinkedIn in 30 days (Berlin; the results stop around 300). In my sample of 58 ads, only 2 are junior and 35 are senior, staff or lead. Two thirds of the ads are in English. German is required in 22%.
2. **"Work with coding agents" is already a line in normal developer jobs.** On arbeitnow, in one week (7 to 14 November), 86 of 588 developer jobs in Germany (14.6%) name Claude Code, Cursor, Copilot, Codex or AI-assisted coding; in Berlin, 28 of 154 (18.2%) **[auto]**. This matches Indeed (20.8% of software development ads mention AI, November 2025) and match.dev ("one engineering posting in five" has a line about AI coding tools).
3. **The market for AI skills grows fast.** Index Research: 58,500 job ads with AI skills in Germany in Q3 2026, +88% on Q3 2025 and about 2.3 times Q3 2024 (~25,000). In my job-ad corpus, the share of AI Engineer ads that mention coding agents grew from 12.8% (February 2026) to 25.1% (November 2026).
4. **The supply of "KI" courses is huge, but most are courses for AI users.** The BA catalog finds 14,559 voucher courses for the word "KI". "Prompt Engineering" appears in 3,071 of them, "LangGraph" in 8, "Evals" in 4, "Agentic Coding" in 41 **[BA]**. Of 2,217 AI courses I pulled, 924 (42%) are for managers, office work and no-code automation **[auto]**.
5. **AI Engineering is crowded.** 136 voucher courses with an "AI/KI Engineer / Entwickler" title from 23 providers. Only 21 of them (15%) describe LLM applications (RAG, LangChain, evals or MCP), and 2 mention coding agents **[auto]**. The rest start from ML/DL or from Azure/Power Platform. Turing College (Berlin) alone has 6 versions of an LLM course.
6. **Agentic engineering for experienced people is not empty, but nobody owns it.** 35 voucher courses from 22 providers name development with AI tools in the title. They are either short German modules of 2 to 4 weeks (alfatraining "Claude Code", the IBB franchise "Softwareentwicklung mit KI-Tools" at 9 providers, future Training, GFN) or long full-stack programs for beginners with one block about agents (WBS, HECKER, Developer Akademie). Courses with "Agentic" in the title (Turing "Agentic Engineering", MSIT "Agentic Software Engineer", Spiced "Agentic AI") teach how to **build** agents, not how to develop **with** agents. I found no program of 3 to 4 months, in English, live, for experienced developers, where working with coding agents is the main subject. The closest is Digitale Leute "AI Software Engineering" (English, 3 months, but also for beginners).
7. **My hypothesis holds only by half.** Long voucher programs are mostly for beginners or start with classic ML (IfaDW, 1,050 UE: Python → ML → DL → NLP → Big Data → MLOps). But modern programs exist: GFN (4 weeks, your own agent loop, an MCP server, eval datasets in CI, diff review), alfatraining Claude Code (CLAUDE.md, sub-agents, hooks, MCP), Turing (LangGraph + DeepEval). "All bootcamps are outdated" does not survive a check. The narrower claim does: "there is no long, modern program for experienced developers".
8. **Agentic has the better balance of demand and supply.** Demand sits inside normal developer jobs (Softwareentwickler: 3,030 at the BA vs 524 "AI Engineer"), and there are almost no long competitors. AI Engineering is a clearer job for a Vermittler, but it is crowded. A test still decides.

## 2. The job market

### 2.1 How many jobs (14 November 2026)

| Query | BA Jobbörse, Berlin 25 km | BA Jobbörse, Germany | StepStone, Berlin | LinkedIn, Berlin, 30 days |
|---|---|---|---|---|
| AI Engineer | 88 | 524 | 314 | ≥283 |
| KI Engineer | 86 | 570 | n/a (blurred results) | — |
| LLM Engineer | 19 | 91 | 55 | ≥297 (blurred) |
| GenAI Engineer | 14 | 40 | n/a | ≥299 (blurred) |
| Generative AI | 45 | 169 | n/a | — |
| Applied AI | 5 | 40 | n/a | ≥295 (blurred) |
| AI agents | 32 | 100 | n/a | ≥250 |
| agentic | 56 | 181 | 117 | ≥300 |
| RAG | 55 | 259 | 60 | — |
| MCP | 9 | 94 | 42 | — |
| LangGraph | 10 | 23 | 14 | — |
| Claude Code | 19 | 143 | n/a | ≥262 (blurred) |
| Cursor | 6 | 92 | 38 | — |
| GitHub Copilot | 8 | 74 | 285 (blurred) | — |
| coding agents | 4 | 35 | n/a | ≥156 |
| Machine Learning Engineer | 22 | 137 | 99 | — |
| Software Engineer | 120 | 1,284 | 721 | — |
| Softwareentwickler | 185 | 3,030 | 676 | — |

How to read it:

- **BA Jobbörse [BA]:** public API, full-text search, jobs only. About half of all openings reach the BA, so the numbers show ratios, not the whole market.
- **StepStone [F]:** the "N Jobs in Berlin" count on the search page. StepStone adds synonyms, so some queries are blurred ("GenAI Engineer" gives 2,617). Those cells say "n/a".
- **LinkedIn [F]:** guest search without login, Berlin, last 30 days. Results stop around 300, so "≥". LinkedIn also mixes in similar jobs: of 887 unique jobs over 10 queries, only 358 have AI/ML/LLM/Agent in the title.
- **arbeitnow [F]:** public API, all jobs from 7 to 14 November 2026 = 5,204, of them ~2,690 in Germany. 588 developer jobs in Germany: 93 (15.8%) with AI/ML/LLM/Agent in the title, 86 (14.6%) with AI coding tools in the text. Berlin: 154 / 32 (20.8%) / 28 (18.2%) **[auto]**.
- **Berlin Startup Jobs [F]:** about 31 engineering jobs, 3 with AI in the title. Too small to count the market.
- **Indeed DE and GermanTechJobs** returned 403, so I could not count them. Indeed Hiring Lab data is below.

### 2.2 Trend: is "AI engineer" growing, and do normal jobs add AI tools?

| Signal | Number | Source |
|---|---|---|
| Job ads with AI skills, Germany | Q3 2024 ~25,000 → Q3 2025 ~31,100 → Q3 2026 ~58,500 (+88% year on year); IT industry 13,100 | [Index Research, KI-Kompetenzmonitor Q3/2026](https://www.index.de/pressemitteilungen/fast-58-500-ki-experten-im-q3-2026-gesucht/) **[F]** |
| Share of software development ads that mention AI | 20.8% (end of November 2025), +37.7% in 2025 | [Indeed, Jobs & Hiring Outlook 2026](https://de.indeed.com/news/releases/arbeitsmarkttrend-2026-ki-verl%C3%A4sst-die-nische-und-ver%C3%A4ndert-den-jobmarkt-fl%C3%A4chendeckend) **[S]** |
| AI Engineer ads that mention coding agents | 12.8% (Feb 2026) → 25.1% (Nov 2026); 22–26% since June | [agentic-engineering-analysis](https://github.com/alexeygrigorev/research-dump/tree/main/courses/ai-engineering-school-germany/agentic-engineering-analysis) **[RD]** |
| What 83 AI engineering ads ask for (26 software companies, US/EU) | agents or tool use 81%, distributed systems/APIs 76%, cost/latency 46%, model training 10%, PhD 4% | [match.dev](https://www.match.dev/post/how-to-hire-ai-engineers/) **[F]** |
| A line about AI coding tools in engineering ads | "one engineering posting in five" | same **[F]** |
| Developers and coding agents | 66% use coding assistants or agents; among coding-agent users, Claude Code 66%, GitHub Copilot 59%; 48% trust AI output "when it is easy to check" | [Stack Overflow Developer Survey 2026, AI](https://survey.stackoverflow.co/2026/ai) **[F/S]** |

Conclusion: yes. AI job ads in Germany almost doubled in a year, and AI requirements show up in normal developer jobs (about a fifth, from three independent sources). An important detail from match.dev: at most companies an "AI engineer" is a strong product developer who shipped an LLM feature to production. Model training appears in only 10% of ads.

### 2.3 Analysis of 58 job ads

Sample (full list with links in the appendix): 32 ads from LinkedIn ("AI Engineer" Berlin, "LLM Engineer" Germany, "Claude Code" Berlin, "AI-native software engineer" Berlin; unrelated results removed) and 26 from arbeitnow (Germany, Berlin first; 11 AI roles and 15 normal developer jobs that name AI coding tools). In total 42 AI roles and 16 normal SWE jobs that ask for AI tools. I counted skills with regular expressions over the full text **[auto]**: this is how often they are mentioned, not "must have".

| Skill | All (n=58) | AI roles (n=42) | SWE + AI tools (n=16) | Track A (Agentic) | Track B (AI Eng) |
|---|---|---|---|---|---|
| Shipping to production, deploy, scale | 86% | 36 | 14 | yes | yes |
| Agents, tool calling, multi-agent | 71% | 31 | 10 | partly (agents as a tool) | **core** |
| LLM APIs (OpenAI, Anthropic, Gemini) | 66% | 31 | 7 | partly | **core** |
| Python | 60% | 32 | 3 | any language | **core** |
| Tests, code review | 55% | 20 | 12 | **core** | yes |
| Docker, Kubernetes, CI/CD | 55% | 21 | 11 | **core** | yes |
| Observability, monitoring, tracing | 53% | 22 | 9 | yes | **core** |
| Evals, LLM testing | 50% | 24 | 5 | partly | **core** |
| SQL, data | 48% | 21 | 7 | yes | yes |
| Cloud (AWS, GCP, Azure) | 47% | 21 | 6 | yes | yes |
| **Coding agents (Claude Code, Cursor, Copilot, Codex)** | 40% | 7 | 16 (by sample design) | **core** | as a work tool |
| Security, guardrails, GDPR, EU AI Act | 38% | 15 | 7 | yes | yes |
| TypeScript / JavaScript | 38% | 12 | 10 | yes | optional |
| RAG, retrieval, vector DB | 34% | 19 | 1 | no | **core** |
| Prompt / context engineering | 34% | 17 | 3 | context engineering | yes |
| Java, Kotlin, Go | 26% | 9 | 6 | yes (legacy) | no |
| LangChain / LangGraph | 26% | 15 | 0 | no | one framework |
| German required | 22% | 10 | 3 | | |
| Fine-tuning, model training | 17% | 10 | 0 | no | overview |
| MCP | 16% | 8 | 1 | yes | yes |
| Classic ML / DL (sklearn, PyTorch) | 10% | 6 | 0 | no | no |
| Other frameworks (CrewAI, PydanticAI, Agents SDK, LlamaIndex) | 9% | 5 | 0 | no | overview |

Other facts about the sample:

- **Level:** senior/staff/lead 35, mid or not stated 21, junior 2. Where experience is stated, it is most often 5+ years. My larger corpus agrees: only 1.5% of ads use a junior word.
- **Language:** 39 ads in English, 19 in German. German is required in 13 (22%), more often in consulting and big companies (Reply, Deloitte, BayernLB, adorsys, Libri).
- **Company types:** startups and scale-ups (Integral, traide AI, bunch, Nelly, Vanilla Steel, Parloa, Qonto, voize), large product companies (Doctolib, Just Eat Takeaway, Redcare, Scalable Capital, AVIV, contentful, ClickHouse, Kayak), consulting (Machine Learning Reply, Deloitte, Bain, aconium, adorsys), corporations and banks (BayernLB, Rohde & Schwarz, ista).

How normal job ads describe work with agents (quotes from public ads):

- vitaservices, AI-Native Software Engineer (Berlin): "Du arbeitest täglich mit agentischen Coding-Werkzeugen wie Claude Code, Cursor oder Codex und orchestrierst mehrere Agenten parallel. Jahreszahlen erwarten wir hier ausdrücklich nicht."
- contentful, Senior Software Engineer: "You will use modern AI tools, including agentic coding workflows, thoughtfully to improve how you explore, build, test, and maintain software."
- Parloa, Staff Product Engineer: "Decide how AI-assisted work is validated before it reaches a customer's production traffic."
- Agent F, Product Design Engineer: "You will use AI coding agents to help implement changes, and take responsibility for reviewing the code and checking the finished experience."
- ClickHouse, Senior Software Engineer (.NET): "Shape the client for agents as users: an API, docs and error messages an AI coding agent can use correctly on the first try."
- Qonto (Go Backend): "Each engineer gets access to Cursor or Copilot, and we want people who use AI to raise the bar, not just to go faster."
- sustaind, Senior DevOps: "Erfahrung mit AI-assisted Coding und die Bereitschaft, solche Tools im Arbeitsalltag gezielt einzusetzen."

The message is the same everywhere: employers do not want "I can prompt". They want **checking and ownership of what the agent produces**: review, tests, validation before production, several agents in parallel. My larger corpus shows the same words next to tool names: workflows and automation 67%, review and validation 48%, productivity 45%, testing 36%, security 35%, specs 31% **[RD]**.

### 2.4 What to teach, based on job ads

- **Track B (AI Engineering) matches the AI job ads almost fully:** LLM APIs, agents and tool calling, RAG, evals, observability, deploy. Fine-tuning (17%) and classic ML (10%) are not core. That is exactly where the long competitor programs start.
- **Track A (Agentic Engineering) matches normal developer jobs:** coding agents plus tests, review, CI/CD, security and work with existing code in TS, Java or Go. This demand is bigger (Softwareentwickler 3,030 at the BA vs 524 AI Engineer), but it is an upgrade of an existing job, not a new job.
- **Shared by both tracks:** production (86%), tests (55%), Docker/CI (55%), observability (53%). A course where the graduate shows a working, tested and deployed project hits the main requirement of both kinds of jobs.

## 3. The supply side

### 3.1 BA catalog (KURSNET / mein NOW): how many voucher courses

Source **[BA]**: the search backend of [mein NOW Weiterbildungssuche](https://mein-now.de/weiterbildungssuche/), filter "Förderart: Bildungsgutschein". The search is full-text and partly fuzzy: "Claude Code" finds 310 voucher courses, but only 63 have "Claude Code" literally in the title or description. So the first table shows **mentions**, not the number of courses on a topic.

| Word in description | All courses | With voucher | With voucher, Berlin region (incl. online with Berlin dates) |
|---|---|---|---|
| KI | 29,268 | 14,559 | 8,147 |
| Künstliche Intelligenz | 16,388 | 7,921 | 4,091 |
| Softwareentwicklung | 12,423 | 5,398 | 2,233 |
| Machine Learning | 7,705 | 3,451 | 2,167 |
| **Prompt Engineering** | 7,537 | **3,071** | 1,652 |
| Webentwicklung | 3,524 | 1,958 | 849 |
| ChatGPT | 4,955 | 1,772 | 1,293 |
| Data Science | 2,494 | 1,621 | 789 |
| Data Analyst | 2,583 | 1,542 | 666 |
| KI-Entwickler | 2,034 | 1,208 | 609 |
| KI-Agenten | 1,953 | 859 | 478 |
| AI Engineer | 1,383 | 703 | 268 |
| LLM | 1,233 | 531 | 363 |
| n8n | 1,548 | 286 | 244 |
| GitHub Copilot | 393 | 222 | 178 |
| Jupyter | 279 | 189 | 144 |
| RAG | 455 | 167 | 88 |
| Agentic | 561 | 127 | 46 |
| Agentische | 144 | 95 | 76 |
| Vibe Coding | 207 | 80 | 12 |
| Coding Agents | 99 | 61 | 31 |
| MCP | 109 | 58 | 32 |
| Agentic Coding | 70 | 41 | 8 |
| LangChain | 146 | 30 | 7 |
| **LangGraph** | 25 | **8** | 0 |
| **Evals** | 9 | **4** | 3 |

For the classification I pulled all voucher courses for 14 queries (Claude Code, Agentic, Agentische, KI-Agenten, GitHub Copilot, Model Context Protocol, Vibe Coding, AI Engineer, LLM, LangChain, RAG, Coding Agents, Agentic Coding, KI-Entwickler). That gave 2,217 unique offers; two queries hit the 600 limit. I put each offer into a category by its title and counted modules from the description **[auto]**:

| Category (by course title) | Courses | Providers | Most common length | Description mentions coding agents |
|---|---|---|---|---|
| AI for managers, office, no-code automation | 924 | 118 | 3–6 months (372), 1–3 months (339) | 50 |
| Other "KI" courses | 525 | 75 | 3–6 months | 7 |
| Software development without AI in the title (web, full-stack, Fachinformatiker) | 331 | 22 | 3–6 months | 3 |
| Data / ML | 200 | 38 | 3–6 months | 1 |
| **AI / KI Engineer, KI-Entwickler** | **136** | **23** | 3–6 months (93) | **2** |
| Vendor certificates (AWS ML Engineer, Azure AI Engineer) | 66 | 56 | 3–6 months | 1 |
| **Development with AI tools / agentic coding** | **35** | **22** | 1–3 months (14), under 1 month (9), 3–6 months (8) | **23** |

Details for our two categories:

- **AI Engineering (136 courses):** 21 courses from 9 providers describe LLM applications (RAG, LangChain/LangGraph, evals or MCP): Turing College ×6, IfaDW ×3, TechPro ×6, MSIT ×2, GFN, Ironhack, alfatraining, Habmann. 25 mention classic ML or DL, 18 prompt engineering, 2 coding agents. A big group are "AI Engineer with Power BI / Fabric / Power Automate / Scrum" bundles, that is the Microsoft stack for users.
- **Agentic coding (35 courses):** 9 are the same course "Softwareentwicklung mit KI-Tools" (Viona/IBB franchise, 4 weeks, needs one programming language and German B2), 6 from future Training & Consulting (Claude Code, Codex, coding assistants), 3 from OneCareer, 3 from HECKER. 10 are long (3+ months), and all of them are either full-stack for beginners with a block about agents (WBS ×2, HECKER ×3, OneCareer, DevKarriere) or courses about **building** agents (Turing "Agentic Engineering", MSIT "Agentic Software Engineer").

**Seats.** KURSNET does not publish seats. Real capacity is better read from training entries: Berlin had 4,038 entries into IT training in the 12 months to July 2026 **[BA, see market sizing]**. Where group sizes are public, they are small: IfaDW up to 12, neue fische about 15, Morphos up to 20 **[RD/S]**. Start frequency: IfaDW and DCI every 5 weeks, StackFuel every 2 weeks, DSI about monthly, GFN AI Engineer three times in 2027 **[F/RD]**. So competitors have enough seats. The gap is not seats. It is the right program.

### 3.2 Providers

Full cards for 24 programs are in [research-dump](https://github.com/alexeygrigorev/research-dump/blob/main/courses/ai-engineering-school-germany/bildungsgutschein/research-notes/germany-azav-programmes.md) **[RD]**. Below is a short summary. "CA" = coding agents / Claude Code, "Ev" = evals, "Ag" = agentic workflows / building agents.

| Provider, course | For whom | Length, format, language | AI content | CA | MCP | Ev | Ag | Source |
|---|---|---|---|---|---|---|---|---|
| **Turing College** (Berlin): AI Engineering; Software & AI Engineering; AI Engineering for Product Engineers; **Agentic Engineering** (new); 17 courses in KURSNET | ≥1 year of Python/JS (AI Eng) | 3 months, 30 h/week, live online, EN or DE | LLM API → RAG (LangChain) → agents (LangGraph) → DeepEval → local models → capstone; "ergänzend Agentic Coding" | partly | no | yes | yes | [RD], [BA] |
| **GFN**: AI Engineer, KI in der Softwareentwicklung | "gute Kenntnisse in einer Programmiersprache", Git, REST | 4 weeks FT, blended online, DE | own agent loop, tool calling, RAG, own MCP server, multi-agent, eval datasets in CI, red-teaming, coding assistants, sub-agents, PR workflow, EU AI Act | yes | yes | yes | yes | [F](https://www.gfn.de/programmierung/softwareentwicklung/ai-engineer-weiterbildung-gefoerdert/) |
| **alfatraining**: Agentische Softwareentwicklung mit Claude Code | a programming language, Git | 2 weeks, live online, DE | CLAUDE.md, multi-file refactoring, MCP, sub-agents, hooks, CI/CD, sandboxing, audit | **yes** | yes | no | yes | [BA], [RD] |
| alfatraining: AI Engineer | Python + SQL | 16 weeks, DE | Data Eng → ML → DL → Reinforcement Learning | no | no | no | no | [RD] |
| **Viona / IBB** (franchise at 9 providers): Softwareentwicklung mit KI-Tools | one language, German B2 | 4 weeks, virtual live, DE | AI-assisted coding, no specific tool | yes | no | no | no | [RD], [BA] |
| future Training & Consulting: Claude Code / Codex / coding assistants (6 courses) | developers | up to 1 month and 1–3 months, DE | planning, generating and checking code with agents, MCP | yes | yes | no | yes | [BA] |
| **MSIT / Masterschool**: Agentic Software Engineer; GenAI Engineering; AI Systems Backend Engineering | from zero (Python, Git, SQL, Flask first) | 6–12 months, online, EN | agents, tool calling, MCP servers, multi-agent, evals; "Coding-Agenten wie Cursor oder Claude Code" | yes | yes | yes | yes | [BA], [RD] |
| **Digitale Leute School**: AI Software Engineering | "Einsteiger, Quereinsteiger und erfahrene Entwickler" | 3 months (12 weeks), remote, **EN** | product skills, AI-assisted engineering, agentic AI, MCP, LangChain; Claude Code, Cursor, Copilot | yes | yes | no | yes | [BA], [RD] |
| WBS Coding School: AI Software Development | beginners, B2 | 17 weeks, live online, EN or DE | MERN + TS, 1 week GenAI, 1 week "Agentic AI & Developer Workflows" | block | no | no | block | [RD] |
| WBS Training: Software Development & AI (English) | beginners | 3–6 months, EN | full-stack + a block "AI-assisted Coding mit GitHub Copilot und Claude Code", MCP | block | yes | no | block | [BA] |
| WBS Training: AI Engineer, Effizient arbeiten mit Power KI-Tools | no programming | 71 days, DE | Python basics, prompt engineering, agents, n8n | no | no | no | n8n | [RD] |
| HECKER Consulting: (Advanced / Full-Stack) Software Development mit KI | mixed level | 3–6 months, online, DE | TS, NestJS, Next.js, Docker → "Agentische Softwareentwicklung: Claude Code, Skills, MCP" | block | yes | no | block | [BA] |
| neue fische / Spiced: Agentic AI, Build and Deploy AI Agents | strong Python, Git, LLM API, entry test | 8 weeks FT, EN | building agents only, 3-week capstone | no | n/a | yes | yes | [RD] |
| neue fische / Spiced: Agentic Machine Learning Engineer | Python, SQL, statistics | 14 weeks, EN | ML → DL → LLM/RAG → agents → evals | no | n/a | yes | yes | [RD] |
| neue fische / Spiced: AI Engineering (DS + MLE) | programming | 32 weeks, EN/DE | DS → ML → DL → GenAI → MLOps → LLMOps | no | no | n/a | partly | [RD] |
| neue fische: Software Development with AI / Advanced | beginners / HTML-CSS-JS | 16 weeks, DE/EN | web dev + a block "Agentic Coding (Claude Code)" | block | no | no | block | [RD] |
| **Le Wagon** Berlin: AI Software Development | "No prerequisites" | 9 weeks FT, 400 h, campus or online | Ruby/Rails, SQL, "AI integration with LLMs", "AI-assisted coding" (about 8 h) | 8 h | no | no | no | [F](https://www.lewagon.com/berlin/web-development-course) |
| Ironhack: Remote AI Engineering | no experience, 40 h prework | 9 weeks FT or 24 weeks PT, EN | Python → ML, DL, **fine-tuning** → GenAI, LLM, agents (LangChain) | no | no | yes | yes | [RD], [BA] |
| **IfaDW**: AI Engineer / KI-Entwickler / KI-Anwendungsentwickler | basic math and IT | 30 / 25 / 15 weeks, live online, up to 12 people | Python DA → ML → DL → NLP & GenAI (NLTK, spaCy, Word2Vec, BERT … RAG) → Big Data → MLOps | no | no | no | 1 item | [RD] |
| **DCI** (the /ai-engineer/ page now says "Data Engineering with Python") | "No coding experience necessary" | 12 months + 3-month internship, online, EN/DE B1 | AI code assistants, GitHub Copilot from module 1 | Copilot | no | no | no | [F](https://digitalcareerinstitute.org/en/courses/ai-engineer/) |
| **StackFuel** (Multiverse): KI-Fachkraft + KI-Workflow & Automatisierung | "Anfänger:innen" | 1–2 months FT, DE, starts every 2 weeks | prompting, CustomGPT, n8n agents with RAG | no | no | no | n8n | [F](https://stackfuel.com/de/weiterbildung/ki-weiterbildung/) |
| **Morphos / ADZ**: KI-Ingenieur | job seekers in general | 6 months, mornings, online, up to 20, DE | Python, FastAPI/Docker/CI, Anthropic/OpenAI/Azure/Bedrock, RAG, LangGraph, MCP, RAGAS/DeepEval, "mit Claude Code als Coding-Agent", QLoRA | yes | yes | yes | yes | [S](https://adz-weiterbildung.de/weiterbildungen/weiterbildung-ki-ingenieur/) |
| **Data Science Institute** (Berlin) | "auch ohne Vorerfahrung" | 6 months FT, DE, online | VS Code, SQL, dbt, Copilot, scikit-learn, Keras, n8n, AWS; they report a 90.6% placement rate | Copilot | no | no | n8n | [F](https://data-science-institute.de/) |
| **Developer Akademie**: KI Softwareentwickler; KI Automation; **KI Agentic Engineering** | "keine Vorkenntnisse" | 3–9 months, 10–40 h/week, distance learning with mentors, DE | HTML, CSS, JS, Angular, "KI-Tools wie ChatGPT & Co."; the Agentic Engineering syllabus is not on the page | n/a | n/a | n/a | n/a | [F](https://developerakademie.com/bildungsgutschein/) |
| CareerFoundry | — | — | closed on 28 February 2026 (insolvency) | — | — | — | — | [S] |
| TechStarter | — | — | AZAV, has AI courses; the program page did not load | n/a | n/a | n/a | n/a | [S] |
| appliedAI Institute | companies | workshop | "Practical Introduction to Agentic AI", corporate; no voucher version found | n/a | n/a | n/a | yes | [S] |

### 3.3 Test of the hypothesis "bootcamps do not have modern programs"

**For the hypothesis:**

1. **Most "KI" supply is prompting for users.** "Prompt Engineering" appears in 3,071 voucher courses, "LangGraph" in 8, "Evals" in 4 **[BA]**. 924 of 2,217 AI courses target managers, office work and no-code automation.
2. **Long "AI Engineer" programs start with classic ML.** IfaDW AI Engineer, 30 weeks: "(1) Datenanalyse mit Python … (2) Angewandtes Maschinelles Lernen … (3) Deep Learning … (4) NLP & Generative AI (NLTK, spaCy, TF-IDF, Word2Vec, BERT …) … (5) Big Data Engineering … (6) MLOps". LLM applications get 5 of 30 weeks **[RD]**. alfatraining AI Engineer: "Data Eng → ML → DL → Reinforcement Learning" **[RD]**. Ironhack: "Machine Learning, Deep Learning and Model Fine-Tuning", then "Generative AI, LLMs and Agents (… with LangChain)" **[RD]**. In job ads, model training appears in 17% (match.dev: 10%), classic ML in 10%.
3. **Long programs "for developers" are really for beginners.** Le Wagon: "No technical experience or prior programming knowledge is required"; Ruby/Rails, AI-assisted coding about 8 of 400 hours **[F/RD]**. DCI: "No coding experience necessary" **[F]**. Developer Akademie: "Du brauchst kein Studium und keine Vorkenntnisse" **[F]**. DSI: "auch ohne Vorerfahrung" **[F]**. WBS Coding School: beginners **[RD]**. But only 2 of 58 job ads are junior.
4. **Coding agents are almost missing in AI Engineer courses:** 2 of 136 **[auto]**. In AI Engineer job ads they appear in 17% of my sample and 25.1% of my larger corpus.
5. **Some drop "AI" from the name:** the DCI page `/courses/ai-engineer/` now leads to "Data Engineering with Python" **[F]**.

**Against the hypothesis (we must be honest about this in positioning):**

1. **GFN, 4 weeks, German, for developers:** "Entwicklung einer eigenen Agenten-Loop", "Entwicklung eines eigenen MCP-Servers", "Aufbau und Pflege von Eval-Datensätzen", "Automatische Qualitätsprüfung in CI-Pipelines", "Änderungen anhand von Diffs und Reviews prüfen", "Sub-Agenten für Recherche, Entwicklung und Qualitätssicherung nutzen" **[F]**. This is almost exactly what job ads ask for.
2. **alfatraining Claude Code, 2 weeks:** "CLAUDE.md und Projektkonventionen, Mehrdateien-Refactoring … MCP-Server, Sub-Agenten, Hooks … Integration in CI/CD-Pipelines … Sandboxing, Audit von Agenten-Aktionen" **[BA]**.
3. **Turing College:** the full LLM stack (LangGraph, DeepEval, RAG, local models) plus a separate "Agentic Engineering" course in KURSNET **[BA]**. A Berlin company, in English, for developers with experience, 3 months, fully funded with a voucher. The main direct competitor for track B.
4. **Morphos KI-Ingenieur:** "RAG-Systeme … LangGraph und eigene MCP-Server … RAGAS und DeepEval – entwickelt mit Claude Code als Coding-Agent" **[S]**.
5. Courses update fast: "Claude Code" appears 63 times in voucher course descriptions; HECKER dates its description "2026-10-19" **[BA]**.

**Verdict:** "bootcamps are outdated" in general is wrong, and a Vermittler or a competitor can easily disprove it with GFN or Turing. The narrow claim is right: **modern programs are short (2 to 4 weeks, German) or teach how to build agents; long programs are for beginners or start with 2019-era ML. The catalog has no long, live, English program for experienced developers where the main thing is shipping software with coding agents and checking the result.**

### 3.4 Courses outside the voucher system (upper reference)

| Course | Format | What it covers | Source |
|---|---|---|---|
| My AI Engineering Buildcamp on Maven | self-paced (and past cohorts), about 6 weeks | RAG → agents (PydanticAI, Agents SDK, MCP) → tests and evals (LLM as judge) → monitoring (Grafana, Logfire, OpenTelemetry) → coding agent and code reviewer → capstone | [F](https://maven.com/alexey-grigorev/from-rag-to-agents) |
| Hamel Husain & Shreya Shankar: AI Evals for Engineers & PMs, Maven | live cohort | evals only | [S](https://maven.com/parlance-labs/evals) |
| DeepLearning.AI × Anthropic: Claude Code, A Highly Agentic Coding Assistant | short course, about 2 h, free | CLAUDE.md, MCP, tests and refactoring, git worktrees | [S](https://www.deeplearning.ai/courses/claude-code-a-highly-agentic-coding-assistant) |
| Udacity: Agentic AI Nanodegree | self-paced | building agents | [S](https://onlinecourseing.com/udacity-agentic-ai-nanodegree-review/) |
| DataTalksClub: AI Dev Tools Zoomcamp ("AI-Native Software Engineering") | free cohort since 31 August 2026 | "Give AI tools the right context, … review what they produce, test the result, and ship software with guardrails" | [F](https://github.com/DataTalksClub/ai-dev-tools-zoomcamp) |

Conclusion: there are enough cheap and free short courses on tools. Expert live cohorts run 4 to 6 weeks in the evenings. None of them is a full-time program paid by the Agentur.

### 3.5 Evidence about us (checked 14 November 2026)

- GitHub stars: Data Engineering Zoomcamp 46,875; MLOps Zoomcamp 15,555; ML Zoomcamp 14,959; LLM Zoomcamp 7,660; AI Engineering Field Guide 6,031; AI Dev Tools Zoomcamp 1,752 **[F]**.
- My Maven page: "Teaching AI and Data to 100k+ students", "15 years of experience" **[F]**.
- **AI Dev Tools Zoomcamp already follows the track A program:** "build and deploy a full-stack application, operate it with observability and an agent-assisted incident response, and extend coding agents with MCP". It also says: "not a prompt-engineering-only course, and it is not a course about training models". This is the strongest evidence for "our program fits today's market".
- **What we do not have:** a verified number of certified graduates and a placement rate. For a Vermittler this matters more than stars, because only 35.6% are employed 6 months after an IT course in Berlin **[BA]**. Competitors publish their own numbers (DSI "90.6% Vermittlungsquote", GFN "95% Integrationsquote"). We should at least survey Zoomcamp graduates.

## 4. Conclusions

### 4.1 How crowded each category is

| Category | Voucher supply | Demand (job ads) | Crowding |
|---|---|---|---|
| Web dev for beginners | very large (Webentwicklung 1,958 mentions; Le Wagon, DCI, WBS, Developer Akademie, neue fische) | few junior jobs (2 of 58) | **oversupplied** |
| Data science / analytics | large (1,621 / 1,542 mentions; StackFuel, DSI, IfaDW) | stable, not growing like AI | saturated |
| General "KI" courses (prompting, Copilot for office, n8n) | huge (924 of 2,217; 3,071 prompt engineering mentions) | 58,500 AI jobs in all industries, but not a developer job | **oversupplied** |
| AI engineering for developers | 136 courses from 23 providers; about 21 modern ones (RAG, evals, LangGraph) from 9 providers; Turing has 6 versions | "AI Engineer" 88 at the BA Berlin, 314 on StepStone Berlin, growing | **crowded in its segment**: strong direct competitors, fully funded with a voucher |
| Agentic engineering for experienced developers | 35 courses, but short German modules of 2–4 weeks or a block inside a beginner course; no long English program for experienced people | 14.6–18.2% of all developer jobs (arbeitnow), about 20% per match.dev and Indeed; base of 3,030 Softwareentwickler at the BA | **the niche is free in the "3–4 months, English, live, experienced only" format** |

### 4.2 The gap: is agentic engineering for experienced people really empty?

No, but our format is free. In detail:

- **Short modules with the right content exist.** GFN (4 weeks), alfatraining (2 weeks), the Viona/IBB franchise (4 weeks), future Training. All in German. A Vermittler may prefer them because they are shorter and cheaper. This is the main risk for track A: "why 3 months if there are 4 weeks?"
- **"Agentic" appears in titles, but means something else.** Turing "Agentic Engineering", MSIT "Agentic Software Engineer" and Spiced "Agentic AI" teach how to build agents with LangGraph and CrewAI. That is our track B, not A. Still, they take the word "Agentic" in the catalog and in the minds of Vermittler.
- **Closest direct competitor for track A:** Digitale Leute "AI Software Engineering" (English, 3 months, Claude Code, Cursor, Copilot, MCP, product skills). But it accepts beginners, and 5 of 24 sessions go to product skills **[RD]**.
- **What nobody has:** 3 to 4 months full-time live in English, only for experienced developers, where each week ships working code with agents, and checking (tests, diff review, CI, security, observability) is the main part. Plus an instructor with a public track record of courses.

To defend the length against 4-week modules, we need an argument for the Vermittler: 4 weeks teach a tool, 3 months give a portfolio of shipped projects, work with legacy code and a team workflow. That is what job ads ask for ("validate before it reaches production", "orchestrierst mehrere Agenten parallel").

### 4.3 Which track has the better balance of demand and supply

| | Track A, Agentic Engineering | Track B, AI Engineering |
|---|---|---|
| Demand | wide, inside normal developer jobs (BA: Softwareentwickler 3,030, Software Engineer 1,284; 15–20% ask for AI tools) | narrow, but with a clear title (AI Engineer 524 at the BA, 88 in Berlin; StepStone Berlin 314) |
| Supply | short German modules; no long English course for experienced people | Turing (×6, English, Berlin, fully funded), IfaDW, MSIT, Morphos, GFN, Ironhack, neue fische |
| Clear for a Vermittler | less: "you are already a developer, why 3 months?" | more: a new target job "AI Engineer" |
| Difference from competitors | clear: format, level, language, our own course as the basis | weaker: Turing has almost the same topics (LangGraph, DeepEval, RAG) |
| **Result** | **better balance of demand and supply** | easier to "sell" to the Agentur, but crowded |

Recommendation **[estimate; the ad test and session signups decide]**: track A is the main track. If we do B, we should differ from Turing by level, not by topics: production, evals in CI, cost and latency, coding agents as a work tool. One option covers both arguments: a single "AI-native software engineer" program, about two thirds work with agents and about one third building LLM features into a product. Both parts show up in job ads: SWE jobs with AI tools, and 44% of them also ask for LLM APIs.

### 4.4 Positioning

**Wording (draft):** "Most courses you can take for free with a Bildungsgutschein either teach beginners from zero or start with 2019-era machine learning. Modern modules exist, but they last two to four weeks and are in German. We teach experienced developers what Berlin companies ask for now: ship a product with coding agents and own the result. Tests, review, CI and production. The program builds on courses that tens of thousands of people already took."

Short, for a landing page: "Built for developers who already ship. Today's job posts ask you to work with coding agents and own what they produce. Most funded courses start from zero or from 2019-era ML."

**Evidence:**

- 14.6% of developer jobs in Germany and 18.2% in Berlin name AI coding tools (arbeitnow, week to 14 November 2026); "one engineering posting in five" (match.dev).
- 3,071 voucher courses mention prompt engineering, 8 mention LangGraph, 4 mention evals (KURSNET).
- In 136 voucher "AI Engineer" courses, 2 mention coding agents, and long programs start with ML and DL (IfaDW, alfatraining, Ironhack).
- 2 of 58 jobs are junior; beginner courses (Le Wagon, DCI, Developer Akademie, DSI) prepare people for a market that almost does not exist.
- Ours: AI Dev Tools Zoomcamp (AI-Native Software Engineering), LLM Zoomcamp 7.7k stars, ML Zoomcamp 15.0k, AI Engineering Buildcamp on Maven.

**Counterpoints to prepare for:**

- GFN and alfatraining already teach Claude Code, MCP, sub-agents and evals in CI. Answer: that is 2 to 4 weeks and German; we offer 3 to 4 months, a portfolio, English.
- Turing College: a modern LLM stack, Berlin, English, fully funded. For track B we can differ only by level and production. For track A, Turing is not a competitor.
- Our graduate count and placement are not public, while competitors publish numbers (DSI 90.6%, GFN 95%). We need a Zoomcamp graduate survey.
- "Don't trust AI code" as a market mood: in Stack Overflow 2026 only 6.6% trust AI with important decisions. This is more an argument **for** the program: it teaches checking.

## 5. First program sketch (by frequency in job ads)

Weight = share of sample ads (n=58, or a subsample) that mention the skill **[auto]**. The order of modules follows learning logic, not only weight. 12 modules per track for 12 to 16 weeks full-time.

### Track A: Agentic Engineering (for experienced developers)

Based on: the 16 SWE jobs with AI tools and the employer quotes in 2.3. Also: my larger corpus (workflows 67%, review 48%, testing 36%, security 35%, specs 31%).

| # | Module | Weight and source |
|---|---|---|
| 1 | Workplace with a coding agent: Claude Code, Cursor, Codex, Copilot, project context (CLAUDE.md, AGENTS.md), cost | coding agents 16/16 SWE (by design), 40% of all |
| 2 | From task to plan: spec, breaking work into tasks, issues and PRs as the interface to the agent | specs 31%; "validate before production" (Parloa) |
| 3 | Tests as a contract for the agent: TDD, test automation, regression | tests and review 12/16 (75%), 55% of all |
| 4 | Reviewing agent code: reading diffs, quality gates, linters, when to rewrite by hand | review 48%; Agent F, contentful |
| 5 | Working with existing code: legacy, refactoring, migrations in TS, Java, Go, PHP | TS/JS 10/16, Java/Go 6/16 |
| 6 | CI/CD, Docker and deploy with agents | Docker/CI 11/16 (69%), production 14/16 |
| 7 | Security: agent permissions, sandboxing, secrets, supply chain, prompt injection | 7/16 (44%), 38% of all |
| 8 | Extending agents: MCP, skills, sub-agents, hooks | MCP 16% of all; core at GFN and alfatraining |
| 9 | Parallel agents: git worktrees, orchestration, task queue | vitaservices "mehrere Agenten parallel" |
| 10 | Operations: observability, incidents with an agent's help, runbooks | observability 9/16 (56%) |
| 11 | An LLM feature in the product (bridge to track B): LLM API, structured output, a simple agent | LLM API 7/16 (44%), agents 10/16 |
| 12 | Team capstone: a product from spec to production, measuring speed, quality and cost | production 86%; a portfolio for the Vermittler |

### Track B: AI Engineering (LLM applications)

Based on: the 42 AI roles in the sample, plus match.dev (agents 81%, cost/latency 46%, training 10%).

| # | Module | Weight and source |
|---|---|---|
| 1 | LLM APIs for production: OpenAI, Anthropic, Gemini, structured output, cost and latency | LLM API 31/42 (74%); cost/latency 46% (match.dev) |
| 2 | Python backend for AI: FastAPI, async, typing; TS as an option | Python 32/42 (76%), TS 12/42 |
| 3 | Search and RAG: chunking, hybrid search, vector DB, Postgres | RAG 19/42 (45%), SQL 21/42 |
| 4 | Agents and tool calling: your own loop, then one framework (PydanticAI or LangGraph) | agents 31/42 (74%); LangChain/LangGraph 15/42 (36%) |
| 5 | MCP and integrations with internal systems | MCP 8/42 (19%) |
| 6 | Evals: test sets, LLM as judge, regression in CI | evals 24/42 (57%) |
| 7 | Observability and monitoring: tracing, cost, feedback | 22/42 (52%) |
| 8 | Deploy: Docker, CI/CD, cloud (AWS, GCP, Azure) | Docker/CI 21/42 (50%), cloud 21/42 (50%), production 36/42 |
| 9 | Security and compliance: guardrails, prompt injection, GDPR, EU AI Act | 15/42 (36%) |
| 10 | Context and prompt engineering as engineering, not as a course | 17/42 (40%) |
| 11 | Coding agents as the AI engineer's work tool | 7/42 (17%); 25.1% in my larger corpus |
| 12 | Capstone: an LLM product in production with evals and monitoring; fine-tuning and local models as an overview | fine-tuning 10/42 (24%) overview only; classic ML 6/42 out of scope |

What **not** to do in either program, based on job ads: start with classic ML and DL (10%), teach prompt engineering as a separate course, teach full-stack from zero.

## 6. Limits

- Job counts are from one date. LinkedIn and StepStone blur queries, and LinkedIn stops at about 300 results. Indeed and GermanTechJobs blocked requests.
- The 58 ads are not a random sample: the first LinkedIn pages for 4 queries and the newest arbeitnow ads in Germany with Berlin first. Skills were counted with regular expressions: "agents" and "evaluation" can catch other meanings. Ratios are more reliable than exact percentages.
- KURSNET: the search is full-text and fuzzy, the list description can be cut, so module flags are a lower bound. The classification by title is automatic. The catalog does not publish seats.
- Some provider programs come from research-dump (12 November 2026) or from snippets (**[RD]**, **[S]**). Open the page again before quoting it in marketing.
- Competitor placement rates (DSI 90.6%, GFN 95%) are their own claims.

## 7. Next steps

1. Before the final track choice, open and save the full programs of direct competitors: Turing "Agentic Engineering" and "Software & AI Engineering", Digitale Leute "AI Software Engineering", GFN AI Engineer, MSIT Agentic Software Engineer.
2. Run a Zoomcamp graduate survey (where they work, what changed) to get our own number for the Vermittler.
3. On the landing page and in the sessions, use the evidence from 4.4 and do not write "all bootcamps are outdated".
4. Repeat this KURSNET scan once a month: courses on Claude Code grow fast.

## Appendix: the 58 job ads

Skills were tagged automatically from the full ad text (Py, TS/JS, JVM/Go, LLM API, RAG, Agents, Evals, Obs = observability, MCP, LangChain, FT = fine-tuning, ML/DL, Cloud, Docker/CI, CodingAgents, Prompt, Tests, Sec, DE req = German required, SQL). 

| # | Source | Type | Job | Company | City | Language | Level | Skills (automatic) |
|---|---|---|---|---|---|---|---|---|
| 1 | LinkedIn | AI role | [Junior AI Engineer (w/m/d)](https://www.linkedin.com/jobs/view/4450169234/) | FLEX Capital | Berlin | DE | junior | Py, LLM API, RAG, Agents, LangChain, FT, ML/DL, Cloud, DE req, SQL |
| 2 | LinkedIn | AI role | [Senior ML Engineer - NLP (m/f/d)](https://www.linkedin.com/jobs/view/4488164064/) | voize | Berlin | EN | senior+ | Py, JVM/Go, LLM API, Agents, Evals, Prod, Prompt, Tests |
| 3 | LinkedIn | AI role | [Join the team! – Senior AI Developer (m/f/d)](https://www.linkedin.com/jobs/view/4459768458/) | Incari Development Platform | Berlin | EN | senior+ | Py, ML/DL, Cloud, Prod, Tests, SQL |
| 4 | LinkedIn | AI role | [Senior AI Engineer (f/m/d)](https://www.linkedin.com/jobs/view/4447019119/) | Integral | Berlin | EN | senior+ | Py, LLM API, Agents, LangChain, Prod, CodingAgents, Prompt, Tests |
| 5 | LinkedIn | AI role | [Staff ML Engineer - Trust & Safety](https://www.linkedin.com/jobs/view/4484013259/) | AVIV Group | Berlin | EN | senior+ | LLM API, Agents, Evals, Obs, Prod, Sec, SQL |
| 6 | LinkedIn | AI role | [Senior ML Engineer - NLP (m/f/d)](https://www.linkedin.com/jobs/view/4488431097/) | voize-l | Berlin | EN | senior+ | Py, JVM/Go, LLM API, Agents, Evals, Prod, Prompt, Tests |
| 7 | LinkedIn | AI role | [Machine Learning Engineer](https://www.linkedin.com/jobs/view/4474453425/) | super.AI | Berlin | EN | mid / not stated | Py, LLM API, FT, Cloud, Docker/CI, Prod, Prompt, Tests |
| 8 | LinkedIn | AI role | [AI Engineer (m/w/d)](https://www.linkedin.com/jobs/view/4462232645/) | aconium GmbH | Berlin | DE | mid / not stated | Py, LLM API, RAG, Agents, MCP, ML/DL, Prod |
| 9 | LinkedIn | AI role | [AI Engineer (x/f/m)](https://www.linkedin.com/jobs/view/4490391558/) | Doctolib | Berlin | EN | mid / not stated | Py, TS/JS, JVM/Go, LLM API, RAG, Agents, Evals, Obs, Docker/CI, Prod, Tests, Sec |
| 10 | LinkedIn | AI role | [Senior Machine Learning Engineer](https://www.linkedin.com/jobs/view/4474856880/) | Just Eat Takeaway.com | Berlin | EN | senior+ | Py, Evals, Cloud, Docker/CI, Prod, SQL |
| 11 | LinkedIn | AI role | [Professional AI Engineer - GenAI & AI Agents (m/w/d)](https://www.linkedin.com/jobs/view/4488809531/) | BayernLB | Munich | DE | mid / not stated | Py, LLM API, RAG, Agents, Evals, LangChain, Docker/CI, Tests, SQL |
| 12 | LinkedIn | AI role | [Senior AI Engineer (m/w/d)](https://www.linkedin.com/jobs/view/4457258066/) | adorsys | Nuremberg | DE | senior+ | Py, LLM API, RAG, Agents, Evals, Obs, MCP, LangChain, other fw, FT, Cloud, Docker/CI, Prod, Prompt, Sec, DE req, SQL |
| 13 | LinkedIn | AI role | [(Senior) AI/LLM Engineer](https://www.linkedin.com/jobs/view/4398249472/) | Mercura | Munich | EN | senior+ | Py, TS/JS, LLM API, RAG, Agents, Evals, Obs, Prod, SQL |
| 14 | LinkedIn | AI role | [GenAI Engineer (m/w/d)](https://www.linkedin.com/jobs/view/4471435376/) | Machine Learning Reply GmbH | Berlin | DE | mid / not stated | Py, LLM API, RAG, Agents, LangChain, FT, Cloud, Prod, Prompt, SQL |
| 15 | LinkedIn | AI role | [Senior GenAI Engineer](https://www.linkedin.com/jobs/view/4481864898/) | Abacus Medicine Group | Berlin | EN | senior+ | Py, LLM API, RAG, Agents, Evals, LangChain, FT, Cloud, Docker/CI, Prod, Prompt |
| 16 | LinkedIn | AI role | [Lead, AI Engineering (m/f/d)](https://www.linkedin.com/jobs/view/4475887243/) | Bain & Company | Berlin | EN | senior+ | TS/JS, LLM API, RAG, Agents, Evals, Obs, FT, Docker/CI, Prod, Prompt, Tests, Sec |
| 17 | LinkedIn | AI role | [AI / ML Engineer - Agentic AI ( m/w/d)](https://www.linkedin.com/jobs/view/4478472349/) | Rohde & Schwarz | Dresden | DE | mid / not stated | Py, LLM API, RAG, Agents, Evals, Obs, MCP, LangChain, Prompt, Tests, Sec, DE req |
| 18 | LinkedIn | AI role | [Senior AI Engineer (m/w/d)](https://www.linkedin.com/jobs/view/4434523202/) | Libri GmbH | Hamburg | DE | senior+ | Py, TS/JS, LLM API, Agents, Evals, LangChain, Cloud, Docker/CI, CodingAgents, Prompt, DE req |
| 19 | LinkedIn | AI role | [GenAI Engineer (m/w/d)](https://www.linkedin.com/jobs/view/4471438198/) | Machine Learning Reply GmbH | Munich | DE | mid / not stated | Py, LLM API, RAG, Agents, LangChain, FT, Cloud, Prod, Prompt, SQL |
| 20 | LinkedIn | AI role | [Senior AI Engineer (all genders)](https://www.linkedin.com/jobs/view/4483018225/) | GeneralMind | Berlin | EN | senior+ | Py, LLM API, RAG, Agents, Evals, Obs, FT, Prod, Prompt, Sec |
| 21 | LinkedIn | SWE + AI tools | [Business Automation Developer (all genders)](https://www.linkedin.com/jobs/view/4490723055/) | flaconi | Berlin | EN | mid / not stated | TS/JS, JVM/Go, LLM API, Agents, Docker/CI, Prod, CodingAgents |
| 22 | LinkedIn | AI role | [Junior AI Application Engineer – AI Products (LLM & RAG) (m/f/d)](https://www.linkedin.com/jobs/view/4483127366/) | Machine Learning Reply GmbH | Berlin | DE | junior | Py, LLM API, RAG, Agents, Evals, Obs, LangChain, other fw, Cloud, Docker/CI, Prod, CodingAgents, DE req |
| 23 | LinkedIn | AI role | [Consultant AI Engineering (m/w/d)](https://www.linkedin.com/jobs/view/4454388224/) | Deloitte | Berlin | DE | mid / not stated | Py, LLM API, Evals, LangChain, other fw, Cloud, Tests |
| 24 | LinkedIn | AI role | [Senior AI Engineer (m/f/d) in B2B SaaS AI Startup](https://www.linkedin.com/jobs/view/4432789499/) | traide AI | Berlin | EN | senior+ | Py, TS/JS, LLM API, Agents, Obs, ML/DL, Docker/CI, Prod, Sec |
| 25 | LinkedIn | AI role | [AI Software Engineer – Python (m/f/x)](https://www.linkedin.com/jobs/view/4482981150/) | Scalable Capital | Berlin | EN | mid / not stated | Py, LLM API, Agents, Obs, LangChain, FT, Cloud, Docker/CI, Prod, Tests |
| 26 | LinkedIn | AI role | [ML Engineer, Backend](https://www.linkedin.com/jobs/view/4486686483/) | FDE Times | Berlin | EN | mid / not stated | Py, LLM API, Obs, ML/DL, Cloud, Docker/CI, Prod, Tests, Sec, SQL |
| 27 | LinkedIn | AI role | [Senior AI Engineer](https://www.linkedin.com/jobs/view/4381773796/) | Nelly Solutions | Berlin | EN | senior+ | Py, TS/JS, LLM API, RAG, Agents, Evals, Obs, MCP, Cloud, Prod, DE req, SQL |
| 28 | LinkedIn | AI role | [Senior Applied AI Engineer, AI Platform (f/m/d)](https://www.linkedin.com/jobs/view/4468227474/) | bunch | Berlin | EN | senior+ | Py, TS/JS, LLM API, RAG, Agents, Evals, Obs, MCP, LangChain, Cloud, Docker/CI, Prod, Prompt, Tests, Sec, SQL |
| 29 | LinkedIn | AI role | [Senior Software Engineer AI (m/w/d)](https://www.linkedin.com/jobs/view/4487435857/) | ista | Berlin | DE | senior+ | JVM/Go, RAG, Agents, Evals, Obs, MCP, Docker/CI, Prod, CodingAgents, Tests |
| 30 | LinkedIn | AI role | [Senior Software Engineer – AI-Driven Platform & Agentic Systems (m/w/d](https://www.linkedin.com/jobs/view/4433988450/) | virtualQ | Berlin | EN | senior+ | Py, TS/JS, LLM API, Agents, Obs, LangChain, other fw, Cloud, Docker/CI, Prod, Prompt, Tests, Sec, SQL |
| 31 | LinkedIn | AI role | [Senior AI Engineer](https://www.linkedin.com/jobs/view/4486820989/) | Vanilla Steel | Berlin | EN | senior+ | Py, TS/JS, LLM API, RAG, Agents, Evals, Obs, MCP, LangChain, other fw, Cloud, Docker/CI, Prod, Prompt, Tests, SQL |
| 32 | LinkedIn | AI role | [Senior AI Engineer](https://www.linkedin.com/jobs/view/4483486028/) | Redcare Pharmacy | Berlin | EN | senior+ | Evals, Obs, Prod, Sec |
| 33 | arbeitnow | AI role | [Industrial Data & Solutions Engineer (gn) @ Stealth AI Venture, Berlin](https://www.arbeitnow.com/jobs/companies/atlanticvc/industrial-data-solutions-engineer-gn-at-stealth-ai-venture-berlin-337847) | atlantic.vc | Berlin | EN | mid / not stated | Py, JVM/Go, Prod, DE req, SQL |
| 34 | arbeitnow | AI role | [AI-Native Software Engineer (m/w/d)](https://www.arbeitnow.com/jobs/companies/vitaservices-gmbh-co-kg/ai-native-software-engineer-berlin-186419) | vitaservices GmbH & Co. KG | Berlin | DE | mid / not stated | JVM/Go, Agents, Docker/CI, CodingAgents, Prompt, Tests, Sec, DE req, SQL |
| 35 | arbeitnow | AI role | [Engineering Manager, ChatBots and AI](https://www.arbeitnow.com/jobs/companies/workato/engineering-manager-chatbots-and-ai-berlin-frankfurt-munich-367917) | workato | Berlin; Frankfurt; | EN | mid / not stated | JVM/Go, LLM API, Agents, Cloud, Docker/CI, Prod, SQL |
| 36 | arbeitnow | AI role | [Staff Robotics Engineer – Physical AI (m/f/d)](https://www.arbeitnow.com/jobs/companies/almetra/staff-robotics-engineer-physical-ai-berlin-285099) | Almetra | Onsite Berlin | EN | senior+ | Py, ML/DL, Prod, Tests |
| 37 | arbeitnow | AI role | [AI Platform Engineer - Edgy device (m/f/d)](https://www.arbeitnow.com/jobs/companies/almetra/ai-platform-engineer-edgy-device-berlin-188549) | Almetra | Onsite Berlin | EN | mid / not stated | Obs, Cloud, Docker/CI, Prod |
| 38 | arbeitnow | AI role | [Senior Fullstack Engineer (m/f/d) - AI Health tech](https://www.arbeitnow.com/jobs/companies/voize/senior-fullstack-engineer-ai-health-tech-berlin-114252) | Voize | Berlin | EN | senior+ | TS/JS, JVM/Go, Evals, Obs, FT, Docker/CI, Prod, Sec, SQL |
| 39 | arbeitnow | AI role | [AI Product Engineer](https://www.arbeitnow.com/jobs/companies/paddy/ai-product-engineer-bielefeld-8892) | paddy | Berlin | DE | mid / not stated | TS/JS, LLM API, RAG, Agents, Evals, Obs, Cloud, Prod, CodingAgents, Prompt, Tests, Sec, DE req, SQL |
| 40 | arbeitnow | AI role | [Software Engineer (gn) @ Industrial AI Venture, Berlin](https://www.arbeitnow.com/jobs/companies/atlanticvc/software-engineer-gn-at-industrial-ai-venture-berlin-169930) | atlantic.vc | Berlin | EN | mid / not stated | Py, LLM API, RAG, Agents, Evals, Obs, Prod, CodingAgents, Tests, Sec, SQL |
| 41 | arbeitnow | AI role | [Founding engineer, AI on CAD geometry (co-founder equity)](https://www.arbeitnow.com/jobs/companies/loopforgelab/founding-engineer-ai-on-cad-geometry-co-founder-equity-berlin-273915) | LoopForgeLab | Berlin | EN | mid / not stated | Py, LLM API, Agents, Evals, MCP, Prod |
| 42 | arbeitnow | AI role | [SAP SD Developer (ABAP) – AI Integration (f/m/d)](https://www.arbeitnow.com/jobs/companies/workist-gmbh/sap-sd-developer-abap-ai-integration-berlin-421440) | Workist GmbH | Berlin | EN | mid / not stated | Py, JVM/Go, Prod, DE req |
| 43 | arbeitnow | AI role | [Senior AI-Native Software Engineer – TypeScript (m/w/d)](https://www.arbeitnow.com/jobs/companies/solarize/senior-software-engineer-nodejs-berlin-390584) | Solarize | Berlin | DE | senior+ | TS/JS, Agents, Obs, Cloud, Docker/CI, Prod, SQL |
| 44 | arbeitnow | SWE + AI tools | [GCP Cloud Engineer (Network) (m/w/d)](https://www.arbeitnow.com/jobs/companies/adconova-gmbh/gcp-cloud-architect-network-berlin-49011) | adconova GmbH | Berlin | DE | mid / not stated | LLM API, Obs, Cloud, Docker/CI, CodingAgents, DE req |
| 45 | arbeitnow | SWE + AI tools | [Senior Data Engineer](https://www.arbeitnow.com/jobs/companies/kayak/senior-data-engineer-berlin-467027) | Kayak | Berlin Office | EN | senior+ | Py, Docker/CI, Prod, CodingAgents, Tests, SQL |
| 46 | arbeitnow | SWE + AI tools | [Founding Engineering Team Lead (HandsOn)](https://www.arbeitnow.com/jobs/companies/techbiz-global-gmbh/founding-engineering-team-lead-handson-berlin-110785) | TechBiz Global GmbH | Berlin | EN | senior+ | JVM/Go, LLM API, Agents, Evals, Obs, Cloud, Docker/CI, Prod, CodingAgents, Tests, Sec |
| 47 | arbeitnow | SWE + AI tools | [Senior Software Engineer (.NET Ecosystem)](https://www.arbeitnow.com/jobs/companies/clickhouse/senior-software-engineer-net-ecosystem-berlin-109033) | Clickhouse | Berlin | EN | senior+ | Py, TS/JS, JVM/Go, Agents, Evals, Prod, CodingAgents, Tests, Sec |
| 48 | arbeitnow | SWE + AI tools | [Senior Software Engineer - Personalization (f/m/d)](https://www.arbeitnow.com/jobs/companies/contentful/senior-software-engineer-personalization-berlin-379123) | contentful | Berlin | EN | senior+ | TS/JS, Agents, Evals, Obs, Docker/CI, Prod, CodingAgents, Tests, Sec |
| 49 | arbeitnow | SWE + AI tools | [Staff Fullstack Engineer](https://www.arbeitnow.com/jobs/companies/deeptech-recruitment/staff-fullstack-engineer-berlin-68381) | Deeptech Recruitment | Berlin | EN | senior+ | TS/JS, LLM API, Agents, Evals, Obs, Prod, CodingAgents, Tests, Sec, SQL |
| 50 | arbeitnow | SWE + AI tools | [Senior Fullstack-Entwickler (m/w/d) – Hybrid PHP/Symfony & React](https://www.arbeitnow.com/jobs/companies/girona-softwareentwicklung-gmbh/senior-fullstack-entwickler-hybrid-php-symfony-react-berlin-165201) | Girona Softwareentwicklung Gmb | Berlin | DE | senior+ | TS/JS, Docker/CI, Prod, CodingAgents, Tests, SQL |
| 51 | arbeitnow | SWE + AI tools | [Senior Product Engineer (m/w/d) – Internal Tools & E-Commerce](https://www.arbeitnow.com/jobs/companies/rosental-organics-gmbh/senior-product-engineer-internal-tools-e-commerce-berlin-32447) | Rosental Organics GmbH | Berlin | DE | senior+ | TS/JS, LLM API, Agents, Obs, CodingAgents, Prompt, SQL |
| 52 | arbeitnow | SWE + AI tools | [Senior Frontend Engineer](https://www.arbeitnow.com/jobs/companies/almedia/senior-frontend-engineer-berlin-327732) | Almedia | Berlin | EN | senior+ | TS/JS, Prod, CodingAgents, Tests |
| 53 | arbeitnow | SWE + AI tools | [Product Design Engineer](https://www.arbeitnow.com/jobs/companies/agent-f-gmbh/product-design-engineer-berlin-303738) | Agent F GmbH | Berlin | EN | mid / not stated | TS/JS, Agents, Prod, CodingAgents, Prompt, Tests |
| 54 | arbeitnow | SWE + AI tools | [(Senior) Product Engineer](https://www.arbeitnow.com/jobs/companies/sustaind-gmbh/senior-product-engineer-bielefeld-429098) | sustaind GmbH | Berlin | DE | senior+ | TS/JS, Agents, Obs, Cloud, Docker/CI, Prod, CodingAgents, Tests, Sec, DE req, SQL |
| 55 | arbeitnow | SWE + AI tools | [Senior DevOps Engineer](https://www.arbeitnow.com/jobs/companies/sustaind-gmbh/senior-devops-engineer-bielefeld-253626) | sustaind GmbH | Berlin | DE | senior+ | Agents, Obs, Cloud, Docker/CI, Prod, CodingAgents, Sec, DE req, SQL |
| 56 | arbeitnow | SWE + AI tools | [Staff Product Engineer](https://www.arbeitnow.com/jobs/companies/parloa/staff-product-engineer-berlin-115686) | Parloa | Berlin | EN | senior+ | Py, TS/JS, JVM/Go, LLM API, RAG, Agents, Evals, Obs, MCP, Cloud, Docker/CI, Prod, CodingAgents, Prompt, Tests, Sec |
| 57 | arbeitnow | SWE + AI tools | [Senior Product Engineer - iOS/Swift](https://www.arbeitnow.com/jobs/companies/qonto/senior-product-engineer-ios-swift-berlin-316842) | Qonto | Berlin | EN | senior+ | JVM/Go, LLM API, Docker/CI, Prod, CodingAgents, Tests |
| 58 | arbeitnow | SWE + AI tools | [Senior/Staff - Go Backend Engineer - remote friendly](https://www.arbeitnow.com/jobs/companies/qonto/senior-staff-go-backend-engineer-remote-friendly-berlin-322072) | Qonto | Berlin | EN | senior+ | JVM/Go, Obs, Cloud, Docker/CI, Prod, CodingAgents, Tests, SQL |
