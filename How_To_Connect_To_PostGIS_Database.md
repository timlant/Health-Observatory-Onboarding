PostGIS Database Connection
================

**To connect to PostGIS database in QGIS:**

**1.** Connect to **sslvpn.asu.edu** VPN in **CISCO AnyConnect** on your
computer (on how to connect to CISCO see CISCO AnyConnect tutorial):

<img src="CISCO.JPG" width="562" />

**2.** In QGIS app **Browser** window on the left, right click on
**PostGIS**, select **New Connection**:

<img src="PostGIS_1.JPG" width="322" />

**3.** “**Create a New PostGIS Connection**” pops up. Enter the
following Connection Information:

    Name: postgis.rc.asu.edu
    Host: postgis.rc.asu.edu
    Port: 5432
    Database: enter the name of the database (“census” in the example below)

<img src="PostGIS_2.JPG" width="493" />

Click **OK**.

**4.** If authentication window pops up, enter your **ASU login** and
password **coda**.

**5.** Click on **Database**, **DB Manager**:

<img src="PostGIS_3.PNG" width="707" />

**6.** Click on **PostGIS** dropdown arrow to verify the connection:

<img src="PostGIS_4.JPG" width="926" />
