# D — Legal, India, Visa & Other Things to Know (accelerator applications)

Research for: Mohd Aqib + Bushra Masood, Talenfra (AI CV-screening for recruiting firms), today a sole proprietorship in Lucknow, India.
Researched: 2026-10-01. All sources read on 2026-10-01 unless noted.
I am NOT a lawyer or CA. This is a fact-gathering note. Anything marked **[LAWYER/CA MUST CONFIRM]** needs a professional sign-off before you act. Anything marked **UNVERIFIED** came from a secondary source I could not confirm on an official page.

---

## 0. The short version (read this first)

1. **You do NOT need a company to apply** to YC (official FAQ). For most programs you can apply as two people and incorporate after acceptance.
2. **You WILL need a "flip" to take money from YC or Techstars.** YC only invests in companies incorporated in the US, Canada, Singapore or Cayman. Techstars names India as a "non-approved" country that must reorganize. The usual answer is: Delaware C-corp parent on top, Indian Pvt Ltd as its 100% subsidiary.
3. **India's ODI rules make the flip harder than for most countries.** An Indian resident individual generally cannot personally *control* a foreign company that owns an Indian company. The common workaround (used in Stripe Atlas' official India guide) is: each founder sets up an Indian LLP; the LLP holds the US shares. This needs an AD bank, a UIN, Form FC, yearly APR + FLA filings. **A CA + FEMA lawyer is essential here.**
4. **Don't flip before you have a reason.** Wait for an acceptance (YC/Techstars will push you and give lawyers), or a US investor term sheet. Flipping costs money every year (Delaware franchise tax, US + India compliance, transfer pricing).
5. **Deals (verified 2026-10-01):** YC = $500K (= $125K for 7% post-money SAFE + $375K uncapped MFN SAFE). Techstars = $220K (= $20K for 5% common + $200K uncapped MFN SAFE). EF = $125K for 8% post-money SAFE + optional $125K uncapped MFN. Antler India = up to ₹4 Cr for 11%. 500 Global has moved to a "500 Fellowship" that **charges a $35,000 program fee** — check carefully.
6. **Visas:** Indians cannot use E-2 (no treaty). Most international founders attend YC on a **B-1 business visitor visa**; longer-term path is usually **O-1A**. H-1B now carries a **$100,000 fee** for new petitions from abroad (extended on 2026-09-18 to 2027-09-21; under court challenge). US visa interview waivers were mostly ended from 2025-09-02, so plan for long Indian consulate wait times. Canada closed its Start-up Visa; UK Innovator Founder and Singapore EntrePass are live alternatives.
7. **Your product is "high-risk" territory.** CV screening is a named high-risk use under the EU AI Act (now applies from **2 Dec 2027**, delayed by the 2026 Omnibus). NYC LL144, Illinois HB 3773 (live since 1 Jan 2026), California FEHA ADS rules (live since 1 Oct 2025), Colorado's new SB 189 (from 1 Jan 2027), India's DPDP Rules (core duties from ~May 2027). Investors will ask about all of this.
8. **YC Winter 2027 on-time deadline: 2 Nov 2026, 8pm PT.** Decisions by 11 Dec. Techstars NYC final deadline: 18 Nov 2026.

---

## 1. Incorporation for accelerator applications

### 1.1 Do you need a company before applying / joining?

| Program | Before applying? | Before money arrives? | Source |
|---|---|---|---|
| **Y Combinator** | No. FAQ: "Do we need to be incorporated to apply?" → "Nope." | Must be incorporated in **US, Canada, Singapore or Cayman**. If incorporated elsewhere (e.g. India), you set up a parent in one of those and your existing company becomes a subsidiary. | https://www.ycombinator.com/faq (read 2026-10-01) |
| **Techstars** | Not stated as needed to apply. | Companies must be US corporations "or foreign equivalents"; companies in **non-approved countries like India require reorganization before investment**. | https://www.techstars.com/investment-terms (read 2026-10-01) |
| **500 Global (500 Fellowship)** | Not stated. Must be "in the U.S. already, or you plan to be within six months". | Not stated on page. **UNVERIFIED**. | https://500.co/founders/flagship (read 2026-10-01) |
| **Antler India** | No; solo founders and teams can apply. | Not stated on page. Antler India invests into Indian companies too (INR cheque). **UNVERIFIED** on exact entity rules. | https://www.antler.co/india (read 2026-10-01) |
| **Entrepreneur First** | No — EF accepts **individuals**, not companies. | Companies incorporating in India get **CCPS (compulsory convertible preference shares)** on equivalent terms; the extra $125K MFN SAFE requires **Delaware C-corp + move to San Francisco**. | https://www.joinef.com/faqs/london/ (read 2026-10-01) |

Note on YC's country list: YC briefly removed Canada from its list in early 2025, then restored it after backlash. Today's FAQ lists US, Canada, Singapore, Cayman. Source: https://betakit.com/y-combinator-reverses-decision-will-invest-in-canadian-domiciled-startups-again (read 2026-10-01).

**What this means for you:** Apply now as a sole proprietorship / as two people. Don't spend on a flip until accepted. The program and its lawyers will tell you exactly what structure they want.

### 1.2 The "flip": Delaware C-corp + Indian subsidiary vs staying Indian Pvt Ltd

**Option A — Delaware C-corp parent + Indian Pvt Ltd subsidiary ("the flip")**
- What US VCs and YC/Techstars expect. Standard SAFE and preferred stock documents work out of the box.
- For Indian resident founders, the shares in the US parent are an **Overseas Direct Investment (ODI)** under FEMA. Stripe's India guide (built with JSA, Cooley and Inkle) says Indian founders are "prohibited from personally controlling a foreign entity that owns an Indian entity", so the usual route is: **each founder forms an Indian LLP → the LLP buys the US shares → US company later forms the Indian Pvt Ltd.** Source: https://docs.stripe.com/atlas/indian-founder-guide (read 2026-10-01).
  - Each LLP needs two partners (e.g. founder + family member with ~0.1%). LLP formation ~2 weeks.
  - Open LLP bank accounts at the **same AD (Authorised Dealer) bank**; bank gets a **UIN** for the US company; payment goes with **Form FC** + bank's Form A2.
  - Share certificate to AD bank within **6 months** of payment.
  - Every year: **Annual Performance Report (APR)** to AD bank by **31 December**; **Form FLA** to RBI by **15 July**. Source: https://support.stripe.com/questions/faq-for-indian-founders-using-stripe-atlas (read 2026-10-01).
