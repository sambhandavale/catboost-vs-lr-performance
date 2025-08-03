# 🏡 CatBoost vs Linear Regression

This notebook compares **Linear Regression** (with manual encoding) and **CatBoost** for predicting house prices using real-world data.

---

## ⚡ Why CatBoost is Better

### ✅ No Manual Encoding  
CatBoost works directly with text (categorical) columns — no need for OneHotEncoder.

### ✅ Learns Complex Patterns  
Linear Regression can only fit straight lines. CatBoost finds non-linear patterns better.

### ✅ Higher Accuracy  
CatBoost gives lower error (RMSE) with less setup.

---

## 📊 Results

| Model              | RMSE (lower is better) |
|-------------------|------------------------|
| Linear Regression | 356,726                |
| CatBoost          | 261,439                |

---

## 📌 Conclusion

CatBoost is **faster to set up** and gives **better results**, especially when the data has text columns and non-linear relationships.
