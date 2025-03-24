# 🏭 Carbon Futures Price Prediction

## 📈 Project Overview

This project aims to predict the carbon futures price for the upcoming 60 days using machine learning algorithms. The original dataset, `Substantial_environment_carbonpred_variables_20240907.csv`, was preprocessed to select highly relevant features.

I implemented and trained **Support Vector Machine (SVM)** and **Random Forest** models for the prediction task. During the training and modeling process, several techniques were applied to enhance performance, including:

- **Pearson Correlation Coefficient (PCC)** for feature selection  
- **Sliding Window** approach for time-series modeling  
- **Cross Validation** to ensure model robustness

---

## 📊 Dataset Description

The original dataset used in this project is:

- `Substantial_environment_carbonpred_variables_20240907.csv`

This file contains various environmental and market-related variables for carbon futures price prediction. To identify the most relevant features, the notebook:

- `data_preprocessing.ipynb`

was used to perform feature selection based on correlation coefficients, helping to improve model accuracy by focusing on high-impact variables.
![correlation matrix](https://github.com/user-attachments/assets/c6955ddb-18bf-4e9a-9ad6-31e1d7e30a25)
![barplot](https://github.com/user-attachments/assets/db70012a-b573-4868-9a3e-ab5063a0aafe)



---

## 🧠 Model Training

The model training and analysis were carried out using the following notebooks:

- `data_RF.ipynb` – for training and evaluating the **Random Forest** model  
- `data_SVM_0103.ipynb` – for training and evaluating the **Support Vector Machine (SVM)** model

Both notebooks include model training procedures, performance evaluation, and final prediction analysis.

---

## 📉 Results
![rf_train_new](https://github.com/user-attachments/assets/f6d16353-16fd-4142-a458-cd272308d0c0)
![SVM_new_sigmoid](https://github.com/user-attachments/assets/e6c40d96-b612-4037-86ea-d579b0a95b3c)
![SVM_new_linear](https://github.com/user-attachments/assets/2fbb3e3f-548a-4dab-af71-353af0d09c1c)
![SVM_new_rbf](https://github.com/user-attachments/assets/6617c31f-3962-4a40-bbce-b7c29202ee01)



