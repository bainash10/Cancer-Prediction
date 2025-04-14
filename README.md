This project involves analyzing and preparing the Breast Cancer Wisconsin Diagnostic Dataset for machine learning. It focuses on identifying whether tumors are benign (non-cancerous) or malignant (cancerous) based on medical features like size, shape, and texture.

The ultimate goal was to understand the data, clean it, and train a model that can predict whether a tumor is benign or malignant.

## What I did in this project:

- Loaded the dataset and explored its structure to understand the type of information it provides.
- Cleaned the data by checking for missing or duplicate values and removing irrelevant columns like `id`.
- Visualized correlations between features to identify which ones were most important.
- Converted categorical values in the `diagnosis` column (M/B) into numeric values (1/0) so that the model could process them.
- Prepared the dataset for training a classification model.

## Model Performance

After preparing the dataset, a classification model was trained, and it achieved excellent performance:

- Accuracy: 0.98  
- Precision: 0.97  
- Recall: 0.98  
- F1 Score: 0.98  

These results show that the model is highly reliable in detecting whether a tumor is cancerous or not.

## Final Outcome

The project successfully transforms raw medical data into a clean and machine-learning-ready format, followed by building a high-accuracy classification model. It lays a solid foundation for developing an intelligent cancer detection system.

---

Developed by Nischal Baidar
