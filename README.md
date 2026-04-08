<img width="1903" height="812" alt="Diabetes" src="https://github.com/user-attachments/assets/d600470c-6897-4ed6-9927-db86b069c423" />
## 🌟 About The Project

Welcome to the **Predictive Health Hub**! This application combines multiple machine learning disease prediction models into a single, seamless, and beautifully designed clinical interface. 

Instead of dealing with scattered scripts, researchers and healthcare professionals can now access risk-assessment tools for three major health areas entirely from one compact web dashboard.

### 🩺 What it screens for:
1. **🫀 Cardiology (Heart Disease)**: Analyzes 13 vital signs (like cholesterol, resting ECG, and max heart rate) to predict cardiac risk.
2. **🩸 Metabolics (Diabetes)**: Calculates diabetes likelihood based on glucose levels, insulin, BMI, and age.
3. **👁️ Ophthalmology (Eye Conditions)**: Provides insight into ocular diseases (such as Cataracts and Glaucoma) via retinal image uploads.

---

## 🚀 Quickstart / Installation

To run this application locally, follow these simple steps:

### 1. Clone the repository
```bash
git clone https://github.com/your-username/predictive-health-hub.git
cd predictive-health-hub
```

### 2. Install dependencies
Make sure you have Python installed. Then, install the required packages using:
```bash
pip install -r requirements.txt
```

### 3. Run the App
Fire up the local Streamlit server:
```bash
streamlit run app.py
```
Your browser will automatically open the application at `http://localhost:8501`.

---

## 🎨 UI Highlights

The interface was fundamentally built to prioritize a **clean, professional healthcare aesthetic**:
- 🧊 **Clinical Theme**: Alice Blue layouts with calming Ocean Blue accents prioritize readability and trust.
- 📱 **Compact Grid Layout**: Input parameters are arranged nicely into 4 columns for maximum efficiency, swapping out bulky sliders for sleek numerical inputs.
- ⚡ **Confidence Metrics**: Every positive or negative prediction showcases its specific confidence interval.

---

## 📂 Project Structure
```text
unified_app/
│
├── app.py                   # Main Streamlit web application & UI
├── requirements.txt         # Required Python packages
└── models/                  # Centralized directory for ML Models
    ├── diabetes_model.pkl   # Trained Python model for diabetes
    ├── diabetes.csv         # Calibration dataset for the scaler
    ├── heart_disease_model.pkl  # Trained Python model for heart disease
    └── mean_std_values.pkl  # Scaling metrics for heart vitals
```
<img width="1902" height="898" alt="HeartDisease2" src="https://github.com/user-attachments/assets/193fcee9-3fe8-4806-a08c-72458ad96732" />

