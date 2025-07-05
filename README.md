# Student_performance_prediction
Predicts student pass/fail outcomes using logistic regression based on study hours and attendance.



# 📊 Student Performance Prediction using Logistic Regression

This project builds a simple machine learning model that predicts whether a student will pass or fail based on two features: **Hours Studied** and **Attendance Percentage**.

---

## 🧠 Objective

To predict a student's outcome (Pass/Fail) using Logistic Regression based on their study habits and attendance.

---

## 📁 Dataset

A manually created dataset of 20 records with the following columns:

- `Hours_Studied` (Number of hours a student studied)
- `Attendance` (Percentage of attendance)
- `Pass_Fail` (1 = Pass, 0 = Fail)

---

## 🔧 Tools & Libraries Used

- Python 3.x
- Pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook / Google Colab

---

## 🔍 Steps Followed

1. **Created a dataset manually** in the notebook.
2. **Visualized** the data to understand the relationship.
3. **Split** the dataset into training and testing sets.
4. **Trained** a Logistic Regression model.
5. **Evaluated** the model using accuracy and classification metrics.
6. **Predicted** new student outcomes based on **user input**.

---

## 💻 User Input Feature

At the end of the notebook, you will be prompted to enter:

- Hours studied
- Attendance percentage

The model will predict and print:

```text
✅ The student is likely to PASS.
❌ The student is likely to FAIL.

This makes the project interactive and user-friendly!


---

📈 Sample Output

Enter hours studied: 4
Enter attendance percentage: 80

Prediction result:
✅ The student is likely to PASS.


---

💡 How to Run

1. Clone or download this repository.


2. Open Student_Performance_Prediction_UserInput.ipynb in Jupyter Notebook or Google Colab.


3. Run all cells to train the model.


4. Enter your input when prompted.




---

📌 Project Status

✅ Completed basic implementation with user interaction.
🚀 Can be extended with real-world data or more features like assignments, quiz marks, etc.


---

🧑‍💻 Author

M. Mohamed Anas
m.mohamedanas10.06@gmail.com
Intern at NSP NEXUS – Week 2 Project


---

📎 License

This project is for educational purposes under MIT License.
