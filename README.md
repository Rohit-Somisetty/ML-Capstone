# ML Capstone 1 - E-Commerce Customer Segmentation

## Project Overview
This project analyzes a UK-based e-commerce dataset to segment customers using unsupervised machine learning. The goal is to enable targeted marketing and product recommendations by understanding customer behavior and purchasing patterns.

## Objectives
- Clean and preprocess transactional data
- Engineer customer-centric features (RFM)
- Perform exploratory data analysis (EDA)
- Segment customers using K-Means clustering
- Analyze and profile customer segments
- Build a simple recommendation system for each segment

## Dataset
- **Source:** UCI Machine Learning Repository (Online Retail dataset)
- **File:** `ecommerce_data.csv`
- **Features:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Project Structure
- `ML_Capstone_1.ipynb`: Main Jupyter notebook with all code, analysis, and results
- `ecommerce_data.csv`: Raw dataset
- `README.md`: Project documentation

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Rohit-Somisetty/ML-Capstone.git
   ```
2. Install dependencies (recommended: use Anaconda):
   ```bash
   conda install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open `ML_Capstone_1.ipynb` in Jupyter Notebook or VS Code and run all cells in order.

## Key Steps
- **Data Loading & Cleaning:** Handle missing values, duplicates, outliers, and cancelled orders.
- **Feature Engineering:** Create RFM (Recency, Frequency, Monetary) and other features.
- **EDA:** Visualize top products, countries, and sales trends.
- **Clustering:** Use KMeans and PCA for customer segmentation.
- **Cluster Analysis:** Profile clusters and visualize with scatter plots.
- **Recommendations:** Suggest top products to each customer segment.

## Results
- Customers are segmented into distinct groups based on purchasing behavior.
- Each segment can be targeted with specific marketing strategies and product recommendations.

## Next Steps
- Tune the number of clusters (k) for optimal segmentation.
- Further analyze clusters for actionable business insights.
- Deploy the recommendation system or integrate with marketing tools.

## References
- [UCI Machine Learning Repository - Online Retail Data Set](https://archive.ics.uci.edu/ml/datasets/online+retail)
- [scikit-learn documentation](https://scikit-learn.org/stable/)
- [pandas documentation](https://pandas.pydata.org/)

---

*Project by Rohit Somisetty*
