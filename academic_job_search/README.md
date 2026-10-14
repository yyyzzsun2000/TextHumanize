# Open business-school faculty positions — R1/R2 universities (search date: 2026-10-14)

Prepared for: PhD candidate in Management Science / MIS (UW–Milwaukee, PhD expected June 2027).

## Files

| File | What it contains | Rows |
|---|---|---|
| `1_research_tenure_track_positions.csv` | Tenure-track / tenured research lines (Assistant, Associate, Open-rank) | 185 |
| `2_teaching_track_positions.csv` | Teaching-track professorial lines (Clinical, Teaching Professor, Professor of Practice, Assistant Professor of Teaching / Instruction, UC teaching-tenure track) | 24 |
| `3_senior_lecturer_lecturer_positions.csv` | Lecturer / Senior Lecturer / Instructor / Visiting and lecturer pools (part-time pools are labelled and capped at fit 2) | 69 |
| `4_search_coverage_by_university.csv` | Supplementary audit: every one of the 324 R1/R2 institutions, its business unit, job portals found and how many open positions were found | 324 |

278 open positions at 159 universities. 165 of the 324 institutions had no open in-scope position (this includes 30 medical/health-science institutions with no business school).

Each file is sorted by **Fit (high → low)**, then by deadline (soonest first).

Fit distribution:
- Research tenure-track: 5: 31, 4: 20, 3: 53, 2: 61, 1: 20
- Teaching track: 5: 2, 4: 5, 3: 8, 2: 8, 1: 1
- Lecturer: 5: 0, 4: 4, 3: 8, 2: 50, 1: 7

## Key columns

- **Fit (1-5)**: 5 = excellent, 3 = moderate, 1 = poor (see the rubric below).
- **Why It Fits Your CV**: the reasoning, citing your research (creator economy, platforms, misinformation; ISR R&R / MISQ under review), methods (econometrics, ML/LLMs, multimodal data) and teaching (cloud/Azure, ML for business, intro IS), plus the risks (timing, credentials, area mismatch).
- **Application Deadline**: a fixed date (YYYY-MM-DD), "Open until filled", or "Not stated". **Deadline / Review Details** gives review-start or priority dates. Rows whose priority date has passed but which still accept applications until filled are marked as such.
- **Posting URL** and **Link Type**: either the official university or application-system page (Interfolio, Workday, PeopleAdmin and similar), a job-board copy (HigherEdJobs, Chronicle, Inside Higher Ed, INFORMS, AIS), or, in a few cases, a job-portal listing page where you need to search for the title.
- **Open-Status Check**:
  - **Confirmed open**: re-checked; a current-cycle posting with a future deadline or open until filled.
  - **Likely open**: a current-cycle (2027-start) posting with no stated deadline and no sign of closure.

## Fit rubric

- **5**: IS / MIS / IT management / business analytics / AI-in-business line at Assistant (or open) rank whose research or teaching needs overlap yours, with ABD acceptable for a ~Fall 2027 start. For teaching roles: IS / analytics / AI / cloud / Python courses that match your teaching record.
- **4**: an IS or analytics line with a modest mismatch, for example:
  - a cybersecurity, ERP or accounting-IS emphasis;
  - a combined IS/OM department;
  - a teaching or lecturer IS role that prefers more experience;
  - marketing analytics that welcomes IS or social-media researchers.
- **3**: an adjacent field where an IS PhD is eligible: operations or supply chain, decision sciences, management science, technology/innovation management, digital or social-media marketing, or open-area searches. Also full-time IS lecturer roles with timing issues.
- **2**: accounting, finance, general marketing, strategy or management lines, and part-time/adjunct pools.
- **1**: Associate/Full-only or chair positions; roles needing credentials you lack (CPA, accounting PhD, years of industry experience); very peripheral fields.

## How the search was done

1. **Job-board sweeps.** 12 sweeps across:
   - general boards: HigherEdJobs, Chronicle, Inside Higher Ed, LinkedIn, Indeed, Glassdoor, ZipRecruiter;
   - society boards: AIS/ISWorld, INFORMS, AACSB, AOM, AAA, DSI;
   - application systems: Interfolio, Workday, PeopleAdmin, HERC, AcademicKeys;
   - AI/digital initiatives, adjacent fields, and region-by-region open-web searches.

   Every lead was mapped to the 324-school list.
2. **Per-university check.** All 324 institutions were checked: the university job portal, the business-school site, and job boards filtered to that university.
3. **Second pass.** Every business school that showed zero results was re-searched inside its own .edu and job-portal domains.
4. **Verification.** Every candidate posting was re-checked by a skeptical verifier. Prior-cycle postings (Fall 2026 start or earlier), closed postings, out-of-scope postings and duplicates were removed. Weak links were replaced with direct posting links where one could be found.
5. **Calibration.** A final pass made fit scores and track categories consistent across all rows.

## Caveats

- This environment could only use web search. Posting pages could not be opened directly, so all dates and open status come from search-result text. **Confirm on the official posting before applying**, especially "Likely open" rows and rows whose deadline is "Not stated".
- Job postings change daily. New Fall 2027 postings keep appearing through December and January (ICIS and INFORMS season), so re-check the AIS/ISWorld and INFORMS boards periodically.
- Postdocs, staff jobs and non-business units (CS, iSchools, medicine) are excluded by design.
