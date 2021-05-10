# time_series_analysis
Using time series analysis, this project finds unusual patterns in hourly Google search traffic of MercadoLibre and analyze that data for seasonality. It then proceeds to analyze potential correlation between search trends and stock price patterns. Finally, it creates a time series model with Prophet and forecasts MercadoLibre revenue using time series models.
--
# Usage
This project is broken down into 5 major sections. It starts by finding unusual patterns in hourly Google search traffic (using Google trends). To do this, the data is read into a dataframe and graphed and analyzed with a few simple calculations. Then the project mines the search traffic data for seasonality using hvplot to look for trends. From there, the search traffic data is compared to stock price patterns with hvplot and the pandas .corr() function to see if any predictable relationship exists between number of searches and stock price. The project then goes on to create a time series model with Prophet. This allows the user to view future possibilities for search trends over several time periods. Finally, MercadoLibre's revenue is forecasted using Prophet to create a future projections dataframe and hvplot to plot the results.
--
# Technologies
This application is written in Python using Jupyter Notebook. It utilizes the pandas, fbprophet, hvplot, datetime, pathlib, and holoviews.
--
# Contributor
Billy Scolinos billyscolinos1@gmail.com
