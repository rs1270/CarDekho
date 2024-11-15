# CarDekho

In my project, I developed a comprehensive car price prediction pipeline with the following steps:

Data Processing-
  Consolidated unstructured datasets from multiple cities into a single structured dataset with a ‘City’ column.
  Handled missing values using mean, median, or mode for numerical data and mode or new categories for categorical data.
  Standardized data formats (e.g., converted "70 kms" to integers) and encoded categorical variables (one-hot and label encoding).
  Normalized numerical features using Min-Max Scaling and removed outliers with IQR and Z-score methods.
Exploratory Data Analysis (EDA)-
  Conducted descriptive statistics and visualized data with scatter plots, histograms, and heatmaps to identify patterns.
  Selected key features based on correlation analysis, model insights, and domain knowledge.
Model Development-
  Split data (80-20) for training and testing and experimented with algorithms like Linear Regression, Random Forest, and Gradient Boosting.
Model Evaluation-
  Evaluated models using MAE, MSE, and R-squared metrics and selected the best-performing model.
Optimization-
  Improved performance with feature engineering and applied regularization (Lasso and Ridge) to avoid overfitting.
Deployment-
  Deployed the final model using Streamlit to create a user-friendly web app for real-time price predictions with robust error handling.
  This streamlined approach ensured accurate predictions and an intuitive interface for users.
