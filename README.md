 Employee Turnover Prediction Model

This project aims to predict employee turnover in a company using machine learning. The model uses various features related to employee demographics, job role, performance, and satisfaction to determine the likelihood of an employee leaving the company.

## Project Structure

1. **Data Preprocessing**:
   - Load the data and handle missing values, if any.
   - Encode categorical variables such as 'BusinessTravel', 'Department', etc.
   - Split data into training and test sets.

2. **Model Training**:
   - Train a predictive model using Logistic Regression or Random Forest Classifier.
   - Evaluate the model on test data using accuracy, precision, recall, and F1-score.

3. **Evaluation**:
   - Generate and visualize the model’s performance metrics.
   - Feature importance analysis to identify the most influential factors.

## Dataset

- The dataset, `HR-Employee-Attrition.csv`, contains information on various employee attributes, such as Age, JobRole, MonthlyIncome, and Attrition status (Yes/No).

## Prerequisites

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Usage

1. **Install Dependencies**:
   ```
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

2. **Run the Model Script**:
   - Ensure the dataset is in the same directory as the script.
   - Run the script to preprocess data, train the model, and evaluate it.

3. **Output**:
   - The script outputs the model’s accuracy and displays feature importance to help interpret which features influence attrition.

## Key Features

- **Age**: Age of the employee.
- **JobRole**: Job role of the employee within the company.
- **MonthlyIncome**: Monthly income of the employee.
- **YearsAtCompany**: Number of years the employee has worked at the company.
- **JobSatisfaction**: Self-reported job satisfaction level.

## Example Results

The model achieves around **85% accuracy** on the test set with features like 'JobRole', 'MonthlyIncome', and 'WorkLifeBalance' significantly contributing to predictions.

## License

This project is licensed under the MIT License.
