# MechaCar Statistical Analysis
![autosRus.png](https://github.com/gracemarshall/MechaCar_Stats_Analysis/blob/main/autosRus.png)

## Project Overview
The objective of this analysis is to perform data analytics to do the following;
 * Perform multiple linear regression analysis to identify which variables in the data-set predict the mpg of MechaCar prototypes.
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

##  Results
## Linear Regression to Predict MPG
![dataframe.png](https://github.com/gracemarshall/MechaCar_Stats_Analysis/blob/main/mechacar_df.png)

![linear_Regression.png](https://github.com/gracemarshall/MechaCar_Stats_Analysis/blob/main/MechaCar_Summary.png)

![Multiple_Regression.png](https://github.com/gracemarshall/MechaCar_Stats_Analysis/blob/main/Multiple_Reg.png)

## Summary Statistics on Suspension Coils
![lot_summary.png](https://github.com/gracemarshall/MechaCar_Stats_Analysis/blob/main/lot_summary.png)

![total_summary.png](https://github.com/gracemarshall/MechaCar_Stats_Analysis/blob/main/total_summary.png)

## T-Test on Suspension Coils

![onesample_ttest.png](https://github.com/gracemarshall/MechaCar_Stats_Analysis/blob/main/onesample_ttest.png)

![lot_1.png](https://github.com/gracemarshall/MechaCar_Stats_Analysis/blob/main/lot1_susp_ttest.png)

![lot_2.png](https://github.com/gracemarshall/MechaCar_Stats_Analysis/blob/main/lot2_susp_ttest.png)

![lot_3.png](https://github.com/gracemarshall/MechaCar_Stats_Analysis/blob/main/lot3_susp_ttest.png)

## Research Design Comparing the MechaCar to the Competition
Using your knowledge of R, a statistical study is conducted to compare performance of the MechaCar vehicles against performance of vehicles from other manufacturers. The study design  defines the study type, research question, hypotheses, variables, and data collection methods. 

The statistical study design include:
## Research Questions
The research questions that guided this study were:
* Research Question 1: What are the comparable price between models by manufacturer from mechaCar and its competitors? 
* Research Question 2: which of the models by manufacturer are the highest performers in terms of safety feature performance in a head-to-head collision?
* Research Question 3: which of the models by manufacturer have the best resale value?
* Research Question 4: which of the models by manufacturer have manufacturer’s warranty rather than a third-party warranty?
* Research Question 5: which of the models by manufacturer gives overall MPG of 38 or greater?

## Hypotheses
The following hypotheses were tested:
* H01: There is no relationship between comparable price between models by manufacturer from mechaCar and its competitors.
* HA1: There is a relationship between comparable price between models by manufacturer from mechaCar and its competitors.
* H01: There is no relationship between the models by manufacturer are the highest performers in terms of safety feature performance in a head-to-head collision.
* HA1: There is a relationship between the models by manufacturer are the highest performers in terms of safety feature performance in a head-to-head collision..
* H01:There is no relationship between the models by manufacturer models by manufacturer in terms of resale value.
* HA1:There is a relationship between the models by manufacturer models by manufacturer in terms of resale value.
* H01:No models by manufacturer have manufacturer’s warranty rather than a third-party warranty.
* HA1:All models by manufacturer have manufacturer’s warranty rather than a third-party warranty.
* H01:No models by manufacturer gives overall MPG of 38 or greater?
* HA1:All models by manufacturer gives overall MPG of 38 or greater?

## Variables
### Independent Variables
* safety 
* collision performance
* resale value
* manufacturers warranty
* MPG (gasoline) performance

### Independent Variables
* price 

## Data collection methods
Historical data will spanning 3 years will be collected from MechaCar and 3 to 5 competitors for comparisons. 

The statistical analysis that would be used to test this study after data * collection and plotting the raw data into RStudio include;
* correlation using scatter plot to find the R-value or the correlation coefficient. 
* The Bell Curve of a normal distribution with mean zero and a Standard Deviation of one will be used for further analysis.
* A null hypothesis or an alternative hypothesis is described
* A statistical test is described to test the hypothesis

