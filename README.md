# Medium Post
https://medium.com/@rohanhazra4/analysing-indian-data-science-community-kaggle-2019-ml-ds-survey-56caf36df41

# Kaggle India Analysis
Analysing the Indian Ml and DS community through visualiztions.

## Table of Contents
1. [Project Motivation](#motivation)
2. [File Descriptions](#descriptions)
3. [Acknowledgements](#acknowledgements)


## Project Motivation <a name="motivation">

The goal of this project was to analyse the Indian ML and DS community.

I tried to answer four key questions:

1. What is the gender distribution in the field?
2. Do people with postgraduate degree earn more in India?
3. What job roles most Indian Kagglers have?
4. What is the age distribution of Indian Kagglers?

## File Descriptions <a name="descriptions">
  
  The jupyter notebook Kaggle_India.ipynb conatins all the codes. 
  
  multiple_choice_responses.csv : Contains all survey responses
  
  other_text_responses.csv : Other text responses from survey.
  
  questions_only.csv : The questions from the survey.
  
  survey_schema.csv : The entire schema os the survey.


## Acknowledgements<a name="acknowledgements"></a>

The dataset was downloaded from Kaggle. It is freely avaliable and you can also do your own study.
https://www.kaggle.com/c/kaggle-survey-2019/data


## CRISP-DM
1. Business Understanding

Surveys are done to understand the market and take relevant Business decisions. Many third party companies can use the Survey Data from Kaggle and update their products and services. 

2. Data Understanding

If we look at the survey responses file, we can see it has total 19717 responses. Total 20 Questions were asked as the part of the survey. Many of the columns have multiple choice answers. Kaggle has published the survey methodology here: https://www.kaggle.com/c/kaggle-survey-2019/data

3. Data Preparation

To prepare the dataset, I took a subset of Indian Kagglers. We proceed with further data cleaning according to the different Questions posed. People having Undergraduate and Postgraduate degrees were separated. Further preprocessing was done to remove all null-values from the dataset. 

4. Plotting

The pandas plotting library was used to plot the gender distribution,salary according to education,job-roles and age distribution.

5. Evaluation

Results can be concluded only on the basis of this survey, which mayn't be representive of the population. We need to keep in mind that maybe many surveyors had a response bias. https://en.wikipedia.org/wiki/Response_bias
The findings here are merley observational, not the result of a formal study.

6. Deployment

The code is hosted on github in the notebook Kaggle_India.ipynb. More questions can be asked according to the needs of the user. 
