# 👁️ Predicting Digital Eye Strain & Vision Risk Using Lifestyle Behavioral Indicators

A machine learning project that predicts a user's risk of developing Computer Vision Syndrome (CVS) by analyzing daily digital habits and physiological micro-behaviors. This research shifts the focus from reactive clinical diagnoses to preventative behavioral indicators, providing a data-driven foundation for accessible health monitoring.

## 📖 Overview

In the post-pandemic era, screen dependency has skyrocketed across all age groups, leading to a massive global surge in Digital Eye Strain. Current diagnostic methods are entirely reactive—treating the issue only after symptoms like dry eyes and headaches become severe. Furthermore, traditional predictive models often rely on complex medical imaging or focus solely on specific occupational groups (like IT professionals), ignoring the daily habits of the general population. 

This project leverages machine learning to analyze a primary dataset of digital device habits, environmental factors, and biological behaviors (e.g., viewing distance, lighting, hydration, blink awareness). By identifying the specific modifiable lifestyle factors that drive eye strain, this project provides a robust, accessible solution for early risk prediction that requires no special hardware or clinical visits.

## ✨ Key Features

* **Primary Data Collection & EDA:** Analyzed a structured survey dataset capturing a diverse, general demographic (ages 18 to 60+) to measure modern metrics like continuous screen usage, room lighting, daily water intake, and conscious blinking.
* **Model Comparison:** Evaluated and compared supervised machine learning classifiers, specifically utilizing Random Forest (RF) and Decision Tree (DT) algorithms to categorize individuals into "At Risk" or "No Risk" classes.
* **Preventative Health Framework:** Shifted the analytical framework to prioritize "Recall" in model evaluation, ensuring the system acts as a safe early-warning tool that minimizes False Negatives (missing genuinely at-risk users).

## 📊 Key Findings & Results

* **Best Model:** The Random Forest classifier achieved the highest overall accuracy, demonstrating superior stability against the natural noise found in self-reported survey data.
* **Accuracy vs. Recall Tradeoff:** Random Forest achieved a baseline accuracy of 61.90% with strong precision. However, the Decision Tree model achieved a remarkable Recall of 72.73% —a crucial metric in health contexts, proving highly effective at catching actual risk cases.
* **Behavioral Insights:** Scatter plot visualizations mathematically validated the "20-20-20" rule; users engaging in continuous screen time for over 2 hours without breaks overwhelmingly fell into the high-risk category.
* **Feature Importance:** The model proved that non-visual physiological factors are critical predictors. Users who drank less than 1 liter of water daily and paid no attention to their blink rate reported the highest frequency of symptoms.

## 🛠️ Technologies

* **Language:** Python
* **Environment:** Jupyter Notebook
* **Data Manipulation & Analysis:** NumPy & Pandas 
* **Machine Learning:** Scikit-Learn (Model implementations: `RandomForestClassifier`, `DecisionTreeClassifier`, `LabelEncoder`, `StandardScaler`) 


* **Data Visualization:** Matplotlib & Seaborn
