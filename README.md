# Analysing Human Relationships

This repository delves into the factors that influence how we choose our partners. By analysing census data and survey responses, I aim to uncover patterns in partner selection and illuminate broader insights into human behaviour.

### Online Dating:

**To Be Started**

### Divorce Predictor Analysis:

**Project Overview**

This project develops a predictive model based on the Divorce Predictors Scale (DPS) derived from Gottman couples therapy research. The dataset consists of responses from 170 couples from various regions of Turkey, providing insights into marital stability based on 54 attributes. Each attribute captures sentiments and behaviors expressed on a scale from 0 (Never) to 4 (Always).

The objective of this analysis is to identify key factors that can predict marital dissolution and to build a predictive model that could potentially aid marriage counselors, relationship therapy platforms, and individuals in understanding and mitigating factors leading to divorce.

**Why This Analysis?**

Marital dissolution is a complex and multifaceted issue that affects numerous aspects of personal and social life. By understanding patterns and predictors of divorce, interventions can be more targeted and potentially more effective. This analysis leverages statistical tools and machine learning models to:

- Identify the most significant predictors of divorce.
- Quantify the impact of various behaviours and attitudes on the likelihood of divorce.
- Develop a robust predictive model that can forecast the probability of divorce based on these predictors.

**Methodology**

Data Exploration
Initial exploratory data analysis (EDA) helped in understanding the distribution of responses and identifying preliminary patterns. Techniques used included:

- Distribution analysis using histograms.
- Correlation analysis to understand the relationships between different variables.

Statistical Testing
Mann-Whitney U tests were conducted to ascertain the differences in responses between couples who are divorced and those who are not, helping identify statistically significant predictors.

Feature Selection and Dimensionality Reduction
Principal Component Analysis (PCA): Used to reduce the dimensionality of the dataset while retaining 95% of the variance, resulting in a simplified yet powerful set of features.
Random Forest Analysis: Provided feature importance scores, identifying the most impactful predictors in the dataset.

Predictive Modeling
Logistic Regression: Chosen for its ability to provide probabilities and for the ease of interpretation of its coefficients.
Model Validation: Utilised cross-validation techniques to ensure the model's robustness and generalisability.

**Results**

The model demonstrated excellent predictive performance with an accuracy of nearly 98%, suggesting it can reliably predict divorce likelihood based on the given predictors.

Dataset: https://www.kaggle.com/datasets/andrewmvd/divorce-prediction

### Couple-Zodiac Analysis: Fact or Fiction?

- Astrological Compatibility: Investigating the potential correlation between zodiac signs and relationship success.
- The Power of Belief: Examining why people find meaning in zodiac signs and their compatibility.
- Understanding Behaviour: Studying if belief in zodiac signs influences relationship choices.
- Mitigating Bias: Exploring methods to account for potential biases within the data.
- Informed Partner Selection: Examining the role of prior knowledge (e.g., religion, shared background) in partner preferences.

**Please Note:** This project is an exploration and does not definitively endorse any belief system.
