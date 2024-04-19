# DS5500 Stock Price Prediction

## Introduction
This project aims to enhance the precision of short-term stock price predictions through a comparative study of machine learning models(Linear Regression, Lasso Regression, Random Forest and LSTM) and feature engineering techniques(Without FE, Boruta, PCA and T-sne), with a focus on [Apple Inc.'s stock (AAPL)](https://finance.yahoo.com/quote/AAPL/history). We seek to determine the most effective computational strategies for financial analytics.

## Motivation
Stock price prediction is a complex challenge that requires robust analytical models to guide investment strategies. By identifying the optimal combination of machine learning techniques and feature engineering, we can provide more accurate forecasts, benefiting investment firms and individual investors alike.


## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.8 or above
- pip (Python package installer)
- Jupyter notebooks

## Installation
To use this project:
1. Clone the repository:

```
git clone https://github.com/QinglinGou/DS5500_Stock_price_prediction.
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```

## Running the Project

After installing the project, you can run the various components as follows:

### Technical Indicator
To calculate the Technical Indicators,run the `technical_indicator.ipynb`
### Feature Engineering
To perform feature engineering, run the `Feature_Engineering.ipynb` 
### LR & Lasso & RF Training
For Training traditional mechine learning models, execute the `linear_Regression&_Lasso&_RF.ipynb`
### LSTM Fine-Tuning
To fine-tune the LSTM model, execute the `LSTM_fine_tuning_gridsearch.ipynb`

### Test Trading strategy on Tesla stock price
In the folder `Tesla`, you can run 


## Usage Instructions

To utilize this project, you'll primarily interact with Jupyter notebooks that contain the machine learning models and analysis code.

### Running the Notebooks
1. Open the terminal and navigate to the project directory.
2. Start the Jupyter Notebook environment:
3. In the browser window that opens, navigate to the notebook you want to run.
4. Open the notebook by clicking on its name, such as `Feature_Engineering.ipynb`.
5. Run the notebook cells in sequence by clicking `Run` or pressing `Shift + Enter`.

### Example
To execute feature engineering, you would open and run the cells within the `Feature_Engineering.ipynb` notebook. The process would be similar for other notebooks like model training or data visualization.

## Libraries and Tools Used

- **Environment**: Google Colab
- **GPU**: Nvidia T4 GPU
- **IDE**: Visual Studio Code
- **Version Control**: Git via GitHub

### Python Libraries:

- **Python**: 3.10.12
- **TensorFlow**: 2.15.0
- **Scikit-learn**: 1.2.2
- **Pandas**: 2.0.3
- **NumPy**: 1.25.2
- **Matplotlib**: 3.7.1


