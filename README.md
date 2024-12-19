# Medical Insurance Premium Prediction

This repository contains a Jupyter Notebook that demonstrates a complete machine learning pipeline to predict medical insurance premiums based on various factors such as age, sex, BMI, children, smoking habits, and region. The project includes data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

## Project Overview

Medical insurance premiums vary significantly based on individual characteristics. This project uses a dataset to analyze these factors and build a predictive model. The notebook aims to provide insights into the data and demonstrate a step-by-step approach to creating a machine learning solution for this problem.

## Dataset

The dataset used in this project contains the following features:
- **Age**: The age of the insured individual.
- **Sex**: Gender of the individual (male/female).
- **BMI**: Body Mass Index, a measure of body fat based on height and weight.
- **Children**: Number of children/dependents covered by the insurance.
- **Smoker**: Whether the individual smokes (yes/no).
- **Region**: The region where the individual resides (e.g., southeast, northwest).
- **Charges**: The insurance premium (target variable).

## Workflow

1. **Data Preprocessing**:
   - Handle missing values (if any).
   - Encode categorical variables (e.g., sex, smoker, region).
   - Feature scaling for numerical variables.

2. **Exploratory Data Analysis (EDA)**:
   - Statistical summaries of the dataset.
   - Visualizations to understand the relationships between features and the target variable.

3. **Model Building**:
   - Train/Test split of the data.
   - Fit regression models, such as Linear Regression and Random Forest.
   - Evaluate model performance using metrics like R-squared and Mean Squared Error (MSE).

4. **Model Evaluation**:
   - Compare the performance of different models.
   - Interpret feature importance.

## How to Use

1. Clone this repository:
   ```bash
   git clone <repository-url>
   
2. Install the required libraries:
   ```bash
    pip install -r requirements.txt
   
3. Open the Jupyter Notebook:
   ```bash
    jupyter notebook medical-insurance-prediction-94.ipynb

Run the cells step by step to replicate the analysis and predictions.

## Requirements 
Python 3.7+
Libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn

## Results
The notebook provides insights into the factors affecting medical insurance premiums and evaluates multiple machine learning models to predict the charges. Detailed results and visualizations are available within the notebook.

## Contributing
Feel free to fork this repository, make changes, and submit a pull request. Suggestions and improvements are always welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.
