# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: SAT and ACT Analysis


### Problem Statement

The problem of low SAT participation rates in various states has an impact on the profits of our College board, we will be to looking to identify and provide a solutions to increase the participation rates.


### Executive Summary

The aim is to examine the scores and participation rates for SAT and ACT in 2017 and 2018. To identify the relationship between each features and make approriate recommedations on how SAT can improve the participation rate of the states. 

Data is organized by state level for all the dataset, with participation rate and section score as columns. First We have to clean the data by removing any duplicates entries and set the approriate datatype for each columns. We also need to look for any suspicious data that might corrupt and provide inaccuracy. We do this by checking for any numbers that are out of the norm, and investigate further if there's any. I will then merge the data into a single dataframe and plot the different graphs to further explore the relationship of each features.

Based on our findings, the high participation rate of each test depends heavily on the state's policies, states with mandatory testing will have high participation. ACT and SAT participation rates tends to mirror each other as the states willl only prefer one over the other.

The Total/Composite Scores on a given test are highly negatively correlated with participation rate. Lower participation rate means higher mean score and vice versa. This is mainly due to selection bias, when the particular test is not compulsory in the state, only higher achieving students would take up the test and hence a higher average score. 

Although ACT is the preferred testing for most states, but we do see that there's an increase in mean participation rate for SAT from 2017 to 2018. This is mainly because Illinois and Colorado have switched to SAT testing in 2018.


### Conclusion and Recommendations

With the findings, the participation rate generally depends alot on the state's policies. Without the support of the state, participation rate most likely will remain low.  

Georgia is one of the state we feel that there's alot of potential. The participation rate for SAT and ACT are both above 50%. This shows that the students in the states does not really favour one test to another. Which present an oppportunity for SAT board. There's also an 9% increase in SAT participation rate in 2018 which indicate increasing trend towards SAT. 

Having said that, SAT board should also work with college and high school. A college admission criteria based on the test would have a great impact on the participation rates. When a well reputable college or high school uses SAT as the admission criteria, this will have a huge impact on the percived value of the test. Which will help the states to make decision on which test should be the preferred test in that particular state.


### Datasets


For this project, i will be using the following datasets:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)
- [2018 ACT Scores](./data/act_2018.csv)
- [2018 ACT Scores](./data/act_2018.csv)

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017 and 2018.


### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|SAT/ACT|The participating states| 
|**sat_2017_participation**|*float*|SAT 2017|The percentage(decimal) of SAT 2017 pariticipation rate|
|**sat_2017_read_write**|*integer*|SAT 2017|The average score for SAT 2017 Evidence-Based Reading and Writing (200-800)| 
|**sat_2017_math**|*integer*|SAT 2017|The average score for SAT 2017 Math (200-800)| 
|**sat_2017_total**|*integer*|SAT 2017|The total SAT 2017 score for Math and Evidence-Based Reading and Writing (400-1600)|
|**act_2017_participation**|*float*|ACT 2017|The percentage(decimal) of ACT 2017 pariticipation rate|
|**act_2017_english**|*float*|ACT 2017|The scaled score for ACT 2017 English (1-36)| 
|**act_2017_math**|*float*|ACT 2017|The scaled score for ACT 2017 Math (1-36)| 
|**act_2017_read**|*float*|ACT 2017|The scaled score for ACT 2017 Reading (1-36) | 
|**act_2017_science**|*float*|ACT 2017|The scaled score for ACT 2017 Science (1-36) | 
|**act_2017_composite**|*float*|ACT 2017|The Composite(average) score for ACT 2017(1-36) | 
|**sat_2018_participation**|*float*|SAT 2018|The percentage(decimal) of SAT 2018 pariticipation rate|
|**sat_2018_read_write**|*integer*|SAT 2018|The average score for SAT 2018 Evidence-Based Reading and Writing (200-800)| 
|**sat_2018_math**|*integer*|SAT 2018|The average score for SAT 2018 Math (200-800)| 
|**sat_2018_total**|*integer*|SAT 2018|The total SAT 2017 score for Math and Evidence-Based Reading and Writing (400-1600)|
|**act_2018_participation**|*float*|ACT 2018|The percentage(decimal) of ACT 2018 pariticipation rate|
|**act_2018_composite**|*float*|ACT 2018|The Composite(average) score for ACT 2018(1-36) | 

---

