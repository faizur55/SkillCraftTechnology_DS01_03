# SkillCraftTechnology_DS01_03
# 🧠 Insurance Product Purchase Prediction

This machine learning project predicts whether a customer will buy an insurance product based on their demographic and behavioral attributes using a Decision Tree model.

## 📁 Dataset
The dataset (`train.csv`) contains information about customer behavior and past insurance history. Key features include:
- Risk Factor
- Car Value
- Previous Contact Duration
- C_Previous
- Target (whether they purchased the insurance)

## 🧪 Project Workflow

1. **Data Exploration & Cleaning**
2. **Feature Selection & Encoding**
3. **Train-Test Split**
4. **Model Building (Decision Tree)**
5. **Manual Hyperparameter Tuning**
6. **GridSearchCV Optimization**
7. **Model Evaluation**
8. **Model Comparison**
9. **Tree Visualization & Feature Importance**

## 📊 Model Performance

Model	          R² Score	MSE
0	Default Tree	0.114720	1651.866354
1	Tuned Tree	  0.321950	1265.189321
2	GridSearchCV	0.438418	1047.869432

Model	R² Score	MSE
0	GridSearchCV	0.438418	1047.869432
1	Tuned Tree	0.321950	1265.189321
2	Default Tree	0.114720	1651.866354


## 🎯 Key Insights
- Features like `car_value`, `risk_factor`, and `C_previous` are key predictors.
- Hyperparameter tuning significantly improved the performance.
- The model helps insurance providers identify purchase intent in customers.

## 📦 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook


## 🚀 How to Run

```bash
git clone https://github.com/yourusername/insurance-purchase-prediction.git
cd insurance-purchase-prediction
pip install -r requirements.txt
