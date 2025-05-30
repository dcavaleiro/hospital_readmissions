# 🩺 Hospital Readmissions Prediction
This project aims to understand and predict hospital readmissions, with the goal of improving healthcare service quality while reducing associated costs. By leveraging machine learning techniques, we analyze patient data to identify factors contributing to readmissions and develop predictive models to assist healthcare providers in decision-making processes.

## 🧠 Project Overview
* **Objective:** Develop predictive models to identify patients at risk of hospital readmission within 30 days post-discharge.
* **Approach:** Utilize machine learning algorithms to analyze patient data, focusing on key indicators that influence readmission rates.
* **Outcome:** Provide insights and tools to healthcare professionals to proactively manage and reduce readmission occurrences.

## 📁 Repository Structure
- `ML2023G36.ipynb`: Jupyter Notebook containing data preprocessing, exploratory data analysis (EDA), model development, and evaluation.
- `MLG36.yaml`: Configuration file detailing the environment setup and dependencies required to run the project.
- `README.md`: Comprehensive documentation of the project, including objectives, methodology, and usage instructions.

## 🛠️ Technologies & Tools
- **Programming Language**: Python
- **Libraries**:
  - Data Manipulation: `pandas`, `numpy`
  - Data Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `imblearn`
  - Statistical Analysis: `scipy`
  - Others: `yaml`, `warnings`
- **Environment**: Jupyter Notebook


1. **Data Preprocessing**:
   - Handle missing values and outliers.
   - Encode categorical variables.
   - Normalize or standardize numerical features.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize distributions and relationships between variables.
   - Identify patterns and correlations that may influence readmissions.

3. **Model Development**:
   - Implement various machine learning algorithms (e.g., Logistic Regression, Decision Trees, Random Forest).
   - Perform hyperparameter tuning to optimize model performance.

4. **Model Evaluation**:
   - Assess models using metrics such as F1-score binary for the binary classification, and the F1-score weighted for the multiclass problem.
   - Compare model performances to select the most effective one.

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/dcavaleiro/hospital_readmissions.git
   cd hospital_readmissions

## Results and conclusion
The observed high rates of readmission among patients with cardiovascular diseases, respiratory disorders, and uncontrolled diabetes underscore the importance of targeted interventions and specialized post discharge care for these populations. Nevertheless, the limited preventability of readmissions emphasizes the need for a comprehensive, patient-centric approach that considers 
factors beyond the hospital's immediate control. 

For the binary classification approach, the best model to deal with this problem was a Random Forest, and in the Kaggle competition we achieved an F1 score of 0.3136. 

For the multiclassification target, the best model is also a Random Forest, with an F1 score of 0.5205. 

It is crucial to acknowledge certain limitations in this study. The data is confined to the United States, potentially impacting the generalizability of findings to regions with different healthcare systems and 
patient demographics. 

Future research could explore the effectiveness of targeted interventions and post-discharge care strategies for high-risk patient groups, aiming to reduce readmission rates. Longitudinal studies tracking patients over an extended period would allow for a more in-depth analysis of readmission trends and the efficacy of interventions over time. Addressing these limitations and building on these findings, future research has the potential to further refine healthcare strategies and policies aimed at minimizing hospital readmissions. 
