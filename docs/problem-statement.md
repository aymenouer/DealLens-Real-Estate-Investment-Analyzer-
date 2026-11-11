# Problem Statement — DealLens

**Project:** DealLens — Real Estate Investment Analyzer  
**Version:** 0.2  
**Status:** Draft — Awaiting User Validation  
**Initial Market:** Germany  
**Last Updated:** November 11, 2026

---

## 1. Background

Buying a residential property as a long-term rental investment requires evaluating more than its advertised purchase price and potential rental income.

In Germany, investors must account for additional acquisition costs, financing obligations, ongoing ownership expenses, and potential periods without rental income.

Property listings typically provide information such as price, location, living area, and rental income. However, this information alone is insufficient to assess the financial viability of an investment.

Investors must combine property data with personal financing assumptions and cost estimates to understand the potential financial outcome.

Several investment calculators already address parts of this process. However, there may be an opportunity to make the overall evaluation more accessible, transparent, and understandable for beginners.

**DealLens aims to help first-time investors evaluate the financial implications of purchasing a rental apartment through a structured, beginner-friendly analysis.**

## 2. Target Users

### Primary Target User

An individual living in Germany who is researching the purchase of their first residential rental apartment.

**Characteristics:**

- Has little or no practical experience investing in rental properties.
- Is actively exploring apartments on German real estate listing platforms.
- Understands basic concepts such as purchase price and rental income.
- Has limited knowledge of acquisition expenses, financing calculations, and investment profitability.
- May purchase using personal savings, mortgage financing, or both.
- Wants to understand the financial implications before contacting banks or committing to a purchase.

### Primary User Scenario

A prospective investor discovers an apartment listed for €150,000 with an advertised monthly cold rent of €650.

Before considering the purchase, the investor wants to understand:

1. What is the estimated total acquisition cost?
2. How much personal capital is needed?
3. What are the expected monthly ownership expenses?
4. Will rental income cover the estimated costs and mortgage payments?
5. What do the estimated financial returns mean?

The user wants an understandable preliminary assessment without creating a custom spreadsheet.

### Secondary Target Users

Small private investors who already own one or two rental properties and want to evaluate additional opportunities.

**Initial product focus:** First-time individual investors evaluating residential apartments for long-term rental income in Germany.

## 3. Problem

First-time investors can find it difficult to evaluate whether a residential apartment is financially viable as a rental investment.

The evaluation requires combining information from different sources, understanding unfamiliar financial concepts, and making assumptions about costs and future income.

### Key Challenges

**P1 — Incomplete understanding of acquisition costs**

The advertised purchase price does not represent the total amount required to acquire a property.

Investors must account for property transfer tax, notary fees, land registration, brokerage fees where applicable, and potential initial renovation expenses.

**P2 — Difficulty estimating rental profitability**

Rental income alone does not represent profit.

Investors must distinguish rental revenue from costs borne by the landlord, including non-recoverable building expenses, administration, maintenance, and potential rental losses.

**P3 — Unclear financing implications**

For financed purchases, investors need to understand how loan amounts, interest rates, and repayment assumptions affect required upfront capital and monthly cash flow.

**P4 — Difficulty interpreting financial metrics**

Metrics such as gross rental yield, net rental yield, and monthly cash flow are not necessarily intuitive for beginners.

Without clear definitions, users may misinterpret calculations or compare results based on inconsistent assumptions.

**P5 — Uncertainty about assumptions**

Some financial information may be missing from property listings or based on estimates.

Users need to distinguish known values from assumptions and understand how missing information affects the reliability of results.

### Core Problem Statement

First-time rental property investors in Germany need a straightforward way to combine property information, acquisition costs, financing assumptions, and recurring expenses into an understandable financial evaluation.

Although existing tools offer investment calculations, it remains to be validated whether beginners can use those tools confidently and interpret their results correctly.

**DealLens will focus on making preliminary investment analysis transparent, understandable, and consistent.**

## 4. Current Alternatives

Investors already have several options for evaluating residential properties.

### Existing Solutions — Initial Research

