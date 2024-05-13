# Workforce-Departure-Analysis
![image](https://github.com/Akxsh-07/Workforce-Departure-Analysis/assets/142329024/51255ee1-15a4-4486-ab50-473f1cbba232)

---
**Hi there, this is my final year college project**
# Aim of this project
- To analyze and predict the workforce departures (also widely known as Employee Attrition), using various Machine Learning algorithms
- To enable the HR to predict the probablistic rate of Employee Turnover based on previous records. Since there are external factors such as health issues, and family reasons etc, we would be able to only predict the probability or the rate of chances of employee attrition.
---
## Dataset used in this project

- The dataset is accessed from Kaggle titled "IBM HR ANALYTICS EMPLOYEE ATTRITON AND PERFORMANCE".
- The dataset consisted of 1470 rows, and 35 attributes. Through the process of data cleaning, we extracted only the key attributes which influenced the Employee Attrition.
---
### Methodologies and approach

- The most important aspect which people tend to overlook is whether the dataset is balanced or not.
- Due to dataset imbalance, we are using a special oversampling approach called as SMOTE (Synthetic Minority Oversampling Technique).
> **[More info about SMOTE method](https://arxiv.org/abs/1106.1813)**
---
### Final Accuracy Reports

| **Algorithm**| Accuracy |
| ----------- | ----------- |
|**Random Forest (with SMOTE)** | 97.10 % |
| **Decision Tree**| 75.60 % |
| **Logistic Regression**| 84.89 % |
| **SVM Classifier**| 81.92 % |
|**XGBoost Algorithm**| 84.79 % |
---
### Not utilizing Deep Neural Networks (Deep Learning Alogrithms)
- Since this is a medium sized dataset and Random Forest was able to achieve a higher accuracy of 97%, the use of DL algorithms often to overfitting, longer execution times and also extensive computational resources.

---

### Future Scope and further developments

- *Implementation of NLP in the future might help with the sentiment analysis of the employee and make us predict if the employee might leave the organization for personal or any undefined reasons which cannot be contained in a dataset.*
