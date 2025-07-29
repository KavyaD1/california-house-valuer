# 🏠 California Housing Price Predictor

This project predicts the **median house price** in California using user-provided inputs and a trained **Linear Regression** model. It features a clean **Streamlit** UI and is based on the California Housing Dataset.

---

To run locally

1. Clone Repository
```bash
git clone https://github.com/KavyaD1/california-house-valuer.git
cd california-house-valuer

 2. Install Dependencies
```bash
Copy code
pip install -r requirements.txt

Run the App
```bash
Copy code
streamlit run app.py
Alternatively:
```bash
Copy code
python -m streamlit run app.py

🗂️Project Structure
bash
Copy code
📁 california-house-valuer/
├── app.py               # Streamlit app UI
├── model.pkl            # Trained ML model
├── README.md            # Documentation
├── requirements.txt     # Project dependencies
└── regression_model.py  # Model training code


🧪 Sample Inputs
Provide the following values in the app:

Median Income
House Age
Average Rooms
Average Bedrooms
Population
Average Occupancy
Latitude
Longitude

And the app will predict the Median House Value 💵.


Tech Stack

Python
scikit-learn
pandas
numpy
Streamlit

 Live Demo
Try the app online 👉
Streamlit App https://california-house-valuer-bnhdre2zfdrzrfh2wmirwe.streamlit.app/ 
