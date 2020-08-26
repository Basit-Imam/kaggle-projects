# Introduction
Classification is a process of dividing the given data points into two or more classes. When the number of classes = 2, it is known as Binary Classification.

In this notebook, I performed Binary Classification to **predict whether a person has a heart disease or not.** using Artificial Neural Networks with the help of Tensorflow and keras

There are 2 classes:
1. Heart disease present (target=1)
2. Heart disease not present (target=0)

# Data Description
* **age:** Age in years
* **sex:** 1 = male, 0 = female
* **cp:** Chest pain type
* **trestbps:** Resting blood pressure (in mm Hg on admission to the hospital)
* **chol:** serum cholesterol in mg/dl
* **fbs:** fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
* **restecg:** Resting electrocardiographic results
* **thalach:** Maximum heart rate achieved
* **exang:** Exercise induced angina (1 = yes; 0 = no)
* **oldpeak:** ST depression induced by exercise relative to rest
* **slope:** The slope of the peak exercise ST segment
* **ca:** Number of major vessels (0-3) colored by fluoroscopy
* **thal:** 3 = normal; 6 = fixed defect; 7 = reversible defect
* **target:** 1 = Heart disease present, 0 = Heart disease not present

# Conclusion
In this example, I developed a working Neural Network for the binary classification problem.
Model gave an accuracy of 83% which can be optimised further using hyperparameter tuning and other techniques.
