---
layout: post
title: Analyzing the outcome of the 2020 Elections
description: The goal of this data analysis is to gather a deeper understanding of why Donald J. Trump won the 2016 elections. 
summary: From this data, we hope to see if any inferences can be made to help candidates prepare for the 2020 elections. Our analysis proposes that there are 3 factors that led to Donald J. Trump winning the election which includes : Publicity, Hate Crime, & Unemployment rates (which we are calling environmental factors).
tags: [EDA: Explatory Data Analysis]
---

       	We have completed our analysis of the results of 2016 presidential election. Based on our analysis, we built the models which can contribute to the predictions of the winning chance of the candidate in each state. The following are the results of our analysis and predictor models.
Problem: The Republican Party wants to know on which factors the party should pay more attention in order to promote the candidate better in the states.
Hypotheses: The environmental factors such as hate crimes, unemployment and publicity had impacts on the voting results of the 2016 presidential election.
Exploratory Data Analysis
We first cleaned the data and created the final dataset that we will be using throughout the whole analysis process. The following link will take you to the final dataset tables.
View Table: Final Data
In this dataset, the numbers you will see under the column, “Votes” is the voting ratio that the candidates from Democratic and Republican parties received in each state. We calculated the voting ratio by dividing the number of votes that each candidate got in a state by the total number of votes from that state. Therefore, if the voting ratio is 0.5, that means both candidates won the same votes. If the voting ratio is smaller than 0.5, the candidate lost in that state, and if the voting ratio is larger than 0.5, the candidate won that state.
 
Observation: The publicity graph shows an analysis on the relationship between the Publicity and Voting Ratio each candidate received during the 2016 election. By looking at the graph, you may note that the candidates won in the states where they gained more popularity.
 
 Observation: The graph above shows the voting ratio of each candidate in the states with different unemployment rates. It seems like Trump won states with low unemployment rates whereas Clinton won the states with larger unemployment rates.
 
 Observation: This graph is to convey how the hate crime rates impact the winning chance of the candidates. From the graph, we can see that Trump mostly won the states with less hate crime rate compared to Clinton who won the states with more hate crimes.
All these graphs and observations are the results of the exploratory data analysis.
The following are building the models to predict which environmental factor has the most impact on the voting ratio.
Building Predictor Models
Predictors: 
  Type of variable: All are numerical.
         (1) Mean Unemployment                         	
  	     (2) Hate Crimes
  	     (3) Publicity         	

Response: Voting Ratio                                	        	
        Type of variable: Numerical
        Type of modelling: Simple Linear Regression
        
Relationship between Publicity and Voting Ratio
 
The plot shows that there is a linear relationship between the publicity of Trump, the predictor variable, and voting ratio, the response variable.
After fitting into the model, it shows that
(1) As the R2 value is 0.9651, it is very close to 1, implying that there is a very strong relationship between the two variables.
(2) The Pr(>|t|) value of the model is described as <2e-16, so it is less than the significant level of 0.05, which means publicity is a good predictor of the voting ratio.
(3) If the publicity increases by 1, the voting ratio for Trump will increase by 0.0104671.
(4) For accuracy, the RSE value is 0.0242.
(5) The RMSE value after k-fold cross-validation is 0.02486383.

 
 
The plot shows that a linear relationship exists between publicity and voting ratio for Clinton.
 After fitting into a simple linear regression model, we now know that
(1) There is a very strong relationship between the two variables as the R2 is equal to 0.9806 which is almost equal to 1.
(2) Publicity contributes to voting ratio because the Pr(>|t|) value is 2e-16 and it is much less than 0.05.
(3) Clinton will receive more voting ratio of 0.0103595 for every 1 unit increase in her publicity.
(4) The RSE value of this model is 0.01802.
(5) From cross validation, we get the RMSE value which is 0.01782725.
