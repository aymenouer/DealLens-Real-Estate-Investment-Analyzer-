# Problem Statement — DealLens

**Project:** DealLens — Real Estate Investment Analyzer  
**Version:** 0.1 (Initial Draft)  
**Status:** Draft — To Be Validated  
**Initial Market:** Germany

---

## 1. Background

Real estate is a popular long-term investment option, but evaluating a potential property purchase requires more than looking at the advertised price and expected rental income.

In Germany, buying an apartment can involve additional acquisition costs, financing expenses, maintenance costs, property management fees, and periods without rental income.

Property listings provide useful information, such as purchase price, location, apartment size, and rental income. However, they do not necessarily provide a complete picture of the financial implications of purchasing the property.

Potential investors must gather information from different sources, calculate expenses, and estimate investment returns before deciding whether an opportunity is financially suitable.

**DealLens aims to simplify this evaluation process by bringing the essential investment calculations into one understandable application.**

## 2. Target Users

### Primary Users

First-time real estate investors in Germany who are considering purchasing an apartment as a long-term rental investment.

Typical characteristics:

- Have limited experience evaluating real estate investments.
- Are researching apartments listed on property websites.
- Want to understand the financial implications before purchasing.
- May use personal savings, mortgage financing, or a combination of both.
- Need straightforward explanations of investment metrics.

### Secondary Users

Individual investors who already own rental properties and want a structured way to evaluate additional investment opportunities.

**Initial focus:** Individuals evaluating residential apartments for long-term rental income in Germany.

## 3. Problem

First-time investors often struggle to determine whether a rental apartment represents a financially viable investment.

Although property listings provide purchase prices and sometimes rental information, evaluating an investment requires additional calculations and assumptions.

The main challenges include:

**1. Understanding total acquisition costs**

The advertised purchase price does not include every expense involved in buying a property. Investors must account for property transfer tax, notary fees, registration costs, and potentially brokerage fees.

**2. Estimating actual profitability**

Rental income alone does not indicate profitability. Investors must consider maintenance, non-recoverable expenses, vacancy allowances, and other ownership costs.

**3. Understanding financing implications**

Investors using mortgage financing need to understand how interest rates, repayment terms, and their available equity affect monthly cash flow.

**4. Interpreting financial results**

Metrics such as gross rental yield, net rental yield, and cash flow can be confusing for beginners, particularly when their assumptions and calculation methods are unclear.

**5. Assessing financial risks**

Unexpected expenses, rental vacancies, or changing financing conditions can affect investment performance.

### Core Problem Statement

First-time rental property investors in Germany lack a simple, transparent, and structured way to estimate the full financial costs, potential returns, and risks of a property purchase.

Consequently, evaluating an investment can become time-consuming, confusing, and vulnerable to incorrect assumptions.

## 4. Current Alternatives

Potential investors currently have several ways to evaluate properties.

| Alternative | Potential limitation |
|---|---|
| Excel or Google Sheets | Requires creating or adapting formulas and understanding which costs to include. |
| Online property calculators | May provide individual metrics without offering a complete evaluation workflow. |
| Real estate listing platforms | Primarily present property information rather than a personalized investment analysis. |
| Financial advisors or real estate professionals | Can provide valuable expertise but may involve additional cost or scheduling. |
| Manual calculations | Can be repetitive, error-prone, and difficult to maintain. |

These alternatives are useful, and their actual limitations must be validated through user research.

**DealLens's proposed opportunity** is to combine essential financial calculations, beginner-friendly explanations, and transparent assumptions into a single workflow.

## 5. Goals and Success Criteria

### Product Goals

**Goal 1 — Simplify investment evaluation**

Help users complete a basic financial assessment without manually building spreadsheets or calculating investment formulas.

**Goal 2 — Improve financial transparency**

Clearly display the total estimated acquisition cost, monthly cash flow, and expected rental profitability.

**Goal 3 — Support informed decisions**

Explain the financial metrics and assumptions so users understand the results rather than receiving unexplained numbers.

**Goal 4 — Reduce calculation mistakes**

Provide consistent calculations using documented formulas and validated inputs.

### Proposed Success Criteria

