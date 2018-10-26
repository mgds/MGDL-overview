# Overview of MGDS Repositories

Marine Geoscience Data System began development in 2004. Code repositories include both back-end and front-end code components that are used for data curation and ingestion as well as data discovery, access and download. At present, much of this code is in private repositories to ensure security of our systems.


Repositories include:
- [GMRTMapTool](https://github.com/mgds/gmrtMapTool) - front-end code for driving the [GMRT MapTool](https://www.gmrt.org)
- [ASP-IntegratedMap](https://github.com/mgds/ASP-IntegratedMap) - front-end code for driving the map-based data discovery tool for the Academic Seismic Portal.
- [home_mgds_local](https://github.com/mgds/home_mgds_local) - a *private* repository that includes line command code for data ingestion and verification, as well as crons that validate database integrity.  This code was developed over the past decade and a half and public distribution was not part of the design spec.  Making this content publicly accessible poses potential security risks to our system.
- [marine-geo.org](https://github.com/mgds/marine-geo.org) - a *private* repository that includes front-end code for data discovery, access and download. Most of the functionality contained in this repository can be accessed directly through the web, but since the code was developed over the past decade and a half and public distribution was not part of the design spec, it has not been made fully publicly accessible. 
