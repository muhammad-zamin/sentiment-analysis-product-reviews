# 📊 Sentiment Analysis of Product Reviews  
*Task 3 – Data Science Internship Project*

## 🔍 Overview

This project applies Natural Language Processing (NLP) techniques to analyze customer reviews and extract insights on sentiment and key themes. It was developed as part of a data science internship and showcases a practical approach to product feedback analysis using Python.

---

## 📁 Project Structure

```
sentiment-analysis-product-reviews/
│
├── sentiment_analysis_product_reviews.ipynb         # Main notebook
├── Sentiment_Analysis_Report_Product_Review_Insights.docx  # Business report
├── Sentiment Analysis of Product Reviews Presentation.pdf  # Slide deck
├── sentiment_analysis_product_reviews_notebook.pdf  # PDF version of notebook
├── data/
│   └── product_reviews_mock_data.csv                # Mock review dataset
├── images/
│   ├── sentiment_distribution.png
│   ├── wordcloud_positive.png
│   ├── wordcloud_negative.png
│   ├── sentiment_by_product.png
│   └── ...
├── requirements.txt                                 # Required libraries
└── README.md                                        # This file
```

---

## 🧠 Objectives

- Perform sentiment analysis on product reviews using VADER
- Identify positive, neutral, and negative sentiments
- Discover key complaint topics via topic modeling
- Provide business-ready visualizations and recommendations

---

## 🧰 Tools & Libraries

- Python (Pandas, NLTK, Matplotlib, Seaborn, WordCloud)
- Scikit-learn (for topic modeling)
- Jupyter Notebook

---

## 🧪 Key Steps

### ✅ Step 1: Data Loading & Exploration
- Loaded mock product reviews
- Parsed review text and dates

### ✅ Step 2: Text Preprocessing
- Cleaned text using tokenization, stopword removal, lemmatization

### ✅ Step 3: Sentiment Analysis
- Applied VADER for sentiment scoring
- Classified reviews into Positive, Neutral, Negative

### ✅ Step 4: Visualization & Insights
- Sentiment by rating, time, and product
- Word clouds for sentiment groups
- Boxplots and trends

### ✅ Step 5: Topic Modeling
- Used LDA to extract complaint themes in negative reviews

---

## 📊 Key Visualizations

📌 Sentiment distribution chart  
📌 Sentiment over time (monthly trend)  
📌 Sentiment by product (bar chart)  
📌 Word clouds (positive & negative)  
📌 LDA topic modeling summary  

*(All visuals are available in the `/images/` folder)*

---

## 💡 Business Insights

- Products B and D had the most negative feedback.
- Main complaints: poor quality, missing parts, difficult setup.
- Positive sentiment aligns with ease of use and satisfaction.
- Actionable recommendations provided for product and marketing teams.

---

## 📎 Files to Explore

- `sentiment_analysis_product_reviews.ipynb`: Full notebook
- `Sentiment_Analysis_Report_Product_Review_Insights.docx`: Summary report
- `Sentiment Analysis of Product Reviews Presentation.pdf`: Business presentation
- `data/product_reviews_mock_data.csv`: Synthetic dataset

---

## ▶️ How to Run

1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `sentiment_analysis_product_reviews.ipynb` in Jupyter

---

## 📬 Feedback & Contributions

If you find this project helpful, feel free to ⭐️ the repo or fork it.  
Feedback and suggestions are welcome!

---

## 📌 Author

**Muhammad Zamin**  
[LinkedIn Profile](https://www.linkedin.com/in/your-profile)  
[Medium Blog](https://medium.com/@your-handle) *(if available)*