These are initial targets to validate, not proven outcomes.

| Success criterion | Initial target |
|---|---|
| Analysis completion | A user with the required property information can complete a basic analysis in under 5 minutes. |
| Calculation accuracy | All documented calculation test scenarios pass. |
| User comprehension | At least 4 out of 5 usability-test participants can explain the displayed cash flow and yield. |
| Usability | At least 4 out of 5 participants complete an analysis without assistance. |
| Transparency | Every financial result has an accessible explanation of its meaning and assumptions. |

## 6. Scope

The first release will focus on evaluating the financial viability of a single residential rental apartment in Germany.

### Included in the First Version (MVP)

**Property information**

- Manually enter the property purchase price, location, size, and expected monthly cold rent.
- Select the German federal state for relevant purchase-cost assumptions.
- Edit entered property information.

**Acquisition cost calculation**

- Estimate property transfer tax, notary fees, land registration, and brokerage costs.
- Allow users to adjust estimated costs.
- Calculate the total acquisition investment.

**Financing calculation**

- Support purchases with or without mortgage financing.
- Enter available equity, loan interest rate, and initial repayment rate.
- Estimate monthly mortgage payments and required upfront capital.

**Rental profitability calculation**

- Enter recurring landlord expenses.
- Calculate gross rental yield, a clearly defined net rental yield, and estimated monthly cash flow.
- Distinguish operating costs from mortgage payments.

**Investment results**

- Display the main financial metrics in a clear summary.
- Explain how the results were calculated.
- Highlight missing information and assumptions that could materially affect results.

### Expected MVP Outcome

A user can enter the information for one apartment and receive a structured financial overview explaining:

- How much the investment is expected to cost.
- How much capital may be needed upfront.
- Whether estimated rental income covers monthly costs.
- What the calculated investment returns mean.

The application provides financial estimates, not a guaranteed investment outcome or a definitive purchase recommendation.

## 7. Out of Scope

The following capabilities are deliberately excluded from the initial release:

- Automatic property listing extraction or website scraping.
- AI-generated property recommendations.
- Automatic property market valuations.
- Direct mortgage applications or bank integrations.
- Tax return preparation or personalized tax optimization.
- Detailed long-term property appreciation forecasts.
- Complex portfolio management.
- Multi-user or professional property management workflows.
- Automated investment scoring or guaranteed buy/sell recommendations.
- Advanced risk simulation and side-by-side property comparisons.

These features may be reconsidered after validating the core product.

## 8. Assumptions and Open Questions

### Assumptions

1. First-time investors have difficulty combining property purchase costs, financing, and rental profitability calculations.
2. Users are willing to manually enter property information if the process is sufficiently simple.
3. Transparent explanations are valuable to users who are unfamiliar with real estate financial metrics.
4. A focused single-property analysis provides meaningful value without requiring advanced features.
5. Germany-specific calculations will make the application more relevant than a generic investment calculator.

These assumptions require validation rather than being treated as established facts.

### Open Questions

**User needs**
- Which part of property evaluation is most difficult for first-time investors?
- Which financial metrics do they consider essential when making an investment decision?
- Do users primarily want calculations, explanations, or guidance on interpreting results?

**Product behavior**
- Should users be able to save analyses in the first version?
- Should the application support vacant and already-rented apartments differently?
- How should missing or uncertain financial information be presented?

**Financial calculations**
- Which acquisition costs should be estimated automatically?
- What default assumptions, if any, should be used for maintenance and vacancy?
- How should German Hausgeld and recoverable tenant expenses be modeled?
- What is the exact definition of net rental yield in DealLens?

**Validation**
- Which existing applications best solve parts of this problem?
- Can target users complete an analysis more easily with DealLens than with their current method?
- Are the proposed financial outputs sufficient to support an initial investment evaluation?

---

## Product Vision

**DealLens helps first-time property investors understand the financial reality behind a rental apartment before making a purchasing decision.**

The long-term vision is to provide a transparent, beginner-friendly platform for evaluating, comparing, and monitoring real estate investment opportunities.

The initial priority is simpler: **make the financial evaluation of one rental apartment understandable and reliable.**