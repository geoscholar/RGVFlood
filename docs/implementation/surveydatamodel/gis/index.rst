Geographic Information System (GIS)
===================================

The required GNSS/GIS work shall result in a fully integrated GIS/GNSS system with covering entire developed portion of the cemetery. The GIS elements that are created shall be sufficient to allow the display of the cemetery with improvements visible on ArcGIS mapping software.

The various elements that will be used to depict the site using the GIS mapping are to be made up of points, polylines and closed polygons that shall be created and displayed.

Graphical representation of the location and elevation, as well as the data information for the geographically displayed information, for the elements in the provided ArcGIS Geodatabase formatshall be provided. The source for the graphical portion of the GIS shall be from the “As-Built” AutoCAD data supplemented with the field collected data. The geographic coordinate and elevation information for the elements being added to the GIS system, whether points, polylines or closed polygons, shall be collected and represented in the GIS based upon the accuracy level for the GNSS equipment being provided for the project being surveyed and mapped.

The Geospatial Data shall represent the feature being identified to the level of 1 centimeter and 2-centimeter accuracy for the horizontal and vertical coordinate, respectively. A geodatabase template for all required features and associated data will be provided to, and be used.

Data will be collected using FEMA Data Capture- Workflow Details.



Survey Code List
-----------------
.. list-table:: 
 :header-rows: 1
  
 * - Attribute
   - Require 
   - Description
 * - DFIRM_ID
   - R
   - Flood Risk Project Identifier. For a single-jurisdiction Flood Risk Project, the value is composed of the two-digit State FIPS code and the four-digit FEMA CID code (e.g., 480001). For a countywide Flood Risk Project, the value is composed of the two-digit State FIPS code, the three-digit county FIPS code and the letter “C” (e.g., 48107C). Within each FIRM Database, the DFIRM_ID value will be identical.
 * - VERSION_ID
   - R
   - Version Identifier. Identifies the product version and relates the feature to standards according to how it was created.
