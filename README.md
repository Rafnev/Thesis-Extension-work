# Thesis Extension Work: Business Intelligence Tools Evaluation

[![License](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

## 📊 Project Overview

This repository contains the extension work of my thesis on evaluating and comparing three widely-used business analytics and visualization tools: **Kibana**, **JMP**, and **Power BI**. The project demonstrates practical implementations of data visualization and analytics across these platforms using a standardized sales dataset.

## 🎓 Thesis Abstract

We are living in a data-driven world where selecting the most appropriate business analytics software is crucial for a user. With a wide range of commercial and open-source BI tools available on the market, users find it difficult to position themselves to align with technical aspects, business needs, and decision-making capabilities. 

This thesis investigates these challenges by developing a structured methodology that consists of testing and decision-making pipeline to evaluate three widely used analytics tools: Kibana, JMP, and Power BI. The methodology includes a sales dataset, which is used to evaluate tools, focusing on:

- **Ease of use**
- **Interactivity**
- **Customizability**
- **Cost**
- **Third-party plugin support**

### Key Findings

The evaluation shows that **Kibana** scores higher in most evaluation criteria compared to other tools. While Kibana is the best choice for users in terms of flexibility, real-time analytics, and cost-effectiveness, **JMP** remains the best choice for statistical purposes with advanced built-in statistical features.

**Keywords:** Business Intelligence, Data Analytics, Visualization Tools, Kibana, JMP, Power BI, Competitor Profile Matrix, Data Integration

## 📁 Repository Contents

### Dataset
- **`sales_data_sample.csv`** - Sample sales dataset used across all three platforms

### Visualization Files

#### JMP Analysis
- **`sales_data_sample.jmp`** - JMP data file
- **`sales_data_sample - Graph Builder.jrp`** - JMP visualization report
- **`sales_data_sample - Graph Builder.jpg`** - Exported JMP visualization
- **`Summary of sales_data_sample grouped by YEAR_ID - Graph Builder.jrp`** - JMP yearly summary report

#### Power BI
- **`ThesisUpdate.pbit`** - Power BI template file

#### Documentation
- **`Ahmed_SyedRafi_FNAT2H.pdf`** - Complete thesis document

## 📈 Dataset Information

### Sales Data Sample

Sample sales data, including order information, sales figures, customer details, and shipping data, utilized for segmentation, customer analytics, clustering, and further analytical purposes. Motivated by retail analytics, this dataset was first utilized for Pentaho DI Kettle and later discovered by Gus Segura to be advantageous for Sales Simulation training.

**License:** CC0: Public Domain

### Dataset Structure

**Number of Columns:** 25

| Column Name | Description |
|-------------|-------------|
| `ORDERNUMBER` | Unique identifier for each order |
| `QUANTITYORDERED` | Number of items ordered |
| `PRICEEACH` | Price of each item |
| `ORDERLINENUMBER` | Line number of the order |
| `SALES` | Total sales amount for the order |
| `ORDERDATE` | Date when the order was placed |
| `STATUS` | Status of the order (e.g., Shipped) |
| `QTR_ID` | Quarter in which the order was placed |
| `MONTH_ID` | Month in which the order was placed |
| `YEAR_ID` | Year in which the order was placed |
| `PRODUCTLINE` | Product line of the ordered items |
| `MSRP` | Manufacturer's Suggested Retail Price |
| `ADDRESSLINE1` | Primary address line |
| `ADDRESSLINE2` | Secondary address line (may contain missing values) |
| `CITY` | City name |
| `STATE` | State/Province (may contain missing values) |
| `POSTALCODE` | Postal/ZIP code |
| `COUNTRY` | Country where the order was shipped |
| `TERRITORY` | Sales territory |
| `CONTACTLASTNAME` | Customer's last name |
| `CONTACTFIRSTNAME` | Customer's first name |
| `DEALSIZE` | Size of the deal (Small, Medium, Large) |

### Data Characteristics

- **Data Types:** Mixed - numeric, categorical, and date fields
- **Missing Values:** Some columns like `ADDRESSLINE2` and `STATE` may have missing values (NaN)
- **Use Cases:** Segmentation, customer analytics, clustering, sales forecasting, and trend analysis

## 🛠️ Tools Evaluated

### 1. Kibana
- **Type:** Open-source
- **Strengths:** Real-time analytics, flexibility, cost-effectiveness
- **Use Case:** Log and time-series data analysis, real-time dashboards

### 2. JMP
- **Type:** Commercial (SAS)
- **Strengths:** Advanced statistical analysis, built-in statistical features
- **Use Case:** Statistical modeling, scientific research, quality control

### 3. Power BI
- **Type:** Commercial (Microsoft)
- **Strengths:** Microsoft ecosystem integration, user-friendly interface
- **Use Case:** Business reporting, enterprise analytics

## 🚀 Getting Started

### Prerequisites

To work with the files in this repository, you'll need:

- **JMP** (version 14 or higher) for `.jmp` and `.jrp` files
- **Power BI Desktop** for `.pbit` files
- **Kibana** (version 7.x or higher) for Elasticsearch-based visualizations
- Any CSV reader/editor for the dataset

### Using the Dataset

1. **For JMP:** Open `sales_data_sample.jmp` directly or import `sales_data_sample.csv`
2. **For Power BI:** Open `ThesisUpdate.pbit` and connect to the data source
3. **For Kibana:** Import `sales_data_sample.csv` into Elasticsearch and create visualizations

## 📊 Evaluation Methodology

The thesis employs a structured methodology with the following components:

1. **Dataset Selection:** Identical dataset implementation across all platforms
2. **Testing Pipeline:** Standardized testing procedures for each tool
3. **Evaluation Criteria:**
   - Ease of use
   - Interactivity
   - Customizability
   - Cost analysis
   - Third-party plugin ecosystem
4. **Decision-Making Framework:** Competitor Profile Matrix for tool comparison

## 📝 Citation

If you use this work or dataset in your research, please cite:

```
Ahmed, Syed Rafi (2024). Business Intelligence Tools Evaluation: 
A Comparative Study of Kibana, JMP, and Power BI. 
[Thesis]. Available at: https://github.com/Rafnev/Thesis-Extension-work
```

## 📄 License

- **Dataset:** CC0: Public Domain
- **Thesis Work:** © Syed Rafi Ahmed

## 👤 Author

**Syed Rafi Ahmed (Rafnev)**

- GitHub: [@Rafnev](https://github.com/Rafnev)

## 🔗 Related Resources

- [Full Thesis PDF](./Ahmed_SyedRafi_FNAT2H.pdf)
- [Sales Dataset (CSV)](./sales_data_sample.csv)

## 📧 Contact

For questions or collaborations, please open an issue in this repository.

---

**Note:** This project is part of academic research and provides a practical decision-making framework for users to choose the appropriate BI tools based on their specific needs.
