# 🛍️ Marketing Analytics Dashboard – ShopEasy

This repository presents a Power BI dashboard project developed for **ShopEasy**, an online retail business. The project analyzes marketing performance across key areas like **conversion rates**, **customer engagement**, and **customer feedback**, with the goal of improving overall marketing effectiveness.

---

## 🧩 Business Problem

**Client**: ShopEasy (Online Retailer)

Despite launching several marketing campaigns and increasing budget allocations, ShopEasy is experiencing:

- 📉 **Decreased conversion rates**
- 👎 **Reduced customer engagement**
- 💸 **High marketing expenses with low ROI**
- 🤔 **Unclear customer sentiment and satisfaction**

The client requested a **comprehensive data analysis** to uncover root causes, highlight trends, and provide actionable strategies to address these issues.

---

## 📊 Dashboard Highlights

This Power BI dashboard provides insights from data collected across three years (2023–2025), including product performance, engagement metrics, and customer reviews.

### 🔄 Conversion Analysis
- **Highest conversion month**: January (18.5%), driven by high-performing items like **Ski Boots** (150% conversion rate).
- **Lowest conversion month**: May (4.3%), suggesting ineffective seasonal campaigns.
- **Top converting products**: Kayaks, Ski Boots, Baseball Gloves.

### 📉 Engagement Analysis
- **Declining views** from August onward, indicating **reduced customer interest** in H2.
- **Low interaction rates** (clicks/likes), especially compared to views.
- **Content performance**: Blog content led views; social media and video were steady but lower.

### 🌟 Customer Feedback
- **Average Rating**: ~3.7 (below target of 4.0).
- **Review Distribution**:  
  - 135 reviews rated 5 stars  
  - 140 reviews rated 4 stars  
  - 83 reviews rated 1–2 stars
- **Sentiment Breakdown**:  
  - 275 Positive  
  - 82 Negative  
  - Some mixed feedback that can be converted into stronger satisfaction.

---

## 🎯 Goals & Actions

### 1. 🟢 Increase Conversion Rates
**Goal**: Identify and address drop-off points in the customer journey.  
**Action**:
- Focus on best-performing products like Kayaks and Ski Boots.
- Launch seasonal and personalized promotions during high-converting periods.

### 2. 💬 Enhance Customer Engagement
**Goal**: Determine what content types and channels drive interaction.  
**Action**:
- Revamp content strategy: Include interactive content and optimize call-to-actions.
- Focus on underperforming months (e.g., Sept–Dec) with targeted campaigns.

### 3. ⭐ Improve Customer Feedback Scores
**Goal**: Understand recurring review themes to improve satisfaction.  
**Action**:
- Analyze negative and mixed reviews to fix pain points.
- Consider follow-up engagement to resolve concerns and encourage updated ratings.

---

## 🚀 How to Use

1. Download or clone the repository.
2. Open the `Marketing_Analytics_Dashboard.pbix` file using **Power BI Desktop**.
3. Explore insights through dynamic visuals and filters.

---

## 📌 Tools Used

- **Power BI Desktop**
- **Data Visualization & DAX**
- **Customer Review & Sentiment Analysis**
- **Time-Series and KPI Trend Analysis**

---

## 🧹 Data Cleaning & SQL Work

Used SQL to:
- Join customer and geographic data for enriched insights.
- Categorize products by price bands (Low, Medium, High).
- Clean and normalize text fields and engagement formats.
- Extract views/clicks from combined fields.
- Identify and remove duplicate records in customer journeys using CTEs and `ROW_NUMBER()`.
- Fill missing durations with daily averages for accurate timeline analysis.

---

## 🙌 Final Thoughts

This project showcases how marketing data can be transformed into clear, actionable insights using Power BI and SQL. It reflects practical skills in business analysis, visualization, and decision-making support.

---

