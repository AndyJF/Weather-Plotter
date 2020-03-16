# Weather-Plotter
Plots data points from weather history csv files. Also computes record temperatures, average temperatures, and average precipitation for each day out of each year. Currently tailored toward rendering results from the given `03824-weather-history.csv` file.  This file contains weather history for Durham, NH spanning back to 1895.

# Usage
The files `03824-climate.py` and `03824-plot.py` have already been created.  These are the files created by `climate.py` and `plot.py` respectively with the corresponding command line arguments.  To create these files for demonstration purposes, follow the directions below.

Using your terminal application, change directory to the directory containing the repository files.  Then run `python climate.py 03824-weather-history.csv 03824-climate.csv`.  This creates the climate file containing weather information for each day over many years.

To plot this weather information, run `python plot.py 03824-climate.csv 03824-plot.csv` in your terminal in the same directory as before.  Use your spreadsheet viewer of choice to see the created plot.
