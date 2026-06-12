Exploratory data analysis with sales data - IDEAS-TIH Summer Internship 2026
# PROJECT:
Sales Data Analysis & Digit Image Clustering
Internship project covering exploratory data analysis on retail sales data and unsupervised machine learning (K-Means clustering) 
on the Scikit-learn digits (MNIST-style) dataset.
# DATASETS:
the dataset used in this project is sales.csv (uploaded)
# KEY LIBRARIES USED:
- **Pandas** – data loading, grouping, aggregation, date handling
- **NumPy** – numerical operations (`bincount`, `argmax`)
- **Scikit-learn** – dataset loading, K-Means clustering, F1 score evaluation
# KEY RESULTS OBTAINED
- Identified top 5 and bottom 5 revenue-generating stores and their department-wise performance
- Found most stable vs. most volatile departments using coefficient of variation
- Quantified holiday impact on overall and department-wise sales
- Detected seasonal sales peaks and troughs by month
- Ranked store-department combinations by % contribution to total revenue
- Achieved a macro-averaged F1 score of ~0.75–0.80 for K-Means clustering on digit images after label mapping
