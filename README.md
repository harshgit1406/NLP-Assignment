# 🧠 Natural Language Processing Assignment – SEC-E

## 📋 Assignment Overview
This project is a part of the **NLP (Natural Language Processing) Assignment** under the **SEC-E Course**.  
It demonstrates fundamental and applied NLP concepts using **Python, NLTK, and Machine Learning models**.  

The notebook includes two major tasks:
1. **Task 1:** Complete NLP Pipeline (Tokenization → Stopword Removal → Stemming → Lemmatization)
2. **Task 2:** Sentiment Analysis using NLP + ML on Movie Review Data

---

## 👨‍💻 Student Information

| Field | Details |
|-------|----------|
| **Name** | Harsh Raj |
| **Roll No.** | 2301730286 |
| **Course** | B.Tech CSE AI ML SEC-E |
| **Semester** | 5 |


---

## 📘 Task 1 – NLP Pipeline

### 🔍 Objective:
To perform basic text preprocessing operations on a custom paragraph and observe transformations at each stage.

### ⚙️ Steps Performed:
1. **Tokenization** – Breaking text into individual words.  
2. **Stopword Removal** – Eliminating common non-informative words.  
3. **Stemming** – Reducing words to their root forms using Porter Stemmer.  
4. **Lemmatization** – Converting words to their dictionary base form.

### 🧠 Example Output:
```
Original: "Artificial Intelligence and Machine Learning are transforming the world..."
After Tokenization: ['Artificial', 'Intelligence', 'and', 'Machine', ...]
After Stopword Removal: ['Artificial', 'Intelligence', 'Machine', 'Learning', 'transforming', 'world', ...]
After Stemming: ['artifici', 'intellig', 'machin', 'learn', 'transform', 'world', ...]
After Lemmatization: ['Artificial', 'Intelligence', 'Machine', 'Learning', 'transform', 'world', ...]
```
## 🤖 Task 2 – Sentiment Analysis

### 🎯 Objective:
To build and evaluate a sentiment analysis model using NLP preprocessing and machine learning.

### 📊 Dataset:
Used the **Movie Reviews dataset** from the `nltk.corpus` library.  
Contains **2000 labeled reviews** (1000 positive, 1000 negative).

### ⚙️ Workflow:
1. Import and preprocess the dataset  
2. Extract features using most frequent words  
3. Train a **Naive Bayes Classifier**  
4. Evaluate model accuracy and analyze key sentiment features  
5. Test the model with custom user text  

### 📈 Example Result:
```
Model Accuracy: ~80%
Most Informative Features:

contains(outstanding) => positive

contains(worst) => negative

contains(excellent) => positive
```
## 🧰 Technologies Used

| Tool / Library | Purpose |
|----------------|----------|
| **Python 3.x** | Programming Language |
| **NLTK** | NLP Processing & Datasets |
| **Scikit-learn** | Machine Learning utilities |
| **Jupyter Notebook** | Development Environment |
