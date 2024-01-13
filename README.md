Cost Function Predictive Model for Diastolic Blood Pressure
Linear Data
In this section, we aim to develop a predictive model for diastolic blood pressure based on total blood cholesterol levels. The synthetic data set consists of 20 patients, with cholesterol levels denoted by x and diastolic blood pressure denoted by y.

Steps:
1. Read and Split Data:
Read the data from data_chol_dias_pressure.txt and split it into two arrays, x and y.
2. Define Cost Function:
Implement a cost function g(a, b) that computes the difference between the predicted values ax + b and actual values y for all patients.
3. Gradient Descent:
Apply the gradient descent algorithm to find optimal values a* and b* that minimize the cost function.
4. Plot Results:
Plot the line y = a*x + b along with the data points.

Non-linear Data
Upon discovering manufacturing errors in the blood pressure monitor, a new, less error-prone machine was used. The updated data set is stored in data_chol_dias_pressure_non_lin.txt.

Steps:

1. Read and Split Updated Data:
2. Read the updated data from data_chol_dias_pressure_non_lin.txt and split it into arrays x and y.
3. Apply Gradient Descent:
Utilize the gradient descent algorithm on the cost function g(a, b) for the new data set to find optimal values a* and b*.
4. Plot Updated Results:
Plot the line y = a*x + b along with the data points. Assess the performance of the updated line.

Reflection:

A linear function (y = ax + b) does not fit the data’s curvature. The plotted line for a linear model on non-linear data deviates from the actual data points, leading to a less accurate representation of the underlying relationship.

We could extend the linear model to a polynomial function or exponential function by including higher-order terms (e.g., x^2). This allows the model to capture non-linear relationships by introducing curvature to the line. 

