# NOAA and NASA Climate Data

Plots of atmospheric CO2, CH4, global temperature anomal, and mean sealevel trends from NOAA and NASA public databases. See specific notes below for each
notebook.

## Notebooks

### `NOAA_SeaLevelTrend.ipynb` - Relative Sea Level Trends

NOAA Tides & Currents data for Galveston Pier 21 (station 8771450) and New York Battery (station 8158750)

Source: [tidesandcurrents.noaa.gov/sltrends/](https:///tidesandcurrents.noaa.gov/sltrends/)

NOAA Center for Operational Oceanographic Products and Services.

Retrieves data from these URLs
 * [Galveston TX Pier 21](https://tidesandcurrents.noaa.gov/sltrends/sltrends_station.shtml?id=8771450)
 * [New York NY Battery](https://tidesandcurrents.noaa.gov/sltrends/sltrends_station.shtml?id=8518750)

### `NOAA_GML_AtmosCO2_MLO.ipynb` - Atmospheric Carbon Dioxide from Mauna Loa

NOAA Global Monitoring Laboratory atmospheric carbon dioxide trend data from the Mauna Loa Observatory.

Source: [gml.noaa.gov/ccgg/trends/mlo.html](https://gml.noaa.gov/ccgg/trends/mlo.html). For the CSV files,
see [Trends in Atmospheric Carbon Dioxide data](https://gml.noaa.gov/ccgg/trends/data.html).

Citation: Dr. Pieter Tans, NOAA/GML (gml.noaa.gov/ccgg/trends/) and Dr. Ralph Keeling, Scripps Institution of
Oceanography (scrippsco2.ucsd.edu/).

### `NOAA_GML_AtmosCH4.ipynb` - Atmospheric Methane Trends

NOAA Global Monitoring Laboratory atmospheric methane trend data.

Source: [gml.noaa.gov/ccgg/trends_ch4/](https://gml.noaa.gov/ccgg/trends_ch4/). For the CSV files,
see [Trends in Atmospheric Methane data](https://gml.noaa.gov/ccgg/trends_ch4/).

Citation: Dr. Pieter Tans, NOAA/GML (gml.noaa.gov/ccgg/trends/) and Dr. Ralph Keeling, Scripps Institution of
Oceanography (scrippsco2.ucsd.edu/).

### `NASA_GISS_GlobalTempAnomaly.ipynb` - NASA GISS Annual Earth Temperature Anomaly

NASA GISS Surface Temperature Analysis (GISTEMP v4) - [data.giss.nasa.gov/gistemp/](https://data.giss.nasa.gov/gistemp/).

Data are updated annually through the most recent complete year. Retrieve the latest version of this CSV
file:

* [ZonAnn.Ts+dSST.csv](https://data.giss.nasa.gov/gistemp/tabledata_v4/ZonAnn.Ts+dSST.csv)

In case they have reorganized the GISS website, these data are the "Combined Land-Surface Air and Sea-Surface
Water Temperature Anomalies (Land-Ocean Temperature Index, L-OTI) Zonal annual means, 1880-present, updated
through most recent complete year".

