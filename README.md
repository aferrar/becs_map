# becs-map - A GeoWeb Service for Locating The Best Breakfast Sandwich

### Getting Started
___
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
___
Here are some of the resources used to create this service.
* Python 3 or another server application with POST support.
* A Browser
___
### Installing
___
Simply fork or clone the project to a local repo or directory. Point data for restaurants and delis can be located in the Data folder. You can also find different subsets of the deli dataset which were used during primary development during host testing.
___
### Deployment
___
First open a terminal (OXS and Ubuntu) or command prompt/PowerShell (Windows) instance. Navigate to the project directory. Launch a server instance using Python 3 or another server application. 
This can be done in Python 3 with:
>python -m http.server[port]

You can now open a browser and direct it to localhost:<port> to view the web service or navigate the directory tree.
___
### Built With
___
* QGIS
* CartoDB Account
* Python 2 or 3
* Text Editor/IDE
* Bootstrap
* JQuery
* Leaflet
___
### Author
___
Adrian Ferrar
___
### Acknowledgments
___
Special thanks to my professor and fellow classmates, everyone over at Stackoverflow who helped me debug issues, and to PurpleBooth for their README-Template.
___
### Further Improvements
___
Include a second sql call to restaurant dataset in Carto. Include toggle button to alternate between datasets on click. Expand both datasets to include more properties. Include realsitic pricing through store surveying, data mining or scraping. Improve popup HTML. Cuzstomize popup markers from leaflet default to sandwich asset in img folder.  
