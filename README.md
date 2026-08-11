# Indian Renewable Energy IPPs — Comparative DCF Valuation

### Bottom-up FCFF valuation of Adani Green Energy, NTPC Green Energy & ACME Solar Holdings

**Author:** Raghav Rao
**Program:** B.Tech, Mechanical Engineering — IIT Ropar
**Project Type:** Self-directed Equity Research / Financial Modelling Project
**Market Data:** Early August 2026
**Currency:** ₹ Crores unless otherwise stated

---

## 📌 Project Overview

This project evaluates whether the current market valuations of listed Indian renewable energy Independent Power Producers (IPPs) are supported by their underlying capacity-addition plans and future cash flows.

The analysis tests a central hypothesis:

> **Are current market valuations of Indian renewable IPPs pricing in capacity-addition and margin assumptions more aggressive than a bottom-up DCF can support?**

Three companies were selected to represent different risk and business profiles within the sector:

| Company                 | Role in Study                                            |
| ----------------------- | -------------------------------------------------------- |
| **Adani Green Energy**  | Primary company / largest pure-play listed renewable IPP |
| **NTPC Green Energy**   | PSU-backed peer with a lower-risk profile                |
| **ACME Solar Holdings** | Smaller, solar-focused pure-play                         |

The three companies provide a useful comparison across scale, sponsorship, capacity pipeline and operating maturity.

---

# 🎯 Key Findings

The DCF analysis produces a differentiated conclusion rather than treating the renewable-energy sector as a single valuation story.

| Company                 | Current Price | Base DCF Value / Share | Base-Case View  |
| ----------------------- | ------------: | ---------------------: | --------------- |
| **Adani Green Energy**  |      ₹1,387.5 |                   ₹136 | **Overvalued**  |
| **NTPC Green Energy**   |         ₹91.3 |               Negative | **Overvalued**  |
| **ACME Solar Holdings** |          ₹366 |                   ₹601 | **Undervalued** |

### Scenario Analysis

| Company                     |   Bear |     Base |     Bull |
| --------------------------- | -----: | -------: | -------: |
| **Adani Green — EV (₹ Cr)** | 63,706 | 1,13,363 | 2,12,729 |
| **NTPC Green — EV (₹ Cr)**  |  6,304 |   19,670 |   47,101 |
| **ACME Solar — EV (₹ Cr)**  | 43,893 |   62,655 |   93,129 |

The model finds that **Adani Green and NTPC Green remain below current market prices even under the Bull scenario**, while ACME Solar's Base and Bull cases exceed its current market price.

---

# 🧮 Valuation Methodology

The project uses a **Free Cash Flow to Firm (FCFF) Discounted Cash Flow framework**.

### FCFF

The model calculates:

```text
FCFF = NOPAT + D&A − Capex − Change in Working Capital
```

Where:

* **NOPAT** = EBIT − Tax
* **D&A** is added back as a non-cash expense
* **Capex** is derived from planned capacity additions × cost per MW
* **Change in Working Capital** is modelled as a percentage of the change in revenue

FCFF is used because it represents cash available to both debt and equity holders and allows comparison between companies with materially different capital structures.

---

# 🏗️ Bottom-Up Capex Modelling

A key feature of this project is that forward Capex is **not simply extrapolated from historical Capex**.

Instead, a company-specific or sector-based **cost-per-MW** assumption is derived and applied to future capacity additions.

### Adani Green

FY26 disclosed:

* Capacity added: **5,100 MW**
* Capex incurred: **₹30,365 Cr**
* Cost per MW: **₹5.95 Cr**

This FY26 rate is carried forward into the forecast.

### NTPC Green

Because an explicit Capex-incurred figure was unavailable, **Cash Used in Investing Activities** was used as a proxy.

FY25:

* Capacity added: **2,977 MW**
* Investing cash flow: **₹17,793 Cr**
* Implied cost/MW: **₹5.98 Cr**

The FY25 figure is used as the more conservative forward assumption.

### ACME Solar

A company-specific cost/MW could not be independently derived from the available source material.

The model therefore uses:

**₹5.97 Cr/MW**

This represents the average of:

* Adani Green FY26: ₹5.95 Cr/MW
* NTPC Green FY25: ₹5.98 Cr/MW

This is explicitly treated as the project's **largest data-quality caveat**.

---

# 📈 Forecast Framework

Each company is modelled from FY27 through FY35.

The forecast incorporates:

* Operational capacity
* Capacity additions
* Revenue
* EBIT
* Effective tax rate
* NOPAT
* D&A
* Capex
* Change in working capital
* FCFF
* Present value of FCFF

The model uses a **0.85 revenue ramp factor** for newly added capacity to account for partial-year contribution.

Terminal growth is set at **5%** across the three models.

---

# 💰 WACC & Terminal Value

The discount rate is calculated using a CAPM-based cost of equity:

```text
Cost of Equity = Risk-Free Rate + Beta × Equity Risk Premium
```

WACC then incorporates:

* Cost of equity
* After-tax cost of debt
* Market-value debt/equity weights

Base-case WACC assumptions:

| Company     |      WACC |
| ----------- | --------: |
| Adani Green | **10.0%** |
| NTPC Green  | **10.6%** |
| ACME Solar  | **10.3%** |

Terminal value is calculated using the Gordon Growth Model:

```text
Terminal Value = FCFF₍FY36₎ / (WACC − g)
```

with a **5% terminal growth rate**.

---

# 📊 Company-Level Results

## Adani Green Energy

The model assumes:

