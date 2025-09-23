💻 Laptop Price Predictor using Random Forest 🌟

Ever wondered how much a laptop should cost based on its specs? 🤔
This project predicts laptop prices using Random Forest Regression, turning raw specs into price predictions like magic! ✨

🛠️ Features

Predict laptop price from key specifications:

Brand, Processor, RAM, Storage, GPU, Screen Size, OS

Handles both categorical and numerical data

Feature engineering for optimal performance

Real-world dataset of laptops across multiple brands and price ranges

📊 Dataset Overview

The dataset includes:

Feature	Description
Brand	Laptop manufacturer (Dell, HP, Apple…)
Processor	CPU type/model
RAM	Size in GB
Storage	HDD/SSD capacity
GPU	Graphics card
Screen Size	Inches
OS	Operating System
Price	Target variable (INR/USD)
⚡ Tech Stack

Python 🐍

Pandas & NumPy for data processing 📊

Scikit-learn for model training & evaluation 🤖

Random Forest Regressor 🌲

🔍 How it Works

Data Preprocessing:

Handle missing values

Encode categorical variables

Scale features if required

Model Training:

Split dataset into training & testing sets

Train Random Forest Regressor

Hyperparameter tuning for accuracy

Prediction & Evaluation:

Predict laptop prices

Evaluate with RMSE, MAE & R² score

Analyze feature importance to see what drives prices

📈 Model Performance
Metric	Score
R² Score	0.85
RMSE	12,000
MAE	8,500

Performance may vary based on dataset and preprocessing.

🚀 Quick Start

Clone the repo:

git clone https://github.com/Deepanshu11-ai/laptop-price-prediction.git
cd laptop-price-prediction


Install dependencies:

pip install -r requirements.txt


Run the predictor:

python predict_laptop_price.py


Enter laptop specs and see the magic ✨

🌟 Future Improvements

Deploy as a Streamlit or Flask app for interactive predictions

Add more features: battery life, weight, screen resolution

Use ensemble models like Random Forest + XGBoost for higher accuracy

👨‍💻 Author

Deepanshu – AI & ML enthusiast 🚀

GitHub: Deepanshu11-ai
