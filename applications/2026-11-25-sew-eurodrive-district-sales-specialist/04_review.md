# 04 Review — SEW-EURODRIVE, District Sales Specialist - Iowa

Reviewed: 11-25-2026 (blind, fresh agent). Inputs: `00_posting.md`, `03_draft.md` (resume text only, Fit note ignored), `_shared/voice.md`, `_shared/ats.md`; `_shared/fact-bank.md` loaded only for section 4.

**Stage Check status: FAIL.** AI-tell score passes (3, target 4 or lower). Truth-check has 7 open items (3 Not found, 4 stronger than the fact) that block stage 05 until fixed or confirmed by Tobi.

---

## 1. AI-tell check

**Score: 3 / 10** (mostly human; a few template habits)

### Lines that read machine-written
- **"Territory growth:" / "Reducer reliability:" / "Largest order:"** — a bold lead-in on every Career Highlight. voice.md: "Identical bullet shapes or bold lead-ins on every bullet." Three for three looks templated.
  - Rewrite: drop the labels and let the first words carry it. "Grew territory sales from under $500,000 in 2016 to about $3 million..." / "Stopped repeat gear reducer failures at a gypsum plant..." / "Largest order: ..." can stay as the one label if you want one.
- **Summary "Manages about 75 active accounts..." vs. bullet "Manage about 75 active accounts as day-to-day contact..."** — near-identical sentence in two places. voice.md allows repeating a number, not a sentence.
  - Rewrite the bullet: "Day-to-day contact for maintenance, planning, parts and purchasing staff across about 75 active accounts."
- **"then grows them by sizing and specifying gear reducers, motors and drives."** — echoes the headline "GEAR REDUCERS, MOTORS AND DRIVES" word for word, and the three-item list reads as rhythm. (Also a truth issue, see section 4.)
- **"Quoted, sourced and expedited orders for the outside sales team."** — clean rule-of-three opener; reads like a job-description template. (Also a truth issue.)
- **"TOBI HUEBBE — PAGE 2 OF 2"** — the only em dash in the resume text. voice.md bans em dashes in body text.
  - Rewrite: "Tobi Huebbe | Page 2 of 2" (or put it in the PDF running header).
- **"Technical Problem Solving"** (Areas of Expertise) — generic filler next to otherwise concrete items.
  - Rewrite: cut it; "Drive Sizing and Application Data" already proves it.
- **"...replaced a quoted $23,000+ gearbox and bearing job and avoided a crane."** — mild punchline ending. Acceptable because it is concrete trade detail, and "the territory's largest account at about $300,000 a year" ends the next bullet the same way. Two punchlines in a row on page 1 is the limit; don't add a third.

### What reads human (keep)
- "$363,000 roll-neck bearing order", "16-inch rack-and-pinion", "5 HP helical-bevel gearmotor", "tons per hour".
- "Traced a bucket elevator vibration everyone blamed on the gearbox to a worn head sprocket."
- "labeled bins, minimums, and count and reorder forms" — that is plant-floor detail nobody invents.
- "Iterated the design and have sold three so far." Honest small number.
- "Covered inside sales and the warehouse at the same time after the warehouse lead retired."
- Odd specific numbers: 53%, nine accounts, about $72,000, about 16%.
- No banned words found (spearheaded, leveraged, robust, results-driven, etc.). No "I" in bullets. No slogan opener.

---

## 2. ATS check

### Keyword coverage (stage-04 mode of extract-keywords)
High weight (title, first paragraph, or repeated 2+ times):
1. District Sales Specialist — high (title) — **Missing.** Don't claim the title; acceptable miss.
2. gear reducers — high (first paragraph, qualifications) — **Present** (Highlights, Expertise, Skills).
3. electric motors — high (first paragraph, qualifications) — **Present** (Expertise, Skills).
4. variable frequency drives — high (first paragraph, qualifications) — **Present** (Expertise, bullet, Skills, Education).
5. motion control solutions / motion controllers — high (first paragraph, qualifications) — **Missing.** Only "encoder for position feedback" and "encoders" are near it.
6. drive technology — high (first paragraph) — **Variant** ("Drives:", "Drive Sizing", "Energy-Efficient Drive Retrofits").
7. Outside Sales — high (qualifications, implied throughout) — **Present** (job title, summary).
8. territory — high (repeated 4+ times) — **Present.**
9. relationships ("develop and maintain strong relationships", "develop and nurture relationships") — high (repeated 3+ times) — **Missing.** The word never appears.
10. revenue growth / generate revenue / increase sales — high (repeated 3 times) — **Variant** ("Territory growth", "Grew territory sales", "up 35%"). Neither "revenue" nor "increase sales" appears.
11. technical and commercial solutions — high (role bullets) — **Variant** ("Technical Problem Solving", "plant-floor problem solving").
12. sales support / technical support — high (role bullets + tasks) — **Variant** ("post-sale support").

