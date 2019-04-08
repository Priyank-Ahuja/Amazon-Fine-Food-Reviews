# Case Study : Amazon Fine Food Reviews

Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews 

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

Number of reviews : 568,454

Number of products : 74,258

Timespan : Oct 1999 - Oct 2012

Number of Attributes/Columns in data : 10

### Attribute Information:

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

### Objective:

Given a review, determine whether the review is positive (rating of 4 or 5) or negative (rating of 1 or 2).

## WORK FLOW
1. Data Cleaning : Deduplication
2. Text Preprocessing
3. Converted Text to Vectors using :
   a. Bag of Words
   b. TF-IDF
   c. Avg-W2V
   d. TF-IDF W2V
4. Applied t-SNE on all vectorization techniques
5. Applied KNN after all vectorization techniques to find the best model
6. Applied Naive Bayes after all vectorization techniques to find the best model
7. Applied Logistic Regression after all vectorization techniques to find the best model
8. Applied SVM after all vectorization techniques to find the best model
9. Applied Decision Tress after all vectorization techniques to find the best model
