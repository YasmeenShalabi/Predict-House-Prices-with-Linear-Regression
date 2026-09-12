****California Housing Price Prediction using Linear Regression**
**


**Overview**

This project uses the California Housing dataset from scikit‑learn to build a Linear Regression model that predicts median house values across California districts. The dataset includes features such as median income, house age, average rooms, population, and geographic coordinates.

The goal is to demonstrate a full machine‑learning workflow:
data loading → preprocessing → model training → evaluation → prediction.


**Dataset**


The California Housing dataset contains:

20,640 samples

8 numerical features

Target: MedHouseVal (median house value in $100,000 units)

Features include:

MedInc — Median income

HouseAge — Median house age

AveRooms — Average number of rooms

AveBedrms — Average number of bedrooms

Population — Block group population

AveOccup — Average household occupancy

Latitude / Longitude — Location coordinates


**Modeling Steps**


1. Load dataset using fetch_california_housing().

2. Convert to a pandas DataFrame.

3. Split data into training and testing sets (80/20).

4. Train a Linear Regression model.

5. Evaluate using:

    Mean Squared Error (MSE)
   
    R² Score

7. Inspect model coefficients.

8. Predict house value for new custom input.


**Evaluation Metrics**


MSE: Measures average squared error between actual and predicted values.

R² Score: Indicates how well the model explains variance (closer to 1 = better).