* FY26 operational capacity: **19,294 MW**
* 2030 target: **50,000 MW**
* Cost/MW: **₹5.95 Cr**
* WACC: **10.0%**
* Terminal growth: **5.0%**

The model forecasts negative FCFF through FY30 due to heavy capacity expansion, followed by positive FCFF as the build-out pace slows.

**Base Enterprise Value: ₹1,13,363 Cr**.

---

## NTPC Green Energy

The model uses a FY27 annualised revenue run-rate because the company significantly increased capacity during the year.

Key assumptions:

* Base capacity: **10,671 MW**
* FY30 target: **26,989 MW**
* Cost/MW: **₹5.98 Cr**
* WACC: **10.6%**
* Terminal growth: **5.0%**

The large contracted and awarded pipeline creates significant near-term Capex requirements relative to the company's current revenue base.

**Base Enterprise Value: ₹19,670 Cr**.

---

## ACME Solar Holdings

Key assumptions:

* Base capacity: **2,990 MW**
* FY30 target: **8,070 MW**
* Cost/MW: **₹5.97 Cr sector proxy**
* WACC: **10.3%**
* Terminal growth: **5.0%**

Because its required Capex is smaller relative to its revenue base, FCFF becomes positive earlier than in the Adani Green and NTPC Green models.

**Base Enterprise Value: ₹62,655 Cr**.

---

# 🐻 Base 🐂 Scenario Analysis

The model explicitly tests the valuation against changes in the most important operating and valuation assumptions.

### Bear Case

* WACC: **+1 percentage point**
* Cost/MW: **+15%**
* Capacity-addition pace: **0.8×**

### Base Case

* Current model assumptions

### Bull Case

* WACC: **−1 percentage point**
* Cost/MW: **−15%**
* Capacity-addition pace: **1.2×**

This provides a range of outcomes instead of relying on a single-point DCF estimate.

---

# 🔎 Hypothesis Test

### Adani Green & NTPC Green

Both companies remain **overvalued relative to the model's intrinsic value across all three scenarios**.

Even the Bull case — incorporating lower WACC, cheaper Capex and faster capacity additions — does not produce an intrinsic value sufficient to justify current market prices.

This supports the project's hypothesis that current valuations are incorporating expectations more optimistic than those supported by the bottom-up cash-flow model.

### ACME Solar

ACME produces the opposite result.

Its Base Case intrinsic value is above the current market price, while even the Bear Case is approximately fair.

This suggests that the valuation gap may **not be uniform across Indian renewable IPPs** and may instead be concentrated among larger, higher-profile names.

---

# ⚠️ Key Limitations

The model deliberately documents its major limitations:

### 1. Beta uncertainty

WACC depends on assumed beta values, particularly for Adani Green, where different data providers show substantial disagreement.

### 2. Net Debt

For NTPC Green and ACME Solar, total borrowings are used as a proxy for net debt because a clean cash-netted figure was not separately available in the sourced data.

### 3. ACME Solar Capex

ACME Solar's cost/MW is a **sector-average proxy rather than a company-disclosed figure**.

### 4. Shares Outstanding

Shares outstanding are back-calculated from market capitalization and share price, making the per-share valuations directional rather than precise price targets.

### 5. Capacity Build-Out

The model uses relatively flat annual capacity additions during the ramp phase rather than reproducing the exact accelerating historical build-out pattern.

### 6. Terminal Value

Terminal Value represents a significant portion of Enterprise Value, making the results particularly sensitive to **WACC and terminal growth assumptions**.

---

# 🛠️ Skills Demonstrated

This project demonstrates:

* **Financial modelling**
* **DCF valuation**
* **FCFF forecasting**
* **WACC / CAPM**
* **Terminal value modelling**
* **Scenario analysis**
* **Sensitivity analysis**
* **Company and sector research**
* **Bottom-up Capex modelling**
* **Equity valuation**
* **Financial statement analysis**
* **Investment thesis development**
* **Risk and limitation assessment**
* **Excel modelling**

---

# 📂 Repository Structure

```text
Indian-Renewable-IPP-DCF/
│
├── README.md
│
├── DCF_Valuation_Report.pdf
│
├── models/
│   ├── Adani_Green_DCF.xlsx
│   ├── NTPC_Green_DCF.xlsx
│   └── ACME_Solar_DCF.xlsx
│
├── research/
│   └── data_sources.md
│
└── screenshots/
    ├── valuation_comparison.png
    ├── scenario_analysis.png
    └── fcff_model.png
```

---

# 📚 Data & Sources

The project uses publicly available company and market information, including:

* Company investor presentations
* Company results and financial disclosures
* Screener.in financial data
* Market capitalization and share-price data
* Company capacity and project pipeline disclosures

All major assumptions are documented alongside their respective source/basis in the report.

---

# 📌 Conclusion

This project finds a **clear valuation divergence within India's renewable IPP sector**.

The bottom-up DCF suggests that:

> **Adani Green Energy and NTPC Green Energy require substantially more optimistic assumptions than those used in the base model to justify their prevailing market valuations, while ACME Solar appears comparatively more reasonably valued.**

The analysis therefore suggests that renewable-energy valuations should not be evaluated solely on headline capacity targets. **Capex intensity, timing of cash flows, cost of capital and the ability to convert capacity additions into sustainable FCFF are equally important.**

---

## ⚠️ Disclaimer

This project is for **educational and portfolio purposes only** and does not constitute investment advice or a recommendation to buy or sell any security.

The valuations are based on assumptions, estimates and publicly available information as of early August 2026. Actual financial and operating outcomes may differ materially from the assumptions used in the model.
# Indian-Renewable-Energy-IPPs-Comparative-DCF-Valuation
