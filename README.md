#key factors that influence US home prices nationally over 20 years

--Objective--:

Find publicly available data for key factors that influence US home prices nationally. Then, build a data science model that explains how these factors have impacted home prices over the last 20 years(2004-2024).

The project aims to build a data science model to predict U.S. home prices based on key economic factors over the last 20 years.

--Steps--

*Data Collection:
Utilized the S&P Case-Schiller Home Price Index as a proxy for home prices, sourced from the Federal Reserve Economic Data (FRED) website.

*Key Factors:
Gathered publicly available data on factors influencing home prices nationally, including Per Capita GDP, Consumer Price Index (CPI), Construction Material Costs, Median Income, Subsidies, and Population Demographics, etc.

*Data Cleaning and Processing:
Cleaned and processed the data, addressing missing values, converting date formats, and handling outliers.

*Exploratory Data Analysis (EDA):
Conducted EDA to understand the distribution of variables, identify correlations, and visualize trends over time.

*Model Selection:
Explored various regression models, including Linear Regression, ElasticNet, Random Forest, Gradient Boosting, Support Vector Regression (SVR), and XGBoost.

*Model Training and Evaluation:
Trained each model using a subset of the data, evaluated performance using metrics such as Mean Squared Error (MSE) and R-squared.

*Feature Importance:
Analyzed feature importance for models like Random Forest, XGBoost, and Gradient Boosting to understand the factors influencing home prices.

*Model Comparison:
Compare the performance of different models based on metrics such as Mean Squared Error (MSE) and R-squared.

Select the best-performing model that provides accurate predictions and insights into the factors influencing home prices over the last 20 years.

*Visualization:
Create visualizations to illustrate the relationships between actual and predicted home prices for each model.

*Visualize the importance of different features or coefficients in influencing home prices.

*Conclusion:
Identified strong contenders for the best model, considering their low MSE and high R-squared values.

Conclude the key factors that have historically influenced US home prices.

---Overall Implication---:
The project contributes to understanding the key factors influencing U.S. home prices over the last 20 years and provides a foundation for building robust predictive models in the real estate domain.

-------Results----------

The project involves understanding and predicting patterns rather than just describing historical trends or providing actionable recommendations.

![Screenshot 2024-07-27 at 2 33 04 AM](https://github.com/user-attachments/assets/34478b32-0157-478f-9db7-0c425d48aaeb)
![Screenshot 2024-07-27 at 2 33 30 AM](https://github.com/user-attachments/assets/b0b11960-527c-45d2-b181-f177513e2301)
![Screenshot 2024-07-27 at 2 33 55 AM](https://github.com/user-attachments/assets/418de95a-dc19-43e8-bdca-d9499654b0b4)

---Data Availability---

The following variables are chosen for the study-

1. Unemployment Rate
2. Employment Rate
3. Per Capita GDP
4. Real Median Household Income
5. Construction Prices
6. CPI
7. Interest Rates
8. Number of new houses supplied
9. Working Population
10. Urban Population
11. Percentage of the population above 65
12. Housing subsidies
13. Number of Households
14. As a proxy for home prices, the S&P CASE-SHILLER Index is used.

Most of the data is downloaded from [https://fred.stlouisfed.org/].

The following sources were used to gather data:

CASE-SCHILLER Home Price Index - https://fred.stlouisfed.org/series/CSUSHPISA

Interest rates - https://fred.stlouisfed.org/series/FEDFUNDS

Unemployment rate - https://fred.stlouisfed.org/series/UNRATE

Working Population - https://fred.stlouisfed.org/series/LFWA64TTUSM647S

Employment rate - https://fred.stlouisfed.org/series/LREM64TTUSM156S

Consumer price index (CPI) - https://fred.stlouisfed.org/series/CPIAUCSL

Real Median Household Income - https://fred.stlouisfed.org/series/MEHOINUSA672N

Per Capita GDP - https://fred.stlouisfed.org/series/A939RX0Q048SBEA

Construction price index - https://fred.stlouisfed.org/series/WPUSI012011

percent urban population - https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS?end=2021&locations=US&start=2001

Housing Subsidies (Federal) - https://fred.stlouisfed.org/series/L312051A027NBEA

Total households - https://fred.stlouisfed.org/series/TTLHH

Article referred -

https://www.investopedia.com/articles/mortgages-real-estate/10/understanding-case-shiller-index.asp

Research Paper referred -

https://www.atlantis-press.com/article/25841966.pdf
