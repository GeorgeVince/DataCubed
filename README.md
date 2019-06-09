# DataCubed
DATA CUBED INTERVIEW

## Technologies Used:
- Python (ETL / Data cleaning / Visualisation)
  - Libraries used: Pandas, geopy, Seaborn, Geomaps.
- Excel (Data Validation)
- PowerBI ( Data Visualisation)



## File descriptions:
- lat_lon.csv - 500 LAT / LON Coords throughout the UK.
- lat_lon_full. csv - The final cleaned dataset
- loc_raw_data.p - scarped OSM data for 500 coords.

- Lat Long - ETL Cleaning.ipynb - workbook documenting the cleaning process.
- Analysis.ipynb - A quick EDA Analysis file.



## Issues Found:
1) Not all LAT/LON Coords could be mapped. 
For such a small dataset, this was trivial to fix. If the data set was much larger, could consider different methodologies to fixing this.  For example, find the closest location to the given coordinates that contains valid data.

2) Erroneous scaped data - for example some sites contained multiple location ID's, such as being a member of a TOWN and a CITY.  It was also easy to fix this due to the relatively low number of items in the dataset.  If this data such as much larger, I would consider using multiple sources to verify the validity of the scraped data.
