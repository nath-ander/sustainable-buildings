# sustainable-buildings


Title: 
LEED Certified Buildings in Lexington Ky
  
Source Information:
 This map uses information from the LEED projects database to show all LEED certificed buildings in Lexington, Ky. 
 Data Source: https://www.usgbc.org/projects

Map Description:
  Sustainable building techniques are important to efforts to limit the effects of climate change and LEED is the predominate organization in the US for tracking and verifing when and where those techniques are implemented. Seeing a visual representation (map) of how many buildings are in the LEED system helps emphasize how much work is left to do.

Mapping Process:
  Once the data from LEED was properly organized I imported it into QGIS. Originally the data was in points. Because I wanted the buildings to be seen I drew polygons to represent them and did a spatial join to connect the LEED data to the building polygons.
  Once imported into Mapbox I added the LEED logo as an .svg file to represent the building locations at lower zoom levels. As the viewer zooms in the logos fade out and the building polygons become visible. Each logo and polygon is colored to match the certification level of the building it represents.
