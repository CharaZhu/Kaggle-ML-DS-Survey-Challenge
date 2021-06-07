# Kaggle ML & DS Survey Challenge

Kaggle has hosted an open data scientist competition in 2020 titled “Kaggle ML & DS Survey
Challenge.” The purpose of this challenge was to “tell a data story about a subset of the data science
community represented in this survey, through a combination of both narrative text and data exploration.”

More information on the competition, data, and prizes can be found on: https://www.kaggle.com/c/kaggle-survey-2020/data

The dataset provided (kaggle_survey_2020_responses.csv) contains the survey results provided by
Kaggle. The survey results from 20036 participants are shown in 355 columns, representing survey
questions. Not all questions are answered by each participant, and responses contain various data types.


## Data Files:

1. clean_kaggle_data_2020.csv: cleaned file to be read in notebook.
2. ○kaggle_survey_2020_responses.csv: original survey responses.
3. kaggle_survey_2020_answer_choices.pdf: the questions and answer choices in the survey.
4. kaggle_survey_2020_methodology.pdf: the methodology and survey flow logic of the survey.


## Running Order:

1. KaggleSalary_DataSet.ipynb: transform the original survey responses to the clean dataset 
2. Main.ipynb:
*  Part 1: explore the survey data to understand (1) the nature of women’s representation in Data Science and Machine Learning and (2) the effects of education on income level.
*  Part 2: 
