# Forecasting-Warner-Music-Group-Stock-Prices-Using-ARIMA

# Introduction 

**1. Objective:** The goal of this project is to forecast the future revenue of Warner Music Group (WMG) using historical financial data.

**2. Significance:** Accurate revenue forecasting can help in strategic planning, budgeting, and investment decisions for companies and stakeholders.


# Problem Defination

With the increasing competition in the music industry, it's crucial for Warner Music Group to anticipate revenue trends and prepare accordingly. This project aims to develop a forecasting model that predicts future revenue based on past performance.


# Project Steps

**Step 1: Data Preparation**

**1. Loading Data:** Read the WMG revenue data from the provided Excel file.

**2. Exploration:** Analyze the data to understand its structure, check for missing values, and perform initial data cleaning.



**Step 2: Feature Engineering**

**1. Time Features:** Extract relevant time-based features, such as Year and Quarter.

**2. Lag Features:** Create lagged revenue features to help the model learn from past performance.



**Step 3: Splitting Data**

**Train-Test Split:** Split the dataset into training and testing sets to evaluate the model's performance effectively.



**Step 4: Data Scaling**

**Normalization:** Scale the revenue data for better model performance using techniques like StandardScaler.



**Step 5: Model Selection**

**Choose a Forecasting Model:** For this project, you can use models like ARIMA, LSTM, or a simple linear regression model.



**Step 6: Forecasting**

**Make Predictions:** Use the trained model to forecast future revenue and evaluate it against the test data.



**Step 7: Evaluation**

**Metrics:** Evaluate model performance using metrics like Mean Absolute Error (MAE) or Mean Squared Error (MSE).



**Step 8:** Data Visualization

**Visualize Results:** Use libraries like Matplotlib or Seaborn to plot the actual vs. predicted revenue.


# Results

**Visual Insights:** 

The chart displays the closing price of Warner Music Group stock over time, represented by the blue line, which shows significant fluctuations, particularly peaking around mid-2021. The 20-day moving average (orange line) provides a short-term view, reacting quickly to recent price changes, while the 50-day moving average (green line) offers a more stable perspective of the overall trend. The analysis indicates that the stock generally trended upward from mid-2020 to mid-2021 but became more volatile in late 2022 and early 2023. Crossings between the closing price and moving averages suggest potential buy (when the price crosses above) or sell (when the price crosses below) signals, providing valuable insights for investors and traders in understanding the stock's behavior.
<img width="841" alt="Screenshot 2024-09-29 at 4 46 35 PM" src="https://github.com/user-attachments/assets/29263958-796d-42e8-93a3-2042819e76ae">

<img width="833" alt="Screenshot 2024-09-29 at 4 52 33 PM" src="https://github.com/user-attachments/assets/8de0dee6-d3d7-45e0-b426-afdd697180e2">



