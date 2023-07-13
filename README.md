# housing_project
In this notebook, I tend to show my skills as a student of Data Science and Machine Learning. This is my second project on [kaggle](https://www.kaggle.com/code/numustafa/notebook225446ceef/edit/run/132462716), and I will apply all of my Machine Learning knowledge to predict the Housing Prices. To improve upon my workflow, I followed the Kaggle Tutorial, Ken Jee's workflow techeniques and ChatGPT for more elaboration.

## Code and Resources Used
Python Version: 3.11 <br>
IDE: VSCode <br>
Workflow building: [KenJee](https://github.com/PlayingNumbers)<br>
Typical concept building: [ChatGPT](https://openai.com/blog/chatgpt) <br>

# Understand Data
This data has 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. The goal is to predict the final price of each home. Following steps shows how I understand the data and what I did to make it more understandable:
* Generate Summary Statistics
* Evaluate Null Values
* Check the distribution of the target variable
* Check the distribution of the features
* Exploratory Data Analysis (EDA)

# Data Preprocessing
Here, I created a data pipeline, a techenique learned from [Ken Jee](https://github.com/PlayingNumbers), to preprocess the data. This pipeline will help me to preprocess the test data as well. Following steps shows what I did to preprocess the data:
* Drop the features with more than 50% null values
* Replace the numerical and categorical null values with the median and mode respectively

# Feature Engineering
Redefine few variables to make them more understandable. Following steps shows what I did to preprocess the data:
* Convert the numerical variables to categorical variables where it makes sense
* Convert the categorical variables to numerical variables where it makes sense


