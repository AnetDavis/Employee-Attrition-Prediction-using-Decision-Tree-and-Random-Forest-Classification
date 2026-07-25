# Employee Attrition Prediction using Decision Tree and Random Forest Classification

**Author:** Anet Davis  
**Registration Number:** 23BHI10146  
**Application Number:** IN26011852  
**Batch Number:** 1A  
**Email ID:** anet.23bhi10146@vitbhopal.ac.in  

## Objective
The objective of this project is to build and compare **Decision Tree** and **Random Forest** classification models to predict employee attrition. The models use employee demographic, professional, and work-related information to identify employees who are likely to leave the organization.

## Dataset
- **Dataset:** IBM HR Analytics Employee Attrition & Performance Dataset
- **Source:** https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
- **Total Records:** 1,470
- **Target Variable:** Attrition (Yes/No)
- **Features:** Employee age, monthly income, job role, education, department, overtime, years at company, job satisfaction, and other work-related attributes.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Methodology
1. Loaded and explored the dataset.
2. Checked for missing values and removed unnecessary columns.
3. Encoded categorical variables using Label Encoding and One-Hot Encoding.
4. Split the dataset into **80% training** and **20% testing** sets.
5. Trained a **Decision Tree Classifier** and a **Random Forest Classifier**.
6. Evaluated both models using **Accuracy, Precision, Recall, F1-Score,** and **Confusion Matrix**.
7. Compared the performance of both models and analyzed the important features.

## Results

| Model | Accuracy |
|--------|----------|
| Decision Tree | 75.9% |
| Random Forest | 82.7% |

### Key Observations
- Random Forest achieved better overall accuracy than Decision Tree.
- Decision Tree performed better in identifying employees who actually left the organization (higher recall).
- Important features included **Monthly Income, Age, Total Working Years, OverTime,** and **Years at Company**.
- The dataset is imbalanced, with fewer employees leaving than staying, which affects model performance.

## Conclusion
Both models successfully predicted employee attrition, with **Random Forest** providing the highest overall accuracy. However, **Decision Tree** showed better performance in detecting employees who actually left the organization. Further improvements such as **class balancing**, **hyperparameter tuning**, and **feature engineering** can enhance prediction performance and make the models more suitable for real-world HR analytics.
