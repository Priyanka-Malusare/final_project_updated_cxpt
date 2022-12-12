First-I created a Demographics table for comparing all the variables in the data and giving an overview of characteristics of the data.

Using the describe function helped me understand the characteristics of the variable that i'm interested in. The variable being incidence of 30-day mortality.

For the analysis of probability: I first created a count matrix of month and ccsmort30rate.The ccsmort30rate was calculated per 10,000 patients.Hence using that knowledge i converted it to number of deaths for easy interpretaion of data. Using for loop I calculated the probability of death of a patient in the month of october as compared to othe rest of the months.

For another probability analysis: I analyzed the probability of gender and complications using probability matrix.

For the analysis of sensitivity of tests: I created a confusion matrix using variables cancer and compliactions.Cancer is one of the confounding variables that could affect mortality rate.The sensitivity and specificity was calculated using this confusion matrix.

The outliers were detected and removed using iqr method.It also gave a fair idea of the outliers in the dataset and if they can be ignored.

For statistics: I calculated the measures of central tendencies, spread of the data, distributionsummary and varibaility using the statistical parameters.This helped me summarize my data in a table to give an overview of the statistical summary.

Hypothesis testing: For the hypotheisis testing for month october and december, I first checked if my data was normally distributed using data visualization.It was not normally distributed. For that reason, I normalized the data before resorting to non parametric tests. After normalization, i performed two samppled independent t test followed by a  mann whitney test for confirmation.I also performed a chi square test to check the realtion between Complications and surgery in october.

Hypothesis testing: For the hypotheisis testing for month october and december, I first checked if my data was normally distributed using data visualization.It was not normally distributed. For that reason, I normalized the data before resorting to non parametric tests. After normalization, i performed two samppled independent t test followed by a  mann whitney test for confirmation.I also performed a chi square test to check the realtion between Complications and surgery in december.

For correlation analysis: I used spearman's correlation test since the scatterplot revealed that the data is non parametric.The results showed no correlation between age and the incidence of mortality rate.

I also showed a correlation matrix for comparison of all my data.
