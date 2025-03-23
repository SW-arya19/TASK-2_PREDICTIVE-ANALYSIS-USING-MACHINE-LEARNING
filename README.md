# TASK-2_PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
**COMPANY**:CODTECH IT SOLUTIONS 

**NAME**: SWADHA ARYA

**INTERNID**:CT12NGK


**DOMAIN**:DATA ANALYTICS

**BATCH DURATION**:JANUARY 25, 2025 TO MARCH 25 , 2025

**MENTOR NAME**: NEELA SANTHOSH KUMAR

**DESCRIPTION**:
The machine learning model built using the Titanic dataset follows a structured approach to classify passengers based on their survival status. Initially, the dataset is loaded, and the presence of missing values is identified. Missing values in numerical columns such as age are imputed using statistical measures like the median, while categorical variables with missing data are filled with a placeholder category. Categorical variables, including gender and embarkation point, are then transformed into numerical format using encoding techniques to ensure compatibility with the model.

Following data preprocessing, the dataset is split into training and testing sets to evaluate the model’s performance on unseen data. A logistic regression model is initially selected due to its suitability for binary classification problems. The model is trained using the training dataset and then tested to measure its accuracy. To improve performance, alternative models such as decision trees, random forests, and support vector machines (SVM) are explored, with cross-validation applied to ensure better generalization.

Feature scaling techniques such as standardization or normalization are applied where necessary, particularly for models sensitive to the magnitude of numerical values. Hyperparameter tuning using GridSearchCV is performed to optimize the selected model’s parameters. Evaluation metrics, including accuracy, precision, recall, and F1-score, are used to assess classification performance. A confusion matrix is generated to provide insights into correct and incorrect predictions.

Feature importance analysis is conducted to determine the most influential variables affecting survival predictions. Variables such as passenger class, fare, and gender exhibit significant contributions to the classification outcome. Finally, the trained model is saved using joblib or pickle, allowing for future predictions on new data. The entire process demonstrates an end-to-end machine learning workflow, from data preprocessing and feature engineering to model training, evaluation, and deployment.

**OUTPUT**: ![Image](https://github.com/user-attachments/assets/60572b16-7925-452e-ab03-e83991108c1e)
