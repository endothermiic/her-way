# HerWay
With more than half of women reporting that they feel unsafe while traveling at night, HerWay is a mapping application designed specifically to help women get home both quickly and safely. It was created in C++ using data from OpenStreetMap (OSM) database with a graphical user interface (GUI) built with setups and callbacks from [GTK](https://docs.gtk.org/) and styled using the [EZGL](https://ug251.eecg.utoronto.ca/ece297s/ezgl_doc/index.html) library and traditional CSS.

Note: This map was created for Software Design and Communication (ECE297) at the University of Toronto. As such, all code is in a separate, private repository to avoid plagarism and is available upon request. A copy of the slides used for the final presentation is externally available [here](https://docs.google.com/presentation/d/1rBmUW8rLhqVlzK6LNSPRxFUlWmQcqsgYzBfIrxKKGQI/edit?usp=sharing) or within the repository as a pdf under `team028-pitch.pdf`.

# Notable features
The map contains several key GUI features (detailed below) that allow users to quickly and easily navigate throughout a given city. 

## Well-lit streets
HerWay highlights streets with the well-lit OSM tag in bright yellow when the map is used in dark mode. 
![well-lit](media/well-lit.png)

## POIs 
When the crisis ("!") button is clicked, HerWay selectively displays important POIs (shelters, healthcare facilities and police/emergency services), regardless of zoom level. However, when unclicked, POIs are displayed only when sufficiently zoomed in, and a wider array are displayed using OSM icons. POI names are visible in the status bar when hovered over.
![POIs](media/poi.gif)

## Public transit
![transit](media/transit.gif)

## Searching methods

## Wayfinding modifications 

# Algorithmic complexity 

## Dijkstra 

## Traveling Courier 