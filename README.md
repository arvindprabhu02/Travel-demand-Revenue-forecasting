# Hotel Demand Forecasting and Financial Scenario Modeling

This project analyzes hotel booking demand across City and Resort segments and translates forecast outputs into operational and financial decision insights.
The analysis combines time-series forecasting, scenario planning, and financial modeling to support capacity and profitability decisions for travel and platform
businesses.

## Business Problem
Travel platforms and hotel operators face high demand volatility driven by seasonality, cancellations, and booking lead times. Forecasting demand alone is insufficient unless
it is connected to utilization risk and financial outcomes. This project addresses how forecast uncertainty impacts operations and profitability.

## Data Source
The dataset is sourced from a publicly available hotel booking dataset containing reservation-level information for City and Resort Hotels across multiple countries.
It includes booking dates, stay duration, ADR, cancellations, and lead-time attributes.

## Analytical Approach
1. Exploratory Data Analysis to understand demand patterns, cancellations, seasonality, and booking behavior.
2. Time-series forecasting using benchmark models and STL-based decomposition to capture local trends and seasonality.
3. Rolling validation to compare short-term accuracy and justify model selection.
4. Scenario planning (base, upside, downside) to reflect demand uncertainty.
5. Financial modeling to translate demand forecasts into utilization, revenue, profit, and break-even insights using transparent cost assumptions.

## Dashboards
Two role-specific dashboards were developed using Tableau:
- Operations Capacity & Demand Risk Dashboard: focuses on utilization stress and capacity planning under different demand scenarios.
- Financial Performance & Scenario Sensitivity Dashboard: highlights profit sensitivity, break-even thresholds, and downside risk.

## Key Insights
- Resort demand exhibits strong and stable seasonality, while City demand is more volatile and influenced by external shocks.
- Short-term forecasts favor level-based models, while medium-term planning benefits from seasonal decomposition.
- Capacity utilization risk varies significantly across scenarios, especially during peak seasonal periods.
- Financial outcomes are highly sensitive to demand fluctuations, emphasizing the need for scenario-based planning rather than point forecasts.

## Business Recommendations
- Actively manage capacity risk in City Hotels, where high average utilization and frequent stress weeks indicate potential service bottlenecks and lost revenue during peak demand.
- Adopt scenario-based financial planning instead of point forecasts, as profit outcomes vary significantly between downside and upside demand scenarios.
- Avoid fixed capacity expansion in Resort Hotels, leveraging seasonal pricing and cost flexibility to capture upside demand without increasing structural risk.
- Link pricing decisions to utilization thresholds, raising ADR during high-demand periods while using targeted promotions to stabilize demand in low-utilization weeks.
- Integrate demand forecasts directly into operational and financial planning, using stress-week indicators to trigger proactive staffing, inventory, and cost-management actions.

## Tools Used
Python (pandas, numpy, statsmodels, scikit-learn, matplotlib), Tableau

## Disclaimer
Cost assumptions are illustrative and intended to demonstrate financial sensitivity rather than estimate actual hotel profitability.
