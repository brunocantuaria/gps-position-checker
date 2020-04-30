# gps-position-checker
Check if your GPS coordinates are inside a polygon created by a GeoJSON file.

## Objective
This sample from a project was created for checking if user is inside a brazillian state, Minas Gerais. Using libraries, the code is fairly simple and can easily be re-usable.

It was built using a GeoJSON file with the state borders, a 3rd party script for reading the file and check if a specific coordinate is inside it's borders, and a simple inline script for reading the browser geolocation.

## Resources Used
- [d3-geo](https://github.com/d3/d3-geo) - Used for reading the GeoJSON file and check if point is inside the polygon created by it.
- [Exploratory Brazil States](https://exploratory.io/map) - The GeoJSON file was originated from the main state files provided by Exploratory.
