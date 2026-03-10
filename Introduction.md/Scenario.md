---
title: Objectives
parent: Introduction
nav_order: 3
---

# Scenario

A global company wants to improve its sales analytics capabilities by building a unified data and analytics solution.

The company currently stores operational sales data including:

- Sales orders
- Customer information
- Product materials

However, business users need better insights into:

- Revenue trends over time
- Customer performance across regions
- Product sales performance
- High-value transactions
- Customer segmentation

To address this challenge, the analytics team builds an analytics solution using SAP Business Data Cloud.
First, operational sales datasets are ingested into **SAP Datasphere**, where the team builds a semantic data model consisting of fact and dimension views. These datasets are connected using associations to create a structured analytical model.
At the same time, customer account data from **Salesforce** is ingested into **SAP Databricks**, where it is prepared and processed. The enriched dataset is then shared as a data product using **Delta Sharing**.
Next, an **Analytic Model** is created to expose business measures such as revenue, discounts, and order metrics together with the enriched customer attributes.
The analytic model is then consumed in **SAP Analytics Cloud**, where an interactive sales analytics dashboard is created with KPIs, charts, tables, and geo maps.
This integrated approach enables business users to analyze sales performance together with enriched customer attributes such as account type, industry, quality score, and customer segment, providing deeper insights into customer behavior and supporting data-driven decision making.