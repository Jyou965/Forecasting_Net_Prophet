# Forecasting_Net_Prophet

This application uses MercadoLibre, the most popular e-commerce site in Latin America as an example to analyses the Google Search trends and patterns and it's relationship with the Company's stock performance.  It also forecasts future Google Search trends and company's revenues using unsupervised machine learning.

---

## Libraries and Dependancies

This application leverages Google Colab with the following packages:

* [fbprophet](https://facebook.github.io/prophet/) - a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data.

* [pystan](https://pystan.readthedocs.io/en/latest/) - a Python interface to Stan, a package for Bayesian inference.  It is a dependancy of fbprophet.

* [hvplot](https://hvplot.holoviz.org/user_guide/Introduction.html) - provides a high-level plotting API built on HoloViews and Bokeh that provides a general and consistent API for plotting data in all the abovementioned formats.

* [holoviews](https://holoviews.org/user_guide/index.html) - an open-source Python 2 and 3 library for data analysis and visualization. It is a dependancy of hovplot.

* [datetime](https://docs.python.org/3/library/datetime.html#module-datetime) - supports date and time arithmetic with the focus of the implementation being on efficient attribute extraction for output formatting and manipulation.

* [matplotlib](https://https://matplotlib.org/) - a comprehensive library for creating static, animated, and interactive visualizations in Python.

* [pandas](https://pandas.pydata.org/docs/) - an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

---

## Usage

This application uses unsupervised machine learning in performing the following steps:

- Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.

- An evaluation of how the company’s stock price correlates to its Google Search traffic.

- A Prophet forecast model that can predict hourly user search traffic.

- A plot of a forecast for the company’s future revenue.

With the application, managers can understand the pattern of Google Search traffic of their offerings, the correlation of Google Search traffic and company stock performance and perform forecasting of Google Search traffic as well of sales revenue.  With such analysis, managers can develop insights for business strategies.

---

## Contributors

Jackie You with the support of FinTech Boot Camp Staff

---

## License

Berkeley
