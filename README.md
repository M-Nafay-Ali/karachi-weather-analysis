Note:-I perform all of this in mobile so everything that I know to do in mobile I tried my best so if there is any thing missing then I apologize 
This project analyzes historical temperature data for Karachi and compares the predictive accuracy of a traditional Time-Series model (ARIMAX) against a Machine Learning approach (Lasso Regression).
Keyy Features
Interactive Dashboard: Developed a "Lively" Plotly-based time-series explorer with range sliders and unified hover effects.
Dual-Model Approach: Evaluated both Autoregressive (Time-Series) and Regularized Linear (Machine Learning) models.
Error Metrics: Calculated Mean Absolute Error (MAE) and RMSE to determine the "Winner" for Karachi's unique coastal climate.
🛠️ Technical Details
Language: Python 3.x
Environment: Google Colab (Mobile-Optimized Workflow)
Core Libraries: * Statsmodels (for ARIMAX)
Scikit-learn (for Lasso Regressor)
Plotly (for interactive visualizations)
Pandas (for data cleaning and datetime manipulation)
📊 Project Structure
Data Cleaning: Removing unit symbols, handling missing values, and converting date strings into datetime objects.
Algorithm Implementation: Training models on historical Karachi temperature trends.
Visualization: Comparing Actual vs. Predicted temperatures to visualize model "lag" and "accuracy."
📉 Insights for Karachi
Seasonality: The ARIMAX model successfully identified the 12-month seasonal cycle, crucial for predicting the pre-monsoon heatwaves in Sindh.
Model Verdict: The ARIMAX model provided more stable predictions for daily peaks, while ARIMAX captured the overall trend more naturally.
📬 Contact:
M.Nafay Ali |2nd Year ICS Student | Google Certified Data Analytics Professional [https://www.linkedin.com/in/mohammed-nafay-ali-16519138a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app]

#karachi-weather-analysis
It is a model comparing ARIMAX and Lasso for Karachi weather forecasting.
