## Data
* DATA provided in 5 Different CSV files
    1. general_data.csv         ==> Employee Information
    2. employee_survey_data.csv ==> Employee - Job survey
    3. manager_survey_data.csv  ==> Manager -Employee Suvey
    4. Intime.csv               ==> Employee Intime Details
    5. OutTime.csv              ==> Employee OutTime Details

## Real World / Business Objectives and Constraints
  1. Interpertablity of the model
  2. No Strict Latency requried
  3. MOdel should give results in Probablity

## Data
* DATA provided in 5 Different CSV files
    1. general_data.csv ==> Employee Information
    2. employee_survey_data.csv ==> Employee - Job survey
    3. manager_survey_data.csv ==> Manager -Employee Suvey
    4. Intime.csv ==> Employee Intime Details
    5. OutTime .csv ==> Employee OutTime Details

## Mapping the real-world problem to a Machine Learning Problem
### Type of Machine Learning Problem ::
@@ -33,3 +34,25 @@ later by desining ML Models finding probablity of the features for the attrition
### Performance Metric ::
  1. Logloss :: i have choosen Logloss as my metric because my output is in probablistic Type 
  2. And also creating Confidence Score and Confusion Matrix.



# Solution consist of ::
    1. Data Preprocessing and Data Cleaning
    2. Exploratory Data Analysis
        1. Numerical variables with histograms
        2. Categorical variables with count plots
        3. Relationships between numerical variables with scatter plots, joint plots, and pair plots, and
        4. Relationships between numerical and categorical variables with box-and-whisker plots and complex conditional plots.
     3. Finding Correlation
         1. Corelation on Numerical Features
         2. categorical Varibles Corelation
                * chi-square Test For Independence
      4. Converting Categorical Column data into Numerical Data
      5. Applied Models on top of Data 
           * with and Without Balanced Data
                1. Logistic Regression
                2. Linear SVM
                3. RBF SVM
                4. Polynominal SVM
       6. Model Comparsion
