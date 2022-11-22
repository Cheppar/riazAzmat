# RiazAzmat Telcom App

A drag and drop telcom application

## Project Proposal
Hey Azmat this is an outline of how I want to achieve tasks under a time frame.

### Outline

| Task           |  Time Frame     |Specifics | Budget |
| -------------  |  -------------  |------    | ----------------|
| UI Features        |  1 week | Build a simple tool  | $800 |
| Portal and Backend  | 1 week  |  User management platform | $800|

#### Detailed Project Execution

##### UI features and capabilities
- Create a simple UI with a map base layer (Google, OSM or Bing Maps).
- Load pin capability from excel file and plot elaborate route using Leaflet routing.
- Enable user (team member) to change route and provide correct feedback.
- Create a simple sidebar to provide updates on the analysis of the rooute.
- When route create the map must fit bounds (zoom to the map route area).
- Have a simple search bar to search nearby landmarks.
- To analyse a route based on the team member movement on the map (planned route, completed and remaining route).
- Enable map sharing between team members
- Provide offline capability. 
- Have a comparison of previous and post routes.

##### Live Tracking Features
- To attain this, we can simply use the device location. 
- or, get data from an API of a car tracking device that provides information regarding the location of the car and team.


##### Dashboard
- From the slides, the dashboard will have a primary screen that will enable the admin to see
  - Weekly progress 
  - Overall progress
  - Management of the  teams 
  - Completed clusters
  
- The dashboard will be simple and easy to navigate.

##### Tech Stack
-  The UI will be created using JS, LeafletJs/Mapbox for the mapping library.
-  The backend will be PHP or NodeJs
-  A simple postGIS enabled postgreSQL to support spatial queries.
-  ReactJS for the user interface.



