# 🚗 Car Price Prediction using Machine Learning

## 📌 Overview

This project was completed as part of the **Oasis Infobyte Data Science Internship (OIBSIP)**.

The objective of this project is to develop a machine learning model that predicts the selling price of used cars based on various features such as the car's age, present price, kilometers driven, fuel type, seller type, transmission type, and ownership history.

---

## 🎯 Objective

The main goal of this project is to accurately estimate the selling price of a used car using regression algorithms.

The project demonstrates the complete machine learning workflow, including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Price Prediction

---

## 📂 Dataset

The project uses the **CarDekho Used Car Dataset**.

### Features

- Car Name
- Year
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

### Target Variable

- Selling Price

---

## 🛠 Technologies Used

- Python
- Google Colab / Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview
- Data cleaning
- Missing value analysis
- Feature engineering (Car Age)
- Correlation heatmap
- Selling Price distribution
- Car Age vs Selling Price
- Present Price vs Selling Price
- Fuel Type analysis

---

## ⚙ Data Preprocessing

The following preprocessing steps were carried out:

- Removed unnecessary columns
- Created a new feature (Car Age)
- One-Hot Encoding of categorical variables
- Feature selection
- Train-Test Split (80:20)

---

## 🤖 Machine Learning Models

The following regression models were trained and compared:

- Linear Regression
- Random Forest Regressor

---

## 📈 Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The Random Forest Regressor provided better prediction accuracy compared to Linear Regression.

---

## 📊 Visualizations

The notebook includes:

- Correlation Heatmap
- Histogram of Selling Prices
- Scatter Plot (Car Age vs Selling Price)
- Scatter Plot (Present Price vs Selling Price)
- Feature Importance Plot
- Actual vs Predicted Prices

---

## 📁 Project Structure

```
Task3_Car_Price_Prediction/
│
├── Car_Price_Prediction.ipynb
├── car data.csv
├── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/OIBSIP.git
```

### 2. Navigate to the Project Folder

```bash
cd OIBSIP/Task3_Car_Price_Prediction
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Run the Notebook

Open the notebook using Jupyter Notebook or upload it to Google Colab and execute all cells.

---

## 📌 Results

The trained machine learning model successfully predicts the selling price of used cars based on their features.

The project demonstrates how regression algorithms can assist buyers and sellers in estimating fair vehicle prices using historical data.

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Regression Algorithms
- Model Evaluation
- Data Visualization
- Machine Learning Workflow

---

## 👨‍💻 Author

**Mudasir Aslam**

- BS Mathematics
- Sukkur IBA University
- GitHub: https://github.com/your-username

---

## 🏢 Internship

**Organization:** Oasis Infobyte

**Domain:** Data Science

**Task:** Car Price Prediction using Machine Learning

---

## ⭐ Acknowledgements

This project was developed as part of the **Oasis Infobyte Data Science Internship Program** to gain practical experience in machine learning, predictive analytics, and data visualization using Python.
