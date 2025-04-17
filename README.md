# Delhi Mean Temperature Prediction with LSTM 🌡️

A deep learning project that predicts **daily mean temperatures** in Delhi using a Long Short-Term Memory (LSTM) model. Forecast the weather like a pro! ☀️

## 🚀 Features
- Loads and visualizes historical climate data (temperature, humidity, wind speed, pressure)
- Preprocesses data with Min-Max scaling for LSTM training
- Trains an **LSTM** model to predict future mean temperatures
- Evaluates predictions with Mean Squared Error (MSE) and Mean Absolute Error (MAE)
- Visualizes actual vs. predicted temperatures 📊

## 📂 Project Structure
- `LSTM_TEMP.ipynb`: Jupyter notebook with the full pipeline (data loading, preprocessing, LSTM training, evaluation)
- `requirements.txt`: Dependency list for reproducibility
- `README.md`: You're reading it! 😎

## 🧠 Model
- **LSTM Model**: Recurrent neural network designed for time-series data, trained on Delhi's mean temperature
- Built with TensorFlow/Keras and optimized for sequence prediction

👉 **Dataset**: Uses `DailyDelhiClimateTrain.csv` (2013–2017) and `DailyDelhiClimateTest.csv` (2017). Download from [Kaggle](https://www.kaggle.com/sumanthvrao/daily-climate-time-series-data) and place in the project root, or update the `pd.read_csv()` paths in the notebook.

## 📦 Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
