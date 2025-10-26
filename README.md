# Social Media Effects on Mental Health  
Comprehensive data-science project analyzing how social-media behavior influences mental health indicators using primary and secondary data sources.  

---

## Overview  
This project, developed for **IT362 – Data Science (2024)** at **King Saud University**, investigates the relationship between social-media usage patterns and mental-health outcomes.  
The analysis integrates data collection, preprocessing, exploratory analysis, machine-learning modeling, and fairness evaluation to derive insights that may help inform healthier digital habits.  

---

## Objectives  
- Examine associations between screen time, engagement type, and self-reported stress or anxiety.  
- Combine primary survey data with secondary sources to enrich behavioral patterns.  
- Apply supervised learning to classify mental-health risk levels.  
- Evaluate model fairness and potential bias across demographic groups.  

---

## Dataset  
- **Primary Data:** Custom survey measuring usage frequency, interaction type, and mental-health indicators.  
- **Secondary Data:** Open-source social-media dataset for cross-validation.  
- **Features:** Platform usage hours, post-interaction type, sleep quality, mood index, demographics.  
- **Preprocessing:**  
  - Handling missing values and outliers  
  - Feature normalization and encoding  
  - Merging and balancing primary and secondary datasets  

---

## Methodology  
1. **Exploratory Data Analysis (EDA):** Distribution plots, correlation heatmaps, and group-wise comparison.  
2. **Feature Engineering:** Encoding categorical data, generating engagement metrics, and scaling features.  
3. **Modeling:** Logistic Regression and Random Forest classifiers for risk prediction.  
4. **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC.  
5. **Bias & Fairness Assessment:** Performance gap across gender and age groups.  

---

## Tools & Technologies  
| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python |
| Data Analysis | Pandas, NumPy, Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn |
| Bias/Fairness | AIF360 |
| Environment | Jupyter Notebook |

---

## Results  
- Logistic Regression achieved **84 % accuracy**; Random Forest improved to **90 % (AUC = 0.91)**.  
- Late-night usage and passive scrolling correlated positively with stress and anxiety levels.  
- Fairness evaluation showed a **3 %** performance difference between male and female subgroups—within acceptable bias limits.

  
## Team
Developed collaboratively for IT362 – Data Science (2024), King Saud University.
Team Members:
- Sirin Al-humud
- Raghad Fares
- Refal Alammari
- Alhanouf AldakelAllah
- Doaa Aldobai
- Razan Alkhaluqi

 
- Insights highlight the importance of limiting late-night exposure and promoting active, positive interaction.  

---
