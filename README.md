# 📊 Product Data Analysis & Interactive Excel Dashboard

## Overview

This project focuses on cleaning, enriching, analyzing, and visualizing product data to uncover insights into product performance, pricing strategies, discounts, ratings, and customer engagement. The final deliverable is an interactive Excel dashboard that enables users to explore key metrics and trends efficiently.

---

## 🧹 Data Cleaning

The dataset was cleaned and standardized to improve consistency and accuracy.

### Tasks Performed

* Standardized product ratings.
* Validated and formatted data fields for analysis.

---

## 🔧 Data Enrichment

Additional calculated fields were created to enhance analysis capabilities.

### New Metrics

#### 1. Absolute Discount Amount

Calculated the discount value for each product:

```text
Absolute Discount = Old Price - Current Price
```

#### 2. Rating Category

Products were classified based on their ratings:

| Rating Range  | Category  |
| ------------- | --------- |
| Below 3.0     | Poor      |
| 3.0 – 4.4     | Average   |
| 4.5 and Above | Excellent |

#### 3. Discount Category

Products were categorized according to discount percentage:

| Discount Percentage | Category        |
| ------------------- | --------------- |
| Below 20%           | Low Discount    |
| 20% – 40%           | Medium Discount |
| Above 40%           | High Discount   |

---

## 📈 Descriptive Analysis

### Overall Metrics

Calculated the following averages across all products:

* Average Current Price
* Average Old Price
* Average Discount Percentage
* Average Product Rating

### Product Pricing Analysis

* Identified the most expensive products.
* Identified the least expensive products.

### Category-Level Analysis

Calculated:

* Average Discount Percentage by Product Category
* Average Rating by Product Category

---

## 📊 Trend Analysis

### Discount vs Reviews

Analyzed the relationship between discount percentage and the number of reviews to determine whether higher discounts drive greater customer engagement.

### Rating vs Reviews

Analyzed the relationship between product ratings and review counts to determine whether highly rated products receive more reviews.

### Product Rating Rankings

Generated:

* Top 5 highest-rated products
* Top 5 lowest-rated products

---

## 🚀 Product Performance Analysis

### Top Discounted Products

Identified the:

* Top 10 products with the highest discount percentages

### Most Reviewed Products

Identified the:

* Top 10 products with the highest number of reviews

### High vs Low Discount Performance

Compared products with high discounts against products with low discounts based on:

* Average Rating
* Average Number of Reviews

---

# 📋 Interactive Excel Dashboard

## Dashboard Features

An interactive Excel dashboard was developed using:

* Pivot Tables
* Pivot Charts
* Slicers
* Conditional Formatting

---

## 📌 Key Performance Indicators (KPIs)

The dashboard displays:

* Total Number of Products
* Average Product Rating
* Average Discount Percentage
* Total Number of Reviews

---

## 📊 Dashboard Sections

### 1. Product Performance

Visualizations showing:

* Top 10 Products by Rating
* Top 10 Products by Reviews
* Top 10 Products by Discount Percentage

### 2. Trend Analysis

Charts illustrating:

* Discount Percentage vs Number of Reviews
* Product Rating vs Number of Reviews

### 3. Product Categories

Breakdown of products by:

#### Rating Categories

* Poor
* Average
* Excellent

#### Discount Categories

* Low Discount
* Medium Discount
* High Discount

---

## 📈 Visualizations Used

The dashboard incorporates:

* Bar Charts
* Line Charts
* Pie Charts

### Conditional Formatting

Used to highlight:

* High Discounts
* Low Ratings
* Other key performance indicators

---

## 🎯 Project Outcome

This analysis provides insights into:

* Product pricing strategies
* Discount effectiveness
* Customer engagement patterns
* Product performance trends
* Category-level performance

The interactive dashboard enables users to filter, explore, and compare product data for informed decision-making.