- **Two-layer rule:** Overseas Investment Rules 2022, Rule 19(3): no Indian resident may invest in a foreign entity that invests into India "resulting in a structure with more than two layers of subsidiaries". Source: summary at https://mondaq.com/india/financial-services/1286750/new-overseas-investment-regulations-and-rules ; primary rules at https://rbi.org.in/scripts/Bs_viewcontent.aspx?Id=5087 (read 2026-10-01). Keep the structure flat (LLP → US Inc → India Pvt Ltd). **[LAWYER/CA MUST CONFIRM how layers are counted for your structure.]**
- When the US parent sends money down to the Indian subsidiary, that is **FDI into India**. IT/software is 100% automatic route; the Indian company must file **FC-GPR within 30 days of allotting shares** (late fee formula applies). Source: https://www.incorpx.io/blog/fema-compliance-foreign-investment-india (secondary; read 2026-10-01) — **[CA MUST CONFIRM]**.
- Costs that keep coming: Delaware franchise tax + registered agent (~$100/yr via Atlas after year 1), US federal tax return (Form 1120 + 5472-type filings), Indian company audit/ROC, APR/FLA, **transfer pricing** between US parent and Indian sub (Indian sub usually bills the parent cost-plus for dev work). **[CA MUST CONFIRM — budget a CA retainer.]**

**Option B — Stay Indian (Pvt Ltd only)**
- Works for Antler India, EF (via CCPS), Indian angels/VCs, DPIIT benefits.
- Does NOT work for YC or Techstars money (they require reorganization).
- Converting the sole proprietorship to a Pvt Ltd is cheap and quick and makes you DPIIT-eligible (see §4.3).

**Option C — Reverse flip later (come back to India)**
- Big Indian companies (PhonePe, Groww, Zepto, Meesho, Pine Labs, Flipkart) moved their parent back to India in 2024–2026 ahead of Indian IPOs. PhonePe reportedly paid ~₹8,000 Cr and Groww ~₹1,340 Cr in tax to do it. Since Sept 2024 a foreign parent can merge into its Indian wholly owned subsidiary via the fast-track (Section 233) route. Source: https://www.corporateprofessionals.com/articles/regulatory-boost-how-india-is-winning-back-its-startups-through-reverse-flipping/ (read 2026-10-01). **Lesson: flipping out is cheap today; flipping back later can be very expensive. Decide with a lawyer.**

**Tax note — forward flip today:** Because Talenfra has almost no value now, a flip done *now* (fresh US company, founders buy shares at par) usually creates little tax. The risk is if your existing proprietorship's **IP/code/customer contracts** are moved into the US company — that is a transfer of a valuable asset out of India (possible capital gains / transfer pricing / GST questions). **[CA MUST CONFIRM how to move the IP — usually an IP assignment to the new company, with a valuation.]**

**Also new:** India's **Income-tax Act, 2025 replaced the 1961 Act from 1 April 2026** (same policy, new section numbers). Old articles quoting "Section 47" / "56(2)(viib)" refer to the old Act. Source: https://taxguru.in/income-tax/income-tax-act-2025-force-1st-april-2026.html (read 2026-10-01).

### 1.3 Cost and time to incorporate (US)

| Service | Price | Includes | Time | Source |
|---|---|---|---|---|
| **Stripe Atlas** | $500 one-time; $100/yr registered agent from year 2 | Delaware C-corp, EIN, founder stock, 83(b) filing (for non-subsidiary setups), YC post-money SAFE templates; has a dedicated **Indian founders guide** with "Subsidiary" option for LLP-owned C-corps | Incorporated in ~2 business days; EIN without SSN can take weeks (15–45 business days per a secondary source, **UNVERIFIED**) | https://stripe.com/atlas ; https://docs.stripe.com/atlas/indian-founder-guide (read 2026-10-01) |
| **Clerky** | ~$427 pay-per-use or ~$819 lifetime package | Delaware C-corp, stock issuance, SAFEs, board consents | 2–3 business days | https://www.rho.co/blog/stripe-atlas-vs-clerky (secondary; **UNVERIFIED**) |
| **Cooley GO / law firm** | Free document generators; full firm cost varies | Cooley advises Atlas on India templates | — | https://docs.stripe.com/atlas/indian-founder-guide |

Plus Indian side: LLP formation (×2), AD bank ODI processing, CA fees. Not priced on official pages — **ask your CA for a quote**. Realistic total time for the India-compliant flip: several weeks (LLPs ~2 weeks + bank UIN + FC filing). **UNVERIFIED exact timing.**

Atlas also notes: Atlas fee itself is not an ODI and can be paid by card under **LRS** (up to **$250,000 per person per year**).

### 1.4 Founder equity split & vesting

