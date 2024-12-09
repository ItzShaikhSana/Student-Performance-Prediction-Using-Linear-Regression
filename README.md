## ***Student Performance Prediction Using Linear Regression***

**Project Overview**

This project aims to predict the Performance Index of students based on various features such as the number of hours studied, previous scores, extracurricular activities, sleep hours, and sample question papers practiced. A Linear Regression model is used to develop an accurate prediction system.

**Dataset Information**

The dataset contains the following attributes:

**Feature	Description**
1. Hours Studied	Number of hours an individual has studied (numeric).
2. Previous Scores	Scores obtained by the individual in previous evaluations/tests (numeric).
3. Extracurricular Activities	Participation in extracurricular activities (yes or no) (categorical).
4. Sleep Hours	Average number of hours of sleep the individual gets daily (numeric).
5. Sample Question Papers Practiced	The number of sample question papers practiced by the individual (numeric).
6. Performance Index	Overall performance score calculated for the individual (numeric, target).
   
The dataset contains 10,000 records with no missing values.

**Objective**

The primary goal is to build a regression model to predict the Performance Index of students and identify the key factors influencing their performance.

**Project Steps**

- Data Exploration:
- Data Preprocessing:
- Model Building:
- Train a Linear Regression model on the dataset.
- Evaluate performance using metrics like R-squared, Adjusted R-squared, and RMSE.
- Model Evaluation:
- Compare with other models like Ridge and Lasso.

**Results**

***Linear Regression:***

R-squared: 0.9878

Adjusted R-squared: 0.9878

RMSE: 2.0932

The model performs well and satisfies all post-model assumptions, including no auto-correlation (Durbin-Watson: 1.992).
______________________________________________________________________________________________________________________________

#### **Technologies Used**

- **Programming Language**: Python
- 
- **Libraries:**
- 
pandas for data manipulation.

numpy for numerical computations.

matplotlib and seaborn for data visualization.

sklearn for regression modeling.

statsmodels for statistical analysis.
______________________________________________________________________--

#### **Future Work**

Test the model on additional datasets to ensure robustness.

Experiment with advanced machine learning models like Random Forest or Gradient Boosting to improve accuracy.

Deploy the model using Flask or Streamlit for real-time predictions.

**Contributing**

Contributions are welcome! Please fork the repository and submit a pull request.
________________________________________________________________________

#### **License**

This project is licensed under the MIT License.

Let me know if you'd like help customizing it further or creating any specific sections!
