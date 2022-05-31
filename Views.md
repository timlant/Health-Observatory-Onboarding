pgAdmin Vews For Mapping in QGIS
================
Anna Gaylord
2022-05-30

Views are virtual tables that can be mapped in QGIS just like regular
tables. Views for 2019 American Community Survey demographic data
(acs_2019_snap_w\_geography), and for SNAP and races demography
(snap_demography_races) currently exist in Census database, Public
schema, Views:

![](view.JPG)<!-- -->

The steps for using views in QGIS are the following:

**1.** (Connect to Cisco AnyConnect before proceeding) In QGIS, click on
**Database** to open **DB Manager**.

**2.** In DB Manager window, click **PostGIS**, **postgis.rc.asu.edu**:

![](view1.JPG)<!-- -->

**3.** In **Enter Credentials** window, enter your login and password,
hit **OK**:

![](view2.JPG)<!-- -->

**4.** Click on **public** dropdown, all Views will be listed as layers
among other available objects:

![](view3.JPG)<!-- -->

**5.** Right click on the view layer you need and click on **Add to
Canvas**. Close DB Manager window. **6.** The table is mapped and is
ready to be symbolized!

![](view4.JPG)<!-- -->
