# **Multinational Company Performance Analysis**

---

## **Table of Contents**

1. [Project Summary](#1-project-summary)  
2. [Background and Motivation](#2-background-and-motivation)  
3. [Dataset Overview](#3-dataset-overview)  
4. [Data Preparation](#4-data-preparation)  
5. [Methodology](#5-methodology)  
6. [Results and Insights](#6-results-and-insights)  
7. [Recommendations](#7-recommendations)  
8. [Conclusion](#8-conclusion)  
9. [Technical Details](#9-technical-details)  
10. [References](#10-references)  

---

## **1. Project Summary**

- **Objective:**  
  To analyse the performance of a multinational company across Europe and uncover actionable insights into revenue, sales trends, and profit margins.

- **Overview:**  
  This project uses a large dataset of 30,000 transactions to explore business performance indicators. It involves detailed data cleaning, statistical analysis, and visualization through Power BI to present insights that stakeholders can use for strategic decision-making.

- **Key Insights:**  
  - Total revenue of €15.11M with an average profit margin of 17%.  
  - Germany and the UK are the top revenue-generating countries.  
  - Peak seasonal sales occur in Q4 due to holiday shopping.

---

## **2. Background and Motivation**

- **Context:**  
  Businesses operating in multiple countries face challenges in identifying key revenue drivers and managing regional performance. This analysis provides a data-driven foundation for improving operations and revenue strategies.

- **Problem Statement:**  
  Identifying the regions and product categories that contribute most to revenue and profitability while uncovering seasonal trends to optimise inventory and marketing strategies.

- **Motivation:**  
  The project demonstrates the application of analytical techniques to solve real-world business challenges, showcasing capabilities in data handling, statistical analysis, and visualization.

---

## **3. Dataset Overview**

- **Source:**  
  - Generated dataset.

- **Description:**  
  - **Size:** 30,000 rows, 12 columns.  
  - **Key Variables:** Transaction ID, Country, City, Product Category, Revenue, Units Sold, Profit Margin, Transaction Date, Customer Segment.  

- **Data Dictionary:**  

| **Column Name**       | **Description**                             | **Data Type** | **Example Value**    |  
|------------------------|---------------------------------------------|---------------|----------------------|  
| Transaction ID         | Unique identifier for transactions         | String        | T000001              |  
| Country                | Country of transaction                     | String        | Germany              |  
| City                   | City of transaction                        | String        | Berlin               |  
| Product Category       | Product category sold                      | String        | Electronics          |  
| Revenue                | Revenue generated (€)                      | Float         | 854.67               |  
| Units Sold             | Number of units sold                       | Integer       | 59                   |  
| Profit Margin          | Profit margin (%)                          | Float         | 0.17                 |  
| Transaction Date       | Date of transaction                        | Date          | 2023-01-01           |  
| Customer Segment       | Customer type                              | String        | Retail               |  

- **Limitations:**  
  - Dataset is fictional and meant for demonstration purposes.  
  - Outliers were retained for analysis but could impact real-world applicability.

---

## **4. Data Preparation**

- **Data Cleaning:**  
  - Removed duplicates and handled missing values.  
  - Transformed `Transaction Date` into a datetime format for time-series analysis.  

- **Feature Engineering:**  
  - Extracted `Month` from `Transaction Date` to analyse seasonal trends.  

- **Data Visualization:**  
  - Initial bar and line charts were created to explore revenue distribution by country and monthly trends.

---

## **5. Methodology**

- **Approach:**  
  Data exploration, statistical analysis, and visualization techniques were applied to uncover insights. A Power BI dashboard was built to make findings accessible and interactive for stakeholders.

- **Techniques:**  
  - Correlation analysis to identify relationships between metrics.  
  - Time-series analysis to capture seasonal patterns.  

- **Tools and Libraries:**  
  - Power BI for visualization.  
  - Python (Pandas, Matplotlib, Seaborn) for data analysis.  

---

## **6. Results and Insights**

- **Key Findings:**  
  - **Total Revenue:** €15.11M.  
  - **Top Countries:** Germany (€2.1M) and UK (€1.8M).  
  - **Profit Margins:** Highest for Electronics and Sports categories.  
  - **Seasonal Trends:** Significant revenue increase in Q4 due to holiday shopping.

- **Visualizations:**  
  - Bar charts for revenue by country.  
  - Line charts for seasonal revenue trends.  
  - Tables with detailed transaction data.

---

## **7. Recommendations**

- **Actionable Steps:**  
  - Focus marketing and resources on Germany and the UK for maximum ROI.  
  - Increase inventory for Electronics and Sports categories to meet demand.  
  - Develop targeted campaigns for Q4 to capitalise on seasonal trends.  

- **Stakeholder Impact:**  
  These actions can optimise revenue and resource allocation, aligning with business objectives.

---

## **8. Conclusion**

- **Summary:**  
  This project highlights the importance of data-driven decision-making. By analysing key metrics and visualizing trends, it provides actionable insights for improving revenue and operational efficiency.

- **Future Work:**  
  Incorporate customer demographics and external market data for deeper insights. Expand the analysis to include machine learning techniques for predictive modelling.

---

## **9. Technical Details**

- **Code:**  
  - Jupyter Notebooks for EDA and statistical analysis.  
  - Scripts available in the `/notebooks` directory.  

- **Dependencies:**  
  - Python: Pandas, Matplotlib, Seaborn  
  - Power BI Desktop  

---

## **10. References**

- **Datasets:**  
  Generated dataset.  

- **Tools:**  
  Power BI, Python, GitHub.  

- **Acknowledgements:**  
  Special thanks to the open-source community for providing tools and libraries.