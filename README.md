# 🏠 House Price Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📌 Overview

This project demonstrates a complete Machine Learning workflow by building a **Linear Regression** model to predict California housing prices using the **California Housing Dataset** from Scikit-Learn.

The project covers every stage of a real-world ML pipeline, including data loading, exploratory data analysis (EDA), preprocessing, model training, evaluation, visualization, and model serialization.

This project was developed as part of an Artificial Intelligence & Machine Learning assignment and is designed to serve as a beginner-friendly portfolio project.

---

## 🎯 Objectives

- Load and explore the California Housing Dataset
- Perform Exploratory Data Analysis (EDA)
- Train a Linear Regression model
- Evaluate model performance using standard regression metrics
- Visualize predictions
- Save the trained model for future use

---

## 📂 Dataset

**Dataset:** California Housing Dataset

The dataset contains information collected from the 1990 California Census, including housing characteristics such as:

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

**Target Variable**

- Median House Value (`MedHouseVal`)

The dataset is directly available through Scikit-Learn.

```python
from sklearn.datasets import fetch_california_housing
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Jupyter Notebook

---

## 📁 Project Structure

```
House-Price-Prediction-Linear-Regression/
│
├── notebook/
│   └── task1_ml_linear_regression.ipynb
│
├── src/
│   ├── train.py
│   ├── evaluate.py
│   └── predict.py
│
├── model/
│   └── house_price_model.pkl
│
├── images/
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   └── residual_plot.png
│
├── report/
│   └── House_Price_Prediction_Report.pdf
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset Overview
- Statistical Summary
- Missing Value Analysis
- Correlation Heatmap
- Feature Relationships

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Linear Regression

The model is trained using Scikit-Learn's `LinearRegression()` class.

---

## 📈 Model Evaluation

The model performance is evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Example Output

```
MAE  : 0.53
RMSE : 0.75
R²   : 0.57
```

*(Actual values may vary slightly depending on the train-test split.)*

---

## 📉 Visualizations

The project generates:

- Correlation Heatmap
- Actual vs Predicted Plot
- Residual Plot

---

## 💾 Saving the Model

The trained model can be saved using Joblib.

```python
import joblib

joblib.dump(model, "house_price_model.pkl")
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/House-Price-Prediction-Linear-Regression.git
```

Go to the project directory

```bash
cd House-Price-Prediction-Linear-Regression
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook or Python scripts.

---

## 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
jupyter
```

---

## 🔮 Future Improvements

- Feature Engineering
- Hyperparameter Tuning
- Cross Validation
- Random Forest Regression
- XGBoost Regressor
- Flask Web Application
- Streamlit Deployment

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data preprocessing
- Exploratory Data Analysis
- Linear Regression
- Regression evaluation metrics
- Data visualization
- Model serialization
- Machine Learning workflow

---

## 🤝 Contributing

Contributions are welcome.

If you'd like to improve this project, feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Shiva Singh**

B.Tech Computer Science & Engineering (AI/ML)

Galgotias University

GitHub: https://github.com/shivasingh2005

---

⭐ If you found this project helpful, consider giving it a star!
