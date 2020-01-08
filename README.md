# DSCore_W4_Independent-project
Analysis of AutoLib data (Paris, France) to test different hypotheses.

## Problem Statement
*Autolib'* was an electric car sharing service which was inaugurated in Paris, France, in December 2011. It was operated by the Bolloré industrial group, and complemented the city's bike sharing scheme

The variable I will be testing is The total counts per day for **Blue Car rentals** in Bourg-la-Reine and Bagnolet, identified in the data by their post codes.
Bourg-la-Reine and Bagnolet are two communes located in Paris, France.

## Null Hypothesis (H0)
The Bourg-la-Reine commune in Paris, benefits from being a residential area and as a result sees more (or equal) electric car rental activity than Bagnolet.

## Alternate Hypothesis(H1)
Bagnolet, by virtue of being a more metropolitan area of Paris, sees more electric car rental activity compared to Bourg-la-Reine which is a more suburban area in nature.

This hypothesis is an interesting one because it compares two completely different parts of the city, which use the same service. The ways of life are different and this should be reflected here. 

## Data Description
Provide information about the data necessary to understand the rest of the report including a precise statement of the random variable.
Provide a description of the source of your data and the data collection procedures, the descriptive statistics, and some assertions about the model that is consistent with the data. 

## Hypothesis Testing Procedure
Occurences for both range between 147 and 156. We can use a sample size that's close to 50%. We will use n = 75. That means we will pick 75 random samples from our data to use for hypothesis testing.

We will use a z_score as the test statistic since our sample size contains more than 30 elements.

My chosen level of significance (Alpha) is 0.05


## Hypothesis Testing Results
The z score is -18.546

The p value is 8.626621621551957e-77

## Summary and Conclusions
Compared to our level of significance stated earlier, the p value is much higher.

This means that our test is statistically insignificant. It also means that we reject the alternate hypothesis.

## Concluding statement concerning the hypothesis, the results, and the sensitivity of the testing.
Random sampling is not a 'silver bullet' for hypothesis testing. The samples may be chosen in a way that makes the sample set skew one way, i.e. bias is introduced.

Stratification of the population can help mitigate this, but even that is not foolproof.

GOOD PRACTICE IS to QUESTION the results of the hypothesis testing and iterate with improvements, as opposed to completely abandoning the entire premise. A rejection of the alternate hypothesis is not equal to complete failure.
