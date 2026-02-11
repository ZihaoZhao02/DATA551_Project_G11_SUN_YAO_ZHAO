# Mercedes-Benz Sales Insights Dashboard (2020–2025)

## 1. Motivation and Purpose
We are a team of data science students. We aim to explore how vehicle types and configurations impact the sales performance of cars in global markets. As hybrid and electric power technologies gain increasing popularity, automakers need further insights into which combinations of fuel type, pricing, and horsepower best meet consumer demand. Understanding the relationships between these factors and sales volume can help support more informed decisions in inventory planning, product strategy, and market positioning. To achieve this, we utilize a large and comprehensive dataset of Mercedes-Benz vehicle sales from 2020 to 2025 from Kaggle. This dataset allows us to analyze how combinations of different fuel types, horsepower, turbo configurations, and price ranges influence vehicle sales performance. By studying these patterns, we aim to reveal the relationship between product characteristics and market demand, thereby gaining meaningful insights.

In this project. we aim to develop an interactive dashboard that enable users to explore automotive sales data. The dashboard helps users identify which vehicles perform best in the market and determine which aspects consumers prioritize when selecting vehicles (e.g. Color, Turbo).It also track shifts in demand for electric and hybrid vehicles to help automakers decide whether to increase R&D and production budgets for these powertrains. By analyzing dashboard data, users and dealers can make more informed strategic market decisions.

## 2. Description of the Data
This dataset covers Mercedes-Benz vehicle sales from 2020 to 2025. Created for educational and analytical purposes, it accurately reflects typical characteristics of the automotive market, including electrification, price evolution, and performance variations across different vehicle models. While not official Mercedes-Benz sales records, the dataset strives for high consistency with real automotive sales data in both scale and variable design.

### Dataset Size and Structure

The dataset contains approximately **1.8 million rows**, where each row represents **one vehicle sold**. It includes **9 main columns** describing vehicle characteristics, performance attributes, and sales-related information. There are no missing values.

### Variables Overview

| Feature | Data Type | Description |
|----------|-----------|-------------|
| **Model** | Categorical | Mercedes-Benz model name (e.g., A-Class, GLC, AMG S 63) |
| **Year** | Numeric (Discrete) | Year of sale (2020–2025) |
| **Region** | Categorical | Geographic area (currently fixed to "Global") |
| **Color** | Categorical | Exterior vehicle color |
| **Fuel Type** | Categorical | Powertrain type: Petrol, Diesel, Hybrid, Electric |
| **Base Price (USD)** | Numeric (Continuous) | Approximate base retail price (includes mild annual inflation trend) |
| **Horsepower** | Numeric (Continuous) | Engine power output (reflects performance differences) |
| **Turbo** | Binary (Categorical) | Indicates whether the vehicle has a turbocharged engine (Yes / No) |
| **Sales Volume** | Numeric (Constant = 1) | Each row represents one vehicle sold |

### Key Characteristics of the Dataset

The dataset captures several important structural patterns in the automotive market:

- Growth in electric and hybrid vehicles over time  
- Differences in sales performance across models and fuel types  
- Variation in pricing and engine performance characteristics  
- Stable consumer preferences for certain colors and vehicle segments  

## 3. Research Questions
