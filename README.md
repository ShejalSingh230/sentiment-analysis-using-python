# 🧠 Sentiment Analysis on Customer Reviews 📊

Welcome to the **Sentiment Analysis** project! This Python-based project connects to a SQL Server database, analyzes customer reviews using NLP (VADER Sentiment Analyzer), and categorizes sentiments based on both textual sentiment and customer ratings.

---

## 🚀 Project Overview

This project helps analyze the tone of customer feedback to gain insights into product reception and customer satisfaction. It performs the following steps:

- Connects to a Microsoft SQL Server database
- Extracts customer review data
- Applies **VADER Sentiment Analysis** using `nltk`
- Combines sentiment score with customer rating for deeper insight
- Categorizes and buckets sentiment
- Saves results to a CSV file for future analysis or reporting

---

## 🧰 Tech Stack

- 🐍 Python
- 📦 Pandas
- 🔗 pyodbc (for SQL Server connection)
- 🧠 NLTK (VADER Sentiment Analyzer)
- 🗃️ SQL Server

---

## 📦 Installation

Install the required libraries:

```bash
pip install pandas nltk pyodbc sqlalchemy

