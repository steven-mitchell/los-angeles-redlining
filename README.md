# Los Angeles Redlining
**Exploring patterns of environmental justice**

![](images\holc-scan.jpg)

### Purpose
This repository demonstrates my analysis of historical redlining in Los Angeles and its modern day impacts to community health and biodiversity metrics.

### Skills and Techniques Demonstrated
- Build effective, responsible, accessible and aesthetically-pleasing maps
- Manipulate vector and raster data to build multi-layer maps
- Spatial analysis between vector and raster datasets


### Contents
```
.
├── README.md
├── gitignore
├──los-angeles-redlining.Rproj
├──los-angeles-redlining.html   # rendered report document
├──los-angeles-redlining.qmd    # non-rendered report with raw code
├──data                         # too large for github: see Data section
│   ├── EJSCREEN_2023_BG_Columns.xlsx
│   ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb #GeoDataBase
│   ├── ejscreen-tech-doc-version-2-2.pdf
│   └── gbif-birds-LA
│       ├── gbif-birds-LA.dbf
│       ├── gbif-birds-LA.prj
│       ├── gbif-birds-LA.shp
│       └── gbif-birds-LA.shx
├──outputs
│   ├── chart_birds.png
│   ├── chart_life_exp.png
│   ├── chart_low_inc.png
│   ├── chart_pm25.png
│   └── map_la.html
└──images
    └── holcscan.png
```
### Data
The data used in this analysis is too large to be hosted on GitHub. Instead, download the data  <a href="https://drive.google.com/file/d/14CauXFZkVh_6z2Euq0m1Sq1kHQ31fiMk/view?usp=sharing"> here </a> as a zipped folder, unzip, and move into the R project manually.



### Acknowledgements
This analysis and workflow was originally created by Dr. Ruth Oliver of the Bren School of Environmental Science & Management for the Masters of Environmental Data Science course, Geospatial Analysis and Remote Sensing. My initial work through of this analysis was conducted as part of a homework assignment for this class, and I later polished up this repository.

### Citations
| Data | Citation | Link |
| -----| ----- | ------|
|EJ Screen |  U.S. Environmental Protection Agency (EPA), 2023. EJScreen Technical Documentation. |https://www.epa.gov/ejscreen |
| Mapping Inequality |Nelson, Robert K., LaDale Winling, et al. "Mapping Inequality: Redlining in New Deal America." Edited by Robert K. Nelson and Edward L. Ayers. American Panorama: An Atlas of United States History, 2023. https://dsl.richmond.edu/panorama/redlining.  | https://www.epa.gov/ejscreen|
| GBIF Bird Observations | GBIF.org (year), GBIF Home Page. Available from: https://www.gbif.org [13 January 2020]. | https://www.gbif.org/|