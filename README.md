Diamond Price Prediction Using Machine Learning
-Project Overview
 This project focuses on predicting diamond prices using Machine Learning techniques. It uses the Diamond Dataset to understand how   different diamond characteristics influence their prices.
  A Linear Regression model is developed to predict diamond prices based on features such as carat, depth, table, and diamond dimensions.

*Objectives
- Analyze the diamond dataset.
- Understand the relationship between diamond features and prices.
- Perform Exploratory Data Analysis (EDA).
- Build a Machine Learning model using Linear Regression.
- Evaluate the model's prediction performance.

*Dataset Information
- Dataset: Diamonds Dataset
- Total Records: 53,940
- Total Columns: 11
- Target Variable: Price

*Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

* Project Workflow
1. Data Loading
- Imported the dataset using Pandas.
- Loaded and explored the diamond dataset.
2. Data Exploration
- Checked dataset shape and information.
- Analyzed statistical descriptions.
- Checked missing values and duplicate records.
3. Exploratory Data Analysis (EDA)
- Created a correlation heatmap.
- Studied relationships between numerical features.
4. Feature Selection
Selected the following input features:
- Carat
- Depth
- Table
- X
- Y
- Z
The target variable is Price.
5. Model Building
- Used the train-test split method.
- Split the dataset into 80% training data and 20% testing data.
- Built a Linear Regression model.
- Trained the model using Scikit-learn.
6. Model Evaluation
Evaluated the model using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
 *Model Performance
Evaluation Metric| Result
MAE| 888.48
MSE| 2,242,178.90
RMSE| 1,497.39
R² Score| 0.85895
Model Accuracy: The R² score of approximately 85.90% indicates that the model explains around 85.90% of the variation in diamond prices on the test dataset.

* Visualizations
- Correlation Heatmap
- Actual vs Predicted Diamond Price

These visualizations help understand relationships between features and evaluate the model's predictions.

*Key Findings
- Carat and diamond dimensions are important features for price prediction.
- Linear Regression provides a useful baseline for predicting diamond prices.
- The model achieved an R² score of approximately 0.859.

*Project Files
- "asli project Ml.ipynb" – Jupyter Notebook containing the complete project workflow.
- "README.md" – Project documentation.
- "diamonds.csv" – Dataset used for analysis.

* How to Run This Project
1. Clone or download this repository.
2. Install the required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
3. Open Jupyter Notebook:
jupyter notebook
4. Open "asli project Ml.ipynb".
5. Make sure the dataset path is correctly configured.
6. Run all the cells.

*Author
Asliya CP
Data Analytics Student
Skills: Python | SQL | Excel | Machine Learning | Data Analysis

⭐ If you find this project interesting, feel free to explore the notebook!
