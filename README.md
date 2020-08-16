# MovieGenre-Prediction-Apache-Spark-
Implemented a predictive analytics pipeline using Spark to predict the genres associated with a movie.

The movie plots were preprocessed using SparkNLP library built on top of Apache Spark and SparkML.

Tokenization was done with RegexTokenizer and the stop words were removed using Stopwords remover.

Term-document matrix from the plots was inputted to the machine learning model.

Logistic Regression model was created in Spark to predict .

Performance was improved with term frequency-inverse document frequency(tf-idf) based engineering technique.

Custom feature engineering method, Word2Vec was implemented and an increase in performance was noted.

Predictions for the test set were uploaded to the Kaggle website.
