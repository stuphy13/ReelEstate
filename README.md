# ReelEstate

This repository contains a beginner-friendly machine learning project where I practice and implement linear and polynomial regression from scratch, Without using Scikit-Learn. The goal is to predict house prices using a real-world dataset.



### **Objectives**

* To practice Data Pre-processing.
* Learn to visualize data using Matplotlib.
* Data handling using Pandas.
* Correlation between variables.
* Feature Selection.
* Feature scaling using K-Scores(mean 0 and st.deviation 1)
* Understanding how the linear regression and multiple linear regression actually works. (Without using Scikit-Learn).
* Practice Gradient descent algorithm.



### Tools and Libraries Used

1. NumPy
2. Pandas
3. Matplotlib
4. Seaborn



### Workflow



#### Data Acquisition and Exploration:



* Loaded the USA\_Housing.csv dataset.
* Inspected the data for null values and duplicates.
* Used df.info() and df.describe() to understand data types and statistical distribution.
* Analyzed correlations using a heatmap.
* Used scatter plots to visualize the relationship between each feature and the target variable, "Price."
* Removed the "Address" column as it was not needed for the regression model.
* Identified Avg. Area Income, Avg. Area House Age, Avg. Area Number of Rooms, and Area Population as the key features.



#### Data Preprocessing:



* Split the DataFrame into training and testing sets (80/20 ratio).
* Used a custom function to perform Z-score standardization on the features and the target variable.
* Converted the pandas DataFrames to NumPy arrays for efficient vectorized calculations.
* Model Implementation:
* Formulated the hypothesis function for a multiple linear regression model.
* Created a vectorized cost function using Mean Squared Error (MSE).
* Developed a vectorized gradient function to compute the gradients with respect to the weights (w) and bias (b).
* Implemented a gradient descent function to iteratively update the parameters and minimize the cost.



#### Model Evaluation:



* Trained the model using the training data with an appropriate learning rate.
* Checked for convergence by analyzing the cost history.
* Used the trained model to make predictions on the testing data.
* Visualized the model's performance by plotting the predicted values against the actual values.
