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
  
 * - Code: 
   - Description	
   - Field Survey Location
 * - ABT:	
   - Abutment	
   - Face/foot of abutment of bridge.
 * - BOCEDS:	
   - Back of Curb Edge Down Stream	
   - Where slope meets top of culvert or top of headwall above culvert centerline on downstream end for determining outlet projection.
 * - BOCEUS:	
   - Back of Curb Edge Up Stream	
   - Where slope meets top of culvert or top of headwall above culvert centerline on upstream end for determining inlet projection.
 * - BRCL:	
   - Bridge Centerline	
   - Centerline of bridge in overtopping section.
 * - CH:	
   - Channel
   - Stream bottom between Toe of Slope (TOS) shots.
 * - CHCL:	
   - Channel Centerline	
   - Center of the main flow area of the stream.
 * - CUL:	
   - Culvert Shape	
   - Multiple CUL codes can be used to define shapes for culverts, especially irregular shapes.
 * - CULCL:	
   - Culvert Centerline	
   - Centerline of culvert in overtopping section.
 * - CULDSCR:	
   - Culvert Down Stream Crown	
   - The highest point of the downstream end of a culvert.
 * - CULDSINV:	
   - Culvert Down Stream Invert	
   - The lowest point of the downstream end of a culvert.
 * - CULUSCR:	
   - Culvert Up Stream Crown	
   - The highest point of the upstream end of a culvert.
 * - CULUSINV:	
   - Culvert Up Stream Invert	
   - The lowest point of the upstream end of a culvert.
 * - DAMCL:	
   - Dam Centerline	
   - The high point of a dam.
 * - DH:	
   - Dune Heel	
   - Landward toe of primary frontal dune.
 * - DP:	
   - Dune Peak	
   - Peak or rear shoulder of primary frontal dune.
 * - DT:	
   - Dune Toe	
   - Seaward toe of primary frontal dune.
 * - EOB:	
   - End of Bridge	
   - End of the bridge deck at the road/rail elevation.
 * - ERM:	
   - Elevation Reference Mark	
   - Permanent elevation monument. An ERM must be set at every structure and at cross sections if they are more than half a mile to the nearest structure.
 * - FBCL:	
   - Foot Bridge Centerline	
   - Centerline of non-vehicular bridges in overtopping section.
 * - GDR:	
   - Guardrail	
   - Top of guardrail at ends to define limit and height.
 * - GDRBOT:	
   - Guardrail at Bottom	
   - Base of guardrail at ends to define and height.
 * - GR:	
   - Ground	
   - On ground to show elevation changes, used outside Top of Bank (TOB) shots, between TOB and TOS, and to indicate islands or bars within the channel. When used in  channel cross-section surveys, a GR point must be placed at least 15 feet past the top of bank or until there is no overhead obstruction from foliage. If overhead foliage is too  thick for the entire overbank area, full valley cross sections should be a consideration for modeling.
 * - HWMARK:	
   - High Water Mark	
   - Historical high water marks-mud/stain lines, drift lines, parole evidence, etc.
 * - INVDS:	
   - Invert Down Stream	
   - Channel invert at downstream end of structure, used to define paved aprons.
 * - INVUS:	
   - Invert Up Stream	
   - Channel invert at upstream end of structure, used to define aprons.
 * - LC:	
   - Low Chord	
   - Change in bridge deck thickness, usually at center of a pile row or pier. Multiple low chord codes can be used to define irregular shaped bridges such as arched bridges  with the explanation of the multiple LC shots shown in the sketch for the structure.
 * - LCDSL:	
   - Low Chord Down Stream Left	
   - Bottom of deck and beam at the downstream left corner of bridge¹.
 * - LCDSR:	
   - Low Chord Down Stream Right	
   - Bottom of deck and beam at the downstream right corner of bridge¹.
 * - LCUSL:	
   - Low Chord Up Stream Left	
   - Bottom of deck and beam at the upstream left corner of bridge¹.
 * - LCUSR:	
   - Low Chord Up Stream Right	
   - Bottom of deck and beam at the upstream right corner of bridge¹.
 * - LV:	
   - Levee	
   - The centerline of the top of a levee.
 * - PIER:	
   - Pier	
   - The up and downstream centerline of a pier.
 * - PILE:	
   - Pile	
   - The up and downstream centerline of a row of piles.
 * - RAIL:	
   - Rail	
   - Top of rail to define limits and height of railing on structures.
 * - RAILBOT:	
   - Rail Bottom	
   - Bottom of rail to define limits and height of railing on structures.
 * - RDCL:	
   - Road Centerline	
   - The centerline on a crowned road or the high side of a road with super elevation.
 * - SFLOOR:	
   - Sea Floor	
   - Shots either direct or combination of bathymetric and conventional/Global Positioning System (GPS) survey of coastal area which can be collected during structure  or transect survey.
 * - TEMP:	
   - Temporary Control Point	
   - Temporary control point used for data collection of cross sections and structures. TEMPs are established when ERMs are not present.
 * - TOB:	
   - Top of Bank	
   - Top of bank in a multiple channel scenario.
 * - TOBL:	
   - Top of Bank Left	
   - Break point from over bank to channel on the left side when looking downstream.
 * - TOBR:	
   - Top of Bank Right	
   - Break point from over bank to channel on the right side when looking downstream.
 * - TOD:	
   - Top of Deck	
   - To show an irregular arch or dip in a bridge deck between the bridge corner shots.
 * - TODDSL:	
   - Top of Deck Down Stream Left	
   - Downstream left corner of a bridge on the deck directly above the LCDSL shot to measure deck thickness and width¹.
 * - TODDSR:	
   - Top of Deck Down Stream Right	
   - Downstream right corner of a bridge on the deck directly above the LCDSR shot to measure deck thickness and width¹.
 * - TODUSL:	
   - Top of Deck Up Stream Left	
   - Upstream left corner of a bridge on the deck directly above the LCUSL shot to measure deck thickness and width¹.
 * - TODUSR:	
   - Top of Deck Up Stream Right	
   - Upstream right corner of a bridge on the deck directly above the LCUSR shot to measure deck thickness and width¹.
 * - TOS:	
   - Toe of Slope	
   - The toe in a multiple channel scenario.
 * - TOSL	
   - Toe of Slope Left	
   - Break point from channel bank to channel bed on the left side when looking downstream.
 * - TOSR	
   - Toe of Slope Right	
   - Break point from channel bank to channel bed on the right side when looking downstream.
 * - WALL	
   - Wall	
   - Top of a retaining wall, also used outside TOBL and TOBR when the stream banks are vertical walls or rock cuts.
 * - WALLBOT 
   - Wall Bottom	
   - Bottom of a retaining wall, also used outside TOBL and TOBR when the stream banks are vertical walls or rock cuts.
 * - WEIR	
   - Weir	
   - Top of dam spillways and outlet structures. Multiple weir codes may be used to collect data for gates, flashboards, and other operable structures. The explanation of the multiple shots should be shown in the structure sketch.
 * - WW	
   - Wing Wall	
   - Top face of each end of a wing wall or headwall on a structure to define height and length.
 * - WWBOT	
   - Wing Wall Bottom	
   - Base of each end of a wing wall or head wall on a structure to define height and length.

 
