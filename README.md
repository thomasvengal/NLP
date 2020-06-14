# NLP
Natural Language Processing

Problem Statement
===================
 Dataset: https://www.kaggle.com/c/yelp-recsys-2013/data
(https://www.kaggle.com/c/yelp-recsys-2013/data)
Description of Data: Each observation in this dataset is a review of a particular business by a
particular user. The "stars" column is the number of stars (1 through 5) assigned by the reviewer to
the business. (Higher stars is better.) In other words, it is the rating of the business by the person who
wrote the review.
1. Read the yelp.csv file and set it as a Dataframe called yelp. Check the head, info, and describe
methods on yelp (4 Marks)
2. Remove punctuations and stopwords from the text in ‘text’ column 
3. Create two objects X and y. X will be the 'text' column of yelp dataframe and y will be the 'stars'
column of yelp. create a CountVectorizer object and split the data into training and testing sets.
Train a MultinomialNB model and Display the confusion Matrix 
4. Display the HMM POS tagging on the first 4 rows of ‘text’ 
5. Parse the first 4 rows of ‘text’ using Viterbi Parser ( [Use toy_pcfg1 and toy_pcfg2 to get the probabilistic context free grammars; use the PCFG suitable for each sentence]
