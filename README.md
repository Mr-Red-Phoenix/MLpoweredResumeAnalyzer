# 🤖 Resume Analyzer using Machine Learning

This project is a **Machine Learning powered Resume Analyzer** that classifies resumes into different categories/domains such as Data Science, HR, Web Development, etc. It uses natural language processing (NLP) techniques for text cleaning, feature extraction using TF-IDF, and classification with machine learning algorithms.

---

## 📁 Project Structure

- `resumeanalyzer.ipynb`: Main Jupyter notebook for data analysis, model training, and evaluation.
- `data/`: Folder containing resume dataset (CSV format).
- `wordcloud.png`: Visual representation of most frequent terms (if generated).
- `README.md`: Project documentation.

---

## 🚀 Features

- Clean and preprocess resume text using NLP.
- Visualize data using bar and pie charts.
- Extract key features using **TF-IDF**.
- Train classification model (e.g., Logistic Regression).
- Evaluate model performance with accuracy metrics.
- Generate word clouds from resume content.

---

## 🛠️ Tech Stack

- Python 🐍
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- NLTK (Natural Language Toolkit)
- Scikit-learn
- WordCloud

---

## 📊 Exploratory Data Analysis

- Bar plots for category count.
- Pie charts for domain distribution.
- WordCloud for keyword analysis.

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/resume-analyzer.git
cd resume-analyzer

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt
