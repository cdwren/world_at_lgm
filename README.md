# world_at_lgm
I just made this map one afternoon to go on my office wall. 

![worldatlgm](https://github.com/cdwren/world_at_lgm/blob/master/world_at_LGM_EE_100dpi.png "World at LGM")

I used global elevation data plus bathymetry from (specifically the single topo30.grd file): Becker, J. J., D. T. Sandwell, W. H. F. Smith, J. Braud, B. Binder, J. Depner, D. Fabre, J. Factor, S. Ingalls, S-H. Kim, R. Ladner, K. Marks, S. Nelson, A. Pharaoh, R. Trimmer, J. Von Rosenberg, G. Wallace, P. Weatherall., Global Bathymetry and Elevation Data at 30 Arc Seconds Resolution: SRTM30_PLUS, Marine Geodesy, 32:4, 355-371, 2009. https://topex.ucsd.edu/WWW_html/srtm30_plus.html

Ice data came from: Ehlers, J., Gibbard, P. L., & Hughes, P. D. (2011). Quaternary glaciations - extent and chronology: A closer look. Amsterdam: Elsevier. http://crc806db.uni-koeln.de/layer/show/6

I tossed it together in QGIS by making three copies of the topo30 layer, one for ocean colour, one for land color (palette roughly stolen from https://i.stack.imgur.com/xJOJV.jpg), and one for hillshade. The original data was longitude 0 - 360, so I reprojected to a custom Equal Earth projection string "+proj=eqearth +datum=WGS84 +wktext" taken from here: https://www.gislounge.com/how-to-use-the-equal-earth-projection-using-qgis-on-the-mac/. Actually I had to reproject into something else first, then from that to Equal Earth to center it on 0 longitude.




