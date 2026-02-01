# Healthy-food-and-healthy-drink-system
Food and drinks for people who are in diet

# 🥗 Healthy Food & Drink Recommendation System

## 📌 Project Overview
This project is a **Healthy Food & Drink Recommendation System** built using **Python**, **Pandas**, and **Scikit-learn**.  
It was created as a **school project** to demonstrate basic concepts of **data handling**, **data preprocessing**, and **machine learning–based recommendations**.

> ⚠️ AI Usage Disclosure  
> This project was initially generated with the help of **AI (ChatGPT)**.  
> AI usage was **allowed by Miss Hiba**, and the code was **edited and modified by me**.

---

## 🎯 Project Objectives
- Store and manage food and drink nutritional data
- Clean and preprocess the dataset
- Scale numerical features
- Apply a machine learning recommendation model
- Recommend healthy food and drink items
- Understand real-world applications of Pandas and basic ML

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
  - StandardScaler  
  - NearestNeighbors  

---

## 📂 Dataset Description
The dataset is created manually inside the code and contains nutritional information.

Columns included:
- `item_name` – Name of the food or drink  
- `type` – Food or drink  
- `calories` – Calories per serving  
- `protein` – Protein content  
- `sugar` – Sugar content  
- `fat` – Fat content  
- `is_healthy` – 1 = Healthy, 0 = Not Healthy  

Duplicate items are removed and missing values are handled during preprocessing.

---

## 👤 User Profile (Sample Data)
A basic user profile is included for demonstration purposes:
- Age: 15  
- Height: 155 cm  
- Weight: 55 kg  
- Activity level: Moderate  
- Goal: Weight loss  
- Dietary preference: Vegetarian  

⚠️ Note: The current version does not personalize recommendations using this profile.  
It is included to show how user data could be used in future improvements.

---

## ⚙️ How the System Works
1. Nutritional data is stored in a Pandas DataFrame  
2. Duplicate records are removed  
3. Missing values are replaced  
4. Numerical features are scaled using `StandardScaler`  
5. A **K-Nearest Neighbors (KNN)** model is trained  
6. The system finds similar items and filters healthy recommendations  

---

## ▶️ How to Run the Project
1. Install required libraries:
   pip install pandas numpy scikit-learn

2. Run the Python file:
   python main.py

3. View the recommended healthy foods printed in the console

---

## 📤 Sample Output
Model Accuracy (Healthy Item Ratio): 0.88

Recommended Healthy Foods & Drinks:
- Apple  
- Salad  
- Yogurt  

---

## 🚀 Future Improvements
- Personalize recommendations based on user goals
- Use a larger real-world dataset
- Add calorie limits based on age and weight
- Create a graphical or web-based interface
- Improve accuracy using advanced ML models

---

## 📚 Learning Outcomes
- Learned how to use Pandas for data analysis
- Understood data preprocessing and feature scaling
- Gained experience with a basic ML recommendation system
- Applied programming to a real-life health problem

---

## 👩‍🏫 Credits
Student: Your Name  
Teacher: Miss Hiba  
AI Assistance: ChatGPT (used with permission)

---

✅ This project is created for educational purposes only.

