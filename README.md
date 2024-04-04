# Cardiovascular_Risk_Prediction_Classifcation

## INTRODUCTION
Welcome to our cardiovascular health prediction project! Leveraging data from an ongoing study in Framingham, Massachusetts, we've delved into predicting the 10-year risk of coronary heart disease (CHD) in patients. With a dataset comprising 3400 records and 17 diverse attributes, including demographic, behavioral, and medical factors, our journey began. Through meticulous data preprocessing involving imputation, outlier removal, and feature engineering, we curated a robust dataset. Addressing data imbalance, we employed advanced techniques like SMOTE and Tomek links, ensuring balanced class distribution.

Our evaluation process focused on recall, a critical metric in identifying individuals at CHD risk. After thorough analysis, the Neural Network (tuned) emerged as our ultimate model choice, highlighting our dedication to precision. This project underscores the transformative power of machine learning in healthcare. By integrating advanced analytics with healthcare insights, we've not only predicted CHD risk accurately but also demonstrated the positive impact technology can have on patient outcomes. Join us in this impactful journey toward informed decision-making and enhanced patient care.

## PROJECT DESCRIPTION:
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham,
Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future
coronary heart disease (CHD). The dataset provides the patients' information. It includes over
3400 records and 17 attributes. Each attribute is a potential risk factor. There are both
demographic, behavioral, and medical risk factors.

![Classification_Cardiovascular_Risk_Prediction_8e8765e394](https://github.com/OmprakashDebata/Cardiovascular_Risk_Prediction_Classifcation/assets/128419635/d3f821a6-206f-414a-9273-e964cceb7b98)

## PROBLEM STATEMENT
In the bustling town of Framingham, Massachusetts, researchers are tirelessly studying residents' hearts to foresee their future. With a treasure trove of data from over 3400 individuals, this project dives deep into understanding who might face the risk of coronary heart disease (CHD) in the next 10 years. The challenge? Predicting this risk accurately based on 17 different aspects of their lives, from age and behavior to medical history. Our mission is to harness this data to build a model that can identify those at risk, providing crucial insights for healthier hearts and happier lives. Join us in this endeavor to unlock the secrets hidden within these numbers and make a difference in cardiovascular health!

## HYPOTHESIS 
In the realm of hypothesis testing, we set out to unravel the intricate relationship between daily cigarette consumption (cigsPerDay) and the TenYearCHD (Ten-Year Coronary Heart Disease) risk. Our null hypothesis posited that there is no substantial connection between the number of cigarettes smoked daily and the likelihood of developing CHD within a decade. Conversely, the alternative hypothesis challenged this notion, suggesting a meaningful association between these variables.

Upon conducting an in-depth analysis using Ordinary Least Squares (OLS) regression, the results painted an intriguing picture. The model, meticulously scrutinized, revealed a surprising revelation. The coefficient for 'cigsPerDay' stood at 0.0021, indicating a subtle yet significant impact. Moreover, the p-value, a crucial indicator in hypothesis testing, was calculated to be 7.39e-05, which is remarkably smaller than the conventional significance level of 0.05. This exceptionally low p-value provided compelling evidence to reject the null hypothesis, paving the way for the acceptance of the alternative hypothesis.

In essence, our statistical exploration uncovered compelling evidence linking daily cigarette consumption to the risk of developing coronary heart disease over a ten-year span. These findings serve as a beacon, guiding further research and public health initiatives to mitigate this risk and foster a healthier tomorrow.

## MODEL BUILDING
- Logistic Regression
- Naive Bayes Classification
- Support Vector Classifier
- XGBoost Classifier
- Neural Network Classifier

These models were fine-tuned using techniques such as GridSearchCV.

## CONCLUSION
In conclusion, this project stands as a testament to the transformative potential of machine learning in healthcare, specifically in predicting the 10-year risk of coronary heart disease (CHD). Leveraging a robust dataset from an ongoing cardiovascular study in Framingham, Massachusetts, our meticulous approach to data preparation and analysis yielded profound insights. Through comprehensive preprocessing steps, including handling missing values, outlier removal, and feature transformations, we curated a high-quality dataset. Key techniques such as the creation of the 'pulse pressure' feature, addressing multicollinearity, and rebalancing class distribution using SMOTE and Tomek links were pivotal in our methodology.

The heart of our success lies in the strategic selection of the Neural Network model, fine-tuned to perfection. This model, chosen based on its exceptional recall score, demonstrated a keen ability to identify individuals at risk, underscoring our commitment to accuracy. Furthermore, our focus on addressing data imbalance showcased our dedication to nuanced modeling techniques, ensuring a comprehensive understanding of both positive and negative outcomes.

This project not only showcases the symbiotic relationship between advanced analytics and healthcare but also emphasizes the criticality of methodical data preparation. By investing time and effort into refining our data, selecting pertinent features, and choosing the optimal model, we achieved precise predictions. These insights are not just confined to the realm of healthcare; they serve as a beacon, illuminating the path for impactful decision-making across diverse fields. This journey exemplifies the true potential of machine learning, not merely as a technical tool but as a catalyst for informed, impactful, and empathetic advancements in healthcare and beyond.

If you have any feedback, please reach out to me at omprakashdebata12@gmail.com






