# Weather Profiteering Application

This is an application that analyzes daily weather patterns during 2019 in the transit hubs of Atlanta, GA, Chicago, IL, Seattle, WA and Dallas, TX to determine any correlations between significant weather events and stock prices of Alaska Airlines, United Airlines, Delta Air Lines, American Air Lines written in Python. The application pairs each airline to a city and analyzes results of how the city's weather may have affected the airline's stock prices. The pairing is a s follows; Alaska Airline-Seattle, WA
American Airline-Dallas, Tx
United Airline-Chicago,IL
Delta Airline-Atlanta,GA
Based upon the results of our analysis there are no material correlations between weather events and stock prices.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [Pandas] (https://github.com/pandas-dev/pandas) - For data analysis

* [HvPlot] (https://github.com/holoviz/hvplot) - For visualization (charts and graphs) of the data

* [Seaborn] (https://seaborn.pydata.org/) - For visualization (charts and graphs) of the data

* [Alpaca] (https://github.com/alpacahq/alpaca-trade-api-python) - Source for data stock

* [VisualCrossing] (https://github.com/visualcrossing/WeatherApi) - Source for weather data

---

## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install pandas
  pip install numpy
  pip install requests
  pip install seaborn
  pip install hvplot
  pip3 install alpaca-trade-api
```

---

## Usage 

To use the Weather Profiteering application simply run the "main.ipynb" file in the terminal. The images below are some screenshots proving our results.

<img src="https://github.com/Schaakattack/weather-profiteering/blob/main/Images/Image1.PNG" width=500 height=300>

<img src="https://github.com/Schaakattack/weather-profiteering/blob/main/Images/Image2.PNG" width=500 height=300>

<img src="https://github.com/Schaakattack/weather-profiteering/blob/main/Images/Image3.PNG" width=500 height=300>

<img src="https://github.com/Schaakattack/weather-profiteering/blob/main/Images/Image4.PNG" width=500 height=300>

<img src="https://github.com/Schaakattack/weather-profiteering/blob/main/Images/Image7.PNG" width=500 height=300>

<img src="https://github.com/Schaakattack/weather-profiteering/blob/main/Images/Image8.PNG" width=500 height=300>
---

## Contributors

Brought to you by Virginia Murage, Jon Mitchell, Chandler Schaak and Sam Lawhead.

---

## License

Copyright 2022

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

