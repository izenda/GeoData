# GeoData

Contains different GeoData.zip files, making it possible to select a different set of coded points for Map visualizations.

GeoData is the primary location where this information is stored, GeoDataAlt is also checked and can be customized using the Izenda.GeoData utility located in the utilities repository. 

Each GeoData.zip and GeoDataAlt.zip file contains a different set of coded place names. They come in two varities: 

All, which covers all nations of the world. 
US, which covers the United States only. 

Each GeoData.zip file also contains a population cutoff. For example, US_15000 contains every city in the United States with more than 15,000 people. 

These files should be placed in \Resources\FromDLL\Resources\Map Cities can be located by a name string or coordinates.

Cities with the same name can be differentiated by the addition of state/region and country strings. 

Coordinates can be listed three ways: 

DDD° MM' SS.S" Degrees, Minutes and Seconds 
DDD° MM.MMM' Degrees and Decimal Minutes 
DDD.DDDDD° Decimal Degrees
