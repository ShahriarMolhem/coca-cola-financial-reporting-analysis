# Release Readiness Checklist

**Current state:** All text analyses ready; Excel successfully uploaded and original file identity verified. The original PowerPoint is still pending upload to the release branch. The repository is **Private**.

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
- [ ] Upload `presentations/coca_cola_accounting_presentation.pptx` to the same branch.
- [ ] Verify file names and workbook/presentation structural integrity on GitHub (Excel presence and SHA match complete; PowerPoint missing).
- [ ] Update READMEs to link to the real binaries.
- [ ] Owner visually reviews and understands the report/model/deck.
- [ ] Merge PR #4.

## Prior to public release
- [ ] Obtain owner's **explicit consent** before changing repository visibility to Public.
- [ ] Check that original SEC source links work and all public interpretations are defensible.
- [ ] Ensure disclosures do not imply Coca-Cola employer relationship, internal access or CPA assurance.
