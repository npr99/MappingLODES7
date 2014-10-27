MappingLODES7
=============

Code written for SAS to import, aggregate, and process the LODES 7 Database.

Still under construction.

I have included the draft code for SAS.

The entire LODES 7 Database can be downloaded using the  LEHD_LODES7_bulkDownload at https://github.com/npr99/LEHD_LODES7_bulkDownload


-- OR --

Individual files can be downloaded from
http://lehd.ces.census.gov/data/#lodes

The programs are based on the file structure created by running the LODES 7 Bulkdownload.

-- Program Order --

1. ReadandSumLODES
- ImportLodes7
- AddCentroidsLodes7
- SF_All_Macro_NPR_20105yr
- SF_20105yr_CensusTractPoverty
- MappingLODESwithPoverty

-- Mapping Files --

All maps can be created using QGIS "Free and Open Source Geographic Information System"
http://www.qgis.org/en/site/

-- References --

U.S. Census Bureau. 2013. LODES Data. Longitudinal-Employer Household Dynamics Program. http://lehd.ces.census.gov/applications/help/onthemap.html

Quantum GIS Development Team (2014). Quantum GIS Geographic Information System. Open Source Geospatial Foundation Project. http://qgis.osgeo.org
