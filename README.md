# Crop Yield Prediction Using Machine Learning

## Project Overview
This project focuses on predicting suitable crops based on key environmental factors like soil nutrients, temperature, humidity, pH levels, and rainfall. Using machine learning classification algorithms, we aim to assist farmers and agricultural experts in optimizing crop choices based on available data.

## Dataset
The dataset consists of 2200 samples with the following features:
- **Nitrogen**: The concentration of nitrogen in the soil.
- **Phosphorus**: The concentration of phosphorus in the soil.
- **Potassium**: The concentration of potassium in the soil.
- **Temperature**: The temperature in degrees Celsius.
- **Humidity**: The relative humidity percentage.
- **pH**: The soil pH level.
- **Rainfall**: The amount of rainfall (in mm).
- **Label**: The crop type (22 different crops).

This combination of features directly affects crop growth and yields, making it crucial for making informed agricultural decisions.

## Model Selection and Training
Four machine learning classification algorithms were trained and evaluated:
1. **Logistic Regression**
2. **Random Forest Classifier**
3. **Gradient Boosting Classifier**
4. **Support Vector Machine (SVM)**

Each model was trained to predict the crop type based on the given environmental factors. The models were evaluated using precision, recall, F1-score, and overall accuracy.

### Logistic Regression
The Logistic Regression model achieved a high accuracy of **96%**. While it performed well in predicting most crops, it had a slight drop in precision and recall for certain classes.

### Random Forest Classifier
The Random Forest Classifier achieved the best performance with an impressive accuracy of **99%**. This model excelled in precision, recall, and F1-score for almost all crop types, making it the top-performing model in this project.

### Gradient Boosting Classifier
The Gradient Boosting Classifier achieved a strong accuracy of **98%**. It had solid performance across the board, with high precision and recall for most crops. However, it did slightly underperform compared to Random Forest in a few crop categories.

### Support Vector Machine (SVM)
The SVM model reached an accuracy of **97%**. It performed well for most crops, though it had a slight dip in precision and recall for a few cases, such as crop classes with smaller sample sizes.

## Results
The Random Forest Classifier outperformed other models in terms of overall accuracy, making it the best choice for predicting crop yield. Below is a summary of the performance metrics for all models:

| Model                     | Accuracy | Precision | Recall | F1-Score |
|----------------------------|----------|-----------|--------|----------|
| **Logistic Regression**     | 96%      | 96%       | 96%    | 96%      |
| **Random Forest Classifier**| 99%      | 99%       | 99%    | 99%      |
| **Gradient Boosting**       | 98%      | 98%       | 98%    | 98%      |
| **Support Vector Machine**  | 97%      | 97%       | 97%    | 97%      |

### Key Insights:
- The Random Forest Classifier exhibited the best overall performance with an accuracy of **99%**, making it highly reliable for predicting the appropriate crop based on environmental inputs.
- Gradient Boosting and SVM models also performed strongly, with accuracies above **97%**.
- Logistic Regression, although not the top performer, showed a decent performance and can still be a good option for simpler or faster predictions.

## Conclusion
The results from this project show that machine learning, particularly ensemble methods like Random Forest, can be highly effective in predicting crop yields based on soil and environmental data. This can be practically applied to support decision-making in agriculture, helping farmers make informed choices to maximize yield and optimize resources.

## Future Work
Future work will include:
- Exploring more advanced algorithms.
- Adding additional features such as soil type or geographic location.
- Deploying the model in a real-world agricultural tool for farmers.

---

Feel free to reach out for questions or suggestions on how to improve the project!
