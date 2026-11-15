# AZAV Quality Management Handbook: First Draft

Draft v0.2, 14 November 2026. The working draft is in German, because the certifier audits in German.

Change from v0.1: there is no second standing instructor. Substitution runs through contracted backup teachers; for the audit we need a CV and a written agreement for each. Mentors review projects.

Basis: § 2 (4) AZAV (the 9 elements), § 2 (1)–(3), (5) and (7) AZAV, § 178 SGB III, and the Beirat recommendations under § 182 SGB III (17 June 2026). Background and timeline: [AZAV certification plan](azav-certification.md). Course design: [3-month course design](three-month-course-design.md). Cost evidence: [cost justification](azav-cost-justification.md).

Important for the audit: the certifier checks not just the paper but how we **apply** it. For each element below there is a record and a start date. The free online sessions on 23 November, 30 November and 7 December 2026 already run through these processes, so we have real records by the audit.

## Part A: Provider and scope

- **Provider:** my sole proprietorship, trading as DataTalksClub, in Berlin. The business registration will add training (Weiterbildung / Schulungen).
- **Field:** 4, vocational further training (§ 5 (1) Nr. 4 AZAV).
- **Offer:** DataTalksClub Academy. First course: a 3-month full-time program for experienced software developers (Agentic Engineering), 520 UE, fully live online in a virtual classroom or in person in Berlin, taught in English, calculation basis 12 participants (§ 3 (3) AZAV), planned group about 15 to 20. I teach alone. Training goal KldB 43414.
- **Format:** a digital course in the Beirat's sense. All lesson units are live; teachers and participants can interact at any time (mic, camera, chat, screen sharing). No asynchronous parts and no recordings promised in the contract. So it is not distance learning under the FernUSG (BGH, 5 February 2026, III ZR 137/25).
- **Administering location:** the Berlin business seat. Open question for the certifier: is a home office enough, or do we need a rented room?

**Roles**

| Role | Person | Tasks |
|---|---|---|
| Head (owner) | me | overall responsibility, design, the only regular teacher, contracts, Kalkulation, company partnerships |
| QM lead | me | handbook, internal audits, KPIs, management review |
| Backup teachers (freelance, on standby) | to be named | teach when I am out, following the documented weekly plan and prepared materials; CV and framework agreement each |
| Mentors (freelance) | to be named | project support and code reviews |
| Organizational assistance | AI assistants under my supervision | scheduling, templates, reports; no decisions about participants |

**Substitution:** if I cannot teach, the contracted backup teachers take over using the weekly plan and prepared materials. Organizational tasks (attendance, participant communication, reports to the Agentur) are in checklists, so a backup can do them without onboarding. Absences and make-up dates go into the class log.

**Subcontracting:** at most 10% of a course to non-certified subcontractors (Beirat 5.2). None planned. Freelance teachers are hired directly and included in the QM system (selection, onboarding, rating).

## Part B: The 9 elements of § 2 (4) AZAV

### 1. Mission statement

Draft:

> DataTalksClub Academy prepares experienced software developers to build and ship software with AI agents and to take responsibility for it. Our goal is lasting employment. We teach live, in small groups and on real codebases, because employers ask for exactly these skills. We measure our success by how many graduates find a fitting job within six months, and we publish that number. We treat participants as adult professionals: we listen, explain our decisions and improve the course after every cohort.

Records: the statement in the handbook and on the website; every teacher signs that they read it. Reviewed yearly.

### 2. Organization, management, goals and internal audits

- Org chart, roles and substitution as in Part A.
- A process map with the core processes: market watch and design; informing interested people; entry check and admission; delivery and attendance; progress checks; completion and certificate; job-search support; evaluation. Support processes: staff, tech and IT, data protection, purchasing, document control, complaints, corrective actions.
- Draft goals for 2027: the first cohort with at least 12 participants starts in April 2027; dropout below 10%; final satisfaction at least 4.3 of 5; at least 60% in insured jobs six months after the course (to be justified against the Berlin IT rate); at least 5 partner companies with project briefs or demo-day visits.
- One internal audit a year using the certifier's AZAV checklist, the first one before the approval audit. As a one-person provider, the internal audit is done by an external person or as a documented self-assessment checked by a backup teacher.
- Management review yearly and after each cohort: KPIs, feedback, complaints, audit results, labour-market changes, resources. Output: actions with dates and owners.
- Document control: all QM documents are versioned in Git (history with date and author) plus an approved PDF. Participant files are separate and access-restricted.

