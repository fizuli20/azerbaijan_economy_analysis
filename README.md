# Azerbaijan Economy Analysis: Oil, GDP, Purchasing Power, Diversification, and 2026 War-Stress Scenario

> **A data storytelling project on Azerbaijan’s economy using real historical data (2005–2024) and a clearly labeled 2026 scenario model.**  
> This repository analyzes how oil prices relate to Azerbaijan’s GDP, how inflation affected purchasing power, whether non-oil growth is becoming more resilient, and how a March 2026 Hormuz escalation scenario could affect Azerbaijan.

## Why this project matters

Azerbaijan is often described as an oil-dependent economy, but that sentence is too simple.

This project tries to answer four more precise questions:

1. **How strongly is Azerbaijan’s GDP linked to Brent oil prices?**
2. **Did inflation erode wage gains and purchasing power in recent years?**
3. **Is non-oil growth still highly dependent on oil, or is diversification improving?**
4. **If regional conflict pushes oil prices up, does Azerbaijan automatically lose — or does the effect depend on export routes and inflation channels?**

The goal is not only visualization. The goal is to build a **clean, transparent, and defensible analytical narrative**.

---

## Main findings

### 1) Oil still matters a lot, but not perfectly
- The historical correlation between **Brent** and **Azerbaijan GDP** is **0.71** for 2005–2024.
- A simple OLS fit gives approximately **R² = 0.51**, which means oil explains a large share of GDP variation, but not all of it.
- This is important: **oil matters structurally**, but Azerbaijan’s economy is **not a one-variable story**.

### 2) Export structure remains heavily oil-weighted
- Oil and gas make up roughly **90%+ of total exports** across the long period shown.
- The charted average is around **92%**, confirming a high external dependence on hydrocarbons.
- So even if domestic activity diversifies gradually, **external earnings are still dominated by energy**.

### 3) Purchasing power was hit hardest by the 2022 inflation shock
- Real wage dynamics were much weaker than nominal wage growth during the inflation spike.
- The analysis shows that **2022 was the key squeeze year**: wages increased on paper, but inflation absorbed much of the gain.
- By 2024, with inflation cooling, **real purchasing power recovered** more clearly.

### 4) Non-oil growth shows signs of resilience
- In the diversification notebook, **non-oil growth outperforms total GDP growth** in several recent years.
- The 2024 note highlights roughly **6.9% non-oil sector growth**.
- A short-sample relationship between Brent and non-oil growth is still positive, but the project’s interpretation is careful:  
  **non-oil activity may still benefit indirectly from oil income, yet it is no longer reasonable to describe it as mechanically identical to oil.**

### 5) The March 2026 conflict scenario is not “Azerbaijan loses because war”
This is the most important framing correction in the project.

A simplistic interpretation would say:
> Middle East war → oil shock → Azerbaijan suffers.

This repository argues that the mechanism is more nuanced:

- Azerbaijan exports crude mainly through the **BTC pipeline**, not through the Strait of Hormuz.
- So a Hormuz disruption does **not automatically block Azerbaijan’s oil exports**.
- If Brent rises sharply, Azerbaijan can benefit through **higher export revenue**.
- The **main downside risk** is **imported inflation**, especially through logistics, trade channels, and external price transmission.

That is why the war notebook is framed as:
> **positive oil-price effect + inflation risk**,  
not “direct export collapse”.

---

## Repository structure

### `01_oil_gdp_correlation.ipynb`
Focus:
- GDP vs Brent historical relationship
- correlation matrix
- scatter + regression
- oil export share context
- growth-rate comparison

Key message:
> Azerbaijan’s GDP remains strongly connected to oil prices, but correlation is not destiny and should not be overstated.

---

### `02_purchasing_power.ipynb`
Focus:
- nominal wage growth
- cumulative inflation
- real wage index
- GDP per capita (PPP basis)

Key message:
> Paper income gains do not equal real welfare gains. Inflation, especially in 2022, materially changed the story.

---

### `03_war_impact.ipynb`
Focus:
- March 2026 Hormuz escalation framing
- Brent dynamics before and during the shock
- Azerbaijan’s likely monthly oil revenue implication
- correct transmission mechanism

Key message:
> Azerbaijan is better understood as a **net oil-price beneficiary with inflation exposure**, not as a direct victim of Hormuz export disruption.

