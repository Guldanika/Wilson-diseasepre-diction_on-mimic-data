# Predicting Wilson's Disease Using Synthetic Medical Data

### 🌟 **Overview**
This project is an end-to-end machine learning workflow designed to predict **Wilson's Disease**, a rare genetic disorder that affects the liver and other organs. Due to the scarcity of real-world datasets for rare diseases, a **synthetic dataset** was created to replicate realistic medical scenarios, including patient profiles with liver-related conditions. 

This repository provides an excellent example of tackling medical data challenges, such as:
- Working with **imbalanced datasets**.
- Handling **missing values** for crucial biochemical indicators.
- Engineering features for better predictive performance.
- Evaluating models with an emphasis on **sensitivity and specificity**—critical for medical use cases.

---

### 📊 **Dataset**
The dataset simulates patient data, including key medical indicators such as liver function tests, biochemical markers, and demographic attributes. 

Key details:
- It includes cases of various liver diseases, with a specific focus on **Wilson's Disease**.
- Features are engineered to reflect real-world medical patterns.
- Missing values were introduced intentionally to mimic challenges often faced in clinical datasets.

---

### 🔬 **Key Objectives**
1. **Develop a robust predictive model**: Train machine learning models to accurately classify patients with Wilson's Disease.
2. **Handle real-world medical challenges**: Work with imbalanced data, manage missing values, and emphasize interpretability.
3. **Educate and showcase skills**: Provide a clear, reproducible workflow for others interested in applying machine learning in healthcare.

---

### 🛠 **Workflow**
1. **Data Preprocessing**:
   - Cleaned missing data using advanced imputation techniques.
   - Normalized and scaled features for better model performance.
   - Engineered features to enhance predictive power.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizations of feature distributions and correlations.
   - Identification of key indicators associated with Wilson's Disease.

3. **Machine Learning Models**:
   - Various classification algorithms, including Logistic Regression, Random Forest, and XGBoost.
   - Hyperparameter tuning using GridSearchCV.
   - Evaluation metrics: ROC-AUC, Precision-Recall curves, and Confusion Matrix.

4. **Model Evaluation**:
   - Focused on minimizing false negatives to prioritize patient safety.
   - Assessed the impact of imbalanced classes and adjusted thresholds.

---

### 💻 **Technology Stack**
- **Languages**: Python
- **Libraries**: 
  - Data Manipulation: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn, XGBoost
- **Tools**: Jupyter Notebooks, Google Colab

---

### 🔑 **Key Learnings and Insights**
- **Synthetic Data**: How to create realistic datasets to overcome the lack of real-world data for rare conditions.
- **Imbalanced Classes**: Strategies such as oversampling (SMOTE) and precision-recall-focused evaluation.
- **Feature Engineering**: Identifying and engineering the most impactful medical features for better predictions.
- **Threshold Tuning**: Adjusting classification thresholds to minimize false negatives, ensuring the model is medically relevant.

---


### 🤝 **Contributing**
If you have suggestions or want to extend this project with new features or methods, feel free to fork the repository and submit a pull request!

---

### 📢 **About the Author**
Hi, I’m Guldnika! I have a diverse background in analytics, ranging from market research to sociological studies, and I’m passionate about applying machine learning to solve impactful problems in healthcare. Connect with me on [LinkedIn](https://linkedin.com/in/) or check out my other projects on [Kaggle](/https://www.kaggle.com/guldanikaosmonova).

---

### 📌 **Future Directions**
1. Incorporate deep learning models for improved predictions.
2. Explore external validation with publicly available medical datasets.
3. Build an interactive dashboard for clinicians to explore model predictions.

---

Let me know if you’d like any further tweaks or additional sections! 😊