| Solution | Existing capabilities | Opportunity to investigate |
|---|---|---|
| Excel / Google Sheets | Flexible, customizable financial calculations | Does building and maintaining formulas create unnecessary effort for beginners? |
| Interhyp Kapitalanlagerechner | Rental yield, cash flow, financing-related inputs, and tax estimates | How easily can first-time investors interpret its calculations? |
| immocation Kalkulationstool | Extensive property and financing calculations, including advanced spreadsheet-based analysis | Is its level of detail appropriate for beginners? |
| InvestBud | German property investment calculator with acquisition costs, yields, cash flow, and market information | What additional value could a guided analysis provide? |
| Financial or real estate advisors | Professional assistance with financial and purchasing decisions | Which preliminary questions do users prefer to answer independently? |

### Preliminary Competitive Finding

Existing products already address many important financial calculations.

Therefore, DealLens should not position itself as the first or only solution for rental property profitability calculations.

### Proposed Differentiation — Hypothesis

DealLens may provide additional value through:

- A guided workflow designed specifically for beginners.
- Plain-language explanations of financial metrics.
- Transparent calculation formulas and assumptions.
- Clear separation of known information from estimated values.
- A focused presentation of the financial information needed for an initial property assessment.

**These are proposed differentiators, not validated competitive advantages.**

### Research References

