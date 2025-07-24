# 🏥 Health Insurance Premium Predictor

A Streamlit web application that predicts health insurance premium costs based on user inputs such as age, income, BMI, medical history, lifestyle, and other personal attributes.

## 💡 What it Does

This app allows users to:
- Enter details like age, gender, income, region, medical history, BMI category, smoking habits, etc.
- Get a real-time prediction of their **expected health insurance premium** using a trained machine learning model.
- Use a clean, responsive interface that runs directly in the browser.

## 🚀 Live App

👉 [Click here to try the app](https://insurance-22g4p4wf8v2zqhgecsajju.streamlit.app/) 

## 🖥 How to Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/usha1459/Insurance.git
cd Insurance
```

2. **Install dependencies**

```bash
Copy code
pip install -r requirements.txt
```

3. Run the Streamlit app
   
```bash
Copy code
streamlit run app.py
```
📁 Project Structure
```bash
Copy code
Insurance/
├── app.py                     # Streamlit frontend code
├── prediction_helper.py       # Prediction logic using ML model
├── model.pkl                  # Trained ML model (if used)
├── requirements.txt           # Python dependencies
└── README.md                  # Project info
```

👩‍💻 Author
Developed by Prathyusha Kopur
