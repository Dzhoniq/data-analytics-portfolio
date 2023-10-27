# Hypothesis testing in Healthcare
## Project Description
This is case study from DataCamp. Pharmaceutical drugs have become an essential part of our health. Therefore, they need to be safe with little or no adverse effects.
In this projects we work with a non-profit that advocates for pharmaceutical drug safety. One of its tasks is to create reports on drugs independent of the drug manufacturer. I'll conduct several hypothesis tests using Python to determine if the adverse reactions of a hypothetical drug are significant. You'll also check if factors such as age and sex significantly influence the adverse reactions.

## Project tasks
Analyze pharmaceutical drug treatment effects.

## Installation and Setup
To work on this project, download CSV file under the folder.
If you download jupyter noteboook (ipynb) in the folder, you can see the the description, tasks and step-by-step analysis with the python script. 

## Codes and Resources Used
 - Python was used for this project
 - Python libraries: (Numpy, Pandas, Seaborn, Matplotlib, Pingouin, StatsModels, Scipy)

## Technial skills 
- Python
- Data Acquisition: upload csv file
- Understanding of the hypothesis testing
- Exploratory Data Analysis (EDA) - visualization of distributions
- Conducting hypotheses test: a two-sample z-test, a chi-square test of independence, Wilcoxon-Main-Whitney test (non-parametric test)
- Transforming data
- Data Visualization to support/check my findings with the audience


## Results and Evaluation 
Visualized the distribution of the number of adverse effects between the groups. It was found the number of adverse effects between 2 groups are not different except for cases when there were 1 or 2 adverse effects. The number of participants with 1 adverse effect was more for the Drug group than Placebo group. Then, to check whether there is a significant difference in proportions of adverse effects between the groups, I conducted a two-sample z-test. According to the results, p_value of 0.964 we fail to reject the null hypothesis that the proportion of adverse effect is the same. In other words, the null hypothesis that there is no difference in proportion of patients that indicated they had adverse effects is not rejected. The next question from the organization was to check if the number of adverse effects is independent of the groups. To check it we were asked to use Chi-square test of independence from pingouin package. The p value was 0.615, which is greater than our significance level. This means that we fail to reject the null hypothesis. Thus, the number of adverse effects is independent of the group type. The organization also asked to look at the age disribution in the groups. According to the visualization, the distribution is not following normal distribution. Hence, it's better to use non-parametric test to check the whether there was a difference in age between the groups. As there are 2 samples and the data is unpaired, we will conduct a two-sided Wilcoxon-Main-Whitney test and round it to 3 decimal places. The p value of this test was 0.257 and it was greater than the significance level. Thus, we fail to reject the null hypothesis. That means there is no significant difference in median age between the Drug and Placebo groups. 

