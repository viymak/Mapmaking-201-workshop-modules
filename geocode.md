## Geocoding

*Address to geographic coordinates*  

*Often, you will find that your data contains a street address without coordinates.  In order to place these points on a leaflet map, you will need to reformat these locations as latitude and longitude.*


##### Nominatim #####  
[Nominatim](https://nominatim.openstreetmap.org/) is a free search engine for OpenStreetMap data.

##### GeoPy ######    
[GeoPy](https://geopy.readthedocs.io/en/stable/) allows you to easily use third party geocoders in python.


`from geopy.geocoders import Nominatim`  
`from geopy.extra.rate_limiter import RateLimiter #optional for our purposes `
