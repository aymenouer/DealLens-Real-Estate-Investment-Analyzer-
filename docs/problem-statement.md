# Problem Statement — DealLens

**Project:** DealLens — Real Estate Investment Analyzer
**Version:** 0.3
**Status:** Product Definition Approved — AI Approved
**Initial Market:** Germany
**Last Updated:** November 11, 2026

---

## 1. Background

Buying an apartment as a long-term rental investment requires evaluating more than its advertised purchase price and potential rental income.

In Germany, investors must consider acquisition costs, financing obligations, ongoing ownership expenses, and potential rental vacancies.

Property listings typically provide information such as purchase price, location, living area, and rental income. However, this information alone does not provide a complete picture of a property's financial performance.

Investors must combine information from different sources and make assumptions about costs, financing, and expected income.

Existing investment calculators already address many of these calculations. However, there may be an opportunity to make the evaluation process more understandable and transparent for beginners.

**DealLens aims to simplify preliminary rental property investment analysis through a structured, beginner-friendly experience.**

## 2. Target Users

### Primary Target User

An individual in Germany researching the purchase of their first residential apartment as a long-term rental investment.

**Characteristics:**

- Has limited or no practical experience investing in rental properties.
- Researches apartments through real estate listing platforms.
- Understands basic concepts such as purchase price and monthly rent.
- Has limited knowledge of acquisition expenses, financing calculations, and rental profitability.
- May finance the purchase through personal savings, a mortgage, or both.
- Wants to understand the financial implications before making a purchasing decision.

### Primary User Scenario

A prospective investor discovers an apartment in Leipzig advertised for €150,000.

The apartment currently generates €650 in monthly cold rent.

Before proceeding, the investor wants to understand:

1. What will the property actually cost, including acquisition expenses?
2. How much personal capital will be required?
3. What recurring expenses will remain the owner's responsibility?
4. Will the rental income cover the expected ownership costs and mortgage payments?
5. How reliable are the financial estimates?

The investor wants an understandable initial assessment without manually constructing financial spreadsheets.

### Secondary Users

Small private investors who already own one or two rental properties and want a structured way to assess additional opportunities.

**Initial focus:** First-time private investors evaluating residential apartments for long-term rental income in Germany.

## 3. Problem

First-time investors may struggle to determine whether a rental apartment represents a financially viable investment.

This evaluation requires combining information from different sources, interpreting financial concepts, and estimating expenses that may not be immediately available.

### Key Challenges

**P1 — Incomplete understanding of acquisition costs**

The advertised purchase price does not represent the total cost of purchasing a property.

Additional expenses may include property transfer tax, notary fees, land registration, brokerage fees, and initial renovation costs.

**P2 — Difficulty understanding rental profitability**

Rental income does not equal profit.

Investors must account for recurring expenses, including property management, maintenance, non-recoverable operating costs, and potential rental losses.

For German apartments, distinguishing landlord-borne expenses from costs recoverable from tenants is particularly important.

**P3 — Unclear financing implications**

Mortgage financing introduces additional financial obligations.

Investors need to understand how loan amounts, interest rates, and repayment assumptions influence monthly payments and required upfront capital.

**P4 — Difficulty interpreting financial metrics**

Terms such as gross rental yield, net rental yield, and monthly cash flow may be unfamiliar to beginners.

Without understandable explanations, users risk misinterpreting results or comparing calculations based on different assumptions.

**P5 — Incomplete or uncertain property information**

Property listings may contain incomplete cost information or estimated rental income rather than contractual rent.

Investors need to understand which financial values are known, which are estimated, and how uncertainty affects the results.

### Core Problem Statement

First-time rental property investors in Germany need an understandable way to evaluate total acquisition costs, financing requirements, rental profitability, and financial assumptions.

Although existing tools provide many relevant calculations, it remains to be validated whether beginners can use them confidently and interpret their results correctly.

**DealLens will focus on transparent calculations, understandable explanations, and a structured preliminary investment evaluation.**

## 4. Current Alternatives

Investors currently use several methods to evaluate rental property investments.

