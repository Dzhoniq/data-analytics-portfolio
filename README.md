# data-analytics-portfolio
![image](https://github.com/Dzhoniq/data-analytics-portfolio/assets/64640862/e11f3a52-2c11-4e48-b094-e6d1731d5c4c)


In this repository, I included my Excel, Power BI, and Python data analytics projects. 
## [Project 1: Sales records analysis with further recommendations](https://github.com/Dzhoniq/data-analytics-portfolio/tree/main/Sales_Record_Analysis)
- Performed EDA analysis of pet products retailer's sales records
- Did Data Cleaning, Data Validation before starting EDA
- As a result of EDA checked whether the retailer's approach to increase sales with selling more of everyday repeatedly was correct or not

## [Project 2: Power BI 5 ](https://github.com/Dzhoniq/data-analytics-portfolio/tree/main/PowerBI_project_5)
- Uploaded Beer brewery and retailer sales data to Power BI
- Structured, cleaned up the data
- Created a data model by establishing relationships between tables
- Provided analysis of sales and gross profit margin for each customer per financial quarter, and helped to identify the bestseller for a CFO with the recommendations. 

## [Project 3: Power BI 6](https://github.com/Dzhoniq/data-analytics-portfolio/tree/main/PowerBI_6)
In this project, I created a Power BI report for Waggle, a startup that makes smart devices for pets. At the end, I applied the key concepts of Power BI to create a user-friendly and interactive report so that based on your report, the CEO of Waggle can make decisions about the future direction of the company. 
- uploaded, cleaned up data and created a date model
- interactive report with visualizations, navigation buttons and filters
- the report helps to:
-  identify the use of smart devices by pet type, state, city
-   check the customer rating and feedback to see the most promising product
-   get general overview of the demographics of pets, and their breed
-   analyze the customer data and see the most promising states, cities


## [Project 4: Power BI 7](https://github.com/Dzhoniq/data-analytics-portfolio/tree/main/PowerBI_Project%207)
In this project I created a market intelligence report for a chain store with Power BI. 
- created a data model and cleaned up the data
- drew conclusions from my analysis
- identified correlation between sales and income, customer ratings and return rates
- used visualization to answer questions from the CEO 
- used models to forecast future prospects

## [Project 5: Calculating the Sharpe Ratio for investment options: Risk and Returns](https://github.com/Dzhoniq/data-analytics-portfolio/tree/main/Sharpe%20Ratio)
In this project I calculated the Sharpe Ratio for the stocks of Facebook and Amazon using S&P 500 as benchmark. This ratio also known as reward-to-variability ratio, compares the expected returns for two investment opportunities and calculates the additional return per unit of risk an investor could obtain by choosing one over the other. A higher Sharpe Ratio means that the reward will be higher for a given amount of risk. 
- uploaded and checked the data
- visualized and summarized daily values of the stocks and S&P 500 to better understand it
- prepared the inputs for the Sharpe ratio: calculated daily stock returns (Amazon, Facebook & S&P500), the difference in returns between stocks and S&P 500 benchmark 
- Computed the Sharpe Ratio: calculated the average and standard deviation of excess returns (between stocks & S&P500 index) and the daily sharpe ratio
- Based on the Sharpe Ratio, provided conclusion to make a buy decision

## [Project 6: Mobile game A/B test](https://github.com/Dzhoniq/data-analytics-portfolio/tree/main/AB%20test_Cookie%20Cats)
In this project I did A/B test to check which scenario for a game called "Cookie Cats" would increase its player retention. The game has gates that players encounter as they progress through the levels. These gates serve the important purpose of giving players an enforced break from playing, hopefully resulting in that the the player's enjoyment of the game being increased and prolonged. The gates where placed in level 30 and level 40, and analyzing an A/B test we checked the impact of these changes on players retention.
- uploaded and checked the descriptoin of the AB-test data
- Performed EDA analysis to check the distribution of game rounds
- Calculated 1-day and 7-day retention
- Used bootstrapping to get at the certainty of the retention numbers
- Computed a difference between retention rates of 2 scenarious and the probability of the difference 
- Based on the A/B-test results, provided recommendations on whether to move the gate from level 30 to level 40

## [Project 7: Hypothesis testing on the pharmaceutical drug treatment effects](https://github.com/Dzhoniq/data-analytics-portfolio/tree/main/Hypothesis_Testing#hypothesis-testing-in-healthcare)
In this porject I conducted several hypothesis tests using Python to determine if the adverse reactions of a hypothetical drug are significant. I also checked if factors such as age and sex significantly influence the adverse reactions. It was found the number of adverse effects between 2 groups are not different except for cases when there were 1 or 2 adverse effects. The number of participants with 1 adverse effect was more for the Drug group than Placebo group. Then, to check whether there is a significant difference in proportions of adverse effects between the groups, I conducted a two-sample z-test. The next question from the organization was to check if the number of adverse effects is independent of the groups. To check it we were asked to use Chi-square test of independence from pingouin package.  The organization also asked to look at the age disribution in the groups. According to the visualization, the distribution is not following normal distribution. Hence, it's better to use non-parametric test to check the whether there was a difference in age between the groups. As there are 2 samples and the data is unpaired, I conducted a two-sided Wilcoxon-Main-Whitney test. The p value of this test was 0.257 and it was greater than the significance level. Thus, we fail to reject the null hypothesis. That means there is no significant difference in median age between the Drug and Placebo groups.
Python
- Data Acquisition: uploaded csv file
- Understanding of the hypothesis testing
- Exploratory Data Analysis (EDA) - visualized distributions
- Conducted hypotheses test: a two-sample z-test, a chi-square test of independence, Wilcoxon-Main-Whitney test (non-parametric test)
- Visualized data to support/check my findings with the audience
- Provided explanation and summary for the hypothesis test results
