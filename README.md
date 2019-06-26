# Amazon-Food-Reviews-Analysis using KNN

#### Performed Exploratory Data Analysis, Data Cleaning, Data Visualization and Text Featurization(BOW,TFIDF,AVG Word2Vec,TF-IDF W2V). 
### Objective:
Given a text review, determine the sentiment of the review whether its positive or negative.

Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

#### About Dataset

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.<br>

Number of reviews: 568,454<br>
Number of users: 256,059<br>
Number of products: 74,258<br>
Timespan: Oct 1999 - Oct 2012<br>
Number of Attributes/Columns in data: 10 

Attribute Information:

1. Id
2. ProductId - unique identifier for the product
3. UserId - unqiue identifier for the user
4. ProfileName
5. HelpfulnessNumerator - number of users who found the review helpful
6. HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
7. Score - rating between 1 and 5
8. Time - timestamp for the review
9. Summary - brief summary of the review
10. Text - text of the review
<hr>
 KNN
1. Applied K-Nearest Neighbour on Different Featurization & Data Visualization. BOW(uni-gram), tfidf, Avg-Word2Vec and tf-idf-Word2Vec 
2. By using both brute & kd-tree implementation of KNN 
3. Evaluated the test data on various performance metrics like accuracy also plotted Confusion matrix 
using seaborne

###### Conclusions:
1.  KNN is a very slow Algorithm takes very long time to train.
2.  Best Accuracy  is achieved by Avg Word2Vec Featurization.
3.  Both kd-tree and brute algorithms of KNN gives comparatively similar results.
<hr>
