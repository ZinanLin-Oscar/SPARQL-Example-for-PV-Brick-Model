# SPARQL-Example-for-PV-Brick-Model
This GitHub repository provides a Python-based implementation of SPARQL queries to retrieve metadata from the HKUST PV System Brick schema model. The example queries included in this repository enable users to obtain an overview of the 60 power stations located on campus, as well as detailed information on individual power stations. 


# Overview
To enhance data comprehension and enable efficient querying, we have developed a Brick schema model that represents the location, equipment, and temporal metadata for HKUST PV systems. The Brick schema is an open-source standardized semantic model that describes the physical, logical and virtual assets in buildings and the relationships between them. Figure below illustrates the entity classes, entities properties, instances, and their relationships of one PV station.
![image](https://github.com/ZinanLin-Oscar/SPARQL-Example-for-PV-Brick-Model/assets/113269274/dee3d0b8-6937-4dae-b9ca-a31c2c150b6c)
The detailed Brick model is stored in .ttl file format. Here we provide a Python sample code to retrieve system metadata using SPAQAL queries.


# Code Usage
### Accessing brick model in turtle (.ttl) file
Read in the Brick schema model in turtle (.ttl) format

### Accessing brick model in turtle (.ttl) file
Read in the Brick schema model in turtle (.ttl) format

### Inquiring overall information of power stations
* Number of PV stations included
* Types of PV inverter
* Types of PV module
* Campus PV station capacity (Sum, Min, Max, Avg)

### Time related inqueries
* The earliest and latest constructed PV station
* Operation period of each station

### Specific Site Information
* Site Information
* Inverter Information
* Module Information


