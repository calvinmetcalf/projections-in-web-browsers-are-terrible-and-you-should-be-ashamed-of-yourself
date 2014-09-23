http://calvinmetcalf.github.io/projections-in-web-browsers-are-terrible-and-you-should-be-ashamed-of-yourself

*projections* in web browsers are *terrible*

and you should be *ashamed* of yourself

my name is *calvin*

i have *opinions*

you might remember me from:

my previous presentation 'things you've never heard of not fully explained'

the new version of proj4js that isn't *terrible*

and leaflet plugins for file formats that shouldn't be used on the web

but first

*apologies* in *advanced* to non-coastal states

im not talking about *your* state

i'm talking about that state *next to your state* that you don't really like

*what is a projection*

when people say projections, they usually mean a

*spatial reference system*

which includes

a *spheroid* or model of the earths shape

a *datum* which are reference points to measure from on the sphere

a *coordinate* reference system with units and and starting points

if it's projected

a *transform* to flatten it

(for the sticklers

when i refer to *wgs84* as a projection

pretend i'm saying *plate carrée* instead)

*background*

math is hard

if you don't have a computer

esp trig, and logs

so traditionally reprojection is *hard*

so an agency picks a projection and does EVERYTHING in that one

e.g. (when I was at *MassDOT* we used *Massachusetts Mainland Meters NAD83*)

this is great

if printers are the main way that data is transfered

desktop GIS software is built around this idea

there are assumptions that projections rarely change

and are never to be mixed because

*TRIG!!!!1*

fast forward to now

my cellphone is *literally* a supercomputer

my desktop runs other computers inside itself like the *matrix*

the *interweb* exists

and everyone has their own projection

*124* in the state plane system

with a version for *feet* and *meters*

and versions in the *data* (plural of *datum*) *NAD27*, *NAD83*

plus in addition to original *NAD83* we have *HARN* and *NSRS2007* variants

= *992* systems

this is just *'murica*

this is *terrible*

*nobody* cares about your flyover state plane projection

*nobody*

if somebody gives you data that is projected tell them they are *terrible*

do you need *precision* that you can't get with *doubles* & *WGS84*

and you have the *accuracy* that it matters?

if not then if you don't use WGS84 Lat Lngs I hate you.

these are *cargo cult projections*

projections are confusing and complex on the desktop

but on the web they are unworkable

self documenting data is *folly*

there is a long tail of *crazy*

the epsg database is far too big

there are 3 different notations for specifying projections

none of which are consistent

storage and interchange are different

we don't leak database indexing details when we share data

geojson removed *crs* support 

this is *not terrible*

kml was always wgs84 only

kml is *terrible* for unrelated reasons

but all this makes us forget

projections *actually* serve a purpose

\*wax poetic about Mike Bostock\*
  
web mercator doesn't work for everyone

no i'm not talking about flyover state plane

*Scandinavia*

*McMurdo*

adaptive composite projections

go forth and be less terrible

http://calvinmetcalf.github.io/projections-in-web-browsers-are-terrible-and-you-should-be-ashamed-of-yourself
