# 📈 Pakistan Student Screen-Time & Exam Performance Analysis

## 📝 Project Overview
This project performs an Exploratory Data Analysis (EDA) and implements Predictive Machine Learning models on a custom synthetic dataset representing university students in Pakistan. The main objective is to analyze how daily digital habits—specifically smartphone screen time—influence academic outcomes (final exam percentages) and to build reliable models that can estimate student performance based on their demographics and daily routines.

---

## 📊 Dataset Features
The dataset contains records for 1,000 Pakistani university students with the following structural attributes:
* **Student_ID**: Unique identifier for each student.
* **Age**: Age of the student (ranging from 18 to 24).
* **Gender**: Gender of the student (Male / Female).
* **Daily_Screen_Time_Hours**: Total hours spent on a smartphone daily.
* **Main_App_Used**: The application where the student spends the majority of their screen time (e.g., Coursera, LinkedIn, Instagram, WhatsApp).
* **Study_Hours_Per_Day**: Total independent study hours per day.
* **Exam_Score_Percentage**: The final academic performance score (Target Variable).

---

## 🛠️ Tech Stack & Libraries Used
* **Language**: Python 3
* **Data Manipulation**: Pandas, NumPy
* **Data Visualization**: Matplotlib, Seaborn
* **Machine Learning**: Scikit-Learn (LabelEncoder, Train-Test Split, Linear Regression, RandomForestRegressor)
* **Evaluation Metric**: Root Mean Squared Error (RMSE)

---

## 📉 Key Insights from Data Visualization
1. **Screen Time vs. Exam Scores**: A clear negative correlation was observed; as non-educational daily screen time increases past a certain threshold, final exam percentages tend to decline.
2. **App Distribution**: Students prioritizing educational and professional platforms like Coursera and LinkedIn showed a higher density of optimal study-to-screen ratios compared to heavy social media usage.

---

## 🤖 Machine Learning Modeling & Evaluation
To accurately predict student exam scores, we implemented and evaluated two distinct machine learning frameworks to compare baseline linear trends against ensemble non-linear capabilities:

### Model Comparison Results:
* **Linear Regression RMSE**: `8.8190`
* **Random Forest Regressor RMSE**: `8.1669`

### 🔍 Conclusion:
The **Random Forest Regressor** outperformed the baseline Linear Regression model by achieving a lower Root Mean Squared Error (RMSE). This indicates that non-linear ensemble techniques are significantly more effective at mapping the complex, multi-dimensional interactions between a student's digital distractions, lifestyle demographics, and final academic metrics.

---

## 🚀 How to Run the Notebook
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
