# ML-Obesity-prediction--Analysis
## Overview

This project aims to classify obesity levels based on various personal attributes such as BMI, age, weight, eating habits, and physical activity. It evaluates and compares the performance of different machine learning models, including **Logistic Regression**, **Random Forest**, **Gradient Boosting**, **XGBoost**, and **SVM**, along with hyperparameter tuning and data balancing techniques like SMOTE.

## Dataset

The dataset used in this project relates to obesity levels determined by personal characteristics and habits. It includes a wide range of features, such as:

- **BMI** (Body Mass Index)
- **Weight** and **Height**
- **Age**
- **Family History with Overweight**
- **Eating Habits** (e.g., frequency of vegetable and fast food consumption)
- **Physical Activity Levels**

This dataset is publicly available and can be accessed [here](https://www.kaggle.com/datasets/jpkochar/obesity-risk-dataset).

## Model Performance

The following machine learning models were implemented and evaluated for obesity classification:

- **Logistic Regression:** Accuracy = 0.85
- **Random Forest:** Accuracy = 0.91
- **Gradient Boosting:** Accuracy = 0.90
- **XGBoost:** Accuracy = 0.91
- **SVM:** Accuracy = 0.87

After performing **hyperparameter tuning** and applying **SMOTE** to handle class imbalance, **Random Forest** and **XGBoost** emerged as the best-performing models, excelling in metrics like accuracy, precision, recall, F1-score, and AUC.

## Results and Visualizations

The project includes comprehensive visualizations to aid the understanding of model performance and data characteristics:

- **Confusion Matrices** for each model to assess classification accuracy per class.
- **Feature Importance plot** from Random Forest to identify the most influential features affecting obesity levels.
- **Precision-Recall Curves** to evaluate the precision-recall trade-offs across multiple classes and models.
- **ROC-AUC Curves** comparing the receiver operating characteristic (ROC) for all models, demonstrating their discriminatory power.
- **Distribution Plots** showcasing features like BMI, Age, and Weight, offering insights into data distribution across different obesity levels.
- **Box Plots** showing the distribution of BMI and Age across various obesity levels to identify trends.
- **Heatmaps** displaying correlations between features to highlight relationships in the dataset.
- **Model Comparison bar charts** for Accuracy, Precision, Recall, and F1-Score, visualizing how each model performed.

## Dependencies

This project was developed using **Python 3.x** and the following libraries:

- **Pandas** for data manipulation
- **Scikit-Learn** for machine learning models and preprocessing
- **XGBoost** for implementing the XGBoost classifier
- **Matplotlib** and **Seaborn** for data visualization
- **Imbalanced-learn (SMOTE)** for handling class imbalance

## Conclusion

In conclusion, this project offers a detailed comparison of multiple machine learning models for obesity classification. **Random Forest** and **XGBoost** demonstrated top-tier performance, especially after hyperparameter tuning and data balancing techniques like SMOTE. The visualizations provide valuable insights into the models' classification abilities, the importance of various features, and the dataset’s structure. These models could potentially be deployed in real-world applications where accurate obesity prediction is needed.

