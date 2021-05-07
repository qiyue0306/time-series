# timeseries
The first homework for applied time series class requires us to analyze a time series.
I download the temperature time series from Jan in 1948 to July in 2019 at https://www.psl.noaa.gov/data/climateindices/. 
The key innovation in this project is that, instead of using "arima.fit", which is a method from pre-written package, I try to code my own function.
I use three methods, which are bartlett equation, residual variance plot and criterion function to determine the order for time series model.
Rmd code shown in ts_hw1.rmd and report shown in ts_hw1.pdf.
