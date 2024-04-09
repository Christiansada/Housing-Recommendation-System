# Exploring Tourist and Business Venues in Indian States

## Introduction
This project aims to explore tourist attractions and business venues in various states of India. Using Foursquare API data, we analyze the distribution of tourist spots and businesses across different districts in selected states. The project includes data visualization, clustering analysis, and insights into the most common venues in each district.

## Data Collection and Preprocessing
- Data was collected from the "capstone_dataset.xlsx" file, containing information about Indian states, districts, population, area, and density.
- Data preprocessing involved renaming columns, handling missing values, and filtering out irrelevant data.

## Data Analysis
- Population in each state was visualized using bar plots, showcasing the demographic distribution.
- A map of each state with its districts superimposed was created using Folium, providing a geographical overview.
- The Foursquare API was utilized to retrieve tourist spots and business venues in each district.

## Foursquare API Integration
- Foursquare API credentials were used to access venue data.
- Tourist categories and business categories were extracted from the API to filter relevant venues.

## Tourist Venues Analysis
- The number of tourist venues in each district was analyzed and visualized.
- Common tourist spots in each district were identified and presented using bar plots and tables.

## Business Venues Analysis
- The number of nearby businesses for each tourist venue was analyzed and visualized.
- Business categories were clustered to identify patterns and distinguish different clusters.

## Clustering Analysis
- K-means clustering was applied to group similar districts based on the types of nearby businesses.
- The optimal number of clusters was determined using the elbow method.
- Clusters were visualized on a map using Folium.

## Cluster Examination
- Each cluster was examined to understand the characteristics and predominant businesses in each group.

## Conclusion
This project provides valuable insights into the distribution of tourist attractions and businesses across Indian states. By analyzing venue data from the Foursquare API, we gain a better understanding of the tourism and business landscape in different regions. The findings can be useful for tourists, local businesses, and policymakers alike.


