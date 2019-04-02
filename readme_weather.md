# Exploration of 2018 Trip Data for the San Francisco Bay Area Bike-Sharing System
## by Ellen Craig


## Dataset

> I downloaded the Ford GoBike public trip data from the program website: https://www.fordgobike.com/system-data.  Each row describes an individual trip taken as well as the gender, birth year, and subscription status of the customer where available. The data was provided month-by-month and my investigation was for 2018, so my data wrangling included adding a month column to each dataset and then combining all twelve dataframes into one for the year.  In addition to the Udacity lessons, I used stackoverflow.com to understand code.


## Summary of Findings

> I was interested in the popularity of the program and what variables might show correlation with usage, and the first bar chart showed that subscribers took more trips than customers.  I  then made bar charts and a histogram showing the number of trips taken from each station in the study, which showed substantial variation and a sharp drop-off from the most popular stations to the rest of the dataset.  Based on box plots that were cut off and a scatterplot that was jittered to accurately show a large number of data points, more popular stations to leave from typically showed shorter trip lengths.  The lat-long graph with a colorbar showing number of trips aided comparison of bike-share usage by station placement.


## Key Insights for Presentation

> The focus of this investigation was bike-share usage based on the number of trips taken.  The histogram showing total trips for the year for each station individually should come first, because it shows the variation in popularity as judged by usage.  Next will come the jittered scatterplot showing average trip duration vs number of trips from a station, because that plot shows how bikes are being used when starting from more-used and less-used stations.  Finally, the multivariate scatterplot showing longitude vs latitude and number of trips starting from each location will show the relative locations of popular and less popular start stations.