#Housing Price Analysis Project

This project explores the Housing Price Prediction Dataset from Kaggle using Pandas, Python, and optional visualizations.

📌 Dataset

Kaggle Dataset: Housing Price Prediction
Contains details such as:

Price

Area

Bedrooms

Bathrooms

Stories

Furnishing status

Access to main road

Parking and other features

🚀 Steps Performed
1. Load the Dataset

The dataset is loaded into Pandas using:

import pandas as pd
df = pd.read_csv('Housing.csv')
2. Explore the Data

df.head() to preview rows

df.describe() for statistical overview

Checked missing values using df.isnull().sum()

No missing data was found

3. Compute Statistics

Statistics calculated for price, area, and bedrooms:

Mean

Median

Mode

Variance

Standard Deviation

Skewness

Kurtosis

Minimum & Maximum values

4. Visualizations (Optional)

Histogram for price and area

Scatter plot: price vs. area

Box plot for price distribution

📊 Key Insights (Short Story)

The housing data shows a wide variety of prices and areas, with some very expensive homes raising the average. Most houses have 2–3 bedrooms, and both price and area vary significantly across the dataset. Prices are right‑skewed, meaning a few luxury homes influence the average strongly. Area affects price, but features like location and furnishing also play an important role.
