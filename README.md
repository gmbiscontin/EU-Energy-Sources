# European Energy and Inflation Analysis

## Project Overview:
The project aims to investigate the relationship between energy sources and the rise in electricity prices across key European countries. Specifically, we want to explore whether reducing dependence on gas and oil could be an effective strategy to mitigate the impacts of inflation.

---

## 1. Data Wrangling
- **Data Preparation:**
  - Modified column labels for clarity.
  - Removed countries with missing data for 2020 and 2021.
  - Converted data to numpy64 format for consistency.
  
- **Selected Countries:**
  - The top 12 relevant countries were selected, based on energy consumption (with Romania's consumption as the threshold: 390,887.076 GW/h).
  
- **Final Dataset:**
  - Data reflects the energy mix per country for 2021.

---

## 2. Electricity Price Increment
- **Comparison of Prices:**
  - Analyzed electricity price changes between 2020, 2021, and 2022.
  - Notable variations were found between countries, with some showing a sharp increase.

---

## 3. Fiscal Analysis
- **Electricity Price with Taxes (2021):**
  - Evaluated how taxes influence electricity prices across different countries, with a special focus on the Netherlands.
  
- **Share of Taxes:**
  - Tax contributions to electricity prices were examined, showing their significant role in the final cost.

---

## 4. Energy Mix Analysis
- **Key Findings:**
  - Countries with the highest electricity price increases tend to have a higher share of gas and oil in their energy mix.
  - Countries with lower inflation have diversified energy sources, incorporating nuclear energy, coal, and renewables.

---

## 5. Electricity and Oil Dependency
- **Data Setup:**
  - Monthly data on oil and gas prices was converted to semester averages.
  - Grouped countries based on their energy dependency trends:
    - **Group 1**: Countries dependent on gas and oil, showing a direct correlation between energy prices and inflation.
    - **Group 2**: Countries with diversified energy sources, showing more independence from oil and gas price fluctuations.

- **Regression Analysis:**
  - Price of electricity was statistically linked to gas prices for the first group of countries.
  - Oil was found to have a weaker correlation with electricity price inflation compared to gas.

---

## 6. Conclusions
- **Key Insights:**
  - The rise in raw material prices, especially gas, since 2020, has significantly impacted electricity prices in countries highly dependent on these fuels.
  - Reducing dependence on gas and oil could be an effective strategy to limit the impact of inflation on electricity prices.
  
- **Limitations:**
  - This study only considers one factor (energy source dependence) affecting electricity prices, while other variables (such as fiscal policy) may also play a crucial role.
  - Future studies should consider a more comprehensive analysis, accounting for multiple factors and longer-term fiscal policies.

---

## Sources
- [European Central Bank Projections]([https://www.ecb.europa.eu/pub/projections/html/ecb.projections202203](https://www.ecb.europa.eu/press/projections/html/ecb.projections202203_ecbstaff~44f998dfd7.it.html))
- [Eurostat Energy Dataset](https://ec.europa.eu/eurostat/databrowser/view/nrg_bal_s/default/table?lang=en)
- [Electricity Price for Household Consumers](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Electricity_price_statistics#Electricity_prices_for_household_consumers)
- [Electricity Maps](https://app.electricitymaps.com/zone/PL/72h)
- [Brent Oil Historical Data](https://it.investing.com/commodities/brent-oil-historical-data)
- [Dutch TTF Natural Gas Futures Historical Data](https://it.investing.com/commodities/dutch-ttf-gas-c1-futures-historical-data)
