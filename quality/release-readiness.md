# Release Readiness Checklist

**Current state:** All report and source documents, Excel, and original PowerPoint are uploaded to the release branch. Both binary files were checked against the prepared originals and passed OOXML archive integrity validation. Repository remains **Private** pending owner publication approval.

## Completed
- [x] Research source register, scope and methods.
- [x] Historical source-linked income, cash flow, balance sheet and OCI CSVs.
- [x] Historical arithmetic validation with zero discrepancies.
- [x] Accounting ratio/cash conversion report.
- [x] Locally prepared formula-driven Excel workbook.
- [x] Locally prepared 10-slide PowerPoint with notes.
- [x] Recruiter-oriented summary and full presentation rehearsal script.

## Before merging PR #4
- [x] Upload `models/coca_cola_accounting_analysis.xlsx` to branch `04-presentation-and-release` (Git object matched original).
- [x] Upload the original `presentations/coca_cola_accounting_presentation.pptx` to the same branch.
- [x] Verify expected paths, byte-identical Git blob SHAs and archive integrity (Excel: 7 worksheets; original PowerPoint: 10 slides + 10 speaker-notes pages).
- [x] Update README and slide outline with links to both real binaries.
- [ ] Owner visually reviews and understands the report/model/deck.
- [ ] Merge PR #4 after final commit; keep repository Private until explicit owner publication approval.

## Prior to public release
- [ ] Obtain owner's **explicit consent** before changing repository visibility to Public.
- [ ] Check that original SEC source links work and all public interpretations are defensible.
- [ ] Ensure disclosures do not imply Coca-Cola employer relationship, internal access or CPA assurance.
