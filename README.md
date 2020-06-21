<H2>UDACITY Communicate Data Findings Project</H2>"

The dataset that we analyzed for this project was from Ford GoBike.  The most recent dataset we used was from April 2019, before the service was rebranded as Bay Wheels after Ford ended its partnership with the program and Lyft absorbed Bay Area Bike Share.  This dataset consists of over 200,000 entries spanning 16 attributes.

Link to the Ford GoBike dataset from April 2019:  https://s3.amazonaws.com/baywheels-data/201904-fordgobike-tripdata.csv.zip

<h3>Summary of Findings</h3>

<h4>Findings from Univariate Exploration</H4>

1.  8:00 AM and 5:00 PM have the highest riding times and have the most riders
2.  4:00 AM is the lowest riding time with the fewest riders
3.  Males represent the majority of riders
4.  There are 8X more Subscribers than Customers

<h4>Findings from Bivariate Exploration</H4>

1.  Saturday and Sunday have the fewest riders, but the durations of the bike rides are longer.  There's a logical reason for this:  Subscribers use the GoBike service for commuting to work; Customers use the GoBike service for leisure.
2.  Females bike longer than males, even though males are older
3.  Subscribers are older than Customers, but Customers bike longer than Subscribers
4.  Most Subscribers bike on Tuesday; most Customers bike on Saturday
5.  Tuesday has the highest bike counts, most Subscribers, highest mean age of bikers, most bikers among males and females.  This is likely because Tuesday is the busiest day of the work week and more Subscribers use the GoBike service on Tuesdays than other days of the week.

<h4>Findings from Multivariate Exploration</H4>

1.  The timeframe between 3:00 AM and 4:00 AM has the fewest riders. Conversely, Saturday and Sunday has the fewest riders (but as we have already observed, more Customers than Subscribers, and mostly for leisure)
2.  There are more bike riders under the age of 40 spanning across the week
3.  Bike rides on Saturday and Sunday have longer durations than other days of the week.

<h3>Key Insights</H3>

1.  Distribution of age groups:  Although the majority of riders are under 40 years of age, if we had to focus specifically on which age group under 40, it would range between 20 and 40.
2.  Distribution of genders:  As mentioned, more female riders bike longer than males.
3.  Distribution of Subscribers/Customers:  There were more Subscribers than Customers.  However, we only examined one dataset, for the month of April 2019.  If we had examined a dataset that encompassed more months (e.g., October 2018 through April 2019), the number of Subscribers would be greater than the number of Customers (maybe 4X greater, but we would have to look at more data before determining an approximation).
