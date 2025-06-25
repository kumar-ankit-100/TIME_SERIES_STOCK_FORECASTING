📈 TIME SERIES STOCK FORECASTING
An interactive and fully-automated stock market forecasting dashboard built with Streamlit, supporting both classical time series models (ARIMA, SARIMA, Prophet) and deep learning (LSTM). The app processes multiple stock datasets, performs exploratory data analysis (EDA), outlier detection, builds models, tunes hyperparameters, and compares model performance using real-time visualizations.

🔗 Live App: Click to Try Now
💻 Repository: TIME_SERIES_STOCK_FORECASTING

🚀 Features:

✅ Upload or auto-load multiple stock datasets

📊 EDA with trend visualization, rolling averages & outlier detection

🧹 Preprocessing: missing values, scaling, formatting

📈 Forecasting with 4 models: ARIMA, SARIMA, Prophet, LSTM

🎛️ Full hyperparameter tuning (manual or automated)

📉 Model performance comparison using RMSE, MAE, MAPE

💾 Save trained models for reuse

🧠 LSTM deep learning with time-sequenced input

📁 Folder-based dataset automation

📊 Real-time interactive plots with Plotly


🧭 Dashboard Overview:

🔍 EDA & Outlier Detection

🤖 LSTM Forecast Example

📊 Model Comparison Metrics

📁 Project Folder Structure
graphql
Copy
Edit

TIME_SERIES_STOCK_FORECASTING/
│
├── app.py                     # Main Streamlit application
|
├── data/                      # Folder containing stock CSVs
|
├── models/                    # Trained models saved here
|
├── screenshots/               # Screenshots for documentation
|
├── traditional_models.py      # ARIMA, SARIMA, Prophet functions
|
├── lstm_model.py              # Deep Learning LSTM logic
|
├── eda_outliers.py            # EDA and outlier detection functions|
|
├── comparison.py              # Model comparison and evaluation
|
├── utils.py                   # Utility functions (scaling, metrics)
|
├── requirements.txt           # Required Python packages
|
└── README.md                  # This documentation

🧠 Models Explained

Model	Type	Framework	Description
ARIMA	Traditional	statsmodels	Works on lag, trend, and moving average
SARIMA	Traditional	statsmodels	Extends ARIMA with seasonal factors
Prophet	Additive Model	fbprophet	Handles seasonality, holidays, trends
LSTM	Deep Learning	TensorFlow/Keras	Captures long-term dependencies in time series

📊 Evaluation Metrics Used
Metric	Description
RMSE	Penalizes large errors (Root Mean Squared Error)
MAE	Mean of absolute errors
MAPE	Percentage-based error measure

Each model is trained/tested on the same dataset split and compared using these metrics.

📦 Installation & Running Locally
1. Clone the Repo
bash
Copy
Edit
git clone https://github.com/kumar-ankit-100/TIME_SERIES_STOCK_FORECASTING.git
cd TIME_SERIES_STOCK_FORECASTING
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Add CSV Data
   Dataset:
   https://www.kaggle.com/datasets/szrlee/stock-time-series-20050101-to-20171231?utm_source=chatgpt.com

4. Run the Streamlit App
bash
Copy
Edit
streamlit run app.py
📬 Usage Notes
✅ Handles multiple stocks: loops through all CSVs in /data folder.

📌 Automatically detects and preprocesses time series structure.

🔁 Compares forecasts from ARIMA, SARIMA, Prophet, and LSTM.

📉 Forecast horizon and model parameters are adjustable in-app.

🤝 Contributing
Want to improve or extend the project? Contributions are welcome!

SCREENSHOTS:

<img width="748" alt="Screenshot 2025-06-25 175124" src="https://github.com/user-attachments/assets/6667e99c-bbd8-4b39-86c2-546fc6722579" />

<img width="674" alt="Screenshot 2025-06-25 175318" src="https://github.com/user-attachments/assets/07ae4f5b-f732-4503-b66d-aabf28e64296" />


How to Contribute:
Fork the repository

Create your feature branch: git checkout -b my-feature

Commit your changes: git commit -am 'Add new feature'

Push to the branch: git push origin my-feature

Create a new Pull Request

👨‍💻 Author
Kumar Ankit
🔗 GitHub Profile


📄 License
This project is licensed under the MIT License.
See the LICENSE file for details.


















