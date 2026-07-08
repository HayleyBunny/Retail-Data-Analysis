# Retail Sales Analysis

**Tools Used:** Python, pandas, matplotlib, seaborn, sklearn

**Dataset:** [Retail Store Product Sales Dataset – Kaggle](https://www.kaggle.com/datasets/ranaghulamnabi/retail-store-product-sales-dataset-analysis)

---

## Purpose

This notebook identifies retail trends within an anonymous client's transaction data. The client has an interest in understanding consumer shopping habits in order to increase profit and customer satisfaction by adhering to shopping tendencies, informing marketing decisions, and supporting planning with quality data evidence.

---

## Approach

The first steps taken were to understand the dataset and ensure it was of sufficient quality for analysis. This involved checking for anomalies, missing values, duplicate records, and incorrect inputs, as well as converting column formats for easier usage. Initial visualisations were produced to explore sales trends by month and product category. From there, EDA was completed across key demographics including age and gender. Following these findings, the elbow method was used to determine the optimal number of clusters for K-Means clustering. The data was then scaled and fitted to the model, with results plotted on a scatter graph.

---

## Findings

A spending peak in May was the first trend identified. This was later re-verified using standard deviation, confirming May sits 1.9 standard deviations above the mean monthly revenue — a notable but not conclusive result given the single year of data available.

In terms of product category, electronics dominated revenue while clothing and electronics were the leading categories for quantity purchased.

The 40–54 age bracket was identified as the highest revenue group, generating £146,330 in total — approximately £23,000 more than Young Adults (18–29) at £123,155. Middle-aged customers also led in total units purchased and total transactions.

Gender analysis showed females dominated both revenue (£232,840 vs £223,160) and quantity across most age bands. Notably, middle-aged and late middle-aged males showed a higher average order value per transaction despite females generating more total revenue — suggesting females drive volume while older males make fewer, higher-value purchases.

K-Means clustering separated customers into three distinct spending tiers spread evenly across all age groups: low (£0–500), mid (£500–1,000), and high (£1,000–2,000). Age was not a meaningful differentiator between clusters, which aligns with the earlier finding that middle-aged revenue dominance was driven by transaction volume rather than individual spend.

---

## Recommendations

To confirm and solidify these trends, data from multiple years would be necessary to determine whether the patterns observed are consistent or specific to this dataset. Without that, definitive marketing recommendations carry risk.

That said, subject to multi-year confirmation, efforts should prioritise female customers in the 40–54 age bracket — particularly in electronics — as this segment represents the highest combination of transaction volume and total revenue.
