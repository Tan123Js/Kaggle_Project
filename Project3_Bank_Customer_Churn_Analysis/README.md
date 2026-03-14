**Project Title**:

**Bank Customer Churn Analysis**

**Objective**:

To predict bank customer churn and identify the key drivers influencing customers to leave, enabling proactive retention strategies and improving overall customer engagement.

**Dataset**:

The analysis uses the Kaggle Bank Customer Churn dataset, containing 10,000 customers with features such as Credit Score, Age, Tenure, Balance, NumOfProducts, IsActiveMember, Geography, and Exited (churn indicator).

**Key Findings**:

- **Top predictors of churn**: NumOfProducts, IsActiveMember, Age, Geography (Germany), Balance
- **High-risk segments**: Mid-aged, multi-product, low-activity customers.
- **Geographical hotspot**: Germany accounts for most high-risk churners.
- **Model performance**: XGBoost achieves **ROC-AUC 0.8630**, **Accuracy 0.87**, **Macro F1 0.75**
- **Threshold optimization**: Lowering probability threshold from **0.50 -> 0.35** increases churn recall from **46.5% -> 60.69%**

**Business Implication**

The bank can proactively identify high-risk customers before churn occurs, allowing targeted retention programs. Key factors such as product engagement, account activity, age, and geography should inform campaign design, resource allocation, and early warning systems. 

**Strategic Recommendation**

1.**Targeted Retention Campaigns**: Focus on mid-aged, multi-product, low-activity customers. 

2.**Enhance Engagement Programs**: Incentivize account activity and loyalty to reduce churn probability. 

3.**Regional Resource Allocation**: Prioritize retention efforts in Germany, the highest-risk region. 

4.**Dynamic Probability Thresholding**: Adjust thresholds to capture additional potential churners efficiently.
