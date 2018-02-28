# Basemap-Tutorial-QT-Creator-
<h2>This tutorial will help you change the basemap of a app using QT Creator in App Studio</h2>

<h2> Step 1: Create the app</h2>

a) Begin by starting AppStudio 

b) In the top right corner select "New App" 

c) From the menu you have a few options, it is recommened to pick a app from the samples, for this example select "Find a Route"

<h2> Step 2: Become familiar</h2> 

a) Right click on your new app and select "Run" 

b) Take a moment to become familar with the app and see what it has to offer

<h2> Step 3: Open up the editor</h2> 

a) Right click on the app and select "Edit in Qt Editor" 

b) This opens up a editor and shows a QML file for your app labeled as "MyApp.qml"

<h2> Step 4: Changing the basemap 

a) Scroll down in the QML file code and find the section under "Map" listed as "Basemap"

b) We will be changing the "ArcGISVectorTiledLayer"

c) Currently the basemap is "World Navigation Map" we want to switch it to a darker one

d) Change the vector url to "http://www.arcgis.com/home/item.html?id=dcbbba0edf094eaa81af19298b9c6247"

```
Map {
                    Basemap {
                        ArcGISVectorTiledLayer {
                            url: "http://www.arcgis.com/home/item.html?id=dcbbba0edf094eaa81af19298b9c6247"
                        }
                    }
```

<h2> Saving </h2>
