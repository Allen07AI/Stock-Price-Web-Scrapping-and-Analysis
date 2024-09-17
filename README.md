# Stock-Price-Web-Scrapping-and-Analysis

Problem Statement:
In this project, the goal was to forecast future stock prices of major banks using historical data. The dataset, scraped from the websites of five major banks, contained over 3,000 data points related to stock prices and financial metrics. The challenge was to analyze and visualize this extensive data and develop a robust forecasting model to predict future stock prices accurately.

Approach:
To address this problem, we began by utilizing Beautiful Soup to scrape stock data from the websites of five banks, aggregating a comprehensive dataset. This dataset was then visualized using Plotly, Matplotlib, and Seaborn to create various visualizations, including scatterplot matrices, moving averages, revenue and share price plots, daily return plots, and candlestick graphs. These visualizations provided valuable insights into the stock price trends and patterns.

Next, a 4-layer Long Short-Term Memory (LSTM) model was developed and trained to forecast future stock prices. The LSTM model, chosen for its capability to handle time series data, was evaluated based on its performance. The model achieved a Root Mean Square Error (RMSE) of 5.794 and a Mean Absolute Percentage Error (MAPE) of 0.065, demonstrating its effectiveness in predicting stock prices.

Conclusion:
This project successfully demonstrated the application of web scraping, data visualization, and deep learning techniques in stock price forecasting. By leveraging Beautiful Soup for data collection and advanced visualization libraries for analysis, combined with a sophisticated LSTM model, we were able to provide accurate stock price predictions and valuable insights into stock market trends.
