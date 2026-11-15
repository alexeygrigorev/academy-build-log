# Cost Justification for a Surcharge Above the B-DKS

Research from 14 November 2026, for the course approval (Maßnahmezulassung). I removed all prices, rates and totals from this public version. The full memo with official list prices stays private.

**The question:** can real, documented costs justify a course price above the B-DKS for KldB 43414, up to the +25% cap that a certifier (FKS) can approve without BA consent?

**The rule I followed:** no invented figures. Where a quantity or a rate is my choice and not a published price, it is marked as an assumption and backed by a market-rate source. Nobody was contacted and nothing was submitted.

This memo is the evidence for special costs. It is not a full cost calculation. My own teaching time belongs in the standard staff block of the Kalkulation, not here; counting it again would double-count it against the B-DKS.

Related: [AZAV certification plan](azav-certification.md), [3-month course design](three-month-course-design.md), [QM handbook draft](azav-qm-handbook.md).

## Working assumptions

- **Length:** 520 UE, 3 months, about 13 weeks at 40 UE a week. A 4-month calendar is a sensitivity for monthly subscriptions only.
- **Group size:** 15 participants for the main totals (my planned group is about 15 to 20). The legal calculation basis stays 12 (§ 3 (3) AZAV). Totals are also checked at 12 and 20.
- **Teaching:** I teach alone. Named backup teachers cover illness. Mentors review projects. No second standing instructor.
- **AI tools:** a planning range per participant per month, backed by official list prices of the top paid plans of Claude, ChatGPT and Cursor. The low end is one top-tier seat; the high end is two top-tier seats.
- **Currency and VAT:** US list prices converted at the ECB reference rate; figures net of VAT where possible.
- **Course Management Platform:** the extra hosting cost is unknown, so it is left out. The totals are a lower bound.

## Cost lines

1. **AI tools.** Paid agent and model access is the learning content, not a nice extra. For the certifier we keep the official price pages and, before submission, real invoices or team quotes.
2. **Cloud and API for student projects.** One small hosting instance per participant for the course, plus a capped GPU budget in AWS Frankfurt for heavier work, based on the official AWS price list.
3. **Backup teachers and mentors.** Backup teachers on a standby retainer, and mentors who review projects (working assumption: 1 hour per participant per week). Rates come from published market ranges for freelance trainers.
4. **Learning platform.** Zoom and GitHub team plans, at official list prices.
5. **Room in Berlin (in-person variant only).** Daily rates from three venues in Prenzlauer Berg.
6. **Individual career coaching and interview preparation.** Three individual career sessions and a written CV review per participant, at market coaching rates.

## Result

- **Online, low AI band:** the special costs just reach the +25% cap.
- **Online, high AI band:** they cover +25% with headroom.
- **In person:** they cover +25% with headroom in both AI bands.
- A result above +25% does not allow a price above the cap. It only means the +25% application has headroom. Above +25% the BA must agree.
- Changing the group from 15 to 12 or 20 barely moves the totals, because the big lines (AI tools, mentors, coaching, per-person cloud) do not depend on group size.

**The +25% result at the low AI band is not robust.** It depends on the mentor-hour assumption. With 30 minutes of mentoring per participant per week instead of 1 hour, the online low-band case supports only about +20%. The high band and both in-person variants still cover +25%.

## What to take to the certifier

- Apply at most at +25%. If mentoring is lighter, either document a higher AI-tool spend, document the in-person room, or apply with a lower surcharge (around +20%) instead of stretching the hours.
- The real evidence is not this memo. It is vendor invoices or team quotes for the chosen AI plans, an AWS budget with caps, contracts and CVs for named mentors and backup teachers, Zoom and GitHub invoices, and a room contract if the course is in person.
- Ask the certifier whether ordinary software (Zoom, GitHub) can count, whether a standby retainer is accepted without actual substitution hours, and whether they want the Kalkulation on 12 seats, on 15 to 20, or both.
- Do not invent more cost lines to close a gap.

## Public sources used

- [Claude pricing](https://claude.com/pricing), [ChatGPT pricing](https://chatgpt.com/pricing/), [Cursor pricing](https://cursor.com/pricing)
- [Amazon Lightsail pricing](https://aws.amazon.com/lightsail/pricing/), [AWS EC2 price list, EU (Frankfurt)](https://pricing.us-east-1.amazonaws.com/offers/v1.0/aws/AmazonEC2/current/eu-central-1/index.csv)
- [Zoom pricing](https://zoom.us/de/pricing), [GitHub pricing](https://github.com/pricing)
- [ECB euro reference rates](https://www.ecb.europa.eu/stats/eurofxref/eurofxref-daily.xml)
- [§ 3 AZAV](https://www.gesetze-im-internet.de/azav/__3.html) (calculation basis of 12)
