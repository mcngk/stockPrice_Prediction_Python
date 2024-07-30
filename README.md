---

# Stock Price Prediction

## Overview

This is a web application for predicting stock prices using machine learning. The application uses historical stock data from Yahoo Finance and employs a Support Vector Regression (SVR) model to forecast future stock prices. The goal is to demonstrate knowledge of machine learning techniques and provide an interactive tool for users to explore stock price trends and predictions.

## Features

- **Input Ticker Symbol**: Enter a stock ticker symbol to fetch historical stock data.
- **Forecast Days**: Specify the number of days into the future to predict stock prices.
- **Data Visualization**: View historical stock price trends and predicted future prices.
- **Instructions and Disclaimers**: Clear instructions on how to use the app and important disclaimers about the predictions.

## Technologies Used

- **Python**: Programming language used for implementing the application.
- **Streamlit**: Framework for creating interactive web applications.
- **scikit-learn**: Library for machine learning models, specifically Support Vector Regression (SVR).
- **yfinance**: Library for fetching stock data from Yahoo Finance.
- **pandas**: Data manipulation and analysis library.
- **numpy**: Library for numerical operations.
- **matplotlib**: Plotting library (if needed for additional visuals).

## Setup and Installation

To run this application locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/mcngk/stock-price-prediction.git
   cd stock-price-prediction
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Prepare Data**
   - Ensure you have the `Data/stockNames.csv` file in the correct directory. This file should contain stock symbols and their names.

5. **Run the Application**
   ```bash
   streamlit run app.py
   ```

## Usage

1. **Enter a Stock Ticker Symbol**: Input a valid stock ticker symbol into the text field.
2. **Specify Forecast Days**: Enter the number of days you want to predict into the forecast input.
3. **View Results**: The application will display a line chart of historical stock prices and a table of predicted prices.

## Disclaimer

- This application is for demonstration purposes only.
- The predictions are not financial advice and should not be used for actual trading decisions.
- The accuracy of the predictions is limited and should be taken with caution.

## Contributing

Feel free to open issues or submit pull requests for improvements. Contributions are welcome!

## Contact

For any questions or comments, please reach out to [Mustafa Can Gök](https://github.com/mcngk).

---


![1](https://github.com/mcngk/stockPrice_Prediction_Python/assets/162835012/b2f59270-07fb-453b-9857-c547e43d0d29)
![2](https://github.com/mcngk/stockPrice_Prediction_Python/assets/162835012/4e70f894-b092-42bb-9bd7-62c6ae558d4f)
![4](https://github.com/mcngk/stockPrice_Prediction_Python/assets/162835012/567cb98b-68ca-47fc-a08d-1804a158954a)
![3](https://github.com/mcngk/stockPrice_Prediction_Python/assets/162835012/2adf9af5-78e8-475b-bec3-c4618bb4bba2)

