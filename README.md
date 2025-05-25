# Spam- Mail-Prediction  

Spam Mail Prediction is a machine learning project that classifies email or SMS messages as spam (unwanted messages) or ham (legitimate messages). By using natural language processing (NLP) techniques and supervised learning algorithms, the system learns to identify patterns in text that are commonly associated with spam content.




## ✨Importing Libraries and Dataset 

## Here What We Are Using 

- Pandas – To load the Dataframe
- Matplotlib – To visualize the data features i.e. barplot
- Scikit-Learn – Model Selection,Feature Extraction,Classification models.
- re – for regular expression operation (text cleaning).

 ## ✨ Key Features of Spam Mail Prediction 
## Text Classification:

- Automatically classifies messages as spam or ham using supervised machine learning models.

## Text Preprocessing:

- Efficient preprocessing pipeline including lowercasing, punctuation removal, stopword filtering, and stemming.



## Model Evalution:

Provides detailed performance metrics like

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
## 🚀 Getting Started
 ## Data Collection:
- The project uses the SMS Spam Collection Dataset .
- It contains over 5,500 SMS messages, each labeled as either "spam" or "ham" (not spam).

## Data Cleaning & Preprocessing:
To prepare the text data for machine learning, we apply:
- Lowercasing.
- Removing punctuation and special characters.
- Tokenization.
- Removing stopwords (common words like “the”, “is”, etc.).

## Feature Extraction:
#Text data is converted into numerical vectors using. 🚀

- Bag of Words (BoW).
- TF-IDF (Term Frequency–Inverse Document Frequency).
- These techniques convert each message into a format that can be understood by machine learning algorithms.

## Prediction and Output:
#Once trained, the model can predict whether new messages are spam or not

Input: "Congratulations! You've won a free iPhone. Click here to claim now!"
Output: SPAM

Input: "Can we reschedule our meeting to tomorrow?"
Output: HAM
