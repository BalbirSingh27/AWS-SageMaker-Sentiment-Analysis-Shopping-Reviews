# 🛍️ Final Project: Evaluating Business Ratings & Preferences Across Shopping Categories

## 🎯 Objective
This project investigates customer reviews across different **shopping categories** to:
- Identify the most positively and negatively rated business types
- Analyze the sentiment drivers behind those ratings
- Provide data-driven **recommendations** to improve customer experience

---

## 📦 Business Problem

Businesses receive a range of reviews across platforms like Yelp, but it's not always clear which shopping categories perform best in the eyes of customers.  
This project focuses on:
- Detecting which types of stores receive consistently high or low reviews
- Understanding **why** customers rate them the way they do
- Offering **business recommendations** for service improvement

---

## 🧹 Data Preparation

### 📁 Datasets Used:
- `business.json`: Includes metadata and category info
- `review.json`: Includes star ratings and review text

### 🔧 Cleaning Process:
- Filtered for records relevant to *shopping categories*
- Merged business and review datasets using `business_id`
- Conducted **K-Means clustering** on categories to group them into 4 key segments:
  1. Fashion & Personal Goods Stores  
  2. Gifts, Florists & Specialty Shops  
  3. Home Improvement & Furniture Stores  
  4. Books, Media & Hobby Shops

---

## 📊 Exploratory Data Analysis (EDA)

### ⭐ Star Rating Trends
- **5-star reviews**: Highlight great customer service, store layout, helpful staff  
- **1-star reviews**: Focus on delivery issues, poor service, wait times

### 📈 Review Length
- Most reviews are **under 100 words**, showing customers tend to leave **brief feedback**

### ☁️ Word Cloud Insights
- **Positive** keywords: “great,” “helpful,” “love,” “fast”  
- **Negative** keywords: “rude,” “late,” “wait,” “broken”

---

## 💬 Sentiment Analysis

- Tools used: **VADER** and **TextBlob**
- Results:
  - Majority of reviews are **positive**
  - **Gifts & Florists** have the most favorable sentiment
  - **Furniture Stores** showed the highest complaint volume

---

## 🧠 NLP Techniques & Topic Modeling

### TF-IDF + BERT
- Extracted top keywords per category
- Applied **topic modeling** to cluster semantic themes

### Topic Examples:
- **Fashion Stores**: “dresses,” “staff,” “mall”  
- **Florists**: “flowers,” “delivery,” “wedding”  
- **Furniture Stores**: “couch,” “delivery,” “price”  
- **Bookstores**: “books,” “selection,” “staff”

---

## 📌 Business Insights

1. **Customer Service** is the #1 driver of both positive and negative reviews
2. **Furniture stores** face the most issues related to **delivery and logistics**
3. **Fashion stores** are heavily reviewed for staff service and shopping experience
4. **Florists** depend on delivery reliability and presentation
5. **Bookstores** had fewer distinct issues—general customer satisfaction
6. **Unexpected Pharmacy Mentions** in furniture-related stores indicate data blending or cross-category discussion

---

## ✅ Recommendations

1. **Improve Customer Service Across All Categories**
   - Consistent staff training, online & in-store support
2. **Fix Delivery Issues in Furniture and Florist Categories**
   - Implement better tracking and transparency
3. **Set Accurate Product Expectations**
   - Use real customer images, control listing accuracy
4. **Investigate Anomalies**
   - Explore pharmacy mentions in unrelated categories

---

## 🧰 Tools & Technologies
- Python (Pandas, Numpy)
- NLP Libraries: NLTK, TextBlob, VADER
- Clustering: K-Means
- Topic Modeling: TF-IDF, BERT
- Visualization: WordCloud, Matplotlib, Seaborn

---

## 📈 Visuals Included (not embedded here)
- Word Clouds by rating
- Star Rating Distributions
- Topic Distributions per Category
- Review Sentiment Scores

---

## 🎯 Outcome
Our team delivered actionable insights on what customers value most—and where businesses can improve—using natural language techniques, sentiment analysis, and clustering. These insights help optimize customer experience strategies and store operations across shopping categories.

---

