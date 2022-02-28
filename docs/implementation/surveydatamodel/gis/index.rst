Geographic Information System (GIS)
===================================

The required GNSS/GIS work shall result in a fully integrated GIS/GNSS system with covering entire developed portion of the cemetery. The GIS elements that are created shall be sufficient to allow the display of the cemetery with improvements visible on ArcGIS mapping software.

The various elements that will be used to depict the site using the GIS mapping are to be made up of points, polylines and closed polygons that shall be created and displayed.

Graphical representation of the location and elevation, as well as the data information for the geographically displayed information, for the elements in the provided ArcGIS Geodatabase formatshall be provided. The source for the graphical portion of the GIS shall be from the “As-Built” AutoCAD data supplemented with the field collected data. The geographic coordinate and elevation information for the elements being added to the GIS system, whether points, polylines or closed polygons, shall be collected and represented in the GIS based upon the accuracy level for the GNSS equipment being provided for the project being surveyed and mapped.

Station Survey GIS Data Model
-----------------
.. list-table:: 
 :header-rows: 1


* - Field Name	
  - Require/ Required if Applicable	
  - Description
* - DFIRM_ID	
  - R	
   - Flood Risk Project Identifier. For a single-jurisdiction Flood Risk Project, the value is composed of the two-digit State FIPS code and the four-digit FEMA CID code (e.g., 480001). For a countywide Flood Risk Project, the value is composed of the two-digit State FIPS code, the three-digit county FIPS code and the letter “C” (e.g., 48107C). Within each FIRM Database, the DFIRM_ID value will be identical.

VERSION_ID	R	Version Identifier. Identifies the product version and relates the feature to standards according to how it was created.
SURVPT_ID	R	Primary key for table lookup. Assigned by table creator.
SURVSTR_ID	R	Structure ID of Structure or Feature Being Surveyed. SURVSTR_ID corresponds to the Structure ID field in the Data Capture Technical Reference where the first three characters represent the stream reach name abbreviation, followed by an underscore and then the stream station at which the feature is found.
SURV_CODE	R	Survey Code Describing the Surveyed Feature Type. SURV_CODE corresponds to the Survey Code field in the Data Capture Technical Reference. Information about the type of feature being surveyed is input into this field, for example “TOS” for “Toe of Slope”. Default survey codes and descriptions are provided as best practice information
in the Data Capture Technical Reference.
STRUCTDESC	R	Description of the structure or feature being surveyed, for example “Cross Section 2”. STRUCTDESC corresponds to the Structure Description field in the Data Capture
Technical Reference.
NORTHING	R	Northing location of the survey point, in the projection specified.
EASTING	R	Easting location of the survey point, in the projection specified.
ELEV	R	Elevation of the survey point, in the vertical datum and elevation units specified.
ELEV_UNIT	R	Elevation Units. This unit indicates the measurement system used for the survey points. Normally, this would be feet. Acceptable values for this field are listed in the D_Length_Units table.
H_DATUM	R	Horizontal Datum. This is the horizontal datum used for the survey points. NAD83 is the preferred horizontal datum.
Acceptable values for this field are listed in the D_Horiz_Datum table.
