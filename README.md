# 🏍️ Bike Market Analysis – Web Scraping & Exploratory Data Analysis

## 📌 Project Overview

**Bike Market Analysis** is a data analytics project focused on collecting real-world bike listing data through web scraping and performing Exploratory Data Analysis (EDA).

The project analyzes bike **pricing, brands, customer ratings, engine capacity, maximum power, braking systems, tire types, and other specifications** to identify market trends, relationships, and business opportunities.

The final dataset contains **263 bike records and 11 analysis-ready features**.

---

## 🎯 Business Problem

Online bike listings contain a large amount of information about prices, brands, performance, customer ratings, and specifications. However, raw listing data is difficult to interpret directly for market analysis.

This project aims to transform raw bike listing data into meaningful business insights by analyzing:

* Brand and pricing trends
* Engine and performance patterns
* Customer ratings and reviews
* Bike specifications and features
* Relationship between price and performance
* Market opportunities and recommendations

---

## 🎯 Project Objectives

* Collect real-world bike data through web scraping
* Extract important bike details such as price, brand, rating, engine capacity, and power
* Clean and preprocess the scraped data
* Handle missing values and inconsistent formats
* Standardize maximum power values into BHP
* Perform Exploratory Data Analysis
* Identify relationships between important bike features
* Generate business insights and recommendations

---

## 🌐 Data Source

**Website:** Flipkart

**Data Category:** Non-Electric Motorcycles

The data was collected from online bike listings and processed for analysis.

---

## 📊 Dataset Information

| Attribute      | Details                      |
| -------------- | ---------------------------- |
| Total Records  | 263                          |
| Total Features | 11                           |
| Data Type      | Structured bike listing data |
| Category       | Non-Electric Motorcycles     |
| Currency       | INR                          |

### Main Features

* Product Name
* Brand
* Price
* Rating
* Total Ratings
* Total Reviews
* Engine Capacity (CC)
* Maximum Power (BHP)
* Front Brake
* Console Type
* Tire Type

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**
* **Web Scraping**
* **BeautifulSoup / Requests** *(if used in the scraping code)*

---

## 🔄 Project Workflow

```text
Online Bike Listings
        ↓
Web Scraping
        ↓
Raw Dataset
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Final Dataset
        ↓
Exploratory Data Analysis
        ↓
Business Insights
        ↓
Recommendations
```

---

## 🌐 Web Scraping Process

The data collection process followed these steps:

1. Select the website and bike category
2. Search for bike listings
3. Extract required product information
4. Store the extracted data in a Pandas DataFrame
5. Save the scraped dataset for further processing

---

## 🧹 Data Cleaning & Feature Engineering

The raw scraped data contained several issues, including:

* Missing values
* Inconsistent formats
* Mixed data types
* Unnecessary columns
* Different formats for power specifications
* Inconsistent brand/category names

### Data Preparation

The following steps were performed:

* Handled missing values
* Corrected data types
* Standardized categories
* Removed unnecessary columns
* Extracted maximum power values
* Converted power values into BHP
* Created analysis-ready features

### Example

```text
Raw Power:
8.68 kW (11.8 PS) @ 8500 rpm

        ↓

Clean Feature:
11.8 BHP
```

---

# 📈 Exploratory Data Analysis

The following business questions were analyzed during the project.

### 1. What is the overall price distribution of bikes?

The bike market is largely concentrated in the **lower-to-mid price segment**, with relatively fewer premium-priced models.

### 2. Which brands have the highest number of bike models?

**Hero** has the highest number of bike models in the analyzed dataset, indicating strong product presence.

### 3. Which brands have the highest average bike prices?

**Harley Davidson** has the highest average bike price among the analyzed brands, indicating stronger positioning in the premium segment.

### 4. Which front braking system is most commonly used?

**Disc brakes** are the most common front braking system, accounting for approximately **57.4%** of the analyzed bikes.

