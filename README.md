
# 🚢 Titanic Survival Prediction — Project 2

**Author:** [Saad Bin Rasheed](https://github.com/saadbinrasheed01)

## 🎯 Goal
Build predictive models to estimate passenger survival on the Titanic using Logistic Regression and Random Forest.

## 📁 Data
- Source: Kaggle Titanic dataset
- File used: `data/train_cleaned.csv` (or `train.csv` with minimal cleaning)

## 🧠 Features Used
- `Pclass`, `Sex`, `Age`, `Fare`, `Embarked`
- Engineered: `FamilySize`, `IsAlone`, `AgeBin`

## 🧪 Models
- Logistic Regression (baseline)
- Random Forest Classifier (tuned)

## 📊 Results
| Metric       | Logistic Regression | Random Forest |
|--------------|----------------------|---------------|
| Accuracy     | 0.XXX                | 0.XXX         |
| Precision    | 0.XXX                | 0.XXX         |
| Recall       | 0.XXX                | 0.XXX         |
| F1-score     | 0.XXX                | 0.XXX         |
| ROC-AUC      | 0.XXX                | 0.XXX         |

**Best Model:** Random Forest (tuned)

## 📈 Figures
- Confusion Matrix (Logistic Regression): `reports/figures/12_confusion_lr.png`
- Confusion Matrix (Random Forest): `reports/figures/13_confusion_rf.png`
- ROC Curve (both models): `reports/figures/14_roc_both.png`

## ▶️ Reproduce Locally
```bash
conda env update -f environment.yml --prune
conda activate titanic-eda
jupyter nbconvert --to html --no-input   --output-dir reports --output titanic-modeling.html   notebooks/02_titanic_modeling.ipynb
```

## 🌐 Optional: Publish to GitHub Pages
Export the notebook to HTML and push to `main` branch. Use `.github/workflows/publish-pages.yml` to automate.

## 📬 Contact
Feel free to connect via GitHub: [saadbinrasheed01](https://github.com/saadbinrasheed01)
