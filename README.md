# ⚡ Household Power Consumption Forecasting with Sequential Models

This project focuses on forecasting household power consumption using a variety of sequential deep learning architectures. We compare the performance of several models on time series data:

- Vanilla RNN  
- Stacked RNN  
- Gated Recurrent Unit (GRU)  
- Vanilla LSTM  
- Stacked LSTM  
- Bidirectional LSTM (BiLSTM)  
- Refined LSTM (custom-enhanced LSTM variant)  

---

## 📊 Dataset

We use the **Household Power Consumption Dataset**, which contains minute-level measurements of electric power consumption in a single household over a four-year period (2006–2010).

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)
- **File Name**: `household_power_consumption.txt`  

---

## 🧠 Models Implemented

Each model was built and trained using **TensorFlow/Keras**. The models vary in depth and architectural style:

- **Vanilla RNN** – Basic recurrent unit  
- **Stacked RNN** – Multi-layer RNN for deeper learning  
- **GRU** – Gated Recurrent Unit for efficient training  
- **Vanilla LSTM** – Standard LSTM cell  
- **Stacked LSTM** – Multi-layer LSTM for capturing deeper dependencies  
- **BiLSTM** – Bidirectional LSTM for richer temporal context  
- **Refined LSTM** – LSTM with architectural enhancements (e.g., dropout, attention)

---

## 📈 Evaluation Metrics

Models are evaluated using the following metrics:

- **MAE** – Mean Absolute Error  
- **MSE** – Mean Squared Error  
- **RMSE** – Root Mean Squared Error  

---

## 🧪 How to Run the Project

### ✅ Prerequisites

Ensure the following are installed:

- Python 3.7+
- Jupyter Notebook
- Required libraries: TensorFlow, NumPy, Pandas, Matplotlib, Scikit-learn

Install them using:

```bash
pip install tensorflow pandas matplotlib scikit-learn
