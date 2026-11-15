# Design of the 3-Month Course (AZAV, Up to +25% Over the B-DKS)

Design from 14 November 2026, checked against the primary sources the same day. 

**The question:** how do we set up a 3-month course so that the certifier approves it at up to +25% over the B-DKS (the BA's standard cost rate)?

**Important update:** the first version of this design had a second instructor in labs and code review. That is no longer the plan. I teach alone, named backup teachers cover absence, and mentors review projects. The case for a surcharge now rests on documented special costs: see the [cost justification](azav-cost-justification.md) and the [AZAV certification plan](azav-certification.md).

Inputs: [market sizing](market-sizing.md), [jobs and course supply](supply-jobs-and-bootcamps.md), [laid-off developers and the Agentur](laid-off-developers-and-agentur.md).

Labels: **[Law]** statute or regulation, **[BA]** BA or Beirat guidance read in the original, **[Inf]** inference.

## 0. Rules that drive the design

- **[Law]** [§ 179 (2) SGB III](https://www.gesetze-im-internet.de/sgb_3/__179.html): costs are appropriate if they do not exceed the B-DKS, or if the excess comes from "notwendige besondere Aufwendungen". Above +25% the BA must agree.
- **[Law]** [§ 3 (3) AZAV](https://www.gesetze-im-internet.de/azav/__3.html): the calculation for a group course is "grundsätzlich" based on 12 participants.
- **[Law]** § 3 (4) AZAV matters up to +25%: above-average staff, special rooms, special tech, special content, accessibility, and a justified group below 12. § 3 (6) only covers BA consent above +25%.
- **[BA]** [Fachliche Weisung Kostenzustimmung](https://www.gut-cert.de/files/content/download/AZAV/ba_weisung-kostenzustimmung-p-179_ba056279.pdf) (from 1 April 2026): up to +25% the certifier decides alone. "Gemeinkosten können grundsätzlich keine besonderen Aufwendungen begründen". Each cost line needs its own reason, including why no cheaper option exists. A correct calculation alone does not justify an excess; the cost-benefit ratio must. The Weisung gives an example that is almost our case: an expert-level course where a highly qualified teacher is necessary. Formally the Weisung covers cases above +25%; **[Inf]** certifiers apply the same logic below, so I use it as the standard.
- **[BA]** [Beirat recommendations](https://www.arbeitsagentur.de/datei/dok_ba032840.pdf) (17 June 2026): every calculation is checked. "Eigenerklärungen des Trägers (ohne Nachweise) genügen nicht". Overhead and profit can be included in reasonable proportion. Group size is part of the approval and printed on the certificate. "Unterricht" means direct interaction with teachers is possible at any time; supervised project and group work counts; a forum or hotline does not. Subcontracting to non-certified parties: at most 10%.
- **[BA]** [Umsetzungshinweis 1/2026](https://www.arbeitsagentur.de/datei/umsetzungshinweis-01-2026_ba055638.pdf): one UE is 45 minutes; work-based learning and asynchronous parts are 60-minute hours. Their costs can go into the total, but the total is divided by live UE only.
- Courses above the B-DKS are not part of the certifier's sampling and are checked one by one ([AZAV Wissensportal](https://azav-wissensportal.de/beitraege/bdks-2026-neue-kostensaetze/), secondary).

## 1. Program structure

All 520 UE are live. No asynchronous parts and no internship, so every hour counts and the certificate stays simple.

**Daily schedule, Monday to Friday, 09:00 to 16:30** (60-minute lunch, two 15-minute breaks, 8 UE):

| Time | Block | UE per week |
|---|---|---|
| 09:00–10:30 | Live input and demo, whole cohort | 10 |
| 10:45–12:15 | Guided lab | 10 |
| 13:15–15:30 | Project studio: squads work on a real codebase | 14 |
| 15:45–16:30, Mon–Thu | Live code review in squads of 5 to 6 | 4 |
| Friday afternoon | Demo and retro, employer guests | 2 |

**Entry gate:** 2+ years of experience plus a code screen. This also supports § 3 (1) AZAV (the course fits the target group).

### Phases (520 UE)

The two programs complement each other (decided on 14 November 2026): AI Engineering gets a module on agentic engineering (using coding agents to write and ship software), and Agentic Engineering gets an Introduction to AI engineering module (building apps on top of LLMs). Weeks 10 to 13 are the same in both programs.

| Program | Weeks 1–4 | Weeks 5–9 | Weeks 10–13 | Total |
|---|---|---|---|---|
| AI Engineering (based on LLM Zoomcamp) | week 1: LLM foundations 32 + coding-agent setup 8; weeks 2–4: Zoomcamp core 120 | week 5: agentic engineering 32 + squad 8; weeks 6–9: squad project 160 (168 in total) | interview prep 80 + capstone 80 | 520 |
| Agentic Engineering | weeks 1–3: agent workflow on existing codebases 120; week 4: Introduction to AI engineering 40 | weeks 5–9: squad project 200 | interview prep 80 + capstone 80 | 520 |

**AI Engineering, agentic engineering module (40 UE):** 8 UE on day 1 (a safe baseline: project context file, permissions, cost control, the plan-edit-review loop), because participants have paid Claude Code and Cursor seats from the start. Then 32 UE in week 5 for the full workflow (spec to tasks, tests as the contract, reviewing agent diffs, CI, parallel agents) at squad kickoff, on the squad's own repo. Less than about 24 UE would be a tool demo; 80 UE would push out Zoomcamp content or cut the squad project to three weeks.

**Agentic Engineering, Introduction to AI engineering (40 UE, all of week 4):** LLM API and structured output, a chatbot, search over documents (RAG), then tool calling and a simple agent, with a small build demoed on Friday. The squad project should include an LLM-backed feature, so the module becomes something to show in interviews.

### Weeks 10 to 13: interview preparation and capstone

Decided on 14 November 2026: 80 UE of interview preparation and 80 UE of individual capstone in both programs. This is interview preparation, not a job placement promise.

- **Week 10, a full interview week (40 UE):** how hiring loops work now and how to prepare; CV, LinkedIn and GitHub; a first algorithm-style coding round; a timed take-home with review; how to present the squad project; a first round of mock interviews. The capstone is scoped this week.
- **Weeks 11 to 13, about 13 UE of interview practice per week (40 UE) plus 80 UE of capstone:** the guided lab slot becomes timed algorithm and live-coding practice; the review slot becomes mock interviews in the squads; two Friday slots become project-talk rehearsals.
- **Trade-off:** the individual capstone is a focused two-week build, not a month-long project. The squad project stays the stronger thing to talk about in interviews. Starting in week 10 means people can apply and interview while they still have support. A certifier may ask why about 15% of the course is interview preparation **[Inf]**; we describe it as technical assessment practice (coding rounds, take-homes, technical presentations).
- **Career consultations** sit next to this block: three individual 45-minute sessions plus a written CV and profile review per participant. Session 1 in weeks 4–5 (target role, positioning, gaps), session 2 in week 10 (application plan, feedback on the first mock), session 3 in weeks 12–13 (debrief of real interviews). They happen during project studio time, so they stay inside the 520 UE. No new cost line.

### What we do not include

- **Internship (betriebliche Lernphase):** allowed, but the hours do not count as UE, and the Beirat says they usually carry "keine oder geringere Kosten". It adds weeks of ALG without adding value to the course. Not included.
- **Employer projects instead:** an employer gives a brief and a product owner for Friday demos. The work happens in our classroom with our teachers, so it stays teaching. Open-source or non-commercial deliverables avoid "unpaid work" and IP issues.
- **After the course:** the Vermittler can grant a short trial at an employer under [§ 45 SGB III](https://www.gesetze-im-internet.de/sgb_3/__45.html) (at most 6 weeks) as a separate instrument.

## 2. Special costs per participant

Paid agent seats (Claude Code, a second agent such as Cursor or Codex), GitHub with Copilot, a capped LLM API budget for agents in CI and evals, a capped cloud sandbox, eval and observability tools, and shared Zoom/Slack/learning platform costs. No hardware: experienced developers have laptops. Before submitting, we attach current price pages or quotes.

## 3. Which justifications work

What works **[BA + Inf]**:

1. **Staff:** individual review of agent-generated code is the learning goal and cannot be done 1:12. We explain why peer review alone is not a cheaper equivalent.
2. **Qualification:** senior practitioners at market pay, like the example in the Weisung.
3. **Technical equipment:** paid agent seats and API budgets, because free tiers do not allow agentic work. The seats are used only in this course.
4. **Content:** regular curriculum updates, spread over the planned runs within the three-year approval.

What fails: "high quality", marketing, certification fees, management time, and anything in overhead.

Documents to prepare:

- Course concept: goal, target group, entry check, methods, success control, staffing plan by block.
- Calculation as a cost and revenue statement, categories separated, KldB 43414.
- A justification table: cost line, § 3 (4) category, why it is needed, the cheaper alternative we rejected, the evidence.
- Evidence: contracts, CVs and qualifications, vendor price lists or quotes, a comparison calculation.
- Labour-market evidence: the Bildungszielplanung Berlin 2026 line on expert and specialist level, a job-ad analysis, employer contacts or letters of intent.
- The planned course success and how we measure it.

## 4. Risks

| Risk | Assessment | Mitigation |
|---|---|---|
| The certifier cuts the surcharge | Likely in part; every course above the B-DKS is checked one by one | Headroom, a line-by-line justification, and the fallbacks below |
| Timeline | A new provider needs the provider approval first; an April 2027 start needs certificates around January–February **[Inf]** | Sign with a certifier now; submit both approvals together |
| The Vermittler finds it expensive | The voucher pays the approved price, but agencies weigh economy **[Inf]** | Compare the total with the longer 6–7 month courses, plus several fewer months of ALG |
| Employment rate | Berlin IT courses are at 35.6%; a new course has no record | Entry gate, employer projects, demo days, a published 6-month placement count from cohort 1 |
| "You are employable" refusal | Real for seniors | A one-pager for the Vermittler: § 81 (1a) SGB III, the Bildungszielplanung quote, job ads that ask for agent skills, the applicant's list of rejections. See [Berater objections](berater-objections.md) |
| Filling seats and dropouts | Break-even is around 11 to 12 seats | A waitlist |

Write "12, up to 15" into the concept, so running 15 matches what was approved.

## 5. Fallbacks

- **+25%:** the design above.
- **+10%:** lighter mentoring and API budgets, fewer career sessions (two per participant; the interview block stays).
- **At the B-DKS:** lead teacher only, peer review, smaller tech budget. Still viable at 15 seats.
- **A smaller group as the legal argument:** with a lead only, the smallest group that fits under +25% is 10. A group of 8 would need BA consent.
- **Two parallel groups:** shared lectures cut the cost per UE and remove the basis for the surcharge. We run sequential cohorts instead (April, September).

## Sources

- [§ 179 SGB III](https://www.gesetze-im-internet.de/sgb_3/__179.html), [§ 3 AZAV](https://www.gesetze-im-internet.de/azav/__3.html), [§ 81 SGB III](https://www.gesetze-im-internet.de/sgb_3/__81.html), [§ 45 SGB III](https://www.gesetze-im-internet.de/sgb_3/__45.html), [§ 180 SGB III](https://www.gesetze-im-internet.de/sgb_3/__180.html)
- [BA Fachliche Weisung Kostenzustimmung, from 1 April 2026](https://www.gut-cert.de/files/content/download/AZAV/ba_weisung-kostenzustimmung-p-179_ba056279.pdf) (certifier-hosted copy)
- [Beirat recommendations under § 182 SGB III, 17 June 2026](https://www.arbeitsagentur.de/datei/dok_ba032840.pdf)
- [Umsetzungshinweis 1/2026](https://www.arbeitsagentur.de/datei/umsetzungshinweis-01-2026_ba055638.pdf)
- [B-DKS table, from 1 July 2026](https://www.arbeitsagentur.de/datei/tabelle-der-kosten-fuer-massnahmen-der-beruflichen-weiterbildung-2024_ba049411.pdf)
- [Bildungszielplanung Berlin 2026](https://www.arbeitsagentur.de/vor-ort/datei/bildungszielplanung_berlin_2026_ba264851.pdf)
- Earlier 640-UE syllabi for both tracks in [research-dump](https://github.com/alexeygrigorev/research-dump/tree/main/courses/ai-engineering-school-germany/bildungsgutschein)
