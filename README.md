# Household Power Consumption Forecasting Sequential Models

This project focuses on forecasting household power consumption using a variety of Sequential modeled architectures. We compare the performance of several deep learning models on time series data, including:

- Vanilla RNN
- Stacked RNN
- Gated Recurrent Unit (GRU)
- Vanilla LSTM
- Stacked LSTM
- Bidirectional LSTM (BiLSTM)
- Refined LSTM (custom-enhanced LSTM variant)

---

## 📊 Dataset

We used the **Household Power Consumption Dataset**, which contains measurements of electric power consumption in a single household over four years (2006-2010).  
**Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)

---

## 🧠 Models Implemented

Each model was built and trained using TensorFlow/Keras. The architecture details vary in depth and configuration:

- **Vanilla RNN** – basic recurrent unit.
- **Stacked RNN** – multiple RNN layers.
- **GRU** – efficient gated recurrent unit.
- **Vanilla LSTM** – traditional LSTM cell.
- **Stacked LSTM** – deeper LSTM networks.
- **BiLSTM** – bidirectional processing for richer context.
- **Refined LSTM** – LSTM variant with architectural tweaks for better performance.

---

## 📈 Evaluation Metrics

We used the following metrics to evaluate model performance:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Squared Error (MSE)


