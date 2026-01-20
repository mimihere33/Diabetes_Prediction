
#  Diabetes Prediction Using Machine Learning

##  Overview

This project focuses on building an end-to-end **machine learning classification pipeline** to predict the likelihood of diabetes in individuals based on healthcare and lifestyle-related features. The project demonstrates the complete applied ML workflow — from exploratory data analysis to model training and evaluation — using a real-world dataset.

The goal of this project is not medical diagnosis, but to showcase practical data analysis and machine learning skills on structured data.

---

##  Objective

* Perform **Exploratory Data Analysis (EDA)** to understand patterns and relationships in healthcare data
* Preprocess and prepare data for machine learning models
* Train and evaluate supervised classification models to predict diabetes occurrence
* Interpret results and extract meaningful insights from the data

---

##  Dataset

* **Source:** Kaggle – Diabetes Prediction Dataset
* **Type:** Structured healthcare data
* **Target Variable:** Diabetes (binary classification)

⚠️ **Note:** The dataset is not included in this repository due to Kaggle’s licensing restrictions. Please download it directly from Kaggle using the link below:

🔗 *https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset* 

---

##  Exploratory Data Analysis

Key EDA steps performed:

* Analysis of class distribution for diabetes outcome
* Distribution analysis of numerical features such as age and BMI
* Comparison of diabetes occurrence across gender and smoking history
* Correlation analysis using a heatmap to identify influential features

Visualizations were created using **Matplotlib** and **Seaborn** to better understand feature behavior and relationships.

---

##  Machine Learning Approach

* Data preprocessing and feature preparation
* Train–test split for model evaluation
* Supervised classification model training using **Scikit-learn**
* Model evaluation using appropriate performance metrics

The focus of the modeling stage is on understanding performance and behavior rather than aggressive optimization.

---

##  Results

* The trained model demonstrates reasonable predictive performance on unseen data
* Feature analysis highlights health indicators such as **BMI and age** as important factors associated with diabetes risk
<img width="461" height="393" alt="image" src="https://github.com/user-attachments/assets/2c14f6aa-43b2-419a-a1ed-305226b0434a" />
<img width="461" height="393" alt="image" src="https://github.com/user-attachments/assets/404b0351-22e4-45ce-b415-2368d602ba09" />



---

##  Tech Stack

* **Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Scikit-learn
  * Matplotlib
  * Seaborn
* **Environment:** Jupyter Notebook

---

##  How to Run the Project

1. Clone the repository
2. Download the dataset from Kaggle and place it in the project directory
3. Install dependencies:

   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```
4. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook Diabetes.ipynb
   ```

---

##  Learning Outcomes

* Hands-on experience with real-world healthcare data
* Understanding of the end-to-end machine learning workflow
* Improved data visualization and analysis skills
* Practical exposure to classification problems in machine learning

---

##  Disclaimer

This project is for **educational purposes only** and should not be used for real-world medical decision-making.

---

##  Author

**Ishika Shrivastava**

Feel free to connect or provide feedback!
