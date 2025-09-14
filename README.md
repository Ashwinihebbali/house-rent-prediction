# 🏠 Boston Housing Price Prediction

## 📌 Overview
This project leverages traditional machine learning algorithms to predict housing prices using datasets like the **Boston Housing Dataset**.  
Users can estimate property prices based on features such as *crime rate, number of rooms, property tax rate, and pupil-teacher ratio*.  
Built with *Python* and *Streamlit*, it offers an **interactive and user-friendly interface** for both single and batch predictions.

---

## ✨ Key Features
- 📊 Accurate house price predictions using *regression models*  
- 🖥 Interactive *Streamlit web application*  
- 📝 Supports *single and batch inputs via CSV*  
- 🧹 Handles numerical and categorical features efficiently  

---

## ⚙ Prerequisites
- *Python 3.8+*  
- *pip*  

Required Python packages:  
```bash
pip install numpy pandas scikit-learn matplotlib seaborn streamlit joblib
```

---

## 🚀 Installation & Usage

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Ashwinihebbali/house-rent-prediction.git
cd house-rent-prediction
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Launch the Application  
```bash
streamlit run app.py
```

A local URL will be displayed in the terminal (e.g., `http://127.0.0.1:8501`).  
Open it in your browser to interact with the application by entering property details or uploading a CSV file to predict housing prices.

### ✅ Deployment
The project has already been pushed to GitHub and deployed on [Streamlit Cloud](https://share.streamlit.io/). You can access the live app [here](https://ashwinihebbali-house-rent-prediction-app-train-test-yghgvh.streamlit.app/).

---

## 🧠 Model Architecture
- **Data Preprocessing:** Handles missing values, encodes categorical features, and normalizes numerical features  
- **Model:** Regression algorithms like *Linear Regression, Decision Trees, Random Forests*, etc.  
- **Training:** Models are trained on historical housing data with evaluation metrics such as *RMSE* and *MAE*  
- **Deployment:** The trained model is saved as `boston_best_model.pkl` and loaded into the Streamlit app for predictions  

---

## 📂 Project Structure

```
house-rent-prediction/
├── app.py                     # Main Streamlit application
├── app-Train-Test.py          # Model training and testing script
├── boston_best_model.pkl      # Trained ML model file
├── boston_linear_regression.pkl # Another model file
├── data.csv                   # Dataset file
├── feature_columns.json      # Feature metadata
├── linear_feature_meta.json   # Additional feature info
├── model_card.md              # Model documentation
├── requirements.txt           # Python dependencies
├── train-Boston-Models.py     # Training scripts
├── train_boston_models.py    # Additional training scripts
├── train_boston_models_all.py # Extended training scripts
├── venv/                      # Virtual environment folder
├── Linear Regression_Train-Save-Test.ipynb # Jupyter notebook
├── Project_Regression_Analysis_With_Boston_Ho... # Project notes
├── Boston-Housing-Prediction Notes and Codes... # Additional notes
```

---

## 🤝 Contributing
Contributions are welcome! Follow these steps:  
1. Fork the repository  
2. Create a new branch (`git checkout -b feature-name`)  
3. Make your changes and commit (`git commit -m "Add new feature"`)  
4. Push to the branch (`git push origin feature-name`)  
5. Create a Pull Request  

---

## 🤝 Acknowledgments
Special thanks to Dr. Victor Ikechukwu for his invaluable guidance and support throughout the development of this project. Explore their work: [Victor-Ikechukwu](https://github.com/Victor-Ikechukwu).

..

---

## 📄 License
This project is licensed under the *MIT License*. See [LICENSE](LICENSE) for details.

---
🔥 If you found this project helpful, please ⭐ it on GitHub!
