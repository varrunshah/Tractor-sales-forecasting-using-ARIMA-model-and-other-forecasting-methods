# Tractor Sales forecasting using ARIMA model and other forecasting methods
Power horse is a tractor and farm equipment company which was established a few years after the end of WW2. The unique thing about the first model was that they had no seating or wheels attached to the original unit.The idea behind this was that the farmers who wanted tractors but could not afford it. The company have made significant growth in their revenue. 
As there was a constant growth in the revenue generation, the comapany still faced the struggle to balance its inventory and tractor sales.
# Data
The data set was acquired from the very known [kaggle](https://kaggle.com) platform. The data set consists of 144 enteries divided within a span of 12 years from 2003-15. The dataset tells us how many tractors were sold during these period. 
# System Requirements
- R 3.6
- Rstudio 3.5.2
# Libraries
The libraris used in this project are as follows--
- ggplot2
- tseries
- .libPath() - all the required packages and functions are defined and installed in this folder.

Now, let us take a look at the execution of the project. We decided to forecast the sales of the tractors for the next three years.

# Execution
The execution of the project is done in Rstudio. 
Using the DOC file made, it contains the snippet of the R code which is used in performing the forecasting of the tractor sales. 
Run the snippet code to get the desired output.

# Insights

The analysis made in this project can be seen with the help of different plots made. Forecasting is a very tricky business, you can predict something for the future but are not 100% sure that it will come out true. Respecting the timeline and keeping in mind all the various events occurring there is a possibility of the slightest error.

The different plots made in the project for a thoughtful insight--

Density plot-
![Result1](diagrams/density.png?raw=true)

Scatter plot-
![Result2](diagrams/scatter.png?raw=true)

Increasing trend-
![Result3](diagrams/trend.png?raw=true)

ARIMA model- ACF 
![Result4](diagrams/ACF.png?raw=true)

The final forecasted graph-
![Result5](diagrams/forecasted.png?raw=true)
