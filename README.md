# Micron Three-Statement Model & DCF — May 2026

A fully integrated 3-statement financial model and DCF valuation for Micron Technology (NASDAQ: MU), updated through Q2 FY2026 SEC filings and the May 2026 market environment. The model covers FY2023–FY2025 historical periods and a FY2026–FY2030 five-year forecast, with bottom-up revenue build, integrated cash flow statement, scenario analysis, sensitivity tables, and a discounted cash flow valuation with both perpetuity growth and exit multiple terminal value approaches.

This is the second iteration of the Micron model, updated from the prior October 2025 version to incorporate updated filings, refined modeling methodology, and a DCF valuation. A changelog documenting all material changes from the prior version is included in the repository.

[Link to downloadable model]

## Model Overview

Micron is in the middle of a documented memory upcycle driven by AI infrastructure demand. The central valuation debate is whether the company is structurally re-rating from a cyclical memory business to a durable AI infrastructure cash generator. The DCF outputs frame both sides of that debate:

- **Perpetuity growth (3.0% LTGR)**: $1,076 / share
- **EBITDA exit multiple (13.0x)**: $1,034 / share
- **WACC**: 12.65%
- **Current price (May 26, 2026)**: $895.88

The model captures the structural improvement thesis (HBM mix, long-term supply agreements, AI demand baseline) through elevated near-term margins and a higher mid-cycle floor than prior cycles, while applying a conservative normalization path in FY2028–FY2030.

## Methodology

### Revenue Build

Revenue is built bottom-up by product segment using (1 + bit growth) × (1 + ΔASP) – 1 = revenue growth. DRAM and NAND are modeled separately.

**FY2026 anchors — sourced directly from Q2 FY2026 10-Q:**
- DRAM bit growth: 45%
- DRAM ASP change: +113%
- NAND bit growth: 30%
- NAND ASP change: +100%

**FY2027 anchors** — calendar 2026 industry NAND bit growth of ~20% per management; DRAM held at 20% reflecting cleanroom constraints and HBM trade ratio. ASP growth of +20% DRAM and +15% NAND informed by TrendForce 2027 memory market peak forecast.

**FY2028–FY2030** — normalization phase. Bit growth accelerates as new capacity comes online (Idaho mid-2027, Tongluo FY2028, Singapore H2 2028). ASP compression begins, cushioned by HBM mix and long-term agreements.

### Gross Margin Assumptions

| Year | Gross Margin | Source |
|---|---|---|
| FY2026 | 75% | Q1 actual 56.8%, Q2 actual 74.4%, Q3 guided ~81% — blended weighted average |
| FY2027 | 80% | Pricing peak per TrendForce; HBM mix tailwind |
| FY2028 | 65% | Normalization inflection year |
| FY2029 | 55% | Continued normalization |
| FY2030 | 50% | Structural floor — higher than prior cycles given HBM mix and SCAs |

The FY2030 floor of 50% is materially above historical mid-cycle troughs (~25–30%) reflecting three structural arguments: HBM permanently improves mix; node transitions structurally lower cost per bit; long-term supply agreements reduce spot price volatility. Defensible peer comps include SK Hynix at 50–60%, TSMC structural floor at 45%+, and the Intel 1995–2005 dominance period (50–55% floor).

### Interest & Debt Schedule

LTD steps down from $14,017M at FY2025 reflecting actual paydowns: Q1 FY2026 paydown of $2.7B (term loan + senior notes), Q2 FY2026 paydown of $1.6B (senior notes due 2029 and 2030). Modeled FY2026 paydown of $5B with $2B/yr thereafter, ending FY2030 at $1,017M.

Weighted average interest rate of 5.25% per 10-K Note 12. Interest income calculated at 4.0% on average BOP/EOP cash balances. All interest lines handle circularity via a break switch (Row 7).

### CapEx

- FY2026: $26B (management guidance: above $25B)
- FY2027: $36B (management guidance: construction CapEx +$10B YoY)
- FY2028–FY2030: $40B (modeler cap; no management guidance available beyond FY2027)

### EPS & Valuation

Diluted share counts for historical periods sourced from 10-K Note 26 (FY2023: 1,093M; FY2024: 1,118M; FY2025: 1,125M). FY2023 loss year applies anti-dilution rule. Forecasted diluted shares reflect SBC issuance net of $1,200M annual repurchases (consistent with Q1 + Q2 actuals; CHIPS Act-constrained).

Target P/E progression: 12x FY2026 → 12x FY2027 → 14x FY2028 → 16x FY2029 → 18x FY2030. The counter-intuitive low-multiple-on-peak-earnings pattern reflects standard memory stock valuation behavior at cycle peaks.

