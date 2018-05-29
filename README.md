# Electric Load Forecasting

Project on short term electric load forecasting. Data was taken from [State Load Despatch Center, Delhi](www.delhisldc.org/) website and multiple time series algorithms were implemented during the course of the project.

### Models implemented:

`models` folder contains all the algorithms/models implemented during the course of the project:

* Simple Moving Average [SMA.ipynb](models/SMA.ipynb)
* Weighted Moving Average [WMA.ipynb](models/WMA.ipynb)

scripts:

* `load_scrap.py` scraps day wise load data of Delhi from [SLDC](https://www.delhisldc.org/Loaddata.aspx?mode=17/01/2018) site and stores it in csv format.
* `wheather_scrap.py` scraps day wise whether data of Delhi from [wunderground](https://www.wunderground.com/history/airport/VIDP/2017/8/1/DailyHistory.html) site and stores it in csv format.


