# Ads_Effectiveness_Assessment
Data-driven assessment on the effectiveness of the current and alternative advertising systems of an online restaurant review platform.
## 📁 Overview
This project analyzes the effectiveness of two different advertising designs for BrownlowReviews, an online restaurant review platform, against a control group where no ads were applied. The goal is to assess if and how effective the advertising programs are, and whether the newly proposed ad design leads to better user engagement compared to the current one.

## 🎯 Objective
Determine which ad format—BrownlowReviews’ existing design or the alternative version—performs better in terms of predicted conversion likelihood, using experimental data. The results aim to guide future marketing decisions and optimize ad spend efficiency.

## 🛠️ Tools & Techniques
- Microsoft Excel
- IBM SPSS Statistics
- SAS Viya
- Data Visualization & Exploratory Data Analysis
- Inferential Statistics
- Statistical Interpretation for Business Decision-Making

## 🧪 Methodology
- Cleaned and pre-processed the dataset
- Descriptive Statistics: Explored key variables and their distributions, Identifying Patterns and Relationships, Generating Hypotheses
- Inferential Statistics: Hypothesis tests including one-way ANOVA and T-tests
- Compared model performance across:
  - Control Group (no ad exposure)
  - Treatment Group 1 (current ad design)
  - Treatment Group 2 (new ad design)
- Interpreted feature importance and group-level conversion probabilities
- Provided marketing recommendations based on data insights

## 📊 Key Findings
- The new ad design (Treatment Group 2) showed a **higher average predicted probability of conversion** than both the control and current ad design.
- The current ad is an improvement over no ad, but only for initial engagement metrics like pageviews and calls.
- The alternative ad consistently delivers stronger performance, especially in calls and reservations.
- The small decline in pageviews under the alternative ad is statistically significant but practically irrelevant when weighed against the substantial gains in conversions.
- Recommendation: **Adopt the new design** for upcoming campaigns, with further A/B testing segmented by user type to refine targeting.

## 📂 Files Included
- `brownlow_data.csv` – Cleaned dataset used for the analysis
- `Business_Report_BrowlowReviews.pdf` – Final business report on key insights to support data-driven decision-making


## 👀 Future Work / Reflection
- Deploy the model to monitor ad performance in real-time
- Incorporate additional behavioral data (e.g., click-through rates, dwell time)
- Test ad performance across different regions or device types
