# electricity-consumptiuon-forecast
Predict Electricity Consumption of household using Neural Networks.

## Dataset : https://www.kaggle.com/jeanmidev/smart-meters-in-london

## Inroduction

With the development of smart meters, electric utilities can obtain precise and detailed
data of single consumers. This has lead to the generation of various big data sets with
previously unattainable information leading to efficient smart grid performance in areas
such as load forecasting. Accurate load forecasting promotes effective functioning of smart
grids and power system ultimately leading to proper utilization of resources and avoidance
of power outages. Meter level predictions, also known as domestic level forecasting, for
short period of time finds applications in load scheduling, management of demand response
and storage systems. This report describes the use of an approach combined using Seasonal
Autoregressive Integrated Moving Average Exogenous (SARIMAX) and Long Short Term
Memory networks (LSTM) with regression models to predict daily energy consumption of
customers located in London area.

## Objectives

* In Smart Meter Data Analytics, we will study databases and try to discover patterns and
on that basis will create a data models.
* Our study includes, Combining all blocks into a single data frame- keeping on relevant
columns.
*  Use day-level energy consumption data per household to normalize data for inconsistent
household count.
* Explore relationships between weather conditions and energy consumptions and create
clusters for the weather data.
* With the help of data models we will try to find out the suitable algorithm for our dataset
for data processing.

## Purpose

Since the inception of electricity deregulation and market-driven pricing throughout the
world, utilities have been looking for a means to match consumption with generation. Nonsmart electrical and gas meters only measure total consumption, providing no information
of when the energy was consumed. Smart meters provide a way of measuring this sitespecific information, allowing utility companies to charge different prices for consumption
according to the time of day and the season.

## Scope

We will use data from the London data store, that contains the energy consumption readings for a sample of 5,567 London Households that took part in the UK Power Networks
led Low Carbon London project between November 2011 and February 2014.
We also collected weather data for London area from the darksky to explore relationships
between weather conditions and energy consumptions and create clusters for the weather
data- using which we can add weather identifiers to day-level data.
We will try to discover patterns by studying these datasets and on that basis will create
a data models to find out the suitable algorithm for data processing.
We will use Python and Pandas. Python provides constructs that enable clear programming on both small and large scales. And pandas is a software library written for the
Python programming language for data analysis.
On that basis we will create a system that would help the consumers recognize their electric
usage patterns and be able to optimize their usage.

## Applicability

This system will help the customers to analyse their electricity usage patterns which will help them to optimize their usage. It will also be able to predict the
electricity usage for the future.


## Clone Repository
Clone this Repository using,

	git clone https://github.com/mayursrt/customer-segmentation-using-k-means.git


## Usage
Install `jupyter` from [here](http://jupyter.readthedocs.io/en/latest/install.html) or use

	pip install jupyter

After installing jupyter notebook Just run `jupyter notebook` in terminal and you can visit the notebook in your web browser.



## Dependencies

* [Pandas](https://pandas.pydata.org/docs/)
* [NumPy](https://numpy.org/devdocs/user/index.html)
* [Matplotlib](https://matplotlib.org/3.3.3/contents.html)
* [Seaborn](https://seaborn.pydata.org/)
* [Sklearn](https://scikit-learn.org/stable/)

Install missing dependencies using,

	pip install pandas numpy matplotlib seaborn sklearn


