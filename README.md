# NLP Projects Portfolio

A collection of Natural Language Processing (NLP) and Machine Learning projects covering sentiment analysis, text classification, and text preprocessing. Each project demonstrates practical applications of NLP techniques for real-world problems.

---

## 📁 Projects

### 1. Amazon Product Review Sentiment Analysis

**Description:**  
Built a sentiment analysis model to classify Amazon product reviews as **Positive**, **Neutral**, or **Negative** using NLP and Machine Learning.

**Key Features:**
- Text preprocessing with punctuation removal, stopword removal, and lemmatization
- EDA with WordClouds, sentiment distribution plots, and bigram analysis
- Feature extraction using TF-IDF vectorization
- Trained models: Random Forest, Naive Bayes, and Gradient Boosting
- Prediction function for classifying new customer reviews

**Skills Used:**  
`Python` · `Pandas` · `NumPy` · `NLTK` · `TextBlob` · `Scikit-learn` · `TF-IDF` · `CountVectorizer` · `Random Forest` · `Naive Bayes` · `Gradient Boosting` · `NLP` · `WordCloud` · `Seaborn` · `Matplotlib` · `EDA`

---

### 2. IMDB Movie Review Sentiment Analysis

**Description:**  
Developed a sentiment analysis model to classify IMDB movie reviews as **Positive** or **Negative** using NLP techniques.

**Key Features:**
- Text preprocessing: tokenization, stopword removal, lowercasing, and lemmatization
- Feature extraction using TF-IDF Vectorization
- WordCloud visualization of frequently occurring words
- Multinomial Naive Bayes classifier with classification metrics
- Real-time sentiment prediction pipeline for new reviews

**Skills Used:**  
`Python` · `Pandas` · `NumPy` · `NLTK` · `TF-IDF Vectorization` · `NLP` · `Scikit-learn` · `Multinomial Naive Bayes` · `WordCloud` · `Matplotlib` · `Machine Learning` · `Text Classification` · `Model Evaluation`

---

### 3. SMS Spam Detection using TF-IDF and Naive Bayes

**Description:**  
Created an SMS spam detection model to classify messages as **Spam** or **Ham** using NLP and machine learning.

**Key Features:**
- Text preprocessing: tokenization, lowercasing, removal of non-alphabetic words, stopword removal
- Feature extraction using TF-IDF Vectorization
- Multinomial Naive Bayes classifier
- Model evaluation using Accuracy Score and Classification Report

**Skills Used:**  
`Python` · `Pandas` · `NLTK` · `NLP` · `Text Preprocessing` · `TF-IDF Vectorization` · `Scikit-learn` · `Multinomial Naive Bayes` · `Machine Learning` · `Model Evaluation`

---

### 4. Text Preprocessing and Feature Extraction using NLP

**Description:**  
Built an NLP preprocessing pipeline for cleaning and transforming text data for machine learning applications.

**Key Features:**
- Preprocessing pipeline: tokenization, lowercasing, punctuation removal, stopword removal, stemming, and lemmatization
- WordCloud visualization of frequent meaningful words
- Feature extraction using CountVectorizer (Bag of Words)
- TF-IDF Vectorization for word importance scoring
- Vocabulary creation, word frequencies, and IDF values exploration

**Skills Used:**  
`Python` · `NLTK` · `Text Preprocessing` · `Tokenization` · `Stopword Removal` · `Stemming` · `Lemmatization` · `WordCloud` · `CountVectorizer` · `Bag of Words` · `TF-IDF` · `Scikit-learn` · `Matplotlib`

---

### 5. Fake News Detection using LSTM and GloVe Word Embeddings

**Description:**  
Developed a deep learning model for fake news detection using LSTM with pre-trained GloVe word embeddings.

**Key Features:**
- Text preprocessing: HTML removal, URL removal, stopword removal, punctuation cleaning, tokenization, and sequence padding
- Stacked LSTM architecture with Embedding layer, Dropout, Dense layers
- Pre-trained Twitter GloVe (100d) embeddings
- ReduceLROnPlateau callback for improved training and overfitting reduction
- Model evaluation: accuracy, precision, recall, F1-score, confusion matrix, training/validation curves
- WordCloud visualization and saved model for future inference

**Skills Used:**  
`Python` · `Pandas` · `NumPy` · `TensorFlow` · `Keras` · `LSTM` · `GloVe Embeddings` · `NLP` · `NLTK` · `BeautifulSoup` · `Regex` · `Tokenization` · `Sequence Padding` · `Text Preprocessing` · `WordCloud` · `Scikit-learn` · `Matplotlib` · `Seaborn` · `Model Evaluation` · `Deep Learning`

---

## 🛠️ Tech Stack Overview

| Category | Technologies |
|----------|--------------|
| Languages | Python |
| Data Processing | Pandas, NumPy |
| NLP Libraries | NLTK, TextBlob, BeautifulSoup, Regex |
| Machine Learning | Scikit-learn, Multinomial Naive Bayes, Random Forest, Gradient Boosting |
| Deep Learning | TensorFlow, Keras, LSTM, GloVe Embeddings |
| Feature Extraction | TF-IDF, CountVectorizer, Bag of Words |
| Visualization | Matplotlib, Seaborn, WordCloud |
| Text Preprocessing | Tokenization, Stemming, Lemmatization, Stopword Removal |
| Model Evaluation | Accuracy, Precision, Recall, F1-Score, Confusion Matrix |

---

## 📊 Key Learnings

- **Text Preprocessing:** Clean and normalize raw text data for analysis
- **Feature Engineering:** Convert text to numerical features using TF-IDF and Bag of Words
- **Model Selection:** Compare classical ML models (Naive Bayes, Random Forest) with deep learning (LSTM)
- **Word Embeddings:** Leverage pre-trained embeddings (GloVe) for better semantic representation
- **Evaluation:** Use multiple metrics to assess model performance comprehensively
- **Pipeline Development:** Build end-to-end NLP pipelines from data preprocessing to prediction
