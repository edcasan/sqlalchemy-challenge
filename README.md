

Climate Analysis and Exploration using Python and SQLAlchemy to do basic climate analysis and data exploration of my climate sqlite database, completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.


Precipitation Analysis
- Query to retrieve the last 12 months of precipitation data,
- Selected only the date and prcp values,
- Loaded the query results into a Pandas DataFrame and set the index to the date column,
- Sorted the DataFrame values by date,
- Plotted the results using the DataFrame plot method,
- Used Pandas to print the summary statistics for the precipitation data.

Station Analysis

- Designed a query to calculate the total number of stations,
- Designed a query to find the most active stations,
- Listed the stations and observation counts in descending order,
- Designed a query to retrieve the last 12 months of temperature observation data (TOBS),
- Filtered by the station with the highest number of observations,
- Plotted the results as a histogram with bins=12.

Climate App

- Used Flask to create my routes,
- Listed all routes that are available,
- Converted the query results to a dictionary using date as the key and prcp as the value,
- Returned the JSON representation of my dictionary,
- Returned a JSON list of stations from the dataset,
- Query the dates and temperature observations of the most active station for the last year of data,
- Returned a JSON list of temperature observations (TOBS) for the previous year,
- Returned a JSON list of the minimum temperature, the average temperature, and the max temperature for a given start or start-end range.

Temperature Analysis I

- Identified the average temperature in June and December at all stations across all available years in the dataset, 
- Used the t-test to determine whether the difference in the means, 

Temperature Analysis II

- Returned the minimum, average, and maximum temperatures for that range of dates,
- Used the calc_temps function to calculate the min, avg, and max temperatures for your trip using the matching dates from the previous year,
- Plotted the min, avg, and max temperature from your previous query as a bar chart.


Daily Rainfall Average

- Calculated the rainfall per weather station using the previous year's matching dates,
- Calculated the daily normals. Normals are the averages for the min, avg, and max temperatures,


![image](https://user-images.githubusercontent.com/63757160/109596068-1db8aa00-7adb-11eb-9bfd-2257a702e1ba.png)

![image](https://user-images.githubusercontent.com/63757160/109596098-31641080-7adb-11eb-99ec-ac6007b31f4a.png)

![image](https://user-images.githubusercontent.com/63757160/109596170-5062a280-7adb-11eb-8105-e43ea085d1be.png)

![image](https://user-images.githubusercontent.com/63757160/109596201-61131880-7adb-11eb-8af4-f476ea14a80a.png)

![image](https://user-images.githubusercontent.com/63757160/109596237-7425e880-7adb-11eb-8cb4-959894777ef4.png)

