# eCommerce_Transactions_Analysis

# eCommerce Transactions Analysis

## Overview
This project involves analyzing eCommerce transactions using a dataset consisting of customer profiles, product details, and transaction history. The tasks include:
1. **Exploratory Data Analysis (EDA)**: Understanding the dataset and deriving actionable business insights.
2. **Lookalike Model**: Building a recommendation system to find similar customers based on profile and transaction history.
3. **Customer Segmentation**: Clustering customers into meaningful groups using transaction and demographic data.

## Dataset
The dataset comprises three files:
- **Customers.csv**: Customer demographic details.
- **Products.csv**: Product details, including category and price.
- **Transactions.csv**: Records of transactions made by customers.

## Deliverables
- **Task 1: Exploratory Data Analysis (EDA)**
  - A detailed analysis with visualizations and insights.
  - File names: 
    - `Kaniyamudhan_Y_EDA.ipynb`
    - `Kaniyamudhan_Y_EDA.pdf`

- **Task 2: Lookalike Model**
  - A recommendation system identifying the top 3 similar customers for the first 20 customers.
  - File names: 
    - `Kaniyamudhan_Y_Lookalike.ipynb`
    - `Kaniyamudhan_Y_Lookalike.csv`

- **Task 3: Customer Segmentation**
  - Customer clusters with evaluation metrics and visualizations.
  - File names: 
    - `Kaniyamudhan_Y_Clustering.ipynb`
    - `Kaniyamudhan_Y_Clustering.pdf`

## Repository Structure
eCommerce_Transactions_Analysis/ ├── Task_1_EDA/ │ ├── Kaniyamudhan_Y_EDA.pdf │ └── Kaniyamudhan_Y_EDA.ipynb ├── Task_2_Lookalike/ │ ├── Kaniyamudhan_Y_Lookalike.csv │ └── Kaniyamudhan_Y_Lookalike.ipynb ├── Task_3_Clustering/ │ ├── Kaniyamudhan_Y_Clustering.pdf │ └── Kaniyamudhan_Y_Clustering.ipynb ├── data/ │ ├── Customers.csv │ ├── Products.csv │ └── Transactions.csv └── README.md


## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/eCommerce_Transactions_Analysis.git
2. Navigate to the folder:
   ```bash
    cd eCommerce_Transactions_Analysis
3. Open the respective Jupyter Notebook files:
   Task_1_EDA/Kaniyamudhan_Y_EDA.ipynb
   Task_2_Lookalike/Kaniyamudhan_Y_Lookalike.ipynb
   Task_3_Clustering/Kaniyamudhan_Y_Clustering.ipynb
4. Run each notebook to explore the results.

Insights Summary
EDA Insights:
Key trends and patterns in customer transactions.
Popular products and high-spending regions.
Lookalike Model:
Identifies similar customers based on demographic and transaction features.
Clustering:
Groups customers into segments to optimize marketing strategies.

Dependencies
Python 3.8+
Libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy

Install dependencies using:
```bash
pip install -r requirements.txt
