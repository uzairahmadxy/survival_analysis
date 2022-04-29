# Survival Analysis

## Background
The United States Patent and Trademark Office (USPTO) is the federal agency for granting U.S. patents and registering trademarks.  The USPTO employs over 10,000 patent examiners whose primary task is to assess inventions for patentability and issue patents when appropriate. The USPTO faced alarming [employee attrition & a backlog in applciations](https://www.networkworld.com/article/2351024/us-patent-backlog--employee-attrition-grow-at-alarming-rates.html).

## Analysis
An analysis was done to look at attrition rates, survaivability of examiners by Demographic segments using Kaplan–Meier estimates. Please note that due to limited availablity of data (masking), the estimates are not accurate.

### Gender
Females have a higher likelihood to stay at their Job at the USPTO.

![gender](/Images/unnamed-chunk-3-1.png)

### Race
We see varying period of stay for different races.

![race](/Images/All&#32;Races-2.png)

**Insights:**
Performing Cox Regression we gain the following insights:
- Men ~14% more likely to leave than Women
- Hispanic ~16% more likely to leave than Asians
- Black ~25% less likely to leave than Hispanic

![coxregression](/Images/CoxRegression_Estimates.png)
