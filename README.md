# SPARQL-Example-for-PV-Brick-Model
This GitHub repository provides a Python-based implementation of SPARQL queries to retrieve metadata from the HKUST PV System Brick schema model. The included example queries enable users to obtain an overview of the 60 power stations located on the campus, as well as detailed information on individual power stations.


# 1. Overview
To enhance data comprehension and enable efficient querying, we have developed a Brick schema model that represents the location, equipment, and temporal metadata for HKUST PV systems. The Brick schema is an open-source standardized semantic model that describes the physical, logical and virtual assets in buildings and the relationships between them. Figure below illustrates the entity classes, entities properties, instances, and their relationships of one PV station.
![image](https://github.com/ZinanLin-Oscar/SPARQL-Example-for-PV-Brick-Model/assets/113269274/dee3d0b8-6937-4dae-b9ca-a31c2c150b6c)
The detailed Brick model is stored in .ttl file format. Here we provide a Python sample code to retrieve system metadata using SPAQAL queries.



# 2. Setting Up the Python Environment
To replicate the notebook and run the provided code, please follow these steps to set up a Python environment.
### 2.1 Prerequisites
Make sure you have Python installed on your machine. It is recommended to use Python 3.6 or higher.

### 2.2 Creating a Virtual Environment
Make sure you have Python installed on your machine. It is recommended to use Python 3.6 or higher.
1. Create a virtual environment
   ```bash
   python -m venv myenv
   ```
2. Activate the virtual environment
   - On Windows:
   ```bash
   myenv\Scripts\activate
   ```
   - On macOS/Linux:
   ```bash 
   source myenv/bin/activate
   ```

### 2.3 Installing Required Packages
Install the necessary Python packages: You can install the required packages using pip. Run the following command:
 ```bash
pip install pandas rdflib brickschema
```

### 2.4 Running the Notebook
Download the notebook and data files: Ensure you have the notebook file and the PV generation system metadata.ttl file in the same directory as your script.
Run the script: You can run the script using:
```bash
python Brick query demo code.ipynb
```



# 3. Code Usage
### Accessing brick model in turtle (.ttl) file
Read in the Brick schema model in turtle (.ttl) format

### Overall information queries
* Number of PV stations included
* Types of PV inverter
* Types of PV module
* Campus PV station capacity (Sum, Min, Max, Avg)

### Time related inqueries
* The earliest and latest constructed PV station
* Operation period of each station

### Specific site queries
* Site Information
* Inverter Information
* Module Information


