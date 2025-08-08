**Website Conversion Analysis**

**Overview**
A strategic analysis of user behavior on an e-commerce website to uncover key drivers of conversion. This project identifies behavioral patterns and proposes actionable business recommendations based on data.

**Business Goal & Dataset**
Understand what drives users to convert on the website and recommend actions to increase conversion rates, reduce bounce rate, and optimize user journey.
Source: [Synthetic E-commerce Behavior Data](https://www.kaggle.com/datasets/itsrohithere/comprehensive-synthetic-e-commerce-behavior-data)

**Tools Used**
- Python (pandas, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook
- Git/GitHub

**Project Structure**
website-conversion-analysis/
│
├── data/                 # Synthetic dataset (CSV file)
├── notebook/             # Main analysis & modeling notebook
├── images/               # Visualizations for portfolio
├── README.md             # Project overview
└── requirements.txt      # Dependencies (optional)

**Tech Stack & Tools**
Category:	Tool / Library
Data Handling: pandas, numpy
Visualization: matplotlib, seaborn
Modeling: scikit-learn (Random Forest)
Environment: Jupyter Notebook, GitHub

**Methodology**
- Exploratory Data Analysis (EDA): Identify outliers, understand feature distributions
- Feature Engineering: Handle missing values, encode categorical variables
- Modeling: Logistic Regression, Random Forest (for feature importance)
- Interpretation: Use model results to extract insights and propose strategies.

**Business Question**
"What behavioral factors influence a user’s likelihood to convert on an e-commerce website?"

**Key Findings**
- CTR & Bounce Rate are the strongest predictors	High Click-Through Rate and low Bounce Rate significantly increase conversion probability.
- Longer session durations correlate with higher conversions	Users who spend more time are more likely to complete a purchase.
- Pages viewed is the least influential	Contrary to expectations, more page views doesn’t guarantee conversion if the session lacks engagement.

**Business Recommendations**
- Increase CTR by optimizing product recommendations and ad placements.
- Reduce Bounce Rate through better landing page design and faster load times.
- Track session intent – not just duration, but meaningful engagement (e.g., add-to-cart).

<p align="center">
  <img src="thumbnail.png" width="600"/>
</p>
