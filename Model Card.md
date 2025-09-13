import joblib

model = joblib.load("house_rent_model.pkl")
prediction = model.predict([[location, size, bathrooms, furnishing_status]])
print("Predicted Rent:", prediction)
