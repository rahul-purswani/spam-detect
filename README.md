# Spam Detect - Bernoulli Classifier from Scratch
In this project, I developed a spam detection system that classifies SMS messages as either spam or ham (non-spam) using a Bernoulli Naive Bayes model. The project involves data preprocessing, feature extraction, and model implementation from scratch.
Key Features:
    Dataset: Utilized a publicly available SMS spam collection dataset, which includes labeled messages categorized as spam or ham.
    Data Cleaning: Performed data cleaning steps such as removing punctuation, converting text to lowercase, and removing stopwords to prepare the dataset for model training.
    Feature Extraction: Employed techniques to transform the cleaned text data into a suitable format for the Bernoulli Naive Bayes model. This included vectorizing the text data and generating a vocabulary - binary feature matrix representing the presence or absence of specific words.
    Model Implementation: Implemented the Bernoulli Naive Bayes algorithm from scratch. This involved calculating the prior probabilities of spam and ham messages and the likelihood probabilities of words given each class. Trained the model on processed dataset and evaluated its performance based on accuracy.
