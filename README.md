An ipython notebook containing functions which make a summary plot of the electric field noise data (heating rates)
found in various publications. 

The functions read the data from a csv file with specific format (see included csv). The data is organized in a pandas
dataframe. A dictionary is used to control which kind of symbol will be used for what publication. There are various options 
for how to label the function, e.g. by reference number, or by a shorthand notation of the reference. If you want to change 
which datapoints are included in the plot, toggle the "Plot" flag in the csv, or in the pandas dataframe.

Prerequisites are python pandas and python matplotlib
