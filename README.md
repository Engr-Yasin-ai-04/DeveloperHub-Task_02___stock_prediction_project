# 📈 Stock Price Prediction - Future Price Forecasting Project

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.2-green.svg)](https://www.djangoproject.com/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3-orange.svg)](https://scikit-learn.org/)
[![yfinance](https://img.shields.io/badge/yfinance-0.2-red.svg)](https://pypi.org/project/yfinance/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A powerful Machine Learning web application that predicts next-day stock closing prices using historical market data. Built with Django, yfinance, and advanced ML algorithms.

---

## 📸 Project Screenshots

### 🗂️ Project Structure
Complete project structure for better understanding.

![Project Structure](Program_Structure_Image.JPG)

### 🖥️ Main GUI Interface
The main interface showing stock selection and prediction configuration.

![GUI Interface](1_Output_GUI.JPG)

### ⚙️ Processing & Prediction
Real-time data processing and prediction generation.

![Processing & Prediction](2_Output_Processing_Prediction.JPG)

### 📊 Program with Chart - Visualization
Interactive chart showing actual vs predicted values.

![Program with Chart](3_Output_Program_with_Chart.JPG)

### 📈 Extended Analysis - 100 Training Days
Comprehensive prediction results with 100 days of training data.

![100 Training Days Analysis](4_Output_Program_with_Chart_for_100_Training_days.JPG)

---

## 📊 Project Overview

This project uses historical stock market data from Yahoo Finance to predict next-day closing prices using Machine Learning algorithms. The application provides:

- **Real-time Stock Data**: Fetches live data from Yahoo Finance API
- **Multiple ML Models**: Linear Regression and Random Forest algorithms
- **Feature Engineering**: Moving averages, price changes, volume indicators
- **Interactive Web Interface**: User-friendly Django-based GUI
- **Performance Metrics**: RMSE, R² Score, and visualization plots

---

## 🎯 Features

### ✅ Data Collection
- **yfinance Integration**: Real-time stock data from Yahoo Finance
- **Multiple Stocks**: Support for AAPL, TSLA, MSFT, GOOGL, AMZN, META, NFLX
- **Custom Date Ranges**: Adjustable training periods (30-365 days)

### ✅ Feature Engineering
- **Technical Indicators**: Moving averages (MA5, MA10, MA20)
- **Price Metrics**: Open-Close difference, High-Low difference
- **Volume Analysis**: Price change, volume change percentages

### ✅ Machine Learning Models
- **Linear Regression**: Simple and interpretable
- **Random Forest**: Advanced ensemble method
- **Model Evaluation**: RMSE, R² Score metrics

### ✅ Visualizations
- **Actual vs Predicted Plot**: Compare model performance
- **Confidence Intervals**: Prediction error visualization
- **Feature Importance**: For Random Forest model

### ✅ Interactive GUI
- **Modern Glassmorphism Design**: Professional look and feel
- **Real-time Predictions**: Instant results
- **Responsive Layout**: Works on all devices

---

## 🚀 Installation & Setup

### Prerequisites
- Python 3.9 or higher
- pip package manager
- Internet connection (for Yahoo Finance API)

### Step-by-Step Installation

1. **Clone the repository**
```bash
git clone https://github.com/Engr-Yasin-ai-04/stock-price-prediction.git
cd stock-price-prediction
