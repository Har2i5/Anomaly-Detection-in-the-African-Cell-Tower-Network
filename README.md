# Isolation-Forest-and-Time-based-Anomaly-Detection-in-the-African-Cell-Tower-Network 
# Dataset Description
This extensive dataset provides geographic coordinates and network information for cell tower locations across the globe, organized by continent. It includes the following columns:

- Radio: The generation of broadband cellular network technology (e.g., LTE, GSM).
- MCC: Mobile Country Code, a unique identifier for each country in the mobile network.
- MNC: Mobile Network Code, identifying the mobile network within a country.
- LAC: Location Area Code, Tracking Area Code, or Network Identifier.
- CID: Unique identifier for each Base Transceiver Station (BTS) or sector.
- Longitude: Geographic coordinate specifying the east-west position.
- Latitude: Geographic coordinate specifying the north-south position.
- Range: Approximate area within which the cell coverage extends (in meters).
- Samples: Number of measures processed to derive the data point.
- Changeable: Indicates if the cell location was determined through sample processing (1) or directly obtained from the telecom firm (0).
- Created: Timestamp indicating when the cell was first added to the database (UNIX format).
- Updated: Timestamp indicating when the cell was last seen or updated in the database (UNIX format).
- AverageSignal: Represents the averaged signal strength of the cell location.
- Country: The country of the cell tower.
- Network: The company that owns the cell tower.
- Continent: The continent of the cell tower.
- This dataset contains over 46 million records in total, making it a rich resource for spatial analysis, telecommunications research, and network planning.

# Source
kaggle datasets download -d zakariaeyoussefi/cell-towers-worldwide-location-data-by-continent
