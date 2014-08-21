*GIS* in *NODE.JS*

hi

my name is *calvin*

[@cwmma](https://twitter.com/CWMma)

[calvinmetcalf.com](http://calvinmetcalf.com)

what is *node*?

in *python* terms

not *django*

not *flask*

*node* is equivalent to *python*

language

run time/vm

standard library

(bring your own batteries)

((except package manager))

yes but why?

'concurent'

i'm not going to wait, call me back

good for iobound stuff

like servers

or http requests

or reading files

*who*

*mapbox*

tilemill

turf

*the new york times*

topojson

d3

*esri*

koop

*appgeo*

(thats my company)

*what*

*geojson*

The last worst geospatial format

except for all the others

more from raj latter

*topojson*

lossy compaction for geojson

perfect for web maps

horrible python port

spec!

*streams*

long pipelines of operations

where only a small part is in memory

especially good with geojson

can be put into postgis, gme, esri

soon to be standardized into the web

used for

geocoding with massgis several hundred thousand addresses

upload all tiles from mbtiles to d3/google cloud storage

*turf*

![](https://www.mapbox.com/img/team/morgan.jpg) by morgan herlocker

less horrible version of JavaScript Topology Suite

things like

buffer

centroid

convex

is-clockwise

jenks

*tile mill*

make web maps

that aren't ugly

nothing compares

also vector tiles

*game utilities*

spatial isn't special

path finding === routing

hit detection is just comparing 2 bboxen

*related*

sometimes you don't need 'real gis'

like if it's only points

*seriously* just use a geohash

because you can do that with leveldb

but that is a different talk

FIN