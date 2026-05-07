# Nike Global Catalogue Analysis

## Project Overview

This project analyzes the cleaned **Nike Global Catalogue 2026** dataset from a business analytics perspective. It explores how Nike’s product assortment, pricing, and availability differ across global markets using a single catalogue snapshot.

The project is organized as a structured analytics workflow, moving from data understanding and cleaning to business-focused analysis.

## Project Objectives

The analysis is built around three main questions:

* How does Nike’s catalog structure vary across countries?
* How do price levels and promotion patterns differ across markets?
* How does product and size availability vary across countries?

## Dataset

* **Source:** Kaggle – *Nike Global Catalogue 2026*
* **Granularity:** Product-size observations across countries
* **Snapshot type:** Single-date catalogue snapshot
* **Main focus:** Cross-market business differences in assortment, pricing, and availability

## Project Structure

### `data\\\_understanding.ipynb`

Initial exploration of the raw dataset, including:

* column inspection
* data types
* missing values
* duplicate checks
* early data quality observations

### `data\\\_cleaning.ipynb`

Data preparation and transformation, including:

* type corrections
* missing-value handling
* currency normalization
* country mapping
* treatment of inconsistent values
* preparation of the cleaned dataset for analysis

### `business\\\_analysis.ipynb`

Business analysis of the cleaned dataset, covering:

* Retail Analytics
* Price Intelligence
* Size Availability Modeling

## Main Analysis Areas

### 1\. Retail Analytics

This section examines catalog structure across markets, including:

* catalog depth by country
* category distribution
* subcategory patterns
* gender segment distribution

### 2\. Price Intelligence

This section evaluates cross-market pricing behavior, including:

* average price differences by country
* category-level price patterns
* promotion activity across markets
* price dispersion for shared products

### 3\. Size Availability Modeling

This section focuses on stock depth and fulfillment patterns, including:

* in-stock rates by country
* availability by category and subcategory
* listed versus available sizes
* size coverage differences across markets

## Key Findings

* Nike’s catalog shows clear cross-market variation in assortment breadth, pricing, and availability.
* Larger markets tend to offer broader assortments, but broader catalog depth does not always translate into stronger stock coverage.
* Price levels differ across countries and categories, with footwear generally positioned as the most premium category.
* Promotion activity is uneven across markets and product groups.
* Overall, the catalogue reflects a mix of global structure and local market adaptation.

## Tools and Libraries

* Python
* pandas
* numpy
* matplotlib

## Project Note

This project is designed as a **business analytics project**, not a forecasting project. Since the dataset represents a **single catalogue snapshot**, it is better suited for descriptive and comparative analysis than for time-based prediction.

## Author

Ammar Saab

