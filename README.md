# Optimal-Mobile-Ad-Targeting

### TZ Gaming: Optimal Targeting of Mobile Ads
#### Project Overview

This project involves utilizing data science to enhance the efficiency of targeted advertising for TZ Gaming on mobile devices. Faced with the decision of either purchasing additional data for in-house model development or subscribing to Vneta's analytics consultancy service, a series of analyses were conducted. This included logistic regression and model comparison to optimize mobile ad performance, focusing on profit and return on marketing expenditure.

#### Analysis Insights

The logistic regression model and Vneta's proprietary decision tree model significantly outperformed the non-targeted and random targeting strategies in terms of profitability.
Vneta's model, despite its higher cost ($150k), achieved the greatest profitability, justifying its expense over the $50k cost for the logistic model data.
Comprehensive evaluation techniques such as multicollinearity testing, omitted variable bias, decile analysis, gains curves, and a confusion matrix (including accuracy, recall, precision, specificity) were employed to ensure the robustness of the logistic model.

#### Repository Contents

`tz-gaming.ipynb`: Jupyter notebook containing the analysis code and model comparisons.
data/: Directory containing the datasets used in the analysis.

`tz-gaming-case.pdf`: Detailed case study PDF outlining the project's background and methodologies.

#### Technologies Used

1. Data Analysis: Logistic Regression, Decision Tree Modeling
2. Evaluation Metrics: Multicollinearity and Omitted Variable Bias, Decile Analysis and Gains Curves, Confusion Matrix
3. Tools: Python, Pandas, Scikit-learn, Matplotlib

#### How to Run

1. Clone the repository.
2. Ensure you have Jupyter Notebook installed to open the .ipynb file.
3. Install necessary Python packages: pyrsm, pandas, numpy, scikit-learn, matplotlib.
4. Run the notebook tz-gaming.ipynb to view the analysis and model comparisons.
