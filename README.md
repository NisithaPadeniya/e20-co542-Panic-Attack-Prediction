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

