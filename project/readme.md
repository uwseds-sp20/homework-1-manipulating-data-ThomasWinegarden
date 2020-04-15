# This is for Homework 1 of the course DATA 515 Spring Quarter 2020 at the University of Washington
## I am Thomas Winegarden
### You will find my final hw notebook in ./analysis and the data use in ./data
#### Below is the Homework 1 specification:

Obtain the CSV (comma separated variable) file containing the counts of bicycles crossing the Fremont Bridge since 2012 (as described in https://data.seattle.gov/Transportation/Fremont-Bridge-Hourly-Bicycle-Counts-by-Month-Octo/65db-xm6k). Create a project directory with subdirectories for data and analysis, and create a README file. Download the data from https://data.seattle.gov/api/views/65db-xm6k/rows.csv?accessType=DOWNLOAD and put it in the data directory. Create a Jupyter notebook to analyze these data. In the notebook, complete the following:

1. Read the CSV file into a pandas dataframe. (1 pt)
1. Add columns to the dataframe containing: ( 3 pt)
   1. The total (East + West) bicycle count
   1. The hour of the day
   1. The year
1. Create a dataframe with the subset of data from the year 2016 (1 pt)
1. Use pandas + matplotlib to plot the counts by hour. (i.e. hour of the day on the x-axis, total daily counts on the y-axis) (1 pt)
1. Use pandas to determine what is (on average) the busiest hour of the day (1 pt)
