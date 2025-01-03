# Time Series New York City Motor Vehicle Collisions Project
This project analyzes traffic crash data from New York City to identify high-risk areas, understand crash patterns, and assess the impact of external factors like COVID-19. Insights aim to inform recommendations for improving road safety, particularly for vulnerable road users such as pedestrians and cyclists.

## Project Overview
This project uses time series analysis and geospatial analysis to explore traffic crash data in New York City. The dataset includes detailed records of motor vehicle collisions, including information on fatalities, injuries, and crash locations. The goal is to identify trends over time, assess the severity of crashes, and provide safety recommendations for vulnerable road users, such as pedestrians, cyclists, and motorists.

## Data Sources
The primary dataset used in this analysis includes traffic crash records provided by the New York City Department of Transportation. This dataset includes key variables such as crash date, crash time, location (latitude and longitude), number of injuries, and fatalities.

## Methodology
1. **Time Series Analysis**: 
   - A deep dive into crash trends over time, focusing on identifying patterns related to specific dates, times of day, and annual trends. 
   - Time series decomposition was used to separate trend, seasonality, and residual components for better understanding of underlying factors.

2. **Geospatial Analysis**: 
   - The geographic distribution of crashes was examined by plotting crash data on a map, with color-coded markers based on severity.
   - Heatmaps were created to identify crash hotspots and assess areas that may require targeted safety measures.

## Key Insights and Findings
- **Crash Trends**: There were noticeable fluctuations in crash frequency due to the impact of COVID-19, with significant declines in crashes during lockdown periods.
- **Crash Severity**: Boroughs with high traffic volumes, such as Brooklyn and Manhattan, showed a higher frequency of crashes, while more suburban areas experienced fewer incidents.
- **Hotspots**: Geospatial analysis identified specific intersections and neighborhoods with disproportionately high crash rates, particularly those with high pedestrian and cyclist activity.

## Recommendations
Based on the findings, several recommendations are proposed to improve road safety:
- **Targeted Safety Measures**: Implement more pedestrian-friendly infrastructure in high-risk areas, such as better crosswalks and bike lanes.
- **Public Awareness**: Increase awareness campaigns for both drivers and pedestrians in crash hotspots, especially during peak hours.
- **Data-Driven Policymaking**: Use time series and geospatial insights to guide city planners in making data-informed decisions for urban traffic management and safety.

## Technologies Used
- Python (Pandas, Matplotlib, Seaborn, Folium)
- Time Series Analysis (Statsmodels)
- Geospatial Mapping (Folium)

## Future Work
- Expansion of the dataset to include additional years of traffic crash data.
- Further refinement of predictive models to anticipate future crash hotspots.
- Incorporation of other relevant data sources (e.g., weather, road conditions) for more comprehensive analyses.

