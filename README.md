# Product Analytics Case Study: E-commerce Funnel & Retention

## 📌 Overview
This project analyzes user behavior in an e-commerce platform using the Retailrocket dataset.

The goal is to identify key conversion bottlenecks and understand user retention patterns to uncover product improvement opportunities.

---

## 🎯 Objectives

- Analyze the user funnel (View → Cart → Purchase)
- Measure user retention using cohort analysis
- Identify key drop-off points
- Provide actionable business recommendations

---

## 📊 Dataset

Retailrocket dataset containing user interaction events:
- View
- Add to Cart
- Transaction

---

## 🔍 Funnel Analysis

- View → Cart: **2.69%**
- Cart → Purchase: **31.07%**
- View → Purchase: **0.83%**

👉 The largest drop-off occurs at the **View → Cart stage**

---

## 📈 Retention Analysis

- Day 1 retention: **2.74%**
- Day 7 retention: **0.56%**

👉 Retention drops sharply after the first interaction

---

## 🧠 Key Insights

- Users rarely progress beyond product browsing
- The main bottleneck is **early-stage engagement**, not checkout
- Users also do not return after their first visit

👉 This indicates issues with:
- Product discovery
- User engagement
- Value proposition

---

## 💼 Business Impact

The analysis reveals critical inefficiencies in the user journey:

- Extremely low overall conversion (0.83%)
- Significant early-stage drop-off
- Low retention → low customer lifetime value

👉 Improving these areas could significantly increase revenue and retention.

---

## ❗ Why This Matters

Improving early-stage engagement has a multiplicative effect:
more users enter the funnel → more conversions → higher revenue.

---

## 🚀 Recommendations

- Improve product page UX (images, descriptions, reviews)
- Enhance recommendation system
- Optimize onboarding experience
- Implement retargeting strategies

---

## 🛠 Tools Used

- Python (Pandas)
- Jupyter Notebook
- Data Visualization (Matplotlib)

---

## 📁 Project Structure
```
.
├── Notebooks/
│ └── retailrocket_analysis.ipynb # main analysis notebook
├── data/                         # raw dataset (not included in repo)
├── README.md                     # project description
```

---

## 👤 Author

Egor Sakulin
