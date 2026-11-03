# 📈 Pakistan Student Screen-Time & Exam Performance Analysis

## 📝 Project Overview              

This project explores the relationship between smartphone screen time, study habits, and academic performance among university students in Pakistan.

Using a synthetic dataset of 1,000 students, this project performs **Exploratory Data Analysis (EDA)** and applies Machine Learning models to understand how students' daily digital habits relate to their final exam scores.

The main objective is to identify patterns in students' screen time and study routines and build predictive models that estimate exam performance.

## 📊 Dataset Features

The dataset contains information about 1,000 Pakistani university students with the following features:

- **Student_ID:** A unique identifier assigned to each student.
- **Age:** Student's age, ranging from 18 to 24 years.
- **Gender:** Gender of the student (Male / Female).
- **Daily_Screen_Time_Hours:** Total hours spent using a smartphone each day.
- **Main_App_Used:** The application used most frequently, such as Coursera, LinkedIn, Instagram, and WhatsApp.
- **Study_Hours_Per_Day:** Number of hours spent studying independently each day.
- **Exam_Score_Percentage:** Student's final exam score, used as the target variable.

## 🛠️ Tech Stack & Libraries Used

- **Programming Language:** Python 3
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn
  - Label Encoding
  - Train-Test Split
  - Linear Regression
  - Random Forest Regressor
- **Evaluation Metric:** Root Mean Squared Error (RMSE)

## 📉 Key Insights from Data Visualization

The exploratory data analysis helped identify several patterns:

1. **📱 Screen Time vs. Exam Scores:** The analysis showed a negative relationship between screen time and exam scores. Students with higher daily screen time tended to have lower exam scores.

2. **📚 Study Hours and Academic Performance:** Study hours provided useful information for understanding differences in students' academic performance.

3. **📲 App Usage Patterns:** The dataset includes educational and professional applications such as Coursera and LinkedIn, alongside social platforms such as Instagram and WhatsApp. Comparing these categories helps explore differences in students' digital habits.

## 🤖 Machine Learning Modeling & Evaluation

Two regression models were implemented to predict students' exam scores. Their performance was compared using Root Mean Squared Error (RMSE).

### Model Comparison Results

| Machine Learning Model | RMSE |
|---|---:|
| Linear Regression | 8.8190 |
| Random Forest Regressor | 8.1669 |

### 🔍 Conclusion

The **Random Forest Regressor** achieved a lower RMSE of `8.1669` compared to Linear Regression, which achieved `8.8190`.

This suggests that Random Forest performed better on this dataset and captured patterns that the baseline Linear Regression model may not have captured as effectively.

The project demonstrates how data analysis and machine learning can be used to explore the relationship between students' digital habits, study routines, and academic performance.

## 🚀 How to Run the Notebook

Follow these steps to run the project on your local machine:

**1. Clone the repository**

```bash
git clone https://github.com/your-username/your-repository-name.git
```

**2. Navigate to the project directory**

```bash
cd your-repository-name
```

**3. Install the required libraries**

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

**4. Open the Jupyter Notebook**

```bash
jupyter notebook
```

Open the project notebook and run the cells to explore the dataset, visualizations, and machine learning models.

## ⚠️ Important Note

This project uses a **synthetic dataset**, not real student records. The findings and model performance demonstrate an analytical approach and should not be interpreted as verified conclusions about all university students in Pakistan.

## 👩‍💻 Author

**Maria Aqdas**

BS Data Science Student | Aspiring Data Scientist

