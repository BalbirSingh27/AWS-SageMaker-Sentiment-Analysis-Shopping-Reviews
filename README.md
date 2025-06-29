## 🧠 Project Overview

This project analyzes customer reviews from various shopping categories to uncover sentiment trends and business insights using Natural Language Processing (NLP). The objective is to identify the most positively and negatively reviewed business types and recommend actionable improvements.

📅 **Key Features**:

* Conducted on **AWS SageMaker** using a Jupyter notebook environment
* Applied **K-Means Clustering**, **TF-IDF**, and **VADER/TextBlob sentiment analysis**
* Performed **Topic Modeling** using Latent Dirichlet Allocation (LDA)
* Developed actionable **business recommendations** based on NLP insights

## 🛒 Business Problem

Within the shopping domain, we aimed to understand:

* Which business categories are most liked/disliked?
* What are the common themes in high/low-rated reviews?
* How can businesses improve customer satisfaction?

## 🛠️ Tools & Technologies

* **Platform:** AWS SageMaker
* **Languages:** Python (Pandas, NLTK, TextBlob, Scikit-learn)
* **Techniques:** NLP, Sentiment Analysis, Clustering, Topic Modeling
* **Visualization:** Word Clouds, Star Rating & Review Length Distributions

## 📈 Key Insights

* **Gifts & Florists** had the highest customer satisfaction, driven by delivery and presentation quality.
* **Furniture & Home Improvement** faced the most negative reviews due to logistics and delivery issues.
* **Customer service** was a critical determinant across all categories.

## 📦 Repository Structure

```

📁 data/                → Raw business and review datasets  
📁 notebooks/           → Jupyter Notebook with full analysis (AWS SageMaker)  
📄 509 Final Project.ipynb → Core analysis script  
📄 README.md            → Project overview and results summary
```
## 💾 Dataset

🔗 **Full Dataset (on Kaggle)**:  
👉[balbir27/yelp-dataset-shopping-reviews-sentiment-analysis](https://www.kaggle.com/datasets/balbir27/yelp-dataset-shopping-reviews-sentiment-analysis)

📎 Note: A small sample dataset may be included in the repo for demonstration purposes.

## 📝 Recommendations

1. **Enhance delivery and logistics**, especially for furniture and florist categories.
2. **Improve staff training** to boost customer experience.
3. **Manage customer expectations** with accurate product representation.
4. **Investigate unrelated mentions** (e.g., pharmacy in furniture store reviews).

## 🔍 Project Outcome

This analysis not only helped highlight high and low-performing retail sectors but also provided strategic recommendations that businesses can implement to improve customer experience and boost ratings.