- [Interhyp — Rental Property Calculator](https://www.interhyp.de/kapitalanlagerechner/)
- [immocation — Tools and Downloads](https://hilfe.immocation.de/faq/tools-downloads)
- [InvestBud — Real Estate Investment Calculator](https://www.investbud.de/)
- [Finanztip — Property Acquisition Costs](https://www.finanztip.de/baufinanzierung/nebenkosten-hauskauf/)

Research conducted: November 2026.

## 5. Goals and Success Criteria

### Product Goals

**G1 — Simplify preliminary investment evaluation**

Allow users to calculate the essential financial metrics of one rental apartment without creating custom spreadsheets.

**G2 — Improve transparency**

Clearly present acquisition costs, required upfront capital, recurring ownership expenses, and estimated monthly cash flow.

**G3 — Improve comprehension**

Help users understand what each financial metric represents and which assumptions influence its result.

**G4 — Ensure calculation consistency**

Produce predictable and verifiable results based on documented financial formulas and validated inputs.

### Initial Success Criteria

The following targets are proposed for MVP usability testing.

| Goal | Success criterion | Measurement |
|---|---|---|
| Usability | At least 4 of 5 test participants complete an analysis independently | Observed usability test |
| Efficiency | At least 4 of 5 participants finish within 5 minutes when provided with complete input data | Task completion time |
| Comprehension | At least 4 of 5 participants correctly explain cash flow and gross rental yield | Post-task questions |
| Calculation accuracy | All approved financial test cases produce expected results | Automated tests against independently verified calculations |
| Transparency | Every displayed financial metric has an accessible definition and its assumptions are identifiable | Product acceptance review |

These are initial acceptance targets, not evidence of existing user demand.

A small usability study will provide preliminary findings, not statistically representative conclusions.

## 6. Scope

### MVP Objective

Enable a first-time investor to evaluate the estimated financial performance of a single residential rental apartment in Germany.

The first version will support one complete analysis, from entering property information to understanding the financial results.

### Included in MVP

**F1 — Property Information**

Users can manually enter:

- Property purchase price
- German federal state
- Property location or descriptive name
- Living area
- Monthly cold rent

**F2 — Acquisition Costs**

The system calculates or estimates:

- Property transfer tax based on the selected federal state
- Notary and land registration costs
- Brokerage fees, where applicable
- Additional upfront costs entered by the user
- Total estimated acquisition cost

Automatically suggested values must be labeled as estimates and be adjustable where appropriate.

**F3 — Financing**

Users can choose between:

- Cash purchase
- Mortgage-financed purchase

For financed purchases, users provide the loan amount, annual interest rate, and initial repayment rate.

The system estimates monthly loan payments and required upfront capital.

**F4 — Recurring Property Expenses**

Users can enter landlord-borne expenses, including non-recoverable Hausgeld, maintenance provisions, and an optional vacancy allowance.

The system must distinguish recoverable operating costs from expenses that remain the landlord's responsibility, avoiding double counting.

**F5 — Financial Calculations**

The system calculates:

- Total acquisition investment
- Required upfront capital
- Gross rental yield
- Net rental yield before financing and personal income taxes
- Estimated monthly cash flow after operating expenses and loan payments, but before personal income taxes

The exact formulas, calculation periods, and treatment of assumptions will be documented separately in `calculation-rules.md`.

**F6 — Investment Results**

The system displays:

- A summary of the estimated acquisition costs
- Estimated initial cash requirement
- Monthly rental income and owner-borne expenses
- Estimated monthly cash flow
- Gross and net rental yields
- Explanations of the financial metrics
- Warnings about missing or estimated inputs

### MVP Boundaries

- One property analysis at a time.
- Manual information entry.
- No user account required.
- No persistent saving of analyses.
- No property comparison.
- No automated financial recommendation.
- No personalized income tax calculation.

### Expected MVP Outcome

A user enters the relevant information for one apartment and receives a transparent financial overview of the potential purchase.

The application helps users understand the financial numbers, but does not determine whether they should buy the property.

## 7. Out of Scope

The following capabilities will not be included in the MVP.

### Product Features

- User authentication and accounts
- Persistently saving property analyses
- Comparing multiple properties
- Portfolio management
- Property listing scraping or automatic imports
- AI-based investment recommendations
- Automated property valuations
- Integration with mortgage providers or banks
- Automatically generated investment reports
- Advanced scenario analysis

### Advanced Financial Features

- Personalized income tax calculations
- Depreciation and tax deduction modeling
- Detailed mortgage amortization schedules
- Mortgage refinancing simulations
- Long-term property value forecasts
- Multi-year cash flow projections
- Complex renovation investment modeling
- Automated investment scoring

These capabilities may be considered for future versions after validating the core analysis experience.

## 8. Assumptions and Open Questions

### Product Hypotheses

| ID | Hypothesis | Proposed validation |
|---|---|---|
| H1 | First-time investors struggle to combine acquisition costs, financing, and rental expenses into one assessment | Interview prospective investors about their existing process |
| H2 | Beginners find at least some existing tools difficult to understand or interpret | Conduct comparative usability tests with existing calculators |
| H3 | Plain-language metric explanations improve user understanding | Test comprehension with and without explanations |
| H4 | Users are willing to enter property information manually | Observe users completing the proposed workflow |
| H5 | A single-property analysis provides sufficient initial value without saved analyses or comparison features | Ask users to evaluate the usefulness of the completed analysis |

### Open Questions

**Users and Product**

- Which part of investment evaluation creates the most confusion?
- Which financial metrics do beginners consider essential?
- Is manually entering property information acceptable?
- Do users need saved analyses earlier than currently planned?

**Calculations**

- Which assumptions should the system suggest by default?
- How should missing cost information be handled?
- How should rental vacancy allowances be incorporated?
- How should acquisition costs affect net yield?
- How should German Hausgeld categories be represented without double counting?
- Which calculation examples should serve as independently verified references?

**Competitive Positioning**

- Which existing tools are easiest for beginners to use?
- What problems remain after using those tools?
- Does DealLens's guided experience provide a measurable improvement?

### Validation Activities Before MVP Completion

1. Review at least three existing German real estate investment tools using the same example property.
2. Conduct exploratory interviews with at least five prospective first-time investors.
3. Create independently verified reference calculations for a cash purchase and a financed purchase.
4. Test the core DealLens workflow with five representative participants.
5. Review the MVP scope based on findings and update the product requirements accordingly.

The research may show that some proposed features are unnecessary or that the initial product direction needs adjustment.

---

## Product Vision

**Make real estate investment analysis understandable for first-time property investors.**

DealLens aims to help users move from a property listing to a transparent financial assessment by understanding purchase costs, financing obligations, rental profitability, and the assumptions behind the calculations.

The long-term vision is to support investors throughout the process of evaluating and comparing real estate opportunities.

**The initial priority is to make the analysis of one rental apartment clear, consistent, and reliable.**