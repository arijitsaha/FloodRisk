# FloodFill
Study &amp; assessment of probable impact of catastrophic flood events to manage flood risk with a first order flood-fill model developed using Python geospatial libraries

### Description
Flooding is one of the most common and devastating natural disasters which affects nearly every population on the globe. An increase in extreme flood events in recent years, has caused massive property damages, economic losses and casualty. Regional ecological challenges coupled with climatic variability are noted to aggravate flood risks and impact on affected communities.

The conventional way of managing flood risk is by using complex GIS & Hydraulic models. Such models has the overhead of large, multipurpose geospatial tools & frameworks and not being very cost-effective for wider adoption.

With advances in remote sensing & availability of high quality geospatial data; computing power getting cheaper & handling big data getting easier, the new direction is to develop flood risk models using powerful geospatial libraries available in open source languages like Python, R.

In this project, an exploratory approach is taken to analyse the topography of the terrain of Bengaluru district, India through a descriptive study of the terrain elevation using Digital Elevation Models (DEM). DEM is 2D/3D representation of a terrain's surface, created from terrain elevation data. A first order flood-inundation model is then used to identify areas that will be impacted due to overflow of a water body in the terrain. An example of identifying the various elevation zones is then shown using clustering.

Some of the geospatial libraries used in this project
 - GeoSpatial Data Abstraction Library (GDAL) : Translator library for raster and vector geospatial data, released under an X/MIT style Open Source license by the Open Source Geospatial Foundation. The GDAL/OGR Python bindings has been used extensively for reading & processing digital elevation model (DEM) rasters.
 - PyDEM : Python (with a bit of Cython) package for topographic analysis 
 - Other Python packages like numpy, pandas, scikit-learn, seaborn, matplotlib etc.
