# Lead-Lag-Spatial-Correlation-of-Sea-Surface-Temperature-and-Latent-Heat-Flux
Spatial Lead-Lag Correlation analysis between Sea Surface Temperature (SST) and Surface Latent Heat Flux (SLHF) over the Tropical Indian Ocean using Python and Cartopy.
SST–SLHF Spatial Correlation Analysis (Indian Ocean)
📌 Overview

This project investigates the relationship between Sea Surface Temperature (SST) and Surface Latent Heat Flux (SLHF) over the Tropical Indian Ocean.
A spatial correlation analysis is performed to understand air–sea interaction mechanisms and their role in climate variability.

🎯 Objective
To compute grid-wise correlation between SST and SLHF
To identify regions where air–sea coupling is strong
To visualize spatial patterns using map-based plotting
📊 Data Used
SST dataset (1973–2022)
SLHF dataset (1973–2022)

Both datasets are in NetCDF format and contain:

Time dimension
Latitude–Longitude grid
⚙️ Methodology
Load SST and SLHF datasets using netCDF4
Extract spatial and temporal data
Compute Pearson correlation at each grid point:
SST time series vs SLHF time series
Generate spatial maps using Cartopy
🛠️ Tools & Libraries
Python
NumPy
NetCDF4
Matplotlib
Cartopy
🌍 Study Region
Longitude: 30°E to 120°E
Latitude: 30°S to 30°N
Region: Tropical Indian Ocean
📈 Output
Spatial correlation map between SST and SLHF
Red/Blue regions indicating:
Positive correlation
Negative correlation
