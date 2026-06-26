Title : New York’s Subway Accessibility and the Burden of "Strength"
This project analyzes subway station accessibility across New York City using the MTA dataset and demographic data from the U.S. Census Bureau. It explores the premise that New York subways lack elevators due to the "strength" of New Yorkers, fact-checking this against the actual infrastructure and the demographic needs of the city's residents.
Guide to the repository :
NYsubway.ipynb: Contains the code used to clean the MTA station data and merge it with U.S. Census population data. It should be noted that demographic data, such as population segments for children under 5 and seniors aged 65 and over, were aggregated to identify vulnerable populations by borough. The analysis highlights the discrepancies between accessibility infrastructure and these demographic needs.
docs: This folder contains the parquet and/or csv files for the MTA station data, census population data, and borough-level metrics.

data analysis process :
Subway Data: I downloaded a comprehensive CSV file containing details about each subway station from the MTA Open Data portal and performed data analysis using pandas. https://data.ny.gov/Transportation/MTA-Subway-Stations-and-Complexes/5f5g-n3cz/about_data

Demographic Data: To gather population statistics, I accessed the U.S. Census Bureau API. The data extraction process was conducted in accordance with the Census API User Guide. https://www2.census.gov/data/api-documentation/api-user-guide.pdf

Growth & New Skills:
I practiced how to retrieve data using API keys.
I analyzed the data using pandas and exported the processed results into appropriate CSV files.
I created visualizations using Datawrapper to effectively communicate the findings.

What I Wanted to Do (Future Steps):
For a more in-depth analysis, I believe incorporating spatial mapping would be highly effective, as it would allow for a more nuanced understanding of how accessibility gaps are distributed geographically across the city.

Link to the story - https://sisksyfftmk.github.io/NYCsubwayAccesibility/
