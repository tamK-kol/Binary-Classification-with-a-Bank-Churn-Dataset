**Binary Classification with a Bank Churn Dataset**
Playground Series - Season 4, Episode 1

**Overview**
Welcome to the 2024 Kaggle Playground Series! Happy New Year! This is the 1st episode of Season 4.

Our Goal: For this Episode of the Series, our task was to predict whether a customer continues with their account or closes it (e.g., churns).

**Evaluation**
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

**Submission File**
For each id in the test set, you must predict the probability for the target variable Exited. The file should contain a header and have the following format:
id,Exited
165034,0.9
165035,0.1
165036,0.5
etc.


**About the Tabular Playground Series**
The goal of the Tabular Playground Series is to provide the Kaggle community with a variety of fairly light-weight challenges that can be used to learn and sharpen skills in different aspects 
of machine learning and data science. The duration of each competition will generally only last a few weeks, and may have longer or shorter durations depending on the challenge. 
The challenges will generally use fairly light-weight datasets that are synthetically generated from real-world data, and will provide an opportunity to quickly iterate through various model 
and feature engineering ideas, create visualizations, etc.

**Synthetically-Generated Datasets**
Using synthetic data for Playground competitions allows us to strike a balance between having real-world data (with named features) and ensuring test labels are not publicly available. 
This allows us to host competitions with more interesting datasets than in the past. While there are still challenges with synthetic data generation, the state-of-the-art is much better now 
than when we started the Tabular Playground Series two years ago, and that goal is to produce datasets that have far fewer artifacts. Please feel free to give us feedback on the datasets for 
the different competitions so that we can continue to improve!

