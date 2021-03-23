# Mapping_Earthquakes
## Project Overview
The objective of this project is to gather earthquake GeoJSON data from the USGS API, create and explore interactive maps of earthquakes around the world.
The earthquake data is represented on the maps in relation to the tectonic plates’ location on the earth, and according to each event's magnitude.

## Resources
Data Source: Earthquakes GeoJSON, Earthquakes above 4.5mag GeoJSON, Tectonic Plate GeoJSON
Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, Leaflet 1.7.1, D3.js 6.2.0
## Results
Create a Mapbox account, setup config.js and open index.html
To interact with the maps API the user have to visit mapbox.com, create a Mapbox account and retrieve the access token.

As shown below, the index.html calls for the Mapbox API key in the config.js file.
![api](https://user-images.githubusercontent.com/64053195/112073628-e02fc580-8b4a-11eb-95d0-c3fd161fc1df.png)

The user would have to save the token key in config.example.js and rename the file config.js:
![tocken](https://user-images.githubusercontent.com/64053195/112073663-f047a500-8b4a-11eb-9667-78c06e41445f.png)

To open the index.html file, open the command line, navigate to the main folder and on the command line, enter python -m http.server.

## Interactive Maps Views
### Street View
![street](https://user-images.githubusercontent.com/64053195/112073748-140aeb00-8b4b-11eb-8ef2-169edf8067c0.png)

### Satellite view
![Satellite view](https://user-images.githubusercontent.com/64053195/112073794-29801500-8b4b-11eb-890e-6dd5d4fb043f.png)

### Dark view
![Dark view](https://user-images.githubusercontent.com/64053195/112073813-369d0400-8b4b-11eb-9443-634a0dc3acd2.png)

