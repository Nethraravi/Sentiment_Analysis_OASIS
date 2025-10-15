# 🧠 Sentiment Analysis Project

This project was completed as part of my **OASIS Infobyte Internship**.  
It focuses on analyzing customer feedback and classifying it into **Positive**, **Neutral**, and **Negative** sentiments using **Natural Language Processing (NLP)** and **Machine Learning**.


## 🚀 Project Overview

The main goal of this project is to understand public opinions, customer feedback, and user reviews by analyzing text sentiment.  
Using NLP and classification algorithms, the model identifies the emotional tone behind each review.


## 🧩 Key Features

- Added three new columns:
  - **Polarity** – measures sentiment strength using TextBlob  
  - **Sentiment** – categorized as *Positive*, *Neutral*, or *Negative*  
  - **Sentiment Score** – numerical mapping of sentiment (-1, 0, +1)
- Implemented **Naive Bayes** for sentiment classification  
- Applied **Feature Engineering** using TF-IDF Vectorization  
- Utilized **Ratings-based sentiment mapping**:
  - 0.0 – 2.5 → Negative  
  - 2.6 – 3.5 → Neutral  
  - 3.6 – 5.0 → Positive  
- Achieved **91.4% accuracy** on the test dataset ✅


## 📊 Visualizations

To better interpret sentiment distribution, several visualizations were created:
- 📈 **Bar Chart** – Sentiment count distribution  
- 🥧 **Pie Chart** – Sentiment percentage breakdown  
- 🔵 **Scatter Plot** – Sentiment score spread  
- 🧮 **Confusion Matrix** – Model performance evaluation  

All visuals were created using **Matplotlib** and **Seaborn** for a colorful, engaging presentation.


## 🧠 Technologies Used

- **Python** 🐍  
- **Pandas**, **NumPy** – Data handling  
- **TextBlob** – Sentiment polarity analysis  
- **Scikit-learn** – Machine Learning (Naive Bayes)  
- **Matplotlib**, **Seaborn** – Data visualization  
- **Jupyter Notebook** – Development environment  


## 🧪 Model Performance

| Metric | Score |
|--------|--------|
| **Accuracy** | 0.914 |
| **Algorithm Used** | Naive Bayes |



## 💡 Insights

- Successfully mapped numeric ratings to textual sentiment.  
- Demonstrated the power of NLP in understanding human emotion through data.  
- Showcased data storytelling using visualizations and machine learning.  


## 🙌 Acknowledgment

Special thanks to **OASIS Infobyte** for providing this opportunity and helping me explore my passion for **Data Science & NLP**.


