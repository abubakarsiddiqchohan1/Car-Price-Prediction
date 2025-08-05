# 🚗 Car Price Prediction with GUI | AI Lab Project of my 4th Semester university project 

## 📌 Overview

This is my **4th semester project** for the **Artificial Intelligence Lab** course, part of the **BS Data Science** degree. It is a **Car Price Prediction System** that combines **Machine Learning** with a **Tkinter-based GUI** to provide an interactive way for users to estimate used car prices.

## 💻 What It Does

- Trains a **Linear Regression** model on a cleaned dataset of used cars
- Encodes categorical features using **LabelEncoder**
- Builds a **Pipeline** for streamlined preprocessing and model training
- Allows users to **input car details via GUI** (Company, Model, Year, Fuel Type, KM Driven)
- Predicts the **estimated car price instantly** in the GUI window

## 🧠 Technologies & Libraries

- Python
- Jupyter Notebook
- Pandas & NumPy
- Scikit-learn
- Tkinter (for GUI)
- Matplotlib / Seaborn (for EDA)

## 🎯 Features of the Application

- Cleaned and preprocessed dataset
- Model training and evaluation
- Fully functional **Tkinter GUI**
- Dropdowns and Entry Fields for:
  - Car Company
  - Car Model
  - Year of Purchase
  - Fuel Type
  - Kilometers Driven
- Result shown directly in the window

## 📊 Machine Learning Pipeline

1. **Data Preprocessing**
   - Handle null values
   - Convert strings to numerical format
2. **Feature Engineering**
   - Combine columns where necessary
3. **Model Training**
   - Linear Regression via Scikit-learn
4. **Model Deployment**
   - Used via GUI (not as web app, but desktop app)

## 🖼 GUI Preview

![GUI Screenshot Placeholder](gui_screenshot.png)  
*(Replace with actual screenshot of the GUI window)*

## 📚 Course Information

- **Course Name**: Artificial Intelligence - Lab
- **Semester**: 4th
- **Degree Program**: BS Data Science
- **Project Type**: Semester Project

## 📌 Example Prediction

> 🧾 A 2019 Toyota Corolla, driven 35,000 km, Petrol → **Predicted Price: ₹9.2 Lakhs** (via GUI)

## 🧑‍💻 How to Run

```bash
1. Clone the repo
2. Install dependencies
3. Run the notebook or export the GUI part as .py
4. Launch GUI → Input → Predict!
