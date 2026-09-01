# Quora Duplicate Question Detection

NLP classification project to identify whether two questions are **duplicate/similar**.

## 🔄 Workflow

```text
Question Pairs
→ Data Cleaning & EDA
→ Text Preprocessing
→ Feature Engineering
→ TF-IDF & Word Embeddings
→ Similarity Features
→ Model Training
→ Evaluation
```

## ⚙️ Features

- Question length & word counts
- Common/shared words
- Fuzzy matching ratios
- Token & stop-word similarity
- Longest substring similarity
- TF-IDF features
- spaCy word embeddings
- t-SNE visualization 
## 🤖 Models

- SGD Classifier
- XGBoost Classifier
- Probability calibration

## 📊 Evaluation

- Log Loss
- Accuracy
- Confusion Matrix
- Precision / Recall analysis

## 🛠️ Tech Stack

Python • Pandas • NumPy • Scikit-learn • NLTK • spaCy • XGBoost • FuzzyWuzzy • Seaborn • Plotly