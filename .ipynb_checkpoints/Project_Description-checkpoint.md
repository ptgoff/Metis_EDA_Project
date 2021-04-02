# EDA Project 
Peter Goff

### Question/need: <br>
A number of analyses have shown that ridership on NYC's subway system (MTA) has decreased during the covid pandemic. While it is usefful to quantify the aggregate drop, it would also be helpful to identyify meaningful heterogeneity in ridership changes across the city. City, state, and federal health offices all stand to benefit from a more nuanced understanding of how ridership has changed as a result of social-distancing policy. For example, in areas where ridership has decreased dramatically, do we observe fewer covid outbreaks? Do we also observe more business forcloseures? <br>
Having information on the ways in which transit sites have deviated from historical traffic patterns in times of crisis may help governmental agencies direct resources (temporary hospitals, vaccines, etc.) and consider implementing alternative policies, such as limiting transactions at certain sites. Further, findings from such analyses could be used to shape these policies by providing viable thesholds and time targets. <br>
This project will examine heterogeneity in transit usage during covid by comparing transit numbers for July of 2020 and comparing them to historical usage from the three prior years with the goal of identifying the stations with greatest proportional decreases and increases. <br>

### Data Description: <br>
This project will draw from several publicly available data sets, centered primarily on [MTA Turnstyle data](http://web.mta.info/developers/turnstile.html). This data will be downloaded directly from the MTA website. Key characteristics of this data include the turnstyle location (station, linename, and division), timestamp, and entries/exits. While the data are recorded at the turnstyle-level, an aggregation to the station-level would likely provide a more meaninful portrayal of usage trends. <br>
At this initial stage of the project, I plan to provide a comprehensive graphical-descriptive portrayal of the heterogeneity in transit usage during covid. However, if time allows, subsequent analyses integrating business/commerce and/or demographic data may add fruitful nuance to the trends that emerge. <br>

### Tools: <br>
Data will be downloaded as local .csv files, then processed into a SQL database. That database will be querried into a Pandas dataframe for final analysis. Data cleaning and analysis will be conducted in Pandas and perhaps geopandas. Ideally, I would like to present my findings in their geographic context via a shapefile and appropriate graphing program. <br>

### MVP Goal: <br>
The minimum viable product will be a catapilliar plot that depicts proportional changes in usage across all MTA stations. Accompanying this plot will be documentation on the stations on the tails of the plot that experienced the greatest and smallest decreases (or increases, as the case may be). <br>
