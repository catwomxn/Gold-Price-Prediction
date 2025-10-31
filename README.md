# Gold-Price-Prediction
End-to-end data science project predicting gold prices using regression models (Python, Pandas, Scikit-learn, Matplotlib). Includes data preprocessing, visualization, and model evaluation.

# Gold Price Prediction using Machine Learning

## Overview
This self-initiated project focuses on predicting monthly gold prices using historical market data.  
It applies **machine learning regression models** to analyze market trends and forecast future prices.  
The project was developed as part of my independent learning in **data analytics and predictive modeling**.

## Objective
To build a **data-driven model** capable of predicting gold prices using historical financial data and technical indicators.

## Dataset
- Source: Yahoo Finance (`GC=F`)
- Time Period: June 2015 – June 2025
- Columns: Open, High, Low, Close, Volume

## Technologies Used
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn (Linear Regression, Random Forest)  
- Jupyter Notebook  

## Methodology
1. Data collection using `yfinance`  
2. Data cleaning and preprocessing  
3. Feature engineering (Open, High, Low, Close, Volume)  
4. Model training using **Linear Regression** and **Random Forest Regressor**  
5. Evaluation using **MAE**, **MSE**, and visual comparison  
6. Visualization of actual vs predicted gold prices

## Results
- The **Random Forest model** produced the lowest Mean Absolute Error (MAE).  
- Achieved high consistency with historical price patterns.  
- Visualized prediction accuracy using scatter and line plots.

## Visualizations
- Actual vs Predicted Gold Prices  
- Error Comparison across Models  

## Future Enhancements
- Incorporate macroeconomic factors (e.g., USD index, inflation rates)  
- Experiment with **LSTM (Deep Learning)** for time-series forecasting  

## Project Files
- **Gold_Price_Prediction.ipynb** — Full notebook with code and output  
- **Gold_Price_Prediction.pdf** — Read-only report for academic review  
- **requirements.txt** — Dependencies list  

>  This project is for educational and portfolio demonstration only. Redistribution or reuse without permission is prohibited.

## Author
**Andrea** — BCA Computer Science graduate passionate about data-driven problem-solving and intelligent systems.

## License
This project is covered under the **Portfolio Use License** (see LICENSE file for details).
