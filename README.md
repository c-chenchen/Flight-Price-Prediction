# Flight Price Prediction

This project uses machine learning techniques to predict **Flight Price Prediction** 

## Files in This Repository
Clean_Dataset – Dataset used for training and testing  
Prediciton_analysis.ipynb – Main notebook containing data analysis and models  
README.md – Project documentation  

## Project Overview
The goal of this project is to build and evaluate regression models that can accurately predict flight price. The project includes data exploration, feature engineering, model training, and performance evaluation.

## Dataset
The dataset used is the Flight Price dataset, which contains information such as:
- Unnamed: 0
- airline
- flight
- source_city
- departure_time	
- stops	
- arrival_time
- destination_city
- class
- duration
- days_left
- price


## Methods Used
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature engineering
- Machine learning regression models

## Models Implemented
- **Random Forest Regressor**

## Results
| Model | R² Score |
|------|----------|
| Random Forest | 0.9863 |

The Random Forest model achieved the best performance, demonstrating its ability to capture non-linear relationships in the data.

## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/c-chenchen/Flight-Price-Prediction.git

```
2. Install required packages:
```bash
pip install pandas numpy matplotlib scikit-learn

```
3. Open the notebook:
```bash
jupyter notebook Prediction_analysis.ipynb

```
## Author

Pirawit Kokiatwarakun

