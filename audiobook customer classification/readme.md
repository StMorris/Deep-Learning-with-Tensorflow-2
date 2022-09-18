






## Audiobook App Users Classification Model

<img src = 'https://github.com/StMorris/web_scraping/blob/main/rotten_tomatoes_140_action_movies/resized_imagee.png'>

#### We want to create a machine learning algorithm based on available data, that can predict if a user will buy again from the Audiobook company.

#### The main idea is that if a user has a low probability of coming back, there is no reason to spend any money on advertizing to him/her. 
#### If we can focus our efforts ONLY on users that are likely to convert again, we can make great savings, increase sales and profitability. Moreover, this model can identify the most important metrics for a customer to come back again.

####  Identifying new users creates value and growth opportunities.

####  So, in fact, we are predicting if: based on the last 2 years of activity and engagement, a user will convert in the next 6 months. 6 months sounds like a reasonable time. If they don't convert after 6 months, chances are they've gone to a competitor or didn't like the Audiobook way of digesting information.

#### The task is simple: create a machine learning algorithm, which is able to predict if a user will buy again.
This is a classification problem with two classes: won't buy and will buy, represented by 0s and 1s.


## Dataset

You are given data from an Audiobook app. Logically, it relates only to the audio versions of books. Each customer in the database has made a purchase at least once, that's why he/she is in the database. 

#### There are several variables contained in the dataset:
Customer ID, 
Book length in mins_avg (average of all purchases), 
Book length in minutes_sum (sum of all purchases), 
Price Paid_avg (average of all purchases), 
Price paid_sum (sum of all purchases), 
Review (a Boolean variable), Review (out of 10), 
Total minutes listened, 
Completion (from 0 to 1), 
Support requests (number), 
Last visited minus purchase date (in days).

We exclude customer ID, as it is completely arbitrary. It's more like a name, than a number.
The targets are a Boolean variable (so 0, or 1). 
We are taking a period of 2 years in our inputs, and the next 6 months as targets. 


Download data set from here https://www.kaggle.com/datasets/faressayah/audiobook-app-data
