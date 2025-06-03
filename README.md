# Workcation-Behavior
This project analyzes trends in workcations—a hybrid model combining work and vacation—based on survey data. It involves data preprocessing, exploratory analysis, and predictive modeling using decision trees.

📊 Project Overview
The goal of this project is to:
- Understand user behavior and preferences around workcations.
- Identify key factors influencing the likelihood of individuals visiting a workcation destination.
- Built a decision tree classifier to predict visiting behavior.

📁 Dataset
The dataset, imported from Response Final- workcation - Form Responses 1.csv, includes survey responses with variables categorized into:
- Opinions & Interests (OIQ1, OIQ2, OIQ3)
- Usage Frequency Attributes (UFA1, UFA2, UFA3)
- Satisfaction Metrics (S1, S2, S3, S4)
- Influence on Travel Decisions (IVTD1, IVTD2, IVTD3)
- Binary variable D6 representing visiting behavior, converted into the target variable Visiting Behaviour.

🔧 Methods Used
- Data Cleaning & Preprocessing: Dropping unnecessary columns, label encoding.
- Exploratory Data Analysis: Summary statistics and visualizations using seaborn and matplotlib.
- Machine Learning: Decision Tree Classifier using scikit-learn.
- Evaluation: Accuracy metric for classification performance.

🧰 Technologies Used:
Python
- pandas
- matplotlib
- seaborn
- scikit-learn

  🔎 Key Influential Factors in Predicting Workcation Behavior
Feature	Interpretation
- IVTD2: Strongest predictor: how much external travel factors influence the decision
- UFA1: Frequency of using certain work or travel-related features
- S3, S4:	Satisfaction levels with prior workcation or remote work setup
- IVTD3: Secondary travel influence factor
- EWOM2: Peer opinion and recommendations (Electronic Word-of-Mouth)

🧠 Insights
- Individuals highly influenced by travel-related factors (IVTD2, IVTD3) and those satisfied with remote work conditions (S3/S4) are more likely to consider workcations.
- External influence from peers (EWOM2) also plays a role.
- There are groups unlikely to go on workcations, especially those with low satisfaction and low influence factors.

✅ Business Implications
- Tourism companies and remote work platforms can target people with high travel decision influence and positive satisfaction scores.
- HR policies supporting flexible remote work may increase workcation interest in specific employee segments.

👤 Author : 
**Ojasvi Gupta**
