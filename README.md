# 📊 Sentiment Analysis on Social Media Data

## 📌 Project Overview
This project analyzes and visualizes sentiment patterns in social media data to understand public opinion and attitudes toward different topics or brands.

---

## 🎯 Objective
- Perform sentiment analysis on textual data
- Classify text into Positive, Negative, and Neutral sentiments
- Visualize sentiment distribution using charts

---

## 📂 Dataset
Dataset used from:
https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%204

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- WordCloud

---

## ⚙️ Project Workflow

### 1. Data Collection
- Load dataset containing social media text and sentiment labels

### 2. Data Preprocessing
- Convert text to lowercase
- Remove special characters and links
- Remove stopwords using NLTK

### 3. Feature Extraction
- Convert text data into numerical format using CountVectorizer

### 4. Model Building
- Train a Naive Bayes model for sentiment classification

### 5. Evaluation
- Evaluate model accuracy

### 6. Visualization
- Bar Chart (Sentiment Distribution)
- Pie Chart (Sentiment Proportion)
- WordCloud (Most frequent words)

---

## 📊 Results

- Successfully classified sentiments into:
  - Positive
  - Negative
  - Neutral

- Visualizations provided clear insights into public opinion trends.

---

## 📸 Sample Outputs

### 📌 Pie Chart
Shows percentage distribution of sentiments.

### 📌 Bar Graph
Displays count of each sentiment category.

### 📌 WordCloud
Highlights frequently used words in dataset.

---

## ▶️ How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
