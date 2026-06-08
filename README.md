# Play Store App Review Analysis (EDA)

##  Project Overview
This project focuses on analyzing Google Play Store app data along with user reviews to understand the key factors that influence app success, user engagement, and overall performance.

The goal is to extract meaningful insights from the data that can help developers and businesses make better decisions.

---

## Business Objective
The main objective is to analyze app-related data and user feedback to identify:
- What makes an app successful
- Factors affecting installs and ratings
- User sentiment and satisfaction
- Opportunities for improving app performance

---

## Dataset Information

### 1. Play Store Data
Contains app details such as:
- App Name
- Category
- Rating
- Reviews
- Installs
- Size
- Price
- Content Rating

### 2. User Reviews Data
Contains:
- App Name
- User Reviews
- Sentiment (Positive, Negative, Neutral)
- Sentiment Polarity & Subjectivity

---

## Data Cleaning & Preprocessing
- Removed duplicate values
- Handled missing values using median/mode
- Converted columns like Installs, Price, and Size into numeric format
- Removed invalid values (e.g., rating > 5)
- Cleaned text data for better analysis

---

## Exploratory Data Analysis (EDA)

The following types of analysis were performed:

- Distribution of ratings
- Free vs Paid apps analysis
- Category-wise app distribution
- Relationship between installs and ratings
- Reviews vs installs analysis
- Price distribution
- Sentiment analysis using user reviews
- Correlation heatmap
- Pair plot for multi-variable relationships

---

## Key Insights

- Free apps dominate the Play Store and have higher installs
- Most apps have ratings between 4 and 4.5
- Strong relationship between installs and reviews
- Ratings alone do not guarantee app success
- User sentiment is mostly positive but highlights improvement areas
- Paid apps have significantly lower installs compared to free apps

---

## Business Recommendations

- Focus on freemium model (free + ads/in-app purchases)
- Improve user experience to maintain high ratings
- Use user reviews to fix issues and improve app quality
- Encourage users to leave reviews to increase trust
- Choose categories wisely (avoid highly saturated markets)

---

## Limitations

- Dataset may not be fully up-to-date
- Ratings may be biased (users mostly rate when satisfied)
- Sentiment analysis is basic and may not capture full context
- Some data cleaning assumptions may affect results

---

## Future Scope

- Build a recommendation system for apps
- Perform advanced sentiment analysis (NLP)
- Predict app ratings using machine learning
- Analyze user behavior patterns in detail

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Conclusion

The project shows that app success depends on multiple factors such as user engagement, reviews, pricing strategy, and overall user experience. Data-driven insights can help developers improve their apps and compete effectively in the market.
