# Metadata Requirements
Since all accessible resources in the enterprise geodatabase will be added to the Analytics Data Portal, metadata (data about the data) is required for all feature and attribute tables to be added to the database.

With limited exceptions, all metadata should be created in ArcGIS as this is the quickest way to get that information onto Portal. For GitHub users, that service should only be used to document data if the process/methodology used to create it is overly complicated/detailed. Regardless, if metadata is only on GitHub the database manager will copy the minimal information set from GitHub to ArcGIS metadata prior to posting it to the enterprise database and Portal. A link to the full documentation on GitHub will be added to the summary and description sections of the metadata for those who would like to see the full documentation.

If the database manager needs to copy information from GitHub to ArcGIS and posting is time sensitive, be sure to account for the extra time needed to transcribe the minimal infomation set to ArcGIS as nothing will be posted to the enterprise database/Portal until metadata in that format exists.


## Requirements (minimum)
- **Title**

- **Summary/Purpose:** 1-2 lines describing the data

- **Description/Abstract:** More detailed information on the data, including sources used to create data (if any). If source information remains in final product, note if there are any restrictions to the access and use of the source information.

- **Contact information for creator:** Try to use a position name or the name of a group instead of a person's name unless creating the data is truly an individual effort. People leave an organization or change roles, and the cost of updating metadata to change a person's name is not insignificant.

- **Date of completion:** Consider the date of the source data, if built off source data, when describing the date of an item. Data created today using an image that is six months old is really six months old.

- **Version of data:** If data is produced on a recurring basis or is part of a series

- **Field descriptions:** A description needs to be included for every column in the attribute table. If values for a field use a set of codes to describe what is in that column (i.e. MU for multi-unit, SR for single residence, etc) then each code needs to be defined as well.
