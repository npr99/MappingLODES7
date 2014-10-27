MappingLODES7
=============

Code written for SAS to import, aggregate, and process the LODES 7 Database.

Still under construction.

I have included the draft code for SAS.

The entire LODES 7 Database can be downloaded using the  LEHD_LODES7_bulkDownload at https://github.com/npr99/LEHD_LODES7_bulkDownload


-- OR --

Individual files can be downloaded from
http://lehd.ces.census.gov/data/#lodes
U.S. Census Bureau. 2013. LODES Data. Longitudinal-Employer Household Dynamics Program. http://lehd.ces.census.gov/applications/help/onthemap.html

The programs are based on the file structure created by running the LODES 7 Bulkdownload.

-- Program Order
1. ImportLodes7
- Includes ReadandSumLODES
2. AddCentroidsLodes7
3. SF_All_Macro_NPR_20105yr
4. SF_20105yr_CensusTractPoverty
5. MappingLODESwithPoverty
