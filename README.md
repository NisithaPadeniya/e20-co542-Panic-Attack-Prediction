# Panic Attack Detection using Machine Learning and Deep Learning

A Panic Attack Detection System based on physiological signals such as heart rate and breathing speed. This project explores multiple machine learning models and deep learning techniques to classify whether a person is experiencing a panic attack.

## Key Features

- **Exploratory Data Analysis (EDA)**
  - Data visualization and preprocessing using `pandas`, `seaborn`, and `matplotlib`.

- **Data Preprocessing**
  - Feature scaling using `StandardScaler` and `RobustScaler`.
  - Handling imbalanced data using `SMOTE`.

- **Deep Learning (ANN) Model**
  - Implemented using TensorFlow/Keras (`Sequential` model).
  - Optimized using:
    - **Adam optimizer** for efficient learning.
    - **EarlyStopping** to prevent overfitting.
    - **ModelCheckpoint** to save the best model.

- **Model Evaluation**
  - Performance metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix.
  - Hyperparameter tuning using GridSearchCV and RandomizedSearchCV.
    
At the end of the project different models for this have been compared to see how their perfromances change from on another

