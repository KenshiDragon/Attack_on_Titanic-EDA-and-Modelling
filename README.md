# Titanic Solution Beginner Walkthrough

The purpose of this notebook is to show how I have navigated through the Kaggle Titanic project by following an effective Data Science Workflow.

I will always treat this notebook as a **work in progress** because I will continuously seek to improve my work as I gain more knowledge and understanding throughout my Data Science learning journey.

## Data Science Workflow
> The foundation of this workflow was based on the author's citations in this [notebook](https://www.kaggle.com/code/ldfreeman3/a-data-science-framework-to-achieve-99-accuracy/notebook). I figured there was still room for more C's.
- **Comprehend.** *Exploratory Data Analysis.* Understand the nature and relationships among each features in the datasets through data analyses and visualization.
- **Correlate.** *Feature Selection* Validate the strength of association across features with the appopriate statistical tools and metrics, and to select the features that are significantly relevant with the solution goal.
- **Clean.** *Data Cleaning.* Identify and remedy missing/null values by imputing them with reasonable inputs.  
- **Create.** *Feature Engineering.* Create new features out of the existing ones which can make better predictions while also reducing noise in the number of features.
- **Classify.** *Feature Engineering.* Practice more advanced feature engineering involving effectively classifying labels/classes that are similar in terms of distribution, which also aims to reduce noise.
- **Convert.** *Data Preprocessing.* Perform the necessary adjustments (one-hot encoding) and data transformations (i.e. sqrt, log trasformations) to make the data fit for modelling.
- **Complete.** *Training Model.* Completion of a working and cleaned dataset in preparation for training the model and predicting solutions out of it. 
- **Configure.** *Hyperparameter Tuning.* Further optimize our learning algorithms by determining and running the optimal parameters. 
- **Combine.** *Ensemble Learning.* Combine multiple algorithms into one that can leverage the strengths and compensates the weaknesses of the tested models.

## Assumptions
To prevent **data leakage and cheating,** analyses and data transformations will exclusively be done and derived based on training data alone without the support of the test data.
> Data leakage happens when information outside of train set was used to assist in creating model. While there is merits to substantially achieve higher scores on our train and validation sets alone, this model will usually result in poorer performances when ran on other testing sets that are **new** and **unseen.** 

## Background of the Problem
The complete overview and description of the Kaggle competition be found [here](https://www.kaggle.com/c/titanic). Here are some of information we were provided with the link.
- On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg.
- Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
- While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.


I am very thrilled to present this first project. I am still a novice as I venture my journey in this field of data science and machine learning so any form of feedback and recommendation for my work are welcome. I am always looking forward to hear them out and take this opportunity to learn more things and to further enhance my skills. 
