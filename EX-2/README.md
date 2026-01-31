# EX02 – Water Temperature Prediction using Regression Models

This project demonstrates a **machine learning regression workflow** to predict **sea water temperature (°C)** using oceanographic features from the **CalCOFI Bottle Dataset**.  
The notebook applies **Linear Regression**, **Ridge Regression**, and **Lasso Regression**, along with proper preprocessing and evaluation.

---

## 📌 Project Information

- **Student Name:** Sanjay R  
- **Register No:** 24BAD407  
- **Experiment:** EX02  
- **Domain:** Machine Learning / Data Analysis  
- **Dataset Source:** CalCOFI Bottle Dataset (Kaggle)

---

## 📊 Dataset Description

The dataset contains physical and chemical measurements of seawater collected over several decades.

### Selected Features
| Feature | Description |
|------|------------|
| `Depthm` | Water depth (meters) |
| `Salnty` | Salinity |
| `O2ml_L` | Dissolved oxygen (ml/L) |

### Target Variable
| Variable | Description |
|--------|-------------|
| `T_degC` | Water temperature (°C) |

---

## ⚙️ Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Machine Learning Workflow

1. Data loading and feature selection  
2. Missing value handling using median imputation  
3. Feature scaling using standardization  
4. Train-test split (80/20)  
5. Model training (Linear, Ridge, Lasso)  
6. Model evaluation using regression metrics  

---

## 📈 Evaluation Metrics

- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

---

## 📉 Visualizations

- Actual vs Predicted temperature plot  
- Residual error distribution  

---

## 🧪 Models Used

- Linear Regression  
- Ridge Regression (L2 regularization)  
- Lasso Regression (L1 regularization)  

---

## ▶️ How to Run

1. Place dataset at:
   /kaggle/input/calcofi/bottle.csv
2. Open the notebook
3. Run all cells sequentially

---

## 📚 Learning Outcomes

- End-to-end regression pipeline
- Proper data preprocessing
- Model comparison and evaluation
- Interpretation of regression coefficients

---

## License

For academic and educational use only.
