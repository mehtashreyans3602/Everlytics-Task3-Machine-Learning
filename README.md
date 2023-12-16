# Everlytics-Task3-Machine-Learning
 This Project consist of Everlytics Data Engineering and Machine Learning Internship Task3
 ### Question:
Build a model that predicts/classifies whether a website phishing website.

### Approach:
#### Data: 'Phishing Data - Phishing Data.csv'

#### 1. Importing Libraries: Essential libraries such as pandas, seaborn, and matplotlib are imported.

#### 2. Importing Dataset: The phishing dataset ("Phishing Data - Phishing Data.csv") is loaded into a Pandas DataFrame for further analysis.

#### 3. Data Preprocessing:
* Checking for missing values in the dataset.
* Forming a correlation matrix to identify important features.
* Selecting features based on a correlation threshold of 20%.
* Data Splitting:
Splitting the dataset into independent features (X) and the target concept (y).
Alternatively, selecting only the important features.
Further splitting the data into training and testing sets.
* Standardization:
Standardizing the features using StandardScaler to ensure that all features have the same scale.
Initializing Classification Algorithms:

#### 4. Creating a dictionary containing instances of various classification algorithms, such as Naive Bayes, Logistic Regression, SVM, Decision Tree, and Random Forest.
#### 5. Training Models:

* Training each model on the entire feature set and evaluating their performance.
* Training each model on the selected important features and evaluating their performance.
#### 6. Displaying Results:
* Displaying confusion matrices for each model on both the entire feature set and important features.
* Displaying evaluation measures, including accuracy, precision, recall, and F1 score, for each model on both feature sets.
### Tools And Techniques Used:
* Libraries: Pandas, Seaborn, Matplotlib, Scikit-learn
* Machine Learning Algorithms: Naive Bayes, Logistic Regression, Support Vector Machine (SVM), Decision Tree, Random Forest
* Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, Confusion Matrix
### Model Accuracy:
<img align="center" height="500" width="500" alt="" src="https://github.com/mehtashreyans3602/Everlytics-Task3-Machine-Learning/blob/main/CorrelationMatrix.png" />

