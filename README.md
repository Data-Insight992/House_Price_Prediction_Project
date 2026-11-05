This project aims to develop a house price prediction model using supervised machine learning techniques. Here California Housing dataset is analyzed to understand data patterns, distributions, and relationships among variables. To predict house prices, three supervised learning algorithms are implemented: Linear Regression, Decision Tree Regressor, and Random Forest Regressor. The performance of each model is evaluated to determine the most accurate and reliable model.


Workflow
1. Exploratory Data Analysis — 1_EDA.ipynb
- Inspected dataset structure, data types, summary statistics, and missing values.
- Explored numerical distributions using histograms and boxplots.
- Examined relationships using Spearman correlation, scatter plots, and a scatter matrix.
- Compared median house values across ocean_proximity categories.
2. Preprocessing and Model Building — 2_ModelBuilding.ipynb
- Created income categories and used stratified sampling to split the data into 80% training and 20% test sets.
- Set median_house_value as the target.
- Imputed missing numerical values with the median and applied standard scaling.
- One-hot encoded ocean_proximity.
- Combined preprocessing steps using a Scikit-learn ColumnTransformer and Pipeline.
3. Models and Evaluation
The following regression models were trained and compared:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
Model performance was compared using 10-fold cross-validation with Root Mean Squared Error (RMSE). The notebook's conclusion identifies Random Forest Regressor as the model with the lowest error among the three evaluated models.

Deployment URL: https://house-price-4708.onrender.com
