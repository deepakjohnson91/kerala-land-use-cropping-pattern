# Land Use and Cropping Pattern Data for Kerala
## 1. Overview
This is to share all data files related to the research note ["Cropping Pattern Changes in Kerala, 1956&#8211;57 to 2016&#8211;17"](https://ras.org.in/index.php?Article=cropping_pattern_changes_in_kerala_1956), published in the *Review of Agrarian Studies* journal. The datasets on land use and cropping pattern statistics are available for both at the State and district level for Kerala (1956&#8211;57 to 2016&#8211;17).

Preparing a comparable dataset on land-use and cropping pattern of Kerala was a challenging engagement. Although some researchers have analysed the long-term statistics in the past, various issues had remained unaddressed at the time of writing the above note. I used the method adopted by the [International Crops Research Institute for the Semi-Arid Tropics (ICRISAT)](https://vdsa.icrisat.org/vdsa-mesodoc.aspx) for their district-level database, to generate comparable dataset at the level of nine composite districts (according to the administrative boundaries of 1957&#8211;58). 

I undertook this exercise as part of my Ph.D research. The research note was an outcome of the exercise. The data for this project came from publicly available resources, published by the [Department of Economics and Statistics (DES), Government of Kerala](https://www.ecostat.kerala.gov.in/publication-list?category=3010&scheme=3038&jurisdiction=&from=&to=&search=&published_from=&published_to=&tab=publications&sort=newest), and a few secondary sources that compiled these statistics. While I did not update the data after 2016&#8211;17, it is not difficult to add this to the existing dataset since the information for latest years are freely available and can be accessed from the DES website. I believe the DES updated its website in the recent years and most of the older reports are available online for compiling a similar dataset from scratch. 

Finally, a note on the other dataset. The database from ICRISAT is currently hosted [here](http://data.icrisat.org/dld/src/about-dld.html). While it covers broadly the same time period, I have not directly checked my data with theirs for consistency. Since I relied on similar set of sources that the ICRISAT uses, there may not be much difference at the aggregate level between the two sources. 

## 2. Data Files
There are three datasets (in six files &#8212; a .xlsx and .ods file for each dataset) associated with this repository.
1. Land use - at State and district levels ([Excel](https://github.com/deepakjohnson91/kerala-land-use-cropping-pattern/blob/main/data_land_use_excel.xlsx)/[ODS](https://github.com/deepakjohnson91/kerala-land-use-cropping-pattern/blob/main/data_land_use.ods))
2. Cropping pattern - at State and district levels for four crops ([Excel](https://github.com/deepakjohnson91/kerala-land-use-cropping-pattern/blob/main/data_crop_area_excel.xlsx)/[ODS](https://github.com/deepakjohnson91/kerala-land-use-cropping-pattern/blob/main/data_crop_area.ods))
3. Crop area and production - at State level for 15 crops ([Excel](https://github.com/deepakjohnson91/kerala-land-use-cropping-pattern/blob/main/data_15_crops_kerala_excel.xlsx)/[ODS](https://github.com/deepakjohnson91/kerala-land-use-cropping-pattern/blob/main/data_15_crops_kerala.ods))

Each file has a "Documentation" sheet, which has detailed information on when the dataset was finalised, how the file is structured, sources of data, description of different variables, and on calculations undertaken for reducing errors and achieving comaparability over time. I initially worked on Excel (.xlsx) for this project. But I have also provided Open Document (.ods) version in this repository. 

## 3. Analysis
The graphs in the [research note](https://ras.org.in/index.php?Article=cropping_pattern_changes_in_kerala_1956) were prepared by taking moving averages of the datasets. Since I was not familiar with R back then, I had relied completely on Excel for producing the graphs. I used the above three datasets for preparing the graphs. 

A look at the methodological issues concerning the long-term statistics is important before any independent analysis is attempted. Some issues are raised under the section "Concerns Regarding the DES Data" from my research note. Those interested may also find a list of references at the end, to look at other studies that have used or talked about the data source. 

## 4. License

This work is licensed under the [GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0.html) license. This work is free: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
This work is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

In case you wish to use this data and want to cite, please find a suggested format below (that links up with the research note):  
Johnson, Deepak (2018), "Cropping Pattern Changes in Kerala, 1956–57 to 2016–17" [data files], *Review of Agrarian Studies*, vol. 8, no. 1.
