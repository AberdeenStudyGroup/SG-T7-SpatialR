README.TXT

Corine Land Cover European seamless vector database (RELEASE v18_5)
-------------------------------------------------------------------------------

This directory contains the Corine Land Cover European seamless vector database 
version 18_5 (dated 02/2016) in ESRI GeoDatabase format. 

Vector databases was provided by National Teams within I&CLC2000, CARDS, CLC2006 and CLC2012 project. 
All features in original vector database were classified and digitised based on satellite images 
with 100 m positional accuracy (according to CLC specifications) and 25 ha minimum mapping unit (5ha MMU 
for change layer) into the standardized CLC nomenclature (44 CLC classes). EU CORINE Land Cover 
seamless DB represents the final product of European CLC2000 data integration. 
Harmonization on country border done for CLC2000 and CHA00 (2km strip) for other themes only small artefact 
along borders (0,1ha) has been removed.
All data files are accompanied with standard XML metadata.

Vector v18_5 database delivery contains:

readme_v18_5.txt           .... readme file
CLC_coverage_v18_5.pdf     .... country coverage for all CLC themes
readme_18_5_<theme>.txt    .... change log file for each CLC theme 
CLC90_Version18_5.gdb  	 .... Geodatabase with CORINE Land Cover data for reference year 1990
CLC00_Version18_5.gdb  	 .... Geodatabase with merged CORINE Land Cover for reference year 2000 and for reference year 2000-revised 
CLC06_Version18_5.gdb  	 .... Geodatabase with merged CORINE Land Cover for reference year 2006 and for reference year 2006-revised
CLC12_Version18_5.gdb    .... Geodatabase with CORINE Land Cover data for reference year 2012
CHA00_Version18_5.gdb  	 .... Geodatabase with CORINE Land Cover change data for reference year 1990-2000
CHA06_Version18_5.gdb  	 .... Geodatabase with CORINE Land Cover change data for reference year 2000-2006
CHA12_Version18_5.gdb  	 .... Geodatabase with CORINE Land Cover change data for reference year 2006-2012

The Coordinate Reference System (CRS):

CRS Name: EUR_ETRS89/LAEA1052 
 
Projection: Lambert Azimuthal - Equal Area projection
        longitude of origin             10d00'00.0000"E
        latitude of origin              52d00'00.0000"N
        false easting                   4321000.000
        false northing                  3210000.000
Datum: ETRS89 (European Terrestrial Reference System 1989)
        type 				geodetic 
	valid area 			Europe / EUREF
Ellipsoid 				GRS 80 (New International) 
	semi major axis 		6 378 137 m 
	inverse flattening 		298.257222101 


Changes from previous release - change log:
Version 18_5
Spain and Turkey were completed. For actual coverage see CLC_coverage_v18_5.pdf
CLC00 and CLC00-revised layers were merged to the one CLC00 layer. For actual coverage see CLC_coverage_v18_5.pdf.
CLC06 and CLC06-revised layers were merged to the one CLC06 layer. For actual coverage see CLC_coverage_v18_5.pdf.

Version 18_4
New parts were included to clc90, clc00, cha00 - Guernsey and Jersey islands and to clc06, cha06 - Guernsey and Jersey islands and Greece. For actual coverage see CLC_coverage_v18_4.pdf
New layer clc12 has been created. For actual coverage see CLC_coverage_v18_4.pdf.
New layer cha12 has been created. For actual coverage see CLC_coverage_v18_4.pdf.
New layer clc06 revised has been created. For actual coverage see CLC_coverage_v18_4.pdf.

Version 17
New part was included to clc90, clc00, clc06, cha00 and cha06 - Azores. For actual coverage see CLC_coverage_v17.pdf

version 16
New country was included in CHA00 and CLC90 - Turkey.For actual coverage see CLC_coverage_v16.pdf.
New layer clc00_revised has been created. For actual coverage see CLC_coverage_v16.pdf.
Shift in Malta position has been repaired - all CLC layers for Malta has been re-projected.
Few polygons inconsistences in CLC layers has been repaired - see details in readme for particular CLC theme included.

version 15 (V5)
New country was included in CHA06 and CLC06 as result of CLC2006 mapping - Great Britain.For actual coverage see CLC_coverage_v14.pdf.
A simplified border matching is applied on CLC06 layer-see details in readme for particular CLC theme included.

Version 14 (V4)
New countries were included in CLC00, CHA06 and CLC06 as result of CLC2006 mapping - Switzerland, Northern Ireland, Madeira island. 
New countries were included in CLC90 and CHA00 as available. For actual coverage see CLC_coverage_v14.pdf.
Seamless database has been further improved addressing action points/feedback from EEA on version 13 (V3).
See details in readme for particular CLC theme included.

Version 3
First real seamless release in ESRI Geodatabase format.
New layers (CLC06 and CHA06) included as result of CLC2006 mapping (36 countries) 
New countries were included in CLC90, CLC00 and CHA00 as available from CLC2006 related mapping.
Sea buffers has been introduced (15km as proxy to 12 nautical miles sea zone).

version 2
All issues in tiles or tile borders, which has been reported by users was corrected.
Original idea was to deliver one big seamless layer, but as it has showed to be not feasible in 
ESRI environment yet it was decided to produce seamless tiles again (but free of any tiling artefacts).
New country deliveries available integrated: Iceland, Montenegro, Serbia, Kosovo from CARDS and CLC2006 projects 
were included. Limited country harmonization done for these add-ons (small artefacts cleaned only).

version 1
Initial version includes all I&CLC2000 project countries
Harmonization on country border done (2km strip)


Prepared by
GISAT 02/2016
For more information contact tomas.soukup@gisat.cz