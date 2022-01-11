# Citibike Analysis
<img src="Images/citibike.jpg" width="600">

### Summary
Visual presentation and short analysis of CitiBike Trip Data. The visual charts were produced using Tableau.

### Tableau Story
The story produced on Tableau can be found here: https://public.tableau.com/shared/SYHZ2MJBY?:display_count=n&:origin=viz_share_link
<br />

### Dataset
Data was obtained from [CitiBike System Data](https://ride.citibikenyc.com/system-data) from the Citi Bike Trip Histories section.
<br />

### Data Cleaning
I initially download the entire latest year from the Citibike downloads page. However I quickly realised that this was too much data. I then attempted to use 6 months of data and this ended up being too much due to Tableau public having a limitation of 15 million rows.

I decided to use the last 4 months of data as this was the most data I could use and keep whole months instead of 4 months and part of a month.

The data cleaning steps can be found in the Jupyter notebook in the repository.

There were missing entries for end station, end time, end etc for many records. However this accounted for only about 0.5% of the total data so I was happy to drop these rows.
<br />

### City Map Analysis
It appears that the most frequetly used start and end stations are in the southern half of the manhattan area. Most of the tourist attractions, main city areas, workplaces, colleges/universities and financial district are in the area south of Central Park, correspondin to the stations with the most activity.

Below are 2 images which clearly indicated points of interest and the geographic population the course of a day. This matches up with the most used stations.
<br />

<img src="Images/manhattan-poi.png" width="250">
<img src="Images/manhattan_population.gif" width="300">

### Phenomenon 1
A few users end their Journey in Jersey City, but none start there!

This is a rather strange phenomenon. If someone travelled all the way to Jersey city then why would they not travel back, and therefore have a start Journey from Jersey.
<br />



### Phenomenon 2
Reducing Memberships towards winter. My data is only from June until the end of September.

We can see the Memberships start to decline as we move away from Summer. This could be due to the weather getting colder, so users would rather not use Bikes in the colder months. Unfortunately my data does not include winter months. This is also supported by an increase of casual users which may be the same people who had memberships using the bikes as casual users for some journeys.
<br />

### Phenomenon 3
We can clearly see the busiest hours in Manhattan both for start and End Journeys. As start and end time charts seem to line up nicely for hours, this is indicative that most journey durations are under an hour long.

The times match nicely with this beating heart visualision of the Manhattan population throughout the day.
<img src="Images/manhattan_population.gif" width="600">
<br />

### Tableau Chart Examples
Below are 2 examples of the charts made using Tableau
<img src="Images/popular-stations.png" width="600">
Map chart showing the most popular Citibike stations.
<br />

<img src="Images/journey-hours.png" width="600">
Bar chart showing average number of trips for each hour of the day.


<br />
<br />
<hr />
<br />

<img width="150" src="https://drive.google.com/uc?export=view&id=1OH_TvDjISYpoKL_98Jx3CDFPM7Xp8J6H">

### Abz Raja
abzraja@gmail.com
