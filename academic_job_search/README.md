# Open faculty positions for an IS / MIS candidate — R1/R2 universities (updated 2026-10-14)

## Version 3 (latest): `Final_Combined_Applications_Fit4-5.xlsx`

This workbook combines every **fit 4–5** posting with your application tracker (`University_Applications_Yuanze_Sun_Updated_1012.xlsx`). On 2026-10-14 each posting you have not yet submitted was re-searched for:
- whether it is still open, and its current deadline;
- visa sponsorship and work-authorization wording;
- whether industry experience is required;
- the exact position type.

| Sheet | Contents |
|---|---|
| README | Live summary counts (formulas) and how to read each column, including OPT / STEM OPT / H-1B notes |
| To Submit by Oct 18 | 111 open fit 4–5 postings you have not submitted and can take (sponsorship stated, not stated, or OPT-only), sorted URGENT → APPLY NOW → UPCOMING |
| All Fit 4-5 Combined | All 150 fit 4–5 postings, including the 30 you already submitted |
| Not Eligible or Closed | 8 postings that require industry experience, plus 1 closed posting |
| Already Submitted | All 60 tracker entries, matched to the R1/R2 list, with the other fit 4–5 lines at each school |

Key columns: Position Type (research tenure-track / teaching tenure-track / clinical-practice / lecturer / part-time), Tenure?, Eligible for You?, Visa Sponsorship, Industry Experience, Start vs Your PhD (June 2027), OPT Path, Your Application Status.

**Fix in this version:** a dedupe bug in version 2 had dropped Tulane's tenure-track IS Assistant Professor line, which you have already applied to. It is restored in `1_research_tenure_track_positions.csv` (294 rows in total now).

---

**Version 2.** This version re-scores everything using the match rule learned from your own IS job-board list (`isjobs-2026_7.csv`), removes positions that do not match, and adds positions found in a second round of searching.

## Files

| File | Contents | Rows |
|---|---|---|
| `1_research_tenure_track_positions.csv` | Tenure-track or tenured lines at any rank (Assistant through Full or chair) | 171 |
| `2_teaching_track_positions.csv` | Clinical, teaching professor, professor of practice, instructional and collegiate professorial lines | 31 |
| `3_senior_lecturer_lecturer_positions.csv` | Lecturer, senior lecturer, instructor, visiting, term and part-time/adjunct pools | 92 |
| `4_search_coverage_by_university.csv` | All 324 R1/R2 institutions and what the first search round found at each | 324 |
| `5_comparison_with_your_example_list.csv` | Every row of your example list, showing whether I had it and why or why not, its learned fit, and whether it is now included | 184 |

Every row now has **fit ≥ 1**. Fit-0 rows (no match) were removed.

Each file is sorted by fit (5 first), then full-time before part-time, then soonest deadline.

New columns:
- **Previous Fit**: your score in version 1, or "new" if the position was added in this round.
- **Unit**: business school, or a non-business IS-adjacent unit.
- **Found By**: which search round found the position.

**Totals: 294 positions.**
- Fit distribution: research 5: 52, 4: 22, 3: 28, 2: 57, 1: 12; teaching 5: 7, 4: 11, 3: 4, 2: 6, 1: 3; lecturer 5: 36, 4: 23, 3: 16, 2: 10, 1: 7.
- 76 positions are new in version 2 (34 of all rows are in non-business IS-adjacent units such as iSchools or data-science schools).
- 83 earlier rows were scored higher and 58 lower.
- 57 earlier rows were removed as fit 0 (marketing, strategy, management/OB, accounting, finance, entrepreneurship, economics, theoretical statistics).

## What I learned from your example list

Your list is an IS job-board export, and you said everything in it is a match (fit ≥ 3), with IS/MIS jobs in business schools all scoring 5. From it, the matching rule is mostly about the **field or unit**, not the rank or track. Your list includes:
- Associate and Full professor lines and endowed chairs;
- clinical, collegiate and professor-of-practice lines;
- lecturers;
- part-time IS adjunct pools;
- IS-adjacent lines outside business schools (iSchools, data-science schools, Penn State IST, BU Computing & Data Sciences).

My version-1 rubric was too narrow. It lowered scores for rank and part-time status, it gave 1–2 to fields you do not want (marketing, strategy, accounting), and it excluded non-business units entirely.

### Learned fit rubric (used for every row in v2)

