# Application Flow Identification

The project provides a comprehensive analysis of various aspects of data preprocessing, machine learning model optimization, and testing performances with advanced tasks focusing on Explainable Artificial Intelligence (XAI). Here's a summary of the key points:

- **Raw Data Visualization/Analysis:**
  - Removal of irrelevant columns, handling missing values, and columns with all zeroes to refine the dataset.
  - Analysis of the dataset identified 22 different application flows and a maximum of 1000 samples for an application.
  - Visualization techniques were used to understand data correspondence and class imbalance, revealing that 7 applications had fewer samples than others.

- **Data Preprocessing:**
  - Evaluation of over-sampling techniques to address dataset imbalance, including Random Over-sampling, SMOTE, Borderline-SMOTE, and ADASYN, each aiming to balance the dataset effectively.

- **ML Models Optimization and Training:**
  - Optimization of Random Forest and K-Nearest Neighbors (KNN) algorithms through hyperparameter tuning and model evaluation.
  - The process involved data preprocessing, train-test split, hyperparameter optimization using the hyperopt library, model training, and evaluation.

- **Testing the Performance:**
  - Performance metrics and confusion matrices were used to evaluate the effectiveness of classifiers and oversampling techniques.
  - A comparative analysis of per-class classification metrics highlighted the impact of oversampling on reducing false negatives and improving recall and f1-scores.

- **Advanced Task - Explainable AI (XAI):**
  - Focus on making machine learning algorithms more transparent and understandable using the SHAP library to analyze the contribution of each feature in predictions.
  - An examination of the importance of features across different oversampling methods showed that certain features consistently contributed to predictions, emphasizing their significance.

It concludes that while over-sampling techniques and model optimizations can improve dataset balance and model performance, the effectiveness varies based on the dataset and problem domain. The advanced task highlights the potential of XAI in providing insights into model predictions and the importance of certain features, leading to more informed decision-making in model development and evaluation.

This project was a joint effort with my colleague Filippo Kubler, we worked together on developing code, analyzing data, and generating visual aids to support our results.
