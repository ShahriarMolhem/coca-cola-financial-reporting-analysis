# Accounting Ratios, Cash Conversion and Financial Reporting

**The Coca-Cola Company (NYSE: KO), FY2021–FY2025**. Undergrad accounting study using official SEC 10-K statements, **USD millions** unless otherwise noted. These are historical facts and formula-derived ratios, **not forecasts**.

## GAAP margin and cash-conversion metrics

| Measure | FY2021 | FY2022 | FY2023 | FY2024 | FY2025 |
|---|---:|---:|---:|---:|---:|
| Gross margin | 60.3% | 58.1% | 59.5% | 61.1% | 61.6% |
| Operating margin | 26.7% | 25.4% | 24.7% | 21.2% | 28.7% |
| CFO / consolidated net income | 128.8% | 115.1% | 108.4% | 63.9% | 56.4% |
| NI less CFO ($m) | −2,821 | −1,447 | −896 | 3,844 | 5,729 |
| Simple FCF: CFO less PP&E purchases ($m) | 11,258 | 9,534 | 9,747 | 4,741 | 5,296 |

**2025:** Coca-Cola reported $47.941bn revenue, $13.762bn operating income, **$13.137bn consolidated net income**, and **$7.408bn operating cash flow**. All figures are from its FY2025 SEC 10-K. Despite higher accounting profit, historical CFO was lower than earnings. This is a **cash-conversion observation**, not an accusation of accounting irregularities.

### Indirect method
The FY2025 consolidated CFO statement reconciles starting from **consolidated net income** and adjusting for noncash items, net non-operating effects and changes in operating assets/liabilities. The latter equals **−$7.208bn** in 2025 and **−$6.234bn** in 2024. The filing discusses significant one-time cash effects, including payments related to **fairlife** and an IRS litigation deposit in 2024. The same line can include multiple current-account movements, so it is inaccurate to treat it as only changes in receivables and inventory.

### Reported operating margin
Operating income increased from $9.992bn in 2024 to $13.762bn in 2025; one critical comparison is **other operating charges** falling from $4.163bn to $1.261bn. This is not proof all other operating charges are non-recurring, nor that a normalized recurring margin must equal reported 2025 margin.

### Liquidity and other comprehensive income
FY2025 year-end current ratio = 31,044 / 21,281 = **1.46x**; FY2024 = 25,997 / 25,249 = **1.03x**. Assets and liabilities **held for sale** can affect reported current classification, making a simple liquidity improvement story incomplete.

The FY2025 net foreign-currency translation adjustment included in other comprehensive income was **+$2.868bn** versus **−$2.893bn** in 2024. Some equity movements are recorded through OCI rather than current-year net income.

## Excel workbook
The locally developed workbook `models/coca_cola_accounting_analysis.xlsx` includes 8 worksheets: Income Statement, Cash Flow, Balance Sheet, OCI, Accounting Ratios, Validation, Notes and Sources. It is **prepared locally but not yet uploaded to GitHub**. All historical ratio calculations use actual source sheet formulas, with embedded SEC source URLs.

## Limitations and disclosure
We analyze publicly reported figures; original filings and notes remain authoritative. Indirect-method reconciliation is **not an external audit**, and ratios alone cannot establish earnings manipulation or internal control deficiencies.

**References:** [FY2025 SEC Form 10-K](https://www.sec.gov/Archives/edgar/data/21344/000162828026010047/ko-20251231.htm), [FY2023 SEC Form 10-K](https://www.sec.gov/Archives/edgar/data/21344/000002134424000009/ko-20231231.htm).
