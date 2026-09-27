# Retail Customer Analytics — app vs website behaviour

Excel analysis of 1,000 retail customers, comparing how members behave depending on which channel
they use (mobile app vs website) and how that maps to spending. Completed during my business-analyst
internship at OESON as a structured Excel project, then written up as a business report.

## The question

Membership programmes usually assume a customer is a customer regardless of channel. This project
tested that assumption: do app users and website users differ in engagement and spend, and if so,
where should the business put its retention and channel effort?

## Data

`FyntraCustomerData.csv` — 1,000 customer records for a retail membership programme: average
session length, membership duration, time spent on app vs website, and yearly amount spent.

## Method

1. **Profiling** — distributions, ranges, and completeness of each field before any comparison.
2. **Grouped analysis** — PivotTables segmenting customers by channel preference; averages and
   counts computed per segment rather than read off the raw rows.
3. **Comparison** — app time against website time, and each against length of membership and spend.
4. **Reporting** — the findings written as a business memo with recommendations, not just a
   workbook of tables.

## Headline figures

| Metric | Value |
|---|---|
| Average session length | 33.1 minutes |
| Average membership duration | 3.53 years |
| Average time on website | 37.1 minutes |
| Average time on app | 12.1 minutes |
| Average yearly spend | 499.3 |

The channel gap is the finding: website time runs roughly three times app time among these members,
while app engagement is comparatively shallow. Read against membership duration, that pattern is
the basis for the recommendation to invest in the channel where the deep sessions already happen
rather than pushing members toward the lighter one.

## Files

| File | What it is |
|---|---|
| `FyntraCustomerData.csv` | The customer dataset |
| `Fyntra_Customer_Analysis.docx` | The Excel project write-up: tables, interpretation, recommendations |