- **Split:** Carta data — about **45.9% of two-founder teams split equally** (2024); many unequal splits are close (e.g. 55/45). Source: https://carta.com/data/founder-ownership/ ; https://carta.com/data/linkedin-cofounder-equity-split-vesting-debate/ (read 2026-10-01). Investors mostly care that the split is **fair, decided, written down, and both founders are full-time**.
- **Vesting:** Norm is **4 years with a 1-year cliff**, applied to founders too (5–6 years becoming more common per Carta). Accelerators and VCs expect founder vesting. Atlas' India templates include a stock purchase agreement with vesting.
- **IP assignment:** Every founder (and any freelancer who wrote code) must sign an **IP assignment / CIIAA** giving all Talenfra code, designs, brand, domain (talenfra.com), and prior work to the company. Diligence will check this. Since the code exists today under a sole proprietorship owned by one person, the proprietorship (Mohd Aqib) must assign it into the new company. **[LAWYER MUST DRAFT.]**
- **Cap table basics:** Keep a clean cap table from day one (Carta Launch is free under $1M raised per Stripe's guide; Pulley also). Track: founders' shares, vesting, option pool, each SAFE (amount, cap, discount, MFN), and who signed what.

### 1.5 83(b) election

- What it is: a US tax election saying "tax me now on my restricted (vesting) stock, at today's tiny value", so later vesting isn't taxed as income. Must be filed **within 30 days** of getting the shares; **no extensions**. Since Nov 2024 the IRS has **Form 15620**, and since mid-2025 it can be filed online (via ID.me — likely needs US identity; non-US founders usually file by mail, **UNVERIFIED**). Source: https://www.mintz.com/insights-center/viewpoints/2906/2025-07-29-new-electronic-filing-option-section-83b-elections ; https://www.withum.com/resources/essential-faqs-on-83b-election-for-non-u-s-taxpayers/ (read 2026-10-01).
- **Non-US founders:** Stripe says it matters most "for founders outside the US who file US tax returns or think they might become a US taxpayer in future" — i.e. if you move to the US (O-1, etc.), it can matter a lot. Atlas does **not** auto-file 83(b) for subsidiary (LLP-owned) setups; you must do it. In the LLP structure the *LLP* is the shareholder, which changes the analysis. **[US tax adviser MUST CONFIRM whether/how each of you files.]** Source: https://support.stripe.com/questions/faq-for-indian-founders-using-stripe-atlas

---

## 2. Deal terms (verified 2026-10-01)

### 2.1 Table

| Program | Money | What they get | Fee? | Format | Source |
|---|---|---|---|---|---|
| **Y Combinator** | **$500,000** | **$125K post-money SAFE for 7%** + **$375K uncapped SAFE with MFN** (takes the best cap of your next SAFE round; e.g. at a $15M post cap it ≈ 2.5%). Pro-rata rights. Invests the day you're accepted. | **No fees** | 3 months, in person, San Francisco | https://www.ycombinator.com/deal ; https://www.ycombinator.com/apply |
| **Techstars** | **$220,000** (Asia-Pacific programs: $120,000) | **$20K Convertible Equity Agreement → 5% common** (fixed %, converts at a priced round ≥ $1M, after SAFEs, incl. option pool) + **$200K uncapped MFN SAFE**. Side letter: pro rata, drag-along, info rights. | No fee mentioned | 3 months; e.g. NYC = hybrid (2 weeks in person at start, 1 mid, demo day); founders can be anywhere | https://www.techstars.com/investment-terms ; https://www.techstars.com/accelerators/new-york |
| **500 Global** | **"500 Fellowship": up to $50K right away, "potential for up to $1M more"** | Equity not stated on page | **Program fee $35,000 per startup for Phase 1** (excl. travel) | Nov 30 2026 – Apr 9 2027, SF; Batch 37 deadline **Oct 2 2026** | https://500.co/founders/flagship |
| 500 Global (older "Flagship" terms, widely quoted) | $150K for 6% (fees ~$37.5K netted) | — | Yes | 4 months | Secondary only — **UNVERIFIED / likely outdated** |
| **Antler India** | **Up to ₹4 Cr (~$470K) for 11%**; follow-on possible | Equity | Not stated | In-person AI Residency, Bangalore, ~3 weeks fast-track; ₹2L relocation grant; next residency "to be announced" | https://www.antler.co/india |
| **Entrepreneur First** | **$125K post-money SAFE for 8%** + optional **$125K uncapped MFN SAFE** (needs Delaware C-corp + SF move). £6,000 "Talent Investment" on signing (London). India: CCPS on equivalent terms. | Equity | No | London/Bangalore/SF; 12-week FORM then 12-week LAUNCH in SF | https://www.joinef.com/faqs/london/ ; https://www.joinef.com/illustrative-cap-tables |

Note: Antler says terms are set locally and vary by city — always read your city's term sheet.

### 2.2 What is a SAFE (simple version)

- **SAFE = Simple Agreement for Future Equity** (invented by YC). Investor gives cash now; gets shares later, when you raise a priced round (e.g. Seed/Series A).
- **Valuation cap:** the highest price at which the SAFE converts. Lower cap = more shares for the investor.
- **Post-money SAFE (YC's standard since 2018):** ownership is locked at signing = investment ÷ post-money cap. $125K at a cap that equals 7% means YC owns 7% before the priced round, no matter how many more SAFEs you sign. **Every new SAFE dilutes only the founders, not earlier SAFE holders.** Source: https://www.wilmerhale.com/en/insights/publications/20260414-giving-away-the-farm-with-safes (read 2026-10-01).
- **Uncapped MFN SAFE:** no cap of its own; if you later sign a SAFE with a cap (or discount), the MFN SAFE copies the best terms. So its % is decided by your *next* SAFE.
- **Discount:** sometimes a SAFE converts at, say, 20% below the round price.
- **Pro-rata right:** right to invest in later rounds to keep their %.
- Tip: Because post-money SAFEs stack on founders, use a SAFE calculator / spreadsheet before every SAFE you sign.

### 2.3 Dilution maths — 2 founders, 50/50, illustrative only

Start: Aqib 50%, Bushra 50%. (Real conversions have more detail — option pool timing, priced-round mechanics. Use these as rough guides only.)

**Scenario YC:**
1. YC $125K → 7% (post-money).
2. You later raise $1.5M on SAFEs at a $15M post-money cap → 10%. YC's $375K MFN SAFE copies the $15M cap → $375K / $15M = 2.5%.
3. Before the priced round: SAFE holders = 7% + 2.5% + 10% = 19.5%. Founders = **80.5% (≈ 40.25% each)**.
4. Priced Seed/Series A: sell 20% new + 10% new option pool → founders ≈ 80.5% × 0.70 = **56.4% (≈ 28.2% each)**.

**Scenario Techstars:**
1. $200K uncapped MFN → copies your next cap. Same $15M cap → $200K/$15M ≈ 1.33%.
2. $1.5M SAFEs at $15M → 10%.
3. CEA = fixed 5% after SAFEs convert (incl. pool).
4. Before new priced-round money: founders ≈ 100 − 1.33 − 10 − 5 = **≈ 83.7% (≈ 41.8% each)**, then diluted by the priced round like above.

**Scenario EF:** $125K for 8% fixed → founders 92% (46% each) before any other money; if you take the extra $125K MFN and later raise at a $15M cap → +0.83%.

**Scenario Antler India:** 11% for up to ₹4 Cr → founders 89% (44.5% each) before other money.

Key point for you: **the % at the accelerator is less important than the next round's cap.** A good accelerator usually lifts your next cap a lot. EF publishes a worked example: https://www.joinef.com/illustrative-cap-tables

---

## 3. Visas (US first, then alternatives)

### 3.1 US options for Indian founders

| Visa | Fits for | Notes for Indians in 2026 | Source |
|---|---|---|---|
| **B-1 (business visitor)** | Attending a short program, meetings, demo day, fundraising | Most common for attending YC as a batch member. You cannot take a US salary/do productive "work" for a US employer on B-1. **[Immigration lawyer must confirm what you may do on B-1.]** Interview needed in India (waivers ended for most from **2 Sept 2025**). | https://www.tryalma.com/learn/best-visa-options-yc-company-founders (secondary); https://www.brownwinick.com/insights/visa-interview-waiver-rollback-most-applicants-must-interview-starting-september-2-2025 |
| **O-1A (extraordinary ability)** | Founders after an accelerator/fundraise | Common next step after YC per attorneys; evidence = press, funding from top investors, judging, high salary, critical role, etc. No lottery, no cap. | same as above (secondary) |
| **H-1B** | Employee of a US company | **$100,000 fee** for new petitions for people outside the US (from 21 Sept 2025); **extended by proclamation of 18 Sept 2026 through 21 Sept 2027**. A July 2026 First Circuit order had barred USCIS from collecting it; litigation continues. Also a new weighted lottery. Founders owning the company face extra "employer-employee" issues. **Not practical for you now.** | https://www.mintz.com/insights-center/viewpoints/2806/2026-09-23-presidential-proclamation-extends-100k-h-1b-fee |
| **E-2 (treaty investor)** | Treaty-country nationals | **Not available to Indian nationals** — India has no E-2 treaty. | https://www.lighthousehq.com/blog/e2-treaty-countries (secondary; matches State Dept treaty list) |
| **J-1** | Exchange/training programs | Not a normal accelerator route; only via a sponsoring program. **UNVERIFIED for any specific accelerator.** | — |
| **International Entrepreneur Parole (IER)** | Founders with ≥10% ownership and ≥ ~$311K from qualified US investors (or ~$124K in govt grants) | **Still listed as available** on USCIS; up to 2.5 + 2.5 years. Thresholds effective 1 Oct 2024. (DHS tried to scrap it in 2018; did not.) Slow and rarely used. | https://www.uscis.gov/working-in-the-united-states/international-entrepreneur-rule |

**Other recent US changes:**
- **$250 "Visa Integrity Fee"** in the July 2025 One Big Beautiful Bill Act for most non-immigrant visas incl. B-1/B-2. As of the latest reports I found (March 2026) it was **not yet being collected**; status on 2026-10-01 **UNVERIFIED**. Source: https://www.beyondborderglobal.com/resources/visa-integrity-fee-2026
- **Interview waivers ended** for most categories from 2 Sept 2025; must apply in country of nationality/residence → expect long B-1/B-2 appointment waits in India. Plan visa timing **as soon as you're accepted**.

**What accelerators actually provide:**
- **YC:** "we'll connect you with immigration attorneys who will work with you to come up with a plan"; "in most cases, yes" visa holders can participate. Batch is **in person in SF** (3-day kickoff retreat, weekly events). YC does not issue visas. Source: https://www.ycombinator.com/faq
- **Techstars NYC:** hybrid; only some weeks in person; founders "can be based anywhere". Fewer visa days needed. Source: https://www.techstars.com/accelerators/new-york
- **EF:** "We do not provide visas... in many circumstances, we can offer support to help you apply." Source: https://www.joinef.com/faqs/london/
- **500 Fellowship:** must be in US or plan to be within 6 months. Source: https://500.co/founders/flagship
- **Antler India:** Bangalore in-person — no visa needed for you.

### 3.2 Alternatives outside the US

| Country | Route | Status 2026 | Source |
|---|---|---|---|
| **UK** | **Innovator Founder visa** | Live. Need endorsement from an approved body (£1,000 endorsement + £500 per checkpoint meeting); visa fee £1,357 from outside UK + health surcharge; 3 years; settlement possible after 3 years; can do other skilled work. Old £50,000 minimum investment no longer applies. Endorsing-body list changed several times in 2026 (Feb, Mar, Apr, Aug updates). | https://www.gov.uk/innovator-founder-visa ; https://www.gov.uk/government/publications/endorsing-bodies-innovator-founder-and-scale-up-visas |
| **Canada** | Start-up Visa (SUV) | **CLOSED** to new applications after 31 Dec 2025 (narrow exception to 30 June 2026 for 2025 commitment certificates). A replacement "targeted pilot" was promised for 2026 — **details UNVERIFIED as of 2026-10-01**. | https://www.cicnews.com/?p=63770 ; https://betakit.com/?p=398456 |
| **Singapore** | **EntrePass** | Live. Singapore Pvt Ltd, you hold ≥30%; meet one "innovative" criterion, e.g. ≥ SGD 100K from a recognised VC, **or backing by a recognised accelerator such as Y Combinator**, or IP, or research tie-up. Note: Singapore is also on YC's approved incorporation list. | https://www.mom.gov.sg/passes-and-permits/entrepass/eligibility |
| **Estonia** | Startup Visa | Live; startup assessed by Startup Committee; secondary sources say fast and cheap. **UNVERIFIED details.** | https://www.roundfunded.com/en/visa/estonia (secondary) |
| **Netherlands** | Startup visa (1 year) | Needs a recognised facilitator. **UNVERIFIED details.** | https://relocate.me/visas/netherlands/startup-visa (secondary) |
| **France** | French Tech Visa (4 years, renewable) | Founders need support from a recognised incubator/accelerator. **UNVERIFIED details.** | https://lafrenchtech.com/en/how-france-helps-startups/french-tech-visa/ |

---

## 4. India-specific: FEMA, RBI, tax, DPIIT, GST

### 4.1 ODI / LRS — owning a US parent as an Indian resident
- **Who it applies to:** FEMA residents (in India >182 days in previous financial year). Source: https://docs.stripe.com/atlas/indian-founder-guide
- **Rules:** Foreign Exchange Management (Overseas Investment) Rules & Regulations 2022 + RBI Master Directions. Resident individuals may make ODI in an operating foreign company **with no subsidiary if they have control** (control = ≥10% voting rights or board/management control). Since a flip means the US company *will* own an Indian subsidiary, individuals holding it directly is the problem → hence LLP route. Source: https://www.livelaw.in/law-firms/law-firm-articles-/overseas-investment-financial-services-centre-overseas-portfolio-investment-mutual-funds-208278 ; https://mondaq.com/india/financial-services/1286750/new-overseas-investment-regulations-and-rules
- **LRS:** up to $250,000 per person per year can be sent abroad. Source: Stripe India FAQ.
- **Penalties for getting it wrong** are real (compounding with RBI). **[FEMA lawyer + CA ESSENTIAL — do not DIY this step.]**

### 4.2 How accelerator money is received
- **YC/Techstars (US):** money goes into the **US parent's US bank account** (Mercury/Brex/SVB etc.). To spend in India, the US parent invests into (or pays service fees to) the Indian subsidiary → FDI reporting (FC-GPR within 30 days of allotment) or export-of-services invoices from India sub to US parent (transfer pricing). **[CA MUST DESIGN.]**
- **Antler India / EF India:** invest directly into an **Indian Pvt Ltd** (equity or CCPS). Foreign investor money into an Indian company = FDI → valuation report (FEMA pricing) + FC-GPR. Since 1 April 2025, **angel tax (old s.56(2)(viib)) is abolished** for all investors. Source: https://india-briefing.com/news/abolishing-the-angel-tax-in-india-applicable-for-fy-2025-26-35289.html
- **You cannot receive equity investment into a sole proprietorship.** You need a Pvt Ltd (or the US company) first.

### 4.3 Startup India / DPIIT recognition
- Eligible entities: **Private Limited Company, registered Partnership Firm, LLP, or Cooperative Society.** **Sole proprietorships are NOT eligible.**
- Age ≤ 10 years (20 for DeepTech); turnover **below ₹200 crore** in every year (₹300 Cr DeepTech) — the official page now shows these higher limits (older blogs say ₹100 Cr).
- Must work on innovation/improvement with potential for jobs or wealth; can't be formed by splitting/reconstructing an existing business. **[CA to confirm whether converting your proprietorship counts as "reconstruction".]**
- Benefits: self-certification for some labour/environment laws, IPR fee rebates (80% patents / 50% trademarks per secondary sources), possible 100% profit tax holiday for 3 of first 10 years (old s.80-IAC — needs separate IMB certificate; partnership firms not eligible).
- Source: https://www.startupindia.gov.in/content/sih/en/startupgov/startup_recognition_page.html (read 2026-10-01); benefits from https://www.patronaccounting.com/blog/dpiit-startup-recognition-2026-benefits-eligibility-application-tax (secondary).

### 4.4 GST on your current services income (sole proprietorship)
- Services to foreign clients are **"export of services" (zero-rated)** only if all 5 conditions in **Section 2(6) IGST Act** hold: supplier in India, recipient outside India, place of supply outside India, payment in convertible foreign exchange (or INR where RBI allows), and not two branches of the same entity.
- Export under **LUT (Letter of Undertaking)** = no IGST charged; LUT renewed every financial year.
- GST registration threshold for services: **₹20 lakh** aggregate turnover (₹10 lakh in special-category states). Exports count toward turnover. **[CA MUST CONFIRM if you need registration now.]**
- Domestic (Indian) clients: 18% GST once registered.
- Source: https://razorpay.com/blog/export-services-gst-conditions-guide/ ; https://www.skydo.com/blog/export-of-services-under-gst (secondary, read 2026-10-01).
- After a flip, if the Indian subsidiary bills the US parent, that can also be export of services — but watch the "distinct persons / establishments" condition. **[CA MUST CONFIRM.]**

### 4.5 Where a CA/lawyer is essential (India)
1. Converting proprietorship → Pvt Ltd/LLP and moving IP/contracts.
2. Any ODI/flip (LLP setup, AD bank, UIN, Form FC, APR, FLA).
3. FDI receipt (valuation, FC-GPR), CCPS terms for EF/Antler.
4. Transfer pricing between US parent and Indian sub.
5. GST LUT/registration and income-tax residency (especially if one of you moves abroad mid-year).
6. US taxes: 83(b), Delaware franchise tax, Form 1120/5472.

---

## 5. Legal/compliance risks investors will diligence (AI CV screening)

Talenfra screens CVs = processes candidates' personal data for recruiters in US/UK/EU/AU. Investors will see this as **high-regulatory-risk** and will want evidence you've handled it.

### 5.1 EU / UK data protection
- **GDPR / UK GDPR:** your recruiter clients are usually the **controller**, Talenfra the **processor** → need an **Art. 28 DPA** with every client.
- **Transfers to India:** India has no EU/UK adequacy decision → use **EU Standard Contractual Clauses (2021)** for EU data; for UK data use the **UK IDTA** or the **UK Addendum to EU SCCs**. Plus a transfer impact assessment. Source: https://cy.ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/international-transfers/international-data-transfer-agreement-and-guidance (read 2026-10-01).
- **Sub-processors in the US** (Anthropic, Google, hosting): EU-US **Data Privacy Framework** survived the Latombe challenge at the EU General Court (3 Sept 2025); an appeal to the CJEU is pending. Source: https://iapp.org/news/a/european-general-court-dismisses-latombe-challenge-upholds-eu-us-data-privacy-framework ; https://www.wilmerhale.com/en/insights/blogs/wilmerhale-privacy-and-cybersecurity-law/20251201-european-court-of-justice-to-review-challenge-to-eu-us-data-privacy-framework
- **UK Data (Use and Access) Act 2025:** amends UK GDPR (incl. automated decision-making rules); phased in June 2025–June 2026. Source: https://www.gov.uk/guidance/data-use-and-access-act-2025-data-protection-and-privacy-changes
- **GDPR Art. 22** (solely automated decisions with significant effects) — keep a **human in the loop** (your approve/verify flow helps).
- **[Privacy lawyer MUST CONFIRM which SCC module and whether your India hosting vs Oracle/US hosting changes it.]**

### 5.2 EU AI Act
- AI systems used for **recruitment/selection (e.g. filtering applications, evaluating candidates)** are **Annex III high-risk**.
- **New date:** the **Digital Omnibus on AI (Regulation (EU) 2026/1744)**, in force 27 July 2026, moved stand-alone Annex III high-risk obligations from 2 Aug 2026 to **2 December 2027**. Obligations themselves are unchanged (risk management, data governance, technical documentation, logging, human oversight, accuracy/robustness, conformity assessment, registration; deployers: transparency, informing workers). Source: https://cdp.cooley.com/digital-ai-omnibus-delays-key-deadlines-introduces-new-rules/ ; https://www.cuatrecasas.com/en/global/labor-and-employment/art/digital-omnibus-on-ai-how-does-it-impact-employment-relations (read 2026-10-01).
- AI literacy duties and prohibited-practices rules already apply since Feb 2025. **[Lawyer to confirm your role: you are likely the "provider".]**

### 5.3 US
- **NYC Local Law 144 (AEDT):** employers/agencies using automated tools for NYC candidates need an **independent annual bias audit**, public summary, and **10 business days' notice** to candidates. NY State Comptroller (Dec 2025) found enforcement "ineffective"; DCWP agreed to step up proactive enforcement in 2026. Source: https://www.dlapiper.com/insights/publications/2026/01/critical-audit-of-nyc-ai-hiring-law-signals-increased-risk-for-employers
- **Illinois HB 3773** (amends Human Rights Act): from **1 Jan 2026**, bans discriminatory AI use in hiring and requires **notice** when AI is used. Also older Illinois AI Video Interview Act (video only). Source: https://www.fisherphillips.com/en/news-insights/illinois-employers-using-ai-workplace-purposes-need-provide-notice-quick-takeaways-things-to-prepare.html
- **Colorado:** the 2024 Colorado AI Act (SB 24-205) never took effect; it was **repealed and replaced by SB 189** (passed 12 May 2026), effective **1 Jan 2027** — narrower ADMT law: developers give deployers a statement of intended/harmful uses, training data categories, limits; deployers give pre-use notice, post-adverse-decision notice within 30 days, 3-year records, right to correct data and to **meaningful human review**. Source: https://www.troutmanprivacy.com/2026/05/colorado-legislature-passes-bill-to-repeal-and-replace-colorado-ai-act/
- **California:** FEHA regulations on automated-decision systems **in force since 1 Oct 2025** (bias testing, 4-year records, vendor/agent liability). CCPA ADMT regulations: compliance for significant decisions from **1 Jan 2027**; risk assessments from 1 Jan 2026 (attestations by 1 Apr 2028). Source: https://www.mcdermottlaw.com/insights/californias-new-ai-rules-under-feha-take-effect-october-1-2025/ ; https://www.sheppard.com/insights/blogs/california-finalizes-new-ccpa-rules-on-admt-cybersecurity-audits-and-risk-assessments
- Federal anti-discrimination law (Title VII, ADA) still applies to the employer; vendor contracts will push liability onto you.

### 5.4 India — DPDP Act 2023 + DPDP Rules 2025
- Rules notified **13 Nov 2025**; phased: consent-manager rules ~Nov 2026; **core duties (notice, consent, security safeguards, 72-hour breach reporting, retention/erasure, processor contracts) from ~13 May 2027**. Source: https://www.hoganlovells.com/en/publications/indias-digital-personal-data-protection-act-2023-brought-into-force- (read 2026-10-01).
- Mostly relevant if you process data of people in India, or as an Indian processor (DPDP applies to processing in India). **[Lawyer to confirm how DPDP applies to foreign candidates' data processed in India.]**

### 5.5 Australia
- Privacy Act 1988 (APPs) — Privacy and Other Legislation Amendment Act 2024 added automated-decision transparency duties (from Dec 2026, **UNVERIFIED date**). **[Lawyer to confirm.]**

### 5.6 Candidate consent / notice
- In GDPR land, consent is usually not the best lawful basis for employers; recruiters rely on legitimate interests + transparency notices. But NYC/Illinois/Colorado require **notice**, and some require **alternative process / human review on request**. Give your clients a ready-made **candidate notice template** and an **opt-out / human review** path.

### 5.7 What an investor expects to see (checklist)
- Signed **DPA template** + sub-processor list + SCC/IDTA pack (you already have a DPA template with FILL slots — finish it).
- **Privacy policy + Terms** (you have lawyer-approved versions — good).
- **Security posture:** encryption at rest/in transit, access control, audit logs, retention/erasure, incident response plan, pen-test or security review (you've done SR-1..SR-21 — summarise it in a 1-page "security overview").
- **SOC 2:** not legally required, but US enterprise/recruiter buyers often ask. At pre-seed, investors accept "SOC 2 roadmap" + tools like Vanta/Drata; Type I first, Type II later. ISO 27001 is the UK/EU equivalent. (General market knowledge — **UNVERIFIED with a single official source**.)
- **Bias testing / model documentation:** a short "how Talenfra scores, what it doesn't use (protected attributes), human-in-the-loop, bias test method" doc — this is your AI Act + LL144 + Colorado story in one page.
- **IP chain:** IP assignment from the proprietorship and both founders to the company.
- **Clean cap table** and founder vesting.

---

## 6. Application mechanics (common to all)

### 6.1 YC specifics (official)
- **Founder video:** **1 minute**, "nothing except the founders talking", **all founders in it** (screen-record a video call if apart). Introduce yourselves, what you're doing and why. **Not** a demo. **Don't read a script** — use bullet points and talk naturally. Source: https://www.ycombinator.com/video/
- **Demo:** separate place in the application; keep it short (a 1–3 minute screen recording is common practice, **UNVERIFIED official length**).
- **Interview:** **10 minutes on Zoom**, all founders, 2–3 partners; no slides, no small talk — rapid questions + look at what you've built. Decisions usually the same day. Source: https://www.ycombinator.com/apply ; https://ycombinator.com/interviews (page content summarised via search, read 2026-10-01).
- **Writing advice (Paul Graham's "How to Apply"):** be clear and matter-of-fact; put the answer in the first sentence; no marketing-speak; show specific impressive things you've done; show you understand the obstacles; admit flaws. Source: https://www.ycombinator.com/howtoapply

### 6.2 Typical questions (YC-style; others are similar)
- Describe what your company does in 50 characters or less.
- What are you making? Why this? What do you understand that others don't?
- Who are your competitors? How will you make money? How big can this be?
- How far along are you? Users / revenue / growth? How long have you worked on it?
- Founders: who writes code? Impressive things each founder has built/done? How did you meet? Full-time?
- Equity split; any previous investment; incorporated? where?

### 6.3 Metrics to show (pre-revenue B2B SaaS)
- Pilots/LOIs from recruiting firms; number of CVs screened in real use; time saved per role; recruiter-measured accuracy vs their own shortlist; weekly active recruiter users; pipeline of paying customers; any paid pilot (even small) is far stronger than "interest".
- Show week-over-week growth if you have any.

### 6.4 Common rejection reasons (from YC's own advice + general)
- Unclear description; vague market claims; no evidence founders can build/sell; founders not full-time; no users; "solution looking for a problem"; crowded market with no insight; co-founder conflict signals; equity/commitment unclear.

### 6.5 Interview prep
- Practise 1-sentence answers; have the live product ready to screen-share; know your numbers cold; both founders should speak; prepare "why you two", "why now", "biggest risk", "who is the user and how do you get the next 10 customers", "what about bias/regulation" (expect this one for AI hiring).

---

## 7. Pitfalls: fake / pay-to-play accelerators

**Red flags** (sources: https://www.openvc.app/blog/vc-scams ; https://latamlist.com/the-new-wave-of-startup-scams-what-founders-need-to-watch-out-for/ ; read 2026-10-01):
- Charges an application fee, "pitch fee", "coaching fee" or "sponsorship" to pitch to investors.
- Charges a program fee **and** takes equity (note: 500 Fellowship now has a $35K fee — legitimate firm, but weigh it).
- VC logos used without permission; unnamed mentors; no verifiable alumni; alumni won't talk to you.
- High-pressure deadlines to pay; "guaranteed funding".
- No real due diligence before "accepting" you.
- Big emphasis on fancy office space, little on investor outcomes.

**How to judge quality:**
- Who are the alumni and what did they raise after? Check Crunchbase/LinkedIn.
- Talk to 3+ founders from recent batches (pick some yourself, not only ones they give you).
- Demo day attendance — which named investors actually attend?
- Money terms: equity % vs cash; any fee; side letter rights.
- Partner quality: have they built/scaled companies?
- General rule: **real accelerators pay you, you don't pay them.** Only acceptable founder costs are your own travel and your own legal fees at closing.

---

## 8. Other important things for an India-based, 2-founder, pre-revenue team (next 3–9 months)

- **Deadlines (verified 2026-10-01):**
  - **YC Winter 2027:** on-time deadline **2 Nov 2026, 8pm PT**; decisions by **11 Dec 2026**; batch Jan–Mar 2027 in SF. Late applications are still read. You can also apply now for future batches (Spring/Summer/Fall) via "Early Decision". YC now runs **4 batches a year**. Source: https://www.ycombinator.com/apply
  - **Techstars NYC:** final deadline **18 Nov 2026**; program 8 Mar – 3 Jun 2027. Each Techstars program has its own deadlines. Source: https://www.techstars.com/accelerators/new-york
  - **500 Fellowship Batch 37:** deadline **2 Oct 2026** (tomorrow). Source: https://500.co/founders/flagship
  - **Antler India:** next residency "to be announced". **EF:** cohort-based, check apply.joinef.com.
- **Reapplying is normal:** ~half of YC companies applied more than once; YC likes to see progress between applications. Source: https://www.ycombinator.com/faq
- **Solo founder bias:** YC accepts solo founders but says two founders are better — you are two, which helps. EF accepts individuals, so **each of you applies separately** and both are not guaranteed.
- **Exclusivity:** Techstars wants full-time exclusivity (no other job/study). YC wants full-time founders. Both of you should be full-time before applying (or say clearly when you will be).
- **Timing vs first customers:** a paid pilot or LOI before the Nov deadlines makes the application much stronger. Apply on time anyway; update via the application if you get traction later.
- **Don't let the agency side confuse the story:** Talenfra has both "agency services" and a "product/engine". Accelerators fund scalable products — pitch the software, mention services revenue as early proof of demand.
- **Visa lead time:** US B-1 appointments in India can take a long time; once accepted, get YC's immigration lawyer on it on day one. Make sure passports are valid >6 months.
- **Founder agreement now:** even before a company exists, sign a simple founders' agreement (split, vesting, roles, IP, what happens if one leaves). **[Lawyer to draft.]**
- **Keep IP clean now:** all code under one owner, no unlicensed assets, open-source licences tracked.
- **Taxes on residency:** if you spend 3+ months in the US/UK in a year, Indian and foreign tax residency can change. **[CA MUST CHECK before travel.]**

---

## 9. Source list (all read 2026-10-01)

Official / primary:
- YC deal — https://www.ycombinator.com/deal
- YC FAQ — https://www.ycombinator.com/faq
- YC apply/deadlines — https://www.ycombinator.com/apply
- YC how to apply (PG) — https://www.ycombinator.com/howtoapply
- YC video — https://www.ycombinator.com/video/
- YC interviews — https://ycombinator.com/interviews
- Techstars terms — https://www.techstars.com/investment-terms
- Techstars NYC — https://www.techstars.com/accelerators/new-york
- 500 Fellowship — https://500.co/founders/flagship
- Antler India — https://www.antler.co/india
- EF FAQ — https://www.joinef.com/faqs/london/ ; https://www.joinef.com/illustrative-cap-tables
- Stripe Atlas — https://stripe.com/atlas ; https://docs.stripe.com/atlas/indian-founder-guide ; https://support.stripe.com/questions/faq-for-indian-founders-using-stripe-atlas
- RBI OI Rules 2022 — https://rbi.org.in/scripts/Bs_viewcontent.aspx?Id=5087
- Startup India recognition — https://www.startupindia.gov.in/content/sih/en/startupgov/startup_recognition_page.html
- USCIS IER — https://www.uscis.gov/working-in-the-united-states/international-entrepreneur-rule
- UK Innovator Founder — https://www.gov.uk/innovator-founder-visa
- Singapore EntrePass — https://www.mom.gov.sg/passes-and-permits/entrepass/eligibility
- UK DUAA guidance — https://www.gov.uk/guidance/data-use-and-access-act-2025-data-protection-and-privacy-changes
- ICO IDTA — https://cy.ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/international-transfers/international-data-transfer-agreement-and-guidance

Law firm / reputable secondary:
- Mintz (H-1B fee extension) — https://www.mintz.com/insights-center/viewpoints/2806/2026-09-23-presidential-proclamation-extends-100k-h-1b-fee
- Mintz (83(b) e-filing) — https://www.mintz.com/insights-center/viewpoints/2906/2025-07-29-new-electronic-filing-option-section-83b-elections
- Withum (83(b) non-US) — https://www.withum.com/resources/essential-faqs-on-83b-election-for-non-u-s-taxpayers/
- WilmerHale (SAFEs) — https://www.wilmerhale.com/en/insights/publications/20260414-giving-away-the-farm-with-safes
- Cooley (AI Omnibus) — https://cdp.cooley.com/digital-ai-omnibus-delays-key-deadlines-introduces-new-rules/
- Cuatrecasas (AI Omnibus & employment) — https://www.cuatrecasas.com/en/global/labor-and-employment/art/digital-omnibus-on-ai-how-does-it-impact-employment-relations
- Troutman (Colorado SB 189) — https://www.troutmanprivacy.com/2026/05/colorado-legislature-passes-bill-to-repeal-and-replace-colorado-ai-act/
- DLA Piper (NYC LL144 audit) — https://www.dlapiper.com/insights/publications/2026/01/critical-audit-of-nyc-ai-hiring-law-signals-increased-risk-for-employers
- Fisher Phillips (Illinois) — https://www.fisherphillips.com/en/news-insights/illinois-employers-using-ai-workplace-purposes-need-provide-notice-quick-takeaways-things-to-prepare.html
- McDermott (California FEHA) — https://www.mcdermottlaw.com/insights/californias-new-ai-rules-under-feha-take-effect-october-1-2025/
- Sheppard (CCPA ADMT) — https://www.sheppard.com/insights/blogs/california-finalizes-new-ccpa-rules-on-admt-cybersecurity-audits-and-risk-assessments
- Hogan Lovells (DPDP Rules) — https://www.hoganlovells.com/en/publications/indias-digital-personal-data-protection-act-2023-brought-into-force-
- IAPP (DPF) — https://iapp.org/news/a/european-general-court-dismisses-latombe-challenge-upholds-eu-us-data-privacy-framework
- Brown Winick (interview waiver rollback) — https://www.brownwinick.com/insights/visa-interview-waiver-rollback-most-applicants-must-interview-starting-september-2-2025
- CIC News / BetaKit (Canada SUV closure) — https://www.cicnews.com/?p=63770 ; https://betakit.com/?p=398456
- BetaKit (YC Canada reversal) — https://betakit.com/y-combinator-reverses-decision-will-invest-in-canadian-domiciled-startups-again
- Carta (founder ownership) — https://carta.com/data/founder-ownership/
- Corporate Professionals (reverse flip) — https://www.corporateprofessionals.com/articles/regulatory-boost-how-india-is-winning-back-its-startups-through-reverse-flipping/
- India Briefing (angel tax) — https://india-briefing.com/news/abolishing-the-angel-tax-in-india-applicable-for-fy-2025-26-35289.html
- TaxGuru (Income-tax Act 2025) — https://taxguru.in/income-tax/income-tax-act-2025-force-1st-april-2026.html

Lower-confidence secondary (used only where marked UNVERIFIED): rho.co (Clerky prices), lighthousehq.com (E-2), tryalma.com (YC visas), beyondborderglobal.com (visa integrity fee), razorpay/skydo (GST), incorpx.io (FC-GPR), openvc/latamlist (scams), roundfunded/relocate.me (EU startup visas).
