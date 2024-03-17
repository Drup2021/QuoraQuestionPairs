Question Similarity Analysis

•Utilized a dataset consisting of question pairs from Quora, comprising thousands of question pairs labeled as similar or dissimilar.
•Preprocessed the dataset by tokenizing text and removing stop words.
•Engineered a total of 22 features, including word embeddings, syntactic features, and fuzzy features extracted using the FuzzyWuzzy library.
•Employed t-SNE (t-distributed Stochastic Neighbor Embedding) technique for dimensionality reduction to visualize high-dimensional feature representations of question pairs in lower-dimensional space.
•Implemented XGBoost Classifier and RandomForest Classifier to predict the similarity between question pairs.
•Evaluated the performance of the classifiers using metrics such as accuracy, precision, recall, and F1 score.



Get the dataset : https://www.kaggle.com/competitions/quora-question-pairs
