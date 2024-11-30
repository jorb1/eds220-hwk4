# Geospatial Data Visualization for the Thomas Fire (2017) Burn Scar, Santa Barbara CA
### Author: Bailey Jorgensen *https://github.com/jorb1*

This repository contains a Jupyter Notebook of my analysis and visualization of fire perimeters and remote sensing data regarding the area of the Thomas Fire. 

## Data
The first is a simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmosperically corrected surface reflectance data, collected by the Landsat 8 satellite.

The data was retrieved from the Microsof Planetary Computer data catalogue and pre-processed to remove data outside land and coarsen the spatial resolution. This initial processing of data was done by Galaz-Garcia (see citations). This data should be used for visualization and educational purposes only.

The second dataset is historical open-access data about fire perimeters in California. There are several datasets with this information online. The dataset that I found is open source from data.gov. See link in citations.

I accessed all these data on November 15th, 2024. See citations section for direct links to these data sites. 

## Repository Structure

```bash
├── eds220-hwk4
│   ├── README.md
│   ├── hwk4-task2-fire-perimeter-JORGENSEN.ipynb
│   ├── hwk4-task2-false-color-JORGENSEN.ipynb
│   └── .gitignore
├── data
│   ├── California_Fire_Perimeters_(all).cpg
│   ├── California_Fire_Perimeters_(all).dbf
│   ├── California_Fire_Perimeters_(all).prj
│   ├── California_Fire_Perimeters_(all).shp
│   ├── California_Fire_Perimeters_(all).sshp.xml
│   ├── California_Fire_Perimeters_(all).shx
│   ├── landsat8-2018-01-26-sb-simplifieds.nc
│   └── thomas.geojson
```

## Citations:

C. Galaz García, EDS 220 - Working with Environmental Datasets, Course Notes. 2024. [Online]. Available: https://meds-eds-220.github.io/MEDS-eds-220-course/book/preface.html

CAL Fire. “California Fire Perimeters (All).” Data.gov. Metadata created March 30, 2024, updated May 14, 2024. https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436.

Microsoft Planetary Computer. Landsat Collection 2 Level-2 Atmospherically Corrected Surface Reflectance Data from Landsat 8 [Dataset]. Simplified for visualization and educational purposes. Accessed November 20, 2024. https://planetarycomputer.microsoft.com.
