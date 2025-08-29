# Exploratory-Data-Analysis-of-Used-Motorbikes-from-BikeKarido

📌 Project Overview

The two-wheeler market in India has seen rapid growth, and resale platforms have become an important channel for buying and selling used bikes. This project focuses on analyzing used bike listings scraped from Bike Karido, a platform for second-hand bikes.

The goal is to identify market trends, price patterns, and ownership behaviors that can guide both buyers and sellers. The project follows a structured data analysis process — from data collection (web scraping) to EDA, insights, and business recommendations.

🎯 Objectives

Understand price distribution of bikes based on year, brand, ownership, and usage (Km driven).

Detect outliers and anomalies in resale data to assess data quality.

Explore buyer preferences for newer vs. older models.

Provide recommendations for sellers (pricing, demand strategy) and buyers (fair deal evaluation).

🛠️ Data Collection & Processing

Source: Bike Karido website.

Method: Web scraping (Python libraries such as requests, BeautifulSoup/Selenium).

Dataset Size: ~700+ records with features like brand, model, registration year, price, ownership, km driven, and location.

Data Cleaning Steps

Removed duplicates and irrelevant rows.

Handled missing values.

Detected outliers (unrealistic mileage/price entries).

Normalized categorical variables (brand names, ownership categories).

📊 Exploratory Data Analysis (EDA)
1. Univariate Analysis

Registration years are skewed towards recent bikes (2017–2022).

Price distribution is positively skewed, with a few luxury/high-end bikes driving up maximum values.

Most listings fall within First and Second ownership, indicating strong demand for bikes within 3–6 years of usage.

2. Bivariate & Multivariate Analysis

Price vs. Km Driven: As expected, more kilometers reduce resale value, but premium brands hold better value.

Year vs. Price: Sharp depreciation in older models; bikes from 2021–2022 dominate resale listings.

Brand Trends: Popular mass brands (Hero, Honda, Bajaj, TVS) have steady resale, while premium brands (Royal Enfield, KTM, Yamaha) show higher value retention.

Location Insights: Metro cities (Delhi, Bangalore, Hyderabad, Pune, Mumbai) dominate resale activity.

🔑 Key Findings

Newer bikes (1–4 years old) dominate resale → buyers prefer modern and efficient models.

Mass-market brands (Hero, Honda, Bajaj, TVS) make up majority listings.

Premium bikes (KTM, Royal Enfield, Yamaha) have stronger resale value even after higher usage.

First-owner bikes fetch the best prices and are in highest demand.

High mileage (Km driven) strongly impacts resale price, but exceptions exist in premium segments.

💡 Business Implications
For Sellers:

Sell within 3–5 years of purchase for the best value.

Highlight low mileage and first ownership in listings to attract higher resale prices.

Premium brands can demand higher resale prices if well maintained.

For Buyers:

Second-owner bikes are often undervalued compared to first-owner but can offer good deals.

Look for listings in metro cities, where variety and negotiation opportunities are higher.

Avoid overpriced new bikes (2022–2023) — better to buy slightly older bikes with lower depreciation.

🧩 Challenges & Learnings

Web scraping required handling dynamic content and inconsistent formats.

Outliers (like bikes showing 200,000+ km usage) needed careful inspection.

Learned the importance of domain understanding (bike market trends) to make meaningful insights.

✅ Conclusion

This project provides a data-driven view of India’s bike resale market. The analysis highlights how year, ownership, brand, and mileage influence resale prices. By combining data cleaning, visualization, and statistical insights, the project offers actionable recommendations for both buyers and sellers.

The study can be extended by:

Integrating more platforms for a larger dataset.

Building price prediction models using ML.

Studying regional demand more deeply.
