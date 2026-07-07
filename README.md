<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0575E6,100:021B79&height=200&section=header&text=Titanic%20Survival%20Prediction&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35)

<a href="https://github.com">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&pause=1000&color=0575E6&center=true&vCenter=true&width=600&lines=Predicting+Survival+with+Machine+Learning;Logistic+Regression+%7C+Random+Forest+%7C+KNN;Pluto+Academy+AI+%26+ML+Internship+Project" alt="Typing SVG" />
</a>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

![Stars](https://img.shields.io/github/stars/Arunprasath-2717/titanic-survival-prediction?style=social)
![Forks](https://img.shields.io/github/forks/Arunprasath-2717/titanic-survival-prediction?style=social)

</div>

---

## 🚢 Project Overview

This project predicts **Titanic passenger survival** using Machine Learning — built as **Project 02** of the Pluto Academy AI & ML Internship Program.

We trained and compared **3 ML algorithms**, evaluated them with real metrics, and picked the best-performing model — just like a real ML engineering workflow.

---

## 📊 Dataset

**Titanic Dataset** — [Kaggle Link](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

891 passengers × 12 features including Age, Sex, Passenger Class, Fare, and Survival status.

---

## 🧠 Models Compared

| Model                  | Type                   |
|-------------------------|------------------------|
| 🔵 Logistic Regression  | Linear Classification  |
| 🌲 Random Forest        | Ensemble Learning      |
| 📍 K-Nearest Neighbors  | Distance-Based         |

---

## 🏆 Results

| Model                   | Accuracy   | Precision | Recall  | F1 Score |
|--------------------------|:----------:|:---------:|:-------:|:--------:|
| **Logistic Regression** | 🥇 0.8101  | 0.7857    | 0.7432  | 0.7639   |
| Random Forest            | 🥈 0.7989  | 0.7639    | 0.7432  | 0.7534   |
| KNN                      | 🥉 0.6983  | 0.6786    | 0.5135  | 0.5846   |

> ✅ **Best Model:** Logistic Regression — highest accuracy, precision, and F1 score.

---

## 🔍 Key Insight

Survival strongly correlated with:
- 👩 **Sex** (women survived far more — "women and children first")
- 🎟️ **Passenger Class** (1st class survived more than 3rd class)
- 💰 **Fare** (linked closely with class/wealth)

KNN underperformed due to **unscaled features** — Fare (0–500 range) dominated distance calculations over Sex (0–1 range), skewing predictions.

---

## 🛠️ Tools & Tech Stack

<div align="center">

![Python](https://skillicons.dev/icons?i=python)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white)

</div>

---

## 📂 Project Structure

```
titanic-survival-prediction/
│
├── Project02_Titanic_ML.ipynb    # Full notebook (EDA, cleaning, models, evaluation)
└── README.md                     # This file
```

---

## 🚀 How to Run

1. Clone this repo or open the notebook directly in Google Colab
2. Upload `Titanic-Dataset.csv` when prompted
3. Run all cells top to bottom

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:021B79,100:0575E6&height=100&section=footer)

⭐ **If you found this useful, consider giving it a star!** ⭐

</div>