| Alternative                       | Existing capabilities                                            | Opportunity to investigate                                                        |
| --------------------------------- | ---------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| Excel / Google Sheets             | Flexible financial models and custom calculations                | Does maintaining formulas make the process unnecessarily difficult for beginners? |
| Interhyp Kapitalanlagerechner     | Cash flow, rental yield, and tax-oriented estimates              | Can beginners understand the inputs, assumptions, and results independently?      |
| immocation Kalkulationstool       | Detailed Excel-based financial analysis for property investments | Is its complexity appropriate for users evaluating their first apartment?         |
| InvestBud                         | Property investment calculations and analysis capabilities       | Could a guided workflow offer measurable usability advantages?                    |
| Financial or real estate advisors | Professional assistance and contextual guidance                  | Which preliminary calculations do users prefer to perform independently?          |

### Competitive Positioning

Existing products already calculate important investment metrics.

DealLens therefore does not aim to differentiate itself through basic financial calculations alone.

Instead, its proposed differentiation is:

1. **Beginner-oriented workflow:** Guide users through a focused preliminary analysis.
2. **Explainable results:** Provide understandable definitions of financial metrics.
3. **Transparent assumptions:** Distinguish supplied information, calculated values, and estimates.
4. **Focused presentation:** Prioritize essential financial information rather than overwhelming users with advanced calculations.
5. **Consistent calculations:** Use clearly documented financial rules and make limitations visible.

## 5. Goals and Success Criteria

### Product Goals

**G1 — Simplify preliminary investment evaluation**

Help users calculate essential financial metrics without creating or maintaining their own spreadsheets.

**G2 — Improve financial transparency**

Clearly present acquisition costs, required upfront capital, recurring owner expenses, and estimated cash flow.

**G3 — Improve user comprehension**

Help users understand financial metrics, calculation assumptions, and potential limitations.

**G4 — Ensure calculation consistency**

Produce predictable and verifiable financial results based on documented calculation rules.

**G5 — Make uncertainty visible**

Clearly distinguish known information from estimates and identify missing inputs that affect reliability.

### Initial Success Criteria

| Goal                | Proposed success criterion                                                                      | Verification                                          |
| ------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| Usability           | At least 4 of 5 test participants complete an analysis independently                            | Observed usability testing                            |
| Efficiency          | At least 4 of 5 participants complete an analysis within 5 minutes using supplied property data | Task completion measurement                           |
| Comprehension       | At least 4 of 5 participants correctly explain cash flow and gross rental yield                 | Post-task questions                                   |
| Accuracy            | All approved calculation test cases produce expected results                                    | Automated tests using independently verified examples |
| Transparency        | Every financial metric has an accessible definition and identifiable assumptions                | Acceptance review                                     |
| Missing information | Unknown material expenses are never silently interpreted as zero                                | Input validation and acceptance tests                 |

These are preliminary validation targets, not demonstrated outcomes.

Testing with five participants will produce exploratory findings rather than statistically representative evidence.

## 6. Scope

### MVP Objective

Enable an investor to complete a transparent financial assessment of one residential rental apartment in Germany.

The MVP focuses on a single complete analysis, without requiring an account or saved property records.

### Core Capabilities

**1. Property Information**

Users can manually enter essential property details, including purchase price, location, living area, and rental income.

The application must distinguish between:

- **Contractual rent:** Rent currently agreed under an existing tenancy.
- **Estimated rent:** Expected rental income for a vacant property or a proposed future tenancy.

Estimated rental income must be clearly identified as an assumption rather than guaranteed revenue.

**2. Acquisition Costs**

The application estimates total initial investment costs, including:

- Property purchase price
- Property transfer tax
- Notary and land registration fees
- Applicable brokerage fees
- Additional one-time costs entered by the user

Suggested acquisition-cost values must be identified as estimates and be adjustable where appropriate.

The application distinguishes acquisition transaction costs from additional initial investment expenses, such as renovation work.

**3. Financing**

The application supports:

- Cash purchases
- Purchases financed through a standard mortgage with initial annuity payments

For financed purchases, users provide the loan amount, nominal annual interest rate, and initial repayment rate.

The application estimates the initial monthly loan payment and the personal capital required.

Required upfront capital is based on the total initial investment less the loan amount, subject to valid financing assumptions.

The calculation must make clear that a loan may finance only part of the purchase or associated expenses. It does not assume banks will approve a proposed financing structure.

**MVP limitation:** Only an initial mortgage-payment estimate is provided. A detailed amortization schedule, future interest changes, and refinancing are excluded.

