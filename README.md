# Pima Indians Diabetes

![Diabetes](https://www.breathewellbeing.in/blog/wp-content/uploads/2021/03/diabetes-complications-1.jpeg)

* Kindly review my Kaggle notebook for accessing the interactive plots.

https://www.kaggle.com/code/walidkw/pima-indians-diabetes-ml-model-selection-83

# About Dataset:
### Context
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

### Content
The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

### Acknowledgements
Smith, J.W., Everhart, J.E., Dickson, W.C., Knowler, W.C., & Johannes, R.S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. In Proceedings of the Symposium on Computer Applications and Medical Care (pp. 261--265). IEEE Computer Society Press.

### Inspiration
Can you build a machine learning model to accurately predict whether or not the patients in the dataset have diabetes or not?

# Requirements:

- Perform Exploratory Data Analysis
- Data Cleaning
- Plot relationship between variables.
- implement machine learning models.
- Perform Cross Validation

# Conclusion:

In this project, we conducted a comprehensive analysis of a dataset comprising eight medical predictor variables and one target variable, 'Outcome.' These predictor variables encompassed pregnancy, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes prevalence function, and age, collectively aiding in predicting the presence or absence of diabetes in patients. Our exploratory data analysis (EDA) journey commenced with a meticulous examination of the dataset's characteristics, revealing eight features and 768 rows of data. Subsequent evaluation of data types confirmed the data's integrity and correctness, rendering any alterations unnecessary.

Further insights were garnered through a correlation heatmap, unveiling interrelationships between variables such as pregnancies and age, skin thickness, and BMI. A thorough assessment for data redundancy and missing values yielded no irregularities, instilling confidence in proceeding with data visualization. To elucidate the distribution of outcomes, we created plots, revealing a notable disparity: patients identified as non-diabetic outnumbered their diabetic counterparts by a substantial margin.

We constructed subplots featuring histograms to visualize feature distributions while distinguishing between 'No Diabetes' and 'Diabetes' cases within the dataset. A pairplot was also employed to unveil pairwise relationships among all features. Utilizing violin and box plots, we delved deeper into understanding these relationships and the dataset's intricacies, laying the foundation for subsequent machine learning endeavors.

In the machine learning phase, we initiated by partitioning the data into 80% for training and 20% for testing, followed by standardizing the features for optimal modeling performance. Addressing the imbalance issue—where 'No Diabetes' cases considerably outnumbered 'Diabetes' cases—we applied the Synthetic Minority Over-sampling Technique (SMOTE) to achieve balance.

Finally, we employed model selection techniques to identify the most accurate predictive model for our scenario. A range of models, including Logistic Regression, Random Forest, XGBoost, SVM, KNN, and Naive Bayes, were assessed. Through rigorous 10-fold cross-validation, we determined that the Random Forest and XGBoost models exhibited the highest accuracy, thereby concluding our project on a promising note.
Additionally, cross-validation was performed to assess the models' generalization performance. The cross-validation scores for all models were plotted, providing an overview of their performance across different folds.

Overall, this analysis provides insights into the dataset, performs data cleaning and preprocessing, conducts model selection, and evaluates the models using various metrics. By combining these steps, we can make informed decisions and develop robust models for predicting house prices.
