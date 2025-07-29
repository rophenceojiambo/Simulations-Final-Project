#  Evaluating Missing Data Handling Techniques Under Different Missingness Mechanisms

![MD](Analysis/MD.png)


## Overview

In epidemiological and clinical research, missing data is a common statistical challenge. Whether
due to participant dropout, data collection errors, or selective non response, missingness can
lead to biased parameter estimates, loss of statistical power, and invalid inferences if not
properly addressed. 


## Methods

We used the UCI Obesity dataset, which originally contained no missing values, to explore the distribution of key predictors related to obesity. To evaluate missing data handling methods, we introduced artificial missingness under three mechanisms: Missing Completely at Random (MCAR), Missing at Random (MAR), and Missing Not at Random (MNAR). We formally tested the MCAR condition using Little’s MCAR test on the simulated MCAR dataset. For MAR and MNAR, formal testing was not feasible; instead, we visualized the missing data patterns to assess structure and plausibility. Multiple imputation techniques were applied to each simulated dataset to address missingness. Three imputation approaches were applied to each simulated dataset:

Multiple Imputation by Chained Equations (MICE)

Complete Case Analysis

Mean/Mode Imputation

Model performance was evaluated across all simulated datasets — as well as the original complete dataset — to assess how each method performed under different missingness conditions.

## Key Insights

Multiple imputation (MICE) consistently performed best across all missingness mechanisms, recovering accuracy and minimizing bias.

Complete case analysis performed reasonably well under MAR but led to biased estimates and data loss under MCAR and MNAR.

Mean/Mode imputation, while simple, was notably less effective — particularly under MNAR.

These results underscore that careful selection of imputation methods is critical, especially when missingness may not be MCAR
