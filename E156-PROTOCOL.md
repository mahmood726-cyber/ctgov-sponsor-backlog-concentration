# E156 Protocol — `ctgov-sponsor-backlog-concentration`

This repository is the source code and dashboard backing an E156 micro-paper on the [E156 Student Board](https://mahmood726-cyber.github.io/e156/students.html).

---

## `[40]` CT.gov Sponsor Backlog Concentration

**Type:** methods  |  ESTIMAND: Share of the 2-year missing-results backlog held by top sponsor slices  
**Data:** 25,584 lead sponsors contributing to the eligible older missing-results backlog in the March 29, 202

### 156-word body

Is the ClinicalTrials.gov missing-results backlog spread evenly across sponsors, or does a relatively small slice hold most of the unresolved stock? We analysed sponsor-level counts for 249,507 eligible older closed interventional studies and ranked 25,584 lead sponsors by two-year missing-results volume. The concentration analysis tracked cumulative shares of unresolved no-results studies, sponsor-level ghost-protocol counts, and inequality metrics alongside named outlier sponsors. The top 1 percent of lead sponsors accounted for 39.6 percent of the missing-results backlog, and the top 10 percent accounted for 77.4 percent. The sponsor-level Gini coefficient reached 0.818, while large industry firms, major academic centers, and public institutions all appeared among the highest-volume sponsors. The unresolved stock is therefore broad but highly uneven, with a thin sponsor slice carrying a disproportionate share of what remains unseen. These concentration statistics describe registry-visible stock distribution, not legal liability, and they depend on the lead-sponsor field recorded in CT.gov across this sponsor field and snapshot frame.

### Submission metadata

```
Corresponding author: Mahmood Ahmad <mahmood.ahmad2@nhs.net>
ORCID: 0000-0001-9107-3704
Affiliation: Tahir Heart Institute, Rabwah, Pakistan

Links:
  Code:      https://github.com/mahmood726-cyber/ctgov-sponsor-backlog-concentration
  Protocol:  https://github.com/mahmood726-cyber/ctgov-sponsor-backlog-concentration/blob/main/E156-PROTOCOL.md
  Dashboard: https://mahmood726-cyber.github.io/ctgov-sponsor-backlog-concentration/

References (topic pack: CT.gov / ClinicalTrials.gov audit):
  1. Zarin DA, Tse T, Williams RJ, Rajakannan T. 2017. Update on trial registration 11 years after the ICMJE policy was established. N Engl J Med. 376(4):383-391. doi:10.1056/NEJMsr1601330
  2. Anderson ML, Chiswell K, Peterson ED, Tasneem A, Topping J, Califf RM. 2015. Compliance with results reporting at ClinicalTrials.gov. N Engl J Med. 372(11):1031-1039. doi:10.1056/NEJMsa1409364

Data availability: No patient-level data used. Analysis derived exclusively
  from publicly available aggregate records. All source identifiers are in
  the protocol document linked above.

Ethics: Not required. Study uses only publicly available aggregate data; no
  human participants; no patient-identifiable information; no individual-
  participant data. No institutional review board approval sought or required
  under standard research-ethics guidelines for secondary methodological
  research on published literature.

Funding: None.

Competing interests: MA serves on the editorial board of Synthēsis (the
  target journal); MA had no role in editorial decisions on this
  manuscript, which was handled by an independent editor of the journal.

Author contributions (CRediT):
  [STUDENT REWRITER, first author] — Writing – original draft, Writing –
    review & editing, Validation.
  [SUPERVISING FACULTY, last/senior author] — Supervision, Validation,
    Writing – review & editing.
  Mahmood Ahmad (middle author, NOT first or last) — Conceptualization,
    Methodology, Software, Data curation, Formal analysis, Resources.

AI disclosure: Computational tooling (including AI-assisted coding via
  Claude Code [Anthropic]) was used to develop analysis scripts and assist
  with data extraction. The final manuscript was human-written, reviewed,
  and approved by the author; the submitted text is not AI-generated. All
  quantitative claims were verified against source data; cross-validation
  was performed where applicable. The author retains full responsibility for
  the final content.

Preprint: Not preprinted.

Reporting checklist: PRISMA 2020 (methods-paper variant — reports on review corpus).

Target journal: ◆ Synthēsis (https://www.synthesis-medicine.org/index.php/journal)
  Section: Methods Note — submit the 156-word E156 body verbatim as the main text.
  The journal caps main text at ≤400 words; E156's 156-word, 7-sentence
  contract sits well inside that ceiling. Do NOT pad to 400 — the
  micro-paper length is the point of the format.

Manuscript license: CC-BY-4.0.
Code license: MIT.

SUBMITTED: [ ]
```


---

_Auto-generated from the workbook by `C:/E156/scripts/create_missing_protocols.py`. If something is wrong, edit `rewrite-workbook.txt` and re-run the script — it will overwrite this file via the GitHub API._