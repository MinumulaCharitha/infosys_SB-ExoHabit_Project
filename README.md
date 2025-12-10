Exoplanet Habitability Prediction – ML Project

This project analyzes exoplanet data to understand planetary characteristics and determine their potential habitability using Machine Learning.
The workflow is divided into structured modules for clarity and smooth development.

📌 Module 1: Data Collection & Understanding

-> Collected datasets from NASA Exoplanet Archive and Kaggle.
-> Explored rows, columns, and the meaning of each feature.
-> Identified key planetary and stellar attributes such as:
* Planet mass, radius, temperature
* Orbital period, distance from star
* Star type, luminosity, temperature
-> Checked dataset summary (shape, dtypes, missing values).
-> Understood the target variable for habitability classification.

📌 Module 2: Data Cleaning & Preprocessing

-> Handled missing values using mean/median for numeric columns.
-> Removed outliers using IQR method.
-> Fixed inconsistent values (e.g., star types like "G-type", "g type", → "g").
-> Converted categorical features to lowercase and standardized labels.
-> Generated essential visualizations:
* Scatter plot (Mass vs Radius)
* Histograms for key features
* Correlation heatmap


📁 Current Status

✔ Data collected
✔ Data cleaned
✔ Initial EDA completed
✔ Visualizations created
