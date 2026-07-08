# 💼 Salary Prediction using Simple Linear Regression

A beginner-friendly Machine Learning project that predicts an employee's salary based on their years of experience using **Simple Linear Regression** with Scikit-learn.

---

## 📌 Project Overview

This project demonstrates how to build a simple regression model that learns the relationship between:

- **Input:** Years of Experience
- **Output:** Salary

The model is trained using the Linear Regression algorithm from Scikit-learn.

---

## 📂 Project Structure

```
├── regression.ipynb        # Jupyter Notebook
├── Salary Data.csv         # Dataset
└── README.md
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset

The dataset contains two columns:

| Column | Description |
|---------|-------------|
| Years of Experience | Employee's years of experience |
| Salary | Employee's salary |

---

## 🚀 Steps Performed

1. Import required libraries.
2. Load the dataset using Pandas.
3. Remove missing values.
4. Select input and target variables.
5. Split the dataset into training and testing sets.
6. Train the Linear Regression model.
7. Evaluate the model using the R² score.

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/salary-prediction-linear-regression.git
```

Install the required libraries:

```bash
pip install pandas scikit-learn notebook
```

---

## ▶️ Run the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```
regression.ipynb
```

Run all cells.

---

## 📈 Model Used

- Linear Regression (`sklearn.linear_model.LinearRegression`)

---

## 📋 Example Code

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)

score = model.score(X_test, y_test)
print(score)
```

---

## 🎯 Learning Outcomes

- Loading datasets with Pandas
- Data preprocessing
- Train-test splitting
- Building a Linear Regression model
- Evaluating model performance
- Understanding regression problems

---

## 🔮 Future Improvements

- Data visualization using Matplotlib/Seaborn
- Predict salary for custom inputs
- Save the trained model using Pickle or Joblib
- Build a web app using Streamlit or Flask

---

## 👨‍💻 Author

**Manoj Kumar R**

- GitHub: https://github.com/manojkumar2107
- LinkedIn: https://www.linkedin.com/in/manoj-kumar-r-36bb22332/

---

## 📄 License

This project is intended for educational and learning purposes.
