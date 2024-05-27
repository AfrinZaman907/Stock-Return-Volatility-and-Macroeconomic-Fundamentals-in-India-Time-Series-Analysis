# Stock-Return-Volatility-and-Macroeconomic-Fundamentals-in-India-Time-Series-Analysis

# Introduction
Financial market volatility plays a significant role in the overall economy, as it reflects the country's economic prosperity and growth. The development of financial markets strongly influences GDP growth. The stock market, being central to the financial system, channels savings into investments, finances real sectors, and contributes to economic growth by increasing savings and enhancing both the quality and quantity of investment. However, investors aim to reduce risk associated with assets, and analyzing volatility estimation and forecasting is crucial for risk management. While market volatility is inevitable and beneficial to a certain extent for better resource allocation, extreme volatility disrupts the smooth functioning of the stock market, leading to uncertainty and affecting investor confidence. The study begins with an introduction to the financial market in India and its importance in the real economy, followed by subsections discussing the research problem, relevance of the study, literature review, research gaps, and study objectives. Section 2 describes the data sets and variables used, while Section 3 elaborates on the analysis of the study objectives. Finally, Section 4 concludes the study.
# Research Problem
This study delves into the volatility of stock returns in the Indian context, particularly focusing on the post-liberalization period. It recognizes the increased activity in the Indian stock market following financial sector reforms and examines the impact of macroeconomic fundamentals on stock return volatility.

The period following the removal of barriers to capital movement in the late 1980s and early 1990s witnessed increased market openness in emerging economies like India, attracting both foreign and domestic investors. However, with this increased integration into global financial markets, there's also a heightened vulnerability to global shocks.

The study aims to analyze the volatility of stock returns by considering factors such as inflation and other macroeconomic variables. It explores how the behavior of major players in the stock market and macro fundamentals affect stock returns. The analysis spans from 1991 to 2021, examining the trend behavior of stock prices of major companies listed on the Bombay Stock Exchange.

Macroeconomic variables like exchange rates, interest rates, money supply, and industrial production are investigated for their impact on stock return movements. The study considers theories like the portfolio balance approach and traditional approaches to understand the relationship between exchange rates and stock prices, as well as the impact of factors like interest rates and industrial production on stock prices.

There's a particular focus on inflation and its relationship with stock returns, exploring conflicting theories in the literature regarding whether inflation has a positive or negative correlation with stock returns. The study employs vector autoregressive models to analyze the relationship between stock market indices and macroeconomic variables.

Understanding stock return volatility is deemed crucial not only for investors in making efficient decisions but also for overall economic prosperity and growth. By examining the linkage between stock market dynamics and real macroeconomic variables, the study aims to provide insights into the Indian financial landscape.

