# Classification
Classification Model (End to End Classification of Heart Disease - UCI Data Set)
****
# Predicting Heart Disease

**Create a Machine Learning Model capable of Predicting Presence of Heart Disease based on their Medical Attributes.**

### Problem Definition : Based on Medical Features, Predict whether the Patient have Heart Disease or not.

### Data : Heart Disease UCI : ( [The Orignal Data Set](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)  |  [Kaggle Data Set](https://www.kaggle.com/ronitf/heart-disease-uci) )

### Features : Data Dictionary : List of Features
* **Age**
* **Sex** : 1 - Male; 0 - Female
* **Chest Pain Type** (4 values)
* **Resting Blood Pressure**
* **Serum Cholestoral** in mg/dl
* **Fasting Blood Sugar** in mg/dl
* **Resting Electrocardiographic Results** (values 0,1,2)
* **Maximum Heart Rate Achieved** : Thalach
* **Exercise Induced Angina**
* **Oldpeak** : ST Depression induced by Exercise Relative to Rest
* **The Slope of the Peak Exercise ST Segment**
* **Number of Major Vessels** (0-3) Colored by Flourosopy
* **Thalassemia** : 3 - Normal; 6 - Fixed Defect; 7 - Reversable Defect.
* **Target : 1 - Heart Diseased; 0 - Not Heart Diseased.**
****
### Machine Learning Model's used for Classification. 

1. **Logistic Regression**
2. **K Nearest Neighbors**
3. **Random Forest Classifier**

**Model Selection :**
1. **Train Test Split**
2. **Cross Validation**
3. **Randommized Search Cross Validation**
4. **Grid Search Cross Validation**

**Classification Evaluation Metrics :**
1. **Accuracy Score**
2. **Precision Score**
3. **Recall Score**
4. **F1 Score**
5. **Receiver Operating Characteristics Curve**
6. **Area Under Curve Score**
7. **Classification Report**

* **A Model that Predicts Zero False Positive has the Precision Score of 100%**

* **A Model that Predicts Zero False Negative has the Recall Score of 100%**

* **A Model that Predicts Zero False Positive and Zero False Negative has the F1 Score of 100%**

* **Macro Average : Average of Precision, Recall and F1 Scores between Classes.**

* **Macro Average does not take Imbalanced Class.**

* **Weighted Average is Biased to the Class with More Samples.**

## Experimentation

**If You have not Reached to your Expected Evaluation Metric :**

1. **Collect some more Data if Possible.**

2. **Try to Explore other Machine Learning Model.**  

3. **Improve Current Model, Experiment with the Hyperparameters.**

