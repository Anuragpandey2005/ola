🚖 Ola Driver Attrition Prediction
This project predicts whether Ola drivers are likely to leave (attrition) or stay, using machine learning models trained on driver data.

It includes:

Exploratory Data Analysis & Model Training (OLa_Driver_Attrition.ipynb)

Deployment-ready Streamlit App (app.py)

Pre-trained ML Models (random_forest_model.joblib, xgboost_model.joblib)

note :- The Random Forest Model Was Compressed Due to Its Big Size Don't Forget to Decompress It 

📂 Project Structure
├── app.py                        # Streamlit web app
├── requirements.txt              # Dependencies
├── OLa_Driver_Attrition.ipynb    # Notebook (EDA + training)
├── random_forest_model.joblib    # Saved RandomForest model
├── xgboost_model.joblib          # Saved XGBoost model
└── README.md                     # Documentation
⚙️ Setup & Installation
Clone the repository:
git clone https: (//github.com/Rutvik936/Ola-Churn-Predition.git)
cd Ola_Driver_Churn_pred
Install dependencies:
pip install -r requirements.txt
🚀 Running the Streamlit App
Run the app with:

streamlit run app.py
👉 Open the link shown in terminal (default: http://localhost:8501).

📊 Models Used
Random Forest Classifier
XGBoost Classifier
Both models are trained and saved as .joblib files. Predictions are served in the Streamlit app.

📘 Usage
Open the Streamlit app.
Enter driver details manually (Age, Tenure, Income, etc.).
Both models will predict:
Stay ✅ or
Leave ❌
🧑‍💻 Author
Developed by Rutvik Mahadik
For learning, deployment, and demonstration of EDA + ML + Streamlit workflow.
