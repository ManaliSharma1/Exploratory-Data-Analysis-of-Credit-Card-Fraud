# 💳 Credit Card Fraud Detection – EDA

##  Overview
This project performs **Exploratory Data Analysis (EDA)** on credit card transactions to understand fraud patterns in a highly imbalanced dataset.  
The focus is on **data insights and visualization**, not model building.

##  Dataset
- **Source:** Kaggle – ULB ML Group  
- **Transactions:** 284,807  
- **Fraud Cases:** 492 (0.17%)  
- **Features:** 31  
- **Classes:**  
  - 0 → Valid  
  - 1 → Fraud  

##  Analysis Performed
- Data overview & summary statistics  
- Class imbalance analysis  
- Transaction amount comparison  
- Time-based fraud patterns  
- Feature correlation analysis  
- Key feature comparison (V14, V17, V12, V10, V3, V11)

##  Key Insights
- Fraud is extremely rare but impactful  
- Fraud transactions tend to have **lower amounts**  
- Fraud activity shows **distinct time-based spikes**  
- PCA features like **V14, V17, V12, V10** strongly separate fraud cases  

##  Tools
Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn

##  Reference
https://www.kaggle.com/mlg-ulb/creditcardfraud
