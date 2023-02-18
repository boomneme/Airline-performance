# Profiling Aircraft On Time Performance for climate-friendly planning.
# by Obum Onwudiwe


## Dataset

The dataset contains scheduled and actual departure and arrival times for 2005 and 2008, reported by certified U.S. air carriers that account for at least one percent of domestic scheduled passenger revenues. The data is collected by the Office of Airline Information, Bureau of Transportation Statistics (BTS). There are 1,048,575 flight records in each dataset with 29 features each and obtained from https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009.


## Summary of Findings

Histograms were used to obtain the distribution of the columns of interest. From 2005 to 2008, an increase in the number of flights and overall delays is observed.
NAS delays show the highest decrease, while late aircraft delays show the highest increase.
There is a lot more reporting of delays on departures compared to delays on arrivals, for delays times less than 15 mins. A scatterplot shows a lot more points for delay times less than 5 mins on departures.
The various delay causes do not show much of a correlation with each other. Flight time is good at predicting the length of an extended delay.
Weather has the highest average duration for delays, but is not the most occuring delay cause. 
Carrier delays have a lower average duration but have a wider stretch, with maximum values higher than late aircraft delays. NAS delays which have the highest count of delays, has one of the lower average duration.
Some airlines with short average flight times have a high delay duration, while some airlines with long flight times have short delay durations.
Airlines with higher average delay durations across all delay causes are not necessarily the airlines with the most delays.
Some airlines have some high peak delay numbers, but not as high on the averages.
The threshold of consideration will affect the apparent average delays.
Frequent flyers are mostly not impacted with security delays.
The heatmap provides a broader view of how each delay cause impacts the various airlines and can be traced to what phase of the flight envelope (arrival or departure) by the airport where the event occurred.


## Key Insights for Presentation

For the presentation, focus is on the count of delays and the average of delays of each airlines. I want to show how much of an impact an average delay duration has on an airline, compared to how the count of delays also affects the airline. I use various plot styles to present count and averages and make comparisons between airlines with reference to both. An annotated heatmap to present numbers that can be benchmarked for decision making and further investigations.  