Medium weight (requirements and tasks):
13. OEMs, Users, Distributors, Resellers — **Present** for OEM ("OEM and MRO Sales"); Distributors **Variant** ("Distributor Operations", "power transmission distributor").
14. CRM — **Present** ("CRM and Pipeline Tracking (Epicor P21)", "Epicor P21 (CRM...)").
15. Microsoft Office — **Present.**
16. qualify and develop sales leads — **Present** ("Prospecting and Lead Qualification").
17. sales calls / face-to-face — **Variant** ("cold calling", "first prospecting call").
18. sales strategies and programs — **Variant** ("consignment program").
19. training for customers — **Variant** ("manufacturer-led customer trainings").
20. associate degree in engineering — **Present** ("A.S., Engineering").
21. Industrial Distribution — **Variant** ("industrial power transmission distributor").
22. new and existing customers — **Variant** ("Opened nine accounts", "Manage about 75 active accounts").
23. major markets and industries — **Variant** (industry list in summary).
24. mathematical and computer skills — **Variant** (Excel sizing tools with VBA, Fusion 360).
25. Iowa (Des Moines / Cedar Rapids) — **Present** for Iowa; Des Moines/Cedar Rapids Missing (location is fine as is).
26. overnight travel / tradeshows — low-medium — **Missing.**

Low (boilerplate): power transmission — **Present**; industrial applications — **Variant**.

**Coverage (Present ÷ high-weight): 5 / 12 = 42%.** Below the 70% target. Present + Variant = 10 / 12.
Reachable truthfully with wording only (no new facts): "relationships", "increase sales", "technical solutions", "sales support" are all supportable from lines already on the page, which takes it to about 9 / 12 (75%). The two that stay Missing are the title (don't claim it) and motion control (needs a fact).

### ats.md "Don't" list
- Column grids / tables for keywords: none. Areas of Expertise is one " | " paragraph, 14 items (within 12–16). Pass.
- Icons, glyphs, photos, logos, text boxes: none in the text. Pass (confirm in the PDF render).
- Graduation year, GPA, high school: none. Pass.
- Street address, family status, salary: city/state only. Pass.
- Employment-type labels: none. Pass.
- Gap explanations: none. Pass.
- Old jobs: none. Pass.
- Section names: standard, except **"PROFESSIONAL EXPERIENCE, CONTINUED"** — some parsers start a new, unknown section on it. Low risk; safer to omit the heading and let the Inside Sales job header follow, or keep it in the PDF running header only.
- **"TOBI HUEBBE — PAGE 2 OF 2"** sits in the body text flow; a parser may read it as a second name/contact block. Put it in a real PDF header/footer or drop it.
- Dates: months on all job dates. Pass.

### Missing keywords Tobi might truthfully claim (gap questions, not edits)
- Motion controllers or servos: has he sold, specified or set up any? (Encoder work is close but not the same.)
- Overnight travel and tradeshows: willing / done? (Only matters if he wants it on the page; the posting lists it as a task, not a qualification.)
- Customer training he delivered himself, not set up for a manufacturer.

---

## 3. Recruiter screen (no fact bank)

### Requirements graded
- Located in Iowa, pref. Des Moines or Cedar Rapids — **Strong.** "West Branch, IA" (Cedar Rapids area; recruiter may need to look it up).
- Gear reducers — **Strong.** Gypsum reducer life "about six months to more than six years"; "5 HP helical-bevel gearmotor"; "worm gearbox with a helical-bevel reducer"; "select gearbox and motor combinations."
- Electric motors — **Partial.** Only as part of gearbox/motor combos and "the motor with a higher-efficiency model." No motor-only win.
- Variable frequency drives — **Partial.** One clause: "also size and sell variable frequency drives, including SEW-EURODRIVE units," plus "WEG variable frequency drive training." No count, application or result. The SEW mention will get asked about.
- Motion controllers — **Missing.**
- Driver's license / travel / frequent customer visits — **Partial** (implied by 10 years of outside territory sales; not stated, and that's normal).
- Organizational and communication skills — **Partial.** "rebuilt it with labeled bins, minimums, and count and reorder forms"; "Set up about six ... customer trainings"; "mentor newer outside reps."
- Math and computer skills, Microsoft Office — **Strong.** "Excel sizing and pricing tools with VBA", "Fusion 360 CAD", "Microsoft Office".
- Associate degree in engineering — **Strong.** "A.S., Engineering."
- 2 years outside sales — **Strong.** "April 2016 – Present."
- Generate revenue / increase sales — **Strong.** "under $500,000 in 2016 to about $3 million"; "up 35% in the last year."
- Develop relationships with prospective and current accounts — **Partial.** "day-to-day contact for maintenance, planning, parts and purchasing staff." The posting says "relationships" three times; the resume never does.
- Face-to-face sales calls — **Partial.** "prospecting and cold calling."
- Develop sales strategies and programs — **Partial.** Consignment program rebuild is the only program.
- Support OEMs, users, distributors, resellers — **Partial.** "OEM and MRO customers." He works at a distributor, which is exactly SEW's indirect channel, but the resume never says he works with manufacturers or their reps from the distributor side except "developed with the manufacturer" and "got a vendor to add the part."
- Understand major markets and industries — **Strong.** "food processing, steel, mining, municipal and fabrication plants."
- Develop and perform customer training — **Partial.** "Set up" manufacturer-led trainings; didn't deliver them.
- Self-training / product knowledge — **Strong.** WEG, Gates, Fenner, Continental, Global O-Ring and Seal training.
- Qualify leads into customers — **Strong.** "Opened nine accounts in 2026 ... all are buying, about $72,000 so far"; "about 75% of sales" from accounts he opened.
- CRM — **Partial.** "Epicor P21 (CRM, quotes, activity logging)." A recruiter will know P21 as an ERP; fine, but not Salesforce.
- Overnight travel, tradeshows, after-hours support — **Missing** (not addressed).