### DCF Valuation

**WACC build:**
- Risk-free rate: 4.26% (10-year US Treasury)
- Equity Beta: 1.7 (reflects memory cyclicality with structural moderation)
- Equity risk premium: 5.0%
- Cost of equity: 12.76%
- After-tax cost of debt: 4.38%
- D/V: 1.4% | E/V: 98.6%
- WACC: 12.65%

**Terminal value approaches:**

| Approach | Assumption | TEV | Equity / Share |
|---|---|---|---|
| Perpetuity growth | 3.0% LTGR | $1,209B | $1,076 |
| EBITDA exit multiple | 13.0x | $1,157B | $1,034 |

The 3.0% LTGR sits above long-term US GDP and below historical semiconductor industry growth.

Mid-year convention applied via discount date midpoint between BOP and EOP for each forecast year. FY2026 treated as a stub year reflecting May 26, 2026 valuation date (0.269 of full fiscal year).

### Net Debt Bridge

| Line | Amount | Source |
|---|---|---|
| Long-term debt | $10,059M | Q2 FY2026 10-Q |
| Convertible debt | $0 | Confirmed: no convertibles outstanding |
| Preferred stock | $0 | None outstanding |
| Noncontrolling interests | $0 | All subsidiaries 100% owned |
| Cash & marketable securities | ($16,700M) | Q2 FY2026 prepared remarks |
| Non-marketable equity investments | ($183M) | Q1 10-Q |
| **Net debt** | **($6,824M)** | Net cash position |

### Sensitivity Analysis

Sensitivity tables on equity value per share across two dimensions:

**Perpetuity approach**: WACC (11.6%–13.6%) × Long-term growth rate (2.0%–4.0%)
- Range: $928 (high WACC, low growth) to $1,313 (low WACC, high growth)

**EBITDA approach**: WACC (11.6%–13.6%) × Exit EBITDA multiple (12.0x–14.0x)
- Range: $956 to $1,118

Additional sensitivities on first forecast year net income and diluted EPS across gross profit margin and revenue growth.

## Material Adjustments from Prior Version

**Revenue build** anchored to Q1 and Q2 FY2026 10-Q actuals rather than analyst estimates. FY2026 revenue revised from $54.5B to $111.3B reflecting actual pricing surge and bit growth disclosed in filings.

**Gross margin** revised from 51.6% peak to 75–80% peak, with structural floor of 50% rather than mid-cycle normalization toward 27%. Sourced from blended Q1 actual + Q2 actual + Q3 guidance and structural thesis documented above.

**CapEx** anchored to Q2 FY2026 prepared remarks (FY2027 +$10B YoY construction CapEx) replacing prior Morningstar-sourced assumptions.

**Capital allocation** updated to reflect Q2 FY2026 announcements: 30% dividend increase ($527M → $685M annualized), CHIPS-constrained buybacks at $1,200M annual run rate (vs prior $306M), and active LTD paydown of $5B in FY2026.

**SBC methodology** changed from growing with revenue (which created a 3x mechanical spike) to 10% fixed annual growth. SBC reclassified from Common Stock to Additional Paid-in Capital per standard equity accounting.

**Tax rate** held flat at 16.5% per Q2 FY2026 guidance.

**Interest income formula** corrected to use average BOP/EOP cash balance across all forecast years (prior version used prior year EOP only).

A full changelog documenting all material changes is available in the repository.

## Potential Improvements

**Comparable companies analysis.** A peer multiples analysis incorporating Samsung, SK Hynix, and Western Digital would provide a third valuation triangulation point and is the natural next iteration of this model.

**Cover page, executive summary, and assumptions page.** Extra sheets could be added to allow the model to present more cleanly. These sheets would allow the reader to understand key takeaways and assumptions from the model.

**Scenario expansion.** The current model supports Base, Best, and Weak cases through scenario toggles. An intermediate case between Base and Weak would capture a broader range of probable economic outcomes given the structural debate around memory normalization.

## Data Sources

- Micron Technology FY2025 10-K (filed October 2025)
- Micron Technology Q1 FY2026 10-Q (filed December 2025)
- Micron Technology Q2 FY2026 10-Q (filed March 2026)
- Micron Q1 FY2026 Earnings Call Prepared Remarks
- Micron Q2 FY2026 Earnings Call Prepared Remarks
- Micron Q1 + Q2 FY2026 Earnings Press Releases
- TrendForce Memory Market Outlook (Q1 2026)
- UBS Research Note on Micron (May 26, 2026)

## Acknowledgements

The model and structure is based on Wall Street Prep's Financial Statement Modeling and DCF courses. Learnings from CFA Level I and their financial statement practical skill module helped inform some model updates.
