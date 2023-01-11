## Project Background

The default rate in the banking industry is a significant indicator for evaluating the economic situation. Small businesses, more specifically, have higher probabilities of default due to their limited size and budget. Moreover, the proportion of bank debt to total debt in small businesses is roughly twice that of large firms. Therefore, it is crucial to evaluate the default risk of small businesses for economic stability purposes.

SBA plays the role of an insurance provider to banks by guaranteeing a portion of the loan. In the case that a loan goes into default, SBA then covers the amount that they guarantee. Despite the safety net provided by the SBA, banks will still incur losses when a loan defaults because not all dollar amount is covered by SBA. Therefore, our analysis aims to analyze the probability that a loan is to default and identify the key factors that impact the loan amount of SBA guaranteed.

## Project Description

The goal of this project is to determine if small business loan records can be used to determine the likelihood of loan defaults and what impact the amount of loan the SBA approves for small businesses in the state of North Carolina.

For our first research question, we are interested in how the aforementioned specific factors can be used to determine the amount covered at the SBA level. We hope to understand the impact that these factors have on the loan and whether they can be used to quantify the amount that the SBA should cover.

Our second research question is more open-ended. We aim to determine what are the various factors that have significant relationships with the status of loan default. We are also interested in measuring the relative impact size among all predictors in scope.

## Research Design

Two types of models were used to answer the research questions:

* ***The multiple linear regression model*** helps quantify the relationship between the dependent variable -- the amount approved by the SBA -- and the coviriates: (1) Loan Term, (2) Revolving Line of Credit, and (3) Employee Count.

* ***The logistic regression models*** helps estimate the probability of an event occurring (i.e., loans paid in full) based on a given set of
independent variables. In logistic regression, a logit transformation is applied to the odds, which is the probability of success divided by the probability of failure. In the case of the small business loan, the preferred outcome is when a loan gets paid in full.

## Data Source

[Should this loan be approved or denied?](https://doi.org/10.1080/10691898.2018.1434342)

## Conclusion

For our first research question, all in-scope variables share a significant relationship with the amount of loan covered by the SBA. We find that the employee count and the loan term positively correlate to the amount guaranteed by the SBA. The intuition is that more employees and longer loan terms both point to an increase in the loan amount requested by the company. Larger businesses tend to provide more jobs and require additional capital investments than smaller ones. Similarly, we would expect the requested loan amount to be greater as the loan terms increase. Therefore, when companies request loans with higher dollar values, the amount covered by the SBA also increases. For example, a 10% coverage on a one-million-dollar loan is higher than the loan coverage of 100,000 dollars at the same percentage. On the other side, we see that the amount the SBA covers decreases if the business has a revolving line of credit.

For our second research question, amongst the variables considered via apriori variable selection, we find eight of them significant at the α = 0.05 significance level: (1) the loan term, (2) the number of employees, (3) the number of jobs created, (4) whether the business is in urban or rural areas, (5) the revolving line of credit, (6) whether the loan is part of the LowDoc Loan program, (7) whether the loan was disbursed during recession years between 2007 and 2009, and (8) SBA’s guaranteed amount of approved. The loan term has the greatest impact on the probability of loan folding. Considering a loan of 20 years, as opposed to a 3-year loan, we expect the loan with a shorter term at a higher risk of default. One likely reason is that the shorter timeframe gives small businesses less time to manage their cash flow and pay back on time. Additionally, the 2008 recession is a crucial driver of the loan default status. According to Glennon and Nigro (2005), small businesses are more sensitive to local and industry time-varying economic trends. A market slowdown increases the likelihood of default. This explanation aligns with our research finding that the economic downturn has a comparably large negative impact on the default status of small businesses. We suspect that the reduced customer demand and decreased revenue during the recession are the leading causes.

## [Full Report] (SBA_Final_Report_12022022.pdf)
