# timeseries
The first project requires us to analyze a time series.
I download the temperature time series from Jan in 1948 to July in 2019 at https://www.psl.noaa.gov/data/climateindices/. 
The key innovation in this project is that, instead of using "arima.fit", which is a method from pre-written package, I try to code my own function.
I use three methods, which are bartlett equation, residual variance plot and criterion function to determine the order for time series model.
Rmd code shown in ts_hw1.rmd and report shown in ts_hw1.html.

The second project requires us to simulate three tables in the page 336-338 for book 《高等时间序列计量经济学》, which are critical value table for Dickey-Fuller t-test, PP t-test and ADF f-test.
Based on functional analysis method, we obtain the limiting distribution for the three test statistics discussed, which are all functions of wiener process.
Therefore, I use different functions of wiener process to simulate the three test statistics. This is also the main innovation for the project.
Rmd code shown in ts_hw2.rmd and report shown in ts_hw2.html.
