# Overview of MGDL Repositories

Development of the [Marine Geoscience Digital Library](http://www.marine-geo.org/library) began in 2004. Our code repositories include back-end components that are used for data curation, validation and ingestion as well as front-end components for user interfaces that enable data discovery, access and download. While all of our code is managed and backed up off-site through Git-Hub, at present, much of this code is in private repositories to ensure the security of our systems.


**MGDL Repositories Include:**
- [ASP-IntegratedMap](https://github.com/mgds/ASP-IntegratedMap) - front-end code for driving the map-based data discovery tool for the Academic Seismic Portal.
- **home_mgds_local** - a *private* repository that includes line command code for data ingestion and verification, as well as crons that validate database integrity.  This code was developed over the past decade and a half and public distribution was not part of the design spec.  Making this content publicly accessible poses potential security risks to our system.
- **marine-geo.org** - a *private* repository that includes front-end code for data discovery, access and download. Most of the functionality and logic contained in this repository can be accessed directly through the web, but since the code was developed over the past decade and a half and public distribution was not part of the design spec, it is not publicly accessible. 
- **ASP @UTIG** - a *private* repository that contains back-end code for processed seismic data curation and web services that enable access to content.
- **MGDL APIs** - the APIs that are used to drive our webpages are documented and accessible on the [MGDS web services page](http://www.marine-geo.org/tools/web_services.php).
