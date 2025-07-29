# 🏠 California Housing Price Predictor

This project predicts the **median house price** in California using user-provided inputs and a machine learning model. It uses **Streamlit** for the user interface and **Linear Regression** for predictions.

---

## 🔍 Features

-  Trained on the California Housing Dataset
-  Linear Regression model with `scikit-learn`
-  R² Score: 0.5758 | MSE: 0.5559
-  Live prediction based on 8 feature inputs
-  Built using Streamlit for a clean and minimal UI

---
---
##  How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/KavyaD1/california-house-valuer.git
cd california-housing-price-predictor

2. Install Dependencies
```bash
Copy code
pip install -r requirements.txt

3. Run the App
```bash
Copy code
streamlit run app.py or python -m streamlit run app.py ##
----
----
# Project Structure
app.py              
model.pkl            
README.md            
requirements.txt
regression_model.py
---

---
   # Sample Inputs
Median Income
House Age
Average Rooms
Average Bedrooms
Population
Average Occupancy
Latitude
Longitude
And the app will predict the Median House Value.
---

---
#Tech Stack
Python
scikit-learn
pandas
numpy
Streamlit
----
----
#streamlit
https://california-house-valuer-bnhdre2zfdrzrfh2wmirwe.streamlit.app/

