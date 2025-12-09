# 🧠 Sentence Pair Relationship Classification using NLP & Machine Learning

This project predicts the relationship between two sentences (e.g., similar, contradiction, unrelated) using a trained NLP model. It takes a pair of input sentences and outputs the relationship between them.

## 📌 Project Overview

Sentence-pair relationship classification is an NLP task where a model learns how two sentences relate to each other.
This project uses a custom-trained ML/NLP model to identify the relationship between unseen sentence pairs.

### 1️⃣ Data Preprocessing

Cleaned and normalized sentence pairs.

Removed unwanted characters and lowercased text.

Converted raw text into model-ready format.

### 2️⃣ Feature Engineering (Text Representation)

Used NLP word embeddings such as Word2Vec / TF-IDF / BERT embeddings.

Combined both sentence vectors to form pair features (concat, subtract, cosine similarity).

Created final input features for model training.

### 3️⃣ Model Building

Trained an NLP classification model (Logistic Regression / SVM / Random Forest / BERT).

Used sentence pair features to learn relational patterns.

Tuned hyperparameters for better accuracy.

### 4️⃣ Model Evaluation

Measured accuracy, F1-score, precision, and recall.

Checked confusion matrix to understand relation classification performance.

Tested the model on unseen sentence pairs.

### 5️⃣ Final Output

The model predicts the relation between two input sentences.

Output includes: Similar / Contradictory / Unrelated / Custom relation labels.

Can be integrated into websites, chatbots, or NLP applications.

### 🚀 Use Cases

Semantic sentence matching

Duplicate question detection

Chatbot intent understanding

Plagiarism and similarity checking

Information retrieval and search systems
