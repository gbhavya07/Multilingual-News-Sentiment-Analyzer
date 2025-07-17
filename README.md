# 📰 Multilingual Sentiment Analyzer for Local News Articles

An end-to-end web application built to analyze sentiment in local news articles across different languages. Developed during a Machine Learning Hackathon, this tool empowers users and organizations to better understand public sentiment regarding community events, policies, and social trends.

---

## 🚀 Features

- 🔍 **Sentiment Analysis** using VADER on user reviews
- 🧠 **Category Prediction** using Logistic Regression trained on article summaries
- 🌐 **Multilingual Support** using Google Translate API
- 💾 **IndexDB Storage** for local data caching
- 🖥️ **Flask Web App** with interactive input form and real-time sentiment prediction

---

## 🧠 Model Overview

| Task                   | Model Used            |
|------------------------|-----------------------|
| Sentiment Analysis     | VADER (Lexicon-based) |
| Article Categorization | Logistic Regression   |

**Target Classes:**
- Sentiment: Positive, Negative, Neutral
- Categories: Social, Community, Policy, Environmental, etc.

---

## 🗂 Dataset Description

Each record includes:
- `Type`: Category (e.g., Social, Policy)
- `Article`: Headline of the article
- `Link`: URL source
- `Summary`: Key points
- `Review`: Feedback or comment
- `Label`: Sentiment (Positive, Negative, Neutral)

---

## 🌐 Multilingual Support

- Users can input article summaries or reviews in **any language**
- Google Translate API auto-translates to English before processing
- Enhances accessibility and inclusivity across regions

---

## 📊 Hackathon Insights

- 📈 Positive & Negative sentiments equally represented (36.7%)
- 🌍 Translation to Kannada boosted local user engagement
- 🔥 Emotionally charged topics led to stronger sentiment polarization

---

## 💡 Use Cases

- Public sentiment tracking on community issues
- Social media/news feedback monitoring
- Cross-language opinion mining for policy makers

---

## ⚙️ Installation & Run

```bash
git clone https://github.com/yourusername/Multilingual-News-Sentiment-Analyzer.git
cd Multilingual-News-Sentiment-Analyzer
pip install -r requirements.txt
python app.py
