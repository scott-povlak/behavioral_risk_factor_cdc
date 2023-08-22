Data import and exploration: 
  Loaded tidyverse and ggplot.
  Used head() to look at data structure.

General health analysis: 
  Used filter and summarise to identify and count number of people who reported general health as poor.

Distribution of poor physical and mental health: 
  Created two histograms to visualize the distribution of people with poor physical and mental health using ggplot2
  Creating these visualizations helped demonstrate the similarities between the two variables.

Comparing physical health for veterans: 
  Used group_by() and summarise to compare meand and std of veterans vs. non-veterans.

Summary statistics for diabetes: 
  Calculated summary statistics(mean, median, std) for the age of which people were diagnosed with diabetes.

Prediction of mental health from employment status: 
  Used linear regression to predict number of days with poor mental health based on emplyoment status.  
  The model was statistically significant according to the p-value, but R-squared shows the overall variability
  explained by the model is relatively low.

ANOVA for physical activity and employment status: 
  Conducted ANOVA to compare frequency of participating in physical activity across employment status.  
  This was again statistically significant and suggests differences between some employment groups and activity
  status.

Box plot for ANOVA: 
  Created a box plot to visualize the relationship between physical activity and employment status from the ANOVA above. 
