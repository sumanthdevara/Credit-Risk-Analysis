# Credit-Risk-Analysis
Credit Risk Analysis


Project Report: German Credit Risk Analysis

Introduction:
The German Credit Risk Analysis project aims to predict credit risk using machine learning techniques. The dataset used in this project contains information about customers' credit applications, including demographic features, credit amount, duration, and risk classification.

Libraries:
Pandas
NumPy
Matplotlib
Seaborn
LightGBM
Scikit-learn
Imbalanced-learn

Data Exploration and Preprocessing:
Imported the dataset and preprocessed column names.
Explored data dimensions and target class balance.
Visualized numerical and categorical features.
Preprocessed the data by handling missing values, encoding categorical variables, and splitting the dataset into training and testing sets.

Model Training and Evaluation:
Trained multiple machine learning models, including Logistic Regression, Decision Trees, Random Forest, and LightGBM.
Tuned hyperparameters using RandomizedSearchCV.
Evaluated models using various metrics such as accuracy, precision, recall, F1 score, and ROC AUC.
Plotted ROC curves, confusion matrices, and learning curves to analyze model performance.

Feature Importance Analysis:
Conducted feature importance analysis using LightGBM.
Visualized feature importance to identify significant predictors in the model.

Model Deployment:
Built a preprocessing pipeline to handle data transformations.
Applied the trained model to new data for credit risk prediction.
Appended predicted probabilities and classes to the dataset for further analysis.

Conclusion:
The Credit Risk Analysis project successfully developed machine learning models to predict credit risk based on customer attributes. The LightGBM model demonstrated the best performance with an accuracy of 72.4% and an ROC AUC of 79.4%. Feature importance analysis identified key predictors influencing credit risk. The deployed model can be used for real-time credit risk assessment in financial institutions.
