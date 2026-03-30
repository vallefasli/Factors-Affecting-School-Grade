Key Features & Analysis
Data Exploration: The project analyzes student data (e.g., age, parental education, failures, and social activities) to understand their distribution and impact on final grades.

Visualization: Includes detailed correlation matrices and histograms to visualize the relationship between categorical features and academic performance.

Feature Engineering: Uses LabelEncoder to process categorical variables for machine learning compatibility.

Model Comparison: Evaluates different feature sets to optimize prediction accuracy (R2 Score) and minimize error (Mean Absolute Error).

Core Findings
The analysis compared two different approaches to feature selection:

Data-Driven Approach (6 Features): Included failures, Medu (mother's education), age, Fedu (father's education), higher (desire for higher education), and goout (frequency of going out).

Literature-Based Approach (4 Features): Focused on failures, Medu, age, and higher.

Results indicated that focusing on a smaller set of high-impact variables (the Literature-Based approach) yielded a better R2 Score (0.0554) and lower MAE (3.6259) compared to the broader data-driven set, suggesting that specific personal and academic background markers are the strongest predictors in this dataset.
