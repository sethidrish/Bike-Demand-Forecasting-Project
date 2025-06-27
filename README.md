# Bike Sharing Demand Forecasting Project

A machine learning project to forecast the hourly demand for a public bike-sharing program based on historical usage patterns and environmental factors.

---

### Technologies & Concepts Demonstrated
* **Languages/Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook
* **Concepts:** Data Cleaning, Feature Engineering, Exploratory Data Analysis (EDA), Predictive Modeling, Time Series Analysis, Model Evaluation

---

### Project Goal
The goal of this project was to build a machine learning model to accurately forecast the hourly rental demand for a bike-sharing program. This can help the company with resource allocation and inventory management.

### Data Source
The dataset used for this project is the "Bike Sharing Demand" dataset from the UCI Machine Learning Repository, made available on Kaggle. You can find it [here](https://www.kaggle.com/c/bike-sharing-demand/data).

### Key Findings & Visualizations
Through Exploratory Data Analysis (EDA), several key patterns were identified:
* **Commuter Patterns:** A clear two-peak "rush hour" pattern was observed on working days (approx. 8 AM and 5-6 PM), while a single, broader leisure-driven peak was observed on weekends and holidays.
* **Seasonal Trends:** Demand is highest in the summer and fall months and lowest in the winter.
* **Weather Impact:** Clear weather conditions and warmer temperatures strongly correlate with higher rental counts.

### Model & Performance
A `RandomForestRegressor` model was trained on the preprocessed data. Key features included the hour, temperature, working day status, and humidity.

* **Final Model Performance (RMSE):** The model achieved a **Root Mean Squared Error of approximately 53.6**, indicating that, on average, the model's predictions are off by about 54 bikes.

### How to Run This Project
1.  Clone this repository to your local machine.
2.  Download the data from the [Kaggle competition page](https://www.kaggle.com/c/bike-sharing-demand/data).
3.  Place the `train.csv` file in the main project folder.
4.  Run the cells sequentially in the `Bike_Demand_Forecasting.ipynb` Jupyter Notebook.