### Call: **Advance to phone screen.**
Ten years of Iowa outside sales in power transmission with real gear reducer application work, 6x territory growth and an engineering A.S. covers the core; the open questions are motion control, how deep the VFD work goes, and whether a distributor rep can run a manufacturer's territory.

### Ranked fixes (on-page facts only; new facts become questions)
1. Use the posting's words where the page already proves them: "relationships" (75 accounts, day-to-day contact) and "increased sales" (the 35%). Cheapest ATS and screen win.
2. Make the roll-neck highlight readable. "Found a $363,000 ... order no authorized supplier could quote" and "the competing price" contradict each other on first read. (Also a truth item.)
3. VFDs are a must-have and get one clause. **Question for Tobi:** a specific VFD application or count he can stand behind.
4. Motion controllers are a must-have and are absent. **Question for Tobi:** any motion control, servo or positioning work beyond the knife gate encoder?
5. Show the distributor-side advantage. SEW sells through distributors; one line that says he works with manufacturers' application engineers on specs would turn "distributor rep" from a question into a reason to hire. **Question for Tobi** if it needs a new fact.
6. "10 years in outside industrial sales and 15 with Standard Bearings" — "15" with no noun reads like a typo. Make it "15 years with Standard Bearings."

---

## 4. Truth check (with fact bank)

### Names
- Employer: "Standard Bearings" in both job headers and the summary. "Weimer" appears nowhere. **Pass.**
- Customers: all described by type ("a gypsum plant", "a limestone mine", "a motor repair shop", "aluminum recycling plant", "pork processor"). No customer named. **Pass.** (Vendors named: SEW-EURODRIVE, WEG, Gates, Fenner, Continental, Global O-Ring and Seal, Epicor. These are manufacturers/training, not customers.)

### Problems (block stage 05)
1. **Stronger than the fact / misstated — "Found a $363,000 roll-neck bearing order no authorized supplier could quote"** (Career Highlights). F-SALES-08: the bearing *was* on the market from one manufacturer; Standard Bearings just wasn't authorized to buy from it, and that manufacturer's price is the "competing price." "No authorized supplier could quote" says no one could supply it.
   - Fix: "Found a $363,000 roll-neck bearing order for a part Standard Bearings couldn't buy from its only maker, and got another vendor to add it to its line. Came in more than $200,000 below the competing price and about three months sooner."
2. **Not found — "Quoted, sourced and expedited orders for the outside sales team."** (Inside Sales summary line). F-JOB-02 says he worked inside sales, learned products in the warehouse and covered both; it says nothing about quoting, sourcing or expediting.
   - Fix: question for Tobi to confirm, or replace with F-JOB-02 wording ("Supported the outside sales team from the inside sales desk.").
3. **Not found — "handling receiving, shipping and local deliveries"** (Inside Sales bullet 2). F-JOB-02 confirms he covered the warehouse after the lead retired; the duty list isn't in the fact bank.
   - Fix: question for Tobi, or cut to "Covered inside sales and the warehouse at the same time after the warehouse lead retired, until a replacement was hired."
