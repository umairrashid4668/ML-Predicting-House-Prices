# Predicting House Prices using Multiple Linear Regression

## Objective
The objective of this project is to implement a Multiple Linear Regression model to predict house prices based on key features such as square footage, number of bedrooms, and the age of the house.

## Dataset
The dataset used in this project includes the following features:
- **Square Footage**: The total square footage of the house.
- **Number of Bedrooms**: The number of bedrooms in the house.
- **House Age**: The age of the house in years.
- **House Price**: The target variable representing the price of the house.

## Data Exploration
Initial data exploration includes:
- **Descriptive Statistics**: Summarizing the key statistics of the dataset.
- **Correlation Matrix**: To identify relationships between the features and the target variable.
- **Visualizations**: Histograms and scatter plots to visualize the distribution of the features and their relationships with the house prices.

## Model Implementation
The project utilizes a Multiple Linear Regression model to predict house prices. The model is built using the following steps:
1. **Data Preprocessing**: Handling missing values, encoding categorical variables (if any), and splitting the data into training and testing sets.
2. **Model Training**: Training the Multiple Linear Regression model on the training data.
3. **Model Evaluation**: Evaluating the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) score.

## Results
The model's performance is evaluated on the test set, and the results indicate the accuracy of the predictions.

## Conclusion
This project demonstrates how a Multiple Linear Regression model can be used to predict house prices based on various features. The model provides a reasonable prediction accuracy, but further improvements can be made by incorporating additional features or using more advanced regression techniques.

## Future Work
Potential areas for improvement include:
- Adding more features such as location, amenities, etc., to improve the model's predictive power.
- Experimenting with other regression techniques such as Ridge Regression, Lasso Regression, or Decision Trees.
- Fine-tuning the model's parameters to optimize performance.

## Dependencies
The following Python libraries are required to run the notebook:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## How to Run
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd <project-directory>`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the Jupyter Notebook: `jupyter notebook ML_Assignment1.ipynb`




