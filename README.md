# 🏠 House Price Predictor

A machine learning pipeline that predicts California house prices using Linear Regression.

# 🎯 Project Objective
To build an end-to-end ML workflow that enables predictive analysis on housing data, showcasing data cleaning, feature engineering, modeling, and evaluation.

# 📊 Dataset
- **Source:** California Housing Prices (Kaggle)
- **Rows:** 20,640
- **Target:** `median_house_value`

# 🚀 How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open `house_price_ml.ipynb` in Jupyter Notebook.
4. Run all cells.

# 🛠️ Process
1. **Data Cleaning:** Removed missing values.
2. **Feature Engineering:** 
   - Encoded categorical variable `ocean_proximity`.
   - Scaled numeric features using `StandardScaler`.
3. **Modeling:** Train/Test split (80/20) → Linear Regression.
4. **Evaluation:** R² Score and Visualizations.

# 📈 Results
- **Model:** Linear Regression
- **R² Score:** ~0.68
- **Visualization:** Actual vs. Predicted scatter plot included in notebook.

## ⚠️ Limitations
- Linear model assumes linear relationships (real estate is complex).
- No geographic feature engineering (latitude/longitude) used yet.
- Single data source only.

# 🔮 Future Work
- Try non-linear models (Random Forest, Gradient Boosting).
- Add feature binning (e.g., age groups).
- Integrate external data (school ratings, crime stats).
- Deploy as a web app using Streamlit.

# 📄 Files
- `house_price_ml.ipynb`: Full analysis code.
- `housing.csv`: Dataset.
- `requirements.txt`: Python dependencies.
