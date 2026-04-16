[readme file.md](https://github.com/user-attachments/files/26795811/readme.file.md)
# Diabetes Prediction using Naive Bayes

A machine learning project that predicts diabetes using a Gaussian Naive Bayes classifier based on patient health metrics.

## 📊 Dataset

The dataset includes 10 patient records with the following features:

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| BMI | Body Mass Index |
| Age | Patient's age |
| Outcome | Target (0 = No Diabetes, 1 = Diabetes) |

## 🚀 Model

- **Algorithm:** Gaussian Naive Bayes
- **Train/Test Split:** 80% / 20%
- **Accuracy:** 100%

## 📈 Visualizations

The notebook includes:
- Correlation heatmap
- Scatter plot (Age vs Glucose)
- Box plot (BMI by Outcome)
- Histogram (Glucose distribution)
- Confusion matrix

## 📁 Files

- `DIABETES_prediction.ipynb` - Main Jupyter notebook
- `diabetes_test.csv` - Dataset file

## 🔧 Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
