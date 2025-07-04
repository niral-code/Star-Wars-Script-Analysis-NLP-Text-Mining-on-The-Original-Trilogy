# 🛰️ Star Wars Script Analysis: NLP & Text Mining on The Original Trilogy

Explore natural language processing and sentiment analysis on the legendary *Star Wars* Original Trilogy scripts. This project uncovers character dialogue patterns, key vocabulary, sentiment trends, and visual insights using Python and NLP techniques.

---

## 📌 Project Summary

This project applies **text mining** and **natural language processing** techniques on the scripts of *Episodes IV–VI* (A New Hope, The Empire Strikes Back, and Return of the Jedi) to analyze:

- Dialogue frequency per character
- Most used words in the trilogy
- Word clouds for Darth Vader and Yoda
- TF-IDF analysis to highlight relevant terms
- Sentiment analysis to detect tone differences between Jedi and Sith

---

## 🧰 Tech Stack

| Tool/Library | Purpose |
|--------------|---------|
| `Python` | Core programming language |
| `Pandas` | Data manipulation |
| `NLTK` | Tokenization, stopword removal, lemmatization |
| `Matplotlib`, `Seaborn`, `Plotly` | Visualizations |
| `WordCloud` | Visual word clouds |
| `Scikit-learn` | TF-IDF modeling |
| `VADER Sentiment` | Sentiment analysis |

---

## 📂 Dataset

- Collection of dialogue scripts from *Star Wars: Episodes IV–VI*
- Each script includes character names and their dialogue lines
- Mask images provided for creating custom-shaped word clouds

---

## 📈 Key Features

### 🎭 Character Dialogue Analysis
- Found the characters with the most dialogue in each episode
- Visualized dialogue distribution using bar charts

### 🧹 Text Preprocessing
- Lowercased text, removed stopwords, lemmatized tokens
- Added cleaned scripts as a new column for analysis

### 📊 Word Frequency
- Frequency distribution plotted before and after preprocessing
- Highlighted commonly used words across the trilogy

### ☁️ Word Clouds
- Generated word clouds for:
  - **Darth Vader** (using a helmet mask)
  - **Yoda** (using a custom mask)
- Showcased each character’s most spoken words

### 🧠 TF-IDF Analysis
- Identified contextually important words using TF-IDF Vectorizer
- Revealed unique dialogue features by character and scene

### 💬 Sentiment Analysis
- Applied **VADER** sentiment analyzer
- Compared positive/neutral/negative tones in Jedi vs. Sith dialogues
- Found Dark Side characters had higher negative sentiment
