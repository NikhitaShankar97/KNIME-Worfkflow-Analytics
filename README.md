# KNIME Workflow Analytics

## Project Overview
This project leverages KNIME, a powerful visual workflow platform, to analyze:
1. **Yelp Data**: Identifying factors driving positive restaurant reviews.
2. **BONK Trading Patterns**: Exploring trading behaviors of top traders on the Solana blockchain.

The workflows aim to extract actionable insights using KNIME's nodes for data preprocessing, analysis, and visualization.

---

## Workflows
### **1. Yelp Positive Reviews Analysis**
**Objective:** Identify factors contributing to high ratings on Yelp for restaurants.  
**Key Insights:**
- Top cuisines like **Mexican**, **Greek**, and **Brazilian** receive the highest average ratings.
- Positive reviews frequently mention **Food**, **Service**, and **Atmosphere** as significant factors.
- Detailed reviews (550-600 characters) tend to correlate with higher ratings.

**Nodes Used:**
- Data Preprocessing: `Column Filter`, `Rule-Based Row Filter`, `Sorter`.
- Text Analysis: `Strings to Document`, `Word Cloud`, `TF Calculation`.
- Visualization: `Bar Chart`, `Scatter Plot`, `Line Plot`.

**Workflow File:**  
Download the workflow directly from the **KNIME Hub**:  
[**YELP Positive Reviews Workflow**](https://hub.knime.com/s/A3IzZcc0AMaOpPFI)

---

### **2. BONK Trading Patterns Analysis**
**Objective:** Explore trading behavior and efficiency of top traders in the BONK ecosystem.  
**Key Insights:**
- Top 10 traders dominate trading volume, with the highest contributor accounting for **21%** of total activity.
- Activity peaks during specific hours, highlighting temporal trading patterns.
- Direct trading on Solana is the preferred method for the majority of trades.

**Nodes Used:**
- Data Preprocessing: `Joiner`, `GroupBy`, `Date&Time Extractor`.
- Visualization: `Heatmap`, `Pie Chart`, `Line Plot`.

**Workflow File:**  
Download the workflow directly from the **KNIME Hub**:  
[**BONK Trading Patterns Workflow**](https://hub.knime.com/s/wVIL4YvC18vDASCL)

