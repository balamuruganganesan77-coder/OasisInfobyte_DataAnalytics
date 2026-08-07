# Task 4 - Sentiment Analysis

## 📌 Objective

Build a machine learning model to classify text data into three sentiment categories:

- Positive
- Negative
- Neutral

The project uses the **FinancialPhraseBank** dataset containing financial news headlines and their corresponding sentiment labels.

---

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- TF-IDF Vectorizer
- Naive Bayes
- Logistic Regression

---

## 📊 Dataset

**Dataset:** FinancialPhraseBank

**File:** `all-data.csv`

The dataset contains financial news headlines classified into Positive, Negative, and Neutral sentiment categories.

---

## 🔄 Project Workflow

1. Load the sentiment dataset
2. Inspect the dataset structure
3. Check sentiment class distribution
4. Clean and preprocess text data
5. Convert text into numerical features using TF-IDF
6. Split the dataset into training and testing sets
7. Train machine learning classification models
8. Evaluate model performance
9. Generate confusion matrices
10. Analyze misclassified examples
11. Compare model performance
12. Identify the best-performing model

---

## 🧹 Text Preprocessing

The following preprocessing techniques are applied:

- Convert text to lowercase
- Remove punctuation
- Remove unnecessary characters
- Tokenization
- Stopword removal
- Text normalization

---

## 🔢 Feature Extraction

### TF-IDF Vectorization

TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert text data into numerical features that machine learning algorithms can understand.

It gives higher importance to words that are useful for distinguishing between different sentiment classes.

---

## 🤖 Machine Learning Models

Two classification models are implemented:

### 1. Multinomial Naive Bayes

A probabilistic machine learning algorithm commonly used for text classification tasks.

### 2. Logistic Regression

A classification algorithm used to predict the sentiment category based on the TF-IDF features.

---

## 📈 Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The performance of both models is compared to identify the better classifier.

---

## 📊 Visualization

The project includes visualizations such as:

- Sentiment distribution
- Confusion matrix
- Model performance comparison
- WordCloud for sentiment classes

---

## 🔍 Error Analysis

Five misclassified examples are analyzed to understand why the model predicted the wrong sentiment.

Possible reasons include:

- Ambiguous financial statements
- Context
