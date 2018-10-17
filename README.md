# ThreatTool
A user-friendly tool to identify potential threats to species on a landscape level
Authors:	Kayla N. Key1 and Christopher Krause2
	1Missouri Cooperative Fish and Wildlife Research Unit, The School of Natural Resources, University of Missouri, knkmr2@mail.missouri.edu
	2Department of Geography, University of South Carolina
  
Introduction: 
This tutorial describes a “user-friendly” tool to identify potential environmental threats to biological units of interest on a landscape level.  Specifically, this will guide the user to use a tool that creates map(s) describing and summarizing potential threats to a biological unit of interest (such as an organism or assemblage) based on specific a boundary of interest.  This tool could useful to state or federal agencies responsible for large geographic areas, which necessitate prioritization of specific regions for threat mitigation or descriptions of threats on the landscape.  This tutorial explains how to easily and quickly use this tool within ArcCatalog and ArcMap. This tutorial is designed for users who have some familiarity with ArcGIS. The final product of the generated tool is a combined PDF files of maps and reports of threats related to the organismal data for each geographic unit of interest. 

Programs required: ArcGIS (tutorial uses 10.3), 

Package includes: 	1. PDF Tutorial with an example
			2. Example data
			3. Python Toolbox and .mxd map template in numerous ArcGIS versions 

User input:	 
      1. Unit of interest in shapefile format.
Data on a group of organisms that span the extent of the study area. 
In the example, we use species richness of mussel beds across the state of Missouri, but this could include other responses: presence/absence, species richness, diversity, demographic information, etc.
			2. Boundary of interest in shapefile format.
Defining boundaries of small subunits. 
In the example, we use watershed boundaries in the form of HUC10, but these could include ecoregional, political boundaries, etc.
			3. Folder with all potential threats as point shapefiles.
Spatially explicit information on potential threats. 
In the example, we use state level information on potential threats to mussel communities, but which will be up to the discretion of the tool user.
 