4. **Stronger than the fact — "then grows them by sizing and specifying gear reducers, motors and drives"** (Summary), together with the headline **"GEAR REDUCERS, MOTORS AND DRIVES."** F-SALES-05 says he grows accounts "through audits, capital projects, and system and process redesigns." F-TECH-09 says VFDs are "not his main line" and "never 'drives specialist.'" Headline plus summary present drives as his specialty and as his growth engine.
   - Fix (summary): "...then grows them through audits, capital projects and redesigns, sizing the gear reducers and motors that go with them." Headline option: "TECHNICAL SALES PROFESSIONAL | GEAR REDUCERS, GEARMOTORS AND POWER TRANSMISSION" — or Tobi confirms he's comfortable with "drives" there.
5. **Stronger than the fact — "Replaced jam-prone knife gates at a limestone mine with a custom 16-inch rack-and-pinion design"** (Experience). F-STORY-05 describes one custom gate ("a custom 16-inch rack-and-pinion slide gate"). The plural implies several replaced.
   - Fix: "Replaced a jam-prone knife gate..." unless Tobi confirms more than one.
6. **Not found — "Turnkey conveyor systems, several plants."** (Selected Projects title). F-STORY-17 gives "at least 6" systems; it says nothing about how many plants.
   - Fix: "Turnkey conveyor systems." (drop "several plants"), or confirm.
7. **Stronger than the fact — "on-site bearing failure analysis"** (Technical Skills, Field). F-TECH-07: "Basic bearing failure analysis on site; sends deeper cases to the manufacturer's lab."
   - Fix: "basic on-site bearing failure analysis" or "on-site bearing failure analysis, with lab follow-up through manufacturers."

### Traced (no action)
- Contact line — F-CON-01.
- "10 years in outside industrial sales and 15 with Standard Bearings", "power transmission and fluid power distributor" — Snapshot, F-JOB-01/02.
- "about 75 active accounts" — F-SALES-02 (safe wording).
- "about $3 million in annual sales, up 35% in the last year" — F-SALES-01.
- "food processing, steel, mining, municipal and fabrication plants in southeast Iowa" — F-MKT-03, F-MKT-01.
- "Opens accounts through prospecting and plant-floor problem solving" — F-SALES-05, Snapshot.
- Areas of Expertise: Territory Development (F-SALES-05/07); Prospecting and Lead Qualification (F-SALES-05); Gear Reducers and Gearmotors (F-TECH-01); Electric Motors (F-TECH-02/03); VFD (F-TECH-09, as a skill); Power Transmission; Drive Sizing and Application Data (F-TECH-08); Energy-Efficient Drive Retrofits (F-TECH-03, F-STORY-12); OEM and MRO Sales (F-SALES-04); Technical Problem Solving (Snapshot); Rep Training and Mentoring (F-LEAD-01/02); CRM and Pipeline Tracking (Epicor P21) (F-TOOL-01/02; "pipeline" is loose but P21 holds the open-quote portal); Fluid Power (Snapshot). "Distributor Operations" traces loosely to F-JOB-02 warehouse and inside-sales work; acceptable, but it's the weakest expertise item.
- "Grew territory sales from under $500,000 in 2016 to about $3 million" — F-SALES-07 (safe wording).
- "Accounts opened through personal prospecting now produce about 75% of sales and grew 53% in the last 12 months" — F-SALES-15.
- Gypsum reducers: "changing brand and style, then upsizing one frame ... about six months to more than six years" — F-STORY-03 (close to safe wording).
- "got a vendor to add the part to its line, coming in more than $200,000 below the competing price and about three months sooner" — F-SALES-08 (safe wording).
- Job headers and dates — F-JOB-01, F-JOB-02.
- "selling to OEM and MRO customers from first prospecting call through post-sale support" — F-SALES-04, F-SALES-05, F-SALES-14.
- "day-to-day contact for maintenance, planning, parts and purchasing staff" — F-SALES-03.
- "Opened nine accounts in 2026 ... all are buying, about $72,000 so far" — F-SALES-15.
- Knife gate design details (16-inch rack-and-pinion, with the manufacturer, 5 HP helical-bevel gearmotor, encoder for position feedback) — F-STORY-05 (count issue is item 5 above).
- "Collect application data such as tons per hour and existing equipment sizes to select gearbox and motor combinations" — F-TECH-08.
- "size and sell variable frequency drives, including SEW-EURODRIVE units" — F-TECH-09.
- Bucket elevator bullet — F-STORY-01 (matches safe version).
- Consignment program and "about $300,000 a year" — F-SALES-09 (safe wording; note the fact says "Tobi's team" did the rebuild).
- "Set up about six manufacturer-led customer trainings on bearing installation and failure analysis" — F-BUILD-07 ("set up," correct).
- "mentor newer outside reps on territory planning and cold calling" — F-LEAD-01/02.
- "Learned the product lines hands-on by working in the warehouse while training on the inside sales desk" — F-JOB-02.
- Drive energy retrofit, "Estimated energy savings: about 16%" — F-STORY-12 ("estimated" kept).
- "at least six complete conveyor systems, typically $12,000 to $20,000 each ... millwright crew" — F-STORY-17 (safe wording).
- Stainless pump base, "sold three so far" — F-STORY-08.
- Technical Skills: Drives line (F-TECH-01, F-STORY-02/05/12, F-TECH-09); Products line (F-TECH-01/02); Field line except item 7 (F-TECH-07); Tools line (F-TOOL-01/03/04/05/06).
- Education: A.S. Engineering, no year (F-EDU-01); WEG VFD training (F-EDU-07); Gates, Fenner, Continental, Global O-Ring and Seal (F-EDU-03); "MSHA Part 48 miner training, surface and underground" (F-EDU-02, safe wording; "current" correctly not claimed).
- Do-not-claim list checked: no bachelor's, no Salesforce, no motion controllers/servos, no margin, no OEM design-in wins, no chillers, no 180/212 accounts. Pass.

