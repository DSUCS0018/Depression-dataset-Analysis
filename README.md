# Depression Classification using Machine Learning

## Project Overview
This project aims to classify depression levels based on survey responses using machine learning models. The dataset contains information such as age, gender, academic year, CGPA, and responses to several questions related to depression symptoms. The goal is to predict the depression level (Minimal, Mild, Moderate, Moderately Severe, or Severe) using this data.

## Dataset
The dataset used in this project is `Depression.csv`, which contains the following columns:

1. **Age**: Age group of the respondent.
2. **Gender**: Gender of the respondent.
3. **University**: The university where the respondent is enrolled.
4. **Department**: The department the respondent belongs to.
5. **Academic Year**: The academic year of the respondent.
6. **Current CGPA**: Current CGPA of the respondent.
7. **Survey Responses**: Responses to 9 questions about the respondent's mental health, rated on a scale.
8. **Depression Value**: Depression value calculated based on the responses (max = 27).
9. **Depression Level**: The categorized depression level based on the depression value.

## Approach
1. **Data Preprocessing**: 
   - Loaded the dataset and previewed its contents.
   - Checked for missing values and dropped irrelevant columns.
   - Encoded categorical columns using label encoding.
   
2. **Feature Selection**:
   - Selected the responses to depression-related questions as the feature set.
   - The target variable is the depression level.

3. **Modeling**:
   - Split the data into training and testing sets.
   - Standardized the features using `StandardScaler`.
   - Built two machine learning models: **Logistic Regression** and **Random Forest**.

4. **Model Evaluation**:
   - Evaluated the models using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
   - Both models achieved an accuracy of 1.00 on the test set.
   - Visualized confusion matrices and ROC curves for both models.

## Dependencies
This project requires the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`


