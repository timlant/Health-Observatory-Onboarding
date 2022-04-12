PostGIS Database Connection
================

**To connect to PostGIS database in QGIS:**

**1.** Connect to **sslvpn.asu.edu** VPN in **CISCO AnyConnect** on your
computer (on how to connect to CISCO see CISCO AnyConnect tutorial):


![CISCO](https://user-images.githubusercontent.com/65433392/159146455-6af540ac-be7a-4886-b18e-ae9361f86095.png)


**2.** In QGIS app **Browser** window on the left, right click on
**PostGIS**, select **New Connection**:


![PostGIS_1](https://user-images.githubusercontent.com/65433392/159146468-dea466e2-91b9-42d3-bf0d-ced31992e923.jpg)


**3.** “**Create a New PostGIS Connection**” pops up. Enter the
following Connection Information:

    Name: postgis.rc.asu.edu
    Host: postgis.rc.asu.edu
    Port: 5432
    Database: enter the name of the database (“census” in the example below)


![PostGIS_2](https://user-images.githubusercontent.com/65433392/159146471-84916978-f4ac-48bc-aecd-4c6e1f1170fe.jpg)

Click **OK**.


**4.** If authentication window pops up, enter your **ASU login** and
password **coda**.  Note: this requires that you have an account on the database system.  If you do not know if you have been added to the database system yet, contact Tim Lant or another project lead.  Accounts on the postgis.rc.asu.edu system are managed (authorized, approved, and provisioned) by the project team on a group role basis and not Research Computing.  


**5.** Click on **Database**, **DB Manager**:


![PostGIS_3](https://user-images.githubusercontent.com/65433392/159146473-4040e5a9-6847-429d-ad76-64a535e610f2.png)


**6.** Click on **PostGIS** dropdown arrow to verify the connection:


![PostGIS_4](https://user-images.githubusercontent.com/65433392/159146476-4ccaf054-7ff5-4d07-b1ad-01b7d6fa9894.jpg)
