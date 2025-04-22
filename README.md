# 📧 Spam Email Detection Using Structured Metadata

This project implements a lightweight machine learning model to classify emails as **spam** or **not spam** based solely on structured metadata — without analyzing full email content.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Model Performance](#model-performance)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [Future Work](#future-work)
- [License](#license)

---

## 📖 Overview

Spam detection is essential for email security and user productivity. Traditional methods rely heavily on full-text analysis, which can be slow and resource-intensive. This project takes a different approach: **using only metadata features like subject length, punctuation, and spam-related keywords** to classify emails.

---

## ❓ Problem Statement

Build a spam classification model using **structured metadata** extracted from emails to determine whether an email is spam or not, without using full email content or NLP techniques.

---

## 🎯 Objectives

- Build a machine learning model to detect spam based on metadata.
- Analyze the importance of each feature in spam classification.
- Achieve high accuracy using lightweight, structured data.
- Optimize for real-time applicability.

---

## 📂 Dataset

- **File Name**: `spam_emails.csv`
- **Columns** (examples):
  - `subject_length`
  - `num_exclamations`
  - `has_free`
  - `has_win`
  - `num_uppercase_words`
  - `spam` (target: 1 = spam, 0 = not spam)

*Note: This dataset was custom-built for this project.*

---

## 🧠 Methodology

1. Load and explore dataset.
2. Preprocess data and check for null values.
3. Split into training and test sets (80/20).
4. Train a **Random Forest Classifier**.
5. Evaluate using accuracy, precision, recall, and F1-score.
6. Visualize feature importance.

---

## 📈 Model Performance

| Metric        | Score  |
|---------------|--------|
| Accuracy      | 0.92   |
| Precision     | 0.91   |
| Recall        | 0.93   |
| F1-Score      | 0.92   |

> Results may vary slightly depending on dataset variations.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/spam-metadata-detector.git
cd spam-metadata-detector
