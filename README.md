# BootCamp_sqlalchemy-challenge


## Precipitation Analysis

1. Find the most recent date in the dataset.
![Most Recent Date](Images/Most_Recent_Date.png)

2. Using that date, get the previous 12 months of precipitation data by querying the previous 12 months of data.

3. Select only the "date" and "prcp" values

4. Load the query results into a Pandas DataFrame. Explicitly set the column names.

5. Sort the DataFrame values by "date".

6. Plot the results by using the DataFrame plot method.
![Bar Plot](Images/Bar_Plot.png)

7. Use Pandas to print the summary statistics for the precipitation data.
![Summary](Images/Summary.png)

## Station Analysis

1. Design a query to calculate the total number of stations in the dataset.
![Number of Stations](Images/Station_Num.png)

2. Design a query to find the most-active stations (that is, the stations that have the most rows)
   * List the stations and observation counts in descending order.
   ![Stations Descending](Images/Station_List_Desc.png)

   * Answer the following question: which station id has the greatest number of observations?
   ![Most Observations](Images/Most_Obs.png)

   * Using the most-active station id, calculate the lowest, highest, and average temperatures.
   ![Low_High_Avg_Prec](Images/low_high_avg.png)

3. Design a query to get the previous 12 months of temperature observation (TOBS) data.
   * Filter by the station that has the greatest number of observations.
   * Query the previous 12 months of TOBS data for that station
   * Plot the results as a histogram with bins=12
   ![Temp Histogram](Images/Temp_Hist.png)


## Design Your Climate App
1. Home Page
![Home Page](Images/Home_Page.png)


2. Precipitation Page
![Precipitation Page](Images/Precipitation_Page.png)

3. Stations Page
![Stations Page](Images/Stations_Page.png)

4. Tobs Page
![Tobs Page](Images/Tobs_Page.png)

5. Start Date plus Start and End Date Pages
![Start Date](Images/Start_Date_Page.png)
![Start and End Date Page](Images/Start_End_Date_Page.png)


