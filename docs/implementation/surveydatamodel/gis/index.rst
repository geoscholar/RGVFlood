Geographic Information System (GIS)
===================================

The required GNSS/GIS work shall result in a fully integrated GIS/GNSS system with covering entire developed portion of the cemetery. The GIS elements that are created shall be sufficient to allow the display of the cemetery with improvements visible on ArcGIS mapping software.

The various elements that will be used to depict the site using the GIS mapping are to be made up of points, polylines and closed polygons that shall be created and displayed.

Graphical representation of the location and elevation, as well as the data information for the geographically displayed information, for the elements in the provided ArcGIS Geodatabase formatshall be provided. The source for the graphical portion of the GIS shall be from the “As-Built” AutoCAD data supplemented with the field collected data. The geographic coordinate and elevation information for the elements being added to the GIS system, whether points, polylines or closed polygons, shall be collected and represented in the GIS based upon the accuracy level for the GNSS equipment being provided for the project being surveyed and mapped.

The Geospatial Data shall represent the feature being identified to the level of 1 centimeter and 2-centimeter accuracy for the horizontal and vertical coordinate, respectively. A geodatabase template for all required features and associated data will be provided to, and be used.

Data will be collected using FEMA Data Capture- Workflow Details.


Site
-----------------
.. list-table:: 
 :header-rows: 1
  
 * - Attribute
   - Required
   - Description
   - Type
   - Length
 * - DFIRM_ID
   - R
   - Flood Risk Project Identifier. For a single-jurisdiction Flood Risk Project, the value is composed of the two-digit State FIPS code and the four-digit FEMA CID code (e.g., 480001). For a countywide Flood Risk Project, the value is composed of the two-digit State FIPS code, the three-digit county FIPS code and the letter “C” (e.g., 48107C). Within each FIRM Database, the DFIRM_ID value will be identical.
   - Text
   - 6
 * - VERSION_ID
   - R
   - Version Identifier. Identifies the product version and relates the feature to standards according to how it was created.
   - Text
   - 11
 * - SURVPT_ID
   - R
   - Primary key for table lookup. Assigned by table creator.
   - Text
   - 25
 * - SURVSTR_ID
   - R
   - Structure ID of Structure or Feature Being Surveyed. SURVSTR_ID corresponds to the Structure ID field in the Data Capture Technical Reference where the first three characters represent the stream reach name abbreviation, followed by an underscore and then the stream station at which the feature is found.
   - Text
   - 11
 * - SURV_CODE
   - R
   - Survey Code Describing the Surveyed Feature Type. SURV_CODE corresponds to the Survey Code field in the Data Capture Technical Reference. Information about the type of feature being surveyed is input into this field, for example “TOS” for “Toe of Slope”. Default survey codes and descriptions are provided as best practice informationin the Data Capture Technical Reference.
   - Text
   - 30
 * - STRUCTDESC
   - R
   - Description of the structure or feature being surveyed, for example “Cross Section 2”. STRUCTDESC corresponds to the Structure Description field in the Data Capture Technical Reference.
   - Text
   - 254
 
