# Analysing the US Treasury term spread and its relationship with economic indicators

## Introduction 
This project explores the interrelationship between finance and economics by analyzing the term spread — the difference between the 10-year and 2-year U.S. Treasury yields—and its relationship with various economic indicators. The yield spread is a crucial metric as it reflects market expectations about the economic situation.

## Key Questions Addressed
- Is the inverted yield curve truly a predictor of recessions, or are there other underlying factors?
- How do different economic indicators, such as the Federal Funds Rate, inflation measures, labor market data, and stock market indices, influence the term spread?
- Can we build a predictive model to forecast the yield spread based on these indicators?

## Data Sources

We collected a set of economic and financial data from the Federal Reserve Economic Data (FRED) and other sources using the tidyquant package in R for the past 40 years:
- Inflation Measures:
  - Consumer Price Index (CPI): CPIAUCSL,
  - Personal Consumption Expenditures (PCE): PCEPI,
  - Inflation Expectations: T10YIE;
- Labor Market Data:
  - Nonfarm Payrolls (NFP): PAYEMS,
  - Unemployment Rate: UNRATE,
  - Job Openings (Vacancies): JTSJOL,
  - Number of Unemployed: UNEMPLOY;
- Federal Funds Rate: FEDFUNDS;
- Gross Domestic Product (GDP) Growth: A191RL1Q225SBEA;
- Treasury Yields:
  - 2-Year Yield: DGS2,
  - 10-Year Yield: DGS10;
- Stock Market Index - as indicator of business activity:
  - S&P 500 Index (SPX): ^GSPC

## Project Overview

#### Exploratory Data Analysis: 
- Analyzed the relationship of the spread with general economic health measured by GDP growth.
- Investigated the influence of the Federal Funds Rate on the yield curve.
- Analyzed the impact of inflation measures and labor market dynamics on the spread.
- Assessed the stability of the relationship between the spread and stock market indices.

#### Predictive Modeling: 
- Developed a Random Forest model to predict the yield spread based on selected factors.
- Recognized the complexity of accurately predicting the spread, a task pursued by many investment firms
- The model provides a solid foundation for creating trading strategies, though it's not yet ready for practical application.

## Conclusion
The project offers insights into the factors influencing the U.S. Treasury term spread and challenges the conventional belief that an inverted yield curve is solely a predictor of recessions. By understanding the interplay between the spread and various economic indicators, we can enhance economic forecasting and inform investment strategies.


