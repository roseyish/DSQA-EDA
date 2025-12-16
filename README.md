# DSQA-EDA
Exploratory Data Analysis on a Domain-Specific Question Answering Dataset

# Exploratory Data Analysis of a Question Answering Dataset

## 📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on a
domain-specific Question Answering (QA) dataset. The goal is to understand
the dataset structure, category distribution, answer types, and textual
complexity of questions before applying NLP or machine learning models.

## 📊 Dataset Description
- Total Questions: 900
- Domains: Multiple (Sports, Politics, Education, Media & Entertainment, etc.)
- Answer Types:
  - Single Answer
  - Set Answer

## 🔍 EDA Objectives
- Analyze dataset structure and completeness
- Identify dominant and underrepresented categories
- Study answer type distributions across domains
- Perform text-based analysis using question length as a complexity proxy

## 📈 Key Insights
- The dataset is category-imbalanced, with certain domains dominating.
- Most questions require single answers, simplifying evaluation strategies.
- Categories like Education and Politics show higher linguistic complexity.
- Sports-related questions tend to be shorter and fact-based.

## 🛠️ Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Project Structure
DSQA-EDA/
├── data/
│ └── DSQA-full.csv
├── notebooks/
│ └── eda_dsqa.ipynb
└── README.md
