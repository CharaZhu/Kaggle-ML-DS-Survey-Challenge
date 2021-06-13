# Kaggle ML & DS Survey Challenge

Kaggle has hosted an open data scientist competition in 2020 titled “Kaggle ML & DS Survey
Challenge.” The purpose of this challenge was to “tell a data story about a subset of the data science
community represented in this survey, through a combination of both narrative text and data exploration.”

More information on the competition, data, and prizes can be found on: https://www.kaggle.com/c/kaggle-survey-2020/data

The dataset provided (kaggle_survey_2020_responses.csv) contains the survey results provided by
Kaggle. The survey results from 20036 participants are shown in 355 columns, representing survey
questions. Not all questions are answered by each participant, and responses contain various data types.


## Data Files:
1. clean_kaggle_data.csv: survey responses with yearly compensation.
2. clean_kaggle_data_2020.csv: cleaned file to be read in notebook.
3. ○kaggle_survey_2020_responses.csv: original survey responses.
4. kaggle_survey_2020_answer_choices.pdf: the questions and answer choices in the survey.
5. kaggle_survey_2020_methodology.pdf: the methodology and survey flow logic of the survey.
 
## Running Order:

1. KaggleSalary_DataSet.ipynb: transform the original survey responses (kaggle_survey_2020_responses.csv) to the clean dataset clean_kaggle_data_2020.csv

2. Main.ipynb, Part 1: explore the survey data to understand (1) the nature of women’s representation in Data Science and Machine Learning and (2) the effects of education on income level.
* Exploratory Data Analysis 
* Statistical Analysis 

3. Main.ipynb, Part 2: train, validate, and tune multi-class ordinary classification models that can classify, given a set of survey responses by a data scientist, what a survey respondent’s current yearly compensation bucket is.
* Data Cleaning
* Feature Selection
* Model Implementation 
* Model Tuning
* Testing  

## Report:
Summarize the key stepes in IPython Notebook, present the results of analysis. 
