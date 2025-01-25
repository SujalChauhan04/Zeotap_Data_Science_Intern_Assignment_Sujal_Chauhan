# Data Science Intern Assignment - Zeotap

## Overview

This repository contains my solution for the Data Science Intern assignment provided by Zeotap. The assignment involves analyzing eCommerce transaction data to derive business insights, develop a lookalike model, and perform customer segmentation using clustering techniques.

---

## Dataset Description

The dataset consists of three CSV files:

1. **Customers.csv**
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. **Transactions.csv**
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

---

## Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- **Objective**: Perform EDA to understand the dataset and derive actionable business insights.
- **Deliverables**:
  - Jupyter Notebook: `Sujal_Chauhan_EDA.ipynb`
  - PDF Report: `Sujal_Chauhan_EDA.pdf`

### Task 2: Lookalike Model
- **Objective**: Develop a lookalike model that recommends 3 similar customers for the first 20 customers (`CustomerID: C0001 - C0020`) based on their profile and transaction history.
- **Deliverables**:
  - Jupyter Notebook: `Sujal_Chauhan_Lookalike.ipynb`
  - CSV File: `Sujal_Chauhan_Lookalike.csv`

### Task 3: Customer Segmentation (Clustering)
- **Objective**: Perform customer segmentation using clustering techniques and evaluate clustering metrics such as the Davies-Bouldin Index.
- **Deliverables**:
  - Jupyter Notebook: `Sujal_Chauhan_Clustering.ipynb`
  - PDF Report: `Sujal_Chauhan_Clustering.pdf`

---

## Files in This Repository

1. **Code Files**:
   - `Sujal_Chauhan_EDA.ipynb`
   - `Sujal_Chauhan_Lookalike.ipynb`
   - `Sujal_Chauhan_Clustering.ipynb`

2. **Reports**:
   - `Sujal_Chauhan_EDA.pdf`
   - `Sujal_Chauhan_Clustering.pdf`

3. **Output Files**:
   - `Sujal_Chauhan_Lookalike.csv`

4. **Dataset**:
   - `Customers.csv`
   - `Products.csv`
   - `Transactions.csv`

---

## Instructions to Run the Code

1. Clone this repository:
   ```bash
   git clone https://github.com/<SujalChauhan04>/<Zeotap_Data_Science_Intern_Assignment_Sujal_Chauhan>.git
