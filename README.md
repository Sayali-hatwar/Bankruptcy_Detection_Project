# 🧠  Bankruptcy Prediction System Using Machine Learning

## 📌 *Project Overview*

  This project presents a machine learning–powered binary classification system that predicts the likelihood of company bankruptcy based on financial and operational risk indicators. The model is deployed using Streamlit for real-time user interaction.

## 🔍 *Problem Statement*

  Bankruptcy poses significant financial risks. Timely prediction can support preventive decision-making. The goal is to classify companies into:

#### 0 → Bankrupt

#### 1 → Non-bankrupt

### 📊 *Features Used (Input Variables)*

The system takes six numeric inputs:
1. Industrial Risk

2. Management Risk

3. Financial Flexibility

4. Credibility

5. Competitiveness

6. Operating Risk

These are modeled as a 6-dimensional input vector:

𝑥⃗=[𝑥1,𝑥2,𝑥3,𝑥4,𝑥5,𝑥6]

## 🤖 *Model and Math*

Supervised learning classifier trained on labeled historical data.

Binary classification function:

𝑓:𝑅6→{0,1}

Model saved via Pickle (*finalized_model.sav*) and loaded at runtime.

### *Output:*

#### 0: The company is likely to be bankrupt

#### 1: The company is likely to remain solvent

## 🧩 *Tools & Technologies*

Python

Pandas, NumPy

Scikit-learn (training)

Pickle (model serialization)

Streamlit (UI for prediction)

PIL (image handling)

## 🚀 *App Preview*

Users input six risk factors, and the app predicts bankruptcy status with a clear result.

✔️ “The company is non-bankrupt”

❌ “The company is going to be bankrupt”

📄 [Download Full Project Report (PDF)](https://github.com/Sayali-hatwar/Bankruptcy_Detection_Project/blob/main/Bankruptcy_prevention_doc.pdf)

