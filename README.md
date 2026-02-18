# 🏥 Health Insurance Payment Predictor

This project is a **Machine Learning-powered web app** that predicts the estimated health insurance payment amount based on user-input features like age, BMI, blood pressure, smoking status, diabetes condition, and number of children. It’s built using **Python**, **Scikit-learn**, and **Streamlit** for an interactive web interface.

---

## 🚀 Features

- 💡 **Machine Learning Model** trained on insurance-related data  
- 🧠 **Predicts insurance payment amount** instantly  
- 🌐 **Streamlit Web App** with a clean and interactive UI  
- 🔄 Automatic **Label Encoding & Feature Scaling**  
- 💾 Pre-trained model stored as `best_model.pkl` using `joblib`  
- ⚡ Fast real-time predictions  

---

## 🧩 Tech Stack

- Python  
- **Pandas**  
- **NumPy**  
- **Scikit-learn**  
- **Streamlit**  
- **Joblib**  

---

## ⚙️ How It Works

1. **Data Preprocessing & Training**  
   The dataset is cleaned, encoded, scaled, and used to train a regression model.

2. **Model Saving**  
   The trained model is saved using `joblib` as:
   - `best_model.pkl`
   - `scaler.pkl`
   - `label_encoder_gender.pkl`
   - `label_encoder_diabetic.pkl`
   - `label_encoder_smoker.pkl`

3. **Web App (Streamlit)**  
   The app (`app.py`) loads the saved model and preprocessing files.

4. **Prediction**  
   Users enter their details, and the app:
   - Encodes categorical features  
   - Scales numerical features  
   - Predicts insurance payment  
   - Displays the result instantly  

---

## 🧠 Example Inputs

| Feature | Example |
|----------|----------|
| Age | 35 |
| Gender | Male |
| BMI | 27.5 |
| Blood Pressure | 120 |
| Diabetic | No |
| Children | 2 |
| Smoker | Yes |

---

## 💰 Example Output

Estimated Insurance Payment Amount: $12,450.75

---

## 📊 Future Improvements

- Add model performance metrics (R², MAE, RMSE)  
- Add data visualization dashboard  
- Deploy app on Streamlit Cloud  
- Add SHAP feature importance visualization  
- Convert into a full AI-powered insurance assistant 🤖  

---

## 👨‍💻 Author

Ahmed Mustafa  
💻 Python Developer | AI & ML Enthusiast  
🚀 Passionate about building intelligent systems  

---

## 📂 Dataset

The dataset used for training this model can be found here:

🔗 **Dataset URL:**  
https://github.com/Onurbltc/InsuranceData/blob/main/insurance.csv 

---

⭐ If you like this project, don’t forget to give it a star on GitHub!
