# Model Selection: Information Criteria Comparison

## Objective of the project: 
In this article, we analyze model selection by Information Criteria. Comparing two estimation methods, different processes, different coefficients for each series and four sample sizes, we analyse Information Criteria performances resulting from these factors. On the one hand, in terms of EstimationMethods, the Maximum Likelihood Estimation does not converge and therefore has no interesting and robust elements to conclude on. On the other hand, the estimation by Generalized Autocorrelation allows us to obtain interesting results. Some Information Criteria give the same performances even if, mathematically, they are different. For the sample size, we see that the more the sample size is large, the more Information Criteria will find the right process and right orders. Underfitting and overfitting percentages vary from one Information Criteria to another depending on the sample size and their penalty function. Another interesting conclusion comes from corrected Information Criteria. They tend to have a lot of underfitting, especially when the sample size increases. As our coefficients vary, their penalty function may be too restrictive. Finally, some processes and even some orders are easily selected by Information Criteria while some others are much more complicated to cast.

## Contents 
<br/>1. **Rapport**
<br/>Pdf file containing the project report.

<br/>2. **code_example**
<br/>In this study we are interested in ARMA model selection by information criteria. It will be based
on 10 000 realizations of 12 different ARMA with different sample sizes. This code is an example of an ARMA simulation with the calculation of information criteria in SAS.
