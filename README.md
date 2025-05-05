This project compares the performance of a Long Short-Term Memory (LSTM) model and a Transformer-based Temporal Fusion Transformer (TFT) on time-series forecasting using the ETTh1 dataset.

**Project Overview**

Goal: Forecast oil temperature inside electrical transformers using past power load data.
**Models Used:**

LSTM (Long Short-Term Memory), Transformer (Temporal Fusion Transformer)
**Dataset** 

ETTh1 — 2 years of hourly electrical load and oil temperature data from China.
**Key Concepts**

-Time-Series Forecasting
-LSTM and Transformer Architectures
-Regression and Gradient Descent
-Data Preprocessing with Pandas
-Normalization using MinMaxScaler
-Evaluation with MSE loss

**Tools & Libraries**

Python, PyTorch, Pandas, Scikit-learn, Matplotlib
**Results**

The Transformer model outperformed the LSTM in forecasting accuracy. However, it required more processing time (Transformer: ~45s, LSTM: ~4s). Evaluation was done using Mean Squared Error (MSE) on both training and testing sets.
**Visualizations**

The repository includes plots comparing training and testing loss over 50 epochs for both models.
**Future Work**

Model optimization, More diverse datasets, Real-time forecasting use cases

