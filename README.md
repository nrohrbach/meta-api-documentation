# Access the metadata of FOEN datasets using CKAN-API of opendata.swiss
All OGD-datasets of the [Swiss Federal Office of Energy (FOEN)](https://www.bfe.admin.ch/bfe/en/home/supply/statistics-and-geodata/geoinformation.html) are listed in the National OGD portal [opendata.swiss](https://opendata.swiss/en). It is possible to access the information using the [CKAN-API](https://handbook.opendata.swiss/de/content/nutzen/api-nutzen.html) of opendata.swiss. Here we show you some examples how to query the CKAN-API:

## General information
A detailled documentation of CKAN-API is found [here](https://docs.ckan.org/en/latest/contents.html).

## List all FOEN datasets
Use the [organization_show](https://docs.ckan.org/en/latest/api/index.html#ckan.logic.action.get.organization_show) endpoint.
```
https://ckan.opendata.swiss/api/3/action/organization_show?
id=bundesamt-fur-energie-bfe&
include_datasets=True 
```
