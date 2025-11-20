# E-Commerce Revenue Prediction — Linear Regression

Project Overview-

This project explores customer purchasing behavior in an online retail setup where users first experience in-store styling sessions and then place orders through either the mobile app or the website. The aim is to identify which digital channel influences revenue more strongly and help guide decisions around UX upgrades, product enhancements, and marketing investment.

Business Problem-

The analysis focuses on understanding which platform drives more revenue 📱💻, which engagement factors affect customer spending the most, and how classical regression modeling can support strategic optimization of digital channels.

Dataset-

The model uses key customer engagement and behavior features:
Avg. Session Length ⏱️ represents the average duration of a customer’s styling session experience, Time on App 📱 measures engagement within the mobile application, Time on Website 💻 captures browsing behavior on the web platform, and Length of Membership 🎯 reflects customer loyalty and long-term association.

Approach-

The project follows a structured machine-learning workflow covering data loading, cleaning, exploratory analysis, feature selection, model building using multiple linear regression in Python, evaluation of performance metrics, and interpretation of business outcomes.

Model Development-

A regression model was developed in Python by splitting data into train and test sets, fitting the model, checking statistical assumptions such as residual distribution and multicollinearity, and computing predictive accuracy using R², MAE, and RMSE. Diagnostic plots and statistical summaries were generated to validate the model.

Evaluation Metrics-

Performance assessment included measuring the proportion of variance explained by the model (R²), average prediction error (MAE), and error magnitude with higher penalty (RMSE). These metrics were complemented with visual diagnostics to confirm model reliability.

Key Insights-

Customer engagement through the mobile app showed a stronger positive impact on revenue compared to website usage. Improving the mobile experience is more likely to yield faster business returns. The interpretability of classical regression made the results actionable and directly relevant to decision-makers.

Tools & Technologies-

Python served as the backbone of the project, supported by libraries such as Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, and statsmodels, executed in notebooks running on Jupyter or Google Colab environments.

Reproducibility-

Dependencies can be installed using

pip install -r requirements.txt

The notebook can be executed in Jupyter Notebook, Google Colab, or VS Code with Jupyter support.
