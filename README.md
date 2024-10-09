# Unemployment Analysis in India During COVID-19 👩🏽‍🔧

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) 
![Pandas](https://img.shields.io/badge/pandas-1.2.4-orange)
![NumPy](https://img.shields.io/badge/numpy-1.19.2-orange)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-orange)
![Seaborn](https://img.shields.io/badge/seaborn-0.11.1-orange)

## Project Overview

This project provides an in-depth analysis of unemployment trends in India, with a focus on the impact of the COVID-19 pandemic. The dataset includes both pre-lockdown and lockdown periods, allowing us to uncover insights into how various states were affected in terms of unemployment, labor participation, and workforce challenges.

## Dataset Information

- **Source:** The dataset is available on both GitHub and Kaggle.
- **Key Columns:**
  - `Region`: The state or region.
  - `Date`: Date of observation.
  - `Frequency`: Data frequency (monthly or otherwise).
  - `Estimated Unemployment Rate (%)`: Percentage of unemployment.
  - `Estimated Employed`: Number of employed individuals.
  - `Estimated Labour Participation Rate (%)`: Labor force participation percentage.
  - `Area`: Specifies whether the region is rural or urban.

## Data Analysis and Visualization

This analysis breaks down unemployment rates, labor participation, and employment trends by state. A comparison between pre-lockdown and lockdown periods sheds light on the pandemic's effect on India's economy.

### Key Insights

1. **COVID-19 Lockdown Impact:**
   - A sharp rise in the unemployment rate during the lockdown period, indicating significant labor market disruption.
   
2. **State-Wise Analysis:**
   - **Pre-Lockdown:** Tripura, Haryana, and Himachal Pradesh had the highest unemployment rates.
   - **During Lockdown:** Puducherry, Jharkhand, and Bihar showed the largest increase in unemployment.
   
3. **Workforce Challenges:**
   - States such as Uttar Pradesh, Maharashtra, and West Bengal struggled to maintain high employment levels both before and during the pandemic.
   
4. **Labor Participation:**
   - Before the lockdown, high labor participation rates were seen in Telangana, Tripura, Meghalaya, and Assam. During the lockdown, resilience was observed in Meghalaya, Telangana, Tripura, and Andhra Pradesh.
   
5. **Correlation Analysis:**
   - A strong negative correlation was identified between the unemployment rate and employment levels, reflecting a complex dynamic between these variables.

## Data Wrangling Steps

1. Renamed columns for clarity.
2. Converted `Date` column to datetime format and extracted the month.
3. Handled missing data by removing rows with null values.
4. Created separate datasets for pre-lockdown and lockdown periods.
5. Generated visualizations to explore relationships between key variables.

### Visualizations

- **Region-wise Unemployment Rate:** Bar plots comparing pre-lockdown and lockdown periods across states.
- **State-wise Unemployment Rate:** Swarm and bar plots for state comparisons before and during lockdown.
- **Correlation Heatmaps:** Visualizations showing relationships between unemployment, labor participation, and employment rates.

## Libraries Used

- **Python**: ![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
- **Pandas**: For data manipulation and analysis. ![Pandas](https://img.shields.io/badge/pandas-1.2.4-orange)
- **NumPy**: For numerical operations. ![NumPy](https://img.shields.io/badge/numpy-1.19.2-orange)
- **Matplotlib**: For static and interactive visualizations. ![Matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-orange)
- **Seaborn**: For statistical data visualization. ![Seaborn](https://img.shields.io/badge/seaborn-0.11.1-orange)

## Conclusion

The analysis highlights the profound impact of COVID-19 on India's labor market. States that had relatively lower unemployment before the pandemic, such as Haryana and Himachal Pradesh, experienced significant shifts during the lockdown, while states like Puducherry and Jharkhand saw some of the highest unemployment rates. The findings emphasize the need for data-driven approaches to address future economic challenges.

## How to Use This Project

1. Clone the repository:  
   ```bash
   git clone https://github.com/devgupta2619/Unemployment_Analysis.git
   ```

2. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```

3. Run the Jupyter Notebook or Python script to view the analysis.

---