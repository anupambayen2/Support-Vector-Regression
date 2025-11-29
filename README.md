Project Summary: Salary Prediction Using Support Vector Regression (SVR)

This project uses Support Vector Regression (SVR) to predict an employee’s salary based on their position level. It is part of my daily machine learning practice uploads on GitHub.

📌 Objective

To build a regression model that can handle non-linear salary trends using Support Vector Machines with kernel functions.

📊 Dataset

The dataset (Position_Salaries.csv) contains:

Position

Level (1–10)

Salary

This dataset has a non-linear relationship, making it suitable for kernel-based regression methods.

🛠️ Steps Performed

Loaded and explored the dataset

Applied feature scaling (important for SVR)

Trained an SVR model using the RBF kernel

Compared predictions with actual salary values

Visualized the SVR regression curve

Predicted salary for a specific level (e.g., 6.5)

📈 Key Insight

SVR with the RBF kernel captures the non-linear relationship more effectively than simple linear models.

Feature scaling significantly improves the model's performance.

SVR produces smooth curves ideal for small datasets with non-linear patterns.

🧪 Outputs

SVR regression curve

Scatter plot of actual salary data

Model predictions

Predicted salary value for a chosen level

🚀 Conclusion

Support Vector Regression is a powerful model for capturing complex, non-linear patterns in small datasets. Unlike linear regression, SVR finds a flexible boundary that best fits the data while controlling error margins.
