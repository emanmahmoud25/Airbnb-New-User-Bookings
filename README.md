# Airbnb New User Bookings Prediction

![air22222222](https://github.com/user-attachments/assets/4cb3147f-955f-41b2-b327-bac6ff9f86f7)
[Report discussing problem.pdf](https://github.com/user-attachments/files/23925889/Report.discussing.problem.pdf)
This project predicts the first booking destination for new users on Airbnb based on their demographics, session behavior, and previous booking patterns. The goal is to recommend the most likely destination for new users, enhancing user experience and improving conversion rates.

## Project Overview

The project uses machine learning models to predict the first booking destination for new Airbnb users. The models consider user attributes like:

- **Demographics** (age, country, etc.)
- **Session behavior** (page views, time spent, etc.)
- **Booking patterns** (previous booking data)

The machine learning algorithms used in this project include:

- **LightGBM**
- **CatBoost**
- **XGBoost**
- **Neural Networks**

The models were evaluated using **NDCG@5** and **accuracy**, with the final model achieving **93% NDCG@5** and **87% accuracy**.

## Key Features

- **High accuracy**: The model predicts the first booking destination with high precision.
- **Data preprocessing and feature engineering**: Includes handling missing values, encoding categorical variables, and engineering useful features.
- **Model performance**: Achieved **93% NDCG@5** and **87% accuracy**, making it highly effective in recommending the first booking destination.
  
## Technologies Used

- **Python**
- **TensorFlow**
- **Scikit-learn**
- **LightGBM**
- **CatBoost**
- **XGBoost**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
  
Developed a web interface using **Flask** to capture user inputs, process data, and integrate with a machine learning model for predicting destination countries in real-time.

<img width="217" alt="flask" src="https://github.com/user-attachments/assets/1f3d3b61-61aa-4776-89e2-c3dd1ffbdf74" />






