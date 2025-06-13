📊 Term-Deposit-Marketing-2020

A data-driven analysis & predictive model for term deposit subscriptions in retail banking.
🧩 Project Overview

This Jupyter notebook explores a 2020 Portuguese banking marketing campaign focused on term deposit subscriptions. It walks through:

    Exploratory Data Analysis (EDA): Uncovering patterns and customer behavior.

    Preprocessing: Handling missing data, encoding categorical variables, feature scaling.

    Modeling: Training and comparing random forest, linear discriminant analysis, bagging.

    Evaluation: Comparing models via accuracy, precision, recall, ROC-AUC, and confusion matrices.

    Results & Insights: Identifying key predictors and offering business recommendations.

🧭 Step-by-Step Project Flow

    Data Ingestion
    Load dataset bank-additional-full.csv, inspect and understand features like age, job, marital status, campaign details, and the target variable (y = “yes”/“no”).

    Exploratory Data Analysis

        Check missing values and variable types

        Visualize distributions (age, balance, duration)

        Analyze categorical relationships (job, marital, education)

        Explore target imbalance and correlations

    Data Preprocessing

        Clean missing or “unknown” entries

        One-hot encode categorical features

        Scale continuous variables

        Split into training and testing sets

    Modeling Pipeline

        Train multiple classifiers: random forest,  linear discriminant analysis, bagging

        Use cross-validation and grid search for hyperparameter tuning

        Generate predictions

    Evaluation & Comparison

        Present accuracy, precision, recall, F1-score, and ROC-AUC

        Plot confusion matrices and ROC curves

        Compare performance across models

    Feature Importance

        Display feature importance from tree-based models

        Interpret drivers like call duration, previous campaign outcome, balance

    Business Insights & Recommendations

        Suggest targeting strategies based on top predictors

        Optimization of marketing resource allocation

        Risk assessment: model limitations and fairness considerations

    Conclusion & Next Steps

📌 Detailed Explanations
Why Each Step Matters

    EDA guides data cleaning and hypothesis formation.

    Preprocessing ensures data suitability for modeling and feature scaling consistency.

    Evaluation with multiple metrics prevents misleading conclusions.

    Feature importance grounds recommendations in data rather than intuition.

✅ Key Results

    Most influential features:

        duration (call length): top predictor.

        previous campaign outcome (“success”/“failure”)

        age, jobs, marital status.

    Strategic insights:
    Focus on customers with longer history and previous successful contacts—allocate marketing budget accordingly.

🏁 Concluding Remarks

This project demonstrates strong capabilities in data science and business analytics:

    End-to-end workflow: from raw data to actionable business insights

    Technical skills: data wrangling, visualization, machine learning

    Communication: clear interpretation of results and strategic recommendations

    Business impact: identifying cost-effective, targeted marketing approaches

📥 Interested? Let’s Connect!

I'm eager to discuss how this project reflects my analytical rigor, problem-solving mindset, and ability to translate data insights into business value.
Feel free to reach out: crozierchris23@gmail.com or via LinkedIn: https://www.linkedin.com/in/chrislcrozier23/.
