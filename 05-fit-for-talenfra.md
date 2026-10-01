# 05 — Do accelerators accept a project like Talenfra?

## Short answer
**Yes, the category is accepted — often. The current business shape is the weak point, not the idea.**

## 1. Proof they fund AI recruiting companies (2026 research; sources in `research-raw/C-fit-and-comparables.md`)

| Company | Program | What | Money |
|---|---|---|---|
| Juicebox | YC S22 | AI people-search / recruiting agents | $30M Series A (Sequoia, 2025); >$10M ARR |
| Alex | YC W24 | AI interviewer for screening | $17M Series A (Peak XV) |
| Contrario | YC W25 | Recruiters + AI agents | $2.3M raised; $6M annualised revenue in under 6 months |
| Prism | YC (F25/P26) | "AI-native recruiting agency", 15% of salary per hire | $500K from YC |
| Spott | YC W25 | AI-native ATS/CRM for **staffing firms** (your buyer) | not found |
| Perfectly, Lightscreen, Serra, Outship | YC | screening/sourcing/assessment | not found |
| Tezi | investors incl. South Park Commons | AI recruiting agent | $9M seed |
| HeyMilo | Entrepreneurs Roundtable | AI screening interviews | $2.2M seed |
| HireBound | Antler (India) | AI recruiting | $2M seed (Kalaari) |
| Cantaloupe AI | Techstars Workforce 2025 | voice pre-screening | not found |

Also big without a classic accelerator: Mercor ($10B valuation, Oct 2025), micro1 (~$50M ARR), Paraform (~$65M), Metaview ($35M B), Pin ($3M seed 40 days after launch).
**Warnings:** Moonhub shut down (2025); Workday bought Paradox (~$1B); the category consolidates fast.

## 2. The "agency" question — how YC thinks
- YC's **Spring and Summer 2026 Requests for Startups** asked for "AI-native agencies / service companies" — "sell the completed work, not the tool", with software-like margins. YC funded Prism, a recruiting agency that charges per hire. (Sources are secondary mirrors of the RFS; the Fall 2026 official list has no agency item.)
- Paul Graham ("Do Things That Don't Scale"): doing things by hand early is good, but if clients pay you "by the hour" for that attention, they expect everything. That is the consulting trap.
- Agencies that productized (Mailchimp, Basecamp) won by building **one standard product for many customers**.

**What this means for Talenfra:** the YC-friendly version is "we deliver finished, evidence-backed shortlists for staffing firms at software margins". The unfriendly version is "we build and run a custom copy for each client for a build fee plus a monthly retainer".

## 3. Where Talenfra stands on that line
| Fact (verified in code and docs) | Reads as |
|---|---|
| One codebase + per-client config, deployed as a separate instance per client | Good: it is one product, not custom code. Investors may still see N instances = N things to run. |
| $1,500 POC, $5,500 build, $2,200/month retainer | Looks like services revenue (linear with people). |
| Add-ons (kit, one-pager, outreach, reverse-match, reactivation, interview) | Good product depth. |
| No customers or revenue | The core gap. |

## 4. Honest strengths and weaknesses for accelerators
**Strengths:** built and tested; evidence-backed scoring fits the regulation wave; clear buyer; two founders; India cost base.
**Weaknesses:**
1. Zero customers; never run live.
2. Per-client instances + build fee look like a dev shop.
3. Same buyer is already being sold to by Bullhorn Amplify (screening agents inside the staffing ATS), LinkedIn Hiring Assistant and Workday/Paradox.
4. No data moat: competitors use the same AI models.
5. US programs need time in San Francisco; distance from customers is a question.
6. High-risk regulation adds compliance work for a two-person team.

## 5. How to present it (suggestions for you to decide)
- **Lead with:** "Auditable CV screening for staffing firms: every score shows the exact CV lines, a recruiter approves the rubric, a human decides." Say why that beats a keyword matcher inside the ATS.
- **Reframe the offer** as a standard product with a simple price (per screened role or per shortlist), with the dedicated instance as the enterprise option. Or test an outcome price (per hire) like Prism.
- **Show one number:** hours saved per role on a real pilot.
- **Say the regulation point out loud:** EU AI Act high-risk duties start 2 Dec 2027; Colorado SB 189 on 1 Jan 2027; NYC and Illinois rules already apply.

## 6. Program-by-program acceptance of this kind of project
| Program | Accepts AI/HR-tech? | Notes |
|---|---|---|
| YC | Yes — many recruiting alumni | No written rule against agencies; likes outcome-selling AI services |
| a16z speedrun | Yes — sector-agnostic, AI-heavy | No rule on services found |
| Antler India | Yes — AI-native/AI-first | HireBound is an Antler recruiting company |
| SPC | Yes, but leans "frontier" | Tezi had SPC backing |
| Alchemist | Yes — enterprise B2B AI | Wants buyer proof |
| Techstars | Yes — workforce track existed in 2026 | Not open now |
| EF | Possible — founder-first | Built for individuals |
| Nasscom GenAI Foundry | Yes — had an HR/talent track | 2026 cohort unconfirmed |
| NVIDIA Inception | Product companies only | Excludes consulting firms |
