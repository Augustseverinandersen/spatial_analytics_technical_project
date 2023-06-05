# Spatial Analytics Technical Project
The is the technical project for the exam in Spatial Analytics. 

## Abstract
The urban coastal nation Australia is forecasted to have a population increase of six million during the next eight years. This increase in population could lead to new highs in the number of shark attacks. This repository, therefore, examines the occurrence, patterns, and factors surrounding shark attacks in Australia by using R and spatial transformation to create maps and other visualizations for analysis. Through the use of spatial visualization, it could be deduced that shark attacks in Australia are increasing, but that might be influenced by the accessibility of the internet and awareness. Moreover, it could be deduced that most shark attacks come from two species each controlling one-half of Australia. Lastly, the number of shark attacks is depended on location, season, and activity.

## Software Framework. 
For this technical project, I have used my 3-year-old HP Envy x360 computer, with 8 GP RAM, on a Windows 11 operating system. I worked on the desktop version of R (4.2.2) and RStudio 2022.12.0 3533.

## Contents 
- ***code*** this folder contains an R markdown file. The *rmd* is used to create visualizations and maps based on spatial data 
- ***data*** this folder contains two CSV files and two folders.
  - [au.csv](https://simplemaps.com/data/au-cities) contains location and population of 323 Australian cities. MIT License
  - [shark_attacks.csv](https://zenodo.org/record/7608411#.ZEZtSXZBxD8 ) contains 1201 reported shark attacks from 1791 until 2023. MIT license
  - [STE_2021_AUST_GDA2020](https://www.abs.gov.au/statistics/standards/australian-statistical-geography-standard-asgs-edition-3/jul2021-jun2026/access-and-downloads/digital-boundary-files#metadata-for-digital-boundary-files), located in the folder *australia_Map* contains a shape file for the states and territories of Australia. Creative Commons Attribution 4.0 International License.
  - [ne_50m_admin_0_countires](https://www.naturalearthdata.com/downloads/50m-cultural-vectors/50m-admin-0-countries-2/ ) contains a shape file for all countries in the world.  Public Domain.
- ***figs*** this folder contains ten visualizations, either made by using __GGPLOT2__ or __Tmap__.

## Libraries 
| Library         | Usage                                             |
|-----------------|---------------------------------------------------|
| Sf (v1.0.9)     | Spatial data, transformation, and operations      |
| Tidyverse (v1.3.2) | Data manipulation, data visualization (includes ggplot2) |
| Tmap (v3.3.3)   | Creation of thematic maps, visualizing spatial objects |
| Knitr (v1.42)   | Dynamic report generation                         |
| Rmdformats (v1.0.4) | Creates clean HTML output formats                |


## Usage 
To use the markdown in this repository follow these steps:
1. Clone the repository ```git clone <link>```
2. Install the libraries ``install.packages("library name")``
3. Run the code.

## License 
Creative Commons 4.0 Attribution 4.0 International
