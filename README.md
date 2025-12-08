# Neighborhood_Res
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This project, as part of the final, will be mapping the potential route refugees in 1980s Ethiopia and Eritrea may have taken to Khartoum, Sudan, taking into account conflict zones, communicable diseases, elevation, and other barriers. This repository includes a series of exploratory labs that explores and maps elevation and conflict data as stepping stones for raster analysis to utilize Least Cost Corridor between both points.

### Datasets:
* Uppsala Conflict Data Program, Department of Conflict Research 1989 Ethiopia and Sudan conflict data
* OpenTopography Elevation API

#### Tools:
* Python (pandas, geopandas, osgeo [gdal])
* ArcGIS Pro

### Summary Results:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Finding reliable geolocated conflict data for Africa pre-1989 is not likely, and by 1989, the largest of the refugee wave had already begun or passed (though many reports place asylum seekers seeking refuge or living in encampments from this era until as late as 1999). This analysis is meant to be supplementary to existing literature and further analysis

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Conflict zones were mapped as vector points to maintain their attribute information so as to weight each location by severity and responsible actors (measured 1-5). The map shows that conflicts in Ethiopia (red points) were disproportionately along and throughout regions with high elevation. Literature from this time notes that government militias would intentionally target these regions as many were the most vulnerable and rural. Following labs and related sub-projects will focus further on the communal strain this mass influx of refugees had on Sudan, a country that had and continues to face widespread famine, conflict, and major economic downturns.

### Literature:
* [Socialist Ethiopia (1974–91)](https://www.britannica.com/place/Ethiopia/Socialist-Ethiopia-1974-91)
* [CIA Intelligence Assessment](https://www.cia.gov/readingroom/docs/CIA-RDP86T00589R000200160004-5.pdf#:~:text=His%20stated%20rationale%20of%20relocating%20peasants%20from,up%20by%20the%20prospect%20of%20forced%20resettlement.)
* [Ethiopia: Conflict and food insecurity 40 years on from the 1984 famine](https://lordslibrary.parliament.uk/ethiopia-conflict-and-food-insecurity-40-years-on-from-the-1984-famine/#:~:text=Between%201983%20and%201985%20there,of%20communities%20into%20planned%20villages%5D.)


![Lab 1 Map](https://github.com/user-attachments/assets/81b55056-f7fe-4443-ad0e-80fc7f9eba09)
