# 🎬 Movie Recommendation & Revenue Prediction System

A machine learning project combining content-based movie recommendations with a revenue prediction model and built using Python, Scikit-learn, and exploratory data analysis across a dataset of thousands of films.

---

## 📌 Overview

This project has two parts:

**1. Recommendation Engine** — given a movie title, the system suggests similar films based on content features (genres, cast, crew, keywords) using TF-IDF vectorization and cosine similarity.

**2. Revenue Prediction Model** — predicts a movie's box office revenue based on budget, popularity, runtime, and other features using Linear Regression and Random Forest.

---

## 🤖 Models & Techniques

| Component | Approach |
|---|---|
| Recommendation | TF-IDF Vectorization + Cosine Similarity |
| Revenue Prediction | Linear Regression, Random Forest |
| Data Processing | Missing value handling, feature extraction, encoding |
| EDA | WordClouds, Budget vs. Revenue scatter plots, genre distributions |

---

## ✨ Features

🎯 Content-based filtering, recommendations driven by movie metadata, not user history

💰 Revenue prediction from pre-release features (budget, cast, genre)

🔍 Exploratory analysis of trends across genres, budgets, and popularity scores

🧹 Full data cleaning pipeline handling nulls, inconsistent formats, and nested JSON fields

---

## 🛠️ Tech Stack

| Tool | Usage |
|---|---|
| Python | Core language |
| Pandas & NumPy | Data manipulation and cleaning |
| Scikit-learn | TF-IDF, cosine similarity, ML models |
| Matplotlib & Seaborn | Visualizations and EDA |
| Jupyter Notebook | Development and analysis environment |

---

## 📁 Project Structure

```
Movie-Recommendation/
│
├── recommend.ipynb       # Content-based recommendation engine
├── moive.ipynb           # EDA and revenue prediction model
├── movies.csv            # Primary movie dataset
└── credits.csv           # Cast and crew data
```

---

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/SamadhiPathirathna/Movie-Recommendation.git
   ```
2. Install dependencies
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```
3. Open either notebook in Jupyter and run all cells
   ```bash
   jupyter notebook recommend.ipynb
   ```

---

## 👤 Author

**Samadhi Pathirathna**
[LinkedIn](https://www.linkedin.com/in/samadhi-pathirathna-a770b426a/) · [Portfolio](https://samadhipathirathna.github.io/DataPortfolio/) · [GitHub](https://github.com/SamadhiPathirathna)
