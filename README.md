# svrwx-plotly
Make interactive maps of severe weather reports with plotly & python

This python code is used to plot severe weather reports (hail, wind, tornadoes) in an interactive manner. In this example, the data are limited to Colorado; see the map at: http://climate.colostate.edu/severe_storms.html.  But this could easily be modified to other states or regions, or even the entire continental US (but this renders *very* slowly). 

You can hover your mouse over a particular report to see the date and magnitude of the report, and turn on/off severe weather types.

Data come from the Storm Prediction Center at https://www.spc.noaa.gov/wcm/#data. Colorado-specific CSVs needed to run the code are included in this repo.

Python dependencies include plotly, pandas, numpy, and json. This code is written assuming you have a (free) mapbox token for displaying background maps, but there are other map options you can use without a token (see https://plotly.com/python/mapbox-layers/).

I've also added county boundaries via a geojson file - if you're plotting for a different state or the US you'll need to track down such a file, for example here: https://eric.clst.org/tech/usgeojson/


