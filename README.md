# Car-Price-Prediction-

**Dataset Overview:**
**Shape:** The dataset contains 2,059 rows and 20 columns.
**Purpose:** The dataset is used for predicting car prices based on various features.

**Column Descriptions:**
**Make** (Object): The brand or manufacturer of the car (e.g., Honda, Toyota, Hyundai).
**Model** (Object): The specific model of the car.
**Price** (Integer): The selling price of the car (Target variable).
**Year** (Integer): The year in which the car was manufactured.
**Kilometer** (Integer): The number of kilometers the car has traveled.
**Fuel Type** (Object): Type of fuel used (Petrol, Diesel, etc.).
**Transmission** (Object): Type of transmission (Manual or Automatic).
**Location** (Object): City where the car is available for sale.
**Color** (Object): The exterior color of the car.
**Owner** (Object): Ownership history (First owner, Second owner, etc.).
**Seller Type** (Object): Whether the car is being sold by an individual, dealer, or corporate entity.
**Engine** (Object, with missing values): Engine displacement in cc (e.g., 1198 cc, 2393 cc).
**Max Power** (Object, with missing values): Maximum power output (e.g., 87 bhp @ 6000 rpm).
**Max Torque** (Object, with missing values): Maximum torque output (e.g., 109 Nm @ 4500 rpm).
**Drivetrain** (Object, with missing values): The type of drivetrain (FWD, RWD, AWD).
**Length** (Float, with missing values): The length of the car in mm.
**Width** (Float, with missing values): The width of the car in mm.
**Height** (Float, with missing values): The height of the car in mm.
**Seating Capacity** (Float, with missing values): Number of seats available.
**Fuel Tank Capacity** (Float, with missing values): Fuel tank capacity in liters.

**Exploratory Data Analysis (EDA) Performed:**
**Data Cleaning:** Handled missing values in "Engine," "Max Power," "Max Torque," "Drivetrain," and other numerical columns.
**Feature Engineering:** Extracted numerical values from "Engine," "Max Power," and "Max Torque" (as they contain units like 'cc', 'bhp', 'Nm').
**Data Visualization:**
Distribution of car prices.
Relationship between "Kilometer" driven and "Price."
Comparison of fuel types and their price variations.
Impact of transmission type on pricing.

**Outlier Detection:** Identified and handled extreme values in "Kilometer" and "Price" columns.

**Machine Learning Models Used:**
**Linear Regression:** Used as a baseline model.
**Ridge and Lasso Regression:** Applied to handle multicollinearity and feature selection.
**Decision Tree Regressor:** Used for non-linear relationships.
**Random Forest Regressor:** Implemented for better generalization and improved accuracy.
