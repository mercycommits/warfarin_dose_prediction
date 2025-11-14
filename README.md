<h1>Warfarin Dose Prediction</h1>
<img width="1400" height="800" alt="image" src="https://github.com/user-attachments/assets/da36328b-188a-4a3f-a670-72688a1fef5d" />

<h3>Overview</h3>

Predict the therapeutic dose of Warfarin based on patient clinical and genetic features using a Random Forest Regressor. Accurate dosing can reduce adverse effects and improve outcomes.

<h3>Dataset</h3>

Features: Age, Gender, Race, Weight, Height, INR, Genotype, Simvastatin, Amiodarone

Target: Therapeutic Dose

Preprocessing: Handle missing values, convert age to numeric, one-hot encode categorical features

<h3>Modeling</h3>

Model: Random Forest Regressor

Hyperparameter Tuning: GridSearchCV

Best Parameters:
max_depth=20, max_features='sqrt', min_samples_leaf=4, min_samples_split=2, n_estimators=100

<h3>Performance</h3>

RMSE: 12.44

R²: 0.37

Moderate performance; further improvement possible with feature engineering or advanced models like XGBoost.

<h3>Technologies</h3>

Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn
