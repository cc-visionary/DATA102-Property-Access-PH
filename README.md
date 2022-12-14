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
2. EDA.ipynb
3. Research Question and Clustering.ipynb
