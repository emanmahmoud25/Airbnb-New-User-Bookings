# Airbnb New User Bookings Prediction

![airbnb](https://github.com/user-attachments/assets/fdc7f573-2634-4ae6-a23c-be56b837c919)

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





