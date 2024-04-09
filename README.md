# Portfolio-Optimization-Using-Python

The objective of this comprehensive portfolio analysis is to guide decision-making by providing insights into the optimal allocation of weights that maximize the Sharpe ratio while initially minimizing the semi-standard deviation. This deliberate focus on the semi-standard deviation allows for a nuanced examination of potential losses, emphasizing risk associated with negative returns, as opposed to the conventional standard deviation, which considers both positive and negative returns.

In pursuit of this goal, the analysis leverages the capabilities of the riskfolio library. By employing this library, we can conduct a thorough exploration of the portfolio landscape, considering different risk measures and optimizing the trade-off between risk and return.

To initiate the analysis, we will delve into the optimization process, seeking the optimal weights that not only maximize the Sharpe ratio but also minimize the semi-standard deviation. This choice is strategic, reflecting an emphasis on risk management by addressing downside volatility. The riskfolio library facilitates a detailed examination of historical data to estimate parameters such as expected returns, covariances, and correlations, forming the basis for the portfolio optimization.

Subsequently, we extend the analysis by introducing a more nuanced risk measure – Conditional Value at Risk (CVaR). This measure, also known as Expected Shortfall (ES), offers a deeper understanding of potential losses beyond a specified threshold. By transitioning to CVaR, we broaden the scope of the analysis, incorporating tail risk and enhancing our risk management strategy.

In essence, this analysis serves as a sophisticated exploration of portfolio optimization, leveraging riskfolio's capabilities to guide decision-making. By sequentially considering the semi-standard deviation and then transitioning to CVaR, we aim to provide actionable insights that align with the specific risk preferences and objectives of the investor.
