ProgFinalAssess2
-----------------------------------------------------------------------
The file 'output.csv' is a file containing data from volcanic eruptions since 46AD. This file contains columns refering to the Day, Month and Year an eruption occured. It also contains Earthquake and Tsunami data. Geographically it contains the Name, Location, Country, Latitude, Longitude and Elevation of the volcano itself. It also contains the Volcanos type and its eruptions VEI (Volcanic explosivity index). It also contain columns regading Deaths, Missing, Injuries, Damage and Homes lost due to the eruption. This data was downloaded from - 
-------------------------------------------------------------------------
List of Python Packages used in code -
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import plotly.express as px
from scipy.stats import spearmanr
--------------------------------------------------------------------------
Brief Description of Programme
Cell 1 - Imports necessary packages for manipulation, calculations and visualisations.
Cell 2 - Reads the file and saves it in a new dataframe, drop the columns cotaining no real data.A new dataframe is then created from the old dataframe using the columns deemed revelant for the analysis. Summary statistics are then calculated for the new dataframe.
Cell 3 - Modes are calculated for the categorical columns in the dataframe
Cell 4 - Geo scatter plot is created showing distributions of volcanos and the year of eruption
Cell 5 - Histograms are created for each column to check normality of data
Cell 6 - Elevation column values are changed to a float so key for next graph can be a colour scale and geo scatter is created. Geo scatter shows distribution of volcanoes and their elevation
Cell 7 - Scatter graph created showing Elevation against deaths caused by eruption
Cell 8 - Spearmans Rank Calculated for Elevation and Deaths
Cell 9 - Scatter graph created showing Elevation against injuries caused by eruption
Cell 10 - Spearmans Rank Calculated for Elevation and injuries
Cell 11 - Scatter graph created showing Elevation against damage caused by eruption
Cell 12 - Spearmans Rank Calculated for Elevation and damage
Cell 13  - Scatter graph created showing Elevation against houses destroyed by eruption
Cell 14 - Spearmans Rank Calculated for Elevation and houses destroyed
Cell 15 - VEI's column values are changed to a float so key for next graph can be a colour scale and geo scatter is created. Geo scatter shows distribution of volcanoes and their VEI
Cell 16 - Scatter graph created showing VEI against deaths caused by eruption
Cell 17 - Spearmans Rank Calculated for VEI and Deaths
Cell 18 - Scatter graph created showing VEI against injuries caused by eruption
Cell 19 - Spearmans Rank Calculated for VEI and injuries
Cell 20 - Scatter graph created showing VEI against damage caused by eruption
Cell 21 - Spearmans Rank Calculated for VEI and damage
Cell 22  - Scatter graph created showing VEI against houses destroyed by eruption
Cell 23 - Spearmans Rank Calculated for VEI and houses destroyed
Cell 24 - Geo scatter is created and shows distribution of volcanos and their type
Cell 25 - Hashed out code that was not used but their for refernce of trying a different method
Cell 26 - New column created with each Type of volcano as a number - was to be used for further calculations
Cell 27 - Bar graph created showing Type of volcano against deaths caused by eruption
Cell 28 - Hashed out calculation for chi sqaured as could not get the code to run
Cell 29 - Bar graph created showing Type of volcano against injuries caused by eruption
Cell 30 - Bar graph created showing Type of volcano against damage caused by eruption
Cell 31 - Bar graph created showing Type of volcano against houses destroyed by eruption
