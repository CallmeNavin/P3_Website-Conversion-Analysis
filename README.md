**Website Conversion Analysis**

**A. VERSION 1 - EXPLORATORY ANALYSIS & BASELINE MODELING**

**A. Project Overview**

- A strategic analysis of user behavior on an e-commerce website to uncover key drivers of conversion. This project identifies behavioral patterns and proposes actionable business recommendations based on data.
- Understand what drives users to convert on the website and recommend actions to increase conversion rates, reduce bounce rate, and optimize user journey.
- "What behavioral factors influence a user’s likelihood to convert on an e-commerce website?"

![Overview](https://github.com/CallmeNavin/P3_Website-Conversion-Analysis/blob/main/Version%201/Visualization/Overview.png)
_Findings Visualization_

**B. Dataset Information**

**Source**

- Synthetic E-commerce Behavior Data (from Kaggle).

https://www.kaggle.com/datasets/itsrohithere/comprehensive-synthetic-e-commerce-behavior-data

**C. Methodology**

- Exploratory Data Analysis (EDA): Identify outliers, understand feature distributions
- Feature Engineering: Handle missing values, encode categorical variables
- Modeling: Logistic Regression, Random Forest (for feature importance)
- Interpretation: Use model results to extract insights and propose strategies.

**D. Key Findings & Actionable Plans**

**Key Findings**
- CTR & Bounce Rate are the strongest predictors: High CTR and Low Bounce Rate significantly increase conversion probability.
- Longer session durations correlate with higher conversions: Users who spend more time are more likely to complete a purchase.
- Pages viewed is the least influential	Contrary to expectations: More page views doesn’t guarantee conversion if the session lacks engagement.

**Actionable Plans**
- Increase CTR by optimizing product recommendations and ad placements.
- Reduce Bounce Rate through better landing page design and faster load times.
- Track session intent – not just duration, but meaningful engagement (add-to-cart, etc).

**B. VERSION 2 - ENHANCE VISUALIZATION, INSIGHTS & ACTIONABLE PLANS**

**A. Enhance Overview**

- This second version enhances the initial analysis by transforming Python-based findings into an interactive Power BI dashboard. The goal is to validate the earlier insights with clear visual storytelling and business-oriented presentation.

![Dashboard Visulization](https://github.com/CallmeNavin/P3_Website-Conversion-Analysis/blob/main/Version%202/Visualization/Dashboard.png)
_From Engagement to Purchase: Conversion Insights_

**B. Methodology**

- Using a Funnel Chart and Heatmap, the analysis highlights how CTR and Bounce Rate drive conversions, while also demonstrating the drop-off points in the user journey.

**C. Key Findings & Actionable Plans**

_**Key Findings**_

- In this synthetic dataset, only 2 sessions had CTR = 0, so the top stage of the funnel (Session → Engaged) appears almost invisible. In a real-world dataset, we would expect a larger drop-off at this step.
- There were ~4.18K sessions on the site; almost all of them were “Engaged” (CTR > 0). Among these, ~4.17K turned into Purchases → meaning once users clicked, they almost certainly purchased. This indicates that conversion is primarily determined after user engagement, which makes the dataset unrealistic compared to real-world behavior.
- Higher CTR is associated with higher Conversion, while lower Bounce Rate also leads to higher Conversion.

_**Actionable Plans**_

- Increase click-through rate by improving content attractiveness, recommendations, and ad placements.
- Raise CTR and Reduce Bounce Rate by optimizing landing page quality and speed while ensuring engaging, relevant content.

**D. About Me**

Hi, I'm Navin (Bao Vy) – an aspiring Data Analyst passionate about turning raw data into actionable business insights. I’m eager to contribute to data-driven decision making and help organizations translate analytics into business impact. For more details, please reach out at:

🌐 LinkedIn: https://www.linkedin.com/in/navin826/

📂 Portfolio: https://github.com/CallmeNavin/
