# 🚑 Insurance Charges Prediction

A simple **Machine Learning project** to predict **medical insurance charges** based on **age, BMI, and smoking status** using **Linear Regression** and a **Streamlit app**.

---

## 📂 Project Files

```
insurance-prediction/
├── insurance.csv
├── insurance_prediction.ipynb
├── insurance_prediction_app.py
├── linear_model.pkl
├── requirements.txt
└── README.md
```

---

## 📊 Dataset: `insurance.csv`

**Columns used for prediction in the app:**

- `age`
- `bmi`
- `smoker`

---

## 📈 Model

Trained **Linear Regression** on:

- **Features:** `age`, `bmi`, `smoker`
- **Target:** `charges`

---

## 🚀 Live Demo

✅ [Try the app here!](https://insurance-prediction-irgn2x5pkxagrigkgnqmdv.streamlit.app/)

---

## ⚙️ How to Run Locally

```bash
git clone https://github.com/your-username/insurance-prediction.git
cd insurance-prediction
pip install -r requirements.txt
streamlit run insurance_prediction_app.py
```

---

## 🔍 How it Works

The **Streamlit app** collects:

- Age
- BMI
- Number of Children
- Sex
- Smoker status
- Region

**However, the current model only uses:**

- Age
- BMI
- Smoker status (encoded as `1` for yes, `0` for no)

to predict insurance charges.

The other fields are collected for potential **future model improvements and feature engineering**.

When the user clicks **Predict**, the app:

✅ Feeds `age`, `bmi`, `smoker` to the trained Linear Regression model  
✅ Predicts and displays **estimated insurance charges instantly**  

---

## 🖥️ Requirements

- `streamlit`
- `scikit-learn`
- `pandas`
- `numpy`
- `matplotlib`

---

## 🎯 Improvements

- Add more features (`children`, `region`, `sex`) to the model.
- Try advanced models for better accuracy.
- Add visualizations inside the app.
- Deploy with version control for updates.

---

## 🤝 Contributing

Feel free to fork, improve, and open PRs!

---

