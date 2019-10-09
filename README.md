# Sentiment-Analysis

**Sentiment Analysis on Amazon Reviews Data**

I have downloaded the amazon review dataset from http://jmcauley.ucsd.edu/data/amazon/. It contains various reviews on many product categories such as books , Electronics , Toys etc.
I have chosen books as my primary dataset that i will be working on. It contains reviews from 1996 to 2014. The file is too large , Hence i have included a pre processing file that will only select reviews from the year 2014.
AFter my pre processing i have included a file named books_smalls_10000.json in the folder data that has reviews of 10000 books from the year 2014. 


### Model 
For this classification task i have used SVM(Support Vectors Machine) Classifier which seems to be the best option for this task. The vectorization i have used first was **Bag of Words** which gave me a decent f1 score , but on further testing i found **TFIDF Vectorizer** to be more apt as it gave me a better F1 score of 0.80582524,  0.80952381 for **Positive** & **Negative** Sentiments.
Although not a bad f1 score the model can be improved firther by removal of punctuation and different vectorization methods 





