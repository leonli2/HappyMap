# Happy Map
Worked in a team of 3 to develop a large scale city mapping software (similar to Google Maps) in C++.

# Note
Since this is a project for Software Communication and Design at the University of Toronto, the source code cannot be shared due to Academic Integrity reasons.

# Application
![main pic](https://user-images.githubusercontent.com/112602959/197061947-8e8c910e-070a-4ea1-baa3-25fe529f3a7b.png)

# Background
• Geographical data such as streets and points of interest were queried with an API from the OSM (OpenStreetMap) database.<br/>
• STL data structures (e.g. vectors) were used to the enhance speed of the API.<br/>
• The EZGL graphics library was used to visualize the map and its features.<br/>
• The GTK graphics package was used to build the user interface.<br/>
• The path finding utilized Dijkstra's and A* algorithm to optimally find the shortest path and the directions that should be taken.<br/>

# Features

### Autocompletion
Search results for streets will autocomplete based on what the user typed.

![image](https://user-images.githubusercontent.com/112602959/197062963-8ef35811-39b5-4b19-aca0-db7853fcdc98.png)

### Reload Map
Allows the user to switch the current city of the map.

![image](https://user-images.githubusercontent.com/112602959/197063303-900af3ba-0c8e-4040-9757-19f02d5758c0.png)

### Show Features
Allows the user to toggle on or off icons showing subway locations and/or points of interest (e.g. restaurants, gas stations, schools).

![image](https://user-images.githubusercontent.com/112602959/197063661-3c05372e-d79e-4043-96a8-0aa4c2510edd.png)

### Search for Intersections
Allows the user to click on the map to find the streets that make up an intersection. The intersection closest to the mouse on the map when clicked will appear as a red square and its name will be listed under the map.

![image](https://user-images.githubusercontent.com/112602959/197064046-cb8c5929-9306-4b51-9911-84d5cda5a2fd.png)

### Search for Points of Interests
Allows the user to click on the map to find the names of points of interest. The point of interest closest to the mouse on the map when clicked will have its name appear above it and it will also be listed under the map.
![image](https://user-images.githubusercontent.com/112602959/197064713-c5fddea4-d8a1-4a1b-9975-85b40793f841.png)

### Common Intersection
Allows the user to type in two streets and find their common intersections (if there are any). Intersections will appear as red squares.

![image](https://user-images.githubusercontent.com/112602959/197065553-97f5583e-42bb-4413-9240-4d618a797f6e.png)

### Path Searching
Allows the user to find the best path between two intersections. The intersecions can be inputted by their street names or by clicking on the map directly.

![image](https://user-images.githubusercontent.com/112602959/197065955-261141ee-8d55-4990-99ba-c4ef7a207882.png)

After pressing "OK", the best path will be calculated and shown in turquoise. The intersections and street names will also be displayed. Additionally, the directions and distances to walk from the starting to end intersection, along with the estimated walking time, will be printed. 
![image](https://user-images.githubusercontent.com/112602959/197066465-6580cef4-9041-419a-9f86-76f211725d71.png)

### Dark Mode
Changes the map colours to be dark.

![image](https://user-images.githubusercontent.com/112602959/197067135-ee143ecf-3a16-4227-91eb-4d9b12810268.png)
