🚑 Insurance Charges Prediction
A simple Machine Learning project to predict medical insurance charges based on age, BMI, and smoking status using Linear Regression and a Streamlit app.

📂 Project Files
Copy
Edit
insurance-prediction/
├── insurance.csv
├── insurance_prediction.ipynb
├── app.py
├── linear_model.pkl
├── requirements.txt
└── README.md
📊 Dataset: insurance.csv
Columns used for prediction in app:

age

bmi

smoker

📈 Model
Trained Linear Regression on:

Features: age, bmi, smoker

Target: charges

Other columns like sex, region, and children are not used in the prediction logic of the deployed app.

🚀 Live Demo
✅ Try the app here!

⚙️ How to Run Locally
bash
Copy
Edit
git clone https://github.com/your-username/insurance-prediction.git
cd insurance-prediction
pip install -r requirements.txt
streamlit run app.py
🔍 How it Works
The Streamlit app collects:

Age

BMI

Smoker status (yes/no)

The app encodes smoker as smoker_yes = 1 or 0.

Feeds age, bmi, smoker_yes to the trained model.

Displays predicted insurance charges.

🖥️ Requirements
nginx
Copy
Edit
streamlit
scikit-learn
pandas
numpy
matplotlib
🎯 Improvements
Add more features like children, region, sex to the model.

Try other models for better accuracy.

Deploy with version control for updates.

🤝 Contributing
Feel free to fork, improve, and open PRs!
