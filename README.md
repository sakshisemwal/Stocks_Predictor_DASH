Forecasting stock prices for the near future and visualizing it graphically using Dash 
framework. Dash is an open-source python framework used for building data visualization 
apps/interfaces. It is widely used for building ML based web applications and is built on top of 
plotly.js, React and Flask. 
It ties down all the modern UI elements to the python code.

Language and concepts used: 
• Python
• ML
• Dash
• sklearn

Design and Algorithm:
This project is designed using the concept of machine learning algorithms (Super Vector 
Machine Algo) in Python language. Some of the operations and functions in this program are
designed to do are:
• Letting the user to either visualize the current stock price or the predicted stock price of the 
given number of days by the user.
• In the predicted/Forecasted stock price a graph gets generated between the date and 
closing/opening stock price.
• If the user chooses to visualize the forecasted stock price then he/she must select the number 
of days he/she wishes to see the forecasted stock price for.
• All this is achieved by importing the real time yfinance library on which our model works on, 
it is an excellent source of information for research and prototyping the stock data.
• The values are then plotted on the graph along with the dataset and the algorithm predicts
the closing price.
