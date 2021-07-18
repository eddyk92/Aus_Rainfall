# Aus_Rainfall
Predict furture rainfall in specific regions of Austrailia 

Group members who worked on this notebook: Brianna Keegan, Mark Gardiola-Chin, Kevin Eddy, Stacey Koo

Saint Mary's College of California Graduate Program of Business Analytics 
OPS808 Machine Learning Final Prject: Australia Rainfall

This project is broken into 3 sections:
- Data Exploration And Feature Engineering
- Logistic Regression
- Machine Learning
  - Random Forest
  - Support Vector Machines

Observations:
Using the rainfall dataset we found on Kaggle that includes around 10 years of daily weather observations from various locations throughout Australia,
we made two observations in the hot climate data specifically located in central-Australia. One, it had the lowest number of datapoints. Secondly, the 
level of imbalance in the dataset between no-rain vs. rain was the highest (1:6 ratio). Even though the hot climate data has the highest metrics (accuracy 
and F1 score) and though we have addressed this imbalance by adjusting the class weights, we feel as though we must factor in a level of suspicion when 
interpreting the results for the hot climate region as there is a possibility that the model has an inherent bias.

Ultimately, we found that the Support Vector model yielded the highest accuracy and therefore was the most desired option.
