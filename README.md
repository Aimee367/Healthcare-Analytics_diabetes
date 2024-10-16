# Health Care Analysis for Diabetes Prediction

### Overview
This project involves analyzing healthcare data to predict diabetes outcomes using various statistical tests and machine learning techniques. The analysis focuses on data preprocessing, balancing the dataset, and building machine learning models to predict whether an individual is diabetic based on several features like BMI, Age, and Fasting Plasma Glucose (FPG).

### Key Objectives
- Perform data cleaning and preprocessing to prepare the dataset.
- Use statistical tests (T-Test, Mann-Whitney, Levene's Test) to select significant features.
- Handle class imbalance using **SMOTE**.
- Build machine learning models (Logistic Regression, Random Forest) to predict diabetes status.
- Evaluate models based on metrics like **Accuracy**, **F1 Score**, and **Classification Report**.

### Key Features
1. **Data Preprocessing**:
   - Categorical features were encoded using label encoding.
   - Missing values were handled, and the dataset was prepared for modeling.
   
2. **Class Imbalance Handling**:
   - Applied **SMOTE** to address the imbalance in the target variable (diabetic vs. non-diabetic cases).

3. **Machine Learning Models**:
   - **Logistic Regression** and **Random Forest** were implemented to predict the diabetes status.
   - The models were evaluated based on **Accuracy**, **F1 Score**, and **Classification Reports**.

4. **Statistical Analysis**:
   - **T-Test**, **Mann-Whitney U Test**, and **Levene’s Test** were used to assess the statistical significance of features.
   
5. **Visualization**:
   - Multiple plots were created to understand the distribution of features and their relationship to diabetes status.

### Repository Structure
- `Health_Care_Analysis_AA.html`: The main analysis file containing the code and results.
- `diabetes.csv`: The dataset used for the analysis (if applicable).

### How to Run the Project
1. Clone or download this repository.
2. Install the required dependencies:
   
### Technologies Used
1) Python
2) Jupyter Notebook
3) Machine Learning: Logistic Regression, Random Forest
4) Libraries: numpy, pandas, scikit-learn, seaborn, matplotlib, imblearn
### Results
- Both models (Logistic Regression and Random Forest) performed well, with improvements in F1 score and recall for diabetic cases after applying SMOTE.
- Key features like BMI and FPG were identified as significant for predicting diabetes.
### Future Work
- Tune model hyperparameters for improved performance.
- Apply more advanced models such as XGBoost or Gradient Boosting.
- Perform additional feature engineering.
### License
This project is available for use under the MIT License.
