**Mental Disorder Classification Using Machine Learning**:

---

# Mental Disorder Classification Using Machine Learning

## Project Overview

This project focuses on classifying mental health disorders, including Mania Bipolar Disorder, Depressive Bipolar Disorder, Major Depressive Disorder, and Normal individuals, using machine learning algorithms. The dataset used comprises 120 psychology patients and 17 essential symptoms. The objective is to develop models that accurately diagnose these disorders based on the provided symptoms.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion and Future Work](#conclusion-and-future-work)
- [Contributions](#contributions)
- [Acknowledgment](#acknowledgment)
- [References](#references)

## Dataset

The dataset used in this project includes data collected from a private psychology clinic. It contains 120 patient records, each with 17 essential symptoms. These include various psychological and behavioral attributes such as sadness, euphoria, exhaustion, suicidal thoughts, and more. 

### Features
- **Sadness:** Measure of unhappiness or sorrow.
- **Euphoric:** Extreme joy or excitement.
- **Exhaustion:** Levels of physical or mental fatigue.
- **Sleep Disorder:** Patterns related to difficulty in maintaining sleep.
- *... (more features listed in the detailed documentation)*

## Methodology

The project involves the following steps:
1. **Data Preprocessing:** We ensured data quality by handling missing values and balancing the dataset.
2. **Feature Encoding:** Categorical data was transformed using One-Hot Encoding and Multiclass Encoding.
3. **Exploratory Data Analysis (EDA):** We visualized the distribution of symptoms like sadness across the four categories to understand the relationships between the features and the disorders.
4. **Model Training:** We trained three machine learning models: Random Forest, Support Vector Machine (SVM), and Logistic Regression, using an 80/20 train-test split.
5. **Hyperparameter Tuning:** Grid search was used to find the optimal parameters for each model.

## Modeling

The following machine learning models were applied:

1. **Random Forest:** An ensemble model that constructs multiple decision trees to improve robustness and accuracy.
2. **Support Vector Machine (SVM):** A supervised learning model that separates classes by finding the optimal margin.
3. **Logistic Regression:** A linear model used for binary classification.

## Results

- **Best Model:** The Random Forest model outperformed other models with:
  - Training accuracy: 94.79%
  - Testing accuracy: 91.67%
  - F1-Score: 0.86

  Detailed results and confusion matrix for all models can be found in the report.

## Conclusion and Future Work

The Random Forest model showed the highest performance in diagnosing mental disorders. Future work includes:
- Expanding the dataset to improve accuracy.
- Exploring deep learning methods like neural networks to capture complex patterns within the data.

## Contributions

All team members contributed equally to data collection, preprocessing, model selection, training, evaluation, and result interpretation.
### Team Members

- Abdulrahman Emad  
  Systems and Biomedical Engineering, Cairo University  
  Email: abdulrahman.masoud02@eng-st.cu.edu.eg

- Youssef Ashraf Mohammed  
  Systems and Biomedical Engineering, Cairo University  
  Email: youssef.aziz02@eng-st.cu.edu.eg

- Mourad Magdy  
  Systems and Biomedical Engineering, Cairo University  
  Email: murad.ibrahim02@eng-st.cu.edu.eg

- Mariam Ahmed Said  
  Systems and Biomedical Engineering, Cairo University  
  Email: maryam.abdulmajeed01@eng-st.cu.edu.eg【5†source】. 

You can include this information in the **Contributions** section of the README.
## Acknowledgment

We would like to thank Dr. Inas A. Yassine and Eng. Mirna Bibars for their guidance and mentorship throughout this project.

## References

1. Sekhon, S., & Gupta, V. (2023). Mood Disorder. *NCBI Bookshelf*.
2. Sheline, Y. I. (2003). Neuroimaging studies of mood disorder effects on the brain. *Biological Psychiatry*, 54(3), 338–352.
3. WHO. (2021). Depressive Disorder (Depression).
4. Singh, T., & Rajput, M. (2006). Misdiagnosis of bipolar disorder. *Psychiatry*, 3(10), 57–63.

---
