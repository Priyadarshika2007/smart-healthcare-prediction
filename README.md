# Smart Healthcare Prediction System using Machine Learning

## Description
This project is a beginner-friendly data science workflow that predicts a healthcare target value using Logistic Regression. It demonstrates how to clean real-world style data, handle missing values, filter records, study feature relationships, and train a machine learning model.

## Features
- Sample healthcare dataset in CSV format
- Data cleaning with duplicate removal and mean-based NaN handling
- Data filtering for patients with age greater than 40
- Correlation analysis across numeric healthcare features
- Logistic Regression model training and prediction
- Correlation heatmap visualization

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## How to Run
1. Open a terminal in the project root folder.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python script:
   ```bash
   python src/main.py
   ```
4. Open and run the notebook:
   - File: `notebook/healthcare.ipynb`
   - Run cells in order from top to bottom.

## Output Description
- The notebook shows each step of the analysis:
  - Loading and previewing data
  - Cleaning and filtering
  - Correlation matrix and heatmap
  - Model training and predictions
- The `main.py` script prints the predicted target for sample input `[50, 220, 130, 80]`.
