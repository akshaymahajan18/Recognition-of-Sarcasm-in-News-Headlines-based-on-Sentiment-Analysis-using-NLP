# Recognition of Sarcasm in News Headlines based on Sentiment Analysis using NLP

# Motivation : 
In the last decade there has been a boom in opinionated textual data both in online resources like social media and in dissemination of information. Sentiment Analysis is used to analyse such opinionated texts which will provide us insights about the emotion or thought process of the author. One of the many challenges faced by sentiment analysis is sarcasm or irony detection. Sarcasm is a complex act of communication that allows speakers the opportunity to express sentiment rich opinions in an implicit way.Although sarcasm is widely used, it is challenging not only for computers but also for humans to detect promptly. This makes the detection of sarcasm a crucial task. Automated sarcasm detection can be seen as a text classification problem. Text data is one of the simplest forms of data. Machine learning algorithms only process numerical data. So the need for feature extraction arises. Here comes in the use of feature extraction using Natural Language Processing (NLP). NLP is a branch of computer science that involves the analysis of human language in speech and text. NLP acts as a translator of sorts between humans and machines. Humans can speak or write normally and NLP translates the language into a form that a machine or algorithm can understand. 

# Objective : 
The main objective for this project is to delve deep into the understanding of text classification methods for sarcasm detection (& sentiment analysis) and understanding and implementing the feature extraction methods of NLP. It is important to extract useful information from any forms of data, especially unstructured forms like text data. Feature extraction and the proper representation of text for classification purposes is an important factor that affects the accuracy of classification. In this project we plan to explore the use of the Count Vectorizer, TF-IDF and Word2Vec on different supervised learning algorithms and the accuracy of these models will be measured and compared. 

# Data description : 
The News headline dataset consists of about 28000 data points.
1. is_sarcastic: 1 if the record is sarcastic, otherwise 0 
2. headline: the headline of the news article
3. article_link: link to the original news article.   
This News Headlines dataset for Sarcasm Detection  is collected from two news websites TheOnion and HuffPost.
The link for the dataset is provided below:  https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection

# Data Pre-processing :
1. Tokenization
2. Stopwords
3. punctuation and noisy texts removal
4. HTML tags removal
5. Stemming and lemmatization

# Exploratory Data Analysis : 
1. Count plot of the is_sarcastic feature.
![image](https://github.com/user-attachments/assets/85278908-4355-41a0-91d8-7d93341f10d1)

2. WORDCLOUD FOR TEXT THAT IS NOT SARCASTIC (LABEL - 0)
![image](https://github.com/user-attachments/assets/58671608-2450-42f7-8f06-18ae3f15647b)

3. WORDCLOUD FOR TEXT THAT IS SARCASTIC (LABEL - 1)
![image](https://github.com/user-attachments/assets/1fbf55ad-efd6-4c63-bbaa-a7cc86cc6968)
4. Plotting the number of characters in text
![image](https://github.com/user-attachments/assets/e50078f4-41a0-4493-b89e-c5fd2b9defcc)
5. Plotting the number of words in text
![image](https://github.com/user-attachments/assets/ea4007c6-c3e9-420e-b5db-6624d280f70c)
6. Plotting the average number of words in text
![image](https://github.com/user-attachments/assets/45b27016-ca18-4556-a139-f99609c4acb5)


# Feature Extraction : 
1. Term Frequency – Inverse Document Frequency (TF-IDF).
2. Word embedding - Word2Vec


# Classification Algorithms : 
1)	support vector classifier
2)	Gaussian Naive Bayes
3)	Logistic Linear Regression
4)	Random Forest Classifier
5)	LSTM (Long Short Term Memory)

# Tools : 
scikit-learn, tensorflow, keras, NLTK, Seaborn, Matplotlib

 











