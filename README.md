# Customer-Sentiment-Analysis
Customer Sentiment Analysis – FlowerAura Product Reviews  This project analyzes customer reviews for the FlowerAura “10 Red Roses Bouquet” to understand customer satisfaction, sentiment patterns, and actionable business insights.

# Customer Sentiment Analysis – FlowerAura Product Reviews

This project analyzes customer reviews for the **FlowerAura "10 Red Roses Bouquet"** to understand customer satisfaction, sentiment patterns, and actionable business insights.

---

## Project Overview
This project performs **Web Scraping, Data Cleaning, Sentiment Analysis, Visualization, and Reporting** on customer reviews collected from the FlowerAura website.

The analysis helps identify:
- Overall customer satisfaction  
- Positive & negative sentiment drivers  
- Rating–sentiment relationships  
- Word patterns in reviews  
- Trends & insights for business decisions  

---

## 1. Data Collection (Web Scraping)
Reviews were collected using **Python, Requests, and BeautifulSoup**.

Two scraping approaches were used:

- **Static page scraping** 
- **Paginated scraping using API endpoint**  
  Successfully collected **110+ reviews**

Captured fields:
- Name  
- Rating  
- Review Text  
- Date  
- City  
- Occasion  

---

## 2. Data Cleaning & Preprocessing
Using **Pandas & NumPy**, the data was cleaned by:

- Handling missing values  
- Extracting:
  - **Date**
  - **City**
  - **Occasion**
- Converting date formats  
- Standardizing text  
- Removing unwanted characters  
- Creating additional columns:
  - **Review Length**
  - **Month**  

---

## 3. Sentiment Analysis (TextBlob)
Every review was analyzed with **TextBlob**:

Generated:
- **Polarity** (−1 to +1)
- **Subjectivity** (0 to 1)
- **Sentiment Label**:
  - Positive (≥ 0.1)
  - Negative (< 0.1)

---

##  4. Exploratory Data Analysis (EDA)
Analysis and charts done using **Matplotlib & Seaborn**.

### Visualizations Included:
- Sentiment Distribution  
- Rating vs Sentiment  
- Average Polarity per Rating  
- Word Cloud (Positive & Negative reviews)  
- Review Length vs Sentiment  
- Month-wise Sentiment Trend  
- Count of Reviews per Month  

All charts created with clean and simple formatting.

---

## 5. Insights & Findings

### Strengths
- Fast delivery ("before time", "on time")  
- High product quality ("beautiful", "fresh")  
- High customer satisfaction in special occasions  

### Improvement Areas
- Occasional quality mismatch  
- Minor delivery delays  
- Some customers report inconsistent experience  

### Rating Correlation
- Higher ratings correlate strongly with **positive polarity**
- 5★ reviews show the **highest sentiment scores**

---

##  6. Recommendations

### Immediate Improvements
- Improve quality consistency checks  
- Provide more accurate product descriptions  
- Enhance packaging  

### Long-Term Strategies
- Offer occasion-specific curated bundles  
- Create fast-response system for negative reviews  
- Launch “Customer Love” marketing campaign  
- Track monthly sentiment trends  

---

## Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Web Scraping | BeautifulSoup, Requests |
| Data Cleaning | Pandas, NumPy |
| Sentiment Analysis | TextBlob |
| Visualization | Matplotlib, Seaborn, WordCloud |
| Reporting | Python, Pandas |

---

License

This project is for educational purposes only.
All data belongs to FlowerAura.

Author

Himani Gautam
