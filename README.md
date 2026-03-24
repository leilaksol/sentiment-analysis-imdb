# 🎬 IMDB Sentiment Analysis: Machine Learning Model Comparison

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF.svg)](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
[![Live Demo](https://img.shields.io/badge/Live-Portfolio-2563eb.svg)](https://leilaksol.github.io/sentiment-analysis-imdb/)

> A comprehensive comparison of 4 machine learning algorithms for sentiment classification on the IMDB movie reviews dataset.

**🔗 [View Live Portfolio](https://leilaksol.github.io/sentiment-analysis-imdb/)**


---
## 📋 Overview

This project compares **four classical machine learning algorithms** for binary sentiment classification:

- ✅ **Logistic Regression**
- ✅ **Naive Bayes**
- ✅ **Random Forest**
- ✅ **Support Vector Machine (SVM)**

**Dataset:** 50,000 movie reviews from IMDB, evenly split between positive and negative sentiment.

**Goal:** Determine which algorithm provides the best balance of accuracy, speed, and interpretability.

---


## 🛠️ Technologies Used

- **Python 3.9+**
- **scikit-learn** - Machine learning models
- **pandas** - Data manipulation
- **matplotlib & seaborn** - Static visualizations
- **plotly** - Interactive charts
- **TF-IDF** - Text feature extraction
- **Jupyter Notebook** - Experimentation

---

## 📁 Project Structure
```
sentiment-analysis-imdb/
├── visualizations/
│   ├── word_clouds/              # Sentiment word clouds
│   ├── confusion_matrices/       # Model confusion matrices
│   ├── metrics/                  # Performance comparison charts
│   └── interactive_metrics_chart.html
├── project_v02.ipynb             # Main Jupyter notebook
├── index.html                    # Portfolio webpage
├── banner_full.png               # Project banner
├── README.md                     # This file
└── LICENSE                       # MIT License
```

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/leilaksol/sentiment-analysis-imdb.git
cd sentiment-analysis-imdb
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```


### 3. Download the Dataset

**Option A: Using KaggleHub (Automated)**
```python
import kagglehub
file_path = kagglehub.dataset_download("lakshmi25npathi/imdb-dataset-of-50k-movie-reviews")
```

**Option B: Manual Download**
1. Visit [Kaggle IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
2. Download `IMDB Dataset.csv`
3. Place in your working directory

### 4. Run the Notebook
```bash
jupyter notebook project_v02.ipynb
```

---

## 📚 Methodology

### 1. Data Preprocessing
- Removed HTML tags, punctuation, and special characters
- Converted text to lowercase
- Tokenized reviews into words

### 2. Feature Extraction
- **TF-IDF Vectorization** (max 1000 features, bigrams)
- Captures word importance across the dataset
- Handles sparse, high-dimensional text data

### 3. Model Training
Trained 4 algorithms with default parameters:
- Logistic Regression (max_iter=1000)
- Multinomial Naive Bayes
- Random Forest (n_estimators=100)
- Linear SVM (max_iter=1000)

### 4. Evaluation
Comprehensive metrics for balanced assessment:
- **Accuracy** - Overall correctness
- **Precision** - Reliability of positive predictions
- **Recall** - Capture rate of positive reviews
- **F1-Score** - Harmonic mean of precision & recall
- **ROC-AUC** - Threshold-independent discrimination

---



## 🔮 Future Work

- Deep learning models (LSTM, BERT)
- Word embeddings (Word2Vec, GloVe)
- Hyperparameter optimization
- REST API deployment
- Multi-class sentiment analysis

---

## 👩‍💻 Author

**Leila Soltani** - Data Science & ML Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/leilak-soltan/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/leilaksol)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-2563eb)](https://leilaksol.github.io/)

---

## 📄 License

MIT License - see [LICENSE](LICENSE) file

---

## 🙏 Acknowledgments

- Dataset: [Kaggle IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- Tools: scikit-learn, pandas, matplotlib, seaborn, plotly

---

<div align="center">

⭐ **Star this project if you found it helpful!** ⭐

**[View Live Portfolio](https://leilaksol.github.io/sentiment-analysis-imdb/)**

</div>
