# MindScope – Depression Detection Engine  

An NLP and traditional ML-powered system for detecting depression signals in social media posts through hybrid feature engineering and transformer-assisted weak labeling.

---

## 🧠 Project Overview
MindScope analyzes social media text to classify posts as **Depression** or **Normal**, going beyond simple keyword spotting by incorporating psychological writing patterns and contextual semantic features.

---

## ⚙️ Key Features
- **Dataset collection from depression-related communities** using :contentReference[oaicite:0]{index=0} API.  
- **Text cleaning, tokenization & linguistic feature extraction** (pronoun frequency, readability, emotional tone, self-focus markers).  
- **Hybrid feature engineering** combining TF-IDF vectors + psychological signals.  
- **Model training and benchmarking** using classical ML classifiers from :contentReference[oaicite:1]{index=1}.  
- **Weak labeling support** via pre-trained emotion and sentiment transformer models.

---

## 📊 Results Snapshot
| Model | Accuracy | AUC-ROC |
|-------|----------|---------|
| Logistic Regression | 77.26% | 85.98 |
| SVM | 79.16% | 86.32 |
| **Random Forest (Best)** | **81.58%** | **88.97** |

---

## 🛠️ Tech Stack
### **Programming & Libraries**
- **Language:** Python  
- **API Scraping:** Reddit API (via PRAW)  
- **ML Models:** Logistic Regression, SVM, Random Forest using :contentReference[oaicite:2]{index=2}  
- **Linguistic Features:** spaCy, TextStat  
- **Visualization:** Matplotlib, WordCloud  

### **Pre-trained Transformers for Labeling**
- Emotion Classification: DistilRoBERTa-based models  
- Sentiment Classification: DistilBERT-based models  

---

## 🚀 Highlights (Implementation)
- Developed an NLP-based depression detection pipeline on :contentReference[oaicite:3]{index=3} posts.  
- Built hybrid TF-IDF + psychological feature architecture to reduce keyword bias.  
- Compared ML classifiers using :contentReference[oaicite:4]{index=4} achieving 81.6% accuracy & 88.9 AUC.  
- Added transformer-assisted weak labeling to handle noisy signals and ambiguous expression.

---
