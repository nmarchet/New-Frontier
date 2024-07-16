---
title: Map | Meredosia Continent with Local Trade Routes (Interactive)
draft: false
tags:
  - map
  - locations
---
 ```leaflet  
### id must be unique  
id: Whakatāne  
### Lock pins so they can't be moved  
lock: true  
### If true, view of map will recenter as you zoom out.  
recenter: true  
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work.  
noScrollZoom: false  
image: [[meredosia-continent.jpg]]  
### Map Pixel Height x 1 / (Pixels between Bar Scale / 1000)  
### Map Pixel Width x 1 / (Pixels between Bar Scale / 1000)  
### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit.  
### Bounds is entered as [Height, Width]  
bounds: [[0,0], [416.6667, 550]]  
height: 508px  
width: 95%  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 208.3333  
long: 275  
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: 0.1875  
### Max zoom is 18.  
maxZoom: 2.5  
### Hover mouse over the Reset Zoom icon to see your current zoom level.  
defaultZoom: 0.1875  
### How far it zooms in or out with each step. Can be in decimals.  
zoomDelta: 0.5  
### This is a string so can be any text. Change it to match your maps measurement scale.  
unit: miles  
scale: 10
darkMode: false  
```