Fuel Consumption Prediction using Linear Regression

**Description:**
This project aims to predict fuel consumption using linear regression techniques. It utilizes a dataset containing various attributes such as engine size, number of cylinders, and fuel consumption in combined both city and highway. The dataset undergoes preprocessing steps including handling outliers and converting categorical variables to numerical format.

**Key Steps:**

1. **Data Preprocessing:** 
   - Checked for missing values and outliers.
   - Visualized the distributions of numerical variables and identified outliers using box plots.
   - Removed outliers using the IQR method.

2. **Data Visualization:** 
   - Explored the distribution of engine size and fuel consumption.
   - Analyzed the relationship between engine size and fuel consumption.
   - Investigated average fuel consumption by vehicle class, transmission type, and fuel type.

3. **Feature Engineering:** 
   - Converted categorical variables (vehicle class, transmission, fuel type) into numerical format using one-hot encoding.
   - Removed irrelevant columns and prepared the data for machine learning.

4. **Model Building:** 
   - Split the dataset into training and testing sets.
   - Applied linear regression using both Statsmodels and scikit-learn.
   - Conducted feature selection using Recursive Feature Elimination (RFE) to identify the most significant features.

5. **Model Evaluation:** 
   - Evaluated model performance using metrics such as \( R^2 \) score and mean squared error (MSE).
   - Conducted residual analysis to assess model assumptions and check for normality.

**Technologies Used:**
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- RFE
- Scikit-learn