- **5** — IS / MIS / IT management / computer information systems / business information technology / IS & analytics in a **business school**, at **any rank and any track**. This includes part-time IS pools and IS lines with an AI, cybersecurity, blockchain, data-science or enterprise-systems focus. Examples: Arkansas IS, Kelley clinical IS, Purdue Associate/Full MIS, UT Dallas part-time IS lecturer, Kennesaw IS & Security, WPI IS/Blockchain, SDSU Data Science in MIS, UIC Enterprise AI, Notre Dame ITAO, CMU Business Technology.
- **4** — Business analytics, data analytics, AI & analytics or decision-science lines in business schools. Also departments that combine IS with another field, such as:
  - Wharton OID, UCLA DOTM, Stanford OIT, HBS TOM;
  - SMU ITOM, UT IROM, UF ISOM;
  - Darden DADS, Iowa Business Analytics;
  - Management Science & IS departments.

  Also Accounting & Information Systems lines, and iSchool lines that are explicitly "Information Systems" (UW iSchool).
- **3** — IS-adjacent lines outside business schools: iSchool or data-science-school lines in HCI, social computing, human-centered or applied AI, or data science (Berkeley I School, BU CDS, UVA SDS, Penn State IST, UNC SDIS). Also tech, innovation or entrepreneurship units (HBS Entrepreneurial Management, Northwestern Innovation Institute, UMN Technological Leadership Institute), operations/supply-chain **teaching** lines with analytics, and management science.
- **2** — Operations management, supply chain, quantitative methods or business statistics research lines; marketing analytics or digital/social-media marketing; strategy focused on digital platforms; computational communication; AI education.
- **1** — Weak: general business lines that list technology as one option; FinTech-focused finance; health informatics in health-administration units.
- **0 (removed)** — Accounting without IS, finance, general marketing, OB/HR, non-tech strategy or entrepreneurship, economics, law, theoretical statistics, health policy, and non-faculty roles (postdocs, research scientists, staff).

Rank and timing risks are still written in **Why It Fits Your CV** (for example, "Associate/Full only — a reach for an ABD"), but they no longer lower the score.

## How my v1 results compare with your example list

Your list has 184 rows. 89 are not at universities on your 324-school R1/R2 list (international, R3 or teaching-focused schools), so they were outside the search. The other 95 are at your R1/R2 schools:

| Result | Count |
|---|---|
| Found in my first files | 57 |
| Not in my files | 28 |
| Found | 7 |
| Not a faculty line (postdoc / research scientist) — excluded by design | 3 |

**84 of the 95 are in the v2 files.**

The rest are excluded for a stated reason:
- the deadline had passed before the search;
- it is a prior-cycle posting (for example, VT's collegiate line, which started in 2026);
- it was verified closed;
- it is not a faculty line (postdoc or research scientist).

`5_comparison_with_your_example_list.csv` gives the reason for each row.

### Why I missed some, and what I did about it

1. **Search depth.** Round 1 used only 2 searches per school, because of the 200-searches-per-turn cap in this environment. That missed some IS lines (VT BIT, UF ISOM, UIC Enterprise AI, SDSU Data Science, UNR IS, Miami IS-Cyber, Colorado State CIS pool, OSU professional practice, TCU analytics instructor, Tulane IS professor of practice).

   **Fix:** a new round searched the AIS Academic Careers IS board region by region, used IS title variants, and gave every business school one extra IS-focused search inside its own domains and the AIS board.
2. **Over-strict verifier.** Some postings with a passed **priority** date that are still open until filled were treated as closed (Kennesaw, Purdue Associate/Full MIS, Wharton OID).

   **Fix:** they were re-verified and added.
3. **Scope.** I had excluded iSchools, data-science schools and other non-business units.

   **Fix:** these are now in scope at fit 2–4 and were searched (iSchools, data-science schools, informatics and technology-leadership units).
4. **Scoring.** Rank and part-time status lowered scores, and unrelated business fields were scored 1–2 instead of 0.

   **Fix:** every row was re-scored with the learned rubric.

## Caveats

- Only web search was available, so dates and open status come from search-result text. Confirm on the official posting before applying, especially rows marked "Likely open" or with a deadline of "Not stated".
- Postdocs are excluded from the three files by design. Your list's postdocs (NYU Tandon, JHU) are noted in file 5.
