# 🌐 Website Traffic Analysis | Alfido Tech Data Analytics Task

## 📌 Project Overview

This project analyzes website traffic data to understand user behavior, traffic sources, session performance, and user journeys. The objective is to identify patterns in website visits, evaluate user engagement, discover the most effective acquisition channels, and provide actionable recommendations to improve website conversions.

This project was completed as part of the **Alfido Tech Data Analytics Internship Task**.

---

## 🎯 Objectives

- Clean and preprocess website traffic data.
- Analyze user sessions and website engagement.
- Identify top landing and exit pages.
- Evaluate referral sources and traffic channels.
- Calculate key website performance metrics.
- Visualize user journeys and website traffic patterns.
- Recommend strategies to improve website conversions.

---

## 📂 Dataset

**Source:** Kaggle – Website Traffic Analysis Dataset

The dataset contains website traffic information such as:

- User Sessions
- User IDs
- Landing Pages
- Exit Pages
- Referral Sources
- Traffic Channels
- Session Duration
- Device Information
- Geographic Information (if available)
- Timestamps

> **Note:** The available metrics depend on the dataset. Any unavailable metrics are clearly documented in the analysis.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Power BI (Optional)
- Git & GitHub

---

## 📊 Data Cleaning & Preparation

The following preprocessing steps were performed:

- Removed duplicate records
- Checked for missing values
- Converted timestamps into datetime format
- Standardized column names
- Removed invalid or incomplete session records
- Created additional features including:
  - Year
  - Month
  - Day
  - Hour
  - Weekday
  - Session Duration (if applicable)

---

## 📈 Key Performance Indicators (KPIs)

The following KPIs were calculated:

- 👥 Total Users
- 💻 Total Sessions
- 📄 Total Page Views
- ⏱ Average Session Duration
- 🔄 Bounce Rate
- 📈 Pages per Session
- 🚪 Exit Rate
- 🎯 Top Referral Sources

---

## 📊 Exploratory Data Analysis

### 👥 User Analysis

- Total Users
- Returning vs New Users (if available)
- User Distribution

### ⏱ Session Analysis

- Session Duration Distribution
- Average Session Duration
- Sessions by Hour
- Sessions by Day

### 🌍 Traffic Source Analysis

- Referral Sources
- Organic Search
- Direct Traffic
- Social Media
- Email Campaigns
- Paid Traffic (if available)

### 📄 Landing & Exit Page Analysis

- Top Landing Pages
- Top Exit Pages
- Most Visited Pages
- Bounce Rate by Landing Page

### 🔀 User Journey Analysis

- Common Navigation Paths
- Entry to Exit Flow
- User Flow Visualization
- Session Behavior

### 📱 Device Analysis

- Desktop Users
- Mobile Users
- Tablet Users

### 📍 Geographic Analysis

- Traffic by Country
- Traffic by Region
- Top Performing Locations

---

## 📊 Dashboard

The dashboard consists of three pages.

### 📌 Page 1 — Website Overview

- Total Users
- Total Sessions
- Average Session Duration
- Bounce Rate
- Sessions Trend
- Users Trend

### 📌 Page 2 — User Behaviour

- Landing Pages
- Exit Pages
- Referral Sources
- User Journey Flow
- Device Distribution

### 📌 Page 3 — Traffic Insights

- Geographic Distribution
- Traffic Channels
- Hourly Traffic
- Daily Traffic
- Bounce Rate Analysis

---

## 📌 Key Insights

The analysis identifies:

- Most visited landing pages.
- Primary traffic acquisition channels.
- User engagement across different devices.
- Website pages with the highest bounce rates.
- User navigation patterns.
- Peak traffic periods.
- High-performing referral sources.

---

## 💡 Business Recommendations

1. Optimize high-traffic landing pages with stronger calls-to-action (CTAs) to improve conversions.

2. Reduce bounce rates by improving page loading speed and content relevance on top exit pages.

3. Invest more in the highest-performing referral channels while optimizing underperforming marketing campaigns.

4. Improve the mobile browsing experience through responsive design and faster page performance.

5. Simplify user navigation and internal linking to encourage deeper engagement and longer session durations.

---

## 📁 Project Structure

```
Website-Traffic-Analysis/
│
├── data/
│   └── website_traffic.csv
│
├── notebook/
│   └── Website_Traffic_Analysis.ipynb
│
├── dashboard/
│   └── Website_Traffic_Dashboard.pbix
│
├── reports/
│   ├── Executive_Summary.pdf
│   └── Dashboard.pdf
│
├── images/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│   ├── dashboard_page3.png
│   └── charts/
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Website-Traffic-Analysis.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook
```

### 4. Run all cells to reproduce the complete analysis.

### 5. Open the Power BI dashboard (`.pbix`) to explore the interactive visualizations.

---

## 📷 Dashboard Preview

Add dashboard screenshots here after completing the project.

Example:

- Website Overview Dashboard
- User Behaviour Dashboard
- Traffic Insights Dashboard

---

## 📄 Deliverables

- ✅ Jupyter Notebook
- ✅ Interactive Dashboard (Power BI/Tableau)
- ✅ Executive Summary Report
- ✅ Business Recommendations
- ✅ Visualizations
- ✅ GitHub Repository

---

## 📚 Python Libraries

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- warnings

---

## 👨‍💻 Author

**Kshitij Garg**

B.Tech CSE (AI) | Maharaja Agrasen Institute of Technology (MAIT)

Aspiring Data Analyst | Power BI | SQL | Python | Excel | Tableau

---

## ⭐ If you found this project useful, consider giving it a star!
