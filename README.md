**# Customer Segmentation with K-Means**



This project demonstrates \*\*customer segmentation\*\* using the K-Means clustering algorithm.  

By analyzing e-commerce transaction data, we group customers into clusters based on their purchasing behavior.  

The project covers the complete workflow from data cleaning to visualization.



---



**## 📌** **Project Overview**

\- ***Objective***: Segment customers to understand purchasing patterns and enable targeted marketing strategies.  

\- ***Dataset:*** \[E-Commerce Dataset from Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  

\- ***Techniques Used:***

&nbsp; - Data cleaning and preprocessing

&nbsp; - Feature engineering (transactions, quantity, spend)

&nbsp; - Feature scaling with `StandardScaler`

&nbsp; - K-Means clustering

&nbsp; - Dimensionality reduction with PCA

&nbsp; - Cluster visualization with Seaborn/Matplotlib



---



**## 📂 Project Structure**



├── data.csv # Dataset (not included in repo, download from Kaggle)

├── Customer\_Segmentation.ipynb # Jupyter Notebook with full workflow

├── README.md # Project documentation





**---**



\## ⚙️ Steps in the Notebook

**1. Load Dataset** – Import raw transactional data.  

**2. Data Cleaning** – Remove nulls, cancelled orders, and invalid values.  

**3. Feature Engineering** – Aggregate per customer (transactions, quantity, spend).  

**4. Scaling** – Standardize features for clustering.  

**5. K-Means Clustering** – Apply clustering with 4 clusters.  

**6. Dimensionality Reduction** – Use PCA for 2D visualization.  

**7. Visualization** – Scatter plot of customer clusters.  

**8. Cluster Summary** – Mean values of features for each cluster.



**---**



**## 📊 Example Output**

**- Scatter plot** of customers in PCA space with cluster colors.  

**- Cluster summary table** showing average spend, quantity, and transactions per group.  



**---**



**## 🚀 How to Run**

**1. Clone this repository:**

   **```bash**

   **git clone https://github.com/your-username/customer-segmentation-kmeans.git**



**2. Install dependencies:**

   **pip install pandas numpy matplotlib seaborn scikit-learn**



**3. Download the dataset from Kaggle and place it in the project folder as data.csv**

   **Kaggle Link : https://www.kaggle.com/datasets/carrie1/ecommerce-data?utm\_source=chatgpt.com**



**4. Open the notebook:**

   **jupyter notebook Customer\_Segmentation.ipynb**



**5. Run all cells.**





**---**



**## References** 



1. **Kaggle E-Commerce Dataset - https://www.kaggle.com/datasets/carrie1/ecommerce-data?utm\_source=chatgpt.com**
2. **K-Means Clustering (Scikit-Learn) - https://scikit-learn.org/stable/modules/clustering.html?utm\_source=chatgpt.com#k-means**






