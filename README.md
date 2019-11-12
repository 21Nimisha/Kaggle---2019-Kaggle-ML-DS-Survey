# Kaggle---2019-Kaggle-ML-DS-Survey
The most comprehensive dataset available on the state of ML and data science

Data Description -

Survey Methodology
This survey received 19,717 usable respondents from 171 countries and territories. If a country or territory received less than 50 respondents, we grouped them into a group named “Other” for anonymity.

We excluded respondents who were flagged by our survey system as “Spam”.

Most of our respondents were found primarily through Kaggle channels, like our email list, discussion forums and social media channels.

The survey was live from October 8th to October 28th. We allowed respondents to complete the survey at any time during that window. The median response time for those who participated in the survey was approximately 10 minutes.

Not every question was shown to every respondent. You can learn more about the different segments we used in the survey_schema.csv file. In general, respondents with more experience were asked more questions and respondents with less experience were asked less questions.

To protect the respondents’ identity, the answers to multiple choice questions have been separated into a separate data file from the open-ended responses. We do not provide a key to match up the multiple choice and free form responses. Further, the free form responses have been randomized column-wise such that the responses that appear on the same row did not necessarily come from the same survey-taker.
 

- Data Sources
1 - multiple_choice_responses.csv = 
Multiple choice single response questions fit into individual 
columns whereas multiple choice multiple response questions were split into multiple columns. 
Text responses were encoded to protect user privacy and countries with fewer than 50 respondents were grouped into the category "other".

2 - other_text_responses.csv = 
If "Other" is selected there is also an option to provide a text response. 
These text responses were separated and shuffled to protect user privacy.

3 - questions_only.csv  =
The list of questions from the 2019 Kaggle Data Science and Machine Learning Survey

4 - survey_schema.csv = 
Survey schema describing which questions were presented to which respondents. 
In general, respondents with more experience were asked more questions than respondents with less experience.
