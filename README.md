
# TRASSE - Trajectory and Relief ASsessment in Single Engine

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martialpohin/trasse/main?labpath=notebook%2Ftrasse.ipynb)
[![Pages](https://img.shields.io/badge/launch-pages-green)](https://martialpohin.github.io/trasse/)


TRASSE is a tool build for pedagogic aspect only. It is freely inspired from ["Getting to grips with Aircraft Performance"](https://skybrary.aero/sites/default/files/bookshelf/2263.pdf).

It must not be used for any other objectives than for learning objectives. 

It can be used using mybinder.org.


## Manual

* To come later.

## Limitations

* 35ft is at end of the runway
* No possible turn before 50ft
* Turn climb gradient is null
* Acceleration during turn is null
* Turn is max bank angle without transition


* Some main significant points are processed as turns, and not as "vertical" points.

## ToDo

* Straight trajectory analysis
* Plot selector
* Net flight path
* Obstacle reports
* Start from any points
* MCT point
* Result files downloader

## Bibliography



* ["Getting to grips with Aircraft Performance"](https://skybrary.aero/sites/default/files/bookshelf/2263.pdf) 
* ["Introduction to EOSID"](http://eosid.blogspot.com/2012/02/introduction-to-eosid.html) 
* ["EOSID Requirements"](http://eosid.blogspot.com/2012/02/eosid-requirements.html) 
* ["EOSID Methods of Analysis"](http://eosid.blogspot.com/2012/02/eosid-methods-of-analysis.html) 
* ["VNKT - Kathmandu Airport EOSID Design"](http://eosid.blogspot.com/2012/02/vnkt-kathmandu-airport-eosid-design.html)
* ["Large Aircraft Takeoff Path Optimization out of Terrain - Challenging Airports"](http://unsworks.unsw.edu.au/fapi/datastream/unsworks:43217/SOURCE02?view=true)  
* [ "Is Engine Failure on the Runway at Takeoff the most limiting case ?"](http://unsworks.unsw.edu.au/fapi/datastream/unsworks:13455/bin7c06f1ce-28d5-4ed3-9db5-e6fa5b02c647?view=true)
* ["One engine out takeoff trajectory optimization"](https://arc.aiaa.org/doi/10.2514/6.2010-9013) 
* ["IMPROVE PAYLOAD and COMMERCIAL OPERATIONS WHILE COMPLYING WITH FLIGHT SAFETY REGULATIONS"](https://www.linkedin.com/pulse/improve-payload-commercial-operations-while-complying-bruno-ramioulle) 

## Data source

* [Runway database](https://ourairports.com/data/)
* [SRTM download](https://srtm.csi.cgiar.org/srtmdata/)


## Dependencies

* [ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/index.html)
* [ipywidgets](https://ipywidgets.readthedocs.io/en/latest/)
* [pyproj](https://pyproj4.github.io/pyproj/stable/)
* [Aerocalc3](https://geoffreynyaga.github.io/aerocalc/)
* [FileLink](https://skeptric.com/jupyter-download/)