**4. Recurring Ownership Expenses**

The application accounts for the ongoing expenses borne by the property owner.

For German apartments, the expense model must distinguish:

- **Recoverable operating costs:** Costs that may be charged to tenants under applicable rules and contractual arrangements.
- **Non-recoverable operating and administration costs:** Expenses remaining the landlord's responsibility.
- **Maintenance reserve contributions:** Owner payments toward the condominium association's maintenance reserve.
- **Additional maintenance expenses:** Separate costs not already included elsewhere.

The application must avoid double counting expenses, particularly where maintenance reserve contributions are already included in the supplied Hausgeld breakdown.

In the simplified cold-rent-based model, recoverable operating costs and corresponding tenant advances are excluded consistently rather than treating one side as profit or expense.

Maintenance reserves are treated as cash outflows for the MVP, not as equivalent to expenses for tax purposes.

**5. Missing Information and Assumptions**

The application distinguishes between:

- Required inputs needed for valid calculations.
- Optional inputs that users may explicitly set to zero.
- Estimated values that users can review or adjust.
- Unknown information that affects result reliability.

Unknown material expenses must not automatically be treated as €0.

When information is insufficient, the application must request clarification, require an explicit assumption, or mark the affected result as incomplete.

Every estimated or user-supplied assumption must be identifiable in the results.

**6. Financial Results**

The application provides a clear overview of:

- Total initial investment
- Required upfront capital
- Initial estimated mortgage payment
- Gross rental yield
- Net rental yield before financing and personal income taxes
- Estimated monthly cash flow after recurring owner expenses and loan payments, before personal income taxes

The calculation model must differentiate between investment profitability and monthly cash flow.

It must also clarify that mortgage principal repayment reduces available cash but is not equivalent to an operating expense.

Detailed formula definitions, assumptions, rounding rules, and independently verified examples will be maintained in `calculation-rules.md`.

### MVP Boundaries

The first version will:

- Evaluate one property at a time.
- Use manually entered property information.
- Support cash purchases and simplified mortgage financing.
- Show transparent calculations and explanations.
- Require no user account.
- Operate without persistent property storage.
- Avoid automatic buy/sell recommendations.

### Expected MVP Outcome

A user enters information about an apartment and receives a preliminary financial assessment.

The application explains:

- The estimated cost of acquiring the property.
- The initial personal capital required.
- The expected recurring financial obligations.
- The estimated monthly cash flow.
- The meaning and limitations of the calculated returns.

**DealLens supports financial understanding. It does not guarantee returns, confirm financing eligibility, or determine whether an investment should be purchased.**

## 7. Out of Scope

The following capabilities are excluded from the MVP.

### Product Features

- Authentication and user accounts
- Persistently saved property analyses
- Side-by-side property comparisons
- Property portfolio management
- Automatic listing extraction or scraping
- AI-generated investment recommendations
- Automated property valuations
- Bank and mortgage-provider integrations
- Automated PDF investment reports
- Advanced scenario simulations

### Advanced Financial Features

- Personalized income tax calculations
- Depreciation and tax deduction modeling
- Detailed mortgage amortization schedules
- Interest-rate refinancing simulations
- Long-term property appreciation forecasts
- Multi-year cash flow projections
- Complex renovation investment modeling
- Automated investment scores
- Detailed liquidity and emergency-reserve planning

### Proposed Future Releases

**MVP v0 — Core Analysis**

Complete one preliminary financial analysis with transparent results.

**v1 — Saved Investments**

Allow users to create, save, reopen, edit, and manage property analyses.

**v2 — Comparison and Risk Assessment**

Compare saved properties and explore how changing assumptions may affect investment performance.

**Later Versions**

Investigate advanced financing, longer-term projections, market data, and other features based on demonstrated user needs.

These releases are preliminary planning boundaries, not committed delivery dates.

---

## Product Vision

**Make rental property investment analysis understandable, transparent, and accessible to first-time investors.**

DealLens helps users move from a property listing to a structured preliminary financial assessment by explaining acquisition costs, financing obligations, rental profitability, and the assumptions behind the numbers.

The long-term vision is to help individual investors evaluate, compare, and understand rental property investment opportunities.

**The first milestone is simple: make the financial evaluation of one rental apartment clear, consistent, and reliable.**
