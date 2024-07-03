# Goldman Sachs Sales Forecast

This project aims to forecast the closing prices of Goldman Sachs stock using historical stock price data. The project involves data exploration, preprocessing, feature engineering, and building a Long Short-Term Memory (LSTM) neural network for time series prediction.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project demonstrates the use of LSTM, a type of recurrent neural network, to predict the closing prices of Goldman Sachs stock. The data used includes daily stock prices with columns such as Open, High, Low, Close, Adjusted Close, and Volume.

## Dataset

The dataset used in this project is historical stock price data for Goldman Sachs, which includes the following columns:
- Date
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

## Installation

To run this project, you need to have Python and the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow

You can install these dependencies using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
```
## Usage
1. Clone the repository:
```bash
git clone https://github.com/your-username/GS_Sales_Forecast.git
cd GS_Sales_Forecast
```
2. Open the project in your preferred IDE or Jupyter Notebook.
3. Load the dataset and run the cells sequentially to preprocess the data, train the model, and make predictions.

# Results
The model's performance is evaluated using the Root Mean Square Error (RMSE). The RMSE for the training and testing datasets are as follows:

- Train RMSE: 139.52
- Test RMSE: 252.78
The results show the predicted closing prices against the actual closing prices, indicating how well the model performs in predicting future stock prices.

# Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
