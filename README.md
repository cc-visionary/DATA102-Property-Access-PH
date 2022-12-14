# DATA102-Property-Access-PH 

## Data Dictionary

| Column    |  Data Description | Data Type|
| :---:   | :---: | :---: |
| Name    | Name of a property listing in the website  | object|
|Address  |   Location of property      |  object |
|Author   |   Name of seller who currently owns the property     |    object |
|Price    | Cost of property in pesos      |           int32|
|Bedrooms  |  Number of bedrooms in the property      |         float64|
|Showers    |   Number of showers in the property    |        float64|
|Parking    |   Number of parking slots    |        float64|
|Furnish     |  If property is furnished or unfurnished     |         int32|
|Total Developed  |    Total area in sqm developed   |  float64|
|Features     |  The property features     |       object|
|Facilities   |  The facilities in the property     |       object|
|Nearby Places |  The places found near the property     |      object|
|URL     |  The url link to the property listing     |            object|
|Timestamp   |  Timestamp when the property was scraped     |        object|
|City   |  City location in the Philippines of the property     |             object|
|Region   | Region location in the Philippines of the property      |           object|
|Island     | Island location in the Philippines of the property     |         object|
|Type      |   If property is a condo or house    |          object|
|NFeatures  |  Number of Features the property has      |          int64|
|NFacilities      |  Number of Facilities the property has     |    int64|
|NNearby Places   |  Number of Nearby Place the property has     |    int64|


## Instructions
User must access the Jupyter notebooks in this sequence:
1. Scraping and Data Cleaning.ipynb
    - Output files: property_urls.csv / unclean_data.json / cleaned_data.json
      - The website is structured with multiple pages with each page having approximately 20 property listings. In our data collection process we collected the url of each property across the website, and stored the urls in property_urls.csv.
       - The data obtained from scraping are property details (name, address, price, author), utility information (bedroom, showers, furnish, parking, lot area), features, and the timestamp that notes what date and time the information was collected. After scraping all urls, the data obtained is stored in unclean_data.json. 
      - After the data cleaning was done on the data stored in unclean_data.json, the cleaned data was exported to cleaned_data.json to be used for analysis in the succeding notebooks
2. EDA.ipynb
    - Input file: cleaned_data.json
3. Research Question and Clustering.ipynb
    - Input file: cleaned_data.json
