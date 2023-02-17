# Seattle's Crime Data Visualized on Mapbox

## Project Idea
We will be creating a smart dashboard displaying Seattle crime statistics. The data set includes longitude and latitude information of crimes that have occurred and time stamps, which we will be visualizing using different icons, each representing the type of crime at the location. Upon clicking on an icon, there will be a pop-up displaying the timestamp of the crime and what kind of crime it was.
With the data on types of crimes and its timeline, we can separate the crimes per year on the map and we can show statistics on what kind of crimes were prevalent in each area. Because we have shapefiles of each neighborhood, we can potentially highlight where each type of crime is the most common with a choropleth theme.

## Project Significance and Broader Impacts

Our project can be used to help people who are deciding where they would like to live as well as to inform law enforcers or police which areas may need stricter patrols to decrease crime levels. Easily accessible maps that are visualized in this manner and kept up to date can help people in real time when looking to travel, making plans, and even for routing, especially if they are walking.

We can see that people may try to find crime data outside of Seattle, or crimes in real time. However, our data is only of finalized crime reports in Seattle, so it may not be representative of all crimes that occurred. We need to specify that our data is just local to Seattle for our mapping purposes, so crimes will only be shown for the city of Seattle. We have also filtered our data to take out crimes without a longitude or latitude number, so the crime number and locations are not completely accurate. Lastly, we do not have real time data, so all data shown will be for reference on recent and annual data analysis to see what areas are safe or not as safe via the map visualizations.

To prevent false interpretations, we could include a disclaimer or note on our website that explains what type of data was collected. 

## Major Data Sources


Our primary data source for crime statistics comes from the city of Seattle at: https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5. 

We will be potentially using the shapefiles of each neighborhood, listed in: https://catalog.data.gov/dataset/micro-community-policing-plans-1a52e/resource/cb04d751-54e8-40a8-bfc1-98ab29200672 or at:
https://data-seattlecitygis.opendata.arcgis.com/datasets/city-clerk-neighborhoods/explore?location=47.614536%2C-122.336950%2C12.87
