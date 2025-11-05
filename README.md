# car_dekho_project
🚗 Used Car Price Prediction (CarDekho Dataset)

This project predicts the selling price of used cars based on features like brand, model year, fuel type, mileage, and ownership history. The goal is to help buyers and sellers get a fair price estimate before making a deal.

## What this project does

Cleans and prepares the dataset (handles missing values, encodes categories, etc.)

Performs exploratory analysis to understand which factors impact price

Builds and compares multiple machine learning models

Selects the best-performing model and saves it for reuse

## Dataset Info

Each row in the dataset represents a single used car listing, with details like:

## Column	Description

Car_Name	Vehicle model name

Year	Manufacturing year

Selling_Price	Selling price (Target)

Present_Price	Current showroom price

Kms_Driven	Total kilometers driven

Fuel_Type	Petrol / Diesel / CNG

Seller_Type	Dealer / Individual

Transmission	Manual / Automatic

Owner	Number of previous owners


## Models Tried

Linear Regression	Works, but not very accurate

Random Forest	Best model — balanced and accurate ✅

Gradient Boosting	Good, but tends to overfit slightly
