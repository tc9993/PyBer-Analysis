<h1>PyBer Analysis</h1>

<h2>Overview</h2>

<h3>Purpose</h3>
<p>
The purpose of this project was to create a summary of the ride-sharing data by city type, a multiple-line graph that shows the total weekly fares for each city type, and provide an analysis of each item as well as business recommendations based on the data.
</p>

<h2>Results</h2>

<h3>Analysis of City Type Summary</h3>
<p align="center">
<img src="https://github.com/tc9993/PyBer-Analysis/blob/main/Analysis/city_type_df.png?raw=true" alt="Summary by City Type"><br>
<b>Exhibit 1.1:</b> Summary by City Type
</p>
<p>
From the summary presented in Exhibit 1.1 it is evident that the majority of ride-sharing business occurs in an urban environment.  Accordingly, urban cities have the most in all "total" categories, but rural cities perform the best on a per ride and per driver basis.  Suburban city ride-sharing is the middle ground between both rural and urban in both aggregate and per ride/per driver statistics.  
</p>
<p>
These statistics are generally reflective of population densities in each city type where urban cities have the largest populations and thereby will provide a greater number of drivers and consume the most ride-shares as opposed to rural communities where populations are sparse and destinations are spread out.  These differences in distance from location to location could be accounting for the differences in Average Fare per Ride where an urban citizen is natively closer to their destination compared to someone in a rural community.
</p>
<p>
Of note is the differences in Total Drivers and Average Fare per Driver between city types.  In urban cities we see that there are more drivers than total rides, driving the Average Fare per Driver down significantly, whereas rural city drivers had almost a 2:1 ride to driver ratio, and an Average Fare per Driver of nearly 3.5x that from Urban cities.

<h3>Analysis of Total Weekly Fares by City Type</h3>
<p align="center">
<img src="https://github.com/tc9993/PyBer-Analysis/blob/main/Analysis/PyBer_fare_summary.png?raw=true" alt="Total Fare by City Type" width=75% height=75%><br>
<b>Exhibit 1.2:</b> Total Fare by City Type
</p>
<p>
As shown in Exhibit 1.2, urban cities drive the most total revenue via fares week over week.  This graph is backed by the summary in Exhibit 1.1 that showed, in an overall summary, how urban cities generated around 9.75x more fare than rural cities.  In each given week from January to April of 2019 urban cities generated the most fare, followed by suburban cities, with rural cities generating the least amount of fare.
</p>

<h2>Summary</h2>

<h3>Business Recommendations</h3>
<ol>
  <li><b>Expansion of Data Collection:</b> To allow for expansion on this analysis, I would recommend collecting as much data as possible such as rider age, time of trip, trip distances, a list of major events in various operational cities, etc.  This would allow for more detailed analysis that extends beyond fare per ride or per driver.  Finding out the fare per distance and/or fare per minute could provide a drastically different look as an addition to Exhibit 1.1 as well as tell us which cities/city types are the most cost-effective ride-sharing solution for patrons, drivers, and the company.</li>
  <li><b>Spread Out Urban Drivers:</b> At present, there are more drivers in urban cities than ride-shares taken in the given timeframe.  Depending on the pay model, this is going to cost the company money in hourly rates or lead to drivers being displeased with their pay if they are not able to provide rides. Incentivizing rural or surburban rides without jeopardizing the ability to have urban rides on demand could be a good tool as currently the disparity between rides per driver, particularly in rural cities, is over 3x that in urban cities.</li>
  <li><b>Do Not Ignore Urban Cities:</b></li> Urban cities are PyBer's bread and butter, so to speak. Urban cities account for over 60% of all fare revenue and should not be an after thought, even if they bring in the least amount of money per ride.  The sheer volume of rides in urban cities is something to further study (i.e. how negative would the response be to a small increase in the base fare, or inversely, would more riders adopt PyBer if the base fare was slightly lower?).  Without more extensive data to analyze, it is difficult to surmise everything making the urban operation so successful besides crediting the large populations that may travel shorter distances than those members of rural and suburban communities.
</ol>
