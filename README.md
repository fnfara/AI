# In Task_Titanic
Titanic Survival Analysis by Gender and Outcome
Project Overview
In this project, I analyzed the Titanic dataset to examine whether age is distributed similarly across four passenger groups, based on gender and survival status:

Surviving men

Deceased men

Surviving women

Deceased women

The goal was to determine, using statistical tests, whether there are significant differences in age distribution between these groups.

Dataset
The analysis uses the Titanic dataset (e.g., available on Kaggle or via seaborn). Relevant columns include:

Sex (gender)

Age

Survived (1 = survived, 0 = did not survive)

Analysis Steps
Data Preprocessing

Removed rows with missing age values.

Split the dataset into four groups based on gender and survival status.

Distribution Analysis

Performed the Shapiro-Wilk test to check for normality in the age distributions.

Statistical Testing

If distributions were normal, used t-test or ANOVA to compare means.

If distributions were not normal, used non-parametric tests such as the binomial test or Mann-Whitney U test, depending on the scenario.

Results
The analysis found (or did not find) statistically significant differences in age distributions between the groups.

Results are supported by visualizations and p-values from the appropriate statistical tests.

Libraries Used
pandas

numpy

scipy.stats
