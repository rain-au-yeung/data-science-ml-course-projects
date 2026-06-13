# Customer Personality Segmentation

## Project Overview

This project applies unsupervised machine learning to segment retail customers based on demographic, behavioral, spending, and campaign-response characteristics.

The goal is to identify meaningful customer groups that can help a business design better marketing strategies, improve customer retention, and personalize promotional campaigns.

K-Means clustering was used to group customers with similar characteristics into distinct customer segments.

---

## Business Problem

Businesses often serve customers with different income levels, spending habits, purchase preferences, and marketing responsiveness. Treating all customers the same can lead to inefficient marketing campaigns and missed revenue opportunities.

This project aims to answer the following business question:

> How can customers be grouped into meaningful segments so that marketing strategies can be better targeted?

---

## Dataset

The dataset contains customer-level information, including:

- Demographics
- Income
- Education
- Marital status
- Number of children and teenagers at home
- Product spending
- Purchase channel activity
- Web visits
- Campaign responses
- Recency of purchase

The dataset file used in this project is:

```text
customer-personality-segmentation/
├── data/
│   └── Customer_Personality_Segmentation.csv
├── notebooks/
│   └── customer-personality-segmentation.ipynb
├── reports/
│   └── figures/
├── .gitignore
├── README.md
└── requirements.txt