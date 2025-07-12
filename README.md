🎬 Netflix Country Clustering Using K-Means

This project performs unsupervised clustering of countries based on Netflix pricing tiers and content library sizes. The goal is to discover patterns in how Netflix structures its offerings across regions and segment countries into meaningful groups.



📌 Project Overview

- ✅ **Type**: Data Science / Unsupervised Learning  
- 🧠 **Algorithm**: K-Means Clustering  
- 📊 **Tech Stack**: Python, Pandas, Scikit-Learn, Matplotlib, Seaborn, PCA  
- 📁 **Dataset**: [Netflix Subscription Prices by Country - Kaggle](https://www.kaggle.com/datasets/prasertk/netflix-subscription-price-in-different-countries)



🔍 Objective

To group countries into clusters based on:
- Total Library Size
- Number of Movies and TV Shows
- Monthly Cost of Basic, Standard, and Premium Plans

This helps in:
- Identifying pricing patterns
- Market segmentation
- Business insights for global OTT strategy



🧪 Process

1. **Data Cleaning**: Removed irrelevant columns and handled missing values  
2. **Feature Scaling**: Standardized numeric columns for clustering  
3. **Elbow Method**: Found optimal number of clusters (k = 5)  
4. **K-Means Clustering**: Applied clustering to segment countries  
5. **PCA Visualization**: Reduced to 2D and visualized the clusters  
6. **Interpretation**: Analyzed cluster behavior across pricing and library size



 📸 Visualizations

- 📈 Elbow Curve to select `k`
- 🎯 PCA Scatter Plot of Clusters
- 📊 Bar Graph showing average pricing and content per cluster and scatter plot



🧠 Key Learnings

- How to use **KMeans** for market segmentation
- Dimensionality reduction using **PCA**
- Interpreting cluster insights in real-world context
- Building clean, scalable data pipelines



💡 Potential Extensions

- Deploy an interactive Streamlit app  
- Add real-time clustering based on user input  
- Compare with hierarchical/agglomerative clustering  
- Use clustering for personalized pricing models



📁 How to Run

```bash
1. Clone this repo
2. Install dependencies (pandas, scikit-learn, matplotlib, seaborn)
3. Run the notebook `netflix_clustering.ipynb`
4. Explore results and plots!
