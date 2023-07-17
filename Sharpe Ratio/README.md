# Project 5: Calculating Sharpe Ratio (Risk & Returns) - Data wrangling, EDA, Calculating the ratio, Summarizing findings with a buy decision
## Project Overview:
William Sharpe introduced the reward-to-variability ratio in 1966 that soon came to be called the Sharpe Ratio. It compares the expected returns for two investment opportunities and calculates the additional return per unit of risk an investor could obtain by choosing one over the other. In particular, it looks at the difference in returns for two investments and compares the average difference to the standard deviation (as a measure of risk) of this difference. A higher Sharpe ratio means that the reward will be higher for a given amount of risk. It is common to compare a specific opportunity against a benchmark that represents an entire category of investments.

The Sharpe ratio is usually calculated for a portfolio and uses the risk-free interest rate as benchmark. In this project we simplified and  used stocks instead of a portfolio. We will also use a stock index as benchmark rather than the risk-free interest rate because both are readily available at daily frequencies and we do not have to get into converting interest rates from annual to daily frequency.

We learnt  about Sharpe ratio by calculating it for the stocks of the two tech giants Facebook and Amazon. As benchmark we used the S&P 500 that measures the performance of the 500 largest stocks in the US. When we used a stock index instead of the risk-free rate, the result is called the **Information Ratio** and is used to benchmark the return on active portfolio management because it tells you how much more return for a given unit of risk your portfolio manager earned relative to just putting your money into a low-cost index fund

## Installation and Setup
To work on this project, download CSV files under the folder.
If you download jupyter noteboook (ipynb) in the folder, you can see the the description, tasks and step-by-step analysis with the python script. 

## Codes and Resources Used
 - Python was used for this project
 - Python libraries: (Numpy, Pandas, Matplotlib)

## Technial skills 
- Python
- Data Acquisition: upload csv file
- Data Preprocessing
-   Exploratory Data Analysis (EDA)
-   Calculating the inputs to the ration using numpy
-   Caclulating the Sharpe Ratio
-   Data Visualization to support my Sharpe Ratio calculations with the audience 
## Results and Evaluation 
Amazon stock had Sharpe Ration of 0.35, and Facebook stock had around 0.17. Amazon had a Sharpe ratio twice as high as Facebook. This means that an investment in Amazon returned twice as much compared to the S&P 500 for each unit of risk an investor would have assumed. In other words, in risk-adjusted terms, the investment in Amazon would have been more attractive.This difference was mostly driven by differences in return rather than risk between Amazon and Facebook. The risk of choosing Amazon over FB (as measured by the standard deviation) was only slightly higher so that the higher Sharpe ratio for Amazon ends up higher mainly due to the higher average daily returns for Amazon.
When faced with investment alternatives that offer both different returns and risks, the Sharpe Ratio helps to make a decision by adjusting the returns by the differences in risk and allows an investor to compare investment opportunities on equal terms. 
![image](https://github.com/Dzhoniq/data-analytics-portfolio/assets/64640862/26b02897-305c-40a1-aaad-91e14afea8ce)

