# TASK 1&2- Red Wine Quality Prediction

This data science project aims to predict the quality of red variants of the Portuguese "Vinho Verde" wine. The dataset consists of physicochemical (input) and sensory (output) variables, with no information about grape types, wine brand, or selling price due to privacy and logistic constraints.

The dataset can be approached as either a classification or regression task. The quality scores are ordered and not evenly distributed, meaning there are significantly more normal wines than excellent or poor ones.
## Dataset Information
The dataset used in this project is sourced from the UCI Machine Learning Repository and is also available for convenience on Kaggle. However, if there are any licensing concerns, the dataset will be promptly removed upon request. Additional details can be found in the reference [Cortez et al., 2009].
## Input Variables (Physicochemical Tests)
1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol
## Output Variable (Sensory Data)
1. Quality (score between 0 and 10)
For further insights and analysis, refer to the research paper by Cortez et al. (2009). This project aims to leverage machine learning techniques to build a predictive model that can estimate the quality of red wines based on their physicochemical properties and sensory attributes.

# TASK 3-House Price Prediction 
![](https://nycdsa-blog-files.s3.us-east-2.amazonaws.com/2021/03/chaitali-majumder/house-price-497112-KhCJQICS.jpg)
This data science project focuses on predicting house prices using a dataset containing various features and attributes related to residential properties. By analyzing and modeling the data, the project aims to develop a predictive model that can estimate the sale prices of houses accurately.
## Dataset Information
The dataset used in this project consists of information about different residential properties. It includes a wide range of features that can potentially influence the price of a house, such as the number of bedrooms, bathrooms, square footage, location, neighborhood characteristics, and other relevant factors.
## Objective
The main objective of this project is to leverage machine learning techniques to build a robust predictive model for house price estimation. By training the model on historical data and leveraging its learned patterns and relationships, it will be able to predict the prices of new or unseen houses accurately.
## Approach
The project will involve several steps, including data preprocessing, exploratory data analysis, feature engineering, model selection, and evaluation. Techniques such as data cleaning, handling missing values, feature scaling, and encoding categorical variables will be employed to prepare the dataset for model training. Various regression algorithms, such as linear regression, random forests will be explored and evaluated to determine the most suitable model for accurate price prediction.
## Impact
Accurate house price prediction can have significant implications for various stakeholders, including homebuyers, sellers, real estate agents, and investors. With an effective predictive model, prospective buyers can make informed decisions about property investments, sellers can set competitive prices, and agents can provide better guidance to their clients. Additionally, investors can use the predicted prices to identify profitable opportunities in the real estate market.

Through this project, insights and patterns in the housing market can be uncovered, allowing for a better understanding of the factors influencing house prices and facilitating more informed decision-making in the real estate industry.

# TASK 4-Breast Cancer Prediction
**Breast Cancer Prediction** is a classification task aimed at predicting the diagnosis of a breast mass as either malignant or benign. The dataset used for this prediction consists of features computed from a digitized image of a fine needle aspirate (FNA) of the breast mass. These features describe various characteristics of the cell nuclei present in the image.

The dataset contains the following information for each instance:

1. ID number: A unique identifier for each sample.
2. Diagnosis: The target variable indicating the diagnosis, where 'M' represents malignant and 'B' represents benign.

For each cell nucleus, ten real-valued features are computed, which are:

1. Radius: The mean distance from the center to points on the perimeter of the nucleus.
2. Texture: The standard deviation of gray-scale values in the nucleus.
3. Perimeter: The perimeter of the nucleus.
4. Area: The area of the nucleus.
5. Smoothness: A measure of local variation in radius lengths.
6. Compactness: Computed as the square of the perimeter divided by the area minus 1.0.
7. Concavity: Describes the severity of concave portions of the nucleus contour.
8. Concave points: Represents the number of concave portions of the nucleus contour.
9. Symmetry: Measures the symmetry of the nucleus.
10. Fractal dimension: This feature approximates the "coastline" of the nucleus, using the concept of fractal geometry.

These features provide quantitative measurements that can be used to assess the characteristics of cell nuclei and aid in distinguishing between malignant and benign breast masses. By training a machine learning model on this dataset, it is possible to develop a predictive model that can assist in the early detection and diagnosis of breast cancer.

# TASK 5- Heart Stroke Prediction
![](https://dezyre.gumlet.io/images/blog/heart-disease-prediction-using-machine-learning-project/Heart_Disease_Prediction_using_Machine_Learning.png?w=330&dpr=2.6)

This data science project aims to predict the likelihood of a patient experiencing a stroke based on various input parameters such as gender, age, presence of diseases, and smoking status. The dataset provides relevant information about each patient, enabling the development of a predictive model.
## Dataset Information
The dataset used in this project contains information necessary to predict the occurrence of a stroke. Each row in the dataset represents a patient, and the dataset includes the following attributes:
1. id: Unique identifier
2. gender: "Male", "Female", or "Other"
3. age: Age of the patient
4. hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5. heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6. ever_married: "No" or "Yes"
7. work_type: "Children", "Govt_job", "Never_worked", "Private", or "Self-employed"
8. Residence_type: "Rural" or "Urban"
9. avg_glucose_level: Average glucose level in the blood
10. bmi: Body mass index
11. smoking_status: "Formerly smoked", "Never smoked", "Smokes", or "Unknown"
12. stroke: 1 if the patient had a stroke, 0 if not
## Context
According to the World Health Organization (WHO), stroke is the second leading cause of death worldwide, responsible for approximately 11% of total deaths. This project aims to leverage machine learning techniques to build a predictive model that can identify individuals at risk of stroke based on their demographic and health-related features. By detecting high-risk individuals early, appropriate preventive measures can be taken to reduce the incidence and impact of stroke.

To enhance the accuracy of the stroke prediction model, the dataset will be analyzed and processed using various data science methodologies and algorithms.

## TASK 6- KNN Classification using Iris Dataset

📌 Objective

Implement and understand the K-Nearest Neighbors (KNN) algorithm for classification using the Iris dataset.

🛠 Tools and Libraries Used

Python
Pandas
NumPy
Matplotlib
Scikit-learn

📁 Dataset

The dataset used is the Iris flower dataset from Kaggle. It contains 150 samples of iris flowers categorized into three species: Setosa, Versicolor, and Virginica.

🔍 Steps Performed

Data Loading: Loaded Iris.csv and removed unnecessary columns like Id.
Label Encoding: Converted categorical species labels to numerical format using LabelEncoder.
Feature Scaling: Standardized the feature values using StandardScaler.
Train-Test Split: Split the data into training and test sets (80/20).
Model Building: Used KNeighborsClassifier from scikit-learn to train models with different values of K.
Evaluation: Calculated accuracy and plotted confusion matrices for each value of K.
Visualization: Plotted decision boundaries using two selected features to visually understand how the KNN algorithm classifies data points.

📊 Results

Tested the model with K values: 1, 3, 5, and 7.
Best performance observed around K=3 with high accuracy.
Confusion matrices clearly indicate the model’s classification effectiveness.

📌 Conclusion

KNN is a simple yet effective classification algorithm when applied to normalized data. It performs well on the Iris dataset and provides intuitive decision boundaries when visualized in 2D.

# TASK 7 - Support Vector Machines on the Breast Cancer Wisconsin (Diagnostic) Data Set

![](nucleus_cover_image.jpg)

**Goal**: Predict breast cancer given all other values with the use of SVMs. <br>
**Approach**:
<ol>
    <li>Supervised Learning task, because given labeled traning examples.</li>
    <li>Classification task.</li>
    <li>There is no continuous flow of data, no need to adjust to changing data, and the data is small enough to fit in memmory: Batch Learning</li>
</ol>

**Data:** [Breast Cancer Wisconsin (Diagnostic) Data Set | Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data/version/2#)<br>

SVM's goal is to have largest possible margin between decision boundary that separetes the classes and the training instances.

# TASK 8- Mall-Customer-Segmentation-using-K-Means
Mall Customer Segmentation using K-Means Algorithm

![image](https://user-images.githubusercontent.com/69152112/221351922-d0352643-c1d6-4a9f-a433-594f5b2be9a8.png)

Customer segmentation is the method of distributing a customer base into collections of people based on mutual characteristics so organizations can market to group efficiently and competently individually.

The purpose of segmenting customers is to determine how to correlate to customers in multiple segments to maximize customer benefits. Perfectly done customer segmentation empowers marketers to interact with every customer in the best efficient approach.

The data includes the following features:

Customer ID

Customer Gender

Customer Age

Annual Income of the customer (in Thousand Dollars)

Spending score of the customer (based on customer behaviour and spending nature)




