# London-Bicycle-Rentals

Tools and Languages: SQL, BigQuery

Description and Intent: This project used Google's BigQuery to explore and analyse a large public database containing data about bicycle rentals from the publicly availably cycle stations within London, England. The database contained two tables: 'cycle_hire' with 83,434,866 rows and 'cycle_stations' with 795 rows. 

Explorations were intended to remain within BigQuery only and used the following set of questions to guide the analysis:

What is the first rental start date and last rental end date? ie. What span of time does the database cover? 

How has the number of rentals changed over time?

What is the longest, shortest and average rental duration?

How many different bikes and bike models have been in use over the full period?

How many times has each bike been rented? Can the highest number of rentals be attributed to older bikes? ie. Are many bikes being used more/less than expected?

What are the most popular starting stations?

Are there any increasing or decreasing trends for use of the top starting station?

What are the most popular finishing stations?

How many journeys start and finish at the same location?

What are the geolocations (latitude, longitude) of each station?

Insights and Reporting: Queries were conducted with various techniques including aggregate functions, joins, CTEs and windows functions. The code was formatted to resemble more closely BigQuery's suggested auto-formatting; this was similar to previous project's code formatting, but code was spread across a greater number of rows to differentiate steps more clearly.

Queried results to the set questions can be found at: https://www.brandonodonnell.com/portfolio/london-bicycle-rentals
