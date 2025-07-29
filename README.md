#  Evaluating Missing Data Handling Techniques Under Different Missingness Mechanisms

![MD](Analysis/MD.png)


## Overview

In epidemiological and clinical research, missing data is a common statistical challenge. Whether
due to participant dropout, data collection errors, or selective non response, missingness can
lead to biased parameter estimates, loss of statistical power, and invalid inferences if not
properly addressed. 


## Methods

We applied a comprehensive approach to evaluate missing data patterns and mechanisms. Initial exploratory analyses included quantifying the extent and distribution of missingness across variables. We assessed whether data were missing completely at random (MCAR), missing at random (MAR), or missing not at random (MNAR) using statistical tests such as Little’s MCAR test and visualizations like missingness maps. Sensitivity analyses and multiple imputation techniques were employed to handle missing data and evaluate the robustness of study findings under different assumptions.


## Key Insights


Missingness varied substantially across key variables, highlighting potential bias if ignored.

Evidence suggested that missing data were not completely random, necessitating appropriate handling methods.

Multiple imputation improved data completeness and reduced bias compared to complete-case analysis.

Sensitivity analyses underscored the importance of modeling missingness mechanisms to ensure valid inferences in epidemiological studies.
