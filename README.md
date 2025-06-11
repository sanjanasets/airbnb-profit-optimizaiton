
Using a Random Forest Regressor trained on Seattle Airbnb data, we predict profits and evaluate **"what-if" counterfactual scenarios** — such as becoming a superhost, changing room type, or adding beds — to recommend actionable improvements.

---

## 🚀 Project Goals
- Predict Airbnb listing profit based on listing features
- Identify key drivers of profit
- Provide **data-backed recommendations** to improve profit
- Enable **what-if simulations** for hosts using trained ML models

---

## 📊 Tools & Technologies
- Python (pandas, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook
- Machine Learning: Random Forest Regressor
- Exploratory Data Analysis (EDA)
- Counterfactual simulation ("what-if" engine)

---

## 📁 Files
| File | Description |
|------|-------------|
| `airbnb_profit_model.ipynb` | Main notebook with EDA, model training, evaluation, and recommendations |
| `listings.csv` | Cleaned dataset from Seattle Airbnb open data |
| `README.md` | Project overview and documentation |
| `images/` | Folder with saved charts (optional) |

---

## 📈 Model Performance

- **MAE**: \$11.62  
- **RMSE**: \$18.77  
- **R² Score**: 0.86  

---

## 🔍 Key Insights

- `price`, `price_per_person`, and `cleaning_fee` were top predictors of profit
- Listings in certain neighborhoods (e.g., Wallingford) had higher returns
- Counterfactual simulations revealed that:
  - Becoming a **superhost** increased profit
  - Adding a **bed** improved revenue slightly
  - Adjusting **room type** had the most impact for some listings

---

## 💡 Recommendation Engine

A custom function runs what-if scenarios like:

- 🏠 Converting to "Entire Home"
- 🛏 Adding more beds
- 🌟 Becoming a Superhost

And returns predicted profits for each:

