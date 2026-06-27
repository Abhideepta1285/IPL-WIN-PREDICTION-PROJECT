# 🏏 IPL Win Predictor

Predict the winning probability of the chasing team in an IPL match using Machine Learning and Streamlit.


---

## 📌 Project Overview

This project predicts the **winning probability of the chasing team** during the second innings of an IPL match using ball-by-ball match data.

The model continuously updates the winning chances after every over based on the current match situation.

---

## 🚀 Live Demo

👉 **Streamlit App:** (Add your Streamlit link here)

Example:

https://ipl-win-predictor.streamlit.app

---

## 📂 Dataset

Dataset Source:
https://www.kaggle.com/datasets/ramjidoolla/ipl-data-set

Dataset contains:

- Match information
- Ball-by-ball delivery data
- Team details
- Venue details
- Match results

---

## ✨ Features

- Predicts live winning probability
- Supports all IPL teams
- Calculates:
  - Runs Left
  - Balls Left
  - Current Run Rate (CRR)
  - Required Run Rate (RRR)
  - Wickets Left
- Interactive Streamlit interface

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- Streamlit
- Matplotlib

---

## 📊 Machine Learning Pipeline

### Data Collection

- IPL Matches Dataset
- IPL Deliveries Dataset

### Data Preprocessing

- Data Cleaning
- Missing Value Handling
- Feature Engineering
- One-Hot Encoding

### Features Used

- Batting Team
- Bowling Team
- City
- Target
- Runs Left
- Balls Left
- Wickets Left
- Current Run Rate
- Required Run Rate

### Model

- Logistic Regression

---

## 📈 Model Performance

Accuracy:

```
Accuracy: 80%
```



---


## 📁 Project Structure

```
IPL-Win-Predictor
│
├── app.py
├── pipe.pkl
├── requirements.txt
├── README.md
├── matches.csv
├── deliveries.csv
├── IPL WIN PRDICTION.ipynb

```

---


## 🧠 How It Works

1. User selects

- Batting Team
- Bowling Team
- Host City
- Target
- Current Score
- Overs Completed
- Wickets Fallen

2. Application calculates

- Runs Left
- Balls Left
- CRR
- RRR

3. Machine Learning model predicts

- Winning Probability
- Losing Probability

---

## 📊 Feature Engineering

The following features are generated before prediction:

- Current Score
- Runs Left
- Balls Left
- Wickets Left
- Current Run Rate
- Required Run Rate

---


## 🤝 Contributing

Contributions are welcome.

Feel free to fork this repository and submit a Pull Request.


---

## 👨‍💻 Author

**Abhideepta**


---

⭐ If you found this project helpful, please consider giving it a star.