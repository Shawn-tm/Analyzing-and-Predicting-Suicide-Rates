Analyzing and Predicting Suicide Rates

This repository attempts to look at the suicide rates through the lens of other census factors as predictors. 
The goal is to look for correlations between these factors and suicide rates, with the goal of being able to predict suicide rates from the environmental factors and in an ideal world mitigate or propagate environmental factors to decrease suicide rates.

My first steps in this process began with collecting the data from the World Bank, CDC, and a Kaggle dataset. This data was then wrangled in Capstone1-Divorce,Lat,suicide.ipynb and Capstone1-main.ipynb where I ultimately segregated a few datasets.

The cleaned datasets were then able to pass an exploratory analysis process in ExploratoryAnalysis.ipynb and further analysis in Statistical Analysis.ipynb.

From the direction given in the data analysis, I crafted machine learning models and optimized my models by testing different weights and parameters against the Mean Squared Error and R2 of the test model on unseen data. This work can be found in Machine learning-Suicide Rates.ipynb.

Please see my presentation slides at Analyzing and Predicting Suicide Rates Slides.pdf for an in-depth examination of the code and my findings. 
