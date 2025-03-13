Location Geocoding and Validation with Google Maps API
This project processes location changes by geocoding city and country names using the Google Maps API. It checks for potential issues such as missing or incorrect country and city updates and saves the results in CSV format.

Features
✅ Reads and processes location data from location_changes.csv
✅ Geocodes locations using Google Maps API
✅ Handles missing or incorrect country/city updates
✅ Saves processed data to full_result.csv and full_result_2.csv


Requirements
Python 3.x
Google Maps API Key
Required Libraries:
pip install pandas geopy fuzzywuzzy python-Levenshtein spellchecker googlemaps

main.ipynb is the main notebook
