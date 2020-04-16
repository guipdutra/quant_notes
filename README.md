Bonds = titulos

Modern Portfolio Theory: alocamento de recursos baseado em alguns pesos
 - expected return for portfolio
 - risk is volatility
     - volatility is something to do with **standard deviation** and **variance**
     - **covariance** measures how much two random variables vary together
      - $covariance < 0 **moves inversely**
      - $covariance > 0 **moves together**
      
 - **Markowitz theory**
  - high positive covariance does not provide very much diversification
  - the aim to diversification is to eliminate the fluctuactions
    - **uncorrelated stocks are better**
  - for calculate the variance  of the portfolio we need the covariance matrix containing all
    the covariance of the stocks in portfolio.
    - covariance matrix: correlation between the stocks
    
  - output from modern portfolio is expected variance/return matrix
   - Efficient frontier are the portfolio that has high return and minor risk THE EDGE!
   
  - Sharper ratio - risk/return measure
   - it describes how much excess return you are receiving for extra volatility that 
   you endure holding a riskier asset.
   - sharpe-ratio **S(x) > 1** is considered to be **good**, high better 
   
   
  - notes on article(https://medium.com/qfx-research/im-approaching-one-year-since-diving-full-time-into-quant-trading-a1bea7bb6d05)
    - Trading US stocks, forex, and bonds probably is a bad idea. It is not the wisest choice, due to too much competition with the biggest players. 
    - Find your liquidity sweet spot by taking a look at markets that would support your liquidity needs
    - Play and win in niche markets by learning their rules
    There’s so much to do in quant trading: strategy development, optimization, backtesting, execution, and risk management. Don’t focus on the wrong things in the beginning — like optimizing parameters. Rather, build very basic MVP versions of each part in the equation and optimize by iterating while in production. A perfectly optimized strategy won’t help if the execution part doesn’t work correctly.
    - Price stops will, as research shows, destroy a good strategy, simply due to randomness in volatility. 
    - By using time stops, you are setting a time constraint in terms of how long your hypothesis is valid, which almost always reduces variance (and increases Sharpe ratio).
    - For each trade, know where to enter and where to exit. For me, these are set based on two rules — one being a modified formula of Average True Range. It’s almost a requirement to have pre-defined rules for entries and exits, in order to properly backtest and to know what to expect in live trading.
    - For each strategy, you must know the expected value, hit rate, expected drawdown, longest drawdown, expected volatility, variance, Sharpe ratio, standard deviation of returns, skewness of returns, and value at risk. Also, proper bet sizing, risk of ruin, Kelly fraction, and optimal F should be strategically chosen based on how the strategy performs during the backtest.
    - Make risk management a priority
    - Use fewer parameters but know what they do
    - Focus on features, not on optimization
There’s a great range of tools for optimization, genetic optimizations, non-convex optimizations, principal component analysis, statistical/Bayesian optimization, and a thousand fancy libraries. From my point of view, optimization will help improve a strategy by 10–20%; however, it won’t lead to a profitable strategy in the first place. If a strategy is bad, no optimization will help. Focus on deductive analysis and feature engineering — in simple terms, making sense out of the inputs and data.
    - Better data, better features, “Data is the oil of the digital world,”
    - Fast feedback is a must
Competing with big players, especially in the HFT realm, is probably a bad idea (like I explained above). Going the opposite — holding trades for days, months, and years — also is not ideal. For me, the sweet spot is a holding time of 5 to 60 minutes. If I can’t test a strategy in 2 weeks with statistical significance (meaning more than 100 trades), I’m not investing my time in it. To test a strategy with a multi-day (and longer) holding period, I’d need months to validate, and this is not what I’m interested in.
    - The truth is, simple statistics, Monte Carlo simulation and a little bit of Python is all you need. Simple assumptions well simulated and validated can spot over-priced and under-priced bids and asks, that’s it. The fancy models are good for your ego and general understanding. In markets, a CS 101 probability and statistics is good enough for a profitable strategy.
   
