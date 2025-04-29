# AI_ML_Housing_LinearRegression-task3
📄 Project Description
This project applies a Linear Regression model to predict housing prices based on various features in a dataset. The dataset includes variables such as area, bedrooms, bathrooms, furnishing status, etc. The goal is to build, evaluate, and visualize a regression model's performance.

📚 Technologies Used
Python

Pandas

NumPy

Matplotlib

Scikit-learn

🛠️ Steps Performed
Import Libraries: Imported required Python libraries.

Load Dataset: Loaded Housing.csv dataset into a Pandas DataFrame.

Data Overview: Displayed the dataset’s head, info, and statistical summary.

Missing Values Check: Checked and handled missing values.

Encode Categorical Variables: Converted categorical columns into numerical form using one-hot encoding.

Feature and Target Definition: Defined independent variables (features) and dependent variable (target: price).

Train-Test Split: Split the dataset into training and testing sets (80%-20%).

Model Training: Trained a Linear Regression model.

Prediction: Predicted housing prices on the test dataset.

Evaluation: Evaluated the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.

Visualization: Plotted actual vs predicted housing prices.

📈 Model Evaluation Metrics
Mean Absolute Error (MAE): Measures average magnitude of errors.

Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.

R² Score: Indicates how well data points fit the model.

📊 Result Visualization
Scatter plot of Actual vs Predicted Prices.

Line showing perfect prediction for comparison.
