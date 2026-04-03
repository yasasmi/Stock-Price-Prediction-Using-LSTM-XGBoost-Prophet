📌 Key Highlights

✅ Hybrid Modeling Approach (LSTM + XGBoost + Prophet)
Used LSTM networks to capture long-term temporal dependencies in stock price sequences
Applied XGBoost for structured feature-based regression
Implemented Prophet to model trend and seasonality components

✅ Comprehensive Time-Series Dataset (1990–2023)
Collected historical stock price data using Yahoo Finance / Alpha Vantage APIs
Worked with features such as Open, High, Low, Close, and Volume

✅ Feature Engineering & Data Preprocessing
Generated time-based features and lag variables
Calculated technical indicators (Moving Averages, RSI, MACD, volatility)
Normalised and scaled data for deep learning models
Created sequences and applied padding for LSTM input

✅ Model Training & Optimization
Tuned hyperparameters using Grid Search and Cross-Validation
Applied dropout regularisation to improve generalisation
Used early stopping to prevent overfitting

✅ Performance Evaluation
Evaluated models using RMSE and MAE
Compared prediction performance across LSTM, XGBoost, and Prophet
Analysed prediction vs actual trends

✅ Data Visualization & Insights
Visualised stock trends and model predictions
Used Matplotlib, Seaborn, and Plotly for interactive charts

✅ Deployment
Built a web application using Flask / Streamlit
Enabled real-time stock price prediction and visualisation
🔗 Technologies Used

Python, TensorFlow/Keras, LSTM, XGBoost, Prophet, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Yahoo Finance AP
