# 04 — What to finish before you apply (gap list)

Ordered by how much each item moves your odds. Effort = rough guess. Nothing here was done or started — it is a list for you to choose from. Dates counted from 2026-10-01.

## Must do (these decide the application)

| # | Gap | What "done" looks like | Effort |
|---|---|---|---|
| 1 | **First real users.** No outreach has started. | 15–30 conversations with staffing/recruiting firm owners; 2–5 firms that run the engine on a real role (free or paid POC); notes and quotes; ideally 1 paid POC or signed LOI. Use the free-audit offer you already designed. | 3–6 weeks, ongoing |
| 2 | **Put the engine live.** It has never run on a real server. | Deploy to `app.talenfra.com` per `docs/FIRST_DEPLOY_PLAN.md` (Oracle free VM — your steps Part A + C). Run it on synthetic then pilot data. A live demo link for the application. | 2–4 days of your time |
| 3 | **Sort out the company.** (an option for you to choose, with your lawyers and a CA) | Founder agreement (split, vesting, roles, what if one leaves) and IP assignment of all code/brand/domain from you and Bushra to a company. Whether to set up an Indian Pvt Ltd/LLP now is optional: the research says wait on the US flip until acceptance or a term sheet, but several programs need an Indian entity and a proprietorship cannot take equity. A CA must confirm whether converting the proprietorship affects DPIIT recognition (it excludes businesses "formed by splitting or reconstructing" an existing one). See `07-other-findings.md`. | 2–4 weeks |
| 4 | **Fix the website's over-promises.** | Remove or reword: ATS integration (Bullhorn/Vincere/JobAdder/Greenhouse), Google Sheet output, Notion/Airtable dashboard, Slack/email notifications, "recorded video" interview answers, "retraining on hiring outcomes", relevance/accuracy numbers ("85–90%" in faqs.ts, "87–92%" in BentoFeatures.tsx, "85–92%" in OutputMockup.tsx, "relevance after a 30-day calibration" in charts.ts, "15–20%" in phases.ts), monthly drift report. Search the site for all of them. Or build them (your own research doc, `Next workflows proposed.md`, recommends exports + alerts first). | 1–2 days to reword |
| 5 | **A sharper story.** | One paragraph: who (staffing firms), pain, why you win vs Bullhorn Amplify / LinkedIn Hiring Assistant (evidence + recruiter-approved rubric + audit trail + runs in the client's own instance), and how it grows (one product, many customers). See `05-fit-for-talenfra.md`. | 2–3 days |
| 6 | **Founder facts.** | Be ready to say: both full-time? (Strategy notes mention a job.) Who codes? What each has built? Willingness to move to SF with visa help? Equity split? Decide the third person's status (Aqdas) — site lists three "team" members, you said two founders. | 1 day of discussion |

## Should do (raise the odds)

| # | Gap | Detail | Effort |
|---|---|---|---|
| 7 | **Investor pitch pack.** | 1-minute founder video (both founders, no script, no demo); 2–3 minute demo recording (you already have a 3:07 customer demo); 10-slide investor deck (your current deck is for customers); one-page metrics sheet; competitor table. | 1 week |
| 8 | **Pricing story that scales.** | Decide whether the lead offer is a standard subscription, a per-shortlist/per-hire price, or the current build + retainer. Keep per-client instances as an "enterprise" option if you like. Needs your decision. | decision + 2 days |
| 9 | **Compliance pack.** | Finish the DPA template (FILL slots); SCC/UK addendum pack for EU/UK clients; 1-page security overview (summarise SECURITY_REVIEW); 1-page "how scoring works, what it never uses, human in the loop, how we test for bias"; candidate-notice template; counsel sign-off on erasure/retention (O3). | 1–2 weeks with lawyers |
| 10 | **Fix two real engine gaps before real candidate data.** | (a) Erasure can leave orphaned résumé files if a delete fails after the DB record is wiped (found in the code check); (b) erasure is not atomic across DB, files and interview transcripts. Also decide whether the One-Pager should skip rejected candidates. | 1–3 days |
| 11 | **Measure it.** | Run the engine on pilot CVs against the recruiter's own shortlist; record agreement, time saved, cost per CV. Real numbers replace the unmeasured website claims. Also test weak candidates and scanned CVs (listed as untested). | 1–2 weeks, with #1 |
| 12 | **Travel readiness.** | Passports valid > 6 months; US visa appointments in India can wait long; ask YC's/a16z's immigration lawyers on day one if accepted. | 1 day |

## Nice to have
- Free perks after incorporating: NVIDIA Inception, Microsoft for Startups.
- Start the SOC 2 roadmap with a tool (Vanta/Drata) — investors accept a roadmap at pre-seed.
- Add a short "regulation" slide (EU AI Act 2 Dec 2027, Colorado 1 Jan 2027, NYC LL144) — it turns your evidence feature into a reason to buy.

## Suggested order for the next 32 days (to 2 Nov) — a recommendation, not a plan I will act on
- **Week 1:** start outreach (#1), reword website (#4), deploy live (#2), book the lawyer/CA meeting for #3.
- **Week 2–3:** pilots running, founder video + deck + demo (#7), founder agreement and IP assignment (#3; Pvt Ltd only if you choose that route).
- **Week 4:** collect quotes/numbers, finish the written YC application, a16z speedrun application (window closes 1 Nov), submit YC by 2 Nov.

If the traction work is not showing by the deadline, an alternative is to submit anyway (free, no entity needed) and use YC "Early Decision" or the next batch to apply again with traction. About half of funded YC companies applied more than once.

## Questions for you (I will not assume)
1. Are both of you full-time on Talenfra from now, or do jobs or study remain? (Only an early planning brief, `ai-agency-launch.md`, says "4 hours per day alongside a job" — it may be out of date.)
2. Which pricing story do you want to lead with: subscription, per-shortlist, per-hire, or current build + retainer?
3. Who is the third person on the website (Aqdas): co-founder, adviser or contractor?
4. Do you want me to turn any item above into a plan (for example the website rewording, the investor deck or the outreach kit)?
