# What is this project?

1. **Web map**: Right now, there is no easy online or offline way to see all the Los Angeles region food banks and their hours of operation. We want to make it easier for people to find their nearest food bank that will be open today and tomorrow. Once complete the map will be hosted by the [LA Regional Food Bank](https://www.lafoodbank.org/) so that those in need can more easily find resources.

2. **Compile a pool of hunger data**: The [LA Regional Food Bank](https://www.lafoodbank.org/) recently was accepted into [ESRI](http://www.esri.com/)'s program for Non-Profit organizations. We want to get them started right so we'll be gathering relevant data on hunger in LA County. This will be used for a [MaptimeLA](http://maptimela.github.io) night on **data visualization**. The data will then be added to the **LA Regional Food Bank's ArcGIS Online** portal. Any public data will remain in a public repository here or managed by the Food Bank so that others can benefit from the work we do.
 
**Current Project Status:** Data research, data cleaning/formatting, adding data to [OpenStreetMaps](http://www.openstreetmap.org/)

**Coming Soon:** We are scheduling and planning a **Data & Map Workshop Night** for early September.

# How can I help?

| Phase        | Task           | Contact  |
| ------------- |:-------------:| -----:|
| Data Formatting      | Truth Table has been formatted in a [Google Spreadsheet](https://docs.google.com/spreadsheets/d/1gfOMO2hE7KMb1lE7e9YKVpDVm0taH_0C9uIxy3KfZkM/edit#gid=0) |  Request access from [@JRHutson](https://github.com/JRHutson)  |
| Open Data | Adding [Food Banks data](https://docs.google.com/spreadsheets/d/1gfOMO2hE7KMb1lE7e9YKVpDVm0taH_0C9uIxy3KfZkM/edit#gid=0) to Open Street Maps |  Questions?  [@JRHutson](https://github.com/JRHutson) |
| Data Researching     | Researching public data about hunger in LA County      |   Make Pull Request |

# Want more help on these tasks? 

- [x] **Truth Table:** `[DONE]` Thank you [@Nina](https://github.com/matikin9) for completing this task. The truth table that will power the symbology of the webmap is currently complete, other than a few issues that need to be resolved.
- [ ] **OSM Updates:** `[ONGOING]` 
- [ ] **Data Gathering:** `[ONGOING]` Some relevant data will be derived from the Food Pantry locations once they are geocoded, such as drive time areas. Other data that would be relevant to the mission of the Food Bank needs to be compiled and prepared for the upcoming Maptime LA Hunger Data Night and eventual upload to ArcGIS Online.

# How to add Food Banks on OpenStreetMap:
1. Request access to the Google Sheet so you can let others know a Food Pantry has been added to OSM.
2. There is also a column in the [Google Spreadsheet](https://docs.google.com/spreadsheets/d/1gfOMO2hE7KMb1lE7e9YKVpDVm0taH_0C9uIxy3KfZkM/edit#gid=0) indicating whether the Food Pantry has been added to Open Street Map. Please request access and update the sheet so others know a pantry has been added. 
3. **Category**: OSM already has a `category` for `food pantries`. Many are housed in `churches` and `community centers`, so be sure to distinguish between the organization and the food pantry in how you name the point added to the map. 
4. **Contact Number and Hours**: Be sure to add the `contact number` and `hours` to the point as well.
5. **Commit notes**: Include `#Maptime` and `#MaptimeLA` in your commit notes. 

# Data brainstorming and checklist:
Datasets are starting to be assembled in the data folder of this repo. If you want to contribute data, try to get it condensed to an extent that will be relevant to the project before uploading. (Generally LA County is ideal) If you are not familiar with how to do this, upload what you have and submit an issue for it to be clipped. For shapfiles, stick to the WGS 1894 State Plane Zone V projection. This is the standard projection used by LA County and will avoid future conflicts when working with the data.

Here are some geographic, demographic and other data sources we've brainstormed as relevant for this project. What else should we look up?
- [ ] Census Poverty Data for LA County
- [ ] Census Block Outlines for LA County
- [ ] Census Statistics on usage of Food Stamps and WIC Benefits for LA County
- [ ] Supermarket Locations and Hours of Operation
- [ ] State Legislative District Boundaries
- [ ] Federal Congressional District Boundaries. 

Latest Brainstorm List is here: https://docs.google.com/spreadsheets/d/1s_PRZ_seM9PUUyPtKjClWV7a3kkxW83RhdWHlBTljto/edit?usp=sharing
# Have questions? Ideas? Open an Issue or submit a suggestion through our Google Form.
https://docs.google.com/forms/d/1IKmcIz4dVsqnK0WavEZo-gWiQZzdLaIjukiFouhPPUA/viewform?usp=send_form

# Contact 
- Project Lead: [@JRHutson](https://github.com/JRHutson)
