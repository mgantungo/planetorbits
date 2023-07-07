# satelliteorbits
Purpose
A simulation on how satellites move within a given orbit. Four satellites namely ug_soil, ug_security, ug_weather, and ug_season are placed within in their respective orbits. 

ug_security is responsible for monitoring security around the country and as such must move at a speed slow enough to keep focus on the country. I will therefore be the slowest satellite. It will be assigned a rotation period of 19 points.

ug_soil is responsible for analyzing agricultural activities undertaken on the country's soil, determining productivity, and helping in coming up with better soil use for the respective country zones it will be assigned a rotation period of 15 points.

ug_security and ug_soil will move in the same orbital space 

ug_weather is responsible for analyzing and providing accurate weather forecasts and also triggering any flood and landslide warnings/alarms. It is, also, supposed to compare weather conditions in other parts of the world. It is assigned a rotation period of 5 points.

ug_season is responsible for determining any season changes and making comparisons on seasons in other countries. This data is designed to help predict crops to grow for export. It is assigned a rotation period of 9 points.

Installation:

To view this simulation, all you need is to launch the HTML file in a web browser preferably Firefox and Chrome. All development has been done in HTML, CSS and Javascript and there is no single external included file in the code. All the application source code has been placed in one single file

To make a visually appealing simulation, the speed on the satellites shall be modified by a factor of 1000 to turn the rotation period to milliseconds.


Reference: 
1. https://en.wikipedia.org/wiki/semi-major_and_semi-minor_axes
2. https://www.physicsclassroom.com/class/circles/Lesson-4/Mathematics-of-satellite-Motion
3. https://developer.electricimp.com/squirrel/math/cos
4. https://www.w3schools.com/jsref/canvas_arc.asp
5. https://www.javascripttutorial.net/web-apis/javascript-arc/