**Truth-check totals: 7 problems (3 Not found, 4 Traced but stronger than the fact).**

---

## Combined fix list (ranked by impact)

1. **Roll-neck highlight** — rewrite to the F-SALES-08 facts (truth item 1; also recruiter fix 2). Blocks stage 05.
2. **Summary growth line and headline "drives"** — rewrite to F-SALES-05 / F-TECH-09 or get Tobi's OK (truth item 4). Blocks stage 05.
3. **Inside Sales lines** — confirm "Quoted, sourced and expedited" and "receiving, shipping and local deliveries" with Tobi or cut to F-JOB-02 wording (truth items 2–3). Blocks stage 05.
4. **Add the posting's own words where the page already proves them** — "relationships" and "increased sales" (ATS 42% to about 75%; recruiter fix 1). Doing it in the 75-accounts bullet also removes the summary/bullet duplicate sentence (AI-tell).
5. **Knife gate plural, "several plants", "basic" bearing analysis** — three one-word fixes (truth items 5–7). Block stage 05.
6. **Question for Tobi: motion controllers / servos** (F-TECH-10 still open). Must-have in the posting; currently Missing.
7. **Question for Tobi: one concrete VFD line** (count, application or result) to back the must-have beyond one clause.
8. **Question for Tobi: distributor-side line** — e.g. F-LEAD-05 "coordinates with manufacturers' application engineers, millwrights and customer engineers" is verified and could go in as a bullet; positions him for SEW's indirect channel.
9. **"15 with Standard Bearings" → "15 years with Standard Bearings."**
10. **Drop bold lead-ins on at least two of the three Career Highlights** (AI-tell).
11. **Page-2 running header** — remove the em dash and move it out of the body text flow; consider dropping "PROFESSIONAL EXPERIENCE, CONTINUED" (AI-tell, ATS).
12. **Cut "Technical Problem Solving"** from Areas of Expertise (generic; 13 items remain, still in range).

---

## Fixes applied (11-25-2026)
- Truth 1, roll-neck: rewritten to F-SALES-08 ("Got a vendor to start making a roll-neck bearing Standard Bearings couldn't buy from its maker, winning a $363,000 order…").
- Truth 4, drives: headline now "Gear Reducers, Motors and Power Transmission"; summary grows accounts "through audits and capital projects" (F-SALES-05).
- Truth 2–3, inside sales: cut to F-JOB-02 wording ("Supported the outside sales team from the inside sales desk"; duty list removed).
- Truth 5–7: one knife gate; "Turnkey conveyor systems"; "basic bearing failure analysis."
- ATS: "relationships" (75-accounts bullet and Expertise) and "increased territory sales 35%" (summary). The summary/bullet duplicate sentence is gone.
- "15 years with Standard Bearings." "Technical Problem Solving" replaced by "Customer Relationships"; "Distributor Operations" became "Distributor and Manufacturer Coordination" (F-LEAD-05).
- Not applied, with reason: bold labels on Career Highlights and the page-2 running header / "Continued" heading are part of the approved v2 layout (`decisions/2026-11-24-foundations.md`, `layout.md`); the running header renders as two spans, not an em dash.
- Open questions for Tobi: motion controllers or servos (F-TECH-10); one concrete VFD example.
