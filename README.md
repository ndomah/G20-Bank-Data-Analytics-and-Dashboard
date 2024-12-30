# G20 Bank Data Analytics and Dashboard
## Project Overview
This project demonstrates a comprehensive workflow for exploratory data analysis (EDA) using Python and Tableau. The analysis focuses on G20 countries, exploring economic and social indicators such as GDP, population growth, education, and health metrics. By leveraging dynamic data from the World Bank API, the project creates custom datasets and interactive dashboards to uncover actionable insights.
## Workflow
[Jupyter Notebook](https://github.com/ndomah/G20-Bank-Data-Analytics-and-Dashboard/blob/main/World%20Bank%20Analytics.ipynb)
### 1. Data Extraction
- **World Bank API Integration**: Extracted live data using the wbdata Python library, mapping indicators like GDP, inflation, and life expectancy.
- **Dynamic Retrieval**: Retrieved data for 16 parameters spanning 2015–2020, ensuring relevance and accuracy.
### 2. Data Preparation
- **Cleaning and Structuring**:
  - Filtered data for G20 countries.
  - Standardized date formats and resolved redundancies.
  - Addressed missing values in key indicators such as inflation rates and literacy rates.
- Custom Dataset: Combined all parameters into a single structured dataset for streamlined analysis.
### 3. Data Analysis
- **Descriptive Statistics**: Used Python libraries (Pandas, NumPy) to summarize trends and compute statistical measures.
- **Outlier Detection**: Identified and addressed anomalies using the IQR method.
- **Correlation Analysis**: Created heatmaps and scatterplots to explore relationships between variables like GDP and GNI.
### 4. Data Visualization
- **Tool**: Tableau was used to create interactive dashboards.
- **Key Metrics**: Visualized parameters such as inflation rates, unemployment, trade balances, and foreign direct investment (FDI).
## Final Dashboard
### Dashboard 1: Social and Economic Trends
1. **Inflation Rate Over the Years**
  - **Type**: Line chart.
  - **Insight**: South Africa had the highest inflation, while the UK exhibited a steady decline post-2017.
2. **Unemployment Rate**
  - **Type**: Horizontal bar chart.
  - **Insight**: South Africa faced persistently high unemployment, while other nations showed stability.
3. **Access to Electricity**
  - **Type**: Heatmap.
  - **Insight**: South Africa revealed notable gaps in electricity access, while other countries achieved near-universal coverage.
4. **Efficacy of Government Education Spending**
  - **Type**: Tree map.
  - **Insight**: Identified inefficiencies in education spending, particularly in South Africa and the UK.

![dashboard 1](https://github.com/ndomah/G20-Bank-Data-Analytics-and-Dashboard/blob/main/Dashboard%201.png)
### **Dashboard 2: Economic Dynamics**
1. **GDP vs. Gross Capital Formation**
  - **Type**: Bubble chart.
  - **Insight**: The US dominated GDP, while Canada exhibited balanced capital formation.
2. **Exports vs. Imports**
  - **Type**: Bar chart.
  - **Insight**: Highlighted trade balance disparities, with Canada and the UK maintaining equilibrium.
3. **Mobile Subscriptions vs. GNI**
  - **Type**: Tree map.
  - **Insight**: Showed a positive correlation between digital connectivity and income levels.
4. **FDI Distribution**
  - **Type**: Box plot.
  - **Insight**: Japan showed significant FDI growth, whereas Italy experienced declines.

![dashboard 2](https://github.com/ndomah/G20-Bank-Data-Analytics-and-Dashboard/blob/main/Dashboard%202.png)

[Tableau Public Link](https://public.tableau.com/app/profile/nilesh.domah4236/viz/WorldBankAnalytics_17156157559640/Dashboard2)
## Conclusion
This project highlights the power of integrating Python and Tableau for exploratory data analysis. By leveraging live data from the World Bank API, it provides a dynamic and scalable workflow for analyzing social and economic trends among G20 countries. The interactive dashboards enable users to derive actionable insights, emphasizing disparities in areas like education spending efficacy, FDI distribution, and trade balances. These findings serve as valuable inputs for policymakers and analysts, showcasing the impact of data-driven decision-making.
