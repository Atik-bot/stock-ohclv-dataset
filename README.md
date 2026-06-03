# Stock Price Prediction using Hybrid Deep Learning Models

This repository contains the complete thesis implementation and dataset for stock price prediction using Deep Learning and Graph Neural Networks (GNNs). The project explores multiple neural network architectures for financial forecasting using historical stock market data.

## Project Overview

The goal of this research is to improve stock price prediction accuracy by combining:

* Temporal dependency learning using RNN and LSTM
* Inter-stock relationship learning using Graph Convolutional Networks (GCN)

The proposed hybrid models capture both sequential market behavior and relationships between stocks.

---

## Dataset

The dataset contains historical OHLCV stock market data for:

* Apple (AAPL)
* Microsoft (MSFT)
* NVIDIA (NVDA)

### Features Included

* Open
* High
* Low
* Close
* Adjusted Close
* Volume

---

## Implemented Models

The repository includes implementations of the following models:

* RNN_ONLY
* LSTM_ONLY
* GCN_ONLY
* GCN_RNN
* GCN_LSTM
* LSTM_RNN

---

## Workflow

1. Data Loading and Cleaning
2. Missing Value Handling
3. Data Normalization
4. Sequence Generation using Sliding Window
5. Correlation-Based Graph Construction
6. Model Training
7. Performance Evaluation
8. Visualization of Results

---

## Technologies Used

### Programming Language

* Python

### Libraries and Frameworks

* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* PyTorch
* TensorFlow
* PyTorch Geometric

---

## Evaluation Metrics

The models are evaluated using:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* R² Score

---

## Repository Structure

```text
├── 3_Companies_OHLCV.csv
├── finalThesisCode_with comments.ipynb
├── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Stock_Price_Prediction_using_GCN_RNN.git
cd Stock_Price_Prediction_using_GCN_RNN
```

Install required dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras torch torch_geometric torch_sparse torch_scatter torch_cluster networkx tqdm
```

---

## Running the Project

Open the Jupyter Notebook:

```text
finalThesisCode_with comments.ipynb
```

Run all cells sequentially to reproduce the results.

---

## Research Contribution

This research demonstrates that combining Graph Neural Networks with sequential deep learning models improves stock price prediction performance by incorporating both:

* Temporal dependencies
* Inter-stock relationships

---

## Future Improvements

Possible future extensions include:

* Sentiment analysis integration
* Transformer-based architectures
* Real-time forecasting
* Multi-market prediction
* Reinforcement learning approaches

---

## Academic Purpose

This repository was developed as part of an academic thesis project focused on financial forecasting using deep learning techniques.
