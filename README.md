
# What is this project?

**Hunger Data Pool**: The [LA Regional Food Bank](https://www.lafoodbank.org/) recently was accepted into [ESRI](http://www.esri.com/)'s program for Non-Profit organizations. We want to get them started right so we'll be gathering relevant data on hunger in LA County. This will be used for a [MaptimeLA](http://maptimela.github.io) night on **data visualization**. The data will then be added to the **LA Regional Food Bank's ArcGIS Online** portal. Any public data will remain in a public repository here or managed by the Food Bank so that others can benefit from the work we do.
 
**Current Project Status:** Data research, data cleaning/formatting, adding data to [OpenStreetMaps](http://www.openstreetmap.org/)


# How can I help?

| Phase        | Task           | Contact  |
| ------------- |:-------------:| -----:|
| Data Researching     | Researching public data about hunger in LA County      |   Make Pull Request |
| Open Data | Adding [Food Banks data](https://docs.google.com/spreadsheets/d/1gfOMO2hE7KMb1lE7e9YKVpDVm0taH_0C9uIxy3KfZkM/edit#gid=0) to Open Street Maps |  Questions?  [@JRHutson](https://github.com/JRHutson) |

# Want more help on these tasks? 

- [ ] **OSM Updates:** `[ONGOING]` 
- [ ] **Data Gathering:** `[ONGOING]` Relevant data for the MaptimeLA Food Bank Data Night is currently being compiled in this repo. Requests for assistance with this process can be found under issues along with questions that we are hoping to answer with the data. If you have or can get data that should be a part of this repo, create a branch to add it. If you have a question that would be interesting to apply this data to, open an issue for it. If you are really interested by one of the questions posed, post a comment and start brainstorming how to address it. Ideally geographic data should be in both Shapefile and GeoJSON formats as well as WGS 1894 State Plane Zone V projection.

# Data brainstorming and checklist:
Datasets are starting to be assembled in the data folder of this repo. If you want to contribute data, try to get it condensed to an extent that will be relevant to the project before uploading. (Generally LA County is ideal) If you are not familiar with how to do this, upload what you have and submit an issue for it to be clipped. For shapfiles, stick to the WGS 1894 State Plane Zone V projection. This is the standard projection used by LA County and will avoid future conflicts when working with the data. 

# Have questions? Ideas? Open an Issue or submit a suggestion through our Google Form.
https://docs.google.com/forms/d/1IKmcIz4dVsqnK0WavEZo-gWiQZzdLaIjukiFouhPPUA/viewform?usp=send_form

# How to add Food Banks on OpenStreetMap:
1. Request access to the Google Sheet so you can let others know a Food Pantry has been added to OSM.
2. There is also a column in the [Google Spreadsheet](https://docs.google.com/spreadsheets/d/1gfOMO2hE7KMb1lE7e9YKVpDVm0taH_0C9uIxy3KfZkM/edit#gid=0) indicating whether the Food Pantry has been added to Open Street Map. Please request access and update the sheet so others know a pantry has been added. 
3. **Category**: OSM already has a `category` for `food bank`. Many are housed in `churches` and `community centers`, so be sure to distinguish between the organization and the food pantry in how you name the point added to the map. 
4. **Contact Number and Hours**: Be sure to add the `contact number` and `hours` to the point as well.
5. **Commit notes**: Include `#Maptime` and `#MaptimeLA` in your commit notes. 


# Contact 
- Project Lead: [@JRHutson](https://github.com/JRHutson)
