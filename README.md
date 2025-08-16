# Association Rule Learning - Apriori

## 📌 Project Overview
This project demonstrates **Association Rule Learning** using the **Apriori Algorithm** on a market basket dataset (`Market_Basket_Optimisation.csv`).  
The goal is to uncover relationships between purchased items and generate association rules.

## 📂 Files
- `Market_Basket_Optimisation.csv` → Dataset containing customer transaction data.  
- `association_rule_learning_apriori.ipynb` → Jupyter Notebook implementing the Apriori algorithm.  

## ⚙️ Requirements
Install the required Python libraries before running the notebook:
```bash
pip install numpy pandas matplotlib apyori
```

## 🚀 How to Run
1. Clone the repository.  
2. Place the dataset and notebook in the same folder.  
3. Open the notebook and run all cells.  

## 📊 Key Steps
- Data Preprocessing (transforming transactions into list format).  
- Applying **Apriori** to find frequent itemsets.  
- Extracting **association rules** (support, confidence, lift).  
- Visualizing the most relevant rules.  

## 🔑 Insights
- Identifies **which products are often bought together**.  
- Helps in **cross-selling strategies** and **store layout optimization**.  
