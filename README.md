# COVID-19 Data Analysis Project

## Overview
This project delves into analyzing COVID-19 data collected across various states in the United States. The dataset contains comprehensive information regarding positive and negative COVID-19 cases, hospitalization rates, testing statistics, and more. The primary objective is to explore this dataset, conduct statistical analysis, and derive insights to comprehend the trends and impacts of COVID-19.

## Tools and Dependencies
- Python 3.x
- Libraries: pandas, matplotlib, seaborn, statsmodels, numpy

## Data Collection and Preparation
- Acquired the dataset from a reliable source comprising daily COVID-19 statistics across different states.
- Initial data cleaning involved renaming columns, handling missing values, and ensuring data consistency.

## Exploratory Data Analysis (EDA)
- Utilized histograms to visualize the distribution of variables such as CovidPos, CovidNeg, Pending, In Hospital, etc.
- Examined crucial statistical measures like mean, mode, variance, and standard deviation for selected variables.
- Utilized probability mass functions (PMFs) to compare COVID-19 positive cases between California (CA) and New York (NY).
- Analyzed cumulative distribution functions (CDFs) of deaths in CA and NY to compare the death rates.

## Statistical Analysis
- Employed normal probability plots to assess the normality of the distribution of death rates in California.
- Conducted Pearson's and Spearman's correlations to investigate relationships between CovidPos, CovidNeg, NegativeIncreasedBy variables between CA and NY.
- Performed hypothesis testing to compare CovidPos between CA and NY using a permutation test.

## Regression Analysis
- Conducted simple linear regression to predict CovidPos based on CovidNeg, exploring the relationship between positive and negative COVID-19 cases.
- Extended the analysis by performing multiple linear regression with CovidPos as the dependent variable and CovidNeg along with NegativeIncreasedBy as explanatory variables.

## Tableau Dashboard and Presentation
- Created a Tableau dashboard using the analyzed COVID-19 dataset to visually represent key findings and insights.
- Presented the project findings and analysis in a recorded PowerPoint presentation, providing a comprehensive overview of the research methodologies, conclusions, and challenges faced during the analysis.

## Summary

### Statistical/Hypothetical Question
The primary question explored was the relationship between Covid Positive and Covid Negative results, specifically examining if CA and NY exhibited any correlation between these variables. The assumption was that both states, being heavily traveled and densely populated, might experience similar epidemic effects.

### Outcome of EDA
The analysis compared Covid positive and negative results for all states due to difficulty in isolating CA and NY data for regression analysis. Missing variables like total population per state might have enhanced the analysis, offering a better understanding of the pandemic's impact.

### Missed Analysis
Challenges were encountered while attempting to perform hypothesis testing, which consistently resulted in zero, hindering the verification of the hypothesis. Regression analysis was limited to a broader dataset due to difficulty in isolating specific state data.

### Assumptions and Challenges
Assumptions to retain zero-valued data in histograms were made to maintain the integrity of daily reports, yet the heavy left skew might affect analysis accuracy. Difficulties were faced in performing regression analysis on specific state data due to limitations in data isolation.

## Conclusion
Despite encountering challenges and limitations in isolating state-specific data for regression analysis, this project provided valuable insights into the relationship between Covid Positive and Negative cases across various states. Further exploration with additional variables and improved hypothesis testing methodologies could enhance the depth of analysis in future studies.

## Submission
Link to the repository containing the project, Tableau dashboard, and recorded PowerPoint presentation will be submitted via the assignment link during the final week of the class.
