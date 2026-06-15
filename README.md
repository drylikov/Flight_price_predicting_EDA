# Flight Price Prediction - Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on a flight price dataset to understand key trends, relationships, and anomalies. The insights derived will later assist in building a machine learning model to predict flight prices.

---

## Dataset

The dataset contains flight-related features such as:

- `Date_of_Journey`
- `Airline`
- `Source`, `Destination`
- `Route`, `Dep_Time`, `Arrival_Time`
- `Duration`
- `Total_Stops`
- `Price`

---

## Objectives

- Clean and preprocess raw data.
- Understand feature distribution and correlations.
- Convert date, time, and categorical data into usable formats.
- Handle missing values and outliers.
- Generate visual insights to guide future modeling.

---

## Key Steps Performed

- Converted `Date_of_Journey`, `Dep_Time`, and `Arrival_Time` into numerical components (`day`, `month`, `hour`, `minute`).
- Extracted hours and minutes from the `Duration` column.
- Handled missing/null values.
- Encoded categorical variables like `Airline`, `Source`, and `Destination`.
- Performed correlation analysis between variables and price.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Next Steps

- Feature engineering for ML model.
- Build regression models (Linear, RandomForest, XGBoost).
- Hyperparameter tuning.
- Model evaluation and deployment.

---
