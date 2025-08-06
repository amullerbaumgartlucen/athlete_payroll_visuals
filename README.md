# 📊 Athlete Payroll Trends and Forecasting by League and Country

This project explores how professional athlete payrolls have evolved across different leagues and countries. Using Tableau for interactive visualizations and R for statistical forecasting, the analysis provides both historical trends and forward-looking projections of athlete compensation.

---

## 🧩 Project Overview

The dataset includes payroll information by country, league, and individual athletes. The goals of this project were to:

- Visualize payroll distribution across sports and countries
- Analyze changes in average pay per player over time
- Forecast future payroll levels using past trends and growth rates

---

## 🖥️ Tools and Technologies

- **Tableau** — for interactive dashboards and visual storytelling  
- **R** — for statistical modeling and payroll growth forecasts  
- **R packages used:** `ggplot2`, `forecast`, `dplyr`

---

## 📈 Key Visualizations

1. **Average Payroll per Player by League**  
   Used a fixed LOD expression:  
   `{ FIXED [League] : MEDIAN([Average Annual pay per player]) }`  
   This helps compare leagues fairly by controlling for player count variability.

2. **Time-Series Payroll Trends**  
   Showed how player payroll has evolved in each league over recent years.

3. **Forecasting Future Payroll**  
   Leveraged R to model payroll growth using historical 5-year percentage changes.  
   Models like ARIMA were tested to project forward values with confidence intervals.

---

## 🔍 Key Insights

- Leagues without salary caps (like some European football leagues) showed the most aggressive payroll growth
- Certain countries demonstrated disproportionately high pay-per-player due to a concentration of high-value contracts
- Forecasts suggest continued growth in athlete pay, with widening gaps between leagues depending on market size and cap structure
