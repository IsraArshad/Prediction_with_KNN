# Advance Project - 5 & 6
# Prediction_with_KNN

This repository contains two machine learning use cases implemented using **K-Nearest Neighbors (KNN)** classification algorithm.

## Use Case 1: iPhone Purchase Prediction
- **Objective:** Predict whether a customer will purchase an iPhone based on their **gender**, **age**, and **salary**.
  
- **Tools Used:**
  - **Programming Language:** Python
  - **Libraries:** pandas, numpy, seaborn, scikit-learn, matplotlib
  - **Algorithm:** K-Nearest Neighbors (KNN)
  
- **Process:**
  1. **Data Loading:** Loaded customer data and performed preprocessing.
  2. **EDA:** Performed exploratory data analysis using Seaborn for visualization.
  3. **Modeling:** Trained and validated a KNN model.
  4. **Model Evaluation:** Used accuracy and confusion matrix to evaluate the model.

- **Insights:**
  - Gender, age, and salary are important factors influencing iPhone purchase decisions.
  - KNN provides a good model for predicting purchases with high accuracy.


## Use Case 2: House Price Prediction (Bangalore)
- **Objective:** Predict the price of a house in Bangalore based on features like area, number of bedrooms, etc.
  
- **Tools Used:**
  - **Programming Language:** Python
  - **Libraries:** pandas, numpy, seaborn, scikit-learn, matplotlib
  - **Algorithm:** K-Nearest Neighbors (KNN)
  
- **Process:**
  1. **Data Loading:** Loaded house pricing data and performed preprocessing.
  2. **EDA:** Performed exploratory data analysis using Seaborn for visualization.
  3. **Modeling:** Trained and validated a KNN model.
  4. **Model Evaluation:** Used metrics like R-squared, Mean Squared Error, and others to evaluate the model.

- **Insights:**
  - House price prediction depends on the area, number of rooms, and location.
  - KNN is effective at providing predictions based on similar properties in the area.


## General Insights and Business Impact:
- **KNN Model Performance:** The KNN model was successfully applied to both use cases with high accuracy, showing its potential in prediction tasks involving customer purchase behaviors and real estate pricing.
- **Business Impact:** 
  - For iPhone stores: Understanding customer profiles based on gender, age, and salary can help in targeting marketing campaigns more effectively.
  - For real estate agents: Price predictions help agents assess property values accurately and adjust their strategies.
