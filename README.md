# Phoenix BII Analysis 
![City of Phoenix](https://i.guim.co.uk/img/media/35a60afad1cc0f38ec82589b72e34f84625fd196/0_338_2868_1722/master/2868.jpg?width=1200&quality=85&auto=format&fit=max&s=5fa57d5db65232134fe2210ee36b2d1e)
Image credits: The Guardian

## About
This project analyzes changes in the Biodiversity Intactness Index (BII) in Phoenix, Arizona (Maricopa County) between 2017 and 2020. The analysis aims to understand the impact of urban expansion on local biodiversity, as Phoenix has experienced significant urban development in recent decades.

## Repository Structure
```
urban-bii-analysis/
├── data_clean/
│   ├── phoenix-boundary-file
│   └── ...
├── .gitignore
├── README.md
└── biodiveristy.ipynb
```
## Data Access

1. Biodiversity Intactness Index (BII) Time Series
Access the `io-biodiveristy` collection from the [Microsoft Planetary Computer STAC catalog](https://planetarycomputer.microsoft.com/dataset/io-biodiversity) Use the 2017 and 2020 raster covering the Phoenix subdivision. A bounding box with cooridinates `[-112.826843, 32.974108, -111.184387, 33.863574]` is used for data acquisition. Data can be retrieved by searching for `io_biodiversity` collection with specified parameters in the MPC catalog. 

2. Phoenix Subdivision Shapefile 
The Phoenix subdivision shapefile was downloaded from the [2020 TIGER/Line® Shapefiles:](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=County+Subdivisions) County Subdivisions for Arizona, as provided by the US Census Bureau. Data can be accessed by selecting Arizona on the webiste and clicking download. 

## Acknowledgments
This repository contains materials created by Carmen Galaz-Garcia for the course [EDS 220 - Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/). This course is part of the [UCSB Masters in Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science).

**Biodiversity Intactness Index data**
De Ornellas, P., Callaghan, C.T., Lahoz-Monfort, J.J., & Simmonds, J.S. (2023). io-biodiversity: Global Time Series Maps of Biodiversity Intactness Index. Microsoft Planetary Computer. https://doi.org/10.34911/rdnt.ev7x2p

**Administrative Boundaries**
U.S. Census Bureau (2020). TIGER/Line Shapefiles: County Subdivisions [Arizona]. Retrieved from https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=County+Subdivisions

