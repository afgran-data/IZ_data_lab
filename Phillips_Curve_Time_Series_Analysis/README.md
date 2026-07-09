# Phillips Curve Series: Inflation vs. Unemployment

This repository explores the **Phillips Curve**, an economic concept describing the relationship between inflation and unemployment in the United States.

Using historical data from the Federal Reserve Economic Data (FRED), the series compares three commonly used measures of inflation:

1. **Headline CPI vs. Unemployment**
2. **Core CPI vs. Unemployment**
3. **Core PCE vs. Unemployment (Federal Reserve's Preferred Measure)**

Each chart displays monthly observations since the 1950s, illustrating how inflation, unemployment, and monetary policy have evolved across different economic environments.

---

# Phillips Curve Series (1/3): Headline CPI

<p align="center">
  <img src="figures/Inflation_vs_Unemployment_with_Path.png" width="850">
</p>

## Overview

Inflation and unemployment have a complex relationship that economists refer to as the **Phillips Curve**.

This analysis examines that relationship using **Headline Consumer Price Index (CPI)** inflation and the U.S. unemployment rate.

Each point represents a monthly observation, while the color of each point reflects the **Federal Funds Rate**, providing additional context for changes in monetary policy over time.

---

## Major Economic Periods

Several important economic regimes are clearly visible:

- 1970s stagflation
- Volcker disinflation (1980s)
- Great Moderation (1990s–2019)
- COVID-19 labor market shock (2020)
- Post-pandemic inflation surge (2021–2022)

Headline CPI includes all consumer prices, including food and energy, making it the inflation measure most directly experienced by households.

---

## Key Takeaway

Headline CPI captures the inflation consumers experience most directly, but it is also the most volatile measure because food and energy prices can change rapidly due to supply shocks, geopolitical events, and commodity price fluctuations.

---

## Limitation

Headline CPI can fluctuate sharply even when underlying inflation trends remain relatively stable because food and energy prices are highly volatile.

---

# Phillips Curve Series (2/3): Core CPI

<p align="center">
  <img src="figures/CoreCPI_vs_Unemployment_with_Path.png" width="850">
</p>

## Overview

Not all inflation measures tell the same story.

This analysis examines the Phillips Curve using **Core CPI**, which excludes food and energy prices to better capture underlying inflation trends.

By removing these highly volatile components, economists can more easily observe inflation driven by wages, housing, and broader domestic economic conditions.

---

## Major Economic Periods

The same macroeconomic cycles remain visible:

- 1970s inflation shock
- Volcker tightening cycle
- Great Moderation
- COVID-19 labor market shock
- Post-pandemic inflation surge

Compared with Headline CPI, Core CPI generally exhibits smoother and more persistent inflation dynamics.

---

## Key Takeaway

Core CPI provides a clearer view of underlying inflation by reducing short-term volatility. It is particularly useful for analyzing persistent inflation pressures within the domestic economy.

---

## Limitation

Housing costs represent a significant portion of Core CPI and often respond slowly to changing economic conditions. As a result, Core CPI may appear more persistent than current real-time inflation pressures.

---

# Phillips Curve Series (3/3): Core PCE (Federal Reserve's Preferred Measure)

<p align="center">
  <img src="figures/CorePCE_vs_Unemployment_with_Path.png" width="850">
</p>

## Overview

The Federal Reserve primarily evaluates inflation using **Core Personal Consumption Expenditures (Core PCE)** rather than CPI.

This analysis examines the Phillips Curve using Core PCE inflation together with the U.S. unemployment rate.

Core PCE differs from CPI because it:

- Reflects changes in consumer spending behavior
- Uses a broader basket of goods and services
- Produces smoother inflation trends over time

Because of these characteristics, the Federal Open Market Committee (FOMC) closely monitors Core PCE when evaluating progress toward its long-run inflation objective.

---

## Major Economic Periods

The same major macroeconomic episodes appear throughout the historical record:

- 1970s inflation crisis
- Volcker-era disinflation
- Great Moderation
- Pandemic labor market disruption
- Post-pandemic inflation surge

---

## Key Takeaway

Core PCE provides one of the clearest views of the underlying inflation trend and is the inflation measure most closely monitored by the Federal Reserve when making monetary policy decisions.

---

## Limitation

Because Core PCE accounts for substitution in consumer spending patterns, it generally reports slightly lower inflation than CPI and may understate the price increases experienced directly by households.

---

# Data Sources

- **Federal Reserve Economic Data (FRED)**
  - Consumer Price Index (CPI)
  - Core Consumer Price Index (Core CPI)
  - Core Personal Consumption Expenditures Price Index (Core PCE)
  - Civilian Unemployment Rate (UNRATE)
  - Effective Federal Funds Rate (FEDFUNDS)

---

# Purpose

The objective of this series is to visualize how the relationship between inflation and unemployment has evolved over more than seven decades while highlighting the influence of monetary policy across different economic regimes.

Rather than serving as a forecasting model, these analyses provide historical context for understanding how different measures of inflation behave throughout business cycles and why policymakers often rely on multiple inflation indicators when assessing the economy.
