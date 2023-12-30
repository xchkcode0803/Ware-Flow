# Ware-Flow

## Overview
Ware Flow is a Full-Stack web app with role-based access for managing and tracking warehouse operations. This full stack web app is written in Vue.js for the front end, while using Java Springboot to handle CRUD operations with a MySQL database hosted on AWS RDS. 

## Functionalities 
This software provides the following functionalities: 
- Role-based access to different content. Different roles with different authorizations can view/modify different content in the web app.
- Record keeping of all the transactions happening across all of the warehouses.
- Security: This system uses JWT token for sign-in authorizations. 
- Item management: Manager has the ability to categorize and assign goods to different warehouses. Manager can also look up certain goods using keyword search.
- User management: Super manager has the ability to add/drop accounts having access to the warehouse management system and edit each account's authorization level.
- Highly customizable: With some small tweaks to the front-end, this warehouse management system can be easily changed to many other management systems! 

### Role-based access 
There are three levels of authorization to this management system: 
- Super Manager: super manager can add/drop normal managers to the system + get access to all of the users, categories, goods, and warehouses present on the system.There is only 1 super manager allowed per system.
![image](https://github.com/xchkcode0803/Ware-Flow/assets/109048196/cffffdea-9ccd-4104-8e29-861938ff81d8)

- Normal manager: normal managers has access to all of the users, categories, goods, and warehouses present on the system. Normal managers can also add/drop normal users to the system.
![image](https://github.com/xchkcode0803/Ware-Flow/assets/109048196/40a16c8f-5b84-4243-b919-d9e4c2aa0467)

- Normal user: normal users can view/edit all of the items on the system and they can also get an overview of the transaction records happening within the system. 




### Record keeping
As shown below, there's a search bar with autocomplete that allows user to look for specific places of interest. All places with a matching name will be highlighted on the map once a place name is entered. 


https://github.com/xchkcode0803/UExplore/assets/109048196/c4046182-d2c1-497c-8611-3aec014d86e1



### Transportation networks 
User can choose to display a specific transportation network on the map by selecting one of the options from the drop down menu. For subway and bus networks, the station names will only be displayed once zoomed in to avoid visual clutters. 



https://github.com/xchkcode0803/UExplore/assets/109048196/3f613151-3110-4986-95d6-04931fe06422



https://github.com/xchkcode0803/UExplore/assets/109048196/ce931783-4caa-4a47-b29d-8c22a9cee1e3


https://github.com/xchkcode0803/UExplore/assets/109048196/d30cb81c-b0ca-4a2d-b86a-29f840401f0c




### Short-cut display buttons 
On the top of the home window, user can click on any of the four buttons to display types of places on the map. User can click on "Clear POI" to clear out the places being displayed on the map. The place's name will be displayed on a pop up window once clicking on the icon. 


https://github.com/xchkcode0803/UExplore/assets/109048196/3f22af82-4cf4-4888-ad04-4533be1730f1


### Path-finding
UExplore can find the fastest driving path between any two intersections on the map considering the speed limit of each street segment and a 15 seconds penalty spent on each turn of the streets. User can perform the path-finding by following these steps: 

1. Click on "Direction" located on the bottom left of the home page. This will take the user to a seperate interface


https://github.com/xchkcode0803/UExplore/assets/109048196/f7d0f316-53bc-48bb-ae5f-73e74204ddd6


3. Enter two intersections by entering the corresponding street names (two street names for one intersection) or by clicking on any two intersections on a map (This auto fills the intersection entry boxes)

4. Click on "Search directions". A path will be displayed along with a detailed driving instruction. Arrows showing the driving direction will be displayed once zoomed in. User can also follow along the path by clicking on "next", which will take the user through each of the turning point along the path. 


https://github.com/xchkcode0803/UExplore/assets/109048196/175035ae-b13b-4fc1-ac67-df0a325d4282
















