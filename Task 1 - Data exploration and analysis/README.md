# Task 1: Quantiun data analysis

## Description

This repository contains the client's transactions dataset and The goal of the analysis was to explore purchasing patterns, customer segmentation, brand preferences, and packaging sizes, as well as identify marketing opportunities and pricing strategies

## The files

**Data files**:
- `QVI_transaction_data.xlsx`: Transaction data.
- `QVI_purchase_behaviour.csv`: Customer purchase behavior data.
- `data`: Customer and Transaction data merged after the data preparation

**Notebooks**:
- Task 1 - Data exploration.ipynb: Notebook that contains exploratory analysis and data preparation
- Task 1 - Data Analysis.ipynb: Notebook with the detailed analysis.

## Analysis Steps
**Data Preparation:**
- Loaded and cleaned transaction and customer data.
- Handled dates, removed non-chip products, and addressed outliers.

**Exploratory Analysis:**
- Analyzed packaging sizes and popular brands.
- Segmented customers by life stage and premium status.

**Sales and Preferences:**
- Calculated sales by segment and visualized trends.
- Identified top brands and average prices per segment.

**Affinity and Insights:**
- Used Apriori for product associations.
- Derived key insights for marketing and pricing strategies.

## Key Insights
**Segments with Highest Sales:**
- The `Budget - Older Families`, `Mainstream - Young Singles/Couples`, and `Mainstream - Retirees` segments dominate sales.
- `Young singles/couples` and `retirees` have a larger number of customers, while older families purchase more chips per customer.

**Brand Preferences:**
- Brands such as "Tostitos Splash Of Lime 175g" and "Kettle Mozzarella Basil & Pesto 175g" are favorites among young singles/couples.

**Packaging Sizes:**
- The most purchased sizes are 175g, 150g, and 134g.

**Pricing:**
- `Mainstream - Midage` and `Young Singles/Couples` customers are willing to pay higher prices per chip pack.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy
- Openpyxl
- Mlxtend (for affinity analysis)

## Contributions
Contributions are welcome! Feel free to open issues or pull requests for code or analysis improvements.

