# 🏏 IPL Winning Team Prediction Using Machine Learning

## 📌 Overview

This project predicts the **winning team** in an IPL (Indian Premier League) cricket match based on various match-related factors such as venue, teams, toss decision, and current score situation.
By analyzing historical IPL data, the model learns patterns that contribute to a team's winning chances and makes predictions for ongoing or future matches.

---

## 🗂 Dataset

* **Source:** Kaggle / IPL official match statistics (historical IPL data)
* **Features Used:**

  * Batting team
  * Bowling team
  * Venue
  * Toss winner & decision
  * Current score, overs completed, wickets lost
  * Target score (in second innings)
* **Target Variable:** Match result (Winning team)

---

## ⚙️ Technologies Used

* **Python** 🐍
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib / Seaborn** – Data visualization
* **Scikit-learn** – Machine learning model building
* **Jupyter Notebook / VS Code** – Development environment

---

## 🧠 Machine Learning Approach

1. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical variables (teams, venues)
   * Feature scaling for numerical values
2. **Model Training**

   * Applied classification algorithms like:

     * Logistic Regression
     * Random Forest Classifier
     * Gradient Boosting
   * Used historical match data for training
3. **Model Evaluation**

   * Accuracy score
   * Confusion matrix
   * Cross-validation for better generalization

---

## 📊 Results

* Achieved **high prediction accuracy** on test data.
* Random Forest & Gradient Boosting performed best.
* Model predicts the **winning probability** for each team before or during the match.

---

## 🚀 How to Run the Project

1. **Clone the repository**

```bash
git clone https://github.com/your-username/IPLWinningPrediction.git
cd IPLWinningPrediction
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook**

```bash
jupyter notebook IPL_Winning_Team_Prediction.ipynb
```

4. **Or run the Python script**

```bash
python ipl_prediction.py
```

---

## 📌 Example Prediction

Input:

```plaintext
Batting Team: Mumbai Indians  
Bowling Team: Chennai Super Kings  
Venue: Wankhede Stadium  
Overs Completed: 10.2  
Runs Scored: 85  
Wickets Lost: 2  
```

Output:

```plaintext
Prediction: Mumbai Indians have a 78.5% chance of winning the match.
```

---

## 📢 Conclusion

This project shows how **machine learning** can be applied to **sports analytics** for predicting match outcomes.
It can help **fans, analysts, and fantasy cricket players** in making informed predictions based on data-driven insights.



If you want, I can also make a **GitHub README for your Lung Cancer Prediction** so all your projects have a **consistent style**.
Do you want me to do that next?
