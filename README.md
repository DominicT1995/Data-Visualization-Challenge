# Data-Visualization-Challenge
UTSA Data Analytics Bootcamp data visualization challenge where data from an animal study for cancer treatment will be used to generate tables and figures used for analysis.

------------------------------------------------------------------------------------------------------------------
PYMACEUTICALS

The Pymaceuticals folder contains the data folder which contains the Mouse_metadata.csv file and the Study_results.csv file where the data for this analysis will be extracted from.

The pymaceuticals.ipynb file in the Pymaceuticals folder utilizes python code and the pandas and matplotlib libraries in a jupyter notebook in order to open and convert the Mouse_metadata.csv file and the Study_results.csv into a single dataframe. The python code will then perform calculations based on the data and aggregate the data into a cleaned dataframe, summary statistics table, and a variety of visual plots for analysis.

Visual representations used in this analysis include a summary statistics table of tumor volume data, bar charts describing total timepoints vs drug regimen, pie charts of gender representation in the tested population, boxplots of data spread for final tumor volume of four drugs of interest, coded block creating a line plot of tumor volume vs timepoints for any given single mouse, and scatter plot of weight vs tumor volume with linear regression.