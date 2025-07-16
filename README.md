# 🏡 Airbnb Profit Optimization with Machine Learning

This project uses a **Random Forest Regressor** trained on Seattle Airbnb data to **predict profits** and simulate **"what-if" counterfactual scenarios** — helping hosts explore actionable ways to improve their earnings.

---

## 🚀 Project Goals

- ✅ Predict Airbnb listing profit using listing and host features  
- 🔍 Identify the most influential factors driving profit  
- 📈 Provide personalized, data-driven recommendations  
- 💡 Enable what-if simulations to help hosts make better decisions  

---

## 📊 Tools & Technologies

- **Python**: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
- **Jupyter Notebook**: Exploratory analysis, model training, evaluation
- **ML Model**: `RandomForestRegressor`  
- **Simulations**: Counterfactual analysis via custom “what-if” engine

---

## 📁 Project Structure

| File/Folder                  | Description                                                               |
|-----------------------------|---------------------------------------------------------------------------|
| `airbnb_profit_model.ipynb` | Main notebook with EDA, model training, evaluation, and simulation code   |
| `listings.csv`              | Cleaned Airbnb dataset (Seattle)                                          |
| `README.md`                 | Project documentation (this file)                                         |
| `images/`                   | Folder for saved charts and visualizations (optional)                     |

---

## 📈 Model Performance

| Metric | Value    |
|--------|----------|
| MAE    | $11.62   |
| RMSE   | $18.77   |
| R²     | 0.86     |

---

## 🔍 Key Insights

- **Top Predictors**:
  - `price`
  - `price_per_person`
  - `cleaning_fee`

- **Neighborhood Trends**:  
  Listings in neighborhoods like **Wallingford** had consistently higher profit margins.

- **Simulation Takeaways**:
  - 🌟 Becoming a **Superhost** leads to higher profit
  - 🛏 Adding a **bed** improves revenue slightly
  - 🏠 Changing the **room type** (e.g., Private Room → Entire Home) had the most dramatic impact

---

## 💡 Recommendation Engine

A custom function runs what-if simulations on listings to test changes like:

- ✅ Becoming a Superhost  
- ✅ Adding more beds  
- ✅ Converting to an "Entire Home" listing

```python
# Example usage
run_counterfactual(listing_id=42, superhost=True, add_bed=1, room_type="Entire home/apt")

