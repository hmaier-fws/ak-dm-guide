# Using the Regional Data Repository


The Alaska Regional Data Repository (RDR) is a centralized server dedicated to the long-term storage of regional projects and their products. It serves as an accessible and secure digital archive that contains authoritative copies of a project’s data, documents, and metadata. Your program’s data manager and technician are responsible for maintaining the RDR.


## Accessing the RDR


The RDR can be accessed through your web browser or file explorer by copying and pasting the following link into the address bar: `\\ifw7ro-file.fws.doi.net\datamgt`


::: {.callout-note}
The RDR can **only** be reached when you are connected to the Service network. Also, capabilities are limited when the RDR is accessed using your web browser.
:::


To ensure that files stored in the RDR are protected from loss or corruption, access to files within the Repository are controlled through permissions. Everyone in the Service with a VPN and link to the RDR may read what's in the Repository, but write and modify permissions are limited and assigned by data managers. For example, data stewards are granted write permission to their project’s “incoming” folder but otherwise have read permission for all other folders.

## Organization of the RDR


![Branching tree of program sub-folders in 'datamgt' folder](</assets/rdr-horiz.png>)


### Directory Template

This folder contains the template for regional project folders and their sub-folders. Your data manager will tailor the template to your particular project once your [data management plan](broken-reference) is approved.

### Contacts

This folder contains JSON files of the master contact list used for metadata creation. These files have regional contact information of staff and external partners and should be imported into [mdEditor](https://www.mdeditor.org/) to prevent duplicating contacts.

## Extents

GeoJSON files and metadata for common study areas in Alaska can be found in this folder. GeoJSON files can be imported into [mdEditor](https://www.mdeditor.org/) under the "Extent" tab to precisely delineate the spatial boundary of your project.

### Program Folders

The upper level of the RDR contains a folder for each program, and within each program folder are [project folders](obtaining-rdr-folder.md). The programs with RDR folders include:

- Fisheries and Ecological Services (fes)
- Migratory Bird Management (mbm)
- National Wildlife Refuge System (nwrs)
- Office of Subsistence Management (osm)
- Science Applications (sa)

