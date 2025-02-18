# Hotel Price Prediction and Optimization

## 📌 Project Overview

This project aims to analyze hotel booking trends and optimize room pricing using **Machine Learning** techniques. The primary objective is to predict the **Average Daily Rate (ADR)** based on various factors like booking lead time, customer demographics, and seasonal trends. Additionally, we explore revenue management strategies to optimize room pricing and maximize occupancy.

## 🚀 Features

- **Data Cleaning & Preprocessing**: Handled missing values, duplicates, and inconsistent records.
- **Exploratory Data Analysis (EDA)**: Visualized booking trends, cancellation rates, seasonality, and lead times.
- **Machine Learning Models**: Implemented various models for ADR prediction, including:
  - **Linear Regression**
  - **Decision Tree Regressor**
  - **Random Forest Regressor**
  - **Gradient Boosting Regressor**
  - **XGBoost Regressor**
  - **K-Nearest Neighbors (KNN)**
  - **Support Vector Regressor (SVR)**
- **Feature Engineering**: Created new features such as total stay duration, seasonal classification, and normalized ADR.
- **Website Interface**: Developed a **Streamlit-based** dashboard for data visualization and hotel price optimization.

## 📊 Dataset

We utilized the **Hotel Booking Demand Dataset** from Kaggle:

📌 [Dataset Link](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/data)

The dataset includes various attributes such as:
- Hotel type (City/Resort)
- Booking lead time
- Number of guests (adults, children, babies)
- Market segment & distribution channel
- Room type, cancellation status, deposit type
- Seasonal booking patterns
- Special requests, previous cancellations, and more.

## 🛠 Tech Stack

| Component                  | Technology Used |
|----------------------------|----------------|
| **Programming Language**    | Python 3.x     |
| **Data Processing**         | Pandas, NumPy, PySpark |
| **Visualization**           | Matplotlib, Seaborn, Plotly |
| **Machine Learning**        | Scikit-learn, XGBoost |
| **Web Framework**           | Streamlit |
| **Dataset Source**          | Kaggle |
| **Version Control**         | Git, GitHub |

## 📈 Model Performance

| Model                     | R² Score |
|---------------------------|----------|
| **Linear Regression**      | 0.4736   |
| **Decision Tree Regressor**| 0.56     |
| **Random Forest Regressor**| 0.65     |
| **Gradient Boosting**      | 0.59     |
| **KNN Regressor**         | 0.38     |
| **Support Vector Regressor** | 0.52  |
| **XGBoost Regressor**      | 0.8395   |

The **Random Forest** and **XGBoost** models performed the best, capturing both linear and non-linear relationships effectively.

## 📌 Results & Insights

- **Cancellation Rates**: ~27.5% of bookings get canceled, impacting revenue.
- **Seasonal Trends**: Peak cancellations occur in **June & December** due to holidays.
- **Lead Time Analysis**: Most bookings happen **10-20 days** before check-in.
- **Room Type Impact**: Some room categories experience higher cancellation rates.
- **Agent Performance**: Certain agents contribute more to high-value bookings.

## 💡 Future Enhancements

- Implement **deep learning models** for better ADR predictions.
- Integrate **real-time price recommendations** based on market demand.
- Deploy the **Streamlit web app** for public access.
- Enhance **feature selection & hyperparameter tuning** for improved accuracy.


