# learning-project-1-ml-bigmart-sales-demand

This repository contains a learning project focused on predicting sales for BigMart outlets using regression techniques. The project emphasizes a clear separation between notebooks to improve workflow clarity and efficiency.

## Highlights
- **Multiple Notebooks:** Analysis, modeling, and preprocessing steps are separated into distinct notebooks for better organization and readability.
- **Preprocessing Approaches:** Includes both standard and more advanced preprocessing pipelines, allowing comparison of their impact on model performance.
- **Modeling:** Several regression models are explored, including OLS, Random Forest, Gradient Boosting, Extra Trees, Ridge, and Lasso, evaluated using MAE and R² metrics.
- **Insights & Observations:** Key findings regarding item and outlet characteristics, feature importance, and modeling limitations are documented for learning purposes.

This project serves as a practical exercise in structuring data science workflows, handling preprocessing strategies, and understanding model evaluation in a real-world sales dataset context.

learning-project-1-ml-bigmart-sales-demand/
│
├── artifacts/
│   ├── preprocess_artifacts.joblib          # Saved preprocessing pipeline
│   └── preprocess_modified1_artifacts.joblib # Alternative/modified preprocessing pipeline
│
├── data/
│   └── bigmart.csv                          # Original dataset
│
├── notebooks/
│   ├── learning-project-1-ml-bigmart-sales-demand-1-data-understanding.ipynb
│   │   # Initial data exploration and basic understanding
│   ├── learning-project-1-ml-bigmart-sales-demand-2-eda.ipynb
│   │   # Exploratory data analysis, visualizations, feature insights
│   ├── learning-project-1-ml-bigmart-sales-demand-3b-alternate-preprocess.ipynb
│   │   # Complex preprocessing pipeline (comparison purposes)
│   └── learning-project-1-ml-bigmart-sales-demand-3-preprocess-&-modeling.ipynb
│       # Standard preprocessing and modeling workflow
│
└── README.md                               # Project overview, instructions, insights
