
# <b>Project_4 - Group_3</b>

# <b>Scope</b>
 - <b> Objective of this project is to predict probability of loan repayment among different customer segments</b>.

 # <b>Dataset/Data Model/Steps</b>
- <b>Find Data/Data Source</b> - Quality, quantity and integrity of Data and Data source.
- <b>Data Cleaning</b> - cleansing and preparing data.
- <b>Best fit Algorithm</b> - Find best fit algorithm/Model.
- <b>Model Development</b> - Selection of right parameters for analysis.
- <b>Model Optimization</b> - Improve the model performance by making adjustments to the parameters.
- <b>Model Evaluation</b> - Testing the model on sample for accuracy.

## Dependencies

To run this code, you need to have the following libraries installed:

```bash

pip install pandas - numpy - matplotlib - seaborn - scikit-learn

```
- **pandas**: Data manipulation and analysis.
- **numpy**: Numerical computing.
- **matplotlib**: Plotting and data visualization.
- **seaborn**: Statistical data visualization.
- **scikit-learn**: Machine learning and data preprocessing.

## Steps in the Analysis

1. **Import Libraries**:
   Essential libraries are imported, including pandas, numpy, matplotlib, seaborn, and scikit-learn.

2. **Load Data**:
   Load the Prosper Loan data using pandas.

3. **Data Preprocessing**:
   - Handle missing values using linear interpolation.
   - Create a new feature, Average Credit Score, by averaging the lower and upper credit scores.
   - Select specific columns for analysis.

4. **Feature Engineering**:
   - Convert categorical features to numerical values.
   - Handle missing values by dropping rows with NaNs.

5. **Exploratory Data Analysis (EDA)**:
   - Generate KDE plots to visualize the relationships between employment status, homeownership, income range, and loan status.
   - Generate a heatmap to show the correlations between different features.
   - Create pair plots to visualize relationships between multiple features.
   - Use KMeans clustering to identify clusters within the loan data.

6. **Model Building**:
   - Split the data into training and testing sets.
   - Standardize the features.
   - Build and evaluate a Random Forest Classifier.
   - Build and evaluate a Logistic Regression model.
   - Build and evaluate a Linear SVM model.


# <b>Models/Algorithms/Functions used in Exploratory Data Analysis</b>
- <b>Logistic Regression</b>:- Logistic Regression naturally outperforms Linear Regression in predicting the probability of loan default since its outcome contains a continuous range of grades between 0 and 1, which represents the likelihood of an event occurring.
- <b>Train_test_split</b>:- This function is used to split dataset into two subsets, training set testing set. 
- <b>RandomForestClassifier</b> :- Random forest classifier is a set of decision trees of random subset of training set. It aggregates the votes from decision trees to decide the final class of the test object.
- <b>Random Forest</b> :- Stochastic gradient descent model is an algorithm often used in machine learning to find the model parameters that correspond to the best fit between predicted and actual outputs.
- <b>Linear SVM</b> :- Support vector machine (SVM) is a type of supervised learning algorithm used in machine learning to solve classification and regression tasks.

# <b>Visualization</b>
- <b>Feature Emprtance</b>
  https://github.com/LachlanPotter33/Proj-4-Group-3/blob/main/Data/Featureimportance.png?raw=true
- <b>Employment Status 1 = full time,Self employed & there are few retirees in category 0</b>
  https://github.com/LachlanPotter33/Proj-4-Group-3/blob/main/Data/EmpVsOwership.png
- <b>Income Range 1= <=$25k, 2= <=100k AN, 3=>=100k </b>
  https://github.com/LachlanPotter33/Proj-4-Group-3/blob/main/Data/IncomeVsloanstatus.png
- <b>Loan Status 0=Safe, 1 = Risk 2= Bad</b>
  https://github.com/LachlanPotter33/Proj-4-Group-3/blob/main/Data/IncomeVsOwership.png


## References

- [Pandas](https://pandas.pydata.org/docs/)
- [Numpy](https://numpy.org/doc/)
- [Matplotlib](https://matplotlib.org/stable/contents.html)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/stable/documentation.html)
- [University of Adelaide Git bootcamp](https://git.bootcampcontent.com/University-of-Adelaide/UADEL-VIRT-DATA-PT-12-2023-U-LOLC)