### 5. How does bike price vary across tire types?

Bikes with **tubeless tires** generally show a higher median price and a wider price distribution compared with tubed bikes.

### 6. Does higher engine capacity result in higher maximum power?

The analysis shows a **strong positive relationship** between engine capacity and maximum power.

### 7. What is the relationship between price and performance?

The correlation analysis indicates a **positive relationship between price and maximum power**, suggesting that higher-performance bikes tend to be positioned at higher price points.

---

# 💡 Key Business Insights

* **Hero** has the highest number of bike listings in the analyzed dataset.
* **Harley Davidson** has the highest average bike price.
* The **100–200 CC** engine segment is the most commonly represented.
* Engine capacity and maximum power have a positive relationship.
* Higher-powered bikes generally command higher prices.
* **Disc brakes** are the most commonly listed front braking system.
* Tubeless tires are more prevalent among higher-priced models.

---

# 📌 Business Recommendations

Based on the analysis, the following recommendations can be made:

### 1. Focus on the Dominant Price Segment

Target the largest market segment to capture greater demand.

### 2. Strengthen Mid-Range Models

Balance price, performance, and features to attract a wider customer base.

### 3. Improve Performance-to-Price Value

Offer better performance at competitive prices.

### 4. Promote Highly Rated Bikes

Give more visibility to highly rated models to support customer purchase decisions.

### 5. Enhance Modern Features

Improve safety and technology features to increase product value.

### 6. Maintain Competitive Pricing

Provide strong value compared with competing products.

---

# ⚠️ Challenges Faced

During the project, we faced several challenges:

* Dynamic website data and changing website structures
* Inconsistent bike specification formats
* Missing values
* Different maximum-power units and formats
* Brand and category standardization
* Cleaning and preprocessing scraped data
* Filtering electric-bike-specific records from the final analysis

---

# 📁 Project Structure

```text
bike-market-analysis-eda/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── raw/
│   │   └── bike_raw_data.csv
│   │
│   └── processed/
│       └── bike_cleaned_data.csv
│
├── notebooks/
│   └── bike_market_analysis.ipynb
├── outputs/
│   ├── charts/
│   └── insights/
│
└── presentation/
    └── Bike_Market_Analysis_Presentation.pptx
```

---

# 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the project directory

```bash
cd bike-market-analysis-eda
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the analysis

Open:

```text
notebooks/bike_market_analysis.ipynb
```

and execute the notebook cells sequentially.

---

# 📊 Final Outcome

The project successfully transformed raw online bike listing data into an analysis-ready dataset.

```text
Real-World Bike Data
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Business Insights
        ↓
Data-Driven Recommendations
```

The analysis provides a structured view of **bike pricing, brand presence, performance, braking systems, tire types, and market positioning**.

---

# 👨‍💻 Team

### Kurivella Bala Venkata Mani Kanta

**Team Leader**

* B.Tech – Computer Science & Engineering
* Data Science Trainee
* Skills: Python, SQL, Power BI, Excel, Web Scraping

### Sankara P Manohar

* B.Tech – Artificial Intelligence & Data Science
* Data Science Trainee
* Skills: Python, SQL, Power BI, Excel, Web Scraping

---

# 📜 Conclusion

We successfully collected **263 bike listings**, cleaned and transformed the data into **11 analysis-ready features**, and performed Exploratory Data Analysis on pricing, brands, performance, ratings, and bike features.

The project identified meaningful relationships between **engine capacity, maximum power, and price**, and converted these findings into practical business insights and recommendations.

> **Real-world bike data → Meaningful market insights**

---

## 📎 Project Presentation

The complete project presentation is available in the `presentation/` folder.

## ⭐ Project Highlights

* Real-world web-scraped dataset
* Data cleaning and preprocessing
* Feature engineering
* Exploratory Data Analysis
* Business-focused questions
* Data-driven insights
* Actionable recommendations
