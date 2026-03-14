**Project Title**:

**Online Retail II - UCI DATASET**

**Objective**

Analyze retail transaction data to understand revenue distribution, product performance, and customer retention patterns, and identify opportunities to improve customer lifetime value and revenue stability.

**Dataset**

The dataset contains historical e-commerce transactions from March 2010 to August 2010, including product purchases, quantities, revenue values, and customer identifiers.

**Key Findings**:

**1.Revenue is highly concentrated in the UK market**

The Unitied Kingdom accounts for **84.31%** of total revenue, indicating a strong geographic dependency and high sensitivity to UK market fluctuations. 

**2.Revenue follows a Pareto distribution**

Pareto analysis  shows that **27.24%** of customers generate **80%** of total revenue, highlighting a core group of high-value “Whale” customers who drive the business.

**3.Customer retention declines rapidly after the first purchase**

Cohort analysis reveals a critical retention drop, plummeting from 100% to 38% within the first month. Most cohorts show a consistent decline in repeat purchases over time.

**4.Sales and Value distribution are highly skewed**

Frequency distribution (log scale) and revenue statistics (Mean vs. Median) show a **highly right-skewed** pattern, where a limited number of transactions and elite customers generate disproportionately large value.

**5.Product sales are unevenly distributed**

A small subset of product catalog drives the majority of sales volume, identifying a “Hero Product” portfolio critical to revenue stability.

**Business Implications**:
* **Geographic Risk**: Over-reliance on a single market (UK) creates a structural risk; any local economic downturn will directly impact the entire revenue stream. 
* **Retention Leakage**: The 62% drop-off in the first month indicates a "Leaky Bucket" problem, suggesting that current customer onboarding or post-purchase engagement is not effectively building habit. 
* **Concentration Vulnerability**: Since 27.24% of customers carry the business, the churn of even a small number of these "Champions" could lead to significant financial loss. 
* **Inefficient Marketing**: A "one-size-fits-all" strategy is likely wasting budget on low-value segments while under-serving the high-value elite.

**Strategic Recommendations**

* **Prioritize High-Value Retention**: Implement a VIP loyalty program or personalized "High-Touch" service for the **top 27%** (identified via RFM) to secure the core revenue base. 
- **Target the "First-Month" Gap**: Introduce automated re-engagement campaigns (e.g., personalized offers or "Thank You" sequences) within 15 days of the first purchase to stabilize the **38% retention floor**. 
- **Optimize via Association Rules**: Use Market Basket Analysis to identify product affinities among top-performing items to create high-conversion bundles and increase Average Order Value (AOV). 
- **Geographic Diversification**: Use data from the UK’s "Hero Products" to inform expansion strategies into secondary markets, reducing the risk of single-market dependency.
