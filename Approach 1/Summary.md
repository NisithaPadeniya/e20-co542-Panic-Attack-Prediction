# Exploratory Data Analysis (EDA) and Graphs

EDA is done to understand the dataset's structure, detect missing values, and identify patterns. The report uses the following visualizations:

1. **Histograms (Distribution of Continuous Variables)**  
   - Shows the distribution of Age, Heart Rate, Panic Attack Frequency, and Duration.  
   - **Why?** Helps understand how these variables are spread (e.g., whether age is normally distributed or heart rate is skewed).

2. **Boxplots (Outliers Detection)**  
   - Shows the spread of Age, Heart Rate, Sleep Hours, and Duration.  
   - **Why?** Helps detect outliers (e.g., unusually high heart rates or long panic attack durations).

3. **Count Plots (Categorical Data Distribution)**  
   - Displays Gender, Sweating, Shortness of Breath, and Triggers.  
   - **Why?** To observe the distribution of categorical variables, such as which gender experiences more panic attacks.

4. **Scatter Plot (Relationship Analysis)**  
   - Plots Panic Score vs. Duration of Panic Attack, with Gender as the hue.  
   - **Why?** Helps understand if longer panic attacks have higher severity scores.

5. **Violin Plot (Gender vs. Heart Rate)**  
   - Compares the spread of heart rates between different genders.  
   - **Why?** Identifies if certain genders have higher heart rate fluctuations during panic attacks.

6. **Pairplot (Correlations Between Features)**  
   - Plots Age, Heart Rate, Duration, and Panic Score against each other.  
   - **Why?** Helps identify strong correlations between features.

7. **Heatmap (Correlation Matrix)**  
   - Shows correlations between numerical features.  
   - **Why?** To understand which features are strongly related (e.g., Panic Score and Heart Rate).

# Machine Learning Models Used

Several ML models were trained on the dataset:

1. **Logistic Regression**  
   - Simple linear classifier.  
   - **Result:** Low accuracy (~10%).

2. **Support Vector Machine (SVM)**  
   - Finds the optimal decision boundary.  
   - **Result:** Best performing ML model (Accuracy: ~12.5%).

3. **K-Nearest Neighbors (KNN)**  
   - Predicts based on the nearest data points.  
   - **Result:** Weak performance (~10.4%).

4. **Decision Tree**  
   - Splits data based on conditions.  
   - **Result:** Poor accuracy (~9%).

5. **Random Forest**  
   - Ensemble of decision trees.  
   - **Result:** ~9.5% accuracy.

6. **XGBoost**  
   - Gradient boosting method.  
   - **Result:** ~11.2% accuracy.

**Best ML Model: SVM with Accuracy = 12.5%.**

# Deep Learning Models Used

Various Deep Learning models were also tested:

1. **Simple Neural Network (NN)**  
   - A basic three-layer NN.  
   - **Result:** 10% accuracy.

2. **Deep Neural Network (DNN)**  
   - More complex architecture with batch normalization and dropout.  
   - **Result:** Best performing Deep Learning model (Accuracy: 10.8%).

3. **Artificial Neural Network (ANN)**  
   - Similar to DNN but with fewer layers.  
   - **Result:** 9.1% accuracy.

4. **Multi-Layer Perceptron (MLP)**  
   - Fully connected network.  
   - **Result:** 12.9% accuracy.

5. **Convolutional Neural Network (CNN)**  
   - Used Conv1D layers to extract features.  
   - **Result:** 10.4% accuracy.

**Best DL Model: DNN with Accuracy = 10.8%.**
