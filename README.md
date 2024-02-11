# Customer Service Chatbot
This project involved the development of a prototype chatbot for customer service, using Python along with several libraries for natural language processing and machine learning.

The practical component of this project involved the development of a prototype chatbot for customer service, using Python along with several libraries for natural language processing and machine learning. The core of this prototype includes:

1. **Data Preprocessing and Analysis**: Utilizing the Pandas library, the prototype processes a dataset of customer service tweets (customer_support_tweets.csv). It involves cleaning the data by removing duplicates and irrelevant columns and preprocessing the text data using NLTK's stopwords, SnowballStemmer, and WordNetLemmatizer for text normalization and noise reduction.
2. **Recommender System Development**: The prototype employs a RandomForestClassifier from the SciKit-Learn library to train a model on the processed text data. The model aims to predict customer needs and preferences, thus allowing for personalized recommendations.
3. **Chatbot Integration with Twitter**: Using the Tweepy library, the chatbot connects to Twitter, where it listens to tweets related to customer service. It employs TextBlob for sentiment analysis to gauge customer sentiment in tweets and respond accordingly.
4. **Personalized Recommendations**: The chatbot is designed to offer personalized recommendations based on the user's tweet content and sentiment, using the trained recommender system.
5. **Performance Evaluation**: The prototype includes a basic evaluation mechanism that measures response time and accuracy of the recommendations given to sample customer queries.
6. **Working of Chatbot**: Our chatbot springs into action through a robustly engineered function that initiates its operation. Upon activation, it adeptly captures and processes customer queries. Utilizing a comprehensive and diverse recommendation map, the chatbot is equipped to provide insightful and high-quality responses. This intricate system ensures that each customer receives tailored recommendations, reflecting a deep understanding of their needs and queries.

This software prototype demonstrates the application of NLPTM in a real-world scenario, embodying the theoretical principles outlined in the research. The combination of text preprocessing, machine learning for recommendation, and real-time interaction with users via social media showcases a practical implementation of the discussed concepts. 