### 3. Qualification and training of management and teachers

- Teacher profile: at least 5 years in software development, proven practical work with AI coding agents, teaching or mentoring experience with adults, English at least C1.
- Teaching ability: shown by teaching experience (DataTalksClub courses with ratings, workshops, talks) and a trial lesson before hiring. Open question: does the certifier expect a formal teaching qualification?
- Onboarding of new teachers: mission, course concept, attendance, data protection, complaints, grading. Checklist and signature.
- Training plan: at least 24 hours of subject training per person per year (new agent tools, conferences, own projects) and at least 8 hours of teaching methods. The field changes every few months.
- Participants rate teachers in every weekly survey and at the end (§ 2 (3) Nr. 3 AZAV). Results are discussed with each teacher once per cohort.

### 4. Targets, KPIs and continuous improvement

| KPI | Definition | Source | Target | When |
|---|---|---|---|---|
| Utilization | participants at start / seats | participant list | at least 12 of 15 | per cohort |
| Attendance | attended UE / planned UE | attendance log | at least 90% | weekly |
| Dropout | dropouts / starters | participant file | below 10% | per cohort |
| Learning success | passed project reviews / participants | review forms | at least 90% | per phase |
| Satisfaction | average final feedback (1–5) | survey | at least 4.3 | per cohort |
| Teacher rating | average weekly survey (1–5) | survey | at least 4.3 | weekly |
| Complaints | count, handling time | complaint log | answer within 2 working days | ongoing |
| Employment | insured job 6 months after the end / graduates | follow-up survey | at least 60% | 6 months after |
| Company partnerships | companies with a project brief or demo day | partner list | at least 5 | yearly |

Each teacher gets written targets before each cohort. Each participant agrees an individual learning and job-search plan in week 1, reviewed in weeks 4, 9 and 13. Every miss against a target goes into an action log (cause, fix, owner, date, check). Each cohort ends with a retrospective and concept changes. Changes that affect the certificate are reported to the certifier.

### 5. Labour-market developments

- A quarterly job-market analysis (BA Jobbörse, StepStone, LinkedIn; Berlin and remote in Germany) against the curriculum skills. The first one exists: [supply and jobs](supply-jobs-and-bootcamps.md) (58 job ads, November 2026).
- The Berlin Agentur's yearly Bildungszielplanung.
- An employer advisory group: 3 to 5 Berlin companies from the DataTalksClub network give curriculum feedback and project briefs once per cohort.
- Community signal: the DataTalksClub community (Slack, courses, podcast) shows which tools people really use.
- The curriculum is reviewed before every cohort, with documented reasons for changes.
- As a new provider (§ 2 (7) AZAV) we explain how we will meet the requirements: processes, templates, partner commitments and our track record from DataTalksClub courses.

### 6. Individual learning and integration

1. Information before entry: a video call and a written Bildungsangebot with course number, dates and costs for the Agentur or Jobcenter.
2. Entry check: at least 2 years of software development, a coding task with fixed criteria, English at least B2, a short talk about goals. Results and reasons are recorded. People who do not fit get a reason and, if possible, a pointer to better options.
3. Individual learning and job-search plan in week 1, reviewed in weeks 4, 9 and 13.
4. Progress checks: project reviews at the end of each phase, daily code reviews in small groups, a demo on Fridays.
5. Support: after two unexcused absences or a failed project review, a one-on-one talk with a support plan. If someone might drop out, the funding body is informed after talking to the person.
6. Job-search support inside the lesson hours: CV and portfolio (GitHub, project demo), technical interview preparation, a demo day with partner companies.
7. Completion: a certificate of the content (§ 180 SGB III) and a certificate of attendance with content, duration and goal (§ 2 (5) AZAV).
8. Attendance: login and logout times in the virtual classroom, plus camera-on phases and teacher spot checks. Absences are reported to the funding body as the voucher requires.

