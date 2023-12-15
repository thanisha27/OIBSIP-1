# OIBSIP-1

Iris flower has three species; setosa, versicolor, and virginica, which differs according to their
measurements. Now assume that you have the measurements of the iris flowers according to
their species, and here your task is to train a machine learning model that can learn from the
measurements of the iris species and classify them.

Explaination:
Performed a comprehensive analysis on the Iris dataset, including data preprocessing, exploratory data analysis (EDA), and training multiple machine learning models (K-nearest neighbors, Logistic Regression, and Decision Tree). Here's a brief explanation of the key steps:

Data Preprocessing:

- Loaded the dataset from a CSV file.
- Checked for null values in the dataset (no null values found).
- Encoded the target variable 'Species' using LabelEncoder.
- Split the dataset into features (X) and the target variable (Y).
- Split the data into training and testing sets (80% training, 20% testing).
- Standardized the features using StandardScaler.

Exploratory Data Analysis (EDA):

- Histograms: Histograms are plotted for each feature, both separately and combined for all features.
- Countplot: A countplot is created to visualize the distribution of species.
- Pairplot: A pairplot is used to visualize relationships between features, with different species colored differently.
- Scatter plots: FacetGrids and scatter plots are used to visualize relationships between pairs of features for different species.
  
Model Training:

- K-nearest neighbors (KNN): A K-nearest neighbors classifier is created ('KNeighborsClassifier') and trained on the training data. Predictions are made on the test set, and accuracy is calculated.
- Logistic Regression: A logistic regression classifier is created ('LogisticRegression') and trained on the training data. Predictions are made on the test set, and accuracy is calculated.
- Decision Tree: A decision tree classifier is created ('DecisionTreeClassifier') and trained on the training data. Predictions are made on the test set, and accuracy is calculated.

Model Comparison:

- Compared the accuracies of the three models (Logistic Regression, K-nearest neighbors, Decision Tree).
- Visualized the comparison using a bar plot.

In summary, The code provides a comprehensive example of data loading, preprocessing, exploratory data analysis, model training, and model comparison using three different classifiers. It's a good demonstration of how to approach a classification problem with machine learning using the popular Iris dataset.
