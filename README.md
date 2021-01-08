# IncomePrediction
Income prediction model based on U.S. Census dataset

## Overview
In this project, I am going to make prediction on whether a person's income is above 50k or below 50k using various features such as age, marrital status, occupation, and education. The dataset comes from 1994 US Census on adults, and it can be downloaded in <https://www.kaggle.com/uciml/adult-census-income>.

## Motivation
Building such prediction models can improve the understanding of population and various factors leading to high income growth. Governments can utilize this knowledge to develop socio-economic policy making that better addresses economic growth and social equity.

## Problem Type
The dependent variable for prediction is the 'income' feature that has two discrete categories of income higher than 50k and less than or equal to 50k. The problem is thus a Supervised Binary Classification type.

## Approach
The dataset contains 32561 rows and 15 features. I'll first explore the dataset with focus on distributions, then using the insights from raw data, I'll conduct data preprocessing. 
For modeling, I'll employ various supervised learning algorithms, and compare the results using f1 score.