### 7. Evaluation of courses and their labour-market results

- A weekly survey (5 questions, can be anonymous), a midpoint evaluation in week 6, a final evaluation in week 13.
- Follow-up surveys 3 and 6 months after the course: job status (insured or not), role, how relevant the course was. Consent is collected at entry.
- A short form for partner companies after the demo day, and for employers who hire graduates (with the graduate's consent).
- An evaluation report per cohort, feeding the management review and the curriculum review.
- We publish the employment rate (see the mission statement).

### 8. Ongoing cooperation with third parties

| Partner | Cooperation | When |
|---|---|---|
| Agentur für Arbeit Berlin, Jobcenter | inform employer service and training advisers about the course; attendance and absence reports; feedback on needs | before each cohort, ongoing |
| Partner companies (advisory group) | project briefs, demo day, curriculum feedback, hiring | per cohort |
| DataTalksClub community | practitioner guest talks, mentoring, job leads | ongoing |
| Certifier | approval, surveillance, change reports | yearly and on change |
| Software and platform vendors | licenses and education terms | yearly |

Once a year we rate each partnership (value for participants, reliability) and decide which to grow.

### 9. Complaint management with regular surveys

- Channels: a dedicated email address, an anonymous form, or talking to a teacher. The channels are in the participant contract, the welcome email and the course channel.
- Process: confirm within 2 working days, resolve and answer within 10 working days, log it (date, content, cause, action, reply, check).
- Escalation: if the person is not happy with the solution, we point them to the funding body or the certifier.
- Regular surveys (element 7). Survey criticism that needs a concrete fix is handled like a complaint.
- Complaints and praise from teachers and companies are logged too.

## Part C: Other things the audit checks

1. **Participant contract** (§ 178 Nr. 5 SGB III): fair withdrawal and termination, the service described as live teaching, **no recordings promised**, certificates.
2. **Data protection:** record of processing, data processing agreements with the video and learning platforms, deletion periods for participant files, consent for follow-up surveys.
3. **Tech and IT:** video platform, learning platform, code hosting, AI tools with a license per participant, requirements for participants' equipment, tech support during lessons, a fallback if something fails.
4. **Health and safety for online teaching:** breaks in the timetable, screen-work guidance.
5. **Capacity and reliability** (§ 2 (1) AZAV): declarations on insolvency, criminal records and trade bans, the updated business registration, proof of financial capacity.
6. **Freelance teachers:** contracts with consent under § 127 SGB IV (transitional rule until 31 December 2027), and the provider's confirmation for their VAT exemption once we have the certificate under § 4 Nr. 21 UStG.

## Part D: Templates and records

| # | Document | Status |
|---|---|---|
| 1 | Org chart and substitution rule | draft in Part A |
| 2 | Process map and process descriptions | open |
| 3 | Goals and KPI sheet | draft in elements 2 and 4 |
| 4 | Internal audit checklist, management review minutes | open |
| 5 | Teacher profile, onboarding checklist, training plan | open |
| 6 | Job-market report template | first analysis exists |
| 7 | Entry check form and code-screen criteria | open |
| 8 | Learning and job-search plan | open |
| 9 | Project review forms | open |
| 10 | Attendance log and class log | open |
| 11 | Weekly survey, midpoint and final evaluation, follow-up survey | open; pilot with the free sessions in November and December 2026 |
| 12 | Complaint log and action log | open; start with the free sessions |
| 13 | Partner list and letters of intent | open |
| 14 | Sample contract, certificate of attendance, final certificate | open |
| 15 | Data protection documents | open |

## Next steps for this handbook

1. I review the mission statement, goals and KPIs.
2. Templates 11 and 12 are ready before the first free session on 23 November 2026, so records start.
3. After we choose a certifier, the handbook follows their checklist and structure.
4. The open points in Part C are done by 18 December 2026.
