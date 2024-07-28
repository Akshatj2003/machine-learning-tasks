Task 1: Predicting Aggregate Ratings
This project focuses on predicting aggregate ratings based on features such as Cuisines and Locality. It includes data preprocessing, encoding categorical variables, model training, evaluation, and visualization of predictions from different regression models.

Overview
The project involves the following key steps:

Data Loading and Preprocessing: Load the dataset, clean it by removing missing values, and prepare it for analysis.
Encoding Categorical Variables: Convert categorical features into numerical format using One-Hot Encoding to make them suitable for machine learning models.
Splitting Data: Split the dataset into training and testing sets to train and evaluate the models.
Training and Evaluating Models: Train Linear Regression and Decision Tree models on the training data, then evaluate their performance using metrics such as Mean Squared Error (MSE) and R-squared.
Visualizing Predictions: Generate predictions for new data and visualize them to compare the performance of the models.
Requirements
To run this project, you need the following Python packages:

pandas: For data manipulation and analysis.
scikit-learn: For machine learning algorithms and metrics.
matplotlib: For plotting and visualizations.
You can install these packages using pip:


pip install pandas scikit-learn matplotlib
Dataset
The dataset used for this project should be named Dataset.csv and must be placed in the path specified in the script. It should contain the following columns:

Cuisines: A categorical feature representing the type of cuisine.
Locality: A categorical feature representing the location.
Aggregate rating: The target variable representing the rating to be predicted.
Ensure that the dataset file is correctly formatted and located in the specified directory.

Usage
Follow these steps to execute the project:

Clone the Repository:


git clone https://github.com/yourusername/your-repository.git
Navigate to the Project Directory:


cd your-repository
Place the Dataset:

Make sure that Dataset.csv is located in the directory specified in the script.

Run the Script:

Execute the script to process the data, train models, and visualize results:



Code Explanation
1. Data Loading and Preprocessing
The script begins by loading the dataset from a specified file path. Missing values are removed to ensure the dataset is clean and ready for analysis. This step is crucial for avoiding errors and inaccuracies in the modeling process.

2. Encoding Categorical Variables
Categorical features, Cuisines and Locality, are transformed into numerical format using One-Hot Encoding. This method converts each category into a binary vector, enabling the machine learning models to process the data. Each category is represented by a new column with binary values.

3. Splitting Data
The dataset is split into training and testing sets. The training set is used to fit the models, while the testing set is used to evaluate their performance. This separation helps in assessing how well the models generalize to new, unseen data.

4. Training and Evaluating Models
Linear Regression:

A Linear Regression model is trained on the training data.
The model’s performance is evaluated using Mean Squared Error (MSE) and R-squared metrics.
The coefficients of the model are examined to understand the importance of different features.
Decision Tree Regressor:

A Decision Tree Regressor model is trained similarly.
Its performance is evaluated using MSE and R-squared, and cross-validation is used to assess its stability and generalization across different data subsets.
5. Visualizing Predictions
Predictions are made for new data samples using both models. The results are visualized in plots to compare how each model performs. This helps in understanding the differences in predictions between the Linear Regression and Decision Tree models.

Results
Upon running the script, you will obtain:

Performance Metrics: MSE and R-squared values for both Linear Regression and Decision Tree models.
Visualizations: Plots comparing the predicted values from both models, which provide insights into their comparative performance.
