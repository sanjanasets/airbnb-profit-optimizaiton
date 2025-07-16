🏡 Airbnb Profit Optimization with Machine Learning
This project uses a Random Forest Regressor trained on Seattle Airbnb data to predict profits and simulate "what-if" counterfactual scenarios — helping hosts explore actionable ways to improve their earnings.

🚀 Project Goals
✅ Predict Airbnb listing profit using listing and host features

🔍 Identify the most influential factors driving profit

📈 Provide personalized, data-driven recommendations

💡 Enable what-if simulations to help hosts make better decisions

📊 Tools & Technologies
Python: pandas, scikit-learn, matplotlib, seaborn

Jupyter Notebook: Exploratory analysis, model training, evaluation

ML Model: RandomForestRegressor

Simulations: Counterfactual analysis via custom “what-if” engine

📁 Project Structure
File/Folder	Description
airbnb_profit_model.ipynb	Main notebook with EDA, model training, evaluation, and simulation code
listings.csv	Cleaned Airbnb dataset (Seattle)
README.md	Project documentation (this file)
images/	Folder for visualizations (optional)

📈 Model Performance
Metric	Value
MAE	$11.62
RMSE	$18.77
R²	0.86

🔍 Key Insights
Top Predictors:

price

price_per_person

cleaning_fee

Neighborhood Trends:
Listings in areas like Wallingford had consistently higher profit margins.

Feature Impact from Simulations:

🌟 Becoming a Superhost → higher profit

🛏 Adding an extra bed → moderate gain

🏠 Switching room type (e.g., to Entire Home) → highest impact in some cases

💡 Recommendation Engine
A custom-built function lets you explore how changes to a listing might affect profit.

Supported what-if scenarios:

✅ Become a Superhost

✅ Add extra beds

✅ Change room type (e.g., Private → Entire Home)


