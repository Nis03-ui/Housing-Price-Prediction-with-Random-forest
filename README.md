🏠 Housing Price Prediction

A Machine Learning project that predicts house prices based on various housing features such as area, number of bedrooms, bathrooms, parking availability, and furnishing status.

This project uses a Housing Price dataset with 13 key features to train regression models and forecast property prices.

📊 Dataset

Dataset used: Housing Price Prediction Dataset (Kaggle)

The dataset contains 13 features describing house characteristics.

Features
Feature	Description
area	Size of the house (square feet)
bedrooms	Number of bedrooms
bathrooms	Number of bathrooms
stories	Number of floors
mainroad	Whether house is near main road
guestroom	Guest room availability
basement	Basement availability
hotwaterheating	Hot water heating availability
airconditioning	Air conditioning availability
parking	Number of parking spaces
prefarea	Located in preferred area
furnishingstatus	Furnishing status
price	Target variable (house price)
⚙️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

📈 Machine Learning Workflow

Data Loading

Data Preprocessing

Encoding Categorical Features

Exploratory Data Analysis (EDA)

Feature Correlation Analysis

Train-Test Split

Model Training

Model Evaluation

🧠 Model Used
Linear Regression / Random Forest Regression

The model learns the relationship between housing features and house price.

📊 Model Performance
Metric	Value
Mean Squared Error (MSE)	347,519,516,515
R² Score	0.93

The model explains 93% of the variance in housing prices, indicating strong predictive performance.

📉 Feature Importance

Key features influencing house price:

Area

Bathrooms

Air Conditioning

Parking

Stories

📁 Project Structure
housing-price-prediction
│
├── data
│   └── Housing.csv
│
├── notebooks
│   └── analysis.ipynb
│
├── src
│   └── model.py
│
├── README.md
└── requirements.txt
🚀 How to Run the Project
1 Install Dependencies
pip install -r requirements.txt
2 Run the Model
python model.py
📌 Future Improvements

Hyperparameter tuning

Advanced models (XGBoost, Gradient Boosting)

Deployment using Flask or FastAPI

Web interface for house price prediction

🎯 Project Goal

The goal of this project is to demonstrate practical machine learning skills, including:

Data preprocessing

Feature engineering

Regression modeling

Model evaluation

👨‍💻 Author

Nishan Bhandari

Machine Learning & Full Stack Development Enthusiast.
