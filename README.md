## 📁 Insurance Charges Prediction
This project was designed to estimate insurance costs for individuals based on their age, body mass index (BMI), number of children, smoking and region.

📄 Data Set Used
The data set used in this project is insurance.csv file.
It contains insurance rates of individuals by age, gender, BMI, smoking, number of children and region

📋 Project Structure
Data Analysis (EDA):
Examining and visualizing the overall structure of the data set.

Data Preprocessing:
Checking for missing data, finding outliers, scaling the data and coding categorical data.

Modeling:
Different regression models were created:
* Linear Regression
* Ridge Regression
* Lasso Regression
* Polynomial Regression

Model Evaluation:
The performance of the models was compared with the following metrics:
R² Score
Mean Square Error (MSE)

Hyperparameter Optimization:
The best model settings were found using GridSearchCV and cross-validation methods.

🔧 Technologies Used
* Python 
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn
* Scipy

📊 Example Visualizations
* Correlation Analysis
  ![Correlation](images/correlation.png)
* Actual Values vs Predicted Values
  ![Actual vs Predicted](images/actual-values-vs-predicted-values.png)
* Feature Importance
  ![Feature Importance](images/feature-importance.png)
* Error Distribution
  ![Error Distribution](images/error-distribution.png)
  
