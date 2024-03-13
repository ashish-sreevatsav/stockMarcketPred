# Stock Market Prediction using LSTM -by Pochampally

This project aims to predict stock market prices using Long Short-Term Memory (LSTM) neural networks. LSTM is a type of recurrent neural network (RNN) architecture that is well-suited for sequence prediction tasks like time series forecasting.

## Overview

The project utilizes historical stock market data to train an LSTM model to predict future stock prices. It includes the following components:

- Data collection from Yahoo Finance API.
- Data preprocessing including scaling and sequence creation.
- Building and training an LSTM model.
- Evaluating the model's performance using metrics like Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
- Visualizing the predicted stock prices against the actual prices.

## Requirements

- Python 3.x
- Libraries: numpy, pandas, matplotlib, scikit-learn, keras, yfinance

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ashish-sreevatsav/stockMarketPred.git
   ```

2. Navigate to the project directory:
   ```bash
   cd stockMarketPred
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook file `stockPredLSTM.ipynb` in your preferred environment (e.g., Jupyter Notebook, JupyterLab, Visual Studio Code with Python extension).

2. Execute each cell in the notebook sequentially to load the data, preprocess it, build and train the LSTM model, and evaluate its performance.

3. Customize the notebook as needed for your specific stock market prediction task.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project is for educational purposes and is inspired by various online tutorials and resources on LSTM-based stock market prediction.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any bugs, feature requests, or improvements.
