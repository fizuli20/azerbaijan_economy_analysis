🇦🇿 Azerbaijan Macroeconomic & Geopolitical Impact Analysis (2005–2026)
This repository contains a deep-dive, data-driven analysis of Azerbaijan's macroeconomic indicators, focusing on the relationship between global oil markets and domestic economic health. The project specifically corrects previous modeling errors by grounding the analysis in verified, real-world data from official institutional sources and applying realistic geopolitical frameworks.

📊 Project Overview
The analysis is broken down into four core Jupyter Notebooks, each targeting a specific economic pillar:

1. Oil Price vs. GDP Correlation Analysis (01_oil_gdp_correlation.ipynb)

Core Logic: Evaluates the historical dependency of Azerbaijan's GDP on global Brent crude oil prices from 2005 to 2024.

Data Corrections: Stripped out unverified 2025-2026 data. Aligned GDP, CPI, and oil export share figures with official World Bank and IMF statistics.

Methodology: Utilizes time-series comparisons and Ordinary Least Squares (OLS) regression.

Key Findings: The OLS model reveals an R² score of 0.5088, indicating that approximately 51% of Azerbaijan's GDP variance is directly explained by Brent crude prices. Every $1 increase in Brent correlates to an approximate $0.59 billion increase in GDP.

2. Purchasing Power & Wage Analysis (02_purchasing_power.ipynb)

Core Logic: Assesses the true purchasing power of citizens by comparing nominal wage growth against cumulative inflation (CPI) from 2019 to 2024.

Data Corrections: Fixed nominal wage and inflation rates to match the State Statistical Committee (DSK) and World Bank data, rectifying a previous model that severely underestimated the 2024 real index.

Methodology: Calculates a Base-100 index (starting in 2019) to track nominal wages, cumulative CPI, and real wage indices over a 5-year period.

Key Findings: Despite a massive inflation shock in 2022 (13.85%) that stagnated real wages, subsequent wage growth and inflation stabilization (dropping to 2.1% in 2024) resulted in a net positive real purchasing power increase of +17.8% compared to 2019.

3. Geopolitical Impact: March 2026 Strait of Hormuz Crisis (03_war_impact.ipynb)

Core Logic: Models the specific impact of the ongoing Middle Eastern geopolitical crisis on Azerbaijan's oil revenues and broader economy.

Geopolitical Context: Following the outbreak of military conflict between the US, Israel, and Iran on February 28, 2026, Iran effectively closed the Strait of Hormuz. Tanker traffic through this vital global energy chokepoint plummeted by approximately 70%, and multiple commercial vessels have been attacked.

Market Shock: Brent crude prices surged from pre-crisis levels of roughly $75-$80 per barrel to highs of over $110 per barrel in early March, before stabilizing around the $98-$105 mark in late March 2026.

Azerbaijan's Strategic Advantage: Unlike Gulf states suffering from the blockade, Azerbaijan exports its oil via the Baku-Tbilisi-Ceyhan (BTC) pipeline directly to the Mediterranean. Consequently, Azerbaijan is bypassing the disruption and capitalizing on the price surge as an external supplier.

Economic Windfall vs. Policy: The Azerbaijani government's 2026 state budget conservatively projected oil at $65 per barrel to deliberately shift focus toward non-oil sector growth, aiming for non-oil revenues to account for 42.6% of the budget. With Brent trading well above this baseline, Azerbaijan is experiencing a significant revenue windfall.

Cascading Risks: While oil revenues rise, the blockade impacts broader Gulf logistics, increasing the risk of imported inflation for food, technology, and fertilizers.

4. Advanced Modeling & Stress Testing (04_advanced_modeling.ipynb)

Core Logic: Analyzes the resilience of the non-oil sector and conducts a macroeconomic stress test for 2026 based on distinct global scenarios.

Data Corrections: Removed faulty rolling-window correlations. Grounded the 2026 baseline in actual 2024 GDP data ($74.32B) and IMF growth forecasts.

Methodology: Evaluates diversification via scatter plots of Brent prices vs. Non-oil GDP growth. Applies scenario-based forecasting to predict 2026 GDP and net revenue/inflation effects.

Key Findings: The non-oil sector shows a weak correlation with oil prices, indicating growing economic independence. Azerbaijan's GDP growth is projected to be in the range of 3-3.5% in 2026.

📈 2026 Executive Stress Test Scenarios
Based on the advanced modeling notebook and real-time market data, here is the projected economic outlook for 2026 depending on global oil market behavior:

Scenario	Brent Crude Price	2026 GDP Forecast	Primary Macro Risk
Hormuz Escalation (Current)	~$100–$110 / bbl	~$82.0 Billion	High import inflation
Status-Quo / Ceasefire	~$82–$87 / bbl	~$78.0 Billion	Minimal macroeconomic change
Price Drop (Long-term)	~$60–$65 / bbl	~$74.0 Billion	Budget deficit if non-oil growth stalls
