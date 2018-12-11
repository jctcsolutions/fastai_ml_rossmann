# The Rossmann Stores Sales Forecast Challenge 
The notebook in this repo tackles the Rossmann Store Sales competition hosted by Kaggle back in 2015 (for detail see: https://www.kaggle.com/c/rossmann-store-sales) via using random forest. This is meant to be a practice utilizing the FastAI 0.7 framework along with Scikit-learn modules. The full dataset can be downloaded from: https://www.kaggle.com/c/4594/download-all.

# The Goal
The goal of this exercise was not to beat the state-of-the-art, but rather to do a very naive, but DAMN QUICK attempt at solving a timeseries prediction problem, with a little feature engineering as possible using the tools provided by FastAI(0.7) as taught in Jeremy Howards' Machine Learning MOOC. (These courses can be found here: https://course.fast.ai/ml.html. They're AWESOME and you should go through them!)

# Summary
We fitted a Random Forest Regressor on the dataset at achieved a RMSPE score of 0.13169 on the public score, and 0.143 on the private score on Kaggle leaderboard. This is by no means performance to be proud of, but with next to no feature engineering, this score ranked 2032 position out of 3253 teams on the private leader board. Furthermore, it should be noted that this result did not utilize the additional supplementary datasets (ie. Google Trends dataset) that the winning solutions incorporated.
