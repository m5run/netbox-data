# netbox-data
Netbox datasource for reports, scripts, etc.

This repository is meant as a datasource for Netbox.  A data source represents some external repository of data which NetBox can consume, such as a git repository. Files within the data source are synchronized to NetBox by saving them in the database as data file objects.  The data files within the source can then be used for things like config contexts, config templates, scripts, and reports.
