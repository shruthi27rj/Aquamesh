# Aquamesh
Intelligent water distribution monitoring system designed to detect anomalies and optimize urban water pipeline networks.

## How It Works
The system models a digital twin of an urban water pipeline network using a graph-based approach, where nodes represent junction points and edges represent pipelines. A simulation engine generates realistic pressure and pH variations along with random leak scenarios to mimic real-world water distribution behavior.
An LSTM-based anomaly detection model analyzes the time-series data to identify abnormal pressure changes or leak events. Once an anomaly is detected, the system performs pipeline rerouting optimization by identifying alternative paths in the network to minimize water loss and maintain supply.

## Technologies Used
- Python
- Streamlit
- NumPy
- Pandas
- NetworkX
- Matplotlib
- Scikit-learn
