# data-analysis-tutorial

Obtain the CSV file containing the counts of
bicycles crossing the Fremont Bridge since 2012 (as described in
`https://data.seattle.gov/Transportation/Fremont-Bridge-Hourly-Bicycle-Counts-by-Month-Octo/65db-xm6k`).
 Data downloaded from: `https://data.seattle.gov/api/views/65db-xm6k/rows.csv?accessType=DOWNLOAD`

Some experiments performed on the dataset are:
1. Read the CSV file into a pandas dataframe
2. Add columns to the dataframe containing:
  * The total (East + West) bicycle count
  * The hour of the day
  * The year
3. Create a dataframe with the subset of data from the year 2016
4. Use pandas + matplotlib to plot the counts by hour. (i.e. hour of the day on the x-axis, total daily counts on the y-axis)
5. Use pandas to determine what is (on average) the busiest hour of the day