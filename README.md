# preprocessing-and-model-selection-case-study
Analysis using example dataset

### by Yaniv Amir  11/2024

## Goal
Improve a model that predicts customer retention. The existing model is based on logistic regression, and the data science team is considering whether alternative statistical or machine learning models might yield better performance.

## Method
Develop a baseline Logistic Regression model and attempt to improve on that model using more advanced preprocessing and regularization techniques. Suggest a different model, Random Forest, which may be more suitable for this particular task. Extract Feature Importance to identify key insights for product and marketing teams. Potentially Use SVM / XGBoost to compare and impove.

#### Tech used:

<img alt="Python" src="https://img.shields.io/badge/Python-3776ab?logo=python&logoColor=white&style-flat">
<img alt="scikit-learn" src="https://img.shields.io/badge/Scikit-f7931e?logo=scikit-learn&logoColor=white&style-flat">
<img alt="NumPy" src="https://img.shields.io/badge/NumPy-013242?logo=numpy&logoColor=white&style-flat">
<img alt="Pandas" src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white&style-flat">
<img alt="SciPy" src="https://img.shields.io/badge/SciPy-8CAAE6?logo=SciPy&logoColor=white&style-flat">
<img alt="Google Colab" src="https://img.shields.io/badge/GoogleColab-f9ab00?logo=googlecolab&logoColor=white&style-flat">
<img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-f37626?logo=jupyter&logoColor=white&style-flat">

### Outline of Analysis
#### 1. Exploratory data analysis: Understanding the target variable and the dif#ferent features
#### 2. Drividing the dataset into training and test sets.
#### 3. Develop a simple Logistic Regression model as baseline model
   
  3.1. simple preprocessing steps: SimpleImputer
   
  3.2. Cross validation without hyperparameter tuning
   
#### 4. Develop an advanced Logistic Regression model
   
   4.1. more advanced preprocessor steps:
      
     4.1.1. Remove highly correlated features
       
     4.1.2. Outlier removal
       
     4.1.3. IterativeImputer
   
  4.2. Cross validation with regularization, L1 and L2, and hyperparameter tuning using GridSearchCV
   
  4.3. Best model evaluation
   
  4.4. Fedature Importance

#### 5. Dvelop a Random Forest Model
   
  5.1. Preprocessing
  
  5.2 Cross validation and hyperparameter tuning using an exhaustive   GridSearchCV
  
  5.3. Model Confidence metrics
  
  5.4. Feature Importance

#### 6. Other models to consider with this dataset

