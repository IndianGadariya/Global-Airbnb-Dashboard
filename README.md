# 🌍 Global Airbnb Performance Dashboard | Power BI

An interactive Power BI dashboard analysing Airbnb's global marketplace performance across 10 cities, focusing on listing growth, geographical distribution, room-type pricing, customer ratings, review behaviour and host trust indicators.

## 📌 Project Overview

This project explores Airbnb's marketplace data from 2008 to 2021 using Power BI. It brings together listing and review data to identify marketplace trends, compare city performance and understand customer experiences.

The dashboard consists of three interactive pages:
- Overview
- Ratings
- Reviews

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and data visualization
- **Power Query** – Data preparation and transformation
- **DAX** – Calculated columns, measures and analytical calculations
- **Data Modelling** – Relationship between Listings and Reviews tables
- **Excel / CSV** – Dataset handling

## 📊 Dataset

- **Source:** Maven Analytics
- **Files:** `Listings.csv` and `Reviews.csv`
- **Time Period:** 2008–2021
- **Geographical Coverage:** 10 global cities

---

# 🔍 Project Analysis – 5-Step Approach

## Step 1: Business Problem

Airbnb operates across multiple cities with different property types, hosts and customer experiences. However, understanding its overall marketplace performance, customer satisfaction and host performance requires analysing data from multiple dimensions.

The challenge is to gain a consolidated understanding of Airbnb's marketplace performance and identify important trends and improvement opportunities.

## Step 2: Goal of the Dashboard

The goal was to analyse Airbnb's global performance across different cities, focusing on listing growth, pricing, customer ratings and review behaviour.

I brought these insights together in an interactive Power BI dashboard to help stakeholders identify trends, compare performance and make data-driven decisions.

## Step 3: Walk Through the Key Visuals

### 1. Overview Page

**Key Visual: Listing Growth Over Time**

- Analyses the growth of Airbnb listings between 2008 and 2021.
- Shows the rapid growth in listings between 2011 and 2016.
- Highlights fluctuations after the peak period and a decline during 2020–2021.
- Entire-place listings form the dominant category in the displayed trend.

### 2. Ratings Page

**Visual 1: Market Share by City (Line and Stacked Column Chart)**

- Paris, New York and Sydney together account for approximately 48.4% of total listings.
- Paris has the highest number of listings.
- The chart compares Superhost and non-Superhost listings across cities.

**Visual 2: Average Price by Room Type**

- Hotel rooms have the highest average price ($800.2).
- Private rooms have the lowest average price ($462.4).

**Visual 3: Overall Ratings (Stacked Column Chart)**

- Mexico City and Rio de Janeiro have the highest overall ratings (95/100).
- Hong Kong has the lowest overall rating (90/100), followed by Istanbul.

**Visual 4: Detailed Ratings (Matrix)**

- Compares city-wise ratings across accuracy, cleanliness, communication, value and location.
- Cleanliness and value are among the relatively lower-scoring rating dimensions.

**Interactive Feature:** Bookmarks allow users to switch between Overall Ratings and Detailed Ratings views without navigating to another report page.

### 3. Reviews Page

**Visual 1: Review Frequency (Line and Clustered Column Chart)**

- Approximately 86% of reviewers have written just one review.
- Most reviewers have written three reviews or fewer.
- One reviewer has an unusually high count of 283 reviews. This outlier was investigated, including their last two reviews dated 13 October 2020 for two Bangkok listings.

**Visual 2: Host Trust Indicators**

- Approximately 66.9% of hosts have both identity verification and a profile picture.
- Nearly all hosts have at least one of these two trust indicators.

**Visual 3: Review Seasonality (Ribbon Chart)**

- Paris and Rome have a higher share of reviews between April and August.
- New York shows an increased review share during November and December.

---

## Step 4: Highlight the Key Insights

1. **Listing Growth:** Listings grew rapidly between 2011 and 2016, followed by fluctuations and a decline in 2020–2021.

2. **Market Share:** Paris, New York and Sydney together account for approximately 48.4% of total listings.

3. **Room Pricing:** Hotel rooms have the highest average price ($800.2), while private rooms have the lowest ($462.4).

4. **Customer Ratings:** Mexico City and Rio de Janeiro have the highest overall ratings, while Hong Kong has the lowest.

5. **Review Behaviour:** Approximately 86% of reviewers wrote just one review.

6. **Host Trust:** Around 66.9% of hosts have both identity verification and a profile picture.

---

## Step 5: Business Impact – Potential Recommendations

Based on the dashboard findings, the following business decisions could be considered:

1. **Paris, New York and Sydney:** Since these cities account for almost half of the listings, Airbnb could prioritise marketplace monitoring and host support in these major markets while exploring growth opportunities in smaller markets.

2. **Hong Kong:** Since it has the lowest overall rating (90/100), Airbnb could investigate customer feedback and identify improvements in listing accuracy, cleanliness and value for money.

3. **Mexico City and Rio de Janeiro:** Since both have the highest overall ratings (95/100), Airbnb could study their successful host and service practices and explore opportunities to replicate them in lower-rated cities.

4. **Hotel Rooms:** With the highest average price ($800.2), Airbnb could review hotel-room pricing and compare its competitiveness with other accommodation types.

5. **Paris and Rome:** Since their review shares increase from April to August, hosts could prepare for seasonal travel patterns by adjusting availability, pricing and staffing.

6. **Review Frequency Outlier:** The unusually high review count of 283 from one reviewer could be investigated further to validate the data and understand exceptional reviewer activity.

7. **Host Verification:** Since only 66.9% of hosts have both identity verification and a profile picture, Airbnb could encourage more hosts to complete their profiles and verification.

---

## 📈 Dashboard Features

- Three interactive report pages.
- KPI cards for key marketplace metrics.
- City-wise listing and market-share analysis.
- Room-type pricing comparison.
- Overall and detailed rating analysis.
- Bookmark-based navigation.
- Review frequency and outlier analysis.
- Seasonal review pattern analysis.
- Host trust indicator analysis.
- DAX-based analytical calculations.

## 🎯 Key Learning Outcomes

Through this project, I gained practical experience in:

- Building interactive dashboards using Power BI.
- Creating DAX measures and calculated columns.
- Establishing relationships between multiple datasets.
- Using bookmarks to improve dashboard navigation.
- Analysing customer ratings and review behaviour.
- Converting raw data into meaningful business insights.
- Presenting data-driven recommendations.


## 👨‍💻 Author

**Ajay Pal**

B.Sc. (Hons.) Computer Science | PGDAV College, University of Delhi

Interested in Data Analytics, Business Intelligence and Data-Driven Decision Making.
