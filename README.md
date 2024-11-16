# Analysing the Term Spread and Its Relationship with Economic Indicators

## Introduction 

Our project focuses on the interrelationship between finance and economics. It aims to analyse the relationship between the term spread—the difference between the 10-year and 2-year U.S. Treasury yields—and various economic indicators. The yield spread is a crucial metric in finance and economics, as it reflects market expectations about the economic situation.
Why is the Yield Curve Normally Upward Sloping?
Under typical economic conditions, the yield curve is upward sloping because investors demand higher yields for longer-term investments to compensate for the increased risks associated with time. These risks include:
  •	Inflation Risk: Over a longer period, the uncertainty about future inflation increases. Investors require a premium to offset the potential loss of purchasing power.
  •	Interest Rate Risk: Longer maturities are more sensitive to interest rate changes. Investors demand higher yields to compensate for this volatility.
  •	Opportunity Cost: Committing funds for a longer time means foregoing other investment opportunities that may arise. Higher yields compensate for this potential loss.
What Does Spread Widening or Narrowing Indicate?
The shape of the yield curve and movements in the term spread provide insights into investor sentiment and economic expectations.
  •	Spread Widening (Steepening Yield Curve):
    o	Definition: A widening spread indicates that long-term yields (10Y) are increasing relative to short-term yields (2Y).
    o	Implications:Often reflects expectations of a stronger economy and potential inflation, leading investors to demand higher yields for longer-term bonds.
  •	Spread Narrowing (Flattening Yield Curve):
    o	Definition: A decreasing difference between long-term and short-term yields.
    o	Implications:May indicate expectations of slower economic growth and less inflation.
•	Inverted Yield Curve:
  o	Definition: Short-term yields exceed long-term yields.
  o	Significance:
    - Recession Predictor: Historically, an inverted yield curve has been a reliable predictor of economic recessions.
    - Investor Pessimism: It reflects significant investor pessimism about the near-term economy, causing a flight to long-term securities.
However, is an inverted yield curve actually a predictor of recession, or are there different underlying reasons?
We decided to look closer into the relationships of the spread with the Federal Funds Rate, as perhaps the Fed's monetary policy cycle accounts for a large part of the movements in the spread. Moreover, we explore the relationships with different measures of inflation, the labor market, and stock market indices as indicators of business activity.
Understanding the true relationship of the spread with market and economic indicators, and selecting the most relevant ones, may help us build a model to predict the spread. So, we built a Random Forest model to predict the spread based on the selected factors.
Predicting the spread is a complicated task and is something many investment firms try to do, as it can actually be traded on. Our model is obviously far from being ready to trade on, but it offers a solid foundation for developing trading strategies.



