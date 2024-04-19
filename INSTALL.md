# Installation Guide

This guide will walk you through the process of setting up the DS5500 Stock Price Prediction project on your system using Google Colab.

## Prerequisites

- A Google account to access Google Colab.
- Internet connection.

## Google Colab Setup

Google Colab provides a cloud-based Python programming environment with most libraries pre-installed. To use Google Colab:

1. Go to [Google Colab](https://colab.research.google.com/).
2. Sign in with your Google account.
3. Click on `File > Open notebook`.
4. Select the `GitHub` tab and enter the repository URL: `https://github.com/QinglinGou/DS5500_Stock_price_prediction`.
5. Choose the notebook you want to open from the list.

## Library Installation

While Google Colab comes with many libraries pre-installed, you may need to install or update certain libraries to match the versions used in this project. You can do so by running the following commands at the start of your Colab notebook:

```python
!pip install pandas==2.0.3
!pip install numpy==1.25.2
!pip install matplotlib==3.7.1
!pip install scikit-learn==1.2.2
!pip install tensorflow==2.15.0
!pip install seaborn==0.13.1
!pip install stockstats==0.6.2
!pip install scikeras==0.13.0
!pip install optuna==3.6.1

