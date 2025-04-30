📌 Overview
This project analyzes the national supply and demand trends of Brazil’s fuel market (2012–2024), focusing on:

✔  ⛽ Gasoline

✔  🌱 Ethanol

✔  🚛 Diesel

Key questions addressed:

✔ How do ethanol and gasoline compete in Brazil’s flex-fuel market?

✔ What is the maximum storage for fuel in Brazil?

📂 Data Sources

All data is publicly available from Brazil’s National Agency of Petroleum (ANP):

  Ethanol Supply	Monthly production volumes by state (hydrous vs. anhydrous) - https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/producao-de-biocombustiveis
  
  Gasoline/Diesel Supply Refinery output - https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/processamento-de-petroleo-e-producao-de-derivados
  
  Demand Fuel sales by state: https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/vendas-de-derivados-de-petroleo-e-biocombustiveis

🔍 Methodology
Data Collection:

  ✔Automated CSV downloads using Python (requests + pandas).

  ✔Geospatial aggregation (state → national-level trends).

Key Metrics:
  ✔ Price Elasticity: Correlation between ethanol and gasoline demand.

  ✔ Seasonality: Demand fluctuations during harvest/sugar-cane crushing periods.

  ✔ Days on Hand: Estimates how long current inventory levels can meet demand based on average daily consumption.

Tools Used:

Python (pandas, matplotlib, statsmodels)

Power BI (Visualizations)
