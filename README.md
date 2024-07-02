# ANOVA Analysis of a New Compound for Hay Fever Relief

# Overview
This project involves analyzing data from an experiment conducted by a research laboratory to develop a new compound for the relief of severe hay fever. The experiment included 36 volunteers, with varying amounts of two active ingredients (A and B) at three levels each. The dataset Fever.csv contains the hours of relief experienced by the volunteers. This analysis involves performing one-way and two-way ANOVA to understand the effects of the active ingredients on relief duration.

# Table of Contents
* Hypothesis Statement
* Data Description
* One-way ANOVA Analysis
* Interaction Plot
* Two-way ANOVA Analysis
* Business Implications

# Hypothesis Statement
# One-way ANOVA for Ingredient A
Null Hypothesis (H0): The hours of relief derived by the volunteers across all three different variations of ingredient A are the same. 
H0: μ1 = μ2 = μ3
Alternate Hypothesis (H1): The hours of relief derived are different for at least one of the three variations of ingredient A. 
H1: Not all means are equal

# One-way ANOVA for Ingredient B
Null Hypothesis (H0): The hours of relief derived by the volunteers across all three different variations of ingredient B are the same.
H0: μ1 = μ2 = μ3
Alternate Hypothesis (H1): The hours of relief derived are different for at least one of the three variations of ingredient B.
H1: Not all means are equal

# Data Description
The dataset Fever.csv contains the following columns:

* Volunteer_ID: Identifier for each volunteer
* A: Level of ingredient A
* B: Level of ingredient B
* Relief: Hours of relief experienced by the volunteer

# One-way ANOVA Analysis
# ANOVA Results for Ingredient A

![image](https://github.com/nit-stack/ANOVA-Analysis-of-a-New-Compound-for-Hay-Fever-Relief/assets/174468592/ab3b3351-718a-4a48-94f1-13187f1dc930)

# Conclusion
The P-value is less than 0.05, hence we reject the null hypothesis. There is significant evidence that the hours of relief differ among the different levels of ingredient A.

# ANOVA Results For Ingredient B

![image](https://github.com/nit-stack/ANOVA-Analysis-of-a-New-Compound-for-Hay-Fever-Relief/assets/174468592/727dce24-990f-4dcc-8cc9-8bd655fe54db)

# Conclusion
The P-value is less than 0.05, hence we reject the null hypothesis. There is significant evidence that the hours of relief differ among the different levels of ingredient B.

# Interaction Plot

![image](https://github.com/nit-stack/ANOVA-Analysis-of-a-New-Compound-for-Hay-Fever-Relief/assets/174468592/1b2e86c6-ef72-4210-9e4a-3806be078346)

The interaction plot and the derived P-value indicate that there is a 95% certainty that there exists a statistically significant interaction between ingredients A and B.

# Two-way ANOVA Analysis
# Hypotheses
# Null Hypotheses

•  H0 (A): μA1=μA2=μA3
•  H0 (B): μB1=μB2=μB3
•  H0 (A*B): There is no interaction effect between A and B

# Alternate Hypotheses

H1 (A): Not all means of A are equal
H1 (B): Not all means of B are equal
H1 (A*B): There is an interaction effect between A and B

# ANOVA Results

![image](https://github.com/nit-stack/ANOVA-Analysis-of-a-New-Compound-for-Hay-Fever-Relief/assets/174468592/613bb363-7fe0-4c8e-ba63-5c27c40c7c6a)

# Conclusion
The P-values for ingredients A, B, and their interaction are all less than 0.05, indicating strong evidence that both ingredients affect the relief and that there is a significant interaction between ingredients A and B.

# Business Implications
Performing ANOVA allows us to understand the effects of the active ingredients on relief duration. It informs us if the variation in ingredients results in different outcomes, which is crucial for optimizing the compound. In this case, the analysis shows significant differences in relief hours based on ingredient levels and a significant interaction between the ingredients. This knowledge helps in formulating the most effective compound for maximum relief.
