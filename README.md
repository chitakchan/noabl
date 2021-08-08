# noabl

objective:  allow use of noabl data for appreciation of potential in wind resource across uk

deliverables:   a list of files in ersi ascii raster format allow import by gis application, such as qgis

If you are like me using qgis, in order to import the raster file, say speed45raster.asc to qgis, follow the following procedure:

1.  make sure the gis is using the correct coordinate system (crs).  The ersi grid raster file do not contain mapping reference data and is xy coordinate in the raster file is base on the Ordnance Survey System for British National Grid (OSGB).  Hence make sure the gis is using OSGB, which authority ID is EPSG:27700.

2. add layer
Layer --> Add Layer --> Add Raster Layer --> 
under source/raster dataset(s), enter path/file name for the raster file say Speed45Raster.asc --> Add

3. after the layer is added, right click the layer --> Property --> Symbology --> Band Rendering.  Under band rendering, I choose singleband pseudocolor for rendering type and choose five colours for each  range of wind speed.  below is the outcome of the wind speed raster, juxtaimposed with wind farm locations in Scotland:

![image](https://user-images.githubusercontent.com/20920121/128647029-bb1244da-3420-4d9e-aef8-70be26336f6e.png)
 
-- END --




