# British_Airways_Project 

At TheForage provides a free virtual work experience opportunity where they give you a real world project 
directly from companies for you to solve and simulate the role you are pursuing.

This repo contains my solutions and attempt at the British Airway work experience.

I webscraped two datasets intially, one with just text reviews and another with text reviews and as well as the rating the consumer associated with the review.
The data was saved as csv files and then read into pandas dataframes.

for the first task, I had to analyze what the topics reviewers were mostly discussing:
After cleaning the data, for my first analysis I carried out a wordcloud to see what words occured the most.
Later I decided to use Python's Natural Language Toolkit to perform a topic analysis for improved insight.
I also did a sentimental analysis to see whether the reviews were more negative or positive.

Lastly, I was given the task of creating a predictive model:
I used the random forest machine learning algorithm to create a predictive model which predicts the consumer booking behaviour, whether they book or not. 
I also summarized what features contributes most to the prediction model. 
