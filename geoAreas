This process :
  -reads in a roster.csv file and stores the name, address, phone, email into Mongo datastore. 
  -reads polygons from a kml file created in GoogleEarth. These are keyed by the code for each polygon, put in datastore.
  -iterates through all households and requests lat-long for each address and adds it to  the household info.
  -Mongo has a 2d index on lat-long .
  -iterates through all polygons, for each: fetch all households insided of polygon, 
    set the polygon code on the household info and updates household datastore.
  
