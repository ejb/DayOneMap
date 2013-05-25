## Create a map from your Day One entries 

DayOne map is a template for [dayone_export](https://github.com/nathangrigg/dayone_export) that produces a interactive [OpenStreetMap](http://www.openstreetmap.org)-powered map using [Leaflet](http://leafletjs.com) from your [Day One](http://dayoneapp.com) entries.

Using it is super-simple, as long as you have a basic grasp of the command line. With dayone_export installed on your computer, enter the following in Terminal to build the map in the current directory:

    dayone_export --output map.htm ~/Dropbox/Apps/Day\ One/Journal.dayone --template-dir . --template map.htm
    
To include photos, make sure to copy the `photos` folder from `Journal.dayone` into the current directory.

This is the result of just a few hours' work so far - definitely a work in progress. I would post a demo, but I'm not too keen on sharing my personal diary with the rest of the world...