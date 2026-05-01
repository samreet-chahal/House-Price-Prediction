# 🏠 House Rent Prediction

Predict monthly rent for residential properties across 6 Indian cities using Machine Learning.

## Dataset
- 4,746 properties across Mumbai, Delhi, Bangalore, Chennai, Kolkata, Hyderabad
- Source: [Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/house-rent-prediction-dataset)

## Models & Results
| Model | R² | MAE |
|---|---|---|
| Linear Regression | 0.857 | ₹6,759 |
| Random Forest | 0.849 | ₹6,494 |
| **Gradient Boosting** | **0.860** | **₹6,361** |

## Key Features
- 3-step outlier removal (size/BHK, price/sqft, bathroom ratio)
- Log-transform on skewed Rent target
- 51 locality-level features, city/furnishing median encoding

## Run
```bash
pip install -r requirements.txt
jupyter notebook house_rental_prediction.ipynb
```