# Trend behaviour in Indian Stock Market
![image](https://github.com/AfrinZaman907/Stock-Return-Volatility-and-Macroeconomic-Fundamentals-in-India-Time-Series-Analysis/assets/157863283/b30190c6-3dde-4d61-ba01-d52d4d0cea92)
The estimated result (Table 2.1) implies that the close price series are non-stochastic 
in nature and at long period there exhibit unit root for all the companies along with 
Sensex.

![image](https://github.com/AfrinZaman907/Stock-Return-Volatility-and-Macroeconomic-Fundamentals-in-India-Time-Series-Analysis/assets/157863283/4989340e-ac87-401a-a744-86b0aa77cb7d)
Now, as financial series are expected to have a lot of fluctuations, for modelling, 
forecasting and drawing any inference the return series are taken under analysis. The 
return series is obtained by taking first difference of log values of close price of BSE 
and for the companies. VAR framework (Table-2.4) for the stationary series (in long 
run) is tested for 2 lag values of each variable. 

# Stock Returns and Macroeconomic Fundamentals
The study conducts trend analysis for each selected macroeconomic series to identify their behavioral patterns. Subsequently, it employs vector autoregressive processes to investigate the nature of shock transmission between stock returns and macroeconomic variables.

Data from the RBI Handbook Statistic for the period 1991:01 to 2021:04 is utilized for analysis. The macro variables under scrutiny include Call Money Rate (as a proxy for interest rate), M3 (broad money supply), Real Effective Exchange Rate (REER_Tr), Index of Industrial Production (IIP), and the growth rate of Wholesale Price Index (WPI) (as a proxy for inflation rate).

By considering the seasonality in the data and analyzing the growth rates of macroeconomic variables, this paper aims to provide insights into the relationship between the real and financial sectors in the Indian context.

![image](https://github.com/AfrinZaman907/Stock-Return-Volatility-and-Macroeconomic-Fundamentals-in-India-Time-Series-Analysis/assets/157863283/33395f27-b2d6-446a-89f7-6df4e40ae1f5)

The Hegy test was employed to examine the presence of unit roots in the macroeconomic variables. It was found that the Real Effective Exchange Rate (REER) and inflation rate did not exhibit unit roots, indicating stationarity. However, variables such as Call Money Rate, Money Supply (M3), and Index of Industrial Production (IIP) displayed unit roots at certain frequencies, suggesting non-stationarity in the long run.

Seasonal unit roots were identified in M3, possibly attributed to fluctuations in demand for money, particularly influenced by innovations in the financial sector, such as changes in payment systems.

Given the non-stationarity of some variables, traditional cointegration analysis may not yield meaningful results. Therefore, an unrestricted Vector Autoregressive (VAR) model was employed, considering variables such as Sensex return, Call Money Rate, M3, IIP, REER, and inflation. To ensure stationarity, first differences were taken for some variables, while second differences were applied to others.

The VAR model revealed seven equations, indicating interrelation among the macroeconomic variables. While the R-squared values suggested a good fit for most equations, the p-values of the chi-square test supported the model's overall validity.

In summary, the study utilized the Hegy test to assess unit roots in macroeconomic variables, applied an unrestricted VAR model due to non-stationarity, and found interrelation among the variables through the analysis.

![image](https://github.com/AfrinZaman907/Stock-Return-Volatility-and-Macroeconomic-Fundamentals-in-India-Time-Series-Analysis/assets/157863283/6060328e-e522-4370-a48e-80ce3c440038)
From the Table -3.2 we can clearly find that the both lag values of growth of call 
money rate is negatively related with present value of growth of call money rate, 
which implies if in previous period call money rate increases then in present period 
there should be a fall in call money rate 

#Volatility in Stock Return


![image](https://github.com/AfrinZaman907/Stock-Return-Volatility-and-Macroeconomic-Fundamentals-in-India-Time-Series-Analysis/assets/157863283/70b1dc96-daf9-4054-a57e-46906a784153)

The study employed a VAR model to investigate causality in the volatility of the macroeconomic series. Since the direction of dependency was uncertain, VAR was considered appropriate. The initial assumption was a positive correlation between variables, as macroeconomic volatility typically increases uncertainty in stock returns, leading to higher stock return volatility. The conditional variances of all variables were affected by their own lagged values.

From the estimated VAR model, it was observed that past period's volatility influenced present period's volatility in each of the seven equations. However, only the equation where volatility of M3 was treated as the dependent variable did not exhibit a good fit.

In summary, the VAR model analysis revealed the impact of past volatility on present volatility across the variables, with M3 volatility being an exception in terms of fitting the model.

# Conclusion
This study explores the association between stock returns and macroeconomic variables' volatility. It utilizes EGARCH/ARCH models to observe volatility among variables and VAR models to analyze causal relationships between BSE Sensex return volatility and macroeconomic determinants' volatility.

Findings suggest that in the long run, leverage effect on financial markets does not dominate symmetric effects. However, changes in money supply growth exhibit a strong positive leverage effect, indicating that positive innovations are more destabilizing. The study reveals similar volatility patterns among most macroeconomic variables but different patterns in BSE stock return volatility.

Additionally, the study analyzes the impact of macroeconomic volatility on stock market volatility, finding that while some macroeconomic factors influence future stock returns deterministically, others do not. Macroeconomic volatility fails to predict financial volatility accurately, consistent with India's real-world scenario, particularly evident during the pandemic-induced economic downturn.

Interestingly, while negative news impacts volatility more than positive news due to the leverage effect, the study concludes that bad news in the Indian stock market does not increase volatility more than good news. Symmetric volatility models are deemed superior, with first-period innovations equally affecting current period volatility.

Furthermore, the study finds a significant effect of BSE return volatility on the growth of industrial production and inflation, indicating a unilateral relationship between real and financial sectors' volatility. Greater fluctuations in the financial sector lead to increased fluctuations in the real sector, but the reverse relationship is not observed.











