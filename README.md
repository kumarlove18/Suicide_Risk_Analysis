# Suicide Risk Analysis Using Machine Learning

This project analyzes factors influencing suicidal behavior using machine learning models. The study leverages survey data provided by UDAYA, a collaboration between **Harvard University** and **Population Council**, focusing on adolescents in Bihar and Uttar Pradesh.

---

## 📁 **Directory Structure**

├── DATASET/

│   └── UP_BH_Individual_UDAYA 2_Uploaded.dta # Original dataset (UDAYA survey data)

├── preprocess.ipynb # Data preprocessing and feature selection

├── ML models and results/

│   └── model.ipynb # Machine learning models and results

│  └── data visualization.ipynb # Feature analysis and visualizations

├── research_papers/ # Reference research papers (PDF format)

├── extract.ipynb # Further analysis using additional datasets

├── README.md # Project documentation

├── Myfile.doc #data description

---

## 📊 **Data Description**

The dataset `UP_BH_Individual_UDAYA 2_Uploaded.dta` consists of individual-level data gathered during the **UDAYA Adolescent Survey (2015-16)** in Bihar and Uttar Pradesh. It includes responses to multiple questions covering:

- **Demographics**: Age, gender, family history, and household details.
- **Behavioral Factors**: Drug or alcohol use, schooling, and domestic violence.
- **Social Indicators**: Close friends count, prior family suicides, etc.

**Source**:  
[Harvard Dataverse - UDAYA Adolescent Survey](https://dataverse.harvard.edu/dataset.xhtml)

---

## 🚀 **ML Models Implemented**

1. **Decision Tree**
2. **Random Forest**
3. **Boosting Models** (XGBoost, Gradient Boosting)
4. **Neural Network**
5. **Support Vector Machine (SVM)**
6. **Logistic Regression**

---

## 🛠 **Preprocessing and Feature Engineering**

- **Null Value Handling**: Interpolation using parallel feature analysis.
- **Feature Selection**: Conversion of numeric data to class-based data and one-hot encoding.
- **Imbalanced Data**: Used **SMOTE (Synthetic Minority Over-sampling Technique)** to address class imbalance.

---

## 🔍 **Results and Observations**

- **Tree-based Models** (Decision Tree, Random Forest, Boosting) performed best due to the binary and categorical nature of features.
- **Neural Networks** performed well but were prone to overfitting.
- **SVM and Logistic Regression** underperformed due to non-linear relationships in the data.

**Key Factors Affecting Suicide Risk**:

- Drug or alcohol use
- Schooling
- Family history of suicide
- Gender and age range
- Domestic violence in the household
- Count of close friends

---

## 📊 **Further Analysis**

Additional datasets are available in the **DATASET/** folder. Use the `extract.ipynb` script for further feature engineering and analysis.

---

## 🎥 **Presentation**

Find the detailed project presentation here:  
[Suicide Risk Analysis - Canva Presentation](https://www.canva.com/design/DAGYJMrpuAA/jl86V1kwpe1c8wpasxmU1g/edit?utm_content=DAGYJMrpuAA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## 📌 **Conclusion**

- Tree-based machine learning models performed best due to the **binary** nature of most features.
- SMOTE was critical for handling class imbalance.
- Neural networks were effective but prone to overfitting.
- Linear models like **SVM** and **Logistic Regression** failed due to the non-linear relationships in the data.

---

## 💡 **Future Work**

- Expand feature analysis using temporal or contextual data.
- Integrate additional datasets for broader generalization.
- Optimize neural networks to reduce overfitting.

---

## ✍️ **Acknowledgment**

This study was conducted using data from UDAYA, supported by Harvard University and Population Council. Special thanks to the UDAYA Adolescent Survey team for providing valuable insights.
