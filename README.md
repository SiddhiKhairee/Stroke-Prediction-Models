# Stroke-Prediction-Models
A simple introductory ML project predicting the chances of stroke based on the attritues present in the dataset. 
Stroke Prediction using ML Models
=================================================

This project uses multiple machine learning models to predict the likelihood of a stroke using patient health data. The dataset is stored in 'stroke-dataset.csv', and the project includes exploratory data analysis, model building, evaluation, and comparison.

Project Files:
--------------
- dt.ipynb              -> Decision Tree model
- rf.ipynb              -> Random Forest model
- knn.ipynb             -> k-Nearest Neighbors model
- svm.ipynb             -> Support Vector Machine model
- eda.ipynb             -> Exploratory Data Analysis
- modelComparison.ipynb -> Comparison of model performances
- ModelPerformance.png  -> Visualization of model metrics
- ModelPerformances.png -> Additional performance visualization
- stroke-dataset.csv    -> Input dataset
- requirements.txt      -> Python dependencies
- README.md            -> This file

Dataset:
--------
The dataset contains information about individuals including age, hypertension, heart disease, smoking status, and other attributes. The goal is to predict whether the individual is likely to experience a stroke (target column: "stroke").

Implemented Models:
--------------------
- Decision Tree
- Random Forest
- k-Nearest Neighbors
- Support Vector Machine

Each model is evaluated based on:
- Accuracy
- Precision
- Recall
- F1 Score
- F2 Score

How to Use:
-----------
1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Install required libraries using:
   pip install -r requirements.txt
4. Run the notebooks in the following order:
   a. eda.ipynb
   b. One or more model notebooks: dt.ipynb, rf.ipynb, knn.ipynb, svm.ipynb
   c. modelComparison.ipynb to compare model performance.

Dependencies:
-------------
See requirements.txt for package details.

Author:
-----------
<table>
  <tr>
  <td align="center"><a href="https://github.com/SiddhiKhairee"><img src="https://avatars.githubusercontent.com/SiddhiKhairee" width="100px;" alt=""/><br /><b>Siddhi Khaire</b></a><br /></td>
  </tr>
</table>

