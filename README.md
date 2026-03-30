Gemini said
Factors Affecting School Grade: Feature Analysis & Prediction
This study explores predicting the final mathematics grades (G3) of secondary school students using machine learning. The project evaluates how different sets of academic and social indicators—ranging from parental education to lifestyle choices—impact the accuracy of grade predictions.

Project Overview
The analysis utilizes a student performance dataset to identify the key drivers of academic success. The study focuses on simplifying predictive models by comparing a broad data-driven feature set against a targeted set derived from academic literature. The workflow involves data preprocessing, categorical encoding, and comparative performance evaluation using regression metrics.

Key Findings
Model Comparison: A Literature-Based approach (4 features) outperformed a broader Data-Driven approach (6 features).

Predictive Accuracy: The refined model achieved a better R2 Score (0.0554) and a lower Mean Absolute Error (3.6259).

Significant Indicators: Prior class failures, mother’s education (Medu), age, and the desire for higher education were identified as the most potent predictors.

Complexity vs. Performance: Reducing model noise by removing less impactful variables like "going out frequency" improved overall predictive stability.

Technical Summary
The analysis was performed using Python in Jupyter Notebooks with the following libraries:

Pandas & Numpy: For data manipulation and numerical analysis.

Scikit-Learn: For implementing LabelEncoder and regression models.

Matplotlib & Seaborn: For generating correlation matrices and distribution histograms.

Repository Contents
FactorAffectingGrades.ipynb: The main Jupyter Notebook containing data exploration, visualization, and model training.

README.md: Documentation of the project's methodology and findings.

Dataset
The Student Performance Dataset used in this study includes various attributes such as student grades, demographic, social, and school-related features.
