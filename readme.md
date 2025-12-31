# Oil Market Stress Scenarios and Price Sensitivity Analysis

## Overview

This project provides an analytical assessment of current conditions in the global oil market, with a focus on supply-demand balances, OPEC+ policy sensitivity and key geopolitical stress scenarios. The analysis aims to identify the main factors that may drive crude oil prices higher or lower, assess how these drivers are transmitted into prices, and evaluate the potential market outcomes under different scenarios.

The project combines institutional data with high-frequency market information to construct a forward-looking, scenario-based view of oil market risks over the 2024-2026 horizon.

---

## Objectives

The key objectives of this project are to:

- Analyse global oil supply and demand dynamics across OECD and non-OECD regions  
- Assess the role of OPEC+ as a marginal supplier through the **call on OPEC+ crude**  
- Evaluate the sensitivity of oil prices to policy-driven supply responses  
- Examine geopolitical stress scenarios and their potential impact on price volatility  
- Translate market fundamentals into trading and risk-relevant implications  

---

## Project Structure

The analysis is organised as follows:

1. **Executive Summary**  
   A concise overview of current market conditions, key risks and price drivers.

2. **Global Supply-Demand Balance**  
   - OECD demand trends  
   - US and European demand dynamics  
   - OECD and non-OECD supply outlook  
   - Demand for DoC crude (Call on OPEC+)  

3. **Stress Scenario Analysis**  
   - Tanker disruptions and Venezuelan supply risks  
   - Escalation of geopolitical tensions related to Ukraine  

4. **Price Sensitivity Analysis**  
   - Oversupply-driven policy response scenarios  
   - Potential price repricing under coordinated OPEC+ action  

5. **Conclusion: Trading & Risk Implications**  
   Market-relevant takeaways focused on positioning, volatility and policy risk.

---

## Data Sources

### Institutional and Official Data

- **OPEC Monthly Oil Market Report (December 2025)**  
  Used for global supply-demand balances, OPEC vs non-OPEC production trends and medium-term outlooks.

- **EIA Weekly Petroleum Status Report (December 2025)**  
  Used for US crude oil production, imports, exports, inventories and short-term market signals.

- **Offshore Energies UK (OEUK) - Business Outlook Report 2025**  
  Used for UK and North Sea supply trends and regional energy security context.

### Market News and Geopolitical Context

Market news sources were used qualitatively to contextualise short-term price movements, geopolitical risk premiums and stress scenarios, particularly related to Ukraine and Venezuelan crude flows.

*Note: Market news sources are used for qualitative context and do not replace primary institutional data.*

---

## Charts and Visual Analysis

The repository includes a set of charts designed to support the analytical narrative, including:

- **Total OECD oil demand trends (2024-2026)**  
- **Total OECD non-DoC liquids production**  
- **Call on OPEC+ crude (Demand for DoC crude)**  
- **DoC crude production levels**  
- **DoC crude supply balance (production minus demand)**  

Charts are generated using Python and are intended to visually highlight structural trends, policy sensitivity and balance-driven risks rather than short-term price forecasting.

---

## Methodology

- Time horizon: **2024-2026** (actuals, estimates and forecasts)  
- Frequency:
  - Weekly data for short-term stress signals (EIA)  
  - Monthly data for structural trends (OPEC)  
- Scenario-based approach rather than point forecasts  
- Emphasis on **policy-driven and sentiment-driven price dynamics**, not only physical disruptions  

---

## Key Takeaways

- Rising non-OPEC supply and inventory accumulation continue to weigh on baseline price dynamics  
- The call on OPEC+ crude increases into 2025-2026, reinforcing OPEC+ pricing power  
- Price risks are asymmetric, with upside tail risks driven primarily by coordinated policy action  
- Geopolitical events are more likely to affect volatility than medium-term price direction  
- Trading opportunities are expected to emerge from policy signals, balance shifts and risk repricing  

---

## Repository Structure

- `data/` – Raw datasets used in the analysis (OPEC, EIA and related source files)  
- `figures/` – Charts and visual outputs generated using matplotlib  
- `notebooks/` – Jupyter notebooks used for data processing, analysis and visualisation  
- `reports/` – Final analytical report and supporting source documents  
- `readme.md` – Project overview, methodology and documentation  
- `.gitignore` – Git ignore rules for environment-specific files
---

## Disclaimer

This project is for educational and analytical purposes only and does not constitute investment advice. All views expressed are based on publicly available data and are subject to change as market conditions evolve.



```python