---

### `04_advanced_modeling.ipynb`
Focus:
- diversification dynamics
- non-oil growth vs total growth
- 2026 scenario stress test
- escalation / base / price-drop comparison

Key message:
> The economy is still oil-sensitive, but the right way to model this is through transparent scenarios, not hidden assumptions or fake “future real data”.

---

## Visual outputs

This repository includes the following generated figures:

- `azerbaijan_correlation_matrix_2005_2024.png`
- `azerbaijan_oil_gdp.png`
- `diversification.png`
- `purchasing_power.png`
- `stress_test.png`
- `war_impact.png`

These visuals are designed for:
- GitHub presentation
- LinkedIn storytelling
- policy/economics discussion
- portfolio demonstration for data analysis roles

---

## Methodology

### Data philosophy
A major strength of this project is that it explicitly separates:

- **real historical data**
from
- **forecast / scenario assumptions**

This matters because many student projects blur those two.

In this repository:
- **2005–2024** is treated as historical data in the oil-GDP analysis.
- **2019–2024** is treated as the valid window for purchasing power and diversification charts.
- **2026 values are clearly labeled as scenarios / forecasts**, not real observations.

### Analytical methods used
- descriptive trend analysis
- correlation analysis
- regression / OLS summary
- comparative index construction
- scenario analysis
- economic interpretation of transmission channels

### Style choices
The project is intentionally designed to be:
- visually readable
- analytically honest
- understandable for non-technical readers
- still credible for recruiters, instructors, and analysts

---

## What makes this project stronger than a typical student notebook

This project does **not** only plot numbers.

It also corrects common analytical mistakes such as:
- mixing forecasts with historical observations
- overstating causal claims from simple correlations
- using wrong economic transmission logic
- treating all regional shocks as uniformly negative
- hiding assumptions in scenario modeling

A core theme of this repository is:
> **better framing leads to better analysis**

---

## Key numbers highlighted in the project

- **GDP–Brent correlation:** ~**0.71**
- **Scatter OLS fit:** **R² ≈ 0.51**
- **Oil & gas share in exports:** average around **92%**
- **2024 Azerbaijan GDP:** ~**$74.3B**
- **2024 PPP GDP per capita:** ~**$25,089**
- **2024 non-oil growth:** ~**6.9%**
- **Stress-test 2026 GDP scenarios:** roughly  
  - **$82B** in escalation / high-oil case  
  - **$77–78B** in status-quo case  
  - **$74–75B** in lower-oil case  

---

## Limitations

This project is analytical, not predictive certainty.

Important limitations:
- Correlation does not prove causation.
- Short windows (especially for diversification analysis) should be interpreted carefully.
- The 2026 war-impact section is a **scenario framework**, not a claim that any exact path will happen.
- Monthly oil revenue effects are simplified and should not be read as a full fiscal model.
- Imported inflation effects may arrive with lags and through multiple channels not fully modeled here.

---

## Data sources referenced in the notebooks

- **World Bank WDI**
- **IMF**
- **BP Statistical Review / energy reference series**
- **State Statistics Committee of Azerbaijan**
- **CBAR**
- **Reuters / energy market reporting**
- Other clearly cited public macro references where relevant

Please check each notebook for the exact context and variable usage.

---

## How to run

1. Clone the repository
2. Open the notebooks in Jupyter
3. Install the standard Python data stack if needed:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn
   - scipy

Then run each notebook in order:

1. `01_oil_gdp_correlation.ipynb`
2. `02_purchasing_power.ipynb`
3. `03_war_impact.ipynb`
4. `04_advanced_modeling.ipynb`

---

## Who this project is for

This project is useful for:
- recruiters reviewing data portfolios
- students interested in economic analytics
- anyone learning how to combine charts with economic reasoning
- readers who want a simple but serious explanation of how oil, inflation, and geopolitics can affect Azerbaijan

---

## Suggested GitHub subtitle

**Data analysis project exploring Azerbaijan’s oil dependence, purchasing power, diversification trends, and a transparent 2026 conflict stress scenario.**

---

## Author note

This project reflects a style of analysis I care about:
- clean visuals
- real data where available
- explicit assumptions where forecasts are necessary
- interpretation that respects economic logic

If you find the project useful, feel free to fork it, reference it, or discuss the results.
