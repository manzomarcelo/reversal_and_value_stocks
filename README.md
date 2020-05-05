# Long-term Reversal and Value

 Objective: Check the correlation in returns between value strategies and a long-run reversal strategy.
 
 Data: 
 
 1 - Monthly returns for various portfolios based on book-to-market value

 2 - Monthly returns for all the NYSE stocks from 1960 to today
       

Steps:

(1) At month t, for stock i, I defined a trading signal based on stock i returns over the last five years (including month t). Then 10 portfolios based on this signal were constructed. After, I reported the portfolio returns for each of these portfolios, their CAPM α, their volatility.

(2) Constructed a portfolio that goes long the bottom decile and short the top decile of the previous signal. Then, I computed the long-short portfolio average returns and its CAPM α. 

(3) Calculated the loading of the long-short porftolio returns on the returns of a value portfolio, constructed using the French dataset. Then, I compared the long-short portfolio α against a 2 factor model that include the market and this value portfolio.

Conclusion:
 
Value is an over-reaction phenomenon, as it is equivalent to a long-run reversal strategy. The returns of the long-short portfolio have a positive correlation of 0.418 with the value portfolio. This reveals that they tend to move together. Also, as illustrated by the previously calculated negative long-short portfolio average return, stocks that did poorly in the past 5 years tend to do worse in the next 5 years than stocks that did well in the past 5 years. Furthermore, in the last model, the long-short portfolio has a negative loading for the market portfolio, revealing that this portfolio and the market move in opposite directions.
