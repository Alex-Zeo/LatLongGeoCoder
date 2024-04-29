# LatLongGeoCoder
Lat &amp; Long generator from a list of addresess

This Python script uses the OpenCage Geocode API to convert a list of addresses, primarily located in and around Atlanta, GA, into geographic coordinates.
The coordinates are obtained by sending each address to the OpenCage Geocode service, which returns latitude and longitude values if the address is successfully geocoded.
These values are then stored in a CSV file along with the corresponding address. If an address cannot be geocoded, the entry for that address is marked as "Not found" for both coordinates.


![image](https://github.com/Alex-Zeo/LatLongGeoCoder/assets/6181715/5f440b0e-4ddd-4b79-aa7a-68dc57acfae8)


Additionally, the script is part of a larger project aiming to enhance tourism in Atlanta by integrating these geocoded addresses with data from Yelp, Michelin, and Google Places.
This integration will help visualize hotels, restaurants, and attractions within a 10-minute walk from a MARTA station.
The geocoded results are also visualized on a map using the Folium library in a Jupyter notebook, providing a spatial representation of the data.
This visualization occurs only if the geocoding process is successful for each address.

![image](https://github.com/Alex-Zeo/LatLongGeoCoder/assets/6181715/e2b7112f-37e5-47a6-9500-e4a3dc964f1c)
