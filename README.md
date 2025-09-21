# Hate Speech Detection using Transformers (Deep Learning)

## 📌 Project Overview  
This project focuses on building a **Hate Speech Detection system** using **transformer-based deep learning models** (BERT, RoBERTa, DistilBERT).  
The goal is to classify tweets as *hate speech* or *non-hate speech* to support safer online communities and reduce harmful content on social media platforms.  

---

## 👥 Team Members  
- **Group Name:** NLP Pioneers  
- **Name:** Duc Duong  
- **Email:** duongduc@grinnell.edu  
- **Country:** United States  
- **College:** Grinnell College  
- **Specialization:** Data Science & NLP  

---

## 📝 Problem Description  
Hate speech is defined as verbal, written, or behavioral communication that attacks or discriminates against individuals or groups based on race, ethnicity, religion, nationality, gender, or identity.  
This project aims to develop a machine learning pipeline that can detect and classify hate speech in tweets automatically.  

---

## 💡 Business Understanding  
Social media companies face challenges in moderating harmful content at scale. Manual moderation is inefficient and costly, while automated hate speech detection can:  
- Improve **content moderation** efficiency  
- Ensure **regulatory compliance**  
- Maintain **brand safety** and protect communities  

---

## 🔄 Project Lifecycle  
1. **Business Understanding & Data Collection** (Week 1–2)  
2. **Exploratory Data Analysis & Preprocessing** (Week 3–4)  
3. **Model Development (Transformers)** (Week 5–6)  
4. **Model Evaluation & Optimization** (Week 7–8)  
5. **Deployment & Documentation** (Week 9–10)  

**Deadline:** 10 weeks  

---

## 📂 Dataset  
- **Source:** [Twitter Hate Speech Dataset (Kaggle)](https://www.kaggle.com/datasets/vkrahul/twitter-hate-speech/data)  
- **Files:** 2 CSV files (train + test)  
- **Size:** ~30 MB  
- **Observations:** ~49,200 tweets (16,130 unique tweets)  
- **Features:** 5 (id, tweet, label, etc.)  

---

## 📊 Data Intake Report  
| Attribute | Value |  
|-----------|--------|  
| Total number of observations | 49,200 (16,130 unique tweets) |  
| Total number of files | 2 (train + test CSV) |  
| Total number of features | 5 (id, tweet, label, etc.) |  
| Base format of the file | CSV |  
| Size of the data | ~30 MB |  

---

## 🚀 Proposed Approach  
- Deduplicate tweets by `id` and `text`  
- Clean and normalize tweets (remove special characters, hashtags, URLs, mentions)  
- Address class imbalance (SMOTE, oversampling, weighted loss)  
- Tokenize text using Hugging Face Transformers (BERT, RoBERTa, DistilBERT)  
- Train models and evaluate using **F1-score, precision, recall**  
- Deploy best-performing model  

---

## 📎 GitHub Repository  
🔗 [Hate Speech Transformers Repo](https://github.com/duongduc388222/twitter_hate_speech)  

---

## ⚙️ Tech Stack  
- **Languages:** Python  
- **Frameworks & Libraries:** PyTorch, TensorFlow, Hugging Face, scikit-learn, Pandas, NumPy  
- **Tools:** Jupyter Notebook, GitHub, Kaggle, Google Colab  
