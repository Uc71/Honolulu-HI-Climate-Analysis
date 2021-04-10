# Honolulu, HI Climate Analysis


For this assignment, I chose to analyze climate data from STARTDATE to ENDDATE.


I created an engine to connect to my sqlite database, reflected the data tables into classes and referenced those classes with the names "Station" and "Measurement".
I retrieved the last 12 months of data, extracted only the date and prcp values, and made them into a dataframe in Pandas.
I printed summary stats for this dataframe.
I then calculated the total number of stations and found the most active stations of the group. I listed these in descending order.
I identified the station with the maximum number of observations.
I then selected the last 12 months' worth of temperature data from the station with the most observations, and made this into a histogram.
In Flask, made and listed several routes, converted the results to a dictionary, and JSONified this dict.
I then got made a JSON list of stations and queried the dates and temperatures of the most active station for the final year.


I got a JSON list of min, avg, and max temperatures for the time between STARTTIME and ENDTIME.


When I only found STARTTIME data, I computed the min, avg, and max temperatures for all dates on or after STARTTIME.
