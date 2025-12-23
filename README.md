# Comparative and Trend Analysis of Agricultural Export Values (2021–2023)

## 📌 Project Overview
This project conducts a comprehensive statistical and multivariate analysis of **agricultural export values from 2021 to 2023**. The study focuses on identifying **regional differences, temporal trends, seasonal variations, and structural patterns** in export performance across countries.

Special emphasis is placed on comparing **Gulf Cooperation Council (GCC)** countries with **non-Gulf countries**, analyzing **item-specific trends**, and uncovering latent structures in export profiles using **dimensionality reduction and clustering techniques**.

The findings aim to support **trade policy formulation, economic planning, and market forecasting**.

---

## 🎯 Research Problem
Agricultural exports play a critical role in economic stability and food security. However, export patterns can vary significantly across regions, time periods, and product categories.

This study investigates:
- Differences in export values between **Gulf and non-Gulf countries**
- **Temporal trends** across years and seasons
- **Item-specific growth and decline patterns**
- **Country-level similarities** based on export structures

---

## ❓ Research Questions & Methods

| Research Question | Statistical / Analytical Method |
|------------------|---------------------------------|
| Is there a significant difference in mean export **VALUE** between Gulf and non-Gulf countries? | Wilcoxon Rank-Sum Test |
| Does export **VALUE** vary significantly across years (2021–2023)? | Kruskal–Wallis Test |
| Does the export **VALUE of Dates** vary across seasons in Gulf countries? | Kruskal–Wallis Test |
| Which agricultural items show significant growth or decline over time? | Spearman’s Rank Correlation |
| Can export profiles be reduced into fewer meaningful dimensions? | Principal Component Analysis (PCA) |
| How can countries be grouped based on export similarity? | K-means Clustering on PCA scores (Elbow & Silhouette validation) |

---

## 📊 Data Variables
The dataset includes:
- **Country**
- **Region (Gulf / Non-Gulf)**
- **Year (2021–2023)**
- **Month / Season**
- **Agricultural Item**
- **Export Value**


---

## 🧠 Methodology
- Non-parametric statistical tests were used due to **non-normal data distributions**
- Trend analysis employed **rank-based correlation**
- **PCA** was applied to reduce dimensionality and interpret latent export structures
- **K-means clustering** was performed on PCA scores to group countries with similar export profiles
- Model validation used **elbow and silhouette methods**

---

## 🛠️ Tools & Technologies
- **R**
  - `dplyr`, `ggplot2`, `readxl`
  - `factoextra`, `cluster`
  - `car`, `stats`
- **Quarto / R Markdown** for reporting
- **Git & GitHub** for version control

---

## 📈 Key Outputs
- Statistical test results with interpretation
- Trend visualizations across time and regions
- PCA biplots and explained variance
- Country clusters with economic interpretation
- Policy-relevant insights for agricultural trade

---

👤 Author
Rayyan Al Shereiqi
Statistics Major | Computer Science Minor
Sultan Qaboos University



