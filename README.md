# 🏏 IPL Insight Engine

### *18-Season Predictive Analytics (2008–2025)*

### *Moving Beyond the Scorecard: A Data-Driven Study of T20 Strategy*

---

## 🚀 Overview

The **IPL Insight Engine** is a professional-grade sports analytics project that transforms **18 years of IPL match data** into actionable insights.

By engineering advanced contextual features such as **Team Momentum**, **Venue Bias**, and **Psychological Head-to-Head (H2H)**, the model achieves:

> 🎯 **55.6% prediction accuracy**, outperforming the 50% statistical baseline.

This project demonstrates how data science can elevate cricket strategy from intuition to **evidence-based decision making**.

---

## 🏗️ Engineering Pipeline

### 🧹 Advanced Data Sanitization

* 🔄 **Franchise Rebranding Handling**

  * Delhi Daredevils → Delhi Capitals
  * Kings XI Punjab → Punjab Kings
* 🌍 **Geographical Consolidation**

  * Reduced **59+ venue variations** into structured categories
  * Included international venues (UAE, South Africa)
* 🚫 **Washout Filtering**

  * Removed *“No Result”* matches to eliminate noise

---

### 🧠 Strategic EDA (Exploratory Data Analysis)

* 📉 **The Toss Myth**

  * Correlation between toss win & match win ≈ **0.00**
  * Conclusion: Toss has **no significant impact**

* 📈 **Run Inflation Trend**

  * Average first innings score:

    * Early IPL → ~160
    * Recent seasons → **190+**

* 🏟️ **Venue DNA Classification**

  * **Chasing Grounds** → Higher success in run chases
  * **Defending Grounds** → Favor defending totals

---

## 🤖 Machine Learning & Feature Engineering

### 🧩 Model

* **Random Forest Classifier (300 estimators)**
* Chosen for:

  * Handling non-linear relationships
  * Strong performance on categorical-heavy data

---

### 💡 Engineered "Moneyball" Features

* 📊 **H2H Rate**

  * Team dominance based on historical matchups

* 🔥 **Season Momentum**

  * Rolling cumulative wins to detect "form"

* 🏠 **Venue Win Rate**

  * Quantified home-ground advantage

---

### 🔍 Explainable AI (XAI)

* Used **SHAP values** to interpret model decisions
* Key findings:

  * 🥇 H2H history = Most influential
  * 🥈 Venue = Strong predictor
  * ❌ Toss = Least important

---

## 🏆 Prescriptive Analytics (Real-World Applications)

### 🎮 Fantasy Advisor

* Identifies high-impact players based on:

  * Venue specialization
  * Player-of-the-Match trends
* Example:

  * Detects “Ground Kings” with repeated success at specific stadiums

---

### 📊 Strategy Dashboard

* Interactive **What-If Simulator**
* Helps captains decide:

  * Bat vs Field after toss
  * Based on venue-specific probabilities

---

## 🛠️ Tech Stack

| Category       | Tools Used          |
| -------------- | ------------------- |
| Language       | Python 3.x          |
| Data Handling  | Pandas, NumPy       |
| ML Modeling    | Scikit-Learn        |
| Visualization  | Matplotlib, Seaborn |
| Explainability | SHAP                |
| Deployment     | Streamlit           |
| Serialization  | Joblib              |

---

## 📂 Project Structure

```
IPL-Insight-Engine/
│── data/
│── notebooks/
│── models/
│── app/
│── src/
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/ipl-insight-engine.git
cd ipl-insight-engine
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
streamlit run app/app.py
```

---

## 📈 Results

* ✅ Prediction Accuracy: **55.6%**
* 📊 Dataset Size: ~1100 matches
* 🎯 Outperforms baseline randomness

---

## 🔥 Key Takeaways

* Cricket is not purely random — **context matters**
* Toss advantage is **overrated**
* Venue and H2H dynamics are **critical decision factors**
* Data can power:

  * 📺 Broadcasting insights
  * 🎮 Fantasy platforms
  * 🏏 Team strategy

---

## 🚀 Future Improvements

* Deep Learning models (LSTM for sequence modeling)
* Player-level predictive analytics
* Live match prediction system
* API deployment for real-time use

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork, improve, and submit a PR.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Abhiram Modukuru**

* AIML Student | Data Science Enthusiast
* Passionate about Sports Analytics & Business Intelligence
---
