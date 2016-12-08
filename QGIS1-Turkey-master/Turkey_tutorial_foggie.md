[Turkish Flag](https://upload.wikimedia.org/wikipedia/commons/8/87/Flag_of_Turkey.png)
# Turkey-Tutorial
### Author: achmed.foggie@mavs.uta.edu
## QGIS Tutorial (Turkey)
##Additions by Lauren

## 1 Create a folder (also known as a directory) and name it “Turkey” on your desktop. (Right click on an empty area of your desktop, select new, and then folder)
## 2 Download the following Turkey data sets from http://www.diva-gis.org/gdata!: Administrative Areas, Roads, and save them into the directory "Turkey" that you just created.
* Next, Unzip the downloaded files; each should be in its own sub-directory (or folder).
* TUR_adm
*  TUR_rds

## 3 Open QGIS and select a new project.
* Select project, and then new, or press Ctrl+N
## 4 CRS


![CRS Screenshot](/CRS Screenshot.png)


* Select the settings tab , then select options
* In the new window select CRS on the side of the window (or press Ctrl+shift+p while on the main screen)
* Enable on the fly
* Select the globe icon on the right
* Type "WGS 84", then select WGS 84/UTM zone 39N

## 5 Add a layer
* First click the layer tab at the top of the screen then Add Layer.
* Select Add Vector Layer
* Select browse, then select TUR_adm0.shp (Make sure you select the file with the .shp format)
* On the left side of the screen in the layers panel select right click on TUR_admin0
* Select style, simple fill and then under fill style select no brush
* Press OK

## 6 Repeat the previous steps from step 5 but instead using the TUR_admin1.shp file

![Layers Screenshot](/Layers Screenshot.png)

## 7 Add the TUR_roads layer
* Right click on the layer in the layer panel
* Go to Properties the select the style tab
* Change the color to make it easier to see
* Change the width to 1.00000

## 8 Add Maps
* Select the Layer tab, then select "Add Raster Layer"
* Select Turkey Map 1.0 (I have already geo-referenced this file.)
* Move the TUR_admin0 and TUR_admin1 layers up in the box on the left so that they are visible on the QGIS screen.
* Repeat steps for Turkey Map 2

    Save your work. Close QGIS
