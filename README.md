Stock Future Predictor

Overview
Stock Future Predictor is a web application built with Python, Streamlit, TensorFlow, and Facebook's Prophet model, designed to predict the future stock prices of various companies. The app allows users to input a stock ticker symbol, and it provides detailed predictions and visualizations based on historical data and advanced machine learning models.
![alt text](<Screenshot (375).png>)
Features
User Input: Input any stock ticker to fetch and analyze the historical stock data.
Data Visualization:
Closing Price vs. Time Chart
Moving Average Charts (100-day & 200-day)
Data Description: Summarizes the statistical properties of the data from 2010 to the current date.
Machine Learning:
Uses a pre-trained TensorFlow model to predict future stock prices.
Forecasting with Prophet to predict future trends for up to 4 years.
Interactive Charts: Displays the forecast using interactive Plotly charts.
Comparison: Visual comparison of predicted prices vs. original prices.

Installation
To run this project locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/stock-future-predictor.git
Navigate to the project directory:
bash
Copy code
cd stock-future-predictor
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Streamlit app:
bash
Copy code
streamlit run Stockprediction.py

Usage
Upon launching the app, enter a stock ticker (e.g., AAPL) in the text input field.
Use the slider to select the number of years for prediction.
Click the "Predict" button to generate the forecast and visualizations.
Explore the various charts, including moving averages and Prophet forecast plots.
Dependencies
Python 3.x
Streamlit
Numpy
Pandas
Matplotlib
Pandas-Datareader
YFinance
TensorFlow
Keras
Scikit-learn
Prophet
Plotly


Here's a README file template for your GitHub repository:

Stock Future Predictor

Overview
Stock Future Predictor is a web application built with Python, Streamlit, TensorFlow, and Facebook's Prophet model, designed to predict the future stock prices of various companies. The app allows users to input a stock ticker symbol, and it provides detailed predictions and visualizations based on historical data and advanced machine learning models.

Features
User Input: Input any stock ticker to fetch and analyze the historical stock data.
Data Visualization:
Closing Price vs. Time Chart
Moving Average Charts (100-day & 200-day)
Data Description: Summarizes the statistical properties of the data from 2010 to the current date.
Machine Learning:
Uses a pre-trained TensorFlow model to predict future stock prices.
Forecasting with Prophet to predict future trends for up to 4 years.
Interactive Charts: Displays the forecast using interactive Plotly charts.
Comparison: Visual comparison of predicted prices vs. original prices.
Installation
To run this project locally, follow these steps:

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/stock-future-predictor.git
Navigate to the project directory:
bash
Copy code
cd stock-future-predictor
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Streamlit app:
bash
Copy code
streamlit run app.py
Usage
Upon launching the app, enter a stock ticker (e.g., AAPL) in the text input field.
Use the slider to select the number of years for prediction.
Click the "Predict" button to generate the forecast and visualizations.
Explore the various charts, including moving averages and Prophet forecast plots.
Dependencies
Python 3.x
Streamlit
Numpy
Pandas
Matplotlib
Pandas-Datareader
YFinance
TensorFlow
Keras
Scikit-learn
Prophet
Plotly


File Structure
plaintext
Copy code
stock-future-predictor/
│
├── app.py               # Main application script
├── model.h5             # Pre-trained TensorFlow model
├── README.md            # Project README
└── requirements.txt     # Python dependencies


License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
Feel free to submit issues or pull requests if you would like to contribute to the project.

Acknowledgments
Streamlit for providing an easy way to build web applications.
Facebook Prophet for time series forecasting.
TensorFlow for powering the machine learning models.
Yahoo Finance API for providing stock market data.

