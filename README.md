The purpose of this project is my attempt at using persisten homology to time-series data. The data
set I used is a time sereies represented by the renewable energy as a proportion to all energy sourses
in the country found at stat.gov.kz. The analysis will try to model the behaviour of the time series
by first doing a simple regression, asses it to get the benchmark error, then further complicate the
analysis by implementing time series model, in partilcular ARIMA, and use the MSE and Akaikes
test to test the model fit. Then we forecast the expected growth in the 5 years ahead. Lastly, the
methods in Topological Data analysis are used to analyse the dataset. These methods look at the
shape of the data, as a collection of simplicial complexes and asses the Betti number of the resultant
metric space, that changes based on the open cover of the set(radious of open balls). While these
methods are mostly applied in classification tasks, to, for instance, acquire additional clusters that
conventional clustering algorithms fail to identify, there are interesting applications of TDA in time
series analysis. In particular, one can transform the TS using time delay embedding operation, to
trasnform the data set into d-dimensional space, on which later one can apply TDA methods to
get the information about loops and voids of the data, that may indicate periodicity of the data,
noise(for TS acquired from arious sensors), strcutural changes etc. In this case I only look at a
simple TS data as a toy example, but similar methods can be applied to broader scale.
Step 1: Expected to growth using Regression and ARIMA model
