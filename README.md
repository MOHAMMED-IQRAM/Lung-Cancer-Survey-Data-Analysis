# **Lung Cancer Survey Data Analysis** 📊🧬

## **Project Overview** 🌟

This project focuses on **exploring** and **analyzing lung cancer data** using advanced data science techniques. By following the **OSEMN framework** (Obtain, Scrub, Explore, Model, iNterpret) 🔍, it provides valuable insights into factors contributing to lung cancer, such as age, smoking habits, and chronic diseases. We apply machine learning models to predict the likelihood of lung cancer and compare their performance to optimize for accuracy 🎯.

---

### **Key Objectives** 🎯

- **Explore** relationships between lung cancer and factors like smoking, age, and chronic diseases.
- Use **data visualizations** to highlight trends and correlations.
- Build **machine learning models** (Random Forest 🌲 and Logistic Regression) to predict lung cancer diagnosis.
- **Compare model performance** to ensure the highest prediction accuracy.

---

## **Dataset** 📂

The dataset is sourced from **[Kaggle](https://www.kaggle.com/datasets/nancyalaswad90/lung-cancer)**. It includes several key features, such as:

- **GENDER:** Male/Female
- **AGE:** Patient’s age
- **SMOKING:** History of smoking (Yes/No)
- **CHRONIC DISEASE:** Presence of chronic disease (Yes/No)
- **LUNG_CANCER:** Target variable (Yes/No diagnosis)

---

## **Project Workflow (OSEMN Framework)** 🔍

1. **Obtain**:  
   - The lung cancer dataset is obtained from [Kaggle](https://www.kaggle.com/datasets/nancyalaswad90/lung-cancer).

2. **Scrub**:  
   - The dataset is cleaned and preprocessed. Categorical values (e.g., "Yes", "No") are converted into numerical values for modeling.

3. **Explore**:  
   - Exploratory Data Analysis (EDA) is conducted to understand relationships. **Visualizations** like count plots and correlation heatmaps are used to identify trends and correlations.

4. **Model**:  
   - Two models are developed to predict lung cancer:
     - **Random Forest** 🌲 (Accuracy: 96.77%)
     - **Logistic Regression** (Accuracy: 88.71%)

5. **iNterpret**:  
   - We evaluate the models using accuracy scores, **confusion matrices**, and **ROC curves**. The **Random Forest model** outperforms, achieving more reliable predictions.

---

## **Results and Insights** 💡

- **Exploratory Analysis**:  
  Significant correlations were found between **smoking**, **chronic diseases**, and lung cancer diagnosis. Visualizations helped clarify the impact of these factors on patient outcomes.

- **Model Performance**:  
  - **Random Forest** 🌲 achieved **96.77% accuracy**, outperforming **Logistic Regression** (88.71%).  
  - The **ROC curve** with an **AUC of 0.70** highlights solid model performance for detecting lung cancer.

---

## **Conclusions** 🔬

This project demonstrates how data science and machine learning can predict lung cancer based on patient data. By examining key factors like smoking and chronic diseases, we developed predictive models that can aid in **early detection** and **treatment planning** 🏥.

- The **Random Forest model** is the most effective in this context, with strong predictive accuracy.
- These insights could help medical professionals better identify high-risk individuals and prioritize screening efforts.

---

## **Acknowledgements** 🙏

We would like to thank **Kaggle** for providing the lung cancer dataset, which is publicly available [here](https://www.kaggle.com/datasets/nancyalaswad90/lung-cancer).

---
