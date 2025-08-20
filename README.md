
# 🌲 Forest Cover Type Classification  

## 📌 Project Overview  
This project predicts the **forest cover type** based on cartographic and environmental features using the **Covertype dataset** (UCI Machine Learning Repository).  

The task is a **multi-class classification problem**, where models learn to classify different forest cover types using tree-based methods like **Random Forest** and **XGBoost**.  

---

## 📂 Dataset  
- **Source**: [UCI Covertype Dataset](https://archive.ics.uci.edu/ml/datasets/covertype)  
- **Target variable**: `Cover_Type` (7 classes)  
- **Features**: Elevation, slope, soil type, wilderness area, etc.  

---

## ⚙️ Workflow  
1. **Data Preprocessing**
   - Handled categorical features (One-Hot Encoding for soil & wilderness areas)  
   - Normalized/standardized numerical features where required  
   - Train-Test split  

2. **Modeling**
   - **Random Forest Classifier**  
   - **XGBoost Classifier**  
   - **Hyperparameter tuning** (GridSearchCV for Random Forest)  

3. **Evaluation**
   - Accuracy score comparison  
   - Confusion Matrix visualization  
   - Feature importance analysis  

---

## 📊 Results  

| Model                   | Accuracy |
|--------------------------|----------|
| Random Forest            | ~0.79    |
| Tuned Random Forest      | ~0.82    |
| XGBoost                  | ~0.85    |

✅ **XGBoost performed the best**, achieving the highest accuracy.  

### 🔑 Key Features (from Feature Importance)  
- Elevation  
- Horizontal Distance to Roadways  
- Hillshade at Noon  
- Horizontal Distance to Fire Points  

---

## 📉 Visualizations  
- Confusion Matrix to inspect per-class performance  
- Feature importance bar plots  

---

Tech Stack

Python

Pandas, NumPy

Scikit-learn

XGBoost

Matplotlib, Seaborn

✨ Bonus Work

Compared Random Forest & XGBoost

Performed hyperparameter tuning

Visualized model comparisons

📌 Author

Developed by Safia Sarfraz 👩‍💻
